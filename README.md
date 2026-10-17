# repo-manage-util

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/repo-manage-util) [![KDE Eco](https://img.shields.io/badge/KDE%20Eco-certified-brightgreen?logo=kde&logoColor=white&style=flat-square)](https://eco.kde.org/) [![Blue Angel](https://img.shields.io/badge/Blue%20Angel-DE--UZ%20215-0055a4?style=flat-square)](https://www.blauer-engel.de/en/certification/criteria)


<!-- AI:start:what-it-does -->
_Description pending._
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/repo-manage-util.git
cd repo-manage-util
```

## Usage


```bash
repo-manage-util --profile <PROFILE> [COMMAND]
```

**Available Commands:**

| Command             | Description                                                              |
| ------------------- | ------------------------------------------------------------------------ |
| `reset`             | Resets the repository.                                                   |
| `update`            | Updates the repository.                                                  |
| `sync`              | Syncs repository with the reference repository.                          |
| `move-pkgs-to-repo` | Moves packages from the current directory to the repository.             |
| `move-pkgs`         | Moves packages from one repository to another repository.                |
| `is-pkgs-up-to-date`| Checks if the packages in the repository are up-to-date.                 |
| `cleanup-backup-dir`| Cleans up the backup directory.                                          |

**Example:**

```bash
# Update the repository defined in the 'myrepo' profile
repo-manage-util --profile myrepo update
```

For comprehensive usage instructions and examples, please refer to the **Usage** section in the main documentation (available after installation using `repo-manage-util --help`).

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
_CI documentation pending._
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/repo-manage-util`](https://github.com/Interested-Deving-1896/repo-manage-util) and mirrored through:

```
Interested-Deving-1896/repo-manage-util  ──►  OpenOS-Project-OSP/repo-manage-util  ──►  OpenOS-Project-Ecosystem-OOC/repo-manage-util
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
| Contributor | Commits |
|---|---|
| [@vnepogodin](https://github.com/vnepogodin) | 151 |
| [@azdanov](https://github.com/azdanov) | 6 |
| [@Interested-Deving-1896](https://github.com/Interested-Deving-1896) | 3 |
| [@ptr1337](https://github.com/ptr1337) | 2 |
| [@SoulHarsh007](https://github.com/SoulHarsh007) | 2 |
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream influences recorded._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## Accessibility

<!-- AI:start:accessibility -->
No  was found when this README was generated. Check the
[Actions tab](https://github.com/Interested-Deving-1896/repo-manage-util/actions) for repository-specific checks, and document an
accessibility status only when a report or workflow provides evidence for it.




See the [W3C Web Content Accessibility Guidelines (WCAG)](https://www.w3.org/WAI/standards-guidelines/wcag/)
for accessibility guidance.
<!-- AI:end:accessibility -->

## License

<!-- AI:start:license -->
[GPL-3.0](https://github.com/Interested-Deving-1896/repo-manage-util/blob/develop/LICENSE) © 2026 [Interested-Deving-1896](https://github.com/Interested-Deving-1896)
<!-- AI:end:license -->
