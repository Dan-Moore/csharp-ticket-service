Creating csharp project with dependeicies.
    - Microsoft.EntityFrameworkCore.Design
    - Npgsql.EntityFrameworkCore.PostgreSQL
    
```bash
dotnet new webapi -n ticket-service-csharp-api
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Npgsql.EntityFrameworkCore.PostgreSQL --version 8.0.4
```