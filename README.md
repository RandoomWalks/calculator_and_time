Add parsing functionality for time periods with tests in Rust
 This commit introduces a new feature for parsing strings representing time periods into a `Period` enum with
 variants for days, weeks, months, and years. The `Period` enum also includes a method to convert these periods in
 `chrono::Duration` objects. The parsing is done using the `nom` crate, with support for both numeric and written
 numbers. Additionally, unit tests are included to ensure the parsing works correctly for various inputs, includin
 edge cases and invalid strings.
