# Note
```
guid: M3dJ+X%4__
notetype: Regex Syntax
```

### Tags
```
groupconstruct
patternmodifier
regex
```

## Name


## Description
Pattern modifier - <b>UCP</b>

## Syntax (back)
<div>
  (*UCP)
</div>

## Description (long)
<div>
  <div>
    <div>
      UCP (Unicode Character Properties) allows regex to treat the
      string as unicode, which means that \d and \w are extended to
      match other unicode characters than [0-9] and [a-zA-Z0-9_].
    </div>
  </div>
</div>

## Example code (back)
<div>
  /(*UCP)\d+\w/
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170,
255);">0٠1١2٢3٣4٤5٥6٦7٨٨9٩hة</span>
