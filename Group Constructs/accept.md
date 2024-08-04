# Note
```
guid: Hp>n[M<ek`
notetype: Regex Syntax
```

### Tags
```
controlverb
groupconstruct
regex
```

## Name
accept

## Description
to cause the regex to end successfully, skipping the rest of the pattern or capture group

## Syntax (back)
<div>
  (*ACCEPT)
</div>

## Description (long)
<div>
  <div>
    <div>
      <div>
        This causes the regex to end successfully, skipping the
        rest of the pattern.
      </div>
      <div>
        If this token is inside a capturing group, only that
        capturing group is ended successfully at that particular
        location, while the parent pattern continues to execute.
      </div>
    </div>
  </div>
</div>

## Example code (back)
<div>
  /Candy.+?great(*ACCEPT).+bad/
</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">Candy tastes
great</span> but is bad for your teeth.
