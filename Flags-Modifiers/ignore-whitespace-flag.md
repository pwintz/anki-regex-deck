# Note
```
guid: hvp|6>y7s~
notetype: Regex Syntax
```

### Tags
```
flags/modifiers
regex
```

## Name
ignore whitespace flag

## Description
for the flag to ignore whitespace

## Syntax (back)
x (flag)

## Description (long)
<div>
  <div>
    <div>
      This flag tells the engine to ignore all whitespace and allow
      for comments in the regex. Comments are indicated by a
      starting "#"-character. If you need to include a space
      character in your regex, it must now be escaped '\ '.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /a#comment here/x
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">a</span>#comment
here
