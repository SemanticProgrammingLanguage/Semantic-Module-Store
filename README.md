# Semantic Module Store

Central release repository for modules of the **Semantic Programming Language**.

This repository is used to publish generated Semantic modules as GitHub Release assets.

## Purpose

Modules can be imported from packages and libraries written in other programming languages and converted into the Semantic module format using the Code Transpiler.

Generated modules are published here as ZIP archives and can then be installed with the Semantic CLI.

Example:

```bash
sp module import https://github.com/SemanticProgrammingLanguage/Semantic-Module-Store/releases/download/<tag>/<module>.zip
Module Registry

The public module registry is maintained separately in the Semantic Programming Language website repository.

The registry contains only:

{
  "name": "ModuleName",
  "url": "https://github.com/SemanticProgrammingLanguage/Semantic-Module-Store/releases/download/<tag>/<module>.zip"
}
Releases

Each generated module is published as a GitHub Release.

A release may contain:

the Semantic module archive
a .smod manifest
imported source files
Semantic artifacts
optional README files
optional license files
optional icons
Automation

Modules can be generated automatically through GitHub Actions.

The workflow:

builds the latest Code Transpiler
imports a package from another language ecosystem
creates a Semantic module
packages it as a ZIP archive
publishes it as a release in this repository
updates the public Semantic Module Store registry
Code Transpiler

The module generation process uses:

github.com/tarekwasfy01/Code-Transpiler

Semantic Programming Language

Main project:

github.com/tarekwasfy01/Semantic-Programming-Language

Website:

https://www.semantic-programming-language.com/

Semantic Programming Language

Code with meaning.
