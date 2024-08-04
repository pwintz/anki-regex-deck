# Note
```
guid: m;!0P)oU+v
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name
recursively match the first capture group

## Description
to recursively match the first capture group

## Syntax (back)
<div>(?1)</div>

## Description (long)


## Example code (back)
<div>/(capture).+((?1))/</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">capture my capture</span> again<div>
</div><div><i>Full match: capture my capture</i></div><div><i>Group 1: capture</i></div><div><i>Group 2: capture</i></div>
