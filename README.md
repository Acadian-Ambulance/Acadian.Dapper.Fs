# Acadian.Dapper.Fs

Adds extensions for Dapper

## Top level functions
- safeSqlConnection - wraps a sql connection with handlers that allow you to use the option type in your F# models. Null from the db is converted to None and values are converted to Some value

## Module Extensions

This library extends several core modules:

- `Task` has additions such as map and bind

## Dependencies
- dotnet v5.0.103

## Development Dependencies
- just (command runner) v0.9.9
- fantomas v4.4.0 - code formatting tool (dotnet tool install -g fantomas-tool)
- dotnet fsharplint - code linter (dotnet tool install -g dotnet-fsharplint)

# Development Tools
- VS Code
- VS Code Extension ionide.ionide-fsharp

# Building/Running/Testing
- Uses dotnet cli
Ex: To run tests
> dotnet test

