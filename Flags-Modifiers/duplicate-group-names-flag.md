# Note
```
guid: Re|}JNXB<A
notetype: Regex Syntax
```

### Tags
```
flags/modifiers
regex
```

## Name
duplicate group names flag

## Description
Duplicate group names <i>(flag)</i>

## Syntax (back)
<div>J</div>

## Description (long)
<div>
  <div>
    <div>
      This allows regex to accept duplicate pattern names, however
      each capture group still has its own ID. Thus the two capture
      groups produce their own match instead of a single combined
      one.
    </div>
  </div>
</div>

## Example code (back)
<div>/(?<letter>a)(?<letter>b)/J</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">ab</span><div>
</div><div><i>Full match: ab</i></div><div><i>Group `letter`: a</i></div><div><i>Group `letter`: b</i></div>
