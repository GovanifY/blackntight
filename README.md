# BlacknTight Theme for Hugo

Based of Base16, check [here](https://govanify.com) for a visual.  
## Installation

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/htdvisser/hugo-base16-theme.git base16

See [the Hugo documentation](http://gohugo.io/themes/installing/) for more information.

## Extra Features

### Syntax highlighting

This theme has support for `highlight` shortcode (with Pygments),
see [the Hugo documentation](http://gohugo.io/extras/highlighting/) for more information.

To use this feature install Pygments (`pip install Pygments`) and add `pygmentsuseclasses = true` to your `config.toml`.

### Figure shortcode

Use the `figure` shortcode if you want nice rendering of pictures, see [the Hugo documentation](http://gohugo.io/extras/shortcodes/) for more information.


## Customization

You probably want to edit the homepage. Get started by copying the supplied homepage to your own site.

    $ mkdir -p layouts/partials
    $ cp themes/base16/layouts/partials/hero.html layouts/partials/hero.html

After this, you can edit `layouts/partials/hero.html` and make it awesome.


## License

MIT Licensed, see [LICENSE](https://github.com/GovanifY/blackntight/blob/master/LICENSE).


