# Note
```
guid: Fll85o%eLu
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name


## Description
to match any uppercase letter

## Syntax (back)
<div>
  [[:upper:]]
</div>

## Description (long)
<div>
  <div>
    <div>
      Matches uppercase letters. Equivalent to <font color=
      "#FF0000">[A-Z]</font>. [[:upper:]] is a POSIX notation and
      it needs to be inside a [character class] notation.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /[[:upper:]]+/g
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170,
255);">ABC</span>abc<span style="background-color: rgb(0, 170,
255);">DEF</span>
