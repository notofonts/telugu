## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[16] NotoSerifTelugu-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, canadian-aboriginal, old-permic, syriac, tifinagh, malayalam, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: grantha, tirhuta, devanagari, nandinagari
 * U+2010 HYPHEN: try adding one of: yi, coptic, kayah-li, sora-sompeng, sundanese, cham, kaithi, kharoshthi, lisu, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* autelu
	* auvowelsigntelu
	* auvowelsigntelu.spacing2
	* baavoweltelu
	* bauvoweltelu
	* beevoweltelu
	* bhaavoweltelu
	* bhauvoweltelu
	* bheevoweltelu
	* bhoovoweltelu
	* boovoweltelu
	* caavoweltelu
	* caivoweltelu
	* cauvoweltelu
	* ceevoweltelu
	* cevoweltelu
	* chaavoweltelu
	* chaivoweltelu
	* chauvoweltelu
	* cheevoweltelu
	* chevoweltelu
	* choovoweltelu
	* coovoweltelu
	* daavoweltelu
	* dahalanttelu
	* dailengthmarktelu
	* daivoweltelu
	* datelu
	* dauvoweltelu
	* ddaavoweltelu
	* ddahalanttelu
	* ddailengthmarktelu
	* ddaivoweltelu
	* ddatelu
	* ddauvoweltelu
	* ddeevoweltelu
	* ddevoweltelu
	* ddhaavoweltelu
	* ddhahalanttelu
	* ddhaivoweltelu
	* ddhatelu
	* ddhauvoweltelu
	* ddheevoweltelu
	* ddhevoweltelu
	* ddhiivoweltelu
	* ddhivoweltelu
	* ddhoovoweltelu
	* ddhovoweltelu
	* ddiivoweltelu
	* ddivoweltelu
	* ddoovoweltelu
	* ddovoweltelu
	* deevoweltelu
	* devoweltelu
	* dhaavoweltelu
	* dhahalanttelu
	* dhailengthmarktelu
	* dhaivoweltelu
	* dhatelu
	* dhauvoweltelu
	* dheevoweltelu
	* dhevoweltelu
	* dhiivoweltelu
	* dhivoweltelu
	* dhoovoweltelu
	* dhovoweltelu
	* diivoweltelu
	* divoweltelu
	* doovoweltelu
	* dovoweltelu
	* dzaavoweltelu
	* dzahalanttelu
	* dzaivoweltelu
	* dzauvoweltelu
	* dzeevoweltelu
	* dziivoweltelu
	* dzoovoweltelu
	* dzovoweltelu
	* dzuuvoweltelu
	* fivetelu
	* fourtelu
	* gahalanttelu
	* gailengthmarktelu
	* gaivoweltelu
	* gatelu
	* gauvoweltelu
	* geevoweltelu
	* gevoweltelu
	* ghaavoweltelu
	* ghahalanttelu
	* ghailengthmarktelu
	* ghaivoweltelu
	* ghatelu
	* ghauvoweltelu
	* gheevoweltelu
	* ghevoweltelu
	* ghiivoweltelu
	* ghivoweltelu
	* ghoovoweltelu
	* ghovoweltelu
	* giivoweltelu
	* goovoweltelu
	* haavoweltelu
	* hahalanttelu
	* hailengthmarktelu
	* haivoweltelu
	* hatelu
	* hauvoweltelu
	* heevoweltelu
	* hevoweltelu
	* hiivoweltelu
	* hivoweltelu
	* hoovoweltelu
	* hovoweltelu
	* iitelu
	* itelu
	* jaavoweltelu
	* jailengthmarktelu
	* jauvoweltelu
	* jeevoweltelu
	* jhaavoweltelu
	* jhahalanttelu
	* jhaivoweltelu
	* jhatelu
	* jhauvoweltelu
	* jheevoweltelu
	* jhevoweltelu
	* jhiivoweltelu
	* jhivoweltelu
	* jhoovoweltelu
	* jhovoweltelu
	* joovoweltelu
	* juuvoweltelu
	* kaavoweltelu
	* kahalanttelu
	* kaivoweltelu
	* kassaavoweltelu
	* kassahalanttelu
	* kassaivoweltelu
	* kassatelu
	* kassauvoweltelu
	* kasseevoweltelu
	* kassevoweltelu
	* kassiivoweltelu
	* kassivoweltelu
	* kassoovoweltelu
	* kassovoweltelu
	* katelu
	* kauvoweltelu
	* keevoweltelu
	* kevoweltelu
	* khaavoweltelu
	* khahalanttelu
	* khailengthmarktelu
	* khaivoweltelu
	* khatelu
	* khauvoweltelu
	* kheevoweltelu
	* khevoweltelu
	* khiivoweltelu
	* khivoweltelu
	* khoovoweltelu
	* khovoweltelu
	* kiivoweltelu
	* kivoweltelu
	* koovoweltelu
	* kovoweltelu
	* laavoweltelu
	* lailengthmarktelu
	* lauvoweltelu
	* leevoweltelu
	* llaavoweltelu
	* llaivoweltelu
	* llauvoweltelu
	* lleevoweltelu
	* llevoweltelu
	* lliivoweltelu
	* lllaavoweltelu
	* lllaivoweltelu
	* lllauvoweltelu
	* llleevoweltelu
	* llloovoweltelu
	* lloovoweltelu
	* llvocalictelu
	* loovoweltelu
	* maavoweltelu
	* maivoweltelu
	* matelu
	* mauvoweltelu
	* meevoweltelu
	* mevoweltelu
	* miivoweltelu
	* mivoweltelu
	* moovoweltelu
	* movoweltelu
	* naavoweltelu
	* naivoweltelu
	* nauvoweltelu
	* neevoweltelu
	* nevoweltelu
	* ngaavoweltelu
	* ngahalanttelu
	* ngaivoweltelu
	* ngauvoweltelu
	* ngeevoweltelu
	* ngevoweltelu
	* ngiivoweltelu
	* ngivoweltelu
	* ngoovoweltelu
	* ngovoweltelu
	* nnailengthmarktelu
	* nnaivoweltelu
	* nnauvoweltelu
	* nneevoweltelu
	* nnevoweltelu
	* nnoovoweltelu
	* numbersign.telu
	* nyaavoweltelu
	* nyahalanttelu
	* nyaivoweltelu
	* nyasubscripttelu
	* nyasubscripttelu.spacing
	* nyatelu
	* nyauvoweltelu
	* nyeevoweltelu
	* nyevoweltelu
	* nyiivoweltelu
	* nyivoweltelu
	* nyoovoweltelu
	* nyovoweltelu
	* paavoweltelu
	* pauvoweltelu
	* peevoweltelu
	* phaavoweltelu
	* phauvoweltelu
	* pheevoweltelu
	* phiivoweltelu
	* phoovoweltelu
	* phovoweltelu
	* phuuvoweltelu
	* phuvoweltelu
	* piivoweltelu
	* poovoweltelu
	* povoweltelu
	* puuvoweltelu
	* puvoweltelu
	* raavoweltelu
	* rahalanttelu
	* raivoweltelu
	* ratelu
	* rauvoweltelu
	* reevoweltelu
	* revoweltelu
	* riivoweltelu
	* roovoweltelu
	* rraavoweltelu
	* rraivoweltelu
	* rrauvoweltelu
	* rreevoweltelu
	* rroovoweltelu
	* rrraavoweltelu
	* rrrauvoweltelu
	* rrreevoweltelu
	* rrriivoweltelu
	* rrrivoweltelu
	* rrroovoweltelu
	* rrrovoweltelu
	* saavoweltelu
	* sauvoweltelu
	* shaavoweltelu
	* shaivoweltelu
	* shauvoweltelu
	* sheevoweltelu
	* shevoweltelu
	* shoovoweltelu
	* soovoweltelu
	* sovoweltelu
	* ssaavoweltelu
	* ssahalanttelu
	* ssailengthmarktelu
	* ssaivoweltelu
	* ssannasubscripttelu
	* ssatelu
	* ssauvoweltelu
	* sseevoweltelu
	* ssevoweltelu
	* ssiivoweltelu
	* ssivoweltelu
	* ssoovoweltelu
	* ssovoweltelu
	* taavoweltelu
	* tahalanttelu
	* tailengthmarknarrowtelu
	* tailengthmarktelu
	* taivoweltelu
	* tatelu
	* tauvoweltelu
	* teevoweltelu
	* tevoweltelu
	* thaavoweltelu
	* thahalanttelu
	* thailengthmarktelu
	* thaivoweltelu
	* thatelu
	* thauvoweltelu
	* theevoweltelu
	* thevoweltelu
	* thiivoweltelu
	* thivoweltelu
	* thoovoweltelu
	* thovoweltelu
	* tiivoweltelu
	* toovoweltelu
	* tovoweltelu
	* tsaavoweltelu
	* tsahalanttelu
	* tsaivoweltelu
	* tsauvoweltelu
	* tseevoweltelu
	* tsevoweltelu
	* tsiivoweltelu
	* tsoovoweltelu
	* tsovoweltelu
	* ttaavoweltelu
	* ttailengthmarktelu
	* ttaivoweltelu
	* ttauvoweltelu
	* tteevoweltelu
	* tthaavoweltelu
	* tthahalanttelu
	* tthaivoweltelu
	* tthatelu
	* tthauvoweltelu
	* ttheevoweltelu
	* tthevoweltelu
	* tthiivoweltelu
	* tthoovoweltelu
	* ttiivoweltelu
	* ttivoweltelu
	* ttoovoweltelu
	* ttovoweltelu
	* uni0C7B
	* utelu
	* uutelu
	* vaavoweltelu
	* vaivoweltelu
	* vauvoweltelu
	* veevoweltelu
	* vevoweltelu
	* viivoweltelu
	* voovoweltelu
	* vovoweltelu
	* vuuvoweltelu
	* vuvoweltelu
	* yaavoweltelu
	* yahalanttelu
	* yaivoweltelu
	* yatelu
	* yauvoweltelu
	* yeevoweltelu
	* yevoweltelu
	* yiivoweltelu
	* yivoweltelu
	* yoovoweltelu and yovoweltelu
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


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

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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

	* ygrave (U+1EF3): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[13] NotoSerifTelugu-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, canadian-aboriginal, old-permic, syriac, tifinagh, malayalam, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: grantha, tirhuta, devanagari, nandinagari
 * U+2010 HYPHEN: try adding one of: yi, coptic, kayah-li, sora-sompeng, sundanese, cham, kaithi, kharoshthi, lisu, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* autelu
	* auvowelsigntelu
	* auvowelsigntelu.spacing2
	* bauvoweltelu
	* bhauvoweltelu
	* bhoovoweltelu
	* boovoweltelu
	* caivoweltelu
	* cauvoweltelu
	* ceevoweltelu
	* cevoweltelu
	* chaavoweltelu
	* chaivoweltelu
	* chauvoweltelu
	* cheevoweltelu
	* chevoweltelu
	* choovoweltelu
	* coovoweltelu
	* daavoweltelu
	* dahalanttelu
	* dailengthmarktelu
	* daivoweltelu
	* datelu
	* dauvoweltelu
	* ddaavoweltelu
	* ddahalanttelu
	* ddailengthmarktelu
	* ddaivoweltelu
	* ddatelu
	* ddauvoweltelu
	* ddeevoweltelu
	* ddevoweltelu
	* ddhaavoweltelu
	* ddhahalanttelu
	* ddhaivoweltelu
	* ddhatelu
	* ddhauvoweltelu
	* ddheevoweltelu
	* ddhevoweltelu
	* ddhiivoweltelu
	* ddhivoweltelu
	* ddhoovoweltelu
	* ddhovoweltelu
	* ddiivoweltelu
	* ddivoweltelu
	* ddoovoweltelu
	* ddovoweltelu
	* deevoweltelu
	* devoweltelu
	* dhaavoweltelu
	* dhahalanttelu
	* dhailengthmarktelu
	* dhaivoweltelu
	* dhatelu
	* dhauvoweltelu
	* dheevoweltelu
	* dhevoweltelu
	* dhiivoweltelu
	* dhoovoweltelu
	* diivoweltelu
	* doovoweltelu
	* dzahalanttelu
	* dzauvoweltelu
	* dzeevoweltelu
	* dziivoweltelu
	* dzoovoweltelu
	* dzovoweltelu
	* dzuuvoweltelu
	* fourtelu
	* gauvoweltelu
	* geevoweltelu
	* ghaavoweltelu
	* ghahalanttelu
	* ghailengthmarktelu
	* ghaivoweltelu
	* ghauvoweltelu
	* gheevoweltelu
	* ghiivoweltelu
	* ghoovoweltelu
	* ghovoweltelu
	* goovoweltelu
	* haavoweltelu
	* hahalanttelu
	* hailengthmarktelu
	* haivoweltelu
	* hatelu
	* hauvoweltelu
	* heevoweltelu
	* hevoweltelu
	* hiivoweltelu
	* hivoweltelu
	* hoovoweltelu
	* hovoweltelu
	* iitelu
	* itelu
	* jailengthmarktelu
	* jauvoweltelu
	* jeevoweltelu
	* jhaavoweltelu
	* jhahalanttelu
	* jhaivoweltelu
	* jhatelu
	* jhauvoweltelu
	* jheevoweltelu
	* jhevoweltelu
	* jhiivoweltelu
	* jhivoweltelu
	* jhoovoweltelu
	* jhovoweltelu
	* joovoweltelu
	* juuvoweltelu
	* kaavoweltelu
	* kahalanttelu
	* kassaavoweltelu
	* kassahalanttelu
	* kassaivoweltelu
	* kassatelu
	* kassauvoweltelu
	* kasseevoweltelu
	* kassevoweltelu
	* kassiivoweltelu
	* kassivoweltelu
	* kassoovoweltelu
	* kassovoweltelu
	* kauvoweltelu
	* keevoweltelu
	* khaavoweltelu
	* khahalanttelu
	* khailengthmarktelu
	* khaivoweltelu
	* khatelu
	* khauvoweltelu
	* kheevoweltelu
	* khevoweltelu
	* khiivoweltelu
	* khivoweltelu
	* khoovoweltelu
	* khovoweltelu
	* kiivoweltelu
	* kivoweltelu
	* koovoweltelu
	* lauvoweltelu
	* llaivoweltelu
	* llauvoweltelu
	* lleevoweltelu
	* llevoweltelu
	* lllaavoweltelu
	* lllauvoweltelu
	* llleevoweltelu
	* lloovoweltelu
	* maavoweltelu
	* maivoweltelu
	* matelu
	* mauvoweltelu
	* meevoweltelu
	* mevoweltelu
	* miivoweltelu
	* moovoweltelu
	* movoweltelu
	* naavoweltelu
	* naivoweltelu
	* nauvoweltelu
	* neevoweltelu
	* nevoweltelu
	* ngaavoweltelu
	* ngahalanttelu
	* ngaivoweltelu
	* ngauvoweltelu
	* ngeevoweltelu
	* ngevoweltelu
	* ngiivoweltelu
	* ngivoweltelu
	* ngoovoweltelu
	* ngovoweltelu
	* nnailengthmarktelu
	* nnauvoweltelu
	* nneevoweltelu
	* numbersign.telu
	* nyaavoweltelu
	* nyahalanttelu
	* nyaivoweltelu
	* nyatelu
	* nyauvoweltelu
	* nyeevoweltelu
	* nyevoweltelu
	* nyiivoweltelu
	* nyivoweltelu
	* nyoovoweltelu
	* nyovoweltelu
	* paavoweltelu
	* pauvoweltelu
	* phaavoweltelu
	* phauvoweltelu
	* phoovoweltelu
	* phovoweltelu
	* phuuvoweltelu
	* poovoweltelu
	* povoweltelu
	* puuvoweltelu
	* raavoweltelu
	* rauvoweltelu
	* reevoweltelu
	* roovoweltelu
	* rraavoweltelu
	* rrauvoweltelu
	* rreevoweltelu
	* rrraavoweltelu
	* rrrauvoweltelu
	* rrreevoweltelu
	* rrriivoweltelu
	* rrrivoweltelu
	* rrroovoweltelu
	* saavoweltelu
	* sauvoweltelu
	* shaavoweltelu
	* shaivoweltelu
	* shauvoweltelu
	* sheevoweltelu
	* shevoweltelu
	* shoovoweltelu
	* soovoweltelu
	* sovoweltelu
	* ssaavoweltelu
	* ssahalanttelu
	* ssailengthmarktelu
	* ssaivoweltelu
	* ssauvoweltelu
	* sseevoweltelu
	* ssiivoweltelu
	* ssoovoweltelu
	* ssovoweltelu
	* taavoweltelu
	* taivoweltelu
	* tauvoweltelu
	* teevoweltelu
	* tevoweltelu
	* thaavoweltelu
	* thahalanttelu
	* thailengthmarktelu
	* thaivoweltelu
	* thatelu
	* thauvoweltelu
	* theevoweltelu
	* thevoweltelu
	* thiivoweltelu
	* thoovoweltelu
	* toovoweltelu
	* tsaavoweltelu
	* tsahalanttelu
	* tsaivoweltelu
	* tsauvoweltelu
	* tseevoweltelu
	* tsevoweltelu
	* tsiivoweltelu
	* tsoovoweltelu
	* tsovoweltelu
	* ttaavoweltelu
	* ttailengthmarktelu
	* ttauvoweltelu
	* tteevoweltelu
	* tthaavoweltelu
	* tthaivoweltelu
	* tthauvoweltelu
	* ttheevoweltelu
	* tthoovoweltelu
	* ttiivoweltelu
	* ttoovoweltelu
	* uni0C7B
	* utelu
	* uutelu
	* vaavoweltelu
	* vaivoweltelu
	* vauvoweltelu
	* veevoweltelu
	* vevoweltelu
	* voovoweltelu
	* vuuvoweltelu
	* vuvoweltelu
	* yaavoweltelu
	* yahalanttelu
	* yaivoweltelu
	* yatelu
	* yauvoweltelu
	* yeevoweltelu
	* yevoweltelu
	* yiivoweltelu
	* yivoweltelu
	* yoovoweltelu and yovoweltelu
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


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

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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

