# @alejyoo000/rules

> Unified code style configurations for modern JavaScript/TypeScript projects

## Overview

Centralized, production-ready configurations for **Biome**, **TypeScript**. One package, consistent code everywhere.

## Installation

```bash
npm install -D @alejyoo000/rules
# or
pnpm add -D @alejyoo000/rules
# or
yarn add -D @alejyoo000/rules
```

## Usage

### Biome

```json
{
  "extends": ["@alejyoo000/rules/biome"]
}
```

### TypeScript

```json
{
  "extends": "@alejyoo000/rules/typescript",
  "include": ["src"],
  "compilerOptions": {
    "outDir": "dist"
  }
}
```

## Features

- 🎯 **Zero config** - Sensible defaults out of the box
- 🔒 **Type-safe** - Strict TypeScript configuration
- ♿ **Accessible** - Built-in a11y rules
- ⚡ **Fast** - Optimized for performance
- 🎨 **Consistent** - Unified style across tools

## What's included

- **Biome**: Formatting + Linting + Import sorting
- **TypeScript**: Strict type checking + Modern features
