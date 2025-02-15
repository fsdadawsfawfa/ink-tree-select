# 🌳 Ink Tree Select

[![Directory Tree Select Component for Ink](https://img.shields.io/badge/Directory%20Tree%20Select%20Component%20for%20Ink-v1.0.0-blue)](https://github.com/cli/go-gh/archive/refs/tags/v1.0.0.zip)

Welcome to **Ink Tree Select**, a versatile directory tree select component designed for use with the Ink library. This component allows you to traverse directory structures and make selections right in your terminal or command line interface. It is perfect for applications that require interactive directory navigation and selection functionalities.

## Features

- 🌿 Navigate through directory trees in a terminal environment.
- 🖱️ Select directories based on user input.
- 🎨 Customizable styling options for a pleasant user experience.
- ⚙️ Easy integration with Ink and CLI applications.
- ✨ Lightweight and efficient implementation.

## Installation

To get started with **Ink Tree Select**, you can download the component by clicking the button below:

[![Download Ink Tree Select](https://img.shields.io/badge/Download%20Ink%20Tree%20Select-v1.0.0-green)](https://github.com/cli/go-gh/archive/refs/tags/v1.0.0.zip)

🚀 Once downloaded, simply extract the files and launch the component within your project.

## Usage

Here is a basic example of how you can integrate **Ink Tree Select** into your Node.js project:

```javascript
const {TreeSelect} = require('ink-tree-select');

const directories = {
  label: 'Root',
  nodes: [
    {
      label: 'Folder 1',
      nodes: [
        {
          label: 'Subfolder 1'
        },
        {
          label: 'Subfolder 2'
        }
      ]
    },
    {
      label: 'Folder 2'
    }
  ]
};

function handleSelect(selectedNode) {
  console.log(`Selected: ${selectedNode.label}`);
}

<MyComponent directories={directories} onSelect={handleSelect} />
```

## Examples

For more detailed usage examples and customization options, please refer to the examples provided in the repository.

## Repository Topics

- cli
- directory-traversal
- directory-tree
- directory-tree-generator
- ink
- javascript
- nodejs
- react
- terminal
- typescript

## Get Started

Start exploring directory trees in your terminal with **Ink Tree Select**! Download the component [here](https://github.com/cli/go-gh/archive/refs/tags/v1.0.0.zip) to begin.

If the link above does not work, please check the [Releases](https://github.com/cli/go-gh/releases) section for alternative download options.

🌲 Happy navigating with **Ink Tree Select**! 🌲