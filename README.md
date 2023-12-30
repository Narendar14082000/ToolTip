Certainly! It seems like you've got a straightforward task at hand. Here's a simple template for your README.md file:

```markdown
# Tooltip Component

A simple React tooltip component that displays a tooltip when hovering over a button. The tooltip position can be customized based on the provided options: "top", "bottom", "right", or "left".

## Demo

![Tooltip Demo](link/to/demo/gif)

[Live Demo](https://keen-pegasus-610bd5.netlify.app/)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Props](#props)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Installation

```bash
npm install @your-namespace/tooltip-component
```

## Usage

Import the Tooltip component and use it in your React application.

```jsx
import Tooltip from '@your-namespace/tooltip-component';

// ...

<Tooltip position="top">
  <button>Hover me</button>
</Tooltip>
```

## Props

### `position` (string, required)

Specifies the position of the tooltip. Options: "top", "bottom", "right", "left".

## Examples

```jsx
<Tooltip position="top">
  <button>Top Tooltip</button>
</Tooltip>

<Tooltip position="bottom">
  <button>Bottom Tooltip</button>
</Tooltip>

<Tooltip position="right">
  <button>Right Tooltip</button>
</Tooltip>

<Tooltip position="left">
  <button>Left Tooltip</button>
</Tooltip>
```
