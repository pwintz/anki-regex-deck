# Note
```
guid: qFq0QidB~!
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name
POSIX  ACII

## Description
ASCII codes 0-127

## Syntax (back)
<div>
  [[:ascii:]]
</div>

## Description (long)
<div>
  <div>
    <div>
      Matches any character in the valid ASCII range. Equivalent to
      <code>[- ]</code>. <code>[[:ascii:]]</code> is a POSIX
      notation and it needs to be inside a [character class]
      notation.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /[[:ascii:]]+/g
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">Any basic latin
character.</span> é <span style="background-color: rgb(0, 170,
255);">is not one of them.</span>
