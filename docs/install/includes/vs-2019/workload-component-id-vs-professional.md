---
title: Visual Studio Professional 2019 workload and component IDs
titleSuffix: ""
description: "Use workload and component IDs to install Visual Studio by using the command line or to specify as a dependency in a VSIX manifest"
keywords:
author: TerryGLee
ms.author: tglee
manager: jillfra
ms.date: 02/29/2019
ms.prod: visual-studio-windows
ms.technology: vs-installation
ms.topic: include
---
## Visual Studio core editor (included with Visual Studio Professional 2019)

**ID:** Microsoft.VisualStudio.Workload.CoreEditor

**Description:** The Visual Studio core shell experience, including syntax-aware code editing, source code control and work item management.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Microsoft.VisualStudio.Component.CoreEditor | Visual Studio core editor | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.StartPageExperiment.Cpp | Visual Studio Start Page for C++ Users | 16.0.28315.86 | Optional

## Azure development

**ID:** Microsoft.VisualStudio.Workload.Azure

**Description:** Azure SDKs, tools, and projects for developing cloud apps, creating resources, and building Containers including Docker support.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Component.Microsoft.VisualStudio.RazorExtension | Razor Language Services | 16.0.28315.86 | Required
Component.Microsoft.VisualStudio.Web.AzureFunctions | Azure WebJobs Tools | 16.0.28625.61 | Required
Component.Microsoft.Web.LibraryManager | Library Manager | 16.0.28315.86 | Required
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Required
Microsoft.Net.Component.4.5.2.TargetingPack | .NET Framework 4.5.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.5.TargetingPack | .NET Framework 4.5 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.6.1.TargetingPack | .NET Framework 4.6.1 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.TargetingPack | .NET Framework 4.7.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.ComponentGroup.DevelopmentPrerequisites | .NET Framework 4.7.2 development tools | 16.0.28516.191 | Required
Microsoft.Net.Core.Component.SDK.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Required
Microsoft.NetCore.ComponentGroup.DevelopmentTools.2.1 | .NET Core 2.1 development tools | 16.0.28516.191 | Required
Microsoft.NetCore.ComponentGroup.Web.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.Azure.AuthoringTools | Azure Authoring Tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Azure.ClientLibs | Azure libraries for .NET | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.Azure.Compute.Emulator | Azure Compute Emulator | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Azure.Storage.Emulator | Azure Storage Emulator | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.CloudExplorer | Cloud Explorer | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Common.Azure.Tools | Connectivity and publishing tools | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.DockerTools | Container development tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.FSharp | F# language support | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.FSharp.WebTemplates | F# language support for web projects | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.IISExpress | IIS Express  | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.JavaScript.Diagnostics | JavaScript diagnostics | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.JavaScript.TypeScript | JavaScript and TypeScript language support | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.ManagedDesktop.Core | Managed Desktop Workload Core | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.MSODBC.SQL | SQL Server ODBC Driver | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.MSSQL.CMDLnUtils | SQL Server Command Line Utilities | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Required
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.SQL.ADAL | SQL ADAL runtime | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.SQL.CLR | CLR data types for SQL Server | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.SQL.DataSources | Data sources for SQL Server support | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.SQL.LocalDB.Runtime | SQL Server Express 2016 LocalDB | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.SQL.SSDT | SQL Server Data Tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.TextTemplating | Text Template Transformation | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.TypeScript.3.3 | TypeScript 3.3 SDK | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Web | ASP.NET and web development tools | 16.0.28517.75 | Required
Microsoft.VisualStudio.ComponentGroup.Azure.Prerequisites | Azure development prerequisites | 16.0.28625.61 | Required
Microsoft.VisualStudio.ComponentGroup.AzureFunctions | Azure WebJobs Tools | 16.0.28621.142 | Required
Microsoft.VisualStudio.ComponentGroup.Web | ASP.NET and web development tools prerequisites | 16.0.28621.142 | Required
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Required
Microsoft.Component.Azure.DataLake.Tools | Azure Data Lake and Stream Analytics Tools | 16.0.28625.61 | Recommended
Microsoft.Net.Component.4.5.1.TargetingPack | .NET Framework 4.5.1 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.6.TargetingPack | .NET Framework 4.6 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.TargetingPack | .NET Framework 4 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.ComponentGroup.TargetingPacks.Common | .NET Framework 4 – 4.6 development tools | 16.0.28516.191 | Recommended
Microsoft.VisualStudio.Component.AspNet45 | Advanced ASP.NET features | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.Azure.Kubernetes.Tools | Visual Studio Tools for Kubernetes | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Azure.ResourceManager.Tools | Azure Resource Manager core tools | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.Azure.ServiceFabric.Tools | Service Fabric Tools | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.Azure.Waverton | Azure Cloud Services core tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Azure.Waverton.BuildTools | Azure Cloud Services build tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.DiagnosticTools | .NET profiling tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.WebDeploy | Web Deploy | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.ComponentGroup.Azure.CloudServices | Azure Cloud Services tools | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.ComponentGroup.Azure.ResourceManager.Tools | Azure Resource Manager tools | 16.0.28528.71 | Recommended
Microsoft.Net.Component.4.6.1.SDK | .NET Framework 4.6.1 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.2.SDK | .NET Framework 4.6.2 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.2.TargetingPack | .NET Framework 4.6.2 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.1.SDK | .NET Framework 4.7.1 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.1.TargetingPack | .NET Framework 4.7.1 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.SDK | .NET Framework 4.7 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.TargetingPack | .NET Framework 4.7 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.ComponentGroup.4.6.1.DeveloperTools | .NET Framework 4.6.1 development tools | 16.0.28621.142 | Optional
Microsoft.Net.ComponentGroup.4.6.2.DeveloperTools | .NET Framework 4.6.2 development tools | 16.0.28516.191 | Optional
Microsoft.Net.ComponentGroup.4.7.1.DeveloperTools | .NET Framework 4.7.1 development tools | 16.0.28516.191 | Optional
Microsoft.Net.ComponentGroup.4.7.DeveloperTools | .NET Framework 4.7 development tools | 16.0.28516.191 | Optional
Microsoft.Net.Core.Component.SDK.2.2 | .NET Core 2.2 development tools | 16.0.28621.142 | Optional
Microsoft.NetCore.ComponentGroup.DevelopmentTools.2.2 | .NET Core 2.2 development tools | 16.0.28516.191 | Optional
Microsoft.NetCore.ComponentGroup.Web.2.2 | .NET Core 2.2 development tools | 16.0.28621.142 | Optional
Microsoft.VisualStudio.Component.Azure.Storage.AzCopy | Azure Storage AzCopy | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.Wcf.Tooling | Windows Communication Foundation | 16.0.28625.61 | Optional

## Data storage and processing

**ID:** Microsoft.VisualStudio.Workload.Data

