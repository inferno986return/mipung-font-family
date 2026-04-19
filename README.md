# mipung-font-family

**Mipung** is an ambitious breath of fresh air that the fixes bugs and adds functionality to Breeze Sans font family. The original Breeze Sans and Breeze Sans Condensed were humanst sans-serif typefaces created by Dalton Maag on commission from Samsung as the UI font for the Tizen operating system.

Mipung adds *true italic*, variable weights and extra glyphs making it suitable for all kinds of projects!

## What are the Mipung fonts?

### Confirmed

**Mipung Sans Text** and **Mipung Sans Condensed** are derivatives of Breeze Sans and Breeze Sans Condensed respectively, and are separated out. These 2 fonts are the top priority!

### Potential expansion

* **Mipung Sans Display** looks a lot better at larger sizes especially 14pt or bigger for headings.

* **Mipung Sans Mono** has a nice ring to it and is a potential `monospaced` counterpart to **Mipung Sans Text** for source code and for terminal output that is highly readable at small sizes, especially at 12pt.

* **Mipung Sans Fallback** is a revival of the Breeze Fallback font, though don't expect much.

* **Mipung Emoji** an Emoji font derived from the Emoji included with Breeze Sans.

* **Mipung Sans Hangeul** supports the Korean Hangeul (Hangul) alphabet.

* **Mipung Sans Thai** supports the Thai script in the informal loopless style.

* **Mipung Serif** could be a cool humanist serif typeface but this is a very bold ambition.

## What new features are included in Mipung?

To its credit the original Breeze Sans has a truly impressive glyphset, so my wishlist feels more nitpicky that usual. Still we could add these, starting with Mipung Sans Text:

* **OpenType features**
    * text figures
    * small caps
    * stylistic sets, such as:
        * single-story 'a'
        * double-storey 'g'
        * serifed 'I'
        * tailed 'l'
        * 'Q' where the tail intersects the counter
        * horizontal baselined "1"
        * open '4'
* **New currency symbols**
    * Bitcoin U+20BF (₿)
    * UAE dirham U+20C3 (D with 2 strokes) - UAE dirham (or in the private use area – which can be moved to the correct codepoint in future) which is a Latin capital Đ, but with 2 horizontal strokes intersecting the centre in parallel similar to the Filipino peso (₱)
    * Saudi rial U+20C1 (⃁)
    * Azerbaijani manat U+20BC (₼)
* **More symbols**
    * Latin g with macron U+1E21 (ḡ)
    * Latin G with macron U+1E20 (Ḡ)
    * Phonograph symbol U+2117 (℗)
    * Copyleft symbol U+1F12F (🄯)
    * triple dagger U+2E4B (⹋)
    * triple prime mark U+2034 (‴)
    * quadruple prime mark U+2057 (⁗)	
