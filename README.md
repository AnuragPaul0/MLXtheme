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

* `Fixed-Dark.html` is the `Fixed.html` with the theme button position fixed.
* `Fixed.html` is the export of `Fixed.mlx`.
* `Fixed.mlx` contains the main program for theme button position fixed, contains most functions that are used to add the button with its functionality.

## Variables:
* `ad`   =  address
* `ans`  =  fwrite(fopen(ad, 'w'),n);    ->    fclose('all');
* `n`    =  editing HTML text string.
