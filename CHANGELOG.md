# Changelog

This file includes a history of past releases. Changes that were not yet added to a release are in the [changelog.d/](./changelog.d) folder.

<!--
⚠️ DO NOT ADD YOUR CHANGES TO THIS FILE! (unless you want to modify existing changelog entries in this file)
Changelog entries are managed by scriv. After you have made some changes to this plugin, create a changelog entry with:

    scriv create

Edit and commit the newly-created file in changelog.d.

If you need to create a new release, create a separate commit just for that. It is important to respect these
instructions, because git commits are used to generate release notes:
  - Modify the version number in `__about__.py`.
  - Collect changelog entries with `scriv collect`
  - The title of the commit should be the same as the new version: "vX.Y.Z".
-->

<!-- scriv-insert-here -->

<a id='changelog-16.0.2'></a>
## v16.0.2 (2023-11-08)

- [BugFix] Corrected variable name for installing pip extra requirements. (by @Faraz32123)

<a id='changelog-16.0.1'></a>
## v16.0.1 (2023-10-24)

- [BugFix] Reorder staticfiles command in Dockerfile to resolve the Missing staticfiles manifest entry for 'bundles'. (by @hinakhadim)

<a id='changelog-16.0.0'></a>
## v16.0.0 (2023-06-15)

- [Improvement] Add a scriv-compliant changelog. (by @regisb)

- 💥[Feature] Upgrade to Palm. (by @Faraz32123)

## Version 14.0.0 (2022-09-15)

* general production release for nutmeg.master

## Version 0.0.3 (2022-09-14)

* bump to nutmeg.master
* rebuild Dockerfile based on openedx and license_manager

## Version 0.0.2 (2022-09-13)

* run user sync after migrations
* remove any parameters that can be defaulted with existing Tutor params
* create_dot_application(s)
* set ALLOWED_HOSTS and SECRET_KEY


## Version 0.0.1 (2022-05-28)

**Experimental. Do not use in production.**

* Initial Git import
