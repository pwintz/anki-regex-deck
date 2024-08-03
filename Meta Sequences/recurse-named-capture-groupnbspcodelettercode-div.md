# Note
```
guid: I)s3^SW&|~
notetype: Regex Syntax
```

### Tags
```
metasequence
regex
```

## Name


## Description
Recurse named capture group <code>'letter'</code>

## Syntax (back)
<div><div>\g'letter'</div></div>

## Description (long)
or<code>\g<letter></code>.
Recurses the capture group called <code>letter</code>.

## Example code (back)


## Example matching (back)
<div><font color="#ff00ff">/(?'letter'a).*(\g'letter')/ </font></div><div>or<font color="#ff00ff"> </font></div><div><span style="color: rgb(255, 0, 255);">/(?<letter>a).*(\g<letter>)/</span></div><div>
</div><div><div><span style="background-color: rgb(0, 170, 255);">a plus a</span></div></div><div>
</div><div><i>Full match: a plus a</i></div><div><i>Group 'letter': a</i></div><div><i>Group 2: a</i></div>
