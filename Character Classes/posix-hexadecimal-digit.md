# Note
```
guid: zI;@6xGI[^
notetype: Regex Syntax
```

### Tags
```
characterclass
regex
```

## Name
POSIX hexadecimal digit

## Description
to match any hexadecimal digit

## Syntax (back)
<div>
  [[:xdigit:]]
</div>

## Description (long)
Matches hexadecimal digits, case insensitive. Equivalent to
<code>[0-9a-fA-F]</code>

## Example code (back)
/[[:xdigit:]]+/g

## Example matching (back)
h<span style="background-color: rgb(0, 170, 255);">e</span>x
<span style="background-color: rgb(0, 170, 255);">123</span>!
n<span style="background-color: rgb(0, 170, 255);">a</span>vy
<span style="background-color: rgb(0, 170, 255);">b</span>lue
<span style="background-color: rgb(0, 170, 255);">f</span>or
<span style="background-color: rgb(0, 170, 255);">c</span>ss:
#<span style="background-color: rgb(0, 170, 255);">0A0AB5</span>
