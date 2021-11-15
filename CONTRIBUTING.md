# Contributing to DataSlime

We love your input! We want to make contributing to this project as easy and transparent as possible.

## Summary of the contribution flow

The following is a summary of the ideal contribution flow. Please, note that Pull Requests can also be rejected by the maintainers when appropriate.

```
    ┌───────────────────────┐
    │                       │
    │    Open an issue      │
    │  (a bug report or a   │
    │   feature request)    │
    │                       │
    └───────────────────────┘
               ⇩
    ┌───────────────────────┐
    │                       │
    │  Open a Pull Request  │
    │   (only after issue   │
    │     is approved)      │
    │                       │
    └───────────────────────┘
               ⇩
    ┌───────────────────────┐
    │                       │
    │   Your changes will   │
    │     be merged and     │
    │ published on the next │
    │        release        │
    │                       │
    └───────────────────────┘
```

## Code of Conduct

DataSlime has adopted a Code of Conduct that we expect project participants to adhere to. Please [read the full text](./CODE_OF_CONDUCT.md) so that you can understand what sort of behaviour is expected.

## Our Development Process

We use Github to host code, to track issues and feature requests, as well as accept pull requests.

## Issues

Open an issue **only** if you want to report a bug or a feature. Don't open issues for questions or support, instead open a disscussion or join our [Discord](https://discord.gg/uvcanfnz5B). It's more likely you'll get help, and much faster!

## Issue Triage

Here are some tags that we're using to better organize issues:

- `good first issue` - Good candidates for someone new to the project to contribute.
- `help wanted` - Issues that should be addressed and which we would welcome a
  PR for but may need significant investigation or work
- `needs more info` - Missing repro steps or context for both project issues \&
  support questions.
- `documentation` - Relating to improving documentation for the project.
- Platform-specific tags for anything that is specific to a particular
  environment (e.g. `amd64`, `macos`, and so all).

## Bug Reports and Feature Requests

Please use our issues templates that provide you with hints on what information we need from you to help you out.

## Pull Requests

**Please, make sure you open an issue before starting with a Pull Request, unless it's a typo or a really obvious error.** Pull requests are the best way to propose changes.

## Conventional commits

Pull requests should have a title that follows this specification, otherwise, merging is blocked.

- `fix: ` prefix in the title indicates that PR is a bug fix and PATCH release must be triggered.
- `feat: ` prefix in the title indicates that PR is a feature and MINOR release must be triggered.
- `docs: ` prefix in the title indicates that PR is only related to the documentation and there is no need to trigger release.
- `chore: ` prefix in the title indicates that PR is only related to cleanup in the project and there is no need to trigger release.
- `test: ` prefix in the title indicates that PR is only related to tests and there is no need to trigger release.
- `refactor: ` prefix in the title indicates that PR is only related to refactoring and there is no need to trigger release.

What about MAJOR release? just add `!` to the prefix, like `fix!: ` or `refactor!: `

If you are not familiar with the specification simply ask maintainers to modify.

Happy contributing :heart:

## License

The documentation is licensed under

- Creative Commons Attribution 4.0 License ([LICENSE-CC-BY](LICENSE-CC-BY)
  or https://creativecommons.org/licenses/by/4.0/legalcode)

And the source code is licensed under either of

- Apache License, Version 2.0 ([LICENSE-APACHE](LICENSE-APACHE) or
  http://www.apache.org/licenses/LICENSE-2.0)

- MIT License ([LICENSE-MIT](LICENSE-MIT) or
  https://opensource.org/licenses/MIT)

at your option.

### Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
licensed as above, without any additional terms or conditions.

## Code of Conduct

Contribution to this crate is organized under the terms of the [DataSlime Code of
Conduct][coc], [all DataSlime members][members], promises
to intervene to uphold that code of conduct.

[coc]: CODE_OF_CONDUCT.md
[members]: https://github.com/orgs/dataslime/teams/all

## References

This document was adapted from the open-source contribution guidelines for [AsyncAPI Initiative](https://github.com/asyncapi/.github/blob/master/CONTRIBUTING.md).
