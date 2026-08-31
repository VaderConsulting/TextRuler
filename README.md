> **Attribution:** Based on work by **Andrey Lundin** ([Advanced Text Editor with Ruler](https://www.codeproject.com/Articles/22783/Advanced-Text-Editor-with-Ruler), CodeProject 2008, CPOL). See [LICENSE](LICENSE) for details.

# TextRuler

A .NET Framework 4.8 Windows Forms application demonstrating a rich-text editor paired with a fully interactive **Word-style ruler control**.

**Source last updated:** 2015-02-04

**Initiated:** 2015-02-10 · **Framework:** .NET Framework 4.8 · **Solution:** `TextRuler.sln`

---

## Overview

Provides the building blocks for a document editor with the familiar ruler bar found in word processors. The ruler supports draggable left indent, hanging indent, right indent, left margin, right margin, and tab-stop markers.

---

## Components

### TextRuler (user control)

Custom `UserControl` rendering a graduated ruler with draggable handles:

| Handle | Event raised |
|--------|-------------|
| Left indent (upper) | `LeftIndentChanging` |
| Left hanging indent (lower) | `LeftHangingIndentChanging` |
| Right indent | `RightIndentChanging` |
| Left margin | `LeftMarginChanging` |
| Right margin | `RightMarginChanging` |
| Tab stops | `TabAdded` / `TabChanged` / `TabRemoved` |

### AdvancedTextEditor (user control)

`RichTextBox` wrapper with formatting toolbar: Bold, Italic, Underline, Strikeout, Font selector, File open/save.

---

## Project Structure

```
TextRuler/
+-- ExtendedRichTextBox.cs
+-- TextRulerControl/TextRuler.cs          # Ruler user control
+-- AdvancedTextEditorControl/
|   +-- AdvancedTextEditor.cs
|   +-- FontComboBoxControl/FontComboBox.cs
+-- Dialogs/dlgFind.cs
```