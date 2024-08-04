# Note
```
guid: L#ksuJ[8^d
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name
POSIX word character

## Description
to match word character

## Syntax (back)
<div>
  [[:word:]]
</div>

## Description (long)
Matches letters, numbers and underscores. Equivalent to
<code>\w</code> or <code>[a-zA-Z0-9_]</code>. [[:word:]] is a POSIX
notation and it needs to be inside a [character class] notation.

## Example code (back)
<div>
  /[[:word:]]+/g
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">any</span>
<span style="background-color: rgb(0, 170, 255);">word_</span>
<span style="background-color: rgb(0, 170, 255);">character</span>
