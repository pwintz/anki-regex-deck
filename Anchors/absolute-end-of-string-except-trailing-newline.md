# Note
```
guid: r`nkN!!UK;
notetype: Regex Syntax
```

### Tags
```
anchor
regex
```

## Name
absolute end of string except trailing newline

## Description
to match the end of string, before a trailing newline (always ignores new lines)

## Syntax (back)
<div>\Z</div>

## Description (long)
Matches the end of a string only. Unlike <code>$</code>, this is not affected by multiline mode.

## Example code (back)
/\w+\Z/

## Example matching (back)
<div>end of <span style="background-color: rgb(0, 170, 255);">string</span>
</div>
