# Note
```
guid: v1!eF9?MH?
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name
non-group pattern

## Description
to match everything enclosed without making a group

## Syntax (back)
<div><div>(?:...)</div></div>

## Description (long)
This construct is similar to (...), but won't create a capture group.

## Example code (back)
/(?:he)+/g

## Example matching (back)
<div><span style="background-color: rgb(0, 170, 255);">hehe</span>h <span style="background-color: rgb(0, 170, 255);">he</span> <span style="background-color: rgb(0, 170, 255);">he</span>h
</div>
