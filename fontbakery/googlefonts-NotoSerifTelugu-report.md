## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[3] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[24] NotoSerifTelugu[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 278. [code: invalid-default-instance-subfamily-nameid:278]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 278. [code: invalid-default-instance-subfamily-nameid:278]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- exclam

	- quotedblright 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- exclam

	- quotedblright 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded), ddasubscript1telu (unencoded) and 53 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded), ddasubscript1telu (unencoded) and 53 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhahalanttelu
	* saavoweltelu
	* vuvoweltelu
	* reevoweltelu
	* khovoweltelu
	* auvowelsigntelu
	* divoweltelu
	* gailengthmarktelu
	* ssevoweltelu
	* ghevoweltelu and 356 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- nbspace

	- exclam 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded), ddasubscript1telu (unencoded) and 53 more.

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

	* V (U+0056): B<<402.5,227.0>-<406.0,208.0>-<407.0,194.0>>/B<<407.0,194.0>-<409.0,211.0>-<416.0,238.5>> = 10.79545358773178

	* eogonek (U+0119): B<<282.5,-58.0>-<309.0,-25.0>-<346.0,-9.0>>/B<<346.0,-9.0>-<340.0,-10.0>-<333.5,-10.0>> = 13.922898849188117

	* four.telu (U+0034): B<<268.5,464.0>-<270.0,505.0>-<274.0,548.0>>/B<<274.0,548.0>-<266.0,523.0>-<248.0,488.0>> = 12.430125955112173

	* y (U+0079): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* yacute (U+00FD): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* yatelu (U+0C2F): B<<729.5,399.0>-<677.0,442.0>-<563.0,454.0>>/L<<563.0,454.0>--<563.0,454.0>> = 6.009005957494474

	* ycircumflex (U+0177): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* ydieresis (U+00FF): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 

	* And ygrave (U+1EF3): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] NotoSerifTelugu-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhahalanttelu
	* saavoweltelu
	* vuvoweltelu
	* reevoweltelu
	* khovoweltelu
	* auvowelsigntelu
	* bhauvoweltelu
	* tsiivoweltelu
	* vauvoweltelu
	* gauvoweltelu and 280 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- nbspace

	- exclam 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded), ddasubscript1telu (unencoded) and 53 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), dotaccentcomb (U+0307), gravecomb (U+0300) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhahalanttelu
	* saavoweltelu
	* vuvoweltelu
	* reevoweltelu
	* khovoweltelu
	* auvowelsigntelu
	* ssevoweltelu
	* ghevoweltelu
	* bhauvoweltelu
	* tsiivoweltelu and 321 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- nbspace

	- exclam 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded), ddasubscript1telu (unencoded) and 53 more.

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

	* khatelu (U+0C16): B<<283.0,300.5>-<256.0,274.0>-<209.0,268.0>>/B<<209.0,268.0>-<250.0,265.0>-<282.5,256.0>> = 11.459921083007638

	* khatelu (U+0C16): B<<56.0,227.0>-<89.0,262.0>-<152.0,267.0>>/B<<152.0,267.0>-<100.0,274.0>-<71.0,303.5>> = 12.204576769720791

	* y (U+0079): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* yacute (U+00FD): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ycircumflex (U+0177): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ydieresis (U+00FF): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124 

	* And ygrave (U+1EF3): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<444.0,335.0>--<285.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSerifTelugu-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* vauvoweltelu
	* gauvoweltelu
	* thauvoweltelu
	* dauvoweltelu
	* ddhauvoweltelu
	* tthauvoweltelu
	* rrauvoweltelu
	* hauvoweltelu
	* ssauvoweltelu
	* nyauvoweltelu and 10 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- nbspace

	- exclam 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), candrabindu_0952telu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 54 more.

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

	* aatelu (U+0C06): B<<122.0,381.0>-<122.0,417.0>-<149.0,445.0>>/B<<149.0,445.0>-<115.0,420.0>-<93.0,378.5>> = 9.71480072388966

	* atelu (U+0C05): B<<122.0,381.0>-<122.0,417.0>-<149.0,445.0>>/B<<149.0,445.0>-<115.0,420.0>-<93.0,378.5>> = 9.71480072388966

	* ddatelu (U+0C21): B<<583.0,66.5>-<612.0,105.0>-<615.0,172.0>>/B<<615.0,172.0>-<606.0,136.0>-<583.0,114.5>> = 11.472473256461464

	* ddhatelu (U+0C22): B<<583.0,66.5>-<612.0,105.0>-<615.0,172.0>>/B<<615.0,172.0>-<606.0,136.0>-<583.0,114.5>> = 11.472473256461464

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648

	* latelu (U+0C32): B<<127.0,412.5>-<132.0,427.0>-<145.0,441.0>>/B<<145.0,441.0>-<112.0,417.0>-<91.5,376.5>> = 11.093723011557817

	* llatelu (U+0C33): B<<108.5,408.5>-<116.0,428.0>-<133.0,443.0>>/B<<133.0,443.0>-<102.0,427.0>-<84.0,398.5>> = 14.124093413669847

	* lllatelu (U+0C34): B<<665.0,346.0>-<648.0,400.0>-<609.0,434.0>>/B<<609.0,434.0>-<617.0,424.0>-<621.0,411.0>> = 10.258440609977272

	* nnatelu (U+0C23): B<<638.0,114.0>-<638.0,60.0>-<604.0,28.0>>/B<<604.0,28.0>-<647.0,52.0>-<673.0,101.5>> = 14.096682031493804

	* tatelu (U+0C24): B<<111.5,336.0>-<118.0,354.0>-<132.0,370.0>>/B<<132.0,370.0>-<103.0,350.0>-<86.5,317.5>> = 14.221786146780405 

	* And 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* bhauvoweltelu
	* vauvoweltelu
	* gauvoweltelu
	* moovoweltelu
	* chauvoweltelu
	* dzoovoweltelu
	* thauvoweltelu
	* phauvoweltelu
	* tsauvoweltelu
	* dauvoweltelu and 38 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- nbspace

	- exclam 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded), ddasubscript1telu (unencoded) and 53 more.

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

	* ddatelu (U+0C21): B<<585.5,82.5>-<613.0,117.0>-<616.0,178.0>>/B<<616.0,178.0>-<607.0,143.0>-<582.5,123.0>> = 11.60521644329975

	* ddhatelu (U+0C22): B<<585.5,82.5>-<613.0,117.0>-<616.0,178.0>>/B<<616.0,178.0>-<607.0,143.0>-<582.5,123.0>> = 11.60521644329975

	* utelu (U+0C09): B<<610.0,83.0>-<637.0,118.0>-<640.0,176.0>>/B<<640.0,176.0>-<631.0,140.0>-<606.5,119.5>> = 11.07530733376276 

	* And uutelu (U+0C0A): B<<610.0,83.0>-<637.0,118.0>-<640.0,176.0>>/B<<640.0,176.0>-<631.0,140.0>-<606.5,119.5>> = 11.07530733376276 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* catelu (U+0C1A): L<<160.0,280.0>--<23.0,281.0>>

	* chatelu (U+0C1B): L<<160.0,280.0>--<23.0,281.0>> 

	* And tsatelu (U+0C58): L<<160.0,280.0>--<23.0,281.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhahalanttelu
	* reevoweltelu
	* khovoweltelu
	* auvowelsigntelu
	* bhauvoweltelu
	* tsiivoweltelu
	* vauvoweltelu
	* gauvoweltelu
	* kassaavoweltelu
	* hiivoweltelu and 159 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- nbspace

	- exclam 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded), ddasubscript1telu (unencoded) and 53 more.

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

	* uutelu (U+0C0A): B<<612.5,117.0>-<637.0,145.0>-<641.0,189.0>>/B<<641.0,189.0>-<630.0,157.0>-<604.5,139.0>> = 13.775978900751738 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* catelu (U+0C1A): L<<147.0,280.0>--<21.0,279.0>>

	* chatelu (U+0C1B): L<<147.0,280.0>--<21.0,279.0>> 

	* And tsatelu (U+0C58): L<<147.0,280.0>--<21.0,279.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/telugu-serif.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf);}
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

<h4>qa/shaping_tests/telugu-serif.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(పచచ్ǵ)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+368|patelu=1+670|catelu=2+713|cahalanttelu=3+713|.notdef=5+600|parenright.telu=6+368</pre>



<pre>Got     : parenleft.telu=0+368|patelu=1+670|catelu=2+713|cahalanttelu=3+713|g=5+538|acutecomb=5+0|parenright.telu=6+368</pre>



