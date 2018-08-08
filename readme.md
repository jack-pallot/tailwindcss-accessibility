# Tailwind CSS Accessibility Plugin

A Tailwind CSS plugin that adds additional functionality to help improve accessibility.

### Installing

    npm install tailwindcss-accessibility

or

    yarn add tailwindcss-accessibility


Simply require the installed plugin directly to your Tailwind config:

    plugins: [
      require('tailwindcss-accessibility')
    ]

### Usage

For usage on individual elements:

    <span class="sr-only">
      Screen readers only
    </span>

Use on focused only elements (skip links etc):

    <a class="sr-only sr-only-focusable" href="#content" tabindex="1">
      Skip to main content
    </a>

### Utilities

By default the class utils are taken from Bootstrap 4, a highly battle-tested framework:

    .sr-only {}
    .sr-only-focusable {}

### Contributions

The goal of this project is to be a single source for as many relevant CSS accessibility helpers as possible. If we're missing something, or you would like to contribute, post an issue or PR.