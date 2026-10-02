# Licensing

Each project must identify the license or licenses applicable to its contents.

## Before selecting a license

Consider:

- Who owns the code?
- Are there project or consortium agreements that restrict license choice?
- Does the project include third-party code or dependencies?
- Should modifications remain open, or is permissive reuse preferred?
- Does the repository contain software, data, documentation, or other assets
  requiring different licenses?

## License selection
If you are a beginner, try https://choosealicense.com/

Use an OSI-approved and SPDX-recognised license where applicable.

Useful references:

- SPDX License List
- Choose a License

The selected license should be reviewed with CRESYM/OSCC (OSPO) before public release.

## Existing code and dependencies

Before public release, scan the repository and its dependencies to identify
existing licenses and possible compatibility issues.

Recommended tooling:

- OSS Review Toolkit (ORT)
- ScanCode
- REUSE/SPDX tooling

## Multiple licenses

If different licenses apply to different parts of the repository, clearly
document which license applies to each component and use SPDX identifiers
where possible.