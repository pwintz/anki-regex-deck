# Note
```
guid: Pg#h8hUNdX
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name
named group match

## Description
to match a capture group named <code>foo</code>

## Syntax (back)
<div>(?P=foo)</div>

## Description (long)
<div><div><div>Matches the text matched by a previously named capture group. This is the python specific notation.</div></div></div>

## Example code (back)
<div>/(?P<named_group>cool)[a-z ]+(?P=named_group)/</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">cool is cool</span><div><span style="background-color: rgb(0, 170, 255);">
</span></div><div><i>Full match: cool is cool<span style="background-color: rgb(0, 170, 255);">
</span></i></div><div><i>Group `named_group`: cool</i></div>
