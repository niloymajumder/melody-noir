# Melody Noir

Melody Noir is a calm, cinematic dark theme inspired by the mood and melody of a Patrick Watson song [Melody Noir](https://www.youtube.com/watch?v=MF-6mBuSGos&list=RDMF-6mBuSGos&start_radio=1), crafted for distraction-free coding.

## Theme Preview

![Theme Preview](./images/preview.png)

## > Features

- Soft, desaturated syntax colors
- High contrast with low visual noise
- Carefully tuned UI & terminal colors
- Designed for long coding sessions

## > Installation

To install the Melody Noir theme directly from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=bluefloyd.melody-noir):

1. Open the **Extensions** sidebar in VS Code (`Ctrl+Shift+X` / `Cmd+Shift+X`).
2. Search for **`Melody Noir`**.
3. Click **Install**
4. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`).
5. Type **`Preferences: Color Theme`** and select it.
6. Choose **`Malachite Starship`** (crruent theme accent) from the list.

## > Manual Installation

1. Download the latest `.vsix` file from [Releases](https://github.com/niloymajumder/melody-noir/releases)
2. In VS Code, go to **Extensions** → **...** → **Install from VSIX**
3. Select the downloaded file

## > Color Palette

| Color           | Hex       | Usage                              |
| --------------- | --------- | ---------------------------------- |
| Primary Green   | `#4BD289` | Functions, strings, active elements|
| Secondary Green | `#2DD17E` | Highlight, success states          |
| Lime Accent     | `#D6F65C` | Numbers, constants, warnings       |
| Teal            | `#016E7F` | Types, classes, UI accents         |
| Dark Teal       | `#014651` | Keywords, storage                  |
| Background      | `#1A2324` | Main editor background             |
| Sidebar         | `#0F1819` | Side panels                        |
| Text            | `#E6F2F2` | Primary text                       |
| Muted Text      | `#8AB3B6` | Secondary text                     |
| Comments        | `#5A7A7F` | Comments, disabled text            |
| Error           | `#FF8C8C` | Errors, deletions                  |
| Warning         | `#D6F65C` | Warnings                           |

## > Customization

If you want to customize the theme:

1. Install the theme
2. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
3. Type `Preferences: Open Settings (JSON)`
4. Add your customizations:

```json
{
  "workbench.colorCustomizations": {
    "[Melody Noir]": {
      "activityBar.background": "#your-color",
      "editor.background": "#your-color"
    }
  }
}
```

## > Bug Reporting & Contributions

<!-- [github-only] -->
**Early Release Status:**
This is a new theme in its initial release. While I thoroughly tested, some visual bugs or incomplete syntax highlighting may exist. If you notice any visual issues, bugs, or have suggestions for improvement, please let us know.

- **Report a bug**: Please open an [issue on GitHub](https://github.com/niloymajumder/melody-noir/issues)
- **Contribute a fix**: If you're comfortable with code, feel free to submit a pull request (PR) with your proposed changes.

Your feedback is essential for improving the theme!

<!-- [/github-only] -->