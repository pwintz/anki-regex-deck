# Note
```
guid: GpD?>_0z^5
notetype: Regex Syntax
```

### Tags
```
metasequence
regex
```

## Name


## Description
to set the given position in the regex as the new "start" of the match

## Syntax (back)
<div><div>\K</div></div>

## Description (long)
This means that nothing preceding <code>\K</code> will be captured in the overall match.

## Example code (back)
/[\d]+\K[\d,]+/

## Example matching (back)
<div>123<span style="background-color: rgb(0, 170, 255);">,456,789</span>
</div>