**Description:** Connect, develop, and test data solutions with SQL Server, Azure Data Lake, or Hadoop.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Component.Microsoft.VisualStudio.RazorExtension | Razor Language Services | 16.0.28315.86 | Recommended
Component.Microsoft.Web.LibraryManager | Library Manager | 16.0.28315.86 | Recommended
Microsoft.Component.Azure.DataLake.Tools | Azure Data Lake and Stream Analytics Tools | 16.0.28625.61 | Recommended
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.5.1.TargetingPack | .NET Framework 4.5.1 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.5.2.TargetingPack | .NET Framework 4.5.2 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.5.TargetingPack | .NET Framework 4.5 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.6.TargetingPack | .NET Framework 4.6 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.7.2.TargetingPack | .NET Framework 4.7.2 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.TargetingPack | .NET Framework 4 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.ComponentGroup.DevelopmentPrerequisites | .NET Framework 4.7.2 development tools | 16.0.28516.191 | Recommended
Microsoft.Net.ComponentGroup.TargetingPacks.Common | .NET Framework 4 – 4.6 development tools | 16.0.28516.191 | Recommended
Microsoft.Net.Core.Component.SDK.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Recommended
Microsoft.VisualStudio.Component.Azure.AuthoringTools | Azure Authoring Tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Azure.ClientLibs | Azure libraries for .NET | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.Azure.Compute.Emulator | Azure Compute Emulator | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Azure.Storage.Emulator | Azure Storage Emulator | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.Azure.Waverton | Azure Cloud Services core tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Azure.Waverton.BuildTools | Azure Cloud Services build tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.CloudExplorer | Cloud Explorer | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Common.Azure.Tools | Connectivity and publishing tools | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.DockerTools | Container development tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.IISExpress | IIS Express  | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.JavaScript.Diagnostics | JavaScript diagnostics | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.JavaScript.TypeScript | JavaScript and TypeScript language support | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.ManagedDesktop.Core | Managed Desktop Workload Core | 16.0.28621.142 | Recommended
Microsoft.VisualStudio.Component.MSODBC.SQL | SQL Server ODBC Driver | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.MSSQL.CMDLnUtils | SQL Server Command Line Utilities | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Recommended
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.SQL.ADAL | SQL ADAL runtime | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.SQL.CLR | CLR data types for SQL Server | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.SQL.DataSources | Data sources for SQL Server support | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.SQL.LocalDB.Runtime | SQL Server Express 2016 LocalDB | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.SQL.SSDT | SQL Server Data Tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.TextTemplating | Text Template Transformation | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.TypeScript.3.3 | TypeScript 3.3 SDK | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Web | ASP.NET and web development tools | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.ComponentGroup.Web | ASP.NET and web development tools prerequisites | 16.0.28621.142 | Recommended
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Recommended
Microsoft.Net.Component.4.6.1.TargetingPack | .NET Framework 4.6.1 targeting pack | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.FSharp.Desktop | F# desktop language support | 16.0.28315.86 | Optional

## Data science and analytical applications

**ID:** Microsoft.VisualStudio.Workload.DataScience

**Description:** Languages and tooling for creating data science applications, including Python and F#.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Microsoft.Component.PythonTools | Python language support | 16.0.28625.61 | Recommended
Microsoft.Component.PythonTools.Minicondax64 | Python miniconda | 16.0.28625.61 | Recommended
Microsoft.Component.PythonTools.Web | Python web support | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.6.1.TargetingPack | .NET Framework 4.6.1 targeting pack | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.Common.Azure.Tools | Connectivity and publishing tools | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.FSharp.Desktop | F# desktop language support | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.JavaScript.TypeScript | JavaScript and TypeScript language support | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Recommended
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.TypeScript.3.3 | TypeScript 3.3 SDK | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.WebDeploy | Web Deploy | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Recommended
Microsoft.Component.VC.Runtime.UCRTSDK | Windows Universal CRT SDK | 16.0.28625.61 | Optional
Microsoft.ComponentGroup.PythonTools.NativeDevelopment | Python native development tools | 16.0.28621.142 | Optional
Microsoft.VisualStudio.Component.Graphics.Tools | Graphics debugger and GPU profiler for DirectX | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.140 | MSVC v140 - VS 2015 C++ build tools (v14.00) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.CoreIde | C++ core features | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.DiagnosticTools | C++ profiling tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.Tools.x86.x64 | MSVC v142 – VS 2019 C++ x64/x86 build tools (v14.20) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Windows10SDK | Windows Universal C Runtime | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.Windows10SDK.17763 | Windows 10 SDK (10.0.17763.0) | 16.0.28517.75 | Optional

## .NET desktop development

**ID:** Microsoft.VisualStudio.Workload.ManagedDesktop

