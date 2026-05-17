# bimlens-api

Backend for **bimlens**.

Receives parsed IFC model data from `bimlens-web` and stores it. Exposes a REST API with controller / service / repository layering (SOLID).

## Stack

- ASP.NET Core .NET 10
- C#
- OpenAPI (built-in)


## Development

```bash
cd Bimlens
dotnet run --project Api/Api.csproj
```

Runs at `http://localhost:5292`. Use `Api/Api.http` to test endpoints.
