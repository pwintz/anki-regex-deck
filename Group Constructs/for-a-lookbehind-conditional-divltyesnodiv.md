# Note
```
guid: o)$Fc!*J@
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name


## Description
for a lookbehind conditional

## Syntax (back)
<div>(?(?<=...)yes|no)</div>

## Description (long)
<div><div><div>If the lookbehind succeeds, match the pattern before the vertical bar. Otherwise, matches the pattern after the vertical bar. The lookaround can be negative. Global flag, <code>'g'</code> breaks conditionals.</div></div></div>

## Example code (back)
<div>/(?(?<=\s)(delish)|(ew))/</div>

## Example matching (back)
Is candy <span style="background-color: rgb(0, 170, 255);">delish</span> or ew?
