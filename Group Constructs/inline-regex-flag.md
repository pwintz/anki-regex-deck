# Note
```
guid: l$qs;ltJ|w
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name
inline regex flag

## Description
to enable regex flags within an expression

## Syntax (back)
<div>(?imsxXU)</div>

## Description (long)
These enable setting regex flags within the expression itself. You can also unset flags using a minus sign: <code>(?-i)</code>.

## Example code (back)
<div>/a(?i)a/g</div>

## Example matching (back)
<span class="regexmatch">aA</span> Aa <span class="regexmatch">aa</span> AA
