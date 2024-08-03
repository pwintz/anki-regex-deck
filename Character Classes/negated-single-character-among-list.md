# Note
```
guid: l:134@|t?(
notetype: Regex Syntax
```

### Tags
```
characterclass
commontoken
regex
```

## Name
negated single character among list

## Description
to match any character except <code>a</code>, <code>b</code> or
<code>c</code>

## Syntax (back)
<div>
  <div>
    [^abc]
  </div>
</div>

## Description (long)
Matches any character except for an <code>a</code>, <code>b</code>
or <code>c</code>.

## Example code (back)
/[^abc]+/g

## Example matching (back)
<div>
  <span style="background-color: rgb(0, 170, 255);">Anything</span>
  b<span style="background-color: rgb(0, 170, 255);">ut</span>
  abc<span style="background-color: rgb(0, 170, 255);">.</span>
</div>
