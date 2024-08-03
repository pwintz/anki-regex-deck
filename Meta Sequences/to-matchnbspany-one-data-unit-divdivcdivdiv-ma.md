# Note
```
guid: rez}c_1mL:
notetype: Regex Syntax
```

### Tags
```
metasequence
regex
```

## Name


## Description
to match any one data unit

## Syntax (back)
<div><div>\C</div></div>

## Description (long)
Matches exactly one data unit of input. Can match individual bytes in UTF-8 mode, leading to undefined behaviour if a search starts inside a character.

## Example code (back)
/\C/

## Example matching (back)
<div><span style="background-color: rgb(0, 170, 255);">a</span> abc
</div>