* **Regional Cyrillic letterforms** – including Bulgarian and Serbian
* **Polytonic Greek** – niche, but it has historic and some comtemporary usage amongst the Estia newspaper and liturgy. The core monotonic glyphs are there so it's a matter of combining accents and breathing marks using OpenType `ccmp` (Glyph Composition/Decomposition) and the superscript Psi (ψ) and Omega (ω) for Unicode 18.
    * Estia (https://www.estianews.gr/) is the only news outlet in Greece that uses polytonic spelling.
    * Hippocratic Oath (https://el.wikisource.org/wiki/%CE%99%CF%80%CF%80%CE%BF%CE%BA%CF%81%CE%AC%CF%84%CE%B5%CE%B9%CE%BF%CF%82_%CF%8C%CF%81%CE%BA%CE%BF%CF%82) - the famous oath taken by medical doctors, short and uses most (if not all) of the polytonic diacritics
    * Rosetta Stone ()
    * Classical texts including *Iliad* and *Odyssey* by Homer.
* **Shavian** - niche, but I really like the writing system and want to represent text. No italics needed and we already have the Namer dot U+00B7 (·). See https://shavian.info/
* **Deseret** - unlikely, but it would compliment Shavian nicely!

Brisa Sans already supports tabular nums, so it shoudl include a 

## What needs to be done?

The font files are old and full of errors making them unsuitable for Google Fonts, though the source files worked on by Dalton Maag were never released to public meaning they will need to be recreated from scratch!

First, we need to fix the outstanding errors found with Google's Fontbakery tool that have been outlined in this issue using a tool like Glyphs (a popular professional font editor for macOS only): https://github.com/google/fonts/issues/2083

Then, we can generate the static fonts for both Mipung Sans Text and Mipung Sans Condensed allowing them to be installed simulateously (which I can't on Windows 11).

## Why the name Mipung?

Mipung (미풍) is a Korean word for 'breeze' from the Hanja 微風. Breeze Sans was comissioned for Samsung which is the largest corporation in South Korea.

The name is meant to be fun to say, and pay homage to the original team.

## What is the licence?

All Mipung fonts will be licenced from the previous Apache License 2.0 to SIL Open Font License (OFL) 1.1 without a Reserved Font Name (RFN) to meet the licencing requirement for Google Fonts.

The original Breeze Sans and Breeze Sans Condensed are licenced under Apache 2.0 similar to Google Android. This is a permissive licence that allows derivatives to be relicenced.

>**4. Redistribution.** You may reproduce and distribute copies of the Work or Derivative Works thereof in any medium, with or without modifications, and in Source or Object form, provided that You meet the following conditions:

>a. You must give any other recipients of the Work or Derivative Works a copy of this License; and
>You must cause any modified files to carry prominent notices stating that You changed the files; and

>b. You must retain, in the Source form of any Derivative Works that You distribute, all copyright, patent, trademark, and attribution notices from the Source form of the Work, excluding those notices that do not pertain to any part of the Derivative Works; and

>c. If the Work includes a "**NOTICE**" text file as part of its distribution, then any Derivative Works that You distribute must include a readable copy of the attribution notices contained within such NOTICE file, excluding those notices that do not pertain to any part of the Derivative Works, in at least one of the following places: within a NOTICE text file distributed as part of the Derivative Works; within the Source form or documentation, if provided along with the Derivative Works; or, within a display generated by the Derivative Works, if and wherever such third-party notices normally appear. The contents of the NOTICE file are for informational purposes only and do not modify the License. You may add Your own attribution notices within Derivative Works that You distribute, alongside or as an addendum to the NOTICE text from the Work, provided that such additional attribution notices cannot be construed as modifying the License.
>You may add Your own copyright statement to Your modifications and may provide additional or different license terms and conditions for use, reproduction, or distribution of Your modifications, or for any such Derivative Works as a whole, provided Your use, reproduction, and distribution of the Work otherwise complies with the conditions stated in this License.

## What is Breeze Sans?
Breeze Sans is a humanist sans-serif font family that was created in 2015 by the independent British type foundry Dalton Maag after being commissioned by Samsung as the user interface font for their open-source Tizen project.

Much like Roboto for Google Android, it was designed to be legible at very small sizes though it has humanistic flair.

The font family would have been expensive as there are 5 weights (Thin, Light Regular, Medium, Bold) for both Breeze Sans and Breeze Sans Condensed that each have support for the vast majority of the languages that use Latin, Greek and Cyrillic.

The mascot for Tizen is a pinwheel, so a breeze would compliment the pinwheel and make it spin!

See the Samsung developer documentation: https://developer.samsung.com/one-ui-watch-tizen/visual/typography.html

There is also a `BreezeColorEmoji.ttf` font and from running the Fonttools `ttx -z extfile BreezeColorEmoji.ttf` command I was able to extract a unique Emoji set I've never seen before. It would be cool to have unique Mipung Emoji to compliment Mipung Sans.

## What languages does Breeze Sans support?
I have performed language support testing with Hyperglot: https://hyperglot.rosettatype.com/support

Breeze Sans supports an astonishing 551 languages (with an estimated 3.4 billion speakers)!

428/503 Latin alphabet languages are marked as supported on Hyperglot (including archaic and constructed languages)

* **Latin** – French, Spanish, German, Vietnamese and Esperanto  
* **Greek** – Modern Greek and Pontic Greek, but not Ancient Greek i.e. polytonic Greek which I confirmed using Notepad and a copy of the Hippocratic Oath from Wikisource: https://el.wikisource.org/wiki/%CE%99%CF%80%CF%80%CE%BF%CE%BA%CF%81%CE%AC%CF%84%CE%B5%CE%B9%CE%BF%CF%82_%CF%8C%CF%81%CE%BA%CE%BF%CF%82 
* **Cyrillic** – everything except Northern Kurdish, Orok, Yagnobi and archaic Church Slavic

Other writing systems are unsupported including CJK, Arabic, Devanagari, etc. 

Esperanto is completely supported and there's even a Smesmilo symbol!

## What is Brisa Sans?

Brisa Sans is fork by Christiano Sobral (cssobral2013) which is a modification of the original Breeze Sans to include a black weight, true italics, tabularised figures and a variable font. The licence is the Apache License 2.0 so this could be used as a base.

The font does not work as intended within Brave and I want the condensed to be a separate family.

## What is Samsung Sans?

Samsung Sans is the latest official release of Breeze Sans with a new name. Not to be confused with the very geometric Samsung Sharpe.
