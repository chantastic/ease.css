## Why

This is a prototyping tool. I can never remember how to define these and I want
them available in an HTML prototype.

## Installation

#### Prototype install

```html
<link rel="stylesheet" href="http://chantastic.s3.amazonaws.com/ease.0.1.0.css" />
```

#### NPM

```bash
npm install ease.css
```

#### Bower

```bash
bower install ease.css
```

## Use

Write your transition styles as normal:

```css
.my-element {
  transition: all .3s;
}
```

In your markup use your class and the name of the transition timing function
you'd like to see applied.

```html
<div class="my-element ease-in-quart">
  ...
</div>
```

The class-based transition timing function will override the one set in your
class.

## Animations

```css
ease-in-quad
ease-in-cubic
ease-in-quart
ease-in-quint
ease-in-sine
ease-in-expo
ease-in-circ
ease-in-back
ease-out-quad
ease-out-cubic
ease-out-quart
ease-out-quint
ease-out-sine
ease-out-expo
ease-out-circ
ease-out-back
ease-out-quad
ease-out-cubic
ease-in-out-quart
ease-in-out-quint
ease-in-out-sine
ease-in-out-expo
ease-in-out-circ
ease-in-out-back
```
