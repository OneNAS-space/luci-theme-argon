# Security Policy

## What this repository is

This repository builds a patched variant of
[jerrykuku/luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon).

- `main` is the upstream source plus the local patches in `patches/`. It is
  what gets built and released.
- `official_channel` is an unmodified copy of upstream, kept for reference.
- `.github/workflows/` contains the sync and build/release automation.

## Supported Versions

Only the latest release built from `main` is supported. Older builds do not
receive fixes; please update to the latest release.

| Version                  | Supported          |
| ------------------------ | ------------------ |
| Latest release (`main`)  | :white_check_mark: |
| Older releases           | :x:                |

## Scope

Please report here:

- Problems in the patches under `patches/`.
- Problems in the sync, build or release workflows, for example token or
  permission handling, or anything that could let someone tamper with the
  published packages or feeds.

Vulnerabilities in the theme code that is **not** touched by these patches
belong to the upstream project. Please report them to
[jerrykuku/luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)
directly. If the issue also affects the packages built here and you would like
a fix sooner, you are welcome to open a report here as well.

## Reporting a Vulnerability

Please **do not** open a public issue for a security problem.

Use GitHub's private vulnerability reporting instead: open the **Security**
tab of this repository and choose **Report a vulnerability**. Include the
affected version (the `PKG_VERSION` / release tag), the steps to reproduce it,
and what an attacker could do with it.

This is a personal, best-effort project. You can expect:

- an acknowledgement within 7 days;
- a follow-up when the report has been confirmed or declined, with the reason;
- for confirmed issues, a fix in a new release, and credit in the release notes
  if you want it.