<pre>                                                                            ^^^^^^^   ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3370 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M322.0,-364.0Q226.0,-319.0 168.0,-248.5Q110.0,-178.0 83.5,-68.0Q57.0,42.0 57.0,206.0Q57.0,370.0 83.5,479.5Q110.0,589.0 168.5,659.5Q227.0,730.0 322.0,775.0L322.0,727.0Q246.0,676.0 207.5,598.5Q169.0,521.0 156.5,422.0Q144.0,323.0 144.0,206.0Q144.0,89.0 156.5,-10.5Q169.0,-110.0 207.5,-187.0Q246.0,-264.0 322.0,-316.0L322.0,-364.0Z"  transform="translate(0, 983)"/>
<path d="M154.0,628.0Q165.0,592.0 177.0,561.5Q189.0,531.0 208.0,496.0Q232.0,513.0 264.0,541.5Q296.0,570.0 331.0,603.0Q366.0,636.0 399.0,668.5Q432.0,701.0 457.0,728.0L504.0,683.0Q406.0,594.0 331.0,534.5Q256.0,475.0 216.0,455.0L185.0,455.0Q163.0,468.0 137.5,494.0Q112.0,520.0 88.5,553.5Q65.0,587.0 49.0,623.0L154.0,628.0ZM635.0,215.0Q635.0,149.0 618.0,97.5Q601.0,46.0 566.0,17.0Q531.0,-12.0 477.0,-12.0Q416.0,-12.0 378.5,21.5Q341.0,55.0 315.0,100.0Q303.0,43.0 264.5,15.5Q226.0,-12.0 175.0,-12.0Q109.0,-12.0 69.0,28.5Q29.0,69.0 29.0,139.0Q29.0,180.0 46.0,214.5Q63.0,249.0 96.0,270.0Q129.0,291.0 176.0,291.0Q225.0,291.0 258.0,268.0Q291.0,245.0 306.0,208.0Q343.0,151.0 380.0,124.5Q417.0,98.0 470.0,98.0Q529.0,98.0 559.5,133.0Q590.0,168.0 590.0,232.0Q590.0,312.0 533.5,365.0Q477.0,418.0 361.0,422.0L364.0,504.0Q453.0,502.0 513.5,463.0Q574.0,424.0 604.5,359.5Q635.0,295.0 635.0,215.0ZM89.0,160.0Q89.0,123.0 111.0,100.0Q133.0,77.0 175.0,77.0Q216.0,77.0 240.0,98.0Q264.0,119.0 264.0,161.0Q264.0,200.0 240.5,224.0Q217.0,248.0 176.0,248.0Q136.0,248.0 112.5,224.5Q89.0,201.0 89.0,160.0Z"  transform="translate(368, 983)"/>
<path d="M521.0,-12.0Q494.0,-12.0 468.5,-4.0Q443.0,4.0 419.5,28.0Q396.0,52.0 375.0,99.0Q345.0,31.0 305.5,9.5Q266.0,-12.0 219.0,-12.0Q154.0,-12.0 115.0,28.5Q76.0,69.0 76.0,136.0Q76.0,177.0 93.0,210.5Q110.0,244.0 148.0,274.0L22.0,273.0L28.0,337.0L237.0,318.0L237.0,287.0Q185.0,262.0 163.5,232.5Q142.0,203.0 142.0,174.0Q142.0,134.0 167.5,116.0Q193.0,98.0 232.0,98.0Q281.0,98.0 313.5,125.5Q346.0,153.0 360.0,204.0L391.0,204.0Q408.0,147.0 438.5,122.5Q469.0,98.0 516.0,98.0Q569.0,98.0 600.0,127.5Q631.0,157.0 631.0,225.0Q631.0,291.0 600.0,342.5Q569.0,394.0 507.0,424.0Q445.0,454.0 353.0,455.0L337.0,455.0Q315.0,468.0 289.5,494.0Q264.0,520.0 240.5,553.5Q217.0,587.0 201.0,623.0L306.0,628.0Q317.0,592.0 329.0,561.5Q341.0,531.0 360.0,496.0Q384.0,513.0 416.0,541.5Q448.0,570.0 483.0,603.0Q518.0,636.0 551.0,668.5Q584.0,701.0 609.0,728.0L656.0,683.0Q589.0,622.0 532.0,574.5Q475.0,527.0 432.0,496.0Q547.0,480.0 612.5,404.0Q678.0,328.0 678.0,211.0Q678.0,148.0 662.0,97.5Q646.0,47.0 611.5,17.5Q577.0,-12.0 521.0,-12.0Z"  transform="translate(1038, 983)"/>
<path d="M521.0,-12.0Q494.0,-12.0 468.5,-4.0Q443.0,4.0 419.5,28.0Q396.0,52.0 375.0,99.0Q345.0,31.0 305.5,9.5Q266.0,-12.0 219.0,-12.0Q154.0,-12.0 115.0,28.5Q76.0,69.0 76.0,136.0Q76.0,177.0 93.0,210.5Q110.0,244.0 148.0,274.0L22.0,273.0L28.0,337.0L237.0,318.0L237.0,287.0Q185.0,262.0 163.5,232.5Q142.0,203.0 142.0,174.0Q142.0,134.0 167.5,116.0Q193.0,98.0 232.0,98.0Q281.0,98.0 313.5,125.5Q346.0,153.0 360.0,204.0L391.0,204.0Q408.0,147.0 438.5,122.5Q469.0,98.0 516.0,98.0Q569.0,98.0 599.5,127.5Q630.0,157.0 630.0,225.0Q630.0,321.0 566.5,383.5Q503.0,446.0 384.0,455.0Q311.0,456.0 280.5,484.5Q250.0,513.0 250.0,551.0Q250.0,601.0 301.0,623.0Q241.0,651.0 241.0,713.0Q241.0,743.0 254.0,764.5Q267.0,786.0 290.0,799.0Q312.0,812.0 342.0,817.5Q372.0,823.0 430.0,823.0L676.0,823.0L669.0,752.0L395.0,752.0Q348.0,752.0 324.0,741.5Q300.0,731.0 300.0,701.0Q300.0,670.0 326.0,659.5Q352.0,649.0 396.0,649.0L511.0,649.0L508.0,602.0L391.0,602.0Q305.0,602.0 305.0,552.0Q305.0,525.0 326.5,512.5Q348.0,500.0 400.0,500.0L404.0,500.0Q531.0,489.0 604.5,414.0Q678.0,339.0 678.0,211.0Q678.0,148.0 662.0,97.5Q646.0,47.0 611.5,17.5Q577.0,-12.0 521.0,-12.0Z"  transform="translate(1751, 983)"/>
<path d="M231.0,-240.0Q127.0,-240.0 75.0,-201.5Q23.0,-163.0 23.0,-94.0Q23.0,-35.0 61.0,-5.0Q99.0,25.0 148.0,34.0Q128.0,43.0 110.5,63.5Q93.0,84.0 93.0,116.0Q93.0,146.0 108.5,168.0Q124.0,190.0 158.0,210.0Q115.0,228.0 91.5,269.5Q68.0,311.0 68.0,361.0Q68.0,447.0 115.0,496.5Q162.0,546.0 256.0,546.0Q292.0,546.0 324.0,536.0Q356.0,526.0 370.0,513.0Q384.0,529.0 409.0,548.0Q434.0,567.0 467.0,567.0Q497.0,567.0 511.5,551.5Q526.0,536.0 526.0,515.0Q526.0,494.0 513.5,478.5Q501.0,463.0 473.0,463.0Q473.0,474.0 466.5,485.5Q460.0,497.0 440.0,497.0Q417.0,497.0 397.0,485.0Q414.0,464.0 425.0,435.5Q436.0,407.0 436.0,364.0Q436.0,290.0 391.5,241.0Q347.0,192.0 256.0,192.0Q244.0,192.0 228.5,193.5Q213.0,195.0 203.0,197.0Q184.0,187.0 170.0,172.0Q156.0,157.0 156.0,134.0Q156.0,116.0 167.5,106.0Q179.0,96.0 218.0,96.0L331.0,96.0Q420.0,96.0 458.0,54.0Q496.0,12.0 496.0,-53.0Q496.0,-139.0 431.5,-189.5Q367.0,-240.0 231.0,-240.0ZM253.0,240.0Q302.0,240.0 322.0,270.0Q342.0,300.0 342.0,365.0Q342.0,433.0 321.5,465.0Q301.0,497.0 252.0,497.0Q204.0,497.0 183.0,464.0Q162.0,431.0 162.0,364.0Q162.0,300.0 183.5,270.0Q205.0,240.0 253.0,240.0ZM233.0,-191.0Q305.0,-191.0 344.0,-175.5Q383.0,-160.0 398.5,-132.5Q414.0,-105.0 414.0,-70.0Q414.0,-24.0 388.0,-8.5Q362.0,7.0 312.0,7.0L214.0,7.0Q186.0,7.0 161.0,-0.5Q136.0,-8.0 120.0,-28.0Q104.0,-48.0 104.0,-88.0Q104.0,-117.0 115.0,-140.5Q126.0,-164.0 154.0,-177.5Q182.0,-191.0 233.0,-191.0Z"  transform="translate(2464, 983)"/>
<path d="M-302.0,619.0Q-280.0,648.0 -255.5,690.0Q-231.0,732.0 -215.0,766.0L-108.0,766.0L-108.0,756.0Q-120.0,739.0 -147.0,710.0Q-174.0,681.0 -205.5,652.5Q-237.0,624.0 -264.0,606.0L-302.0,606.0L-302.0,619.0Z"  transform="translate(3002, 983)"/>
<path d="M46.0,775.0Q142.0,730.0 200.5,659.5Q259.0,589.0 285.0,479.0Q311.0,369.0 311.0,205.0Q311.0,42.0 284.5,-68.0Q258.0,-178.0 199.5,-248.5Q141.0,-319.0 46.0,-364.0L46.0,-316.0Q123.0,-264.0 161.0,-187.0Q199.0,-110.0 211.5,-11.0Q224.0,88.0 224.0,205.0Q224.0,323.0 211.5,422.0Q199.0,521.0 161.0,598.5Q123.0,676.0 46.0,727.0L46.0,775.0Z"  transform="translate(3002, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3432 2352" transform="matrix(1 0 0 -1 0 0)">
<path d="M322.0,-364.0Q226.0,-319.0 168.0,-248.5Q110.0,-178.0 83.5,-68.0Q57.0,42.0 57.0,206.0Q57.0,370.0 83.5,479.5Q110.0,589.0 168.5,659.5Q227.0,730.0 322.0,775.0L322.0,727.0Q246.0,676.0 207.5,598.5Q169.0,521.0 156.5,422.0Q144.0,323.0 144.0,206.0Q144.0,89.0 156.5,-10.5Q169.0,-110.0 207.5,-187.0Q246.0,-264.0 322.0,-316.0L322.0,-364.0Z"  transform="translate(0, 983)"/>
<path d="M154.0,628.0Q165.0,592.0 177.0,561.5Q189.0,531.0 208.0,496.0Q232.0,513.0 264.0,541.5Q296.0,570.0 331.0,603.0Q366.0,636.0 399.0,668.5Q432.0,701.0 457.0,728.0L504.0,683.0Q406.0,594.0 331.0,534.5Q256.0,475.0 216.0,455.0L185.0,455.0Q163.0,468.0 137.5,494.0Q112.0,520.0 88.5,553.5Q65.0,587.0 49.0,623.0L154.0,628.0ZM635.0,215.0Q635.0,149.0 618.0,97.5Q601.0,46.0 566.0,17.0Q531.0,-12.0 477.0,-12.0Q416.0,-12.0 378.5,21.5Q341.0,55.0 315.0,100.0Q303.0,43.0 264.5,15.5Q226.0,-12.0 175.0,-12.0Q109.0,-12.0 69.0,28.5Q29.0,69.0 29.0,139.0Q29.0,180.0 46.0,214.5Q63.0,249.0 96.0,270.0Q129.0,291.0 176.0,291.0Q225.0,291.0 258.0,268.0Q291.0,245.0 306.0,208.0Q343.0,151.0 380.0,124.5Q417.0,98.0 470.0,98.0Q529.0,98.0 559.5,133.0Q590.0,168.0 590.0,232.0Q590.0,312.0 533.5,365.0Q477.0,418.0 361.0,422.0L364.0,504.0Q453.0,502.0 513.5,463.0Q574.0,424.0 604.5,359.5Q635.0,295.0 635.0,215.0ZM89.0,160.0Q89.0,123.0 111.0,100.0Q133.0,77.0 175.0,77.0Q216.0,77.0 240.0,98.0Q264.0,119.0 264.0,161.0Q264.0,200.0 240.5,224.0Q217.0,248.0 176.0,248.0Q136.0,248.0 112.5,224.5Q89.0,201.0 89.0,160.0Z"  transform="translate(368, 983)"/>
<path d="M521.0,-12.0Q494.0,-12.0 468.5,-4.0Q443.0,4.0 419.5,28.0Q396.0,52.0 375.0,99.0Q345.0,31.0 305.5,9.5Q266.0,-12.0 219.0,-12.0Q154.0,-12.0 115.0,28.5Q76.0,69.0 76.0,136.0Q76.0,177.0 93.0,210.5Q110.0,244.0 148.0,274.0L22.0,273.0L28.0,337.0L237.0,318.0L237.0,287.0Q185.0,262.0 163.5,232.5Q142.0,203.0 142.0,174.0Q142.0,134.0 167.5,116.0Q193.0,98.0 232.0,98.0Q281.0,98.0 313.5,125.5Q346.0,153.0 360.0,204.0L391.0,204.0Q408.0,147.0 438.5,122.5Q469.0,98.0 516.0,98.0Q569.0,98.0 600.0,127.5Q631.0,157.0 631.0,225.0Q631.0,291.0 600.0,342.5Q569.0,394.0 507.0,424.0Q445.0,454.0 353.0,455.0L337.0,455.0Q315.0,468.0 289.5,494.0Q264.0,520.0 240.5,553.5Q217.0,587.0 201.0,623.0L306.0,628.0Q317.0,592.0 329.0,561.5Q341.0,531.0 360.0,496.0Q384.0,513.0 416.0,541.5Q448.0,570.0 483.0,603.0Q518.0,636.0 551.0,668.5Q584.0,701.0 609.0,728.0L656.0,683.0Q589.0,622.0 532.0,574.5Q475.0,527.0 432.0,496.0Q547.0,480.0 612.5,404.0Q678.0,328.0 678.0,211.0Q678.0,148.0 662.0,97.5Q646.0,47.0 611.5,17.5Q577.0,-12.0 521.0,-12.0Z"  transform="translate(1038, 983)"/>
<path d="M521.0,-12.0Q494.0,-12.0 468.5,-4.0Q443.0,4.0 419.5,28.0Q396.0,52.0 375.0,99.0Q345.0,31.0 305.5,9.5Q266.0,-12.0 219.0,-12.0Q154.0,-12.0 115.0,28.5Q76.0,69.0 76.0,136.0Q76.0,177.0 93.0,210.5Q110.0,244.0 148.0,274.0L22.0,273.0L28.0,337.0L237.0,318.0L237.0,287.0Q185.0,262.0 163.5,232.5Q142.0,203.0 142.0,174.0Q142.0,134.0 167.5,116.0Q193.0,98.0 232.0,98.0Q281.0,98.0 313.5,125.5Q346.0,153.0 360.0,204.0L391.0,204.0Q408.0,147.0 438.5,122.5Q469.0,98.0 516.0,98.0Q569.0,98.0 599.5,127.5Q630.0,157.0 630.0,225.0Q630.0,321.0 566.5,383.5Q503.0,446.0 384.0,455.0Q311.0,456.0 280.5,484.5Q250.0,513.0 250.0,551.0Q250.0,601.0 301.0,623.0Q241.0,651.0 241.0,713.0Q241.0,743.0 254.0,764.5Q267.0,786.0 290.0,799.0Q312.0,812.0 342.0,817.5Q372.0,823.0 430.0,823.0L676.0,823.0L669.0,752.0L395.0,752.0Q348.0,752.0 324.0,741.5Q300.0,731.0 300.0,701.0Q300.0,670.0 326.0,659.5Q352.0,649.0 396.0,649.0L511.0,649.0L508.0,602.0L391.0,602.0Q305.0,602.0 305.0,552.0Q305.0,525.0 326.5,512.5Q348.0,500.0 400.0,500.0L404.0,500.0Q531.0,489.0 604.5,414.0Q678.0,339.0 678.0,211.0Q678.0,148.0 662.0,97.5Q646.0,47.0 611.5,17.5Q577.0,-12.0 521.0,-12.0Z"  transform="translate(1751, 983)"/>
<path d="M94.0,0.0L94.0,714.0L505.0,714.0L505.0,0.0L94.0,0.0ZM145.0,51.0L454.0,51.0L454.0,663.0L145.0,663.0L145.0,51.0Z"  transform="translate(2464, 983)"/>
<path d="M46.0,775.0Q142.0,730.0 200.5,659.5Q259.0,589.0 285.0,479.0Q311.0,369.0 311.0,205.0Q311.0,42.0 284.5,-68.0Q258.0,-178.0 199.5,-248.5Q141.0,-319.0 46.0,-364.0L46.0,-316.0Q123.0,-264.0 161.0,-187.0Q199.0,-110.0 211.5,-11.0Q224.0,88.0 224.0,205.0Q224.0,323.0 211.5,422.0Q199.0,521.0 161.0,598.5Q123.0,676.0 46.0,727.0L46.0,775.0Z"  transform="translate(3064, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">అౘ◌్చంĦా</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: atelu=0+762|tsatelu=1+713|uni25CC=2+578|casubscripttelu=2+316|anusvaratelu=2+490|.notdef=6+600|uni25CC=6+578|aavowelsigntelu=6+219</pre>



