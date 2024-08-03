# Note
```
guid: x^M`)(Q.bt
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
Control verb - <b>MARK:NAME</b>

## Syntax (back)
(*MARK:NAME)

## Description (long)
<div>
  (*MARK:NAME) or (*:NAME) is used to track how a match was arrived
  at. Name is always required, but it doesn't need to be unique.
  When used in conjunction with the /K modifier, pcretest can
  return the mark together with a successful match.
</div>
<div>
  <div>
    <div>
      <font color="#FF0000">re>
      /X(*MARK:A)Y|X(*MARK:B)Z/K</font>
    </div>
    <div>
      <font color="#FF0000">data> XY</font>
    </div>
    <div>
      <font color="#FF0000">0: XY</font>
    </div>
    <div>
      <font color="#FF0000">MK: A</font>
    </div>
    <div>
      <font color="#FF0000">XZ</font>
    </div>
    <div>
      <font color="#FF0000">0: XZ</font>
    </div>
    <div>
      <font color="#FF0000">MK: B</font>
    </div>
  </div>
</div>

## Example code (back)


## Example matching (back)

