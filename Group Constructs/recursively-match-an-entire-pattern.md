# Note
```
guid: H)ZF%sTYKe
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name
recursively match an entire pattern

## Description
to recursively match an entire pattern

## Syntax (back)
<div>(?R)</div>

## Description (long)
Recursively match the entire expression. <code>(?0)</code> and <code>\g<0></code> are synonymous. This is useful for balanced tags.

## Example code (back)
<div>/\[(?:[\w\/ ="-]|(?R))*]/g</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">[shortcode title="Title Here"]</span>Some content here<span style="background-color: rgb(0, 170, 255);">[/shortcode]</span>
