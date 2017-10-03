# Drupal-8-Bootstrap-Sass-Patch
Automatically add bootstrap sass theme with Drush

Download the patch into your Drupal 8 Bootstrap theme folder.

Apply the patch with the command:

patch -p1 < path/file.patch

Go to your sites/sitename folder or sites if you have only 1 website

Use Drush to create a new bootstrap sass subtheme with the command:

drush bsass [theme-name]

example:

drush bsass mynewtheme

This will setup the new theme with the name provided.
