# Note
```
guid: oy5~[bp+Z4
notetype: Regex Syntax
```

### Tags
```
flags/modifiers
regex
```

## Name
ungreedy flag

## Description
Ungreedy <i>(flag)</i>

## Syntax (back)
<div>
  U
</div>

## Description (long)
The engine will per default do lazy matching, instead of greedy. This means that a ? following a quantifier instead makes it greedy.

## Example code (back)
/a+/U

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">a</span>aaa
