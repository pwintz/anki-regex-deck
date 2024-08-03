# Note
```
guid: C^+N{IC|Z?
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name


## Description
to insert a comment that is ignored by RegEx processing

## Syntax (back)
<div>(?#...)</div>

## Description (long)
<div><div><div>A comment. Any text appearing in this group is ignored in the regex. </div><div>(Another option is enabling the x flag to allow #comments. This flag will also cause regex to ignore spaces.)</div></div></div>

## Example code (back)
<div>/Not(?# .* <-- that should match all)/</div>

## Example matching (back)
<span class="regexmatch">Not</span>hing else matches.
