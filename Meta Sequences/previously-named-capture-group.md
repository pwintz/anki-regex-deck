# Note
```
guid: H6iULr[T0s
notetype: Regex Syntax
```

### Tags
```
metasequence
regex
```

## Name
previously-named capture group

## Description
to match a previously-named capture group 'letter'

## Syntax (back)
<div><div>\g{letter}</div></div>

## Description (long)
Matches the capture group called "name". Note that you cannot use curly brackets (?{name}a+) to name a capture group in PCRE.

## Example code (back)
/(?'letter'a).*(\g{letter})/

## Example matching (back)
<div><span style="background-color: rgb(0, 170, 255);">a plus a</span>
</div><div><span style="background-color: rgb(0, 170, 255);">
</span></div><div><div><i>Full match: a plus a</i></div><div><i>Group 'letter': a</i></div><div><i>Group 2: a</i></div></div>
