# Setting up mdBook

For full documentation see: https://rust-lang.github.io/mdBook/index.html

## Install

```zsh
cargo install mdbook
```

To uninstall, run

```zsh
cargo uninstall mdbook
```

## Create a book

```zsh
mdbook init my-first-book
```

## Editing the book

All edits should be made in the src directory, and new notes should be created from the `SUMMARY.md` file, which should be present after initialization. Once the `SUMMARY.md` file is saved, and `mdbook serve` is fun, appropriate markdown files will automatically be created.

For example,

```md
- [setting-up-mdbook](./setting-up-mdbook.md)
```

The markdown files themselves can be edited using any standard markdown syntax.
