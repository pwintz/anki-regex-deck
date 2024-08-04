# Note
```
guid: H1|VCI!N-&
notetype: Regex Syntax
```

### Tags
```
groupconstruct
regex
```

## Name
predefine named patterns

## Description
to define patterns before using them

## Syntax (back)
<div>(?(DEFINE)...)</div>

## Description (long)
The <code>DEFINE</code> group is completely ignored by regex. It gets treated like <code>var name="value"</code>, whereas you can recall the specific pattern for use via its name. Multiple patterns can be defined in the same <code>DEFINE</code> group.<pre>(?(DEFINE)(?'numbers'\d+)(?'lowercase'[a-z]+)(?'uppercase'[A-Z]+))</pre>

## Example code (back)
<div>/(?(DEFINE)(?'letters'[a-z]+))(?P>letters)/</div>

## Example matching (back)
123 <span style="background-color: rgb(0, 170, 255);">letters</span> 123
