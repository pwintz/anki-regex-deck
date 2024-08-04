# Note
```
guid: kw%_I7[hS+
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name
named caputre group

## Description
to create a named capturing group

## Syntax (back)
<div>(?'name'...)</div>

## Description (long)
This capturing group can be referred to using the given name instead of a number. <h3>Alternative versions</h3><ol><li><code>(?<name>...)</code></li><li><code>(?P<name>...)</code></li></ol>

## Example code (back)
/(?'name'Sally)/

/(?<name>Sally)/

/(?P<name>Sally)/

## Example matching (back)
Call me <span style="background-color: rgb(0, 170, 255);">Sally</span>.
