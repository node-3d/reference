# Contributing to Node3D


The following is a set of guidelines for contributing to **Node3D** and its modules,
which are hosted in the [Node3D Organization](https://github.com/node-3d) on GitHub.


#### Table Of Contents

[How Can I Contribute?](#how-can-i-contribute)
  * [Submitting A Bug Report](#submitting-a-bug-report)
  * [Submitting An Enhancement Suggestion](#submitting-an-enhancement-suggestion)
  * [Pull Requests](#pull-requests)

[Styleguides](#styleguides)
  * [Git Commit Messages](#git-commit-messages)
  * [Node3D Styleguide](#node3d-styleguide)


## How Can I Contribute?

Bugs and enhancements are tracked as
[GitHub issues](https://github.com/node-3d/node-3d/issues).
You can also create an issue on a specific repository of
[Node3D]((https://github.com/node-3d)).

### Submitting A Bug Report

Bugs are tracked as [GitHub issues](https://github.com/node-3d/node-3d/issues).
You can also create an issue on a specific repository of
[Node3D]((https://github.com/node-3d)).

* Use a clear and descriptive title.
* Provide examples to demonstrate the problem.
* Explain which behavior you expected to see instead and why.
* If the problem involves a crash, provide its trace log.


### Submitting An Enhancement Suggestion

* Use a clear and descriptive title.
* Describe the desired enhancement.
* Provide specific examples of it being used.


### Pull Requests

* Do not include issue numbers in the PR title.
* Follow the [Node3D Styleguide](#node3d-styleguide).


## Node3D Styleguide


The code must adhere to [Node3D Codestyle](/CODESTYLE.md).


## File System

1. Only lowercase in file/directory names.

1. Words are separated with dashes.

1. Do **not use .npmignore** file, use
	["files"](https://docs.npmjs.com/files/package.json#files)
	package field.

1. If there is an empty directory to be kept, place an empty **.keep** file inside.

1. Use [SemVer](https://semver.org) versioning pattern.


### Git Commit Messages

1. Use the present tense ("Add feature" not "Added feature").

1. Use the imperative mood ("Move cursor to..." not "Moves cursor to...").

1. Limit the first line to 72 characters or less.

1. You can start the commit message with an applicable emoji:
	* :art: `:art:` when improving the format/structure of the code;
	* :racehorse: `:racehorse:` when improving performance;
	* :non-potable_water: `:non-potable_water:` when plugging memory leaks;
	* :memo: `:memo:` when writing docs;
	* :penguin: `:penguin:` when fixing something on Linux;
	* :apple: `:apple:` when fixing something on macOS;
	* :checkered_flag: `:checkered_flag:` when fixing something on Windows;
	* :bug: `:bug:` when fixing a bug;
	* :fire: `:fire:` when removing code or files;
	* :green_heart: `:green_heart:` when fixing the CI build;
	* :white_check_mark: `:white_check_mark:` when adding tests;
	* :lock: `:lock:` when dealing with security;
	* :arrow_up: `:arrow_up:` when upgrading dependencies;
	* :arrow_down: `:arrow_down:` when downgrading dependencies;
	* :shirt: `:shirt:` when removing linter warnings;
