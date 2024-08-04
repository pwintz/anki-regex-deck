# Note
```
guid: >3c!8g_h.
notetype: Regex Syntax
```

### Tags
```
quantifier
regex
```

## Name
possessive quantifier

## Description
to make a qualifier possessive

## Syntax (back)
<div><div>a*+, a++, a?+</div></div>

## Description (long)
Matches as many characters as possible; backtracking can't reduce the number of characters matched. Because it is greedy, it will match all the way to the last digit, leaving nothing else for the <code>.</code> to match. Without backtracking, this regex fails to produce a match.

## Example code (back)
<div>/\d++./</div>

## Example matching (back)
<div>123
</div>
