# Note
```
guid: s+MkU~p-/D
notetype: Regex Syntax
```

### Tags
```
commontoken
quantifier
regex
```

## Name
repetition range quantifier

## Description
to quantify a pattern as repeating <b>between 3 and 6</b> times

## Syntax (back)
<div>
  <div>
    a{3,6}
  </div>
</div>

## Description (long)
Matches between 3 and 6 (inclusive) consecutive `a` characters.

## Example code (back)
/a{3,6}/

## Example matching (back)
<div>
  a aa <span style="background-color: rgb(0, 170, 255);">aaa</span>
  <span style="background-color: rgb(0, 170, 255);">aaaa</span>
  <span style="background-color: rgb(0, 170,
  255);">aaaaaa</span>aaaa
</div>
