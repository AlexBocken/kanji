# kanji

<img src="/../assets/kanji_front.png" alt="Front side with kanji displayed" width="300"> <img src="/../assets/kanji_back.png" alt="Back side revealing meaning of kanji" width="300">

<img src="/../assets/german_front.png" alt="Front side with german word displayed" width="300"> <img src="/../assets/german_back.png" alt="Back side revealing kanji with that meaning" width="300">

This is my personal vocab list to learn the Japanese Kanji which is using J.W. Heisig/R. Rauther's [__"Die Kanji - lernen und behalten 1"__](https://www.amazon.de/Bedeutung-Schreibweise-japanischen-Schriftzeichen-behalten/dp/3465041577/ref=sr_1_2?crid=2LX7RDRS8FEGW&dchild=1&keywords=die+kanji+lernen+und+behalten&qid=1595191168&sprefix=Die+kanji+lern%2Caps%2C154&sr=8-2)

I'm using Anki as my vocab program with the Addon __CrowdAnki__ to export in a diff-friendly json-file.

Since I'm using the German version of the book (and my native language is German) the cards are Japanese-German.
I'm following the guide of the book, only implementing hints if I have troubles with memorizing the words.
Feel free to base your vocab list off of mine via a fork, that's probably the best way to go ahead.

## Disclaimer
This deck is still heavily in developement, I will be adding new cards and hints from time to time, see the commits for more details.

Currently I'm using this [Kanji recognition site](https://kanji.sljfaq.org/draw-canvas.html). Seems a lot faster than having to rely on Google Translate (plus I don't have to use Google, which is a benefit in itself.)

## Primitves
I've been adding the seperately listed primitives as well, although that has some issues connected with it: Some/most of the primitives listed seperately do not have a unicode character associated with them. Thus I've been using two strategies:

1. Choosing a simple kanji which uses this primitive and stating with part of this kanji is meant
2. Misusing another unicode character which looks pretty much the same. For example for "Besen" as used in "雪" uses the charakter "ヨ" ("yo" from Katakana).

Both of these strategies are not optimal and I'm currently looking into other options. Inserting pictures does not seem optimal to me as well since those are heavily font-dependent. Reccommendations on how to solve this issue are always welcome.
