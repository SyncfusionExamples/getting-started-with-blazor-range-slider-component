# Getting Started with the Blazor Range Slider Component

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Range Slider](https://www.syncfusion.com/blazor-components/blazor-range-slider) component in a  The implementation showcases a range-based slider with configurable limits, always visible tooltips, tick customization, built-in increment and decrement buttons, and custom CSS styling for slider handles. It serves as a practical reference for implementing controlled range selection scenarios while providing a customizable user experience.

## Key Features

- Uses the `SfSlider` component from the `Syncfusion.Blazor.Inputs` package.
- Configures the slider as a range selector using `Type="SliderType.Range"`.
- Binds range values through the `Value` property using an integer array.
- Enables increment and decrement controls with `ShowButtons="true"`.
- Initializes the selected range with `RangeValue`.
- Demonstrates CSS customization of slider handles using the selector.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the `GettingStarted.sln` solution file.
3. Restore all NuGet packages.
4. Build the solution.
5. Press `Ctrl+F5` to run the application.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the `Server` project directory:

```bash
cd Server 
```

4. Restore project dependencies:

```bash
dotnet restore
```

5. Run the application:

```bash
dotnet run
```

6. Open the local URL displayed in the terminal after the application starts.

## Project Structure

- `GettingStarted.sln` — Visual Studio solution file containing the sample projects.

- `Client/` — Contains the Blazor WebAssembly client application.

- `Client/Pages/Index.razor` — Demonstrates the Range Slider component with buttons, tooltips, ticks, limits, and custom styling.
  
- `Server/` — Hosts and serves the Blazor WebAssembly application.

- `Shared/` — Contains shared models and resources used by both the Client and Server projects.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/range-slider/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
