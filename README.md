---
title: Mozc UT Personal Name Dictionary
date: 2023-01-15
---

## Overview

Mozc UT Personal Name Dictionary is a dictionary for Mozc.

## License

Apache License, Version 2.0

## Usage

Add mozcdic-ut-*.txt to dictionary00.txt and build Mozc as usual.

```
tar xf mozcdic-ut-*.txt.tar.bz2
cat ../mozc-master/src/data/dictionary_oss/dictionary00.txt mozcdic-ut-*.txt > dictionary00.txt.new
mv dictionary00.txt.new ../mozc-master/src/data/dictionary_oss/dictionary00.txt
```

To modify the costs for words or merge multiple UT dictionaries into one, use this tool:

[merge-ut-dictionaries](https://github.com/utuhiro78/merge-ut-dictionaries)

[HOME](http://linuxplayers.g1.xrea.com/mozc-ut.html)
