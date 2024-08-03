# Note
```
guid: l($FS(1;I>
notetype: Regex Syntax
```

### Tags
```
commontoken
quantifier
regex
```

## Name


## Description
to quantify a pattern as repeating <b>three or more</b> times

## Syntax (back)
<div>
  a{3,}
</div>

## Description (long)
Matches at least 3 consecutive `a` characters.

## Example code (back)
<div>
  <div>
    /a{3,}/
  </div>
</div>

## Example matching (back)
<div>
  a aa <span style="background-color: rgb(0, 170, 255);">aaa</span>
  <span style="background-color: rgb(0, 170, 255);">aaaa</span>
  <span style="background-color: rgb(0, 170, 255);">aaaaaa</span>
</div>
