# hebrew-data

## transliteration

dotted hebrew is transliterated according to the transliteration scheme specified by transliteration-scheme.tsv

## word.tsv

this file contains words and expressions in hebrew with morphological and phonological info

* repr: transliterated dotted hebrew
* dotted: dotted hebrew
* pos: part of speech
* root: consonantal root
* gender: grammatical gender
* paradigm, plural_suffix, singular_suffix: these 3 columns indicate the word's declension paradigm
  use [hebrew-declension](https://github.com/twyair/hebrew-declension) to decline nouns
* phonemic: (modern israeli hebrew) pronunciation in IPA (with the following exceptions: ʃ->c, ʒ->j, j->y)

## hebrew wiktionary

pages-utf8.json contains a list of heb-wiktionary pages structured in a computer friendly way

pages-utf8.json.zip is available under the [Creative Commons Attribution-ShareAlike License](https://creativecommons.org/licenses/by-sa/3.0/)
