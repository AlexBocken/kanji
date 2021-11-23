# kanji

<img src="/../assets/reveal_stroke_order.gif" alt="Front side with kanji displayed" width="49%"> <img src="/../assets/kanji_back.png" alt="Back side revealing meaning of kanji" width="49%">

<img src="/../assets/german_front.png" alt="Front side with german word displayed" width="49%"> <img src="/../assets/german_back.png" alt="Back side revealing kanji with that meaning" width="49%">

This is my personal vocab list to learn the Japanese Kanji which is using J.W. Heisig/R. Rauther's [__"Die Kanji - lernen und behalten 1"__](https://www.amazon.de/Bedeutung-Schreibweise-japanischen-Schriftzeichen-behalten/dp/3465041577/ref=sr_1_2?crid=2LX7RDRS8FEGW&dchild=1&keywords=die+kanji+lernen+und+behalten&qid=1595191168&sprefix=Die+kanji+lern%2Caps%2C154&sr=8-2) as well as for the third book in the series.
All in all it includes 3000 Kanjis and 171 primitives.

Since I'm using the German version of the book (and my native language is German) the cards are Japanese-German.
Most of the hints I have gotten from [another Deck for the same book](https://ankiweb.net/shared/info/1354129669) (probably should have looked for something like this earlier).
A big thanks to the contributors of that deck for sharing their work.
These have not yet been formatted corrected (i.e. bold for the word in question and italics for components of the kanji).

Feel free to base your vocab list off of mine via a fork, that's probably the best way to go ahead.

## Import

I'm using Anki as my vocab program with the Addon [CrowdAnki](https://github.com/Stvad/CrowdAnki) to export in a diff-friendly json-file.
You can easily add it to yout Anki setup via the code given on [its AnkiWeb page](https://ankiweb.net/shared/info/1788670778).
From there it's a simple `File -> CrowdAnki: Import git repository`.

If you're using different Anki applications, please see the release section for `.apkg` files.
These will not be as up to date as the `json` files used by CrowndAnki.

## Contributing

If you find a mistake, or have other ideas on how to improve the deck, please don't hesitate to [open a new issue](https://github.com/blinry/anki-fonts/issues)!

This deck is maintained using the [CrowdAnki](https://github.com/Stvad/CrowdAnki) add-on. If you want to contribute corrections or improvements yourself, follow these steps:

1. Make changes to the deck.
2. Install the [CrowdAnki add-on](https://ankiweb.net/shared/info/1788670778).
3. Fork and clone this repository.
4. Use `Export -> CrowdAnki Json representation` on the deck and chose the repository's base directory.
5. Commit the changes, and submit a pull request to this repository.

### Disclaimer

Hints are now implemented, but need correct formatting to highlight meaning and primitives in the sentences.
The correct formatting is as of today (20210111) at no.1005 and will gain roughly ten new correctly formatted hints per day.
To get the Kanji unicode characters I used this [Kanji recognition site](https://kanji.sljfaq.org/draw-canvas.html).
Seems a lot faster than having to rely on Google Translate (plus I don't have to use Google, which is a benefit in itself.)

## Primitves
I'm mapping primitives which cannot be found in the Unicode standard to a section of the Ethiopian Alphabet.
My custom fonts then display these primitives instead of the ethiopian letters.
This means that the symbol displayed in Browse mode is incorrect for primitives.

## Composites
I have now implemented all composites from the 2nd book.
The composites from the 3rd book should soon follow.
The formatting of how these composites are represented will gradually be improved.
Let's hope Javascript can wrangle these multiple fields into something coherent on the cards.

## Readings
I've pulled all available On- Kun- and Nanori-readings from http://nihongo.monash.edu/ using a script.
These readings are not yet displayed on the cards themselves but are listed in the notes.
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

GPL3 Affero

(Fonts seperate)
