# Blazor DataGrid - Hide Default Grid Spinner and Show Customized Spinner

## Overview

This sample demonstrates how to hide the default loading spinner displayed by the Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) and replace it with a customized loading indicator. The implementation focuses on controlling the loading experience during DataGrid operations by displaying a custom spinner instead of the built-in loading animation. This approach is useful when applications require branded loading indicators, customized animations, or a consistent user experience across multiple components. The sample provides a practical implementation for managing loading states while preserving the built-in functionality of the Syncfusion Blazor DataGrid.

## Key Features

- Demonstrates how to hide the default loading spinner rendered by the Syncfusion Blazor DataGrid.
- Shows how to display a custom spinner during DataGrid loading operations.
- Uses custom CSS and UI elements to provide a tailored loading experience.
- Demonstrates loading-state customization without changing DataGrid functionality.
- Provides a branded alternative to the default Syncfusion loading indicator.
- Illustrates how custom loading animations can be integrated into DataGrid workflows.
- Maintains a seamless user experience during data processing operations.
- Shows how developers can personalize DataGrid behavior through UI customization techniques.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the solution file `HideGridSpinner.sln`.
3. Restore all NuGet packages.
4. Set the `HideGridSpinner` project as the startup project if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

4. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `Pages/` — contains the Razor page that hosts the Syncfusion Blazor DataGrid and custom spinner implementation.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/overview

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
