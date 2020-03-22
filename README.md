# dotnet_core_microservice_template
A .net core microservice template with ddd

Download either microservice.zip or SenorDeveloper.MicroServiceTemplate.CSharp.1.0.0

    $ dotnet new --list

    $ dotnet new -i ./microservice

    $ dotnet new micro -n FooBar
    The template "Microservice domain driven design template using mediatr" was created successfully.

    $ cd FooBar/ && ls
    FooBar.API/  FooBar.Domain/  FooBar.Infrastructure/  FooBar.UnitTest/

    $ dotnet new sln
    The template "Solution File" was created successfully.

    $ ls
    FooBar.API/  FooBar.Domain/  FooBar.Infrastructure/  FooBar.sln  FooBar.UnitTest/

    $ for d in *; do dotnet sln add  $d; done
  Project `FooBar.API\FooBar.API.csproj` added to the solution.
  Project `FooBar.Domain\FooBar.Domain.csproj` added to the solution.
  Project `FooBar.Infrastructure\FooBar.Infrastructure.csproj` added to the solution.
  Project `FooBar.UnitTest\FooBar.UnitTests.csproj` added to the solution.

Open solution in your favorite C# IDE, note that the template has run dotnet restore and all project references are intact. **sweet isn't it?

For more information on templating
https://docs.microsoft.com/en-us/dotnet/core/tools/custom-templates
https://github.com/dotnet/dotnet-template-samples

The code used for the domain is from the following article
https://docs.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/ddd-oriented-microservice

