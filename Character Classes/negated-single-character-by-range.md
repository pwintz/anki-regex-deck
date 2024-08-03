# Note
```
guid: NmY>1*iZ-n
notetype: Regex Syntax
```

### Tags
```
characterclass
commontoken
regex
```

## Name
negated single character by range

## Description
to match any character not in the range: <code>a-z</code>

## Syntax (back)
<div>
  <div>
    [^a-z]
  </div>
</div>

## Description (long)
Matches any characters except those in the range <code>a-z</code>.

## Example code (back)
/[^a-z]+/g

## Example matching (back)
<div>
  <span style="background-color: rgb(0, 170, 255);">A</span>nything
  but a<span style="background-color: rgb(0, 170,
  255);">-</span>z<span style="background-color: rgb(0, 170,
  255);">.</span>
</div>
