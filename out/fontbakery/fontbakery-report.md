## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[12] Sector-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"copyright 2023 sector mono, mateo broillet"

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Stricter unitsPerEm criteria for Google Fonts.  (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/unitsperem_strict">com.google.fonts/check/unitsperem_strict</a>)</summary><div>


* 🔥 **FAIL** Font em size (unitsPerEm) is 1200. If possible, please consider using 1000. Good values for unitsPerEm, though, are typically these: [16, 32, 64, 128, 256, 500, 512, 1000, 1024, 2000, 2048]. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1131 when it should be at least 1440 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̊ i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĭ i̇ ǐ i̒ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̇ i̧̊ i̧̋ ǐ̧ i̧̒ ĵ j̆ j̇ j̊ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'Mate' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> License URL matches License text on name table? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license_url">com.google.fonts/check/name/license_url</a>)</summary><div>


* ⚠ **WARN** Please consider using HTTPS URLs at name table entry [plat=3, enc=1, name=14] [code: http-in-license-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni030C.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

	- Glyph name: W	Contours detected: 4	Expected: 1 or 2

	- Glyph name: v	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 4	Expected: 1

	- Glyph name: braceleft	Contours detected: 2	Expected: 1

	- Glyph name: braceright	Contours detected: 2	Expected: 1

	- Glyph name: newGlyph	Contours detected: 0	Expected: 2 or 3

	- Glyph name: newGlyph.001	Contours detected: 0	Expected: 2 or 3

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: wgrave	Contours detected: 5	Expected: 2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: wacute	Contours detected: 5	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: arrowboth	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 4	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: W	Contours detected: 4	Expected: 1 or 2

	- Glyph name: Wacute	Contours detected: 5	Expected: 2

	- Glyph name: Wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: Wdieresis	Contours detected: 6	Expected: 3

	- Glyph name: Wgrave	Contours detected: 5	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: arrowboth	Contours detected: 2	Expected: 1

	- Glyph name: arrowupdn	Contours detected: 2	Expected: 1

	- Glyph name: asterisk	Contours detected: 2	Expected: 1 or 4

	- Glyph name: braceleft	Contours detected: 2	Expected: 1

	- Glyph name: braceright	Contours detected: 2	Expected: 1

	- Glyph name: eogonek	Contours detected: 3	Expected: 2

	- Glyph name: germandbls	Contours detected: 2	Expected: 1

	- Glyph name: infinity	Contours detected: 4	Expected: 3

	- Glyph name: uni1E9E	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: v	Contours detected: 2	Expected: 1

	- Glyph name: w	Contours detected: 4	Expected: 1

	- Glyph name: wacute	Contours detected: 5	Expected: 2

	- Glyph name: wcircumflex	Contours detected: 5	Expected: 2

	- Glyph name: wdieresis	Contours detected: 6	Expected: 3 

	- Glyph name: wgrave	Contours detected: 5	Expected: 2
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 382 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Aring (U+00C5): B<<336.0,858.0>-<345.0,849.0>-<346.0,837.0>>/B<<346.0,837.0>-<347.0,849.0>-<356.0,858.0>> = 9.527283381452328

	* Aring (U+00C5): B<<338.0,777.0>-<347.0,768.0>-<348.0,756.0>>/B<<348.0,756.0>-<349.0,768.0>-<358.0,777.0>> = 9.527283381452328

	* Aring (U+00C5): B<<356.0,811.0>-<347.0,820.0>-<346.0,832.0>>/B<<346.0,832.0>-<345.0,820.0>-<336.0,811.0>> = 9.527283381452328

	* Aring (U+00C5): B<<358.0,730.0>-<349.0,739.0>-<348.0,751.0>>/B<<348.0,751.0>-<347.0,739.0>-<338.0,730.0>> = 9.527283381452328

	* Uring (U+016E): B<<339.0,858.0>-<348.0,849.0>-<349.0,837.0>>/B<<349.0,837.0>-<350.0,849.0>-<359.0,858.0>> = 9.527283381452328

	* Uring (U+016E): B<<341.0,777.0>-<350.0,768.0>-<351.0,756.0>>/B<<351.0,756.0>-<352.0,768.0>-<361.0,777.0>> = 9.527283381452328

	* Uring (U+016E): B<<359.0,811.0>-<350.0,820.0>-<349.0,832.0>>/B<<349.0,832.0>-<348.0,820.0>-<339.0,811.0>> = 9.527283381452328

	* Uring (U+016E): B<<361.0,730.0>-<352.0,739.0>-<351.0,751.0>>/B<<351.0,751.0>-<350.0,739.0>-<341.0,730.0>> = 9.527283381452328

	* W (U+0057): B<<342.0,411.0>-<349.0,398.0>-<348.0,384.0>>/B<<348.0,384.0>-<348.0,397.0>-<355.0,410.0>> = 4.085616779974799

	* W (U+0057): B<<349.0,377.0>-<349.0,380.0>-<348.0,384.0>>/L<<348.0,384.0>--<348.0,378.0>> = 14.036243467926484

	* W (U+0057): B<<445.0,55.0>-<445.0,82.0>-<464.0,98.0>>/L<<464.0,98.0>--<462.0,97.0>> = 13.53585636913422

	* Wacute (U+1E82): B<<342.0,411.0>-<349.0,398.0>-<348.0,384.0>>/B<<348.0,384.0>-<348.0,397.0>-<355.0,410.0>> = 4.085616779974799

	* Wacute (U+1E82): B<<349.0,377.0>-<349.0,380.0>-<348.0,384.0>>/L<<348.0,384.0>--<348.0,378.0>> = 14.036243467926484

	* Wacute (U+1E82): B<<445.0,55.0>-<445.0,82.0>-<464.0,98.0>>/L<<464.0,98.0>--<462.0,97.0>> = 13.53585636913422

	* Wcircumflex (U+0174): B<<342.0,411.0>-<349.0,398.0>-<348.0,384.0>>/B<<348.0,384.0>-<348.0,397.0>-<355.0,410.0>> = 4.085616779974799

	* Wcircumflex (U+0174): B<<349.0,377.0>-<349.0,380.0>-<348.0,384.0>>/L<<348.0,384.0>--<348.0,378.0>> = 14.036243467926484

	* Wcircumflex (U+0174): B<<445.0,55.0>-<445.0,82.0>-<464.0,98.0>>/L<<464.0,98.0>--<462.0,97.0>> = 13.53585636913422

	* Wdieresis (U+1E84): B<<342.0,411.0>-<349.0,398.0>-<348.0,384.0>>/B<<348.0,384.0>-<348.0,397.0>-<355.0,410.0>> = 4.085616779974799

	* Wdieresis (U+1E84): B<<349.0,377.0>-<349.0,380.0>-<348.0,384.0>>/L<<348.0,384.0>--<348.0,378.0>> = 14.036243467926484

	* Wdieresis (U+1E84): B<<445.0,55.0>-<445.0,82.0>-<464.0,98.0>>/L<<464.0,98.0>--<462.0,97.0>> = 13.53585636913422

	* Wgrave (U+1E80): B<<342.0,411.0>-<349.0,398.0>-<348.0,384.0>>/B<<348.0,384.0>-<348.0,397.0>-<355.0,410.0>> = 4.085616779974799

	* Wgrave (U+1E80): B<<349.0,377.0>-<349.0,380.0>-<348.0,384.0>>/L<<348.0,384.0>--<348.0,378.0>> = 14.036243467926484

	* Wgrave (U+1E80): B<<445.0,55.0>-<445.0,82.0>-<464.0,98.0>>/L<<464.0,98.0>--<462.0,97.0>> = 13.53585636913422

	* Z (U+005A): B<<208.0,124.0>-<196.0,110.0>-<177.0,106.0>>/B<<177.0,106.0>-<180.0,106.0>-<184.0,105.0>> = 11.888658039627968

	* Zacute (U+0179): B<<208.0,124.0>-<196.0,110.0>-<177.0,106.0>>/B<<177.0,106.0>-<180.0,106.0>-<184.0,105.0>> = 11.888658039627968

	* Zcaron (U+017D): B<<208.0,124.0>-<196.0,110.0>-<177.0,106.0>>/B<<177.0,106.0>-<180.0,106.0>-<184.0,105.0>> = 11.888658039627968

	* Zdotaccent (U+017B): B<<208.0,124.0>-<196.0,110.0>-<177.0,106.0>>/B<<177.0,106.0>-<180.0,106.0>-<184.0,105.0>> = 11.888658039627968

	* aring (U+00E5): B<<339.0,706.0>-<348.0,697.0>-<349.0,685.0>>/B<<349.0,685.0>-<350.0,697.0>-<359.0,706.0>> = 9.527283381452328

	* aring (U+00E5): B<<341.0,625.0>-<350.0,616.0>-<351.0,604.0>>/B<<351.0,604.0>-<352.0,616.0>-<361.0,625.0>> = 9.527283381452328

	* aring (U+00E5): B<<359.0,659.0>-<350.0,668.0>-<349.0,680.0>>/B<<349.0,680.0>-<348.0,668.0>-<339.0,659.0>> = 9.527283381452328

	* aring (U+00E5): B<<361.0,578.0>-<352.0,587.0>-<351.0,599.0>>/B<<351.0,599.0>-<350.0,587.0>-<341.0,578.0>> = 9.527283381452328

	* ring (U+02DA): B<<339.0,672.0>-<348.0,663.0>-<349.0,651.0>>/B<<349.0,651.0>-<350.0,663.0>-<359.0,672.0>> = 9.527283381452328

	* ring (U+02DA): B<<341.0,591.0>-<350.0,582.0>-<351.0,570.0>>/B<<351.0,570.0>-<352.0,582.0>-<361.0,591.0>> = 9.527283381452328

	* ring (U+02DA): B<<359.0,625.0>-<350.0,634.0>-<349.0,646.0>>/B<<349.0,646.0>-<348.0,634.0>-<339.0,625.0>> = 9.527283381452328

	* ring (U+02DA): B<<361.0,544.0>-<352.0,553.0>-<351.0,565.0>>/B<<351.0,565.0>-<350.0,553.0>-<341.0,544.0>> = 9.527283381452328

	* uni030A (U+030A): B<<339.0,858.0>-<348.0,849.0>-<349.0,837.0>>/B<<349.0,837.0>-<350.0,849.0>-<359.0,858.0>> = 9.527283381452328

	* uni030A (U+030A): B<<341.0,777.0>-<350.0,768.0>-<351.0,756.0>>/B<<351.0,756.0>-<352.0,768.0>-<361.0,777.0>> = 9.527283381452328

	* uni030A (U+030A): B<<359.0,811.0>-<350.0,820.0>-<349.0,832.0>>/B<<349.0,832.0>-<348.0,820.0>-<339.0,811.0>> = 9.527283381452328

	* uni030A (U+030A): B<<361.0,730.0>-<352.0,739.0>-<351.0,751.0>>/B<<351.0,751.0>-<350.0,739.0>-<341.0,730.0>> = 9.527283381452328

	* uni1EF9 (U+1EF9): B<<221.0,410.0>-<209.0,410.0>-<188.0,414.0>>/B<<188.0,414.0>-<207.0,408.0>-<216.0,392.0>> = 6.741270506160247

	* uni1EF9 (U+1EF9): B<<260.5,283.5>-<255.0,263.0>-<237.0,253.0>>/B<<237.0,253.0>-<255.0,264.0>-<275.5,259.0>> = 2.374961515761332

	* uni1EF9 (U+1EF9): B<<425.5,259.0>-<446.0,264.0>-<464.0,253.0>>/B<<464.0,253.0>-<445.0,263.0>-<440.0,283.5>> = 3.6710250137784786

	* uni1EF9 (U+1EF9): B<<484.0,392.0>-<493.0,407.0>-<510.0,413.0>>/B<<510.0,413.0>-<492.0,410.0>-<481.0,410.0>> = 9.97771262015058

	* uring (U+016F): B<<339.0,708.0>-<348.0,699.0>-<349.0,687.0>>/B<<349.0,687.0>-<350.0,699.0>-<359.0,708.0>> = 9.527283381452328

	* uring (U+016F): B<<341.0,627.0>-<350.0,618.0>-<351.0,606.0>>/B<<351.0,606.0>-<352.0,618.0>-<361.0,627.0>> = 9.527283381452328

	* uring (U+016F): B<<359.0,661.0>-<350.0,670.0>-<349.0,682.0>>/B<<349.0,682.0>-<348.0,670.0>-<339.0,661.0>> = 9.527283381452328

	* uring (U+016F): B<<361.0,580.0>-<352.0,589.0>-<351.0,601.0>>/B<<351.0,601.0>-<350.0,589.0>-<341.0,580.0>> = 9.527283381452328

	* v (U+0076): B<<207.0,410.0>-<195.0,410.0>-<174.0,414.0>>/B<<174.0,414.0>-<193.0,408.0>-<202.0,392.0>> = 6.741270506160247

	* v (U+0076): B<<246.5,283.5>-<241.0,263.0>-<223.0,253.0>>/B<<223.0,253.0>-<241.0,264.0>-<261.5,259.0>> = 2.374961515761332

	* v (U+0076): B<<411.5,259.0>-<432.0,264.0>-<450.0,253.0>>/B<<450.0,253.0>-<431.0,263.0>-<426.0,283.5>> = 3.6710250137784786

	* v (U+0076): B<<470.0,392.0>-<479.0,407.0>-<496.0,413.0>>/B<<496.0,413.0>-<478.0,410.0>-<467.0,410.0>> = 9.97771262015058

	* w (U+0077): B<<285.0,411.5>-<300.0,423.0>-<316.0,418.0>>/B<<316.0,418.0>-<289.0,434.0>-<289.0,465.0>> = 13.296643320791533

	* w (U+0077): B<<345.0,410.0>-<338.0,410.0>-<331.0,412.0>>/B<<331.0,412.0>-<340.0,407.0>-<345.0,398.0>> = 13.109208198154267

	* wacute (U+1E83): B<<285.0,411.5>-<300.0,423.0>-<316.0,418.0>>/B<<316.0,418.0>-<289.0,434.0>-<289.0,465.0>> = 13.296643320791533

	* wacute (U+1E83): B<<345.0,410.0>-<338.0,410.0>-<331.0,412.0>>/B<<331.0,412.0>-<340.0,407.0>-<345.0,398.0>> = 13.109208198154267

	* wcircumflex (U+0175): B<<285.0,411.5>-<300.0,423.0>-<316.0,418.0>>/B<<316.0,418.0>-<289.0,434.0>-<289.0,465.0>> = 13.296643320791533

	* wcircumflex (U+0175): B<<345.0,410.0>-<338.0,410.0>-<331.0,412.0>>/B<<331.0,412.0>-<340.0,407.0>-<345.0,398.0>> = 13.109208198154267

	* wdieresis (U+1E85): B<<285.0,411.5>-<300.0,423.0>-<316.0,418.0>>/B<<316.0,418.0>-<289.0,434.0>-<289.0,465.0>> = 13.296643320791533

	* wdieresis (U+1E85): B<<345.0,410.0>-<338.0,410.0>-<331.0,412.0>>/B<<331.0,412.0>-<340.0,407.0>-<345.0,398.0>> = 13.109208198154267

	* wgrave (U+1E81): B<<285.0,411.5>-<300.0,423.0>-<316.0,418.0>>/B<<316.0,418.0>-<289.0,434.0>-<289.0,465.0>> = 13.296643320791533

	* wgrave (U+1E81): B<<345.0,410.0>-<338.0,410.0>-<331.0,412.0>>/B<<331.0,412.0>-<340.0,407.0>-<345.0,398.0>> = 13.109208198154267

	* y (U+0079): B<<221.0,410.0>-<209.0,410.0>-<188.0,414.0>>/B<<188.0,414.0>-<207.0,408.0>-<216.0,392.0>> = 6.741270506160247

	* y (U+0079): B<<260.5,283.5>-<255.0,263.0>-<237.0,253.0>>/B<<237.0,253.0>-<255.0,264.0>-<275.5,259.0>> = 2.374961515761332

	* y (U+0079): B<<425.5,259.0>-<446.0,264.0>-<464.0,253.0>>/B<<464.0,253.0>-<445.0,263.0>-<440.0,283.5>> = 3.6710250137784786

	* y (U+0079): B<<484.0,392.0>-<493.0,407.0>-<510.0,413.0>>/B<<510.0,413.0>-<492.0,410.0>-<481.0,410.0>> = 9.97771262015058

	* yacute (U+00FD): B<<221.0,410.0>-<209.0,410.0>-<188.0,414.0>>/B<<188.0,414.0>-<207.0,408.0>-<216.0,392.0>> = 6.741270506160247

	* yacute (U+00FD): B<<260.5,283.5>-<255.0,263.0>-<237.0,253.0>>/B<<237.0,253.0>-<255.0,264.0>-<275.5,259.0>> = 2.374961515761332

	* yacute (U+00FD): B<<425.5,259.0>-<446.0,264.0>-<464.0,253.0>>/B<<464.0,253.0>-<445.0,263.0>-<440.0,283.5>> = 3.6710250137784786

	* yacute (U+00FD): B<<484.0,392.0>-<493.0,407.0>-<510.0,413.0>>/B<<510.0,413.0>-<492.0,410.0>-<481.0,410.0>> = 9.97771262015058

	* ycircumflex (U+0177): B<<221.0,410.0>-<209.0,410.0>-<188.0,414.0>>/B<<188.0,414.0>-<207.0,408.0>-<216.0,392.0>> = 6.741270506160247

	* ycircumflex (U+0177): B<<260.5,283.5>-<255.0,263.0>-<237.0,253.0>>/B<<237.0,253.0>-<255.0,264.0>-<275.5,259.0>> = 2.374961515761332

	* ycircumflex (U+0177): B<<425.5,259.0>-<446.0,264.0>-<464.0,253.0>>/B<<464.0,253.0>-<445.0,263.0>-<440.0,283.5>> = 3.6710250137784786

	* ycircumflex (U+0177): B<<484.0,392.0>-<493.0,407.0>-<510.0,413.0>>/B<<510.0,413.0>-<492.0,410.0>-<481.0,410.0>> = 9.97771262015058

	* ydieresis (U+00FF): B<<221.0,410.0>-<209.0,410.0>-<188.0,414.0>>/B<<188.0,414.0>-<207.0,408.0>-<216.0,392.0>> = 6.741270506160247

	* ydieresis (U+00FF): B<<260.5,283.5>-<255.0,263.0>-<237.0,253.0>>/B<<237.0,253.0>-<255.0,264.0>-<275.5,259.0>> = 2.374961515761332

	* ydieresis (U+00FF): B<<425.5,259.0>-<446.0,264.0>-<464.0,253.0>>/B<<464.0,253.0>-<445.0,263.0>-<440.0,283.5>> = 3.6710250137784786

	* ydieresis (U+00FF): B<<484.0,392.0>-<493.0,407.0>-<510.0,413.0>>/B<<510.0,413.0>-<492.0,410.0>-<481.0,410.0>> = 9.97771262015058

	* ygrave (U+1EF3): B<<221.0,410.0>-<209.0,410.0>-<188.0,414.0>>/B<<188.0,414.0>-<207.0,408.0>-<216.0,392.0>> = 6.741270506160247

	* ygrave (U+1EF3): B<<260.5,283.5>-<255.0,263.0>-<237.0,253.0>>/B<<237.0,253.0>-<255.0,264.0>-<275.5,259.0>> = 2.374961515761332

	* ygrave (U+1EF3): B<<425.5,259.0>-<446.0,264.0>-<464.0,253.0>>/B<<464.0,253.0>-<445.0,263.0>-<440.0,283.5>> = 3.6710250137784786 

	* ygrave (U+1EF3): B<<484.0,392.0>-<493.0,407.0>-<510.0,413.0>>/B<<510.0,413.0>-<492.0,410.0>-<481.0,410.0>> = 9.97771262015058 [code: found-jaggy-segments]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 4 | 8 | 121 | 7 | 106 | 0 |
| 0% | 2% | 3% | 49% | 3% | 43% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
