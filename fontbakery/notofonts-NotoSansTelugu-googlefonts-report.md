## FontBakery report

fontbakery version: 0.11.2

<h2>Check results</h2><details><summary><b>[12] NotoSansTelugu[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 2.005 is equal to version on **Google Fonts**.
* 🔥 **FAIL** Version number 2.005 is equal to version on google/fonts **GitHub repo**.
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


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
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, coptic, tifinagh, math
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: syriac, coptic, tifinagh, tai-le, canadian-aboriginal, malayalam, old-permic, math
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+2010 HYPHEN: try adding one of: syloti-nagri, arabic, kayah-li, cham, coptic, kaithi, kharoshthi, sundanese, armenian, sora-sompeng, yi, lisu, hebrew

Or you can add the above codepoints to one of the subsets supported by the font: `cyrillic-ext`, `greek-ext`, `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check that legacy accents aren't used in composite glyphs. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* ⚠ **WARN** Glyph "Aacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Abreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Acircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Adieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Agrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Aogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Aring" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Atilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Cacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ccaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ccedilla" has a legacy accent component  (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Cdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Dcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Eacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ecaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ecircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Edieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Edotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Egrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Eogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Gbreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Gdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Iacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Icircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Idieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Idotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Igrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Iogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Lacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Nacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ncaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ntilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Oacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ocircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Odieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ograve" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ohungarumlaut" has a legacy accent component  (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Otilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Racute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Rcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Sacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Scaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Scedilla" has a legacy accent component  (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Tcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Uacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ubreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ucircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Udieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ugrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Uhungarumlaut" has a legacy accent component  (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Uring" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Wacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Wcircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Wdieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Wgrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Yacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ycircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ydieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Ygrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Zacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Zcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "Zdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "aacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "abreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "acircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "acutecomb" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "adieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "agrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "aogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "aring" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "atilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0306" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "cacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni030C" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ccaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ccedilla" has a legacy accent component  (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "cdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0327" has a legacy accent component  (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0302" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0308" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0307" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "eacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ecaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ecircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "edieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "edotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "egrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "gbreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "gdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "gravecomb" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni030B" has a legacy accent component  (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "iacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "icircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "idieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "igrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "iogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "lacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "nacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ncaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ntilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "oacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ocircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "odieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni0328" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ograve" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ohungarumlaut" has a legacy accent component  (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "otilde" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "racute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "rcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uni030A" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "sacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "scaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "scedilla" has a legacy accent component  (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "tildecomb" has a legacy accent component  (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ubreve" has a legacy accent component  (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ucircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "udieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ugrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uhungarumlaut" has a legacy accent component  (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uogonek" has a legacy accent component  (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "uring" has a legacy accent component  (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "wacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "wcircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "wdieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "wgrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "yacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ycircumflex" has a legacy accent component  (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ydieresis" has a legacy accent component  (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "ygrave" has a legacy accent component  (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "zacute" has a legacy accent component  (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "zcaron" has a legacy accent component  (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* ⚠ **WARN** Glyph "zdotaccent" has a legacy accent component  (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>⚠ <b>WARN:</b> Glyph names are all valid? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/valid_glyphnames">com.google.fonts/check/valid_glyphnames</a>)</summary><div>


* ⚠ **WARN** The following glyph names may be too long for some legacy systems which may expect a maximum 31-characters length limit:
llvocalicvowelsignUItelu.spacing and rrvocalicvowelsignUItelu.spacing [code: legacy-long-names]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- aavoweltelu.spacing2

	- ailengthmarkUItelu

	- ailengthmarknarrowUItelu

	- ailengthmarkwideUItelu

	- ailengthmarkwiderUItelu

	- aivowelsignUItelu

	- auvowelsign6telu

	- auvowelsigntelu.spacing

	- baivowelUItelu

	- bapostscriptUItelu

	- bapostscriptUItelu.spacing

	- bhaivowelUItelu

	- bhapostscriptUItelu

	- bhapostscriptUItelu.spacing

	- caivowelUItelu

	- capostscriptUItelu.spacing

	- chaivowelUItelu

	- chapostscriptUItelu

	- chapostscriptUItelu.spacing

	- dailengthmarkUItelu

	- dailengthmarkUItelu.spacing

	- daivowelUItelu

	- dasubscriptUItelu

	- dasubscriptUItelu.spacing

	- dasubscriptlowUItelu

	- ddailengthmarkUItelu

	- ddailengthmarkUItelu.spacing

	- ddaivowelUItelu

	- ddasubscriptUItelu

	- ddasubscriptUItelu.spacing

	- ddasubscriptlowUItelu

	- ddhaivowelUItelu

	- ddhasubscriptUItelu

	- ddhasubscriptUItelu.spacing

	- dhailengthmarkUItelu

	- dhailengthmarkUItelu.spacing

	- dhaivowelUItelu

	- dhasubscriptUItelu

	- dhasubscriptUItelu.spacing

	- dhasubscriptlowUItelu

	- dzaivowelUItelu

	- gailengthmarkUItelu

	- gailengthmarkUItelu.spacing

	- gaivowelUItelu

	- gasubscriptUItelu

	- gasubscriptUItelu.spacing

	- ghailengthmarkUItelu

	- ghailengthmarkUItelu.spacing

	- ghaivowelUItelu

	- ghasubscriptUItelu

	- ghasubscriptUItelu.spacing

	- hailengthmarkUItelu

	- hailengthmarkUItelu.spacing

	- haivowelUItelu

	- hasubscriptUItelu

	- hasubscriptUItelu.spacing

	- jailengthmarkUItelu

	- jailengthmarkUItelu.spacing

	- jaivowelUItelu

	- jasubscriptUItelu

	- jasubscriptUItelu.spacing

	- jasubscriptlowUItelu

	- jhaivowelUItelu

	- jhasubscriptUItelu

	- jhasubscriptUItelu.spacing

	- kaivowelUItelu

	- kapostscriptUItelu.spacing

	- kassaivowelUItelu

	- kassasubscriptUItelu

	- kassasubscriptUItelu.spacing

	- khailengthmarkUItelu

	- khailengthmarkUItelu.spacing

	- khaivowelUItelu

	- khasubscriptUItelu

	- khasubscriptUItelu.spacing

	- lailengthmarkUItelu

	- lailengthmarkUItelu.spacing

	- laivowelUItelu

	- lasubscriptUItelu

	- lasubscriptUItelu.spacing

	- lasubscriptlowUItelu

	- llaivowelUItelu

	- llapostscriptUItelu

	- llapostscriptUItelu.spacing

	- lllaivowelUItelu

	- lllasubscriptUItelu

	- lllasubscriptUItelu.spacing

	- llvocalicvowelsignUItelu

	- llvocalicvowelsignUItelu.spacing

	- lvocalicvowelsignUItelu

	- lvocalicvowelsignUItelu.spacing

	- maivowelUItelu

	- mapostscriptUItelu

	- mapostscriptUItelu.spacing

	- naivowelUItelu

	- napostscriptUItelu.spacing

	- ngaivowelUItelu

	- ngasubscriptUItelu

	- ngasubscriptUItelu.spacing

	- nnailengthmarkUItelu

	- nnailengthmarkUItelu.spacing

	- nnaivowelUItelu

	- nnasubscriptUItelu

	- nnasubscriptUItelu.spacing

	- nuktailengthmarktelu

	- nyaivowelUItelu

	- nyasubscriptUItelu

	- nyasubscriptUItelu.spacing

	- paivowelUItelu

	- papostscriptUItelu.spacing

	- phaivowelUItelu

	- phapostscriptUItelu

	- phapostscriptUItelu.spacing

	- question

	- raivowelUItelu

	- rapostscriptUItelu

	- rasubscriptlowUItelu

	- rraivowelUItelu

	- rrasubscriptUItelu

	- rrasubscriptUItelu.spacing

	- rrraivowelUItelu

	- rrrasubscriptUItelu

	- rrrasubscriptUItelu.spacing

	- rrvocalicvowelsignUItelu

	- rrvocalicvowelsignUItelu.spacing

	- rvocalicvowelsignUItelu

	- rvocalicvowelsignUItelu.spacing

	- saivowelUItelu

	- sapostscriptUItelu.spacing

	- shaivowelUItelu

	- shapostscriptUItelu

	- shapostscriptUItelu.spacing

	- ssailengthmarkUItelu

	- ssailengthmarkUItelu.spacing

	- ssaivowelUItelu

	- ssannasubscriptUItelu

	- ssarasubscriptUItelu

	- ssasubscriptUItelu

	- ssasubscriptUItelu.spacing

	- taalttelu

	- tailengthmarkUItelu

	- tailengthmarknarrowUItelu

	- tailengthmarkwideUItelu

	- taivowelUItelu

	- tasubscriptUItelu

	- tasubscriptUItelu.spacing

	- tasubscriptlowUItelu

	- tasubscriptnarrowUItelu

	- tasubscriptwideUItelu

	- thailengthmarkUItelu

	- thailengthmarkUItelu.spacing

	- thaivowelUItelu

	- thasubscriptUItelu

	- thasubscriptUItelu.spacing

	- tsaivowelUItelu

	- ttailengthmarkUItelu

	- ttailengthmarkUItelu.spacing

	- ttaivowelUItelu

	- ttasubscriptUItelu

	- ttasubscriptUItelu.spacing

	- ttasubscriptlowUItelu

	- tthaivowelUItelu

	- tthasubscriptUItelu

	- tthasubscriptUItelu.spacing

	- vaivowelUItelu

	- vapostscriptUItelu.spacing

	- yaivowelUItelu

	- yapostscriptUItelu

	- yapostscriptUItelu.spacing
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Does the font contain a soft hyphen? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_hyphen">com.google.fonts/check/soft_hyphen</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character. [code: softhyphen]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsigntelu (U+0C3E), aavowelsigntelu.spacing (unencoded), aavoweltelu.spacing2 (unencoded), auvowelsigntelu.spacing (unencoded), auvoweltelu.spacing2 (unencoded), auvoweltelu.spacing3 (unencoded), baalttelu.spacing (unencoded), bapostscriptUItelu (unencoded), bapostscriptUItelu.spacing (unencoded), bapostscripttelu (unencoded), bapostscripttelu.spacing (unencoded), bhaalttelu.spacing (unencoded), bhapostscriptUItelu (unencoded), bhapostscriptUItelu.spacing (unencoded), bhapostscripttelu (unencoded), bhapostscripttelu.spacing (unencoded), caalttelu.spacing (unencoded), candrabindu_095telu.spacing (unencoded), capostscriptUItelu.spacing (unencoded), capostscripttelu (unencoded), capostscripttelu.spacing (unencoded), chaalttelu.spacing (unencoded), chapostscriptUItelu (unencoded), chapostscriptUItelu.spacing (unencoded), chapostscripttelu (unencoded), chapostscripttelu.spacing (unencoded), dailengthmarkUItelu.spacing (unencoded), dasubscriptUItelu.spacing (unencoded), dasubscripttelu.spacing (unencoded), ddailengthmarkUItelu.spacing (unencoded), ddasubscriptUItelu.spacing (unencoded), ddasubscripttelu.spacing (unencoded), ddhasubscriptUItelu.spacing (unencoded), ddhasubscripttelu.spacing (unencoded), dhailengthmarkUItelu.spacing (unencoded), dhasubscriptUItelu.spacing (unencoded), dhasubscripttelu.spacing (unencoded), gailengthmarkUItelu.spacing (unencoded), gasubscriptUItelu.spacing (unencoded), gasubscripttelu.spacing (unencoded), ghailengthmarkUItelu.spacing (unencoded), ghasubscriptUItelu.spacing (unencoded), ghasubscripttelu.spacing (unencoded), hailengthmarkUItelu.spacing (unencoded), hasubscriptUItelu.spacing (unencoded), hasubscripttelu.spacing (unencoded), jailengthmarkUItelu.spacing (unencoded), jasubscriptUItelu.spacing (unencoded), jasubscripttelu.spacing (unencoded), jhasubscriptUItelu.spacing (unencoded), jhasubscripttelu.spacing (unencoded), kapostscriptUItelu.spacing (unencoded), kapostscripttelu (unencoded), kapostscripttelu.spacing (unencoded), kassasubscriptUItelu.spacing (unencoded), kassasubscripttelu.spacing (unencoded), khailengthmarkUItelu.spacing (unencoded), khasubscriptUItelu.spacing (unencoded), khasubscripttelu.spacing (unencoded), lailengthmarkUItelu.spacing (unencoded), lasubscriptUItelu.spacing (unencoded), lasubscripttelu.spacing (unencoded), llapostscriptUItelu (unencoded), llapostscriptUItelu.spacing (unencoded), llapostscripttelu (unencoded), llapostscripttelu.spacing (unencoded), lllasubscriptUItelu.spacing (unencoded), lllasubscripttelu.spacing (unencoded), llvocalicvowelsignUItelu (unencoded), llvocalicvowelsignUItelu.spacing (unencoded), llvocalicvowelsigntelu (U+0C63), llvocalicvowelsigntelu.spacing (unencoded), lvocalicvowelsignUItelu.spacing (unencoded), lvocalicvowelsigntelu.spacing (unencoded), maalttelu.spacing (unencoded), mapostscriptUItelu (unencoded), mapostscriptUItelu.spacing (unencoded), mapostscripttelu (unencoded), mapostscripttelu.spacing (unencoded), naalttelu.spacing (unencoded), napostscriptUItelu.spacing (unencoded), napostscripttelu (unencoded), napostscripttelu.spacing (unencoded), ngasubscriptUItelu.spacing (unencoded), ngasubscripttelu.spacing (unencoded), nnailengthmarkUItelu.spacing (unencoded), nnasubscriptUItelu.spacing (unencoded), nnasubscripttelu.spacing (unencoded), nyasubscriptUItelu.spacing (unencoded), nyasubscripttelu.spacing (unencoded), oovowelsigntelu.spacing (unencoded), oovoweltelu.spacing2 (unencoded), oovoweltelu.spacing3 (unencoded), ovowelsigntelu.spacing (unencoded), ovoweltelu.spacing2 (unencoded), ovoweltelu.spacing3 (unencoded), papostscriptUItelu.spacing (unencoded), papostscripttelu (unencoded), papostscripttelu.spacing (unencoded), phapostscriptUItelu (unencoded), phapostscriptUItelu.spacing (unencoded), phapostscripttelu (unencoded), phapostscripttelu.spacing (unencoded), rapostscriptUItelu (unencoded), rrasubscriptUItelu.spacing (unencoded), rrasubscripttelu.spacing (unencoded), rrrasubscriptUItelu.spacing (unencoded), rrrasubscripttelu.spacing (unencoded), rrvocalicvowelsignUItelu (unencoded), rrvocalicvowelsignUItelu.spacing (unencoded), rrvocalicvowelsigntelu (U+0C44), rrvocalicvowelsigntelu.spacing (unencoded), rvocalicvowelsignUItelu (unencoded), rvocalicvowelsignUItelu.spacing (unencoded), rvocalicvowelsigntelu (U+0C43), rvocalicvowelsigntelu.spacing (unencoded), sapostscriptUItelu.spacing (unencoded), sapostscripttelu (unencoded), sapostscripttelu.spacing (unencoded), shapostscriptUItelu (unencoded), shapostscriptUItelu.spacing (unencoded), shapostscripttelu (unencoded), shapostscripttelu.spacing (unencoded), ssailengthmarkUItelu.spacing (unencoded), ssasubscriptUItelu.spacing (unencoded), ssasubscripttelu.spacing (unencoded), tasubscriptUItelu.spacing (unencoded), tasubscripttelu.spacing (unencoded), thailengthmarkUItelu.spacing (unencoded), thasubscriptUItelu.spacing (unencoded), thasubscripttelu.spacing (unencoded), ttailengthmarkUItelu.spacing (unencoded), ttasubscriptUItelu.spacing (unencoded), ttasubscripttelu.spacing (unencoded), tthasubscriptUItelu.spacing (unencoded), tthasubscripttelu.spacing (unencoded), uuvowelsigntelu (U+0C42), uuvowelsigntelu.spacing (unencoded), uuvoweltelu.spacing2 (unencoded), uuvoweltelu.spacing3 (unencoded), uvowelsigntelu (U+0C41), uvowelsigntelu.spacing (unencoded), uvoweltelu.spacing2 (unencoded), uvoweltelu.spacing3 (unencoded), vaalttelu.spacing (unencoded), vapostscriptUItelu.spacing (unencoded), vapostscripttelu (unencoded), vapostscripttelu.spacing (unencoded), yapostscriptUItelu (unencoded), yapostscriptUItelu.spacing (unencoded), yapostscripttelu (unencoded) and yapostscripttelu.spacing (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 viramatelu (U+0C4D) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0C41, U+0C42, U+0C43 and U+0C44 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/Shaping Checks.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Bete-Bendi (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Ekpeye (Latn, 226,000 speakers), Mfumte (Latn, 79,000 speakers), Bafut (Latn, 158,146 speakers), South Central Banda (Latn, 244,000 speakers), Gulay (Latn, 250,478 speakers), Nateni (Latn, 100,000 speakers), Dii (Latn, 71,000 speakers), Igbo (Latn, 27,823,640 speakers), Aghem (Latn, 38,843 speakers), Yala (Latn, 200,000 speakers), Navajo (Latn, 166,319 speakers), Southern Kisi (Latn, 360,000 speakers), Mundani (Latn, 34,000 speakers), Cicipu (Latn, 44,000 speakers), Sar (Latn, 500,000 speakers), Makaa (Latn, 221,000 speakers), Kom (Latn, 360,685 speakers), Nzakara (Latn, 50,000 speakers), Koonzime (Latn, 40,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Avokaya (Latn, 100,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Zapotec (Latn, 490,000 speakers), Basaa (Latn, 332,940 speakers), Belarusian (Cyrl, 10,064,517 speakers), Ngbaka (Latn, 1,020,000 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Mango (Latn, 77,000 speakers), Lugbara (Latn, 2,200,000 speakers), Ejagham (Latn, 120,000 speakers), Fur (Latn, 1,230,163 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | ☠ FATAL | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
| 0 | 0 | 2 | 10 | 101 | 8 | 139 | 0 |
| 0% | 0% | 1% | 4% | 39% | 3% | 53% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
