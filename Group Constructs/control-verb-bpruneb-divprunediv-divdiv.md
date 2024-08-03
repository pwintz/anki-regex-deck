# Note
```
guid: nEQ>K#=aC~
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
Control verb - <b>PRUNE</b>

## Syntax (back)
<div>
  (*PRUNE)
</div>

## Description (long)
<div>
  <div>
    <div>
      (*PRUNE) or (*PRUNE:NAME) will cause the regex to exit if it
      tries to backtrack past its position. This is useful when
      looking to cut down on backtracking at specific points in the
      regex. The example above would normally match both terms but
      due to (*PRUNE) the second alternative is not acted on.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /(*PRUNE)\w{4,9} strategy|\w{4,9} dynamics/g
</div>

## Example matching (back)
marketing dynamics, <span style="background-color: rgb(0, 170,
255);">marketing strategy</span>
