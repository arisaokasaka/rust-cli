# what is this?

Search for a pattern in a file and display the lines that contain it.
It's like a command 'grep'.

# will fail

```
cargo run
```

# will work successfully (but no output)

```
cargo run -- some-pattern some-file
```

example with output: `cargo run -- str src/main.rs`

### memo

- A Cargo.toml file that contains metadata for our project, incl. a list of dependencies/external libraries we use.
- A src/main.rs file that is the entry point for our (main) binary.
