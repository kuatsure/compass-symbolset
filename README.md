# Compass Plugin for Symbolset ( DEPRECATED )

I decompassed these files. Please look for Symbolset [sass mixins](https://github.com/kuatsure/symbolset-sass).

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
$use-ss-standard: true; // If you want to use Standard Symbolset
```

## Versions

SS-Standard			=> 1.004

SS-Social-Circle	=> 1.005

SS-Social-Regular	=> 1.005


## Don't forget to ...

Copy the font libraries to your `font_dir`.

Update your js files.

## Contributing

Currently this only supports a small fraction of the available sets from Symbolset. If you could fork and provide the css ( use the `@include font-face()` compass syntax ) to other sets ( one fork per set please :) ), I'd truely apprieciate it. My goal is to have every set available via this gem.

## Thanks
[Compass](http://compass-style.org/) & [Symbolset](https://symbolset.com/)

### Enjoy!
