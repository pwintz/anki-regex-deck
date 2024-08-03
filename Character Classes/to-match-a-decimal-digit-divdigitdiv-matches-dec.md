# Note
```
guid: yEd5:@me2r
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name


## Description
to match a decimal digit

## Syntax (back)
<div>
  [[:digit:]]
</div>

## Description (long)
Matches decimal digits. Equivalent to <code>[0-9]</code>.
<code>[[:digit:]]</code> is a POSIX notation and it needs to be
inside a [character class] notation.

## Example code (back)
<div>
  /[[:digit:]]/g
</div>

## Example matching (back)
one: <span style="background-color: rgb(0, 170, 255);">1</span>,
two: <span style="background-color: rgb(0, 170, 255);">2</span>
