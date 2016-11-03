# wordpress46
WordPress 4.6 development project contains the codebase used to test my plugins. Projects is based on WordPress 4.6 core with symbolic links to shared themes and plugins. There are also other third-party plugins used to support my plugins and a "WordPress setup" plugin that is used to create a first setup for themes. It creates a custom taxonomy "genre", a custom post type "book" and contains a set of utility functions used in WordPress theme to test plugin functionalities.

Local environment works on:
* 127.0.0.1	wordpress46.dev

Here the default set of symlinks:
* ln -s ~/Projects/WordPress/Themes/twentysixteen twentysixteen
* ln -s ~/Projects/WordPress/Themes/twentyfourteen twentyfourteen
* ln -s ~/Projects/WordPress/Themes/twentyfifteen twentyfifteen
* ln -s ~/Projects/WordPress/Plugins/amazon-web-services amazon-web-services
* ln -s ~/Projects/WordPress/Plugins/cloud-search/trunk cloud-search
* ln -s ~/Projects/WordPress/Plugins/daily-logo/trunk daily-logo
* ln -s ~/Projects/WordPress/Plugins/picker/trunk picker
* ln -s ~/Projects/WordPress/Plugins/taxonomy-filter/trunk taxonomy-filter
* ln -s ~/Projects/WordPress/Plugins/wordpress-importer wordpress-importer
* ln -s ~/Projects/WordPress/Plugins/wordpress-setup wordpress-setup

First setup:
* cd /var/www/dev/
* git clone git@github.com:andrealandonio/wordpress-46.git wordpress46
* restore database
