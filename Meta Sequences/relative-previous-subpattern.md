# Note
```
guid: d*>8/cuAM7
notetype: Regex Syntax
```

### Tags
```
metasequence
regex
```

## Name
relative previous subpattern

## Description
to match the n<sup>th</sup> relative previous subpattern

## Syntax (back)
<div>\g{-n}</div>

## Description (long)
<div><div>Recurses nth capture group prior to the current position of \g{-n}. \g{-1} would be the last capture group before \g. \g{-2} would be the capture group before the last, and so on.</div></div>

## Example code (back)
/b+(a+).*(\g{-1})/

## Example matching (back)
<div><span style="background-color: rgb(0, 170, 255);">bbbbaaaa and aaaa</span>3
</div>
