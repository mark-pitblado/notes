# Notes

This repository stores a series of technical "cheatsheets" that I use on a regular basis. The primary purpose for creating this service was to allow me to easily look things up both on desktop and on mobile, and to not have to worry about syncing things back and forth. 

## FAQ

**Doesn't all this information exist already elsewhere?**
Absolutely. This repository is a selection of what I find most useful so that I can reference it *instead* of going to all of those different sites. Perhaps the same functionality will be useful for you.

**How do I get started?**
These notes run on [mdbook](https://rust-lang.github.io/mdBook/index.html).

First, clone the repository.

```bash
git clone "https://codeberg.org/mark-pitblado/notes.git"
cd notes
```

Then, install mdbook through [cargo](https://crates.io/).

```bash
cargo install mdbook
```

Lastly, while in the notes directory, use mdbook serve to spin up the server on localhost

```bash
mdbook serve
```