**Description:** Build WPF, Windows Forms, and console applications using C#, Visual Basic, and F#.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.TargetingPack | .NET Framework 4.7.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.ComponentGroup.DevelopmentPrerequisites | .NET Framework 4.7.2 development tools | 16.0.28516.191 | Required
Microsoft.Net.Core.Component.SDK.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.ManagedDesktop.Core | Managed Desktop Workload Core | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.ManagedDesktop.Prerequisites | .NET desktop development tools | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Required
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.SQL.CLR | CLR data types for SQL Server | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.TextTemplating | Text Template Transformation | 16.0.28625.61 | Required
Component.Microsoft.VisualStudio.LiveShare | Live Share - Preview | 0.3.1225.0 | Recommended
Microsoft.ComponentGroup.Blend | Blend for Visual Studio | 16.0.28315.86 | Recommended
Microsoft.Net.Component.4.5.1.TargetingPack | .NET Framework 4.5.1 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.5.2.TargetingPack | .NET Framework 4.5.2 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.5.TargetingPack | .NET Framework 4.5 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.6.TargetingPack | .NET Framework 4.6 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.TargetingPack | .NET Framework 4 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.ComponentGroup.TargetingPacks.Common | .NET Framework 4 – 4.6 development tools | 16.0.28516.191 | Recommended
Microsoft.VisualStudio.Component.Debugger.JustInTime | Just-In-Time debugger | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.EntityFramework | Entity Framework 6 tools | 16.0.28315.86 | Recommended
Component.Dotfuscator | PreEmptive Protection - Dotfuscator | 16.0.28528.71 | Optional
Component.Microsoft.VisualStudio.RazorExtension | Razor Language Services | 16.0.28315.86 | Optional
Component.Microsoft.Web.LibraryManager | Library Manager | 16.0.28315.86 | Optional
Microsoft.Net.Component.4.6.1.SDK | .NET Framework 4.6.1 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.1.TargetingPack | .NET Framework 4.6.1 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.2.SDK | .NET Framework 4.6.2 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.2.TargetingPack | .NET Framework 4.6.2 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.1.SDK | .NET Framework 4.7.1 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.1.TargetingPack | .NET Framework 4.7.1 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.SDK | .NET Framework 4.7 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.TargetingPack | .NET Framework 4.7 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.ComponentGroup.4.6.1.DeveloperTools | .NET Framework 4.6.1 development tools | 16.0.28621.142 | Optional
Microsoft.Net.ComponentGroup.4.6.2.DeveloperTools | .NET Framework 4.6.2 development tools | 16.0.28516.191 | Optional
Microsoft.Net.ComponentGroup.4.7.1.DeveloperTools | .NET Framework 4.7.1 development tools | 16.0.28516.191 | Optional
Microsoft.Net.ComponentGroup.4.7.DeveloperTools | .NET Framework 4.7 development tools | 16.0.28516.191 | Optional
Microsoft.Net.Core.Component.SDK.2.2 | .NET Core 2.2 development tools | 16.0.28621.142 | Optional
Microsoft.NetCore.ComponentGroup.DevelopmentTools.2.1 | .NET Core 2.1 development tools | 16.0.28516.191 | Optional
Microsoft.NetCore.ComponentGroup.DevelopmentTools.2.2 | .NET Core 2.2 development tools | 16.0.28516.191 | Optional
Microsoft.VisualStudio.Component.Common.Azure.Tools | Connectivity and publishing tools | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.DockerTools | Container development tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.FSharp | F# language support | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.FSharp.Desktop | F# desktop language support | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.IISExpress | IIS Express  | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.JavaScript.Diagnostics | JavaScript diagnostics | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.JavaScript.TypeScript | JavaScript and TypeScript language support | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.MSODBC.SQL | SQL Server ODBC Driver | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.MSSQL.CMDLnUtils | SQL Server Command Line Utilities | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.PortableLibrary | .NET Portable Library targeting pack | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.SQL.ADAL | SQL ADAL runtime | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.SQL.DataSources | Data sources for SQL Server support | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.SQL.LocalDB.Runtime | SQL Server Express 2016 LocalDB | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.SQL.SSDT | SQL Server Data Tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.TypeScript.3.3 | TypeScript 3.3 SDK | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Wcf.Tooling | Windows Communication Foundation | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Web | ASP.NET and web development tools | 16.0.28517.75 | Optional
Microsoft.VisualStudio.ComponentGroup.Web | ASP.NET and web development tools prerequisites | 16.0.28621.142 | Optional
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Optional

## Game development with Unity

**ID:** Microsoft.VisualStudio.Workload.ManagedGame

**Description:** Create 2D and 3D games with Unity, a powerful cross-platform development environment.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Microsoft.Net.Component.3.5.DeveloperTools | .NET Framework 3.5 development tools | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.1.TargetingPack | .NET Framework 4.7.1 targeting pack | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Required
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Unity | Visual Studio Tools for Unity | 16.0.28315.86 | Required
Component.UnityEngine.x64 | Unity 2018.3 64-bit Editor | 16.0.28528.71 | Recommended
Component.UnityEngine.x86 | Unity 5.6 32-bit Editor | 16.0.28315.86 | Recommended

## Linux development with C++

**ID:** Microsoft.VisualStudio.Workload.NativeCrossPlat

**Description:** Create and debug applications running in a Linux environment.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Component.MDD.Linux | C++ for Linux Development | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.VC.CoreIde | C++ core features | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Windows10SDK | Windows Universal C Runtime | 16.0.28315.86 | Required
Component.Linux.CMake | C++ CMake tools for Linux | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.VC.Tools.x86.x64 | MSVC v142 – VS 2019 C++ x64/x86 build tools (v14.20) | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Windows10SDK.17763 | Windows 10 SDK (10.0.17763.0) | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Recommended
Component.MDD.Linux.GCC.arm | Embedded and IoT development tools | 16.0.28625.61 | Optional

## Desktop development with C++

**ID:** Microsoft.VisualStudio.Workload.NativeDesktop

**Description:** Build Windows desktop applications using the Microsoft C++ toolset, ATL, or MFC.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Required
Microsoft.VisualStudio.Component.TextTemplating | Text Template Transformation | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.VC.CoreIde | C++ core features | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.VC.Redist.14.Latest | C++ 2019 Redistributable Update | 16.0.28625.61 | Required
Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Core | Visual C++ core desktop features | 16.0.28315.86 | Required
Component.Microsoft.VisualStudio.LiveShare | Live Share - Preview | 0.3.1225.0 | Recommended
Microsoft.VisualStudio.Component.Debugger.JustInTime | Just-In-Time debugger | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.Graphics.Tools | Graphics debugger and GPU profiler for DirectX | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.VC.ATL | C++ ATL for v142 build tools (x86 & x64) | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.VC.CMake.Project | C++ CMake tools for Windows | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.VC.DiagnosticTools | C++ profiling tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.VC.TestAdapterForBoostTest | Test Adapter for Boost.Test | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.VC.TestAdapterForGoogleTest | Test Adapter for Google Test | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.VC.Tools.x86.x64 | MSVC v142 – VS 2019 C++ x64/x86 build tools (v14.20) | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Windows10SDK.17763 | Windows 10 SDK (10.0.17763.0) | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Recommended
Component.Incredibuild | IncrediBuild - Build Acceleration | 16.0.28528.71 | Optional
Component.IncredibuildMenu | IncrediBuildMenu | 1.5.0.2 | Optional
Microsoft.Component.VC.Runtime.UCRTSDK | Windows Universal CRT SDK | 16.0.28625.61 | Optional
Microsoft.Net.Component.4.6.1.SDK | .NET Framework 4.6.1 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.1.TargetingPack | .NET Framework 4.6.1 targeting pack | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.VC.140 | MSVC v140 - VS 2015 C++ build tools (v14.00) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.ATLMFC | C++ MFC for v142 build tools (x86 & x64) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.CLI.Support | C++/CLI support for v142 build tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.Modules.x86.x64 | C++ Modules for v142 build tools (x64/x86 – experimental) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.v141.x86.x64 | MSVC v141 – VS 2017 C++ x64/x86 build tools (v14.16) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Windows10SDK.16299 | Windows 10 SDK (10.0.16299.0) | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.Windows10SDK.17134 | Windows 10 SDK (10.0.17134.0) | 16.0.28517.75 | Optional

## Game development with C++

**ID:** Microsoft.VisualStudio.Workload.NativeGame

