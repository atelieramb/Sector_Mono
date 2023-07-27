## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[25] Sector-Normal.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00A0 (NO-BREAK SPACE)


	- 0x010A (LATIN CAPITAL LETTER C WITH DOT ABOVE)


	- 0x011E (LATIN CAPITAL LETTER G WITH BREVE)


	- 0x0120 (LATIN CAPITAL LETTER G WITH DOT ABOVE)


	- 0x0126 (LATIN CAPITAL LETTER H WITH STROKE)


	- 0x0132 (LATIN CAPITAL LIGATURE IJ)


	- 0x0130 (LATIN CAPITAL LETTER I WITH DOT ABOVE)


	- 0x014A (LATIN CAPITAL LETTER ENG)


	- 0x0218 (LATIN CAPITAL LETTER S WITH COMMA BELOW)


	- 0x021A (LATIN CAPITAL LETTER T WITH COMMA BELOW)


	- 0x016C (LATIN CAPITAL LETTER U WITH BREVE)


	- 0x010B (LATIN SMALL LETTER C WITH DOT ABOVE)


	- 0x00F0 (LATIN SMALL LETTER ETH)


	- 0x011F (LATIN SMALL LETTER G WITH BREVE)


	- 0x0121 (LATIN SMALL LETTER G WITH DOT ABOVE)


	- 0x0127 (LATIN SMALL LETTER H WITH STROKE)


	- 0x0133 (LATIN SMALL LIGATURE IJ)


	- 0x0237 (LATIN SMALL LETTER DOTLESS J)


	- 0x014B (LATIN SMALL LETTER ENG)


	- 0x0219 (LATIN SMALL LETTER S WITH COMMA BELOW)


	- 0x00DF (LATIN SMALL LETTER SHARP S)


	- 0x021B (LATIN SMALL LETTER T WITH COMMA BELOW)


	- 0x016D (LATIN SMALL LETTER U WITH BREVE)


	- 0x00AA (FEMININE ORDINAL INDICATOR)
 

	- 0x00BA (MASCULINE ORDINAL INDICATOR)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check license file has good copyright string. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_copyright">com.google.fonts/check/license/OFL_copyright</a>)</summary><div>


* 🔥 **FAIL** First line in license file is:

"this font software is licensed under the sil open font license, version 1.1."

which does not match the expected format, similar to:

