# Note
```
guid: Dibj%-d(%O
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name
duplicate subpattern group number

## Description
for a duplicate subpattern group number

## Syntax (back)
<div>(?|...)</div>

## Description (long)
<div><div><div>Any subpatterns in (...) in such a group share the same number.</div></div></div>

## Example code (back)
<div>/(?|(candy)|(kiss)|(berry))/g</div>

## Example matching (back)
A <span style="background-color: rgb(0, 170, 255);">candy</span>, <span style="background-color: rgb(0, 170, 255);">kiss</span>, or even a <span style="background-color: rgb(0, 170, 255);">berry</span> is delicious.