Your font does *not* cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, canadian-aboriginal, old-permic, syriac, tifinagh, malayalam, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: grantha, tirhuta, devanagari, nandinagari
 * U+2010 HYPHEN: try adding one of: yi, coptic, kayah-li, sora-sompeng, sundanese, cham, kaithi, kharoshthi, lisu, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* autelu
	* auvowelsigntelu
	* auvowelsigntelu.spacing2
	* bauvoweltelu
	* bhauvoweltelu
	* bhoovoweltelu
	* boovoweltelu
	* caavoweltelu
	* caivoweltelu
	* cauvoweltelu
	* ceevoweltelu
	* cevoweltelu
	* chaavoweltelu
	* chaivoweltelu
	* chauvoweltelu
	* cheevoweltelu
	* chevoweltelu
	* choovoweltelu
	* coovoweltelu
	* daavoweltelu
	* dahalanttelu
	* dailengthmarktelu
	* daivoweltelu
	* datelu
	* dauvoweltelu
	* ddaavoweltelu
	* ddahalanttelu
	* ddailengthmarktelu
	* ddaivoweltelu
	* ddatelu
	* ddauvoweltelu
	* ddeevoweltelu
	* ddevoweltelu
	* ddhaavoweltelu
	* ddhahalanttelu
	* ddhaivoweltelu
	* ddhatelu
	* ddhauvoweltelu
	* ddheevoweltelu
	* ddhevoweltelu
	* ddhiivoweltelu
	* ddhivoweltelu
	* ddhoovoweltelu
	* ddhovoweltelu
	* ddiivoweltelu
	* ddivoweltelu
	* ddoovoweltelu
	* ddovoweltelu
	* deevoweltelu
	* devoweltelu
	* dhaavoweltelu
	* dhahalanttelu
	* dhailengthmarktelu
	* dhaivoweltelu
	* dhatelu
	* dhauvoweltelu
	* dheevoweltelu
	* dhevoweltelu
	* dhiivoweltelu
	* dhoovoweltelu
	* dhovoweltelu
	* diivoweltelu
	* doovoweltelu
	* dovoweltelu
	* dzaavoweltelu
	* dzahalanttelu
	* dzauvoweltelu
	* dzeevoweltelu
	* dziivoweltelu
	* dzoovoweltelu
	* dzovoweltelu
	* dzuuvoweltelu
	* fourtelu
	* gahalanttelu
	* gaivoweltelu
	* gatelu
	* gauvoweltelu
	* geevoweltelu
	* gevoweltelu
	* ghaavoweltelu
	* ghahalanttelu
	* ghailengthmarktelu
	* ghaivoweltelu
	* ghatelu
	* ghauvoweltelu
	* gheevoweltelu
	* ghevoweltelu
	* ghiivoweltelu
	* ghivoweltelu
	* ghoovoweltelu
	* ghovoweltelu
	* giivoweltelu
	* goovoweltelu
	* haavoweltelu
	* hahalanttelu
	* hailengthmarktelu
	* haivoweltelu
	* hatelu
	* hauvoweltelu
	* heevoweltelu
	* hevoweltelu
	* hiivoweltelu
	* hivoweltelu
	* hoovoweltelu
	* hovoweltelu
	* iitelu
	* itelu
	* jailengthmarktelu
	* jauvoweltelu
	* jeevoweltelu
	* jhaavoweltelu
	* jhahalanttelu
	* jhaivoweltelu
	* jhatelu
	* jhauvoweltelu
	* jheevoweltelu
	* jhevoweltelu
	* jhiivoweltelu
	* jhivoweltelu
	* jhoovoweltelu
	* jhovoweltelu
	* joovoweltelu
	* juuvoweltelu
	* kaavoweltelu
	* kahalanttelu
	* kaivoweltelu
	* kassaavoweltelu
	* kassahalanttelu
	* kassaivoweltelu
	* kassatelu
	* kassauvoweltelu
	* kasseevoweltelu
	* kassevoweltelu
	* kassiivoweltelu
	* kassivoweltelu
	* kassoovoweltelu
	* kassovoweltelu
	* katelu
	* kauvoweltelu
	* keevoweltelu
	* kevoweltelu
	* khaavoweltelu
	* khahalanttelu
	* khailengthmarktelu
	* khaivoweltelu
	* khatelu
	* khauvoweltelu
	* kheevoweltelu
	* khevoweltelu
	* khiivoweltelu
	* khivoweltelu
	* khoovoweltelu
	* khovoweltelu
	* kiivoweltelu
	* kivoweltelu
	* koovoweltelu
	* lailengthmarktelu
	* lauvoweltelu
	* leevoweltelu
	* llaivoweltelu
	* llauvoweltelu
	* lleevoweltelu
	* llevoweltelu
	* lllaavoweltelu
	* lllauvoweltelu
	* llleevoweltelu
	* lloovoweltelu
	* maavoweltelu
	* maivoweltelu
	* matelu
	* mauvoweltelu
	* meevoweltelu
	* mevoweltelu
	* miivoweltelu
	* mivoweltelu
	* moovoweltelu
	* movoweltelu
	* naavoweltelu
	* naivoweltelu
	* nauvoweltelu
	* neevoweltelu
	* nevoweltelu
	* ngaavoweltelu
	* ngahalanttelu
	* ngaivoweltelu
	* ngauvoweltelu
	* ngeevoweltelu
	* ngevoweltelu
	* ngiivoweltelu
	* ngivoweltelu
	* ngoovoweltelu
	* ngovoweltelu
	* nnailengthmarktelu
	* nnauvoweltelu
	* nneevoweltelu
	* numbersign.telu
	* nyaavoweltelu
	* nyahalanttelu
	* nyaivoweltelu
	* nyatelu
	* nyauvoweltelu
	* nyeevoweltelu
	* nyevoweltelu
	* nyiivoweltelu
	* nyivoweltelu
	* nyoovoweltelu
	* nyovoweltelu
	* paavoweltelu
	* pauvoweltelu
	* peevoweltelu
	* phaavoweltelu
	* phauvoweltelu
	* pheevoweltelu
	* phiivoweltelu
	* phoovoweltelu
	* phovoweltelu
	* phuuvoweltelu
	* phuvoweltelu
	* piivoweltelu
	* poovoweltelu
	* povoweltelu
	* puuvoweltelu
	* puvoweltelu
	* raavoweltelu
	* rahalanttelu
	* raivoweltelu
	* rauvoweltelu
	* reevoweltelu
	* revoweltelu
	* riivoweltelu
	* roovoweltelu
	* rraavoweltelu
	* rrauvoweltelu
	* rreevoweltelu
	* rroovoweltelu
	* rrraavoweltelu
	* rrrauvoweltelu
	* rrreevoweltelu
	* rrriivoweltelu
	* rrrivoweltelu
	* rrroovoweltelu
	* saavoweltelu
	* sauvoweltelu
	* shaavoweltelu
	* shaivoweltelu
	* shauvoweltelu
	* sheevoweltelu
	* shevoweltelu
	* shoovoweltelu
	* soovoweltelu
	* sovoweltelu
	* ssaavoweltelu
	* ssahalanttelu
	* ssailengthmarktelu
	* ssaivoweltelu
	* ssatelu
	* ssauvoweltelu
	* sseevoweltelu
	* ssevoweltelu
	* ssiivoweltelu
	* ssivoweltelu
	* ssoovoweltelu
	* ssovoweltelu
	* taavoweltelu
	* tailengthmarknarrowtelu
	* taivoweltelu
	* tatelu
	* tauvoweltelu
	* teevoweltelu
	* tevoweltelu
	* thaavoweltelu
	* thahalanttelu
	* thailengthmarktelu
	* thaivoweltelu
	* thatelu
	* thauvoweltelu
	* theevoweltelu
	* thevoweltelu
	* thiivoweltelu
	* thoovoweltelu
	* thovoweltelu
	* tiivoweltelu
	* toovoweltelu
	* tovoweltelu
	* tsaavoweltelu
	* tsahalanttelu
	* tsaivoweltelu
	* tsauvoweltelu
	* tseevoweltelu
	* tsevoweltelu
	* tsiivoweltelu
	* tsoovoweltelu
	* tsovoweltelu
	* ttaavoweltelu
	* ttailengthmarktelu
	* ttauvoweltelu
	* tteevoweltelu
	* tthaavoweltelu
	* tthahalanttelu
	* tthaivoweltelu
	* tthauvoweltelu
	* ttheevoweltelu
	* tthevoweltelu
	* tthiivoweltelu
	* tthoovoweltelu
	* ttiivoweltelu
	* ttoovoweltelu
	* ttovoweltelu
	* uni0C7B
	* utelu
	* uutelu
	* vaavoweltelu
	* vaivoweltelu
	* vauvoweltelu
	* veevoweltelu
	* vevoweltelu
	* voovoweltelu
	* vuuvoweltelu
	* vuvoweltelu
	* yaavoweltelu
	* yahalanttelu
	* yaivoweltelu
	* yatelu
	* yauvoweltelu
	* yeevoweltelu
	* yevoweltelu
	* yiivoweltelu
	* yivoweltelu
	* yoovoweltelu and yovoweltelu
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


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

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* khatelu (U+0C16): B<<283.0,300.5>-<256.0,274.0>-<209.0,268.0>>/B<<209.0,268.0>-<250.0,265.0>-<282.5,256.0>> = 11.459921083007638

	* khatelu (U+0C16): B<<56.0,227.0>-<89.0,262.0>-<152.0,267.0>>/B<<152.0,267.0>-<100.0,274.0>-<71.0,303.5>> = 12.204576769720791

	* y (U+0079): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* yacute (U+00FD): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ycircumflex (U+0177): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ydieresis (U+00FF): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ygrave (U+1EF3): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<444.0,335.0>--<285.0,336.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[15] NotoSerifTelugu-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, canadian-aboriginal, old-permic, syriac, tifinagh, malayalam, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: grantha, tirhuta, devanagari, nandinagari
 * U+2010 HYPHEN: try adding one of: yi, coptic, kayah-li, sora-sompeng, sundanese, cham, kaithi, kharoshthi, lisu, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* dauvoweltelu
	* ddauvoweltelu
	* ddhauvoweltelu
	* dhauvoweltelu
	* gauvoweltelu
	* ghauvoweltelu
	* hauvoweltelu
	* jhauvoweltelu
	* kassauvoweltelu
	* kauvoweltelu
	* nyauvoweltelu
	* rauvoweltelu
	* ssauvoweltelu
	* thauvoweltelu
	* tthauvoweltelu and vauvoweltelu
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


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

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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

	* ttatelu (U+0C1F): B<<146.0,413.5>-<151.0,427.0>-<160.0,439.0>>/B<<160.0,439.0>-<116.0,403.0>-<96.0,349.0>> = 13.840695491655639

	* uni0C7F (U+0C7F): B<<149.0,413.5>-<154.0,429.0>-<168.0,443.0>>/B<<168.0,443.0>-<133.0,419.0>-<107.5,375.5>> = 10.56101069119633

	* utelu (U+0C09): B<<609.5,66.5>-<638.0,105.0>-<641.0,171.0>>/B<<641.0,171.0>-<633.0,135.0>-<609.5,113.5>> = 9.926245506651668

	* uutelu (U+0C0A): B<<609.5,66.5>-<638.0,105.0>-<641.0,171.0>>/B<<641.0,171.0>-<633.0,135.0>-<609.5,113.5>> = 9.926245506651668 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[17] NotoSerifTelugu-Light.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Familyname must be unique according to namecheck.fontdata.com (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fontdata_namecheck">com.google.fonts/check/fontdata_namecheck</a>)</summary><div>


* 💔 **ERROR** Failed to access: http://namecheck.fontdata.com.
		This check relies on the external service http://namecheck.fontdata.com via the internet. While the service cannot be reached or does not respond this check is broken.

		You can exclude this check with the command line option:
		-x com.google.fonts/check/fontdata_namecheck

		Or you can wait until the service is available again.
		If the problem persists please report this issue at: https://github.com/fonttools/fontbakery/issues

		Original error message:
		<class 'requests.exceptions.ReadTimeout'> [code: namecheck-service]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, canadian-aboriginal, old-permic, syriac, tifinagh, malayalam, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: grantha, tirhuta, devanagari, nandinagari
 * U+2010 HYPHEN: try adding one of: yi, coptic, kayah-li, sora-sompeng, sundanese, cham, kaithi, kharoshthi, lisu, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* autelu
	* bauvoweltelu
	* bhauvoweltelu
	* cauvoweltelu
	* chauvoweltelu
	* dauvoweltelu
	* ddauvoweltelu
	* ddhauvoweltelu
	* dhauvoweltelu
	* dzauvoweltelu
	* dzoovoweltelu
	* gauvoweltelu
	* ghauvoweltelu
	* hauvoweltelu
	* hoovoweltelu
	* jauvoweltelu
	* jhauvoweltelu
	* kassauvoweltelu
	* kauvoweltelu
	* khauvoweltelu
	* llauvoweltelu
	* maivoweltelu
	* mauvoweltelu
	* meevoweltelu
	* moovoweltelu
	* movoweltelu
	* nauvoweltelu
	* ngauvoweltelu
	* numbersign.telu
	* nyauvoweltelu
	* pauvoweltelu
	* phauvoweltelu
	* rauvoweltelu
	* rrrauvoweltelu
	* sauvoweltelu
	* shauvoweltelu
	* ssauvoweltelu
	* tauvoweltelu
	* thauvoweltelu
	* tsauvoweltelu
	* tsoovoweltelu
	* ttauvoweltelu
	* tthauvoweltelu
	* vauvoweltelu and yauvoweltelu
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


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

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ddatelu (U+0C21): B<<585.5,82.5>-<613.0,117.0>-<616.0,178.0>>/B<<616.0,178.0>-<607.0,143.0>-<582.5,123.0>> = 11.60521644329975

	* ddhatelu (U+0C22): B<<585.5,82.5>-<613.0,117.0>-<616.0,178.0>>/B<<616.0,178.0>-<607.0,143.0>-<582.5,123.0>> = 11.60521644329975

	* utelu (U+0C09): B<<610.0,83.0>-<637.0,118.0>-<640.0,176.0>>/B<<640.0,176.0>-<631.0,140.0>-<606.5,119.5>> = 11.07530733376276

	* uutelu (U+0C0A): B<<610.0,83.0>-<637.0,118.0>-<640.0,176.0>>/B<<640.0,176.0>-<631.0,140.0>-<606.5,119.5>> = 11.07530733376276 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* catelu (U+0C1A): L<<160.0,280.0>--<23.0,281.0>>

	* chatelu (U+0C1B): L<<160.0,280.0>--<23.0,281.0>>

	* tsatelu (U+0C58): L<<160.0,280.0>--<23.0,281.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, canadian-aboriginal, old-permic, syriac, tifinagh, malayalam, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: grantha, tirhuta, devanagari, nandinagari
 * U+2010 HYPHEN: try adding one of: yi, coptic, kayah-li, sora-sompeng, sundanese, cham, kaithi, kharoshthi, lisu, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* autelu
	* auvowelsigntelu
	* auvowelsigntelu.spacing2
	* bauvoweltelu
	* bhauvoweltelu
	* cauvoweltelu
	* ceevoweltelu
	* chauvoweltelu
	* cheevoweltelu
	* daavoweltelu
	* dauvoweltelu
	* ddaavoweltelu
	* ddahalanttelu
	* ddauvoweltelu
	* ddeevoweltelu
	* ddhaavoweltelu
	* ddhahalanttelu
	* ddhauvoweltelu
	* ddheevoweltelu
	* ddhiivoweltelu
	* ddhivoweltelu
	* ddhoovoweltelu
	* ddiivoweltelu
	* ddivoweltelu
	* ddoovoweltelu
	* deevoweltelu
	* dhaavoweltelu
	* dhauvoweltelu
	* dheevoweltelu
	* dzahalanttelu
	* dzauvoweltelu
	* dzeevoweltelu
	* dzoovoweltelu
	* dzovoweltelu
	* gauvoweltelu
	* ghailengthmarktelu
	* ghauvoweltelu
	* haavoweltelu
	* hahalanttelu
	* hailengthmarktelu
	* hauvoweltelu
	* heevoweltelu
	* hiivoweltelu
	* hoovoweltelu
	* hovoweltelu
	* iitelu
	* jauvoweltelu
	* jhaavoweltelu
	* jhahalanttelu
	* jhaivoweltelu
	* jhatelu
	* jhauvoweltelu
	* jheevoweltelu
	* jhevoweltelu
	* jhiivoweltelu
	* jhivoweltelu
	* jhoovoweltelu
	* jhovoweltelu
	* kassaavoweltelu
	* kassahalanttelu
	* kassaivoweltelu
	* kassatelu
	* kassauvoweltelu
	* kasseevoweltelu
	* kassevoweltelu
	* kassiivoweltelu
	* kassivoweltelu
	* kassoovoweltelu
	* kauvoweltelu
	* khaavoweltelu
	* khahalanttelu
	* khailengthmarktelu
	* khaivoweltelu
	* khauvoweltelu
	* kheevoweltelu
	* khevoweltelu
	* khoovoweltelu
	* khovoweltelu
	* kiivoweltelu
	* kivoweltelu
	* lauvoweltelu
	* llauvoweltelu
	* lllaavoweltelu
	* lllauvoweltelu
	* maavoweltelu
	* maivoweltelu
	* mauvoweltelu
	* meevoweltelu
	* mevoweltelu
	* moovoweltelu
	* movoweltelu
	* naavoweltelu
	* naivoweltelu
	* nauvoweltelu
	* neevoweltelu
	* nevoweltelu
	* ngauvoweltelu
	* ngeevoweltelu
	* ngiivoweltelu
	* ngoovoweltelu
	* nnauvoweltelu
	* numbersign.telu
	* nyaavoweltelu
	* nyahalanttelu
	* nyaivoweltelu
	* nyauvoweltelu
	* nyeevoweltelu
	* nyevoweltelu
	* nyiivoweltelu
	* nyivoweltelu
	* nyoovoweltelu
	* nyovoweltelu
	* pauvoweltelu
	* phauvoweltelu
	* phoovoweltelu
	* phovoweltelu
	* poovoweltelu
	* povoweltelu
	* rauvoweltelu
	* reevoweltelu
	* rraavoweltelu
	* rrauvoweltelu
	* rrraavoweltelu
	* rrrauvoweltelu
	* rrriivoweltelu
	* rrrivoweltelu
	* sauvoweltelu
	* shauvoweltelu
	* sheevoweltelu
	* soovoweltelu
	* ssaavoweltelu
	* ssailengthmarktelu
	* ssauvoweltelu
	* ssoovoweltelu
	* ssovoweltelu
	* taivoweltelu
	* tauvoweltelu
	* teevoweltelu
	* tevoweltelu
	* thaavoweltelu
	* thauvoweltelu
	* theevoweltelu
	* toovoweltelu
	* tsahalanttelu
	* tsaivoweltelu
	* tsauvoweltelu
	* tseevoweltelu
	* tsiivoweltelu
	* tsoovoweltelu
	* tsovoweltelu
	* ttauvoweltelu
	* tthauvoweltelu
	* uni0C7B
	* utelu
	* uutelu
	* vaavoweltelu
	* vaivoweltelu
	* vauvoweltelu
	* veevoweltelu
	* vevoweltelu
	* vuuvoweltelu
	* yaavoweltelu
	* yahalanttelu
	* yaivoweltelu
	* yauvoweltelu
	* yeevoweltelu
	* yevoweltelu
	* yiivoweltelu
	* yoovoweltelu and yovoweltelu
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


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

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uutelu (U+0C0A): B<<612.5,117.0>-<637.0,145.0>-<641.0,189.0>>/B<<641.0,189.0>-<630.0,157.0>-<604.5,139.0>> = 13.775978900751738 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* catelu (U+0C1A): L<<147.0,280.0>--<21.0,279.0>>

	* chatelu (U+0C1B): L<<147.0,280.0>--<21.0,279.0>>

	* tsatelu (U+0C58): L<<147.0,280.0>--<21.0,279.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-Regular.ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 💔 **ERROR** Failed with KeyError: 'casubscripttelu'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, canadian-aboriginal, old-permic, syriac, tifinagh, malayalam, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: grantha, tirhuta, devanagari, nandinagari
 * U+2010 HYPHEN: try adding one of: yi, coptic, kayah-li, sora-sompeng, sundanese, cham, kaithi, kharoshthi, lisu, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* autelu
	* auvowelsigntelu.spacing2
	* bauvoweltelu
	* bhauvoweltelu
	* cauvoweltelu
	* ceevoweltelu
	* chauvoweltelu
	* cheevoweltelu
	* daavoweltelu
	* dauvoweltelu
	* ddaavoweltelu
	* ddauvoweltelu
	* ddeevoweltelu
	* ddhaavoweltelu
	* ddhauvoweltelu
	* ddheevoweltelu
	* ddhiivoweltelu
	* ddhivoweltelu
	* ddhoovoweltelu
	* ddiivoweltelu
	* ddivoweltelu
	* ddoovoweltelu
	* deevoweltelu
	* dhaavoweltelu
	* dhauvoweltelu
	* dheevoweltelu
	* dzahalanttelu
	* dzauvoweltelu
	* dzeevoweltelu
	* dzoovoweltelu
	* dzovoweltelu
	* gauvoweltelu
	* ghailengthmarktelu
	* ghauvoweltelu
	* haavoweltelu
	* hailengthmarktelu
	* hauvoweltelu
	* hiivoweltelu
	* hoovoweltelu
	* hovoweltelu
	* iitelu
	* jauvoweltelu
	* jhaavoweltelu
	* jhahalanttelu
	* jhaivoweltelu
	* jhatelu
	* jhauvoweltelu
	* jheevoweltelu
	* jhevoweltelu
	* jhiivoweltelu
	* jhoovoweltelu
	* jhovoweltelu
	* kassahalanttelu
	* kassauvoweltelu
	* kasseevoweltelu
	* kassiivoweltelu
	* kassivoweltelu
	* kassoovoweltelu
	* kauvoweltelu
	* khailengthmarktelu
	* khauvoweltelu
	* kheevoweltelu
	* khoovoweltelu
	* kiivoweltelu
	* lauvoweltelu
	* llauvoweltelu
	* lllaavoweltelu
	* lllauvoweltelu
	* maivoweltelu
	* mauvoweltelu
	* meevoweltelu
	* mevoweltelu
	* moovoweltelu
	* movoweltelu
	* nauvoweltelu
	* neevoweltelu
	* ngauvoweltelu
	* ngeevoweltelu
	* ngiivoweltelu
	* nnauvoweltelu
	* numbersign.telu
	* nyaavoweltelu
	* nyahalanttelu
	* nyaivoweltelu
	* nyauvoweltelu
	* nyeevoweltelu
	* nyevoweltelu
	* nyiivoweltelu
	* nyivoweltelu
	* nyoovoweltelu
	* pauvoweltelu
	* phauvoweltelu
	* phoovoweltelu
	* poovoweltelu
	* rauvoweltelu
	* rraavoweltelu
	* rrauvoweltelu
	* rrraavoweltelu
	* rrrauvoweltelu
	* rrriivoweltelu
	* rrrivoweltelu
	* sauvoweltelu
	* shauvoweltelu
	* ssaavoweltelu
	* ssailengthmarktelu
	* ssauvoweltelu
	* ssoovoweltelu
	* ssovoweltelu
	* tauvoweltelu
	* teevoweltelu
	* thaavoweltelu
	* thauvoweltelu
	* theevoweltelu
	* tsahalanttelu
	* tsauvoweltelu
	* tseevoweltelu
	* tsiivoweltelu
	* tsoovoweltelu
	* tsovoweltelu
	* ttauvoweltelu
	* tthauvoweltelu
	* uni0C7B
	* utelu
	* uutelu
	* vaavoweltelu
	* vaivoweltelu
	* vauvoweltelu
	* veevoweltelu
	* vevoweltelu
	* yauvoweltelu
	* yeevoweltelu
	* yoovoweltelu and yovoweltelu
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


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

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* ddatelu (U+0C21): B<<589.5,105.5>-<615.0,135.0>-<618.0,187.0>>/B<<618.0,187.0>-<598.0,116.0>-<516.0,116.0>> = 12.430139110672277

	* ddhatelu (U+0C22): B<<589.5,105.5>-<615.0,135.0>-<618.0,187.0>>/B<<618.0,187.0>-<598.0,116.0>-<516.0,116.0>> = 12.430139110672277

	* utelu (U+0C09): B<<611.0,106.0>-<635.0,136.0>-<639.0,183.0>>/B<<639.0,183.0>-<629.0,148.0>-<603.0,128.5>> = 11.080881463162276

	* uutelu (U+0C0A): B<<611.0,106.0>-<635.0,136.0>-<639.0,183.0>>/B<<639.0,183.0>-<629.0,148.0>-<603.0,128.5>> = 11.080881463162276 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* catelu (U+0C1A): L<<148.0,274.0>--<22.0,273.0>>

	* chatelu (U+0C1B): L<<148.0,274.0>--<22.0,273.0>>

	* tsatelu (U+0C58): L<<148.0,274.0>--<22.0,273.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, canadian-aboriginal, old-permic, syriac, tifinagh, malayalam, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: grantha, tirhuta, devanagari, nandinagari
 * U+2010 HYPHEN: try adding one of: yi, coptic, kayah-li, sora-sompeng, sundanese, cham, kaithi, kharoshthi, lisu, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* autelu
	* auvowelsigntelu
	* auvowelsigntelu.spacing2
	* bauvoweltelu
	* bhauvoweltelu
	* caivoweltelu
	* cauvoweltelu
	* ceevoweltelu
	* cevoweltelu
	* chaivoweltelu
	* chauvoweltelu
	* cheevoweltelu
	* chevoweltelu
	* daavoweltelu
	* dahalanttelu
	* daivoweltelu
	* dauvoweltelu
	* ddaavoweltelu
	* ddahalanttelu
	* ddaivoweltelu
	* ddauvoweltelu
	* ddeevoweltelu
	* ddevoweltelu
	* ddhaavoweltelu
	* ddhahalanttelu
	* ddhaivoweltelu
	* ddhauvoweltelu
	* ddheevoweltelu
	* ddhevoweltelu
	* ddhiivoweltelu
	* ddhivoweltelu
	* ddhoovoweltelu
	* ddiivoweltelu
	* ddivoweltelu
	* ddoovoweltelu
	* deevoweltelu
	* devoweltelu
	* dhaavoweltelu
	* dhahalanttelu
	* dhailengthmarktelu
	* dhaivoweltelu
	* dhauvoweltelu
	* dheevoweltelu
	* dhevoweltelu
	* dhiivoweltelu
	* dhoovoweltelu
	* diivoweltelu
	* doovoweltelu
	* dzahalanttelu
	* dzauvoweltelu
	* dzeevoweltelu
	* dzoovoweltelu
	* dzovoweltelu
	* dzuuvoweltelu
	* fourtelu
	* gauvoweltelu
	* geevoweltelu
	* ghaavoweltelu
	* ghailengthmarktelu
	* ghauvoweltelu
	* gheevoweltelu
	* ghiivoweltelu
	* ghoovoweltelu
	* ghovoweltelu
	* haavoweltelu
	* hahalanttelu
	* hailengthmarktelu
	* haivoweltelu
	* hatelu
	* hauvoweltelu
	* heevoweltelu
	* hevoweltelu
	* hiivoweltelu
	* hivoweltelu
	* hoovoweltelu
	* hovoweltelu
	* iitelu
	* jailengthmarktelu
	* jauvoweltelu
	* jeevoweltelu
	* jhaavoweltelu
	* jhahalanttelu
	* jhaivoweltelu
	* jhatelu
	* jhauvoweltelu
	* jheevoweltelu
	* jhevoweltelu
	* jhiivoweltelu
	* jhivoweltelu
	* jhoovoweltelu
	* jhovoweltelu
	* juuvoweltelu
	* kaavoweltelu
	* kahalanttelu
	* kassaavoweltelu
	* kassahalanttelu
	* kassaivoweltelu
	* kassatelu
	* kassauvoweltelu
	* kasseevoweltelu
	* kassevoweltelu
	* kassiivoweltelu
	* kassivoweltelu
	* kassoovoweltelu
	* kassovoweltelu
	* kauvoweltelu
	* keevoweltelu
	* khaavoweltelu
	* khahalanttelu
	* khailengthmarktelu
	* khaivoweltelu
	* khauvoweltelu
	* kheevoweltelu
	* khevoweltelu
	* khiivoweltelu
	* khivoweltelu
	* khoovoweltelu
	* khovoweltelu
	* kiivoweltelu
	* kivoweltelu
	* koovoweltelu
	* lauvoweltelu
	* llauvoweltelu
	* lleevoweltelu
	* lllaavoweltelu
	* lllauvoweltelu
	* llleevoweltelu
	* maavoweltelu
	* maivoweltelu
	* mauvoweltelu
	* meevoweltelu
	* mevoweltelu
	* miivoweltelu
	* moovoweltelu
	* movoweltelu
	* naavoweltelu
	* naivoweltelu
	* nauvoweltelu
	* neevoweltelu
	* nevoweltelu
	* ngaavoweltelu
	* ngaivoweltelu
	* ngauvoweltelu
	* ngeevoweltelu
	* ngevoweltelu
	* ngiivoweltelu
	* ngivoweltelu
	* ngoovoweltelu
	* nnailengthmarktelu
	* nnauvoweltelu
	* numbersign.telu
	* nyaavoweltelu
	* nyahalanttelu
	* nyaivoweltelu
	* nyatelu
	* nyauvoweltelu
	* nyeevoweltelu
	* nyevoweltelu
	* nyiivoweltelu
	* nyivoweltelu
	* nyoovoweltelu
	* nyovoweltelu
	* paavoweltelu
	* pauvoweltelu
	* phaavoweltelu
	* phauvoweltelu
	* phoovoweltelu
	* phovoweltelu
	* phuuvoweltelu
	* poovoweltelu
	* povoweltelu
	* puuvoweltelu
	* raavoweltelu
	* rauvoweltelu
	* reevoweltelu
	* rraavoweltelu
	* rrauvoweltelu
	* rreevoweltelu
	* rrraavoweltelu
	* rrrauvoweltelu
	* rrriivoweltelu
	* rrrivoweltelu
	* rrroovoweltelu
	* sauvoweltelu
	* shaivoweltelu
	* shauvoweltelu
	* sheevoweltelu
	* shevoweltelu
	* soovoweltelu
	* sovoweltelu
	* ssaavoweltelu
	* ssailengthmarktelu
	* ssauvoweltelu
	* sseevoweltelu
	* ssiivoweltelu
	* ssoovoweltelu
	* ssovoweltelu
	* taivoweltelu
	* tauvoweltelu
	* teevoweltelu
	* tevoweltelu
	* thaavoweltelu
	* thahalanttelu
	* thailengthmarktelu
	* thaivoweltelu
	* thauvoweltelu
	* theevoweltelu
	* thiivoweltelu
	* thoovoweltelu
	* toovoweltelu
	* tsahalanttelu
	* tsaivoweltelu
	* tsauvoweltelu
	* tseevoweltelu
	* tsevoweltelu
	* tsiivoweltelu
	* tsoovoweltelu
	* tsovoweltelu
	* ttailengthmarktelu
	* ttauvoweltelu
	* tteevoweltelu
	* tthaavoweltelu
	* tthauvoweltelu
	* ttheevoweltelu
	* ttiivoweltelu
	* ttoovoweltelu
	* uni0C7B
	* utelu
	* uutelu
	* vaavoweltelu
	* vaivoweltelu
	* vauvoweltelu
	* veevoweltelu
	* vevoweltelu
	* vuuvoweltelu
	* yaavoweltelu
	* yahalanttelu
	* yaivoweltelu
	* yatelu
	* yauvoweltelu
	* yeevoweltelu
	* yevoweltelu
	* yiivoweltelu
	* yoovoweltelu and yovoweltelu
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


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

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* katelu (U+0C15): L<<230.0,504.0>--<234.0,504.0>> -> L<<234.0,504.0>--<235.0,504.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* catelu (U+0C1A): L<<146.0,287.0>--<20.0,286.0>>

	* chatelu (U+0C1B): L<<146.0,287.0>--<20.0,286.0>>

	* sterling (U+00A3): L<<419.0,336.0>--<262.0,337.0>>

	* tsatelu (U+0C58): L<<146.0,287.0>--<20.0,286.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details><details><summary><b>[16] NotoSerifTelugu-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 869 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.telu": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, yi, canadian-aboriginal
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: yi, canadian-aboriginal
 * U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal
 * U+02DB OGONEK: try adding one of: yi, canadian-aboriginal
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: coptic, canadian-aboriginal, old-permic, syriac, tifinagh, malayalam, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+1CF2 VEDIC SIGN ARDHAVISARGA: try adding one of: grantha, tirhuta, devanagari, nandinagari
 * U+2010 HYPHEN: try adding one of: yi, coptic, kayah-li, sora-sompeng, sundanese, cham, kaithi, kharoshthi, lisu, syloti-nagri

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext`, `telugu` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* hauvoweltelu
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Telugu Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


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

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
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

	* rratelu (U+0C31): B<<140.0,416.0>-<145.0,430.0>-<154.0,442.0>>/B<<154.0,442.0>-<111.0,404.0>-<92.0,347.0>> = 11.662396938046887

	* sterling (U+00A3): B<<192.0,89.0>-<173.0,58.0>-<145.0,40.0>>/L<<145.0,40.0>--<149.0,42.0>> = 6.170175095029526

	* tatelu (U+0C24): B<<115.0,341.5>-<124.0,362.0>-<144.0,379.0>>/B<<144.0,379.0>-<107.0,358.0>-<87.0,322.5>> = 10.786697891836063

	* ttatelu (U+0C1F): B<<151.0,421.5>-<158.0,438.0>-<171.0,451.0>>/B<<171.0,451.0>-<119.0,415.0>-<96.0,355.0>> = 10.304846468766009

	* uni0C7F (U+0C7F): B<<152.5,420.5>-<159.0,438.0>-<178.0,456.0>>/B<<178.0,456.0>-<138.0,430.0>-<108.5,383.0>> = 10.427974745225361

	* utelu (U+0C09): B<<609.5,56.0>-<639.0,97.0>-<642.0,168.0>>/B<<642.0,168.0>-<634.0,132.0>-<611.5,109.5>> = 10.109298492495101

	* uutelu (U+0C0A): B<<609.5,56.0>-<639.0,97.0>-<642.0,168.0>>/B<<642.0,168.0>-<634.0,132.0>-<611.5,109.5>> = 10.109298492495101 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.telu (U+0021): L<<126.0,176.0>--<122.0,657.0>>

	* exclam.telu (U+0021): L<<150.0,657.0>--<148.0,176.0>>

	* exclamdown (U+00A1): L<<123.0,-177.0>--<124.0,370.0>>

	* exclamdown (U+00A1): L<<149.0,370.0>--<152.0,-177.0>> [code: found-semi-vertical]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Dan (Latn, 1,099,244 speakers), Avokaya (Latn, 100,000 speakers), Ejagham (Latn, 120,000 speakers), Aghem (Latn, 38,843 speakers), Ma’di (Latn, 584,000 speakers), Lugbara (Latn, 2,200,000 speakers), Kom (Latn, 360,685 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dutch (Latn, 31,709,104 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Nateni (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 2 | 27 | 112 | 1054 | 55 | 855 | 0 |
| 0% | 1% | 5% | 50% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
