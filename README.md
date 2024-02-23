# .github
Personal GitHub Repository Scaffolder

## Usages
### as GitHub metafiles
This repository stores [Community Health Files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file#about-default-community-health-files) with builtin feature of GitHub.
With this features, the following [supported files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file#supported-file-types) in this repository will be implicitly applied to ALL of user repository as default.
- `README.md` (this file)
- `CODE_OF_CONDUCT.md`
- `CONTRIBUTING.md`
- Issue Templates: `.github/ISSUE_TEMPLATE/*`
- PR Template: `.github/PULL_REQUEST_TEMPLATE.md`

If you would override above files in specific repository, simply creating file in the repository.
In case you need not to explicitly include above files in your code basis, all you have to do is to fork this repository as you like, which copy GitHub metafiles onto your repository.

### as Repository Templates
Since we can make this repository as public repository templates, you can also levarage with cloning initial files in your repository as well as GitHub metafiles.
So you can easily create your repository from scaffolded files with [creating repository from template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).
For this usage, firstly you have to fork this repository same as above, then create your repository from the forked repository.

If you can successfully create your repository from fork, you can confirm it the descriptions like `generated from ${YOUR_USERNAME}/.github` bottom of the your repository name in code explorer.

## Features
- Git metafiles
  - `.gitignore` (minimal)
  - `.gitattributes
- GitHub metafiles
  - `CODEOWNERS`
- declarative label preset
- Issue Labeler
- PR Labeler
- Stale Issue
- Semantic PR
- release-please
- renovate

## Prerequisites

## Workflows

## Caveats
- Replace `GH_USERNAME` and `GH_REPONAME` in CONTRIBUTING.md

## (Optional) Checklist
