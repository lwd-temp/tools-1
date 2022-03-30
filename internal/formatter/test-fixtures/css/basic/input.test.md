# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/formatter/index.test.ts --update-snapshots` to update.

## `css > basic`

### `Diagnostics`

```

```

### `Input`

```css
.a {
	text-decoration: none;
}

span.something {
	margin-bottom: 2px;
}

#id .class:hover {
	background-color: red;
}

h1::before  {
  content: " content ";
}

a {
	transition: background-color 0.3s ease-in-out;
}

```

### `Output`

```css
.a {
	text-decoration: none;
}

span.something {
	margin-bottom: 2px;
}

#id .class:hover {
	background-color: red;
}

h1::before {
	content: " content ";
}

a {
	transition: background-color 0.3s ease-in-out;
}

```