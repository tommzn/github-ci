![GitHub release (latest by date)](https://img.shields.io/github/v/release/tommzn/github-ci)

# GitHub Actions, Reusable Workflows
This repository provides reusable workflows for Github actions to other projects.

## List of workflow

### create.release.yml
This workflow is used for this repo to create a release after a new semantic tag has been pushed.  
[create.release.yml](https://github.com/tommzn/github-ci/blob/main/.github/workflows/create.release.yml)

### go.image.build.yml
a workflow to run Golang tests, compile a binary (amd64), build an image and push it to Github registry.  
[go.image.build.yml](https://github.com/tommzn/github-ci/blob/main/.github/workflows/go.image.build.yml)