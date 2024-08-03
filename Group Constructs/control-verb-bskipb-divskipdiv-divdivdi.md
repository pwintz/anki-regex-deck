# Note
```
guid: xO@5:b.Jh+
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
Control verb - <b>SKIP</b>

## Syntax (back)
<div>
  (*SKIP)
</div>

## Description (long)
<div>
  <div>
    <div>
      (*SKIP) or (*SKIP:NAME) will cause the regex to give up on
      the current match if it tries to backtrack past its position.
      This is useful when looking to cut down on backtracking at
      specific points in the regex.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /aa(*SKIP)ard\w+/g
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">aaardvark</span>
aaaardvark aa<span style="background-color: rgb(0, 170,
255);">aaardvark</span> aaaaaardvark aaaa<span style= 
"background-color: rgb(0, 170, 255);">aaardvark</span>
