---
languages:
- csharp
- aspx-csharp
page_type: sample
description: "A sample application you can use to follow along with Tutorial: Deploy an ASP.NET Core and Azure SQL Database app to Azure App Service."
products:
- azure
- aspnet-core
- azure-app-service
---

# .NET Core MVC sample for Azure App Service

This is a sample application that you can use to follow along with the activity at 
Activity: Deploy an ASP.NET Core and Azure SQL Database app to Azure App Service 

## Getting started

### Run from Visual Studio

1. git clone https://github.com/CSA-DanielVillamizar/app-service-sqldb-dotnetcore.git
2. cd app-service-sqldb-dotnetcore
3. Open *DotNetCoreSqlDb.sln* in Visual Studio.
4. Start debugging.

### Run from command line

Run the following commands in a terminal:

```
git git clone https://github.com/CSA-DanielVillamizar/app-service-sqldb-dotnetcore.git
cd app-service-sqldb-dotnetcore
dotnet ef database update
dotnet run
```
