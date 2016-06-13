# Standardized Commit Messages

A tool to aid in standardizing commit messages. Based on this wonderful emoji based [standard Git Commit Message format by @slashsBin](https://github.com/slashsBin/styleguide-git-commit-message).

## Setup

- Clone the repo
- Run `composer install`
- Set Git's file editor to use the included `bin/commit` with something like `export GIT_EDITOR=/your/path/to/commit-repo/bin/commit`

## Known issues
- The 80 character limit of the subject line is not enforced.
- Editing existing messages is not supported. Probably best to pop open an actual editor for this use case.

## Copyright
The smacme/commit library is copyright © Jake A. Smith and licensed for use under the MIT License (MIT). Please see LICENSE for more information.
