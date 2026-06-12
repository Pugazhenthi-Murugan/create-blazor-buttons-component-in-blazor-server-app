# Blazor Button Component - Getting Started

A Blazor Server sample that demonstrates how to use the [Blazor Button component](https://www.syncfusion.com/blazor-components/blazor-button) in a .NET 10 app.

## Overview

This sample shows how to build a simple button experience with Blazor Buttons in a server-side Blazor application. It focuses on the most common button scenarios so you can quickly understand how the component behaves in a real app.

The sample uses `SfButton` to demonstrate:

- text and icon content
- icon placement on the left or right
- predefined styling with CSS classes
- button state changes through a click handler
- disabled button behavior
- custom icon font usage for button icons

## Features

- Button text changes on click
- Icon support with custom icon CSS
- Icon placement on the right
- Disabled state and event handling

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/create-blazor-buttons-component-in-blazor-server-app.git
cd create-blazor-buttons-component-in-blazor-server-app
```

### Run with Visual Studio

1. Open [buttons.slnx](buttons.slnx) in Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to verify the setup.
4. Run the `buttons` project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run --project buttons
```

## Related resources

**Documentation**: https://blazor.syncfusion.com/documentation/button/getting-started

**Demos**: https://blazor.syncfusion.com/demos/buttons/default-functionalities?theme=fluent2
