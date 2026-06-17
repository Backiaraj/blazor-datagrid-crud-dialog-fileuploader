# Blazor DataGrid — CRUD Dialog FileUploader

A sample Blazor application demonstrating how to integrate the [Blazor File Upload](https://www.syncfusion.com/blazor-components/blazor-file-upload) component within CRUD dialogs of the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component for seamless file upload operations during edit and add operations in a Blazor server-side application.

## Overview

This repository demonstrates a practical real-world scenario where users can manage employee data with file uploads. When creating or editing employee records in a DataGrid, a dialog appears with form fields and an integrated file uploader component. This pattern is commonly used for applications that require both data input and file attachment capabilities.

## Features

- **Full CRUD Operations** — Create, read, update, and delete employee records with an intuitive toolbar interface
- **Dialog-Based Editing** — Modal forms for adding and editing records with inline form controls and validation support
- **File Upload Integration** — Seamlessly upload images during add/edit operations with the SfUploader component
- **Real-Time Image Preview** — Preview employee photos in dialogs as files are selected
- **File Validation** — Automatic validation for supported image formats (.jpg, .png, .jpeg)
- **Server-Side File Storage** — Secure handling and persistent storage of employee images on the server
- **Image Gallery Display** — Circular thumbnail images displayed in grid columns with professional styling
- **Blazor Server Architecture** — Real-time interactivity with server-side rendering and component state management
- **Custom Event Handling** — Extensible event handlers for row editing, adding, and updating operations

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-crud-dialog-fileuploader.git
cd blazor-datagrid-crud-dialog-fileuploader
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**:

* https://www.syncfusion.com/blazor-components/blazor-datagrid
* https://www.syncfusion.com/blazor-components/blazor-file-upload
* https://www.syncfusion.com/blazor-components/blazor-datagrid/editing

**Live example**:

* https://blazor.syncfusion.com/demos/datagrid/dialog-editing?theme=bootstrap5
