# Note
```
guid: kxdh2h4`>j
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
to force the match to fail

## Syntax (back)
<div>
  (*FAIL)
</div>

## Description (long)
<div>
  <div>
    <div>
      (*FAIL) or (*F) is a synonym for (?!), and it allows you to
      force a matching failure at a specific point in the regex.
    </div>
  </div>
</div>

## Example code (back)
<div>
  /Candy.+?(?:bad(*FAIL)|good)/
</div>

## Example matching (back)
Candy is bad <span style="background-color: rgb(0, 170,
255);">Candy is good</span>
