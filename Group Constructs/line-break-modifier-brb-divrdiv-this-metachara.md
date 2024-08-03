# Note
```
guid: x&w5,GJS<h
notetype: Regex Syntax
```

### Tags
```
groupconstruct
linebreakmodifier
regex
```

## Name


## Description
Line break modifier - <b>R</b>

## Syntax (back)
<div>
  \R
</div>

## Description (long)
This metacharacter matches any unicode newline character or sequence thereof. Its behavior can be controlled by (*UTF) pattern modifiers. In (*UTF8) mode, '\R' will match the line separator, paragraph separator, carriage return, carriage return & newline sequence, line feed, vertical tab, form feed, and next line. When outside (*UTF8) mode, line and paragraph separators are not matched. Newline conventions can also be specified via (*BSR_ANYCRLF) and (*BSR_UNICODE).

## Example code (back)


## Example matching (back)

