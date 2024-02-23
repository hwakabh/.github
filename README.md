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
  - [`.gitignore`](https://git-scm.com/docs/gitignore) (minimal)
  - [`.gitattributes`](https://git-scm.com/docs/gitattributes)
- GitHub metafiles
  - [`CODEOWNERS`](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners#about-code-owners)

- declarative label presetting
  - [azu@github-label-setup](https://github.com/azu/github-label-setup)
    - CLI tools
    - Require Node.js environment and GitHub Personal Access Token
  - config: `.github/config/label-defaults.json`

- Issue Labeler
  - actions: [github/issue-labeler](https://github.com/github/issue-labeler)
  - config: `.github/config/issue-labels.yaml`
- PR Labeler
  - actions: [actions/labeler](https://github.com/actions/labeler)
  - config: `.github/config/pr-labels.yaml`
- Stale Issue
  - actions: [actions/stale](https://github.com/actions/stale)
- release-please
  - actions: [google-github-actions/release-please-action](https://github.com/google-github-actions/release-please-action)
  - configs:
    - `.release-please-manifest.json`
    - `.github/config/release-please-config.json`

- Semantic PRs
  - config: `.github/semantic.yaml`
  - Require installation of [Semantic PR](https://github.com/apps/semantic-prs) as GitHub Apps
- renovate
  - config: `.github/config/renovate.json`
  - Require installation of [Mend Renovate](https://github.com/apps/renovate) as GitHub Apps

## Workflows
- Triage Issue
- Triage PRs
- Stale Issues
- Release Please

## Caveats
- Replace `GH_USERNAME` and `GH_REPONAME` in CONTRIBUTING.md

## (Optional) Checklist
