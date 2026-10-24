# 🚀 harbour-minigui-doc-extension

🌐 **Select Language:** 
[![English](https://shields.io)](#) · [![Español](https://shields.io)](README.es.md)

---

An enhanced **Visual Studio Code** extension that improves support for the **Harbour** and **xHarbour** programming languages, originally based on the excellent work by Antonino Perricone (`harbourCodeExtension`).

---

## ✨ Main Features

### 🌟 Newly Added Features
* **MiniGUI Extended Support:** Autocomplete, syntax highlighting, and specific tools for development with the MiniGUI Extended graphical library.
* **harbour-doc Documentation System:** Full support and formatting for documentation comments in the `harbour-doc` style (fully compatible with the **Javadoc** format).

### 🛠️ Features Inherited from the Original Extension
* **Syntax Highlighting:** Robust configuration in collaboration with Edgard Lorraine Messias.
* **Debug Support:** Tools to debug your code directly.
* **Diagnostic Info:** Real-time error validation.
* **Document Symbol Provider:** Quick access by pressing `CTRL + SHIFT + O` (or `CTRL + P` then `@`).
* **Workspace Symbol Provider:** Global access by pressing `CTRL + T` (or `CTRL + P` then `#`).

---

## ⚙️ Extension Settings

This extension contributes the following settings to VS Code:

* `harbour.validating`: Enable/disable validation every time you open or save Harbour files.
* `harbour.compilerExecutable`: Full path to the Harbour compiler executable (necessary if automatic validation fails).
* `harbour.extraIncludePaths`: Additional paths to look for header files (`.ch` / `.h`) to avoid file not found errors.
* `harbour.extraOptions`: Extra parameters or options to pass directly to the Harbour compiler.
* `harbour.warningLevel`: Sets the warning level for code validation.
* `harbour.decorator`: If set to `true`, enables visual decoration of corresponding blocks (`if/endif`, `for/next`, `while/endwhile`, etc.).

---

## 🐞 How to Use the Debugger?

You can run the **"Harbour: Get debugger code"** command to get the debugger source code. Save the output to a file (for example, `dbg_lib.prg`). 
* You can include this file directly in your project.
* **RECOMMENDED:** Compile this file as an external library and link it in your project configuration files.

> ⚠️ **Important Note:** Always remember to compile your Harbour files using the `-b` parameter to include debugging information.

---

## 📜 Credits, License, and Acknowledgments

This project is distributed under the **MIT License**. 

This extension is an enhanced fork that extends the original code created by **Antonino Perricone** (`APerricone/harbourCodeExtension`). We greatly appreciate his initial contribution and that of all the collaborators of the base project.
