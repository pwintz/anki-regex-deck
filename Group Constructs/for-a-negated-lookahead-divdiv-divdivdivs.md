# Note
```
guid: Nqu8;lKJ+(
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name


## Description
for a negated lookahead

## Syntax (back)
<div>
  (?!...)
</div>

## Description (long)
<div>
  <div>
    <div>
      Starting at the current position in the expression, ensures
      that the given pattern does not match. Does not consume
      characters.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /foo(?!bar)/
</div>

## Example matching (back)
foobar <span style="background-color: rgb(0, 170,
255);">foo</span>baz