**Description:** Use the full power of C++ to build professional games powered by DirectX, Unreal, or Cocos2d.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Microsoft.VisualStudio.Component.VC.CoreIde | C++ core features | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.VC.Redist.14.Latest | C++ 2019 Redistributable Update | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.VC.Tools.x86.x64 | MSVC v142 – VS 2019 C++ x64/x86 build tools (v14.20) | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Windows10SDK | Windows Universal C Runtime | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.Graphics.Tools | Graphics debugger and GPU profiler for DirectX | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.VC.DiagnosticTools | C++ profiling tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Windows10SDK.17763 | Windows 10 SDK (10.0.17763.0) | 16.0.28517.75 | Recommended
Component.Android.NDK.R16B | Android NDK (R16B) | 16.0.28625.61 | Optional
Component.Android.SDK25.Private | Android SDK setup (API level 25) (local install for Mobile development with C++) | 16.0.28625.61 | Optional
Component.Ant | Apache Ant (1.9.3) | 1.9.3.8 | Optional
Component.Cocos | Cocos | 16.0.28315.86 | Optional
Component.Incredibuild | IncrediBuild - Build Acceleration | 16.0.28528.71 | Optional
Component.IncredibuildMenu | IncrediBuildMenu | 1.5.0.2 | Optional
Component.MDD.Android | C++ Android development tools | 16.0.28517.75 | Optional
Component.OpenJDK | OpenJDK (Microsoft distribution) | 16.0.28625.61 | Optional
Component.Unreal | Unreal Engine installer | 16.0.28625.61 | Optional
Component.Unreal.Android | Android IDE support for Unreal engine | 16.0.28625.61 | Optional
Microsoft.Net.Component.4.5.1.TargetingPack | .NET Framework 4.5.1 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.5.2.TargetingPack | .NET Framework 4.5.2 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.5.TargetingPack | .NET Framework 4.5 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.2.TargetingPack | .NET Framework 4.6.2 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.TargetingPack | .NET Framework 4.6 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.2.TargetingPack | .NET Framework 4.7.2 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.TargetingPack | .NET Framework 4 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.ComponentGroup.DevelopmentPrerequisites | .NET Framework 4.7.2 development tools | 16.0.28516.191 | Optional
Microsoft.Net.ComponentGroup.TargetingPacks.Common | .NET Framework 4 – 4.6 development tools | 16.0.28516.191 | Optional
Microsoft.VisualStudio.Component.NuGet.BuildTools | NuGet targets and build tasks | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Optional
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Windows10SDK.16299 | Windows 10 SDK (10.0.16299.0) | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.Windows10SDK.17134 | Windows 10 SDK (10.0.17134.0) | 16.0.28517.75 | Optional

## Mobile development with C++

**ID:** Microsoft.VisualStudio.Workload.NativeMobile

**Description:** Build cross-platform applications for iOS, Android or Windows using C++.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Component.Android.SDK25.Private | Android SDK setup (API level 25) (local install for Mobile development with C++) | 16.0.28625.61 | Required
Component.OpenJDK | OpenJDK (Microsoft distribution) | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.VC.CoreIde | C++ core features | 16.0.28625.61 | Required
Component.Android.NDK.R16B | Android NDK (R16B) | 16.0.28625.61 | Recommended
Component.Ant | Apache Ant (1.9.3) | 1.9.3.8 | Recommended
Component.MDD.Android | C++ Android development tools | 16.0.28517.75 | Recommended
Component.Android.NDK.R16B_3264 | Android NDK (R16B) (32bit) | 16.0.28625.61 | Optional
Component.Google.Android.Emulator.API25.Private | Google Android Emulator (API Level 25) (local install) | 16.0.28625.61 | Optional
Component.HAXM.Private | Intel Hardware Accelerated Execution Manager (HAXM) (local install) | 16.0.28528.71 | Optional
Component.Incredibuild | IncrediBuild - Build Acceleration | 16.0.28528.71 | Optional
Component.IncredibuildMenu | IncrediBuildMenu | 1.5.0.2 | Optional
Component.MDD.IOS | C++ iOS development tools | 16.0.28517.75 | Optional

## .NET Core cross-platform development

**ID:** Microsoft.VisualStudio.Workload.NetCoreTools

**Description:** Build cross-platform applications using .NET Core, ASP.NET Core, HTML/JavaScript, and Containers including Docker support.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Component.Microsoft.VisualStudio.RazorExtension | Razor Language Services | 16.0.28315.86 | Required
Component.Microsoft.Web.LibraryManager | Library Manager | 16.0.28315.86 | Required
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Required
Microsoft.Net.Component.4.5.2.TargetingPack | .NET Framework 4.5.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.5.TargetingPack | .NET Framework 4.5 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.6.1.TargetingPack | .NET Framework 4.6.1 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.TargetingPack | .NET Framework 4.7.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.ComponentGroup.DevelopmentPrerequisites | .NET Framework 4.7.2 development tools | 16.0.28516.191 | Required
Microsoft.Net.Core.Component.SDK.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Required
Microsoft.NetCore.ComponentGroup.DevelopmentTools.2.1 | .NET Core 2.1 development tools | 16.0.28516.191 | Required
Microsoft.NetCore.ComponentGroup.Web.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.Common.Azure.Tools | Connectivity and publishing tools | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.DockerTools | Container development tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.FSharp | F# language support | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.FSharp.WebTemplates | F# language support for web projects | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.IISExpress | IIS Express  | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.JavaScript.Diagnostics | JavaScript diagnostics | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.JavaScript.TypeScript | JavaScript and TypeScript language support | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.ManagedDesktop.Core | Managed Desktop Workload Core | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.MSODBC.SQL | SQL Server ODBC Driver | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.MSSQL.CMDLnUtils | SQL Server Command Line Utilities | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Required
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.SQL.ADAL | SQL ADAL runtime | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.SQL.CLR | CLR data types for SQL Server | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.SQL.DataSources | Data sources for SQL Server support | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.SQL.LocalDB.Runtime | SQL Server Express 2016 LocalDB | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.SQL.SSDT | SQL Server Data Tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.TextTemplating | Text Template Transformation | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.TypeScript.3.3 | TypeScript 3.3 SDK | 16.0.28625.61 | Required
Microsoft.VisualStudio.ComponentGroup.Web | ASP.NET and web development tools prerequisites | 16.0.28621.142 | Required
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Required
Component.Microsoft.VisualStudio.LiveShare | Live Share - Preview | 0.3.1225.0 | Recommended
Component.Microsoft.VisualStudio.Web.AzureFunctions | Azure WebJobs Tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.AppInsights.Tools | Developer Analytics tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Azure.AuthoringTools | Azure Authoring Tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Azure.ClientLibs | Azure libraries for .NET | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.Azure.Compute.Emulator | Azure Compute Emulator | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Azure.Storage.Emulator | Azure Storage Emulator | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.CloudExplorer | Cloud Explorer | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.DiagnosticTools | .NET profiling tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Web | ASP.NET and web development tools | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.WebDeploy | Web Deploy | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.ComponentGroup.AzureFunctions | Azure WebJobs Tools | 16.0.28621.142 | Recommended
Microsoft.VisualStudio.ComponentGroup.Web.CloudTools | Cloud tools for web development | 16.0.28621.142 | Recommended
Microsoft.Net.Core.Component.SDK.2.2 | .NET Core 2.2 development tools | 16.0.28621.142 | Optional
Microsoft.NetCore.ComponentGroup.DevelopmentTools.2.2 | .NET Core 2.2 development tools | 16.0.28516.191 | Optional
Microsoft.NetCore.ComponentGroup.Web.2.2 | .NET Core 2.2 development tools | 16.0.28621.142 | Optional
Microsoft.VisualStudio.ComponentGroup.IISDevelopment | Development time IIS support | 16.0.28315.86 | Optional

