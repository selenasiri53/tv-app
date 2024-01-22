----TVStationsApp

$ dotnet --version
8.0.101

$ dotnet new blazor -o TVStationsApp && cd TVStationsApp
$ code .

--- one time setup for git and .gitignore file:
$ git init
$ dotnet new gitignore
Note: This command will create a perfect .gitignore in your folder with a lot of settings to ignore unnecessary files
---- 

create file StationDetails.razor in Components\Pages
$ dotnet new razorcomponent -n Stations -o Components/Pages

create file StationDetails.razor in Components/Pages
$ dotnet new razorcomponent -n StationDetails -o Components/Pages

$ dotnet watch run  ----- eq  $ npm start 

Leave the app running the command shell. Each time a file is saved, the app is automatically rebuilt, and the page in the browser is automatically reloaded.