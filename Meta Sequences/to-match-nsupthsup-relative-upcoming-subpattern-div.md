# Note
```
guid: Pd-oyFOC:4
notetype: Regex Syntax
```

### Tags
```
metasequence
regex
```

## Name


## Description
to match n<sup>th</sup> relative upcoming subpattern

## Syntax (back)
<div><div>\g'+n'</div></div>

## Description (long)
Recurses nth capture group ahead of the current position of <code>\g'+n'</code>. For example, <code>\g'+2'</code> is the second capture group after <code>\g</code>.

## Example code (back)
/g'+1' and (b)/

## Example matching (back)
<div>extra <span style="background-color: rgb(0, 170, 255);">b and b</span> stuff
</div>
