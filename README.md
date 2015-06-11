Composer Platform Support Module
================================

This module allows [Composer Manager][] to work correctly on a [Drupal Composer][]
platform. When Composer Manager generates a `composer.json` file for a site, any projects
whose dependencies are required by the platform's `composer.json` are filtered out. Those
dependencies will still appear in the Composer Manager administrative interface but they
are not in the site's `composer.json` file.

Extras
------

* Rewrite URL for AJAX statistics front controller to be in web root.

[Composer Manager]: https://www.drupal.org/project/composer_manager
[Drupal Composer]: https://github.com/drufony/drupal-skeleton
