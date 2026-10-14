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
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

4. Open the URL displayed in the terminal after the application starts.

## Project Structure

- `GettingStarted.sln` — Visual Studio solution file containing the sample projects.

- `Client/Pages/Index.razor` — Demonstrates the Range Slider component with buttons, tooltips, ticks, limits, and custom styling.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/range-slider/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.