## Mobile development with .NET

**ID:** Microsoft.VisualStudio.Workload.NetCrossPlat

**Description:** Build cross-platform applications for iOS, Android or Windows using Xamarin.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Component.Xamarin | Xamarin | 16.0.28625.61 | Required
Component.Xamarin.RemotedSimulator | Xamarin Remoted Simulator | 16.0.28315.86 | Required
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Required
Microsoft.Net.Component.4.6.1.TargetingPack | .NET Framework 4.6.1 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.TargetingPack | .NET Framework 4.7.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.ComponentGroup.DevelopmentPrerequisites | .NET Framework 4.7.2 development tools | 16.0.28516.191 | Required
Microsoft.Net.Core.Component.SDK.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Required
Microsoft.NetCore.ComponentGroup.DevelopmentTools.2.1 | .NET Core 2.1 development tools | 16.0.28516.191 | Required
Microsoft.VisualStudio.Component.FSharp | F# language support | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.Merq | Common Xamarin internal tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.MonoDebugger | Mono debugger | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Required
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Required
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions.TemplateEngine | ASP.NET templating engine | 16.0.28315.86 | Required
Component.Android.SDK27 | Android SDK setup (API level 27) | 16.0.28517.75 | Recommended
Component.OpenJDK | OpenJDK (Microsoft distribution) | 16.0.28625.61 | Recommended

## ASP.NET and web development

**ID:** Microsoft.VisualStudio.Workload.NetWeb

**Description:** Build web applications using ASP.NET, ASP.NET Core, HTML/JavaScript, and Containers including Docker support.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Component.Microsoft.VisualStudio.RazorExtension | Razor Language Services | 16.0.28315.86 | Required
Component.Microsoft.Web.LibraryManager | Library Manager | 16.0.28315.86 | Required
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Required
Microsoft.Net.Component.4.5.2.TargetingPack | .NET Framework 4.5.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.5.TargetingPack | .NET Framework 4.5 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.6.1.TargetingPack | .NET Framework 4.6.1 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.TargetingPack | .NET Framework 4.7.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.ComponentGroup.DevelopmentPrerequisites | .NET Framework 4.7.2 development tools | 16.0.28516.191 | Required
Microsoft.Net.Core.Component.SDK.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Required
Microsoft.NetCore.ComponentGroup.DevelopmentTools.2.1 | .NET Core 2.1 development tools | 16.0.28516.191 | Required
Microsoft.NetCore.ComponentGroup.Web.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.Common.Azure.Tools | Connectivity and publishing tools | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.DockerTools | Container development tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.FSharp | F# language support | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.FSharp.WebTemplates | F# language support for web projects | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.IISExpress | IIS Express  | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.JavaScript.Diagnostics | JavaScript diagnostics | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.JavaScript.TypeScript | JavaScript and TypeScript language support | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.ManagedDesktop.Core | Managed Desktop Workload Core | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.MSODBC.SQL | SQL Server ODBC Driver | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.MSSQL.CMDLnUtils | SQL Server Command Line Utilities | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Required
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.SQL.ADAL | SQL ADAL runtime | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.SQL.CLR | CLR data types for SQL Server | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.SQL.DataSources | Data sources for SQL Server support | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.SQL.LocalDB.Runtime | SQL Server Express 2016 LocalDB | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.SQL.SSDT | SQL Server Data Tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.TextTemplating | Text Template Transformation | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.TypeScript.3.3 | TypeScript 3.3 SDK | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Web | ASP.NET and web development tools | 16.0.28517.75 | Required
Microsoft.VisualStudio.ComponentGroup.Web | ASP.NET and web development tools prerequisites | 16.0.28621.142 | Required
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Required
Component.Microsoft.VisualStudio.LiveShare | Live Share - Preview | 0.3.1225.0 | Recommended
Component.Microsoft.VisualStudio.Web.AzureFunctions | Azure WebJobs Tools | 16.0.28625.61 | Recommended
Microsoft.Net.Component.4.5.1.TargetingPack | .NET Framework 4.5.1 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.6.TargetingPack | .NET Framework 4.6 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.TargetingPack | .NET Framework 4 targeting pack | 16.0.28517.75 | Recommended
Microsoft.Net.ComponentGroup.TargetingPacks.Common | .NET Framework 4 – 4.6 development tools | 16.0.28516.191 | Recommended
Microsoft.VisualStudio.Component.AppInsights.Tools | Developer Analytics tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.AspNet45 | Advanced ASP.NET features | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.Azure.AuthoringTools | Azure Authoring Tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Azure.ClientLibs | Azure libraries for .NET | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.Azure.Compute.Emulator | Azure Compute Emulator | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.Azure.Storage.Emulator | Azure Storage Emulator | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.CloudExplorer | Cloud Explorer | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.DiagnosticTools | .NET profiling tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.EntityFramework | Entity Framework 6 tools | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.WebDeploy | Web Deploy | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.ComponentGroup.AzureFunctions | Azure WebJobs Tools | 16.0.28621.142 | Recommended
Microsoft.VisualStudio.ComponentGroup.Web.CloudTools | Cloud tools for web development | 16.0.28621.142 | Recommended
Microsoft.Net.Component.4.6.1.SDK | .NET Framework 4.6.1 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.2.SDK | .NET Framework 4.6.2 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.2.TargetingPack | .NET Framework 4.6.2 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.1.SDK | .NET Framework 4.7.1 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.1.TargetingPack | .NET Framework 4.7.1 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.SDK | .NET Framework 4.7 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.TargetingPack | .NET Framework 4.7 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.ComponentGroup.4.6.1.DeveloperTools | .NET Framework 4.6.1 development tools | 16.0.28621.142 | Optional
Microsoft.Net.ComponentGroup.4.6.2.DeveloperTools | .NET Framework 4.6.2 development tools | 16.0.28516.191 | Optional
Microsoft.Net.ComponentGroup.4.7.1.DeveloperTools | .NET Framework 4.7.1 development tools | 16.0.28516.191 | Optional
Microsoft.Net.ComponentGroup.4.7.DeveloperTools | .NET Framework 4.7 development tools | 16.0.28516.191 | Optional
Microsoft.Net.Core.Component.SDK.2.2 | .NET Core 2.2 development tools | 16.0.28621.142 | Optional
Microsoft.NetCore.ComponentGroup.DevelopmentTools.2.2 | .NET Core 2.2 development tools | 16.0.28516.191 | Optional
Microsoft.NetCore.ComponentGroup.Web.2.2 | .NET Core 2.2 development tools | 16.0.28621.142 | Optional
Microsoft.VisualStudio.Component.Wcf.Tooling | Windows Communication Foundation | 16.0.28625.61 | Optional
Microsoft.VisualStudio.ComponentGroup.AdditionalWebProjectTemplates | Additional project templates (previous versions) | 16.0.28621.142 | Optional
Microsoft.VisualStudio.ComponentGroup.IISDevelopment | Development time IIS support | 16.0.28315.86 | Optional

