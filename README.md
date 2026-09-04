# glib-sharp-master

**Source last updated:** 2026-04-03

GLibSharp is a C# wrapper for the GLib library, kept as a Dave Robinson working copy of third-party GtkSharp / glib-sharp sources. The tree is a .NET Standard 2.0 project under Source/Libs/GLibSharp; the gapi submodule is recorded in .gitmodules but was not present in this zip. Original authors include Mike Kestner, Novell, and later GtkSharp contributors.

**Language:** C#  
**Target:** .NET Standard 2.0  
**Output:** Class library (GLibSharp)

## What it is

GLibSharp is a C# wrapper for the GLib library, kept as a Dave Robinson working copy of third-party GtkSharp / glib-sharp sources. The tree is a .NET Standard 2.0 project under Source/Libs/GLibSharp; the gapi submodule is recorded in .gitmodules but was not present in this zip. Original authors include Mike Kestner, Novell, and later GtkSharp contributors.

## Solution structure

| Project | Language | Path |
|---------|----------|------|
| `GLibSharp` | C# | `Source/Libs/GLibSharp/GLibSharp.csproj` |

## How to open

Open `Source/Libs/GLibSharp/GLibSharp.csproj` in Visual Studio or `dotnet build` that project. The csproj also compiles files from the missing `Source/Tools/gapi` submodule.

## Requirements

- netstandard2.0

## Attribution and provenance

- Third-party GtkSharp / glib-sharp working copy (see `THIRD_PARTY_NOTICES.md`).
- Source headers name Mike Kestner, Novell, Inc., and Andres G. Aragoneses among others.
- Package metadata points at https://github.com/GtkSharp/GtkSharp
- Submodule: `Source/Tools/gapi` → https://github.com/glib-sharp/gapi

## License

Original LGPL v2.0 terms from GtkSharp / gtk-sharp. See `LICENSE` and `THIRD_PARTY_NOTICES.md`. Dave Robinson additions, if any, are a working copy of that third-party tree and are not re-licensed as MIT.
