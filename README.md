# 🪐 Martian Finance UIkit

[![Version](https://img.shields.io/npm/v/@marsswap/uikit)](https://www.npmjs.com/package/@marsswap/uikit) [![Size](https://img.shields.io/bundlephobia/min/@marsswap/uikit)](https://www.npmjs.com/package/@marsswap/uikit)

Mars UIkit is a set of React components and hooks used to build pages on Mars's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @marsswap/uikit`

## Setup

### Theme

Before using Mars UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@marsswap/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@marsswap/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://marsswap.github.io/mars-uikit/)