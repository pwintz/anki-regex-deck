# Note
```
guid: hF^GU1H%){
notetype: Regex Syntax
```

### Tags
```
anchor
regex
```

## Name
absolute end of string

## Description
to match the absolute end of string, after a trailing newline (always ignores new lines)

## Syntax (back)
<div>\z</div>

## Description (long)
<div><div>Matches the end of a string only. Unlike <code>$</code>, this is not affected by multiline mode, and, in contrast to <code>\Z</code>, will not match before a trailing newline at the end of a string.</div></div>

## Example code (back)
/\w+\z/

## Example matching (back)
<div>absolute end of <span style="background-color: rgb(0, 170, 255);">string</span>
</div>
