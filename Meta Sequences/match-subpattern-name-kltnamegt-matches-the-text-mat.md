# Note
```
guid: l,:h58$Qat
notetype: Regex Syntax
```

### Tags
```
metasequence
regex
```

## Name


## Description
match subpattern 'name'

## Syntax (back)
\k<name>

## Description (long)
Matches the text matched by a previously named capture group.
Please note this feature is experimental in JavaScript and might not be supported by your browser.

<h3>Alternative versions</h3>:
1. <span style="color: rgb(255, 0, 0);">\k'name'</span><div>alternate syntax for \k<name> or \k{name}.</div><div>
</div><div>2. <span style="color: rgb(255, 0, 0);">\k{name}</span></div><div>alternate syntax for \k<name> or \k'name' and it is valid for .NET. Note that you cannot use curly brackets (?{name}a+) to name a capture group in PCRE</div>

## Example code (back)
/(?<first>a+) and again (\k<first>)/

## Example matching (back)
<div><span style="background-color: rgb(21, 181, 255);">aaaa and again aaaa</span>
</div><div>
</div><div><i>Full match: aaaa and again aaaa</i></div><div><i>Group 'first': aaaa</i></div><div><i>Group 2: aaaa</i></div><div><i>
</i></div><div><span><u style="">Alternative versions</u>:</span></div><div><i>1. </i><span style="color: rgb(255, 0, 255);">/(?'first'a+) and again (\k'first')/</span></div><div><span style="background-color: rgb(0, 170, 255);">
</span></div><div><span style="background-color: rgb(0, 170, 255);">aaaa and again aaaa</span></div><div><span style="color: rgb(255, 0, 255);">
</span></div><div><span>2. </span><span style="color: rgb(255, 0, 255);">/(?'first'a+) and again (\k{first})/</span></div><div><span style="background-color: rgb(21, 181, 255);">
</span></div><div><span style="background-color: rgb(21, 181, 255);">aaaa and again aaaa</span></div>
