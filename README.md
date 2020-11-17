# kanji

<img src="/../assets/kanji_front.png" alt="Front side with kanji displayed" width="49%"> <img src="/../assets/kanji_back.png" alt="Back side revealing meaning of kanji" width="49%">

<img src="/../assets/german_front.png" alt="Front side with german word displayed" width="49%"> <img src="/../assets/german_back.png" alt="Back side revealing kanji with that meaning" width="49%">

This is my personal vocab list to learn the Japanese Kanji which is using J.W. Heisig/R. Rauther's [__"Die Kanji - lernen und behalten 1"__](https://www.amazon.de/Bedeutung-Schreibweise-japanischen-Schriftzeichen-behalten/dp/3465041577/ref=sr_1_2?crid=2LX7RDRS8FEGW&dchild=1&keywords=die+kanji+lernen+und+behalten&qid=1595191168&sprefix=Die+kanji+lern%2Caps%2C154&sr=8-2)

I'm using Anki as my vocab program with the Addon [CrowdAnki](https://github.com/Stvad/CrowdAnki) to export in a diff-friendly json-file. You can easily add it to yout Anki setup via the code given on [its AnkiWeb page](https://ankiweb.net/shared/info/1788670778).
From there it's a simple `File -> CrowdAnki: Import git repository`.

Since I'm using the German version of the book (and my native language is German) the cards are Japanese-German.
I'm following the guide of the book, only implementing hints if I have troubles with memorizing the words.
Feel free to base your vocab list off of mine via a fork, that's probably the best way to go ahead.

## Disclaimer
All cards have now been added.
Hints are only sporadically used and can only be expected for difficult kanjis in the first few hundred cards for now.

To get the Kanji unicode characters I used this [Kanji recognition site](https://kanji.sljfaq.org/draw-canvas.html).
Seems a lot faster than having to rely on Google Translate (plus I don't have to use Google, which is a benefit in itself.)

## Contributing

If you find a mistake, or have other ideas on how to improve the deck, please don't hesitate to [open a new issue](https://github.com/blinry/anki-fonts/issues)!

This deck is maintained using the [CrowdAnki](https://github.com/Stvad/CrowdAnki) add-on. If you want to contribute corrections or improvements yourself, follow these steps:

1. Make changes to the deck.
2. Install the [CrowdAnki add-on](https://ankiweb.net/shared/info/1788670778).
3. Fork and clone this repository.
4. Use `Export -> CrowdAnki Json representation` on the deck and chose the repository's base directory.
5. Commit the changes, and submit a pull request to this repository.

## Primitves
I've been adding the seperately listed primitives as well, although that has some issues connected with it: Some/most of the primitives listed seperately do not have a unicode character associated with them. Thus I've been using two strategies:

1. Choosing a simple kanji which uses this primitive and stating with part of this kanji is meant
2. Misusing another unicode character which looks pretty much the same. For example for "Besen" as used in "雪" uses the charakter "ヨ" ("yo" from Katakana).

Both of these strategies are not optimal and I'm currently looking into other options. Inserting pictures does not seem optimal to me as well since those are heavily font-dependent. Reccommendations on how to solve this issue are always welcome.

## Compounds
Compounds are added to the last kanji learned to completely understand the compound.
E.g. "週末" (Wochenende) is added at "週" (no. 340), not "末" (no. 230).

## Fonts
For Kanjis I'm using the IPAGothic font, for the stroke order I'm using Timothy Eyre's great font I found on [his website](https://www.nihilist.org.uk/). Please notice the license he has listed for this font.

### Importing via apkg

I've included an apkg file with the font files included as well as one apkg file without these font files.
Choose the one you prefer, the one with fonts has the additional benefit of synchronising the fonts with other devices.

### Importing via CrowdAnki

Either install these fonts seperately or add the ttfs to your `collection.media` Anki folder as `_ipag.ttf` and `_KanjiStrokeOrders.ttf`.
The latter method has the benefit of synchronising these fonts to your other devices as well.

## License

MIT
