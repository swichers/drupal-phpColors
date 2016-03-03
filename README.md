# Introduction

This module provides composer integration for the phpColors library. The
phpColors library provides an easy-to-use PHP class for dealing with color
manipulation.

## Requirements

* [Composer Manager][1]
* [phpColors][2] (installed via Composer Manager)

## Installation

 1. Install as usual, see http://drupal.org/node/70151 for further information.
 2. Rebuild and install libraries via [Composer Manager][1]
  1. Run `drush composer-json-rebuild`
  2. Run `drush composer-manager update`
  3. Run `drush composer-manager install -o`
  4. See the [composer manager documentation][3] for more information.

## Usage

```php
<?php

use Mexitek\PHPColors\Color;

$my_blue = new Color("#336699");
echo $my_blue->darken();
?>
```

or

```php
<?php

  $my_blue = phpcolors_get_color('#336699');
  echo $my_blue->darken();
?>
```

See [http://mexitek.github.io/phpColors/][2] for more in depth documentation.

[1]: https://www.drupal.org/project/composer_manager
[2]: http://mexitek.github.io/phpColors
[3]: https://www.drupal.org/node/2405805
