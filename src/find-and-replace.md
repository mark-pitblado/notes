# Find and Replace in Neovim

## Current Line - First Occurrence
Where `foo` is what you want to replace and `bar` is what you want to replace it with. 
If what you need to search for uses `/` then `|` can be used a seperated instead.

```vimscript
:s/foo/bar/
```
## Current Line - All Occurrences

```vimscript
:s/foo/bar/g
```

## Entire File

```vimscript
:s%/food/bar
```

## Remove Occurrences

```vimscript
:s%/foo//
```

