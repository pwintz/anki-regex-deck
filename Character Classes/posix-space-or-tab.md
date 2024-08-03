# Note
```
guid: MoAa5LGGv=
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name
POSIX space or tab

## Description
any space or tab only

## Syntax (back)
<div>
  [[:blank:]]
</div>

## Description (long)
Matches spaces and tabs (but not newlines). Equivalent to <code>[
]</code>. <code>[[:blank:]]</code> is a POSIX notation and it needs
to be inside a [character class] notation.

## Example code (back)
<div>
  /[[:blank:]]/g
</div>

## Example matching (back)
a b c
