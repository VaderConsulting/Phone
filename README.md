# Phone

Phone is a Visual Studio 2008 VB.NET solution with two CallInfo class-library targets, one for .NET Compact Framework 2.0 and one for 3.5. CallInfo2.0 is a Smartphone library (Windows Mobile 5.0 Smartphone SDK, OS 5.1) whose only source type is an empty Class1 stub. CallInfo3.5 is the Pocket PC counterpart (Windows Mobile 5.0 Pocket PC SDK) also containing only a Class1 stub, plus Compact Framework 3.5 references such as System.Core and System.Xml.Linq. Both projects import Microsoft.CompactFramework.VisualBasic.targets.

**Source last updated:** 2010-02-17  
**Language:** VB.NET  
**Target:** .NET Compact Framework 2.0 / 3.5  
**Output:** Class libraries (Smartphone + Pocket PC)

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `CallInfo2.0` | VB.NET | CF 2.0 class library | Empty Class1 stub for Windows Mobile 5.0 Smartphone |
| `CallInfo3.5` | VB.NET | CF 3.5 class library | Empty Class1 stub for Windows Mobile 5.0 Pocket PC |

## How to open

Open `Phone.sln` in Visual Studio 2008 with the Windows Mobile 5.0 Smartphone and Pocket PC SDKs.

## Attribution and provenance

From Dave Robinson's Historical Dev archive (OneDrive folder `Phone`). Assembly company and copyright on both projects are the Visual Studio defaults: Microsoft, Copyright © Microsoft 2010.

## License

MIT License. Copyright (c) 2026 VaderConsulting.