<pre>Got     : atelu=0+762|tsatelu=1+713|uni25CC=2+578|casubscripttelu=2+316|anusvaratelu=2+490|Hbar=6+793|uni25CC=6+578|aavowelsigntelu=6+219</pre>



<pre>                                                                                           ^^^^^^^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4449 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(762, 983)"/>
<path d=""  transform="translate(1475, 983)"/>
<path d=""  transform="translate(2053, 983)"/>
<path d=""  transform="translate(2369, 983)"/>
<path d=""  transform="translate(2859, 983)"/>
<path d=""  transform="translate(3652, 983)"/>
<path d=""  transform="translate(4230, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4256 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(762, 983)"/>
<path d=""  transform="translate(1475, 983)"/>
<path d=""  transform="translate(2053, 983)"/>
<path d=""  transform="translate(2369, 983)"/>
<path d=""  transform="translate(2859, 983)"/>
<path d=""  transform="translate(3459, 983)"/>
<path d=""  transform="translate(4037, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(అచచ్ంĦా)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+368|atelu=1+762|catelu=2+713|cahalanttelu=3+713|anusvaratelu=3+490|.notdef=6+600|uni25CC=6+578|aavowelsigntelu=6+219|parenright.telu=8+368</pre>



<pre>Got     : parenleft.telu=0+368|atelu=1+762|catelu=2+713|cahalanttelu=3+713|anusvaratelu=3+490|Hbar=6+793|uni25CC=6+578|aavowelsigntelu=6+219|parenright.telu=8+368</pre>



