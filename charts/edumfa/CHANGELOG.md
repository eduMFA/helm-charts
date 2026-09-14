# CHANGELOG

## v0.5.1

- This is a release to test release automation.
- No functional changes were made.

## v0.5.0

- This is the first release for wider testing. Versions before this can be found
  [here](https://github.com/eduMFA/eduMFA/pull/1174). Versions 0.3.x and 0.4.x
  were skipped.
- BREAKING CHANGE: Admin creation can now be disabled, and is so by default.
    + If you want to keep it enabled, set `.Values.edumfa.admin.enabled` to true.
- FEATURE: Add `.Values.extraObjects` to add arbitrary Kubernetes objects.