## Node.js development

**ID:** Microsoft.VisualStudio.Workload.Node

**Description:** Build scalable network applications using Node.js, an asynchronous event-driven JavaScript runtime. 

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Microsoft.VisualStudio.Component.JavaScript.Diagnostics | JavaScript diagnostics | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.JavaScript.TypeScript | JavaScript and TypeScript language support | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Node.Tools | Node.js development tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.TypeScript.3.3 | TypeScript 3.3 SDK | 16.0.28625.61 | Required
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Required
Component.Microsoft.VisualStudio.LiveShare | Live Share - Preview | 0.3.1225.0 | Recommended
Microsoft.VisualStudio.Component.WebDeploy | Web Deploy | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.AppInsights.Tools | Developer Analytics tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Common.Azure.Tools | Connectivity and publishing tools | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.VC.CoreIde | C++ core features | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.Tools.x86.x64 | MSVC v142 – VS 2019 C++ x64/x86 build tools (v14.20) | 16.0.28625.61 | Optional

## Office/SharePoint development

**ID:** Microsoft.VisualStudio.Workload.Office

**Description:** Create Office and SharePoint add-ins, SharePoint solutions, and VSTO add-ins using C#, VB, and JavaScript.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Component.Microsoft.VisualStudio.RazorExtension | Razor Language Services | 16.0.28315.86 | Required
Component.Microsoft.Web.LibraryManager | Library Manager | 16.0.28315.86 | Required
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Required
Microsoft.Net.Component.4.5.2.TargetingPack | .NET Framework 4.5.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.5.TargetingPack | .NET Framework 4.5 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.6.1.TargetingPack | .NET Framework 4.6.1 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.TargetingPack | .NET Framework 4.7.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.TargetingPack | .NET Framework 4 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.ComponentGroup.DevelopmentPrerequisites | .NET Framework 4.7.2 development tools | 16.0.28516.191 | Required
Microsoft.Net.Core.Component.SDK.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.AppInsights.Tools | Developer Analytics tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Common.Azure.Tools | Connectivity and publishing tools | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.DockerTools | Container development tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.IISExpress | IIS Express  | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.JavaScript.Diagnostics | JavaScript diagnostics | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.JavaScript.TypeScript | JavaScript and TypeScript language support | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.ManagedDesktop.Core | Managed Desktop Workload Core | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.ManagedDesktop.Prerequisites | .NET desktop development tools | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.MSODBC.SQL | SQL Server ODBC Driver | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.MSSQL.CMDLnUtils | SQL Server Command Line Utilities | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Required
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Sharepoint.Tools | Office Developer Tools for Visual Studio | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.SQL.ADAL | SQL ADAL runtime | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.SQL.CLR | CLR data types for SQL Server | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.SQL.DataSources | Data sources for SQL Server support | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.SQL.LocalDB.Runtime | SQL Server Express 2016 LocalDB | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.SQL.SSDT | SQL Server Data Tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.TextTemplating | Text Template Transformation | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.TypeScript.3.3 | TypeScript 3.3 SDK | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Wcf.Tooling | Windows Communication Foundation | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Web | ASP.NET and web development tools | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.Workflow | Windows Workflow Foundation | 16.0.28315.86 | Required
Microsoft.VisualStudio.ComponentGroup.Web | ASP.NET and web development tools prerequisites | 16.0.28621.142 | Required
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.TeamOffice | Visual Studio Tools for Office (VSTO) | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.WebDeploy | Web Deploy | 16.0.28517.75 | Recommended
Microsoft.Net.Component.4.6.1.SDK | .NET Framework 4.6.1 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.2.SDK | .NET Framework 4.6.2 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.6.2.TargetingPack | .NET Framework 4.6.2 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.1.SDK | .NET Framework 4.7.1 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.1.TargetingPack | .NET Framework 4.7.1 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.SDK | .NET Framework 4.7 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.TargetingPack | .NET Framework 4.7 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.ComponentGroup.4.6.1.DeveloperTools | .NET Framework 4.6.1 development tools | 16.0.28621.142 | Optional
Microsoft.Net.ComponentGroup.4.6.2.DeveloperTools | .NET Framework 4.6.2 development tools | 16.0.28516.191 | Optional
Microsoft.Net.ComponentGroup.4.7.1.DeveloperTools | .NET Framework 4.7.1 development tools | 16.0.28516.191 | Optional
Microsoft.Net.ComponentGroup.4.7.DeveloperTools | .NET Framework 4.7 development tools | 16.0.28516.191 | Optional
Microsoft.VisualStudio.ComponentGroup.Sharepoint.WIF | Windows Identity Foundation 3.5 | 16.0.28621.142 | Optional

## Python development

**ID:** Microsoft.VisualStudio.Workload.Python