<pre>                                                                                              ^^^^^^^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5004 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(368, 983)"/>
<path d=""  transform="translate(1130, 983)"/>
<path d=""  transform="translate(1843, 983)"/>
<path d=""  transform="translate(2556, 983)"/>
<path d=""  transform="translate(3046, 983)"/>
<path d=""  transform="translate(3839, 983)"/>
<path d=""  transform="translate(4417, 983)"/>
<path d=""  transform="translate(4636, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4811 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(368, 983)"/>
<path d=""  transform="translate(1130, 983)"/>
<path d=""  transform="translate(1843, 983)"/>
<path d=""  transform="translate(2556, 983)"/>
<path d=""  transform="translate(3046, 983)"/>
<path d=""  transform="translate(3646, 983)"/>
<path d=""  transform="translate(4224, 983)"/>
<path d=""  transform="translate(4443, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">పౘ◌్చǵ</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: patelu=0+670|tsatelu=1+713|uni25CC=2+578|casubscripttelu=2+326|.notdef=5+600</pre>



<pre>Got     : patelu=0+670|tsatelu=1+713|uni25CC=2+578|casubscripttelu=2+326|g=5+538|acutecomb=5+0</pre>



<pre>                                                                         ^^^^^^^   ^ +
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2825 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(670, 983)"/>
<path d=""  transform="translate(1383, 983)"/>
<path d=""  transform="translate(1961, 983)"/>
<path d=""  transform="translate(2287, 983)"/>
<path d=""  transform="translate(2825, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2887 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(670, 983)"/>
<path d=""  transform="translate(1383, 983)"/>
<path d=""  transform="translate(1961, 983)"/>
<path d=""  transform="translate(2287, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(Ĩాకȃ)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+368|.notdef=1+600|aavowelsigntelu=1+0|katelu=3+481|.notdef=4+600|parenright.telu=5+368</pre>



<pre>Got     : parenleft.telu=0+368|I=1+367|tildecomb=1+0|aavowelsigntelu=1+0|katelu=3+481|.notdef=4+600|parenright.telu=5+368</pre>



<pre>                               ^^^^^^^    ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2184 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(368, 983)"/>
<path d=""  transform="translate(735, 983)"/>
<path d=""  transform="translate(735, 983)"/>
<path d=""  transform="translate(735, 983)"/>
<path d=""  transform="translate(1216, 983)"/>
<path d=""  transform="translate(1816, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2417 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(368, 983)"/>
<path d=""  transform="translate(968, 983)"/>
<path d=""  transform="translate(968, 983)"/>
<path d=""  transform="translate(1449, 983)"/>
<path d=""  transform="translate(2049, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ౙ◌ాǹȃ</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: dzatelu=0+686|uni25CC=1+578|aavowelsigntelu=1+219|.notdef=3+600|.notdef=4+600</pre>



<pre>Got     : dzatelu=0+686|uni25CC=1+578|aavowelsigntelu=1+219|n=3+645|gravecomb=3+0|.notdef=4+600</pre>



<pre>                                                            + +++++    ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2728 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(686, 983)"/>
<path d=""  transform="translate(1264, 983)"/>
<path d=""  transform="translate(1483, 983)"/>
<path d=""  transform="translate(2128, 983)"/>
<path d=""  transform="translate(2128, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2683 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(686, 983)"/>
<path d=""  transform="translate(1264, 983)"/>
<path d=""  transform="translate(1483, 983)"/>
<path d=""  transform="translate(2083, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(జాǹȃ)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+368|jaavoweltelu=1+949|.notdef=3+600|.notdef=4+600|parenright.telu=5+368</pre>



<pre>Got     : parenleft.telu=0+368|jaavoweltelu=1+949|n=3+645|gravecomb=3+0|.notdef=4+600|parenright.telu=5+368</pre>



<pre>                                                  + +++++    ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2930 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(368, 983)"/>
<path d=""  transform="translate(1317, 983)"/>
<path d=""  transform="translate(1962, 983)"/>
<path d=""  transform="translate(1962, 983)"/>
<path d=""  transform="translate(2562, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2885 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(368, 983)"/>
<path d=""  transform="translate(1317, 983)"/>
<path d=""  transform="translate(1917, 983)"/>
<path d=""  transform="translate(2517, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">(ǰలు)</span> (fontdiff-346-NotoSansTelugu.html)</li>


<pre>Expected: parenleft.telu=0+368|.notdef=1+600|latelu=2+665|uvowelsigntelu=2+0|parenright.telu=4+368</pre>



<pre>Got     : parenleft.telu=0+368|j=1+300|caroncomb=1+0|latelu=2+665|uvowelsigntelu=2+0|parenright.telu=4+368</pre>



<pre>                               ^^^^^^^   ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1701 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(368, 983)"/>
<path d=""  transform="translate(668, 983)"/>
<path d=""  transform="translate(668, 983)"/>
<path d=""  transform="translate(1333, 983)"/>
<path d=""  transform="translate(1333, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2001 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(368, 983)"/>
<path d=""  transform="translate(968, 983)"/>
<path d=""  transform="translate(1633, 983)"/>
<path d=""  transform="translate(1633, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C18</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|one.telu=2+559|eight.telu=3+559</pre>



<pre>Got     : zero.telu=0+559|C=1+614|one.telu=2+559|eight.telu=3+559</pre>



<pre>                          ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2291 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2277 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C24</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|two.telu=2+559|four.telu=3+559</pre>



<pre>Got     : zero.telu=0+559|C=1+614|two.telu=2+559|four.telu=3+559</pre>



<pre>                          ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2291 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2277 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C30</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|three.telu=2+559|zero.telu=3+559</pre>



<pre>Got     : zero.telu=0+559|C=1+614|three.telu=2+559|zero.telu=3+559</pre>



<pre>                          ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2291 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2277 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C4D</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|four.telu=2+559|.notdef=3+600</pre>



<pre>Got     : zero.telu=0+559|C=1+614|four.telu=2+559|D=3+727</pre>



<pre>                          ^^^^^^^    ^^                 ^^^^^^^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2459 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2318 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C59</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|five.telu=2+559|nine.telu=3+559</pre>



<pre>Got     : zero.telu=0+559|C=1+614|five.telu=2+559|nine.telu=3+559</pre>



<pre>                          ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2291 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2277 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C6D</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|six.telu=2+559|.notdef=3+600</pre>



<pre>Got     : zero.telu=0+559|C=1+614|six.telu=2+559|D=3+727</pre>



