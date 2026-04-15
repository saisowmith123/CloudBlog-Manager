# CloudBlog-Manager

CloudBlog-Manager is an ASP.NET Core MVC web application that manages blog-related content using Azure Blob Storage. It allows users to create and manage containers, upload and view files, and organize stored content through a simple web interface.

## Features
- Create and delete Azure Blob Storage containers
- Upload, view, and delete files in containers
- Display containers and associated blobs
- View stored images from a specific container
- Service based architecture for blob and container operations

## Tech Stack
- ASP.NET Core MVC
- C#
- Azure Blob Storage
- Razor Views

## Project Structure
- `Controllers/` - Handles container, blob, and home routes
- `Models/` - Contains data models like `Blob`, `Container`, and error models
- `Services/` - Implements blob and container service logic
- `Views/` - Razor UI pages
- `wwwroot/` - Static assets
- `appsettings.json` - Stores configuration such as Azure Blob connection string

## Getting Started
1. Clone the repository
2. Open the project in Visual Studio
3. Add your Azure Blob Storage connection string in `appsettings.json` under `BlobConnection`
4. Build and run the application

## Purpose
This project was built to demonstrate how to integrate Azure Blob Storage into a .NET Core MVC application for managing files and containers in a blog-style platform.
