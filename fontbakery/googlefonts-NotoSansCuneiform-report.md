## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[12] NotoSansCuneiform-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 2.0 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 2.0 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansCuneiform/googlefonts/ttf/NotoSansCuneiform-Regular.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- uni00A0.1
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 commaaccent2 (unencoded) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u120B6 (U+120B6): L<<242.0,291.0>--<242.0,292.0>> -> L<<242.0,292.0>--<245.0,336.0>>

	* u12126 (U+12126): L<<164.0,3.0>--<158.0,98.0>> -> L<<158.0,98.0>--<158.0,101.0>>

	* u1214D (U+1214D): L<<200.0,360.0>--<200.0,361.0>> -> L<<200.0,361.0>--<202.0,391.0>>

	* u12194 (U+12194): L<<1005.0,936.0>--<1008.0,924.0>> -> L<<1008.0,924.0>--<1011.0,915.0>>

	* u12194 (U+12194): L<<1179.0,107.0>--<1149.0,149.0>> -> L<<1149.0,149.0>--<1116.0,194.0>>

	* u12194 (U+12194): L<<334.0,-118.0>--<331.0,-74.0>> -> L<<331.0,-74.0>--<331.0,-66.0>>

	* u12194 (U+12194): L<<978.0,105.0>--<1005.0,63.0>> -> L<<1005.0,63.0>--<1032.0,24.0>> 

	* And u1220B (U+1220B): L<<1190.0,431.0>--<1187.0,413.0>> -> L<<1187.0,413.0>--<1185.0,393.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u12009 (U+12009): B<<1105.5,92.5>-<1100.0,203.0>-<1090.0,300.0>>/B<<1090.0,300.0>-<1088.0,276.0>-<1087.0,251.0>> = 10.649629523754403

	* u12009 (U+12009): B<<488.5,232.0>-<487.0,249.0>-<485.0,267.0>>/B<<485.0,267.0>-<474.0,131.0>-<468.0,6.0>> = 10.964343074338954

	* u12017 (U+12017): B<<1064.0,52.5>-<1090.0,67.0>-<1122.0,89.0>>/B<<1122.0,89.0>-<991.0,30.0>-<880.5,-24.5>> = 10.26259430646775

	* u12017 (U+12017): B<<887.5,670.5>-<996.0,618.0>-<1124.0,560.0>>/B<<1124.0,560.0>-<1090.0,583.0>-<1062.5,598.0>> = 9.700726663455956

	* u12017 (U+12017): B<<984.5,515.0>-<1015.0,511.0>-<1046.0,507.0>>/B<<1046.0,507.0>-<867.0,562.0>-<726.0,597.0>> = 9.727854211999025

	* u12019 (U+12019): B<<1196.5,454.0>-<1211.0,450.0>-<1230.0,446.0>>/B<<1230.0,446.0>-<1217.0,451.0>-<1203.5,455.0>> = 9.148852985793804

	* u12019 (U+12019): L<<1087.0,61.0>--<1123.0,89.0>>/L<<1123.0,89.0>--<1064.0,62.0>> = 13.284866484902132

	* u1201D (U+1201D): B<<1254.5,403.0>-<1253.0,425.0>-<1251.0,447.0>>/B<<1251.0,447.0>-<1241.0,349.0>-<1233.0,214.0>> = 11.020770937290555

	* u1201F (U+1201F): L<<617.0,413.0>--<627.0,413.0>>/B<<627.0,413.0>-<605.0,418.0>-<587.5,420.0>> = 12.80426606528674

	* u12021 (U+12021): B<<958.0,213.0>-<925.0,196.0>-<908.0,185.0>>/L<<908.0,185.0>--<1033.0,234.0>> = 11.500063492869367 

	* And 567 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 5 | 7 | 116 | 8 | 99 | 0 |
| 0% | 2% | 3% | 49% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