<pre>                          ^^^^^^^    ^^                ^^^^^^^   ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2459 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2318 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C83</span> (fontdiff-Telugu-BIS-annex3.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|eight.telu=2+559|three.telu=3+559</pre>



<pre>Got     : zero.telu=0+559|C=1+614|eight.telu=2+559|three.telu=3+559</pre>



<pre>                          ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2291 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2277 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C4D+0C30</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|four.telu=2+559|.notdef=3+600|plus.telu=4+559|zero.telu=5+559|.notdef=6+600|three.telu=7+559|zero.telu=8+559</pre>



<pre>Got     : zero.telu=0+559|C=1+614|four.telu=2+559|D=3+727|plus.telu=4+559|zero.telu=5+559|C=6+614|three.telu=7+559|zero.telu=8+559</pre>



<pre>                          ^^^^^^^    ^^                 ^^^^^^^   ^^^                                 ^^^^^^^    ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5309 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
<path d=""  transform="translate(2459, 983)"/>
<path d=""  transform="translate(3018, 983)"/>
<path d=""  transform="translate(3577, 983)"/>
<path d=""  transform="translate(4191, 983)"/>
<path d=""  transform="translate(4750, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5154 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
<path d=""  transform="translate(2318, 983)"/>
<path d=""  transform="translate(2877, 983)"/>
<path d=""  transform="translate(3436, 983)"/>
<path d=""  transform="translate(4036, 983)"/>
<path d=""  transform="translate(4595, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C4D+200C+0C30</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|four.telu=2+559|.notdef=3+600|plus.telu=4+559|two.telu=5+559|zero.telu=6+559|zero.telu=7+559|.notdef=8+600|plus.telu=9+559|zero.telu=10+559|.notdef=11+600|three.telu=12+559|zero.telu=13+559</pre>



<pre>Got     : zero.telu=0+559|C=1+614|four.telu=2+559|D=3+727|plus.telu=4+559|two.telu=5+559|zero.telu=6+559|zero.telu=7+559|C=8+614|plus.telu=9+559|zero.telu=10+559|C=11+614|three.telu=12+559|zero.telu=13+559</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 8159 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
<path d=""  transform="translate(2459, 983)"/>
<path d=""  transform="translate(3018, 983)"/>
<path d=""  transform="translate(3577, 983)"/>
<path d=""  transform="translate(4136, 983)"/>
<path d=""  transform="translate(4695, 983)"/>
<path d=""  transform="translate(5309, 983)"/>
<path d=""  transform="translate(5868, 983)"/>
<path d=""  transform="translate(6427, 983)"/>
<path d=""  transform="translate(7041, 983)"/>
<path d=""  transform="translate(7600, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7990 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
<path d=""  transform="translate(2318, 983)"/>
<path d=""  transform="translate(2877, 983)"/>
<path d=""  transform="translate(3436, 983)"/>
<path d=""  transform="translate(3995, 983)"/>
<path d=""  transform="translate(4554, 983)"/>
<path d=""  transform="translate(5154, 983)"/>
<path d=""  transform="translate(5713, 983)"/>
<path d=""  transform="translate(6272, 983)"/>
<path d=""  transform="translate(6872, 983)"/>
<path d=""  transform="translate(7431, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C2A+0C4D+0C30+0C24+0C3F</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|two.telu=2+559|.notdef=3+600|plus.telu=4+559|zero.telu=5+559|.notdef=6+600|four.telu=7+559|.notdef=8+600|plus.telu=9+559|zero.telu=10+559|.notdef=11+600|three.telu=12+559|zero.telu=13+559|plus.telu=14+559|zero.telu=15+559|.notdef=16+600|two.telu=17+559|four.telu=18+559|plus.telu=19+559|zero.telu=20+559|.notdef=21+600|three.telu=22+559|.notdef=23+600</pre>



<pre>Got     : zero.telu=0+559|C=1+614|two.telu=2+559|A=3+705|plus.telu=4+559|zero.telu=5+559|C=6+614|four.telu=7+559|D=8+727|plus.telu=9+559|zero.telu=10+559|C=11+614|three.telu=12+559|zero.telu=13+559|plus.telu=14+559|zero.telu=15+559|C=16+614|two.telu=17+559|four.telu=18+559|plus.telu=19+559|zero.telu=20+559|C=21+614|three.telu=22+559|F=23+590</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 14036 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
<path d=""  transform="translate(2437, 983)"/>
<path d=""  transform="translate(2996, 983)"/>
<path d=""  transform="translate(3555, 983)"/>
<path d=""  transform="translate(4169, 983)"/>
<path d=""  transform="translate(4728, 983)"/>
<path d=""  transform="translate(5455, 983)"/>
<path d=""  transform="translate(6014, 983)"/>
<path d=""  transform="translate(6573, 983)"/>
<path d=""  transform="translate(7187, 983)"/>
<path d=""  transform="translate(7746, 983)"/>
<path d=""  transform="translate(8305, 983)"/>
<path d=""  transform="translate(8864, 983)"/>
<path d=""  transform="translate(9423, 983)"/>
<path d=""  transform="translate(10037, 983)"/>
<path d=""  transform="translate(10596, 983)"/>
<path d=""  transform="translate(11155, 983)"/>
<path d=""  transform="translate(11714, 983)"/>
<path d=""  transform="translate(12273, 983)"/>
<path d=""  transform="translate(12887, 983)"/>
<path d=""  transform="translate(13446, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13744 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
<path d=""  transform="translate(2318, 983)"/>
<path d=""  transform="translate(2877, 983)"/>
<path d=""  transform="translate(3436, 983)"/>
<path d=""  transform="translate(4036, 983)"/>
<path d=""  transform="translate(4595, 983)"/>
<path d=""  transform="translate(5195, 983)"/>
<path d=""  transform="translate(5754, 983)"/>
<path d=""  transform="translate(6313, 983)"/>
<path d=""  transform="translate(6913, 983)"/>
<path d=""  transform="translate(7472, 983)"/>
<path d=""  transform="translate(8031, 983)"/>
<path d=""  transform="translate(8590, 983)"/>
<path d=""  transform="translate(9149, 983)"/>
<path d=""  transform="translate(9749, 983)"/>
<path d=""  transform="translate(10308, 983)"/>
<path d=""  transform="translate(10867, 983)"/>
<path d=""  transform="translate(11426, 983)"/>
<path d=""  transform="translate(11985, 983)"/>
<path d=""  transform="translate(12585, 983)"/>
<path d=""  transform="translate(13144, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C2A+0C4D+0C30+0C47+0C2E</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|two.telu=2+559|.notdef=3+600|plus.telu=4+559|zero.telu=5+559|.notdef=6+600|four.telu=7+559|.notdef=8+600|plus.telu=9+559|zero.telu=10+559|.notdef=11+600|three.telu=12+559|zero.telu=13+559|plus.telu=14+559|zero.telu=15+559|.notdef=16+600|four.telu=17+559|seven.telu=18+559|plus.telu=19+559|zero.telu=20+559|.notdef=21+600|two.telu=22+559|.notdef=23+600</pre>



<pre>Got     : zero.telu=0+559|C=1+614|two.telu=2+559|A=3+705|plus.telu=4+559|zero.telu=5+559|C=6+614|four.telu=7+559|D=8+727|plus.telu=9+559|zero.telu=10+559|C=11+614|three.telu=12+559|zero.telu=13+559|plus.telu=14+559|zero.telu=15+559|C=16+614|four.telu=17+559|seven.telu=18+559|plus.telu=19+559|zero.telu=20+559|C=21+614|two.telu=22+559|E=23+623</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 14069 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
<path d=""  transform="translate(2437, 983)"/>
<path d=""  transform="translate(2996, 983)"/>
<path d=""  transform="translate(3555, 983)"/>
<path d=""  transform="translate(4169, 983)"/>
<path d=""  transform="translate(4728, 983)"/>
<path d=""  transform="translate(5455, 983)"/>
<path d=""  transform="translate(6014, 983)"/>
<path d=""  transform="translate(6573, 983)"/>
<path d=""  transform="translate(7187, 983)"/>
<path d=""  transform="translate(7746, 983)"/>
<path d=""  transform="translate(8305, 983)"/>
<path d=""  transform="translate(8864, 983)"/>
<path d=""  transform="translate(9423, 983)"/>
<path d=""  transform="translate(10037, 983)"/>
<path d=""  transform="translate(10596, 983)"/>
<path d=""  transform="translate(11155, 983)"/>
<path d=""  transform="translate(11714, 983)"/>
<path d=""  transform="translate(12273, 983)"/>
<path d=""  transform="translate(12887, 983)"/>
<path d=""  transform="translate(13446, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13744 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
<path d=""  transform="translate(2318, 983)"/>
<path d=""  transform="translate(2877, 983)"/>
<path d=""  transform="translate(3436, 983)"/>
<path d=""  transform="translate(4036, 983)"/>
<path d=""  transform="translate(4595, 983)"/>
<path d=""  transform="translate(5195, 983)"/>
<path d=""  transform="translate(5754, 983)"/>
<path d=""  transform="translate(6313, 983)"/>
<path d=""  transform="translate(6913, 983)"/>
<path d=""  transform="translate(7472, 983)"/>
<path d=""  transform="translate(8031, 983)"/>
<path d=""  transform="translate(8590, 983)"/>
<path d=""  transform="translate(9149, 983)"/>
<path d=""  transform="translate(9749, 983)"/>
<path d=""  transform="translate(10308, 983)"/>
<path d=""  transform="translate(10867, 983)"/>
<path d=""  transform="translate(11426, 983)"/>
<path d=""  transform="translate(11985, 983)"/>
<path d=""  transform="translate(12585, 983)"/>
<path d=""  transform="translate(13144, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C36+0C47+0C16+0C30+0C4D</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|three.telu=2+559|six.telu=3+559|plus.telu=4+559|zero.telu=5+559|.notdef=6+600|four.telu=7+559|seven.telu=8+559|plus.telu=9+559|zero.telu=10+559|.notdef=11+600|one.telu=12+559|six.telu=13+559|plus.telu=14+559|zero.telu=15+559|.notdef=16+600|three.telu=17+559|zero.telu=18+559|plus.telu=19+559|zero.telu=20+559|.notdef=21+600|four.telu=22+559|.notdef=23+600</pre>



<pre>Got     : zero.telu=0+559|C=1+614|three.telu=2+559|six.telu=3+559|plus.telu=4+559|zero.telu=5+559|C=6+614|four.telu=7+559|seven.telu=8+559|plus.telu=9+559|zero.telu=10+559|C=11+614|one.telu=12+559|six.telu=13+559|plus.telu=14+559|zero.telu=15+559|C=16+614|three.telu=17+559|zero.telu=18+559|plus.telu=19+559|zero.telu=20+559|C=21+614|four.telu=22+559|D=23+727</pre>



<pre>                          ^^^^^^^^^^^^^                                                                 ^^^^^^^^^^^^^                                                                   ^^^^^^^^^^^^^^                                                                   ^^^^^^^^^^^^^^                                                                      ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^    ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13859 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
<path d=""  transform="translate(2291, 983)"/>
<path d=""  transform="translate(2850, 983)"/>
<path d=""  transform="translate(3409, 983)"/>
<path d=""  transform="translate(4023, 983)"/>
<path d=""  transform="translate(4582, 983)"/>
<path d=""  transform="translate(5141, 983)"/>
<path d=""  transform="translate(5700, 983)"/>
<path d=""  transform="translate(6259, 983)"/>
<path d=""  transform="translate(6873, 983)"/>
<path d=""  transform="translate(7432, 983)"/>
<path d=""  transform="translate(7991, 983)"/>
<path d=""  transform="translate(8550, 983)"/>
<path d=""  transform="translate(9109, 983)"/>
<path d=""  transform="translate(9723, 983)"/>
<path d=""  transform="translate(10282, 983)"/>
<path d=""  transform="translate(10841, 983)"/>
<path d=""  transform="translate(11400, 983)"/>
<path d=""  transform="translate(11959, 983)"/>
<path d=""  transform="translate(12573, 983)"/>
<path d=""  transform="translate(13132, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13662 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
<path d=""  transform="translate(2277, 983)"/>
<path d=""  transform="translate(2836, 983)"/>
<path d=""  transform="translate(3395, 983)"/>
<path d=""  transform="translate(3995, 983)"/>
<path d=""  transform="translate(4554, 983)"/>
<path d=""  transform="translate(5113, 983)"/>
<path d=""  transform="translate(5672, 983)"/>
<path d=""  transform="translate(6231, 983)"/>
<path d=""  transform="translate(6831, 983)"/>
<path d=""  transform="translate(7390, 983)"/>
<path d=""  transform="translate(7949, 983)"/>
<path d=""  transform="translate(8508, 983)"/>
<path d=""  transform="translate(9067, 983)"/>
<path d=""  transform="translate(9667, 983)"/>
<path d=""  transform="translate(10226, 983)"/>
<path d=""  transform="translate(10785, 983)"/>
<path d=""  transform="translate(11344, 983)"/>
<path d=""  transform="translate(11903, 983)"/>
<path d=""  transform="translate(12503, 983)"/>
<path d=""  transform="translate(13062, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">main(teacher)</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: .notdef=0+600|.notdef=1+600|.notdef=2+600|.notdef=3+600|parenleft.telu=4+368|.notdef=5+600|.notdef=6+600|.notdef=7+600|.notdef=8+600|.notdef=9+600|.notdef=10+600|.notdef=11+600|parenright.telu=12+368</pre>



<pre>Got     : m=0+945|a=1+563|i=2+320|n=3+645|parenleft.telu=4+368|t=5+352|e=6+535|a=7+563|c=8+492|h=9+635|e=10+535|r=11+471|parenright.telu=12+368</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 6792 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(945, 983)"/>
<path d=""  transform="translate(1508, 983)"/>
<path d=""  transform="translate(1828, 983)"/>
<path d=""  transform="translate(2473, 983)"/>
<path d=""  transform="translate(2841, 983)"/>
<path d=""  transform="translate(3193, 983)"/>
<path d=""  transform="translate(3728, 983)"/>
<path d=""  transform="translate(4291, 983)"/>
<path d=""  transform="translate(4783, 983)"/>
<path d=""  transform="translate(5418, 983)"/>
<path d=""  transform="translate(5953, 983)"/>
<path d=""  transform="translate(6424, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7336 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(600, 983)"/>
<path d=""  transform="translate(1200, 983)"/>
<path d=""  transform="translate(1800, 983)"/>
<path d=""  transform="translate(2400, 983)"/>
<path d=""  transform="translate(2768, 983)"/>
<path d=""  transform="translate(3368, 983)"/>
<path d=""  transform="translate(3968, 983)"/>
<path d=""  transform="translate(4568, 983)"/>
<path d=""  transform="translate(5168, 983)"/>
<path d=""  transform="translate(5768, 983)"/>
<path d=""  transform="translate(6368, 983)"/>
<path d=""  transform="translate(6968, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">0C2E+0C3E+0C38+0C4D+0C1F+0C30+0C4D</span> (fontdiff-Telugu-sn-manoj-20171023.html)</li>


<pre>Expected: zero.telu=0+559|.notdef=1+600|two.telu=2+559|.notdef=3+600|plus.telu=4+559|zero.telu=5+559|.notdef=6+600|three.telu=7+559|.notdef=8+600|plus.telu=9+559|zero.telu=10+559|.notdef=11+600|three.telu=12+559|eight.telu=13+559|plus.telu=14+559|zero.telu=15+559|.notdef=16+600|four.telu=17+559|.notdef=18+600|plus.telu=19+559|zero.telu=20+559|.notdef=21+600|one.telu=22+559|.notdef=23+600|plus.telu=24+559|zero.telu=25+559|.notdef=26+600|three.telu=27+559|zero.telu=28+559|plus.telu=29+559|zero.telu=30+559|.notdef=31+600|four.telu=32+559|.notdef=33+600</pre>



<pre>Got     : zero.telu=0+559|C=1+614|two.telu=2+559|E=3+623|plus.telu=4+559|zero.telu=5+559|C=6+614|three.telu=7+559|E=8+623|plus.telu=9+559|zero.telu=10+559|C=11+614|three.telu=12+559|eight.telu=13+559|plus.telu=14+559|zero.telu=15+559|C=16+614|four.telu=17+559|D=18+727|plus.telu=19+559|zero.telu=20+559|C=21+614|one.telu=22+559|F=23+590|plus.telu=24+559|zero.telu=25+559|C=26+614|three.telu=27+559|zero.telu=28+559|plus.telu=29+559|zero.telu=30+559|C=31+614|four.telu=32+559|D=33+727</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 19886 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1173, 983)"/>
<path d=""  transform="translate(1732, 983)"/>
<path d=""  transform="translate(2355, 983)"/>
<path d=""  transform="translate(2914, 983)"/>
<path d=""  transform="translate(3473, 983)"/>
<path d=""  transform="translate(4087, 983)"/>
<path d=""  transform="translate(4646, 983)"/>
<path d=""  transform="translate(5269, 983)"/>
<path d=""  transform="translate(5828, 983)"/>
<path d=""  transform="translate(6387, 983)"/>
<path d=""  transform="translate(7001, 983)"/>
<path d=""  transform="translate(7560, 983)"/>
<path d=""  transform="translate(8119, 983)"/>
<path d=""  transform="translate(8678, 983)"/>
<path d=""  transform="translate(9237, 983)"/>
<path d=""  transform="translate(9851, 983)"/>
<path d=""  transform="translate(10410, 983)"/>
<path d=""  transform="translate(11137, 983)"/>
<path d=""  transform="translate(11696, 983)"/>
<path d=""  transform="translate(12255, 983)"/>
<path d=""  transform="translate(12869, 983)"/>
<path d=""  transform="translate(13428, 983)"/>
<path d=""  transform="translate(14018, 983)"/>
<path d=""  transform="translate(14577, 983)"/>
<path d=""  transform="translate(15136, 983)"/>
<path d=""  transform="translate(15750, 983)"/>
<path d=""  transform="translate(16309, 983)"/>
<path d=""  transform="translate(16868, 983)"/>
<path d=""  transform="translate(17427, 983)"/>
<path d=""  transform="translate(17986, 983)"/>
<path d=""  transform="translate(18600, 983)"/>
<path d=""  transform="translate(19159, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 19498 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(559, 983)"/>
<path d=""  transform="translate(1159, 983)"/>
<path d=""  transform="translate(1718, 983)"/>
<path d=""  transform="translate(2318, 983)"/>
<path d=""  transform="translate(2877, 983)"/>
<path d=""  transform="translate(3436, 983)"/>
<path d=""  transform="translate(4036, 983)"/>
<path d=""  transform="translate(4595, 983)"/>
<path d=""  transform="translate(5195, 983)"/>
<path d=""  transform="translate(5754, 983)"/>
<path d=""  transform="translate(6313, 983)"/>
<path d=""  transform="translate(6913, 983)"/>
<path d=""  transform="translate(7472, 983)"/>
<path d=""  transform="translate(8031, 983)"/>
<path d=""  transform="translate(8590, 983)"/>
<path d=""  transform="translate(9149, 983)"/>
<path d=""  transform="translate(9749, 983)"/>
<path d=""  transform="translate(10308, 983)"/>
<path d=""  transform="translate(10908, 983)"/>
<path d=""  transform="translate(11467, 983)"/>
<path d=""  transform="translate(12026, 983)"/>
<path d=""  transform="translate(12626, 983)"/>
<path d=""  transform="translate(13185, 983)"/>
<path d=""  transform="translate(13785, 983)"/>
<path d=""  transform="translate(14344, 983)"/>
<path d=""  transform="translate(14903, 983)"/>
<path d=""  transform="translate(15503, 983)"/>
<path d=""  transform="translate(16062, 983)"/>
<path d=""  transform="translate(16621, 983)"/>
<path d=""  transform="translate(17180, 983)"/>
<path d=""  transform="translate(17739, 983)"/>
<path d=""  transform="translate(18339, 983)"/>
<path d=""  transform="translate(18898, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">జన్యు</span> (fontdiff-Telugu.html)</li>


