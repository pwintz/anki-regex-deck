# Note
```
guid: B`RLU@g!zY
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name


## Description
to match an atomic group (non-capturing)

## Syntax (back)
<div>(?>...)</div>

## Description (long)
<div><div><div>Matches the longest possible substring in the group and doesn't allow later backtracking to reevaluate the group. It is not a capturing group.</div></div></div>

## Example code (back)
<div>/(?>.+)@/</div>

## Example matching (back)
this line is matched/consumed to the end by .+ and is not allowed to backtrack to find @