**Description:** Editing, debugging, interactive development and source control for Python.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Microsoft.Component.PythonTools | Python language support | 16.0.28625.61 | Required
Component.CPython3.x64 | Python 3 64-bit (3.7.2) | 3.7.2 | Recommended
Component.Microsoft.VisualStudio.LiveShare | Live Share - Preview | 0.3.1225.0 | Recommended
Microsoft.Component.PythonTools.Minicondax64 | Python miniconda | 16.0.28625.61 | Recommended
Microsoft.Component.PythonTools.Web | Python web support | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.Component.Common.Azure.Tools | Connectivity and publishing tools | 16.0.28315.86 | Recommended
Microsoft.VisualStudio.Component.JavaScript.TypeScript | JavaScript and TypeScript language support | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.TypeScript.3.3 | TypeScript 3.3 SDK | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.WebDeploy | Web Deploy | 16.0.28517.75 | Recommended
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Recommended
Component.CPython2.x64 | Python 2 64-bit (2.7.15) | 2.7.15 | Optional
Component.CPython2.x86 | Python 2 32-bit (2.7.15) | 2.7.15 | Optional
Component.CPython3.x86 | Python 3 32-bit (3.7.2) | 3.7.2 | Optional
Component.Microsoft.VisualStudio.RazorExtension | Razor Language Services | 16.0.28315.86 | Optional
Component.Microsoft.Web.LibraryManager | Library Manager | 16.0.28315.86 | Optional
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Optional
Microsoft.Component.VC.Runtime.UCRTSDK | Windows Universal CRT SDK | 16.0.28625.61 | Optional
Microsoft.ComponentGroup.PythonTools.NativeDevelopment | Python native development tools | 16.0.28621.142 | Optional
Microsoft.Net.Component.4.5.2.TargetingPack | .NET Framework 4.5.2 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.5.TargetingPack | .NET Framework 4.5 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Optional
Microsoft.Net.Component.4.7.2.TargetingPack | .NET Framework 4.7.2 targeting pack | 16.0.28517.75 | Optional
Microsoft.Net.ComponentGroup.DevelopmentPrerequisites | .NET Framework 4.7.2 development tools | 16.0.28516.191 | Optional
Microsoft.Net.Core.Component.SDK.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Optional
Microsoft.VisualStudio.Component.Azure.AuthoringTools | Azure Authoring Tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Azure.ClientLibs | Azure libraries for .NET | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.Azure.Compute.Emulator | Azure Compute Emulator | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Azure.Storage.Emulator | Azure Storage Emulator | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.Azure.Waverton | Azure Cloud Services core tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Azure.Waverton.BuildTools | Azure Cloud Services build tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.DockerTools | Container development tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Graphics.Tools | Graphics debugger and GPU profiler for DirectX | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.IISExpress | IIS Express  | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.JavaScript.Diagnostics | JavaScript diagnostics | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.ManagedDesktop.Core | Managed Desktop Workload Core | 16.0.28621.142 | Optional
Microsoft.VisualStudio.Component.MSODBC.SQL | SQL Server ODBC Driver | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.MSSQL.CMDLnUtils | SQL Server Command Line Utilities | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Optional
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.SQL.ADAL | SQL ADAL runtime | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.SQL.CLR | CLR data types for SQL Server | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.SQL.DataSources | Data sources for SQL Server support | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.SQL.LocalDB.Runtime | SQL Server Express 2016 LocalDB | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.SQL.SSDT | SQL Server Data Tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.TextTemplating | Text Template Transformation | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.140 | MSVC v140 - VS 2015 C++ build tools (v14.00) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.CoreIde | C++ core features | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.DiagnosticTools | C++ profiling tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.Tools.x86.x64 | MSVC v142 – VS 2019 C++ x64/x86 build tools (v14.20) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Web | ASP.NET and web development tools | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.Windows10SDK | Windows Universal C Runtime | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.Windows10SDK.17763 | Windows 10 SDK (10.0.17763.0) | 16.0.28517.75 | Optional
Microsoft.VisualStudio.ComponentGroup.Web | ASP.NET and web development tools prerequisites | 16.0.28621.142 | Optional

## Universal Windows Platform development

**ID:** Microsoft.VisualStudio.Workload.Universal

**Description:** Create applications for the Universal Windows Platform with C#, VB, or optionally C﻿+﻿+.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Microsoft.Component.NetFX.Native | .NET Native | 16.0.28315.86 | Required
Microsoft.ComponentGroup.Blend | Blend for Visual Studio | 16.0.28315.86 | Required
Microsoft.Net.Component.4.5.TargetingPack | .NET Framework 4.5 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.6.1.SDK | .NET Framework 4.6.1 SDK | 16.0.28517.75 | Required
Microsoft.Net.Core.Component.SDK.2.1 | .NET Core 2.1 development tools | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.AppInsights.Tools | Developer Analytics tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.DiagnosticTools | .NET profiling tools | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Graphics | Image and 3D model editors | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.JavaScript.Diagnostics | JavaScript diagnostics | 16.0.28517.75 | Required
Microsoft.VisualStudio.Component.JavaScript.TypeScript | JavaScript and TypeScript language support | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Required
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.SQL.CLR | CLR data types for SQL Server | 16.0.28315.86 | Required
Microsoft.VisualStudio.Component.TypeScript.3.3 | TypeScript 3.3 SDK | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Windows10SDK.17763 | Windows 10 SDK (10.0.17763.0) | 16.0.28517.75 | Required
Microsoft.VisualStudio.ComponentGroup.UWP.NetCoreAndStandard | .NET Native and .NET Standard | 16.0.28516.191 | Required
Microsoft.VisualStudio.ComponentGroup.UWP.Support | Universal Windows Platform tools | 16.0.28621.142 | Required
Microsoft.VisualStudio.ComponentGroup.UWP.Xamarin | Universal Windows Platform tools for Xamarin | 16.0.28621.142 | Required
Microsoft.VisualStudio.ComponentGroup.WebToolsExtensions | ASP.NET and web development | 16.0.28621.142 | Required
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Optional
Microsoft.Component.VC.Runtime.OSSupport | C++ Universal Windows Platform runtime for v142 build tools | 16.0.28625.61 | Optional
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.Graphics.Tools | Graphics debugger and GPU profiler for DirectX | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.TextTemplating | Text Template Transformation | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.UWP.VC.ARM64 | C++ Universal Windows Platform support for v142 build tools (ARM64) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.CoreIde | C++ core features | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.Redist.14.Latest | C++ 2019 Redistributable Update | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.Tools.ARM | MSVC v142 – VS 2019 C++ ARM build tools (v14.20) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.Tools.ARM64 | MSVC v142 – VS 2019 C++ ARM64 build tools (v14.20) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.Tools.x86.x64 | MSVC v142 – VS 2019 C++ x64/x86 build tools (v14.20) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.v141.ARM | MSVC v141 – VS 2017 C++ ARM build tools (v14.16) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.v141.ARM64 | MSVC v141 – VS 2017 C++ ARM64 build tools (v14.16) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.v141.x86.x64 | MSVC v141 – VS 2017 C++ x64/x86 build tools (v14.16) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.Windows10SDK.16299 | Windows 10 SDK (10.0.16299.0) | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.Windows10SDK.17134 | Windows 10 SDK (10.0.17134.0) | 16.0.28517.75 | Optional
Microsoft.VisualStudio.Component.Windows10SDK.IpOverUsb | USB Device Connectivity | 16.0.28320.51 | Optional
Microsoft.VisualStudio.ComponentGroup.NativeDesktop.Core | Visual C++ core desktop features | 16.0.28315.86 | Optional
Microsoft.VisualStudio.ComponentGroup.UWP.VC | C++ (v142) Universal Windows Platform tools | 16.0.28621.142 | Optional
Microsoft.VisualStudio.ComponentGroup.UWP.VC.v141 | C++ (v141) Universal Windows Platform tools | 16.0.28621.142 | Optional

## Visual Studio extension development

**ID:** Microsoft.VisualStudio.Workload.VisualStudioExtension

**Description:** Create add-ons and extensions for Visual Studio, including new commands, code analyzers and tool windows.

### Components included by this workload

