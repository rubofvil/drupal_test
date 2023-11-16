# Readme

## Description

Repo to generate a Drupal and CiviCRM to test the "CiviCRM Drupalmodule", "CiviCRM extension", "Drupal module".

## Versions

"Drupal + CiviCRM" versions are defined in the `composer.json` file.

### Tagging

Example: Drupal 9.5 + CiviCRM 5.63 + internal version = `9.5-5.63-0.0.1`

- There is no patch version (only major. minor) the purpose is for the repo is testing, not prod.
- Each time a new tag is created, `composer_install` is executed and created a new zip release.
