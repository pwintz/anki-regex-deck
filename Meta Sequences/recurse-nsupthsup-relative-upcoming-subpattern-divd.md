# Note
```
guid: B%D?VWs2YR
notetype: Regex Syntax
```

### Tags
```
metasequence
regex
```

## Name


## Description
Recurse n<sup>th</sup> relative upcoming subpattern

## Syntax (back)
<div><div>\g<+n></div></div>

## Description (long)
Recurses nth capture group ahead of the current position of \g<+n>. \g<+2> is the second capture group after \g.

## Example code (back)
<div>/\g<+1> and (b)/</div>

## Example matching (back)
<div>extra <span style="background-color: rgb(0, 170, 255);">b and b</span> stuff
</div>
