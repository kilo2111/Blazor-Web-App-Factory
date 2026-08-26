# newFactory - Blazor Web App (.NET 8+)

A modern web application built with **Blazor Web App** and **.NET 8**.

## Project Structure

```
├── Components/           # Reusable Blazor components
├── Pages/               # Routed pages
│   ├── Home.razor       # Home page
│   ├── Counter.razor    # Counter demo
│   └── Weather.razor    # Weather data demo
├── Layouts/             # Layout components
│   └── MainLayout.razor # Main page layout
├── wwwroot/             # Static files (CSS, JS, etc.)
├── Program.cs           # Application configuration
├── App.razor            # Root component
├── Routes.razor         # Routing configuration
├── appsettings.json     # Application settings
└── newFactory.csproj    # Project file
```

## Features

- ✅ Blazor Web App (.NET 8+)
- ✅ Component-based architecture
- ✅ Responsive design with Bootstrap
- ✅ Built-in routing and navigation
- ✅ Interactive WebAssembly components

## Getting Started

### Prerequisites

- **.NET 8 SDK** or later
- Visual Studio 2022 or VS Code

### Installation

1. Clone the repository:
```bash
git clone https://github.com/kilo2111/Blazor-Web-App-Factory.git
cd Blazor-Web-App-Factory
```

2. Restore NuGet packages:
```bash
dotnet restore
```

3. Run the application:
```bash
dotnet run
```

4. Open your browser and navigate to `https://localhost:7000`

## Building

```bash
dotnet build
```

## Publishing

```bash
dotnet publish -c Release
```

## Technologies

- **Blazor Web App** - Interactive web framework
- **.NET 8** - Latest .NET runtime
- **C#** - Programming language
- **Bootstrap 5** - CSS framework
- **WebAssembly** - Client-side execution

## Documentation

- [Blazor Documentation](https://learn.microsoft.com/aspnet/core/blazor)
- [.NET 8 Documentation](https://learn.microsoft.com/dotnet/core/whats-new/dotnet-8)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Created:** August 26, 2026  
**Owner:** kilo2111
