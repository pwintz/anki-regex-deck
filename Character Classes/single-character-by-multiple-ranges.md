# Note
```
guid: bcPM|*0sr$
notetype: Regex Syntax
```

### Tags
```
characterclass
commontoken
regex
```

## Name
single character by multiple ranges

## Description
to match any character in the range: <code>a-z</code> or
<code>A-Z</code>

## Syntax (back)
<div>
  <div>
    [a-zA-Z]
  </div>
</div>

## Description (long)
Matches any characters between <code>a-z</code> or
<code>A-Z</code>. You can combine as much as you please.

## Example code (back)
/[a-zA-Z]+/g

## Example matching (back)
<div>
  <span style="background-color: rgb(0, 170,
255);">abc</span>123<span style="background-color: rgb(0, 170, 
   255);">DEF</span>
</div>
