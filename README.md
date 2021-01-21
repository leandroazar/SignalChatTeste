# SignalChatTeste
Exemplo simples de chat com SignalR.

Fonte de exemplo:
https://docs.microsoft.com/pt-br/aspnet/core/tutorials/signalr?view=aspnetcore-5.0&tabs=visual-studio-code


Requisitos
Instalar o Libman (só uma vez na maquina)
>dotnet tool install -g Microsoft.Web.LibraryManager.Cli

Adicoinar os arquivos do signal no projeto >
>libman install @microsoft/signalr@latest -p unpkg -d wwwroot/js/signalr --files dist/browser/signalr.js --files dist/browser/signalr.min.js
------------------------------------------------------------


Inicialiar / Executar / Rodar a aplicação:
>dotnet watch run -p SignalRChat.csproj
