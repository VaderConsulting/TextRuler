# TextRuler

C# WinForms rich-text editor demo with a Word-style ruler control. The `TextRuler` UserControl draws a graduated ruler with draggable left indent, hanging indent, right indent, left and right margin, and tab-stop markers, raising events such as `LeftIndentChanging`, `TabAdded`, and `TabRemoved`. `AdvancedTextEditor` wraps an extended `RichTextBox` with a formatting toolbar (bold, italic, underline, strikeout, font picker, open and save) and a Find dialog.

**Source last updated:** 2022-05-01 · **Language:** C# · **Target:** .NET Framework 4.8 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `TextRuler` (`TextRuler/TextRuler.csproj`) | C# | WinForms exe | Ruler UserControl, AdvancedTextEditor, FontComboBox, ExtendedRichTextBox, and Find dialog hosted on Form1 |

## How to open

Open `TextRuler.sln` in Visual Studio and run the `TextRuler` project.

## Requirements

- Visual Studio 2019 or 2022 (solution Format Version 12.00, originally Visual Studio 2013)
- .NET Framework 4.8 Developer Pack

## Attribution and provenance

Original author Andrey Lundin, CodeProject article [Advanced Text Editor with Ruler](https://www.codeproject.com/Articles/22783/Advanced-Text-Editor-with-Ruler) (January 2008, CPOL). `ExtendedRichTextBox.cs` is by Oscar Londono ([MyExtRichTextBox](http://www.codeproject.com/KB/edit/MyExtRichTextBox.aspx), CPOL). AssemblyCompany `Home`; AssemblyCopyright `Copyright © Home 2008`. Working copy from my Development folder `TextRuler`, retargeted to .NET Framework 4.8.

## License

Original license terms apply (Code Project Open License / CPOL). No copyright is claimed over this code by VaderConsulting. See `LICENSE`.