<pre>Expected: jatelu=0+686|natelu=1+658|uvowelsigntelu=1+307|yasubscripttelu=1+396</pre>



<pre>Got     : jatelu=0+686|natelu=1+647|uvowelsigntelu=1+307|yasubscripttelu=1+396</pre>



<pre>                                 ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2036 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(686, 983)"/>
<path d=""  transform="translate(1333, 983)"/>
<path d=""  transform="translate(1640, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2047 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(686, 983)"/>
<path d=""  transform="translate(1344, 983)"/>
<path d=""  transform="translate(1651, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">మెచ్చు</span> (fontdiff-Telugu.html)</li>


<pre>Expected: mevoweltelu=0+988|catelu=2+713|uvowelsigntelu=2+282|casubscripttelu=2+326</pre>



<pre>Got     : mevoweltelu=0+988|catelu=2+677|uvowelsigntelu=2+282|casubscripttelu=2+326</pre>



<pre>                                      ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2273 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(988, 983)"/>
<path d=""  transform="translate(1665, 983)"/>
<path d=""  transform="translate(1947, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2309 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(988, 983)"/>
<path d=""  transform="translate(1701, 983)"/>
<path d=""  transform="translate(1983, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">అచ్చుతో</span> (fontdiff-Telugu.html)</li>


<pre>Expected: atelu=0+762|catelu=1+713|uvowelsigntelu=1+282|casubscripttelu=1+326|toovoweltelu=5+845</pre>



