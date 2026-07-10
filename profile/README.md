<img width="436" height="54" alt="Logo_Short" src="https://github.com/user-attachments/assets/722d0d0f-fcbe-4976-9ec9-2e5888fa095c" />

# Code Effects Decision Engine

A commercial, embeddable decision automation platform for .NET - visual rule editor, AI/LLM-assisted rule authoring and execution, no-code for business users, full control for developers.

## Demo Project Repos

Except for the Data Filtering repository (see its description below), these demo repos demonstrate how to integrate the rule editor into web applications, persist user-created business rules, and execute them on the server using the execution engine. Each repo targets a different UI framework or source object model while following the same end-to-end workflow.

Every repo is a standalone Visual Studio 2022 solution with its own `.sln` file. Clone the one you want to run and follow the instructions in its README.

- [`Rule.Demo.Asp`](https://github.com/codeeffects-software/Rule.Demo.Asp) - ASP.NET Core (.NET 8+) + Reflection source model
- [`Rule.Demo.Asp.AdaptiveSource`](https://github.com/codeeffects-software/Rule.Demo.Asp.AdaptiveSource) - ASP.NET Core (.NET 8+) + Adaptive Source model
- [`Rule.Demo.Angular`](https://github.com/codeeffects-software/Rule.Demo.Angular) - ASP.NET Core (.NET 8+) + Angular + Reflection source model
- [`Rule.Demo.React`](https://github.com/codeeffects-software/Rule.Demo.React) - ASP.NET Core (.NET 8+) + React + Reflection source model
- [`Rule.Demo.Asp.DataFiltering`](https://github.com/codeeffects-software/Rule.Demo.Asp.DataFiltering) - Demonstrates how to use the rule editor as a visual search interface that generates `IQueryable` LINQ queries against an included SQL Server test database in an ASP.NET Core (.NET 8+) web application.

## Code Effects Documentation Repo

- [`Rule.Docs`](https://github.com/codeeffects-software/Rule.Docs) - Official documentation for Code Effects platform. The live, browsable version of this documentation is available at [codeeffects.com/decision-automation](https://codeeffects.com/decision-automation).

## Feedback

Found an error or something unclear? Open an issue in related repo - corrections and suggestions are welcome.

## About Code Effects Software

Code Effects Software has been building business rules automation software since 2009. Our embeddable rules engine is used by organizations across finance, insurance, healthcare, and government to let non-developers manage complex business logic - without waiting on engineering for every rule change.

With the release of [Version 6](https://codeeffects.com/decision-automation/new-features-version-6-business-rules-engine), CodeEffects adds AI/LLM-assisted rule authoring, making it faster than ever for business users to describe rules in plain language and have them translated into working logic.

## Resources

[CodeEffects.com](https://codeeffects.com) · [Docs](https://codeeffects.com/decision-automation) · [NuGet](https://www.nuget.org/packages?q=codeeffects) · [npm](https://www.npmjs.com/package/codeeffects)
