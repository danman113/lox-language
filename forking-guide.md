# Forking Guide

One of my favorite things about Crafting Interpreters is how it encourages readers to create their own flavor of lox. As such, it's basically impossible that `lox-language` will be able to fulfill the needs of all Lox Implementers (loxers?). If you're one of those people, you're at the right place! This page will guide you through creating a VSCode plugin for your own personal flavor of Lox.


## Creating the VSCode Plugin
There are two ways to go about creating your own VSCode Plugin:
1. Clone the `lox-language` repository. This is recommended if you want to spend most of your time working on your _language implementation_ rather than the _VSCode plugin for your language implementation_.
2. Create your own VSCode Plugin using the [VSCode Syntax Highlighter Guide](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide). It's a great tutorial but may be overkill if you just want to add a few keywords.

## Installing Your Plugin and Inspecting Scopes
*TODO*: Add instructions on how to install the cloned plugin, and high-level explain how VSCode syntax highlighting/scoping works.

## Updating tmLanguage.json
*TODO*: Explain how tmLanguage.json typically works. Go through adding an `import` keyword as an example