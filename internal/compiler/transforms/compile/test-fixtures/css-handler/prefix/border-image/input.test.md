# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/transforms/compile/index.test.ts --update-snapshots` to update.

## `css-handler > prefix > border-image`

### `Diagnostics`

```css

```

### `Input`

```css
.style {
	border-image: none;
}

```

### `Output`

```css
.style {
	-moz-border-image: none;
	-webkit-border-image: none;
	-o-border-image: none;
	border-image: none;
}

```