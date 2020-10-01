# New Project Template

This repository contains a template that can be used for a new Widen open
source project.

This template uses the [ISC license](https://choosealicense.com/licenses/isc/).

## How to use this template

If working on a brand new project, one can use the GitHub UI to create a new
repository and use this one as a template. All the files in the `new-project`
will be in your future project.

To do the same locally to a new or existing project:

1. Clone it from GitHub.
1. Create a new local repository or use an existing one
and copy the files from this repo into it.
1. Modify README.md and docs/contributing.md to represent your project.
1. Develop your new project!

``` shell
git clone https://github.com/Widen/new-project
mkdir my-new-thing
cd my-new-thing
git init # if this is a new project
cp -r ../new-project/* ../new-project/.github .
git add *
git commit -a -m 'Boilerplate for new Widen open source project'
```
