# Compass Plugin for Symbolset

*Keep in mind you'll need to buy the font libraries from Symbolset for this plugin to be of any use to you and your project*

## Install via [Rubygems](https://rubygems.org/gems/compass-symbolset-plugin)
```bash
$ gem update --system

$ gem install compass-symbolset-plugin
```

## Usage
Add the following to your `config.rb` in your compass project
```rb
require 'compass-symbolset'
```

Import it in your `.scss` file.
```scss
@import 'compass-symbolset'
```

### Triggers ( new )

In your `.scss` file that imports the stylesheets, we now use sass variable triggers. All styles are off by default. Turn them on by switching the variable.

```scss
$use-standard: true; // If you want to use Standard Symbolset
```

## Versions

SS-Standard			=> 1.004

SS-Social-Circle	=> 1.005

SS-Social-Regular	=> 1.005


## Don't forget to ...

Copy the font libraries to your `font_dir`.

Update your js files.

### Enjoy!

Currently only supports the Standard & Social ( Regular & Circle ) libraries.

## Thanks
[Compass](http://compass-style.org/) & [Symbolset](https://symbolset.com/)
