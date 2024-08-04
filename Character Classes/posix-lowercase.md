# Note
```
guid: M$9JQy!+D+
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name
POSIX lowercase

## Description
to match lowercase characters

## Syntax (back)
<div>
  [[:lower:]]
</div>

## Description (long)
Matches lowercase letters. Equivalent to <code>[a-z]</code>.
[[:lower:]] is a POSIX notation and it needs to be inside a
[character class] notation.

## Example code (back)
<div>
  /[[:lower:]]+/g
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170,
255);">abc</span>DEF<span style="background-color: rgb(0, 170,
255);">ghi</span>
