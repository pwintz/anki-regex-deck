# Note
```
guid: sJ=8[z&g6k
notetype: Regex Syntax
```

### Tags
```
flags/modifiers
regex
```

## Name


## Description
eXtended <i>(flag)</i>

## Syntax (back)
<div>
  X
</div>

## Description (long)
<div>
  <div>
    <div>
      Any character following a \ that is not a valid meta sequence
      will be faulted and raise an error. For example, escaping a
      (.) meta character will cause an error, and it will not
      match.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /\x42oo\./X
</div>

## Example matching (back)
Boo.
