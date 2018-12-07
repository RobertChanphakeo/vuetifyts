# SPA Template for ASP.NET Core 2.2 with VueJS, Vuetify and TypeScript

This is a modified template based upon official Microsoft.AspNetCore.SpaTemplate::*

## This template has the following changes:

- Migrated to .Net Core 2.2
- Updated NPM packages
- Updated to WebPack 4
- Added Vuetify
- Added Serilog

Other than that it has minor changes to VueJS original files.

## How to install:

Just clone or download this repo, and install as follows:

```
dotnet new --install <path to this template directory>
```
You can see it listed `dotnet new -l` with the shortname `vuetifyts` so in order to create new projects using this template just use that shortname.

```
dotnet new vuetifyts -n myspa -o myspa
cd myspa
dotnet restore
npm install
dotnet run
```
To publish, just as usual: `dotnet publish -c release`