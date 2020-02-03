# Commit Message Rules

## Prefixes
Every commit must be prefixed with exactly one of these prefixes, followed by a colon and a single space:
- *STATIC*\
Use for commits that contain only automatically generated files.
- *FEATURE*\
Use for code modifications that add new functionality to a project or modify the bahaviour of existing features (but are not bugfixes.
- *BUGFIX*\
Use for code modifications that fix existing functionality.
- *REFACTOR*\
Use for code modifications that do not change the code's behaviour. This includes code style changes, type error fixes, linter warning fixes and comment improvements.
- *MERGE*\
 Use for merge commits.
- *DOCS*\
 Use for commits that add or improve documentation documents (like the README). This does not include docblocks and exlanatory comments in source code. Those should be commited as REFACTOR.
- *TOOL*\
Use for changes to Makefiles, deployer files, JS build systems etc.
- *TEST*\
Use for commits that only add or modify test classes. Avoid in favour of adding/fixing tests in the corresponding FEATURE or BUGFIX commit.
- *UPGRADE*\
Use for composer/node dependency upgrades.
- *INITIAL*\
Use only for the first commit in a new repository.
