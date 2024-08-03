# Note
```
guid: gx8v9Nsb*W
notetype: Regex Syntax
```

### Tags
```
anchor
commontoken
regex
```

## Name
word boundary

## Description
to match a word boundary

## Syntax (back)
<div>
  <div>
    \b
  </div>
</div>

## Description (long)
Matches, without consuming any characters, immediately between a character matched by \w and a character not matched by \w (in either order). It cannot be used to separate non words from words.

## Example code (back)
/d\b/g

## Example matching (back)
<div>
  wor<span style="background-color: rgb(0, 170, 255);">d</span>
  boundaries are od<span style="background-color: rgb(0, 170,
  255);">d</span>
</div>
