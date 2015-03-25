INTRODUCTION
------------

This module provides composer integration for the phpColors library. The
phpColors library provides an easy-to-use PHP class for dealing with color
manipulation.

REQUIREMENTS
------------
composer_manager https://www.drupal.org/project/composer_manager
phpColors http://mexitek.github.io/phpColors

INSTALLATION
------------

 1. Install as usual, see http://drupal.org/node/70151 for further information.

 2. Run `drush composer-manager install -o` or follow the steps from the composer manager project.

USAGE
-----

<?php

use Mexitek\PHPColors\Color;

$my_blue = new Color("#336699");
echo $my_blue->darken();
?>

or

<?php

  $my_blue = phpcolors_get_color('#336699');
  echo $my_blue->darken();
?>

See http://mexitek.github.io/phpColors/ for more in depth documentation.

CONTACT
-------

Current maintainers:
* Steven Wichers (steven.wichers) - http://drupal.org/user/1774136

This project has been sponsored by:
* McMurry/TMG
  McMurry/TMG is a world-leading, results-focused content marketing firm. We
  leverage the power of world-class content — in the form of the broad
  categories of video, websites, print and mobile — to keep our clients’ brands
  top of mind with their customers.  Visit http://www.mcmurry.com for more
  information.
