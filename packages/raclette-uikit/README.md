# 🥞 Raclette UIkit

[![Version](https://img.shields.io/npm/v/@racletteswap-libs/uikit)](https://www.npmjs.com/package/@racletteswap-libs/uikit) [![Size](https://img.shields.io/bundlephobia/min/@racletteswap-libs/uikit)](https://www.npmjs.com/package/@racletteswap-libs/uikit)

Raclette UIkit is a set of React components and hooks used to build pages on Raclette's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @racletteswap-libs/uikit`

## Setup

### Theme

Before using Raclette UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@racletteswap-libs/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@racletteswap-libs/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

## How to use the UIkit

If you want to use components from the UIkit, check the [Storybook documentation](https://racletteswap.github.io/raclette-uikit/)
