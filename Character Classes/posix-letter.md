# Note
```
guid: n,r(Yk(V{P
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name
POSIX letter

## Description
any letter

## Syntax (back)
<div>
  [[:alpha:]]
</div>

## Description (long)
<div>
  <div>
    <div>
      An alternate way to match alphabet letters. Equivalent to
      <code>[A-Za-z]</code>. <code>[[:alpha:]]</code> is a POSIX
      notation and it needs to be inside a [character class]
      notation.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /[[:alpha:]]+/g
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">hello</span>,
<span style="background-color: rgb(0, 170, 255);">there</span>!
