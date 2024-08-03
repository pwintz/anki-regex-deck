# Note
```
guid: yG`Z#_]:([
notetype: Regex Syntax
```

### Tags
```
flags/modifiers
regex
```

## Name
multiline flag

## Description
for the flag to treat each line sparately

## Syntax (back)
<div>
  m (flag)
</div>

## Description (long)
<div>
  <div>
    <div>
      The multiline flag causes the anchors <code>^</code> and
      <code>$</code> to match at the beginning/end of each line
      respectively, instead of beginning/end of the entire string.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /^d.+\d{3}$/m
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">digits coming up
443</span>
