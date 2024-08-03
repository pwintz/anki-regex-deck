# Note
```
guid: w@`9/YM90_
notetype: Regex Syntax
```

### Tags
```
anchor
regex
```

## Name
start of string or start of last match

## Description
to look for a match starting at the start of the string or the start of the last match

## Syntax (back)
<div><div>\G</div></div>

## Description (long)
This will match only at the starting point of the search or the position the previous successful match ended. Useful with the <code>/g</code> flag, or when you are only trying to match after a certain point in a string.

## Example code (back)
/(?:George|\G) likes ([^ ]+)/

## Example matching (back)
<div>Bob likes pie, <span style="background-color: rgb(0, 170, 255);">George likes icecream</span>
</div>
