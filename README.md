<div align="center">
<h1>asdf-crystal</h1>
<span><a href="https://crystal-lang.org">Crystal</a> plugin for asdf version manager</span>
</div>
<hr />

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/asdf-community/asdf-crystal/Main%20workflow?style=flat-square)](https://github.com/asdf-community/asdf-crystal/actions)
[![All Contributors](https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square)](#contributors-)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/github/license/asdf-community/asdf-crystal?style=flat-square&color=brightgreen)](https://github.com/asdf-community/asdf-crystal/blob/master/LICENSE)

## Installation

```
asdf plugin-add crystal https://github.com/asdf-community/asdf-crystal.git
```

## Usage

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to
install & manage versions.

## Useful information

asdf uses the `.tool-versions` for auto-switching between software versions. To
ease migration, you can have it read `.crystal-version` file to find out what
version of Crystal should be used. This only works with the exact version. To do
this, add the following to `~/.asdfrc`:

```
legacy_version_file = yes
```

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/marciogm"><img src="https://avatars1.githubusercontent.com/u/34196389?v=4" width="100px;" alt=""/><br /><sub><b>marciogm</b></sub></a><br /><a href="https://github.com/asdf-community/asdf-crystal/commits?author=marciogm" title="Code">💻</a> <a href="https://github.com/asdf-community/asdf-crystal/commits?author=marciogm" title="Documentation">📖</a> <a href="#maintenance-marciogm" title="Maintenance">🚧</a></td>
    <td align="center"><a href="https://bsky.moe"><img src="https://avatars3.githubusercontent.com/u/38746192?v=4" width="100px;" alt=""/><br /><sub><b>BSKY</b></sub></a><br /><a href="https://github.com/asdf-community/asdf-crystal/commits?author=imbsky" title="Code">💻</a> <a href="https://github.com/asdf-community/asdf-crystal/commits?author=imbsky" title="Documentation">📖</a> <a href="#maintenance-imbsky" title="Maintenance">🚧</a> <a href="#infra-imbsky" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
    <td align="center"><a href="https://github.com/Stanislav-Lapata"><img src="https://avatars1.githubusercontent.com/u/12072329?v=4" width="100px;" alt=""/><br /><sub><b>Stanislav Lapata</b></sub></a><br /><a href="https://github.com/asdf-community/asdf-crystal/commits?author=Stanislav-Lapata" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