<pre>Got     : atelu=0+762|catelu=1+677|uvowelsigntelu=1+282|casubscripttelu=1+326|toovoweltelu=5+845</pre>



<pre>                                ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2892 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(762, 983)"/>
<path d=""  transform="translate(1439, 983)"/>
<path d=""  transform="translate(1721, 983)"/>
<path d=""  transform="translate(2047, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2928 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(762, 983)"/>
<path d=""  transform="translate(1475, 983)"/>
<path d=""  transform="translate(1757, 983)"/>
<path d=""  transform="translate(2083, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">అవలోకనం[మార్చు]</span> (fontdiff-Telugu.html)</li>


<pre>Expected: atelu=0+762|vatelu=1+670|loovoweltelu=2+922|katelu=4+481|natelu=5+658|anusvaratelu=5+490|bracketleft.telu=7+330|maavoweltelu=8+1270|ratelu=10+550|uvowelsigntelu=10+282|casubscripttelu=10+326|bracketright.telu=14+330</pre>



<pre>Got     : atelu=0+762|vatelu=1+670|loovoweltelu=2+922|katelu=4+481|natelu=5+658|anusvaratelu=5+490|bracketleft.telu=7+330|maavoweltelu=8+1270|ratelu=10+530|uvowelsigntelu=10+282|casubscripttelu=10+326|bracketright.telu=14+330</pre>



<pre>                                                                                                                                                         ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7051 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(762, 983)"/>
<path d=""  transform="translate(1432, 983)"/>
<path d=""  transform="translate(2354, 983)"/>
<path d=""  transform="translate(2835, 983)"/>
<path d=""  transform="translate(3493, 983)"/>
<path d=""  transform="translate(3983, 983)"/>
<path d=""  transform="translate(4313, 983)"/>
<path d=""  transform="translate(5583, 983)"/>
<path d=""  transform="translate(6113, 983)"/>
<path d=""  transform="translate(6395, 983)"/>
<path d=""  transform="translate(6721, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 7071 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(762, 983)"/>
<path d=""  transform="translate(1432, 983)"/>
<path d=""  transform="translate(2354, 983)"/>
<path d=""  transform="translate(2835, 983)"/>
<path d=""  transform="translate(3493, 983)"/>
<path d=""  transform="translate(3983, 983)"/>
<path d=""  transform="translate(4313, 983)"/>
<path d=""  transform="translate(5583, 983)"/>
<path d=""  transform="translate(6133, 983)"/>
<path d=""  transform="translate(6415, 983)"/>
<path d=""  transform="translate(6741, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">వినవచ్చు"</span> (fontdiff-Telugu.html)</li>


<pre>Expected: vivoweltelu=0+687|natelu=2+658|vatelu=3+670|catelu=4+713|uvowelsigntelu=4+282|casubscripttelu=4+326|quotedbl.telu=8+460</pre>



<pre>Got     : vivoweltelu=0+687|natelu=2+658|vatelu=3+670|catelu=4+677|uvowelsigntelu=4+282|casubscripttelu=4+326|quotedbl.telu=8+460</pre>



<pre>                                                                ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3760 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(687, 983)"/>
<path d=""  transform="translate(1345, 983)"/>
<path d=""  transform="translate(2015, 983)"/>
<path d=""  transform="translate(2692, 983)"/>
<path d=""  transform="translate(2974, 983)"/>
<path d=""  transform="translate(3300, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3796 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(687, 983)"/>
<path d=""  transform="translate(1345, 983)"/>
<path d=""  transform="translate(2015, 983)"/>
<path d=""  transform="translate(2728, 983)"/>
<path d=""  transform="translate(3010, 983)"/>
<path d=""  transform="translate(3336, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">మార్చు</span> (fontdiff-te-20180314.html)</li>


<pre>Expected: maavoweltelu=0+1270|ratelu=2+550|uvowelsigntelu=2+282|casubscripttelu=2+326</pre>



<pre>Got     : maavoweltelu=0+1270|ratelu=2+530|uvowelsigntelu=2+282|casubscripttelu=2+326</pre>



<pre>                                        ^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2408 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(1270, 983)"/>
<path d=""  transform="translate(1800, 983)"/>
<path d=""  transform="translate(2082, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2428 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(1270, 983)"/>
<path d=""  transform="translate(1820, 983)"/>
<path d=""  transform="translate(2102, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">అందించవచ్చు.</span> (fontdiff-te-google-app-info.html)</li>


<pre>Expected: atelu=0+762|anusvaratelu=0+490|divoweltelu=2+657|anusvaratelu=2+490|catelu=5+713|vatelu=6+670|catelu=7+713|uvowelsigntelu=7+282|casubscripttelu=7+326|period.telu=11+250</pre>



<pre>Got     : atelu=0+762|anusvaratelu=0+490|divoweltelu=2+657|anusvaratelu=2+490|catelu=5+713|vatelu=6+670|catelu=7+677|uvowelsigntelu=7+282|casubscripttelu=7+326|period.telu=11+250</pre>



<pre>                                                                                                                  ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5317 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(762, 983)"/>
<path d=""  transform="translate(1252, 983)"/>
<path d=""  transform="translate(1909, 983)"/>
<path d=""  transform="translate(2399, 983)"/>
<path d=""  transform="translate(3112, 983)"/>
<path d=""  transform="translate(3782, 983)"/>
<path d=""  transform="translate(4459, 983)"/>
<path d=""  transform="translate(4741, 983)"/>
<path d=""  transform="translate(5067, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5353 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(762, 983)"/>
<path d=""  transform="translate(1252, 983)"/>
<path d=""  transform="translate(1909, 983)"/>
<path d=""  transform="translate(2399, 983)"/>
<path d=""  transform="translate(3112, 983)"/>
<path d=""  transform="translate(3782, 983)"/>
<path d=""  transform="translate(4495, 983)"/>
<path d=""  transform="translate(4777, 983)"/>
<path d=""  transform="translate(5103, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ఢీర్య॑శ’హి</span> (Added by SIESTA)</li>


<pre>Expected: ddhiivoweltelu=0+690|ratelu=2+556|yasubscripttelu=2+396|uni0951=2@-384,293+0|shatelu=6+569|quoteright.telu=7+276|hivoweltelu=8+950</pre>



<pre>Got     : ddhiivoweltelu=0+690|ratelu=2+556|yasubscripttelu=2+396|uni0951=2+0|shatelu=6+569|quoteright.telu=7+276|hivoweltelu=8+950</pre>



<pre>                                                                           +++++++++
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3437 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(690, 983)"/>
<path d=""  transform="translate(1246, 983)"/>
<path d=""  transform="translate(1642, 983)"/>
<path d=""  transform="translate(1642, 983)"/>
<path d=""  transform="translate(2211, 983)"/>
<path d=""  transform="translate(2487, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 3437 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(690, 983)"/>
<path d=""  transform="translate(1246, 983)"/>
<path d=""  transform="translate(1258, 1276)"/>
<path d=""  transform="translate(1642, 983)"/>
<path d=""  transform="translate(2211, 983)"/>
<path d=""  transform="translate(2487, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ఫ᳚ౡళలోతోౄన</span> (Added by SIESTA)</li>


<pre>Expected: phatelu=0+670|uni1CDA=0@-49,293+0|llvocalictelu=2+1089|llatelu=3+622|loovoweltelu=4+845|toovoweltelu=6+875|rrvocalicvowelsigntelu=6+546|natelu=9+658</pre>



<pre>Got     : phatelu=0+670|uni1CDA=0@-49,293+0|llvocalictelu=2+1089|llatelu=3+622|loovoweltelu=4+845|toovoweltelu=6+860|rrvocalicvowelsigntelu=6+546|natelu=9+658</pre>



