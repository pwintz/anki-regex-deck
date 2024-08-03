# Note
```
guid: ht+}y1?(Nn
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name


## Description
to match visible characters

## Syntax (back)
<div>
  [[:print:]]
</div>

## Description (long)
Matches printable characters, part of the basic latin set, such as
letters and spaces, without including control characters.
<code>[[:print:]]</code> is a POSIX notation and it needs to be
inside a [character class] notation.

## Example code (back)
<div>
  /[[:print:]]+/g
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">A|m0st</span>
é<span style="background-color: rgb(0, 170, 255);">verything
goes.</span>
