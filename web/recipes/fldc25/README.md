To run the recipe run.

ddev drush site-install --existing-config
ddev ssh
php core/scripts/drupal recipe recipes/fldc25 -vvv
ddev drush cr
ddev drush --uid=4 uli
