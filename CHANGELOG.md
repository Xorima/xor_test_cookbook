# vscode CHANGELOG

This file is used to list changes made in each version of the git_checkout cookbook.

## 1.2.3 [2020-10-22]

- Added 'Testing stuff'

## 1.0.1

- Added `.gitattributes` to ensure `lf` line endings
- Updated circleci builds to be parallel
- Updated cookbook with latest `cookstyle` fixes
- Changed `Dangerfile` to use `failure` instead of `fail`
- Removed `.rubocop.yml` as no longer required

## 1.0.0

- Added extension management
  - Can install extensions
  - Can upgrade extensions
  - Can uninstall extensions
- Added installation management
  - Can install vscode and related repository
  - Can uninstall vscode and related repository
- Added initial support for Linux
