---
title: Blur Reveal
description: A component to smoothly blur fade in content.
---

::ComponentLoader{label="Preview" componentName="BlurRevealDemo" type="examples"}
::

## API

| Prop Name  | Type     | Default | Description                                                                  |
| ---------- | -------- | ------- | ---------------------------------------------------------------------------- |
| `duration` | `number` | `1`     | Duration of the blur fade in animation.                                      |
| `delay`    | `number` | `1`     | Delay between child components to reveal                                     |
| `blur`     | `string` | `10px`  | Amount of blur to apply to the child components.                             |
| `yOffset`  | `number` | `20`    | Specifies the vertical offset distance (yOffset) for the entrance animation. |

## Component Code

You can copy and paste the following code to create these components:

::CodeViewer{filename="BlurReveal.vue" language="vue" componentName="BlurReveal" type="ui" id="blur-reveal"}
::

## Credits

- Credits to [Magic UI](https://magicui.design/docs/components/shine-border) for this fantastic component.
