This module provides library and xautoload integration for the phpColors
library. The phpColors library provides an easy-to-use PHP class for dealing
with color manipulation.

## Requirements

 * [libraries][1]
 * [xautoload][2]
 * [phpColors][3]

## Installation

 1. Install as usual, see http://drupal.org/node/70151 for further information.

 2. Download the phpColors library from http://mexitek.github.io/phpColors/ and
    install into sites/all/libraries/phpcolors.

    `git clone git://github.com/mexitek/phpColors.git sites/all/libraries/phpcolors`

## Usage

```php
<?php

using phpColors\Color;

// Initialize my color.
$my_blue = new Color("#336699");

echo $my_blue->darken();
// 1a334d
?>
```

See http://mexitek.github.io/phpColors/ for more in depth documentation.

[1]: https://drupal.org/project/libraries
[2]: https://drupal.org/project/xautoload
[3]: http://mexitek.github.io/phpColors
