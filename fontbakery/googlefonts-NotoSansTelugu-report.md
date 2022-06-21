## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf', 'fonts/NotoSansTelugu/googlefonts/ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Each font in a family must have the same set of vertical metrics values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/vertical_metrics">com.google.fonts/check/family/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** sTypoAscender is not the same across the family:
Noto Sans Telugu Regular: 869
Noto Sans Telugu Black: 869
Noto Sans Telugu Bold: 869
Noto Sans Telugu ExtraBold: 869
Noto Sans Telugu ExtraLight: 869
Noto Sans Telugu Light: 869
Noto Sans Telugu Medium: 869
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
Noto Sans Telugu Regular: -483
Noto Sans Telugu Black: -483
Noto Sans Telugu Bold: -483
Noto Sans Telugu ExtraBold: -483
Noto Sans Telugu ExtraLight: -483
Noto Sans Telugu Light: -483
Noto Sans Telugu Medium: -483
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
Noto Sans Telugu Regular: 869
Noto Sans Telugu Black: 869
Noto Sans Telugu Bold: 869
Noto Sans Telugu ExtraBold: 869
Noto Sans Telugu ExtraLight: 869
Noto Sans Telugu Light: 869
Noto Sans Telugu Medium: 869
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
Noto Sans Telugu Regular: 483
Noto Sans Telugu Black: 483
Noto Sans Telugu Bold: 483
Noto Sans Telugu ExtraBold: 483
Noto Sans Telugu ExtraLight: 483
Noto Sans Telugu Light: 483
Noto Sans Telugu Medium: 483
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
Noto Sans Telugu Regular: 869
Noto Sans Telugu Black: 869
Noto Sans Telugu Bold: 869
Noto Sans Telugu ExtraBold: 869
Noto Sans Telugu ExtraLight: 869
Noto Sans Telugu Light: 869
Noto Sans Telugu Medium: 869
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
Noto Sans Telugu Regular: -483
Noto Sans Telugu Black: -483
Noto Sans Telugu Bold: -483
Noto Sans Telugu ExtraBold: -483
Noto Sans Telugu ExtraLight: -483
Noto Sans Telugu Light: -483
Noto Sans Telugu Medium: -483
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
</div></details><br></div></details><details><summary><b>[14] NotoSansTelugu[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSansTelugu[wght].ttf' must be renamed to 'NotoSansTelugu[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 292. [code: invalid-default-instance-subfamily-nameid:292]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- comma

	- taalttelu

	- dhailengthmark1UItelu

	- parenright

	- ttailengthmarkUItelu

	- bracketright

	- jailengthmarkUItelu

	- khaivowelUItelu

	- seven

	- ddasubscript1UItelu 

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
</div></details><br></div></details><details><summary><b>[18] NotoSansTelugu-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu Black [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* juvoweltelu
	* rrauvoweltelu
	* moovoweltelu
	* chiivoweltelu
	* gauvoweltelu
	* laavoweltelu
	* ttovoweltelu
	* sovoweltelu
	* dzaavoweltelu
	* chauvoweltelu and 531 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 793 but it should be 903 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three.telu (U+0033): X=125.5,Y=-2.0 (should be at baseline 0?)

	* etelu (U+0C0E): X=477.5,Y=1.5 (should be at baseline 0?)

	* eetelu (U+0C0F): X=477.5,Y=1.5 (should be at baseline 0?)

	* aitelu (U+0C10): X=501.5,Y=1.5 (should be at baseline 0?)

	* autelu (U+0C14): X=809.0,Y=621.5 (should be at cap-height 620?)

	* katelu (U+0C15): X=176.5,Y=0.5 (should be at baseline 0?)

	* khatelu (U+0C16): X=488.0,Y=2.0 (should be at baseline 0?)

	* khatelu (U+0C16): X=310.0,Y=1.5 (should be at baseline 0?)

	* khatelu (U+0C16): X=319.0,Y=1.0 (should be at baseline 0?)

	* khatelu (U+0C16): X=467.0,Y=1.0 (should be at baseline 0?) 

	* And 29 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* khatelu (U+0C16): B<<291.0,276.5>-<266.0,253.0>-<219.0,246.0>>/B<<219.0,246.0>-<252.0,243.0>-<280.0,234.0>> = 13.665573540749627 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSansTelugu-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* juvoweltelu
	* rrauvoweltelu
	* moovoweltelu
	* chiivoweltelu
	* laavoweltelu
	* ttovoweltelu
	* dzaavoweltelu
	* chauvoweltelu
	* rraavoweltelu
	* tthoovoweltelu and 442 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 751 but it should be 851 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenright.telu (U+0029): X=163.0,Y=-0.5 (should be at baseline 0?)

	* zero.telu (U+0030): X=139.0,Y=621.0 (should be at cap-height 620?)

	* three.telu (U+0033): X=448.5,Y=620.5 (should be at cap-height 620?)

	* itelu (U+0C07): X=663.0,Y=2.0 (should be at baseline 0?)

	* itelu (U+0C07): X=533.0,Y=1.0 (should be at baseline 0?)

	* nyatelu (U+0C1E): X=663.0,Y=2.0 (should be at baseline 0?)

	* nyatelu (U+0C1E): X=533.0,Y=1.0 (should be at baseline 0?)

	* rratelu (U+0C31): X=357.0,Y=-1.5 (should be at baseline 0?)

	* satelu (U+0C38): X=445.5,Y=-0.5 (should be at baseline 0?)

	* iivowelsigntelu (U+0C40): X=-279.0,Y=622.0 (should be at cap-height 620?) 

	* And 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* llatelu (U+0C33): B<<268.5,439.0>-<296.0,433.0>-<316.0,423.0>>/B<<316.0,423.0>-<289.0,441.0>-<269.5,474.5>> = 7.125016348901757

	* llatelu (U+0C33): B<<421.0,396.0>-<367.0,396.0>-<330.0,415.0>>/B<<330.0,415.0>-<356.0,397.0>-<366.5,373.5>> = 7.514042445756763 

	* And natelu (U+0C28): L<<269.0,396.0>--<269.0,396.0>>/B<<269.0,396.0>-<201.0,398.0>-<157.5,434.0>> = 1.68468431789628 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[18] NotoSansTelugu-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu ExtraBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* juvoweltelu
	* rrauvoweltelu
	* moovoweltelu
	* chiivoweltelu
	* laavoweltelu
	* ttovoweltelu
	* dzaavoweltelu
	* chauvoweltelu
	* rraavoweltelu
	* tthoovoweltelu and 464 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 770 but it should be 875 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* zero.telu (U+0030): X=141.0,Y=620.5 (should be at cap-height 620?)

	* three.telu (U+0033): X=130.0,Y=-1.0 (should be at baseline 0?)

	* three.telu (U+0033): X=448.5,Y=619.0 (should be at cap-height 620?)

	* braceleft.telu (U+007B): X=148.0,Y=622.0 (should be at cap-height 620?)

	* braceright.telu (U+007D): X=271.0,Y=622.0 (should be at cap-height 620?)

	* itelu (U+0C07): X=539.0,Y=2.0 (should be at baseline 0?)

	* khatelu (U+0C16): X=300.0,Y=2.0 (should be at baseline 0?)

	* nyatelu (U+0C1E): X=539.0,Y=2.0 (should be at baseline 0?)

	* natelu (U+0C28): X=460.5,Y=-1.0 (should be at baseline 0?)

	* rratelu (U+0C31): X=371.5,Y=-1.5 (should be at baseline 0?) 

	* And 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* bhatelu (U+0C2D): B<<503.0,392.0>-<445.0,399.0>-<409.0,434.0>>/B<<409.0,434.0>-<427.0,405.0>-<427.0,368.0>> = 13.979482878429264

	* ssatelu (U+0C37): B<<538.0,-15.0>-<538.0,-12.0>-<539.0,-12.0>>/B<<539.0,-12.0>-<491.0,-10.0>-<453.0,5.5>> = 2.3859440303887243 

	* And tatelu (U+0C24): B<<472.0,284.0>-<472.0,361.0>-<542.0,394.0>>/B<<542.0,394.0>-<522.0,390.0>-<500.0,390.0>> = 13.930596790766563 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansTelugu-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu ExtraLight [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* iitelu
	* nnaavoweltelu
	* rrraavoweltelu and uni0C7B
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 651 but it should be 733 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam.telu (U+0021): X=161.5,Y=-1.5 (should be at baseline 0?)

	* exclam.telu (U+0021): X=109.5,Y=-1.5 (should be at baseline 0?)

	* period.telu (U+002E): X=135.5,Y=1.5 (should be at baseline 0?)

	* period.telu (U+002E): X=83.5,Y=1.5 (should be at baseline 0?)

	* zero.telu (U+0030): X=153.0,Y=618.5 (should be at cap-height 620?)

	* zero.telu (U+0030): X=421.0,Y=619.5 (should be at cap-height 620?)

	* three.telu (U+0033): X=135.0,Y=-0.5 (should be at baseline 0?)

	* five.telu (U+0035): X=147.0,Y=-0.5 (should be at baseline 0?)

	* six.telu (U+0036): X=425.5,Y=622.0 (should be at cap-height 620?)

	* seven.telu (U+0037): X=510.0,Y=621.0 (should be at cap-height 620?) 

	* And 43 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<112.0,39.0>--<112.0,37.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<266.0,-12.0>--<262.0,-12.0>>

	* atelu (U+0C05) contains a short segment B<<79.0,293.0>-<78.0,285.0>-<78.0,276.0>>

	* aatelu (U+0C06) contains a short segment B<<79.0,293.0>-<78.0,285.0>-<78.0,276.0>>

	* iitelu (U+0C08) contains a short segment B<<95.0,239.0>-<95.0,246.0>-<96.0,252.0>>

	* iitelu (U+0C08) contains a short segment B<<314.0,494.0>-<317.0,494.0>-<319.0,494.0>>

	* iitelu (U+0C08) contains a short segment B<<319.0,494.0>-<320.0,494.0>-<322.0,494.0>>

	* iitelu (U+0C08) contains a short segment B<<580.0,252.0>-<580.0,245.0>-<580.0,238.0>>

	* uutelu (U+0C0A) contains a short segment B<<85.0,263.0>-<82.0,246.0>-<80.5,228.0>>

	* uutelu (U+0C0A) contains a short segment B<<80.5,228.0>-<79.0,210.0>-<79.0,191.0>> 

	* And 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<586.0,396.5>-<603.0,390.0>-<617.0,380.0>>/B<<617.0,380.0>-<594.0,405.0>-<558.5,422.0>> = 11.8482662384144 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansTelugu-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu Light [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* dzaavoweltelu
	* rraavoweltelu
	* jhauvoweltelu
	* nyauvoweltelu
	* juuvoweltelu
	* dzoovoweltelu
	* dzaivoweltelu
	* raavoweltelu
	* daavoweltelu
	* llleevoweltelu and 52 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 668 but it should be 752 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
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

	* braceleft.telu (U+007B): X=207.0,Y=619.0 (should be at cap-height 620?)

	* braceright.telu (U+007D): X=166.0,Y=621.0 (should be at cap-height 620?)

	* itelu (U+0C07): X=589.0,Y=-1.0 (should be at baseline 0?) 

	* And 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<134.0,56.0>--<134.0,53.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<272.0,-12.0>--<269.0,-12.0>>

	* atelu (U+0C05) contains a short segment L<<92.0,278.0>--<92.0,270.0>>

	* aatelu (U+0C06) contains a short segment L<<92.0,278.0>--<92.0,270.0>>

	* iitelu (U+0C08) contains a short segment B<<95.0,238.0>-<95.0,242.0>-<95.0,245.0>>

	* iitelu (U+0C08) contains a short segment B<<593.0,245.0>-<594.0,242.0>-<594.0,238.0>>

	* iitelu (U+0C08) contains a short segment B<<540.0,240.0>-<540.0,240.0>-<539.5,240.5>>

	* iitelu (U+0C08) contains a short segment B<<539.5,240.5>-<539.0,241.0>-<539.0,245.0>>

	* iitelu (U+0C08) contains a short segment L<<149.0,245.0>--<149.0,244.0>>

	* uutelu (U+0C0A) contains a short segment B<<377.0,497.0>-<399.0,496.0>-<419.0,495.0>> 

	* And 40 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* aatelu (U+0C06): L<<92.0,279.0>--<92.0,278.0>> -> L<<92.0,278.0>--<92.0,270.0>> 

	* And atelu (U+0C05): L<<92.0,279.0>--<92.0,278.0>> -> L<<92.0,278.0>--<92.0,270.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<576.0,403.0>-<587.0,400.0>-<598.0,395.0>>/B<<598.0,395.0>-<564.0,419.0>-<512.5,432.0>> = 10.773638187776136 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansTelugu-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu Medium [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* juvoweltelu
	* rrauvoweltelu
	* moovoweltelu
	* laavoweltelu
	* ttovoweltelu
	* dzaavoweltelu
	* chauvoweltelu
	* rraavoweltelu
	* tthoovoweltelu
	* khovoweltelu and 304 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 712 but it should be 804 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenright.telu (U+0029): X=292.0,Y=-1.5 (should be at baseline 0?)

	* three.telu (U+0033): X=136.0,Y=-1.0 (should be at baseline 0?)

	* nine.telu (U+0039): X=96.0,Y=-1.0 (should be at baseline 0?)

	* braceleft.telu (U+007B): X=150.0,Y=621.0 (should be at cap-height 620?)

	* braceright.telu (U+007D): X=243.0,Y=621.0 (should be at cap-height 620?)

	* itelu (U+0C07): X=625.0,Y=1.0 (should be at baseline 0?)

	* itelu (U+0C07): X=431.5,Y=2.0 (should be at baseline 0?)

	* eetelu (U+0C0F): X=248.0,Y=621.0 (should be at cap-height 620?)

	* nyatelu (U+0C1E): X=625.0,Y=1.0 (should be at baseline 0?)

	* nyatelu (U+0C1E): X=431.5,Y=2.0 (should be at baseline 0?) 

	* And 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<190.0,98.0>--<190.0,93.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<288.0,-12.0>--<285.0,-12.0>>

	* iitelu (U+0C08) contains a short segment B<<917.0,278.0>-<924.0,273.0>-<931.0,268.0>>

	* uutelu (U+0C0A) contains a short segment B<<1032.0,289.0>-<1039.0,285.0>-<1046.0,280.0>>

	* rvocalictelu (U+0C0B) contains a short segment B<<133.0,363.0>-<133.0,350.0>-<136.5,339.5>>

	* rvocalictelu (U+0C0B) contains a short segment B<<136.5,339.5>-<140.0,329.0>-<143.0,323.0>>

	* aitelu (U+0C10) contains a short segment B<<134.0,362.0>-<134.0,353.0>-<136.0,341.5>>

	* aitelu (U+0C10) contains a short segment B<<136.0,341.5>-<138.0,330.0>-<142.0,322.0>>

	* otelu (U+0C12) contains a short segment B<<136.5,339.5>-<140.0,329.0>-<143.0,323.0>>

	* ootelu (U+0C13) contains a short segment B<<136.5,339.5>-<140.0,329.0>-<143.0,323.0>> 

	* And 50 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* natelu (U+0C28): L<<247.0,416.0>--<247.0,416.0>>/B<<247.0,416.0>-<213.0,417.0>-<184.0,429.5>> = 1.68468431789628 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansTelugu-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
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

<li>Shaping did not match: <span class="tf">రాష్ట్రాల</span> (fontdiff-Telugu.html)</li>


<pre>Expected: raavoweltelu=0+906|ssaavoweltelu=2+1051|ttasubscripttelu=2@-424,-30+0|rasubscripttelu=2+420|latelu=8+709</pre>



<pre>Got     : raavoweltelu=0+906|ssaavoweltelu=2+1051|ttasubscripttelu=2@-424,0+0|rasubscripttelu=2+420|latelu=8+709</pre>



<pre>                                                                          ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3086 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(906, 983)"/>
<path d=""  transform="translate(1533, 983)"/>
<path d=""  transform="translate(1957, 983)"/>
<path d=""  transform="translate(2377, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3086 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(906, 983)"/>
<path d=""  transform="translate(1533, 953)"/>
<path d=""  transform="translate(1957, 983)"/>
<path d=""  transform="translate(2377, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(ఎథ్నోలాగ్)</span> (fontdiff-Telugu.html)</li>


<pre>Expected: parenleft.telu=0+362|etelu=1+711|thoovoweltelu=2+904|nasubscripttelu=2+346|laavoweltelu=6+1047|gahalanttelu=8+583|parenright.telu=10+362</pre>



<pre>Got     : parenleft.telu=0+362|etelu=1+711|thoovoweltelu=2+869|nasubscripttelu=2+346|laavoweltelu=6+1047|gahalanttelu=8+583|parenright.telu=10+362</pre>



<pre>                                                            ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4280 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(362, 983)"/>
<path d=""  transform="translate(1073, 983)"/>
<path d=""  transform="translate(1942, 983)"/>
<path d=""  transform="translate(2288, 983)"/>
<path d=""  transform="translate(3335, 983)"/>
<path d=""  transform="translate(3918, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4315 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(362, 983)"/>
<path d=""  transform="translate(1073, 983)"/>
<path d=""  transform="translate(1977, 983)"/>
<path d=""  transform="translate(2323, 983)"/>
<path d=""  transform="translate(3370, 983)"/>
<path d=""  transform="translate(3953, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">జన్యు</span> (fontdiff-Telugu.html)</li>


<pre>Expected: jatelu=0+731|natelu=1+702|uvowelsigntelu=1+335|yasubscripttelu=1+458</pre>



<pre>Got     : jatelu=0+731|natelu=1+691|uvowelsigntelu=1+335|yasubscripttelu=1+458</pre>



<pre>                                ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2215 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(731, 983)"/>
<path d=""  transform="translate(1422, 983)"/>
<path d=""  transform="translate(1757, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2226 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(731, 983)"/>
<path d=""  transform="translate(1433, 983)"/>
<path d=""  transform="translate(1768, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ఇష్టమైన</span> (fontdiff-Telugu.html)</li>


<pre>Expected: itelu=0+689|ssatelu=1+713|ttasubscripttelu=1@-86,-30+0|maivoweltelu=4+1058|natelu=6+702</pre>



<pre>Got     : itelu=0+689|ssatelu=1+713|ttasubscripttelu=1@-86,0+0|maivoweltelu=4+1058|natelu=6+702</pre>



<pre>                                                           ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3162 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(689, 983)"/>
<path d=""  transform="translate(1316, 983)"/>
<path d=""  transform="translate(1402, 983)"/>
<path d=""  transform="translate(2460, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3162 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(689, 983)"/>
<path d=""  transform="translate(1316, 953)"/>
<path d=""  transform="translate(1402, 983)"/>
<path d=""  transform="translate(2460, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">కృష్ణదేవ</span> (fontdiff-Telugu.html)</li>


<pre>Expected: katelu=0+522|rvocalicvowelsigntelu=0+400|ssatelu=2+713|nnasubscripttelu=2@-67,-30+0|deevoweltelu=5+706|vatelu=7+711</pre>



<pre>Got     : katelu=0+522|rvocalicvowelsigntelu=0+400|ssatelu=2+713|nnasubscripttelu=2@-67,0+0|deevoweltelu=5+706|vatelu=7+711</pre>



<pre>                                                                                        ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3052 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(522, 983)"/>
<path d=""  transform="translate(922, 983)"/>
<path d=""  transform="translate(1568, 983)"/>
<path d=""  transform="translate(1635, 983)"/>
<path d=""  transform="translate(2341, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3052 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(522, 983)"/>
<path d=""  transform="translate(922, 983)"/>
<path d=""  transform="translate(1568, 953)"/>
<path d=""  transform="translate(1635, 983)"/>
<path d=""  transform="translate(2341, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">రామకృష్ణ</span> (fontdiff-Telugu.html)</li>


<pre>Expected: raavoweltelu=0+906|matelu=2+1058|katelu=3+522|rvocalicvowelsigntelu=3+400|ssatelu=5+713|nnasubscripttelu=5@-67,-30+0</pre>



<pre>Got     : raavoweltelu=0+906|matelu=2+1058|katelu=3+522|rvocalicvowelsigntelu=3+400|ssatelu=5+713|nnasubscripttelu=5@-67,0+0</pre>



<pre>                                                                                                                         ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3599 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(906, 983)"/>
<path d=""  transform="translate(1964, 983)"/>
<path d=""  transform="translate(2486, 983)"/>
<path d=""  transform="translate(2886, 983)"/>
<path d=""  transform="translate(3532, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3599 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(906, 983)"/>
<path d=""  transform="translate(1964, 983)"/>
<path d=""  transform="translate(2486, 983)"/>
<path d=""  transform="translate(2886, 983)"/>
<path d=""  transform="translate(3532, 953)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">కార్యనిర్వాహక</span> (fontdiff-Telugu.html)</li>


<pre>Expected: kaavoweltelu=0+867|ratelu=2+593|yasubscripttelu=2+458|nivoweltelu=5+702|raavoweltelu=7+937|vasubscripttelu=7+458|hatelu=11+1040|katelu=12+522</pre>



<pre>Got     : kaavoweltelu=0+867|ratelu=2+593|yasubscripttelu=2+458|nivoweltelu=5+702|raavoweltelu=7+906|vasubscripttelu=7+458|hatelu=11+1040|katelu=12+522</pre>



<pre>                                                                                                  ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5546 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(867, 983)"/>
<path d=""  transform="translate(1460, 983)"/>
<path d=""  transform="translate(1918, 983)"/>
<path d=""  transform="translate(2620, 983)"/>
<path d=""  transform="translate(3526, 983)"/>
<path d=""  transform="translate(3984, 983)"/>
<path d=""  transform="translate(5024, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5577 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(867, 983)"/>
<path d=""  transform="translate(1460, 983)"/>
<path d=""  transform="translate(1918, 983)"/>
<path d=""  transform="translate(2620, 983)"/>
<path d=""  transform="translate(3557, 983)"/>
<path d=""  transform="translate(4015, 983)"/>
<path d=""  transform="translate(5055, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">కష్గౄత్ᳲ॑దౄ</span> (Added by SIESTA)</li>


<pre>Expected: katelu=0+522|ssatelu=1+713|gasubscripttelu=1@-156,-30+0|rrvocalicvowelsign1telu=1+801|tahalanttelu=5+778|uni0951=7@-103,293+0|uni1CF2=7+471|datelu=9+679|rrvocalicvowelsigntelu=9+656</pre>



<pre>Got     : katelu=0+522|ssatelu=1+713|gasubscripttelu=1@-156,0+0|rrvocalicvowelsign1telu=1+801|tahalanttelu=5+778|uni0951=7@-103,293+0|uni1CF2=7+471|datelu=9+679|rrvocalicvowelsigntelu=9+656</pre>



<pre>                                                            ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4620 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(522, 983)"/>
<path d=""  transform="translate(1079, 983)"/>
<path d=""  transform="translate(1235, 983)"/>
<path d=""  transform="translate(2036, 983)"/>
<path d=""  transform="translate(2711, 1276)"/>
<path d=""  transform="translate(2814, 983)"/>
<path d=""  transform="translate(3285, 983)"/>
<path d=""  transform="translate(3964, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4620 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(522, 983)"/>
<path d=""  transform="translate(1079, 953)"/>
<path d=""  transform="translate(1235, 983)"/>
<path d=""  transform="translate(2036, 983)"/>
<path d=""  transform="translate(2711, 1276)"/>
<path d=""  transform="translate(2814, 983)"/>
<path d=""  transform="translate(3285, 983)"/>
<path d=""  transform="translate(3964, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">రొౄవఛ॑ఝ॑</span> (Added by SIESTA)</li>


<pre>Expected: rovoweltelu=0+837|rrvocalicvowelsigntelu=0+625|vatelu=3+711|chatelu=4+760|uni0951=4@-94,293+0|jhatelu=6+1286|uni0951=6@-489,293+0</pre>



<pre>Got     : rovoweltelu=0+812|rrvocalicvowelsigntelu=0+625|vatelu=3+711|chatelu=4+760|uni0951=4@-94,293+0|jhatelu=6+1286|uni0951=6@-489,293+0</pre>



<pre>                         ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4194 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(812, 983)"/>
<path d=""  transform="translate(1437, 983)"/>
<path d=""  transform="translate(2148, 983)"/>
<path d=""  transform="translate(2814, 1276)"/>
<path d=""  transform="translate(2908, 983)"/>
<path d=""  transform="translate(3705, 1276)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4219 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(837, 983)"/>
<path d=""  transform="translate(1462, 983)"/>
<path d=""  transform="translate(2173, 983)"/>
<path d=""  transform="translate(2839, 1276)"/>
<path d=""  transform="translate(2933, 983)"/>
<path d=""  transform="translate(3730, 1276)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">వీనెష్లే</span> (Added by SIESTA)</li>


<pre>Expected: viivoweltelu=0+711|nevoweltelu=2+702|sseevoweltelu=4+713|lasubscripttelu=4@-81,-30+0</pre>



<pre>Got     : viivoweltelu=0+711|nevoweltelu=2+702|sseevoweltelu=4+713|lasubscripttelu=4@-81,0+0</pre>



<pre>                                                                                         ++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2126 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(711, 983)"/>
<path d=""  transform="translate(1413, 983)"/>
<path d=""  transform="translate(2045, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2126 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(711, 983)"/>
<path d=""  transform="translate(1413, 983)"/>
<path d=""  transform="translate(2045, 953)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">హహ్బూళ</span> (Added by SIESTA)</li>


<pre>Expected: hatelu=0+1002|hatelu=1+1033|uuvowelsign2telu=1+712|basubscripttelu=1+415|llatelu=5+645</pre>



<pre>Got     : hatelu=0+1002|hatelu=1+1044|uuvowelsign2telu=1+712|basubscripttelu=1+415|llatelu=5+645</pre>



<pre>                                   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3818 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(1002, 983)"/>
<path d=""  transform="translate(2046, 983)"/>
<path d=""  transform="translate(2758, 983)"/>
<path d=""  transform="translate(3173, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3807 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(1002, 983)"/>
<path d=""  transform="translate(2035, 983)"/>
<path d=""  transform="translate(2747, 983)"/>
<path d=""  transform="translate(3162, 983)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* juvoweltelu
	* laavoweltelu
	* ttovoweltelu
	* dzaavoweltelu
	* rraavoweltelu
	* khovoweltelu
	* jhauvoweltelu
	* nyauvoweltelu
	* kasseevoweltelu
	* ddhiivoweltelu and 212 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 696 but it should be 785 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three.telu (U+0033): X=137.0,Y=-1.5 (should be at baseline 0?)

	* eight.telu (U+0038): X=439.0,Y=621.0 (should be at cap-height 620?)

	* ivowelsigntelu (U+0C3F): X=-313.0,Y=621.0 (should be at cap-height 620?)

	* ivowelsigntelu (U+0C3F): X=-289.0,Y=618.0 (should be at cap-height 620?)

	* iivowelsigntelu (U+0C40): X=-236.5,Y=619.5 (should be at cap-height 620?)

	* ovowelsigntelu (U+0C4A): X=272.0,Y=618.5 (should be at cap-height 620?)

	* oovowelsigntelu (U+0C4B): X=272.0,Y=618.5 (should be at cap-height 620?)

	* tsatelu (U+0C58): X=513.5,Y=619.0 (should be at cap-height 620?)

	* threetelu (U+0C69): X=158.5,Y=618.0 (should be at cap-height 620?)

	* fourtelu (U+0C6A): X=266.0,Y=-1.0 (should be at baseline 0?) 

	* And fourtelu (U+0C6A): X=420.0,Y=-1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<169.0,84.0>--<169.0,80.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<282.0,-12.0>--<279.0,-12.0>>

	* iitelu (U+0C08) contains a short segment B<<901.0,278.0>-<910.0,273.0>-<918.0,266.0>>

	* uutelu (U+0C0A) contains a short segment B<<1002.0,291.0>-<1011.0,286.0>-<1019.0,279.0>>

	* rvocalictelu (U+0C0B) contains a short segment B<<118.0,365.0>-<118.0,352.0>-<121.5,341.0>>

	* rvocalictelu (U+0C0B) contains a short segment B<<121.5,341.0>-<125.0,330.0>-<128.0,323.0>>

	* otelu (U+0C12) contains a short segment B<<121.5,341.0>-<125.0,330.0>-<128.0,323.0>>

	* ootelu (U+0C13) contains a short segment B<<121.5,341.0>-<125.0,330.0>-<128.0,323.0>>

	* autelu (U+0C14) contains a short segment B<<118.0,365.0>-<118.0,352.0>-<121.5,341.0>>

	* autelu (U+0C14) contains a short segment B<<121.5,341.0>-<125.0,330.0>-<128.0,323.0>> 

	* And 48 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* nnatelu (U+0C23): L<<708.0,221.0>--<708.0,226.0>> -> L<<708.0,226.0>--<708.0,239.0>> 

	* And uni0C7F (U+0C7F): L<<128.0,259.0>--<128.0,256.0>> -> L<<128.0,256.0>--<128.0,250.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<561.0,409.0>-<565.0,409.0>-<571.0,408.0>>/B<<571.0,408.0>-<541.0,417.0>-<504.0,422.0>> = 7.236922025967975 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansTelugu-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu SemiBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* juvoweltelu
	* rrauvoweltelu
	* moovoweltelu
	* laavoweltelu
	* ttovoweltelu
	* dzaavoweltelu
	* chauvoweltelu
	* rraavoweltelu
	* tthoovoweltelu
	* khovoweltelu and 366 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 730 but it should be 826 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenright.telu (U+0029): X=292.0,Y=-0.5 (should be at baseline 0?)

	* zero.telu (U+0030): X=143.0,Y=621.0 (should be at cap-height 620?)

	* three.telu (U+0033): X=135.0,Y=-0.5 (should be at baseline 0?)

	* three.telu (U+0033): X=444.5,Y=618.5 (should be at cap-height 620?)

	* nine.telu (U+0039): X=90.0,Y=-2.0 (should be at baseline 0?)

	* itelu (U+0C07): X=643.0,Y=1.0 (should be at baseline 0?)

	* itelu (U+0C07): X=533.0,Y=2.0 (should be at baseline 0?)

	* itelu (U+0C07): X=434.0,Y=-0.5 (should be at baseline 0?)

	* nyatelu (U+0C1E): X=643.0,Y=1.0 (should be at baseline 0?)

	* nyatelu (U+0C1E): X=533.0,Y=2.0 (should be at baseline 0?) 

	* And 9 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<213.0,113.0>--<213.0,108.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<294.0,-12.0>--<292.0,-12.0>>

	* iitelu (U+0C08) contains a short segment B<<935.0,277.0>-<940.0,274.0>-<945.0,270.0>>

	* uutelu (U+0C0A) contains a short segment B<<408.0,500.0>-<425.0,500.0>-<441.0,499.0>>

	* uutelu (U+0C0A) contains a short segment B<<1010.0,406.5>-<998.0,417.0>-<979.0,417.0>>

	* uutelu (U+0C0A) contains a short segment B<<1065.0,288.0>-<1070.0,284.0>-<1076.0,280.0>>

	* rvocalictelu (U+0C0B) contains a short segment B<<150.0,361.0>-<150.0,348.0>-<153.5,338.0>>

	* rvocalictelu (U+0C0B) contains a short segment B<<153.5,338.0>-<157.0,328.0>-<159.0,322.0>>

	* aitelu (U+0C10) contains a short segment B<<150.0,358.0>-<150.0,350.0>-<152.0,339.5>>

	* aitelu (U+0C10) contains a short segment B<<152.0,339.5>-<154.0,329.0>-<157.0,321.0>> 

	* And 62 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* lllatelu (U+0C34): L<<149.0,244.0>--<149.0,243.0>> -> L<<149.0,243.0>--<149.0,231.0>> 

	* And ttatelu (U+0C1F): L<<149.0,244.0>--<149.0,243.0>> -> L<<149.0,243.0>--<149.0,231.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* natelu (U+0C28): L<<257.0,407.0>--<257.0,407.0>>/B<<257.0,407.0>-<198.0,408.0>-<157.0,440.5>> = 0.9710219310788218 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansTelugu-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu Thin [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 641 but it should be 719 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 56 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* period.telu (U+002E): X=124.5,Y=1.0 (should be at baseline 0?)

	* period.telu (U+002E): X=82.0,Y=1.0 (should be at baseline 0?)

	* zero.telu (U+0030): X=422.0,Y=618.5 (should be at cap-height 620?)

	* two.telu (U+0032): X=180.0,Y=619.0 (should be at cap-height 620?)

	* three.telu (U+0033): X=414.5,Y=621.0 (should be at cap-height 620?)

	* nine.telu (U+0039): X=94.0,Y=1.0 (should be at baseline 0?)

	* colon.telu (U+003A): X=124.5,Y=1.0 (should be at baseline 0?)

	* colon.telu (U+003A): X=82.0,Y=1.0 (should be at baseline 0?)

	* question.telu (U+003F): X=346.5,Y=621.5 (should be at cap-height 620?)

	* question.telu (U+003F): X=294.5,Y=621.0 (should be at cap-height 620?) 

	* And 31 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<98.0,28.0>--<98.0,26.0>>

	* question.telu (U+003F) contains a short segment L<<186.0,159.0>--<186.0,169.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<262.0,-12.0>--<258.0,-12.0>>

	* atelu (U+0C05) contains a short segment B<<70.0,302.0>-<69.0,289.0>-<69.0,275.0>>

	* atelu (U+0C05) contains a short segment L<<272.0,215.0>--<272.0,240.0>>

	* iitelu (U+0C08) contains a short segment B<<96.0,240.0>-<96.0,249.0>-<96.0,257.0>>

	* iitelu (U+0C08) contains a short segment L<<30.0,257.0>--<30.0,282.0>>

	* iitelu (U+0C08) contains a short segment B<<311.0,492.0>-<317.0,493.0>-<323.0,493.0>>

	* iitelu (U+0C08) contains a short segment B<<571.0,257.0>-<571.0,248.0>-<571.0,238.0>>

	* utelu (U+0C09) contains a short segment L<<719.0,292.0>--<719.0,267.0>> 

	* And 39 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* llatelu (U+0C33): B<<200.5,143.0>-<225.0,166.0>-<267.0,174.0>>/B<<267.0,174.0>-<141.0,180.0>-<86.0,219.5>> = 13.510608861468855 

	* And tatelu (U+0C24): B<<592.5,392.5>-<613.0,383.0>-<629.0,368.0>>/B<<629.0,368.0>-<607.0,400.0>-<568.5,421.0>> = 12.33908727832621 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.telu (U+0021): L<<120.0,162.0>--<118.0,657.0>> 

	* And exclam.telu (U+0021): L<<146.0,657.0>--<144.0,162.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[18] NotoSansTeluguUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu UI Black [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nnaivowelUItelu

	- chaivowelUItelu

	- llaivowelUItelu

	- shasubscript1UItelu

	- rrraivowelUItelu

	- ttaivowelUItelu

	- dhailengthmark1UItelu

	- hailengthmark1UItelu

	- lvocalicvowelsign1UItelu

	- ghailengthmarkUItelu 

	- And 114 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 793 but it should be 870 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48) and viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* eight.telu (U+0038): X=286.0,Y=621.0 (should be at cap-height 620?)

	* eight.telu (U+0038): X=286.0,Y=621.0 (should be at cap-height 620?)

	* iitelu (U+0C08): X=584.0,Y=619.0 (should be at cap-height 620?)

	* autelu (U+0C14): X=487.0,Y=619.0 (should be at cap-height 620?)

	* katelu (U+0C15): X=519.0,Y=619.0 (should be at cap-height 620?)

	* gatelu (U+0C17): X=549.0,Y=619.0 (should be at cap-height 620?)

	* ghatelu (U+0C18): X=490.0,Y=619.0 (should be at cap-height 620?)

	* catelu (U+0C1A): X=691.0,Y=619.0 (should be at cap-height 620?)

	* chatelu (U+0C1B): X=691.0,Y=619.0 (should be at cap-height 620?)

	* jhatelu (U+0C1D): X=539.0,Y=619.0 (should be at cap-height 620?) 

	* And 29 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* khatelu (U+0C16): B<<291.0,369.5>-<266.0,346.0>-<219.0,339.0>>/B<<219.0,339.0>-<252.0,336.0>-<280.0,327.0>> = 13.665573540749627

	* rrvocalicvowelsignUItelu (U+0C44): B<<54.0,-144.0>-<33.0,-144.0>-<11.0,-140.0>>/B<<11.0,-140.0>-<45.0,-154.0>-<113.0,-154.0>> = 12.075288583193531 

	* And rvocalicvowelsignUItelu (U+0C43): B<<54.0,-144.0>-<33.0,-144.0>-<11.0,-140.0>>/B<<11.0,-140.0>-<45.0,-154.0>-<113.0,-154.0>> = 12.075288583193531 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSansTeluguUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nnaivowelUItelu

	- chaivowelUItelu

	- llaivowelUItelu

	- shasubscript1UItelu

	- rrraivowelUItelu

	- ttaivowelUItelu

	- dhailengthmark1UItelu

	- hailengthmark1UItelu

	- lvocalicvowelsign1UItelu

	- ghailengthmarkUItelu 

	- And 114 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 751 but it should be 820 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48) and viramatelu (U+0C4D) [code: mark-chars]
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

	* autelu (U+0C14): X=473.0,Y=622.0 (should be at cap-height 620?)

	* ssatelu (U+0C37): X=820.0,Y=2.0 (should be at baseline 0?)

	* iivowelsigntelu (U+0C40): X=-227.5,Y=618.0 (should be at cap-height 620?)

	* rvocalicvowelsignUItelu (U+0C43): X=42.0,Y=-2.0 (should be at baseline 0?)

	* rvocalicvowelsignUItelu (U+0C43): X=42.0,Y=-2.0 (should be at baseline 0?) 

	* And 21 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* llatelu (U+0C33): B<<268.5,532.0>-<296.0,526.0>-<316.0,516.0>>/B<<316.0,516.0>-<289.0,534.0>-<269.5,567.5>> = 7.125016348901757

	* llatelu (U+0C33): B<<421.0,489.0>-<367.0,489.0>-<330.0,508.0>>/B<<330.0,508.0>-<356.0,490.0>-<366.5,466.5>> = 7.514042445756763

	* natelu (U+0C28): L<<269.0,489.0>--<269.0,489.0>>/B<<269.0,489.0>-<201.0,491.0>-<157.5,527.0>> = 1.68468431789628

	* rrvocalicvowelsignUItelu (U+0C44): B<<42.0,-161.0>-<23.0,-161.0>-<6.0,-157.0>>/B<<6.0,-157.0>-<41.0,-172.0>-<110.0,-172.0>> = 9.958070598460957 

	* And rvocalicvowelsignUItelu (U+0C43): B<<42.0,-161.0>-<23.0,-161.0>-<6.0,-157.0>>/B<<6.0,-157.0>-<41.0,-172.0>-<110.0,-172.0>> = 9.958070598460957 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[18] NotoSansTeluguUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu UI ExtraBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nnaivowelUItelu

	- chaivowelUItelu

	- llaivowelUItelu

	- shasubscript1UItelu

	- rrraivowelUItelu

	- ttaivowelUItelu

	- dhailengthmark1UItelu

	- hailengthmark1UItelu

	- lvocalicvowelsign1UItelu

	- ghailengthmarkUItelu 

	- And 114 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 770 but it should be 843 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48) and viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* zero.telu (U+0030): X=285.0,Y=622.0 (should be at cap-height 620?)

	* two.telu (U+0032): X=275.0,Y=618.0 (should be at cap-height 620?)

	* eight.telu (U+0038): X=232.5,Y=619.5 (should be at cap-height 620?)

	* iitelu (U+0C08): X=316.0,Y=619.5 (should be at cap-height 620?)

	* autelu (U+0C14): X=479.0,Y=621.0 (should be at cap-height 620?)

	* katelu (U+0C15): X=246.5,Y=619.5 (should be at cap-height 620?)

	* gatelu (U+0C17): X=283.5,Y=619.5 (should be at cap-height 620?)

	* ghatelu (U+0C18): X=219.5,Y=619.5 (should be at cap-height 620?)

	* catelu (U+0C1A): X=421.5,Y=619.5 (should be at cap-height 620?)

	* chatelu (U+0C1B): X=421.5,Y=619.5 (should be at cap-height 620?) 

	* And 41 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* bhatelu (U+0C2D): B<<503.0,485.0>-<445.0,492.0>-<409.0,527.0>>/B<<409.0,527.0>-<427.0,498.0>-<427.0,461.0>> = 13.979482878429264

	* rrvocalicvowelsignUItelu (U+0C44): B<<48.0,-153.0>-<28.0,-153.0>-<9.0,-149.0>>/B<<9.0,-149.0>-<44.0,-164.0>-<111.0,-164.0>> = 11.309932474020195

	* rvocalicvowelsignUItelu (U+0C43): B<<48.0,-153.0>-<28.0,-153.0>-<9.0,-149.0>>/B<<9.0,-149.0>-<44.0,-164.0>-<111.0,-164.0>> = 11.309932474020195

	* ssatelu (U+0C37): B<<538.0,78.0>-<538.0,81.0>-<539.0,81.0>>/B<<539.0,81.0>-<491.0,83.0>-<453.0,98.5>> = 2.3859440303887243 

	* And tatelu (U+0C24): B<<472.0,377.0>-<472.0,454.0>-<542.0,487.0>>/B<<542.0,487.0>-<522.0,483.0>-<500.0,483.0>> = 13.930596790766563 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansTeluguUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu UI ExtraLight [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nnaivowelUItelu

	- chaivowelUItelu

	- llaivowelUItelu

	- shasubscript1UItelu

	- rrraivowelUItelu

	- ttaivowelUItelu

	- dhailengthmark1UItelu

	- hailengthmark1UItelu

	- lvocalicvowelsign1UItelu

	- ghailengthmarkUItelu 

	- And 114 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 651 but it should be 704 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48) and viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* divide.telu (U+00F7): X=261.0,Y=622.0 (should be at cap-height 620?)

	* divide.telu (U+00F7): X=311.0,Y=622.0 (should be at cap-height 620?)

	* itelu (U+0C07): X=524.0,Y=1.0 (should be at baseline 0?)

	* nyatelu (U+0C1E): X=524.0,Y=1.0 (should be at baseline 0?)

	* ssatelu (U+0C37): X=740.0,Y=2.0 (should be at baseline 0?)

	* aivowelsignUItelu (U+0C48): X=-366.0,Y=1.0 (should be at baseline 0?)

	* aivowelsignUItelu (U+0C48): X=-523.0,Y=1.0 (should be at baseline 0?)

	* ailengthmarkUItelu (U+0C56): X=-366.0,Y=1.0 (should be at baseline 0?)

	* ailengthmarkUItelu (U+0C56): X=-523.0,Y=1.0 (should be at baseline 0?)

	* llvocalicvowelsignUItelu (U+0C63): X=78.0,Y=0.5 (should be at baseline 0?) 

	* And 14 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<112.0,132.0>--<112.0,130.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<266.0,81.0>--<262.0,81.0>>

	* atelu (U+0C05) contains a short segment B<<79.0,386.0>-<78.0,378.0>-<78.0,369.0>>

	* aatelu (U+0C06) contains a short segment B<<79.0,386.0>-<78.0,378.0>-<78.0,369.0>>

	* iitelu (U+0C08) contains a short segment B<<95.0,332.0>-<95.0,339.0>-<96.0,345.0>>

	* iitelu (U+0C08) contains a short segment B<<314.0,587.0>-<317.0,587.0>-<319.0,587.0>>

	* iitelu (U+0C08) contains a short segment B<<319.0,587.0>-<320.0,587.0>-<322.0,587.0>>

	* iitelu (U+0C08) contains a short segment B<<580.0,345.0>-<580.0,338.0>-<580.0,331.0>>

	* uutelu (U+0C0A) contains a short segment B<<85.0,356.0>-<82.0,339.0>-<80.5,321.0>>

	* uutelu (U+0C0A) contains a short segment B<<80.5,321.0>-<79.0,303.0>-<79.0,284.0>> 

	* And 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<586.0,489.5>-<603.0,483.0>-<617.0,473.0>>/B<<617.0,473.0>-<594.0,498.0>-<558.5,515.0>> = 11.8482662384144 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansTeluguUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu UI Light [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nnaivowelUItelu

	- chaivowelUItelu

	- llaivowelUItelu

	- shasubscript1UItelu

	- rrraivowelUItelu

	- ttaivowelUItelu

	- dhailengthmark1UItelu

	- hailengthmark1UItelu

	- lvocalicvowelsign1UItelu

	- ghailengthmarkUItelu 

	- And 114 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 668 but it should be 723 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48) and viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* four.telu (U+0034): X=379.5,Y=618.5 (should be at cap-height 620?)

	* ssatelu (U+0C37): X=553.0,Y=-1.5 (should be at baseline 0?)

	* lvocalicvowelsignUItelu (U+0C62): X=-311.5,Y=2.0 (should be at baseline 0?)

	* lvocalicvowelsignUItelu (U+0C62): X=-405.0,Y=2.0 (should be at baseline 0?)

	* llvocalicvowelsignUItelu (U+0C63): X=-311.5,Y=2.0 (should be at baseline 0?)

	* llvocalicvowelsignUItelu (U+0C63): X=-405.0,Y=2.0 (should be at baseline 0?)

	* sixtelu (U+0C6C): X=74.0,Y=621.5 (should be at cap-height 620?)

	* uni0C7E (U+0C7E): X=416.0,Y=619.0 (should be at cap-height 620?)

	* quoteleft.telu (U+2018): X=69.0,Y=622.0 (should be at cap-height 620?)

	* quoteleft.telu (U+2018): X=131.0,Y=622.0 (should be at cap-height 620?) 

	* And 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<134.0,149.0>--<134.0,146.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<272.0,81.0>--<269.0,81.0>>

	* atelu (U+0C05) contains a short segment L<<92.0,371.0>--<92.0,363.0>>

	* aatelu (U+0C06) contains a short segment L<<92.0,371.0>--<92.0,363.0>>

	* iitelu (U+0C08) contains a short segment B<<95.0,331.0>-<95.0,335.0>-<95.0,338.0>>

	* iitelu (U+0C08) contains a short segment B<<593.0,338.0>-<594.0,335.0>-<594.0,331.0>>

	* iitelu (U+0C08) contains a short segment B<<540.0,333.0>-<540.0,333.0>-<539.5,333.5>>

	* iitelu (U+0C08) contains a short segment B<<539.5,333.5>-<539.0,334.0>-<539.0,338.0>>

	* iitelu (U+0C08) contains a short segment L<<149.0,338.0>--<149.0,337.0>>

	* uutelu (U+0C0A) contains a short segment B<<377.0,590.0>-<399.0,590.0>-<419.0,588.0>> 

	* And 40 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* aatelu (U+0C06): L<<92.0,372.0>--<92.0,371.0>> -> L<<92.0,371.0>--<92.0,363.0>> 

	* And atelu (U+0C05): L<<92.0,372.0>--<92.0,371.0>> -> L<<92.0,371.0>--<92.0,363.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<576.0,496.0>-<587.0,493.0>-<598.0,488.0>>/B<<598.0,488.0>-<564.0,512.0>-<512.5,525.0>> = 10.773638187776136 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansTeluguUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu UI Medium [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nnaivowelUItelu

	- chaivowelUItelu

	- llaivowelUItelu

	- shasubscript1UItelu

	- rrraivowelUItelu

	- ttaivowelUItelu

	- dhailengthmark1UItelu

	- hailengthmark1UItelu

	- lvocalicvowelsign1UItelu

	- ghailengthmarkUItelu 

	- And 114 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 712 but it should be 774 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48) and viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft.telu (U+0028): X=93.0,Y=-1.0 (should be at baseline 0?)

	* parenright.telu (U+0029): X=168.0,Y=2.0 (should be at baseline 0?)

	* autelu (U+0C14): X=459.0,Y=621.0 (should be at cap-height 620?)

	* ssatelu (U+0C37): X=560.5,Y=-1.0 (should be at baseline 0?)

	* ivowelsigntelu (U+0C3F): X=-384.0,Y=618.0 (should be at cap-height 620?)

	* iivowelsigntelu (U+0C40): X=-384.0,Y=618.0 (should be at cap-height 620?)

	* auvowelsigntelu (U+0C4C): X=2.0,Y=621.0 (should be at cap-height 620?)

	* lengthmarktelu (U+0C55): X=-211.0,Y=621.0 (should be at cap-height 620?)

	* lvocalicvowelsignUItelu (U+0C62): X=-5.0,Y=1.0 (should be at baseline 0?)

	* sixtelu (U+0C6C): X=72.0,Y=619.0 (should be at cap-height 620?) 

	* And 18 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<190.0,191.0>--<190.0,186.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<288.0,81.0>--<285.0,81.0>>

	* iitelu (U+0C08) contains a short segment B<<917.0,371.0>-<924.0,366.0>-<931.0,361.0>>

	* uutelu (U+0C0A) contains a short segment B<<1032.0,382.0>-<1039.0,378.0>-<1046.0,373.0>>

	* rvocalictelu (U+0C0B) contains a short segment B<<133.0,456.0>-<133.0,443.0>-<136.5,432.5>>

	* rvocalictelu (U+0C0B) contains a short segment B<<136.5,432.5>-<140.0,422.0>-<143.0,416.0>>

	* aitelu (U+0C10) contains a short segment B<<134.0,455.0>-<134.0,446.0>-<136.0,434.5>>

	* aitelu (U+0C10) contains a short segment B<<136.0,434.5>-<138.0,423.0>-<142.0,415.0>>

	* otelu (U+0C12) contains a short segment B<<136.5,432.5>-<140.0,422.0>-<143.0,416.0>>

	* ootelu (U+0C13) contains a short segment B<<136.5,432.5>-<140.0,422.0>-<143.0,416.0>> 

	* And 50 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* natelu (U+0C28): L<<247.0,509.0>--<247.0,509.0>>/B<<247.0,509.0>-<213.0,510.0>-<184.0,522.5>> = 1.68468431789628 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[19] NotoSansTeluguUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu UI [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nnaivowelUItelu

	- chaivowelUItelu

	- llaivowelUItelu

	- shasubscript1UItelu

	- rrraivowelUItelu

	- ttaivowelUItelu

	- dhailengthmark1UItelu

	- hailengthmark1UItelu

	- lvocalicvowelsign1UItelu

	- ghailengthmarkUItelu 

	- And 114 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 696 but it should be 755 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48) and viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* asterisk.telu (U+002A): X=339.0,Y=621.0 (should be at cap-height 620?)

	* asterisk.telu (U+002A): X=238.0,Y=621.0 (should be at cap-height 620?)

	* iitelu (U+0C08): X=481.0,Y=619.0 (should be at cap-height 620?)

	* katelu (U+0C15): X=393.0,Y=619.0 (should be at cap-height 620?)

	* gatelu (U+0C17): X=423.0,Y=619.0 (should be at cap-height 620?)

	* ghatelu (U+0C18): X=356.0,Y=619.0 (should be at cap-height 620?)

	* catelu (U+0C1A): X=546.0,Y=619.0 (should be at cap-height 620?)

	* chatelu (U+0C1B): X=546.0,Y=619.0 (should be at cap-height 620?)

	* jhatelu (U+0C1D): X=424.0,Y=619.0 (should be at cap-height 620?)

	* tthatelu (U+0C20): X=424.0,Y=619.0 (should be at cap-height 620?) 

	* And 40 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<169.0,177.0>--<169.0,173.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<282.0,81.0>--<279.0,81.0>>

	* iitelu (U+0C08) contains a short segment B<<901.0,371.0>-<910.0,366.0>-<918.0,359.0>>

	* uutelu (U+0C0A) contains a short segment B<<1002.0,384.0>-<1011.0,379.0>-<1019.0,372.0>>

	* rvocalictelu (U+0C0B) contains a short segment B<<118.0,458.0>-<118.0,445.0>-<121.5,434.0>>

	* rvocalictelu (U+0C0B) contains a short segment B<<121.5,434.0>-<125.0,423.0>-<128.0,416.0>>

	* otelu (U+0C12) contains a short segment B<<121.5,434.0>-<125.0,423.0>-<128.0,416.0>>

	* ootelu (U+0C13) contains a short segment B<<121.5,434.0>-<125.0,423.0>-<128.0,416.0>>

	* autelu (U+0C14) contains a short segment B<<118.0,458.0>-<118.0,445.0>-<121.5,434.0>>

	* autelu (U+0C14) contains a short segment B<<121.5,434.0>-<125.0,423.0>-<128.0,416.0>> 

	* And 48 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* nnatelu (U+0C23): L<<708.0,314.0>--<708.0,319.0>> -> L<<708.0,319.0>--<708.0,332.0>> 

	* And uni0C7F (U+0C7F): L<<128.0,352.0>--<128.0,349.0>> -> L<<128.0,349.0>--<128.0,343.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* tatelu (U+0C24): B<<561.0,502.0>-<565.0,502.0>-<571.0,501.0>>/B<<571.0,501.0>-<541.0,510.0>-<504.0,515.0>> = 7.236922025967975 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansTeluguUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu UI SemiBold [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nnaivowelUItelu

	- chaivowelUItelu

	- llaivowelUItelu

	- shasubscript1UItelu

	- rrraivowelUItelu

	- ttaivowelUItelu

	- dhailengthmark1UItelu

	- hailengthmark1UItelu

	- lvocalicvowelsign1UItelu

	- ghailengthmarkUItelu 

	- And 114 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 730 but it should be 796 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48) and viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenright.telu (U+0029): X=155.0,Y=-2.0 (should be at baseline 0?)

	* asterisk.telu (U+002A): X=529.0,Y=622.0 (should be at cap-height 620?)

	* nine.telu (U+0039): X=193.5,Y=622.0 (should be at cap-height 620?)

	* lvocalictelu (U+0C0C): X=582.0,Y=1.0 (should be at baseline 0?)

	* lvocalictelu (U+0C0C): X=582.0,Y=1.0 (should be at baseline 0?)

	* autelu (U+0C14): X=465.0,Y=621.0 (should be at cap-height 620?)

	* ivowelsigntelu (U+0C3F): X=-389.0,Y=621.0 (should be at cap-height 620?)

	* iivowelsigntelu (U+0C40): X=-389.0,Y=621.0 (should be at cap-height 620?)

	* auvowelsigntelu (U+0C4C): X=8.0,Y=621.0 (should be at cap-height 620?)

	* lengthmarktelu (U+0C55): X=-205.5,Y=619.0 (should be at cap-height 620?) 

	* And 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<213.0,206.0>--<213.0,201.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<294.0,81.0>--<292.0,81.0>>

	* iitelu (U+0C08) contains a short segment B<<935.0,370.0>-<940.0,367.0>-<945.0,363.0>>

	* uutelu (U+0C0A) contains a short segment B<<408.0,593.0>-<425.0,593.0>-<441.0,592.0>>

	* uutelu (U+0C0A) contains a short segment B<<1010.0,499.5>-<998.0,510.0>-<979.0,510.0>>

	* uutelu (U+0C0A) contains a short segment B<<1065.0,381.0>-<1070.0,377.0>-<1076.0,373.0>>

	* rvocalictelu (U+0C0B) contains a short segment B<<150.0,454.0>-<150.0,441.0>-<153.5,431.0>>

	* rvocalictelu (U+0C0B) contains a short segment B<<153.5,431.0>-<157.0,421.0>-<159.0,415.0>>

	* aitelu (U+0C10) contains a short segment B<<150.0,451.0>-<150.0,443.0>-<152.0,432.5>>

	* aitelu (U+0C10) contains a short segment B<<152.0,432.5>-<154.0,422.0>-<157.0,414.0>> 

	* And 62 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* lllatelu (U+0C34): L<<149.0,337.0>--<149.0,336.0>> -> L<<149.0,336.0>--<149.0,324.0>> 

	* And ttatelu (U+0C1F): L<<149.0,337.0>--<149.0,336.0>> -> L<<149.0,336.0>--<149.0,324.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* natelu (U+0C28): L<<257.0,500.0>--<257.0,500.0>>/B<<257.0,500.0>-<198.0,501.0>-<157.0,533.5>> = 0.9710219310788218 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[20] NotoSansTeluguUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x0030 (DIGIT ZERO)


	- 0x0031 (DIGIT ONE)


	- 0x0032 (DIGIT TWO)


	- 0x0033 (DIGIT THREE)


	- 0x0034 (DIGIT FOUR)


	- 0x0035 (DIGIT FIVE)


	- 0x0036 (DIGIT SIX)


	- 0x0037 (DIGIT SEVEN)


	- 0x0038 (DIGIT EIGHT)


	- 0x0039 (DIGIT NINE)
 

	- And 321 more.

Use -F or --full-lists to disable shortening of long lists. [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font can render its own name. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/render_own_name">com.google.fonts/check/render_own_name</a>)</summary><div>


* 🔥 **FAIL** .notdef glyphs were found when attempting to render Noto Sans Telugu UI Thin [code: render-own-name]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 480, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Telugu UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nnaivowelUItelu

	- chaivowelUItelu

	- llaivowelUItelu

	- shasubscript1UItelu

	- rrraivowelUItelu

	- ttaivowelUItelu

	- dhailengthmark1UItelu

	- hailengthmark1UItelu

	- lvocalicvowelsign1UItelu

	- ghailengthmarkUItelu 

	- And 114 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check if OS/2 xAvgCharWidth is correct. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/xavgcharwidth">com.google.fonts/check/xavgcharwidth</a>)</summary><div>


* ⚠ **WARN** OS/2 xAvgCharWidth is 641 but it should be 692 which corresponds to the average of the widths of all glyphs in the font. [code: xAvgCharWidth-wrong]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), casubscript1telu (unencoded), casubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 60 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 ailengthmarkUItelu (U+0C56), aivowelsignUItelu (U+0C48) and viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* divide.telu (U+00F7): X=265.0,Y=618.5 (should be at cap-height 620?)

	* divide.telu (U+00F7): X=307.5,Y=618.5 (should be at cap-height 620?)

	* itelu (U+0C07): X=525.0,Y=-1.0 (should be at baseline 0?)

	* eetelu (U+0C0F): X=189.0,Y=619.0 (should be at cap-height 620?)

	* nyatelu (U+0C1E): X=525.0,Y=-1.0 (should be at baseline 0?)

	* ssatelu (U+0C37): X=733.0,Y=-1.0 (should be at baseline 0?)

	* aivowelsignUItelu (U+0C48): X=-373.0,Y=-1.0 (should be at baseline 0?)

	* aivowelsignUItelu (U+0C48): X=-519.5,Y=-1.5 (should be at baseline 0?)

	* ailengthmarkUItelu (U+0C56): X=-373.0,Y=-1.0 (should be at baseline 0?)

	* ailengthmarkUItelu (U+0C56): X=-519.5,Y=-1.5 (should be at baseline 0?) 

	* And 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two.telu (U+0032) contains a short segment L<<98.0,121.0>--<98.0,119.0>>

	* question.telu (U+003F) contains a short segment L<<186.0,252.0>--<186.0,262.0>>

	* candrabindutelu (U+0C01) contains a short segment L<<262.0,81.0>--<258.0,81.0>>

	* atelu (U+0C05) contains a short segment B<<70.0,395.0>-<69.0,382.0>-<69.0,368.0>>

	* atelu (U+0C05) contains a short segment L<<272.0,308.0>--<272.0,333.0>>

	* iitelu (U+0C08) contains a short segment B<<96.0,333.0>-<96.0,342.0>-<96.0,350.0>>

	* iitelu (U+0C08) contains a short segment L<<30.0,350.0>--<30.0,375.0>>

	* iitelu (U+0C08) contains a short segment B<<311.0,585.0>-<317.0,586.0>-<323.0,586.0>>

	* iitelu (U+0C08) contains a short segment B<<571.0,350.0>-<571.0,341.0>-<571.0,331.0>>

	* utelu (U+0C09) contains a short segment L<<719.0,385.0>--<719.0,360.0>> 

	* And 39 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* llatelu (U+0C33): B<<200.5,236.0>-<225.0,259.0>-<267.0,267.0>>/B<<267.0,267.0>-<141.0,273.0>-<86.0,312.5>> = 13.510608861468855 

	* And tatelu (U+0C24): B<<592.5,485.5>-<613.0,476.0>-<629.0,461.0>>/B<<629.0,461.0>-<607.0,493.0>-<568.5,514.0>> = 12.33908727832621 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.telu (U+0021): L<<120.0,255.0>--<118.0,750.0>> 

	* And exclam.telu (U+0021): L<<146.0,750.0>--<144.0,255.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSansTelugu[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansTelugu/googlefonts/slim-variable-ttf/NotoSansTelugu[wght].ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTelugu-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Black.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Bold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-ExtraLight.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Light.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Medium.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Regular.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-SemiBold.ttf', 'fonts/NotoSansTelugu/googlefonts/ttf/NotoSansTeluguUI-Thin.ttf', 'fonts/NotoSansTelugu/googlefonts/variable-ttf/NotoSansTelugu[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 995, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0C00

	- uni0951

	- uni0952

	- uni0C04 

	- And uni1CDA [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking font version fields (head and name table). (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/font_version">com.google.fonts/check/font_version</a>)</summary><div>


* 🔥 **FAIL** head version is "2.00200" while name version string (for platform 3, encoding 1) is "Version 2.001". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 292. [code: invalid-default-instance-subfamily-nameid:292]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- comma

	- taalttelu

	- dhailengthmark1UItelu

	- parenright

	- ttailengthmarkUItelu

	- bracketright

	- jailengthmarkUItelu

	- khaivowelUItelu

	- seven

	- ddasubscript1UItelu 

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
| 0 | 166 | 205 | 2265 | 141 | 1638 | 0 |
| 0% | 4% | 5% | 51% | 3% | 37% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
