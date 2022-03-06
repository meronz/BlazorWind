# BlazorWind

Blazor Webassembly application fully integrated with TailwindCSS 3.0.

### Build
The `Styles/app.pcss` file is automatically built by dotnet when dotnet build is run.
```shell
dotnet build
```

### Hot reload
To build with hot-reload, you need to run two separate watch commands: one for tailwind, and the other for dotnet:
```shell
npm run watch
dotnet watch
```