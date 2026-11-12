# Ferrite Engine Support

This repository is the public place to report bugs in the **Ferrite SDK**. It contains no source code, only the issue tracker and this guide.

[Ferrite](https://ferriteengine.com) is a C++ game engine with an in-engine editor, Schematic visual scripting and C# (.NET 10) gameplay code. It is distributed as a prebuilt SDK. Supported platforms:

- Windows (x64 and ARM64)
- Linux, Ubuntu 24.04 or later (x64 and ARM64)
- macOS 14 or later on Apple Silicon (M1 and later; Intel Macs are not supported)

Graphics backends are DirectX 12, Vulkan and Metal. C# projects need the .NET 10 SDK.

## Questions or bugs?

| You want to | Go to |
|---|---|
| Ask a question, get help using Ferrite, discuss ideas | [Discord](https://discord.gg/VE6Q7Vu4mR) |
| Request a feature | [Discord](https://discord.gg/VE6Q7Vu4mR) (feature requests are not tracked as issues here) |
| Report a bug or crash | [New issue](../../issues/new/choose) in this repository |
| Report a security problem | Ask for a private channel on [Discord](https://discord.gg/VE6Q7Vu4mR). **Do not post details publicly.** |

## Before you open an issue

1. Search the [existing issues](../../issues) (open and closed). Add a comment or a reaction if yours is already there.
2. Update to the latest SDK and see whether the problem is still present.
3. Open **one issue per bug**. Separate problems are easier to track and fix.

## What a good bug report contains

- **Ferrite SDK version.** In the editor, open Help > About. The command line tool prints its own version with `ferrite --version`; that is the tool version, so please give the SDK version from the editor as well.
- **Operating system and version**, for example Windows 11 24H2, Ubuntu 24.04, macOS 14.
- **CPU, GPU and graphics driver version.** In the editor, Help > About has a "This Machine" tab with a "Copy as JSON" button; pasting that is ideal.
- **Graphics backend** in use: DirectX 12, Vulkan or Metal.
- **Project type:** Schematic, C#, or both; editor, play-in-editor or a packaged game.
- **What you did**, step by step, starting from a fresh editor session if you can.
- **What you expected** and **what happened instead.**
- **A minimal project or reproduction steps.** The smaller the better. A new project from one of the SDK templates with the smallest change that shows the bug is perfect.
- **Logs.** Attach the editor or game log and the console output around the problem. Please check your log for anything private before posting it.
- **Screenshots or a short video** for anything visual.
- **Crash dump or crash report**, if the editor or game crashed. If it is large, say so in the issue.

## Please do not post

- Licence keys, passwords, tokens or other secrets.
- Private or confidential project content. If you cannot share your project, reduce the problem to a small sample, or ask on Discord.
- Security vulnerabilities (see the table above).

## Licence

The Ferrite SDK is provided under its own licence terms, see https://ferriteengine.com/license.html.
