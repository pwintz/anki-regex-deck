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
extended flag

## Description
eXtended <i>(flag)</i>

## Syntax (back)
<div>
  X (flag)
</div>

## Description (long)
Any character following a \ that is not a valid meta sequence will be faulted and raise an error. For example, escaping a (.) meta character will cause an error, and it will not match.

## Example code (back)
/\x42oo\./X

## Example matching (back)
Boo.