Component ID | Name | Version | Dependency type
--- | --- | --- | ---
Microsoft.Component.MSBuild | MSBuild | 16.0.28517.75 | Required
Microsoft.Net.Component.4.6.TargetingPack | .NET Framework 4.6 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.SDK | .NET Framework 4.7.2 SDK | 16.0.28517.75 | Required
Microsoft.Net.Component.4.7.2.TargetingPack | .NET Framework 4.7.2 targeting pack | 16.0.28517.75 | Required
Microsoft.Net.ComponentGroup.DevelopmentPrerequisites | .NET Framework 4.7.2 development tools | 16.0.28516.191 | Required
Microsoft.VisualStudio.Component.NuGet | NuGet package manager | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.Roslyn.Compiler | C# and Visual Basic Roslyn compilers | 16.0.28528.71 | Required
Microsoft.VisualStudio.Component.Roslyn.LanguageServices | C# and Visual Basic | 16.0.28625.61 | Required
Microsoft.VisualStudio.Component.VSSDK | Visual Studio SDK | 16.0.28315.86 | Required
Microsoft.VisualStudio.ComponentGroup.VisualStudioExtension.Prerequisites | Visual Studio extension development prerequisites | 16.0.28621.142 | Required
Microsoft.VisualStudio.Component.DiagnosticTools | .NET profiling tools | 16.0.28625.61 | Recommended
Microsoft.VisualStudio.Component.TextTemplating | Text Template Transformation | 16.0.28625.61 | Recommended
Component.Dotfuscator | PreEmptive Protection - Dotfuscator | 16.0.28528.71 | Optional
Microsoft.Component.CodeAnalysis.SDK | .NET Compiler Platform SDK | 16.0.28625.61 | Optional
Microsoft.Component.VC.Runtime.OSSupport | C++ Universal Windows Platform runtime for v142 build tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.AppInsights.Tools | Developer Analytics tools | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.ClassDesigner | Class Designer | 16.0.28528.71 | Optional
Microsoft.VisualStudio.Component.DslTools | Modeling SDK | 16.0.28315.86 | Optional
Microsoft.VisualStudio.Component.VC.ATL | C++ ATL for v142 build tools (x86 & x64) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.ATLMFC | C++ MFC for v142 build tools (x86 & x64) | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.CoreIde | C++ core features | 16.0.28625.61 | Optional
Microsoft.VisualStudio.Component.VC.Tools.x86.x64 | MSVC v142 – VS 2019 C++ x64/x86 build tools (v14.20) | 16.0.28625.61 | Optional

## Unaffiliated components

These are components that are not included with any workload, but may be selected as an individual component.

Component ID | Name | Version
--- | --- | ---
Component.GitHub.VisualStudio | GitHub extension for Visual Studio | 2.5.9.5485
Component.Xamarin.Inspector | Xamarin Inspector | 16.0.28315.86
Component.Xamarin.Profiler | Xamarin Profiler | 16.0.28315.86
Component.Xamarin.Workbooks | Xamarin Workbooks | 16.0.28315.86
Microsoft.Component.HelpViewer | Help Viewer | 16.0.28625.61
Microsoft.NetCore.1x.ComponentGroup.Web | .NET Core 1.0 - 1.1 development tools for Web | 16.0.28621.142
Microsoft.VisualStudio.Component.AzureDevOps.OfficeIntegration | Azure DevOps Office Integration | 16.0.28625.61
Microsoft.VisualStudio.Component.DependencyValidation.Community | Dependency Validation | 16.0.28517.75
Microsoft.VisualStudio.Component.Git | Git for Windows | 16.0.28625.61
Microsoft.VisualStudio.Component.GraphDocument | DGML editor | 16.0.28625.61
Microsoft.VisualStudio.Component.LinqToSql | LINQ to SQL tools | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.ATL.ARM | C++ ATL for v142 build tools (ARM) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.ATL.ARM.Spectre | C++ ATL for v142 build tools with Spectre Mitigations (ARM) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.ATL.ARM64 | C++ ATL for v142 build tools (ARM64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.ATL.ARM64.Spectre | C++ ATL for v142 build tools with Spectre Mitigations (ARM64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.ATL.Spectre | C++ ATL for v142 build tools with Spectre Mitigations (x86 & x64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.ATLMFC.Spectre | C++ MFC for v142 build tools with Spectre Mitigations (x86 & x64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.MFC.ARM | C++ MFC for v142 build tools (ARM) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.MFC.ARM.Spectre | C++ MFC for v142 build tools with Spectre Mitigations (ARM) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.MFC.ARM64 | C++ MFC for v142 build tools (ARM64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.MFC.ARM64.Spectre | C++ MFC for v142 build tools with Spectre Mitigations (ARM64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.Redist.MSM | C++ 2019 Redistributable MSMs | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.Runtimes.ARM.Spectre | MSVC v142 – VS 2019 C++ ARM Spectre-mitigated libs (v14.20) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.Runtimes.ARM64.Spectre | MSVC v142 – VS 2019 C++ ARM64 Spectre-mitigated libs (v14.20) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.Runtimes.x86.x64.Spectre | MSVC v142 – VS 2019 C++ x64/x86 Spectre-mitigated libs (v14.20)  | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.ARM.Spectre | MSVC v141 – VS 2017 C++ ARM Spectre-mitigated libs (v14.16) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.ARM64.Spectre | MSVC v141 – VS 2017 C++ ARM64 Spectre-mitigated libs (v14.16) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.ATL | C++ ATL for v141 build tools (x86 & x64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.ATL.ARM | C++ ATL for v141 build tools (ARM) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.ATL.ARM.Spectre | C++ ATL for v141 build tools with Spectre Mitigations (ARM) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.ATL.ARM64 | C++ ATL for v141 build tools (ARM64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.ATL.ARM64.Spectre | C++ ATL for v141 build tools with Spectre Mitigations (ARM64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.ATL.Spectre | C++ ATL for v141 build tools with Spectre Mitigations (x86 & x64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.CLI.Support | C++/CLI support for v141 build tools | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.MFC | C++ MFC for v141 build tools (x86 & x64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.MFC.ARM | C++ MFC for v141 build tools (ARM) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.MFC.ARM.Spectre | C++ MFC for v141 build tools with Spectre Mitigations (ARM) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.MFC.ARM64 | C++ MFC for v141 build tools (ARM64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.MFC.ARM64.Spectre | C++ MFC for v141 build tools with Spectre Mitigations (ARM64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.MFC.Spectre | C++ MFC for v141 build tools with Spectre Mitigations (x86 & x64) | 16.0.28625.61
Microsoft.VisualStudio.Component.VC.v141.x86.x64.Spectre | MSVC v141 – VS 2017 C++ x64/x86 Spectre-mitigated libs (v14.16) | 16.0.28625.61
Microsoft.VisualStudio.Component.WinXP | C++ Windows XP Support for VS 2017 (v141) tools [Deprecated] | 16.0.28625.61
Microsoft.VisualStudio.Web.Mvc4.ComponentGroup | ASP.NET MVC 4 | 16.0.28621.142