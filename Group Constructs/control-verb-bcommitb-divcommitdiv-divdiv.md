# Note
```
guid: nrH~hd0w#>
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
Control verb - <b>COMMIT</b>

## Syntax (back)
<div>
  (*COMMIT)
</div>

## Description (long)
<div>
  <div>
    <div>
      This verb does not allow regex to continue parsing after a
      matching failure, even if there are other matching strings
      ahead, and regardless of how many successful matches are
      before the failure.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /wo+(*COMMIT)w/g
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">woow</span>
<span style="background-color: rgb(0, 170, 255);">woow</span> woot
woow
