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

## format.py
Alternate way of text formatting, useful for relays without text formatting features (Glowingbear, WeechatAndroid, etc)

--
Usage:

```
text <*/_|> text <*/_|> more text

*: bold text
/: italic text
_: underlined text\n"
|: reversed (black on white) text
```

ie:
```
/format This /must/ be the *work* of an _enemy_ |stand|
```

will output (can't underline with this markdown):

![](https://raw.githubusercontent.com/Hairo/weechat-scripts/master/format.png)
