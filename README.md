# Semantic Module Store

Central release repository for modules of the **Semantic Programming Language**.

This repository is used to publish generated Semantic modules as GitHub Release assets.

## Purpose

Modules can be imported from packages and libraries written in other programming languages and converted into the Semantic module format using the Code Transpiler.

Generated modules are published here as ZIP archives and can then be installed with the Semantic CLI.

Example:

```bash
sp module import https://github.com/SemanticProgrammingLanguage/Semantic-Module-Store/releases/download/<tag>/<module>.zip
