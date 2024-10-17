## CREATING A CLEAN ARCHITECTURE PROJECT

The porpouse of this code is understand the Clean Architecture.

### THE PROJECT

I will make a API where you can find informations about movies

### CLEAN ARCHITECTURE: FIRST STEPS

To start, I create the soluction, all the classlibs and the API.
```
dotnet new sln -o MovieTime
```
```
dotnet new webapi -o MovieTime.Api
```
```
dotnet new classlib -o MovieTime.Contracts
```
```
dotnet new classlib -o MovieTime.Infrastructure
```
```
dotnet new classlib -o MovieTime.Application
```
```
dotnet new classlib -o MovieTime.Domain
```

After that, added it into the solution
```
dotnet sln add (ls -r **\*.csproj)
```
