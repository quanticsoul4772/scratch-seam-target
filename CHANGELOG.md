# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html)
once versioned releases begin.

## [Unreleased]

_Nothing yet. Future changes will be documented here._

## [0.1.1] - 2026-09-20

M6 auth-posture decision checkpoint. This entry records the authentication
posture decided in devharness PR #31; it is a documentation-only change with
no source code, build step, dependencies, or automated tests affected.

### Added

- M6 auth-posture decision record — API-key-first billing is the default,
  with an adaptive OAuth posture, as decided in devharness PR #31.

## [0.1.0] - 2026-09-19

Initial seam-test staging checkpoint. This commit captures the repository's
starting state for the W1 seam test (converged-harness pilot staging); it is a
documentation-only scratch repo with no source code, build step, dependencies,
or automated tests.

### Added

- `README.md` — describes the repo as a throwaway target for the W1 seam test,
  existing so the seam test's hygiene class has something real to certify.
- `CONTRIBUTING.md` — contribution guide covering dev environment setup
  (clone only; no build or dependencies), manual verification in place of an
  automated test suite, commit/PR conventions, and what kinds of changes are
  welcome.
- `LICENSE` — MIT License, copyright (c) 2026 quanticsoul4772.
- `CHANGELOG.md` — this file, establishing the Keep a Changelog structure so
  future entries can be appended under `[Unreleased]` without restructuring.
