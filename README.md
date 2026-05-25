# Blazor Scheduler Clipboard

A demonstration of copy-and-paste functionality between a Blazor Grid and Scheduler component, built with UI components in a .NET 8 Blazor Web App.

## Overview

This project demonstrates how to copy data from a Blazor Grid and paste it into a Blazor Scheduler. The sample transforms grid data (such as order information) into appointment data when pasted, enabling seamless data migration between components.

The application uses:

- **Blazor Scheduler** - displays appointments in day, week, work week, month, and agenda views
- **Blazor Grid** - displays order data with customer and shipping information
- **.NET 8 Blazor Web App** - with Interactive Auto render mode (WebAssembly + Server)

## Features

- **Clipboard Integration** - Built-in clipboard support via `AllowClipboard="true"`
- **Custom Paste Handling** - `PasteEventArgs` allows transforming data before insertion
- **Multiple View Modes** - Day, Week, Work Week, Month, and Agenda views
- **Auto Render Mode** - Combines server-side rendering with client-side interactivity

## Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/Copy-and-Paste-Grid-data-to-Blazor-Scheduler.git
cd Copy-and-Paste-Grid-data-to-Blazor-Scheduler
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

## References

- [Blazor DataGrid Documentation](https://www.syncfusion.com/blazor-components/blazor-datagrid)
- [ASP.NET Core Documentation](https://learn.microsoft.com/en-us/aspnet/core)
- [Blazor Documentation](https://learn.microsoft.com/en-us/aspnet/core/blazor)
- [Syncfusion Blazor Scheduler - Clipboard](https://blazor.syncfusion.com/documentation/scheduler/clipboard)
- [.NET 8 Blazor Web App](https://learn.microsoft.com/aspnet/core/blazor/?view=aspnetcore-8.0)