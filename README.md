# Box Image Picker

[![release](https://img.shields.io/github/release/jeffbocala/box-image-picker.svg)](https://github.com/jeffbocala/box-image-picker/releases)
[![release](https://img.shields.io/github/license/jeffbocala/box-image-picker.svg)](https://github.com/jeffbocala/box-image-picker/blob/master/LICENSE)

*Turn a simple `<select>` element into an Image Picker* 🖼

![Box Image Picker Example](https://imgur.com/S90ChU4.png)

## Installation

Just add the js & css files

```html
<link rel="stylesheet" href="dist/box-image-picker.css" />
<script src="dist/box-image-picker.js"></script>
```

## Usage

In your HTML file add your `<select>` element:
```html
<select id="imagepicker">
    <option value="image1" data-img-src="image1.jpg">Image 1</option>
    <option value="image2" data-img-src="image2.jpg">Image 2</option>
    <option value="image3" data-img-src="image3.jpg">Image 3</option>
    <option value="image4" data-img-src="image4.jpg">Image 4</option>
</select>
```

And then in your JS file, add:
```javascript
var imagepicker = new BoxImagePicker('#imagepicker', {
    // options
});
```

## Options

| Option | Default | Description |
|---|---|---|
| `hide_select` | `true` | Hide the original `<select>` element. |
| `box_size` | `150` | The width & height of each box. |
| `spacing` | `5` | Padding in between the boxes. |
| `border_size` | `5` | The border width of the selected box. |

## Methods

| Method | Arguments | Description |
|---|---|---|
| `getSelected` | `-` | Get the `index` and `value` of the selected image. |


## Development

Feel free to implement anything from the roadmap, submit pull requests, create issues, discuss ideas or spread the word.

Add Box Image Picker to your dev folder:
```bash
$ git clone git@github.com:jeffbocala/box-image-picker.git
```

Install dependencies (make sure you have yarn):
```bash
$ yarn install
```

To build your changes:
```bash
$ yarn build
```

or you can watch for changes using:
```bash
$ yarn watch
```

After `git add`-ing commit your changes using:
```bash
$ yarn commit
```

**DO NOT USE** `git commit`.

## Credit

Thanks for inspiration : https://github.com/rvera/image-picker

Built with ❤️ by [Jeff Bocala](https://jeffbocala.com)

