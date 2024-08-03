# Note
```
guid: q4pu8I]J2b
notetype: Regex Syntax
```

### Tags
```
controlverb
groupconstruct
regex
```

## Name


## Description
Control verb - <b>THEN</b>

## Syntax (back)
<div>
  (*THEN)
</div>

## Description (long)
<div>
  <div>
    <div>
      (*THEN) or (*THEN:NAME) allows one to cut down on
      backtracking within an alternation. It won't allow regex to
      backtrack past its position, and it will give up matching the
      current alternation if there's a failure. If (*THEN) is used
      outside of an alternation, it will act like (*PRUNE).
    </div>
  </div>
</div>

## Example code (back)
<div>
  /^.*?(?(?=2)2|3(*THEN)4)/g
</div>

## Example matching (back)
35234
