# Vue.js Code Style

This code style is derived from the Vue.js official style guide.

## Table of Contents

- [Vue.js Code Style](#vuejs-code-style)
  - [Table of Contents](#table-of-contents)
  - [Naming Conventions](#naming-conventions)
  - [Component Guidelines](#component-guidelines)
  - [Code Formatting](#code-formatting)
  - [Commenting Guidelines](#commenting-guidelines)
  - [Other Guidelines](#other-guidelines)
- [JavaScript Code Style Guidelines](#javascript-code-style-guidelines)
  - [Table of Contents](#table-of-contents-1)
  - [Naming Conventions](#naming-conventions-1)
  - [Formatting](#formatting)
  - [Variables](#variables)
  - [Functions](#functions)
  - [Comments](#comments)

## Naming Conventions

- File names should be in lowercase with hyphen-separated words, e.g., `my-component.vue`.
- Component names should be in PascalCase, e.g., `MyComponent`.
- Prop names should be in camelCase, e.g., `myProp`.

## Component Guidelines

- Component options should be ordered as follows: `name`, `components`, `props`, `data`, `computed`, `watch`, `methods`, `lifecycle hooks`.
- Component options should be organized using single-file components, where the template, style, and logic are in the same file.
- Component templates should use single-line templates or use 4 spaces for indentation.
- Component styles should use scoped styles to avoid style pollution.

## Code Formatting

- Use 2 spaces for indentation.
- Add a space between each attribute in a tag.
- Add a space before the closing bracket of each tag.
- Add a space after the colon in each attribute.
- Use double quotes for attribute values.
- Do not add spaces around the equal sign in attribute values.

## Commenting Guidelines

- Use `<!-- -->` for HTML comments.
- Use `//` for single-line JavaScript comments.
- Use `/* */` for multi-line JavaScript comments.

## Other Guidelines

- Use ES6 module syntax for importing and exporting modules.
- Avoid complex expressions in templates; put complex logic in computed properties or methods.
- Avoid direct DOM manipulation in templates; use Vue directives and event handlers.

These are some basic Vue.js code style guidelines. You can adjust and supplement them based on your specific project requirements and team conventions.

Reference: [Vue.js Style Guide](https://vuejs.org/v2/style-guide/)

------------------------

# JavaScript Code Style Guidelines

These code style guidelines are based on the Airbnb JavaScript Style Guide.

## Table of Contents

1. [Naming Conventions](#naming-conventions)
2. [Formatting](#formatting)
3. [Variables](#variables)
4. [Functions](#functions)
5. [Comments](#comments)

## Naming Conventions

- Use camelCase for variable and function names.
- Use PascalCase for class names.
- Use UPPERCASE for constants.

## Formatting

- Use 2 spaces for indentation.
- Use single quotes for strings unless interpolating variables.
- Use semicolons at the end of statements.
- Use braces for all control structures.

## Variables

- Declare variables at the beginning of the scope.
- Use `const` for variables that do not need reassignment.
- Use `let` for variables that need reassignment.

## Functions

- Use arrow functions for anonymous functions.
- Use function declarations for named functions.
- Use meaningful function and parameter names.

## Comments

- Use `//` for single-line comments.
- Use `/* */` for multi-line comments.
- Write descriptive comments for complex logic.

These guidelines are based on the Airbnb JavaScript Style Guide. Feel free to adjust and supplement them based on your project's requirements and team conventions.

Reference: [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

