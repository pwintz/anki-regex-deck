# Note
```
guid: zjv<H}ti*B
notetype: Regex Syntax
```

### Tags
```
metasequence
regex
```

## Name
recursive capture group

## Description
Recurse n<sup>th</sup> capture group

## Syntax (back)
<div><div>\g<n></div></div>

## Description (long)
<div><div><div>Recurses <code>n</code>th capture group. <code>n</code> can contain more than one digit, and can be positional as well; i.e. <code>\g<-1></code> would be the previous capture group, <code>\g<+3></code> would be the third next capture group. Similar to <code>\g'n'</code>.</div></div></div><div>
</div><div><u>Alternative version</u>:</div><div><div><code>\g'n'</code>
</div><div><div>Recurses nth capture group. n can contain more than one digit, and can be positional as well; i.e. <code>\g'-1'</code> would be the previous capture group, <code>\g'3'</code> would be the third capture group. Similar to <code>\g<n></code>.</div></div></div>

## Example code (back)
/(a+) and (\g<1>)/

## Example matching (back)
<div><span style="background-color: rgb(21, 181, 255);">aaaa and aaaa</span>3
</div><div>
</div><div><u>Alternartive version</u>:</div><div><div><font color="#ff00ff">/(a+) and (\g'1')/</font></div><div>
</div><div><div><span style="background-color: rgb(21, 181, 255);">aaaa and aaaa</span>3</div></div></div>
