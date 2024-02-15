![1704357824455](https://github.com/ViniMortinho/Blazin-2024/assets/110264434/c2153def-39bf-4ea0-9d7e-e2ec67a59e01)


# Blazin' 2024 With Blazor
![Microsoft](https://img.shields.io/badge/Microsoft-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)![Blazor](https://img.shields.io/badge/blazor-%235C2D91.svg?style=for-the-badge&logo=blazor&logoColor=white)![.Net](https://img.shields.io/badge/.NET-5C2D91?style=for-the-badge&logo=.net&logoColor=white)![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
###
_Blazin' with 2024 Blazor é uma conferência online dedicada a desenvolvedores que desejam aprender e se aprofundar no framework Blazor da Microsoft. A conferência acontecerá em 2024 e será focada em Blazor WebAssembly_

## Descrição
O Blazor é uma estrutura Web de front-end moderna baseada em HTML, CSS e C# que ajuda você a criar aplicativos Web mais rapidamente. Com o Blazor, você cria aplicativos Web usando componentes reutilizáveis que podem ser executados do cliente e do servidor para que você possa oferecer ótimas experiências na Web. O Blazor faz parte do .NET, uma plataforma de desenvolvedores para criar qualquer coisa. O .NET é gratuito, de código aberto e é executado entre plataformas.
Alguns dos benefícios do uso do Blazor incluem:

>- __Criação rápida da interface do usuário da Web com componentes reutilizáveis:__ O modelo de componente flexível do Blazor facilita a criação de componentes reutilizáveis que você pode usar para montar aplicativos rapidamente.
>- __A possibilidade de adicionar interatividade avançada em C#:__ Lide com eventos arbitrários de interface do usuário do navegador e implemente a lógica do componente em C#, uma linguagem moderna e fortemente tipada que é fácil de aprender e altamente versátil.
>- __Uma pilha de desenvolvimento:__ Crie todo o aplicativo Web do front-end ao back-end usando uma única pilha de desenvolvimento e código de compartilhamento para lógica comum no cliente e no servidor.
>- __Renderização baseada em diferenciação eficiente:__ À medida que os componentes são renderizados, o Blazor controla cuidadosamente quais partes do DOM foram alteradas, para que as atualizações da interface do usuário sejam rápidas e eficientes.
>- __Renderização no servidor e no lado do cliente:__ Renderize componentes do servidor e do cliente para implementar várias arquiteturas de aplicativo Web e fornecer a melhor experiência possível de aplicativo Web.-
>- __Renderização de servidor progressivamente aprimorada:__ Use o suporte interno para manipulação avançada de formulários e processamento de streaming para aprimorar progressivamente a experiência do usuário de aplicativos Web renderizados pelo servidor.
>- __Interoperabilidade com JavaScript:__ Use o ecossistema de bibliotecas JavaScript e APIs do navegador do código C#.
>- __Integração com aplicativos existentes:__ Integre componentes Blazor com aplicativos baseados em MVC, Razor Pages ou JavaScript existentes.
>- __Ótimas ferramentas:__ Use o Visual Studio ou o Visual Studio Code para começar em segundos e manter-se produtivo com ótimo suporte à edição de código.
>- __Criação de aplicativos para Web, dispositivos móveis e desktop:__ Os componentes do Blazor também podem ser usados para criar aplicativos nativos para dispositivos móveis e desktop usando um híbrido de nativo e web, chamado Blazor Hybrid.

## __Ambientação__
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

Este módulo usa o SDK do .NET 8.0. Verifique se você tem o .NET 8.0 instalado executando o seguinte comando em seu terminal de comando preferencial:
 
 (dotnet --list-sdks)
 
 Uma saída semelhante ao seguinte exemplo aparece:
```
 (6.0.317 [C:\Program Files\dotnet\sdk]
 7.0.401 [C:\Program Files\dotnet\sdk]
 8.0.100 [C:\Program Files\dotnet\sdk])
```
Verifique se uma versão que começa com 8 está listada. Se nenhum estiver listado ou o comando não for encontrado, instal
e o SDK do .NET 8.0 mais recente: __https://dotnet.microsoft.com/pt-br/download__


##Criar um novo aplicativo Web do Blazor com o Kit de Desenvolvimento em C#
Para criar um novo projeto de aplicativo Web do Blazor no Visual Studio Code com o Kit de Desenvolvimento em C#:

1 - Abra a paleta de comandos usando Ctrl+Shift+P e digite ".NET".

2 - Localize e selecione o .NET: Comando Novo projeto.

3 - Selecione Aplicativo Web Blazor na lista suspensa.

4 - Selecione a pasta na qual você deseja criar o novo projeto.

5 - Nomeie o projeto BlazorApp e pressione Enter para confirmar.

6 - Exiba seu novo projeto de aplicativo Blazor no Gerenciador de Soluções.

## Opcional: Criar um novo aplicativo Blazor com o C# Dev Kit
Para criar um projeto de aplicativo Web do Blazor usando o SDK do .NET na linha de comando, use o seguinte comando:

CLI do .NET
```
dotnet new blazor
```
Se você criou o aplicativo Blazor com o Visual Studio Code ou a CLI do .NET, o projeto gerado contém os seguintes arquivos e páginas:

Program.cs é o ponto de entrada do aplicativo que inicia o servidor e onde você configura os serviços de aplicativo e o middleware.
App.razor é o componente raiz do aplicativo.
Routes.razor configura o roteador do Blazor.
O diretório Componentes/Páginas contém algumas páginas da Web de exemplo para o aplicativo.
BlazorApp.csproj define o projeto de aplicativo e suas dependências e pode ser exibido clicando duas vezes no nó do projeto no Gerenciador de Soluções.
O arquivo launchSettings.json dentro do diretório Propriedades define diferentes configurações de perfil para o ambiente de desenvolvimento local. Um número de porta é atribuído automaticamente na criação do projeto e salvo neste arquivo.
Executar o aplicativo com o depurador integrado
No Visual Studio Code, selecione Executar no menu.

Selecione Iniciar Depuração.

Selecione C# na lista suspensa Selecionar depurador.

Selecione C#: BlazorApp [Configuração Padrão]

Isso cria e inicia o aplicativo com a depuração habilitada. O aplicativo deve ser aberto automaticamente no navegador padrão. Seu navegador pode avisar que o site não é seguro. É seguro continuar.

Screenshot showing the default Blazor app running in a browser.

Opcional: Executar o aplicativo com a CLI do .NET
Na janela do terminal, copie e cole o seguinte comando para executar o aplicativo e observe as alterações de arquivo:

CLI do .NET

Copiar
dotnet watch
Esse comando cria e inicia o aplicativo e aplica todas as alterações de código ao aplicativo em execução. O aplicativo deve ser aberto automaticamente no navegador padrão. Seu navegador pode avisá-lo de que o site ainda não tem um certificado válido; É seguro continuar.
[https://learn.microsoft.com/pt-br/training/aspnetcore/blazor-introduction/media/interactive-server.png]
