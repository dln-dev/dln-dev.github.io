# dln-dev.github.io
Personal blog about some past and present projects. Mostly Machine Learning and Quantum Computing.

## Workflow
* checkout branch gh-pages
* write article as, e.g., md in content/etc
* `pelican content` in main directory
* `pelican -l` for local testing on localhost:8000
* commit to gh-pages branch
* `ghp-import output` in main directory (pushes changes to main, which holds the static website)
* git push
* wait around 10 minutes and check whether everything worked

