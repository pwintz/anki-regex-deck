# Note
```
guid: e!;XyW#X)V
notetype: Regex Syntax
```

### Tags
```
flags/modifiers
regex
```

## Name


## Description
for the flag to treat pattern strings as unicode

## Syntax (back)
<div>
  u (flag)
</div>

## Description (long)
<div>
  <div>
    <div>
      Pattern strings will be treated as UTF-16, which means that
      unicode characters will also be included in [a-z] ranges, and
      in escape sequences.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /\wa/u
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">ça</span> va?
