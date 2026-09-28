# Blazor TreeView Authentication and Authorization

## Overview

This sample demonstrates how to integrate the Syncfusion [Blazor TreeView](https://www.syncfusion.com/blazor-components/blazor-treeview) component with ASP.NET uthentication and authorization in a Blazor Server application. The project combines hierarchical TreeView navigation with secured application access, allowing developers to understand how TreeView content can be used within authenticated user experiences. It also provides a reference implementation for configuring Identity services, user management, and protected application resources alongside Syncfusion UI components.

## Key Features

- Uses the Syncfusion TreeView component to display hierarchical navigation data.
- Integrates ASP.NET Core Identity for user authentication.
- Includes Identity UI scaffolding under the `Areas/Identity` folder.
- Configures authentication services through `Program.cs`.
- Demonstrates secured access patterns within a Blazor Server application.
- Uses application configuration from `appsettings.json` and `appsettings.Development.json`.
- Includes shared layouts and application routing through `App.razor` and files in the `Shared` folder.
- Demonstrates TreeView navigation within an authenticated application workflow.
- Uses the project file `Authentication.csproj` and solution file `Authentication.sln` for application configuration and execution.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `Authentication.sln`

3. Restore all NuGet packages.
4. Set the startup project to:

   `Authentication`

5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Register or sign in using the configured Identity authentication system and verify TreeView navigation functionality.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root.

```bash
cd Blazor-TreeView-Authentication-Authorization
```

4. Restore NuGet packages.

```bash
dotnet restore
```

5. Run the application.

```bash
dotnet run
```

6. Open the local URL displayed in the terminal and verify authentication and TreeView functionality.

## Project Structure

`Pages/Index.razor` — landing page for the application. [VERIFY: TreeView implementation details]

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official documentation: https://blazor.syncfusion.com/documentation/treeview/getting-started

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components