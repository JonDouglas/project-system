### Roadmap

The first release of the project system ("15.0") was heavily focused on supporting .NET Core scenarios and parity with [VS 2015 project.json tooling](https://github.com/dotnet/roslyn-project-system/issues?utf8=%E2%9C%93&q=label%3AParity-XProj%20). This will continue through the Visual Studio 15.x.x updates and releases. In 16.0, we'll start focusing on [feature parity](https://github.com/dotnet/roslyn-project-system/labels/Parity-VSLangProj) with the legacy project systems in csproj.dll and msvbprj.dll, where the aim will be to allow a seamless open of existing projects with zero conversions or upgrades.

|Release|Branches|Description|
|-------|--------|--------|
|[15.0.x](https://github.com/dotnet/roslyn-project-system/milestone/4)|[15.0.x](https://github.com/dotnet/roslyn-project-system/tree/dev15.0.x)|Impactful bugs, crashes and hangs that block _major_ scenarios.
|[15.3.x](https://github.com/dotnet/roslyn-project-system/milestone/7)|[15.3.x](https://github.com/dotnet/project-system/tree/dev15.3.x)|Impactful bugs, crashes and hangs that block _major_ scenarios.
|[15.4](https://github.com/dotnet/project-system/milestone/17)|[15.4.x](https://github.com/dotnet/project-system/tree/dev15.4.x)|Impactful bugs, crashes and hangs that block _minor_ scenarios.
|[15.5](https://github.com/dotnet/project-system/milestone/16)|[master](https://github.com/dotnet/roslyn-project-system/tree/master)|Majority non-breaking feature work, and bugs, crashes and hangs that block/impact _major_ and _minor_ scenarios.
|[16.0](https://github.com/dotnet/roslyn-project-system/milestone/12)|none|[Feature parity](https://github.com/dotnet/project-system/issues?q=is%3Aopen+is%3Aissue+label%3AParity-VSLangProj) with the legacy project system, support for WinForms, WPF and ASP.NET.
|[Unknown](https://github.com/dotnet/roslyn-project-system/milestone/5)|none|Uncommitted features.
