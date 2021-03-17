# WorkerService.Testing

Adoption of [Microsoft.AspNetCore.Mvc.Testing](https://docs.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-3.1) for Worker service. It's compatible with .Net Core 3.1.

```forked from gao-artur/WorkerService.Testing```

## Installation

Download via NuGet: https://www.nuget.org/packages/WorkerService.Testing

## Usage
The usage almost similar to [Microsoft.AspNetCore.Mvc.Testing](https://docs.microsoft.com/en-us/aspnet/core/test/integration-tests?view=aspnetcore-3.1). The main difference is that you should call `StartAsync()` method to start the host. Check `WorkerService.Testing.IntegrationTests` project for usage example.
