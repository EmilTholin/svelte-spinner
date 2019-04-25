[![npm][npm]][npm-url]

<img src="Logotype Primary.png" alt="Svelte Spinner" width="40%" height="40%" />

A Svelte SVG loading spinner.

## Install

```bash
npm install --save svelte-spinner
```

## Example

Look at the [example folder][example-folder-url] for a basic working example.

## Usage

```html
<!-- App.html -->
<Spinner
  size="50"
  speed="750"
  color="#A82124"
  thickness="2"
  gap="40"
/>

<script>
  import Spinner from 'svelte-spinner';
</script>
```

## API

The spinner component is the only export of the module.

```javascript
import Spinner from 'svelte-spinner';
```

###### Properties

| Property    | Default Value       | Description                                                                  |
| :---------- | :------------------ | :--------------------------------------------------------------------------- |
| `size`      | `25`                | The height and width of the SVG spinner.                                     |
| `speed`     | `750`               | How many milliseconds it will take for the spinner to complete one rotation. |
| `color`     | `'rgba(0,0,0,0.4)'` | The color of the spinner.                                                    |
| `thickness` | `2`                 | The thickness of the spinner.                                                |
| `gap`       | `40`                | How many percent of the spinner that will not be filled.                     |

[npm]: https://img.shields.io/npm/v/svelte-spinner.svg
[npm-url]: https://npmjs.com/package/svelte-spinner
[example-folder-url]: https://github.com/EmilTholin/svelte-spinner/tree/master/example
