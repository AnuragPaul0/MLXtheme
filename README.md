# MLXtheme
HTML export of MLX file with theme button using MATLAB.

[Button-Dark.html](https://anuragpaul0.github.io/MLXtheme/Button-Dark.html)

[Fixed-Dark.html](https://anuragpaul0.github.io/MLXtheme/Fixed-Dark.html)

[Button.html](https://anuragpaul0.github.io/MLXtheme/Button.html)

[Fixed.html](https://anuragpaul0.github.io/MLXtheme/Fixed.html)

## Usage

Just replace the adress of the HTML export, as input at the top of the Button.mlx file in matlab.

```
ad = '/MATLAB Drive/MLX.html'
```
A new file MLX-dark.html should be created with the same content with a theme button.

### Content

* `Button-Dark.html` is the `Button.html` with the theme button.
* `Button.html` is the export of `Button.mlx`.
* `Button.mlx` contains the main program, constants and most functions that are used to add the button with its functionality.
&nbsp;
* `Fixed-Dark.html` is the `Fixed.html` with the theme button position fixed.
* `Fixed.html` is the export of `Fixed.mlx`.
* `Fixed.mlx` contains the main program for theme button position fixed, contains most functions that are used to add the button with its functionality.

## Variables:
* `ad`   =  address
* `ans`  =  fwrite(fopen(ad, 'w'),n);    ->    fclose('all');
* `n`    =  editing HTML text string.

## License

MIT License
Copyright (c) 2023 Anurag Paul

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
