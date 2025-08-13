# {{ repository_name }}
Note: This file is expected to generate from template. See [.github wiki](https://github.com/hwakabh/.github/wiki) for detailed instructions.

## Templating checklists
- [ ] Replace `{{ repository_name }}` as placeholder text above with your repository name
- [ ] Initialize repository configs with [`repooster`](https://github.com/hwakabh/repooster) command
- [ ] Initialize default labels with [`github-label-setup`](https://github.com/azu/github-label-setup) command
- [ ] Update `release-type` in [`.github/config/release-please-config.json`](./.github/config/release-please-config.json) (default: `simple`)
  - See more in documents of [release-please](https://github.com/googleapis/release-please?tab=readme-ov-file#strategy-language-types-supported)
- [ ] Validate repository access of [semantic-prs](https://github.com/Ezard/semantic-prs) GitHub Apps, whose configurations exists [`.github/semantic.yml`](./.github/semantic.yml)
- [ ] Validate `Allow GitHub Actions to create and approve pull requests` as Workflow Permision in repository settings
  - release-please requires permission to raise PR with your repository and for this you need to update workflow permission in your repository settings
<!-- GitHub's Community Health files -->
- [ ] Add `LICENSE` file to your project
  - See more details in [GitHub Official Docs](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository)
- [ ] Replace `GH_USERNAME` and `GH_REPONAME` in [CONTRIBUTING.md](.github/CONTRIBUTING.md)
- [ ] Adjust `.github/CODEOWNERS`
  - See its syntax in [GitHub Official Docs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners)
- [ ] Adjust in [CITATION.cff](./CITATION.cff)
  - See more details about Citation File Format in [GitHub documents](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-citation-files) and [official repository](https://github.com/citation-file-format/citation-file-format/blob/main/README.md)

Then, you can clean texts above in this section and update with any of descriptions for your project!
The following headers are skeletons of basic README.

<!-- *** -->
## Local Setup
Makefile, docker-compose, ...etc

<!-- *** -->
## Configurations
Environmental Variables, ...etc

<!-- *** -->
## Good to know / Caveats
Anything if you have
