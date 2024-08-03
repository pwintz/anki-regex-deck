# Note
```
guid: uQ47S~0{+N
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name


## Description
to match any visible punctuation characters

## Syntax (back)
<div>
  [[:punct:]]
</div>

## Description (long)
<div>
  <div>
    <div>
      Matches characters that are not whitespace, letters or
      numbers. [[:punct:]] is a POSIX notation and it needs to be
      inside a [character class] notation.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /[[:punct:]]/g
</div>

## Example matching (back)
hello<span style="background-color: rgb(0, 170, 255);">,</span>
regex user<span style="background-color: rgb(0, 170,
255);">!</span>
