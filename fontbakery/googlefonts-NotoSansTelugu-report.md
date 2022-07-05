## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansTelugu/googlefonts/ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Each font in a family must have the same set of vertical metrics values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/vertical_metrics">com.google.fonts/check/family/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** sTypoAscender is not the same across the family:
Noto Sans Telugu Black: 869
Noto Sans Telugu Bold: 869
Noto Sans Telugu ExtraBold: 869
Noto Sans Telugu ExtraLight: 869
Noto Sans Telugu Light: 869
Noto Sans Telugu Medium: 869
Noto Sans Telugu Regular: 869
Noto Sans Telugu SemiBold: 869
Noto Sans Telugu Thin: 869
Noto Sans Telugu UI Black: 1069
Noto Sans Telugu UI Bold: 1069
Noto Sans Telugu UI ExtraBold: 1069
Noto Sans Telugu UI ExtraLight: 1069
Noto Sans Telugu UI Light: 1069
Noto Sans Telugu UI Medium: 1069
Noto Sans Telugu UI Regular: 1069
Noto Sans Telugu UI SemiBold: 1069
Noto Sans Telugu UI Thin: 1069 [code: sTypoAscender-mismatch]
* 🔥 **FAIL** sTypoDescender is not the same across the family:
Noto Sans Telugu Black: -483
Noto Sans Telugu Bold: -483
Noto Sans Telugu ExtraBold: -483
Noto Sans Telugu ExtraLight: -483
Noto Sans Telugu Light: -483
Noto Sans Telugu Medium: -483
Noto Sans Telugu Regular: -483
Noto Sans Telugu SemiBold: -483
Noto Sans Telugu Thin: -483
Noto Sans Telugu UI Black: -293
Noto Sans Telugu UI Bold: -293
Noto Sans Telugu UI ExtraBold: -293
Noto Sans Telugu UI ExtraLight: -293
Noto Sans Telugu UI Light: -293
Noto Sans Telugu UI Medium: -293
Noto Sans Telugu UI Regular: -293
Noto Sans Telugu UI SemiBold: -293
Noto Sans Telugu UI Thin: -293 [code: sTypoDescender-mismatch]
* 🔥 **FAIL** usWinAscent is not the same across the family:
Noto Sans Telugu Black: 869
Noto Sans Telugu Bold: 869
Noto Sans Telugu ExtraBold: 869
Noto Sans Telugu ExtraLight: 869
Noto Sans Telugu Light: 869
Noto Sans Telugu Medium: 869
Noto Sans Telugu Regular: 869
Noto Sans Telugu SemiBold: 869
Noto Sans Telugu Thin: 869
Noto Sans Telugu UI Black: 1069
Noto Sans Telugu UI Bold: 1069
Noto Sans Telugu UI ExtraBold: 1069
Noto Sans Telugu UI ExtraLight: 1069
Noto Sans Telugu UI Light: 1069
Noto Sans Telugu UI Medium: 1069
Noto Sans Telugu UI Regular: 1069
Noto Sans Telugu UI SemiBold: 1069
Noto Sans Telugu UI Thin: 1069 [code: usWinAscent-mismatch]
* 🔥 **FAIL** usWinDescent is not the same across the family:
Noto Sans Telugu Black: 483
Noto Sans Telugu Bold: 483
Noto Sans Telugu ExtraBold: 483
Noto Sans Telugu ExtraLight: 483
Noto Sans Telugu Light: 483
Noto Sans Telugu Medium: 483
Noto Sans Telugu Regular: 483
Noto Sans Telugu SemiBold: 483
Noto Sans Telugu Thin: 483
Noto Sans Telugu UI Black: 293
Noto Sans Telugu UI Bold: 293
Noto Sans Telugu UI ExtraBold: 293
Noto Sans Telugu UI ExtraLight: 293
Noto Sans Telugu UI Light: 293
Noto Sans Telugu UI Medium: 293
Noto Sans Telugu UI Regular: 293
Noto Sans Telugu UI SemiBold: 293
Noto Sans Telugu UI Thin: 293 [code: usWinDescent-mismatch]
* 🔥 **FAIL** ascent is not the same across the family:
Noto Sans Telugu Black: 869
Noto Sans Telugu Bold: 869
Noto Sans Telugu ExtraBold: 869
Noto Sans Telugu ExtraLight: 869
Noto Sans Telugu Light: 869
Noto Sans Telugu Medium: 869
Noto Sans Telugu Regular: 869
Noto Sans Telugu SemiBold: 869
Noto Sans Telugu Thin: 869
Noto Sans Telugu UI Black: 1069
Noto Sans Telugu UI Bold: 1069
Noto Sans Telugu UI ExtraBold: 1069
Noto Sans Telugu UI ExtraLight: 1069
Noto Sans Telugu UI Light: 1069
Noto Sans Telugu UI Medium: 1069
Noto Sans Telugu UI Regular: 1069
Noto Sans Telugu UI SemiBold: 1069
Noto Sans Telugu UI Thin: 1069 [code: ascent-mismatch]
* 🔥 **FAIL** descent is not the same across the family:
Noto Sans Telugu Black: -483
Noto Sans Telugu Bold: -483
Noto Sans Telugu ExtraBold: -483
Noto Sans Telugu ExtraLight: -483
Noto Sans Telugu Light: -483
Noto Sans Telugu Medium: -483
Noto Sans Telugu Regular: -483
Noto Sans Telugu SemiBold: -483
Noto Sans Telugu Thin: -483
Noto Sans Telugu UI Black: -293
Noto Sans Telugu UI Bold: -293
Noto Sans Telugu UI ExtraBold: -293
Noto Sans Telugu UI ExtraLight: -293
Noto Sans Telugu UI Light: -293
Noto Sans Telugu UI Medium: -293
Noto Sans Telugu UI Regular: -293
Noto Sans Telugu UI SemiBold: -293
Noto Sans Telugu UI Thin: -293 [code: descent-mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[13] NotoSansTelugu-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhauvoweltelu
	* reevoweltelu
	* ssauvoweltelu
	* tsivoweltelu
	* ttaalttelu
	* rivoweltelu
	* seevoweltelu
	* givoweltelu
	* rrratelu
	* catelu and 531 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* three.telu (U+0033): X=125.5,Y=-2.0 (should be at baseline 0?)

	* C (U+0043): X=490.5,Y=-0.5 (should be at baseline 0?)

	* G (U+0047): X=545.5,Y=2.0 (should be at baseline 0?)

	* a (U+0061): X=282.0,Y=-1.5 (should be at baseline 0?)

	* f (U+0066): X=365.5,Y=622.0 (should be at cap-height 620?)

	* g (U+0067): X=577.0,Y=-1.0 (should be at baseline 0?)

	* g (U+0067): X=386.0,Y=1.0 (should be at baseline 0?)

	* t (U+0074): X=363.0,Y=-1.0 (should be at baseline 0?)

	* copyright (U+00A9): X=148.5,Y=620.5 (should be at cap-height 620?) 

	* And 87 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] NotoSansTelugu-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhauvoweltelu
	* reevoweltelu
	* ssauvoweltelu
	* tsivoweltelu
	* ttaalttelu
	* rivoweltelu
	* seevoweltelu
	* givoweltelu
	* rrratelu
	* catelu and 442 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansTelugu-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhauvoweltelu
	* reevoweltelu
	* ssauvoweltelu
	* tsivoweltelu
	* ttaalttelu
	* rivoweltelu
	* seevoweltelu
	* givoweltelu
	* rrratelu
	* catelu and 464 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,209.5>-<333.0,177.0>-<335.0,156.0>>/B<<335.0,156.0>-<338.0,177.0>-<344.5,209.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357 

	* And 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansTelugu-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* iitelu
	* nnaavoweltelu
	* uni0C7B and rrraavoweltelu
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<112.0,39.0>--<112.0,37.0>>

	* M (U+004D) contains a short segment L<<140.0,668.0>--<137.0,668.0>>

	* M (U+004D) contains a short segment L<<424.0,64.0>--<427.0,64.0>>

	* M (U+004D) contains a short segment L<<440.0,0.0>--<409.0,0.0>>

	* N (U+004E) contains a short segment L<<139.0,642.0>--<137.0,642.0>>

	* N (U+004E) contains a short segment L<<570.0,74.0>--<572.0,74.0>>

	* a (U+0061) contains a short segment L<<401.0,98.0>--<399.0,98.0>>

	* d (U+0064) contains a short segment L<<465.0,105.0>--<463.0,105.0>>

	* k (U+006B) contains a short segment L<<126.0,218.0>--<126.0,218.0>>

	* m (U+006D) contains a short segment L<<126.0,438.0>--<129.0,438.0>> 

	* And 79 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<586.0,396.5>-<603.0,390.0>-<617.0,380.0>>/B<<617.0,380.0>-<594.0,405.0>-<558.5,422.0>> = 11.8482662384144 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[14] NotoSansTelugu-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhauvoweltelu
	* dzeevoweltelu
	* iitelu
	* ddaavoweltelu
	* autelu
	* lllaavoweltelu
	* lllauvoweltelu
	* ngeevoweltelu
	* lloovoweltelu
	* dzovoweltelu and 52 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* zero.telu (U+0030): X=151.5,Y=619.5 (should be at cap-height 620?)

	* three.telu (U+0033): X=136.0,Y=-0.5 (should be at baseline 0?)

	* three.telu (U+0033): X=426.5,Y=618.0 (should be at cap-height 620?)

	* eight.telu (U+0038): X=434.0,Y=621.5 (should be at cap-height 620?)

	* nine.telu (U+0039): X=98.0,Y=1.0 (should be at baseline 0?)

	* question.telu (U+003F): X=364.5,Y=618.5 (should be at cap-height 620?)

	* question.telu (U+003F): X=62.0,Y=618.0 (should be at cap-height 620?)

	* at (U+0040): X=278.0,Y=618.0 (should be at cap-height 620?)

	* C (U+0043): X=491.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=478.0,Y=2.0 (should be at baseline 0?) 

	* And 71 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* aatelu (U+0C06): L<<92.0,279.0>--<92.0,278.0>> -> L<<92.0,278.0>--<92.0,270.0>> 

	* And atelu (U+0C05): L<<92.0,279.0>--<92.0,278.0>> -> L<<92.0,278.0>--<92.0,270.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<576.0,403.0>-<587.0,400.0>-<598.0,395.0>>/B<<598.0,395.0>-<564.0,419.0>-<512.5,432.0>> = 10.773638187776136 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansTelugu-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhauvoweltelu
	* ssauvoweltelu
	* tsivoweltelu
	* rrratelu
	* phoovoweltelu
	* lovoweltelu
	* rrvocalictelu
	* khaivoweltelu
	* yaivoweltelu
	* dzeevoweltelu and 304 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* natelu (U+0C28): L<<247.0,416.0>--<247.0,416.0>>/B<<247.0,416.0>-<213.0,417.0>-<184.0,429.5>> = 1.68468431789628 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansTelugu-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/telugu.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/telugu.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(పచచ్ǵ)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+362|patelu=1+711|catelu=2+760|cahalanttelu=3+760|.notdef=5+600|parenright.telu=6+362</pre>



<pre>Got     : parenleft.telu=0+362|patelu=1+711|catelu=2+760|cahalanttelu=3+760|g=5+615|acutecomb=5+0|parenright.telu=6+362</pre>



<pre>                                                                            ^^^^^^^    ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3570 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,193.0Q593.0,251.0 570.0,294.5Q547.0,338.0 507.0,369.5Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,99.0 626.0,43.5Q576.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(362, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1073, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,261.0 611.0,309.0Q580.0,357.0 532.0,385.5Q484.0,414.0 434.0,425.0L418.0,425.0Q347.0,425.0 304.0,452.5Q261.0,480.0 261.0,540.0Q261.0,592.0 309.0,627.0Q253.0,664.0 253.0,724.0Q253.0,751.0 263.0,771.0Q273.0,791.0 291.0,805.0Q312.0,822.0 345.5,830.0Q379.0,838.0 448.0,838.0L735.0,838.0L735.0,763.0L432.0,763.0Q398.0,763.0 383.0,761.0Q368.0,759.0 359.0,754.0Q336.0,743.0 336.0,717.0Q336.0,689.0 357.0,678.0Q367.0,673.0 383.5,670.5Q400.0,668.0 432.0,668.0L568.0,668.0L568.0,593.0L427.0,593.0Q399.0,593.0 383.5,589.5Q368.0,586.0 360.0,580.0Q344.0,568.0 344.0,546.0Q344.0,522.0 360.0,511.0Q369.0,504.0 383.5,502.0Q398.0,500.0 420.0,500.0L462.0,500.0Q590.0,466.0 657.5,384.5Q725.0,303.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1833, 983)"/>
<path d="M275.0,546.0Q328.0,546.0 370.5,526.0Q413.0,506.0 443.0,465.0L448.0,465.0L460.0,536.0L530.0,536.0L530.0,-9.0Q530.0,-124.0 471.5,-182.0Q413.0,-240.0 290.0,-240.0Q172.0,-240.0 97.0,-206.0L97.0,-125.0Q176.0,-167.0 295.0,-167.0Q364.0,-167.0 403.5,-126.5Q443.0,-86.0 443.0,-16.0L443.0,5.0Q443.0,17.0 444.0,39.5Q445.0,62.0 446.0,71.0L442.0,71.0Q388.0,-10.0 276.0,-10.0Q172.0,-10.0 113.5,63.0Q55.0,136.0 55.0,267.0Q55.0,395.0 113.5,470.5Q172.0,546.0 275.0,546.0ZM287.0,472.0Q220.0,472.0 183.0,418.5Q146.0,365.0 146.0,266.0Q146.0,167.0 182.5,114.5Q219.0,62.0 289.0,62.0Q370.0,62.0 407.0,105.5Q444.0,149.0 444.0,246.0L444.0,267.0Q444.0,377.0 406.0,424.5Q368.0,472.0 287.0,472.0Z"  transform="translate(2593, 983)"/>
<path d="M-124.0,756.0Q-136.0,738.0 -161.0,709.5Q-186.0,681.0 -214.5,652.5Q-243.0,624.0 -267.0,606.0L-325.0,606.0L-325.0,618.0Q-310.0,637.0 -292.5,663.0Q-275.0,689.0 -258.0,716.5Q-241.0,744.0 -230.0,766.0L-124.0,766.0L-124.0,756.0Z"  transform="translate(3208, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(3208, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3555 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,193.0Q593.0,251.0 570.0,294.5Q547.0,338.0 507.0,369.5Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,99.0 626.0,43.5Q576.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(362, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1073, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,261.0 611.0,309.0Q580.0,357.0 532.0,385.5Q484.0,414.0 434.0,425.0L418.0,425.0Q347.0,425.0 304.0,452.5Q261.0,480.0 261.0,540.0Q261.0,592.0 309.0,627.0Q253.0,664.0 253.0,724.0Q253.0,751.0 263.0,771.0Q273.0,791.0 291.0,805.0Q312.0,822.0 345.5,830.0Q379.0,838.0 448.0,838.0L735.0,838.0L735.0,763.0L432.0,763.0Q398.0,763.0 383.0,761.0Q368.0,759.0 359.0,754.0Q336.0,743.0 336.0,717.0Q336.0,689.0 357.0,678.0Q367.0,673.0 383.5,670.5Q400.0,668.0 432.0,668.0L568.0,668.0L568.0,593.0L427.0,593.0Q399.0,593.0 383.5,589.5Q368.0,586.0 360.0,580.0Q344.0,568.0 344.0,546.0Q344.0,522.0 360.0,511.0Q369.0,504.0 383.5,502.0Q398.0,500.0 420.0,500.0L462.0,500.0Q590.0,466.0 657.5,384.5Q725.0,303.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1833, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(2593, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(3193, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ȇౘ◌్చుకుǵ</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: .notdef=0+600|tsatelu=1+760|uni25CC=2+578|viramatelu=2+0|catelu=4+760|uvowelsigntelu=4+0|katelu=6+522|uvowelsigntelu=6+0|.notdef=8+600</pre>



<pre>Got     : .notdef=0+600|tsatelu=1+760|uni25CC=2+578|viramatelu=2+0|catelu=4+760|uvowelsigntelu=4+0|katelu=6+522|uvowelsigntelu=6+0|g=8+615|acutecomb=8+0</pre>



<pre>                                                                                                                                   ^^^^^^^     +
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3835 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(0, 983)"/>
<path d="M496.0,869.0Q555.0,869.0 591.0,835.0Q627.0,801.0 627.0,749.0Q627.0,712.0 614.0,688.0Q601.0,664.0 581.0,648.0Q551.0,626.0 513.5,619.0Q476.0,612.0 412.0,612.0L79.0,612.0L79.0,687.0L383.0,687.0Q374.0,702.0 369.0,719.0Q364.0,736.0 364.0,757.0Q364.0,784.0 377.0,809.5Q390.0,835.0 419.0,852.0Q448.0,869.0 496.0,869.0ZM433.0,746.0Q433.0,715.0 455.0,687.0L460.0,687.0Q507.0,687.0 532.5,701.5Q558.0,716.0 558.0,750.0Q558.0,772.0 543.0,787.5Q528.0,803.0 497.0,803.0Q466.0,803.0 449.5,787.5Q433.0,772.0 433.0,746.0ZM543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 462.0,95.5Q496.0,67.0 539.0,67.0Q564.0,67.0 587.5,75.5Q611.0,84.0 626.5,108.0Q642.0,132.0 642.0,179.0Q642.0,241.0 609.0,284.5Q576.0,328.0 525.0,353.0Q474.0,378.0 419.0,384.0Q411.0,383.0 403.0,383.0Q374.0,383.0 347.5,394.0Q321.0,405.0 299.0,435.5Q277.0,466.0 261.0,522.0L344.0,549.0Q359.0,494.0 373.0,476.0Q387.0,458.0 409.0,458.0Q429.0,458.0 447.0,470.0Q465.0,482.0 496.0,523.0L527.0,563.0Q561.0,607.0 589.5,633.0Q618.0,659.0 650.0,671.0Q682.0,683.0 726.0,683.0L732.0,606.0Q697.0,604.0 674.0,595.0Q651.0,586.0 631.0,566.5Q611.0,547.0 585.0,514.0L562.0,484.0Q541.0,457.0 522.0,439.0Q622.0,404.0 673.5,334.0Q725.0,264.0 725.0,178.0Q725.0,114.0 701.0,72.0Q677.0,30.0 636.0,9.0Q595.0,-12.0 543.0,-12.0Z"  transform="translate(600, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(1360, 983)"/>
<path d="M-355.0,540.0Q-355.0,592.0 -307.0,627.0Q-363.0,664.0 -363.0,724.0Q-363.0,751.0 -353.0,771.0Q-343.0,791.0 -325.0,805.0Q-304.0,822.0 -270.5,830.0Q-237.0,838.0 -168.0,838.0L119.0,838.0L119.0,763.0L-184.0,763.0Q-218.0,763.0 -233.0,761.0Q-248.0,759.0 -257.0,754.0Q-280.0,743.0 -280.0,717.0Q-280.0,689.0 -259.0,678.0Q-249.0,673.0 -232.5,670.5Q-216.0,668.0 -185.0,668.0L-48.0,668.0L-48.0,593.0L-189.0,593.0Q-217.0,593.0 -232.5,589.5Q-248.0,586.0 -256.0,580.0Q-272.0,568.0 -272.0,546.0Q-272.0,522.0 -256.0,511.0Q-247.0,504.0 -233.0,502.0Q-219.0,500.0 -197.0,500.0L-160.0,500.0L-160.0,425.0L-198.0,425.0Q-269.0,425.0 -312.0,452.5Q-355.0,480.0 -355.0,540.0Z"  transform="translate(1938, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1938, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(2698, 983)"/>
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(2698, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(3220, 983)"/>
<path d="M275.0,546.0Q328.0,546.0 370.5,526.0Q413.0,506.0 443.0,465.0L448.0,465.0L460.0,536.0L530.0,536.0L530.0,-9.0Q530.0,-124.0 471.5,-182.0Q413.0,-240.0 290.0,-240.0Q172.0,-240.0 97.0,-206.0L97.0,-125.0Q176.0,-167.0 295.0,-167.0Q364.0,-167.0 403.5,-126.5Q443.0,-86.0 443.0,-16.0L443.0,5.0Q443.0,17.0 444.0,39.5Q445.0,62.0 446.0,71.0L442.0,71.0Q388.0,-10.0 276.0,-10.0Q172.0,-10.0 113.5,63.0Q55.0,136.0 55.0,267.0Q55.0,395.0 113.5,470.5Q172.0,546.0 275.0,546.0ZM287.0,472.0Q220.0,472.0 183.0,418.5Q146.0,365.0 146.0,266.0Q146.0,167.0 182.5,114.5Q219.0,62.0 289.0,62.0Q370.0,62.0 407.0,105.5Q444.0,149.0 444.0,246.0L444.0,267.0Q444.0,377.0 406.0,424.5Q368.0,472.0 287.0,472.0Z"  transform="translate(3220, 983)"/>
<path d="M-124.0,756.0Q-136.0,738.0 -161.0,709.5Q-186.0,681.0 -214.5,652.5Q-243.0,624.0 -267.0,606.0L-325.0,606.0L-325.0,618.0Q-310.0,637.0 -292.5,663.0Q-275.0,689.0 -258.0,716.5Q-241.0,744.0 -230.0,766.0L-124.0,766.0L-124.0,756.0Z"  transform="translate(3835, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3820 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(0, 983)"/>
<path d="M496.0,869.0Q555.0,869.0 591.0,835.0Q627.0,801.0 627.0,749.0Q627.0,712.0 614.0,688.0Q601.0,664.0 581.0,648.0Q551.0,626.0 513.5,619.0Q476.0,612.0 412.0,612.0L79.0,612.0L79.0,687.0L383.0,687.0Q374.0,702.0 369.0,719.0Q364.0,736.0 364.0,757.0Q364.0,784.0 377.0,809.5Q390.0,835.0 419.0,852.0Q448.0,869.0 496.0,869.0ZM433.0,746.0Q433.0,715.0 455.0,687.0L460.0,687.0Q507.0,687.0 532.5,701.5Q558.0,716.0 558.0,750.0Q558.0,772.0 543.0,787.5Q528.0,803.0 497.0,803.0Q466.0,803.0 449.5,787.5Q433.0,772.0 433.0,746.0ZM543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 462.0,95.5Q496.0,67.0 539.0,67.0Q564.0,67.0 587.5,75.5Q611.0,84.0 626.5,108.0Q642.0,132.0 642.0,179.0Q642.0,241.0 609.0,284.5Q576.0,328.0 525.0,353.0Q474.0,378.0 419.0,384.0Q411.0,383.0 403.0,383.0Q374.0,383.0 347.5,394.0Q321.0,405.0 299.0,435.5Q277.0,466.0 261.0,522.0L344.0,549.0Q359.0,494.0 373.0,476.0Q387.0,458.0 409.0,458.0Q429.0,458.0 447.0,470.0Q465.0,482.0 496.0,523.0L527.0,563.0Q561.0,607.0 589.5,633.0Q618.0,659.0 650.0,671.0Q682.0,683.0 726.0,683.0L732.0,606.0Q697.0,604.0 674.0,595.0Q651.0,586.0 631.0,566.5Q611.0,547.0 585.0,514.0L562.0,484.0Q541.0,457.0 522.0,439.0Q622.0,404.0 673.5,334.0Q725.0,264.0 725.0,178.0Q725.0,114.0 701.0,72.0Q677.0,30.0 636.0,9.0Q595.0,-12.0 543.0,-12.0Z"  transform="translate(600, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(1360, 983)"/>
<path d="M-355.0,540.0Q-355.0,592.0 -307.0,627.0Q-363.0,664.0 -363.0,724.0Q-363.0,751.0 -353.0,771.0Q-343.0,791.0 -325.0,805.0Q-304.0,822.0 -270.5,830.0Q-237.0,838.0 -168.0,838.0L119.0,838.0L119.0,763.0L-184.0,763.0Q-218.0,763.0 -233.0,761.0Q-248.0,759.0 -257.0,754.0Q-280.0,743.0 -280.0,717.0Q-280.0,689.0 -259.0,678.0Q-249.0,673.0 -232.5,670.5Q-216.0,668.0 -185.0,668.0L-48.0,668.0L-48.0,593.0L-189.0,593.0Q-217.0,593.0 -232.5,589.5Q-248.0,586.0 -256.0,580.0Q-272.0,568.0 -272.0,546.0Q-272.0,522.0 -256.0,511.0Q-247.0,504.0 -233.0,502.0Q-219.0,500.0 -197.0,500.0L-160.0,500.0L-160.0,425.0L-198.0,425.0Q-269.0,425.0 -312.0,452.5Q-355.0,480.0 -355.0,540.0Z"  transform="translate(1938, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1938, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(2698, 983)"/>
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(2698, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(3220, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3220, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(ȇచుచ్కుǵ)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+362|.notdef=1+600|catelu=2+760|uvowelsigntelu=2+0|catelu=4+760|viramatelu=4+0|katelu=6+522|uvowelsigntelu=6+0|.notdef=8+600|parenright.telu=9+362</pre>



<pre>Got     : parenleft.telu=0+362|.notdef=1+600|catelu=2+760|uvowelsigntelu=2+0|catelu=4+760|viramatelu=4+0|katelu=6+522|uvowelsigntelu=6+0|g=8+615|acutecomb=8+0|parenright.telu=9+362</pre>



<pre>                                                                                                                                         ^^^^^^^    ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3981 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(362, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(962, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(1722, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1722, 983)"/>
<path d="M-355.0,540.0Q-355.0,592.0 -307.0,627.0Q-363.0,664.0 -363.0,724.0Q-363.0,751.0 -353.0,771.0Q-343.0,791.0 -325.0,805.0Q-304.0,822.0 -270.5,830.0Q-237.0,838.0 -168.0,838.0L119.0,838.0L119.0,763.0L-184.0,763.0Q-218.0,763.0 -233.0,761.0Q-248.0,759.0 -257.0,754.0Q-280.0,743.0 -280.0,717.0Q-280.0,689.0 -259.0,678.0Q-249.0,673.0 -232.5,670.5Q-216.0,668.0 -185.0,668.0L-48.0,668.0L-48.0,593.0L-189.0,593.0Q-217.0,593.0 -232.5,589.5Q-248.0,586.0 -256.0,580.0Q-272.0,568.0 -272.0,546.0Q-272.0,522.0 -256.0,511.0Q-247.0,504.0 -233.0,502.0Q-219.0,500.0 -197.0,500.0L-160.0,500.0L-160.0,425.0L-198.0,425.0Q-269.0,425.0 -312.0,452.5Q-355.0,480.0 -355.0,540.0Z"  transform="translate(2482, 983)"/>
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(2482, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(3004, 983)"/>
<path d="M275.0,546.0Q328.0,546.0 370.5,526.0Q413.0,506.0 443.0,465.0L448.0,465.0L460.0,536.0L530.0,536.0L530.0,-9.0Q530.0,-124.0 471.5,-182.0Q413.0,-240.0 290.0,-240.0Q172.0,-240.0 97.0,-206.0L97.0,-125.0Q176.0,-167.0 295.0,-167.0Q364.0,-167.0 403.5,-126.5Q443.0,-86.0 443.0,-16.0L443.0,5.0Q443.0,17.0 444.0,39.5Q445.0,62.0 446.0,71.0L442.0,71.0Q388.0,-10.0 276.0,-10.0Q172.0,-10.0 113.5,63.0Q55.0,136.0 55.0,267.0Q55.0,395.0 113.5,470.5Q172.0,546.0 275.0,546.0ZM287.0,472.0Q220.0,472.0 183.0,418.5Q146.0,365.0 146.0,266.0Q146.0,167.0 182.5,114.5Q219.0,62.0 289.0,62.0Q370.0,62.0 407.0,105.5Q444.0,149.0 444.0,246.0L444.0,267.0Q444.0,377.0 406.0,424.5Q368.0,472.0 287.0,472.0Z"  transform="translate(3004, 983)"/>
<path d="M-124.0,756.0Q-136.0,738.0 -161.0,709.5Q-186.0,681.0 -214.5,652.5Q-243.0,624.0 -267.0,606.0L-325.0,606.0L-325.0,618.0Q-310.0,637.0 -292.5,663.0Q-275.0,689.0 -258.0,716.5Q-241.0,744.0 -230.0,766.0L-124.0,766.0L-124.0,756.0Z"  transform="translate(3619, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(3619, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3966 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(362, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(962, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(1722, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1722, 983)"/>
<path d="M-355.0,540.0Q-355.0,592.0 -307.0,627.0Q-363.0,664.0 -363.0,724.0Q-363.0,751.0 -353.0,771.0Q-343.0,791.0 -325.0,805.0Q-304.0,822.0 -270.5,830.0Q-237.0,838.0 -168.0,838.0L119.0,838.0L119.0,763.0L-184.0,763.0Q-218.0,763.0 -233.0,761.0Q-248.0,759.0 -257.0,754.0Q-280.0,743.0 -280.0,717.0Q-280.0,689.0 -259.0,678.0Q-249.0,673.0 -232.5,670.5Q-216.0,668.0 -185.0,668.0L-48.0,668.0L-48.0,593.0L-189.0,593.0Q-217.0,593.0 -232.5,589.5Q-248.0,586.0 -256.0,580.0Q-272.0,568.0 -272.0,546.0Q-272.0,522.0 -256.0,511.0Q-247.0,504.0 -233.0,502.0Q-219.0,500.0 -197.0,500.0L-160.0,500.0L-160.0,425.0L-198.0,425.0Q-269.0,425.0 -312.0,452.5Q-355.0,480.0 -355.0,540.0Z"  transform="translate(2482, 983)"/>
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(2482, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(3004, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3004, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(3604, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">అౘ◌్చంĦా</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: atelu=0+800|tsatelu=1+760|uni25CC=2+578|casubscripttelu=2+379|anusvaratelu=2+507|.notdef=6+600|uni25CC=6+578|aavowelsigntelu=6+260</pre>



<pre>Got     : atelu=0+800|tsatelu=1+760|uni25CC=2+578|casubscripttelu=2+379|anusvaratelu=2+507|Hbar=6+741|uni25CC=6+578|aavowelsigntelu=6+260</pre>



<pre>                                                                                           ^^^^^^^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4603 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M390.0,-12.0Q270.0,-12.0 191.5,25.5Q113.0,63.0 74.5,128.0Q36.0,193.0 36.0,273.0Q36.0,345.0 61.0,396.0Q86.0,447.0 128.5,473.5Q171.0,500.0 225.0,500.0Q285.0,500.0 321.0,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 202.0,235.0Q177.0,235.0 155.5,241.5Q134.0,248.0 115.0,257.0Q119.0,208.0 148.0,164.5Q177.0,121.0 236.0,94.0Q295.0,67.0 390.0,67.0Q538.0,67.0 610.0,119.5Q682.0,172.0 682.0,285.0Q682.0,322.0 671.0,353.5Q660.0,385.0 637.5,405.0Q615.0,425.0 580.0,425.0Q557.0,425.0 537.5,409.5Q518.0,394.0 518.0,360.0Q518.0,321.0 544.0,295.5Q570.0,270.0 612.0,256.0L612.0,184.0L303.0,184.0L303.0,258.0L500.0,258.0Q439.0,296.0 439.0,374.0Q439.0,404.0 454.0,433.0Q469.0,462.0 501.5,481.0Q534.0,500.0 584.0,500.0Q636.0,500.0 676.5,472.0Q717.0,444.0 741.0,395.5Q765.0,347.0 765.0,284.0Q765.0,133.0 665.5,60.5Q566.0,-12.0 390.0,-12.0ZM220.0,429.0Q182.0,429.0 155.0,403.0Q128.0,377.0 119.0,329.0Q133.0,319.0 152.5,312.0Q172.0,305.0 197.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0Z"  transform="translate(0, 983)"/>
<path d="M496.0,869.0Q555.0,869.0 591.0,835.0Q627.0,801.0 627.0,749.0Q627.0,712.0 614.0,688.0Q601.0,664.0 581.0,648.0Q551.0,626.0 513.5,619.0Q476.0,612.0 412.0,612.0L79.0,612.0L79.0,687.0L383.0,687.0Q374.0,702.0 369.0,719.0Q364.0,736.0 364.0,757.0Q364.0,784.0 377.0,809.5Q390.0,835.0 419.0,852.0Q448.0,869.0 496.0,869.0ZM433.0,746.0Q433.0,715.0 455.0,687.0L460.0,687.0Q507.0,687.0 532.5,701.5Q558.0,716.0 558.0,750.0Q558.0,772.0 543.0,787.5Q528.0,803.0 497.0,803.0Q466.0,803.0 449.5,787.5Q433.0,772.0 433.0,746.0ZM543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 462.0,95.5Q496.0,67.0 539.0,67.0Q564.0,67.0 587.5,75.5Q611.0,84.0 626.5,108.0Q642.0,132.0 642.0,179.0Q642.0,241.0 609.0,284.5Q576.0,328.0 525.0,353.0Q474.0,378.0 419.0,384.0Q411.0,383.0 403.0,383.0Q374.0,383.0 347.5,394.0Q321.0,405.0 299.0,435.5Q277.0,466.0 261.0,522.0L344.0,549.0Q359.0,494.0 373.0,476.0Q387.0,458.0 409.0,458.0Q429.0,458.0 447.0,470.0Q465.0,482.0 496.0,523.0L527.0,563.0Q561.0,607.0 589.5,633.0Q618.0,659.0 650.0,671.0Q682.0,683.0 726.0,683.0L732.0,606.0Q697.0,604.0 674.0,595.0Q651.0,586.0 631.0,566.5Q611.0,547.0 585.0,514.0L562.0,484.0Q541.0,457.0 522.0,439.0Q622.0,404.0 673.5,334.0Q725.0,264.0 725.0,178.0Q725.0,114.0 701.0,72.0Q677.0,30.0 636.0,9.0Q595.0,-12.0 543.0,-12.0Z"  transform="translate(800, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(1560, 983)"/>
<path d="M224.0,-337.0Q179.0,-337.0 150.0,-317.5Q121.0,-298.0 102.0,-270.0Q73.0,-305.0 42.5,-321.0Q12.0,-337.0 -32.0,-337.0Q-87.0,-337.0 -125.0,-304.5Q-163.0,-272.0 -163.0,-214.0Q-163.0,-192.0 -153.0,-170.5Q-143.0,-149.0 -122.0,-131.0L-198.0,-131.0L-198.0,-62.0L1.0,-62.0L1.0,-127.0Q-47.0,-138.0 -67.0,-160.5Q-87.0,-183.0 -87.0,-209.0Q-87.0,-238.0 -68.0,-252.0Q-49.0,-266.0 -24.0,-266.0Q17.0,-266.0 37.5,-241.5Q58.0,-217.0 65.0,-183.0L138.0,-183.0Q144.0,-226.0 166.5,-246.0Q189.0,-266.0 222.0,-266.0Q265.0,-266.0 294.5,-227.5Q324.0,-189.0 324.0,-95.0Q324.0,-12.0 296.5,65.5Q269.0,143.0 221.5,211.5Q174.0,280.0 112.5,335.5Q51.0,391.0 -18.0,430.0L22.0,500.0Q88.0,462.0 155.5,403.0Q223.0,344.0 279.0,267.0Q335.0,190.0 369.0,97.5Q403.0,5.0 403.0,-101.0Q403.0,-215.0 356.5,-276.0Q310.0,-337.0 224.0,-337.0Z"  transform="translate(2138, 983)"/>
<path d="M33.0,208.0Q33.0,271.0 60.5,320.5Q88.0,370.0 138.0,399.0Q188.0,428.0 253.0,428.0Q319.0,428.0 369.0,399.5Q419.0,371.0 446.5,321.0Q474.0,271.0 474.0,208.0Q474.0,145.0 447.0,95.5Q420.0,46.0 370.5,17.0Q321.0,-12.0 253.0,-12.0Q186.0,-12.0 136.5,17.0Q87.0,46.0 60.0,96.0Q33.0,146.0 33.0,208.0ZM115.0,209.0Q115.0,149.0 150.0,107.5Q185.0,66.0 253.0,66.0Q322.0,66.0 357.0,107.5Q392.0,149.0 392.0,209.0Q392.0,268.0 355.5,309.0Q319.0,350.0 253.0,350.0Q187.0,350.0 151.0,309.0Q115.0,268.0 115.0,209.0Z"  transform="translate(2517, 983)"/>
<path d="M97.0,0.0L97.0,523.0L0.0,523.0L0.0,595.0L97.0,595.0L97.0,714.0L187.0,714.0L187.0,595.0L553.0,595.0L553.0,714.0L643.0,714.0L643.0,595.0L740.0,595.0L740.0,523.0L643.0,523.0L643.0,0.0L553.0,0.0L553.0,333.0L187.0,333.0L187.0,0.0L97.0,0.0ZM187.0,412.0L553.0,412.0L553.0,523.0L187.0,523.0L187.0,412.0Z"  transform="translate(3024, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(3765, 983)"/>
<path d="M104.0,220.0Q54.0,220.0 24.0,239.0Q-6.0,258.0 -19.5,287.0Q-33.0,316.0 -33.0,344.0Q-33.0,369.0 -27.0,388.5Q-21.0,408.0 -11.0,425.0L-546.0,425.0L-546.0,500.0L33.0,500.0Q98.0,500.0 134.5,492.0Q171.0,484.0 198.0,462.0Q219.0,446.0 232.0,418.5Q245.0,391.0 245.0,353.0Q245.0,290.0 207.0,255.0Q169.0,220.0 104.0,220.0ZM40.0,353.0Q40.0,323.0 57.5,304.5Q75.0,286.0 108.0,286.0Q143.0,286.0 157.5,304.5Q172.0,323.0 172.0,350.0Q172.0,392.0 146.5,408.5Q121.0,425.0 75.0,425.0L66.0,425.0Q40.0,391.0 40.0,353.0Z"  transform="translate(4343, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4462 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M390.0,-12.0Q270.0,-12.0 191.5,25.5Q113.0,63.0 74.5,128.0Q36.0,193.0 36.0,273.0Q36.0,345.0 61.0,396.0Q86.0,447.0 128.5,473.5Q171.0,500.0 225.0,500.0Q285.0,500.0 321.0,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 202.0,235.0Q177.0,235.0 155.5,241.5Q134.0,248.0 115.0,257.0Q119.0,208.0 148.0,164.5Q177.0,121.0 236.0,94.0Q295.0,67.0 390.0,67.0Q538.0,67.0 610.0,119.5Q682.0,172.0 682.0,285.0Q682.0,322.0 671.0,353.5Q660.0,385.0 637.5,405.0Q615.0,425.0 580.0,425.0Q557.0,425.0 537.5,409.5Q518.0,394.0 518.0,360.0Q518.0,321.0 544.0,295.5Q570.0,270.0 612.0,256.0L612.0,184.0L303.0,184.0L303.0,258.0L500.0,258.0Q439.0,296.0 439.0,374.0Q439.0,404.0 454.0,433.0Q469.0,462.0 501.5,481.0Q534.0,500.0 584.0,500.0Q636.0,500.0 676.5,472.0Q717.0,444.0 741.0,395.5Q765.0,347.0 765.0,284.0Q765.0,133.0 665.5,60.5Q566.0,-12.0 390.0,-12.0ZM220.0,429.0Q182.0,429.0 155.0,403.0Q128.0,377.0 119.0,329.0Q133.0,319.0 152.5,312.0Q172.0,305.0 197.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0Z"  transform="translate(0, 983)"/>
<path d="M496.0,869.0Q555.0,869.0 591.0,835.0Q627.0,801.0 627.0,749.0Q627.0,712.0 614.0,688.0Q601.0,664.0 581.0,648.0Q551.0,626.0 513.5,619.0Q476.0,612.0 412.0,612.0L79.0,612.0L79.0,687.0L383.0,687.0Q374.0,702.0 369.0,719.0Q364.0,736.0 364.0,757.0Q364.0,784.0 377.0,809.5Q390.0,835.0 419.0,852.0Q448.0,869.0 496.0,869.0ZM433.0,746.0Q433.0,715.0 455.0,687.0L460.0,687.0Q507.0,687.0 532.5,701.5Q558.0,716.0 558.0,750.0Q558.0,772.0 543.0,787.5Q528.0,803.0 497.0,803.0Q466.0,803.0 449.5,787.5Q433.0,772.0 433.0,746.0ZM543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 462.0,95.5Q496.0,67.0 539.0,67.0Q564.0,67.0 587.5,75.5Q611.0,84.0 626.5,108.0Q642.0,132.0 642.0,179.0Q642.0,241.0 609.0,284.5Q576.0,328.0 525.0,353.0Q474.0,378.0 419.0,384.0Q411.0,383.0 403.0,383.0Q374.0,383.0 347.5,394.0Q321.0,405.0 299.0,435.5Q277.0,466.0 261.0,522.0L344.0,549.0Q359.0,494.0 373.0,476.0Q387.0,458.0 409.0,458.0Q429.0,458.0 447.0,470.0Q465.0,482.0 496.0,523.0L527.0,563.0Q561.0,607.0 589.5,633.0Q618.0,659.0 650.0,671.0Q682.0,683.0 726.0,683.0L732.0,606.0Q697.0,604.0 674.0,595.0Q651.0,586.0 631.0,566.5Q611.0,547.0 585.0,514.0L562.0,484.0Q541.0,457.0 522.0,439.0Q622.0,404.0 673.5,334.0Q725.0,264.0 725.0,178.0Q725.0,114.0 701.0,72.0Q677.0,30.0 636.0,9.0Q595.0,-12.0 543.0,-12.0Z"  transform="translate(800, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(1560, 983)"/>
<path d="M224.0,-337.0Q179.0,-337.0 150.0,-317.5Q121.0,-298.0 102.0,-270.0Q73.0,-305.0 42.5,-321.0Q12.0,-337.0 -32.0,-337.0Q-87.0,-337.0 -125.0,-304.5Q-163.0,-272.0 -163.0,-214.0Q-163.0,-192.0 -153.0,-170.5Q-143.0,-149.0 -122.0,-131.0L-198.0,-131.0L-198.0,-62.0L1.0,-62.0L1.0,-127.0Q-47.0,-138.0 -67.0,-160.5Q-87.0,-183.0 -87.0,-209.0Q-87.0,-238.0 -68.0,-252.0Q-49.0,-266.0 -24.0,-266.0Q17.0,-266.0 37.5,-241.5Q58.0,-217.0 65.0,-183.0L138.0,-183.0Q144.0,-226.0 166.5,-246.0Q189.0,-266.0 222.0,-266.0Q265.0,-266.0 294.5,-227.5Q324.0,-189.0 324.0,-95.0Q324.0,-12.0 296.5,65.5Q269.0,143.0 221.5,211.5Q174.0,280.0 112.5,335.5Q51.0,391.0 -18.0,430.0L22.0,500.0Q88.0,462.0 155.5,403.0Q223.0,344.0 279.0,267.0Q335.0,190.0 369.0,97.5Q403.0,5.0 403.0,-101.0Q403.0,-215.0 356.5,-276.0Q310.0,-337.0 224.0,-337.0Z"  transform="translate(2138, 983)"/>
<path d="M33.0,208.0Q33.0,271.0 60.5,320.5Q88.0,370.0 138.0,399.0Q188.0,428.0 253.0,428.0Q319.0,428.0 369.0,399.5Q419.0,371.0 446.5,321.0Q474.0,271.0 474.0,208.0Q474.0,145.0 447.0,95.5Q420.0,46.0 370.5,17.0Q321.0,-12.0 253.0,-12.0Q186.0,-12.0 136.5,17.0Q87.0,46.0 60.0,96.0Q33.0,146.0 33.0,208.0ZM115.0,209.0Q115.0,149.0 150.0,107.5Q185.0,66.0 253.0,66.0Q322.0,66.0 357.0,107.5Q392.0,149.0 392.0,209.0Q392.0,268.0 355.5,309.0Q319.0,350.0 253.0,350.0Q187.0,350.0 151.0,309.0Q115.0,268.0 115.0,209.0Z"  transform="translate(2517, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3024, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(3624, 983)"/>
<path d="M104.0,220.0Q54.0,220.0 24.0,239.0Q-6.0,258.0 -19.5,287.0Q-33.0,316.0 -33.0,344.0Q-33.0,369.0 -27.0,388.5Q-21.0,408.0 -11.0,425.0L-546.0,425.0L-546.0,500.0L33.0,500.0Q98.0,500.0 134.5,492.0Q171.0,484.0 198.0,462.0Q219.0,446.0 232.0,418.5Q245.0,391.0 245.0,353.0Q245.0,290.0 207.0,255.0Q169.0,220.0 104.0,220.0ZM40.0,353.0Q40.0,323.0 57.5,304.5Q75.0,286.0 108.0,286.0Q143.0,286.0 157.5,304.5Q172.0,323.0 172.0,350.0Q172.0,392.0 146.5,408.5Q121.0,425.0 75.0,425.0L66.0,425.0Q40.0,391.0 40.0,353.0Z"  transform="translate(4202, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(అచచ్ంĦా)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+362|atelu=1+800|catelu=2+760|cahalanttelu=3+760|anusvaratelu=3+507|.notdef=6+600|uni25CC=6+578|aavowelsigntelu=6+260|parenright.telu=8+362</pre>



<pre>Got     : parenleft.telu=0+362|atelu=1+800|catelu=2+760|cahalanttelu=3+760|anusvaratelu=3+507|Hbar=6+741|uni25CC=6+578|aavowelsigntelu=6+260|parenright.telu=8+362</pre>



<pre>                                                                                              ^^^^^^^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5130 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M390.0,-12.0Q270.0,-12.0 191.5,25.5Q113.0,63.0 74.5,128.0Q36.0,193.0 36.0,273.0Q36.0,345.0 61.0,396.0Q86.0,447.0 128.5,473.5Q171.0,500.0 225.0,500.0Q285.0,500.0 321.0,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 202.0,235.0Q177.0,235.0 155.5,241.5Q134.0,248.0 115.0,257.0Q119.0,208.0 148.0,164.5Q177.0,121.0 236.0,94.0Q295.0,67.0 390.0,67.0Q538.0,67.0 610.0,119.5Q682.0,172.0 682.0,285.0Q682.0,322.0 671.0,353.5Q660.0,385.0 637.5,405.0Q615.0,425.0 580.0,425.0Q557.0,425.0 537.5,409.5Q518.0,394.0 518.0,360.0Q518.0,321.0 544.0,295.5Q570.0,270.0 612.0,256.0L612.0,184.0L303.0,184.0L303.0,258.0L500.0,258.0Q439.0,296.0 439.0,374.0Q439.0,404.0 454.0,433.0Q469.0,462.0 501.5,481.0Q534.0,500.0 584.0,500.0Q636.0,500.0 676.5,472.0Q717.0,444.0 741.0,395.5Q765.0,347.0 765.0,284.0Q765.0,133.0 665.5,60.5Q566.0,-12.0 390.0,-12.0ZM220.0,429.0Q182.0,429.0 155.0,403.0Q128.0,377.0 119.0,329.0Q133.0,319.0 152.5,312.0Q172.0,305.0 197.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0Z"  transform="translate(362, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1162, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,261.0 611.0,309.0Q580.0,357.0 532.0,385.5Q484.0,414.0 434.0,425.0L418.0,425.0Q347.0,425.0 304.0,452.5Q261.0,480.0 261.0,540.0Q261.0,592.0 309.0,627.0Q253.0,664.0 253.0,724.0Q253.0,751.0 263.0,771.0Q273.0,791.0 291.0,805.0Q312.0,822.0 345.5,830.0Q379.0,838.0 448.0,838.0L735.0,838.0L735.0,763.0L432.0,763.0Q398.0,763.0 383.0,761.0Q368.0,759.0 359.0,754.0Q336.0,743.0 336.0,717.0Q336.0,689.0 357.0,678.0Q367.0,673.0 383.5,670.5Q400.0,668.0 432.0,668.0L568.0,668.0L568.0,593.0L427.0,593.0Q399.0,593.0 383.5,589.5Q368.0,586.0 360.0,580.0Q344.0,568.0 344.0,546.0Q344.0,522.0 360.0,511.0Q369.0,504.0 383.5,502.0Q398.0,500.0 420.0,500.0L462.0,500.0Q590.0,466.0 657.5,384.5Q725.0,303.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1922, 983)"/>
<path d="M33.0,208.0Q33.0,271.0 60.5,320.5Q88.0,370.0 138.0,399.0Q188.0,428.0 253.0,428.0Q319.0,428.0 369.0,399.5Q419.0,371.0 446.5,321.0Q474.0,271.0 474.0,208.0Q474.0,145.0 447.0,95.5Q420.0,46.0 370.5,17.0Q321.0,-12.0 253.0,-12.0Q186.0,-12.0 136.5,17.0Q87.0,46.0 60.0,96.0Q33.0,146.0 33.0,208.0ZM115.0,209.0Q115.0,149.0 150.0,107.5Q185.0,66.0 253.0,66.0Q322.0,66.0 357.0,107.5Q392.0,149.0 392.0,209.0Q392.0,268.0 355.5,309.0Q319.0,350.0 253.0,350.0Q187.0,350.0 151.0,309.0Q115.0,268.0 115.0,209.0Z"  transform="translate(2682, 983)"/>
<path d="M97.0,0.0L97.0,523.0L0.0,523.0L0.0,595.0L97.0,595.0L97.0,714.0L187.0,714.0L187.0,595.0L553.0,595.0L553.0,714.0L643.0,714.0L643.0,595.0L740.0,595.0L740.0,523.0L643.0,523.0L643.0,0.0L553.0,0.0L553.0,333.0L187.0,333.0L187.0,0.0L97.0,0.0ZM187.0,412.0L553.0,412.0L553.0,523.0L187.0,523.0L187.0,412.0Z"  transform="translate(3189, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(3930, 983)"/>
<path d="M104.0,220.0Q54.0,220.0 24.0,239.0Q-6.0,258.0 -19.5,287.0Q-33.0,316.0 -33.0,344.0Q-33.0,369.0 -27.0,388.5Q-21.0,408.0 -11.0,425.0L-546.0,425.0L-546.0,500.0L33.0,500.0Q98.0,500.0 134.5,492.0Q171.0,484.0 198.0,462.0Q219.0,446.0 232.0,418.5Q245.0,391.0 245.0,353.0Q245.0,290.0 207.0,255.0Q169.0,220.0 104.0,220.0ZM40.0,353.0Q40.0,323.0 57.5,304.5Q75.0,286.0 108.0,286.0Q143.0,286.0 157.5,304.5Q172.0,323.0 172.0,350.0Q172.0,392.0 146.5,408.5Q121.0,425.0 75.0,425.0L66.0,425.0Q40.0,391.0 40.0,353.0Z"  transform="translate(4508, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(4768, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4989 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M390.0,-12.0Q270.0,-12.0 191.5,25.5Q113.0,63.0 74.5,128.0Q36.0,193.0 36.0,273.0Q36.0,345.0 61.0,396.0Q86.0,447.0 128.5,473.5Q171.0,500.0 225.0,500.0Q285.0,500.0 321.0,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 202.0,235.0Q177.0,235.0 155.5,241.5Q134.0,248.0 115.0,257.0Q119.0,208.0 148.0,164.5Q177.0,121.0 236.0,94.0Q295.0,67.0 390.0,67.0Q538.0,67.0 610.0,119.5Q682.0,172.0 682.0,285.0Q682.0,322.0 671.0,353.5Q660.0,385.0 637.5,405.0Q615.0,425.0 580.0,425.0Q557.0,425.0 537.5,409.5Q518.0,394.0 518.0,360.0Q518.0,321.0 544.0,295.5Q570.0,270.0 612.0,256.0L612.0,184.0L303.0,184.0L303.0,258.0L500.0,258.0Q439.0,296.0 439.0,374.0Q439.0,404.0 454.0,433.0Q469.0,462.0 501.5,481.0Q534.0,500.0 584.0,500.0Q636.0,500.0 676.5,472.0Q717.0,444.0 741.0,395.5Q765.0,347.0 765.0,284.0Q765.0,133.0 665.5,60.5Q566.0,-12.0 390.0,-12.0ZM220.0,429.0Q182.0,429.0 155.0,403.0Q128.0,377.0 119.0,329.0Q133.0,319.0 152.5,312.0Q172.0,305.0 197.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0Z"  transform="translate(362, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1162, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,261.0 611.0,309.0Q580.0,357.0 532.0,385.5Q484.0,414.0 434.0,425.0L418.0,425.0Q347.0,425.0 304.0,452.5Q261.0,480.0 261.0,540.0Q261.0,592.0 309.0,627.0Q253.0,664.0 253.0,724.0Q253.0,751.0 263.0,771.0Q273.0,791.0 291.0,805.0Q312.0,822.0 345.5,830.0Q379.0,838.0 448.0,838.0L735.0,838.0L735.0,763.0L432.0,763.0Q398.0,763.0 383.0,761.0Q368.0,759.0 359.0,754.0Q336.0,743.0 336.0,717.0Q336.0,689.0 357.0,678.0Q367.0,673.0 383.5,670.5Q400.0,668.0 432.0,668.0L568.0,668.0L568.0,593.0L427.0,593.0Q399.0,593.0 383.5,589.5Q368.0,586.0 360.0,580.0Q344.0,568.0 344.0,546.0Q344.0,522.0 360.0,511.0Q369.0,504.0 383.5,502.0Q398.0,500.0 420.0,500.0L462.0,500.0Q590.0,466.0 657.5,384.5Q725.0,303.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0Z"  transform="translate(1922, 983)"/>
<path d="M33.0,208.0Q33.0,271.0 60.5,320.5Q88.0,370.0 138.0,399.0Q188.0,428.0 253.0,428.0Q319.0,428.0 369.0,399.5Q419.0,371.0 446.5,321.0Q474.0,271.0 474.0,208.0Q474.0,145.0 447.0,95.5Q420.0,46.0 370.5,17.0Q321.0,-12.0 253.0,-12.0Q186.0,-12.0 136.5,17.0Q87.0,46.0 60.0,96.0Q33.0,146.0 33.0,208.0ZM115.0,209.0Q115.0,149.0 150.0,107.5Q185.0,66.0 253.0,66.0Q322.0,66.0 357.0,107.5Q392.0,149.0 392.0,209.0Q392.0,268.0 355.5,309.0Q319.0,350.0 253.0,350.0Q187.0,350.0 151.0,309.0Q115.0,268.0 115.0,209.0Z"  transform="translate(2682, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3189, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(3789, 983)"/>
<path d="M104.0,220.0Q54.0,220.0 24.0,239.0Q-6.0,258.0 -19.5,287.0Q-33.0,316.0 -33.0,344.0Q-33.0,369.0 -27.0,388.5Q-21.0,408.0 -11.0,425.0L-546.0,425.0L-546.0,500.0L33.0,500.0Q98.0,500.0 134.5,492.0Q171.0,484.0 198.0,462.0Q219.0,446.0 232.0,418.5Q245.0,391.0 245.0,353.0Q245.0,290.0 207.0,255.0Q169.0,220.0 104.0,220.0ZM40.0,353.0Q40.0,323.0 57.5,304.5Q75.0,286.0 108.0,286.0Q143.0,286.0 157.5,304.5Q172.0,323.0 172.0,350.0Q172.0,392.0 146.5,408.5Q121.0,425.0 75.0,425.0L66.0,425.0Q40.0,391.0 40.0,353.0Z"  transform="translate(4367, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(4627, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">పౘ◌్చǵ</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: patelu=0+711|tsatelu=1+760|uni25CC=2+578|casubscripttelu=2+406|.notdef=5+600</pre>



<pre>Got     : patelu=0+711|tsatelu=1+760|uni25CC=2+578|casubscripttelu=2+406|g=5+615|acutecomb=5+0</pre>



<pre>                                                                         ^^^^^^^     +
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3070 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,193.0Q593.0,251.0 570.0,294.5Q547.0,338.0 507.0,369.5Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,99.0 626.0,43.5Q576.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(0, 983)"/>
<path d="M496.0,869.0Q555.0,869.0 591.0,835.0Q627.0,801.0 627.0,749.0Q627.0,712.0 614.0,688.0Q601.0,664.0 581.0,648.0Q551.0,626.0 513.5,619.0Q476.0,612.0 412.0,612.0L79.0,612.0L79.0,687.0L383.0,687.0Q374.0,702.0 369.0,719.0Q364.0,736.0 364.0,757.0Q364.0,784.0 377.0,809.5Q390.0,835.0 419.0,852.0Q448.0,869.0 496.0,869.0ZM433.0,746.0Q433.0,715.0 455.0,687.0L460.0,687.0Q507.0,687.0 532.5,701.5Q558.0,716.0 558.0,750.0Q558.0,772.0 543.0,787.5Q528.0,803.0 497.0,803.0Q466.0,803.0 449.5,787.5Q433.0,772.0 433.0,746.0ZM543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 462.0,95.5Q496.0,67.0 539.0,67.0Q564.0,67.0 587.5,75.5Q611.0,84.0 626.5,108.0Q642.0,132.0 642.0,179.0Q642.0,241.0 609.0,284.5Q576.0,328.0 525.0,353.0Q474.0,378.0 419.0,384.0Q411.0,383.0 403.0,383.0Q374.0,383.0 347.5,394.0Q321.0,405.0 299.0,435.5Q277.0,466.0 261.0,522.0L344.0,549.0Q359.0,494.0 373.0,476.0Q387.0,458.0 409.0,458.0Q429.0,458.0 447.0,470.0Q465.0,482.0 496.0,523.0L527.0,563.0Q561.0,607.0 589.5,633.0Q618.0,659.0 650.0,671.0Q682.0,683.0 726.0,683.0L732.0,606.0Q697.0,604.0 674.0,595.0Q651.0,586.0 631.0,566.5Q611.0,547.0 585.0,514.0L562.0,484.0Q541.0,457.0 522.0,439.0Q622.0,404.0 673.5,334.0Q725.0,264.0 725.0,178.0Q725.0,114.0 701.0,72.0Q677.0,30.0 636.0,9.0Q595.0,-12.0 543.0,-12.0Z"  transform="translate(711, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(1471, 983)"/>
<path d="M224.0,-337.0Q179.0,-337.0 150.0,-317.5Q121.0,-298.0 102.0,-270.0Q73.0,-305.0 42.5,-321.0Q12.0,-337.0 -32.0,-337.0Q-87.0,-337.0 -125.0,-304.5Q-163.0,-272.0 -163.0,-214.0Q-163.0,-192.0 -153.0,-170.5Q-143.0,-149.0 -122.0,-131.0L-198.0,-131.0L-198.0,-62.0L1.0,-62.0L1.0,-127.0Q-47.0,-138.0 -67.0,-160.5Q-87.0,-183.0 -87.0,-209.0Q-87.0,-238.0 -68.0,-252.0Q-49.0,-266.0 -24.0,-266.0Q17.0,-266.0 37.5,-241.5Q58.0,-217.0 65.0,-183.0L138.0,-183.0Q144.0,-226.0 166.5,-246.0Q189.0,-266.0 222.0,-266.0Q265.0,-266.0 294.5,-227.5Q324.0,-189.0 324.0,-95.0Q324.0,-12.0 296.5,65.5Q269.0,143.0 221.5,211.5Q174.0,280.0 112.5,335.5Q51.0,391.0 -18.0,430.0L22.0,500.0Q88.0,462.0 155.5,403.0Q223.0,344.0 279.0,267.0Q335.0,190.0 369.0,97.5Q403.0,5.0 403.0,-101.0Q403.0,-215.0 356.5,-276.0Q310.0,-337.0 224.0,-337.0Z"  transform="translate(2049, 983)"/>
<path d="M275.0,546.0Q328.0,546.0 370.5,526.0Q413.0,506.0 443.0,465.0L448.0,465.0L460.0,536.0L530.0,536.0L530.0,-9.0Q530.0,-124.0 471.5,-182.0Q413.0,-240.0 290.0,-240.0Q172.0,-240.0 97.0,-206.0L97.0,-125.0Q176.0,-167.0 295.0,-167.0Q364.0,-167.0 403.5,-126.5Q443.0,-86.0 443.0,-16.0L443.0,5.0Q443.0,17.0 444.0,39.5Q445.0,62.0 446.0,71.0L442.0,71.0Q388.0,-10.0 276.0,-10.0Q172.0,-10.0 113.5,63.0Q55.0,136.0 55.0,267.0Q55.0,395.0 113.5,470.5Q172.0,546.0 275.0,546.0ZM287.0,472.0Q220.0,472.0 183.0,418.5Q146.0,365.0 146.0,266.0Q146.0,167.0 182.5,114.5Q219.0,62.0 289.0,62.0Q370.0,62.0 407.0,105.5Q444.0,149.0 444.0,246.0L444.0,267.0Q444.0,377.0 406.0,424.5Q368.0,472.0 287.0,472.0Z"  transform="translate(2455, 983)"/>
<path d="M-124.0,756.0Q-136.0,738.0 -161.0,709.5Q-186.0,681.0 -214.5,652.5Q-243.0,624.0 -267.0,606.0L-325.0,606.0L-325.0,618.0Q-310.0,637.0 -292.5,663.0Q-275.0,689.0 -258.0,716.5Q-241.0,744.0 -230.0,766.0L-124.0,766.0L-124.0,756.0Z"  transform="translate(3070, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3055 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,193.0Q593.0,251.0 570.0,294.5Q547.0,338.0 507.0,369.5Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,99.0 626.0,43.5Q576.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(0, 983)"/>
<path d="M496.0,869.0Q555.0,869.0 591.0,835.0Q627.0,801.0 627.0,749.0Q627.0,712.0 614.0,688.0Q601.0,664.0 581.0,648.0Q551.0,626.0 513.5,619.0Q476.0,612.0 412.0,612.0L79.0,612.0L79.0,687.0L383.0,687.0Q374.0,702.0 369.0,719.0Q364.0,736.0 364.0,757.0Q364.0,784.0 377.0,809.5Q390.0,835.0 419.0,852.0Q448.0,869.0 496.0,869.0ZM433.0,746.0Q433.0,715.0 455.0,687.0L460.0,687.0Q507.0,687.0 532.5,701.5Q558.0,716.0 558.0,750.0Q558.0,772.0 543.0,787.5Q528.0,803.0 497.0,803.0Q466.0,803.0 449.5,787.5Q433.0,772.0 433.0,746.0ZM543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 462.0,95.5Q496.0,67.0 539.0,67.0Q564.0,67.0 587.5,75.5Q611.0,84.0 626.5,108.0Q642.0,132.0 642.0,179.0Q642.0,241.0 609.0,284.5Q576.0,328.0 525.0,353.0Q474.0,378.0 419.0,384.0Q411.0,383.0 403.0,383.0Q374.0,383.0 347.5,394.0Q321.0,405.0 299.0,435.5Q277.0,466.0 261.0,522.0L344.0,549.0Q359.0,494.0 373.0,476.0Q387.0,458.0 409.0,458.0Q429.0,458.0 447.0,470.0Q465.0,482.0 496.0,523.0L527.0,563.0Q561.0,607.0 589.5,633.0Q618.0,659.0 650.0,671.0Q682.0,683.0 726.0,683.0L732.0,606.0Q697.0,604.0 674.0,595.0Q651.0,586.0 631.0,566.5Q611.0,547.0 585.0,514.0L562.0,484.0Q541.0,457.0 522.0,439.0Q622.0,404.0 673.5,334.0Q725.0,264.0 725.0,178.0Q725.0,114.0 701.0,72.0Q677.0,30.0 636.0,9.0Q595.0,-12.0 543.0,-12.0Z"  transform="translate(711, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(1471, 983)"/>
<path d="M224.0,-337.0Q179.0,-337.0 150.0,-317.5Q121.0,-298.0 102.0,-270.0Q73.0,-305.0 42.5,-321.0Q12.0,-337.0 -32.0,-337.0Q-87.0,-337.0 -125.0,-304.5Q-163.0,-272.0 -163.0,-214.0Q-163.0,-192.0 -153.0,-170.5Q-143.0,-149.0 -122.0,-131.0L-198.0,-131.0L-198.0,-62.0L1.0,-62.0L1.0,-127.0Q-47.0,-138.0 -67.0,-160.5Q-87.0,-183.0 -87.0,-209.0Q-87.0,-238.0 -68.0,-252.0Q-49.0,-266.0 -24.0,-266.0Q17.0,-266.0 37.5,-241.5Q58.0,-217.0 65.0,-183.0L138.0,-183.0Q144.0,-226.0 166.5,-246.0Q189.0,-266.0 222.0,-266.0Q265.0,-266.0 294.5,-227.5Q324.0,-189.0 324.0,-95.0Q324.0,-12.0 296.5,65.5Q269.0,143.0 221.5,211.5Q174.0,280.0 112.5,335.5Q51.0,391.0 -18.0,430.0L22.0,500.0Q88.0,462.0 155.5,403.0Q223.0,344.0 279.0,267.0Q335.0,190.0 369.0,97.5Q403.0,5.0 403.0,-101.0Q403.0,-215.0 356.5,-276.0Q310.0,-337.0 224.0,-337.0Z"  transform="translate(2049, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(2455, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">సౙ◌్జలు</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: satelu=0+702|dzatelu=1+731|uni25CC=2+578|jasubscripttelu=2+0|latelu=5+709|uvowelsigntelu=5+346</pre>



<pre>Got     : satelu=0+702|dzatelu=1+731|uni25CC=2+578|jasubscripttelu=2@-28,0+0|latelu=5+709|uvowelsigntelu=5+346</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3066 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M472.0,-12.0Q425.0,-12.0 390.0,3.5Q355.0,19.0 324.0,51.5Q293.0,84.0 256.0,133.0Q224.0,176.0 206.5,192.5Q189.0,209.0 164.0,209.0Q141.0,209.0 126.0,190.5Q111.0,172.0 111.0,143.0Q111.0,108.0 123.0,77.0Q135.0,46.0 159.0,14.0L78.0,-13.0Q56.0,22.0 42.5,59.5Q29.0,97.0 29.0,143.0Q29.0,204.0 67.0,245.0Q105.0,286.0 165.0,286.0Q204.0,286.0 230.5,272.5Q257.0,259.0 279.5,234.5Q302.0,210.0 328.0,175.0Q358.0,136.0 380.0,112.5Q402.0,89.0 425.0,78.0Q448.0,67.0 480.0,67.0Q530.0,67.0 557.0,99.5Q584.0,132.0 584.0,193.0Q584.0,251.0 561.0,294.5Q538.0,338.0 498.0,369.5Q458.0,401.0 408.0,423.0L446.0,500.0Q508.0,474.0 558.0,430.0Q608.0,386.0 637.5,327.5Q667.0,269.0 667.0,198.0Q667.0,100.0 617.0,44.0Q567.0,-12.0 472.0,-12.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(0, 983)"/>
<path d="M534.0,825.0Q596.0,825.0 630.5,791.0Q665.0,757.0 665.0,705.0Q665.0,668.0 652.0,644.0Q639.0,620.0 619.0,604.0Q589.0,582.0 551.5,575.0Q514.0,568.0 450.0,568.0L94.0,568.0L94.0,643.0L422.0,643.0Q413.0,658.0 407.5,675.0Q402.0,692.0 402.0,713.0Q402.0,740.0 415.5,765.5Q429.0,791.0 458.0,808.0Q487.0,825.0 534.0,825.0ZM471.0,702.0Q471.0,671.0 494.0,643.0L498.0,643.0Q545.0,643.0 570.5,657.5Q596.0,672.0 596.0,706.0Q596.0,728.0 581.0,743.5Q566.0,759.0 535.0,759.0Q504.0,759.0 487.5,743.5Q471.0,728.0 471.0,702.0ZM530.0,-12.0Q477.0,-12.0 440.0,8.0Q403.0,28.0 375.0,74.0Q338.0,22.0 298.5,5.0Q259.0,-12.0 205.0,-12.0Q150.0,-12.0 113.5,7.5Q77.0,27.0 59.0,59.5Q41.0,92.0 41.0,130.0Q41.0,191.0 78.5,227.0Q116.0,263.0 189.0,289.0Q230.0,304.0 254.0,321.0Q278.0,338.0 278.0,371.0Q278.0,394.0 261.5,410.5Q245.0,427.0 203.0,427.0Q160.0,427.0 139.0,410.5Q118.0,394.0 118.0,365.0Q118.0,352.0 121.5,341.0Q125.0,330.0 128.0,323.0L53.0,302.0Q36.0,333.0 36.0,375.0Q36.0,407.0 53.0,435.5Q70.0,464.0 107.0,482.0Q144.0,500.0 203.0,500.0Q257.0,500.0 290.5,483.0Q324.0,466.0 340.0,439.5Q356.0,413.0 359.0,385.0Q390.0,356.0 432.5,341.5Q475.0,327.0 514.0,327.0Q592.0,327.0 592.0,376.0Q592.0,404.0 571.0,414.5Q550.0,425.0 521.0,425.0Q503.0,425.0 488.0,423.0Q473.0,421.0 460.0,419.0L450.0,491.0Q462.0,494.0 482.0,497.0Q502.0,500.0 529.0,500.0Q565.0,500.0 598.0,489.0Q631.0,478.0 652.0,451.0Q673.0,424.0 673.0,377.0Q673.0,324.0 631.5,288.0Q590.0,252.0 512.0,252.0Q458.0,252.0 416.0,267.5Q374.0,283.0 345.0,306.0Q330.0,279.0 300.5,260.0Q271.0,241.0 227.0,225.0Q174.0,205.0 148.5,184.5Q123.0,164.0 123.0,131.0Q123.0,102.0 143.5,84.5Q164.0,67.0 207.0,67.0Q269.0,67.0 300.5,99.5Q332.0,132.0 336.0,185.0L414.0,185.0Q418.0,124.0 450.0,95.5Q482.0,67.0 527.0,67.0Q574.0,67.0 596.0,87.0Q618.0,107.0 618.0,142.0Q618.0,165.0 611.0,184.0Q604.0,203.0 593.0,221.0L667.0,252.0Q682.0,230.0 691.5,198.5Q701.0,167.0 701.0,135.0Q701.0,66.0 656.5,27.0Q612.0,-12.0 530.0,-12.0Z"  transform="translate(702, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(1433, 983)"/>
<path d="M-57.0,-142.0Q-57.0,-176.0 -84.5,-200.0Q-112.0,-224.0 -173.0,-224.0Q-210.0,-224.0 -240.0,-213.5Q-270.0,-203.0 -292.0,-188.0Q-310.0,-219.0 -374.0,-240.0Q-412.0,-253.0 -426.0,-263.5Q-440.0,-274.0 -440.0,-289.0Q-440.0,-322.0 -391.0,-322.0Q-315.0,-322.0 -305.0,-254.0L-236.0,-254.0Q-231.0,-291.0 -210.5,-306.5Q-190.0,-322.0 -165.0,-322.0Q-106.0,-322.0 -106.0,-280.0Q-106.0,-256.0 -121.0,-237.0L-58.0,-217.0Q-47.0,-235.0 -42.0,-253.0Q-37.0,-271.0 -37.0,-288.0Q-37.0,-334.0 -70.0,-360.0Q-103.0,-386.0 -159.0,-386.0Q-197.0,-386.0 -224.0,-371.0Q-251.0,-356.0 -270.0,-328.0Q-295.0,-359.0 -324.5,-372.5Q-354.0,-386.0 -392.0,-386.0Q-453.0,-386.0 -481.0,-358.0Q-509.0,-330.0 -509.0,-292.0Q-509.0,-257.0 -483.0,-233.0Q-457.0,-209.0 -402.0,-190.0Q-373.0,-180.0 -361.0,-171.0Q-349.0,-162.0 -349.0,-147.0Q-349.0,-136.0 -359.0,-127.0Q-369.0,-118.0 -396.0,-118.0Q-425.0,-118.0 -437.5,-127.0Q-450.0,-136.0 -450.0,-150.0Q-450.0,-157.0 -447.5,-164.0Q-445.0,-171.0 -443.0,-174.0L-506.0,-189.0Q-518.0,-168.0 -518.0,-140.0Q-518.0,-110.0 -489.0,-85.5Q-460.0,-61.0 -396.0,-61.0Q-339.0,-61.0 -313.0,-82.5Q-287.0,-104.0 -282.0,-129.0Q-261.0,-148.0 -232.5,-157.0Q-204.0,-166.0 -177.0,-166.0Q-144.0,-166.0 -133.0,-159.0Q-122.0,-152.0 -122.0,-142.0Q-122.0,-119.0 -167.0,-119.0Q-189.0,-119.0 -212.0,-124.0L-220.0,-67.0Q-211.0,-65.0 -195.5,-63.0Q-180.0,-61.0 -159.0,-61.0Q-133.0,-61.0 -110.0,-68.5Q-87.0,-76.0 -72.0,-93.5Q-57.0,-111.0 -57.0,-142.0Z"  transform="translate(1983, 983)"/>
<path d="M356.0,-12.0Q251.0,-12.0 179.5,24.0Q108.0,60.0 71.5,123.5Q35.0,187.0 35.0,269.0Q35.0,343.0 60.5,394.5Q86.0,446.0 129.0,473.0Q172.0,500.0 225.0,500.0Q284.0,500.0 320.5,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 201.0,235.0Q176.0,235.0 154.0,241.5Q132.0,248.0 114.0,258.0Q116.0,206.0 142.5,163.0Q169.0,120.0 221.0,93.5Q273.0,67.0 353.0,67.0Q463.0,67.0 527.0,113.0Q591.0,159.0 591.0,245.0Q591.0,303.0 558.5,349.0Q526.0,395.0 457.0,423.0L497.0,500.0Q580.0,464.0 627.0,400.0Q674.0,336.0 674.0,250.0Q674.0,176.0 641.0,116.5Q608.0,57.0 537.5,22.5Q467.0,-12.0 356.0,-12.0ZM220.0,429.0Q181.0,429.0 154.0,402.5Q127.0,376.0 118.0,329.0Q132.0,319.0 151.5,312.0Q171.0,305.0 196.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0Z"  transform="translate(2011, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(2720, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3066 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M472.0,-12.0Q425.0,-12.0 390.0,3.5Q355.0,19.0 324.0,51.5Q293.0,84.0 256.0,133.0Q224.0,176.0 206.5,192.5Q189.0,209.0 164.0,209.0Q141.0,209.0 126.0,190.5Q111.0,172.0 111.0,143.0Q111.0,108.0 123.0,77.0Q135.0,46.0 159.0,14.0L78.0,-13.0Q56.0,22.0 42.5,59.5Q29.0,97.0 29.0,143.0Q29.0,204.0 67.0,245.0Q105.0,286.0 165.0,286.0Q204.0,286.0 230.5,272.5Q257.0,259.0 279.5,234.5Q302.0,210.0 328.0,175.0Q358.0,136.0 380.0,112.5Q402.0,89.0 425.0,78.0Q448.0,67.0 480.0,67.0Q530.0,67.0 557.0,99.5Q584.0,132.0 584.0,193.0Q584.0,251.0 561.0,294.5Q538.0,338.0 498.0,369.5Q458.0,401.0 408.0,423.0L446.0,500.0Q508.0,474.0 558.0,430.0Q608.0,386.0 637.5,327.5Q667.0,269.0 667.0,198.0Q667.0,100.0 617.0,44.0Q567.0,-12.0 472.0,-12.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(0, 983)"/>
<path d="M534.0,825.0Q596.0,825.0 630.5,791.0Q665.0,757.0 665.0,705.0Q665.0,668.0 652.0,644.0Q639.0,620.0 619.0,604.0Q589.0,582.0 551.5,575.0Q514.0,568.0 450.0,568.0L94.0,568.0L94.0,643.0L422.0,643.0Q413.0,658.0 407.5,675.0Q402.0,692.0 402.0,713.0Q402.0,740.0 415.5,765.5Q429.0,791.0 458.0,808.0Q487.0,825.0 534.0,825.0ZM471.0,702.0Q471.0,671.0 494.0,643.0L498.0,643.0Q545.0,643.0 570.5,657.5Q596.0,672.0 596.0,706.0Q596.0,728.0 581.0,743.5Q566.0,759.0 535.0,759.0Q504.0,759.0 487.5,743.5Q471.0,728.0 471.0,702.0ZM530.0,-12.0Q477.0,-12.0 440.0,8.0Q403.0,28.0 375.0,74.0Q338.0,22.0 298.5,5.0Q259.0,-12.0 205.0,-12.0Q150.0,-12.0 113.5,7.5Q77.0,27.0 59.0,59.5Q41.0,92.0 41.0,130.0Q41.0,191.0 78.5,227.0Q116.0,263.0 189.0,289.0Q230.0,304.0 254.0,321.0Q278.0,338.0 278.0,371.0Q278.0,394.0 261.5,410.5Q245.0,427.0 203.0,427.0Q160.0,427.0 139.0,410.5Q118.0,394.0 118.0,365.0Q118.0,352.0 121.5,341.0Q125.0,330.0 128.0,323.0L53.0,302.0Q36.0,333.0 36.0,375.0Q36.0,407.0 53.0,435.5Q70.0,464.0 107.0,482.0Q144.0,500.0 203.0,500.0Q257.0,500.0 290.5,483.0Q324.0,466.0 340.0,439.5Q356.0,413.0 359.0,385.0Q390.0,356.0 432.5,341.5Q475.0,327.0 514.0,327.0Q592.0,327.0 592.0,376.0Q592.0,404.0 571.0,414.5Q550.0,425.0 521.0,425.0Q503.0,425.0 488.0,423.0Q473.0,421.0 460.0,419.0L450.0,491.0Q462.0,494.0 482.0,497.0Q502.0,500.0 529.0,500.0Q565.0,500.0 598.0,489.0Q631.0,478.0 652.0,451.0Q673.0,424.0 673.0,377.0Q673.0,324.0 631.5,288.0Q590.0,252.0 512.0,252.0Q458.0,252.0 416.0,267.5Q374.0,283.0 345.0,306.0Q330.0,279.0 300.5,260.0Q271.0,241.0 227.0,225.0Q174.0,205.0 148.5,184.5Q123.0,164.0 123.0,131.0Q123.0,102.0 143.5,84.5Q164.0,67.0 207.0,67.0Q269.0,67.0 300.5,99.5Q332.0,132.0 336.0,185.0L414.0,185.0Q418.0,124.0 450.0,95.5Q482.0,67.0 527.0,67.0Q574.0,67.0 596.0,87.0Q618.0,107.0 618.0,142.0Q618.0,165.0 611.0,184.0Q604.0,203.0 593.0,221.0L667.0,252.0Q682.0,230.0 691.5,198.5Q701.0,167.0 701.0,135.0Q701.0,66.0 656.5,27.0Q612.0,-12.0 530.0,-12.0Z"  transform="translate(702, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(1433, 983)"/>
<path d="M-57.0,-142.0Q-57.0,-176.0 -84.5,-200.0Q-112.0,-224.0 -173.0,-224.0Q-210.0,-224.0 -240.0,-213.5Q-270.0,-203.0 -292.0,-188.0Q-310.0,-219.0 -374.0,-240.0Q-412.0,-253.0 -426.0,-263.5Q-440.0,-274.0 -440.0,-289.0Q-440.0,-322.0 -391.0,-322.0Q-315.0,-322.0 -305.0,-254.0L-236.0,-254.0Q-231.0,-291.0 -210.5,-306.5Q-190.0,-322.0 -165.0,-322.0Q-106.0,-322.0 -106.0,-280.0Q-106.0,-256.0 -121.0,-237.0L-58.0,-217.0Q-47.0,-235.0 -42.0,-253.0Q-37.0,-271.0 -37.0,-288.0Q-37.0,-334.0 -70.0,-360.0Q-103.0,-386.0 -159.0,-386.0Q-197.0,-386.0 -224.0,-371.0Q-251.0,-356.0 -270.0,-328.0Q-295.0,-359.0 -324.5,-372.5Q-354.0,-386.0 -392.0,-386.0Q-453.0,-386.0 -481.0,-358.0Q-509.0,-330.0 -509.0,-292.0Q-509.0,-257.0 -483.0,-233.0Q-457.0,-209.0 -402.0,-190.0Q-373.0,-180.0 -361.0,-171.0Q-349.0,-162.0 -349.0,-147.0Q-349.0,-136.0 -359.0,-127.0Q-369.0,-118.0 -396.0,-118.0Q-425.0,-118.0 -437.5,-127.0Q-450.0,-136.0 -450.0,-150.0Q-450.0,-157.0 -447.5,-164.0Q-445.0,-171.0 -443.0,-174.0L-506.0,-189.0Q-518.0,-168.0 -518.0,-140.0Q-518.0,-110.0 -489.0,-85.5Q-460.0,-61.0 -396.0,-61.0Q-339.0,-61.0 -313.0,-82.5Q-287.0,-104.0 -282.0,-129.0Q-261.0,-148.0 -232.5,-157.0Q-204.0,-166.0 -177.0,-166.0Q-144.0,-166.0 -133.0,-159.0Q-122.0,-152.0 -122.0,-142.0Q-122.0,-119.0 -167.0,-119.0Q-189.0,-119.0 -212.0,-124.0L-220.0,-67.0Q-211.0,-65.0 -195.5,-63.0Q-180.0,-61.0 -159.0,-61.0Q-133.0,-61.0 -110.0,-68.5Q-87.0,-76.0 -72.0,-93.5Q-57.0,-111.0 -57.0,-142.0Z"  transform="translate(2011, 983)"/>
<path d="M356.0,-12.0Q251.0,-12.0 179.5,24.0Q108.0,60.0 71.5,123.5Q35.0,187.0 35.0,269.0Q35.0,343.0 60.5,394.5Q86.0,446.0 129.0,473.0Q172.0,500.0 225.0,500.0Q284.0,500.0 320.5,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 201.0,235.0Q176.0,235.0 154.0,241.5Q132.0,248.0 114.0,258.0Q116.0,206.0 142.5,163.0Q169.0,120.0 221.0,93.5Q273.0,67.0 353.0,67.0Q463.0,67.0 527.0,113.0Q591.0,159.0 591.0,245.0Q591.0,303.0 558.5,349.0Q526.0,395.0 457.0,423.0L497.0,500.0Q580.0,464.0 627.0,400.0Q674.0,336.0 674.0,250.0Q674.0,176.0 641.0,116.5Q608.0,57.0 537.5,22.5Q467.0,-12.0 356.0,-12.0ZM220.0,429.0Q181.0,429.0 154.0,402.5Q127.0,376.0 118.0,329.0Q132.0,319.0 151.5,312.0Q171.0,305.0 196.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0Z"  transform="translate(2011, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(2720, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(Ĩాకȃ)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+362|.notdef=1+600|aavowelsigntelu=1+0|katelu=3+522|.notdef=4+600|parenright.telu=5+362</pre>



<pre>Got     : parenleft.telu=0+362|I=1+339|tildecomb=1+0|aavowelsigntelu=1+0|katelu=3+522|.notdef=4+600|parenright.telu=5+362</pre>



<pre>                               ^^^^^^^   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2185 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M298.0,0.0L40.0,0.0L40.0,52.0L124.0,71.0L124.0,642.0L40.0,662.0L40.0,714.0L298.0,714.0L298.0,662.0L214.0,642.0L214.0,71.0L298.0,52.0L298.0,0.0Z"  transform="translate(362, 983)"/>
<path d="M-491.0,606.0Q-485.0,665.0 -456.5,699.5Q-428.0,734.0 -381.0,734.0Q-351.0,734.0 -324.5,719.5Q-298.0,705.0 -274.0,691.0Q-250.0,677.0 -229.0,677.0Q-206.0,677.0 -193.5,691.5Q-181.0,706.0 -174.0,735.0L-124.0,735.0Q-130.0,677.0 -158.0,642.0Q-186.0,607.0 -233.0,607.0Q-261.0,607.0 -287.5,621.0Q-314.0,635.0 -338.5,649.5Q-363.0,664.0 -385.0,664.0Q-409.0,664.0 -421.0,649.5Q-433.0,635.0 -440.0,606.0L-491.0,606.0Z"  transform="translate(701, 983)"/>
<path d="M104.0,220.0Q54.0,220.0 24.0,239.0Q-6.0,258.0 -19.5,287.0Q-33.0,316.0 -33.0,344.0Q-33.0,369.0 -27.0,388.5Q-21.0,408.0 -11.0,425.0L-546.0,425.0L-546.0,500.0L33.0,500.0Q98.0,500.0 134.5,492.0Q171.0,484.0 198.0,462.0Q219.0,446.0 232.0,418.5Q245.0,391.0 245.0,353.0Q245.0,290.0 207.0,255.0Q169.0,220.0 104.0,220.0ZM40.0,353.0Q40.0,323.0 57.5,304.5Q75.0,286.0 108.0,286.0Q143.0,286.0 157.5,304.5Q172.0,323.0 172.0,350.0Q172.0,392.0 146.5,408.5Q121.0,425.0 75.0,425.0L66.0,425.0Q40.0,391.0 40.0,353.0Z"  transform="translate(701, 983)"/>
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(701, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1223, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(1823, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2446 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(362, 983)"/>
<path d="M104.0,220.0Q54.0,220.0 24.0,239.0Q-6.0,258.0 -19.5,287.0Q-33.0,316.0 -33.0,344.0Q-33.0,369.0 -27.0,388.5Q-21.0,408.0 -11.0,425.0L-546.0,425.0L-546.0,500.0L33.0,500.0Q98.0,500.0 134.5,492.0Q171.0,484.0 198.0,462.0Q219.0,446.0 232.0,418.5Q245.0,391.0 245.0,353.0Q245.0,290.0 207.0,255.0Q169.0,220.0 104.0,220.0ZM40.0,353.0Q40.0,323.0 57.5,304.5Q75.0,286.0 108.0,286.0Q143.0,286.0 157.5,304.5Q172.0,323.0 172.0,350.0Q172.0,392.0 146.5,408.5Q121.0,425.0 75.0,425.0L66.0,425.0Q40.0,391.0 40.0,353.0Z"  transform="translate(962, 983)"/>
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(962, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1484, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(2084, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ౙ◌ాǹȃ</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: dzatelu=0+731|uni25CC=1+578|aavowelsigntelu=1+260|.notdef=3+600|.notdef=4+600</pre>



<pre>Got     : dzatelu=0+731|uni25CC=1+578|aavowelsigntelu=1+260|n=3+618|gravecomb=3+0|.notdef=4+600</pre>



<pre>                                                            + +++++    ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2787 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M534.0,825.0Q596.0,825.0 630.5,791.0Q665.0,757.0 665.0,705.0Q665.0,668.0 652.0,644.0Q639.0,620.0 619.0,604.0Q589.0,582.0 551.5,575.0Q514.0,568.0 450.0,568.0L94.0,568.0L94.0,643.0L422.0,643.0Q413.0,658.0 407.5,675.0Q402.0,692.0 402.0,713.0Q402.0,740.0 415.5,765.5Q429.0,791.0 458.0,808.0Q487.0,825.0 534.0,825.0ZM471.0,702.0Q471.0,671.0 494.0,643.0L498.0,643.0Q545.0,643.0 570.5,657.5Q596.0,672.0 596.0,706.0Q596.0,728.0 581.0,743.5Q566.0,759.0 535.0,759.0Q504.0,759.0 487.5,743.5Q471.0,728.0 471.0,702.0ZM530.0,-12.0Q477.0,-12.0 440.0,8.0Q403.0,28.0 375.0,74.0Q338.0,22.0 298.5,5.0Q259.0,-12.0 205.0,-12.0Q150.0,-12.0 113.5,7.5Q77.0,27.0 59.0,59.5Q41.0,92.0 41.0,130.0Q41.0,191.0 78.5,227.0Q116.0,263.0 189.0,289.0Q230.0,304.0 254.0,321.0Q278.0,338.0 278.0,371.0Q278.0,394.0 261.5,410.5Q245.0,427.0 203.0,427.0Q160.0,427.0 139.0,410.5Q118.0,394.0 118.0,365.0Q118.0,352.0 121.5,341.0Q125.0,330.0 128.0,323.0L53.0,302.0Q36.0,333.0 36.0,375.0Q36.0,407.0 53.0,435.5Q70.0,464.0 107.0,482.0Q144.0,500.0 203.0,500.0Q257.0,500.0 290.5,483.0Q324.0,466.0 340.0,439.5Q356.0,413.0 359.0,385.0Q390.0,356.0 432.5,341.5Q475.0,327.0 514.0,327.0Q592.0,327.0 592.0,376.0Q592.0,404.0 571.0,414.5Q550.0,425.0 521.0,425.0Q503.0,425.0 488.0,423.0Q473.0,421.0 460.0,419.0L450.0,491.0Q462.0,494.0 482.0,497.0Q502.0,500.0 529.0,500.0Q565.0,500.0 598.0,489.0Q631.0,478.0 652.0,451.0Q673.0,424.0 673.0,377.0Q673.0,324.0 631.5,288.0Q590.0,252.0 512.0,252.0Q458.0,252.0 416.0,267.5Q374.0,283.0 345.0,306.0Q330.0,279.0 300.5,260.0Q271.0,241.0 227.0,225.0Q174.0,205.0 148.5,184.5Q123.0,164.0 123.0,131.0Q123.0,102.0 143.5,84.5Q164.0,67.0 207.0,67.0Q269.0,67.0 300.5,99.5Q332.0,132.0 336.0,185.0L414.0,185.0Q418.0,124.0 450.0,95.5Q482.0,67.0 527.0,67.0Q574.0,67.0 596.0,87.0Q618.0,107.0 618.0,142.0Q618.0,165.0 611.0,184.0Q604.0,203.0 593.0,221.0L667.0,252.0Q682.0,230.0 691.5,198.5Q701.0,167.0 701.0,135.0Q701.0,66.0 656.5,27.0Q612.0,-12.0 530.0,-12.0Z"  transform="translate(0, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(731, 983)"/>
<path d="M104.0,220.0Q54.0,220.0 24.0,239.0Q-6.0,258.0 -19.5,287.0Q-33.0,316.0 -33.0,344.0Q-33.0,369.0 -27.0,388.5Q-21.0,408.0 -11.0,425.0L-546.0,425.0L-546.0,500.0L33.0,500.0Q98.0,500.0 134.5,492.0Q171.0,484.0 198.0,462.0Q219.0,446.0 232.0,418.5Q245.0,391.0 245.0,353.0Q245.0,290.0 207.0,255.0Q169.0,220.0 104.0,220.0ZM40.0,353.0Q40.0,323.0 57.5,304.5Q75.0,286.0 108.0,286.0Q143.0,286.0 157.5,304.5Q172.0,323.0 172.0,350.0Q172.0,392.0 146.5,408.5Q121.0,425.0 75.0,425.0L66.0,425.0Q40.0,391.0 40.0,353.0Z"  transform="translate(1309, 983)"/>
<path d="M343.0,546.0Q439.0,546.0 488.0,499.5Q537.0,453.0 537.0,349.0L537.0,0.0L450.0,0.0L450.0,343.0Q450.0,472.0 330.0,472.0Q241.0,472.0 207.0,422.0Q173.0,372.0 173.0,278.0L173.0,0.0L85.0,0.0L85.0,536.0L156.0,536.0L169.0,463.0L174.0,463.0Q200.0,505.0 246.0,525.5Q292.0,546.0 343.0,546.0Z"  transform="translate(1569, 983)"/>
<path d="M-388.0,766.0Q-377.0,744.0 -360.5,716.5Q-344.0,689.0 -325.5,663.0Q-307.0,637.0 -292.0,618.0L-292.0,606.0L-351.0,606.0Q-374.0,624.0 -403.0,652.5Q-432.0,681.0 -456.5,709.5Q-481.0,738.0 -493.0,756.0L-493.0,766.0L-388.0,766.0Z"  transform="translate(2187, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(2187, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2769 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M534.0,825.0Q596.0,825.0 630.5,791.0Q665.0,757.0 665.0,705.0Q665.0,668.0 652.0,644.0Q639.0,620.0 619.0,604.0Q589.0,582.0 551.5,575.0Q514.0,568.0 450.0,568.0L94.0,568.0L94.0,643.0L422.0,643.0Q413.0,658.0 407.5,675.0Q402.0,692.0 402.0,713.0Q402.0,740.0 415.5,765.5Q429.0,791.0 458.0,808.0Q487.0,825.0 534.0,825.0ZM471.0,702.0Q471.0,671.0 494.0,643.0L498.0,643.0Q545.0,643.0 570.5,657.5Q596.0,672.0 596.0,706.0Q596.0,728.0 581.0,743.5Q566.0,759.0 535.0,759.0Q504.0,759.0 487.5,743.5Q471.0,728.0 471.0,702.0ZM530.0,-12.0Q477.0,-12.0 440.0,8.0Q403.0,28.0 375.0,74.0Q338.0,22.0 298.5,5.0Q259.0,-12.0 205.0,-12.0Q150.0,-12.0 113.5,7.5Q77.0,27.0 59.0,59.5Q41.0,92.0 41.0,130.0Q41.0,191.0 78.5,227.0Q116.0,263.0 189.0,289.0Q230.0,304.0 254.0,321.0Q278.0,338.0 278.0,371.0Q278.0,394.0 261.5,410.5Q245.0,427.0 203.0,427.0Q160.0,427.0 139.0,410.5Q118.0,394.0 118.0,365.0Q118.0,352.0 121.5,341.0Q125.0,330.0 128.0,323.0L53.0,302.0Q36.0,333.0 36.0,375.0Q36.0,407.0 53.0,435.5Q70.0,464.0 107.0,482.0Q144.0,500.0 203.0,500.0Q257.0,500.0 290.5,483.0Q324.0,466.0 340.0,439.5Q356.0,413.0 359.0,385.0Q390.0,356.0 432.5,341.5Q475.0,327.0 514.0,327.0Q592.0,327.0 592.0,376.0Q592.0,404.0 571.0,414.5Q550.0,425.0 521.0,425.0Q503.0,425.0 488.0,423.0Q473.0,421.0 460.0,419.0L450.0,491.0Q462.0,494.0 482.0,497.0Q502.0,500.0 529.0,500.0Q565.0,500.0 598.0,489.0Q631.0,478.0 652.0,451.0Q673.0,424.0 673.0,377.0Q673.0,324.0 631.5,288.0Q590.0,252.0 512.0,252.0Q458.0,252.0 416.0,267.5Q374.0,283.0 345.0,306.0Q330.0,279.0 300.5,260.0Q271.0,241.0 227.0,225.0Q174.0,205.0 148.5,184.5Q123.0,164.0 123.0,131.0Q123.0,102.0 143.5,84.5Q164.0,67.0 207.0,67.0Q269.0,67.0 300.5,99.5Q332.0,132.0 336.0,185.0L414.0,185.0Q418.0,124.0 450.0,95.5Q482.0,67.0 527.0,67.0Q574.0,67.0 596.0,87.0Q618.0,107.0 618.0,142.0Q618.0,165.0 611.0,184.0Q604.0,203.0 593.0,221.0L667.0,252.0Q682.0,230.0 691.5,198.5Q701.0,167.0 701.0,135.0Q701.0,66.0 656.5,27.0Q612.0,-12.0 530.0,-12.0Z"  transform="translate(0, 983)"/>
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(731, 983)"/>
<path d="M104.0,220.0Q54.0,220.0 24.0,239.0Q-6.0,258.0 -19.5,287.0Q-33.0,316.0 -33.0,344.0Q-33.0,369.0 -27.0,388.5Q-21.0,408.0 -11.0,425.0L-546.0,425.0L-546.0,500.0L33.0,500.0Q98.0,500.0 134.5,492.0Q171.0,484.0 198.0,462.0Q219.0,446.0 232.0,418.5Q245.0,391.0 245.0,353.0Q245.0,290.0 207.0,255.0Q169.0,220.0 104.0,220.0ZM40.0,353.0Q40.0,323.0 57.5,304.5Q75.0,286.0 108.0,286.0Q143.0,286.0 157.5,304.5Q172.0,323.0 172.0,350.0Q172.0,392.0 146.5,408.5Q121.0,425.0 75.0,425.0L66.0,425.0Q40.0,391.0 40.0,353.0Z"  transform="translate(1309, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1569, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(2169, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(జాǹȃ)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+362|jaavoweltelu=1+1046|.notdef=3+600|.notdef=4+600|parenright.telu=5+362</pre>



<pre>Got     : parenleft.telu=0+362|jaavoweltelu=1+1046|n=3+618|gravecomb=3+0|.notdef=4+600|parenright.telu=5+362</pre>



<pre>                                                   + +++++    ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2988 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M530.0,-12.0Q477.0,-12.0 440.0,8.0Q403.0,28.0 375.0,74.0Q338.0,22.0 298.5,5.0Q259.0,-12.0 205.0,-12.0Q150.0,-12.0 113.5,7.5Q77.0,27.0 59.0,59.5Q41.0,92.0 41.0,130.0Q41.0,191.0 78.5,227.0Q116.0,263.0 189.0,289.0Q230.0,304.0 254.0,321.0Q278.0,338.0 278.0,371.0Q278.0,394.0 261.5,410.5Q245.0,427.0 203.0,427.0Q160.0,427.0 139.0,410.5Q118.0,394.0 118.0,365.0Q118.0,352.0 121.5,341.0Q125.0,330.0 128.0,323.0L53.0,302.0Q36.0,333.0 36.0,375.0Q36.0,407.0 53.0,435.5Q70.0,464.0 107.0,482.0Q144.0,500.0 203.0,500.0Q257.0,500.0 290.5,483.0Q324.0,466.0 340.0,439.5Q356.0,413.0 359.0,385.0Q390.0,356.0 432.5,341.5Q475.0,327.0 514.0,327.0Q592.0,327.0 592.0,376.0Q592.0,395.0 581.5,407.0Q571.0,419.0 556.0,425.0L452.0,425.0L452.0,500.0L819.0,500.0Q884.0,500.0 920.5,492.0Q957.0,484.0 984.0,462.0Q1005.0,446.0 1018.0,418.5Q1031.0,391.0 1031.0,353.0Q1031.0,290.0 993.0,255.0Q955.0,220.0 890.0,220.0Q840.0,220.0 810.0,239.0Q780.0,258.0 766.5,287.0Q753.0,316.0 753.0,344.0Q753.0,369.0 759.0,388.5Q765.0,408.0 775.0,425.0L663.0,425.0Q673.0,404.0 673.0,377.0Q673.0,324.0 631.5,288.0Q590.0,252.0 512.0,252.0Q458.0,252.0 416.0,267.5Q374.0,283.0 345.0,306.0Q330.0,279.0 300.5,260.0Q271.0,241.0 227.0,225.0Q174.0,205.0 148.5,184.5Q123.0,164.0 123.0,131.0Q123.0,102.0 143.5,84.5Q164.0,67.0 207.0,67.0Q269.0,67.0 300.5,99.5Q332.0,132.0 336.0,185.0L414.0,185.0Q418.0,124.0 450.0,95.5Q482.0,67.0 527.0,67.0Q574.0,67.0 596.0,87.0Q618.0,107.0 618.0,142.0Q618.0,165.0 611.0,184.0Q604.0,203.0 593.0,221.0L667.0,252.0Q682.0,230.0 691.5,198.5Q701.0,167.0 701.0,135.0Q701.0,66.0 656.5,27.0Q612.0,-12.0 530.0,-12.0ZM826.0,353.0Q826.0,323.0 843.5,304.5Q861.0,286.0 894.0,286.0Q929.0,286.0 943.5,304.5Q958.0,323.0 958.0,350.0Q958.0,392.0 932.5,408.5Q907.0,425.0 861.0,425.0L852.0,425.0Q826.0,391.0 826.0,353.0Z"  transform="translate(362, 983)"/>
<path d="M343.0,546.0Q439.0,546.0 488.0,499.5Q537.0,453.0 537.0,349.0L537.0,0.0L450.0,0.0L450.0,343.0Q450.0,472.0 330.0,472.0Q241.0,472.0 207.0,422.0Q173.0,372.0 173.0,278.0L173.0,0.0L85.0,0.0L85.0,536.0L156.0,536.0L169.0,463.0L174.0,463.0Q200.0,505.0 246.0,525.5Q292.0,546.0 343.0,546.0Z"  transform="translate(1408, 983)"/>
<path d="M-388.0,766.0Q-377.0,744.0 -360.5,716.5Q-344.0,689.0 -325.5,663.0Q-307.0,637.0 -292.0,618.0L-292.0,606.0L-351.0,606.0Q-374.0,624.0 -403.0,652.5Q-432.0,681.0 -456.5,709.5Q-481.0,738.0 -493.0,756.0L-493.0,766.0L-388.0,766.0Z"  transform="translate(2026, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(2026, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(2626, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2970 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M530.0,-12.0Q477.0,-12.0 440.0,8.0Q403.0,28.0 375.0,74.0Q338.0,22.0 298.5,5.0Q259.0,-12.0 205.0,-12.0Q150.0,-12.0 113.5,7.5Q77.0,27.0 59.0,59.5Q41.0,92.0 41.0,130.0Q41.0,191.0 78.5,227.0Q116.0,263.0 189.0,289.0Q230.0,304.0 254.0,321.0Q278.0,338.0 278.0,371.0Q278.0,394.0 261.5,410.5Q245.0,427.0 203.0,427.0Q160.0,427.0 139.0,410.5Q118.0,394.0 118.0,365.0Q118.0,352.0 121.5,341.0Q125.0,330.0 128.0,323.0L53.0,302.0Q36.0,333.0 36.0,375.0Q36.0,407.0 53.0,435.5Q70.0,464.0 107.0,482.0Q144.0,500.0 203.0,500.0Q257.0,500.0 290.5,483.0Q324.0,466.0 340.0,439.5Q356.0,413.0 359.0,385.0Q390.0,356.0 432.5,341.5Q475.0,327.0 514.0,327.0Q592.0,327.0 592.0,376.0Q592.0,395.0 581.5,407.0Q571.0,419.0 556.0,425.0L452.0,425.0L452.0,500.0L819.0,500.0Q884.0,500.0 920.5,492.0Q957.0,484.0 984.0,462.0Q1005.0,446.0 1018.0,418.5Q1031.0,391.0 1031.0,353.0Q1031.0,290.0 993.0,255.0Q955.0,220.0 890.0,220.0Q840.0,220.0 810.0,239.0Q780.0,258.0 766.5,287.0Q753.0,316.0 753.0,344.0Q753.0,369.0 759.0,388.5Q765.0,408.0 775.0,425.0L663.0,425.0Q673.0,404.0 673.0,377.0Q673.0,324.0 631.5,288.0Q590.0,252.0 512.0,252.0Q458.0,252.0 416.0,267.5Q374.0,283.0 345.0,306.0Q330.0,279.0 300.5,260.0Q271.0,241.0 227.0,225.0Q174.0,205.0 148.5,184.5Q123.0,164.0 123.0,131.0Q123.0,102.0 143.5,84.5Q164.0,67.0 207.0,67.0Q269.0,67.0 300.5,99.5Q332.0,132.0 336.0,185.0L414.0,185.0Q418.0,124.0 450.0,95.5Q482.0,67.0 527.0,67.0Q574.0,67.0 596.0,87.0Q618.0,107.0 618.0,142.0Q618.0,165.0 611.0,184.0Q604.0,203.0 593.0,221.0L667.0,252.0Q682.0,230.0 691.5,198.5Q701.0,167.0 701.0,135.0Q701.0,66.0 656.5,27.0Q612.0,-12.0 530.0,-12.0ZM826.0,353.0Q826.0,323.0 843.5,304.5Q861.0,286.0 894.0,286.0Q929.0,286.0 943.5,304.5Q958.0,323.0 958.0,350.0Q958.0,392.0 932.5,408.5Q907.0,425.0 861.0,425.0L852.0,425.0Q826.0,391.0 826.0,353.0Z"  transform="translate(362, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1408, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(2008, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(2608, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(ǰలు)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+362|.notdef=1+600|latelu=2+709|uvowelsigntelu=2+0|parenright.telu=4+362</pre>



<pre>Got     : parenleft.telu=0+362|j=1+258|caroncomb=1+0|latelu=2+709|uvowelsigntelu=2+0|parenright.telu=4+362</pre>



<pre>                               ^^^^^^^   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1691 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M78.0,681.0Q78.0,710.0 93.0,723.5Q108.0,737.0 130.0,737.0Q150.0,737.0 165.5,723.5Q181.0,710.0 181.0,681.0Q181.0,653.0 165.5,639.0Q150.0,625.0 130.0,625.0Q108.0,625.0 93.0,639.0Q78.0,653.0 78.0,681.0ZM22.0,-240.0Q-3.0,-240.0 -22.0,-236.5Q-41.0,-233.0 -55.0,-228.0L-55.0,-157.0Q-40.0,-161.0 -24.0,-164.0Q-8.0,-167.0 11.0,-167.0Q43.0,-167.0 64.0,-149.5Q85.0,-132.0 85.0,-83.0L85.0,536.0L173.0,536.0L173.0,-80.0Q173.0,-155.0 137.0,-197.5Q101.0,-240.0 22.0,-240.0Z"  transform="translate(362, 983)"/>
<path d="M-46.0,606.0Q-59.0,629.0 -81.0,655.5Q-103.0,682.0 -127.0,708.0Q-151.0,734.0 -169.0,753.0L-169.0,766.0L-109.0,766.0Q-83.0,749.0 -55.0,725.0Q-27.0,701.0 -2.0,674.0Q25.0,701.0 53.0,725.0Q81.0,749.0 107.0,766.0L169.0,766.0L169.0,753.0Q150.0,734.0 125.5,708.0Q101.0,682.0 78.5,655.5Q56.0,629.0 44.0,606.0L-46.0,606.0Z"  transform="translate(620, 983)"/>
<path d="M356.0,-12.0Q251.0,-12.0 179.5,24.0Q108.0,60.0 71.5,123.5Q35.0,187.0 35.0,269.0Q35.0,343.0 60.5,394.5Q86.0,446.0 129.0,473.0Q172.0,500.0 225.0,500.0Q284.0,500.0 320.5,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 201.0,235.0Q176.0,235.0 154.0,241.5Q132.0,248.0 114.0,258.0Q116.0,206.0 142.5,163.0Q169.0,120.0 221.0,93.5Q273.0,67.0 353.0,67.0Q463.0,67.0 527.0,113.0Q591.0,159.0 591.0,245.0Q591.0,303.0 558.5,349.0Q526.0,395.0 457.0,423.0L497.0,500.0Q580.0,464.0 627.0,400.0Q674.0,336.0 674.0,250.0Q674.0,176.0 641.0,116.5Q608.0,57.0 537.5,22.5Q467.0,-12.0 356.0,-12.0ZM220.0,429.0Q181.0,429.0 154.0,402.5Q127.0,376.0 118.0,329.0Q132.0,319.0 151.5,312.0Q171.0,305.0 196.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0Z"  transform="translate(620, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(1329, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(1329, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2033 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(362, 983)"/>
<path d="M356.0,-12.0Q251.0,-12.0 179.5,24.0Q108.0,60.0 71.5,123.5Q35.0,187.0 35.0,269.0Q35.0,343.0 60.5,394.5Q86.0,446.0 129.0,473.0Q172.0,500.0 225.0,500.0Q284.0,500.0 320.5,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 201.0,235.0Q176.0,235.0 154.0,241.5Q132.0,248.0 114.0,258.0Q116.0,206.0 142.5,163.0Q169.0,120.0 221.0,93.5Q273.0,67.0 353.0,67.0Q463.0,67.0 527.0,113.0Q591.0,159.0 591.0,245.0Q591.0,303.0 558.5,349.0Q526.0,395.0 457.0,423.0L497.0,500.0Q580.0,464.0 627.0,400.0Q674.0,336.0 674.0,250.0Q674.0,176.0 641.0,116.5Q608.0,57.0 537.5,22.5Q467.0,-12.0 356.0,-12.0ZM220.0,429.0Q181.0,429.0 154.0,402.5Q127.0,376.0 118.0,329.0Q132.0,319.0 151.5,312.0Q171.0,305.0 196.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0Z"  transform="translate(962, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(1671, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(1671, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">Language:</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: .notdef=0+600|.notdef=1+600|.notdef=2+600|.notdef=3+600|.notdef=4+600|.notdef=5+600|.notdef=6+600|.notdef=7+600|colon.telu=8+268</pre>



<pre>Got     : L=0+524|a=1+561|n=2+618|g=3+615|u=4+618|a=5+561|g=6+615|e=7+564|colon.telu=8+268</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4944 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M97.0,0.0L97.0,714.0L187.0,714.0L187.0,80.0L499.0,80.0L499.0,0.0L97.0,0.0Z"  transform="translate(0, 983)"/>
<path d="M288.0,545.0Q386.0,545.0 433.0,502.0Q480.0,459.0 480.0,365.0L480.0,0.0L416.0,0.0L399.0,76.0L395.0,76.0Q360.0,32.0 321.5,11.0Q283.0,-10.0 215.0,-10.0Q142.0,-10.0 94.0,28.5Q46.0,67.0 46.0,149.0Q46.0,229.0 109.0,272.5Q172.0,316.0 303.0,320.0L394.0,323.0L394.0,355.0Q394.0,422.0 365.0,448.0Q336.0,474.0 283.0,474.0Q241.0,474.0 203.0,461.5Q165.0,449.0 132.0,433.0L105.0,499.0Q140.0,518.0 188.0,531.5Q236.0,545.0 288.0,545.0ZM314.0,259.0Q214.0,255.0 175.5,227.0Q137.0,199.0 137.0,148.0Q137.0,103.0 164.5,82.0Q192.0,61.0 235.0,61.0Q303.0,61.0 348.0,98.5Q393.0,136.0 393.0,214.0L393.0,262.0L314.0,259.0Z"  transform="translate(524, 983)"/>
<path d="M343.0,546.0Q439.0,546.0 488.0,499.5Q537.0,453.0 537.0,349.0L537.0,0.0L450.0,0.0L450.0,343.0Q450.0,472.0 330.0,472.0Q241.0,472.0 207.0,422.0Q173.0,372.0 173.0,278.0L173.0,0.0L85.0,0.0L85.0,536.0L156.0,536.0L169.0,463.0L174.0,463.0Q200.0,505.0 246.0,525.5Q292.0,546.0 343.0,546.0Z"  transform="translate(1085, 983)"/>
<path d="M275.0,546.0Q328.0,546.0 370.5,526.0Q413.0,506.0 443.0,465.0L448.0,465.0L460.0,536.0L530.0,536.0L530.0,-9.0Q530.0,-124.0 471.5,-182.0Q413.0,-240.0 290.0,-240.0Q172.0,-240.0 97.0,-206.0L97.0,-125.0Q176.0,-167.0 295.0,-167.0Q364.0,-167.0 403.5,-126.5Q443.0,-86.0 443.0,-16.0L443.0,5.0Q443.0,17.0 444.0,39.5Q445.0,62.0 446.0,71.0L442.0,71.0Q388.0,-10.0 276.0,-10.0Q172.0,-10.0 113.5,63.0Q55.0,136.0 55.0,267.0Q55.0,395.0 113.5,470.5Q172.0,546.0 275.0,546.0ZM287.0,472.0Q220.0,472.0 183.0,418.5Q146.0,365.0 146.0,266.0Q146.0,167.0 182.5,114.5Q219.0,62.0 289.0,62.0Q370.0,62.0 407.0,105.5Q444.0,149.0 444.0,246.0L444.0,267.0Q444.0,377.0 406.0,424.5Q368.0,472.0 287.0,472.0Z"  transform="translate(1703, 983)"/>
<path d="M533.0,536.0L533.0,0.0L461.0,0.0L448.0,71.0L444.0,71.0Q418.0,29.0 372.0,9.5Q326.0,-10.0 274.0,-10.0Q177.0,-10.0 128.0,36.5Q79.0,83.0 79.0,185.0L79.0,536.0L168.0,536.0L168.0,191.0Q168.0,63.0 287.0,63.0Q376.0,63.0 410.5,113.0Q445.0,163.0 445.0,257.0L445.0,536.0L533.0,536.0Z"  transform="translate(2318, 983)"/>
<path d="M288.0,545.0Q386.0,545.0 433.0,502.0Q480.0,459.0 480.0,365.0L480.0,0.0L416.0,0.0L399.0,76.0L395.0,76.0Q360.0,32.0 321.5,11.0Q283.0,-10.0 215.0,-10.0Q142.0,-10.0 94.0,28.5Q46.0,67.0 46.0,149.0Q46.0,229.0 109.0,272.5Q172.0,316.0 303.0,320.0L394.0,323.0L394.0,355.0Q394.0,422.0 365.0,448.0Q336.0,474.0 283.0,474.0Q241.0,474.0 203.0,461.5Q165.0,449.0 132.0,433.0L105.0,499.0Q140.0,518.0 188.0,531.5Q236.0,545.0 288.0,545.0ZM314.0,259.0Q214.0,255.0 175.5,227.0Q137.0,199.0 137.0,148.0Q137.0,103.0 164.5,82.0Q192.0,61.0 235.0,61.0Q303.0,61.0 348.0,98.5Q393.0,136.0 393.0,214.0L393.0,262.0L314.0,259.0Z"  transform="translate(2936, 983)"/>
<path d="M275.0,546.0Q328.0,546.0 370.5,526.0Q413.0,506.0 443.0,465.0L448.0,465.0L460.0,536.0L530.0,536.0L530.0,-9.0Q530.0,-124.0 471.5,-182.0Q413.0,-240.0 290.0,-240.0Q172.0,-240.0 97.0,-206.0L97.0,-125.0Q176.0,-167.0 295.0,-167.0Q364.0,-167.0 403.5,-126.5Q443.0,-86.0 443.0,-16.0L443.0,5.0Q443.0,17.0 444.0,39.5Q445.0,62.0 446.0,71.0L442.0,71.0Q388.0,-10.0 276.0,-10.0Q172.0,-10.0 113.5,63.0Q55.0,136.0 55.0,267.0Q55.0,395.0 113.5,470.5Q172.0,546.0 275.0,546.0ZM287.0,472.0Q220.0,472.0 183.0,418.5Q146.0,365.0 146.0,266.0Q146.0,167.0 182.5,114.5Q219.0,62.0 289.0,62.0Q370.0,62.0 407.0,105.5Q444.0,149.0 444.0,246.0L444.0,267.0Q444.0,377.0 406.0,424.5Q368.0,472.0 287.0,472.0Z"  transform="translate(3497, 983)"/>
<path d="M292.0,546.0Q361.0,546.0 410.5,516.0Q460.0,486.0 486.5,431.5Q513.0,377.0 513.0,304.0L513.0,251.0L146.0,251.0Q148.0,160.0 192.5,112.5Q237.0,65.0 317.0,65.0Q368.0,65.0 407.5,74.5Q447.0,84.0 489.0,102.0L489.0,25.0Q448.0,7.0 408.0,-1.5Q368.0,-10.0 313.0,-10.0Q237.0,-10.0 178.5,21.0Q120.0,52.0 87.5,113.5Q55.0,175.0 55.0,264.0Q55.0,352.0 84.5,415.0Q114.0,478.0 167.5,512.0Q221.0,546.0 292.0,546.0ZM291.0,474.0Q228.0,474.0 191.5,433.5Q155.0,393.0 148.0,321.0L421.0,321.0Q420.0,389.0 389.0,431.5Q358.0,474.0 291.0,474.0Z"  transform="translate(4112, 983)"/>
<path d="M72.0,387.0Q72.0,425.0 90.0,440.0Q108.0,455.0 133.0,455.0Q159.0,455.0 177.5,440.0Q196.0,425.0 196.0,387.0Q196.0,351.0 177.5,335.0Q159.0,319.0 133.0,319.0Q108.0,319.0 90.0,335.0Q72.0,351.0 72.0,387.0ZM72.0,57.0Q72.0,93.0 90.0,108.5Q108.0,124.0 133.0,124.0Q159.0,124.0 177.5,108.5Q196.0,93.0 196.0,57.0Q196.0,20.0 177.5,4.0Q159.0,-12.0 133.0,-12.0Q108.0,-12.0 90.0,4.0Q72.0,20.0 72.0,57.0Z"  transform="translate(4676, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5068 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(600, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1200, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1800, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(2400, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3000, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3600, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(4200, 983)"/>
<path d="M72.0,387.0Q72.0,425.0 90.0,440.0Q108.0,455.0 133.0,455.0Q159.0,455.0 177.5,440.0Q196.0,425.0 196.0,387.0Q196.0,351.0 177.5,335.0Q159.0,319.0 133.0,319.0Q108.0,319.0 90.0,335.0Q72.0,351.0 72.0,387.0ZM72.0,57.0Q72.0,93.0 90.0,108.5Q108.0,124.0 133.0,124.0Q159.0,124.0 177.5,108.5Q196.0,93.0 196.0,57.0Q196.0,20.0 177.5,4.0Q159.0,-12.0 133.0,-12.0Q108.0,-12.0 90.0,4.0Q72.0,20.0 72.0,57.0Z"  transform="translate(4800, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C18</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|one.telu=2+572|eight.telu=3+572</pre>



<pre>Got     : zero.telu=0+572|C=1+632|one.telu=2+572|eight.telu=3+572</pre>



<pre>                          ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2348 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M356.0,0.0L272.0,0.0L272.0,440.0Q272.0,483.0 273.0,511.0Q274.0,539.0 276.0,567.0Q260.0,551.0 245.0,537.5Q230.0,524.0 210.0,508.0L134.0,446.0L88.0,505.0L281.0,655.0L356.0,655.0L356.0,0.0Z"  transform="translate(1204, 983)"/>
<path d="M285.0,661.0Q379.0,661.0 439.0,621.0Q499.0,581.0 499.0,506.0Q499.0,447.0 460.5,409.5Q422.0,372.0 363.0,347.0Q408.0,329.0 444.0,304.5Q480.0,280.0 501.0,247.0Q522.0,214.0 522.0,169.0Q522.0,87.0 458.5,38.5Q395.0,-10.0 288.0,-10.0Q173.0,-10.0 111.0,36.5Q49.0,83.0 49.0,167.0Q49.0,233.0 92.0,275.0Q135.0,317.0 197.0,342.0Q142.0,370.0 107.0,408.0Q72.0,446.0 72.0,506.0Q72.0,556.0 100.0,590.5Q128.0,625.0 176.0,643.0Q224.0,661.0 285.0,661.0ZM284.0,590.0Q227.0,590.0 191.5,567.0Q156.0,544.0 156.0,500.0Q156.0,469.0 174.0,447.5Q192.0,426.0 222.0,410.5Q252.0,395.0 289.0,381.0Q342.0,400.0 378.0,427.0Q414.0,454.0 414.0,500.0Q414.0,544.0 378.5,567.0Q343.0,590.0 284.0,590.0ZM133.0,167.0Q133.0,121.0 170.5,90.5Q208.0,60.0 286.0,60.0Q360.0,60.0 399.0,90.5Q438.0,121.0 438.0,170.0Q438.0,216.0 396.5,246.5Q355.0,277.0 287.0,300.0L270.0,306.0Q203.0,281.0 168.0,248.5Q133.0,216.0 133.0,167.0Z"  transform="translate(1776, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2316 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M356.0,0.0L272.0,0.0L272.0,440.0Q272.0,483.0 273.0,511.0Q274.0,539.0 276.0,567.0Q260.0,551.0 245.0,537.5Q230.0,524.0 210.0,508.0L134.0,446.0L88.0,505.0L281.0,655.0L356.0,655.0L356.0,0.0Z"  transform="translate(1172, 983)"/>
<path d="M285.0,661.0Q379.0,661.0 439.0,621.0Q499.0,581.0 499.0,506.0Q499.0,447.0 460.5,409.5Q422.0,372.0 363.0,347.0Q408.0,329.0 444.0,304.5Q480.0,280.0 501.0,247.0Q522.0,214.0 522.0,169.0Q522.0,87.0 458.5,38.5Q395.0,-10.0 288.0,-10.0Q173.0,-10.0 111.0,36.5Q49.0,83.0 49.0,167.0Q49.0,233.0 92.0,275.0Q135.0,317.0 197.0,342.0Q142.0,370.0 107.0,408.0Q72.0,446.0 72.0,506.0Q72.0,556.0 100.0,590.5Q128.0,625.0 176.0,643.0Q224.0,661.0 285.0,661.0ZM284.0,590.0Q227.0,590.0 191.5,567.0Q156.0,544.0 156.0,500.0Q156.0,469.0 174.0,447.5Q192.0,426.0 222.0,410.5Q252.0,395.0 289.0,381.0Q342.0,400.0 378.0,427.0Q414.0,454.0 414.0,500.0Q414.0,544.0 378.5,567.0Q343.0,590.0 284.0,590.0ZM133.0,167.0Q133.0,121.0 170.5,90.5Q208.0,60.0 286.0,60.0Q360.0,60.0 399.0,90.5Q438.0,121.0 438.0,170.0Q438.0,216.0 396.5,246.5Q355.0,277.0 287.0,300.0L270.0,306.0Q203.0,281.0 168.0,248.5Q133.0,216.0 133.0,167.0Z"  transform="translate(1744, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C24</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|two.telu=2+572|four.telu=3+572</pre>



<pre>Got     : zero.telu=0+572|C=1+632|two.telu=2+572|four.telu=3+572</pre>



<pre>                          ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2348 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(1204, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(1776, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2316 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(1172, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(1744, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C30</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|three.telu=2+572|zero.telu=3+572</pre>



<pre>Got     : zero.telu=0+572|C=1+632|three.telu=2+572|zero.telu=3+572</pre>



<pre>                          ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2348 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(1204, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(1776, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2316 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(1172, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(1744, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C4D</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|four.telu=2+572|.notdef=3+600</pre>



<pre>Got     : zero.telu=0+572|C=1+632|four.telu=2+572|D=3+730</pre>



<pre>                          ^^^^^^^    ^^                 ^^^^^^^   ^ +
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2506 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(1204, 983)"/>
<path d="M669.0,364.0Q669.0,183.0 570.5,91.5Q472.0,0.0 296.0,0.0L97.0,0.0L97.0,714.0L317.0,714.0Q425.0,714.0 504.0,674.0Q583.0,634.0 626.0,556.5Q669.0,479.0 669.0,364.0ZM574.0,361.0Q574.0,504.0 503.5,570.5Q433.0,637.0 304.0,637.0L187.0,637.0L187.0,77.0L284.0,77.0Q574.0,77.0 574.0,361.0Z"  transform="translate(1776, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2344 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(1172, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1744, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C59</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|five.telu=2+572|nine.telu=3+572</pre>



<pre>Got     : zero.telu=0+572|C=1+632|five.telu=2+572|nine.telu=3+572</pre>



<pre>                          ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2348 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M272.0,402.0Q383.0,402.0 449.0,351.5Q515.0,301.0 515.0,209.0Q515.0,107.0 444.5,48.5Q374.0,-10.0 248.0,-10.0Q193.0,-10.0 144.5,0.0Q96.0,10.0 63.0,29.0L63.0,112.0Q99.0,90.0 151.5,77.5Q204.0,65.0 251.0,65.0Q330.0,65.0 378.5,98.0Q427.0,131.0 427.0,201.0Q427.0,263.0 384.5,295.5Q342.0,328.0 248.0,328.0Q219.0,328.0 182.5,323.0Q146.0,318.0 124.0,313.0L80.0,341.0L107.0,651.0L465.0,651.0L465.0,571.0L179.0,571.0L164.0,392.0Q181.0,395.0 209.0,398.5Q237.0,402.0 272.0,402.0Z"  transform="translate(1204, 983)"/>
<path d="M520.0,373.0Q520.0,303.0 506.5,235.0Q493.0,167.0 457.5,111.5Q422.0,56.0 357.5,23.0Q293.0,-10.0 192.0,-10.0Q172.0,-10.0 145.5,-7.5Q119.0,-5.0 102.0,0.0L102.0,75.0Q141.0,62.0 190.0,62.0Q260.0,62.0 306.0,82.5Q352.0,103.0 379.0,138.5Q406.0,174.0 418.5,221.0Q431.0,268.0 433.0,321.0L428.0,321.0Q401.0,284.0 361.0,261.0Q321.0,238.0 256.0,238.0Q163.0,238.0 106.5,290.5Q50.0,343.0 50.0,438.0Q50.0,542.0 112.5,601.5Q175.0,661.0 278.0,661.0Q346.0,661.0 401.0,629.5Q456.0,598.0 488.0,534.5Q520.0,471.0 520.0,373.0ZM278.0,587.0Q215.0,587.0 175.0,550.5Q135.0,514.0 135.0,439.0Q135.0,378.0 169.5,343.0Q204.0,308.0 274.0,308.0Q323.0,308.0 358.5,325.0Q394.0,342.0 413.5,369.0Q433.0,396.0 433.0,424.0Q433.0,463.0 415.5,500.5Q398.0,538.0 364.0,562.5Q330.0,587.0 278.0,587.0Z"  transform="translate(1776, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2316 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M272.0,402.0Q383.0,402.0 449.0,351.5Q515.0,301.0 515.0,209.0Q515.0,107.0 444.5,48.5Q374.0,-10.0 248.0,-10.0Q193.0,-10.0 144.5,0.0Q96.0,10.0 63.0,29.0L63.0,112.0Q99.0,90.0 151.5,77.5Q204.0,65.0 251.0,65.0Q330.0,65.0 378.5,98.0Q427.0,131.0 427.0,201.0Q427.0,263.0 384.5,295.5Q342.0,328.0 248.0,328.0Q219.0,328.0 182.5,323.0Q146.0,318.0 124.0,313.0L80.0,341.0L107.0,651.0L465.0,651.0L465.0,571.0L179.0,571.0L164.0,392.0Q181.0,395.0 209.0,398.5Q237.0,402.0 272.0,402.0Z"  transform="translate(1172, 983)"/>
<path d="M520.0,373.0Q520.0,303.0 506.5,235.0Q493.0,167.0 457.5,111.5Q422.0,56.0 357.5,23.0Q293.0,-10.0 192.0,-10.0Q172.0,-10.0 145.5,-7.5Q119.0,-5.0 102.0,0.0L102.0,75.0Q141.0,62.0 190.0,62.0Q260.0,62.0 306.0,82.5Q352.0,103.0 379.0,138.5Q406.0,174.0 418.5,221.0Q431.0,268.0 433.0,321.0L428.0,321.0Q401.0,284.0 361.0,261.0Q321.0,238.0 256.0,238.0Q163.0,238.0 106.5,290.5Q50.0,343.0 50.0,438.0Q50.0,542.0 112.5,601.5Q175.0,661.0 278.0,661.0Q346.0,661.0 401.0,629.5Q456.0,598.0 488.0,534.5Q520.0,471.0 520.0,373.0ZM278.0,587.0Q215.0,587.0 175.0,550.5Q135.0,514.0 135.0,439.0Q135.0,378.0 169.5,343.0Q204.0,308.0 274.0,308.0Q323.0,308.0 358.5,325.0Q394.0,342.0 413.5,369.0Q433.0,396.0 433.0,424.0Q433.0,463.0 415.5,500.5Q398.0,538.0 364.0,562.5Q330.0,587.0 278.0,587.0Z"  transform="translate(1744, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C6D</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|six.telu=2+572|.notdef=3+600</pre>



<pre>Got     : zero.telu=0+572|C=1+632|six.telu=2+572|D=3+730</pre>



<pre>                          ^^^^^^^    ^^                ^^^^^^^   ^ +
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2506 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M55.0,278.0Q55.0,348.0 68.5,416.0Q82.0,484.0 117.5,539.5Q153.0,595.0 217.0,628.0Q281.0,661.0 382.0,661.0Q403.0,661.0 428.5,659.0Q454.0,657.0 470.0,652.0L470.0,577.0Q452.0,583.0 429.5,586.0Q407.0,589.0 384.0,589.0Q314.0,589.0 268.0,568.5Q222.0,548.0 195.5,512.0Q169.0,476.0 156.5,428.5Q144.0,381.0 142.0,328.0L146.0,328.0Q167.0,361.0 207.5,387.0Q248.0,413.0 317.0,413.0Q410.0,413.0 467.5,360.5Q525.0,308.0 525.0,212.0Q525.0,109.0 463.5,49.5Q402.0,-10.0 298.0,-10.0Q230.0,-10.0 175.0,21.0Q120.0,52.0 87.5,116.0Q55.0,180.0 55.0,278.0ZM297.0,64.0Q361.0,64.0 400.5,100.0Q440.0,136.0 440.0,212.0Q440.0,273.0 405.5,308.5Q371.0,344.0 300.0,344.0Q252.0,344.0 216.5,326.5Q181.0,309.0 161.5,282.0Q142.0,255.0 142.0,227.0Q142.0,189.0 159.5,151.0Q177.0,113.0 211.5,88.5Q246.0,64.0 297.0,64.0Z"  transform="translate(1204, 983)"/>
<path d="M669.0,364.0Q669.0,183.0 570.5,91.5Q472.0,0.0 296.0,0.0L97.0,0.0L97.0,714.0L317.0,714.0Q425.0,714.0 504.0,674.0Q583.0,634.0 626.0,556.5Q669.0,479.0 669.0,364.0ZM574.0,361.0Q574.0,504.0 503.5,570.5Q433.0,637.0 304.0,637.0L187.0,637.0L187.0,77.0L284.0,77.0Q574.0,77.0 574.0,361.0Z"  transform="translate(1776, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2344 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M55.0,278.0Q55.0,348.0 68.5,416.0Q82.0,484.0 117.5,539.5Q153.0,595.0 217.0,628.0Q281.0,661.0 382.0,661.0Q403.0,661.0 428.5,659.0Q454.0,657.0 470.0,652.0L470.0,577.0Q452.0,583.0 429.5,586.0Q407.0,589.0 384.0,589.0Q314.0,589.0 268.0,568.5Q222.0,548.0 195.5,512.0Q169.0,476.0 156.5,428.5Q144.0,381.0 142.0,328.0L146.0,328.0Q167.0,361.0 207.5,387.0Q248.0,413.0 317.0,413.0Q410.0,413.0 467.5,360.5Q525.0,308.0 525.0,212.0Q525.0,109.0 463.5,49.5Q402.0,-10.0 298.0,-10.0Q230.0,-10.0 175.0,21.0Q120.0,52.0 87.5,116.0Q55.0,180.0 55.0,278.0ZM297.0,64.0Q361.0,64.0 400.5,100.0Q440.0,136.0 440.0,212.0Q440.0,273.0 405.5,308.5Q371.0,344.0 300.0,344.0Q252.0,344.0 216.5,326.5Q181.0,309.0 161.5,282.0Q142.0,255.0 142.0,227.0Q142.0,189.0 159.5,151.0Q177.0,113.0 211.5,88.5Q246.0,64.0 297.0,64.0Z"  transform="translate(1172, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1744, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C83</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|eight.telu=2+572|three.telu=3+572</pre>



<pre>Got     : zero.telu=0+572|C=1+632|eight.telu=2+572|three.telu=3+572</pre>



<pre>                          ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2348 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M285.0,661.0Q379.0,661.0 439.0,621.0Q499.0,581.0 499.0,506.0Q499.0,447.0 460.5,409.5Q422.0,372.0 363.0,347.0Q408.0,329.0 444.0,304.5Q480.0,280.0 501.0,247.0Q522.0,214.0 522.0,169.0Q522.0,87.0 458.5,38.5Q395.0,-10.0 288.0,-10.0Q173.0,-10.0 111.0,36.5Q49.0,83.0 49.0,167.0Q49.0,233.0 92.0,275.0Q135.0,317.0 197.0,342.0Q142.0,370.0 107.0,408.0Q72.0,446.0 72.0,506.0Q72.0,556.0 100.0,590.5Q128.0,625.0 176.0,643.0Q224.0,661.0 285.0,661.0ZM284.0,590.0Q227.0,590.0 191.5,567.0Q156.0,544.0 156.0,500.0Q156.0,469.0 174.0,447.5Q192.0,426.0 222.0,410.5Q252.0,395.0 289.0,381.0Q342.0,400.0 378.0,427.0Q414.0,454.0 414.0,500.0Q414.0,544.0 378.5,567.0Q343.0,590.0 284.0,590.0ZM133.0,167.0Q133.0,121.0 170.5,90.5Q208.0,60.0 286.0,60.0Q360.0,60.0 399.0,90.5Q438.0,121.0 438.0,170.0Q438.0,216.0 396.5,246.5Q355.0,277.0 287.0,300.0L270.0,306.0Q203.0,281.0 168.0,248.5Q133.0,216.0 133.0,167.0Z"  transform="translate(1204, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(1776, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2316 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M285.0,661.0Q379.0,661.0 439.0,621.0Q499.0,581.0 499.0,506.0Q499.0,447.0 460.5,409.5Q422.0,372.0 363.0,347.0Q408.0,329.0 444.0,304.5Q480.0,280.0 501.0,247.0Q522.0,214.0 522.0,169.0Q522.0,87.0 458.5,38.5Q395.0,-10.0 288.0,-10.0Q173.0,-10.0 111.0,36.5Q49.0,83.0 49.0,167.0Q49.0,233.0 92.0,275.0Q135.0,317.0 197.0,342.0Q142.0,370.0 107.0,408.0Q72.0,446.0 72.0,506.0Q72.0,556.0 100.0,590.5Q128.0,625.0 176.0,643.0Q224.0,661.0 285.0,661.0ZM284.0,590.0Q227.0,590.0 191.5,567.0Q156.0,544.0 156.0,500.0Q156.0,469.0 174.0,447.5Q192.0,426.0 222.0,410.5Q252.0,395.0 289.0,381.0Q342.0,400.0 378.0,427.0Q414.0,454.0 414.0,500.0Q414.0,544.0 378.5,567.0Q343.0,590.0 284.0,590.0ZM133.0,167.0Q133.0,121.0 170.5,90.5Q208.0,60.0 286.0,60.0Q360.0,60.0 399.0,90.5Q438.0,121.0 438.0,170.0Q438.0,216.0 396.5,246.5Q355.0,277.0 287.0,300.0L270.0,306.0Q203.0,281.0 168.0,248.5Q133.0,216.0 133.0,167.0Z"  transform="translate(1172, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(1744, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ಃ</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: uni25CC=0+578|.notdef=0+600</pre>



<pre>Got     : .notdef=0+600</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 600 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(0, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1178 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M318.0,359.0Q318.0,330.0 289.0,330.0Q260.0,330.0 260.0,359.0Q260.0,387.0 289.0,387.0Q318.0,387.0 318.0,359.0ZM193.0,309.0Q193.0,280.0 165.0,280.0Q136.0,280.0 136.0,309.0Q136.0,338.0 165.0,338.0Q193.0,338.0 193.0,309.0ZM442.0,309.0Q442.0,280.0 414.0,280.0Q385.0,280.0 385.0,309.0Q385.0,338.0 414.0,338.0Q442.0,338.0 442.0,309.0ZM487.0,189.0Q487.0,161.0 458.0,161.0Q429.0,161.0 429.0,189.0Q429.0,218.0 458.0,218.0Q487.0,218.0 487.0,189.0ZM148.0,189.0Q148.0,161.0 120.0,161.0Q91.0,161.0 91.0,189.0Q91.0,218.0 120.0,218.0Q148.0,218.0 148.0,189.0ZM193.0,70.0Q193.0,41.0 165.0,41.0Q136.0,41.0 136.0,70.0Q136.0,99.0 165.0,99.0Q193.0,99.0 193.0,70.0ZM442.0,70.0Q442.0,41.0 414.0,41.0Q385.0,41.0 385.0,70.0Q385.0,99.0 414.0,99.0Q442.0,99.0 442.0,70.0ZM318.0,20.0Q318.0,-9.0 289.0,-9.0Q260.0,-9.0 260.0,20.0Q260.0,49.0 289.0,49.0Q318.0,49.0 318.0,20.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(578, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C4D+0C30</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|four.telu=2+572|.notdef=3+600|plus.telu=4+572|zero.telu=5+572|.notdef=6+600|three.telu=7+572|zero.telu=8+572</pre>



<pre>Got     : zero.telu=0+572|C=1+632|four.telu=2+572|D=3+730|plus.telu=4+572|zero.telu=5+572|C=6+632|three.telu=7+572|zero.telu=8+572</pre>



<pre>                          ^^^^^^^    ^^                 ^^^^^^^   ^^                                  ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5426 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(1204, 983)"/>
<path d="M669.0,364.0Q669.0,183.0 570.5,91.5Q472.0,0.0 296.0,0.0L97.0,0.0L97.0,714.0L317.0,714.0Q425.0,714.0 504.0,674.0Q583.0,634.0 626.0,556.5Q669.0,479.0 669.0,364.0ZM574.0,361.0Q574.0,504.0 503.5,570.5Q433.0,637.0 304.0,637.0L187.0,637.0L187.0,77.0L284.0,77.0Q574.0,77.0 574.0,361.0Z"  transform="translate(1776, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2506, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(3078, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(3650, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(4282, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(4854, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5232 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(1172, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1744, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2344, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(2916, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3488, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(4088, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(4660, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C4D+200C+0C30</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|four.telu=2+572|.notdef=3+600|plus.telu=4+572|two.telu=5+572|zero.telu=6+572|zero.telu=7+572|.notdef=8+600|plus.telu=9+572|zero.telu=10+572|.notdef=11+600|three.telu=12+572|zero.telu=13+572</pre>



<pre>Got     : zero.telu=0+572|C=1+632|four.telu=2+572|D=3+730|plus.telu=4+572|two.telu=5+572|zero.telu=6+572|zero.telu=7+572|C=8+632|plus.telu=9+572|zero.telu=10+572|C=11+632|three.telu=12+572|zero.telu=13+572</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8346 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(1204, 983)"/>
<path d="M669.0,364.0Q669.0,183.0 570.5,91.5Q472.0,0.0 296.0,0.0L97.0,0.0L97.0,714.0L317.0,714.0Q425.0,714.0 504.0,674.0Q583.0,634.0 626.0,556.5Q669.0,479.0 669.0,364.0ZM574.0,361.0Q574.0,504.0 503.5,570.5Q433.0,637.0 304.0,637.0L187.0,637.0L187.0,77.0L284.0,77.0Q574.0,77.0 574.0,361.0Z"  transform="translate(1776, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2506, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(3078, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(3650, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(4222, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(4794, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(5426, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(5998, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(6570, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(7202, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(7774, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8120 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(1172, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1744, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2344, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(2916, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(3488, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(4060, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(4632, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(5232, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(5804, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(6376, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(6976, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(7548, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C2A+0C4D+0C30+0C24+0C3F</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|two.telu=2+572|.notdef=3+600|plus.telu=4+572|zero.telu=5+572|.notdef=6+600|four.telu=7+572|.notdef=8+600|plus.telu=9+572|zero.telu=10+572|.notdef=11+600|three.telu=12+572|zero.telu=13+572|plus.telu=14+572|zero.telu=15+572|.notdef=16+600|two.telu=17+572|four.telu=18+572|plus.telu=19+572|zero.telu=20+572|.notdef=21+600|three.telu=22+572|.notdef=23+600</pre>



<pre>Got     : zero.telu=0+572|C=1+632|two.telu=2+572|A=3+639|plus.telu=4+572|zero.telu=5+572|C=6+632|four.telu=7+572|D=8+730|plus.telu=9+572|zero.telu=10+572|C=11+632|three.telu=12+572|zero.telu=13+572|plus.telu=14+572|zero.telu=15+572|C=16+632|two.telu=17+572|four.telu=18+572|plus.telu=19+572|zero.telu=20+572|C=21+632|three.telu=22+572|F=23+519</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 14200 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(1204, 983)"/>
<path d="M545.0,0.0L459.0,221.0L176.0,221.0L91.0,0.0L0.0,0.0L279.0,717.0L360.0,717.0L638.0,0.0L545.0,0.0ZM352.0,517.0Q349.0,525.0 342.0,546.0Q335.0,567.0 328.5,589.5Q322.0,612.0 318.0,624.0Q311.0,593.0 302.0,563.5Q293.0,534.0 287.0,517.0L206.0,301.0L432.0,301.0L352.0,517.0Z"  transform="translate(1776, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2415, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(2987, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(3559, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(4191, 983)"/>
<path d="M669.0,364.0Q669.0,183.0 570.5,91.5Q472.0,0.0 296.0,0.0L97.0,0.0L97.0,714.0L317.0,714.0Q425.0,714.0 504.0,674.0Q583.0,634.0 626.0,556.5Q669.0,479.0 669.0,364.0ZM574.0,361.0Q574.0,504.0 503.5,570.5Q433.0,637.0 304.0,637.0L187.0,637.0L187.0,77.0L284.0,77.0Q574.0,77.0 574.0,361.0Z"  transform="translate(4763, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(5493, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(6065, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(6637, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(7269, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(7841, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(8413, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(8985, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(9557, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(10189, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(10761, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(11333, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(11905, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(12477, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(13109, 983)"/>
<path d="M187.0,0.0L97.0,0.0L97.0,714.0L496.0,714.0L496.0,635.0L187.0,635.0L187.0,382.0L477.0,382.0L477.0,303.0L187.0,303.0L187.0,0.0Z"  transform="translate(13681, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13952 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(1172, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1744, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2344, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(2916, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3488, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(4088, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(4660, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(5260, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(5832, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(6404, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(7004, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(7576, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(8148, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(8720, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(9292, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(9892, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(10464, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(11036, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(11608, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(12180, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(12780, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(13352, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C2A+0C4D+0C30+0C47+0C2E</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|two.telu=2+572|.notdef=3+600|plus.telu=4+572|zero.telu=5+572|.notdef=6+600|four.telu=7+572|.notdef=8+600|plus.telu=9+572|zero.telu=10+572|.notdef=11+600|three.telu=12+572|zero.telu=13+572|plus.telu=14+572|zero.telu=15+572|.notdef=16+600|four.telu=17+572|seven.telu=18+572|plus.telu=19+572|zero.telu=20+572|.notdef=21+600|two.telu=22+572|.notdef=23+600</pre>



<pre>Got     : zero.telu=0+572|C=1+632|two.telu=2+572|A=3+639|plus.telu=4+572|zero.telu=5+572|C=6+632|four.telu=7+572|D=8+730|plus.telu=9+572|zero.telu=10+572|C=11+632|three.telu=12+572|zero.telu=13+572|plus.telu=14+572|zero.telu=15+572|C=16+632|four.telu=17+572|seven.telu=18+572|plus.telu=19+572|zero.telu=20+572|C=21+632|two.telu=22+572|E=23+556</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 14237 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(1204, 983)"/>
<path d="M545.0,0.0L459.0,221.0L176.0,221.0L91.0,0.0L0.0,0.0L279.0,717.0L360.0,717.0L638.0,0.0L545.0,0.0ZM352.0,517.0Q349.0,525.0 342.0,546.0Q335.0,567.0 328.5,589.5Q322.0,612.0 318.0,624.0Q311.0,593.0 302.0,563.5Q293.0,534.0 287.0,517.0L206.0,301.0L432.0,301.0L352.0,517.0Z"  transform="translate(1776, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2415, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(2987, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(3559, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(4191, 983)"/>
<path d="M669.0,364.0Q669.0,183.0 570.5,91.5Q472.0,0.0 296.0,0.0L97.0,0.0L97.0,714.0L317.0,714.0Q425.0,714.0 504.0,674.0Q583.0,634.0 626.0,556.5Q669.0,479.0 669.0,364.0ZM574.0,361.0Q574.0,504.0 503.5,570.5Q433.0,637.0 304.0,637.0L187.0,637.0L187.0,77.0L284.0,77.0Q574.0,77.0 574.0,361.0Z"  transform="translate(4763, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(5493, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(6065, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(6637, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(7269, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(7841, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(8413, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(8985, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(9557, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(10189, 983)"/>
<path d="M136.0,0.0L429.0,571.0L44.0,571.0L44.0,651.0L523.0,651.0L523.0,583.0L233.0,0.0L136.0,0.0Z"  transform="translate(10761, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(11333, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(11905, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(12477, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(13109, 983)"/>
<path d="M496.0,0.0L97.0,0.0L97.0,714.0L496.0,714.0L496.0,635.0L187.0,635.0L187.0,412.0L478.0,412.0L478.0,334.0L187.0,334.0L187.0,79.0L496.0,79.0L496.0,0.0Z"  transform="translate(13681, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13952 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(1172, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1744, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2344, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(2916, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3488, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(4088, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(4660, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(5260, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(5832, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(6404, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(7004, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(7576, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(8148, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(8720, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(9292, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(9892, 983)"/>
<path d="M136.0,0.0L429.0,571.0L44.0,571.0L44.0,651.0L523.0,651.0L523.0,583.0L233.0,0.0L136.0,0.0Z"  transform="translate(10464, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(11036, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(11608, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(12180, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(12780, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(13352, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C36+0C47+0C16+0C30+0C4D</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|three.telu=2+572|six.telu=3+572|plus.telu=4+572|zero.telu=5+572|.notdef=6+600|four.telu=7+572|seven.telu=8+572|plus.telu=9+572|zero.telu=10+572|.notdef=11+600|one.telu=12+572|six.telu=13+572|plus.telu=14+572|zero.telu=15+572|.notdef=16+600|three.telu=17+572|zero.telu=18+572|plus.telu=19+572|zero.telu=20+572|.notdef=21+600|four.telu=22+572|.notdef=23+600</pre>



<pre>Got     : zero.telu=0+572|C=1+632|three.telu=2+572|six.telu=3+572|plus.telu=4+572|zero.telu=5+572|C=6+632|four.telu=7+572|seven.telu=8+572|plus.telu=9+572|zero.telu=10+572|C=11+632|one.telu=12+572|six.telu=13+572|plus.telu=14+572|zero.telu=15+572|C=16+632|three.telu=17+572|zero.telu=18+572|plus.telu=19+572|zero.telu=20+572|C=21+632|four.telu=22+572|D=23+730</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 14186 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(1204, 983)"/>
<path d="M55.0,278.0Q55.0,348.0 68.5,416.0Q82.0,484.0 117.5,539.5Q153.0,595.0 217.0,628.0Q281.0,661.0 382.0,661.0Q403.0,661.0 428.5,659.0Q454.0,657.0 470.0,652.0L470.0,577.0Q452.0,583.0 429.5,586.0Q407.0,589.0 384.0,589.0Q314.0,589.0 268.0,568.5Q222.0,548.0 195.5,512.0Q169.0,476.0 156.5,428.5Q144.0,381.0 142.0,328.0L146.0,328.0Q167.0,361.0 207.5,387.0Q248.0,413.0 317.0,413.0Q410.0,413.0 467.5,360.5Q525.0,308.0 525.0,212.0Q525.0,109.0 463.5,49.5Q402.0,-10.0 298.0,-10.0Q230.0,-10.0 175.0,21.0Q120.0,52.0 87.5,116.0Q55.0,180.0 55.0,278.0ZM297.0,64.0Q361.0,64.0 400.5,100.0Q440.0,136.0 440.0,212.0Q440.0,273.0 405.5,308.5Q371.0,344.0 300.0,344.0Q252.0,344.0 216.5,326.5Q181.0,309.0 161.5,282.0Q142.0,255.0 142.0,227.0Q142.0,189.0 159.5,151.0Q177.0,113.0 211.5,88.5Q246.0,64.0 297.0,64.0Z"  transform="translate(1776, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2348, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(2920, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(3492, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(4124, 983)"/>
<path d="M136.0,0.0L429.0,571.0L44.0,571.0L44.0,651.0L523.0,651.0L523.0,583.0L233.0,0.0L136.0,0.0Z"  transform="translate(4696, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(5268, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(5840, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(6412, 983)"/>
<path d="M356.0,0.0L272.0,0.0L272.0,440.0Q272.0,483.0 273.0,511.0Q274.0,539.0 276.0,567.0Q260.0,551.0 245.0,537.5Q230.0,524.0 210.0,508.0L134.0,446.0L88.0,505.0L281.0,655.0L356.0,655.0L356.0,0.0Z"  transform="translate(7044, 983)"/>
<path d="M55.0,278.0Q55.0,348.0 68.5,416.0Q82.0,484.0 117.5,539.5Q153.0,595.0 217.0,628.0Q281.0,661.0 382.0,661.0Q403.0,661.0 428.5,659.0Q454.0,657.0 470.0,652.0L470.0,577.0Q452.0,583.0 429.5,586.0Q407.0,589.0 384.0,589.0Q314.0,589.0 268.0,568.5Q222.0,548.0 195.5,512.0Q169.0,476.0 156.5,428.5Q144.0,381.0 142.0,328.0L146.0,328.0Q167.0,361.0 207.5,387.0Q248.0,413.0 317.0,413.0Q410.0,413.0 467.5,360.5Q525.0,308.0 525.0,212.0Q525.0,109.0 463.5,49.5Q402.0,-10.0 298.0,-10.0Q230.0,-10.0 175.0,21.0Q120.0,52.0 87.5,116.0Q55.0,180.0 55.0,278.0ZM297.0,64.0Q361.0,64.0 400.5,100.0Q440.0,136.0 440.0,212.0Q440.0,273.0 405.5,308.5Q371.0,344.0 300.0,344.0Q252.0,344.0 216.5,326.5Q181.0,309.0 161.5,282.0Q142.0,255.0 142.0,227.0Q142.0,189.0 159.5,151.0Q177.0,113.0 211.5,88.5Q246.0,64.0 297.0,64.0Z"  transform="translate(7616, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(8188, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(8760, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(9332, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(9964, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(10536, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(11108, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(11680, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(12252, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(12884, 983)"/>
<path d="M669.0,364.0Q669.0,183.0 570.5,91.5Q472.0,0.0 296.0,0.0L97.0,0.0L97.0,714.0L317.0,714.0Q425.0,714.0 504.0,674.0Q583.0,634.0 626.0,556.5Q669.0,479.0 669.0,364.0ZM574.0,361.0Q574.0,504.0 503.5,570.5Q433.0,637.0 304.0,637.0L187.0,637.0L187.0,77.0L284.0,77.0Q574.0,77.0 574.0,361.0Z"  transform="translate(13456, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13896 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(1172, 983)"/>
<path d="M55.0,278.0Q55.0,348.0 68.5,416.0Q82.0,484.0 117.5,539.5Q153.0,595.0 217.0,628.0Q281.0,661.0 382.0,661.0Q403.0,661.0 428.5,659.0Q454.0,657.0 470.0,652.0L470.0,577.0Q452.0,583.0 429.5,586.0Q407.0,589.0 384.0,589.0Q314.0,589.0 268.0,568.5Q222.0,548.0 195.5,512.0Q169.0,476.0 156.5,428.5Q144.0,381.0 142.0,328.0L146.0,328.0Q167.0,361.0 207.5,387.0Q248.0,413.0 317.0,413.0Q410.0,413.0 467.5,360.5Q525.0,308.0 525.0,212.0Q525.0,109.0 463.5,49.5Q402.0,-10.0 298.0,-10.0Q230.0,-10.0 175.0,21.0Q120.0,52.0 87.5,116.0Q55.0,180.0 55.0,278.0ZM297.0,64.0Q361.0,64.0 400.5,100.0Q440.0,136.0 440.0,212.0Q440.0,273.0 405.5,308.5Q371.0,344.0 300.0,344.0Q252.0,344.0 216.5,326.5Q181.0,309.0 161.5,282.0Q142.0,255.0 142.0,227.0Q142.0,189.0 159.5,151.0Q177.0,113.0 211.5,88.5Q246.0,64.0 297.0,64.0Z"  transform="translate(1744, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2316, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(2888, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3460, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(4060, 983)"/>
<path d="M136.0,0.0L429.0,571.0L44.0,571.0L44.0,651.0L523.0,651.0L523.0,583.0L233.0,0.0L136.0,0.0Z"  transform="translate(4632, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(5204, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(5776, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(6348, 983)"/>
<path d="M356.0,0.0L272.0,0.0L272.0,440.0Q272.0,483.0 273.0,511.0Q274.0,539.0 276.0,567.0Q260.0,551.0 245.0,537.5Q230.0,524.0 210.0,508.0L134.0,446.0L88.0,505.0L281.0,655.0L356.0,655.0L356.0,0.0Z"  transform="translate(6948, 983)"/>
<path d="M55.0,278.0Q55.0,348.0 68.5,416.0Q82.0,484.0 117.5,539.5Q153.0,595.0 217.0,628.0Q281.0,661.0 382.0,661.0Q403.0,661.0 428.5,659.0Q454.0,657.0 470.0,652.0L470.0,577.0Q452.0,583.0 429.5,586.0Q407.0,589.0 384.0,589.0Q314.0,589.0 268.0,568.5Q222.0,548.0 195.5,512.0Q169.0,476.0 156.5,428.5Q144.0,381.0 142.0,328.0L146.0,328.0Q167.0,361.0 207.5,387.0Q248.0,413.0 317.0,413.0Q410.0,413.0 467.5,360.5Q525.0,308.0 525.0,212.0Q525.0,109.0 463.5,49.5Q402.0,-10.0 298.0,-10.0Q230.0,-10.0 175.0,21.0Q120.0,52.0 87.5,116.0Q55.0,180.0 55.0,278.0ZM297.0,64.0Q361.0,64.0 400.5,100.0Q440.0,136.0 440.0,212.0Q440.0,273.0 405.5,308.5Q371.0,344.0 300.0,344.0Q252.0,344.0 216.5,326.5Q181.0,309.0 161.5,282.0Q142.0,255.0 142.0,227.0Q142.0,189.0 159.5,151.0Q177.0,113.0 211.5,88.5Q246.0,64.0 297.0,64.0Z"  transform="translate(7520, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(8092, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(8664, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(9236, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(9836, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(10408, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(10980, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(11552, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(12124, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(12724, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(13296, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">main(teacher)</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: .notdef=0+600|.notdef=1+600|.notdef=2+600|.notdef=3+600|parenleft.telu=4+362|.notdef=5+600|.notdef=6+600|.notdef=7+600|.notdef=8+600|.notdef=9+600|.notdef=10+600|.notdef=11+600|parenright.telu=12+362</pre>



<pre>Got     : m=0+935|a=1+561|i=2+258|n=3+618|parenleft.telu=4+362|t=5+361|e=6+564|a=7+561|c=8+480|h=9+618|e=10+564|r=11+413|parenright.telu=12+362</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6657 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M673.0,546.0Q764.0,546.0 809.0,499.5Q854.0,453.0 854.0,349.0L854.0,0.0L767.0,0.0L767.0,345.0Q767.0,472.0 658.0,472.0Q580.0,472.0 546.5,427.0Q513.0,382.0 513.0,296.0L513.0,0.0L426.0,0.0L426.0,345.0Q426.0,472.0 316.0,472.0Q235.0,472.0 204.0,422.0Q173.0,372.0 173.0,278.0L173.0,0.0L85.0,0.0L85.0,536.0L156.0,536.0L169.0,463.0L174.0,463.0Q199.0,505.0 241.5,525.5Q284.0,546.0 332.0,546.0Q458.0,546.0 496.0,456.0L501.0,456.0Q528.0,502.0 574.5,524.0Q621.0,546.0 673.0,546.0Z"  transform="translate(0, 983)"/>
<path d="M288.0,545.0Q386.0,545.0 433.0,502.0Q480.0,459.0 480.0,365.0L480.0,0.0L416.0,0.0L399.0,76.0L395.0,76.0Q360.0,32.0 321.5,11.0Q283.0,-10.0 215.0,-10.0Q142.0,-10.0 94.0,28.5Q46.0,67.0 46.0,149.0Q46.0,229.0 109.0,272.5Q172.0,316.0 303.0,320.0L394.0,323.0L394.0,355.0Q394.0,422.0 365.0,448.0Q336.0,474.0 283.0,474.0Q241.0,474.0 203.0,461.5Q165.0,449.0 132.0,433.0L105.0,499.0Q140.0,518.0 188.0,531.5Q236.0,545.0 288.0,545.0ZM314.0,259.0Q214.0,255.0 175.5,227.0Q137.0,199.0 137.0,148.0Q137.0,103.0 164.5,82.0Q192.0,61.0 235.0,61.0Q303.0,61.0 348.0,98.5Q393.0,136.0 393.0,214.0L393.0,262.0L314.0,259.0Z"  transform="translate(935, 983)"/>
<path d="M130.0,737.0Q150.0,737.0 165.5,723.5Q181.0,710.0 181.0,681.0Q181.0,653.0 165.5,639.0Q150.0,625.0 130.0,625.0Q108.0,625.0 93.0,639.0Q78.0,653.0 78.0,681.0Q78.0,710.0 93.0,723.5Q108.0,737.0 130.0,737.0ZM173.0,536.0L173.0,0.0L85.0,0.0L85.0,536.0L173.0,536.0Z"  transform="translate(1496, 983)"/>
<path d="M343.0,546.0Q439.0,546.0 488.0,499.5Q537.0,453.0 537.0,349.0L537.0,0.0L450.0,0.0L450.0,343.0Q450.0,472.0 330.0,472.0Q241.0,472.0 207.0,422.0Q173.0,372.0 173.0,278.0L173.0,0.0L85.0,0.0L85.0,536.0L156.0,536.0L169.0,463.0L174.0,463.0Q200.0,505.0 246.0,525.5Q292.0,546.0 343.0,546.0Z"  transform="translate(1754, 983)"/>
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(2372, 983)"/>
<path d="M264.0,62.0Q284.0,62.0 305.0,65.5Q326.0,69.0 339.0,73.0L339.0,6.0Q325.0,-1.0 299.0,-5.5Q273.0,-10.0 249.0,-10.0Q207.0,-10.0 171.5,4.5Q136.0,19.0 114.0,55.0Q92.0,91.0 92.0,156.0L92.0,468.0L16.0,468.0L16.0,510.0L93.0,545.0L128.0,659.0L180.0,659.0L180.0,536.0L335.0,536.0L335.0,468.0L180.0,468.0L180.0,158.0Q180.0,109.0 203.5,85.5Q227.0,62.0 264.0,62.0Z"  transform="translate(2734, 983)"/>
<path d="M292.0,546.0Q361.0,546.0 410.5,516.0Q460.0,486.0 486.5,431.5Q513.0,377.0 513.0,304.0L513.0,251.0L146.0,251.0Q148.0,160.0 192.5,112.5Q237.0,65.0 317.0,65.0Q368.0,65.0 407.5,74.5Q447.0,84.0 489.0,102.0L489.0,25.0Q448.0,7.0 408.0,-1.5Q368.0,-10.0 313.0,-10.0Q237.0,-10.0 178.5,21.0Q120.0,52.0 87.5,113.5Q55.0,175.0 55.0,264.0Q55.0,352.0 84.5,415.0Q114.0,478.0 167.5,512.0Q221.0,546.0 292.0,546.0ZM291.0,474.0Q228.0,474.0 191.5,433.5Q155.0,393.0 148.0,321.0L421.0,321.0Q420.0,389.0 389.0,431.5Q358.0,474.0 291.0,474.0Z"  transform="translate(3095, 983)"/>
<path d="M288.0,545.0Q386.0,545.0 433.0,502.0Q480.0,459.0 480.0,365.0L480.0,0.0L416.0,0.0L399.0,76.0L395.0,76.0Q360.0,32.0 321.5,11.0Q283.0,-10.0 215.0,-10.0Q142.0,-10.0 94.0,28.5Q46.0,67.0 46.0,149.0Q46.0,229.0 109.0,272.5Q172.0,316.0 303.0,320.0L394.0,323.0L394.0,355.0Q394.0,422.0 365.0,448.0Q336.0,474.0 283.0,474.0Q241.0,474.0 203.0,461.5Q165.0,449.0 132.0,433.0L105.0,499.0Q140.0,518.0 188.0,531.5Q236.0,545.0 288.0,545.0ZM314.0,259.0Q214.0,255.0 175.5,227.0Q137.0,199.0 137.0,148.0Q137.0,103.0 164.5,82.0Q192.0,61.0 235.0,61.0Q303.0,61.0 348.0,98.5Q393.0,136.0 393.0,214.0L393.0,262.0L314.0,259.0Z"  transform="translate(3659, 983)"/>
<path d="M300.0,-10.0Q229.0,-10.0 173.5,19.0Q118.0,48.0 86.5,109.0Q55.0,170.0 55.0,265.0Q55.0,364.0 88.0,426.0Q121.0,488.0 177.5,517.0Q234.0,546.0 306.0,546.0Q347.0,546.0 385.0,537.5Q423.0,529.0 447.0,517.0L420.0,444.0Q396.0,453.0 364.0,461.0Q332.0,469.0 304.0,469.0Q146.0,469.0 146.0,266.0Q146.0,169.0 184.5,117.5Q223.0,66.0 299.0,66.0Q343.0,66.0 376.5,75.0Q410.0,84.0 438.0,97.0L438.0,19.0Q411.0,5.0 378.5,-2.5Q346.0,-10.0 300.0,-10.0Z"  transform="translate(4220, 983)"/>
<path d="M173.0,537.0Q173.0,497.0 168.0,462.0L174.0,462.0Q200.0,503.0 244.5,524.0Q289.0,545.0 341.0,545.0Q439.0,545.0 488.0,498.5Q537.0,452.0 537.0,349.0L537.0,0.0L450.0,0.0L450.0,343.0Q450.0,472.0 330.0,472.0Q240.0,472.0 206.5,421.5Q173.0,371.0 173.0,277.0L173.0,0.0L85.0,0.0L85.0,760.0L173.0,760.0L173.0,537.0Z"  transform="translate(4700, 983)"/>
<path d="M292.0,546.0Q361.0,546.0 410.5,516.0Q460.0,486.0 486.5,431.5Q513.0,377.0 513.0,304.0L513.0,251.0L146.0,251.0Q148.0,160.0 192.5,112.5Q237.0,65.0 317.0,65.0Q368.0,65.0 407.5,74.5Q447.0,84.0 489.0,102.0L489.0,25.0Q448.0,7.0 408.0,-1.5Q368.0,-10.0 313.0,-10.0Q237.0,-10.0 178.5,21.0Q120.0,52.0 87.5,113.5Q55.0,175.0 55.0,264.0Q55.0,352.0 84.5,415.0Q114.0,478.0 167.5,512.0Q221.0,546.0 292.0,546.0ZM291.0,474.0Q228.0,474.0 191.5,433.5Q155.0,393.0 148.0,321.0L421.0,321.0Q420.0,389.0 389.0,431.5Q358.0,474.0 291.0,474.0Z"  transform="translate(5318, 983)"/>
<path d="M335.0,546.0Q350.0,546.0 367.5,544.5Q385.0,543.0 398.0,540.0L387.0,459.0Q374.0,462.0 358.5,464.0Q343.0,466.0 329.0,466.0Q288.0,466.0 252.0,443.5Q216.0,421.0 194.5,380.5Q173.0,340.0 173.0,286.0L173.0,0.0L85.0,0.0L85.0,536.0L157.0,536.0L167.0,438.0L171.0,438.0Q197.0,482.0 238.0,514.0Q279.0,546.0 335.0,546.0Z"  transform="translate(5882, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(6295, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7324 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(600, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1200, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1800, 983)"/>
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(2400, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(2762, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3362, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3962, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(4562, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(5162, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(5762, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(6362, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(6962, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C2E+0C3E+0C38+0C4D+0C1F+0C30+0C4D</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+572|.notdef=1+600|two.telu=2+572|.notdef=3+600|plus.telu=4+572|zero.telu=5+572|.notdef=6+600|three.telu=7+572|.notdef=8+600|plus.telu=9+572|zero.telu=10+572|.notdef=11+600|three.telu=12+572|eight.telu=13+572|plus.telu=14+572|zero.telu=15+572|.notdef=16+600|four.telu=17+572|.notdef=18+600|plus.telu=19+572|zero.telu=20+572|.notdef=21+600|one.telu=22+572|.notdef=23+600|plus.telu=24+572|zero.telu=25+572|.notdef=26+600|three.telu=27+572|zero.telu=28+572|plus.telu=29+572|zero.telu=30+572|.notdef=31+600|four.telu=32+572|.notdef=33+600</pre>



<pre>Got     : zero.telu=0+572|C=1+632|two.telu=2+572|E=3+556|plus.telu=4+572|zero.telu=5+572|C=6+632|three.telu=7+572|E=8+556|plus.telu=9+572|zero.telu=10+572|C=11+632|three.telu=12+572|eight.telu=13+572|plus.telu=14+572|zero.telu=15+572|C=16+632|four.telu=17+572|D=18+730|plus.telu=19+572|zero.telu=20+572|C=21+632|one.telu=22+572|F=23+519|plus.telu=24+572|zero.telu=25+572|C=26+632|three.telu=27+572|zero.telu=28+572|plus.telu=29+572|zero.telu=30+572|C=31+632|four.telu=32+572|D=33+730</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20099 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(572, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(1204, 983)"/>
<path d="M496.0,0.0L97.0,0.0L97.0,714.0L496.0,714.0L496.0,635.0L187.0,635.0L187.0,412.0L478.0,412.0L478.0,334.0L187.0,334.0L187.0,79.0L496.0,79.0L496.0,0.0Z"  transform="translate(1776, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2332, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(2904, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(3476, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(4108, 983)"/>
<path d="M496.0,0.0L97.0,0.0L97.0,714.0L496.0,714.0L496.0,635.0L187.0,635.0L187.0,412.0L478.0,412.0L478.0,334.0L187.0,334.0L187.0,79.0L496.0,79.0L496.0,0.0Z"  transform="translate(4680, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(5236, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(5808, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(6380, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(7012, 983)"/>
<path d="M285.0,661.0Q379.0,661.0 439.0,621.0Q499.0,581.0 499.0,506.0Q499.0,447.0 460.5,409.5Q422.0,372.0 363.0,347.0Q408.0,329.0 444.0,304.5Q480.0,280.0 501.0,247.0Q522.0,214.0 522.0,169.0Q522.0,87.0 458.5,38.5Q395.0,-10.0 288.0,-10.0Q173.0,-10.0 111.0,36.5Q49.0,83.0 49.0,167.0Q49.0,233.0 92.0,275.0Q135.0,317.0 197.0,342.0Q142.0,370.0 107.0,408.0Q72.0,446.0 72.0,506.0Q72.0,556.0 100.0,590.5Q128.0,625.0 176.0,643.0Q224.0,661.0 285.0,661.0ZM284.0,590.0Q227.0,590.0 191.5,567.0Q156.0,544.0 156.0,500.0Q156.0,469.0 174.0,447.5Q192.0,426.0 222.0,410.5Q252.0,395.0 289.0,381.0Q342.0,400.0 378.0,427.0Q414.0,454.0 414.0,500.0Q414.0,544.0 378.5,567.0Q343.0,590.0 284.0,590.0ZM133.0,167.0Q133.0,121.0 170.5,90.5Q208.0,60.0 286.0,60.0Q360.0,60.0 399.0,90.5Q438.0,121.0 438.0,170.0Q438.0,216.0 396.5,246.5Q355.0,277.0 287.0,300.0L270.0,306.0Q203.0,281.0 168.0,248.5Q133.0,216.0 133.0,167.0Z"  transform="translate(7584, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(8156, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(8728, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(9300, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(9932, 983)"/>
<path d="M669.0,364.0Q669.0,183.0 570.5,91.5Q472.0,0.0 296.0,0.0L97.0,0.0L97.0,714.0L317.0,714.0Q425.0,714.0 504.0,674.0Q583.0,634.0 626.0,556.5Q669.0,479.0 669.0,364.0ZM574.0,361.0Q574.0,504.0 503.5,570.5Q433.0,637.0 304.0,637.0L187.0,637.0L187.0,77.0L284.0,77.0Q574.0,77.0 574.0,361.0Z"  transform="translate(10504, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(11234, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(11806, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(12378, 983)"/>
<path d="M356.0,0.0L272.0,0.0L272.0,440.0Q272.0,483.0 273.0,511.0Q274.0,539.0 276.0,567.0Q260.0,551.0 245.0,537.5Q230.0,524.0 210.0,508.0L134.0,446.0L88.0,505.0L281.0,655.0L356.0,655.0L356.0,0.0Z"  transform="translate(13010, 983)"/>
<path d="M187.0,0.0L97.0,0.0L97.0,714.0L496.0,714.0L496.0,635.0L187.0,635.0L187.0,382.0L477.0,382.0L477.0,303.0L187.0,303.0L187.0,0.0Z"  transform="translate(13582, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(14101, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(14673, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(15245, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(15877, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(16449, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(17021, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(17593, 983)"/>
<path d="M403.0,645.0Q288.0,645.0 222.0,568.0Q156.0,491.0 156.0,357.0Q156.0,224.0 217.5,146.5Q279.0,69.0 402.0,69.0Q449.0,69.0 491.0,77.0Q533.0,85.0 573.0,97.0L573.0,19.0Q533.0,4.0 490.5,-3.0Q448.0,-10.0 389.0,-10.0Q280.0,-10.0 207.0,35.0Q134.0,80.0 97.5,163.0Q61.0,246.0 61.0,358.0Q61.0,466.0 100.5,548.5Q140.0,631.0 217.0,677.5Q294.0,724.0 404.0,724.0Q517.0,724.0 601.0,682.0L565.0,606.0Q532.0,621.0 491.5,633.0Q451.0,645.0 403.0,645.0Z"  transform="translate(18165, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(18797, 983)"/>
<path d="M669.0,364.0Q669.0,183.0 570.5,91.5Q472.0,0.0 296.0,0.0L97.0,0.0L97.0,714.0L317.0,714.0Q425.0,714.0 504.0,674.0Q583.0,634.0 626.0,556.5Q669.0,479.0 669.0,364.0ZM574.0,361.0Q574.0,504.0 503.5,570.5Q433.0,637.0 304.0,637.0L187.0,637.0L187.0,77.0L284.0,77.0Q574.0,77.0 574.0,361.0Z"  transform="translate(19369, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 19784 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(0, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(572, 983)"/>
<path d="M520.0,0.0L48.0,0.0L48.0,73.0L235.0,242.0Q291.0,293.0 328.5,330.5Q366.0,368.0 384.5,403.0Q403.0,438.0 403.0,479.0Q403.0,531.0 368.5,558.5Q334.0,586.0 275.0,586.0Q223.0,586.0 183.5,568.0Q144.0,550.0 103.0,518.0L56.0,577.0Q98.0,612.0 152.5,636.5Q207.0,661.0 275.0,661.0Q375.0,661.0 433.0,615.5Q491.0,570.0 491.0,490.0Q491.0,438.0 470.5,394.0Q450.0,350.0 411.5,307.5Q373.0,265.0 318.0,216.0L169.0,84.0L169.0,80.0L520.0,80.0L520.0,0.0Z"  transform="translate(1172, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(1744, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(2344, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(2916, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(3488, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(4088, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(4660, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(5260, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(5832, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(6404, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(7004, 983)"/>
<path d="M285.0,661.0Q379.0,661.0 439.0,621.0Q499.0,581.0 499.0,506.0Q499.0,447.0 460.5,409.5Q422.0,372.0 363.0,347.0Q408.0,329.0 444.0,304.5Q480.0,280.0 501.0,247.0Q522.0,214.0 522.0,169.0Q522.0,87.0 458.5,38.5Q395.0,-10.0 288.0,-10.0Q173.0,-10.0 111.0,36.5Q49.0,83.0 49.0,167.0Q49.0,233.0 92.0,275.0Q135.0,317.0 197.0,342.0Q142.0,370.0 107.0,408.0Q72.0,446.0 72.0,506.0Q72.0,556.0 100.0,590.5Q128.0,625.0 176.0,643.0Q224.0,661.0 285.0,661.0ZM284.0,590.0Q227.0,590.0 191.5,567.0Q156.0,544.0 156.0,500.0Q156.0,469.0 174.0,447.5Q192.0,426.0 222.0,410.5Q252.0,395.0 289.0,381.0Q342.0,400.0 378.0,427.0Q414.0,454.0 414.0,500.0Q414.0,544.0 378.5,567.0Q343.0,590.0 284.0,590.0ZM133.0,167.0Q133.0,121.0 170.5,90.5Q208.0,60.0 286.0,60.0Q360.0,60.0 399.0,90.5Q438.0,121.0 438.0,170.0Q438.0,216.0 396.5,246.5Q355.0,277.0 287.0,300.0L270.0,306.0Q203.0,281.0 168.0,248.5Q133.0,216.0 133.0,167.0Z"  transform="translate(7576, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(8148, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(8720, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(9292, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(9892, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(10464, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(11064, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(11636, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(12208, 983)"/>
<path d="M356.0,0.0L272.0,0.0L272.0,440.0Q272.0,483.0 273.0,511.0Q274.0,539.0 276.0,567.0Q260.0,551.0 245.0,537.5Q230.0,524.0 210.0,508.0L134.0,446.0L88.0,505.0L281.0,655.0L356.0,655.0L356.0,0.0Z"  transform="translate(12808, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(13380, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(13980, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(14552, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(15124, 983)"/>
<path d="M493.0,500.0Q493.0,435.0 455.5,397.5Q418.0,360.0 356.0,344.0L356.0,340.0Q436.0,328.0 475.5,288.0Q515.0,248.0 515.0,186.0Q515.0,100.0 449.0,45.0Q383.0,-10.0 241.0,-10.0Q185.0,-10.0 137.0,-1.5Q89.0,7.0 45.0,29.0L45.0,111.0Q90.0,89.0 142.0,76.5Q194.0,64.0 242.0,64.0Q340.0,64.0 382.5,97.0Q425.0,130.0 425.0,188.0Q425.0,247.0 372.0,273.0Q319.0,299.0 223.0,299.0L154.0,299.0L154.0,374.0L224.0,374.0Q313.0,374.0 359.0,406.5Q405.0,439.0 405.0,492.0Q405.0,537.0 369.5,562.0Q334.0,587.0 273.0,587.0Q215.0,587.0 174.0,570.0Q133.0,553.0 93.0,527.0L49.0,587.0Q87.0,617.0 143.5,639.0Q200.0,661.0 272.0,661.0Q384.0,661.0 438.5,615.5Q493.0,570.0 493.0,500.0Z"  transform="translate(15724, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(16296, 983)"/>
<path d="M249.0,291.0L50.0,291.0L50.0,362.0L249.0,362.0L249.0,569.0L321.0,569.0L321.0,362.0L520.0,362.0L520.0,291.0L321.0,291.0L321.0,84.0L249.0,84.0L249.0,291.0Z"  transform="translate(16868, 983)"/>
<path d="M523.0,326.0Q523.0,168.0 467.0,79.0Q411.0,-10.0 285.0,-10.0Q164.0,-10.0 106.5,79.0Q49.0,168.0 49.0,326.0Q49.0,484.0 104.5,572.5Q160.0,661.0 285.0,661.0Q405.0,661.0 464.0,573.0Q523.0,485.0 523.0,326.0ZM135.0,326.0Q135.0,195.0 169.0,130.0Q203.0,65.0 285.0,65.0Q367.0,65.0 401.5,129.5Q436.0,194.0 436.0,326.0Q436.0,457.0 401.5,521.5Q367.0,586.0 285.0,586.0Q203.0,586.0 169.0,521.5Q135.0,457.0 135.0,326.0Z"  transform="translate(17440, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(18012, 983)"/>
<path d="M552.0,146.0L446.0,146.0L446.0,0.0L363.0,0.0L363.0,146.0L21.0,146.0L21.0,220.0L357.0,655.0L446.0,655.0L446.0,220.0L552.0,220.0L552.0,146.0ZM363.0,225.0L363.0,422.0Q363.0,468.0 364.5,500.0Q366.0,532.0 368.0,561.0L364.0,561.0Q355.0,545.0 341.0,523.5Q327.0,502.0 310.0,479.0L110.0,225.0L363.0,225.0Z"  transform="translate(18612, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(19184, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">రాష్ట్రాల</span> (fontdiff-Telugu.html)</li>


<pre>Expected: raavoweltelu=0+906|ssaavoweltelu=2+1051|ttasubscripttelu=2@-424,-30+0|rasubscripttelu=2+420|latelu=8+709</pre>



<pre>Got     : raavoweltelu=0+906|ssaavoweltelu=2+1051|ttasubscripttelu=2@-424,0+0|rasubscripttelu=2+420|latelu=8+709</pre>



<pre>                                                                          ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3086 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M42.0,236.0Q42.0,297.0 62.5,345.0Q83.0,393.0 121.0,425.0L43.0,425.0L43.0,500.0L710.0,500.0Q775.0,500.0 811.5,492.0Q848.0,484.0 875.0,462.0Q896.0,446.0 909.0,418.5Q922.0,391.0 922.0,353.0Q922.0,290.0 884.0,255.0Q846.0,220.0 781.0,220.0Q731.0,220.0 701.0,239.0Q671.0,258.0 657.5,287.0Q644.0,316.0 644.0,344.0Q644.0,369.0 650.0,388.5Q656.0,408.0 666.0,425.0L488.0,425.0Q524.0,393.0 544.5,346.0Q565.0,299.0 565.0,237.0Q565.0,163.0 533.0,106.5Q501.0,50.0 442.0,19.0Q383.0,-12.0 303.0,-12.0Q224.0,-12.0 165.5,18.5Q107.0,49.0 74.5,105.0Q42.0,161.0 42.0,236.0ZM717.0,353.0Q717.0,323.0 734.5,304.5Q752.0,286.0 785.0,286.0Q820.0,286.0 834.5,304.5Q849.0,323.0 849.0,350.0Q849.0,392.0 823.5,408.5Q798.0,425.0 752.0,425.0L743.0,425.0Q717.0,391.0 717.0,353.0ZM125.0,248.0Q125.0,167.0 170.0,117.0Q215.0,67.0 303.0,67.0Q392.0,67.0 437.0,116.5Q482.0,166.0 482.0,242.0Q482.0,293.0 462.5,334.5Q443.0,376.0 403.5,400.5Q364.0,425.0 303.0,425.0Q242.0,425.0 202.5,400.5Q163.0,376.0 144.0,336.0Q125.0,296.0 125.0,248.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,98.5Q593.0,130.0 593.0,200.0Q593.0,260.0 571.5,317.5Q550.0,375.0 513.0,425.0L97.0,425.0L97.0,500.0L457.0,500.0Q408.0,544.0 355.0,577.0Q302.0,610.0 244.0,636.0L280.0,712.0Q355.0,680.0 431.5,626.0Q508.0,572.0 567.0,500.0L804.0,500.0Q869.0,500.0 905.5,492.0Q942.0,484.0 969.0,462.0Q990.0,446.0 1003.0,418.5Q1016.0,391.0 1016.0,353.0Q1016.0,290.0 978.0,255.0Q940.0,220.0 875.0,220.0Q825.0,220.0 795.0,239.0Q765.0,258.0 751.5,287.0Q738.0,316.0 738.0,344.0Q738.0,369.0 744.0,388.5Q750.0,408.0 760.0,425.0L613.0,425.0Q643.0,375.0 659.5,317.5Q676.0,260.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM811.0,353.0Q811.0,323.0 828.5,304.5Q846.0,286.0 879.0,286.0Q914.0,286.0 928.5,304.5Q943.0,323.0 943.0,350.0Q943.0,392.0 917.5,408.5Q892.0,425.0 846.0,425.0L837.0,425.0Q811.0,391.0 811.0,353.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0Z"  transform="translate(906, 983)"/>
<path d="M-167.0,-386.0Q-204.0,-386.0 -230.5,-373.0Q-257.0,-360.0 -280.0,-329.0Q-303.0,-363.0 -331.5,-374.5Q-360.0,-386.0 -393.0,-386.0Q-440.0,-386.0 -471.5,-364.5Q-503.0,-343.0 -519.0,-307.5Q-535.0,-272.0 -535.0,-230.0Q-535.0,-175.0 -513.0,-137.5Q-491.0,-100.0 -456.5,-80.5Q-422.0,-61.0 -384.0,-61.0Q-338.0,-61.0 -312.5,-84.5Q-287.0,-108.0 -287.0,-147.0Q-287.0,-188.0 -315.0,-214.5Q-343.0,-241.0 -399.0,-241.0Q-418.0,-241.0 -435.5,-236.5Q-453.0,-232.0 -468.0,-225.0L-468.0,-229.0Q-468.0,-251.0 -462.0,-272.5Q-456.0,-294.0 -439.0,-308.0Q-422.0,-322.0 -391.0,-322.0Q-353.0,-322.0 -335.0,-303.5Q-317.0,-285.0 -313.0,-254.0L-246.0,-254.0Q-242.0,-289.0 -222.5,-305.5Q-203.0,-322.0 -175.0,-322.0Q-140.0,-322.0 -124.0,-303.5Q-108.0,-285.0 -108.0,-251.0Q-108.0,-204.0 -141.0,-174.0Q-174.0,-144.0 -229.0,-123.0L-195.0,-61.0Q-129.0,-86.0 -83.0,-135.5Q-37.0,-185.0 -37.0,-252.0Q-37.0,-316.0 -72.0,-351.0Q-107.0,-386.0 -167.0,-386.0ZM-390.0,-119.0Q-413.0,-119.0 -432.0,-132.5Q-451.0,-146.0 -460.0,-172.0Q-450.0,-178.0 -436.0,-182.0Q-422.0,-186.0 -406.0,-186.0Q-349.0,-186.0 -349.0,-151.0Q-349.0,-119.0 -390.0,-119.0Z"  transform="translate(1533, 983)"/>
<path d="M168.0,500.0Q224.0,500.0 264.5,473.0Q305.0,446.0 331.0,401.0Q357.0,356.0 369.0,300.5Q381.0,245.0 381.0,187.0Q381.0,52.0 338.0,-59.5Q295.0,-171.0 221.0,-262.5Q147.0,-354.0 54.0,-430.0L1.0,-369.0Q56.0,-324.0 109.0,-269.5Q162.0,-215.0 205.5,-147.0Q249.0,-79.0 275.0,3.5Q301.0,86.0 301.0,186.0Q301.0,207.0 299.0,231.0Q297.0,255.0 292.0,279.0Q225.0,236.0 156.0,236.0Q92.0,236.0 53.5,272.0Q15.0,308.0 15.0,369.0Q15.0,425.0 57.0,462.5Q99.0,500.0 168.0,500.0ZM93.0,368.0Q93.0,342.0 105.0,328.5Q117.0,315.0 134.0,310.0Q151.0,305.0 165.0,305.0Q197.0,305.0 223.0,318.0Q249.0,331.0 270.0,350.0Q254.0,385.0 228.0,408.0Q202.0,431.0 164.0,431.0Q133.0,431.0 113.0,414.0Q93.0,397.0 93.0,368.0Z"  transform="translate(1957, 983)"/>
<path d="M356.0,-12.0Q251.0,-12.0 179.5,24.0Q108.0,60.0 71.5,123.5Q35.0,187.0 35.0,269.0Q35.0,343.0 60.5,394.5Q86.0,446.0 129.0,473.0Q172.0,500.0 225.0,500.0Q284.0,500.0 320.5,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 201.0,235.0Q176.0,235.0 154.0,241.5Q132.0,248.0 114.0,258.0Q116.0,206.0 142.5,163.0Q169.0,120.0 221.0,93.5Q273.0,67.0 353.0,67.0Q463.0,67.0 527.0,113.0Q591.0,159.0 591.0,245.0Q591.0,303.0 558.5,349.0Q526.0,395.0 457.0,423.0L497.0,500.0Q580.0,464.0 627.0,400.0Q674.0,336.0 674.0,250.0Q674.0,176.0 641.0,116.5Q608.0,57.0 537.5,22.5Q467.0,-12.0 356.0,-12.0ZM220.0,429.0Q181.0,429.0 154.0,402.5Q127.0,376.0 118.0,329.0Q132.0,319.0 151.5,312.0Q171.0,305.0 196.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0Z"  transform="translate(2377, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3086 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M42.0,236.0Q42.0,297.0 62.5,345.0Q83.0,393.0 121.0,425.0L43.0,425.0L43.0,500.0L710.0,500.0Q775.0,500.0 811.5,492.0Q848.0,484.0 875.0,462.0Q896.0,446.0 909.0,418.5Q922.0,391.0 922.0,353.0Q922.0,290.0 884.0,255.0Q846.0,220.0 781.0,220.0Q731.0,220.0 701.0,239.0Q671.0,258.0 657.5,287.0Q644.0,316.0 644.0,344.0Q644.0,369.0 650.0,388.5Q656.0,408.0 666.0,425.0L488.0,425.0Q524.0,393.0 544.5,346.0Q565.0,299.0 565.0,237.0Q565.0,163.0 533.0,106.5Q501.0,50.0 442.0,19.0Q383.0,-12.0 303.0,-12.0Q224.0,-12.0 165.5,18.5Q107.0,49.0 74.5,105.0Q42.0,161.0 42.0,236.0ZM717.0,353.0Q717.0,323.0 734.5,304.5Q752.0,286.0 785.0,286.0Q820.0,286.0 834.5,304.5Q849.0,323.0 849.0,350.0Q849.0,392.0 823.5,408.5Q798.0,425.0 752.0,425.0L743.0,425.0Q717.0,391.0 717.0,353.0ZM125.0,248.0Q125.0,167.0 170.0,117.0Q215.0,67.0 303.0,67.0Q392.0,67.0 437.0,116.5Q482.0,166.0 482.0,242.0Q482.0,293.0 462.5,334.5Q443.0,376.0 403.5,400.5Q364.0,425.0 303.0,425.0Q242.0,425.0 202.5,400.5Q163.0,376.0 144.0,336.0Q125.0,296.0 125.0,248.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,98.5Q593.0,130.0 593.0,200.0Q593.0,260.0 571.5,317.5Q550.0,375.0 513.0,425.0L97.0,425.0L97.0,500.0L457.0,500.0Q408.0,544.0 355.0,577.0Q302.0,610.0 244.0,636.0L280.0,712.0Q355.0,680.0 431.5,626.0Q508.0,572.0 567.0,500.0L804.0,500.0Q869.0,500.0 905.5,492.0Q942.0,484.0 969.0,462.0Q990.0,446.0 1003.0,418.5Q1016.0,391.0 1016.0,353.0Q1016.0,290.0 978.0,255.0Q940.0,220.0 875.0,220.0Q825.0,220.0 795.0,239.0Q765.0,258.0 751.5,287.0Q738.0,316.0 738.0,344.0Q738.0,369.0 744.0,388.5Q750.0,408.0 760.0,425.0L613.0,425.0Q643.0,375.0 659.5,317.5Q676.0,260.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM811.0,353.0Q811.0,323.0 828.5,304.5Q846.0,286.0 879.0,286.0Q914.0,286.0 928.5,304.5Q943.0,323.0 943.0,350.0Q943.0,392.0 917.5,408.5Q892.0,425.0 846.0,425.0L837.0,425.0Q811.0,391.0 811.0,353.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0Z"  transform="translate(906, 983)"/>
<path d="M-167.0,-386.0Q-204.0,-386.0 -230.5,-373.0Q-257.0,-360.0 -280.0,-329.0Q-303.0,-363.0 -331.5,-374.5Q-360.0,-386.0 -393.0,-386.0Q-440.0,-386.0 -471.5,-364.5Q-503.0,-343.0 -519.0,-307.5Q-535.0,-272.0 -535.0,-230.0Q-535.0,-175.0 -513.0,-137.5Q-491.0,-100.0 -456.5,-80.5Q-422.0,-61.0 -384.0,-61.0Q-338.0,-61.0 -312.5,-84.5Q-287.0,-108.0 -287.0,-147.0Q-287.0,-188.0 -315.0,-214.5Q-343.0,-241.0 -399.0,-241.0Q-418.0,-241.0 -435.5,-236.5Q-453.0,-232.0 -468.0,-225.0L-468.0,-229.0Q-468.0,-251.0 -462.0,-272.5Q-456.0,-294.0 -439.0,-308.0Q-422.0,-322.0 -391.0,-322.0Q-353.0,-322.0 -335.0,-303.5Q-317.0,-285.0 -313.0,-254.0L-246.0,-254.0Q-242.0,-289.0 -222.5,-305.5Q-203.0,-322.0 -175.0,-322.0Q-140.0,-322.0 -124.0,-303.5Q-108.0,-285.0 -108.0,-251.0Q-108.0,-204.0 -141.0,-174.0Q-174.0,-144.0 -229.0,-123.0L-195.0,-61.0Q-129.0,-86.0 -83.0,-135.5Q-37.0,-185.0 -37.0,-252.0Q-37.0,-316.0 -72.0,-351.0Q-107.0,-386.0 -167.0,-386.0ZM-390.0,-119.0Q-413.0,-119.0 -432.0,-132.5Q-451.0,-146.0 -460.0,-172.0Q-450.0,-178.0 -436.0,-182.0Q-422.0,-186.0 -406.0,-186.0Q-349.0,-186.0 -349.0,-151.0Q-349.0,-119.0 -390.0,-119.0Z"  transform="translate(1533, 953)"/>
<path d="M168.0,500.0Q224.0,500.0 264.5,473.0Q305.0,446.0 331.0,401.0Q357.0,356.0 369.0,300.5Q381.0,245.0 381.0,187.0Q381.0,52.0 338.0,-59.5Q295.0,-171.0 221.0,-262.5Q147.0,-354.0 54.0,-430.0L1.0,-369.0Q56.0,-324.0 109.0,-269.5Q162.0,-215.0 205.5,-147.0Q249.0,-79.0 275.0,3.5Q301.0,86.0 301.0,186.0Q301.0,207.0 299.0,231.0Q297.0,255.0 292.0,279.0Q225.0,236.0 156.0,236.0Q92.0,236.0 53.5,272.0Q15.0,308.0 15.0,369.0Q15.0,425.0 57.0,462.5Q99.0,500.0 168.0,500.0ZM93.0,368.0Q93.0,342.0 105.0,328.5Q117.0,315.0 134.0,310.0Q151.0,305.0 165.0,305.0Q197.0,305.0 223.0,318.0Q249.0,331.0 270.0,350.0Q254.0,385.0 228.0,408.0Q202.0,431.0 164.0,431.0Q133.0,431.0 113.0,414.0Q93.0,397.0 93.0,368.0Z"  transform="translate(1957, 983)"/>
<path d="M356.0,-12.0Q251.0,-12.0 179.5,24.0Q108.0,60.0 71.5,123.5Q35.0,187.0 35.0,269.0Q35.0,343.0 60.5,394.5Q86.0,446.0 129.0,473.0Q172.0,500.0 225.0,500.0Q284.0,500.0 320.5,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 201.0,235.0Q176.0,235.0 154.0,241.5Q132.0,248.0 114.0,258.0Q116.0,206.0 142.5,163.0Q169.0,120.0 221.0,93.5Q273.0,67.0 353.0,67.0Q463.0,67.0 527.0,113.0Q591.0,159.0 591.0,245.0Q591.0,303.0 558.5,349.0Q526.0,395.0 457.0,423.0L497.0,500.0Q580.0,464.0 627.0,400.0Q674.0,336.0 674.0,250.0Q674.0,176.0 641.0,116.5Q608.0,57.0 537.5,22.5Q467.0,-12.0 356.0,-12.0ZM220.0,429.0Q181.0,429.0 154.0,402.5Q127.0,376.0 118.0,329.0Q132.0,319.0 151.5,312.0Q171.0,305.0 196.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0Z"  transform="translate(2377, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(ఎథ్నోలాగ్)</span> (fontdiff-Telugu.html)</li>


<pre>Expected: parenleft.telu=0+362|etelu=1+711|thoovoweltelu=2+904|nasubscripttelu=2+346|laavoweltelu=6+1047|gahalanttelu=8+583|parenright.telu=10+362</pre>



<pre>Got     : parenleft.telu=0+362|etelu=1+711|thoovoweltelu=2+869|nasubscripttelu=2+346|laavoweltelu=6+1047|gahalanttelu=8+583|parenright.telu=10+362</pre>



<pre>                                                            ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4280 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.0Q593.0,131.0 593.0,200.0Q593.0,270.0 565.0,335.0Q537.0,400.0 488.0,456.0Q439.0,512.0 375.5,557.0Q312.0,602.0 242.0,632.0L280.0,712.0Q349.0,683.0 419.0,634.5Q489.0,586.0 547.0,520.5Q605.0,455.0 640.5,374.0Q676.0,293.0 676.0,198.0Q676.0,99.0 626.0,43.5Q576.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0Z"  transform="translate(362, 983)"/>
<path d="M504.0,-12.0Q452.0,-12.0 416.5,7.5Q381.0,27.0 352.0,74.0Q321.0,20.0 282.0,4.0Q243.0,-12.0 198.0,-12.0Q125.0,-12.0 80.0,44.0Q35.0,100.0 35.0,200.0Q35.0,289.0 74.0,356.5Q113.0,424.0 185.0,462.0Q257.0,500.0 357.0,500.0Q457.0,500.0 527.0,461.5Q597.0,423.0 634.0,355.5Q671.0,288.0 671.0,200.0Q671.0,97.0 626.0,42.5Q581.0,-12.0 504.0,-12.0ZM496.0,67.0Q538.0,67.0 563.0,98.0Q588.0,129.0 588.0,202.0Q588.0,267.0 563.5,317.0Q539.0,367.0 489.5,396.0Q440.0,425.0 364.0,425.0L349.0,425.0Q237.0,425.0 177.5,364.0Q118.0,303.0 118.0,205.0Q118.0,130.0 142.5,98.5Q167.0,67.0 210.0,67.0Q255.0,67.0 279.5,95.5Q304.0,124.0 314.0,169.0L392.0,169.0Q401.0,118.0 430.0,92.5Q459.0,67.0 496.0,67.0ZM300.0,268.0Q300.0,300.0 315.0,313.0Q330.0,326.0 354.0,326.0Q376.0,326.0 391.5,313.0Q407.0,300.0 407.0,268.0Q407.0,236.0 391.5,222.0Q376.0,208.0 354.0,208.0Q330.0,208.0 315.0,222.0Q300.0,236.0 300.0,268.0ZM308.0,-125.0L315.0,16.0L390.0,16.0L398.0,-125.0L308.0,-125.0ZM749.0,420.0Q699.0,420.0 669.0,439.0Q639.0,458.0 625.5,486.5Q612.0,515.0 612.0,544.0Q612.0,569.0 618.0,588.5Q624.0,608.0 634.0,625.0L595.0,625.0Q546.0,625.0 523.0,599.0Q500.0,573.0 494.0,532.0L416.0,532.0Q409.0,578.0 382.0,601.5Q355.0,625.0 323.0,625.0L307.0,625.0Q269.0,625.0 250.0,607.5Q231.0,590.0 231.0,564.0Q231.0,535.0 249.0,517.5Q267.0,500.0 313.0,500.0L342.0,500.0L342.0,425.0L311.0,425.0Q238.0,425.0 193.5,462.0Q149.0,499.0 149.0,567.0Q149.0,626.0 191.5,663.0Q234.0,700.0 304.0,700.0L312.0,700.0Q358.0,700.0 393.5,684.5Q429.0,669.0 454.0,623.0Q475.0,661.0 509.0,680.5Q543.0,700.0 604.0,700.0L640.0,700.0Q635.0,717.0 635.0,737.0Q635.0,790.0 675.0,820.0Q715.0,850.0 776.0,850.0Q837.0,850.0 871.5,824.5Q906.0,799.0 923.0,754.0L847.0,734.0Q839.0,757.0 822.5,770.5Q806.0,784.0 777.0,784.0Q750.0,784.0 730.0,770.0Q710.0,756.0 710.0,729.0Q710.0,722.0 712.0,714.5Q714.0,707.0 719.0,699.0Q765.0,697.0 793.0,688.5Q821.0,680.0 843.0,662.0Q864.0,646.0 877.0,618.5Q890.0,591.0 890.0,553.0Q890.0,490.0 852.0,455.0Q814.0,420.0 749.0,420.0ZM685.0,553.0Q685.0,523.0 702.5,504.5Q720.0,486.0 753.0,486.0Q788.0,486.0 802.5,504.5Q817.0,523.0 817.0,550.0Q817.0,592.0 791.5,608.5Q766.0,625.0 720.0,625.0L711.0,625.0Q685.0,591.0 685.0,553.0Z"  transform="translate(1073, 983)"/>
<path d="M329.0,-337.0Q295.0,-337.0 267.5,-322.5Q240.0,-308.0 202.0,-271.0Q164.0,-303.0 114.5,-320.0Q65.0,-337.0 6.0,-337.0Q-76.0,-337.0 -127.0,-296.0Q-178.0,-255.0 -178.0,-182.0Q-178.0,-123.0 -137.0,-80.0Q-96.0,-37.0 -18.0,-37.0Q24.0,-37.0 57.0,-51.0Q90.0,-65.0 123.5,-94.0Q157.0,-123.0 198.0,-167.0Q219.0,-134.0 230.0,-90.5Q241.0,-47.0 241.0,7.0Q241.0,135.0 180.5,241.0Q120.0,347.0 -18.0,430.0L22.0,500.0Q167.0,414.0 243.5,286.0Q320.0,158.0 320.0,10.0Q320.0,-58.0 303.0,-116.0Q286.0,-174.0 250.0,-221.0Q277.0,-245.0 295.5,-255.5Q314.0,-266.0 330.0,-266.0Q350.0,-266.0 364.5,-257.5Q379.0,-249.0 395.0,-230.0L442.0,-282.0Q416.0,-310.0 390.0,-323.5Q364.0,-337.0 329.0,-337.0ZM-99.0,-182.0Q-99.0,-224.0 -69.5,-245.0Q-40.0,-266.0 10.0,-266.0Q94.0,-266.0 152.0,-220.0Q110.0,-176.0 83.0,-152.0Q56.0,-128.0 33.5,-118.0Q11.0,-108.0 -18.0,-108.0Q-51.0,-108.0 -75.0,-127.0Q-99.0,-146.0 -99.0,-182.0Z"  transform="translate(1942, 983)"/>
<path d="M356.0,-12.0Q251.0,-12.0 179.5,24.0Q108.0,60.0 71.5,123.5Q35.0,187.0 35.0,269.0Q35.0,343.0 60.5,394.5Q86.0,446.0 129.0,473.0Q172.0,500.0 225.0,500.0Q284.0,500.0 320.5,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 201.0,235.0Q176.0,235.0 154.0,241.5Q132.0,248.0 114.0,258.0Q116.0,206.0 142.5,163.0Q169.0,120.0 221.0,93.5Q273.0,67.0 353.0,67.0Q423.0,67.0 476.5,86.5Q530.0,106.0 560.5,146.5Q591.0,187.0 591.0,249.0Q591.0,310.0 558.0,356.0Q525.0,402.0 475.0,425.0L396.0,425.0L396.0,500.0L820.0,500.0Q885.0,500.0 921.5,492.0Q958.0,484.0 985.0,462.0Q1006.0,446.0 1019.0,418.5Q1032.0,391.0 1032.0,353.0Q1032.0,290.0 994.0,255.0Q956.0,220.0 891.0,220.0Q841.0,220.0 811.0,239.0Q781.0,258.0 767.5,287.0Q754.0,316.0 754.0,344.0Q754.0,369.0 760.0,388.5Q766.0,408.0 776.0,425.0L602.0,425.0Q638.0,391.0 656.0,346.0Q674.0,301.0 674.0,250.0Q674.0,177.0 642.0,117.5Q610.0,58.0 540.0,23.0Q470.0,-12.0 356.0,-12.0ZM220.0,429.0Q181.0,429.0 154.0,402.5Q127.0,376.0 118.0,329.0Q132.0,319.0 151.5,312.0Q171.0,305.0 196.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0ZM827.0,353.0Q827.0,323.0 844.5,304.5Q862.0,286.0 895.0,286.0Q930.0,286.0 944.5,304.5Q959.0,323.0 959.0,350.0Q959.0,392.0 933.5,408.5Q908.0,425.0 862.0,425.0L853.0,425.0Q827.0,391.0 827.0,353.0Z"  transform="translate(2288, 983)"/>
<path d="M294.0,500.0Q411.0,500.0 477.0,435.0Q543.0,370.0 543.0,255.0Q543.0,192.0 531.0,144.0Q519.0,96.0 501.5,59.0Q484.0,22.0 465.0,-8.0L382.0,29.0Q401.0,57.0 419.0,87.0Q437.0,117.0 448.5,155.5Q460.0,194.0 460.0,245.0Q460.0,294.0 444.0,335.0Q428.0,376.0 390.5,400.5Q353.0,425.0 289.0,425.0Q213.0,425.0 168.0,378.0Q123.0,331.0 123.0,246.0Q123.0,178.0 145.0,126.5Q167.0,75.0 201.0,29.0L118.0,-8.0Q84.0,44.0 62.0,108.0Q40.0,172.0 40.0,245.0Q40.0,314.0 68.5,372.0Q97.0,430.0 153.5,465.0Q210.0,500.0 294.0,500.0ZM117.0,540.0Q117.0,592.0 165.0,627.0Q109.0,664.0 109.0,724.0Q109.0,751.0 119.0,771.0Q129.0,791.0 147.0,805.0Q168.0,822.0 201.5,830.0Q235.0,838.0 304.0,838.0L591.0,838.0L591.0,763.0L288.0,763.0Q254.0,763.0 239.0,761.0Q224.0,759.0 215.0,754.0Q192.0,743.0 192.0,717.0Q192.0,689.0 213.0,678.0Q223.0,673.0 239.5,670.5Q256.0,668.0 287.0,668.0L424.0,668.0L424.0,593.0L283.0,593.0Q255.0,593.0 239.5,589.5Q224.0,586.0 216.0,580.0Q200.0,568.0 200.0,546.0Q200.0,522.0 216.0,511.0Q225.0,504.0 239.0,502.0Q253.0,500.0 275.0,500.0L312.0,500.0L312.0,425.0L274.0,425.0Q203.0,425.0 160.0,452.5Q117.0,480.0 117.0,540.0Z"  transform="translate(3335, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(3918, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4315 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M50.0,211.0Q50.0,368.0 95.5,511.5Q141.0,655.0 233.0,773.0L318.0,773.0Q227.0,640.0 183.0,500.5Q139.0,361.0 139.0,210.0Q139.0,56.0 182.0,-84.0Q225.0,-224.0 319.0,-361.0L233.0,-361.0Q140.0,-243.0 95.0,-95.5Q50.0,52.0 50.0,211.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.0Q593.0,131.0 593.0,200.0Q593.0,270.0 565.0,335.0Q537.0,400.0 488.0,456.0Q439.0,512.0 375.5,557.0Q312.0,602.0 242.0,632.0L280.0,712.0Q349.0,683.0 419.0,634.5Q489.0,586.0 547.0,520.5Q605.0,455.0 640.5,374.0Q676.0,293.0 676.0,198.0Q676.0,99.0 626.0,43.5Q576.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0Z"  transform="translate(362, 983)"/>
<path d="M504.0,-12.0Q452.0,-12.0 416.5,7.5Q381.0,27.0 352.0,74.0Q321.0,20.0 282.0,4.0Q243.0,-12.0 198.0,-12.0Q125.0,-12.0 80.0,44.0Q35.0,100.0 35.0,200.0Q35.0,289.0 74.0,356.5Q113.0,424.0 185.0,462.0Q257.0,500.0 357.0,500.0Q457.0,500.0 527.0,461.5Q597.0,423.0 634.0,355.5Q671.0,288.0 671.0,200.0Q671.0,97.0 626.0,42.5Q581.0,-12.0 504.0,-12.0ZM496.0,67.0Q538.0,67.0 563.0,98.0Q588.0,129.0 588.0,202.0Q588.0,267.0 563.5,317.0Q539.0,367.0 489.5,396.0Q440.0,425.0 364.0,425.0L349.0,425.0Q237.0,425.0 177.5,364.0Q118.0,303.0 118.0,205.0Q118.0,130.0 142.5,98.5Q167.0,67.0 210.0,67.0Q255.0,67.0 279.5,95.5Q304.0,124.0 314.0,169.0L392.0,169.0Q401.0,118.0 430.0,92.5Q459.0,67.0 496.0,67.0ZM300.0,268.0Q300.0,300.0 315.0,313.0Q330.0,326.0 354.0,326.0Q376.0,326.0 391.5,313.0Q407.0,300.0 407.0,268.0Q407.0,236.0 391.5,222.0Q376.0,208.0 354.0,208.0Q330.0,208.0 315.0,222.0Q300.0,236.0 300.0,268.0ZM308.0,-125.0L315.0,16.0L390.0,16.0L398.0,-125.0L308.0,-125.0ZM749.0,420.0Q699.0,420.0 669.0,439.0Q639.0,458.0 625.5,486.5Q612.0,515.0 612.0,544.0Q612.0,569.0 618.0,588.5Q624.0,608.0 634.0,625.0L595.0,625.0Q546.0,625.0 523.0,599.0Q500.0,573.0 494.0,532.0L416.0,532.0Q409.0,578.0 382.0,601.5Q355.0,625.0 323.0,625.0L307.0,625.0Q269.0,625.0 250.0,607.5Q231.0,590.0 231.0,564.0Q231.0,535.0 249.0,517.5Q267.0,500.0 313.0,500.0L342.0,500.0L342.0,425.0L311.0,425.0Q238.0,425.0 193.5,462.0Q149.0,499.0 149.0,567.0Q149.0,626.0 191.5,663.0Q234.0,700.0 304.0,700.0L312.0,700.0Q358.0,700.0 393.5,684.5Q429.0,669.0 454.0,623.0Q475.0,661.0 509.0,680.5Q543.0,700.0 604.0,700.0L640.0,700.0Q635.0,717.0 635.0,737.0Q635.0,790.0 675.0,820.0Q715.0,850.0 776.0,850.0Q837.0,850.0 871.5,824.5Q906.0,799.0 923.0,754.0L847.0,734.0Q839.0,757.0 822.5,770.5Q806.0,784.0 777.0,784.0Q750.0,784.0 730.0,770.0Q710.0,756.0 710.0,729.0Q710.0,722.0 712.0,714.5Q714.0,707.0 719.0,699.0Q765.0,697.0 793.0,688.5Q821.0,680.0 843.0,662.0Q864.0,646.0 877.0,618.5Q890.0,591.0 890.0,553.0Q890.0,490.0 852.0,455.0Q814.0,420.0 749.0,420.0ZM685.0,553.0Q685.0,523.0 702.5,504.5Q720.0,486.0 753.0,486.0Q788.0,486.0 802.5,504.5Q817.0,523.0 817.0,550.0Q817.0,592.0 791.5,608.5Q766.0,625.0 720.0,625.0L711.0,625.0Q685.0,591.0 685.0,553.0Z"  transform="translate(1073, 983)"/>
<path d="M329.0,-337.0Q295.0,-337.0 267.5,-322.5Q240.0,-308.0 202.0,-271.0Q164.0,-303.0 114.5,-320.0Q65.0,-337.0 6.0,-337.0Q-76.0,-337.0 -127.0,-296.0Q-178.0,-255.0 -178.0,-182.0Q-178.0,-123.0 -137.0,-80.0Q-96.0,-37.0 -18.0,-37.0Q24.0,-37.0 57.0,-51.0Q90.0,-65.0 123.5,-94.0Q157.0,-123.0 198.0,-167.0Q219.0,-134.0 230.0,-90.5Q241.0,-47.0 241.0,7.0Q241.0,135.0 180.5,241.0Q120.0,347.0 -18.0,430.0L22.0,500.0Q167.0,414.0 243.5,286.0Q320.0,158.0 320.0,10.0Q320.0,-58.0 303.0,-116.0Q286.0,-174.0 250.0,-221.0Q277.0,-245.0 295.5,-255.5Q314.0,-266.0 330.0,-266.0Q350.0,-266.0 364.5,-257.5Q379.0,-249.0 395.0,-230.0L442.0,-282.0Q416.0,-310.0 390.0,-323.5Q364.0,-337.0 329.0,-337.0ZM-99.0,-182.0Q-99.0,-224.0 -69.5,-245.0Q-40.0,-266.0 10.0,-266.0Q94.0,-266.0 152.0,-220.0Q110.0,-176.0 83.0,-152.0Q56.0,-128.0 33.5,-118.0Q11.0,-108.0 -18.0,-108.0Q-51.0,-108.0 -75.0,-127.0Q-99.0,-146.0 -99.0,-182.0Z"  transform="translate(1977, 983)"/>
<path d="M356.0,-12.0Q251.0,-12.0 179.5,24.0Q108.0,60.0 71.5,123.5Q35.0,187.0 35.0,269.0Q35.0,343.0 60.5,394.5Q86.0,446.0 129.0,473.0Q172.0,500.0 225.0,500.0Q284.0,500.0 320.5,466.0Q357.0,432.0 357.0,373.0Q357.0,312.0 319.0,273.5Q281.0,235.0 201.0,235.0Q176.0,235.0 154.0,241.5Q132.0,248.0 114.0,258.0Q116.0,206.0 142.5,163.0Q169.0,120.0 221.0,93.5Q273.0,67.0 353.0,67.0Q423.0,67.0 476.5,86.5Q530.0,106.0 560.5,146.5Q591.0,187.0 591.0,249.0Q591.0,310.0 558.0,356.0Q525.0,402.0 475.0,425.0L396.0,425.0L396.0,500.0L820.0,500.0Q885.0,500.0 921.5,492.0Q958.0,484.0 985.0,462.0Q1006.0,446.0 1019.0,418.5Q1032.0,391.0 1032.0,353.0Q1032.0,290.0 994.0,255.0Q956.0,220.0 891.0,220.0Q841.0,220.0 811.0,239.0Q781.0,258.0 767.5,287.0Q754.0,316.0 754.0,344.0Q754.0,369.0 760.0,388.5Q766.0,408.0 776.0,425.0L602.0,425.0Q638.0,391.0 656.0,346.0Q674.0,301.0 674.0,250.0Q674.0,177.0 642.0,117.5Q610.0,58.0 540.0,23.0Q470.0,-12.0 356.0,-12.0ZM220.0,429.0Q181.0,429.0 154.0,402.5Q127.0,376.0 118.0,329.0Q132.0,319.0 151.5,312.0Q171.0,305.0 196.0,305.0Q237.0,305.0 257.5,322.0Q278.0,339.0 278.0,369.0Q278.0,398.0 262.0,413.5Q246.0,429.0 220.0,429.0ZM827.0,353.0Q827.0,323.0 844.5,304.5Q862.0,286.0 895.0,286.0Q930.0,286.0 944.5,304.5Q959.0,323.0 959.0,350.0Q959.0,392.0 933.5,408.5Q908.0,425.0 862.0,425.0L853.0,425.0Q827.0,391.0 827.0,353.0Z"  transform="translate(2323, 983)"/>
<path d="M294.0,500.0Q411.0,500.0 477.0,435.0Q543.0,370.0 543.0,255.0Q543.0,192.0 531.0,144.0Q519.0,96.0 501.5,59.0Q484.0,22.0 465.0,-8.0L382.0,29.0Q401.0,57.0 419.0,87.0Q437.0,117.0 448.5,155.5Q460.0,194.0 460.0,245.0Q460.0,294.0 444.0,335.0Q428.0,376.0 390.5,400.5Q353.0,425.0 289.0,425.0Q213.0,425.0 168.0,378.0Q123.0,331.0 123.0,246.0Q123.0,178.0 145.0,126.5Q167.0,75.0 201.0,29.0L118.0,-8.0Q84.0,44.0 62.0,108.0Q40.0,172.0 40.0,245.0Q40.0,314.0 68.5,372.0Q97.0,430.0 153.5,465.0Q210.0,500.0 294.0,500.0ZM117.0,540.0Q117.0,592.0 165.0,627.0Q109.0,664.0 109.0,724.0Q109.0,751.0 119.0,771.0Q129.0,791.0 147.0,805.0Q168.0,822.0 201.5,830.0Q235.0,838.0 304.0,838.0L591.0,838.0L591.0,763.0L288.0,763.0Q254.0,763.0 239.0,761.0Q224.0,759.0 215.0,754.0Q192.0,743.0 192.0,717.0Q192.0,689.0 213.0,678.0Q223.0,673.0 239.5,670.5Q256.0,668.0 287.0,668.0L424.0,668.0L424.0,593.0L283.0,593.0Q255.0,593.0 239.5,589.5Q224.0,586.0 216.0,580.0Q200.0,568.0 200.0,546.0Q200.0,522.0 216.0,511.0Q225.0,504.0 239.0,502.0Q253.0,500.0 275.0,500.0L312.0,500.0L312.0,425.0L274.0,425.0Q203.0,425.0 160.0,452.5Q117.0,480.0 117.0,540.0Z"  transform="translate(3370, 983)"/>
<path d="M312.0,201.0Q312.0,44.0 266.0,-99.5Q220.0,-243.0 128.0,-361.0L44.0,-361.0Q136.0,-226.0 179.5,-87.5Q223.0,51.0 223.0,202.0Q223.0,357.0 180.5,495.5Q138.0,634.0 43.0,773.0L128.0,773.0Q221.0,655.0 266.5,507.5Q312.0,360.0 312.0,201.0Z"  transform="translate(3953, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">జన్యు</span> (fontdiff-Telugu.html)</li>


<pre>Expected: jatelu=0+731|natelu=1+702|uvowelsigntelu=1+335|yasubscripttelu=1+458</pre>



<pre>Got     : jatelu=0+731|natelu=1+691|uvowelsigntelu=1+335|yasubscripttelu=1+458</pre>



<pre>                                ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2215 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M530.0,-12.0Q477.0,-12.0 440.0,8.0Q403.0,28.0 375.0,74.0Q338.0,22.0 298.5,5.0Q259.0,-12.0 205.0,-12.0Q150.0,-12.0 113.5,7.5Q77.0,27.0 59.0,59.5Q41.0,92.0 41.0,130.0Q41.0,191.0 78.5,227.0Q116.0,263.0 189.0,289.0Q230.0,304.0 254.0,321.0Q278.0,338.0 278.0,371.0Q278.0,394.0 261.5,410.5Q245.0,427.0 203.0,427.0Q160.0,427.0 139.0,410.5Q118.0,394.0 118.0,365.0Q118.0,352.0 121.5,341.0Q125.0,330.0 128.0,323.0L53.0,302.0Q36.0,333.0 36.0,375.0Q36.0,407.0 53.0,435.5Q70.0,464.0 107.0,482.0Q144.0,500.0 203.0,500.0Q257.0,500.0 290.5,483.0Q324.0,466.0 340.0,439.5Q356.0,413.0 359.0,385.0Q390.0,356.0 432.5,341.5Q475.0,327.0 514.0,327.0Q592.0,327.0 592.0,376.0Q592.0,404.0 571.0,414.5Q550.0,425.0 521.0,425.0Q503.0,425.0 488.0,423.0Q473.0,421.0 460.0,419.0L450.0,491.0Q462.0,494.0 482.0,497.0Q502.0,500.0 529.0,500.0Q565.0,500.0 598.0,489.0Q631.0,478.0 652.0,451.0Q673.0,424.0 673.0,377.0Q673.0,324.0 631.5,288.0Q590.0,252.0 512.0,252.0Q458.0,252.0 416.0,267.5Q374.0,283.0 345.0,306.0Q330.0,279.0 300.5,260.0Q271.0,241.0 227.0,225.0Q174.0,205.0 148.5,184.5Q123.0,164.0 123.0,131.0Q123.0,102.0 143.5,84.5Q164.0,67.0 207.0,67.0Q269.0,67.0 300.5,99.5Q332.0,132.0 336.0,185.0L414.0,185.0Q418.0,124.0 450.0,95.5Q482.0,67.0 527.0,67.0Q574.0,67.0 596.0,87.0Q618.0,107.0 618.0,142.0Q618.0,165.0 611.0,184.0Q604.0,203.0 593.0,221.0L667.0,252.0Q682.0,230.0 691.5,198.5Q701.0,167.0 701.0,135.0Q701.0,66.0 656.5,27.0Q612.0,-12.0 530.0,-12.0Z"  transform="translate(0, 983)"/>
<path d="M472.0,-12.0Q425.0,-12.0 390.0,3.5Q355.0,19.0 324.0,51.5Q293.0,84.0 256.0,133.0Q224.0,176.0 206.5,192.5Q189.0,209.0 164.0,209.0Q141.0,209.0 126.0,190.5Q111.0,172.0 111.0,143.0Q111.0,108.0 123.0,77.0Q135.0,46.0 159.0,14.0L78.0,-13.0Q56.0,22.0 42.5,59.5Q29.0,97.0 29.0,143.0Q29.0,204.0 67.0,245.0Q105.0,286.0 165.0,286.0Q204.0,286.0 230.5,272.5Q257.0,259.0 279.5,234.5Q302.0,210.0 328.0,175.0Q358.0,136.0 380.5,112.0Q403.0,88.0 425.5,77.5Q448.0,67.0 478.0,67.0Q530.0,67.0 557.0,100.0Q584.0,133.0 584.0,194.0Q584.0,269.0 544.0,320.5Q504.0,372.0 435.5,398.5Q367.0,425.0 282.0,425.0L238.0,425.0L238.0,425.0L236.0,425.0Q207.0,425.0 180.5,436.0Q154.0,447.0 132.0,477.5Q110.0,508.0 94.0,564.0L177.0,591.0Q192.0,536.0 206.0,518.0Q220.0,500.0 242.0,500.0Q262.0,500.0 279.5,512.5Q297.0,525.0 329.0,565.0L360.0,605.0Q394.0,649.0 422.5,675.0Q451.0,701.0 483.0,713.0Q515.0,725.0 559.0,725.0L565.0,648.0Q530.0,646.0 506.5,637.0Q483.0,628.0 463.5,608.5Q444.0,589.0 418.0,556.0L395.0,526.0Q381.0,508.0 369.0,494.0Q464.0,480.0 530.5,438.5Q597.0,397.0 632.0,334.5Q667.0,272.0 667.0,194.0Q667.0,101.0 618.0,44.5Q569.0,-12.0 472.0,-12.0Z"  transform="translate(731, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(1422, 983)"/>
<path d="M174.0,-386.0Q103.0,-386.0 58.5,-368.5Q14.0,-351.0 -6.5,-322.5Q-27.0,-294.0 -27.0,-260.0Q-27.0,-223.0 -5.5,-194.5Q16.0,-166.0 82.0,-138.0Q123.0,-121.0 140.5,-108.5Q158.0,-96.0 158.0,-73.0Q158.0,-57.0 146.0,-44.0Q134.0,-31.0 99.0,-31.0Q40.0,-31.0 40.0,-72.0Q40.0,-89.0 47.0,-105.0L-23.0,-121.0Q-38.0,-89.0 -38.0,-61.0Q-38.0,-23.0 -6.0,7.0Q26.0,37.0 100.0,37.0Q150.0,37.0 179.5,20.0Q209.0,3.0 222.0,-22.0Q235.0,-47.0 235.0,-72.0Q235.0,-120.0 205.0,-146.0Q175.0,-172.0 122.0,-194.0Q77.0,-213.0 64.0,-225.5Q51.0,-238.0 51.0,-257.0Q51.0,-283.0 82.0,-298.5Q113.0,-314.0 174.0,-314.0Q229.0,-314.0 275.0,-299.0Q321.0,-284.0 349.0,-250.0Q377.0,-216.0 377.0,-159.0Q377.0,-119.0 362.0,-82.5Q347.0,-46.0 306.0,-3.0Q265.0,40.0 187.0,101.0Q111.0,160.0 70.5,213.0Q30.0,266.0 30.0,333.0Q30.0,379.0 53.0,417.0Q76.0,455.0 119.0,477.5Q162.0,500.0 222.0,500.0Q290.0,500.0 332.0,476.0Q374.0,452.0 393.5,414.0Q413.0,376.0 413.0,333.0Q413.0,295.0 400.5,263.5Q388.0,232.0 368.0,206.0L305.0,245.0Q318.0,262.0 325.5,281.5Q333.0,301.0 333.0,327.0Q333.0,368.0 306.0,398.0Q279.0,428.0 220.0,428.0Q168.0,428.0 138.5,401.5Q109.0,375.0 109.0,333.0Q109.0,283.0 155.0,238.0Q201.0,193.0 268.0,141.0Q333.0,91.0 375.0,45.0Q417.0,-1.0 437.5,-50.0Q458.0,-99.0 458.0,-158.0Q458.0,-233.0 422.5,-284.0Q387.0,-335.0 323.5,-360.5Q260.0,-386.0 174.0,-386.0Z"  transform="translate(1757, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2226 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M530.0,-12.0Q477.0,-12.0 440.0,8.0Q403.0,28.0 375.0,74.0Q338.0,22.0 298.5,5.0Q259.0,-12.0 205.0,-12.0Q150.0,-12.0 113.5,7.5Q77.0,27.0 59.0,59.5Q41.0,92.0 41.0,130.0Q41.0,191.0 78.5,227.0Q116.0,263.0 189.0,289.0Q230.0,304.0 254.0,321.0Q278.0,338.0 278.0,371.0Q278.0,394.0 261.5,410.5Q245.0,427.0 203.0,427.0Q160.0,427.0 139.0,410.5Q118.0,394.0 118.0,365.0Q118.0,352.0 121.5,341.0Q125.0,330.0 128.0,323.0L53.0,302.0Q36.0,333.0 36.0,375.0Q36.0,407.0 53.0,435.5Q70.0,464.0 107.0,482.0Q144.0,500.0 203.0,500.0Q257.0,500.0 290.5,483.0Q324.0,466.0 340.0,439.5Q356.0,413.0 359.0,385.0Q390.0,356.0 432.5,341.5Q475.0,327.0 514.0,327.0Q592.0,327.0 592.0,376.0Q592.0,404.0 571.0,414.5Q550.0,425.0 521.0,425.0Q503.0,425.0 488.0,423.0Q473.0,421.0 460.0,419.0L450.0,491.0Q462.0,494.0 482.0,497.0Q502.0,500.0 529.0,500.0Q565.0,500.0 598.0,489.0Q631.0,478.0 652.0,451.0Q673.0,424.0 673.0,377.0Q673.0,324.0 631.5,288.0Q590.0,252.0 512.0,252.0Q458.0,252.0 416.0,267.5Q374.0,283.0 345.0,306.0Q330.0,279.0 300.5,260.0Q271.0,241.0 227.0,225.0Q174.0,205.0 148.5,184.5Q123.0,164.0 123.0,131.0Q123.0,102.0 143.5,84.5Q164.0,67.0 207.0,67.0Q269.0,67.0 300.5,99.5Q332.0,132.0 336.0,185.0L414.0,185.0Q418.0,124.0 450.0,95.5Q482.0,67.0 527.0,67.0Q574.0,67.0 596.0,87.0Q618.0,107.0 618.0,142.0Q618.0,165.0 611.0,184.0Q604.0,203.0 593.0,221.0L667.0,252.0Q682.0,230.0 691.5,198.5Q701.0,167.0 701.0,135.0Q701.0,66.0 656.5,27.0Q612.0,-12.0 530.0,-12.0Z"  transform="translate(0, 983)"/>
<path d="M472.0,-12.0Q425.0,-12.0 390.0,3.5Q355.0,19.0 324.0,51.5Q293.0,84.0 256.0,133.0Q224.0,176.0 206.5,192.5Q189.0,209.0 164.0,209.0Q141.0,209.0 126.0,190.5Q111.0,172.0 111.0,143.0Q111.0,108.0 123.0,77.0Q135.0,46.0 159.0,14.0L78.0,-13.0Q56.0,22.0 42.5,59.5Q29.0,97.0 29.0,143.0Q29.0,204.0 67.0,245.0Q105.0,286.0 165.0,286.0Q204.0,286.0 230.5,272.5Q257.0,259.0 279.5,234.5Q302.0,210.0 328.0,175.0Q358.0,136.0 380.5,112.0Q403.0,88.0 425.5,77.5Q448.0,67.0 478.0,67.0Q530.0,67.0 557.0,100.0Q584.0,133.0 584.0,194.0Q584.0,269.0 544.0,320.5Q504.0,372.0 435.5,398.5Q367.0,425.0 282.0,425.0L238.0,425.0L238.0,425.0L236.0,425.0Q207.0,425.0 180.5,436.0Q154.0,447.0 132.0,477.5Q110.0,508.0 94.0,564.0L177.0,591.0Q192.0,536.0 206.0,518.0Q220.0,500.0 242.0,500.0Q262.0,500.0 279.5,512.5Q297.0,525.0 329.0,565.0L360.0,605.0Q394.0,649.0 422.5,675.0Q451.0,701.0 483.0,713.0Q515.0,725.0 559.0,725.0L565.0,648.0Q530.0,646.0 506.5,637.0Q483.0,628.0 463.5,608.5Q444.0,589.0 418.0,556.0L395.0,526.0Q381.0,508.0 369.0,494.0Q464.0,480.0 530.5,438.5Q597.0,397.0 632.0,334.5Q667.0,272.0 667.0,194.0Q667.0,101.0 618.0,44.5Q569.0,-12.0 472.0,-12.0Z"  transform="translate(731, 983)"/>
<path d="M116.0,-12.0Q49.0,-12.0 -1.5,22.0Q-52.0,56.0 -91.0,111.0L-51.0,176.0Q-9.0,121.0 32.5,94.0Q74.0,67.0 123.0,67.0Q174.0,67.0 201.0,99.5Q228.0,132.0 228.0,193.0Q228.0,251.0 204.5,294.5Q181.0,338.0 141.5,369.5Q102.0,401.0 52.0,423.0L89.0,500.0Q151.0,474.0 201.0,430.0Q251.0,386.0 281.0,328.0Q311.0,270.0 311.0,199.0Q311.0,100.0 261.0,44.0Q211.0,-12.0 116.0,-12.0Z"  transform="translate(1433, 983)"/>
<path d="M174.0,-386.0Q103.0,-386.0 58.5,-368.5Q14.0,-351.0 -6.5,-322.5Q-27.0,-294.0 -27.0,-260.0Q-27.0,-223.0 -5.5,-194.5Q16.0,-166.0 82.0,-138.0Q123.0,-121.0 140.5,-108.5Q158.0,-96.0 158.0,-73.0Q158.0,-57.0 146.0,-44.0Q134.0,-31.0 99.0,-31.0Q40.0,-31.0 40.0,-72.0Q40.0,-89.0 47.0,-105.0L-23.0,-121.0Q-38.0,-89.0 -38.0,-61.0Q-38.0,-23.0 -6.0,7.0Q26.0,37.0 100.0,37.0Q150.0,37.0 179.5,20.0Q209.0,3.0 222.0,-22.0Q235.0,-47.0 235.0,-72.0Q235.0,-120.0 205.0,-146.0Q175.0,-172.0 122.0,-194.0Q77.0,-213.0 64.0,-225.5Q51.0,-238.0 51.0,-257.0Q51.0,-283.0 82.0,-298.5Q113.0,-314.0 174.0,-314.0Q229.0,-314.0 275.0,-299.0Q321.0,-284.0 349.0,-250.0Q377.0,-216.0 377.0,-159.0Q377.0,-119.0 362.0,-82.5Q347.0,-46.0 306.0,-3.0Q265.0,40.0 187.0,101.0Q111.0,160.0 70.5,213.0Q30.0,266.0 30.0,333.0Q30.0,379.0 53.0,417.0Q76.0,455.0 119.0,477.5Q162.0,500.0 222.0,500.0Q290.0,500.0 332.0,476.0Q374.0,452.0 393.5,414.0Q413.0,376.0 413.0,333.0Q413.0,295.0 400.5,263.5Q388.0,232.0 368.0,206.0L305.0,245.0Q318.0,262.0 325.5,281.5Q333.0,301.0 333.0,327.0Q333.0,368.0 306.0,398.0Q279.0,428.0 220.0,428.0Q168.0,428.0 138.5,401.5Q109.0,375.0 109.0,333.0Q109.0,283.0 155.0,238.0Q201.0,193.0 268.0,141.0Q333.0,91.0 375.0,45.0Q417.0,-1.0 437.5,-50.0Q458.0,-99.0 458.0,-158.0Q458.0,-233.0 422.5,-284.0Q387.0,-335.0 323.5,-360.5Q260.0,-386.0 174.0,-386.0Z"  transform="translate(1768, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ఇష్టమైన</span> (fontdiff-Telugu.html)</li>


<pre>Expected: itelu=0+689|ssatelu=1+713|ttasubscripttelu=1@-86,-30+0|maivoweltelu=4+1058|natelu=6+702</pre>



<pre>Got     : itelu=0+689|ssatelu=1+713|ttasubscripttelu=1@-86,0+0|maivoweltelu=4+1058|natelu=6+702</pre>



<pre>                                                           ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3162 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M300.0,-12.0Q192.0,-12.0 142.5,27.0Q93.0,66.0 93.0,132.0Q93.0,195.0 144.0,232.0Q195.0,269.0 292.0,269.0Q374.0,269.0 436.5,240.0Q499.0,211.0 540.0,167.0Q571.0,215.0 571.0,286.0Q571.0,359.0 542.0,390.0Q513.0,421.0 469.0,421.0Q425.0,421.0 399.5,391.0Q374.0,361.0 366.0,318.0L288.0,318.0Q270.0,425.0 184.0,425.0Q147.0,425.0 129.5,407.5Q112.0,390.0 112.0,364.0Q112.0,348.0 116.5,331.5Q121.0,315.0 126.0,305.0L50.0,283.0Q42.0,300.0 35.5,321.5Q29.0,343.0 29.0,372.0Q29.0,411.0 49.5,439.5Q70.0,468.0 104.5,484.0Q139.0,500.0 181.0,500.0Q232.0,500.0 266.5,479.5Q301.0,459.0 327.0,414.0Q357.0,465.0 396.0,482.5Q435.0,500.0 476.0,500.0Q527.0,500.0 567.0,474.5Q607.0,449.0 630.5,401.5Q654.0,354.0 654.0,287.0Q654.0,227.0 636.5,181.0Q619.0,135.0 586.0,99.0Q609.0,51.0 609.0,0.0Q609.0,-25.0 605.0,-49.5Q601.0,-74.0 591.0,-97.0L518.0,-82.0Q525.0,-65.0 528.5,-44.0Q532.0,-23.0 532.0,4.0Q532.0,28.0 526.0,50.0Q483.0,21.0 429.0,4.5Q375.0,-12.0 300.0,-12.0ZM176.0,132.0Q176.0,99.0 206.0,81.0Q236.0,63.0 302.0,63.0Q359.0,63.0 408.0,76.0Q457.0,89.0 491.0,115.0Q461.0,151.0 410.0,172.5Q359.0,194.0 292.0,194.0Q235.0,194.0 205.5,177.5Q176.0,161.0 176.0,132.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,192.0Q593.0,250.0 570.0,293.5Q547.0,337.0 507.0,369.0Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(689, 983)"/>
<path d="M-167.0,-386.0Q-204.0,-386.0 -230.5,-373.0Q-257.0,-360.0 -280.0,-329.0Q-303.0,-363.0 -331.5,-374.5Q-360.0,-386.0 -393.0,-386.0Q-440.0,-386.0 -471.5,-364.5Q-503.0,-343.0 -519.0,-307.5Q-535.0,-272.0 -535.0,-230.0Q-535.0,-175.0 -513.0,-137.5Q-491.0,-100.0 -456.5,-80.5Q-422.0,-61.0 -384.0,-61.0Q-338.0,-61.0 -312.5,-84.5Q-287.0,-108.0 -287.0,-147.0Q-287.0,-188.0 -315.0,-214.5Q-343.0,-241.0 -399.0,-241.0Q-418.0,-241.0 -435.5,-236.5Q-453.0,-232.0 -468.0,-225.0L-468.0,-229.0Q-468.0,-251.0 -462.0,-272.5Q-456.0,-294.0 -439.0,-308.0Q-422.0,-322.0 -391.0,-322.0Q-353.0,-322.0 -335.0,-303.5Q-317.0,-285.0 -313.0,-254.0L-246.0,-254.0Q-242.0,-289.0 -222.5,-305.5Q-203.0,-322.0 -175.0,-322.0Q-140.0,-322.0 -124.0,-303.5Q-108.0,-285.0 -108.0,-251.0Q-108.0,-204.0 -141.0,-174.0Q-174.0,-144.0 -229.0,-123.0L-195.0,-61.0Q-129.0,-86.0 -83.0,-135.5Q-37.0,-185.0 -37.0,-252.0Q-37.0,-316.0 -72.0,-351.0Q-107.0,-386.0 -167.0,-386.0ZM-390.0,-119.0Q-413.0,-119.0 -432.0,-132.5Q-451.0,-146.0 -460.0,-172.0Q-450.0,-178.0 -436.0,-182.0Q-422.0,-186.0 -406.0,-186.0Q-349.0,-186.0 -349.0,-151.0Q-349.0,-119.0 -390.0,-119.0Z"  transform="translate(1316, 983)"/>
<path d="M481.0,-12.0Q429.0,-12.0 392.0,10.0Q355.0,32.0 321.0,71.0Q293.0,34.0 261.0,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 438.0,75.5Q459.0,67.0 487.0,67.0Q539.0,67.0 566.0,99.0Q593.0,131.0 593.0,192.0Q593.0,256.0 565.0,302.0Q537.0,348.0 493.0,378.5Q449.0,409.0 402.0,425.0L296.0,425.0L296.0,500.0L337.0,500.0L459.0,474.0Q518.0,452.0 567.0,415.5Q616.0,379.0 646.0,324.5Q676.0,270.0 676.0,194.0Q676.0,176.0 674.0,159.0Q713.0,112.0 751.5,89.5Q790.0,67.0 835.0,67.0Q886.0,67.0 913.0,99.5Q940.0,132.0 940.0,193.0Q940.0,251.0 916.5,294.5Q893.0,338.0 853.5,369.5Q814.0,401.0 764.0,423.0L801.0,500.0Q863.0,474.0 913.0,430.0Q963.0,386.0 993.0,328.0Q1023.0,270.0 1023.0,199.0Q1023.0,100.0 973.0,44.0Q923.0,-12.0 828.0,-12.0Q773.0,-12.0 728.5,12.0Q684.0,36.0 649.0,76.0Q626.0,35.0 584.5,11.5Q543.0,-12.0 481.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM631.0,553.0Q631.0,520.0 619.5,496.5Q608.0,473.0 592.0,460.0Q569.0,441.0 536.5,433.0Q504.0,425.0 447.0,425.0L325.0,425.0L325.0,500.0L459.0,500.0Q518.0,500.0 534.0,515.0Q549.0,529.0 549.0,552.0Q549.0,579.0 533.0,592.0Q523.0,600.0 508.0,604.0Q493.0,608.0 458.0,608.0L69.0,608.0L69.0,683.0L452.0,683.0Q507.0,683.0 538.5,675.0Q570.0,667.0 593.0,647.0Q610.0,632.0 620.5,609.5Q631.0,587.0 631.0,553.0ZM183.0,-61.0Q229.0,-61.0 257.5,-78.0Q286.0,-95.0 299.0,-121.0Q312.0,-147.0 312.0,-173.0Q312.0,-194.0 306.5,-211.0Q301.0,-228.0 292.0,-243.0L743.0,-243.0L743.0,-318.0L264.0,-318.0Q200.0,-318.0 160.5,-310.0Q121.0,-302.0 95.0,-282.0Q74.0,-266.0 61.5,-242.0Q49.0,-218.0 49.0,-181.0Q49.0,-127.0 86.0,-94.0Q123.0,-61.0 183.0,-61.0ZM215.0,-243.0L220.0,-243.0Q243.0,-215.0 243.0,-184.0Q243.0,-158.0 226.5,-142.5Q210.0,-127.0 179.0,-127.0Q148.0,-127.0 133.0,-142.5Q118.0,-158.0 118.0,-180.0Q118.0,-215.0 143.5,-229.0Q169.0,-243.0 215.0,-243.0Z"  transform="translate(1402, 983)"/>
<path d="M472.0,-12.0Q425.0,-12.0 390.0,3.5Q355.0,19.0 324.0,51.5Q293.0,84.0 256.0,133.0Q224.0,176.0 206.5,192.5Q189.0,209.0 164.0,209.0Q141.0,209.0 126.0,190.5Q111.0,172.0 111.0,143.0Q111.0,108.0 123.0,77.0Q135.0,46.0 159.0,14.0L78.0,-13.0Q56.0,22.0 42.5,59.5Q29.0,97.0 29.0,143.0Q29.0,204.0 67.0,245.0Q105.0,286.0 165.0,286.0Q204.0,286.0 230.5,272.5Q257.0,259.0 279.5,234.5Q302.0,210.0 328.0,175.0Q358.0,136.0 380.5,112.0Q403.0,88.0 425.5,77.5Q448.0,67.0 478.0,67.0Q530.0,67.0 557.0,100.0Q584.0,133.0 584.0,194.0Q584.0,269.0 544.0,320.5Q504.0,372.0 435.5,398.5Q367.0,425.0 282.0,425.0L238.0,425.0L238.0,425.0L236.0,425.0Q207.0,425.0 180.5,436.0Q154.0,447.0 132.0,477.5Q110.0,508.0 94.0,564.0L177.0,591.0Q192.0,536.0 206.0,518.0Q220.0,500.0 242.0,500.0Q262.0,500.0 279.5,512.5Q297.0,525.0 329.0,565.0L360.0,605.0Q394.0,649.0 422.5,675.0Q451.0,701.0 483.0,713.0Q515.0,725.0 559.0,725.0L565.0,648.0Q530.0,646.0 506.5,637.0Q483.0,628.0 463.5,608.5Q444.0,589.0 418.0,556.0L395.0,526.0Q381.0,508.0 369.0,494.0Q464.0,480.0 530.5,438.5Q597.0,397.0 632.0,334.5Q667.0,272.0 667.0,194.0Q667.0,101.0 618.0,44.5Q569.0,-12.0 472.0,-12.0Z"  transform="translate(2460, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3162 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M300.0,-12.0Q192.0,-12.0 142.5,27.0Q93.0,66.0 93.0,132.0Q93.0,195.0 144.0,232.0Q195.0,269.0 292.0,269.0Q374.0,269.0 436.5,240.0Q499.0,211.0 540.0,167.0Q571.0,215.0 571.0,286.0Q571.0,359.0 542.0,390.0Q513.0,421.0 469.0,421.0Q425.0,421.0 399.5,391.0Q374.0,361.0 366.0,318.0L288.0,318.0Q270.0,425.0 184.0,425.0Q147.0,425.0 129.5,407.5Q112.0,390.0 112.0,364.0Q112.0,348.0 116.5,331.5Q121.0,315.0 126.0,305.0L50.0,283.0Q42.0,300.0 35.5,321.5Q29.0,343.0 29.0,372.0Q29.0,411.0 49.5,439.5Q70.0,468.0 104.5,484.0Q139.0,500.0 181.0,500.0Q232.0,500.0 266.5,479.5Q301.0,459.0 327.0,414.0Q357.0,465.0 396.0,482.5Q435.0,500.0 476.0,500.0Q527.0,500.0 567.0,474.5Q607.0,449.0 630.5,401.5Q654.0,354.0 654.0,287.0Q654.0,227.0 636.5,181.0Q619.0,135.0 586.0,99.0Q609.0,51.0 609.0,0.0Q609.0,-25.0 605.0,-49.5Q601.0,-74.0 591.0,-97.0L518.0,-82.0Q525.0,-65.0 528.5,-44.0Q532.0,-23.0 532.0,4.0Q532.0,28.0 526.0,50.0Q483.0,21.0 429.0,4.5Q375.0,-12.0 300.0,-12.0ZM176.0,132.0Q176.0,99.0 206.0,81.0Q236.0,63.0 302.0,63.0Q359.0,63.0 408.0,76.0Q457.0,89.0 491.0,115.0Q461.0,151.0 410.0,172.5Q359.0,194.0 292.0,194.0Q235.0,194.0 205.5,177.5Q176.0,161.0 176.0,132.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,192.0Q593.0,250.0 570.0,293.5Q547.0,337.0 507.0,369.0Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(689, 983)"/>
<path d="M-167.0,-386.0Q-204.0,-386.0 -230.5,-373.0Q-257.0,-360.0 -280.0,-329.0Q-303.0,-363.0 -331.5,-374.5Q-360.0,-386.0 -393.0,-386.0Q-440.0,-386.0 -471.5,-364.5Q-503.0,-343.0 -519.0,-307.5Q-535.0,-272.0 -535.0,-230.0Q-535.0,-175.0 -513.0,-137.5Q-491.0,-100.0 -456.5,-80.5Q-422.0,-61.0 -384.0,-61.0Q-338.0,-61.0 -312.5,-84.5Q-287.0,-108.0 -287.0,-147.0Q-287.0,-188.0 -315.0,-214.5Q-343.0,-241.0 -399.0,-241.0Q-418.0,-241.0 -435.5,-236.5Q-453.0,-232.0 -468.0,-225.0L-468.0,-229.0Q-468.0,-251.0 -462.0,-272.5Q-456.0,-294.0 -439.0,-308.0Q-422.0,-322.0 -391.0,-322.0Q-353.0,-322.0 -335.0,-303.5Q-317.0,-285.0 -313.0,-254.0L-246.0,-254.0Q-242.0,-289.0 -222.5,-305.5Q-203.0,-322.0 -175.0,-322.0Q-140.0,-322.0 -124.0,-303.5Q-108.0,-285.0 -108.0,-251.0Q-108.0,-204.0 -141.0,-174.0Q-174.0,-144.0 -229.0,-123.0L-195.0,-61.0Q-129.0,-86.0 -83.0,-135.5Q-37.0,-185.0 -37.0,-252.0Q-37.0,-316.0 -72.0,-351.0Q-107.0,-386.0 -167.0,-386.0ZM-390.0,-119.0Q-413.0,-119.0 -432.0,-132.5Q-451.0,-146.0 -460.0,-172.0Q-450.0,-178.0 -436.0,-182.0Q-422.0,-186.0 -406.0,-186.0Q-349.0,-186.0 -349.0,-151.0Q-349.0,-119.0 -390.0,-119.0Z"  transform="translate(1316, 953)"/>
<path d="M481.0,-12.0Q429.0,-12.0 392.0,10.0Q355.0,32.0 321.0,71.0Q293.0,34.0 261.0,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 438.0,75.5Q459.0,67.0 487.0,67.0Q539.0,67.0 566.0,99.0Q593.0,131.0 593.0,192.0Q593.0,256.0 565.0,302.0Q537.0,348.0 493.0,378.5Q449.0,409.0 402.0,425.0L296.0,425.0L296.0,500.0L337.0,500.0L459.0,474.0Q518.0,452.0 567.0,415.5Q616.0,379.0 646.0,324.5Q676.0,270.0 676.0,194.0Q676.0,176.0 674.0,159.0Q713.0,112.0 751.5,89.5Q790.0,67.0 835.0,67.0Q886.0,67.0 913.0,99.5Q940.0,132.0 940.0,193.0Q940.0,251.0 916.5,294.5Q893.0,338.0 853.5,369.5Q814.0,401.0 764.0,423.0L801.0,500.0Q863.0,474.0 913.0,430.0Q963.0,386.0 993.0,328.0Q1023.0,270.0 1023.0,199.0Q1023.0,100.0 973.0,44.0Q923.0,-12.0 828.0,-12.0Q773.0,-12.0 728.5,12.0Q684.0,36.0 649.0,76.0Q626.0,35.0 584.5,11.5Q543.0,-12.0 481.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM631.0,553.0Q631.0,520.0 619.5,496.5Q608.0,473.0 592.0,460.0Q569.0,441.0 536.5,433.0Q504.0,425.0 447.0,425.0L325.0,425.0L325.0,500.0L459.0,500.0Q518.0,500.0 534.0,515.0Q549.0,529.0 549.0,552.0Q549.0,579.0 533.0,592.0Q523.0,600.0 508.0,604.0Q493.0,608.0 458.0,608.0L69.0,608.0L69.0,683.0L452.0,683.0Q507.0,683.0 538.5,675.0Q570.0,667.0 593.0,647.0Q610.0,632.0 620.5,609.5Q631.0,587.0 631.0,553.0ZM183.0,-61.0Q229.0,-61.0 257.5,-78.0Q286.0,-95.0 299.0,-121.0Q312.0,-147.0 312.0,-173.0Q312.0,-194.0 306.5,-211.0Q301.0,-228.0 292.0,-243.0L743.0,-243.0L743.0,-318.0L264.0,-318.0Q200.0,-318.0 160.5,-310.0Q121.0,-302.0 95.0,-282.0Q74.0,-266.0 61.5,-242.0Q49.0,-218.0 49.0,-181.0Q49.0,-127.0 86.0,-94.0Q123.0,-61.0 183.0,-61.0ZM215.0,-243.0L220.0,-243.0Q243.0,-215.0 243.0,-184.0Q243.0,-158.0 226.5,-142.5Q210.0,-127.0 179.0,-127.0Q148.0,-127.0 133.0,-142.5Q118.0,-158.0 118.0,-180.0Q118.0,-215.0 143.5,-229.0Q169.0,-243.0 215.0,-243.0Z"  transform="translate(1402, 983)"/>
<path d="M472.0,-12.0Q425.0,-12.0 390.0,3.5Q355.0,19.0 324.0,51.5Q293.0,84.0 256.0,133.0Q224.0,176.0 206.5,192.5Q189.0,209.0 164.0,209.0Q141.0,209.0 126.0,190.5Q111.0,172.0 111.0,143.0Q111.0,108.0 123.0,77.0Q135.0,46.0 159.0,14.0L78.0,-13.0Q56.0,22.0 42.5,59.5Q29.0,97.0 29.0,143.0Q29.0,204.0 67.0,245.0Q105.0,286.0 165.0,286.0Q204.0,286.0 230.5,272.5Q257.0,259.0 279.5,234.5Q302.0,210.0 328.0,175.0Q358.0,136.0 380.5,112.0Q403.0,88.0 425.5,77.5Q448.0,67.0 478.0,67.0Q530.0,67.0 557.0,100.0Q584.0,133.0 584.0,194.0Q584.0,269.0 544.0,320.5Q504.0,372.0 435.5,398.5Q367.0,425.0 282.0,425.0L238.0,425.0L238.0,425.0L236.0,425.0Q207.0,425.0 180.5,436.0Q154.0,447.0 132.0,477.5Q110.0,508.0 94.0,564.0L177.0,591.0Q192.0,536.0 206.0,518.0Q220.0,500.0 242.0,500.0Q262.0,500.0 279.5,512.5Q297.0,525.0 329.0,565.0L360.0,605.0Q394.0,649.0 422.5,675.0Q451.0,701.0 483.0,713.0Q515.0,725.0 559.0,725.0L565.0,648.0Q530.0,646.0 506.5,637.0Q483.0,628.0 463.5,608.5Q444.0,589.0 418.0,556.0L395.0,526.0Q381.0,508.0 369.0,494.0Q464.0,480.0 530.5,438.5Q597.0,397.0 632.0,334.5Q667.0,272.0 667.0,194.0Q667.0,101.0 618.0,44.5Q569.0,-12.0 472.0,-12.0Z"  transform="translate(2460, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">కృష్ణదేవ</span> (fontdiff-Telugu.html)</li>


<pre>Expected: katelu=0+522|rvocalicvowelsigntelu=0+400|ssatelu=2+713|nnasubscripttelu=2@-67,-30+0|deevoweltelu=5+706|vatelu=7+711</pre>



<pre>Got     : katelu=0+522|rvocalicvowelsigntelu=0+400|ssatelu=2+713|nnasubscripttelu=2@-67,0+0|deevoweltelu=5+706|vatelu=7+711</pre>



<pre>                                                                                        ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3052 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(0, 983)"/>
<path d="M97.0,-386.0Q26.0,-386.0 -25.0,-360.0Q-76.0,-334.0 -103.0,-288.5Q-130.0,-243.0 -130.0,-186.0Q-130.0,-133.0 -108.5,-95.0Q-87.0,-57.0 -50.0,-36.0Q-13.0,-15.0 32.0,-15.0Q99.0,-15.0 130.0,-50.5Q161.0,-86.0 161.0,-131.0Q161.0,-189.0 125.0,-222.5Q89.0,-256.0 13.0,-256.0Q-17.0,-256.0 -48.0,-243.0Q-16.0,-315.0 102.0,-315.0Q140.0,-315.0 178.0,-305.5Q216.0,-296.0 248.0,-271.0Q280.0,-246.0 299.5,-200.5Q319.0,-155.0 319.0,-83.0Q319.0,-6.0 292.0,68.5Q265.0,143.0 217.5,210.0Q170.0,277.0 108.5,333.5Q47.0,390.0 -23.0,430.0L18.0,500.0Q84.0,462.0 151.0,403.0Q218.0,344.0 274.0,268.0Q330.0,192.0 364.0,103.0Q398.0,14.0 398.0,-84.0Q398.0,-190.0 358.0,-256.5Q318.0,-323.0 250.0,-354.5Q182.0,-386.0 97.0,-386.0ZM31.0,-79.0Q-8.0,-79.0 -32.0,-105.5Q-56.0,-132.0 -59.0,-175.0Q-30.0,-192.0 8.0,-192.0Q88.0,-192.0 88.0,-135.0Q88.0,-109.0 72.5,-94.0Q57.0,-79.0 31.0,-79.0Z"  transform="translate(522, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,192.0Q593.0,250.0 570.0,293.5Q547.0,337.0 507.0,369.0Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(922, 983)"/>
<path d="M-180.0,-386.0Q-232.0,-386.0 -259.0,-359.5Q-286.0,-333.0 -286.0,-296.0Q-286.0,-260.0 -260.0,-232.5Q-234.0,-205.0 -182.0,-205.0Q-158.0,-205.0 -139.0,-211.5Q-120.0,-218.0 -104.0,-229.0L-104.0,-229.0Q-104.0,-184.0 -126.5,-154.5Q-149.0,-125.0 -193.0,-125.0Q-226.0,-125.0 -244.0,-143.5Q-262.0,-162.0 -267.0,-184.0L-335.0,-184.0Q-341.0,-163.0 -364.5,-143.0Q-388.0,-123.0 -438.0,-123.0Q-502.0,-123.0 -502.0,-159.0Q-502.0,-174.0 -489.5,-184.0Q-477.0,-194.0 -448.0,-194.0L-386.0,-194.0L-386.0,-251.0L-438.0,-251.0Q-506.0,-251.0 -506.0,-290.0Q-506.0,-303.0 -496.0,-314.5Q-486.0,-326.0 -458.0,-326.0Q-429.0,-326.0 -410.0,-314.5Q-391.0,-303.0 -369.0,-282.0L-322.0,-324.0Q-351.0,-354.0 -383.5,-370.0Q-416.0,-386.0 -461.0,-386.0Q-521.0,-386.0 -549.5,-361.0Q-578.0,-336.0 -578.0,-300.0Q-578.0,-274.0 -563.5,-253.5Q-549.0,-233.0 -516.0,-223.0Q-547.0,-212.0 -560.0,-192.0Q-573.0,-172.0 -573.0,-147.0Q-573.0,-108.0 -538.0,-84.5Q-503.0,-61.0 -445.0,-61.0Q-394.0,-61.0 -361.5,-75.5Q-329.0,-90.0 -302.0,-118.0Q-281.0,-91.0 -254.5,-76.0Q-228.0,-61.0 -189.0,-61.0Q-116.0,-61.0 -76.5,-109.0Q-37.0,-157.0 -37.0,-228.0Q-37.0,-303.0 -73.0,-344.5Q-109.0,-386.0 -180.0,-386.0ZM-220.0,-295.0Q-220.0,-308.0 -210.0,-318.0Q-200.0,-328.0 -177.0,-328.0Q-156.0,-328.0 -139.0,-319.5Q-122.0,-311.0 -113.0,-289.0Q-125.0,-276.0 -140.5,-268.5Q-156.0,-261.0 -176.0,-261.0Q-196.0,-261.0 -208.0,-270.0Q-220.0,-279.0 -220.0,-295.0Z"  transform="translate(1568, 983)"/>
<path d="M504.0,-12.0Q452.0,-12.0 416.5,7.5Q381.0,27.0 352.0,74.0Q321.0,20.0 282.0,4.0Q243.0,-12.0 198.0,-12.0Q125.0,-12.0 80.0,44.0Q35.0,100.0 35.0,200.0Q35.0,289.0 74.0,356.5Q113.0,424.0 185.0,462.0Q257.0,500.0 357.0,500.0Q457.0,500.0 527.0,461.5Q597.0,423.0 634.0,355.5Q671.0,288.0 671.0,200.0Q671.0,97.0 626.0,42.5Q581.0,-12.0 504.0,-12.0ZM496.0,67.0Q538.0,67.0 563.0,98.0Q588.0,129.0 588.0,202.0Q588.0,267.0 563.5,317.0Q539.0,367.0 489.5,396.0Q440.0,425.0 364.0,425.0L349.0,425.0Q237.0,425.0 177.5,364.0Q118.0,303.0 118.0,205.0Q118.0,130.0 142.5,98.5Q167.0,67.0 210.0,67.0Q255.0,67.0 282.5,99.5Q310.0,132.0 314.0,185.0L392.0,185.0Q396.0,124.0 427.5,95.5Q459.0,67.0 496.0,67.0ZM612.0,553.0Q612.0,520.0 600.5,496.5Q589.0,473.0 573.0,460.0Q550.0,441.0 517.5,433.0Q485.0,425.0 428.0,425.0L373.0,425.0L373.0,500.0L440.0,500.0Q472.0,500.0 488.5,503.5Q505.0,507.0 515.0,515.0Q530.0,529.0 530.0,552.0Q530.0,579.0 514.0,592.0Q504.0,600.0 489.0,604.0Q474.0,608.0 439.0,608.0L95.0,608.0L95.0,683.0L370.0,683.0Q365.0,700.0 365.0,719.0Q365.0,772.0 405.0,802.0Q445.0,832.0 506.0,832.0Q567.0,832.0 601.5,806.5Q636.0,781.0 653.0,736.0L577.0,716.0Q569.0,739.0 552.5,752.5Q536.0,766.0 507.0,766.0Q480.0,766.0 460.0,752.0Q440.0,738.0 440.0,711.0Q440.0,696.0 448.0,683.0Q495.0,682.0 523.5,673.5Q552.0,665.0 574.0,647.0Q591.0,632.0 601.5,609.5Q612.0,587.0 612.0,553.0Z"  transform="translate(1635, 983)"/>
<path d="M481.0,-12.0Q429.0,-12.0 392.0,10.0Q355.0,32.0 321.0,71.0Q293.0,34.0 261.0,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 438.0,75.5Q459.0,67.0 486.0,67.0Q539.0,67.0 566.0,99.0Q593.0,131.0 593.0,192.0Q593.0,268.0 553.0,319.5Q513.0,371.0 445.0,398.0Q377.0,425.0 292.0,425.0L243.0,425.0L326.0,500.0Q437.0,493.0 515.5,452.5Q594.0,412.0 635.0,345.5Q676.0,279.0 676.0,194.0Q676.0,135.0 655.0,88.0Q634.0,41.0 590.5,14.5Q547.0,-12.0 481.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM239.0,425.0Q210.0,425.0 183.5,436.0Q157.0,447.0 135.0,477.5Q113.0,508.0 97.0,564.0L180.0,591.0Q195.0,536.0 209.0,518.0Q223.0,500.0 245.0,500.0Q265.0,500.0 282.5,512.5Q300.0,525.0 332.0,565.0L363.0,605.0Q397.0,649.0 425.5,675.0Q454.0,701.0 486.0,713.0Q518.0,725.0 562.0,725.0L568.0,648.0Q533.0,646.0 509.5,637.0Q486.0,628.0 466.5,608.5Q447.0,589.0 421.0,556.0L398.0,526.0Q356.0,472.0 320.0,448.5Q284.0,425.0 239.0,425.0Z"  transform="translate(2341, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3052 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(0, 983)"/>
<path d="M97.0,-386.0Q26.0,-386.0 -25.0,-360.0Q-76.0,-334.0 -103.0,-288.5Q-130.0,-243.0 -130.0,-186.0Q-130.0,-133.0 -108.5,-95.0Q-87.0,-57.0 -50.0,-36.0Q-13.0,-15.0 32.0,-15.0Q99.0,-15.0 130.0,-50.5Q161.0,-86.0 161.0,-131.0Q161.0,-189.0 125.0,-222.5Q89.0,-256.0 13.0,-256.0Q-17.0,-256.0 -48.0,-243.0Q-16.0,-315.0 102.0,-315.0Q140.0,-315.0 178.0,-305.5Q216.0,-296.0 248.0,-271.0Q280.0,-246.0 299.5,-200.5Q319.0,-155.0 319.0,-83.0Q319.0,-6.0 292.0,68.5Q265.0,143.0 217.5,210.0Q170.0,277.0 108.5,333.5Q47.0,390.0 -23.0,430.0L18.0,500.0Q84.0,462.0 151.0,403.0Q218.0,344.0 274.0,268.0Q330.0,192.0 364.0,103.0Q398.0,14.0 398.0,-84.0Q398.0,-190.0 358.0,-256.5Q318.0,-323.0 250.0,-354.5Q182.0,-386.0 97.0,-386.0ZM31.0,-79.0Q-8.0,-79.0 -32.0,-105.5Q-56.0,-132.0 -59.0,-175.0Q-30.0,-192.0 8.0,-192.0Q88.0,-192.0 88.0,-135.0Q88.0,-109.0 72.5,-94.0Q57.0,-79.0 31.0,-79.0Z"  transform="translate(522, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,192.0Q593.0,250.0 570.0,293.5Q547.0,337.0 507.0,369.0Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(922, 983)"/>
<path d="M-180.0,-386.0Q-232.0,-386.0 -259.0,-359.5Q-286.0,-333.0 -286.0,-296.0Q-286.0,-260.0 -260.0,-232.5Q-234.0,-205.0 -182.0,-205.0Q-158.0,-205.0 -139.0,-211.5Q-120.0,-218.0 -104.0,-229.0L-104.0,-229.0Q-104.0,-184.0 -126.5,-154.5Q-149.0,-125.0 -193.0,-125.0Q-226.0,-125.0 -244.0,-143.5Q-262.0,-162.0 -267.0,-184.0L-335.0,-184.0Q-341.0,-163.0 -364.5,-143.0Q-388.0,-123.0 -438.0,-123.0Q-502.0,-123.0 -502.0,-159.0Q-502.0,-174.0 -489.5,-184.0Q-477.0,-194.0 -448.0,-194.0L-386.0,-194.0L-386.0,-251.0L-438.0,-251.0Q-506.0,-251.0 -506.0,-290.0Q-506.0,-303.0 -496.0,-314.5Q-486.0,-326.0 -458.0,-326.0Q-429.0,-326.0 -410.0,-314.5Q-391.0,-303.0 -369.0,-282.0L-322.0,-324.0Q-351.0,-354.0 -383.5,-370.0Q-416.0,-386.0 -461.0,-386.0Q-521.0,-386.0 -549.5,-361.0Q-578.0,-336.0 -578.0,-300.0Q-578.0,-274.0 -563.5,-253.5Q-549.0,-233.0 -516.0,-223.0Q-547.0,-212.0 -560.0,-192.0Q-573.0,-172.0 -573.0,-147.0Q-573.0,-108.0 -538.0,-84.5Q-503.0,-61.0 -445.0,-61.0Q-394.0,-61.0 -361.5,-75.5Q-329.0,-90.0 -302.0,-118.0Q-281.0,-91.0 -254.5,-76.0Q-228.0,-61.0 -189.0,-61.0Q-116.0,-61.0 -76.5,-109.0Q-37.0,-157.0 -37.0,-228.0Q-37.0,-303.0 -73.0,-344.5Q-109.0,-386.0 -180.0,-386.0ZM-220.0,-295.0Q-220.0,-308.0 -210.0,-318.0Q-200.0,-328.0 -177.0,-328.0Q-156.0,-328.0 -139.0,-319.5Q-122.0,-311.0 -113.0,-289.0Q-125.0,-276.0 -140.5,-268.5Q-156.0,-261.0 -176.0,-261.0Q-196.0,-261.0 -208.0,-270.0Q-220.0,-279.0 -220.0,-295.0Z"  transform="translate(1568, 953)"/>
<path d="M504.0,-12.0Q452.0,-12.0 416.5,7.5Q381.0,27.0 352.0,74.0Q321.0,20.0 282.0,4.0Q243.0,-12.0 198.0,-12.0Q125.0,-12.0 80.0,44.0Q35.0,100.0 35.0,200.0Q35.0,289.0 74.0,356.5Q113.0,424.0 185.0,462.0Q257.0,500.0 357.0,500.0Q457.0,500.0 527.0,461.5Q597.0,423.0 634.0,355.5Q671.0,288.0 671.0,200.0Q671.0,97.0 626.0,42.5Q581.0,-12.0 504.0,-12.0ZM496.0,67.0Q538.0,67.0 563.0,98.0Q588.0,129.0 588.0,202.0Q588.0,267.0 563.5,317.0Q539.0,367.0 489.5,396.0Q440.0,425.0 364.0,425.0L349.0,425.0Q237.0,425.0 177.5,364.0Q118.0,303.0 118.0,205.0Q118.0,130.0 142.5,98.5Q167.0,67.0 210.0,67.0Q255.0,67.0 282.5,99.5Q310.0,132.0 314.0,185.0L392.0,185.0Q396.0,124.0 427.5,95.5Q459.0,67.0 496.0,67.0ZM612.0,553.0Q612.0,520.0 600.5,496.5Q589.0,473.0 573.0,460.0Q550.0,441.0 517.5,433.0Q485.0,425.0 428.0,425.0L373.0,425.0L373.0,500.0L440.0,500.0Q472.0,500.0 488.5,503.5Q505.0,507.0 515.0,515.0Q530.0,529.0 530.0,552.0Q530.0,579.0 514.0,592.0Q504.0,600.0 489.0,604.0Q474.0,608.0 439.0,608.0L95.0,608.0L95.0,683.0L370.0,683.0Q365.0,700.0 365.0,719.0Q365.0,772.0 405.0,802.0Q445.0,832.0 506.0,832.0Q567.0,832.0 601.5,806.5Q636.0,781.0 653.0,736.0L577.0,716.0Q569.0,739.0 552.5,752.5Q536.0,766.0 507.0,766.0Q480.0,766.0 460.0,752.0Q440.0,738.0 440.0,711.0Q440.0,696.0 448.0,683.0Q495.0,682.0 523.5,673.5Q552.0,665.0 574.0,647.0Q591.0,632.0 601.5,609.5Q612.0,587.0 612.0,553.0Z"  transform="translate(1635, 983)"/>
<path d="M481.0,-12.0Q429.0,-12.0 392.0,10.0Q355.0,32.0 321.0,71.0Q293.0,34.0 261.0,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 438.0,75.5Q459.0,67.0 486.0,67.0Q539.0,67.0 566.0,99.0Q593.0,131.0 593.0,192.0Q593.0,268.0 553.0,319.5Q513.0,371.0 445.0,398.0Q377.0,425.0 292.0,425.0L243.0,425.0L326.0,500.0Q437.0,493.0 515.5,452.5Q594.0,412.0 635.0,345.5Q676.0,279.0 676.0,194.0Q676.0,135.0 655.0,88.0Q634.0,41.0 590.5,14.5Q547.0,-12.0 481.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM239.0,425.0Q210.0,425.0 183.5,436.0Q157.0,447.0 135.0,477.5Q113.0,508.0 97.0,564.0L180.0,591.0Q195.0,536.0 209.0,518.0Q223.0,500.0 245.0,500.0Q265.0,500.0 282.5,512.5Q300.0,525.0 332.0,565.0L363.0,605.0Q397.0,649.0 425.5,675.0Q454.0,701.0 486.0,713.0Q518.0,725.0 562.0,725.0L568.0,648.0Q533.0,646.0 509.5,637.0Q486.0,628.0 466.5,608.5Q447.0,589.0 421.0,556.0L398.0,526.0Q356.0,472.0 320.0,448.5Q284.0,425.0 239.0,425.0Z"  transform="translate(2341, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">రామకృష్ణ</span> (fontdiff-Telugu.html)</li>


<pre>Expected: raavoweltelu=0+906|matelu=2+1058|katelu=3+522|rvocalicvowelsigntelu=3+400|ssatelu=5+713|nnasubscripttelu=5@-67,-30+0</pre>



<pre>Got     : raavoweltelu=0+906|matelu=2+1058|katelu=3+522|rvocalicvowelsigntelu=3+400|ssatelu=5+713|nnasubscripttelu=5@-67,0+0</pre>



<pre>                                                                                                                         ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3599 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M42.0,236.0Q42.0,297.0 62.5,345.0Q83.0,393.0 121.0,425.0L43.0,425.0L43.0,500.0L710.0,500.0Q775.0,500.0 811.5,492.0Q848.0,484.0 875.0,462.0Q896.0,446.0 909.0,418.5Q922.0,391.0 922.0,353.0Q922.0,290.0 884.0,255.0Q846.0,220.0 781.0,220.0Q731.0,220.0 701.0,239.0Q671.0,258.0 657.5,287.0Q644.0,316.0 644.0,344.0Q644.0,369.0 650.0,388.5Q656.0,408.0 666.0,425.0L488.0,425.0Q524.0,393.0 544.5,346.0Q565.0,299.0 565.0,237.0Q565.0,163.0 533.0,106.5Q501.0,50.0 442.0,19.0Q383.0,-12.0 303.0,-12.0Q224.0,-12.0 165.5,18.5Q107.0,49.0 74.5,105.0Q42.0,161.0 42.0,236.0ZM717.0,353.0Q717.0,323.0 734.5,304.5Q752.0,286.0 785.0,286.0Q820.0,286.0 834.5,304.5Q849.0,323.0 849.0,350.0Q849.0,392.0 823.5,408.5Q798.0,425.0 752.0,425.0L743.0,425.0Q717.0,391.0 717.0,353.0ZM125.0,248.0Q125.0,167.0 170.0,117.0Q215.0,67.0 303.0,67.0Q392.0,67.0 437.0,116.5Q482.0,166.0 482.0,242.0Q482.0,293.0 462.5,334.5Q443.0,376.0 403.5,400.5Q364.0,425.0 303.0,425.0Q242.0,425.0 202.5,400.5Q163.0,376.0 144.0,336.0Q125.0,296.0 125.0,248.0Z"  transform="translate(0, 983)"/>
<path d="M239.0,425.0Q210.0,425.0 183.5,436.0Q157.0,447.0 135.0,477.5Q113.0,508.0 97.0,564.0L180.0,591.0Q195.0,536.0 209.0,518.0Q223.0,500.0 245.0,500.0Q265.0,500.0 282.5,512.5Q300.0,525.0 332.0,565.0L363.0,605.0Q397.0,649.0 425.5,675.0Q454.0,701.0 486.0,713.0Q518.0,725.0 562.0,725.0L568.0,648.0Q533.0,646.0 509.5,637.0Q486.0,628.0 466.5,608.5Q447.0,589.0 421.0,556.0L398.0,526.0Q356.0,472.0 320.0,448.5Q284.0,425.0 239.0,425.0ZM481.0,-12.0Q429.0,-12.0 392.0,10.0Q355.0,32.0 321.0,71.0Q293.0,34.0 261.0,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 438.0,75.5Q459.0,67.0 486.0,67.0Q539.0,67.0 566.0,99.0Q593.0,131.0 593.0,192.0Q593.0,268.0 553.0,319.5Q513.0,371.0 445.0,398.0Q377.0,425.0 292.0,425.0L243.0,425.0L326.0,500.0Q437.0,493.0 515.5,452.5Q594.0,412.0 635.0,345.5Q676.0,279.0 676.0,194.0Q676.0,135.0 655.0,88.0Q634.0,41.0 590.5,14.5Q547.0,-12.0 481.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM828.0,-12.0Q761.0,-12.0 710.5,22.0Q660.0,56.0 621.0,111.0L661.0,176.0Q703.0,121.0 744.5,94.0Q786.0,67.0 835.0,67.0Q886.0,67.0 913.0,99.5Q940.0,132.0 940.0,193.0Q940.0,251.0 916.5,294.5Q893.0,338.0 853.5,369.5Q814.0,401.0 764.0,423.0L801.0,500.0Q863.0,474.0 913.0,430.0Q963.0,386.0 993.0,328.0Q1023.0,270.0 1023.0,199.0Q1023.0,100.0 973.0,44.0Q923.0,-12.0 828.0,-12.0Z"  transform="translate(906, 983)"/>
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(1964, 983)"/>
<path d="M97.0,-386.0Q26.0,-386.0 -25.0,-360.0Q-76.0,-334.0 -103.0,-288.5Q-130.0,-243.0 -130.0,-186.0Q-130.0,-133.0 -108.5,-95.0Q-87.0,-57.0 -50.0,-36.0Q-13.0,-15.0 32.0,-15.0Q99.0,-15.0 130.0,-50.5Q161.0,-86.0 161.0,-131.0Q161.0,-189.0 125.0,-222.5Q89.0,-256.0 13.0,-256.0Q-17.0,-256.0 -48.0,-243.0Q-16.0,-315.0 102.0,-315.0Q140.0,-315.0 178.0,-305.5Q216.0,-296.0 248.0,-271.0Q280.0,-246.0 299.5,-200.5Q319.0,-155.0 319.0,-83.0Q319.0,-6.0 292.0,68.5Q265.0,143.0 217.5,210.0Q170.0,277.0 108.5,333.5Q47.0,390.0 -23.0,430.0L18.0,500.0Q84.0,462.0 151.0,403.0Q218.0,344.0 274.0,268.0Q330.0,192.0 364.0,103.0Q398.0,14.0 398.0,-84.0Q398.0,-190.0 358.0,-256.5Q318.0,-323.0 250.0,-354.5Q182.0,-386.0 97.0,-386.0ZM31.0,-79.0Q-8.0,-79.0 -32.0,-105.5Q-56.0,-132.0 -59.0,-175.0Q-30.0,-192.0 8.0,-192.0Q88.0,-192.0 88.0,-135.0Q88.0,-109.0 72.5,-94.0Q57.0,-79.0 31.0,-79.0Z"  transform="translate(2486, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,192.0Q593.0,250.0 570.0,293.5Q547.0,337.0 507.0,369.0Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(2886, 983)"/>
<path d="M-180.0,-386.0Q-232.0,-386.0 -259.0,-359.5Q-286.0,-333.0 -286.0,-296.0Q-286.0,-260.0 -260.0,-232.5Q-234.0,-205.0 -182.0,-205.0Q-158.0,-205.0 -139.0,-211.5Q-120.0,-218.0 -104.0,-229.0L-104.0,-229.0Q-104.0,-184.0 -126.5,-154.5Q-149.0,-125.0 -193.0,-125.0Q-226.0,-125.0 -244.0,-143.5Q-262.0,-162.0 -267.0,-184.0L-335.0,-184.0Q-341.0,-163.0 -364.5,-143.0Q-388.0,-123.0 -438.0,-123.0Q-502.0,-123.0 -502.0,-159.0Q-502.0,-174.0 -489.5,-184.0Q-477.0,-194.0 -448.0,-194.0L-386.0,-194.0L-386.0,-251.0L-438.0,-251.0Q-506.0,-251.0 -506.0,-290.0Q-506.0,-303.0 -496.0,-314.5Q-486.0,-326.0 -458.0,-326.0Q-429.0,-326.0 -410.0,-314.5Q-391.0,-303.0 -369.0,-282.0L-322.0,-324.0Q-351.0,-354.0 -383.5,-370.0Q-416.0,-386.0 -461.0,-386.0Q-521.0,-386.0 -549.5,-361.0Q-578.0,-336.0 -578.0,-300.0Q-578.0,-274.0 -563.5,-253.5Q-549.0,-233.0 -516.0,-223.0Q-547.0,-212.0 -560.0,-192.0Q-573.0,-172.0 -573.0,-147.0Q-573.0,-108.0 -538.0,-84.5Q-503.0,-61.0 -445.0,-61.0Q-394.0,-61.0 -361.5,-75.5Q-329.0,-90.0 -302.0,-118.0Q-281.0,-91.0 -254.5,-76.0Q-228.0,-61.0 -189.0,-61.0Q-116.0,-61.0 -76.5,-109.0Q-37.0,-157.0 -37.0,-228.0Q-37.0,-303.0 -73.0,-344.5Q-109.0,-386.0 -180.0,-386.0ZM-220.0,-295.0Q-220.0,-308.0 -210.0,-318.0Q-200.0,-328.0 -177.0,-328.0Q-156.0,-328.0 -139.0,-319.5Q-122.0,-311.0 -113.0,-289.0Q-125.0,-276.0 -140.5,-268.5Q-156.0,-261.0 -176.0,-261.0Q-196.0,-261.0 -208.0,-270.0Q-220.0,-279.0 -220.0,-295.0Z"  transform="translate(3532, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3599 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M42.0,236.0Q42.0,297.0 62.5,345.0Q83.0,393.0 121.0,425.0L43.0,425.0L43.0,500.0L710.0,500.0Q775.0,500.0 811.5,492.0Q848.0,484.0 875.0,462.0Q896.0,446.0 909.0,418.5Q922.0,391.0 922.0,353.0Q922.0,290.0 884.0,255.0Q846.0,220.0 781.0,220.0Q731.0,220.0 701.0,239.0Q671.0,258.0 657.5,287.0Q644.0,316.0 644.0,344.0Q644.0,369.0 650.0,388.5Q656.0,408.0 666.0,425.0L488.0,425.0Q524.0,393.0 544.5,346.0Q565.0,299.0 565.0,237.0Q565.0,163.0 533.0,106.5Q501.0,50.0 442.0,19.0Q383.0,-12.0 303.0,-12.0Q224.0,-12.0 165.5,18.5Q107.0,49.0 74.5,105.0Q42.0,161.0 42.0,236.0ZM717.0,353.0Q717.0,323.0 734.5,304.5Q752.0,286.0 785.0,286.0Q820.0,286.0 834.5,304.5Q849.0,323.0 849.0,350.0Q849.0,392.0 823.5,408.5Q798.0,425.0 752.0,425.0L743.0,425.0Q717.0,391.0 717.0,353.0ZM125.0,248.0Q125.0,167.0 170.0,117.0Q215.0,67.0 303.0,67.0Q392.0,67.0 437.0,116.5Q482.0,166.0 482.0,242.0Q482.0,293.0 462.5,334.5Q443.0,376.0 403.5,400.5Q364.0,425.0 303.0,425.0Q242.0,425.0 202.5,400.5Q163.0,376.0 144.0,336.0Q125.0,296.0 125.0,248.0Z"  transform="translate(0, 983)"/>
<path d="M239.0,425.0Q210.0,425.0 183.5,436.0Q157.0,447.0 135.0,477.5Q113.0,508.0 97.0,564.0L180.0,591.0Q195.0,536.0 209.0,518.0Q223.0,500.0 245.0,500.0Q265.0,500.0 282.5,512.5Q300.0,525.0 332.0,565.0L363.0,605.0Q397.0,649.0 425.5,675.0Q454.0,701.0 486.0,713.0Q518.0,725.0 562.0,725.0L568.0,648.0Q533.0,646.0 509.5,637.0Q486.0,628.0 466.5,608.5Q447.0,589.0 421.0,556.0L398.0,526.0Q356.0,472.0 320.0,448.5Q284.0,425.0 239.0,425.0ZM481.0,-12.0Q429.0,-12.0 392.0,10.0Q355.0,32.0 321.0,71.0Q293.0,34.0 261.0,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 438.0,75.5Q459.0,67.0 486.0,67.0Q539.0,67.0 566.0,99.0Q593.0,131.0 593.0,192.0Q593.0,268.0 553.0,319.5Q513.0,371.0 445.0,398.0Q377.0,425.0 292.0,425.0L243.0,425.0L326.0,500.0Q437.0,493.0 515.5,452.5Q594.0,412.0 635.0,345.5Q676.0,279.0 676.0,194.0Q676.0,135.0 655.0,88.0Q634.0,41.0 590.5,14.5Q547.0,-12.0 481.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM828.0,-12.0Q761.0,-12.0 710.5,22.0Q660.0,56.0 621.0,111.0L661.0,176.0Q703.0,121.0 744.5,94.0Q786.0,67.0 835.0,67.0Q886.0,67.0 913.0,99.5Q940.0,132.0 940.0,193.0Q940.0,251.0 916.5,294.5Q893.0,338.0 853.5,369.5Q814.0,401.0 764.0,423.0L801.0,500.0Q863.0,474.0 913.0,430.0Q963.0,386.0 993.0,328.0Q1023.0,270.0 1023.0,199.0Q1023.0,100.0 973.0,44.0Q923.0,-12.0 828.0,-12.0Z"  transform="translate(906, 983)"/>
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(1964, 983)"/>
<path d="M97.0,-386.0Q26.0,-386.0 -25.0,-360.0Q-76.0,-334.0 -103.0,-288.5Q-130.0,-243.0 -130.0,-186.0Q-130.0,-133.0 -108.5,-95.0Q-87.0,-57.0 -50.0,-36.0Q-13.0,-15.0 32.0,-15.0Q99.0,-15.0 130.0,-50.5Q161.0,-86.0 161.0,-131.0Q161.0,-189.0 125.0,-222.5Q89.0,-256.0 13.0,-256.0Q-17.0,-256.0 -48.0,-243.0Q-16.0,-315.0 102.0,-315.0Q140.0,-315.0 178.0,-305.5Q216.0,-296.0 248.0,-271.0Q280.0,-246.0 299.5,-200.5Q319.0,-155.0 319.0,-83.0Q319.0,-6.0 292.0,68.5Q265.0,143.0 217.5,210.0Q170.0,277.0 108.5,333.5Q47.0,390.0 -23.0,430.0L18.0,500.0Q84.0,462.0 151.0,403.0Q218.0,344.0 274.0,268.0Q330.0,192.0 364.0,103.0Q398.0,14.0 398.0,-84.0Q398.0,-190.0 358.0,-256.5Q318.0,-323.0 250.0,-354.5Q182.0,-386.0 97.0,-386.0ZM31.0,-79.0Q-8.0,-79.0 -32.0,-105.5Q-56.0,-132.0 -59.0,-175.0Q-30.0,-192.0 8.0,-192.0Q88.0,-192.0 88.0,-135.0Q88.0,-109.0 72.5,-94.0Q57.0,-79.0 31.0,-79.0Z"  transform="translate(2486, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,192.0Q593.0,250.0 570.0,293.5Q547.0,337.0 507.0,369.0Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(2886, 983)"/>
<path d="M-180.0,-386.0Q-232.0,-386.0 -259.0,-359.5Q-286.0,-333.0 -286.0,-296.0Q-286.0,-260.0 -260.0,-232.5Q-234.0,-205.0 -182.0,-205.0Q-158.0,-205.0 -139.0,-211.5Q-120.0,-218.0 -104.0,-229.0L-104.0,-229.0Q-104.0,-184.0 -126.5,-154.5Q-149.0,-125.0 -193.0,-125.0Q-226.0,-125.0 -244.0,-143.5Q-262.0,-162.0 -267.0,-184.0L-335.0,-184.0Q-341.0,-163.0 -364.5,-143.0Q-388.0,-123.0 -438.0,-123.0Q-502.0,-123.0 -502.0,-159.0Q-502.0,-174.0 -489.5,-184.0Q-477.0,-194.0 -448.0,-194.0L-386.0,-194.0L-386.0,-251.0L-438.0,-251.0Q-506.0,-251.0 -506.0,-290.0Q-506.0,-303.0 -496.0,-314.5Q-486.0,-326.0 -458.0,-326.0Q-429.0,-326.0 -410.0,-314.5Q-391.0,-303.0 -369.0,-282.0L-322.0,-324.0Q-351.0,-354.0 -383.5,-370.0Q-416.0,-386.0 -461.0,-386.0Q-521.0,-386.0 -549.5,-361.0Q-578.0,-336.0 -578.0,-300.0Q-578.0,-274.0 -563.5,-253.5Q-549.0,-233.0 -516.0,-223.0Q-547.0,-212.0 -560.0,-192.0Q-573.0,-172.0 -573.0,-147.0Q-573.0,-108.0 -538.0,-84.5Q-503.0,-61.0 -445.0,-61.0Q-394.0,-61.0 -361.5,-75.5Q-329.0,-90.0 -302.0,-118.0Q-281.0,-91.0 -254.5,-76.0Q-228.0,-61.0 -189.0,-61.0Q-116.0,-61.0 -76.5,-109.0Q-37.0,-157.0 -37.0,-228.0Q-37.0,-303.0 -73.0,-344.5Q-109.0,-386.0 -180.0,-386.0ZM-220.0,-295.0Q-220.0,-308.0 -210.0,-318.0Q-200.0,-328.0 -177.0,-328.0Q-156.0,-328.0 -139.0,-319.5Q-122.0,-311.0 -113.0,-289.0Q-125.0,-276.0 -140.5,-268.5Q-156.0,-261.0 -176.0,-261.0Q-196.0,-261.0 -208.0,-270.0Q-220.0,-279.0 -220.0,-295.0Z"  transform="translate(3532, 953)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">కార్యనిర్వాహక</span> (fontdiff-Telugu.html)</li>


<pre>Expected: kaavoweltelu=0+867|ratelu=2+593|yasubscripttelu=2+458|nivoweltelu=5+702|raavoweltelu=7+937|vasubscripttelu=7+458|hatelu=11+1040|katelu=12+522</pre>



<pre>Got     : kaavoweltelu=0+867|ratelu=2+593|yasubscripttelu=2+458|nivoweltelu=5+702|raavoweltelu=7+906|vasubscripttelu=7+458|hatelu=11+1040|katelu=12+522</pre>



<pre>                                                                                                  ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5546 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,378.0 45.0,395.0Q53.0,412.0 66.0,425.0L38.0,425.0L38.0,500.0L640.0,500.0Q705.0,500.0 741.5,492.0Q778.0,484.0 805.0,462.0Q826.0,446.0 839.0,418.5Q852.0,391.0 852.0,353.0Q852.0,290.0 814.0,255.0Q776.0,220.0 711.0,220.0Q661.0,220.0 631.0,239.0Q601.0,258.0 587.5,287.0Q574.0,316.0 574.0,344.0Q574.0,369.0 580.0,388.5Q586.0,408.0 596.0,425.0L447.0,425.0Q469.0,400.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM647.0,353.0Q647.0,323.0 664.5,304.5Q682.0,286.0 715.0,286.0Q750.0,286.0 764.5,304.5Q779.0,323.0 779.0,350.0Q779.0,392.0 753.5,408.5Q728.0,425.0 682.0,425.0L673.0,425.0Q647.0,391.0 647.0,353.0Z"  transform="translate(0, 983)"/>
<path d="M35.0,236.0Q35.0,314.0 68.0,373.5Q101.0,433.0 159.5,466.5Q218.0,500.0 296.0,500.0Q375.0,500.0 433.5,467.5Q492.0,435.0 525.0,376.0Q558.0,317.0 558.0,237.0Q558.0,163.0 526.0,106.5Q494.0,50.0 435.0,19.0Q376.0,-12.0 296.0,-12.0Q217.0,-12.0 158.5,19.0Q100.0,50.0 67.5,105.5Q35.0,161.0 35.0,236.0ZM118.0,248.0Q118.0,167.0 163.0,117.0Q208.0,67.0 296.0,67.0Q385.0,67.0 430.0,116.5Q475.0,166.0 475.0,242.0Q475.0,293.0 455.5,334.5Q436.0,376.0 396.5,400.5Q357.0,425.0 296.0,425.0Q235.0,425.0 195.5,400.5Q156.0,376.0 137.0,336.0Q118.0,296.0 118.0,248.0ZM265.0,425.0Q236.0,425.0 209.5,436.0Q183.0,447.0 161.0,477.5Q139.0,508.0 123.0,564.0L206.0,591.0Q221.0,536.0 235.0,518.0Q249.0,500.0 271.0,500.0Q291.0,500.0 308.5,512.5Q326.0,525.0 358.0,565.0L389.0,605.0Q423.0,649.0 451.5,675.0Q480.0,701.0 512.0,713.0Q544.0,725.0 588.0,725.0L594.0,648.0Q559.0,646.0 535.5,637.0Q512.0,628.0 492.5,608.5Q473.0,589.0 447.0,556.0L424.0,526.0Q382.0,472.0 346.0,448.5Q310.0,425.0 265.0,425.0Z"  transform="translate(867, 983)"/>
<path d="M174.0,-386.0Q103.0,-386.0 58.5,-368.5Q14.0,-351.0 -6.5,-322.5Q-27.0,-294.0 -27.0,-260.0Q-27.0,-223.0 -5.5,-194.5Q16.0,-166.0 82.0,-138.0Q123.0,-121.0 140.5,-108.5Q158.0,-96.0 158.0,-73.0Q158.0,-57.0 146.0,-44.0Q134.0,-31.0 99.0,-31.0Q40.0,-31.0 40.0,-72.0Q40.0,-89.0 47.0,-105.0L-23.0,-121.0Q-38.0,-89.0 -38.0,-61.0Q-38.0,-23.0 -6.0,7.0Q26.0,37.0 100.0,37.0Q150.0,37.0 179.5,20.0Q209.0,3.0 222.0,-22.0Q235.0,-47.0 235.0,-72.0Q235.0,-120.0 205.0,-146.0Q175.0,-172.0 122.0,-194.0Q77.0,-213.0 64.0,-225.5Q51.0,-238.0 51.0,-257.0Q51.0,-283.0 82.0,-298.5Q113.0,-314.0 174.0,-314.0Q229.0,-314.0 275.0,-299.0Q321.0,-284.0 349.0,-250.0Q377.0,-216.0 377.0,-159.0Q377.0,-119.0 362.0,-82.5Q347.0,-46.0 306.0,-3.0Q265.0,40.0 187.0,101.0Q111.0,160.0 70.5,213.0Q30.0,266.0 30.0,333.0Q30.0,379.0 53.0,417.0Q76.0,455.0 119.0,477.5Q162.0,500.0 222.0,500.0Q290.0,500.0 332.0,476.0Q374.0,452.0 393.5,414.0Q413.0,376.0 413.0,333.0Q413.0,295.0 400.5,263.5Q388.0,232.0 368.0,206.0L305.0,245.0Q318.0,262.0 325.5,281.5Q333.0,301.0 333.0,327.0Q333.0,368.0 306.0,398.0Q279.0,428.0 220.0,428.0Q168.0,428.0 138.5,401.5Q109.0,375.0 109.0,333.0Q109.0,283.0 155.0,238.0Q201.0,193.0 268.0,141.0Q333.0,91.0 375.0,45.0Q417.0,-1.0 437.5,-50.0Q458.0,-99.0 458.0,-158.0Q458.0,-233.0 422.5,-284.0Q387.0,-335.0 323.5,-360.5Q260.0,-386.0 174.0,-386.0Z"  transform="translate(1460, 983)"/>
<path d="M472.0,-12.0Q425.0,-12.0 390.0,3.5Q355.0,19.0 324.0,51.5Q293.0,84.0 256.0,133.0Q224.0,176.0 206.5,192.5Q189.0,209.0 164.0,209.0Q141.0,209.0 126.0,190.5Q111.0,172.0 111.0,143.0Q111.0,108.0 123.0,77.0Q135.0,46.0 159.0,14.0L78.0,-13.0Q56.0,22.0 42.5,59.5Q29.0,97.0 29.0,143.0Q29.0,204.0 67.0,245.0Q105.0,286.0 165.0,286.0Q204.0,286.0 230.5,272.5Q257.0,259.0 279.5,234.0Q302.0,209.0 328.0,175.0Q359.0,134.0 381.5,110.5Q404.0,87.0 425.5,77.0Q447.0,67.0 476.0,67.0Q530.0,67.0 556.5,104.5Q583.0,142.0 583.0,227.0Q583.0,284.0 566.0,341.0Q549.0,398.0 519.0,450.0Q489.0,502.0 447.5,542.0Q406.0,582.0 357.0,606.0Q360.0,590.0 360.0,575.0Q360.0,519.0 324.5,485.5Q289.0,452.0 226.0,452.0Q179.0,452.0 150.0,471.0Q121.0,490.0 108.0,517.5Q95.0,545.0 95.0,572.0Q95.0,635.0 140.5,668.0Q186.0,701.0 259.0,701.0Q338.0,701.0 411.0,664.5Q484.0,628.0 541.5,563.0Q599.0,498.0 632.5,412.5Q666.0,327.0 666.0,228.0Q666.0,104.0 617.0,46.0Q568.0,-12.0 472.0,-12.0ZM169.0,576.0Q169.0,551.0 183.5,536.0Q198.0,521.0 226.0,521.0Q253.0,521.0 271.0,535.0Q289.0,549.0 289.0,584.0Q289.0,608.0 279.0,630.0Q263.0,632.0 246.0,632.0Q209.0,632.0 189.0,616.0Q169.0,600.0 169.0,576.0Z"  transform="translate(1918, 983)"/>
<path d="M42.0,236.0Q42.0,297.0 62.5,345.0Q83.0,393.0 121.0,425.0L43.0,425.0L43.0,500.0L710.0,500.0Q775.0,500.0 811.5,492.0Q848.0,484.0 875.0,462.0Q896.0,446.0 909.0,418.5Q922.0,391.0 922.0,353.0Q922.0,290.0 884.0,255.0Q846.0,220.0 781.0,220.0Q731.0,220.0 701.0,239.0Q671.0,258.0 657.5,287.0Q644.0,316.0 644.0,344.0Q644.0,369.0 650.0,388.5Q656.0,408.0 666.0,425.0L488.0,425.0Q524.0,393.0 544.5,346.0Q565.0,299.0 565.0,237.0Q565.0,163.0 533.0,106.5Q501.0,50.0 442.0,19.0Q383.0,-12.0 303.0,-12.0Q224.0,-12.0 165.5,18.5Q107.0,49.0 74.5,105.0Q42.0,161.0 42.0,236.0ZM717.0,353.0Q717.0,323.0 734.5,304.5Q752.0,286.0 785.0,286.0Q820.0,286.0 834.5,304.5Q849.0,323.0 849.0,350.0Q849.0,392.0 823.5,408.5Q798.0,425.0 752.0,425.0L743.0,425.0Q717.0,391.0 717.0,353.0ZM125.0,248.0Q125.0,167.0 170.0,117.0Q215.0,67.0 303.0,67.0Q392.0,67.0 437.0,116.5Q482.0,166.0 482.0,242.0Q482.0,293.0 462.5,334.5Q443.0,376.0 403.5,400.5Q364.0,425.0 303.0,425.0Q242.0,425.0 202.5,400.5Q163.0,376.0 144.0,336.0Q125.0,296.0 125.0,248.0Z"  transform="translate(2620, 983)"/>
<path d="M279.0,-337.0Q239.0,-337.0 204.0,-321.5Q169.0,-306.0 133.0,-268.0Q110.0,-299.0 83.0,-318.0Q56.0,-337.0 5.0,-337.0Q-59.0,-337.0 -90.5,-299.5Q-122.0,-262.0 -122.0,-212.0Q-122.0,-178.0 -105.5,-151.0Q-89.0,-124.0 -61.0,-108.5Q-33.0,-93.0 1.0,-93.0Q48.0,-93.0 81.0,-115.0Q114.0,-137.0 154.0,-184.0Q192.0,-227.0 218.0,-246.5Q244.0,-266.0 284.0,-266.0Q334.0,-266.0 355.5,-234.0Q377.0,-202.0 377.0,-159.0Q377.0,-119.0 362.0,-82.5Q347.0,-46.0 306.0,-3.0Q265.0,40.0 186.0,101.0Q111.0,160.0 70.5,213.0Q30.0,266.0 30.0,333.0Q30.0,379.0 53.0,416.5Q76.0,454.0 119.0,477.0Q162.0,500.0 222.0,500.0Q290.0,500.0 332.0,476.0Q374.0,452.0 393.5,414.0Q413.0,376.0 413.0,333.0Q413.0,295.0 400.5,263.5Q388.0,232.0 368.0,206.0L305.0,245.0Q318.0,262.0 325.5,281.5Q333.0,301.0 333.0,327.0Q333.0,368.0 306.0,398.0Q279.0,428.0 220.0,428.0Q168.0,428.0 138.5,401.5Q109.0,375.0 109.0,333.0Q109.0,283.0 155.0,238.0Q201.0,193.0 268.0,141.0Q366.0,66.0 412.0,-2.5Q458.0,-71.0 458.0,-157.0Q458.0,-238.0 412.5,-287.5Q367.0,-337.0 279.0,-337.0ZM-47.0,-215.0Q-47.0,-238.0 -33.0,-254.0Q-19.0,-270.0 9.0,-270.0Q37.0,-270.0 55.0,-254.5Q73.0,-239.0 87.0,-214.0Q61.0,-183.0 44.5,-172.5Q28.0,-162.0 5.0,-162.0Q-15.0,-162.0 -31.0,-175.5Q-47.0,-189.0 -47.0,-215.0Z"  transform="translate(3526, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.0Q593.0,131.0 593.0,189.0Q593.0,244.0 569.5,288.0Q546.0,332.0 506.0,366.5Q466.0,401.0 418.0,425.0L454.0,500.0L806.0,500.0Q871.0,500.0 907.5,492.0Q944.0,484.0 971.0,462.0Q992.0,446.0 1005.0,418.5Q1018.0,391.0 1018.0,353.0Q1018.0,290.0 980.0,255.0Q942.0,220.0 877.0,220.0Q827.0,220.0 797.0,239.0Q767.0,258.0 753.5,287.0Q740.0,316.0 740.0,344.0Q740.0,369.0 746.0,388.5Q752.0,408.0 762.0,425.0L554.0,425.0Q607.0,385.0 641.5,325.5Q676.0,266.0 676.0,193.0Q676.0,98.0 626.5,43.0Q577.0,-12.0 485.0,-12.0ZM813.0,353.0Q813.0,323.0 830.5,304.5Q848.0,286.0 881.0,286.0Q916.0,286.0 930.5,304.5Q945.0,323.0 945.0,350.0Q945.0,392.0 919.5,408.5Q894.0,425.0 848.0,425.0L839.0,425.0Q813.0,391.0 813.0,353.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(3984, 983)"/>
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(5024, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5577 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,378.0 45.0,395.0Q53.0,412.0 66.0,425.0L38.0,425.0L38.0,500.0L640.0,500.0Q705.0,500.0 741.5,492.0Q778.0,484.0 805.0,462.0Q826.0,446.0 839.0,418.5Q852.0,391.0 852.0,353.0Q852.0,290.0 814.0,255.0Q776.0,220.0 711.0,220.0Q661.0,220.0 631.0,239.0Q601.0,258.0 587.5,287.0Q574.0,316.0 574.0,344.0Q574.0,369.0 580.0,388.5Q586.0,408.0 596.0,425.0L447.0,425.0Q469.0,400.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM647.0,353.0Q647.0,323.0 664.5,304.5Q682.0,286.0 715.0,286.0Q750.0,286.0 764.5,304.5Q779.0,323.0 779.0,350.0Q779.0,392.0 753.5,408.5Q728.0,425.0 682.0,425.0L673.0,425.0Q647.0,391.0 647.0,353.0Z"  transform="translate(0, 983)"/>
<path d="M35.0,236.0Q35.0,314.0 68.0,373.5Q101.0,433.0 159.5,466.5Q218.0,500.0 296.0,500.0Q375.0,500.0 433.5,467.5Q492.0,435.0 525.0,376.0Q558.0,317.0 558.0,237.0Q558.0,163.0 526.0,106.5Q494.0,50.0 435.0,19.0Q376.0,-12.0 296.0,-12.0Q217.0,-12.0 158.5,19.0Q100.0,50.0 67.5,105.5Q35.0,161.0 35.0,236.0ZM118.0,248.0Q118.0,167.0 163.0,117.0Q208.0,67.0 296.0,67.0Q385.0,67.0 430.0,116.5Q475.0,166.0 475.0,242.0Q475.0,293.0 455.5,334.5Q436.0,376.0 396.5,400.5Q357.0,425.0 296.0,425.0Q235.0,425.0 195.5,400.5Q156.0,376.0 137.0,336.0Q118.0,296.0 118.0,248.0ZM265.0,425.0Q236.0,425.0 209.5,436.0Q183.0,447.0 161.0,477.5Q139.0,508.0 123.0,564.0L206.0,591.0Q221.0,536.0 235.0,518.0Q249.0,500.0 271.0,500.0Q291.0,500.0 308.5,512.5Q326.0,525.0 358.0,565.0L389.0,605.0Q423.0,649.0 451.5,675.0Q480.0,701.0 512.0,713.0Q544.0,725.0 588.0,725.0L594.0,648.0Q559.0,646.0 535.5,637.0Q512.0,628.0 492.5,608.5Q473.0,589.0 447.0,556.0L424.0,526.0Q382.0,472.0 346.0,448.5Q310.0,425.0 265.0,425.0Z"  transform="translate(867, 983)"/>
<path d="M174.0,-386.0Q103.0,-386.0 58.5,-368.5Q14.0,-351.0 -6.5,-322.5Q-27.0,-294.0 -27.0,-260.0Q-27.0,-223.0 -5.5,-194.5Q16.0,-166.0 82.0,-138.0Q123.0,-121.0 140.5,-108.5Q158.0,-96.0 158.0,-73.0Q158.0,-57.0 146.0,-44.0Q134.0,-31.0 99.0,-31.0Q40.0,-31.0 40.0,-72.0Q40.0,-89.0 47.0,-105.0L-23.0,-121.0Q-38.0,-89.0 -38.0,-61.0Q-38.0,-23.0 -6.0,7.0Q26.0,37.0 100.0,37.0Q150.0,37.0 179.5,20.0Q209.0,3.0 222.0,-22.0Q235.0,-47.0 235.0,-72.0Q235.0,-120.0 205.0,-146.0Q175.0,-172.0 122.0,-194.0Q77.0,-213.0 64.0,-225.5Q51.0,-238.0 51.0,-257.0Q51.0,-283.0 82.0,-298.5Q113.0,-314.0 174.0,-314.0Q229.0,-314.0 275.0,-299.0Q321.0,-284.0 349.0,-250.0Q377.0,-216.0 377.0,-159.0Q377.0,-119.0 362.0,-82.5Q347.0,-46.0 306.0,-3.0Q265.0,40.0 187.0,101.0Q111.0,160.0 70.5,213.0Q30.0,266.0 30.0,333.0Q30.0,379.0 53.0,417.0Q76.0,455.0 119.0,477.5Q162.0,500.0 222.0,500.0Q290.0,500.0 332.0,476.0Q374.0,452.0 393.5,414.0Q413.0,376.0 413.0,333.0Q413.0,295.0 400.5,263.5Q388.0,232.0 368.0,206.0L305.0,245.0Q318.0,262.0 325.5,281.5Q333.0,301.0 333.0,327.0Q333.0,368.0 306.0,398.0Q279.0,428.0 220.0,428.0Q168.0,428.0 138.5,401.5Q109.0,375.0 109.0,333.0Q109.0,283.0 155.0,238.0Q201.0,193.0 268.0,141.0Q333.0,91.0 375.0,45.0Q417.0,-1.0 437.5,-50.0Q458.0,-99.0 458.0,-158.0Q458.0,-233.0 422.5,-284.0Q387.0,-335.0 323.5,-360.5Q260.0,-386.0 174.0,-386.0Z"  transform="translate(1460, 983)"/>
<path d="M472.0,-12.0Q425.0,-12.0 390.0,3.5Q355.0,19.0 324.0,51.5Q293.0,84.0 256.0,133.0Q224.0,176.0 206.5,192.5Q189.0,209.0 164.0,209.0Q141.0,209.0 126.0,190.5Q111.0,172.0 111.0,143.0Q111.0,108.0 123.0,77.0Q135.0,46.0 159.0,14.0L78.0,-13.0Q56.0,22.0 42.5,59.5Q29.0,97.0 29.0,143.0Q29.0,204.0 67.0,245.0Q105.0,286.0 165.0,286.0Q204.0,286.0 230.5,272.5Q257.0,259.0 279.5,234.0Q302.0,209.0 328.0,175.0Q359.0,134.0 381.5,110.5Q404.0,87.0 425.5,77.0Q447.0,67.0 476.0,67.0Q530.0,67.0 556.5,104.5Q583.0,142.0 583.0,227.0Q583.0,284.0 566.0,341.0Q549.0,398.0 519.0,450.0Q489.0,502.0 447.5,542.0Q406.0,582.0 357.0,606.0Q360.0,590.0 360.0,575.0Q360.0,519.0 324.5,485.5Q289.0,452.0 226.0,452.0Q179.0,452.0 150.0,471.0Q121.0,490.0 108.0,517.5Q95.0,545.0 95.0,572.0Q95.0,635.0 140.5,668.0Q186.0,701.0 259.0,701.0Q338.0,701.0 411.0,664.5Q484.0,628.0 541.5,563.0Q599.0,498.0 632.5,412.5Q666.0,327.0 666.0,228.0Q666.0,104.0 617.0,46.0Q568.0,-12.0 472.0,-12.0ZM169.0,576.0Q169.0,551.0 183.5,536.0Q198.0,521.0 226.0,521.0Q253.0,521.0 271.0,535.0Q289.0,549.0 289.0,584.0Q289.0,608.0 279.0,630.0Q263.0,632.0 246.0,632.0Q209.0,632.0 189.0,616.0Q169.0,600.0 169.0,576.0Z"  transform="translate(1918, 983)"/>
<path d="M42.0,236.0Q42.0,297.0 62.5,345.0Q83.0,393.0 121.0,425.0L43.0,425.0L43.0,500.0L710.0,500.0Q775.0,500.0 811.5,492.0Q848.0,484.0 875.0,462.0Q896.0,446.0 909.0,418.5Q922.0,391.0 922.0,353.0Q922.0,290.0 884.0,255.0Q846.0,220.0 781.0,220.0Q731.0,220.0 701.0,239.0Q671.0,258.0 657.5,287.0Q644.0,316.0 644.0,344.0Q644.0,369.0 650.0,388.5Q656.0,408.0 666.0,425.0L488.0,425.0Q524.0,393.0 544.5,346.0Q565.0,299.0 565.0,237.0Q565.0,163.0 533.0,106.5Q501.0,50.0 442.0,19.0Q383.0,-12.0 303.0,-12.0Q224.0,-12.0 165.5,18.5Q107.0,49.0 74.5,105.0Q42.0,161.0 42.0,236.0ZM717.0,353.0Q717.0,323.0 734.5,304.5Q752.0,286.0 785.0,286.0Q820.0,286.0 834.5,304.5Q849.0,323.0 849.0,350.0Q849.0,392.0 823.5,408.5Q798.0,425.0 752.0,425.0L743.0,425.0Q717.0,391.0 717.0,353.0ZM125.0,248.0Q125.0,167.0 170.0,117.0Q215.0,67.0 303.0,67.0Q392.0,67.0 437.0,116.5Q482.0,166.0 482.0,242.0Q482.0,293.0 462.5,334.5Q443.0,376.0 403.5,400.5Q364.0,425.0 303.0,425.0Q242.0,425.0 202.5,400.5Q163.0,376.0 144.0,336.0Q125.0,296.0 125.0,248.0Z"  transform="translate(2620, 983)"/>
<path d="M279.0,-337.0Q239.0,-337.0 204.0,-321.5Q169.0,-306.0 133.0,-268.0Q110.0,-299.0 83.0,-318.0Q56.0,-337.0 5.0,-337.0Q-59.0,-337.0 -90.5,-299.5Q-122.0,-262.0 -122.0,-212.0Q-122.0,-178.0 -105.5,-151.0Q-89.0,-124.0 -61.0,-108.5Q-33.0,-93.0 1.0,-93.0Q48.0,-93.0 81.0,-115.0Q114.0,-137.0 154.0,-184.0Q192.0,-227.0 218.0,-246.5Q244.0,-266.0 284.0,-266.0Q334.0,-266.0 355.5,-234.0Q377.0,-202.0 377.0,-159.0Q377.0,-119.0 362.0,-82.5Q347.0,-46.0 306.0,-3.0Q265.0,40.0 186.0,101.0Q111.0,160.0 70.5,213.0Q30.0,266.0 30.0,333.0Q30.0,379.0 53.0,416.5Q76.0,454.0 119.0,477.0Q162.0,500.0 222.0,500.0Q290.0,500.0 332.0,476.0Q374.0,452.0 393.5,414.0Q413.0,376.0 413.0,333.0Q413.0,295.0 400.5,263.5Q388.0,232.0 368.0,206.0L305.0,245.0Q318.0,262.0 325.5,281.5Q333.0,301.0 333.0,327.0Q333.0,368.0 306.0,398.0Q279.0,428.0 220.0,428.0Q168.0,428.0 138.5,401.5Q109.0,375.0 109.0,333.0Q109.0,283.0 155.0,238.0Q201.0,193.0 268.0,141.0Q366.0,66.0 412.0,-2.5Q458.0,-71.0 458.0,-157.0Q458.0,-238.0 412.5,-287.5Q367.0,-337.0 279.0,-337.0ZM-47.0,-215.0Q-47.0,-238.0 -33.0,-254.0Q-19.0,-270.0 9.0,-270.0Q37.0,-270.0 55.0,-254.5Q73.0,-239.0 87.0,-214.0Q61.0,-183.0 44.5,-172.5Q28.0,-162.0 5.0,-162.0Q-15.0,-162.0 -31.0,-175.5Q-47.0,-189.0 -47.0,-215.0Z"  transform="translate(3557, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.0Q593.0,131.0 593.0,189.0Q593.0,244.0 569.5,288.0Q546.0,332.0 506.0,366.5Q466.0,401.0 418.0,425.0L454.0,500.0L806.0,500.0Q871.0,500.0 907.5,492.0Q944.0,484.0 971.0,462.0Q992.0,446.0 1005.0,418.5Q1018.0,391.0 1018.0,353.0Q1018.0,290.0 980.0,255.0Q942.0,220.0 877.0,220.0Q827.0,220.0 797.0,239.0Q767.0,258.0 753.5,287.0Q740.0,316.0 740.0,344.0Q740.0,369.0 746.0,388.5Q752.0,408.0 762.0,425.0L554.0,425.0Q607.0,385.0 641.5,325.5Q676.0,266.0 676.0,193.0Q676.0,98.0 626.5,43.0Q577.0,-12.0 485.0,-12.0ZM813.0,353.0Q813.0,323.0 830.5,304.5Q848.0,286.0 881.0,286.0Q916.0,286.0 930.5,304.5Q945.0,323.0 945.0,350.0Q945.0,392.0 919.5,408.5Q894.0,425.0 848.0,425.0L839.0,425.0Q813.0,391.0 813.0,353.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(4015, 983)"/>
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(5055, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">కష్గౄత్ᳲ॑దౄ</span> (Added by SIESTA)</li>


<pre>Expected: katelu=0+522|ssatelu=1+713|gasubscripttelu=1@-156,-30+0|rrvocalicvowelsign1telu=1+801|tahalanttelu=5+778|uni0951=7@-103,293+0|uni1CF2=7+471|datelu=9+679|rrvocalicvowelsigntelu=9+656</pre>



<pre>Got     : katelu=0+522|ssatelu=1+713|gasubscripttelu=1@-156,0+0|rrvocalicvowelsign1telu=1+801|tahalanttelu=5+778|uni0951=7@-103,293+0|uni1CF2=7+471|datelu=9+679|rrvocalicvowelsigntelu=9+656</pre>



<pre>                                                            ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4620 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,192.0Q593.0,250.0 570.0,293.5Q547.0,337.0 507.0,369.0Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(522, 983)"/>
<path d="M-214.0,-61.0Q-132.0,-61.0 -84.5,-106.0Q-37.0,-151.0 -37.0,-223.0Q-37.0,-281.0 -54.5,-319.0Q-72.0,-357.0 -92.0,-386.0L-159.0,-357.0Q-138.0,-331.0 -123.0,-299.5Q-108.0,-268.0 -108.0,-231.0Q-108.0,-187.0 -132.0,-156.0Q-156.0,-125.0 -218.0,-125.0Q-267.0,-125.0 -296.0,-153.0Q-325.0,-181.0 -325.0,-230.0Q-325.0,-266.0 -310.0,-298.5Q-295.0,-331.0 -273.0,-357.0L-340.0,-386.0Q-364.0,-353.0 -380.0,-312.5Q-396.0,-272.0 -396.0,-226.0Q-396.0,-182.0 -375.5,-144.5Q-355.0,-107.0 -314.5,-84.0Q-274.0,-61.0 -214.0,-61.0Z"  transform="translate(1079, 983)"/>
<path d="M240.0,-451.0Q169.0,-451.0 118.5,-425.0Q68.0,-399.0 41.5,-353.5Q15.0,-308.0 15.0,-251.0Q15.0,-198.0 36.5,-160.0Q58.0,-122.0 95.0,-101.0Q132.0,-80.0 177.0,-80.0Q244.0,-80.0 275.0,-115.5Q306.0,-151.0 306.0,-196.0Q306.0,-254.0 270.0,-287.5Q234.0,-321.0 158.0,-321.0Q128.0,-321.0 97.0,-309.0Q112.0,-343.0 149.0,-361.5Q186.0,-380.0 245.0,-380.0Q283.0,-380.0 321.5,-370.5Q360.0,-361.0 392.5,-336.0Q425.0,-311.0 444.5,-265.5Q464.0,-220.0 464.0,-148.0Q464.0,-70.0 437.5,2.5Q411.0,75.0 365.5,140.5Q320.0,206.0 261.5,260.0Q203.0,314.0 140.0,354.0L169.0,435.0L575.0,435.0Q640.0,435.0 676.5,427.0Q713.0,419.0 740.0,397.0Q761.0,381.0 774.0,353.5Q787.0,326.0 787.0,288.0Q787.0,225.0 749.0,190.0Q711.0,155.0 646.0,155.0Q596.0,155.0 566.0,174.0Q536.0,193.0 522.5,222.0Q509.0,251.0 509.0,279.0Q509.0,303.0 515.0,323.0Q521.0,343.0 531.0,360.0L338.0,360.0Q300.0,360.0 249.0,362.0Q306.0,323.0 358.5,269.0Q411.0,215.0 453.0,149.0Q495.0,83.0 519.0,7.5Q543.0,-68.0 543.0,-149.0Q543.0,-255.0 502.5,-321.5Q462.0,-388.0 393.5,-419.5Q325.0,-451.0 240.0,-451.0ZM582.0,288.0Q582.0,258.0 599.5,239.5Q617.0,221.0 650.0,221.0Q685.0,221.0 699.5,239.5Q714.0,258.0 714.0,285.0Q714.0,328.0 688.5,344.0Q663.0,360.0 617.0,360.0L608.0,360.0Q582.0,325.0 582.0,288.0ZM176.0,-144.0Q137.0,-144.0 113.0,-170.5Q89.0,-197.0 86.0,-240.0Q115.0,-257.0 153.0,-257.0Q233.0,-257.0 233.0,-200.0Q233.0,-174.0 217.5,-159.0Q202.0,-144.0 176.0,-144.0Z"  transform="translate(1235, 983)"/>
<path d="M394.0,-12.0Q273.0,-12.0 193.5,20.5Q114.0,53.0 75.0,109.5Q36.0,166.0 36.0,237.0Q36.0,293.0 59.5,335.5Q83.0,378.0 124.0,401.5Q165.0,425.0 218.0,425.0Q281.0,425.0 316.5,391.0Q352.0,357.0 352.0,301.0Q352.0,240.0 310.5,203.5Q269.0,167.0 194.0,167.0Q173.0,167.0 155.0,170.5Q137.0,174.0 120.0,181.0Q146.0,124.0 217.0,95.5Q288.0,67.0 389.0,67.0Q479.0,67.0 535.0,86.5Q591.0,106.0 621.0,136.5Q651.0,167.0 661.0,200.0Q642.0,184.0 618.5,175.5Q595.0,167.0 563.0,167.0Q505.0,167.0 468.0,200.5Q431.0,234.0 431.0,293.0Q431.0,347.0 466.0,378.5Q501.0,410.0 558.0,410.0Q561.0,410.0 563.0,410.0Q542.0,418.0 516.0,425.0L466.0,425.0Q386.0,425.0 342.5,452.5Q299.0,480.0 299.0,540.0Q299.0,592.0 347.0,627.0Q291.0,664.0 291.0,724.0Q291.0,751.0 301.0,771.0Q311.0,791.0 329.0,805.0Q350.0,822.0 383.5,830.0Q417.0,838.0 486.0,838.0L773.0,838.0L773.0,763.0L470.0,763.0Q436.0,763.0 421.0,761.0Q406.0,759.0 397.0,754.0Q374.0,743.0 374.0,717.0Q374.0,689.0 395.0,678.0Q405.0,673.0 421.5,670.5Q438.0,668.0 469.0,668.0L606.0,668.0L606.0,593.0L465.0,593.0Q437.0,593.0 421.5,589.5Q406.0,586.0 398.0,580.0Q382.0,568.0 382.0,546.0Q382.0,522.0 398.0,511.0Q407.0,504.0 421.0,502.0Q435.0,500.0 457.0,500.0L509.0,500.0Q619.0,466.0 681.0,406.0Q743.0,346.0 743.0,245.0Q743.0,172.0 706.5,113.5Q670.0,55.0 593.0,21.5Q516.0,-12.0 394.0,-12.0ZM510.0,293.0Q510.0,271.0 526.0,254.0Q542.0,237.0 576.0,237.0Q611.0,237.0 632.5,254.0Q654.0,271.0 664.0,300.0Q653.0,323.0 630.5,338.5Q608.0,354.0 576.0,354.0Q551.0,354.0 530.5,339.5Q510.0,325.0 510.0,293.0ZM213.0,354.0Q171.0,354.0 142.0,327.0Q113.0,300.0 109.0,258.0Q125.0,248.0 143.0,242.5Q161.0,237.0 182.0,237.0Q231.0,237.0 251.5,255.0Q272.0,273.0 272.0,301.0Q272.0,327.0 256.5,340.5Q241.0,354.0 213.0,354.0Z"  transform="translate(2036, 983)"/>
<path d="M-250.0,599.0L-322.0,599.0L-322.0,810.0L-250.0,810.0L-250.0,599.0Z"  transform="translate(2711, 1276)"/>
<path d="M236.0,246.0Q161.0,246.0 110.5,287.0Q60.0,328.0 25.0,427.0L104.0,454.0Q128.0,385.0 157.5,354.5Q187.0,324.0 235.0,324.0Q284.0,324.0 313.5,354.5Q343.0,385.0 367.0,454.0L446.0,427.0Q412.0,328.0 361.5,287.0Q311.0,246.0 236.0,246.0ZM235.0,204.0Q310.0,204.0 361.0,163.0Q412.0,122.0 446.0,23.0L367.0,-4.0Q343.0,65.0 313.5,95.5Q284.0,126.0 236.0,126.0Q187.0,126.0 157.5,95.5Q128.0,65.0 104.0,-4.0L25.0,23.0Q60.0,122.0 110.5,163.0Q161.0,204.0 235.0,204.0Z"  transform="translate(2814, 983)"/>
<path d="M504.0,-12.0Q452.0,-12.0 416.5,7.5Q381.0,27.0 352.0,74.0Q321.0,20.0 282.0,4.0Q243.0,-12.0 198.0,-12.0Q125.0,-12.0 80.0,44.0Q35.0,100.0 35.0,200.0Q35.0,289.0 74.0,356.5Q113.0,424.0 185.0,462.0Q257.0,500.0 357.0,500.0Q457.0,500.0 527.0,461.5Q597.0,423.0 634.0,355.5Q671.0,288.0 671.0,200.0Q671.0,97.0 626.0,42.5Q581.0,-12.0 504.0,-12.0ZM496.0,67.0Q538.0,67.0 563.0,98.0Q588.0,129.0 588.0,202.0Q588.0,267.0 563.5,317.0Q539.0,367.0 489.5,396.0Q440.0,425.0 364.0,425.0L349.0,425.0Q237.0,425.0 177.5,364.0Q118.0,303.0 118.0,205.0Q118.0,130.0 142.5,98.5Q167.0,67.0 210.0,67.0Q255.0,67.0 282.5,99.5Q310.0,132.0 314.0,185.0L392.0,185.0Q396.0,124.0 427.5,95.5Q459.0,67.0 496.0,67.0ZM323.0,425.0Q294.0,425.0 267.5,436.0Q241.0,447.0 219.0,477.5Q197.0,508.0 181.0,564.0L264.0,591.0Q279.0,536.0 293.0,518.0Q307.0,500.0 329.0,500.0Q349.0,500.0 366.5,512.5Q384.0,525.0 416.0,565.0L447.0,605.0Q481.0,649.0 509.5,675.0Q538.0,701.0 570.0,713.0Q602.0,725.0 646.0,725.0L652.0,648.0Q617.0,646.0 593.5,637.0Q570.0,628.0 550.5,608.5Q531.0,589.0 505.0,556.0L482.0,526.0Q440.0,472.0 404.0,448.5Q368.0,425.0 323.0,425.0Z"  transform="translate(3285, 983)"/>
<path d="M95.0,-386.0Q24.0,-386.0 -26.5,-360.0Q-77.0,-334.0 -103.5,-288.5Q-130.0,-243.0 -130.0,-186.0Q-130.0,-133.0 -108.5,-95.0Q-87.0,-57.0 -50.0,-36.0Q-13.0,-15.0 32.0,-15.0Q99.0,-15.0 130.0,-50.5Q161.0,-86.0 161.0,-131.0Q161.0,-189.0 125.0,-222.5Q89.0,-256.0 13.0,-256.0Q-17.0,-256.0 -48.0,-244.0Q-33.0,-278.0 4.0,-296.5Q41.0,-315.0 100.0,-315.0Q138.0,-315.0 176.5,-305.5Q215.0,-296.0 247.5,-271.0Q280.0,-246.0 299.5,-200.5Q319.0,-155.0 319.0,-83.0Q319.0,-5.0 292.5,67.5Q266.0,140.0 220.5,205.5Q175.0,271.0 116.5,325.0Q58.0,379.0 -5.0,419.0L24.0,500.0L430.0,500.0Q495.0,500.0 531.5,492.0Q568.0,484.0 595.0,462.0Q616.0,446.0 629.0,418.5Q642.0,391.0 642.0,353.0Q642.0,290.0 604.0,255.0Q566.0,220.0 501.0,220.0Q451.0,220.0 421.0,239.0Q391.0,258.0 377.5,287.0Q364.0,316.0 364.0,344.0Q364.0,368.0 370.0,388.0Q376.0,408.0 386.0,425.0L193.0,425.0Q155.0,425.0 104.0,427.0Q161.0,388.0 213.5,334.0Q266.0,280.0 308.0,214.0Q350.0,148.0 374.0,72.5Q398.0,-3.0 398.0,-84.0Q398.0,-190.0 357.5,-256.5Q317.0,-323.0 248.5,-354.5Q180.0,-386.0 95.0,-386.0ZM437.0,353.0Q437.0,323.0 454.5,304.5Q472.0,286.0 505.0,286.0Q540.0,286.0 554.5,304.5Q569.0,323.0 569.0,350.0Q569.0,393.0 543.5,409.0Q518.0,425.0 472.0,425.0L463.0,425.0Q437.0,390.0 437.0,353.0ZM31.0,-79.0Q-8.0,-79.0 -32.0,-105.5Q-56.0,-132.0 -59.0,-175.0Q-30.0,-192.0 8.0,-192.0Q88.0,-192.0 88.0,-135.0Q88.0,-109.0 72.5,-94.0Q57.0,-79.0 31.0,-79.0Z"  transform="translate(3964, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4620 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M264.0,-12.0Q167.0,-12.0 101.5,28.0Q36.0,68.0 18.0,146.0L104.0,169.0Q118.0,123.0 153.5,95.0Q189.0,67.0 267.0,67.0Q346.0,67.0 377.0,87.5Q408.0,108.0 408.0,141.0Q408.0,171.0 384.5,190.0Q361.0,209.0 297.0,213.0L232.0,218.0Q180.0,222.0 142.5,230.5Q105.0,239.0 81.0,258.0Q60.0,274.0 48.5,298.5Q37.0,323.0 37.0,357.0Q37.0,419.0 90.5,459.5Q144.0,500.0 252.0,500.0Q318.0,500.0 362.5,487.5Q407.0,475.0 436.5,444.5Q466.0,414.0 484.0,360.0L398.0,338.0Q385.0,382.0 353.0,403.5Q321.0,425.0 252.0,425.0Q176.0,425.0 148.0,406.0Q120.0,387.0 120.0,358.0Q120.0,331.0 142.5,315.5Q165.0,300.0 231.0,295.0L308.0,290.0Q360.0,286.0 392.5,275.0Q425.0,264.0 446.0,247.0Q469.0,228.0 480.0,201.0Q491.0,174.0 491.0,142.0Q491.0,67.0 434.0,27.5Q377.0,-12.0 264.0,-12.0ZM234.0,425.0Q205.0,425.0 178.5,436.0Q152.0,447.0 130.0,477.5Q108.0,508.0 92.0,564.0L175.0,591.0Q190.0,536.0 204.0,518.0Q218.0,500.0 240.0,500.0Q260.0,500.0 277.5,512.5Q295.0,525.0 327.0,565.0L358.0,605.0Q392.0,649.0 420.5,675.0Q449.0,701.0 481.0,713.0Q513.0,725.0 557.0,725.0L563.0,648.0Q528.0,646.0 504.5,637.0Q481.0,628.0 461.5,608.5Q442.0,589.0 416.0,556.0L393.0,526.0Q351.0,472.0 315.0,448.5Q279.0,425.0 234.0,425.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,192.0Q593.0,250.0 570.0,293.5Q547.0,337.0 507.0,369.0Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(522, 983)"/>
<path d="M-214.0,-61.0Q-132.0,-61.0 -84.5,-106.0Q-37.0,-151.0 -37.0,-223.0Q-37.0,-281.0 -54.5,-319.0Q-72.0,-357.0 -92.0,-386.0L-159.0,-357.0Q-138.0,-331.0 -123.0,-299.5Q-108.0,-268.0 -108.0,-231.0Q-108.0,-187.0 -132.0,-156.0Q-156.0,-125.0 -218.0,-125.0Q-267.0,-125.0 -296.0,-153.0Q-325.0,-181.0 -325.0,-230.0Q-325.0,-266.0 -310.0,-298.5Q-295.0,-331.0 -273.0,-357.0L-340.0,-386.0Q-364.0,-353.0 -380.0,-312.5Q-396.0,-272.0 -396.0,-226.0Q-396.0,-182.0 -375.5,-144.5Q-355.0,-107.0 -314.5,-84.0Q-274.0,-61.0 -214.0,-61.0Z"  transform="translate(1079, 953)"/>
<path d="M240.0,-451.0Q169.0,-451.0 118.5,-425.0Q68.0,-399.0 41.5,-353.5Q15.0,-308.0 15.0,-251.0Q15.0,-198.0 36.5,-160.0Q58.0,-122.0 95.0,-101.0Q132.0,-80.0 177.0,-80.0Q244.0,-80.0 275.0,-115.5Q306.0,-151.0 306.0,-196.0Q306.0,-254.0 270.0,-287.5Q234.0,-321.0 158.0,-321.0Q128.0,-321.0 97.0,-309.0Q112.0,-343.0 149.0,-361.5Q186.0,-380.0 245.0,-380.0Q283.0,-380.0 321.5,-370.5Q360.0,-361.0 392.5,-336.0Q425.0,-311.0 444.5,-265.5Q464.0,-220.0 464.0,-148.0Q464.0,-70.0 437.5,2.5Q411.0,75.0 365.5,140.5Q320.0,206.0 261.5,260.0Q203.0,314.0 140.0,354.0L169.0,435.0L575.0,435.0Q640.0,435.0 676.5,427.0Q713.0,419.0 740.0,397.0Q761.0,381.0 774.0,353.5Q787.0,326.0 787.0,288.0Q787.0,225.0 749.0,190.0Q711.0,155.0 646.0,155.0Q596.0,155.0 566.0,174.0Q536.0,193.0 522.5,222.0Q509.0,251.0 509.0,279.0Q509.0,303.0 515.0,323.0Q521.0,343.0 531.0,360.0L338.0,360.0Q300.0,360.0 249.0,362.0Q306.0,323.0 358.5,269.0Q411.0,215.0 453.0,149.0Q495.0,83.0 519.0,7.5Q543.0,-68.0 543.0,-149.0Q543.0,-255.0 502.5,-321.5Q462.0,-388.0 393.5,-419.5Q325.0,-451.0 240.0,-451.0ZM582.0,288.0Q582.0,258.0 599.5,239.5Q617.0,221.0 650.0,221.0Q685.0,221.0 699.5,239.5Q714.0,258.0 714.0,285.0Q714.0,328.0 688.5,344.0Q663.0,360.0 617.0,360.0L608.0,360.0Q582.0,325.0 582.0,288.0ZM176.0,-144.0Q137.0,-144.0 113.0,-170.5Q89.0,-197.0 86.0,-240.0Q115.0,-257.0 153.0,-257.0Q233.0,-257.0 233.0,-200.0Q233.0,-174.0 217.5,-159.0Q202.0,-144.0 176.0,-144.0Z"  transform="translate(1235, 983)"/>
<path d="M394.0,-12.0Q273.0,-12.0 193.5,20.5Q114.0,53.0 75.0,109.5Q36.0,166.0 36.0,237.0Q36.0,293.0 59.5,335.5Q83.0,378.0 124.0,401.5Q165.0,425.0 218.0,425.0Q281.0,425.0 316.5,391.0Q352.0,357.0 352.0,301.0Q352.0,240.0 310.5,203.5Q269.0,167.0 194.0,167.0Q173.0,167.0 155.0,170.5Q137.0,174.0 120.0,181.0Q146.0,124.0 217.0,95.5Q288.0,67.0 389.0,67.0Q479.0,67.0 535.0,86.5Q591.0,106.0 621.0,136.5Q651.0,167.0 661.0,200.0Q642.0,184.0 618.5,175.5Q595.0,167.0 563.0,167.0Q505.0,167.0 468.0,200.5Q431.0,234.0 431.0,293.0Q431.0,347.0 466.0,378.5Q501.0,410.0 558.0,410.0Q561.0,410.0 563.0,410.0Q542.0,418.0 516.0,425.0L466.0,425.0Q386.0,425.0 342.5,452.5Q299.0,480.0 299.0,540.0Q299.0,592.0 347.0,627.0Q291.0,664.0 291.0,724.0Q291.0,751.0 301.0,771.0Q311.0,791.0 329.0,805.0Q350.0,822.0 383.5,830.0Q417.0,838.0 486.0,838.0L773.0,838.0L773.0,763.0L470.0,763.0Q436.0,763.0 421.0,761.0Q406.0,759.0 397.0,754.0Q374.0,743.0 374.0,717.0Q374.0,689.0 395.0,678.0Q405.0,673.0 421.5,670.5Q438.0,668.0 469.0,668.0L606.0,668.0L606.0,593.0L465.0,593.0Q437.0,593.0 421.5,589.5Q406.0,586.0 398.0,580.0Q382.0,568.0 382.0,546.0Q382.0,522.0 398.0,511.0Q407.0,504.0 421.0,502.0Q435.0,500.0 457.0,500.0L509.0,500.0Q619.0,466.0 681.0,406.0Q743.0,346.0 743.0,245.0Q743.0,172.0 706.5,113.5Q670.0,55.0 593.0,21.5Q516.0,-12.0 394.0,-12.0ZM510.0,293.0Q510.0,271.0 526.0,254.0Q542.0,237.0 576.0,237.0Q611.0,237.0 632.5,254.0Q654.0,271.0 664.0,300.0Q653.0,323.0 630.5,338.5Q608.0,354.0 576.0,354.0Q551.0,354.0 530.5,339.5Q510.0,325.0 510.0,293.0ZM213.0,354.0Q171.0,354.0 142.0,327.0Q113.0,300.0 109.0,258.0Q125.0,248.0 143.0,242.5Q161.0,237.0 182.0,237.0Q231.0,237.0 251.5,255.0Q272.0,273.0 272.0,301.0Q272.0,327.0 256.5,340.5Q241.0,354.0 213.0,354.0Z"  transform="translate(2036, 983)"/>
<path d="M-250.0,599.0L-322.0,599.0L-322.0,810.0L-250.0,810.0L-250.0,599.0Z"  transform="translate(2711, 1276)"/>
<path d="M236.0,246.0Q161.0,246.0 110.5,287.0Q60.0,328.0 25.0,427.0L104.0,454.0Q128.0,385.0 157.5,354.5Q187.0,324.0 235.0,324.0Q284.0,324.0 313.5,354.5Q343.0,385.0 367.0,454.0L446.0,427.0Q412.0,328.0 361.5,287.0Q311.0,246.0 236.0,246.0ZM235.0,204.0Q310.0,204.0 361.0,163.0Q412.0,122.0 446.0,23.0L367.0,-4.0Q343.0,65.0 313.5,95.5Q284.0,126.0 236.0,126.0Q187.0,126.0 157.5,95.5Q128.0,65.0 104.0,-4.0L25.0,23.0Q60.0,122.0 110.5,163.0Q161.0,204.0 235.0,204.0Z"  transform="translate(2814, 983)"/>
<path d="M504.0,-12.0Q452.0,-12.0 416.5,7.5Q381.0,27.0 352.0,74.0Q321.0,20.0 282.0,4.0Q243.0,-12.0 198.0,-12.0Q125.0,-12.0 80.0,44.0Q35.0,100.0 35.0,200.0Q35.0,289.0 74.0,356.5Q113.0,424.0 185.0,462.0Q257.0,500.0 357.0,500.0Q457.0,500.0 527.0,461.5Q597.0,423.0 634.0,355.5Q671.0,288.0 671.0,200.0Q671.0,97.0 626.0,42.5Q581.0,-12.0 504.0,-12.0ZM496.0,67.0Q538.0,67.0 563.0,98.0Q588.0,129.0 588.0,202.0Q588.0,267.0 563.5,317.0Q539.0,367.0 489.5,396.0Q440.0,425.0 364.0,425.0L349.0,425.0Q237.0,425.0 177.5,364.0Q118.0,303.0 118.0,205.0Q118.0,130.0 142.5,98.5Q167.0,67.0 210.0,67.0Q255.0,67.0 282.5,99.5Q310.0,132.0 314.0,185.0L392.0,185.0Q396.0,124.0 427.5,95.5Q459.0,67.0 496.0,67.0ZM323.0,425.0Q294.0,425.0 267.5,436.0Q241.0,447.0 219.0,477.5Q197.0,508.0 181.0,564.0L264.0,591.0Q279.0,536.0 293.0,518.0Q307.0,500.0 329.0,500.0Q349.0,500.0 366.5,512.5Q384.0,525.0 416.0,565.0L447.0,605.0Q481.0,649.0 509.5,675.0Q538.0,701.0 570.0,713.0Q602.0,725.0 646.0,725.0L652.0,648.0Q617.0,646.0 593.5,637.0Q570.0,628.0 550.5,608.5Q531.0,589.0 505.0,556.0L482.0,526.0Q440.0,472.0 404.0,448.5Q368.0,425.0 323.0,425.0Z"  transform="translate(3285, 983)"/>
<path d="M95.0,-386.0Q24.0,-386.0 -26.5,-360.0Q-77.0,-334.0 -103.5,-288.5Q-130.0,-243.0 -130.0,-186.0Q-130.0,-133.0 -108.5,-95.0Q-87.0,-57.0 -50.0,-36.0Q-13.0,-15.0 32.0,-15.0Q99.0,-15.0 130.0,-50.5Q161.0,-86.0 161.0,-131.0Q161.0,-189.0 125.0,-222.5Q89.0,-256.0 13.0,-256.0Q-17.0,-256.0 -48.0,-244.0Q-33.0,-278.0 4.0,-296.5Q41.0,-315.0 100.0,-315.0Q138.0,-315.0 176.5,-305.5Q215.0,-296.0 247.5,-271.0Q280.0,-246.0 299.5,-200.5Q319.0,-155.0 319.0,-83.0Q319.0,-5.0 292.5,67.5Q266.0,140.0 220.5,205.5Q175.0,271.0 116.5,325.0Q58.0,379.0 -5.0,419.0L24.0,500.0L430.0,500.0Q495.0,500.0 531.5,492.0Q568.0,484.0 595.0,462.0Q616.0,446.0 629.0,418.5Q642.0,391.0 642.0,353.0Q642.0,290.0 604.0,255.0Q566.0,220.0 501.0,220.0Q451.0,220.0 421.0,239.0Q391.0,258.0 377.5,287.0Q364.0,316.0 364.0,344.0Q364.0,368.0 370.0,388.0Q376.0,408.0 386.0,425.0L193.0,425.0Q155.0,425.0 104.0,427.0Q161.0,388.0 213.5,334.0Q266.0,280.0 308.0,214.0Q350.0,148.0 374.0,72.5Q398.0,-3.0 398.0,-84.0Q398.0,-190.0 357.5,-256.5Q317.0,-323.0 248.5,-354.5Q180.0,-386.0 95.0,-386.0ZM437.0,353.0Q437.0,323.0 454.5,304.5Q472.0,286.0 505.0,286.0Q540.0,286.0 554.5,304.5Q569.0,323.0 569.0,350.0Q569.0,393.0 543.5,409.0Q518.0,425.0 472.0,425.0L463.0,425.0Q437.0,390.0 437.0,353.0ZM31.0,-79.0Q-8.0,-79.0 -32.0,-105.5Q-56.0,-132.0 -59.0,-175.0Q-30.0,-192.0 8.0,-192.0Q88.0,-192.0 88.0,-135.0Q88.0,-109.0 72.5,-94.0Q57.0,-79.0 31.0,-79.0Z"  transform="translate(3964, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">రొౄవఛ॑ఝ॑</span> (Added by SIESTA)</li>


<pre>Expected: rovoweltelu=0+837|rrvocalicvowelsigntelu=0+625|vatelu=3+711|chatelu=4+760|uni0951=4@-94,293+0|jhatelu=6+1286|uni0951=6@-489,293+0</pre>



<pre>Got     : rovoweltelu=0+812|rrvocalicvowelsigntelu=0+625|vatelu=3+711|chatelu=4+760|uni0951=4@-94,293+0|jhatelu=6+1286|uni0951=6@-489,293+0</pre>



<pre>                         ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4194 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M35.0,236.0Q35.0,314.0 68.0,373.5Q101.0,433.0 159.5,466.5Q218.0,500.0 296.0,500.0Q375.0,500.0 433.5,467.5Q492.0,435.0 525.0,376.0Q558.0,317.0 558.0,237.0Q558.0,163.0 526.0,106.5Q494.0,50.0 435.0,19.0Q376.0,-12.0 296.0,-12.0Q217.0,-12.0 158.5,19.0Q100.0,50.0 67.5,105.5Q35.0,161.0 35.0,236.0ZM118.0,248.0Q118.0,167.0 163.0,117.0Q208.0,67.0 296.0,67.0Q385.0,67.0 430.0,116.5Q475.0,166.0 475.0,242.0Q475.0,293.0 455.5,334.5Q436.0,376.0 396.5,400.5Q357.0,425.0 296.0,425.0Q235.0,425.0 195.5,400.5Q156.0,376.0 137.0,336.0Q118.0,296.0 118.0,248.0ZM682.0,420.0Q632.0,420.0 602.0,439.0Q572.0,458.0 558.5,486.5Q545.0,515.0 545.0,544.0Q545.0,569.0 551.0,588.5Q557.0,608.0 567.0,625.0L528.0,625.0Q479.0,625.0 456.0,599.0Q433.0,573.0 427.0,532.0L349.0,532.0Q342.0,578.0 315.0,601.5Q288.0,625.0 256.0,625.0L240.0,625.0Q202.0,625.0 183.0,607.5Q164.0,590.0 164.0,564.0Q164.0,535.0 182.0,517.5Q200.0,500.0 246.0,500.0L275.0,500.0L275.0,425.0L244.0,425.0Q171.0,425.0 126.5,462.0Q82.0,499.0 82.0,567.0Q82.0,626.0 124.5,663.0Q167.0,700.0 237.0,700.0L245.0,700.0Q291.0,700.0 326.5,684.5Q362.0,669.0 387.0,623.0Q408.0,661.0 442.0,680.5Q476.0,700.0 537.0,700.0L602.0,700.0Q673.0,700.0 711.0,692.0Q749.0,684.0 776.0,662.0Q797.0,646.0 810.0,618.5Q823.0,591.0 823.0,553.0Q823.0,490.0 785.0,455.0Q747.0,420.0 682.0,420.0ZM618.0,553.0Q618.0,523.0 635.5,504.5Q653.0,486.0 686.0,486.0Q721.0,486.0 735.5,504.5Q750.0,523.0 750.0,550.0Q750.0,592.0 724.5,608.5Q699.0,625.0 653.0,625.0L644.0,625.0Q618.0,591.0 618.0,553.0Z"  transform="translate(0, 983)"/>
<path d="M95.0,-386.0Q24.0,-386.0 -26.5,-360.0Q-77.0,-334.0 -103.5,-288.5Q-130.0,-243.0 -130.0,-186.0Q-130.0,-133.0 -108.5,-95.0Q-87.0,-57.0 -50.0,-36.0Q-13.0,-15.0 32.0,-15.0Q99.0,-15.0 130.0,-50.5Q161.0,-86.0 161.0,-131.0Q161.0,-189.0 125.0,-222.5Q89.0,-256.0 13.0,-256.0Q-17.0,-256.0 -48.0,-244.0Q-33.0,-278.0 4.0,-296.5Q41.0,-315.0 100.0,-315.0Q138.0,-315.0 176.5,-305.5Q215.0,-296.0 247.5,-271.0Q280.0,-246.0 299.5,-200.5Q319.0,-155.0 319.0,-83.0Q319.0,-5.0 292.5,67.5Q266.0,140.0 220.5,205.5Q175.0,271.0 116.5,325.0Q58.0,379.0 -5.0,419.0L24.0,500.0L430.0,500.0Q495.0,500.0 531.5,492.0Q568.0,484.0 595.0,462.0Q616.0,446.0 629.0,418.5Q642.0,391.0 642.0,353.0Q642.0,290.0 604.0,255.0Q566.0,220.0 501.0,220.0Q451.0,220.0 421.0,239.0Q391.0,258.0 377.5,287.0Q364.0,316.0 364.0,344.0Q364.0,368.0 370.0,388.0Q376.0,408.0 386.0,425.0L193.0,425.0Q155.0,425.0 104.0,427.0Q161.0,388.0 213.5,334.0Q266.0,280.0 308.0,214.0Q350.0,148.0 374.0,72.5Q398.0,-3.0 398.0,-84.0Q398.0,-190.0 357.5,-256.5Q317.0,-323.0 248.5,-354.5Q180.0,-386.0 95.0,-386.0ZM437.0,353.0Q437.0,323.0 454.5,304.5Q472.0,286.0 505.0,286.0Q540.0,286.0 554.5,304.5Q569.0,323.0 569.0,350.0Q569.0,393.0 543.5,409.0Q518.0,425.0 472.0,425.0L463.0,425.0Q437.0,390.0 437.0,353.0ZM31.0,-79.0Q-8.0,-79.0 -32.0,-105.5Q-56.0,-132.0 -59.0,-175.0Q-30.0,-192.0 8.0,-192.0Q88.0,-192.0 88.0,-135.0Q88.0,-109.0 72.5,-94.0Q57.0,-79.0 31.0,-79.0Z"  transform="translate(812, 983)"/>
<path d="M481.0,-12.0Q429.0,-12.0 392.0,10.0Q355.0,32.0 321.0,71.0Q293.0,34.0 261.0,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 438.0,75.5Q459.0,67.0 486.0,67.0Q539.0,67.0 566.0,99.0Q593.0,131.0 593.0,192.0Q593.0,268.0 553.0,319.5Q513.0,371.0 445.0,398.0Q377.0,425.0 292.0,425.0L243.0,425.0L326.0,500.0Q437.0,493.0 515.5,452.5Q594.0,412.0 635.0,345.5Q676.0,279.0 676.0,194.0Q676.0,135.0 655.0,88.0Q634.0,41.0 590.5,14.5Q547.0,-12.0 481.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM239.0,425.0Q210.0,425.0 183.5,436.0Q157.0,447.0 135.0,477.5Q113.0,508.0 97.0,564.0L180.0,591.0Q195.0,536.0 209.0,518.0Q223.0,500.0 245.0,500.0Q265.0,500.0 282.5,512.5Q300.0,525.0 332.0,565.0L363.0,605.0Q397.0,649.0 425.5,675.0Q454.0,701.0 486.0,713.0Q518.0,725.0 562.0,725.0L568.0,648.0Q533.0,646.0 509.5,637.0Q486.0,628.0 466.5,608.5Q447.0,589.0 421.0,556.0L398.0,526.0Q356.0,472.0 320.0,448.5Q284.0,425.0 239.0,425.0Z"  transform="translate(1437, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0ZM340.0,-125.0L347.0,16.0L422.0,16.0L430.0,-125.0L340.0,-125.0Z"  transform="translate(2148, 983)"/>
<path d="M-250.0,599.0L-322.0,599.0L-322.0,810.0L-250.0,810.0L-250.0,599.0Z"  transform="translate(2814, 1276)"/>
<path d="M35.0,236.0Q35.0,314.0 68.0,373.5Q101.0,433.0 159.5,466.5Q218.0,500.0 296.0,500.0Q375.0,500.0 433.5,467.5Q492.0,435.0 525.0,376.0Q558.0,317.0 558.0,237.0Q558.0,200.0 550.0,166.0Q589.0,116.0 629.0,91.5Q669.0,67.0 716.0,67.0Q767.0,67.0 794.0,99.5Q821.0,132.0 821.0,193.0Q821.0,251.0 797.5,294.5Q774.0,338.0 734.5,369.5Q695.0,401.0 645.0,423.0L682.0,500.0Q744.0,474.0 794.0,430.0Q844.0,386.0 874.0,328.0Q904.0,270.0 904.0,199.0Q904.0,178.0 902.0,160.0Q940.0,113.0 979.0,90.0Q1018.0,67.0 1063.0,67.0Q1114.0,67.0 1141.0,99.5Q1168.0,132.0 1168.0,193.0Q1168.0,251.0 1144.5,294.5Q1121.0,338.0 1081.5,369.5Q1042.0,401.0 992.0,423.0L1029.0,500.0Q1091.0,474.0 1141.0,430.0Q1191.0,386.0 1221.0,328.0Q1251.0,270.0 1251.0,199.0Q1251.0,100.0 1201.0,44.0Q1151.0,-12.0 1056.0,-12.0Q1001.0,-12.0 956.5,12.0Q912.0,36.0 877.0,76.0Q854.0,34.0 811.5,11.0Q769.0,-12.0 709.0,-12.0Q648.0,-12.0 601.0,16.5Q554.0,45.0 517.0,92.0Q484.0,43.0 427.5,15.5Q371.0,-12.0 296.0,-12.0Q217.0,-12.0 158.5,19.0Q100.0,50.0 67.5,105.5Q35.0,161.0 35.0,236.0ZM118.0,248.0Q118.0,167.0 163.0,117.0Q208.0,67.0 296.0,67.0Q385.0,67.0 430.0,116.5Q475.0,166.0 475.0,242.0Q475.0,293.0 455.5,334.5Q436.0,376.0 396.5,400.5Q357.0,425.0 296.0,425.0Q235.0,425.0 195.5,400.5Q156.0,376.0 137.0,336.0Q118.0,296.0 118.0,248.0ZM837.0,-125.0L844.0,16.0L919.0,16.0L927.0,-125.0L837.0,-125.0ZM265.0,425.0Q236.0,425.0 209.5,436.0Q183.0,447.0 161.0,477.5Q139.0,508.0 123.0,564.0L206.0,591.0Q221.0,536.0 235.0,518.0Q249.0,500.0 271.0,500.0Q291.0,500.0 308.5,512.5Q326.0,525.0 358.0,565.0L389.0,605.0Q423.0,649.0 451.5,675.0Q480.0,701.0 512.0,713.0Q544.0,725.0 588.0,725.0L594.0,648.0Q559.0,646.0 535.5,637.0Q512.0,628.0 492.5,608.5Q473.0,589.0 447.0,556.0L424.0,526.0Q382.0,472.0 346.0,448.5Q310.0,425.0 265.0,425.0Z"  transform="translate(2908, 983)"/>
<path d="M-250.0,599.0L-322.0,599.0L-322.0,810.0L-250.0,810.0L-250.0,599.0Z"  transform="translate(3705, 1276)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4219 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M35.0,236.0Q35.0,314.0 68.0,373.5Q101.0,433.0 159.5,466.5Q218.0,500.0 296.0,500.0Q375.0,500.0 433.5,467.5Q492.0,435.0 525.0,376.0Q558.0,317.0 558.0,237.0Q558.0,163.0 526.0,106.5Q494.0,50.0 435.0,19.0Q376.0,-12.0 296.0,-12.0Q217.0,-12.0 158.5,19.0Q100.0,50.0 67.5,105.5Q35.0,161.0 35.0,236.0ZM118.0,248.0Q118.0,167.0 163.0,117.0Q208.0,67.0 296.0,67.0Q385.0,67.0 430.0,116.5Q475.0,166.0 475.0,242.0Q475.0,293.0 455.5,334.5Q436.0,376.0 396.5,400.5Q357.0,425.0 296.0,425.0Q235.0,425.0 195.5,400.5Q156.0,376.0 137.0,336.0Q118.0,296.0 118.0,248.0ZM682.0,420.0Q632.0,420.0 602.0,439.0Q572.0,458.0 558.5,486.5Q545.0,515.0 545.0,544.0Q545.0,569.0 551.0,588.5Q557.0,608.0 567.0,625.0L528.0,625.0Q479.0,625.0 456.0,599.0Q433.0,573.0 427.0,532.0L349.0,532.0Q342.0,578.0 315.0,601.5Q288.0,625.0 256.0,625.0L240.0,625.0Q202.0,625.0 183.0,607.5Q164.0,590.0 164.0,564.0Q164.0,535.0 182.0,517.5Q200.0,500.0 246.0,500.0L275.0,500.0L275.0,425.0L244.0,425.0Q171.0,425.0 126.5,462.0Q82.0,499.0 82.0,567.0Q82.0,626.0 124.5,663.0Q167.0,700.0 237.0,700.0L245.0,700.0Q291.0,700.0 326.5,684.5Q362.0,669.0 387.0,623.0Q408.0,661.0 442.0,680.5Q476.0,700.0 537.0,700.0L602.0,700.0Q673.0,700.0 711.0,692.0Q749.0,684.0 776.0,662.0Q797.0,646.0 810.0,618.5Q823.0,591.0 823.0,553.0Q823.0,490.0 785.0,455.0Q747.0,420.0 682.0,420.0ZM618.0,553.0Q618.0,523.0 635.5,504.5Q653.0,486.0 686.0,486.0Q721.0,486.0 735.5,504.5Q750.0,523.0 750.0,550.0Q750.0,592.0 724.5,608.5Q699.0,625.0 653.0,625.0L644.0,625.0Q618.0,591.0 618.0,553.0Z"  transform="translate(0, 983)"/>
<path d="M95.0,-386.0Q24.0,-386.0 -26.5,-360.0Q-77.0,-334.0 -103.5,-288.5Q-130.0,-243.0 -130.0,-186.0Q-130.0,-133.0 -108.5,-95.0Q-87.0,-57.0 -50.0,-36.0Q-13.0,-15.0 32.0,-15.0Q99.0,-15.0 130.0,-50.5Q161.0,-86.0 161.0,-131.0Q161.0,-189.0 125.0,-222.5Q89.0,-256.0 13.0,-256.0Q-17.0,-256.0 -48.0,-244.0Q-33.0,-278.0 4.0,-296.5Q41.0,-315.0 100.0,-315.0Q138.0,-315.0 176.5,-305.5Q215.0,-296.0 247.5,-271.0Q280.0,-246.0 299.5,-200.5Q319.0,-155.0 319.0,-83.0Q319.0,-5.0 292.5,67.5Q266.0,140.0 220.5,205.5Q175.0,271.0 116.5,325.0Q58.0,379.0 -5.0,419.0L24.0,500.0L430.0,500.0Q495.0,500.0 531.5,492.0Q568.0,484.0 595.0,462.0Q616.0,446.0 629.0,418.5Q642.0,391.0 642.0,353.0Q642.0,290.0 604.0,255.0Q566.0,220.0 501.0,220.0Q451.0,220.0 421.0,239.0Q391.0,258.0 377.5,287.0Q364.0,316.0 364.0,344.0Q364.0,368.0 370.0,388.0Q376.0,408.0 386.0,425.0L193.0,425.0Q155.0,425.0 104.0,427.0Q161.0,388.0 213.5,334.0Q266.0,280.0 308.0,214.0Q350.0,148.0 374.0,72.5Q398.0,-3.0 398.0,-84.0Q398.0,-190.0 357.5,-256.5Q317.0,-323.0 248.5,-354.5Q180.0,-386.0 95.0,-386.0ZM437.0,353.0Q437.0,323.0 454.5,304.5Q472.0,286.0 505.0,286.0Q540.0,286.0 554.5,304.5Q569.0,323.0 569.0,350.0Q569.0,393.0 543.5,409.0Q518.0,425.0 472.0,425.0L463.0,425.0Q437.0,390.0 437.0,353.0ZM31.0,-79.0Q-8.0,-79.0 -32.0,-105.5Q-56.0,-132.0 -59.0,-175.0Q-30.0,-192.0 8.0,-192.0Q88.0,-192.0 88.0,-135.0Q88.0,-109.0 72.5,-94.0Q57.0,-79.0 31.0,-79.0Z"  transform="translate(837, 983)"/>
<path d="M481.0,-12.0Q429.0,-12.0 392.0,10.0Q355.0,32.0 321.0,71.0Q293.0,34.0 261.0,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 438.0,75.5Q459.0,67.0 486.0,67.0Q539.0,67.0 566.0,99.0Q593.0,131.0 593.0,192.0Q593.0,268.0 553.0,319.5Q513.0,371.0 445.0,398.0Q377.0,425.0 292.0,425.0L243.0,425.0L326.0,500.0Q437.0,493.0 515.5,452.5Q594.0,412.0 635.0,345.5Q676.0,279.0 676.0,194.0Q676.0,135.0 655.0,88.0Q634.0,41.0 590.5,14.5Q547.0,-12.0 481.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM239.0,425.0Q210.0,425.0 183.5,436.0Q157.0,447.0 135.0,477.5Q113.0,508.0 97.0,564.0L180.0,591.0Q195.0,536.0 209.0,518.0Q223.0,500.0 245.0,500.0Q265.0,500.0 282.5,512.5Q300.0,525.0 332.0,565.0L363.0,605.0Q397.0,649.0 425.5,675.0Q454.0,701.0 486.0,713.0Q518.0,725.0 562.0,725.0L568.0,648.0Q533.0,646.0 509.5,637.0Q486.0,628.0 466.5,608.5Q447.0,589.0 421.0,556.0L398.0,526.0Q356.0,472.0 320.0,448.5Q284.0,425.0 239.0,425.0Z"  transform="translate(1462, 983)"/>
<path d="M543.0,-12.0Q485.0,-12.0 450.5,8.0Q416.0,28.0 385.0,74.0Q353.0,23.0 314.5,5.5Q276.0,-12.0 228.0,-12.0Q155.0,-12.0 110.5,31.0Q66.0,74.0 66.0,144.0Q66.0,172.0 80.0,203.5Q94.0,235.0 125.0,258.0L25.0,258.0L25.0,332.0L259.0,332.0L259.0,261.0Q199.0,248.0 173.0,218.0Q147.0,188.0 147.0,149.0Q147.0,112.0 170.0,89.5Q193.0,67.0 233.0,67.0Q283.0,67.0 312.5,99.5Q342.0,132.0 346.0,185.0L423.0,185.0Q428.0,124.0 461.5,95.5Q495.0,67.0 535.0,67.0Q563.0,67.0 587.5,77.0Q612.0,87.0 627.0,114.0Q642.0,141.0 642.0,192.0Q642.0,247.0 621.0,289.0Q600.0,331.0 565.5,360.0Q531.0,389.0 488.0,405.5Q445.0,422.0 402.0,426.0Q395.0,425.0 387.0,425.0Q358.0,425.0 331.5,436.0Q305.0,447.0 283.0,477.5Q261.0,508.0 245.0,564.0L328.0,591.0Q343.0,536.0 357.0,518.0Q371.0,500.0 393.0,500.0Q413.0,500.0 430.5,512.5Q448.0,525.0 480.0,565.0L511.0,605.0Q545.0,649.0 573.5,675.0Q602.0,701.0 634.0,713.0Q666.0,725.0 710.0,725.0L716.0,648.0Q681.0,646.0 657.5,637.0Q634.0,628.0 614.5,608.5Q595.0,589.0 569.0,556.0L546.0,526.0Q526.0,500.0 508.0,482.0Q615.0,446.0 670.0,368.5Q725.0,291.0 725.0,194.0Q725.0,124.0 701.0,78.5Q677.0,33.0 636.0,10.5Q595.0,-12.0 543.0,-12.0ZM340.0,-125.0L347.0,16.0L422.0,16.0L430.0,-125.0L340.0,-125.0Z"  transform="translate(2173, 983)"/>
<path d="M-250.0,599.0L-322.0,599.0L-322.0,810.0L-250.0,810.0L-250.0,599.0Z"  transform="translate(2839, 1276)"/>
<path d="M35.0,236.0Q35.0,314.0 68.0,373.5Q101.0,433.0 159.5,466.5Q218.0,500.0 296.0,500.0Q375.0,500.0 433.5,467.5Q492.0,435.0 525.0,376.0Q558.0,317.0 558.0,237.0Q558.0,200.0 550.0,166.0Q589.0,116.0 629.0,91.5Q669.0,67.0 716.0,67.0Q767.0,67.0 794.0,99.5Q821.0,132.0 821.0,193.0Q821.0,251.0 797.5,294.5Q774.0,338.0 734.5,369.5Q695.0,401.0 645.0,423.0L682.0,500.0Q744.0,474.0 794.0,430.0Q844.0,386.0 874.0,328.0Q904.0,270.0 904.0,199.0Q904.0,178.0 902.0,160.0Q940.0,113.0 979.0,90.0Q1018.0,67.0 1063.0,67.0Q1114.0,67.0 1141.0,99.5Q1168.0,132.0 1168.0,193.0Q1168.0,251.0 1144.5,294.5Q1121.0,338.0 1081.5,369.5Q1042.0,401.0 992.0,423.0L1029.0,500.0Q1091.0,474.0 1141.0,430.0Q1191.0,386.0 1221.0,328.0Q1251.0,270.0 1251.0,199.0Q1251.0,100.0 1201.0,44.0Q1151.0,-12.0 1056.0,-12.0Q1001.0,-12.0 956.5,12.0Q912.0,36.0 877.0,76.0Q854.0,34.0 811.5,11.0Q769.0,-12.0 709.0,-12.0Q648.0,-12.0 601.0,16.5Q554.0,45.0 517.0,92.0Q484.0,43.0 427.5,15.5Q371.0,-12.0 296.0,-12.0Q217.0,-12.0 158.5,19.0Q100.0,50.0 67.5,105.5Q35.0,161.0 35.0,236.0ZM118.0,248.0Q118.0,167.0 163.0,117.0Q208.0,67.0 296.0,67.0Q385.0,67.0 430.0,116.5Q475.0,166.0 475.0,242.0Q475.0,293.0 455.5,334.5Q436.0,376.0 396.5,400.5Q357.0,425.0 296.0,425.0Q235.0,425.0 195.5,400.5Q156.0,376.0 137.0,336.0Q118.0,296.0 118.0,248.0ZM837.0,-125.0L844.0,16.0L919.0,16.0L927.0,-125.0L837.0,-125.0ZM265.0,425.0Q236.0,425.0 209.5,436.0Q183.0,447.0 161.0,477.5Q139.0,508.0 123.0,564.0L206.0,591.0Q221.0,536.0 235.0,518.0Q249.0,500.0 271.0,500.0Q291.0,500.0 308.5,512.5Q326.0,525.0 358.0,565.0L389.0,605.0Q423.0,649.0 451.5,675.0Q480.0,701.0 512.0,713.0Q544.0,725.0 588.0,725.0L594.0,648.0Q559.0,646.0 535.5,637.0Q512.0,628.0 492.5,608.5Q473.0,589.0 447.0,556.0L424.0,526.0Q382.0,472.0 346.0,448.5Q310.0,425.0 265.0,425.0Z"  transform="translate(2933, 983)"/>
<path d="M-250.0,599.0L-322.0,599.0L-322.0,810.0L-250.0,810.0L-250.0,599.0Z"  transform="translate(3730, 1276)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">వీనెష్లే</span> (Added by SIESTA)</li>


<pre>Expected: viivoweltelu=0+711|nevoweltelu=2+702|sseevoweltelu=4+713|lasubscripttelu=4@-81,-30+0</pre>



<pre>Got     : viivoweltelu=0+711|nevoweltelu=2+702|sseevoweltelu=4+713|lasubscripttelu=4@-81,0+0</pre>



<pre>                                                                                         ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2126 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M481.0,-12.0Q429.0,-12.0 392.0,10.0Q355.0,32.0 321.0,71.0Q293.0,34.0 261.0,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 438.0,75.5Q459.0,67.0 487.0,67.0Q539.0,67.0 566.0,103.5Q593.0,140.0 593.0,225.0Q593.0,282.0 576.0,340.0Q559.0,398.0 528.5,449.5Q498.0,501.0 456.5,541.5Q415.0,582.0 366.0,606.0Q369.0,590.0 369.0,575.0Q369.0,519.0 334.0,485.5Q299.0,452.0 235.0,452.0Q189.0,452.0 160.0,471.0Q131.0,490.0 118.0,517.5Q105.0,545.0 105.0,572.0Q105.0,635.0 150.5,668.0Q196.0,701.0 269.0,701.0Q348.0,701.0 421.0,664.5Q494.0,628.0 551.5,563.0Q609.0,498.0 642.5,411.0Q676.0,324.0 676.0,223.0Q676.0,101.0 624.5,44.5Q573.0,-12.0 481.0,-12.0ZM179.0,576.0Q179.0,551.0 193.0,536.0Q207.0,521.0 236.0,521.0Q263.0,521.0 280.5,535.0Q298.0,549.0 298.0,584.0Q298.0,608.0 288.0,630.0Q272.0,632.0 256.0,632.0Q219.0,632.0 199.0,616.0Q179.0,600.0 179.0,576.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM286.0,853.0Q347.0,853.0 381.5,827.5Q416.0,802.0 433.0,757.0L357.0,737.0Q349.0,760.0 332.5,773.5Q316.0,787.0 287.0,787.0Q260.0,787.0 240.0,773.0Q220.0,759.0 220.0,732.0Q220.0,718.0 229.5,700.5Q239.0,683.0 269.0,663.0L195.0,635.0Q168.0,660.0 156.5,685.0Q145.0,710.0 145.0,740.0Q145.0,793.0 185.0,823.0Q225.0,853.0 286.0,853.0Z"  transform="translate(0, 983)"/>
<path d="M473.0,-12.0Q426.0,-12.0 391.0,3.5Q356.0,19.0 324.5,51.5Q293.0,84.0 256.0,133.0Q224.0,176.0 206.5,192.5Q189.0,209.0 164.0,209.0Q141.0,209.0 126.0,190.5Q111.0,172.0 111.0,143.0Q111.0,108.0 123.0,77.0Q135.0,46.0 159.0,14.0L78.0,-13.0Q56.0,22.0 42.5,59.5Q29.0,97.0 29.0,143.0Q29.0,204.0 67.0,245.0Q105.0,286.0 165.0,286.0Q204.0,286.0 230.5,272.5Q257.0,259.0 279.5,234.5Q302.0,210.0 328.0,175.0Q358.0,136.0 380.5,112.0Q403.0,88.0 425.5,77.5Q448.0,67.0 478.0,67.0Q529.0,67.0 556.5,99.0Q584.0,131.0 584.0,192.0Q584.0,256.0 556.0,302.0Q528.0,348.0 484.0,378.5Q440.0,409.0 393.0,425.0L287.0,425.0L287.0,500.0L335.0,500.0L450.0,474.0Q509.0,452.0 558.0,415.5Q607.0,379.0 637.0,324.5Q667.0,270.0 667.0,194.0Q667.0,101.0 617.5,44.5Q568.0,-12.0 473.0,-12.0ZM627.0,553.0Q627.0,520.0 615.5,496.5Q604.0,473.0 588.0,460.0Q565.0,441.0 532.5,433.0Q500.0,425.0 443.0,425.0L321.0,425.0L321.0,500.0L455.0,500.0Q514.0,500.0 530.0,515.0Q545.0,529.0 545.0,552.0Q545.0,579.0 529.0,592.0Q519.0,600.0 504.0,604.0Q489.0,608.0 454.0,608.0L65.0,608.0L65.0,683.0L448.0,683.0Q503.0,683.0 534.5,675.0Q566.0,667.0 589.0,647.0Q606.0,632.0 616.5,609.5Q627.0,587.0 627.0,553.0Z"  transform="translate(711, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,192.0Q593.0,250.0 570.0,293.5Q547.0,337.0 507.0,369.0Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM393.0,553.0Q393.0,520.0 381.5,496.5Q370.0,473.0 354.0,460.0Q331.0,441.0 298.5,433.0Q266.0,425.0 209.0,425.0L144.0,425.0L144.0,500.0L221.0,500.0Q253.0,500.0 269.5,503.5Q286.0,507.0 296.0,515.0Q311.0,529.0 311.0,552.0Q311.0,579.0 295.0,592.0Q285.0,600.0 270.0,604.0Q255.0,608.0 220.0,608.0L-15.0,608.0L-15.0,683.0L151.0,683.0Q146.0,700.0 146.0,719.0Q146.0,772.0 186.0,802.0Q226.0,832.0 287.0,832.0Q348.0,832.0 382.5,806.5Q417.0,781.0 434.0,736.0L358.0,716.0Q350.0,739.0 333.5,752.5Q317.0,766.0 288.0,766.0Q261.0,766.0 241.0,752.0Q221.0,738.0 221.0,711.0Q221.0,696.0 229.0,683.0Q276.0,682.0 304.5,673.5Q333.0,665.0 355.0,647.0Q372.0,632.0 382.5,609.5Q393.0,587.0 393.0,553.0Z"  transform="translate(1413, 983)"/>
<path d="M-411.0,-61.0Q-367.0,-61.0 -339.5,-80.5Q-312.0,-100.0 -291.0,-134.0Q-270.0,-99.0 -242.5,-80.0Q-215.0,-61.0 -171.0,-61.0Q-128.0,-61.0 -98.5,-79.5Q-69.0,-98.0 -53.0,-129.0Q-37.0,-160.0 -37.0,-196.0Q-37.0,-237.0 -52.0,-269.5Q-67.0,-302.0 -89.5,-327.0Q-112.0,-352.0 -135.0,-371.0L-187.0,-322.0Q-152.0,-295.0 -130.0,-265.5Q-108.0,-236.0 -108.0,-199.0Q-108.0,-171.0 -124.0,-151.5Q-140.0,-132.0 -175.0,-132.0Q-211.0,-132.0 -231.0,-154.5Q-251.0,-177.0 -257.0,-216.0L-325.0,-216.0Q-329.0,-178.0 -350.5,-155.0Q-372.0,-132.0 -410.0,-132.0Q-441.0,-132.0 -457.5,-151.5Q-474.0,-171.0 -474.0,-200.0Q-474.0,-237.0 -452.0,-265.0Q-430.0,-293.0 -395.0,-321.0L-447.0,-371.0Q-483.0,-340.0 -514.0,-298.0Q-545.0,-256.0 -545.0,-195.0Q-545.0,-141.0 -510.0,-101.0Q-475.0,-61.0 -411.0,-61.0Z"  transform="translate(2045, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2126 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M481.0,-12.0Q429.0,-12.0 392.0,10.0Q355.0,32.0 321.0,71.0Q293.0,34.0 261.0,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 438.0,75.5Q459.0,67.0 487.0,67.0Q539.0,67.0 566.0,103.5Q593.0,140.0 593.0,225.0Q593.0,282.0 576.0,340.0Q559.0,398.0 528.5,449.5Q498.0,501.0 456.5,541.5Q415.0,582.0 366.0,606.0Q369.0,590.0 369.0,575.0Q369.0,519.0 334.0,485.5Q299.0,452.0 235.0,452.0Q189.0,452.0 160.0,471.0Q131.0,490.0 118.0,517.5Q105.0,545.0 105.0,572.0Q105.0,635.0 150.5,668.0Q196.0,701.0 269.0,701.0Q348.0,701.0 421.0,664.5Q494.0,628.0 551.5,563.0Q609.0,498.0 642.5,411.0Q676.0,324.0 676.0,223.0Q676.0,101.0 624.5,44.5Q573.0,-12.0 481.0,-12.0ZM179.0,576.0Q179.0,551.0 193.0,536.0Q207.0,521.0 236.0,521.0Q263.0,521.0 280.5,535.0Q298.0,549.0 298.0,584.0Q298.0,608.0 288.0,630.0Q272.0,632.0 256.0,632.0Q219.0,632.0 199.0,616.0Q179.0,600.0 179.0,576.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM286.0,853.0Q347.0,853.0 381.5,827.5Q416.0,802.0 433.0,757.0L357.0,737.0Q349.0,760.0 332.5,773.5Q316.0,787.0 287.0,787.0Q260.0,787.0 240.0,773.0Q220.0,759.0 220.0,732.0Q220.0,718.0 229.5,700.5Q239.0,683.0 269.0,663.0L195.0,635.0Q168.0,660.0 156.5,685.0Q145.0,710.0 145.0,740.0Q145.0,793.0 185.0,823.0Q225.0,853.0 286.0,853.0Z"  transform="translate(0, 983)"/>
<path d="M473.0,-12.0Q426.0,-12.0 391.0,3.5Q356.0,19.0 324.5,51.5Q293.0,84.0 256.0,133.0Q224.0,176.0 206.5,192.5Q189.0,209.0 164.0,209.0Q141.0,209.0 126.0,190.5Q111.0,172.0 111.0,143.0Q111.0,108.0 123.0,77.0Q135.0,46.0 159.0,14.0L78.0,-13.0Q56.0,22.0 42.5,59.5Q29.0,97.0 29.0,143.0Q29.0,204.0 67.0,245.0Q105.0,286.0 165.0,286.0Q204.0,286.0 230.5,272.5Q257.0,259.0 279.5,234.5Q302.0,210.0 328.0,175.0Q358.0,136.0 380.5,112.0Q403.0,88.0 425.5,77.5Q448.0,67.0 478.0,67.0Q529.0,67.0 556.5,99.0Q584.0,131.0 584.0,192.0Q584.0,256.0 556.0,302.0Q528.0,348.0 484.0,378.5Q440.0,409.0 393.0,425.0L287.0,425.0L287.0,500.0L335.0,500.0L450.0,474.0Q509.0,452.0 558.0,415.5Q607.0,379.0 637.0,324.5Q667.0,270.0 667.0,194.0Q667.0,101.0 617.5,44.5Q568.0,-12.0 473.0,-12.0ZM627.0,553.0Q627.0,520.0 615.5,496.5Q604.0,473.0 588.0,460.0Q565.0,441.0 532.5,433.0Q500.0,425.0 443.0,425.0L321.0,425.0L321.0,500.0L455.0,500.0Q514.0,500.0 530.0,515.0Q545.0,529.0 545.0,552.0Q545.0,579.0 529.0,592.0Q519.0,600.0 504.0,604.0Q489.0,608.0 454.0,608.0L65.0,608.0L65.0,683.0L448.0,683.0Q503.0,683.0 534.5,675.0Q566.0,667.0 589.0,647.0Q606.0,632.0 616.5,609.5Q627.0,587.0 627.0,553.0Z"  transform="translate(711, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.5Q593.0,132.0 593.0,192.0Q593.0,250.0 570.0,293.5Q547.0,337.0 507.0,369.0Q467.0,401.0 417.0,423.0L455.0,500.0Q517.0,474.0 567.0,430.0Q617.0,386.0 646.5,327.5Q676.0,269.0 676.0,198.0Q676.0,83.0 609.0,28.0Q607.0,18.0 607.0,8.0Q607.0,-17.0 620.0,-32.0Q633.0,-47.0 655.0,-47.0Q674.0,-47.0 688.5,-40.5Q703.0,-34.0 722.0,-18.0L769.0,-80.0Q741.0,-103.0 715.5,-114.0Q690.0,-125.0 652.0,-125.0Q589.0,-125.0 557.0,-90.5Q525.0,-56.0 522.0,-9.0Q505.0,-12.0 485.0,-12.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM393.0,553.0Q393.0,520.0 381.5,496.5Q370.0,473.0 354.0,460.0Q331.0,441.0 298.5,433.0Q266.0,425.0 209.0,425.0L144.0,425.0L144.0,500.0L221.0,500.0Q253.0,500.0 269.5,503.5Q286.0,507.0 296.0,515.0Q311.0,529.0 311.0,552.0Q311.0,579.0 295.0,592.0Q285.0,600.0 270.0,604.0Q255.0,608.0 220.0,608.0L-15.0,608.0L-15.0,683.0L151.0,683.0Q146.0,700.0 146.0,719.0Q146.0,772.0 186.0,802.0Q226.0,832.0 287.0,832.0Q348.0,832.0 382.5,806.5Q417.0,781.0 434.0,736.0L358.0,716.0Q350.0,739.0 333.5,752.5Q317.0,766.0 288.0,766.0Q261.0,766.0 241.0,752.0Q221.0,738.0 221.0,711.0Q221.0,696.0 229.0,683.0Q276.0,682.0 304.5,673.5Q333.0,665.0 355.0,647.0Q372.0,632.0 382.5,609.5Q393.0,587.0 393.0,553.0Z"  transform="translate(1413, 983)"/>
<path d="M-411.0,-61.0Q-367.0,-61.0 -339.5,-80.5Q-312.0,-100.0 -291.0,-134.0Q-270.0,-99.0 -242.5,-80.0Q-215.0,-61.0 -171.0,-61.0Q-128.0,-61.0 -98.5,-79.5Q-69.0,-98.0 -53.0,-129.0Q-37.0,-160.0 -37.0,-196.0Q-37.0,-237.0 -52.0,-269.5Q-67.0,-302.0 -89.5,-327.0Q-112.0,-352.0 -135.0,-371.0L-187.0,-322.0Q-152.0,-295.0 -130.0,-265.5Q-108.0,-236.0 -108.0,-199.0Q-108.0,-171.0 -124.0,-151.5Q-140.0,-132.0 -175.0,-132.0Q-211.0,-132.0 -231.0,-154.5Q-251.0,-177.0 -257.0,-216.0L-325.0,-216.0Q-329.0,-178.0 -350.5,-155.0Q-372.0,-132.0 -410.0,-132.0Q-441.0,-132.0 -457.5,-151.5Q-474.0,-171.0 -474.0,-200.0Q-474.0,-237.0 -452.0,-265.0Q-430.0,-293.0 -395.0,-321.0L-447.0,-371.0Q-483.0,-340.0 -514.0,-298.0Q-545.0,-256.0 -545.0,-195.0Q-545.0,-141.0 -510.0,-101.0Q-475.0,-61.0 -411.0,-61.0Z"  transform="translate(2045, 953)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">హహ్బూళ</span> (Added by SIESTA)</li>


<pre>Expected: hatelu=0+1002|hatelu=1+1033|uuvowelsign2telu=1+712|basubscripttelu=1+415|llatelu=5+645</pre>



<pre>Got     : hatelu=0+1002|hatelu=1+1044|uuvowelsign2telu=1+712|basubscripttelu=1+415|llatelu=5+645</pre>



<pre>                                   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3818 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.0Q593.0,131.0 593.0,189.0Q593.0,244.0 569.5,288.0Q546.0,332.0 506.0,366.5Q466.0,401.0 418.0,425.0L454.0,500.0L806.0,500.0Q871.0,500.0 907.5,492.0Q944.0,484.0 971.0,462.0Q992.0,446.0 1005.0,418.5Q1018.0,391.0 1018.0,353.0Q1018.0,290.0 980.0,255.0Q942.0,220.0 877.0,220.0Q827.0,220.0 797.0,239.0Q767.0,258.0 753.5,287.0Q740.0,316.0 740.0,344.0Q740.0,369.0 746.0,388.5Q752.0,408.0 762.0,425.0L554.0,425.0Q607.0,385.0 641.5,325.5Q676.0,266.0 676.0,193.0Q676.0,98.0 626.5,43.0Q577.0,-12.0 485.0,-12.0ZM813.0,353.0Q813.0,323.0 830.5,304.5Q848.0,286.0 881.0,286.0Q916.0,286.0 930.5,304.5Q945.0,323.0 945.0,350.0Q945.0,392.0 919.5,408.5Q894.0,425.0 848.0,425.0L839.0,425.0Q813.0,391.0 813.0,353.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.0Q593.0,131.0 593.0,189.0Q593.0,244.0 569.5,288.0Q546.0,332.0 506.0,366.5Q466.0,401.0 418.0,425.0L454.0,500.0L806.0,500.0Q871.0,500.0 907.5,492.0Q944.0,484.0 971.0,462.0Q992.0,446.0 1005.0,418.5Q1018.0,391.0 1018.0,353.0Q1018.0,290.0 980.0,255.0Q942.0,220.0 877.0,220.0Q827.0,220.0 797.0,239.0Q767.0,258.0 753.5,287.0Q740.0,316.0 740.0,344.0Q740.0,369.0 746.0,388.5Q752.0,408.0 762.0,425.0L554.0,425.0Q607.0,385.0 641.5,325.5Q676.0,266.0 676.0,193.0Q676.0,98.0 626.5,43.0Q577.0,-12.0 485.0,-12.0ZM813.0,353.0Q813.0,323.0 830.5,304.5Q848.0,286.0 881.0,286.0Q916.0,286.0 930.5,304.5Q945.0,323.0 945.0,350.0Q945.0,392.0 919.5,408.5Q894.0,425.0 848.0,425.0L839.0,425.0Q813.0,391.0 813.0,353.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(1002, 983)"/>
<path d="M137.0,-12.0Q78.0,-12.0 33.0,10.0Q-12.0,32.0 -45.0,68.0Q-78.0,104.0 -101.5,148.0Q-125.0,192.0 -142.0,236.0L-61.0,270.0Q-46.0,222.0 -21.5,175.5Q3.0,129.0 42.5,98.0Q82.0,67.0 139.0,67.0Q253.0,67.0 253.0,193.0Q253.0,252.0 229.5,295.5Q206.0,339.0 166.5,370.5Q127.0,402.0 77.0,425.0L113.0,500.0L465.0,500.0Q530.0,500.0 566.5,492.0Q603.0,484.0 630.0,462.0Q651.0,446.0 664.0,418.5Q677.0,391.0 677.0,353.0Q677.0,290.0 639.0,255.0Q601.0,220.0 536.0,220.0Q486.0,220.0 456.0,239.0Q426.0,258.0 412.5,287.0Q399.0,316.0 399.0,344.0Q399.0,369.0 405.0,388.5Q411.0,408.0 421.0,425.0L216.0,425.0Q270.0,385.0 303.0,328.0Q336.0,271.0 336.0,199.0Q336.0,100.0 285.5,44.0Q235.0,-12.0 137.0,-12.0ZM472.0,353.0Q472.0,323.0 489.5,304.5Q507.0,286.0 540.0,286.0Q575.0,286.0 589.5,304.5Q604.0,323.0 604.0,350.0Q604.0,392.0 578.5,408.5Q553.0,425.0 507.0,425.0L498.0,425.0Q472.0,391.0 472.0,353.0Z"  transform="translate(2046, 983)"/>
<path d="M231.0,-386.0Q182.0,-386.0 154.0,-367.5Q126.0,-349.0 108.0,-316.0Q84.0,-353.0 50.0,-369.5Q16.0,-386.0 -34.0,-386.0Q-98.0,-386.0 -131.0,-356.0Q-164.0,-326.0 -164.0,-285.0Q-164.0,-247.0 -137.5,-219.5Q-111.0,-192.0 -45.0,-171.0Q-7.0,-158.0 7.0,-148.0Q21.0,-138.0 21.0,-121.0Q21.0,-110.0 9.0,-100.0Q-3.0,-90.0 -35.0,-90.0Q-69.0,-90.0 -83.5,-99.5Q-98.0,-109.0 -98.0,-125.0Q-98.0,-132.0 -95.5,-140.0Q-93.0,-148.0 -91.0,-151.0L-161.0,-167.0Q-166.0,-157.0 -170.0,-142.5Q-174.0,-128.0 -174.0,-115.0Q-174.0,-82.0 -141.0,-55.5Q-108.0,-29.0 -36.0,-29.0Q14.0,-29.0 42.5,-43.0Q71.0,-57.0 83.5,-77.5Q96.0,-98.0 96.0,-119.0Q96.0,-161.0 69.5,-183.5Q43.0,-206.0 -19.0,-227.0Q-57.0,-240.0 -71.5,-252.0Q-86.0,-264.0 -86.0,-279.0Q-86.0,-298.0 -71.5,-306.0Q-57.0,-314.0 -32.0,-314.0Q18.0,-314.0 42.0,-293.0Q66.0,-272.0 75.0,-237.0L146.0,-237.0Q152.0,-279.0 172.5,-296.5Q193.0,-314.0 225.0,-314.0Q250.0,-314.0 274.0,-298.5Q298.0,-283.0 313.5,-240.5Q329.0,-198.0 329.0,-117.0Q329.0,-27.0 301.0,55.0Q273.0,137.0 224.0,207.0Q175.0,277.0 113.0,333.5Q51.0,390.0 -18.0,430.0L22.0,500.0Q88.0,462.0 156.0,402.0Q224.0,342.0 281.0,262.5Q338.0,183.0 373.0,85.5Q408.0,-12.0 408.0,-125.0Q408.0,-258.0 358.5,-322.0Q309.0,-386.0 231.0,-386.0Z"  transform="translate(2758, 983)"/>
<path d="M329.0,-12.0Q295.0,-12.0 260.5,-3.0Q226.0,6.0 202.5,28.5Q179.0,51.0 179.0,92.0Q179.0,113.0 188.5,131.5Q198.0,150.0 220.0,165.0Q133.0,178.0 81.0,216.0Q29.0,254.0 29.0,321.0Q29.0,352.0 46.5,379.5Q64.0,407.0 98.5,424.5Q133.0,442.0 183.0,442.0Q237.0,442.0 270.0,424.0Q303.0,406.0 317.5,378.5Q332.0,351.0 332.0,323.0Q332.0,291.0 314.5,267.0Q297.0,243.0 267.0,225.0Q286.0,223.0 308.0,222.0Q337.0,220.0 358.0,215.0Q450.0,222.0 490.5,251.0Q531.0,280.0 531.0,323.0Q531.0,362.0 494.0,390.5Q457.0,419.0 384.0,426.0Q375.0,425.0 366.0,425.0Q337.0,425.0 310.5,436.0Q284.0,447.0 262.0,477.5Q240.0,508.0 224.0,564.0L307.0,591.0Q322.0,536.0 336.0,518.0Q350.0,500.0 372.0,500.0Q392.0,500.0 409.5,512.5Q427.0,525.0 459.0,565.0L490.0,605.0Q524.0,649.0 552.5,675.0Q581.0,701.0 613.0,713.0Q645.0,725.0 689.0,725.0L695.0,648.0Q660.0,646.0 636.5,637.0Q613.0,628.0 593.5,608.5Q574.0,589.0 548.0,556.0L525.0,526.0Q502.0,497.0 482.0,477.0Q546.0,455.0 580.0,417.0Q614.0,379.0 614.0,324.0Q614.0,266.0 576.0,222.5Q538.0,179.0 448.0,161.0Q463.0,149.0 473.0,131.5Q483.0,114.0 483.0,94.0Q483.0,54.0 460.5,30.5Q438.0,7.0 403.0,-2.5Q368.0,-12.0 329.0,-12.0ZM109.0,315.0Q109.0,297.0 119.5,277.5Q130.0,258.0 173.0,244.0Q209.0,254.0 231.0,272.5Q253.0,291.0 253.0,316.0Q253.0,338.0 237.0,354.5Q221.0,371.0 181.0,371.0Q146.0,371.0 127.5,354.5Q109.0,338.0 109.0,315.0ZM257.0,97.0Q257.0,74.0 279.5,64.5Q302.0,55.0 332.0,55.0Q362.0,55.0 383.5,64.5Q405.0,74.0 405.0,97.0Q405.0,116.0 387.0,131.0Q369.0,146.0 330.0,152.0Q286.0,144.0 271.5,129.0Q257.0,114.0 257.0,97.0Z"  transform="translate(3173, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3807 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.0Q593.0,131.0 593.0,189.0Q593.0,244.0 569.5,288.0Q546.0,332.0 506.0,366.5Q466.0,401.0 418.0,425.0L454.0,500.0L806.0,500.0Q871.0,500.0 907.5,492.0Q944.0,484.0 971.0,462.0Q992.0,446.0 1005.0,418.5Q1018.0,391.0 1018.0,353.0Q1018.0,290.0 980.0,255.0Q942.0,220.0 877.0,220.0Q827.0,220.0 797.0,239.0Q767.0,258.0 753.5,287.0Q740.0,316.0 740.0,344.0Q740.0,369.0 746.0,388.5Q752.0,408.0 762.0,425.0L554.0,425.0Q607.0,385.0 641.5,325.5Q676.0,266.0 676.0,193.0Q676.0,98.0 626.5,43.0Q577.0,-12.0 485.0,-12.0ZM813.0,353.0Q813.0,323.0 830.5,304.5Q848.0,286.0 881.0,286.0Q916.0,286.0 930.5,304.5Q945.0,323.0 945.0,350.0Q945.0,392.0 919.5,408.5Q894.0,425.0 848.0,425.0L839.0,425.0Q813.0,391.0 813.0,353.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(0, 983)"/>
<path d="M485.0,-12.0Q431.0,-12.0 393.0,10.0Q355.0,32.0 321.0,71.0Q294.0,34.0 261.5,11.0Q229.0,-12.0 175.0,-12.0Q122.0,-12.0 90.0,10.0Q58.0,32.0 43.5,66.5Q29.0,101.0 29.0,138.0Q29.0,203.0 70.0,242.5Q111.0,282.0 170.0,282.0Q206.0,282.0 234.0,269.5Q262.0,257.0 289.0,230.5Q316.0,204.0 348.0,161.0Q375.0,126.0 396.0,105.0Q417.0,84.0 439.0,75.5Q461.0,67.0 490.0,67.0Q540.0,67.0 566.5,99.0Q593.0,131.0 593.0,189.0Q593.0,244.0 569.5,288.0Q546.0,332.0 506.0,366.5Q466.0,401.0 418.0,425.0L454.0,500.0L806.0,500.0Q871.0,500.0 907.5,492.0Q944.0,484.0 971.0,462.0Q992.0,446.0 1005.0,418.5Q1018.0,391.0 1018.0,353.0Q1018.0,290.0 980.0,255.0Q942.0,220.0 877.0,220.0Q827.0,220.0 797.0,239.0Q767.0,258.0 753.5,287.0Q740.0,316.0 740.0,344.0Q740.0,369.0 746.0,388.5Q752.0,408.0 762.0,425.0L554.0,425.0Q607.0,385.0 641.5,325.5Q676.0,266.0 676.0,193.0Q676.0,98.0 626.5,43.0Q577.0,-12.0 485.0,-12.0ZM813.0,353.0Q813.0,323.0 830.5,304.5Q848.0,286.0 881.0,286.0Q916.0,286.0 930.5,304.5Q945.0,323.0 945.0,350.0Q945.0,392.0 919.5,408.5Q894.0,425.0 848.0,425.0L839.0,425.0Q813.0,391.0 813.0,353.0ZM107.0,136.0Q107.0,105.0 126.5,84.0Q146.0,63.0 180.0,63.0Q212.0,63.0 234.0,81.0Q256.0,99.0 272.0,133.0Q243.0,172.0 222.5,189.5Q202.0,207.0 172.0,207.0Q144.0,207.0 125.5,189.0Q107.0,171.0 107.0,136.0ZM197.0,425.0Q168.0,425.0 141.5,436.0Q115.0,447.0 93.0,477.5Q71.0,508.0 55.0,564.0L138.0,591.0Q153.0,536.0 167.0,518.0Q181.0,500.0 203.0,500.0Q223.0,500.0 240.5,512.5Q258.0,525.0 290.0,565.0L321.0,605.0Q355.0,649.0 383.5,675.0Q412.0,701.0 444.0,713.0Q476.0,725.0 520.0,725.0L526.0,648.0Q491.0,646.0 467.5,637.0Q444.0,628.0 424.5,608.5Q405.0,589.0 379.0,556.0L356.0,526.0Q314.0,472.0 278.0,448.5Q242.0,425.0 197.0,425.0Z"  transform="translate(1002, 983)"/>
<path d="M137.0,-12.0Q78.0,-12.0 33.0,10.0Q-12.0,32.0 -45.0,68.0Q-78.0,104.0 -101.5,148.0Q-125.0,192.0 -142.0,236.0L-61.0,270.0Q-46.0,222.0 -21.5,175.5Q3.0,129.0 42.5,98.0Q82.0,67.0 139.0,67.0Q253.0,67.0 253.0,193.0Q253.0,252.0 229.5,295.5Q206.0,339.0 166.5,370.5Q127.0,402.0 77.0,425.0L113.0,500.0L465.0,500.0Q530.0,500.0 566.5,492.0Q603.0,484.0 630.0,462.0Q651.0,446.0 664.0,418.5Q677.0,391.0 677.0,353.0Q677.0,290.0 639.0,255.0Q601.0,220.0 536.0,220.0Q486.0,220.0 456.0,239.0Q426.0,258.0 412.5,287.0Q399.0,316.0 399.0,344.0Q399.0,369.0 405.0,388.5Q411.0,408.0 421.0,425.0L216.0,425.0Q270.0,385.0 303.0,328.0Q336.0,271.0 336.0,199.0Q336.0,100.0 285.5,44.0Q235.0,-12.0 137.0,-12.0ZM472.0,353.0Q472.0,323.0 489.5,304.5Q507.0,286.0 540.0,286.0Q575.0,286.0 589.5,304.5Q604.0,323.0 604.0,350.0Q604.0,392.0 578.5,408.5Q553.0,425.0 507.0,425.0L498.0,425.0Q472.0,391.0 472.0,353.0Z"  transform="translate(2035, 983)"/>
<path d="M231.0,-386.0Q182.0,-386.0 154.0,-367.5Q126.0,-349.0 108.0,-316.0Q84.0,-353.0 50.0,-369.5Q16.0,-386.0 -34.0,-386.0Q-98.0,-386.0 -131.0,-356.0Q-164.0,-326.0 -164.0,-285.0Q-164.0,-247.0 -137.5,-219.5Q-111.0,-192.0 -45.0,-171.0Q-7.0,-158.0 7.0,-148.0Q21.0,-138.0 21.0,-121.0Q21.0,-110.0 9.0,-100.0Q-3.0,-90.0 -35.0,-90.0Q-69.0,-90.0 -83.5,-99.5Q-98.0,-109.0 -98.0,-125.0Q-98.0,-132.0 -95.5,-140.0Q-93.0,-148.0 -91.0,-151.0L-161.0,-167.0Q-166.0,-157.0 -170.0,-142.5Q-174.0,-128.0 -174.0,-115.0Q-174.0,-82.0 -141.0,-55.5Q-108.0,-29.0 -36.0,-29.0Q14.0,-29.0 42.5,-43.0Q71.0,-57.0 83.5,-77.5Q96.0,-98.0 96.0,-119.0Q96.0,-161.0 69.5,-183.5Q43.0,-206.0 -19.0,-227.0Q-57.0,-240.0 -71.5,-252.0Q-86.0,-264.0 -86.0,-279.0Q-86.0,-298.0 -71.5,-306.0Q-57.0,-314.0 -32.0,-314.0Q18.0,-314.0 42.0,-293.0Q66.0,-272.0 75.0,-237.0L146.0,-237.0Q152.0,-279.0 172.5,-296.5Q193.0,-314.0 225.0,-314.0Q250.0,-314.0 274.0,-298.5Q298.0,-283.0 313.5,-240.5Q329.0,-198.0 329.0,-117.0Q329.0,-27.0 301.0,55.0Q273.0,137.0 224.0,207.0Q175.0,277.0 113.0,333.5Q51.0,390.0 -18.0,430.0L22.0,500.0Q88.0,462.0 156.0,402.0Q224.0,342.0 281.0,262.5Q338.0,183.0 373.0,85.5Q408.0,-12.0 408.0,-125.0Q408.0,-258.0 358.5,-322.0Q309.0,-386.0 231.0,-386.0Z"  transform="translate(2747, 983)"/>
<path d="M329.0,-12.0Q295.0,-12.0 260.5,-3.0Q226.0,6.0 202.5,28.5Q179.0,51.0 179.0,92.0Q179.0,113.0 188.5,131.5Q198.0,150.0 220.0,165.0Q133.0,178.0 81.0,216.0Q29.0,254.0 29.0,321.0Q29.0,352.0 46.5,379.5Q64.0,407.0 98.5,424.5Q133.0,442.0 183.0,442.0Q237.0,442.0 270.0,424.0Q303.0,406.0 317.5,378.5Q332.0,351.0 332.0,323.0Q332.0,291.0 314.5,267.0Q297.0,243.0 267.0,225.0Q286.0,223.0 308.0,222.0Q337.0,220.0 358.0,215.0Q450.0,222.0 490.5,251.0Q531.0,280.0 531.0,323.0Q531.0,362.0 494.0,390.5Q457.0,419.0 384.0,426.0Q375.0,425.0 366.0,425.0Q337.0,425.0 310.5,436.0Q284.0,447.0 262.0,477.5Q240.0,508.0 224.0,564.0L307.0,591.0Q322.0,536.0 336.0,518.0Q350.0,500.0 372.0,500.0Q392.0,500.0 409.5,512.5Q427.0,525.0 459.0,565.0L490.0,605.0Q524.0,649.0 552.5,675.0Q581.0,701.0 613.0,713.0Q645.0,725.0 689.0,725.0L695.0,648.0Q660.0,646.0 636.5,637.0Q613.0,628.0 593.5,608.5Q574.0,589.0 548.0,556.0L525.0,526.0Q502.0,497.0 482.0,477.0Q546.0,455.0 580.0,417.0Q614.0,379.0 614.0,324.0Q614.0,266.0 576.0,222.5Q538.0,179.0 448.0,161.0Q463.0,149.0 473.0,131.5Q483.0,114.0 483.0,94.0Q483.0,54.0 460.5,30.5Q438.0,7.0 403.0,-2.5Q368.0,-12.0 329.0,-12.0ZM109.0,315.0Q109.0,297.0 119.5,277.5Q130.0,258.0 173.0,244.0Q209.0,254.0 231.0,272.5Q253.0,291.0 253.0,316.0Q253.0,338.0 237.0,354.5Q221.0,371.0 181.0,371.0Q146.0,371.0 127.5,354.5Q109.0,338.0 109.0,315.0ZM257.0,97.0Q257.0,74.0 279.5,64.5Q302.0,55.0 332.0,55.0Q362.0,55.0 383.5,64.5Q405.0,74.0 405.0,97.0Q405.0,116.0 387.0,131.0Q369.0,146.0 330.0,152.0Q286.0,144.0 271.5,129.0Q257.0,114.0 257.0,97.0Z"  transform="translate(3162, 983)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhauvoweltelu
	* ssauvoweltelu
	* phoovoweltelu
	* lovoweltelu
	* khaivoweltelu
	* dzeevoweltelu
	* hiivoweltelu
	* iitelu
	* toovoweltelu
	* yiivoweltelu and 212 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* nnatelu (U+0C23): L<<708.0,221.0>--<708.0,226.0>> -> L<<708.0,226.0>--<708.0,239.0>> 

	* And uni0C7F (U+0C7F): L<<128.0,259.0>--<128.0,256.0>> -> L<<128.0,256.0>--<128.0,250.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<561.0,409.0>-<565.0,409.0>-<571.0,408.0>>/B<<571.0,408.0>-<541.0,417.0>-<504.0,422.0>> = 7.236922025967975 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansTelugu-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhauvoweltelu
	* ssauvoweltelu
	* tsivoweltelu
	* rrratelu
	* phoovoweltelu
	* lovoweltelu
	* shevoweltelu
	* rrvocalictelu
	* khaivoweltelu
	* yaivoweltelu and 366 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* lllatelu (U+0C34): L<<149.0,244.0>--<149.0,243.0>> -> L<<149.0,243.0>--<149.0,231.0>> 

	* And ttatelu (U+0C1F): L<<149.0,244.0>--<149.0,243.0>> -> L<<149.0,243.0>--<149.0,231.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726 

	* And natelu (U+0C28): L<<257.0,407.0>--<257.0,407.0>>/B<<257.0,407.0>-<198.0,408.0>-<157.0,440.5>> = 0.9710219310788218 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansTelugu-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* llatelu (U+0C33): B<<200.5,143.0>-<225.0,166.0>-<267.0,174.0>>/B<<267.0,174.0>-<141.0,180.0>-<86.0,219.5>> = 13.510608861468855 

	* And tatelu (U+0C24): B<<592.5,392.5>-<613.0,383.0>-<629.0,368.0>>/B<<629.0,368.0>-<607.0,400.0>-<568.5,421.0>> = 12.33908727832621 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.telu (U+0021): L<<120.0,162.0>--<118.0,657.0>>

	* exclam.telu (U+0021): L<<146.0,657.0>--<144.0,162.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>> 

	* And exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] NotoSansTeluguUI-Black.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* eight.telu (U+0038): X=286.0,Y=621.0 (should be at cap-height 620?)

	* eight.telu (U+0038): X=286.0,Y=621.0 (should be at cap-height 620?)

	* G (U+0047): X=596.0,Y=621.0 (should be at cap-height 620?)

	* a (U+0061): X=228.0,Y=509.5 (should be at x-height 508?)

	* b (U+0062): X=334.0,Y=506.0 (should be at x-height 508?)

	* b (U+0062): X=334.0,Y=506.0 (should be at x-height 508?)

	* c (U+0063): X=333.0,Y=506.0 (should be at x-height 508?)

	* g (U+0067): X=271.0,Y=2.0 (should be at baseline 0?)

	* h (U+0068): X=348.0,Y=506.0 (should be at x-height 508?)

	* m (U+006D): X=678.0,Y=506.0 (should be at x-height 508?) 

	* And 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,329.0>-<346.0,297.0>-<347.0,277.0>>/B<<347.0,277.0>-<349.0,297.0>-<354.5,328.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,304.5>-<313.0,278.0>-<315.0,260.0>>/B<<315.0,260.0>-<319.0,290.0>-<325.5,329.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,535.0>-<523.0,561.0>-<521.0,579.0>>/B<<521.0,579.0>-<519.0,561.0>-<514.5,535.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,328.0>-<721.0,289.0>-<724.0,260.0>>/B<<724.0,260.0>-<727.0,285.0>-<734.0,322.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,304.5>-<313.0,278.0>-<315.0,260.0>>/B<<315.0,260.0>-<319.0,290.0>-<325.5,329.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,535.0>-<523.0,561.0>-<521.0,579.0>>/B<<521.0,579.0>-<519.0,561.0>-<514.5,535.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,328.0>-<721.0,289.0>-<724.0,260.0>>/B<<724.0,260.0>-<727.0,285.0>-<734.0,322.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,304.5>-<313.0,278.0>-<315.0,260.0>>/B<<315.0,260.0>-<319.0,290.0>-<325.5,329.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,535.0>-<523.0,561.0>-<521.0,579.0>>/B<<521.0,579.0>-<519.0,561.0>-<514.5,535.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,328.0>-<721.0,289.0>-<724.0,260.0>>/B<<724.0,260.0>-<727.0,285.0>-<734.0,322.0>> = 12.748914526401432 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] NotoSansTeluguUI-Bold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five.telu (U+0035): X=477.0,Y=618.0 (should be at cap-height 620?)

	* five.telu (U+0035): X=217.0,Y=618.0 (should be at cap-height 620?)

	* seven.telu (U+0037): X=378.0,Y=619.0 (should be at cap-height 620?)

	* seven.telu (U+0037): X=27.0,Y=619.0 (should be at cap-height 620?)

	* question.telu (U+003F): X=287.0,Y=620.5 (should be at cap-height 620?)

	* at (U+0040): X=470.0,Y=621.0 (should be at cap-height 620?)

	* S (U+0053): X=202.0,Y=619.0 (should be at cap-height 620?)

	* c (U+0063): X=173.5,Y=619.0 (should be at cap-height 620?)

	* h (U+0068): X=224.5,Y=621.0 (should be at cap-height 620?)

	* n (U+006E): X=412.0,Y=500.5 (should be at x-height 500?) 

	* And 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,289.0>-<272.0,254.0>-<275.0,230.0>>/B<<275.0,230.0>-<278.0,255.0>-<284.0,289.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,598.5>-<485.0,622.0>-<483.0,635.0>>/B<<483.0,635.0>-<482.0,622.0>-<477.5,598.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,289.0>-<689.0,254.0>-<692.0,230.0>>/B<<692.0,230.0>-<695.0,255.0>-<701.0,289.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,289.0>-<272.0,254.0>-<275.0,230.0>>/B<<275.0,230.0>-<278.0,255.0>-<284.0,289.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,598.5>-<485.0,622.0>-<483.0,635.0>>/B<<483.0,635.0>-<482.0,622.0>-<477.5,598.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,289.0>-<689.0,254.0>-<692.0,230.0>>/B<<692.0,230.0>-<695.0,255.0>-<701.0,289.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,289.0>-<272.0,254.0>-<275.0,230.0>>/B<<275.0,230.0>-<278.0,255.0>-<284.0,289.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,598.5>-<485.0,622.0>-<483.0,635.0>>/B<<483.0,635.0>-<482.0,622.0>-<477.5,598.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,289.0>-<689.0,254.0>-<692.0,230.0>>/B<<692.0,230.0>-<695.0,255.0>-<701.0,289.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,289.0>-<272.0,254.0>-<275.0,230.0>>/B<<275.0,230.0>-<278.0,255.0>-<284.0,289.5>> = 13.967789761532726 

	* And 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansTeluguUI-ExtraBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* zero.telu (U+0030): X=285.0,Y=622.0 (should be at cap-height 620?)

	* two.telu (U+0032): X=275.0,Y=618.0 (should be at cap-height 620?)

	* eight.telu (U+0038): X=232.5,Y=619.5 (should be at cap-height 620?)

	* at (U+0040): X=573.0,Y=619.0 (should be at cap-height 620?)

	* S (U+0053): X=220.0,Y=618.0 (should be at cap-height 620?)

	* b (U+0062): X=239.0,Y=619.5 (should be at cap-height 620?)

	* c (U+0063): X=178.0,Y=622.0 (should be at cap-height 620?)

	* e (U+0065): X=169.5,Y=620.5 (should be at cap-height 620?)

	* e (U+0065): X=382.0,Y=505.5 (should be at x-height 504?)

	* o (U+006F): X=453.5,Y=619.0 (should be at cap-height 620?) 

	* And 84 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,302.5>-<333.0,270.0>-<335.0,249.0>>/B<<335.0,249.0>-<338.0,270.0>-<344.5,302.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,304.5>-<290.0,268.0>-<293.0,244.0>>/B<<293.0,244.0>-<297.0,276.0>-<305.0,319.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,568.5>-<502.0,593.0>-<501.0,609.0>>/B<<501.0,609.0>-<499.0,593.0>-<494.5,568.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,304.5>-<290.0,268.0>-<293.0,244.0>>/B<<293.0,244.0>-<297.0,276.0>-<305.0,319.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,568.5>-<502.0,593.0>-<501.0,609.0>>/B<<501.0,609.0>-<499.0,593.0>-<494.5,568.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,304.5>-<290.0,268.0>-<293.0,244.0>>/B<<293.0,244.0>-<297.0,276.0>-<305.0,319.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,568.5>-<502.0,593.0>-<501.0,609.0>>/B<<501.0,609.0>-<499.0,593.0>-<494.5,568.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,304.5>-<290.0,268.0>-<293.0,244.0>>/B<<293.0,244.0>-<297.0,276.0>-<305.0,319.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,568.5>-<502.0,593.0>-<501.0,609.0>>/B<<501.0,609.0>-<499.0,593.0>-<494.5,568.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,304.5>-<290.0,268.0>-<293.0,244.0>>/B<<293.0,244.0>-<297.0,276.0>-<305.0,319.5>> = 14.25003269780357 

	* And 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansTeluguUI-ExtraLight.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* G (U+0047): X=141.5,Y=621.5 (should be at cap-height 620?)

	* a (U+0061): X=180.0,Y=620.5 (should be at cap-height 620?)

	* e (U+0065): X=84.0,Y=493.5 (should be at x-height 494?)

	* g (U+0067): X=445.5,Y=494.5 (should be at x-height 494?)

	* m (U+006D): X=216.0,Y=618.0 (should be at cap-height 620?)

	* r (U+0072): X=367.0,Y=621.0 (should be at cap-height 620?)

	* w (U+0077): X=15.0,Y=622.0 (should be at cap-height 620?)

	* w (U+0077): X=57.0,Y=622.0 (should be at cap-height 620?)

	* w (U+0077): X=342.0,Y=622.0 (should be at cap-height 620?)

	* w (U+0077): X=378.0,Y=622.0 (should be at cap-height 620?) 

	* And 72 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<112.0,132.0>--<112.0,130.0>>

	* M (U+004D) contains a short segment L<<140.0,761.0>--<137.0,761.0>>

	* M (U+004D) contains a short segment L<<424.0,157.0>--<427.0,157.0>>

	* M (U+004D) contains a short segment L<<440.0,93.0>--<409.0,93.0>>

	* N (U+004E) contains a short segment L<<139.0,735.0>--<137.0,735.0>>

	* N (U+004E) contains a short segment L<<570.0,167.0>--<572.0,167.0>>

	* a (U+0061) contains a short segment L<<401.0,191.0>--<399.0,191.0>>

	* d (U+0064) contains a short segment L<<465.0,198.0>--<463.0,198.0>>

	* k (U+006B) contains a short segment L<<126.0,311.0>--<126.0,311.0>>

	* m (U+006D) contains a short segment L<<126.0,531.0>--<129.0,531.0>> 

	* And 79 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<586.0,489.5>-<603.0,483.0>-<617.0,473.0>>/B<<617.0,473.0>-<594.0,498.0>-<558.5,515.0>> = 11.8482662384144 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansTeluguUI-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* four.telu (U+0034): X=379.5,Y=618.5 (should be at cap-height 620?)

	* at (U+0040): X=424.0,Y=-1.0 (should be at baseline 0?)

	* W (U+0057): X=477.0,Y=618.0 (should be at cap-height 620?)

	* a (U+0061): X=183.5,Y=622.0 (should be at cap-height 620?)

	* e (U+0065): X=84.5,Y=499.0 (should be at x-height 497?)

	* s (U+0073): X=54.0,Y=499.0 (should be at x-height 497?)

	* y (U+0079): X=230.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=148.0,Y=618.0 (should be at cap-height 620?)

	* registered (U+00AE): X=409.0,Y=621.0 (should be at cap-height 620?)

	* registered (U+00AE): X=339.0,Y=621.0 (should be at cap-height 620?) 

	* And 39 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* aatelu (U+0C06): L<<92.0,372.0>--<92.0,371.0>> -> L<<92.0,371.0>--<92.0,363.0>> 

	* And atelu (U+0C05): L<<92.0,372.0>--<92.0,371.0>> -> L<<92.0,371.0>--<92.0,363.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<576.0,496.0>-<587.0,493.0>-<598.0,488.0>>/B<<598.0,488.0>-<564.0,512.0>-<512.5,525.0>> = 10.773638187776136 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansTeluguUI-Medium.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft.telu (U+0028): X=93.0,Y=-1.0 (should be at baseline 0?)

	* parenright.telu (U+0029): X=168.0,Y=2.0 (should be at baseline 0?)

	* b (U+0062): X=250.5,Y=618.0 (should be at cap-height 620?)

	* d (U+0064): X=370.0,Y=619.0 (should be at cap-height 620?)

	* h (U+0068): X=259.5,Y=621.0 (should be at cap-height 620?)

	* m (U+006D): X=255.0,Y=622.0 (should be at cap-height 620?)

	* m (U+006D): X=590.0,Y=621.0 (should be at cap-height 620?)

	* n (U+006E): X=259.5,Y=622.0 (should be at cap-height 620?)

	* p (U+0070): X=250.5,Y=618.0 (should be at cap-height 620?)

	* q (U+0071): X=371.0,Y=618.0 (should be at cap-height 620?) 

	* And 45 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* natelu (U+0C28): L<<247.0,509.0>--<247.0,509.0>>/B<<247.0,509.0>-<213.0,510.0>-<184.0,522.5>> = 1.68468431789628 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansTeluguUI-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* asterisk.telu (U+002A): X=339.0,Y=621.0 (should be at cap-height 620?)

	* asterisk.telu (U+002A): X=238.0,Y=621.0 (should be at cap-height 620?)

	* W (U+0057): X=481.0,Y=619.0 (should be at cap-height 620?)

	* g (U+0067): X=370.5,Y=619.0 (should be at cap-height 620?)

	* m (U+006D): X=241.5,Y=618.5 (should be at cap-height 620?)

	* n (U+006E): X=246.0,Y=618.5 (should be at cap-height 620?)

	* s (U+0073): X=135.0,Y=502.0 (should be at x-height 500?)

	* sterling (U+00A3): X=219.0,Y=618.0 (should be at cap-height 620?)

	* ntilde (U+00F1): X=246.0,Y=618.5 (should be at cap-height 620?)

	* oslash (U+00F8): X=533.0,Y=621.0 (should be at cap-height 620?) 

	* And 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* nnatelu (U+0C23): L<<708.0,314.0>--<708.0,319.0>> -> L<<708.0,319.0>--<708.0,332.0>> 

	* And uni0C7F (U+0C7F): L<<128.0,352.0>--<128.0,349.0>> -> L<<128.0,349.0>--<128.0,343.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<561.0,502.0>-<565.0,502.0>-<571.0,501.0>>/B<<571.0,501.0>-<541.0,510.0>-<504.0,515.0>> = 7.236922025967975 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] NotoSansTeluguUI-SemiBold.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenright.telu (U+0029): X=155.0,Y=-2.0 (should be at baseline 0?)

	* asterisk.telu (U+002A): X=529.0,Y=622.0 (should be at cap-height 620?)

	* nine.telu (U+0039): X=193.5,Y=622.0 (should be at cap-height 620?)

	* at (U+0040): X=470.0,Y=618.0 (should be at cap-height 620?)

	* J (U+004A): X=-42.0,Y=2.0 (should be at baseline 0?)

	* J (U+004A): X=-4.0,Y=-1.0 (should be at baseline 0?)

	* M (U+004D): X=203.0,Y=621.5 (should be at cap-height 620?)

	* S (U+0053): X=56.0,Y=622.0 (should be at cap-height 620?)

	* b (U+0062): X=267.0,Y=621.5 (should be at cap-height 620?)

	* b (U+0062): X=235.0,Y=502.0 (should be at x-height 500?) 

	* And 46 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* lllatelu (U+0C34): L<<149.0,337.0>--<149.0,336.0>> -> L<<149.0,336.0>--<149.0,324.0>> 

	* And ttatelu (U+0C1F): L<<149.0,337.0>--<149.0,336.0>> -> L<<149.0,336.0>--<149.0,324.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,275.5>-<263.0,243.0>-<266.0,219.0>>/B<<266.0,219.0>-<269.0,244.0>-<275.0,277.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,275.0>-<684.0,243.0>-<687.0,219.0>>/B<<687.0,219.0>-<690.0,244.0>-<695.5,276.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,275.5>-<263.0,243.0>-<266.0,219.0>>/B<<266.0,219.0>-<269.0,244.0>-<275.0,277.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,275.0>-<684.0,243.0>-<687.0,219.0>>/B<<687.0,219.0>-<690.0,244.0>-<695.5,276.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,275.5>-<263.0,243.0>-<266.0,219.0>>/B<<266.0,219.0>-<269.0,244.0>-<275.0,277.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,275.0>-<684.0,243.0>-<687.0,219.0>>/B<<687.0,219.0>-<690.0,244.0>-<695.5,276.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,275.5>-<263.0,243.0>-<266.0,219.0>>/B<<266.0,219.0>-<269.0,244.0>-<275.0,277.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,275.0>-<684.0,243.0>-<687.0,219.0>>/B<<687.0,219.0>-<690.0,244.0>-<695.5,276.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,275.5>-<263.0,243.0>-<266.0,219.0>>/B<<266.0,219.0>-<269.0,244.0>-<275.0,277.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,275.0>-<684.0,243.0>-<687.0,219.0>>/B<<687.0,219.0>-<690.0,244.0>-<695.5,276.0>> = 13.967789761532726 

	* And natelu (U+0C28): L<<257.0,500.0>--<257.0,500.0>>/B<<257.0,500.0>-<198.0,501.0>-<157.0,533.5>> = 0.9710219310788218 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[12] NotoSansTeluguUI-Thin.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* llatelu (U+0C33): B<<200.5,236.0>-<225.0,259.0>-<267.0,267.0>>/B<<267.0,267.0>-<141.0,273.0>-<86.0,312.5>> = 13.510608861468855 

	* And tatelu (U+0C24): B<<592.5,485.5>-<613.0,476.0>-<629.0,461.0>>/B<<629.0,461.0>-<607.0,493.0>-<568.5,514.0>> = 12.33908727832621 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.telu (U+0021): L<<120.0,255.0>--<118.0,750.0>>

	* exclam.telu (U+0021): L<<146.0,750.0>--<144.0,255.0>>

	* exclamdown (U+00A1): L<<122.0,447.0>--<124.0,-93.0>> 

	* And exclamdown (U+00A1): L<<96.0,-93.0>--<98.0,447.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] NotoSansTelugu[wdth,wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 💔 **ERROR** Failed with IndexError: list index out of range
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1105, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 292. [code: invalid-default-instance-subfamily-nameid:292]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- tailengthmarkUItelu

	- maivowelUItelu

	- nasubscript1UItelu

	- ssaivowelUItelu

	- divide

	- bracketleft

	- three

	- taivowelUItelu

	- one

	- haivowelUItelu 

	- And 163 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsign2telu (unencoded), aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded) and 68 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 19 | 44 | 173 | 2126 | 116 | 1717 | 0 |
| 0% | 1% | 4% | 51% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
