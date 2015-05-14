# langdata
Source training data for Tesseract for lots of languages

Want to re-train tesseract for a specific language, by modifying/augmenting the original training data?
Then you have come to the right place!

If you want to find a language data set to run Tesseract, then look at our
[tessdata repository](https://github.com/tesseract-ocr/tessdata) instead.

To re-create the training of a single language, _lang,_ you need the following:
* All the data in the _lang_ directory.
* The corresponding unicharset/xheights files for the script(s) used by _lang._
* All the remaining non-lang-specific files in the top-level directory, such as `font_properties.`
* You also need to obtain the fonts needed to train the language.
Some languages were trained with commercially available fonts, so you will need to buy them in order to
reproduce the training exactly, or use substitutes.
