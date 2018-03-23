# PYTHON

## Running
### CLI
- start
```
$ python
```
- end

`quit()` OR `ctrl + d`

### Script
```
$ python <FILE_PATH>
```

### Source Code Encoding
- default is `UTF-8`
- editing

```
# -*- coding: <ENCODING> -*-
```
EX: `# -*- coding: cp-1252 -*-` for using _Windows-1252_ encoding

## Introduction
### Comment
```
# <COMMENT_TEXT>
```
- Lay at start | end of lines
- If stay between `" "`, It's act as `hash character (#)` not a comment mark

### Numbers
- __int__: for integer
- __float__: for fractional

⚠ Division
- `/`: classic division, always return float

```
>>> 17 / 3 # return 5.666666666666667
```
- `//`: floor division discards the fractional part

```
>>> 17 // 3 # return 5
```

⚠ Power
- `**`: powers

```
>>> 2 ** 3 # return 8
```