# Entity Framework Core tools reference - .NET Core CLI
The command-line interface (CLI) tools for Entity Framework Core perform design-time development tasks.
## Installing the tools
```dotnet ef``` can be installed as either a global or local tool.
``` csharp
dotnet tool install --global dotnet-ef
```

Update the tool using the following command:
```csharp
dotnet tool update --global dotnet-ef
```

Before you can use the tools on a specific project, you'll need to add the ```Microsoft.EntityFrameworkCore.Design``` package to it.

```powershell
dotnet add package Microsoft.EntityFrameworkCore.Design
```



```Microsoft.EntityFrameworkCore.SqlServer``` is the official SQL Server provider for Entity Framework Core.

```Microsoft.EntityFrameworkCore.Tools``` provides tool commands for working with Entity Framework Core from the CLI or the NuGet package console in Visual Studio.

```Microsoft.EntityFrameworkCore.Design``` It is a design-time support package for Entity Framework Core. Its purpose is to allow tools like dotnet ef to work correctly by generating code to and from the database.


