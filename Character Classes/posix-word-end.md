# Note
```
guid: ix+t*![URo
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name
POSIX word end

## Description
the end of a word

## Syntax (back)
<div>
  [[:>:]]
</div>

## Description (long)
This POSIX equivalent of the <code>\b</code> word boundary is
interpreted as <code>\\b(?<=\\w)</code>.

## Example code (back)
/d[[:>:]]/g

## Example matching (back)
dot en<span style="background-color: rgb(0, 170, 255);">d</span>
