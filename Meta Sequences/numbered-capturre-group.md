# Note
```
guid: H[iMRyG1Te
notetype: Regex Syntax
```

### Tags
```
metasequence
regex
```

## Name
numbered capturre group

## Description
to match the 4<sup>th</sup> capture group

## Syntax (back)
\4

## Description (long)
Usually referred to as a "backreference", this will match a repeat of the text captured in a previous set of parentheses. To reduce ambiguity one may also use <code>\gn</code>, or <code>\g{n}</code> where <code>n</code> is a digit.
<h3>Alternative versions</h3>
<ol><li><code>\gn</code>: Matches the text captured by the nth group. n can contain more than one digit, if necessary. This may be useful in order to avoid ambiguity with octal characters.</li>
  <li><code>\g{n}</code>: Matches the text captured by the nth group. n represents the capture group number and can positionally refer to past capture groups as well; i.e. <code>\g{-2}</code> would be the second previous capture group, <code>\g{3}</code> would be the third capture group. This may be useful in order to avoid ambiguity with octal characters, or when a literal number needs to be matched immediately after a <code>\gn</code> in the regex.</li></ol>

## Example code (back)
/(.)\1/

## Example matching (back)
<div>Repeated le<span style="background-color: rgb(0, 170, 255);">tt</span>ers
</div><div>
</div><div><u>Alternative versions:</u></div><div><span style="color: rgb(255, 0, 255);">
</span></div><div>1. <span style="color: rgb(255, 0, 255);">/(a+) and (\g1)/</span></div><div><span style="background-color: rgb(21, 181, 255);">
</span></div><div><span style="background-color: rgb(21, 181, 255);">aaaa and aaaa</span>3</div><div>
</div><div><i>Full match: aaaa and aaaa</i></div><div><i>Group 1: aaaa</i></div><div><i>Group 2: aaaa</i></div><div><span style="color: rgb(255, 0, 255);">
</span></div><div><i>2. </i><span style="color: rgb(255, 0, 255);">/(a+) (and1) aaaa (\g{2}3)/</span></div><div><span style="background-color: rgb(21, 181, 255);">
</span></div><div><span style="background-color: rgb(21, 181, 255);">aaaa and1 aaaa and13</span></div><div><i>
</i></div><div><i>Full match: aaaa and 1 aaaa and13
Group 1: aaaa
Group 2: and1
Group 3: and13</i>
</div>
