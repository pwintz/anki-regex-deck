# Note
```
guid: pYRD_jFlP!
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name
recurisve named group match

## Description
to recursively match a capture group named <code>foo</code>

## Syntax (back)
(?&foo)

## Description (long)
Recursively matches the given named capture group. 

Python supports <code>(?P=named_group)</code>, but '<code>named_group</code>' has to be previously defined.<div><h3>Alternative version:</h3></div><div><code>(?P>name)</code>
</div>

## Example code (back)
/(?&named_group)[a-z ]+(?'named_group'[tb]oys)/

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">boys like toys</span>.<div>
</div><div><i>Full match: boys like toys</i></div><div><i>Group 1: toys</i></div><div><i>
</i></div><div><u>Alternative version:</u></div><div><div><font color="#ff00ff">/((?P>who))[a-z ]+(?P<who>one)/</font></div><div><font color="#ff00ff">
</font></div><div><div><span style="background-color: rgb(0, 170, 255);">one does not simply eat one</span> pie</div></div></div><div>
</div><div><i>Full match: one does not simply eat one</i></div><div><i>Group 1: one
</i></div><div><i>Group `who`: one</i></div>
