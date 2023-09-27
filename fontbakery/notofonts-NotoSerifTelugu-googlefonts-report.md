## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[9] NotoSerifTelugu[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, malayalam, tai-le, canadian-aboriginal, old-permic, tifinagh, math, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: nandinagari, devanagari, grantha, tirhuta
 * U+2010 HYPHEN: try adding one of: sundanese, syloti-nagri, yi, sora-sompeng, kaithi, cham, kayah-li, lisu, kharoshthi, coptic

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- aavowelsigntelu.spacing

	- aavowelsigntelu.spacing2

	- auvowelsign6telu

	- auvowelsigntelu.spacing

	- auvowelsigntelu.spacing3

	- exclam

	- nuktaailengthmarktelu

	- oovowelsigntelu.spacing

	- oovowelsigntelu.spacing3

	- ovowelsigntelu.spacing

	- ovowelsigntelu.spacing3

	- question
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), aavowelsigntelu.spacing (unencoded), aavowelsigntelu.spacing2 (unencoded), auvowelsign6telu (unencoded), auvowelsigntelu (U+0C4C), auvowelsigntelu.spacing (unencoded), auvowelsigntelu.spacing2 (unencoded), auvowelsigntelu.spacing3 (unencoded), bapostscripttelu (unencoded), basubscripttelu.spacing (unencoded), bhapostscripttelu (unencoded), bhasubscripttelu.spacing (unencoded), chapostscripttelu (unencoded), chasubscripttelu.spacing (unencoded), dasubscripttelu.spacing (unencoded), ddasubscripttelu.spacing (unencoded), ddhasubscripttelu.spacing (unencoded), dhasubscripttelu.spacing (unencoded), gasubscripttelu.spacing (unencoded), ghasubscripttelu.spacing (unencoded), hasubscripttelu.spacing (unencoded), jasubscripttelu.spacing (unencoded), jhasubscripttelu.spacing (unencoded), kapostscripttelu (unencoded), kassasubscripttelu.spacing (unencoded), kasubscripttelu.spacing (unencoded), khasubscripttelu.spacing (unencoded), lasubscripttelu.spacing (unencoded), llapostscripttelu (unencoded), llasubscripttelu.spacing (unencoded), lllasubscripttelu.spacing (unencoded), llvocalicvowelsigntelu (U+0C63), llvocalicvowelsigntelu.spacing (unencoded), lvocalicvowelsigntelu.spacing (unencoded), mapostscripttelu (unencoded), masubscripttelu.spacing (unencoded), ngasubscripttelu.spacing (unencoded), nnasubscripttelu.spacing (unencoded), nyasubscripttelu.spacing (unencoded), oovowelsigntelu (U+0C4B), oovowelsigntelu.spacing (unencoded), oovowelsigntelu.spacing2 (unencoded), oovowelsigntelu.spacing3 (unencoded), ovowelsigntelu (U+0C4A), ovowelsigntelu.spacing (unencoded), ovowelsigntelu.spacing2 (unencoded), ovowelsigntelu.spacing3 (unencoded), papostscripttelu (unencoded), pasubscripttelu.spacing (unencoded), phapostscripttelu (unencoded), phasubscripttelu.spacing (unencoded), rrasubscripttelu.spacing (unencoded), rrrasubscripttelu.spacing (unencoded), rrvocalicvowelsigntelu (U+0C44), rrvocalicvowelsigntelu.spacing (unencoded), rvocalicvowelsigntelu (U+0C43), rvocalicvowelsigntelu.spacing (unencoded), sapostscripttelu (unencoded), sasubscripttelu.spacing (unencoded), shapostscripttelu (unencoded), shasubscripttelu.spacing (unencoded), ssasubscripttelu.spacing (unencoded), tasubscripttelu.spacing (unencoded), thasubscripttelu.spacing (unencoded), ttasubscripttelu.spacing (unencoded), tthasubscripttelu.spacing (unencoded), uuvowelsigntelu (U+0C42), uuvowelsigntelu.spacing (unencoded), uuvowelsigntelu.spacing2 (unencoded), uuvowelsigntelu.spacing3 (unencoded), uvowelsigntelu (U+0C41), uvowelsigntelu.spacing (unencoded), uvowelsigntelu.spacing2 (unencoded), uvowelsigntelu.spacing3 (unencoded) and yasubscripttelu.spacing (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Igbo (Latn, 27,823,640 speakers), Ma’di (Latn, 584,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Avokaya (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Lugbara (Latn, 2,200,000 speakers), Aghem (Latn, 38,843 speakers), Nateni (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Koonzime (Latn, 40,000 speakers), Ejagham (Latn, 120,000 speakers), Kom (Latn, 360,685 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 8 | 99 | 8 | 133 | 0 |
| 0% | 0% | 3% | 40% | 3% | 53% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
