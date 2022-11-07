# @pixi/accessibility

SR Version with improvements:

-   HTML Element default is Div, not button
-   Tabindex applied if specified by DisplayObject
-   Non-interactive elements get added to the DOM as well

## Installation

```bash
npm install @pixi/accessibility
```

## Usage

```js
import { AccessibilityManager } from '@pixi/accessibility';
import { extensions } from '@pixi/core';

extensions.add(AccessibilityManager);
```
