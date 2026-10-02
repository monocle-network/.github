# .github

This repository centralizes GitHub community health files, templates, and organization-wide defaults for the Monocle Network organization.

## What is a .github repository?

The `.github` repository is a special repository that acts as a **fallback** for every repository in the organization that does not define its own community health files. Anyone who opens an issue or pull request in a repository without its own templates or policies will see the defaults from this repository instead.

This lets the organization standardize issues, pull requests, and policies in one place: a change made here applies everywhere it is not overridden.

## How overrides work

A repository's own files always take precedence. For files that can be stored in more than one location, GitHub looks in this order:

1. The `.github` folder
2. The root of the repository
3. The `docs` folder

If no corresponding file is found in the current repository, GitHub uses the default from this repository. Repository maintainers can therefore override any default with templates or content specific to their repository.

## Files in this repository

| File | Purpose |
|---|---|
| [README.md](https://github.com/monocle-network/.github/blob/main/profile/README.md) | This is the read-me file for the Monocle Network GitHub organization |
| [SECURITY.md](https://github.com/monocle-network/.github/blob/main/SECURITY.md) | How to report a security vulnerability to Monocle |
| [SUPPORT.md](https://github.com/monocle-network/.github/blob/main/SUPPORT.md) | Where to get help with Monocle |
| [CONTRIBUTING.md](https://github.com/monocle-network/.github/blob/main/CONTRIBUTING.md) | How to contribute to Monocle projects |
| [CODE_OF_CONDUCT.md](https://github.com/monocle-network/.github/blob/main/CODE_OF_CONDUCT.md) | Standards for engaging in the community |
| FUNDING.yml | Sponsor links displayed on Monocle repositories |
| [ACCESSIBILITY.md](https://github.com/monocle-network/.github/blob/main/ACCESSIBILITY.md) | Accessibility goals, known barriers, and reporting process |

Default community health files do not appear in the file browser or Git history of individual repositories, and are not included in their clones, packages, or downloads.

## Project matters

General project matters — proposals, meeting notes, incident reports, and transparency reports - are handled in the [meta repository](https://github.com/monocle-network/meta).