"Copyright 2022 The Familyname Project Authors (git url)" [code: bad-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check OFL body text is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/license/OFL_body_text">com.google.fonts/check/license/OFL_body_text</a>)</summary><div>


* 🔥 **FAIL** The OFL.txt body text is incorrect. Please use https://github.com/googlefonts/Unified-Font-Repository/blob/main/OFL.txt as a template. You should only modify the first line. [code: incorrect-ofl-body-text]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Are there non-ASCII characters in ASCII-only NAME table entries? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/ascii_only_entries">com.google.fonts/check/name/ascii_only_entries</a>)</summary><div>


* 🔥 **FAIL** Bad string at [nameID 0, 'utf_16_be']: 'b'Created in 2020 for Juan Arturo Garc&#237;a, updated in 2022. SIL Open Font License.'' [code: bad-string]
* 🔥 **FAIL** There are 1 strings containing non-ASCII characters in the ASCII-only NAME table entries. [code: non-ascii-strings]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Created in 2020 for Juan Arturo García, updated in 2022. SIL Open Font License." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Sector Normal | Sector Normal |
| Subfamily Name | Regular | Regular |
| Full Name | Sector Normal | Sector Normal Regular |
| Poscript Name | Sector-Normal | SectorNormal-Regular |
| Typographic Family Name | Sector | N/A |
| Typographic Subfamily Name | Normal | N/A | [code: bad-names]
* ⚠ **WARN** Regular missing from full name [code: lacks-regular]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "280" it should be 0 [code: bad-OS/2.sTypoLineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/Sector-Normal.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 262, but got 240 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (680) and hhea ascent (960) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Font contains glyphs for whitespace characters? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphs">com.google.fonts/check/whitespace_glyphs</a>)</summary><div>


* 🔥 **FAIL** Whitespace glyph missing for codepoint 0x00A0. [code: missing-whitespace-glyph-0x00A0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: i̋ j̀ j́ j̃ j̄ j̈ į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: ĭ ǐ i̒ ĩ̦ ĭ̦ i̦̇ i̦̊ i̦̋ ǐ̦ i̦̒ ĭ̧ i̧̋ ǐ̧ i̧̒ ĵ j̆ j̇ j̊ j̋ ǰ [code: soft-dotted]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking correctness of monospaced metadata. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/monospace">com.google.fonts/check/monospace</a>)</summary><div>


* 🔥 **FAIL** On monospaced fonts, the value of post.isFixedPitch must be set to a non-zero value (meaning 'fixed width monospaced'), but got 0 instead. [code: mono-bad-post-isFixedPitch]
* 🔥 **FAIL** The PANOSE numbers are incorrect for a monospaced font. Note: Family Type is set to 0, which does not seem right. [code: mono-bad-panose]
* ⚠ **WARN** The OpenType spec recomments at https://learn.microsoft.com/en-us/typography/opentype/spec/recom#hhea-table that hhea.numberOfHMetrics be set to 3 but this font has 329 instead.
Please read https://github.com/fonttools/fonttools/issues/3014 to decide whether this makes sense for your font. [code: bad-numberOfHMetrics]
* ⚠ **WARN** Font is monospaced but 2 glyphs (0.59%) have a different width. You should check the widths of: ['uni1E9E', 'trademark'] [code: mono-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure Stylistic Sets have description. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/stylisticset_description">com.google.fonts/check/stylisticset_description</a>)</summary><div>


* ⚠ **WARN** The stylistic set ss01 lacks a description string on the 'name' table. [code: missing-description]
* ⚠ **WARN** The stylistic set ss02 lacks a description string on the 'name' table. [code: missing-description]
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
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* asciicircum (U+005E): L<<389.0,663.0>--<389.0,663.0>> -> L<<389.0,663.0>--<389.0,663.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* Aring (U+00C5): B<<339.0,858.0>-<348.0,849.0>-<349.0,837.0>>/B<<349.0,837.0>-<350.0,849.0>-<359.0,858.0>> = 9.527283381452328

	* Aring (U+00C5): B<<341.0,777.0>-<350.0,768.0>-<351.0,756.0>>/B<<351.0,756.0>-<352.0,768.0>-<361.0,777.0>> = 9.527283381452328

	* Aring (U+00C5): B<<359.0,811.0>-<350.0,820.0>-<349.0,832.0>>/B<<349.0,832.0>-<348.0,820.0>-<339.0,811.0>> = 9.527283381452328

	* Aring (U+00C5): B<<361.0,730.0>-<352.0,739.0>-<351.0,751.0>>/B<<351.0,751.0>-<350.0,739.0>-<341.0,730.0>> = 9.527283381452328

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

	* aring (U+00E5): B<<339.0,672.0>-<348.0,663.0>-<349.0,651.0>>/B<<349.0,651.0>-<350.0,663.0>-<359.0,672.0>> = 9.527283381452328

	* aring (U+00E5): B<<341.0,591.0>-<350.0,582.0>-<351.0,570.0>>/B<<351.0,570.0>-<352.0,582.0>-<361.0,591.0>> = 9.527283381452328

	* aring (U+00E5): B<<359.0,625.0>-<350.0,634.0>-<349.0,646.0>>/B<<349.0,646.0>-<348.0,634.0>-<339.0,625.0>> = 9.527283381452328

	* aring (U+00E5): B<<361.0,544.0>-<352.0,553.0>-<351.0,565.0>>/B<<351.0,565.0>-<350.0,553.0>-<341.0,544.0>> = 9.527283381452328

	* ring (U+02DA): B<<339.0,672.0>-<348.0,663.0>-<349.0,651.0>>/B<<349.0,651.0>-<350.0,663.0>-<359.0,672.0>> = 9.527283381452328

	* ring (U+02DA): B<<341.0,591.0>-<350.0,582.0>-<351.0,570.0>>/B<<351.0,570.0>-<352.0,582.0>-<361.0,591.0>> = 9.527283381452328

	* ring (U+02DA): B<<359.0,625.0>-<350.0,634.0>-<349.0,646.0>>/B<<349.0,646.0>-<348.0,634.0>-<339.0,625.0>> = 9.527283381452328

	* ring (U+02DA): B<<361.0,544.0>-<352.0,553.0>-<351.0,565.0>>/B<<351.0,565.0>-<350.0,553.0>-<341.0,544.0>> = 9.527283381452328

	* uni030A (U+030A): B<<339.0,858.0>-<348.0,849.0>-<349.0,837.0>>/B<<349.0,837.0>-<350.0,849.0>-<359.0,858.0>> = 9.527283381452328

	* uni030A (U+030A): B<<341.0,777.0>-<350.0,768.0>-<351.0,756.0>>/B<<351.0,756.0>-<352.0,768.0>-<361.0,777.0>> = 9.527283381452328

	* uni030A (U+030A): B<<359.0,811.0>-<350.0,820.0>-<349.0,832.0>>/B<<349.0,832.0>-<348.0,820.0>-<339.0,811.0>> = 9.527283381452328

	* uni030A (U+030A): B<<361.0,730.0>-<352.0,739.0>-<351.0,751.0>>/B<<351.0,751.0>-<350.0,739.0>-<341.0,730.0>> = 9.527283381452328

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
| 0 | 15 | 10 | 131 | 7 | 83 | 0 |
| 0% | 6% | 4% | 53% | 3% | 34% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
