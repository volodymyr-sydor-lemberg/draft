## Draft 1.x.x

- Disable anonymous account creation by default
- Removed *Administration Links Access Filter* module as it has been [merged into Admin Toolbar as a submodule](https://www.drupal.org/project/admin_toolbar/issues/2919346) as of version 1.21.0
- Updated vendor libraries:
    * Admin Toolbar (drupal/admin_toolbar: **^1.21**)
- Removed dev vendor libraries:
    * Devel (drupal/devel)
    * Drupal Console (drupal/console)
    * Drush (drush/drush)

## Draft 1.2.1, 2017-06-28

- Add integration with Travis CI
- Fixed issue with prefixed dependencies for profile, see [this issue on drupal.org](https://www.drupal.org/node/2855026).

## Draft 1.2.0, 2017-06-22

- Added empty Develop configuration split
- Added dependencies on:
    * Administration Links Access Filter (admin_links_access_filter:admin_links_access_filter)
    * Configuration Split (config_split:config_split)
- Added vendor libraries:
    * Administration Links Access Filter (drupal/admin_links_access_filter: **^1.0**)
    * Configuration Split (drupal/admin_links_access_filter: **^1.0**)
    * Drupal Console (drupal/console: **^1.0**)
    * Drush (drush/drush: **^8.1**)
- Make sure that all dependencies are prefixed with the project name
- Added this file

## Draft 1.1.0, 2017-02-08

- Added dependencies on:
    * Block (drupal:block)
    * Internal Dynamic Page Cache (drupal:dynamic_page_cache)
    * Internal Page Cache (drupal:page_cache)

## Draft 1.0.0, 2017-02-07

- Initial release, nothing fancy
