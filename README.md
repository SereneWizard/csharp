# csharp
Practicing C Sharp

* Create new solution: `dotnet new sln`
* Create new project in new directory called *MyConsoleApp*: `dotnet new console -o MyConsoleApp`
* Add the project to the solution: `dotnet sln add MyConsoleApp/MyConsoleApp.csproj`
* Add a new class library: `dotnet new classlib -o MyClassLib`
* Add the new classlib to the solution: `dotnet sln add MyClassLib/MyClassLib`
* Add reference to the classlib in the project (command in the project director): `dotnet add reference ../MyClassLib/MyClassLib.csproj`