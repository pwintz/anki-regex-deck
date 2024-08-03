# Note
```
guid: e0e1?,khn{
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name
POSIX Latin letter or digit

## Description
to match any Latin letter or digit

## Syntax (back)
<div>
  [[:alnum:]]
</div>

## Description (long)
An alternate way to match any letter or digit. Equivalent to
<code>[A-Za-z0-9]</code>. <code>[[:alnum:]]</code> is a POSIX
notation and it needs to be inside a [character class] notation.

## Example code (back)
<div>
  /[[:alnum:]]+/g
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">1st</span>,
<span style="background-color: rgb(0, 170, 255);">2nd</span>,
<span style="background-color: rgb(0, 170, 255);">and</span>
<span style="background-color: rgb(0, 170, 255);">3rd</span>.
