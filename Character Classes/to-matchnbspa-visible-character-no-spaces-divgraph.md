# Note
```
guid: Id.*N.6K_j
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name


## Description
to match a visible character (no spaces)

## Syntax (back)
<div>
  [[:graph:]]
</div>

## Description (long)
Matches printable, non-whitespace, non-control characters only.
Equivalent to <code>[!-~]</code>. <code>[[:graph:]]</code> is a
POSIX notation and it needs to be inside a [character class]
notation.

## Example code (back)
<div>
  /[[:graph:]]+/g
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">A|m0st</span>
é<span style="background-color: rgb(0, 170, 255);">verything</span>
<span style="background-color: rgb(0, 170, 255);">goes.</span>
