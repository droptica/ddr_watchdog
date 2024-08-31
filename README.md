# Droptica’s Drupal Recipes: Watchdog

## Recipe description

This recipe includes improvements for the Watchdog (dblog) module.
The recipe adds views that make browsing system logs more convenient.

The Watchdog Advanced view has more filters than the standard view, such as a user filter to quickly find logs related to a specific user.

The Summary view provides a summary of log types, allowing you to see, for example, how many error logs were recorded in the last 24 hours.
## Installation


```shell

composer require droptica/ddr_watchdog
php core/scripts/drupal recipe recipes/contrib/drupal_recipe_test_03


```

## How to report issues and new features requests

@todo

## Contact

https://www.droptica.com

## Changelog

### 2024-08-31
First version of the recipe.
