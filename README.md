# Getting Started with the Blazor Skeleton Component

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Skeleton](https://www.syncfusion.com/blazor-components/blazor-skeleton) component in a Blazor WebAssembly applicationys loading placeholders while content is being fetched and replaces them with actual UI elements after a simulated asynchronous operation completes. The sample uses conditional rendering, lifecycle methods, and custom Skeleton styling to create a realistic loading experience for end users.

## Key Features

- Uses the `SfSkeleton` component to display loading placeholders before content becomes available.
- Configures avatar placeholders using `Shape="SkeletonType.Circle"`.
- Demonstrates conditional rendering with the `IsDataLoaded` flag.
- Uses the `OnAfterRender(bool firstRender)` lifecycle method to initiate content loading after the first render.
- Simulates asynchronous data retrieval using `Task.Delay(3000)`.
- Refreshes the UI by calling `StateHasChanged()` after the loading operation completes.
- Displays profile content and images after the loading state finishes.
- Demonstrates custom Skeleton styling through the `.e-customize.e-skeleton` CSS class.
- Customizes the shimmer animation effect using `.e-skeleton.e-shimmer-wave::after`.
- Shows how Skeleton placeholders can be integrated into a card-based layout.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone this repository.
2. Open the repository folder in Visual Studio 2022.
3. Restore NuGet packages.
4. Set the Blazor WebAssembly project as the startup project if required.
5. Build the project.
6. Run the application using **Ctrl+F5**.

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

`Pages/Index.razor` — Main sample page demonstrating the Syncfusion Skeleton component, conditional rendering, delayed data loading, and custom Skeleton styling.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/skeleton/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.