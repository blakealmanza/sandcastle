---
name: pre-release
description: "Run a series of pre-release checks on the repo."
disable-model-invocation: true
---

Check all of the files in the `.changeset` directory.

For the changesets as a whole, check the following:

- Each changeset should be about a user-facing feature. Internal refactors or things that don't affect users should not be added as changesets.
- Related changes should be grouped under a single changeset.

Once done, commit your changes.
