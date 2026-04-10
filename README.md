# dotnet-blazor

A Blazor Server web application built with .NET 9.

## Overview

This project demonstrates a Blazor Server application with interactive server-side rendering. It uses Razor components and supports interactive UI via SignalR.

## Requirements

- [.NET 9 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)

## Getting Started

```bash
dotnet run
```

The server will start and listen on the default port. Visit `http://localhost:8080` to view the Blazor application.

## Project Structure

```
Components/
├── App.razor         # Root application component
├── Routes.razor      # Router configuration
├── _Imports.razor    # Global using directives
└── Pages/            # Page components
```
