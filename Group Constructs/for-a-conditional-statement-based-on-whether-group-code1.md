# Note
```
guid: hNpHkbEu*5
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name


## Description
for a conditional statement based on whether group <code>1</code> has been matched

## Syntax (back)
<div>(?(1)yes|no)</div>

## Description (long)
<div><div><div>If capturing group <code>1</code> was already matched, then this syntax matches the pattern before the vertical bar. Otherwise, matches the pattern after the vertical bar. </div><div>A group name, or a relative position (-1) in PCRE, can be used. </div><div>Global flag breaks conditionals.</div></div></div><div>
</div><div><div><u>Alternative versions</u>:</div><div><ol><li><code>(?(R)yes|no)</code>: If recursion of the whole pattern is successful, do something | otherwise do this.</li><li><code>(?(R&name)yes|no)</code>: In this case <code>(?(R&sub1)...|...)</code> checks if a call to <code>sub1</code> has been made. The first time the recursive conditional is parsed, the engine is in the process of matching what <code>sub1</code> requires, but it isn't because of a callback to <code>sub1</code>. Once we actually call <code>sub1</code> the conditional will return true, at which point <code>ction</code> matches.</li></ol></div></div>

## Example code (back)
<div>/(A candy)?(?(1) is true| is false)/</div>

## Example matching (back)
<span style="background-color: rgb(0, 170, 255);">A candy is true is false.</span><div>
</div><div><i>Full match: A candy is true</i></div><div><i>Group 1: A candy</i></div><div>
</div><div><u>Alternative versions</u>:
</div><div>1. <span style="color: rgb(255, 0, 255);">/<(?:(?(R)\w++|[^<>]*+)|(?R))*>/</span></div><div><div>
</div><div><div><span style="background-color: rgb(0, 170, 255);"><tag allows="for nested" <tag> /></span></div></div></div><div><span style="background-color: rgb(0, 170, 255);">
</span></div><div><div>2. <font color="#ff00ff">/(?<sub1> *fun(?(R&sub1)ction|ky))(?&sub1)/</font></div><div><div><span style="background-color: rgb(0, 170, 255);">funky function</span></div></div></div><div>
</div><div><div><i>Full match: funky function</i></div><div><i>Group 1: function</i></div></div>