<pre>                                                                                                                  ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5290 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(621, 1276)"/>
<path d=""  transform="translate(670, 983)"/>
<path d=""  transform="translate(1759, 983)"/>
<path d=""  transform="translate(2381, 983)"/>
<path d=""  transform="translate(3226, 983)"/>
<path d=""  transform="translate(4086, 983)"/>
<path d=""  transform="translate(4632, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5305 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(621, 1276)"/>
<path d=""  transform="translate(670, 983)"/>
<path d=""  transform="translate(1759, 983)"/>
<path d=""  transform="translate(2381, 983)"/>
<path d=""  transform="translate(3226, 983)"/>
<path d=""  transform="translate(4101, 983)"/>
<path d=""  transform="translate(4647, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">భృపే్ఘషేలొ</span> (Added by SIESTA)</li>


<pre>Expected: bhatelu=0+662|rvocalicvowelsigntelu=0+358|peevoweltelu=2+685|viramatelu=2+0|ghatelu=5+988|sseevoweltelu=6+689|lovoweltelu=8+922</pre>



<pre>Got     : bhatelu=0+688|rvocalicvowelsigntelu=0+358|peevoweltelu=2+685|viramatelu=2+0|ghatelu=5+988|sseevoweltelu=6+689|lovoweltelu=8+922</pre>



<pre>                     ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4330 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(688, 983)"/>
<path d=""  transform="translate(1046, 983)"/>
<path d=""  transform="translate(1731, 983)"/>
<path d=""  transform="translate(1731, 983)"/>
<path d=""  transform="translate(2719, 983)"/>
<path d=""  transform="translate(3408, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4304 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(662, 983)"/>
<path d=""  transform="translate(1020, 983)"/>
<path d=""  transform="translate(1705, 983)"/>
<path d=""  transform="translate(1705, 983)"/>
<path d=""  transform="translate(2693, 983)"/>
<path d=""  transform="translate(3382, 983)"/>
</svg>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">తఄరోూన</span> (Added by SIESTA)</li>


<pre>Expected: tatelu=0+723|uni0C04=0@-75,293+0|roovoweltelu=2+714|uuvowelsigntelu=2+569|natelu=5+658</pre>



<pre>Got     : tatelu=0+723|uni0C04=0@-75,293+0|roovoweltelu=2+699|uuvowelsigntelu=2+569|natelu=5+658</pre>



<pre>                                                          ^^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2649 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(648, 1276)"/>
<path d=""  transform="translate(723, 983)"/>
<path d=""  transform="translate(1422, 983)"/>
<path d=""  transform="translate(1991, 983)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 2664 2352" transform="matrix(1 0 0 -1 0 0)">
<path d=""  transform="translate(0, 983)"/>
<path d=""  transform="translate(648, 1276)"/>
<path d=""  transform="translate(723, 983)"/>
<path d=""  transform="translate(1437, 983)"/>
<path d=""  transform="translate(2006, 983)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhahalanttelu
	* bhauvoweltelu
	* tsiivoweltelu
	* vauvoweltelu
	* gauvoweltelu
	* hiivoweltelu
	* nyahalanttelu
	* kassiivoweltelu
	* tsovoweltelu
	* ddhaavoweltelu and 122 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- nbspace

	- exclam 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded), ddasubscript1telu (unencoded) and 53 more.

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

	* ddatelu (U+0C21): B<<589.5,105.5>-<615.0,135.0>-<618.0,187.0>>/B<<618.0,187.0>-<598.0,116.0>-<516.0,116.0>> = 12.430139110672277

	* ddhatelu (U+0C22): B<<589.5,105.5>-<615.0,135.0>-<618.0,187.0>>/B<<618.0,187.0>-<598.0,116.0>-<516.0,116.0>> = 12.430139110672277

	* utelu (U+0C09): B<<611.0,106.0>-<635.0,136.0>-<639.0,183.0>>/B<<639.0,183.0>-<629.0,148.0>-<603.0,128.5>> = 11.080881463162276 

	* And uutelu (U+0C0A): B<<611.0,106.0>-<635.0,136.0>-<639.0,183.0>>/B<<639.0,183.0>-<629.0,148.0>-<603.0,128.5>> = 11.080881463162276 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* catelu (U+0C1A): L<<148.0,274.0>--<22.0,273.0>>

	* chatelu (U+0C1B): L<<148.0,274.0>--<22.0,273.0>> 

	* And tsatelu (U+0C58): L<<148.0,274.0>--<22.0,273.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jhahalanttelu
	* reevoweltelu
	* khovoweltelu
	* auvowelsigntelu
	* bhauvoweltelu
	* tsiivoweltelu
	* vauvoweltelu
	* gauvoweltelu
	* ttheevoweltelu
	* thiivoweltelu and 236 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- nbspace

	- exclam 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded), ddasubscript1telu (unencoded) and 53 more.

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

	* katelu (U+0C15): L<<230.0,504.0>--<234.0,504.0>> -> L<<234.0,504.0>--<235.0,504.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* catelu (U+0C1A): L<<146.0,287.0>--<20.0,286.0>>

	* chatelu (U+0C1B): L<<146.0,287.0>--<20.0,286.0>>

	* sterling (U+00A3): L<<419.0,336.0>--<262.0,337.0>> 

	* And tsatelu (U+0C58): L<<146.0,287.0>--<20.0,286.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifTelugu/googlefonts/slim-variable-ttf/NotoSerifTelugu[wght].ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Black.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Bold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-ExtraLight.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Light.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Medium.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Regular.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-SemiBold.ttf', 'fonts/NotoSerifTelugu/googlefonts/ttf/NotoSerifTelugu-Thin.ttf', 'fonts/NotoSerifTelugu/googlefonts/variable-ttf/NotoSerifTelugu[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni1CDA

	- uni0C04

	- uni0C00

	- uni0951 

	- And uni0952 [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* hauvoweltelu
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quoteright

	- braceleft

	- numbersign

	- bracketleft

	- semicolon

	- quotedblleft

	- bar

	- asciicircum

	- nbspace

	- exclam 

	- And 36 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.telu	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), auvowelsigntelu (U+0C4C), basubscript1telu (unencoded), basubscripttelu (unencoded), bhasubscript1telu (unencoded), bhasubscripttelu (unencoded), candrabindu_0952telu (unencoded), chasubscript1telu (unencoded), chasubscripttelu (unencoded), dasubscript1telu (unencoded) and 54 more.

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

	* aatelu (U+0C06): B<<122.0,381.0>-<122.0,428.0>-<163.0,462.0>>/B<<163.0,462.0>-<122.0,437.0>-<95.0,391.5>> = 8.294835978231973

	* atelu (U+0C05): B<<122.0,381.0>-<122.0,428.0>-<163.0,462.0>>/B<<163.0,462.0>-<122.0,437.0>-<95.0,391.5>> = 8.294835978231973

	* ddatelu (U+0C21): B<<581.5,56.0>-<611.0,97.0>-<614.0,168.0>>/B<<614.0,168.0>-<606.0,132.0>-<583.5,109.5>> = 10.109298492495101

	* ddhatelu (U+0C22): B<<581.5,56.0>-<611.0,97.0>-<614.0,168.0>>/B<<614.0,168.0>-<606.0,132.0>-<583.5,109.5>> = 10.109298492495101

	* eth (U+00F0): B<<385.5,450.5>-<412.0,431.0>-<428.0,400.0>>/B<<428.0,400.0>-<403.0,480.0>-<371.5,537.5>> = 9.945547575071476

	* latelu (U+0C32): B<<128.5,420.0>-<135.0,438.0>-<153.0,455.0>>/B<<153.0,455.0>-<115.0,429.0>-<91.5,385.0>> = 8.983078234538413

	* llatelu (U+0C33): B<<111.5,416.0>-<122.0,438.0>-<144.0,452.0>>/B<<144.0,452.0>-<108.0,437.0>-<86.0,405.5>> = 9.851327342808043

	* lllatelu (U+0C34): B<<140.0,416.0>-<145.0,430.0>-<154.0,442.0>>/B<<154.0,442.0>-<111.0,404.0>-<92.0,347.0>> = 11.662396938046887

	* lllatelu (U+0C34): B<<660.0,355.0>-<639.0,416.0>-<591.0,452.0>>/B<<591.0,452.0>-<604.0,438.0>-<611.5,422.0>> = 10.251198750817418

	* nnatelu (U+0C23): B<<630.0,108.0>-<630.0,43.0>-<587.0,15.0>>/B<<587.0,15.0>-<637.0,37.0>-<667.5,91.0>> = 9.321183329894854 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.telu (U+0021): L<<126.0,176.0>--<122.0,657.0>>

	* exclam.telu (U+0021): L<<150.0,657.0>--<148.0,176.0>>

	* exclamdown (U+00A1): L<<123.0,-177.0>--<124.0,370.0>> 

	* And exclamdown (U+00A1): L<<149.0,370.0>--<152.0,-177.0>> [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 72 | 95 | 1234 | 78 | 956 | 0 |
| 0% | 3% | 4% | 51% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
