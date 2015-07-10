Provides Letter Avatar integration with Avatar Kit

Copyright (C) 2015 Daniel Phin (@dpi)

# License

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.

# Installation

 1. Enable this module in Drupal
 2. Run `composer drupal-update` from the core/ directory.

## Troubleshooting

### Composer 

See _Composer Manager for Drupal 8_: https://www.drupal.org/node/2405811

 * `composer: command not found`
   If your terminal complains that it is unaware of the `composer` command, you
   must install Composer: https://getcomposer.org/download/
 * `Command "drupal-update" is not defined.`
   If you get this error, run `drush composer-manager-init` in your Drupal
   directory.