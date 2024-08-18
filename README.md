# kanji

<img src="/../assets/reveal_stroke_order.gif" alt="Front side with kanji displayed" width="49%"> <img src="/../assets/kanji_back.png" alt="Back side revealing meaning of kanji" width="49%">

<img src="/../assets/german_front.png" alt="Front side with german word displayed" width="49%"> <img src="/../assets/german_back.png" alt="Back side revealing kanji with that meaning" width="49%">

This is my personal vocab list to learn the Japanese Kanji which is using J.W. Heisig/R. Rauther's [__"Die Kanji - lernen und behalten 1"__](https://www.amazon.de/Bedeutung-Schreibweise-japanischen-Schriftzeichen-behalten/dp/3465041577/ref=sr_1_2?crid=2LX7RDRS8FEGW&dchild=1&keywords=die+kanji+lernen+und+behalten&qid=1595191168&sprefix=Die+kanji+lern%2Caps%2C154&sr=8-2) as well as for the third book in the series.
All in all it includes 3000 Kanjis and 171 primitives.

Since I'm using the German version of the book (and my native language is German) the cards are Japanese-German.
Most of the hints I have gotten from [another Deck for the same book](https://ankiweb.net/shared/info/1354129669) (probably should have looked for something like this earlier).
A big thanks to the contributors of that deck for sharing their work.
For hints from the 3rd book I have found mostly English sentences online. These are still in the process of being translated in to German (if applicable) or being replaced by better sentences.

Feel free to base your vocab list off of mine via a fork, that's probably the best way to go ahead.

## Import

I'm using Anki as my vocab program with the Addon [CrowdAnki](https://github.com/Stvad/CrowdAnki) to export in a diff-friendly Json-file.
You can easily add it to your Anki setup via the code given on [its AnkiWeb page](https://ankiweb.net/shared/info/1788670778).
From there it's a simple `File -> CrowdAnki: Import git repository`.

If you're using different Anki applications, please see the release section for `.apkg` files.
These will not be as up-to-date as the `json` files used by CrowndAnki.

## Contributing

If you find a mistake, or have other ideas on how to improve the deck, please don't hesitate to [open a new issue](https://github.com/AlexBocken/kanji/issues)!

This deck is maintained using the [CrowdAnki](https://github.com/Stvad/CrowdAnki) add-on. If you want to contribute corrections or improvements yourself, follow these steps:

1. Make changes to the deck.
2. Install the [CrowdAnki add-on](https://ankiweb.net/shared/info/1788670778).
3. Fork and clone this repository.
4. Use `Export -> CrowdAnki Json representation` on the deck and chose the repository's base directory.
5. Commit the changes, and submit a pull request to this repository.

### Disclaimer

Hints are now been mostly implemented, but need correct formatting to highlight meaning and primitives in the sentences.
The correct formatting (and German sentences) are as of today (20211128) at no.2308.

## Primitives
I'm mapping primitives which cannot be found in the Unicode standard to a section of the Ethiopian Alphabet.
My custom fonts then display these primitives instead of the Ethiopian letters.
This means that the symbol displayed in Browse mode is incorrect for primitives.

## Composites
All composites of the 2nd and 3rd book have now been implemented.
Formatting on the cards has been improved. As can be seen in the above pictures.

## Readings
I've pulled all available On- Kun- and Nanori-readings from http://nihongo.monash.edu/ using a script.
If you want to see my awful coding practices for such one off stuff which just needs to generate a file once, look into the `scripts` branch of this git repository.

## Fonts
For Kanjis I'm using the IPAGothic font, for the stroke order I'm using Timothy Eyre's (or is it Ulrich Apel's? It's not quite clear to me.) great font I found on [his website](https://www.nihilist.org.uk/).
The licenses for these fonts can also be found in the `licenses` folder of this git repository.
I believe me distributing these fonts with this project is not a breach of contract, but I am also not a lawyer.

Note: These fonts have been slightly altered by me.
This is mostly done to add support for Heisig's primitives system.
Otherwise, sometimes, a Kanji might slightly differ from the original font to more accurately reflect how Heisig has it written.
This is mostly removing a single drop of water or similar.
For example, Heisig does not seem to like to use '辶' and almost always prefers '⻌'.


## License

AGPL3

(Fonts separate)
