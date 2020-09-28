# JobTo

[![N|ASP.NET Core 3.0](https://i.ibb.co/rM1ds8y/dot-net-core-angular.png)](https://docs.microsoft.com/en-us/aspnet/core)

![Build and deploy ASP.Net Core app to Azure Web App](https://github.com/osnipezzini/JobTo.Web/workflows/Build%20and%20deploy%20ASP.Net%20Core%20app%20to%20Azure%20Web%20App%20-%20jobtoapi/badge.svg)

JobTo is software that comes with the idea of helping support companies to control the attendance of tickets and products sold.

- Registration of products, services, customers, companies and more.
- Opening of tickets can be done by both the customer and the technician, with fully customizable permissions by company, group of companies, groups of customers and much more.

## Tech

JobTo uses a number of open source projects to work properly:

- Template pages with [Angular8](https://angular.io) and [TypeScript](https://www.typescriptlang.org)
- RESTful API Backend using [ASP.NET Core 3.0](https://docs.microsoft.com/en-us/aspnet/core) MVC Web API
- Database using [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core)
- Authentication based on  [IdentityServer4](http://docs.identityserver.io/en/release) and [ASP.NET Core Identity](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/identity-configuration?tabs=aspnetcore2x)
- API Documentation using [Swagger](https://swagger.io)
- Client-side built on [Angular CLI](https://cli.angular.io)
- Theming using  [Bootstrap 4](https://getbootstrap.com) with [Bootswatch](https://bootswatch.com)

### Installation

JobTo requires [Node.js](https://nodejs.org/) v4+ to run and .NET Core 3.0.

Install the dependencies and devDependencies and start the server.

```sh
$cd jobto.web
$dotnet restore obTo.Web.csproj
$npm install -d ClientApp\
$dotnet run
```

License

----

MIT
