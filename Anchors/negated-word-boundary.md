# Note
```
guid: G*=1#`^L>x
notetype: Regex Syntax
```

### Tags
```
anchor
commontoken
regex
```

## Name
negated word boundary

## Description
to match a non-word boundary

## Syntax (back)
<div>
  <div>
    \B
  </div>
</div>

## Description (long)
Matches, without consuming any characters, at the position between
two characters matched by <code>\w</code>.

## Example code (back)
/r\B/g

## Example matching (back)
<div>
  <span style="background-color: rgb(0, 170, 255);">r</span>egex is
  <span style="background-color: rgb(0, 170, 255);">r</span>eally
  cool
</div>
