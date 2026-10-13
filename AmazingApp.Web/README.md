# AmazingApp.Web

AmazingApp.Web is an ASP.NET Core MVC application for the AZ-400 learning project.

## Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)

## Build and run

Run these commands from the repository root:

```sh
dotnet restore
dotnet build --no-restore
dotnet test --no-build
dotnet run --project AmazingApp.Web
```

The launch settings provide these local URLs:

- HTTP: <http://localhost:5174>
- HTTPS: <https://localhost:7243>
