## stand.py
weechat script to summon 「ＳＴＡＮＤＳ」 (from JoJo's Bizarre Adventure)

--
Converts the text between :: to fullwidth then adds 「 and 」.


ie:
```
/stand TOKI WO TOMARE :THE WORLD:
```

will output:
```
TOKI WO TOMARE 「ＴＨＥ ＷＯＲＬＤ」
```

## aformat.py
Alternate way of text formatting, useful for relays without text formatting features (Glowingbear, WeechatAndroid, etc)

--
Usage:

```
/aformat text <*/_|> text <*/_|> more text

*: bold text
/: italic text
_: underlined text
|: reversed (black on white) text
```

ie:
```
/aformat This /must/ be the *work* of an _enemy_ |stand|
```

will output (can't underline with github markdown >.>):

![](https://raw.githubusercontent.com/Hairo/weechat-scripts/master/format.png)
