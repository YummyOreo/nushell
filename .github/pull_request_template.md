
# Description
<!--
Thank you for improving Nushell. Please, check our [contributing guide](../CONTRIBUTING.md) and talk to the core team before making major changes.

Description of your pull request goes here. **Provide examples and/or screenshots** if your changes affect the user experience.
-->

# User-Facing Changes
<!-- List of all changes that impact the user experience here. This helps us keep track of breaking changes. -->

# Tests + Formatting
<!--
Don't forget to add tests that cover your changes.

Make sure you've run and fixed any issues with these commands:

- `cargo fmt --all -- --check` to check standard code formatting (`cargo fmt --all` applies these changes)
- `cargo clippy --workspace -- -D warnings -D clippy::unwrap_used -A clippy::needless_collect -A clippy::result_large_err` to check that you're using the standard code style
- `cargo test --workspace` to check that all tests pass
- `cargo run -- crates/nu-std/tests/run.nu` to run the tests for the standard library

> **Note**
> from `nushell` you can also use the `toolkit` as follows
> ```bash
> use toolkit.nu  # or use an `env_change` hook to activate it automatically
> toolkit check pr
> ```
-->

# After Submitting
<!-- If your PR had any user-facing changes, update [the documentation](https://github.com/nushell/nushell.github.io) after the PR is merged, if necessary. This will help us keep the docs up to date. -->
