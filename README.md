# blazorwasm
this project demonstrates about .net core blazor client side wasm apps

# App strucutre
Install .net core 3.0 sdk preview from official web site

after that run `dotnet new blazorwasm` for creating a new dot net core web wasm app.

after cloning app run `dotnet restore` to restore the packages in the app

to build the app run `dotnet build` 

to start the app run `dotnet run`

to publish the app run `dotnet publish` will produce o/p in `bin\Debug\netstandard2.0\publish\` copy the publish files and paste in the server you want.

for supporting `wasm` format on server to server your app we need to add a MIME type in server with 
`.wasm` and `application/wasm` as the mime for it.


