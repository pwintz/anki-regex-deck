# Note
```
guid: nO2$Q#=ySC
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name


## Description
for a lookahead conditional

## Syntax (back)
<div>(?(?=...)yes|no)</div>

## Description (long)
<div><div><div>If the lookahead succeeds, matches the pattern before the vertical bar. Otherwise, matches the pattern after the vertical bar. The lookaround can be negative. Global flag breaks conditionals.</div></div></div>

## Example code (back)
<div>/(?(?=is)(is delicious)|(disgusting))/</div>

## Example matching (back)
Candy <span style="background-color: rgb(0, 170, 255);">is delicious</span> or disgusting.<div>
</div><div><i>Full match: is delicious</i></div><div><i>Group 1: is delicious</i></div>
