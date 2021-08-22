Título do projeto
Minimum Boilerplate Theme - Projeto teste

🚀 Começando
O tema padrão mínimo é o modelo básico de fachada de loja baseado no VTEX IO Store Framework.

Deve ser usado apenas quando você deseja iniciar um novo tema de loja sem nenhuma configuração predefinida, como é o caso com Tema de Loja .

Enquanto Store Theme oferece aos desenvolvedores uma estrutura de fachada de loja padrão pronta para uso, o Minimum Boilerplate Theme permitirá que você crie sua loja livremente a partir do zero.

Configuração

Etapa 1 - configuração básica
Acesse o guia de configuração básica do VTEX IO e siga todas as etapas fornecidas.

Ao final da configuração, você deve ter a interface de linha de comando VTEX (Toolbelt) instalada junto com um espaço de trabalho do desenvolvedor no qual você pode trabalhar.

Etapa 2 - Clonando o repositório de Tema de Boilerplate Mínimo
Clone este repositório em seus arquivos locais para poder começar a trabalhar com eficácia nele.

Em seguida, acesse o diretório do repositório usando seu terminal.

Etapa 3 - Editando o Manifest.json
Uma vez no diretório do repositório, é hora de editar o manifest.jsonarquivo Minimum Boilerplate .

Assim que estiver no arquivo, você deve substituir os valores vendore account. vendoré o nome da conta na qual você está trabalhando e accounté qualquer coisa que você queira nomear para o seu tema. Por exemplo:

{
  "vendor": "storecomponents",
  "name": "my-test-theme",
}

Etapa 4 - Instalando os aplicativos necessários
Para utilizar loja Framework e trabalhar em seu tema loja, é necessário ter os dois vtex.store-sitemape vtex.storeinstalado.

Execute vtex list e verifique se esses aplicativos já estão instalados.

Se não forem, execute o seguinte comando para instalá-los: vtex install vtex.store-sitemap vtex.store -f

Etapa 5 - Desinstalar qualquer tema existente
Ao executar vtex list, você pode verificar se algum tema está instalado.

É comum já ter um vtex.store-theme instalado quando você inicia o processo de desenvolvimento da fachada da loja.

Portanto, se você encontrá-lo na lista do aplicativo, copie seu nome e use-o junto com o comando vtex uninstall. Por exemplo:

vtex uninstall vtex.store-theme

Etapa 6 - Executar e visualizar sua loja
Então chegou a hora de fazer upload de todas as alterações feitas em seus arquivos locais para a plataforma. Para isso, use o vtex linkcomando.

Se o processo é executado sem erros, a seguinte mensagem será exibida: App linked successfully. Em seguida, execute o vtex browsecomando para abrir uma janela do navegador com sua loja vinculada.

Isso permitirá que você veja as alterações aplicadas em tempo real, por meio da conta e do espaço de trabalho em que está trabalhando.

🛠️ Construído com
Nesse projeto foi usado o editor VisualCode

📌 Versão
Foi usada a versão 0.1.1 para fins de estudos

✒️ Autores
Vinícius Soares - Trabalho Inicial

📄 Licença
Este projeto está sob a licença (0.1.1).

🎁 Expressões de gratidão
Esse projeto apesar de básico para desenvolvedores experientes, tive bastante dificuldade e não pude concluir no prazo estipulado, mas fica aqui o grande aprendizado para pode me dedicar cada vez mais e sempre melhorar como pessoa e profissional. Simplesmente fiquei muito feliz em poder participar o treinamento proposto pela Gama Academy e Vtex 📢
Agradeço a Gama Academy e Vtex por serem empresas acima de tudo humana, isso mostra o quanto outras empresas devem se espelhar em vocês.
Fica aqui o meu muito Obrigado publicamente! 🤓.