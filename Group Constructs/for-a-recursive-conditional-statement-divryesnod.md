# Note
```
guid: bFeWd0v6H>
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name


## Description
for a recursive conditional statement

## Syntax (back)
<div>(?(R#)yes|no)</div>

## Description (long)
<code>(?R1)</code> checks if a call to capture group <code>1</code> was made, which will return false the first time it is encountered because the regex engine is simply parsing capture group one.<div>Once <code>(?1)</code> is called, <code>(?(R1)true|false)</code> will return true since capture group <code>1</code> was called, and will match <code>ction</code>.</div>

## Example code (back)
<div>/( *fun(?(R1)ction|ky))(?1)/</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">funky function</span><div>
</div><div><i>Full match: funky function</i></div><div><i>Group 1: funky</i></div>
