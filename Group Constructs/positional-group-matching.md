# Note
```
guid: cm-Po^2Wk~
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name
positional group matching

## Description
to match the first capture group following the current position in the expression.

## Syntax (back)
<div>(?+1)</div>

## Description (long)
<div><div><div>Match the first capture group following the current position in the expression. (?+2) is the second one, (?-1) is before current position.</div></div></div>

## Example code (back)
<div>/(?+1).+(match)/</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">match if I start with match</span><div>
</div><div><i>Full match: match if I start with match</i></div><div><i>Group 1: match</i></div>
