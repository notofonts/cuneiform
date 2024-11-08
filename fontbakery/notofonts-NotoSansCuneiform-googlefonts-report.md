## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[10] NotoSansCuneiform-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansCuneiform/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: coptic, math, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: coptic, hebrew, math, old-permic, tai-le, tifinagh, duployan, syriac, todhri, canadian-aboriginal, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cuneiform</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ekpeye (Latn, 226,000 speakers), Heiltsuk (Latn, 300 speakers), Lugbara (Latn, 2,200,000 speakers), Yala (Latn, 200,000 speakers), Makaa (Latn, 221,000 speakers), Igbo (Latn, 27,823,640 speakers), Teke-Ebo (Latn, 260,000 speakers), Gulay (Latn, 250,478 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Kaska (Latn, 125 speakers), Avokaya (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), Vute (Latn, 21,000 speakers), Ebira (Latn, 2,200,000 speakers), Mfumte (Latn, 79,000 speakers), Han (Latn, 6 speakers), Navajo (Latn, 166,319 speakers), Ngbaka (Latn, 1,020,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), South Central Banda (Latn, 244,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Dii (Latn, 71,000 speakers), Ejagham (Latn, 120,000 speakers), Nateni (Latn, 100,000 speakers), Ma’di (Latn, 584,000 speakers), Fur (Latn, 1,230,163 speakers), Bete-Bendi (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Zapotec (Latn, 490,000 speakers), Basaa (Latn, 332,940 speakers), Mundani (Latn, 34,000 speakers), Aghem (Latn, 38,843 speakers), Nzakara (Latn, 50,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Bafut (Latn, 158,146 speakers), Kom (Latn, 360,685 speakers), Koonzime (Latn, 40,000 speakers), Mango (Latn, 77,000 speakers), Sar (Latn, 500,000 speakers), Southern Kisi (Latn, 360,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* u120B6 (U+120B6): L&lt;&lt;242.0,291.0&gt;--&lt;242.0,292.0&gt;&gt; -&gt; L&lt;&lt;242.0,292.0&gt;--&lt;245.0,336.0&gt;&gt;

* u12126 (U+12126): L&lt;&lt;164.0,3.0&gt;--&lt;158.0,98.0&gt;&gt; -&gt; L&lt;&lt;158.0,98.0&gt;--&lt;158.0,101.0&gt;&gt;

* u1214D (U+1214D): L&lt;&lt;200.0,360.0&gt;--&lt;200.0,361.0&gt;&gt; -&gt; L&lt;&lt;200.0,361.0&gt;--&lt;202.0,391.0&gt;&gt;

* u12194 (U+12194): L&lt;&lt;1005.0,936.0&gt;--&lt;1008.0,924.0&gt;&gt; -&gt; L&lt;&lt;1008.0,924.0&gt;--&lt;1011.0,915.0&gt;&gt;

* u12194 (U+12194): L&lt;&lt;1179.0,107.0&gt;--&lt;1149.0,149.0&gt;&gt; -&gt; L&lt;&lt;1149.0,149.0&gt;--&lt;1116.0,194.0&gt;&gt;

* u12194 (U+12194): L&lt;&lt;334.0,-118.0&gt;--&lt;331.0,-74.0&gt;&gt; -&gt; L&lt;&lt;331.0,-74.0&gt;--&lt;331.0,-66.0&gt;&gt;

* u12194 (U+12194): L&lt;&lt;978.0,105.0&gt;--&lt;1005.0,63.0&gt;&gt; -&gt; L&lt;&lt;1005.0,63.0&gt;--&lt;1032.0,24.0&gt;&gt;

* u1220B (U+1220B): L&lt;&lt;1190.0,431.0&gt;--&lt;1187.0,413.0&gt;&gt; -&gt; L&lt;&lt;1187.0,413.0&gt;--&lt;1185.0,393.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* u12009 (U+12009): B&lt;&lt;1105.5,92.5&gt;-&lt;1100.0,203.0&gt;-&lt;1090.0,300.0&gt;&gt;/B&lt;&lt;1090.0,300.0&gt;-&lt;1088.0,276.0&gt;-&lt;1087.0,251.0&gt;&gt; = 10.649629523754403

* u12009 (U+12009): B&lt;&lt;488.5,232.0&gt;-&lt;487.0,249.0&gt;-&lt;485.0,267.0&gt;&gt;/B&lt;&lt;485.0,267.0&gt;-&lt;474.0,131.0&gt;-&lt;468.0,6.0&gt;&gt; = 10.964343074338954

* u12017 (U+12017): B&lt;&lt;1064.0,52.5&gt;-&lt;1090.0,67.0&gt;-&lt;1122.0,89.0&gt;&gt;/B&lt;&lt;1122.0,89.0&gt;-&lt;991.0,30.0&gt;-&lt;880.5,-24.5&gt;&gt; = 10.26259430646775

* u12017 (U+12017): B&lt;&lt;887.5,670.5&gt;-&lt;996.0,618.0&gt;-&lt;1124.0,560.0&gt;&gt;/B&lt;&lt;1124.0,560.0&gt;-&lt;1090.0,583.0&gt;-&lt;1062.5,598.0&gt;&gt; = 9.700726663455956

* u12017 (U+12017): B&lt;&lt;984.5,515.0&gt;-&lt;1015.0,511.0&gt;-&lt;1046.0,507.0&gt;&gt;/B&lt;&lt;1046.0,507.0&gt;-&lt;867.0,562.0&gt;-&lt;726.0,597.0&gt;&gt; = 9.727854211999025

* u12019 (U+12019): B&lt;&lt;1196.5,454.0&gt;-&lt;1211.0,450.0&gt;-&lt;1230.0,446.0&gt;&gt;/B&lt;&lt;1230.0,446.0&gt;-&lt;1217.0,451.0&gt;-&lt;1203.5,455.0&gt;&gt; = 9.148852985793804

* u12019 (U+12019): L&lt;&lt;1087.0,61.0&gt;--&lt;1123.0,89.0&gt;&gt;/L&lt;&lt;1123.0,89.0&gt;--&lt;1064.0,62.0&gt;&gt; = 13.284866484902132

* u1201D (U+1201D): B&lt;&lt;1254.5,403.0&gt;-&lt;1253.0,425.0&gt;-&lt;1251.0,447.0&gt;&gt;/B&lt;&lt;1251.0,447.0&gt;-&lt;1241.0,349.0&gt;-&lt;1233.0,214.0&gt;&gt; = 11.020770937290555

* u1201F (U+1201F): L&lt;&lt;617.0,413.0&gt;--&lt;627.0,413.0&gt;&gt;/B&lt;&lt;627.0,413.0&gt;-&lt;605.0,418.0&gt;-&lt;587.5,420.0&gt;&gt; = 12.80426606528674

* u12021 (U+12021): B&lt;&lt;958.0,213.0&gt;-&lt;925.0,196.0&gt;-&lt;908.0,185.0&gt;&gt;/L&lt;&lt;908.0,185.0&gt;--&lt;1033.0,234.0&gt;&gt; = 11.500063492869367

* u12022 (U+12022): B&lt;&lt;589.0,266.5&gt;-&lt;585.0,318.0&gt;-&lt;580.0,357.0&gt;&gt;/B&lt;&lt;580.0,357.0&gt;-&lt;573.0,275.0&gt;-&lt;567.0,195.0&gt;&gt; = 12.185033316317504

* u12026 (U+12026): B&lt;&lt;1040.0,413.5&gt;-&lt;1067.0,409.0&gt;-&lt;1098.0,404.0&gt;&gt;/L&lt;&lt;1098.0,404.0&gt;--&lt;982.0,436.0&gt;&gt; = 6.259814273016902

* u12026 (U+12026): L&lt;&lt;1045.0,482.0&gt;--&lt;1100.0,458.0&gt;&gt;/B&lt;&lt;1100.0,458.0&gt;-&lt;1087.0,467.0&gt;-&lt;1076.5,475.0&gt;&gt; = 11.120447329321324

* u12027 (U+12027): L&lt;&lt;1072.0,197.0&gt;--&lt;1095.0,215.0&gt;&gt;/L&lt;&lt;1095.0,215.0&gt;--&lt;1076.0,206.0&gt;&gt; = 12.70086658987938

* u12028 (U+12028): B&lt;&lt;1331.5,135.5&gt;-&lt;1324.0,241.0&gt;-&lt;1316.0,322.0&gt;&gt;/B&lt;&lt;1316.0,322.0&gt;-&lt;1312.0,273.0&gt;-&lt;1307.5,222.5&gt;&gt; = 10.307407803595808

* u12033 (U+12033): B&lt;&lt;718.5,245.5&gt;-&lt;717.0,262.0&gt;-&lt;715.0,281.0&gt;&gt;/B&lt;&lt;715.0,281.0&gt;-&lt;711.0,214.0&gt;-&lt;708.0,141.0&gt;&gt; = 9.425594149265816

* u12043 (U+12043): B&lt;&lt;231.5,211.0&gt;-&lt;231.0,214.0&gt;-&lt;231.0,218.0&gt;&gt;/B&lt;&lt;231.0,218.0&gt;-&lt;221.0,106.0&gt;-&lt;213.5,-33.5&gt;&gt; = 5.102165252358147

* u12043 (U+12043): B&lt;&lt;236.0,247.0&gt;-&lt;236.0,262.0&gt;-&lt;236.0,277.0&gt;&gt;/B&lt;&lt;236.0,277.0&gt;-&lt;235.0,264.0&gt;-&lt;233.5,249.0&gt;&gt; = 4.398705354995508

* u12045 (U+12045): B&lt;&lt;955.5,508.0&gt;-&lt;957.0,528.0&gt;-&lt;955.0,549.0&gt;&gt;/B&lt;&lt;955.0,549.0&gt;-&lt;949.0,474.0&gt;-&lt;944.5,400.5&gt;&gt; = 10.014253290906368

* u12045 (U+12045): B&lt;&lt;956.5,-113.5&gt;-&lt;958.0,-92.0&gt;-&lt;955.0,-70.0&gt;&gt;/B&lt;&lt;955.0,-70.0&gt;-&lt;948.0,-164.0&gt;-&lt;942.5,-254.5&gt;&gt; = 12.02401214059564

* u1204F (U+1204F): B&lt;&lt;1317.5,307.0&gt;-&lt;1251.0,302.0&gt;-&lt;1202.0,297.0&gt;&gt;/B&lt;&lt;1202.0,297.0&gt;-&lt;1252.0,292.0&gt;-&lt;1318.5,287.5&gt;&gt; = 11.53693516705541

* u1204F (U+1204F): B&lt;&lt;1399.0,430.5&gt;-&lt;1299.0,423.0&gt;-&lt;1223.0,414.0&gt;&gt;/B&lt;&lt;1223.0,414.0&gt;-&lt;1296.0,407.0&gt;-&lt;1398.5,401.5&gt;&gt; = 12.230942764359844

* u12055 (U+12055): B&lt;&lt;484.5,245.5&gt;-&lt;483.0,262.0&gt;-&lt;481.0,281.0&gt;&gt;/B&lt;&lt;481.0,281.0&gt;-&lt;477.0,214.0&gt;-&lt;474.0,141.0&gt;&gt; = 9.425594149265816

* u12057 (U+12057): B&lt;&lt;1459.5,28.5&gt;-&lt;1587.0,50.0&gt;-&lt;1748.0,84.0&gt;&gt;/L&lt;&lt;1748.0,84.0&gt;--&lt;1733.0,84.0&gt;&gt; = 11.92452393761189

* u12057 (U+12057): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12057 (U+12057): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12057 (U+12057): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12057 (U+12057): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12058 (U+12058): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12058 (U+12058): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12058 (U+12058): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12058 (U+12058): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12059 (U+12059): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12059 (U+12059): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12059 (U+12059): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12059 (U+12059): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1205A (U+1205A): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u1205A (U+1205A): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u1205A (U+1205A): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u1205A (U+1205A): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1205B (U+1205B): B&lt;&lt;1332.5,262.0&gt;-&lt;1300.0,260.0&gt;-&lt;1281.0,258.0&gt;&gt;/B&lt;&lt;1281.0,258.0&gt;-&lt;1300.0,256.0&gt;-&lt;1333.0,253.5&gt;&gt; = 12.018011914988996

* u1205B (U+1205B): B&lt;&lt;1345.5,363.0&gt;-&lt;1304.0,360.0&gt;-&lt;1281.0,358.0&gt;&gt;/B&lt;&lt;1281.0,358.0&gt;-&lt;1304.0,355.0&gt;-&lt;1346.5,352.5&gt;&gt; = 12.401148699282784

* u1205B (U+1205B): B&lt;&lt;1347.0,313.0&gt;-&lt;1304.0,310.0&gt;-&lt;1281.0,308.0&gt;&gt;/B&lt;&lt;1281.0,308.0&gt;-&lt;1300.0,306.0&gt;-&lt;1332.0,303.5&gt;&gt; = 10.978746685604765

* u1205B (U+1205B): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u1205B (U+1205B): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u1205B (U+1205B): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u1205B (U+1205B): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1205B (U+1205B): L&lt;&lt;1265.0,384.0&gt;--&lt;1265.0,394.0&gt;&gt;/B&lt;&lt;1265.0,394.0&gt;-&lt;1259.0,363.0&gt;-&lt;1254.5,315.5&gt;&gt; = 10.954062643398332

* u1205C (U+1205C): B&lt;&lt;1289.5,313.0&gt;-&lt;1251.0,310.0&gt;-&lt;1230.0,308.0&gt;&gt;/B&lt;&lt;1230.0,308.0&gt;-&lt;1251.0,305.0&gt;-&lt;1290.5,302.5&gt;&gt; = 13.570434385161475

* u1205C (U+1205C): B&lt;&lt;1290.5,263.0&gt;-&lt;1251.0,260.0&gt;-&lt;1230.0,258.0&gt;&gt;/B&lt;&lt;1230.0,258.0&gt;-&lt;1251.0,255.0&gt;-&lt;1291.5,252.5&gt;&gt; = 13.570434385161475

* u1205C (U+1205C): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u1205C (U+1205C): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u1205C (U+1205C): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u1205C (U+1205C): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1205C (U+1205C): L&lt;&lt;1215.0,384.0&gt;--&lt;1215.0,394.0&gt;&gt;/B&lt;&lt;1215.0,394.0&gt;-&lt;1209.0,363.0&gt;-&lt;1204.5,315.5&gt;&gt; = 10.954062643398332

* u1205D (U+1205D): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u1205D (U+1205D): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u1205D (U+1205D): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u1205D (U+1205D): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1205E (U+1205E): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u1205E (U+1205E): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u1205E (U+1205E): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u1205E (U+1205E): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1205F (U+1205F): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u1205F (U+1205F): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u1205F (U+1205F): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u1205F (U+1205F): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12060 (U+12060): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12060 (U+12060): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12060 (U+12060): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12060 (U+12060): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12061 (U+12061): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12061 (U+12061): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12061 (U+12061): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12061 (U+12061): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12062 (U+12062): B&lt;&lt;1768.5,88.0&gt;-&lt;1856.0,107.0&gt;-&lt;1950.0,129.0&gt;&gt;/B&lt;&lt;1950.0,129.0&gt;-&lt;1896.0,122.0&gt;-&lt;1850.0,114.0&gt;&gt; = 5.786510272059523

* u12062 (U+12062): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12062 (U+12062): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12062 (U+12062): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12062 (U+12062): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12063 (U+12063): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12063 (U+12063): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12063 (U+12063): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12063 (U+12063): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12064 (U+12064): B&lt;&lt;1453.5,27.0&gt;-&lt;1577.0,47.0&gt;-&lt;1734.0,81.0&gt;&gt;/B&lt;&lt;1734.0,81.0&gt;-&lt;1682.0,77.0&gt;-&lt;1633.5,70.0&gt;&gt; = 7.820607568223794

* u12064 (U+12064): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12064 (U+12064): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12064 (U+12064): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12064 (U+12064): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12065 (U+12065): B&lt;&lt;1734.5,81.0&gt;-&lt;1892.0,115.0&gt;-&lt;2075.0,159.0&gt;&gt;/B&lt;&lt;2075.0,159.0&gt;-&lt;2032.0,153.0&gt;-&lt;1979.5,146.0&gt;&gt; = 5.575942303538924

* u12065 (U+12065): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12065 (U+12065): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12065 (U+12065): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12065 (U+12065): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12066 (U+12066): B&lt;&lt;1647.0,312.0&gt;-&lt;1647.0,336.0&gt;-&lt;1644.0,361.0&gt;&gt;/B&lt;&lt;1644.0,361.0&gt;-&lt;1639.0,310.0&gt;-&lt;1633.5,257.5&gt;&gt; = 12.44211274915147

* u12066 (U+12066): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12066 (U+12066): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12066 (U+12066): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12066 (U+12066): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12067 (U+12067): B&lt;&lt;1488.0,388.5&gt;-&lt;1514.0,371.0&gt;-&lt;1534.0,357.0&gt;&gt;/B&lt;&lt;1534.0,357.0&gt;-&lt;1532.0,359.0&gt;-&lt;1532.0,361.0&gt;&gt; = 10.007979801441312

* u12067 (U+12067): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12067 (U+12067): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12067 (U+12067): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12067 (U+12067): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12068 (U+12068): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12068 (U+12068): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12068 (U+12068): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12068 (U+12068): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12069 (U+12069): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12069 (U+12069): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12069 (U+12069): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12069 (U+12069): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1206A (U+1206A): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u1206A (U+1206A): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u1206A (U+1206A): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u1206A (U+1206A): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1206B (U+1206B): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u1206B (U+1206B): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u1206B (U+1206B): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u1206B (U+1206B): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1206C (U+1206C): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u1206C (U+1206C): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u1206C (U+1206C): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u1206C (U+1206C): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1206D (U+1206D): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u1206D (U+1206D): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u1206D (U+1206D): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u1206D (U+1206D): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u12071 (U+12071): B&lt;&lt;338.0,545.0&gt;-&lt;293.0,540.0&gt;-&lt;253.0,534.0&gt;&gt;/B&lt;&lt;253.0,534.0&gt;-&lt;284.0,533.0&gt;-&lt;316.0,536.0&gt;&gt; = 10.378375875942721

* u12071 (U+12071): B&lt;&lt;752.5,574.5&gt;-&lt;653.0,570.0&gt;-&lt;566.0,565.0&gt;&gt;/B&lt;&lt;566.0,565.0&gt;-&lt;628.0,556.0&gt;-&lt;708.0,549.5&gt;&gt; = 11.548680658370602

* u12072 (U+12072): B&lt;&lt;160.0,272.5&gt;-&lt;187.0,295.0&gt;-&lt;213.0,327.0&gt;&gt;/L&lt;&lt;213.0,327.0&gt;--&lt;205.0,320.0&gt;&gt; = 9.72021594806085

* u12075 (U+12075): L&lt;&lt;1347.0,454.0&gt;--&lt;1357.0,447.0&gt;&gt;/L&lt;&lt;1357.0,447.0&gt;--&lt;1348.0,454.0&gt;&gt; = 2.882963452539461

* u1207F (U+1207F): B&lt;&lt;1152.5,405.5&gt;-&lt;1152.0,413.0&gt;-&lt;1151.0,420.0&gt;&gt;/B&lt;&lt;1151.0,420.0&gt;-&lt;1147.0,362.0&gt;-&lt;1143.5,276.0&gt;&gt; = 12.075288583193501

* u1207F (U+1207F): B&lt;&lt;1372.0,133.5&gt;-&lt;1368.0,223.0&gt;-&lt;1363.0,292.0&gt;&gt;/B&lt;&lt;1363.0,292.0&gt;-&lt;1359.0,228.0&gt;-&lt;1356.0,142.0&gt;&gt; = 7.720958116101659

* u1207F (U+1207F): L&lt;&lt;1296.0,473.0&gt;--&lt;1293.0,488.0&gt;&gt;/B&lt;&lt;1293.0,488.0&gt;-&lt;1293.0,484.0&gt;-&lt;1292.5,480.5&gt;&gt; = 11.309932474020227

* u12094 (U+12094): B&lt;&lt;202.0,454.5&gt;-&lt;191.0,452.0&gt;-&lt;181.0,449.0&gt;&gt;/B&lt;&lt;181.0,449.0&gt;-&lt;190.0,450.0&gt;-&lt;199.0,451.0&gt;&gt; = 10.359052488083714

* u12098 (U+12098): B&lt;&lt;221.0,438.0&gt;-&lt;221.0,437.0&gt;-&lt;220.0,437.0&gt;&gt;/B&lt;&lt;220.0,437.0&gt;-&lt;237.0,433.0&gt;-&lt;251.5,434.0&gt;&gt; = 13.240519915187184

* u12098 (U+12098): B&lt;&lt;286.0,438.0&gt;-&lt;286.0,437.0&gt;-&lt;285.0,437.0&gt;&gt;/B&lt;&lt;285.0,437.0&gt;-&lt;302.0,433.0&gt;-&lt;316.5,434.0&gt;&gt; = 13.240519915187184

* u12098 (U+12098): B&lt;&lt;351.0,438.0&gt;-&lt;351.0,437.0&gt;-&lt;350.0,437.0&gt;&gt;/B&lt;&lt;350.0,437.0&gt;-&lt;367.0,433.0&gt;-&lt;383.5,434.0&gt;&gt; = 13.240519915187184

* u1209B (U+1209B): B&lt;&lt;742.0,177.0&gt;-&lt;761.0,187.0&gt;-&lt;779.0,203.0&gt;&gt;/L&lt;&lt;779.0,203.0&gt;--&lt;742.0,177.0&gt;&gt; = 6.537722549544061

* u1209B (U+1209B): L&lt;&lt;779.0,203.0&gt;--&lt;742.0,177.0&gt;&gt;/B&lt;&lt;742.0,177.0&gt;-&lt;761.0,187.0&gt;-&lt;779.0,203.0&gt;&gt; = 7.337276185966107

* u1209E (U+1209E): B&lt;&lt;675.0,702.5&gt;-&lt;611.0,697.0&gt;-&lt;546.0,690.0&gt;&gt;/B&lt;&lt;546.0,690.0&gt;-&lt;570.0,687.0&gt;-&lt;591.0,687.0&gt;&gt; = 13.271642008548458

* u120A3 (U+120A3): B&lt;&lt;895.0,427.5&gt;-&lt;896.0,437.0&gt;-&lt;897.0,447.0&gt;&gt;/B&lt;&lt;897.0,447.0&gt;-&lt;888.0,421.0&gt;-&lt;881.0,374.5&gt;&gt; = 13.38289886298597

* u120A4 (U+120A4): B&lt;&lt;895.0,427.5&gt;-&lt;896.0,437.0&gt;-&lt;897.0,447.0&gt;&gt;/B&lt;&lt;897.0,447.0&gt;-&lt;888.0,421.0&gt;-&lt;881.0,374.5&gt;&gt; = 13.38289886298597

* u120A8 (U+120A8): B&lt;&lt;813.5,272.0&gt;-&lt;812.0,286.0&gt;-&lt;810.0,302.0&gt;&gt;/B&lt;&lt;810.0,302.0&gt;-&lt;805.0,259.0&gt;-&lt;801.5,212.5&gt;&gt; = 13.75753096404026

* u120AD (U+120AD): B&lt;&lt;969.5,354.5&gt;-&lt;970.0,346.0&gt;-&lt;971.0,338.0&gt;&gt;/B&lt;&lt;971.0,338.0&gt;-&lt;973.0,368.0&gt;-&lt;976.0,393.5&gt;&gt; = 10.939091183192135

* u120AD (U+120AD): L&lt;&lt;567.0,88.0&gt;--&lt;568.0,80.0&gt;&gt;/B&lt;&lt;568.0,80.0&gt;-&lt;568.0,82.0&gt;-&lt;568.0,85.0&gt;&gt; = 7.1250163489018075

* u120AD (U+120AD): L&lt;&lt;849.0,-88.0&gt;--&lt;849.0,-89.0&gt;&gt;/B&lt;&lt;849.0,-89.0&gt;-&lt;853.0,-57.0&gt;-&lt;857.0,-16.0&gt;&gt; = 7.125016348901757

* u120AF (U+120AF): B&lt;&lt;985.5,221.0&gt;-&lt;980.0,294.0&gt;-&lt;972.0,359.0&gt;&gt;/B&lt;&lt;972.0,359.0&gt;-&lt;967.0,312.0&gt;-&lt;963.0,259.5&gt;&gt; = 13.088958151930598

* u120B5 (U+120B5): L&lt;&lt;242.0,291.0&gt;--&lt;245.0,336.0&gt;&gt;/B&lt;&lt;245.0,336.0&gt;-&lt;235.0,280.0&gt;-&lt;227.5,210.5&gt;&gt; = 6.310596821107455

* u120B6 (U+120B6): L&lt;&lt;242.0,292.0&gt;--&lt;245.0,336.0&gt;&gt;/B&lt;&lt;245.0,336.0&gt;-&lt;235.0,280.0&gt;-&lt;227.5,210.5&gt;&gt; = 6.224177913015922

* u120B8 (U+120B8): B&lt;&lt;254.0,513.5&gt;-&lt;216.0,507.0&gt;-&lt;187.0,500.0&gt;&gt;/L&lt;&lt;187.0,500.0&gt;--&lt;198.0,500.0&gt;&gt; = 13.570434385161475

* u120B8 (U+120B8): B&lt;&lt;953.5,566.0&gt;-&lt;842.0,562.0&gt;-&lt;739.0,556.0&gt;&gt;/B&lt;&lt;739.0,556.0&gt;-&lt;752.0,554.0&gt;-&lt;762.5,552.5&gt;&gt; = 12.080012924091777

* u120B8 (U+120B8): L&lt;&lt;212.0,204.0&gt;--&lt;205.0,204.0&gt;&gt;/B&lt;&lt;205.0,204.0&gt;-&lt;222.0,202.0&gt;-&lt;239.5,200.0&gt;&gt; = 6.709836807756896

* u120B9 (U+120B9): B&lt;&lt;766.0,557.0&gt;-&lt;569.0,547.0&gt;-&lt;420.0,533.0&gt;&gt;/B&lt;&lt;420.0,533.0&gt;-&lt;436.0,532.0&gt;-&lt;453.0,533.5&gt;&gt; = 8.944071222153452

* u120BA (U+120BA): B&lt;&lt;809.0,560.0&gt;-&lt;631.0,552.0&gt;-&lt;488.0,540.0&gt;&gt;/B&lt;&lt;488.0,540.0&gt;-&lt;502.0,538.0&gt;-&lt;514.0,536.5&gt;&gt; = 12.926901320991528

* u120BB (U+120BB): B&lt;&lt;412.5,204.5&gt;-&lt;413.0,205.0&gt;-&lt;414.0,205.0&gt;&gt;/B&lt;&lt;414.0,205.0&gt;-&lt;385.0,212.0&gt;-&lt;366.5,215.0&gt;&gt; = 13.570434385161475

* u120BE (U+120BE): B&lt;&lt;517.5,209.0&gt;-&lt;478.0,204.0&gt;-&lt;449.0,199.0&gt;&gt;/B&lt;&lt;449.0,199.0&gt;-&lt;467.0,198.0&gt;-&lt;485.0,196.5&gt;&gt; = 12.96223715167149

* u120C0 (U+120C0): B&lt;&lt;628.0,229.5&gt;-&lt;628.0,239.0&gt;-&lt;627.0,249.0&gt;&gt;/B&lt;&lt;627.0,249.0&gt;-&lt;626.0,237.0&gt;-&lt;625.0,225.0&gt;&gt; = 10.474234828225807

* u120C2 (U+120C2): B&lt;&lt;636.5,252.0&gt;-&lt;636.0,246.0&gt;-&lt;636.0,241.0&gt;&gt;/B&lt;&lt;636.0,241.0&gt;-&lt;637.0,247.0&gt;-&lt;637.5,252.5&gt;&gt; = 9.462322208025613

* u120C2 (U+120C2): B&lt;&lt;637.5,252.5&gt;-&lt;638.0,258.0&gt;-&lt;638.0,264.0&gt;&gt;/B&lt;&lt;638.0,264.0&gt;-&lt;637.0,258.0&gt;-&lt;636.5,252.0&gt;&gt; = 9.462322208025613

* u120C2 (U+120C2): B&lt;&lt;992.0,567.5&gt;-&lt;898.0,564.0&gt;-&lt;809.0,560.0&gt;&gt;/B&lt;&lt;809.0,560.0&gt;-&lt;836.0,555.0&gt;-&lt;874.0,550.0&gt;&gt; = 13.064836475508425

* u120C3 (U+120C3): B&lt;&lt;811.0,351.0&gt;-&lt;811.0,357.0&gt;-&lt;810.0,363.0&gt;&gt;/B&lt;&lt;810.0,363.0&gt;-&lt;806.0,311.0&gt;-&lt;802.5,255.5&gt;&gt; = 13.861027563021121

* u120C3 (U+120C3): B&lt;&lt;872.0,563.0&gt;-&lt;722.0,556.0&gt;-&lt;593.0,547.0&gt;&gt;/B&lt;&lt;593.0,547.0&gt;-&lt;651.0,542.0&gt;-&lt;731.0,537.0&gt;&gt; = 8.918023046078739

* u120C4 (U+120C4): B&lt;&lt;1164.0,330.5&gt;-&lt;1173.0,323.0&gt;-&lt;1182.0,315.0&gt;&gt;/L&lt;&lt;1182.0,315.0&gt;--&lt;1147.0,347.0&gt;&gt; = 0.8026904519649123

* u120C4 (U+120C4): L&lt;&lt;1182.0,315.0&gt;--&lt;1147.0,347.0&gt;&gt;/B&lt;&lt;1147.0,347.0&gt;-&lt;1155.0,338.0&gt;-&lt;1164.0,330.5&gt;&gt; = 5.930230874894854

* u120C6 (U+120C6): B&lt;&lt;753.0,496.0&gt;-&lt;772.0,496.0&gt;-&lt;791.0,499.0&gt;&gt;/L&lt;&lt;791.0,499.0&gt;--&lt;741.0,496.0&gt;&gt; = 5.53899625244578

* u120C6 (U+120C6): B&lt;&lt;906.0,505.0&gt;-&lt;847.0,502.0&gt;-&lt;796.0,499.0&gt;&gt;/B&lt;&lt;796.0,499.0&gt;-&lt;814.0,496.0&gt;-&lt;834.0,496.0&gt;&gt; = 12.828782871455422

* u120C6 (U+120C6): B&lt;&lt;958.0,566.0&gt;-&lt;848.0,562.0&gt;-&lt;747.0,557.0&gt;&gt;/B&lt;&lt;747.0,557.0&gt;-&lt;798.0,554.0&gt;-&lt;862.5,550.5&gt;&gt; = 6.200571679736286

* u120C6 (U+120C6): L&lt;&lt;791.0,499.0&gt;--&lt;741.0,496.0&gt;&gt;/L&lt;&lt;741.0,496.0&gt;--&lt;753.0,496.0&gt;&gt; = 3.4336303624505082

* u120C8 (U+120C8): B&lt;&lt;1145.0,240.0&gt;-&lt;1144.0,252.0&gt;-&lt;1142.0,268.0&gt;&gt;/L&lt;&lt;1142.0,268.0&gt;--&lt;1142.0,264.0&gt;&gt; = 7.125016348901757

* u120C8 (U+120C8): B&lt;&lt;644.0,270.0&gt;-&lt;650.0,297.0&gt;-&lt;647.0,337.0&gt;&gt;/L&lt;&lt;647.0,337.0&gt;--&lt;644.0,270.0&gt;&gt; = 6.852923540284015

* u120C8 (U+120C8): B&lt;&lt;878.5,563.5&gt;-&lt;731.0,557.0&gt;-&lt;604.0,548.0&gt;&gt;/B&lt;&lt;604.0,548.0&gt;-&lt;610.0,547.0&gt;-&lt;616.0,546.5&gt;&gt; = 13.515876439857001

* u120C8 (U+120C8): L&lt;&lt;647.0,337.0&gt;--&lt;644.0,270.0&gt;&gt;/B&lt;&lt;644.0,270.0&gt;-&lt;650.0,297.0&gt;-&lt;647.0,337.0&gt;&gt; = 9.965037497686453

* u120C9 (U+120C9): B&lt;&lt;925.5,565.0&gt;-&lt;896.0,564.0&gt;-&lt;867.0,562.0&gt;&gt;/B&lt;&lt;867.0,562.0&gt;-&lt;888.0,559.0&gt;-&lt;909.0,559.0&gt;&gt; = 12.075288583193501

* u120C9 (U+120C9): B&lt;&lt;947.0,561.0&gt;-&lt;966.0,563.0&gt;-&lt;986.0,567.0&gt;&gt;/B&lt;&lt;986.0,567.0&gt;-&lt;955.0,566.0&gt;-&lt;925.5,565.0&gt;&gt; = 9.462322208025613

* u120CA (U+120CA): B&lt;&lt;1227.5,245.5&gt;-&lt;1225.0,277.0&gt;-&lt;1222.0,307.0&gt;&gt;/B&lt;&lt;1222.0,307.0&gt;-&lt;1220.0,277.0&gt;-&lt;1218.0,241.5&gt;&gt; = 9.52466797179

* u120CE (U+120CE): B&lt;&lt;382.5,200.0&gt;-&lt;395.0,202.0&gt;-&lt;408.0,204.0&gt;&gt;/L&lt;&lt;408.0,204.0&gt;--&lt;357.0,197.0&gt;&gt; = 0.9308687157880478

* u120CE (U+120CE): L&lt;&lt;408.0,204.0&gt;--&lt;357.0,197.0&gt;&gt;/B&lt;&lt;357.0,197.0&gt;-&lt;370.0,198.0&gt;-&lt;382.5,200.0&gt;&gt; = 3.41658819177129

* u120CF (U+120CF): B&lt;&lt;327.0,208.0&gt;-&lt;288.0,203.0&gt;-&lt;258.0,198.0&gt;&gt;/B&lt;&lt;258.0,198.0&gt;-&lt;272.0,197.0&gt;-&lt;286.5,196.5&gt;&gt; = 13.547938988000464

* u120D1 (U+120D1): B&lt;&lt;423.5,533.5&gt;-&lt;342.0,526.0&gt;-&lt;279.0,517.0&gt;&gt;/B&lt;&lt;279.0,517.0&gt;-&lt;289.0,516.0&gt;-&lt;297.5,514.5&gt;&gt; = 13.840695491655614

* u120D3 (U+120D3): L&lt;&lt;1147.0,211.0&gt;--&lt;1142.0,267.0&gt;&gt;/L&lt;&lt;1142.0,267.0&gt;--&lt;1142.0,264.0&gt;&gt; = 5.102165252358147

* u120D4 (U+120D4): B&lt;&lt;282.5,284.5&gt;-&lt;311.0,257.0&gt;-&lt;358.0,219.0&gt;&gt;/B&lt;&lt;358.0,219.0&gt;-&lt;346.0,233.0&gt;-&lt;332.5,244.5&gt;&gt; = 10.442797517236661

* u120D4 (U+120D4): L&lt;&lt;338.0,525.0&gt;--&lt;315.0,506.0&gt;&gt;/B&lt;&lt;315.0,506.0&gt;-&lt;321.0,510.0&gt;-&lt;327.0,515.0&gt;&gt; = 5.869600443014703

* u120D6 (U+120D6): B&lt;&lt;1022.0,384.0&gt;-&lt;1022.0,407.0&gt;-&lt;1019.0,431.0&gt;&gt;/B&lt;&lt;1019.0,431.0&gt;-&lt;1014.0,388.0&gt;-&lt;1009.5,339.0&gt;&gt; = 13.75753096404026

* u120D7 (U+120D7): B&lt;&lt;430.5,534.5&gt;-&lt;405.0,532.0&gt;-&lt;381.0,529.0&gt;&gt;/B&lt;&lt;381.0,529.0&gt;-&lt;396.0,528.0&gt;-&lt;411.0,529.5&gt;&gt; = 10.939091183192135

* u120DA (U+120DA): B&lt;&lt;582.5,200.5&gt;-&lt;563.0,198.0&gt;-&lt;553.0,196.0&gt;&gt;/B&lt;&lt;553.0,196.0&gt;-&lt;571.0,197.0&gt;-&lt;588.5,198.5&gt;&gt; = 8.13010235415596

* u120DA (U+120DA): B&lt;&lt;712.0,468.0&gt;-&lt;736.0,466.0&gt;-&lt;762.0,471.0&gt;&gt;/L&lt;&lt;762.0,471.0&gt;--&lt;712.0,468.0&gt;&gt; = 7.451896692208198

* u120DA (U+120DA): B&lt;&lt;892.5,476.0&gt;-&lt;834.0,474.0&gt;-&lt;775.0,471.0&gt;&gt;/B&lt;&lt;775.0,471.0&gt;-&lt;796.0,468.0&gt;-&lt;816.0,468.0&gt;&gt; = 11.04094018032372

* u120DA (U+120DA): L&lt;&lt;762.0,471.0&gt;--&lt;712.0,468.0&gt;&gt;/B&lt;&lt;712.0,468.0&gt;-&lt;736.0,466.0&gt;-&lt;762.0,471.0&gt;&gt; = 8.197272053176658

* u120DB (U+120DB): B&lt;&lt;540.5,454.0&gt;-&lt;477.0,452.0&gt;-&lt;417.0,449.0&gt;&gt;/B&lt;&lt;417.0,449.0&gt;-&lt;434.0,447.0&gt;-&lt;450.5,446.0&gt;&gt; = 9.572242033868656

* u120DB (U+120DB): L&lt;&lt;415.0,449.0&gt;--&lt;371.0,446.0&gt;&gt;/B&lt;&lt;371.0,446.0&gt;-&lt;382.0,445.0&gt;-&lt;393.0,445.5&gt;&gt; = 9.09492265011669

* u120DD (U+120DD): B&lt;&lt;870.0,563.0&gt;-&lt;719.0,556.0&gt;-&lt;589.0,547.0&gt;&gt;/B&lt;&lt;589.0,547.0&gt;-&lt;613.0,543.0&gt;-&lt;657.5,538.5&gt;&gt; = 13.422634038484004

* u120DE (U+120DE): B&lt;&lt;525.0,276.0&gt;-&lt;532.0,321.0&gt;-&lt;531.0,368.0&gt;&gt;/B&lt;&lt;531.0,368.0&gt;-&lt;527.0,337.0&gt;-&lt;523.5,295.5&gt;&gt; = 8.571254595023658

* u120DE (U+120DE): B&lt;&lt;925.5,565.0&gt;-&lt;896.0,564.0&gt;-&lt;867.0,562.0&gt;&gt;/B&lt;&lt;867.0,562.0&gt;-&lt;888.0,559.0&gt;-&lt;909.0,559.0&gt;&gt; = 12.075288583193501

* u120DE (U+120DE): B&lt;&lt;947.0,561.0&gt;-&lt;966.0,563.0&gt;-&lt;986.0,567.0&gt;&gt;/B&lt;&lt;986.0,567.0&gt;-&lt;955.0,566.0&gt;-&lt;925.5,565.0&gt;&gt; = 9.462322208025613

* u120E4 (U+120E4): B&lt;&lt;916.0,564.5&gt;-&lt;822.0,561.0&gt;-&lt;735.0,556.0&gt;&gt;/B&lt;&lt;735.0,556.0&gt;-&lt;776.0,549.0&gt;-&lt;839.0,542.5&gt;&gt; = 12.978029238858594

* u120E7 (U+120E7): B&lt;&lt;836.5,561.5&gt;-&lt;670.0,554.0&gt;-&lt;532.0,543.0&gt;&gt;/B&lt;&lt;532.0,543.0&gt;-&lt;558.0,540.0&gt;-&lt;602.0,536.5&gt;&gt; = 11.139363674892017

* u1211A (U+1211A): B&lt;&lt;1120.0,367.5&gt;-&lt;1120.0,371.0&gt;-&lt;1120.0,374.0&gt;&gt;/L&lt;&lt;1120.0,374.0&gt;--&lt;1117.0,362.0&gt;&gt; = 14.036243467926484

* u1211C (U+1211C): B&lt;&lt;1091.5,607.0&gt;-&lt;1065.0,575.0&gt;-&lt;1039.0,543.0&gt;&gt;/B&lt;&lt;1039.0,543.0&gt;-&lt;1059.0,560.0&gt;-&lt;1066.0,574.0&gt;&gt; = 10.541604540673166

* u12120 (U+12120): B&lt;&lt;632.0,698.5&gt;-&lt;644.0,697.0&gt;-&lt;656.0,695.0&gt;&gt;/B&lt;&lt;656.0,695.0&gt;-&lt;648.0,698.0&gt;-&lt;640.0,700.0&gt;&gt; = 11.093723011557817

* u12121 (U+12121): B&lt;&lt;476.5,268.0&gt;-&lt;483.0,267.0&gt;-&lt;490.0,266.0&gt;&gt;/B&lt;&lt;490.0,266.0&gt;-&lt;485.0,268.0&gt;-&lt;480.5,269.0&gt;&gt; = 13.671307132195812

* u12121 (U+12121): B&lt;&lt;476.5,759.0&gt;-&lt;483.0,758.0&gt;-&lt;490.0,757.0&gt;&gt;/B&lt;&lt;490.0,757.0&gt;-&lt;485.0,759.0&gt;-&lt;480.5,760.0&gt;&gt; = 13.671307132195812

* u12128 (U+12128): B&lt;&lt;179.5,58.5&gt;-&lt;183.0,87.0&gt;-&lt;182.0,116.0&gt;&gt;/L&lt;&lt;182.0,116.0&gt;--&lt;175.0,52.0&gt;&gt; = 8.216848358297021

* u1212B (U+1212B): L&lt;&lt;496.0,382.0&gt;--&lt;431.0,378.0&gt;&gt;/B&lt;&lt;431.0,378.0&gt;-&lt;448.0,376.0&gt;-&lt;464.5,374.5&gt;&gt; = 10.231290184679123

* u12135 (U+12135): B&lt;&lt;409.5,557.5&gt;-&lt;362.0,499.0&gt;-&lt;321.0,446.0&gt;&gt;/B&lt;&lt;321.0,446.0&gt;-&lt;338.0,460.0&gt;-&lt;360.0,477.0&gt;&gt; = 12.802545109545417

* u12143 (U+12143): B&lt;&lt;1873.5,724.0&gt;-&lt;1881.0,724.0&gt;-&lt;1888.0,725.0&gt;&gt;/B&lt;&lt;1888.0,725.0&gt;-&lt;1885.0,725.0&gt;-&lt;1884.0,726.0&gt;&gt; = 8.13010235415596

* u12145 (U+12145): B&lt;&lt;417.0,696.0&gt;-&lt;419.0,711.0&gt;-&lt;420.0,727.0&gt;&gt;/B&lt;&lt;420.0,727.0&gt;-&lt;404.0,669.0&gt;-&lt;392.0,614.0&gt;&gt; = 11.845826943741303

* u1214D (U+1214D): B&lt;&lt;1518.5,465.5&gt;-&lt;1518.0,474.0&gt;-&lt;1517.0,482.0&gt;&gt;/B&lt;&lt;1517.0,482.0&gt;-&lt;1511.0,434.0&gt;-&lt;1505.5,371.5&gt;&gt; = 14.25003269780357

* u1214D (U+1214D): L&lt;&lt;200.0,361.0&gt;--&lt;202.0,391.0&gt;&gt;/B&lt;&lt;202.0,391.0&gt;-&lt;195.0,352.0&gt;-&lt;189.5,302.5&gt;&gt; = 6.361436008752841

* u1215A (U+1215A): B&lt;&lt;1525.0,229.5&gt;-&lt;1502.0,249.0&gt;-&lt;1481.0,265.0&gt;&gt;/B&lt;&lt;1481.0,265.0&gt;-&lt;1490.0,255.0&gt;-&lt;1499.0,248.0&gt;&gt; = 10.708839226199862

* u1215B (U+1215B): B&lt;&lt;1184.5,499.5&gt;-&lt;1168.0,499.0&gt;-&lt;1152.0,497.0&gt;&gt;/B&lt;&lt;1152.0,497.0&gt;-&lt;1169.0,496.0&gt;-&lt;1186.0,494.5&gt;&gt; = 10.491477012331599

* u1215B (U+1215B): L&lt;&lt;1215.0,557.0&gt;--&lt;1152.0,553.0&gt;&gt;/L&lt;&lt;1152.0,553.0&gt;--&lt;1215.0,548.0&gt;&gt; = 8.170723247394802

* u1215F (U+1215F): B&lt;&lt;1256.0,196.0&gt;-&lt;1268.0,196.0&gt;-&lt;1281.0,199.0&gt;&gt;/L&lt;&lt;1281.0,199.0&gt;--&lt;1105.0,186.0&gt;&gt; = 8.770213574832644

* u1215F (U+1215F): L&lt;&lt;1029.0,178.0&gt;--&lt;999.0,175.0&gt;&gt;/L&lt;&lt;999.0,175.0&gt;--&lt;1030.0,172.0&gt;&gt; = 11.238133289155778

* u12161 (U+12161): B&lt;&lt;1237.0,587.0&gt;-&lt;1225.0,584.0&gt;-&lt;1216.0,581.0&gt;&gt;/L&lt;&lt;1216.0,581.0&gt;--&lt;1223.0,583.0&gt;&gt; = 2.4895529219991284

* u12161 (U+12161): L&lt;&lt;1439.0,558.0&gt;--&lt;1364.0,547.0&gt;&gt;/L&lt;&lt;1364.0,547.0&gt;--&lt;1440.0,543.0&gt;&gt; = 11.356679088216396

* u12161 (U+12161): L&lt;&lt;1442.0,505.0&gt;--&lt;1362.0,500.0&gt;&gt;/B&lt;&lt;1362.0,500.0&gt;-&lt;1383.0,497.0&gt;-&lt;1404.0,494.5&gt;&gt; = 11.706436729153296

* u12162 (U+12162): B&lt;&lt;1202.0,173.5&gt;-&lt;1148.0,170.0&gt;-&lt;1101.0,165.0&gt;&gt;/B&lt;&lt;1101.0,165.0&gt;-&lt;1152.0,161.0&gt;-&lt;1206.5,156.5&gt;&gt; = 10.557062416752332

* u12162 (U+12162): B&lt;&lt;1215.5,490.0&gt;-&lt;1142.0,484.0&gt;-&lt;1075.0,478.0&gt;&gt;/B&lt;&lt;1075.0,478.0&gt;-&lt;1110.0,473.0&gt;-&lt;1159.0,470.0&gt;&gt; = 13.247417204128599

* u12162 (U+12162): L&lt;&lt;973.0,320.0&gt;--&lt;973.0,338.0&gt;&gt;/B&lt;&lt;973.0,338.0&gt;-&lt;968.0,305.0&gt;-&lt;963.5,263.0&gt;&gt; = 8.615648184164108

* u12163 (U+12163): B&lt;&lt;1245.0,568.0&gt;-&lt;1202.0,565.0&gt;-&lt;1167.0,561.0&gt;&gt;/B&lt;&lt;1167.0,561.0&gt;-&lt;1211.0,557.0&gt;-&lt;1256.5,554.0&gt;&gt; = 11.714230659391728

* u12163 (U+12163): B&lt;&lt;1261.5,493.0&gt;-&lt;1215.0,490.0&gt;-&lt;1170.0,486.0&gt;&gt;/B&lt;&lt;1170.0,486.0&gt;-&lt;1208.0,483.0&gt;-&lt;1254.5,480.5&gt;&gt; = 9.593596318015791

* u12167 (U+12167): L&lt;&lt;1570.0,510.0&gt;--&lt;1574.0,495.0&gt;&gt;/L&lt;&lt;1574.0,495.0&gt;--&lt;1572.0,510.0&gt;&gt; = 7.336773809546094

* u1216C (U+1216C): B&lt;&lt;1031.5,192.0&gt;-&lt;983.0,189.0&gt;-&lt;949.0,185.0&gt;&gt;/B&lt;&lt;949.0,185.0&gt;-&lt;1068.0,176.0&gt;-&lt;1238.0,165.0&gt;&gt; = 11.034897242495322

* u1216C (U+1216C): L&lt;&lt;956.0,461.0&gt;--&lt;919.0,458.0&gt;&gt;/B&lt;&lt;919.0,458.0&gt;-&lt;928.0,457.0&gt;-&lt;937.0,458.0&gt;&gt; = 10.975655172812548

* u1216D (U+1216D): B&lt;&lt;1273.5,494.0&gt;-&lt;1191.0,488.0&gt;-&lt;1113.0,481.0&gt;&gt;/B&lt;&lt;1113.0,481.0&gt;-&lt;1129.0,479.0&gt;-&lt;1141.5,477.5&gt;&gt; = 12.253207390754602

* u12170 (U+12170): B&lt;&lt;1375.0,291.0&gt;-&lt;1386.0,283.0&gt;-&lt;1397.0,275.0&gt;&gt;/L&lt;&lt;1397.0,275.0&gt;--&lt;1361.0,309.0&gt;&gt; = 7.336049573279631

* u12171 (U+12171): B&lt;&lt;1143.0,405.0&gt;-&lt;1166.0,403.0&gt;-&lt;1190.0,408.0&gt;&gt;/L&lt;&lt;1190.0,408.0&gt;--&lt;1143.0,405.0&gt;&gt; = 8.116066151714275

* u12171 (U+12171): L&lt;&lt;1145.0,168.0&gt;--&lt;1095.0,165.0&gt;&gt;/B&lt;&lt;1095.0,165.0&gt;-&lt;1108.0,164.0&gt;-&lt;1120.5,163.5&gt;&gt; = 7.8323357174460435

* u12171 (U+12171): L&lt;&lt;1190.0,408.0&gt;--&lt;1143.0,405.0&gt;&gt;/B&lt;&lt;1143.0,405.0&gt;-&lt;1166.0,403.0&gt;-&lt;1190.0,408.0&gt;&gt; = 8.621963508416624

* u12172 (U+12172): B&lt;&lt;1405.5,436.0&gt;-&lt;1437.0,431.0&gt;-&lt;1466.0,427.0&gt;&gt;/B&lt;&lt;1466.0,427.0&gt;-&lt;1454.0,431.0&gt;-&lt;1442.5,434.0&gt;&gt; = 10.58163552094374

* u12173 (U+12173): B&lt;&lt;1325.5,566.5&gt;-&lt;1270.0,562.0&gt;-&lt;1218.0,557.0&gt;&gt;/B&lt;&lt;1218.0,557.0&gt;-&lt;1271.0,553.0&gt;-&lt;1324.5,549.5&gt;&gt; = 9.808352076993023

* u12178 (U+12178): B&lt;&lt;1188.0,487.5&gt;-&lt;1126.0,482.0&gt;-&lt;1069.0,477.0&gt;&gt;/B&lt;&lt;1069.0,477.0&gt;-&lt;1105.0,472.0&gt;-&lt;1152.5,467.5&gt;&gt; = 12.920276457994246

* u12178 (U+12178): B&lt;&lt;1461.0,506.0&gt;-&lt;1400.0,503.0&gt;-&lt;1334.0,498.0&gt;&gt;/B&lt;&lt;1334.0,498.0&gt;-&lt;1359.0,494.0&gt;-&lt;1399.0,490.0&gt;&gt; = 13.42259090401081

* u1217C (U+1217C): B&lt;&lt;1273.5,494.0&gt;-&lt;1191.0,488.0&gt;-&lt;1113.0,481.0&gt;&gt;/B&lt;&lt;1113.0,481.0&gt;-&lt;1129.0,479.0&gt;-&lt;1141.5,477.5&gt;&gt; = 12.253207390754602

* u1217D (U+1217D): B&lt;&lt;1215.0,203.0&gt;-&lt;1098.0,191.0&gt;-&lt;984.0,176.0&gt;&gt;/B&lt;&lt;984.0,176.0&gt;-&lt;1139.0,161.0&gt;-&lt;1296.0,149.0&gt;&gt; = 13.023397791386

* u1217E (U+1217E): B&lt;&lt;1078.0,241.5&gt;-&lt;1075.0,279.0&gt;-&lt;1071.0,311.0&gt;&gt;/B&lt;&lt;1071.0,311.0&gt;-&lt;1068.0,276.0&gt;-&lt;1065.5,240.0&gt;&gt; = 12.02410880268957

* u1217E (U+1217E): B&lt;&lt;1130.5,212.0&gt;-&lt;1128.0,236.0&gt;-&lt;1125.0,257.0&gt;&gt;/L&lt;&lt;1125.0,257.0&gt;--&lt;1117.0,163.0&gt;&gt; = 12.994616791916512

* u1217E (U+1217E): B&lt;&lt;1240.5,185.5&gt;-&lt;1241.0,188.0&gt;-&lt;1241.0,190.0&gt;&gt;/L&lt;&lt;1241.0,190.0&gt;--&lt;1235.0,154.0&gt;&gt; = 9.462322208025613

* u1217E (U+1217E): B&lt;&lt;1309.0,496.5&gt;-&lt;1236.0,492.0&gt;-&lt;1164.0,486.0&gt;&gt;/B&lt;&lt;1164.0,486.0&gt;-&lt;1206.0,482.0&gt;-&lt;1260.5,479.0&gt;&gt; = 10.203973721731666

* u1217E (U+1217E): L&lt;&lt;1187.0,256.0&gt;--&lt;1190.0,283.0&gt;&gt;/B&lt;&lt;1190.0,283.0&gt;-&lt;1188.0,275.0&gt;-&lt;1186.5,265.5&gt;&gt; = 7.696051722016556

* u12180 (U+12180): L&lt;&lt;1159.0,311.0&gt;--&lt;1169.0,314.0&gt;&gt;/B&lt;&lt;1169.0,314.0&gt;-&lt;1137.0,311.0&gt;-&lt;1105.0,306.5&gt;&gt; = 11.34341919113838

* u12180 (U+12180): L&lt;&lt;1216.0,577.0&gt;--&lt;1135.0,564.0&gt;&gt;/L&lt;&lt;1135.0,564.0&gt;--&lt;1266.0,554.0&gt;&gt; = 13.483120488823696

* u12180 (U+12180): L&lt;&lt;1268.0,493.0&gt;--&lt;1210.0,489.0&gt;&gt;/L&lt;&lt;1210.0,489.0&gt;--&lt;1268.0,483.0&gt;&gt; = 9.851327342808043

* u12182 (U+12182): B&lt;&lt;1030.0,178.0&gt;-&lt;1016.0,176.0&gt;-&lt;1003.0,174.0&gt;&gt;/L&lt;&lt;1003.0,174.0&gt;--&lt;1058.0,169.0&gt;&gt; = 13.94059117029001

* u12182 (U+12182): B&lt;&lt;1514.5,508.0&gt;-&lt;1484.0,507.0&gt;-&lt;1451.0,505.0&gt;&gt;/B&lt;&lt;1451.0,505.0&gt;-&lt;1472.0,502.0&gt;-&lt;1492.0,502.0&gt;&gt; = 11.598331613073073

* u12183 (U+12183): B&lt;&lt;1311.0,562.5&gt;-&lt;1265.0,560.0&gt;-&lt;1224.0,557.0&gt;&gt;/B&lt;&lt;1224.0,557.0&gt;-&lt;1270.0,553.0&gt;-&lt;1316.0,550.0&gt;&gt; = 9.154656853228708

* u12183 (U+12183): L&lt;&lt;1411.0,503.0&gt;--&lt;1232.0,491.0&gt;&gt;/B&lt;&lt;1232.0,491.0&gt;-&lt;1273.0,487.0&gt;-&lt;1320.0,485.0&gt;&gt; = 9.407516901097024

* u12189 (U+12189): B&lt;&lt;1074.0,460.5&gt;-&lt;1119.0,470.0&gt;-&lt;1175.0,486.0&gt;&gt;/B&lt;&lt;1175.0,486.0&gt;-&lt;1085.0,479.0&gt;-&lt;1006.0,471.0&gt;&gt; = 11.498011050832337

* u1218A (U+1218A): B&lt;&lt;1156.5,485.0&gt;-&lt;1083.0,479.0&gt;-&lt;1019.0,473.0&gt;&gt;/B&lt;&lt;1019.0,473.0&gt;-&lt;1026.0,472.0&gt;-&lt;1032.0,472.0&gt;&gt; = 13.485927397011148

* u1218B (U+1218B): B&lt;&lt;1119.5,585.5&gt;-&lt;1061.0,581.0&gt;-&lt;1010.0,576.0&gt;&gt;/B&lt;&lt;1010.0,576.0&gt;-&lt;1074.0,570.0&gt;-&lt;1148.0,563.5&gt;&gt; = 10.955164379375713

* u1218C (U+1218C): B&lt;&lt;1110.5,481.0&gt;-&lt;1061.0,477.0&gt;-&lt;1017.0,472.0&gt;&gt;/B&lt;&lt;1017.0,472.0&gt;-&lt;1025.0,471.0&gt;-&lt;1034.0,470.5&gt;&gt; = 13.608090041799006

* u1218C (U+1218C): B&lt;&lt;1387.0,294.0&gt;-&lt;1321.0,291.0&gt;-&lt;1251.0,287.0&gt;&gt;/L&lt;&lt;1251.0,287.0&gt;--&lt;1252.0,287.0&gt;&gt; = 3.270487923183572

* u1218E (U+1218E): B&lt;&lt;287.5,511.5&gt;-&lt;319.0,550.0&gt;-&lt;344.0,583.0&gt;&gt;/B&lt;&lt;344.0,583.0&gt;-&lt;306.0,552.0&gt;-&lt;267.5,518.5&gt;&gt; = 13.646109797010354

* u1218E (U+1218E): B&lt;&lt;292.0,596.5&gt;-&lt;322.0,632.0&gt;-&lt;347.0,663.0&gt;&gt;/B&lt;&lt;347.0,663.0&gt;-&lt;313.0,634.0&gt;-&lt;277.0,602.5&gt;&gt; = 10.653276074192068

* u1218E (U+1218E): B&lt;&lt;329.0,244.0&gt;-&lt;300.0,211.0&gt;-&lt;278.0,185.0&gt;&gt;/B&lt;&lt;278.0,185.0&gt;-&lt;300.0,202.0&gt;-&lt;338.5,235.0&gt;&gt; = 12.069401224037005

* u1218E (U+1218E): B&lt;&lt;361.5,-6.0&gt;-&lt;326.0,24.0&gt;-&lt;295.0,49.0&gt;&gt;/B&lt;&lt;295.0,49.0&gt;-&lt;324.0,15.0&gt;-&lt;355.5,-21.0&gt;&gt; = 10.653276074192068

* u1218E (U+1218E): B&lt;&lt;397.5,201.5&gt;-&lt;382.0,183.0&gt;-&lt;368.0,167.0&gt;&gt;/B&lt;&lt;368.0,167.0&gt;-&lt;384.0,178.0&gt;-&lt;410.0,199.5&gt;&gt; = 14.305551846621958

* u1218E (U+1218E): B&lt;&lt;401.0,549.0&gt;-&lt;407.0,554.0&gt;-&lt;413.0,559.0&gt;&gt;/L&lt;&lt;413.0,559.0&gt;--&lt;379.0,534.0&gt;&gt; = 3.4787451401449503

* u1218E (U+1218E): B&lt;&lt;447.0,-10.0&gt;-&lt;409.0,22.0&gt;-&lt;376.0,46.0&gt;&gt;/B&lt;&lt;376.0,46.0&gt;-&lt;407.0,9.0&gt;-&lt;440.0,-29.5&gt;&gt; = 14.015077684067291

* u1218E (U+1218E): B&lt;&lt;538.0,632.5&gt;-&lt;508.0,659.0&gt;-&lt;483.0,680.0&gt;&gt;/B&lt;&lt;483.0,680.0&gt;-&lt;497.0,661.0&gt;-&lt;524.0,629.5&gt;&gt; = 13.585388912274428

* u1218E (U+1218E): B&lt;&lt;915.5,256.0&gt;-&lt;926.0,271.0&gt;-&lt;936.0,286.0&gt;&gt;/L&lt;&lt;936.0,286.0&gt;--&lt;930.0,280.0&gt;&gt; = 11.309932474020227

* u1218E (U+1218E): L&lt;&lt;375.0,446.0&gt;--&lt;389.0,456.0&gt;&gt;/L&lt;&lt;389.0,456.0&gt;--&lt;365.0,441.0&gt;&gt; = 3.532294583890835

* u1218E (U+1218E): L&lt;&lt;419.0,92.0&gt;--&lt;401.0,113.0&gt;&gt;/L&lt;&lt;401.0,113.0&gt;--&lt;424.0,82.0&gt;&gt; = 4.0282636664851035

* u1218E (U+1218E): L&lt;&lt;485.0,467.0&gt;--&lt;449.0,498.0&gt;&gt;/B&lt;&lt;449.0,498.0&gt;-&lt;454.0,491.0&gt;-&lt;461.0,481.0&gt;&gt; = 13.730215508316443

* u1218E (U+1218E): L&lt;&lt;513.0,77.0&gt;--&lt;503.0,90.0&gt;&gt;/B&lt;&lt;503.0,90.0&gt;-&lt;527.0,53.0&gt;-&lt;561.0,8.5&gt;&gt; = 4.599188125365316

* u1218E (U+1218E): L&lt;&lt;543.0,521.0&gt;--&lt;466.0,588.0&gt;&gt;/B&lt;&lt;466.0,588.0&gt;-&lt;486.0,560.0&gt;-&lt;531.0,509.0&gt;&gt; = 13.434818148776278

* u12193 (U+12193): B&lt;&lt;1682.0,655.0&gt;-&lt;1706.0,673.0&gt;-&lt;1743.0,704.0&gt;&gt;/B&lt;&lt;1743.0,704.0&gt;-&lt;1714.0,686.0&gt;-&lt;1684.5,667.0&gt;&gt; = 8.13010235415596

* u12194 (U+12194): B&lt;&lt;102.0,-30.0&gt;-&lt;100.0,-30.0&gt;-&lt;100.0,-31.0&gt;&gt;/L&lt;&lt;100.0,-31.0&gt;--&lt;101.0,-24.0&gt;&gt; = 8.13010235415596

* u12197 (U+12197): B&lt;&lt;171.0,-42.0&gt;-&lt;183.0,14.0&gt;-&lt;183.0,79.0&gt;&gt;/L&lt;&lt;183.0,79.0&gt;--&lt;175.0,6.0&gt;&gt; = 6.254032743916452

* u12198 (U+12198): B&lt;&lt;171.0,-42.0&gt;-&lt;183.0,14.0&gt;-&lt;183.0,79.0&gt;&gt;/L&lt;&lt;183.0,79.0&gt;--&lt;175.0,6.0&gt;&gt; = 6.254032743916452

* u12199 (U+12199): B&lt;&lt;141.5,476.0&gt;-&lt;163.0,493.0&gt;-&lt;183.0,513.0&gt;&gt;/L&lt;&lt;183.0,513.0&gt;--&lt;137.0,476.0&gt;&gt; = 6.188615963241613

* u12199 (U+12199): B&lt;&lt;613.0,-317.0&gt;-&lt;585.0,-275.0&gt;-&lt;545.0,-234.0&gt;&gt;/L&lt;&lt;545.0,-234.0&gt;--&lt;582.0,-280.0&gt;&gt; = 5.481296594697316

* u1219D (U+1219D): B&lt;&lt;1134.0,196.0&gt;-&lt;1087.0,188.0&gt;-&lt;1062.0,179.0&gt;&gt;/B&lt;&lt;1062.0,179.0&gt;-&lt;1067.0,180.0&gt;-&lt;1072.0,181.0&gt;&gt; = 8.488943880504696

* u1219D (U+1219D): B&lt;&lt;1134.0,822.0&gt;-&lt;1087.0,814.0&gt;-&lt;1062.0,805.0&gt;&gt;/B&lt;&lt;1062.0,805.0&gt;-&lt;1067.0,806.0&gt;-&lt;1072.0,807.0&gt;&gt; = 8.488943880504696

* u1219E (U+1219E): B&lt;&lt;944.0,196.0&gt;-&lt;897.0,188.0&gt;-&lt;872.0,179.0&gt;&gt;/B&lt;&lt;872.0,179.0&gt;-&lt;877.0,180.0&gt;-&lt;882.0,181.0&gt;&gt; = 8.488943880504696

* u1219E (U+1219E): B&lt;&lt;944.0,822.0&gt;-&lt;897.0,814.0&gt;-&lt;872.0,805.0&gt;&gt;/B&lt;&lt;872.0,805.0&gt;-&lt;877.0,806.0&gt;-&lt;882.0,807.0&gt;&gt; = 8.488943880504696

* u1219F (U+1219F): B&lt;&lt;1215.0,568.0&gt;-&lt;1215.0,594.0&gt;-&lt;1212.0,619.0&gt;&gt;/B&lt;&lt;1212.0,619.0&gt;-&lt;1205.0,543.0&gt;-&lt;1198.5,449.0&gt;&gt; = 12.105168812226038

* u1219F (U+1219F): B&lt;&lt;622.5,266.5&gt;-&lt;617.0,352.0&gt;-&lt;612.0,428.0&gt;&gt;/B&lt;&lt;612.0,428.0&gt;-&lt;605.0,381.0&gt;-&lt;598.5,321.5&gt;&gt; = 12.23517949792054

* u121A0 (U+121A0): B&lt;&lt;160.0,302.5&gt;-&lt;187.0,325.0&gt;-&lt;213.0,357.0&gt;&gt;/L&lt;&lt;213.0,357.0&gt;--&lt;205.0,350.0&gt;&gt; = 9.72021594806085

* u121A1 (U+121A1): B&lt;&lt;160.0,302.5&gt;-&lt;187.0,325.0&gt;-&lt;213.0,357.0&gt;&gt;/L&lt;&lt;213.0,357.0&gt;--&lt;205.0,350.0&gt;&gt; = 9.72021594806085

* u121A1 (U+121A1): B&lt;&lt;656.5,260.0&gt;-&lt;698.0,252.0&gt;-&lt;755.0,246.0&gt;&gt;/L&lt;&lt;755.0,246.0&gt;--&lt;722.0,257.0&gt;&gt; = 12.425942865427485

* u121A2 (U+121A2): B&lt;&lt;160.0,302.5&gt;-&lt;187.0,325.0&gt;-&lt;213.0,357.0&gt;&gt;/L&lt;&lt;213.0,357.0&gt;--&lt;205.0,350.0&gt;&gt; = 9.72021594806085

* u121A3 (U+121A3): B&lt;&lt;160.0,302.5&gt;-&lt;187.0,325.0&gt;-&lt;213.0,357.0&gt;&gt;/L&lt;&lt;213.0,357.0&gt;--&lt;205.0,350.0&gt;&gt; = 9.72021594806085

* u121A4 (U+121A4): B&lt;&lt;427.0,509.0&gt;-&lt;348.0,503.0&gt;-&lt;283.0,498.0&gt;&gt;/B&lt;&lt;283.0,498.0&gt;-&lt;309.0,495.0&gt;-&lt;335.0,495.0&gt;&gt; = 10.980650010173553

* u121A5 (U+121A5): B&lt;&lt;405.0,630.0&gt;-&lt;410.0,657.0&gt;-&lt;411.0,684.0&gt;&gt;/B&lt;&lt;411.0,684.0&gt;-&lt;397.0,632.0&gt;-&lt;386.0,582.5&gt;&gt; = 12.947391762830742

* u121A7 (U+121A7): B&lt;&lt;704.5,619.5&gt;-&lt;725.0,621.0&gt;-&lt;745.0,625.0&gt;&gt;/B&lt;&lt;745.0,625.0&gt;-&lt;744.0,625.0&gt;-&lt;743.5,625.5&gt;&gt; = 11.309932474020195

* u121AC (U+121AC): B&lt;&lt;645.0,178.0&gt;-&lt;626.0,189.0&gt;-&lt;609.0,198.0&gt;&gt;/B&lt;&lt;609.0,198.0&gt;-&lt;617.0,193.0&gt;-&lt;625.5,188.0&gt;&gt; = 4.108112177135753

* u121AC (U+121AC): L&lt;&lt;674.0,242.0&gt;--&lt;657.0,257.0&gt;&gt;/B&lt;&lt;657.0,257.0&gt;-&lt;694.0,223.0&gt;-&lt;746.5,177.0&gt;&gt; = 1.15682515834087

* u121AE (U+121AE): B&lt;&lt;1010.5,454.0&gt;-&lt;1022.0,408.0&gt;-&lt;1032.0,374.0&gt;&gt;/L&lt;&lt;1032.0,374.0&gt;--&lt;1030.0,390.0&gt;&gt; = 9.264523985132932

* u121AE (U+121AE): B&lt;&lt;930.5,835.0&gt;-&lt;932.0,821.0&gt;-&lt;934.0,804.0&gt;&gt;/B&lt;&lt;934.0,804.0&gt;-&lt;937.0,827.0&gt;-&lt;937.0,852.0&gt;&gt; = 14.141244778929407

* u121B5 (U+121B5): B&lt;&lt;243.5,344.0&gt;-&lt;243.0,355.0&gt;-&lt;242.0,366.0&gt;&gt;/B&lt;&lt;242.0,366.0&gt;-&lt;232.0,264.0&gt;-&lt;224.0,160.0&gt;&gt; = 10.793768244255364

* u121B6 (U+121B6): B&lt;&lt;455.0,218.5&gt;-&lt;454.0,244.0&gt;-&lt;452.0,268.0&gt;&gt;/L&lt;&lt;452.0,268.0&gt;--&lt;452.0,264.0&gt;&gt; = 4.763641690726143

* u121BA (U+121BA): B&lt;&lt;289.0,372.0&gt;-&lt;292.0,384.0&gt;-&lt;292.0,397.0&gt;&gt;/B&lt;&lt;292.0,397.0&gt;-&lt;289.0,385.0&gt;-&lt;287.0,368.5&gt;&gt; = 14.036243467926457

* u121BA (U+121BA): B&lt;&lt;395.5,284.0&gt;-&lt;396.0,294.0&gt;-&lt;394.0,306.0&gt;&gt;/B&lt;&lt;394.0,306.0&gt;-&lt;393.0,287.0&gt;-&lt;392.0,267.0&gt;&gt; = 12.475109712208948

* u121C1 (U+121C1): L&lt;&lt;493.0,211.0&gt;--&lt;508.0,214.0&gt;&gt;/L&lt;&lt;508.0,214.0&gt;--&lt;373.0,203.0&gt;&gt; = 6.651678364344551

* u121C2 (U+121C2): L&lt;&lt;656.0,249.0&gt;--&lt;653.0,299.0&gt;&gt;/L&lt;&lt;653.0,299.0&gt;--&lt;653.0,297.0&gt;&gt; = 3.4336303624505082

* u121C4 (U+121C4): B&lt;&lt;261.0,324.5&gt;-&lt;261.0,328.0&gt;-&lt;261.0,332.0&gt;&gt;/B&lt;&lt;261.0,332.0&gt;-&lt;257.0,307.0&gt;-&lt;253.5,273.5&gt;&gt; = 9.090276920822312

* u121CD (U+121CD): B&lt;&lt;849.5,346.5&gt;-&lt;848.0,356.0&gt;-&lt;847.0,365.0&gt;&gt;/B&lt;&lt;847.0,365.0&gt;-&lt;846.0,355.0&gt;-&lt;845.0,345.5&gt;&gt; = 12.050784883409548

* u121CE (U+121CE): B&lt;&lt;770.5,202.5&gt;-&lt;763.0,302.0&gt;-&lt;751.0,399.0&gt;&gt;/B&lt;&lt;751.0,399.0&gt;-&lt;748.0,374.0&gt;-&lt;744.5,333.0&gt;&gt; = 13.8950794204721

* u121CF (U+121CF): B&lt;&lt;651.0,317.0&gt;-&lt;662.0,309.0&gt;-&lt;673.0,301.0&gt;&gt;/B&lt;&lt;673.0,301.0&gt;-&lt;665.0,310.0&gt;-&lt;655.5,318.5&gt;&gt; = 12.33908727832618

* u121D1 (U+121D1): B&lt;&lt;489.0,251.5&gt;-&lt;484.0,254.0&gt;-&lt;480.0,256.0&gt;&gt;/B&lt;&lt;480.0,256.0&gt;-&lt;484.0,253.0&gt;-&lt;488.5,250.5&gt;&gt; = 10.304846468766009

* u121D9 (U+121D9): B&lt;&lt;281.0,269.0&gt;-&lt;287.0,298.0&gt;-&lt;285.0,333.0&gt;&gt;/B&lt;&lt;285.0,333.0&gt;-&lt;281.0,303.0&gt;-&lt;278.0,257.0&gt;&gt; = 10.865131291775022

* u121DC (U+121DC): B&lt;&lt;414.5,268.0&gt;-&lt;407.0,252.0&gt;-&lt;397.0,238.0&gt;&gt;/B&lt;&lt;397.0,238.0&gt;-&lt;411.0,250.0&gt;-&lt;429.5,264.0&gt;&gt; = 13.861027563021121

* u121DD (U+121DD): B&lt;&lt;438.0,411.5&gt;-&lt;438.0,434.0&gt;-&lt;436.0,456.0&gt;&gt;/B&lt;&lt;436.0,456.0&gt;-&lt;421.0,302.0&gt;-&lt;415.0,147.0&gt;&gt; = 10.757637728478757

* u121DE (U+121DE): B&lt;&lt;189.0,193.5&gt;-&lt;188.0,207.0&gt;-&lt;186.0,221.0&gt;&gt;/L&lt;&lt;186.0,221.0&gt;--&lt;179.0,95.0&gt;&gt; = 11.309932474020162

* u121DE (U+121DE): B&lt;&lt;773.0,172.0&gt;-&lt;767.0,255.0&gt;-&lt;758.0,339.0&gt;&gt;/B&lt;&lt;758.0,339.0&gt;-&lt;755.0,298.0&gt;-&lt;752.0,255.0&gt;&gt; = 10.300419691403793

* u121E4 (U+121E4): B&lt;&lt;1162.0,333.5&gt;-&lt;1168.0,329.0&gt;-&lt;1174.0,325.0&gt;&gt;/L&lt;&lt;1174.0,325.0&gt;--&lt;1154.0,344.0&gt;&gt; = 9.841131759634326

* u121EB (U+121EB): B&lt;&lt;508.0,539.5&gt;-&lt;515.0,540.0&gt;-&lt;522.0,541.0&gt;&gt;/B&lt;&lt;522.0,541.0&gt;-&lt;520.0,541.0&gt;-&lt;517.5,541.5&gt;&gt; = 8.13010235415596

* u121F1 (U+121F1): B&lt;&lt;149.0,329.5&gt;-&lt;171.0,348.0&gt;-&lt;192.0,375.0&gt;&gt;/L&lt;&lt;192.0,375.0&gt;--&lt;186.0,369.0&gt;&gt; = 7.1250163489018075

* u121F1 (U+121F1): L&lt;&lt;902.0,369.0&gt;--&lt;895.0,375.0&gt;&gt;/B&lt;&lt;895.0,375.0&gt;-&lt;903.0,365.0&gt;-&lt;911.5,356.5&gt;&gt; = 10.738897100905428

* u121F5 (U+121F5): B&lt;&lt;834.0,20.0&gt;-&lt;831.0,137.0&gt;-&lt;825.0,254.0&gt;&gt;/B&lt;&lt;825.0,254.0&gt;-&lt;817.0,194.0&gt;-&lt;822.0,133.0&gt;&gt; = 10.530316815012581

* u12200 (U+12200): B&lt;&lt;1088.0,188.5&gt;-&lt;1181.0,203.0&gt;-&lt;1273.0,218.0&gt;&gt;/B&lt;&lt;1273.0,218.0&gt;-&lt;1140.0,214.0&gt;-&lt;1056.5,206.0&gt;&gt; = 7.537559459548656

* u12201 (U+12201): B&lt;&lt;1073.0,369.0&gt;-&lt;1089.0,366.0&gt;-&lt;1109.0,363.0&gt;&gt;/B&lt;&lt;1109.0,363.0&gt;-&lt;1092.0,369.0&gt;-&lt;1074.0,374.5&gt;&gt; = 10.90926921822806

* u12201 (U+12201): B&lt;&lt;1089.0,188.5&gt;-&lt;1182.0,203.0&gt;-&lt;1275.0,219.0&gt;&gt;/B&lt;&lt;1275.0,219.0&gt;-&lt;1139.0,215.0&gt;-&lt;1056.0,206.5&gt;&gt; = 8.07709045714589

* u12202 (U+12202): L&lt;&lt;1141.0,197.0&gt;--&lt;1138.0,212.0&gt;&gt;/B&lt;&lt;1138.0,212.0&gt;-&lt;1138.0,208.0&gt;-&lt;1138.0,204.0&gt;&gt; = 11.309932474020227

* u12204 (U+12204): B&lt;&lt;596.5,159.5&gt;-&lt;583.0,173.0&gt;-&lt;568.0,184.0&gt;&gt;/L&lt;&lt;568.0,184.0&gt;--&lt;622.0,120.0&gt;&gt; = 13.590162637635853

* u12205 (U+12205): B&lt;&lt;713.0,617.5&gt;-&lt;840.0,549.0&gt;-&lt;1014.0,469.0&gt;&gt;/B&lt;&lt;1014.0,469.0&gt;-&lt;966.0,503.0&gt;-&lt;924.5,528.0&gt;&gt; = 10.619655276155106

* u12205 (U+12205): B&lt;&lt;869.0,427.5&gt;-&lt;890.0,425.0&gt;-&lt;915.0,424.0&gt;&gt;/B&lt;&lt;915.0,424.0&gt;-&lt;763.0,469.0&gt;-&lt;645.5,496.5&gt;&gt; = 14.20091626327537

* u12206 (U+12206): B&lt;&lt;667.5,643.0&gt;-&lt;761.0,591.0&gt;-&lt;888.0,529.0&gt;&gt;/B&lt;&lt;888.0,529.0&gt;-&lt;847.0,558.0&gt;-&lt;811.5,578.5&gt;&gt; = 9.251301204311801

* u12209 (U+12209): B&lt;&lt;1088.0,188.5&gt;-&lt;1181.0,203.0&gt;-&lt;1272.0,218.0&gt;&gt;/B&lt;&lt;1272.0,218.0&gt;-&lt;1186.0,215.0&gt;-&lt;1124.5,210.5&gt;&gt; = 7.362310945436675

* u12209 (U+12209): B&lt;&lt;1131.0,348.0&gt;-&lt;1152.0,344.0&gt;-&lt;1178.0,341.0&gt;&gt;/L&lt;&lt;1178.0,341.0&gt;--&lt;1106.0,364.0&gt;&gt; = 11.133848051198932

* u12209 (U+12209): B&lt;&lt;1366.0,488.0&gt;-&lt;1366.0,507.0&gt;-&lt;1363.0,525.0&gt;&gt;/B&lt;&lt;1363.0,525.0&gt;-&lt;1360.0,480.0&gt;-&lt;1357.0,429.0&gt;&gt; = 13.276397042315942

* u12209 (U+12209): B&lt;&lt;609.5,495.0&gt;-&lt;647.0,490.0&gt;-&lt;693.0,485.0&gt;&gt;/B&lt;&lt;693.0,485.0&gt;-&lt;619.0,503.0&gt;-&lt;556.0,515.0&gt;&gt; = 7.467859230504027

* u1220E (U+1220E): B&lt;&lt;1088.0,188.5&gt;-&lt;1181.0,203.0&gt;-&lt;1272.0,218.0&gt;&gt;/B&lt;&lt;1272.0,218.0&gt;-&lt;1186.0,215.0&gt;-&lt;1124.5,210.5&gt;&gt; = 7.362310945436675

* u1220E (U+1220E): B&lt;&lt;1366.0,488.0&gt;-&lt;1366.0,506.0&gt;-&lt;1363.0,524.0&gt;&gt;/B&lt;&lt;1363.0,524.0&gt;-&lt;1360.0,480.0&gt;-&lt;1357.0,429.0&gt;&gt; = 13.362815950407496

* u1220F (U+1220F): B&lt;&lt;798.0,450.0&gt;-&lt;822.0,446.0&gt;-&lt;851.0,442.0&gt;&gt;/B&lt;&lt;851.0,442.0&gt;-&lt;832.0,448.0&gt;-&lt;813.0,453.5&gt;&gt; = 9.672255071744633

* u1221E (U+1221E): B&lt;&lt;586.0,398.5&gt;-&lt;635.0,361.0&gt;-&lt;674.0,333.0&gt;&gt;/B&lt;&lt;674.0,333.0&gt;-&lt;672.0,335.0&gt;-&lt;672.0,337.0&gt;&gt; = 9.323591778137999

* u1221E (U+1221E): B&lt;&lt;586.0,868.5&gt;-&lt;635.0,831.0&gt;-&lt;674.0,803.0&gt;&gt;/B&lt;&lt;674.0,803.0&gt;-&lt;672.0,805.0&gt;-&lt;672.0,807.0&gt;&gt; = 9.323591778137999

* u1221F (U+1221F): B&lt;&lt;586.0,398.5&gt;-&lt;635.0,361.0&gt;-&lt;674.0,333.0&gt;&gt;/B&lt;&lt;674.0,333.0&gt;-&lt;672.0,335.0&gt;-&lt;672.0,337.0&gt;&gt; = 9.323591778137999

* u1221F (U+1221F): B&lt;&lt;586.0,868.5&gt;-&lt;635.0,831.0&gt;-&lt;674.0,803.0&gt;&gt;/B&lt;&lt;674.0,803.0&gt;-&lt;672.0,805.0&gt;-&lt;672.0,807.0&gt;&gt; = 9.323591778137999

* u12221 (U+12221): B&lt;&lt;758.5,481.0&gt;-&lt;773.0,481.0&gt;-&lt;789.0,483.0&gt;&gt;/B&lt;&lt;789.0,483.0&gt;-&lt;788.0,483.0&gt;-&lt;788.0,485.0&gt;&gt; = 7.125016348901757

* u12229 (U+12229): B&lt;&lt;204.0,419.0&gt;-&lt;207.0,437.0&gt;-&lt;208.0,456.0&gt;&gt;/B&lt;&lt;208.0,456.0&gt;-&lt;189.0,368.0&gt;-&lt;182.5,241.0&gt;&gt; = 9.170869081804081

* u12230 (U+12230): B&lt;&lt;1435.5,333.5&gt;-&lt;1442.0,334.0&gt;-&lt;1449.0,335.0&gt;&gt;/B&lt;&lt;1449.0,335.0&gt;-&lt;1448.0,335.0&gt;-&lt;1448.0,337.0&gt;&gt; = 8.13010235415596

* u12230 (U+12230): B&lt;&lt;1506.0,333.5&gt;-&lt;1512.0,334.0&gt;-&lt;1519.0,335.0&gt;&gt;/B&lt;&lt;1519.0,335.0&gt;-&lt;1518.0,335.0&gt;-&lt;1518.0,337.0&gt;&gt; = 8.13010235415596

* u12230 (U+12230): B&lt;&lt;1576.0,333.5&gt;-&lt;1582.0,334.0&gt;-&lt;1589.0,335.0&gt;&gt;/B&lt;&lt;1589.0,335.0&gt;-&lt;1588.0,335.0&gt;-&lt;1588.0,337.0&gt;&gt; = 8.13010235415596

* u12235 (U+12235): B&lt;&lt;1518.0,499.5&gt;-&lt;1517.0,504.0&gt;-&lt;1517.0,508.0&gt;&gt;/B&lt;&lt;1517.0,508.0&gt;-&lt;1516.0,504.0&gt;-&lt;1515.0,500.0&gt;&gt; = 14.036243467926484

* u12237 (U+12237): B&lt;&lt;1349.5,365.5&gt;-&lt;1359.0,358.0&gt;-&lt;1369.0,352.0&gt;&gt;/B&lt;&lt;1369.0,352.0&gt;-&lt;1361.0,360.0&gt;-&lt;1352.0,367.5&gt;&gt; = 14.036243467926457

* u1223B (U+1223B): B&lt;&lt;1188.0,119.0&gt;-&lt;1202.0,99.0&gt;-&lt;1225.0,85.0&gt;&gt;/L&lt;&lt;1225.0,85.0&gt;--&lt;1185.0,122.0&gt;&gt; = 11.440132524164513

* u1223C (U+1223C): B&lt;&lt;1127.0,90.0&gt;-&lt;1133.0,86.0&gt;-&lt;1139.0,82.0&gt;&gt;/L&lt;&lt;1139.0,82.0&gt;--&lt;1116.0,103.0&gt;&gt; = 8.707370271520388

* u1223E (U+1223E): L&lt;&lt;1076.0,369.0&gt;--&lt;1069.0,375.0&gt;&gt;/B&lt;&lt;1069.0,375.0&gt;-&lt;1111.0,324.0&gt;-&lt;1162.0,296.0&gt;&gt; = 9.926245506651668

* u1223F (U+1223F): L&lt;&lt;1299.0,87.0&gt;--&lt;1298.0,86.0&gt;&gt;/B&lt;&lt;1298.0,86.0&gt;-&lt;1314.0,98.0&gt;-&lt;1334.0,113.5&gt;&gt; = 8.13010235415596

* u12245 (U+12245): L&lt;&lt;254.0,219.0&gt;--&lt;214.0,214.0&gt;&gt;/B&lt;&lt;214.0,214.0&gt;-&lt;224.0,213.0&gt;-&lt;234.5,212.0&gt;&gt; = 12.835609486401424

* u12246 (U+12246): B&lt;&lt;1350.0,2.0&gt;-&lt;1373.0,21.0&gt;-&lt;1401.0,44.0&gt;&gt;/L&lt;&lt;1401.0,44.0&gt;--&lt;1394.0,40.0&gt;&gt; = 9.655779366537146

* u12246 (U+12246): L&lt;&lt;1311.0,269.0&gt;--&lt;1401.0,344.0&gt;&gt;/L&lt;&lt;1401.0,344.0&gt;--&lt;1394.0,340.0&gt;&gt; = 10.060689795322912

* u1224A (U+1224A): B&lt;&lt;1202.0,173.5&gt;-&lt;1242.0,165.0&gt;-&lt;1285.0,157.0&gt;&gt;/B&lt;&lt;1285.0,157.0&gt;-&lt;1238.0,174.0&gt;-&lt;1203.0,180.0&gt;&gt; = 9.345981385227201

* u1224A (U+1224A): B&lt;&lt;1203.0,180.0&gt;-&lt;1168.0,186.0&gt;-&lt;1127.0,192.0&gt;&gt;/B&lt;&lt;1127.0,192.0&gt;-&lt;1162.0,182.0&gt;-&lt;1202.0,173.5&gt;&gt; = 7.619745570496004

* u1224A (U+1224A): B&lt;&lt;1238.0,433.5&gt;-&lt;1273.0,443.0&gt;-&lt;1320.0,462.0&gt;&gt;/B&lt;&lt;1320.0,462.0&gt;-&lt;1227.0,448.0&gt;-&lt;1151.0,429.5&gt;&gt; = 13.450393626754728

* u1224D (U+1224D): B&lt;&lt;1126.5,92.0&gt;-&lt;1080.0,89.0&gt;-&lt;1032.0,84.0&gt;&gt;/B&lt;&lt;1032.0,84.0&gt;-&lt;1049.0,82.0&gt;-&lt;1064.0,81.0&gt;&gt; = 12.6566998617304

* u12260 (U+12260): L&lt;&lt;635.0,217.0&gt;--&lt;635.0,214.0&gt;&gt;/L&lt;&lt;635.0,214.0&gt;--&lt;640.0,247.0&gt;&gt; = 8.615648184164108

* u12260 (U+12260): L&lt;&lt;640.0,292.0&gt;--&lt;635.0,325.0&gt;&gt;/L&lt;&lt;635.0,325.0&gt;--&lt;635.0,322.0&gt;&gt; = 8.615648184164108

* u12266 (U+12266): B&lt;&lt;1649.5,328.5&gt;-&lt;1649.0,337.0&gt;-&lt;1648.0,346.0&gt;&gt;/B&lt;&lt;1648.0,346.0&gt;-&lt;1643.0,302.0&gt;-&lt;1639.0,255.5&gt;&gt; = 12.82326543880712

* u12268 (U+12268): B&lt;&lt;1867.0,120.5&gt;-&lt;1862.0,211.0&gt;-&lt;1854.0,305.0&gt;&gt;/B&lt;&lt;1854.0,305.0&gt;-&lt;1849.0,264.0&gt;-&lt;1844.0,215.0&gt;&gt; = 11.817471905934392

* u1226B (U+1226B): B&lt;&lt;904.5,495.0&gt;-&lt;852.0,531.0&gt;-&lt;803.0,561.0&gt;&gt;/B&lt;&lt;803.0,561.0&gt;-&lt;808.0,557.0&gt;-&lt;813.5,553.0&gt;&gt; = 7.182968904506028

* u1226C (U+1226C): B&lt;&lt;1393.0,214.0&gt;-&lt;1408.0,210.0&gt;-&lt;1424.0,208.0&gt;&gt;/B&lt;&lt;1424.0,208.0&gt;-&lt;1333.0,231.0&gt;-&lt;1263.5,248.0&gt;&gt; = 7.059277899368935

* u1226F (U+1226F): B&lt;&lt;1250.0,504.0&gt;-&lt;1293.0,496.0&gt;-&lt;1354.0,489.0&gt;&gt;/B&lt;&lt;1354.0,489.0&gt;-&lt;1209.0,533.0&gt;-&lt;1094.0,562.5&gt;&gt; = 10.334039382229752

* u1226F (U+1226F): L&lt;&lt;1667.0,95.0&gt;--&lt;1688.0,99.0&gt;&gt;/B&lt;&lt;1688.0,99.0&gt;-&lt;1681.0,98.0&gt;-&lt;1673.5,98.0&gt;&gt; = 2.654195513406582

* u12270 (U+12270): B&lt;&lt;1478.0,544.5&gt;-&lt;1594.0,492.0&gt;-&lt;1718.0,437.0&gt;&gt;/B&lt;&lt;1718.0,437.0&gt;-&lt;1666.0,471.0&gt;-&lt;1619.0,497.0&gt;&gt; = 9.258908739315263

* u12270 (U+12270): L&lt;&lt;1709.0,119.0&gt;--&lt;1713.0,122.0&gt;&gt;/L&lt;&lt;1713.0,122.0&gt;--&lt;1707.0,119.0&gt;&gt; = 10.304846468766009

* u12271 (U+12271): B&lt;&lt;1375.0,592.0&gt;-&lt;1485.0,542.0&gt;-&lt;1611.0,485.0&gt;&gt;/B&lt;&lt;1611.0,485.0&gt;-&lt;1586.0,499.0&gt;-&lt;1561.0,511.5&gt;&gt; = 4.907736399854292

* u12271 (U+12271): B&lt;&lt;1557.5,49.5&gt;-&lt;1581.0,61.0&gt;-&lt;1605.0,74.0&gt;&gt;/B&lt;&lt;1605.0,74.0&gt;-&lt;1501.0,28.0&gt;-&lt;1391.5,-22.0&gt;&gt; = 4.582753433021014

* u12274 (U+12274): B&lt;&lt;1075.5,563.0&gt;-&lt;1093.0,560.0&gt;-&lt;1118.0,556.0&gt;&gt;/B&lt;&lt;1118.0,556.0&gt;-&lt;1054.0,573.0&gt;-&lt;1000.0,584.0&gt;&gt; = 5.785405080816419

* u12274 (U+12274): B&lt;&lt;1510.0,441.0&gt;-&lt;1520.0,436.0&gt;-&lt;1541.0,433.0&gt;&gt;/L&lt;&lt;1541.0,433.0&gt;--&lt;1385.0,481.0&gt;&gt; = 8.972626614896358

* u12277 (U+12277): L&lt;&lt;1314.0,501.0&gt;--&lt;1323.0,499.0&gt;&gt;/L&lt;&lt;1323.0,499.0&gt;--&lt;1315.0,502.0&gt;&gt; = 8.027237510431947

* u12278 (U+12278): B&lt;&lt;1358.0,152.5&gt;-&lt;1361.0,153.0&gt;-&lt;1364.0,154.0&gt;&gt;/B&lt;&lt;1364.0,154.0&gt;-&lt;1315.0,150.0&gt;-&lt;1254.5,147.0&gt;&gt; = 13.768090451482976

* u12279 (U+12279): L&lt;&lt;1352.0,152.0&gt;--&lt;1367.0,155.0&gt;&gt;/B&lt;&lt;1367.0,155.0&gt;-&lt;1318.0,151.0&gt;-&lt;1256.5,147.5&gt;&gt; = 6.643074102581175

* u12282 (U+12282): B&lt;&lt;924.0,34.5&gt;-&lt;930.0,36.0&gt;-&lt;936.0,37.0&gt;&gt;/B&lt;&lt;936.0,37.0&gt;-&lt;899.0,33.0&gt;-&lt;855.0,30.0&gt;&gt; = 3.2921471129960316

* u12284 (U+12284): B&lt;&lt;865.0,252.5&gt;-&lt;831.0,250.0&gt;-&lt;796.0,246.0&gt;&gt;/B&lt;&lt;796.0,246.0&gt;-&lt;819.0,244.0&gt;-&lt;842.0,246.0&gt;&gt; = 11.489542479767234

* u1228A (U+1228A): B&lt;&lt;792.0,293.5&gt;-&lt;790.0,331.0&gt;-&lt;788.0,368.0&gt;&gt;/B&lt;&lt;788.0,368.0&gt;-&lt;784.0,340.0&gt;-&lt;780.0,302.0&gt;&gt; = 11.224160413073102

* u1228B (U+1228B): B&lt;&lt;244.0,-213.0&gt;-&lt;243.0,-231.0&gt;-&lt;242.0,-247.0&gt;&gt;/B&lt;&lt;242.0,-247.0&gt;-&lt;245.0,-227.0&gt;-&lt;246.5,-210.0&gt;&gt; = 4.954431234950769

* u1228B (U+1228B): B&lt;&lt;246.5,-210.0&gt;-&lt;248.0,-193.0&gt;-&lt;246.0,-176.0&gt;&gt;/B&lt;&lt;246.0,-176.0&gt;-&lt;245.0,-195.0&gt;-&lt;244.0,-213.0&gt;&gt; = 9.722624311940221

* u1228B (U+1228B): B&lt;&lt;792.0,296.5&gt;-&lt;790.0,333.0&gt;-&lt;788.0,368.0&gt;&gt;/B&lt;&lt;788.0,368.0&gt;-&lt;784.0,340.0&gt;-&lt;780.5,304.0&gt;&gt; = 11.400590277339543

* u1228C (U+1228C): B&lt;&lt;792.0,295.5&gt;-&lt;790.0,332.0&gt;-&lt;788.0,368.0&gt;&gt;/B&lt;&lt;788.0,368.0&gt;-&lt;784.0,340.0&gt;-&lt;780.5,303.0&gt;&gt; = 11.309932474020162

* u1228D (U+1228D): B&lt;&lt;792.0,295.5&gt;-&lt;790.0,332.0&gt;-&lt;788.0,368.0&gt;&gt;/B&lt;&lt;788.0,368.0&gt;-&lt;784.0,340.0&gt;-&lt;780.5,303.0&gt;&gt; = 11.309932474020162

* u1228E (U+1228E): B&lt;&lt;2212.5,379.5&gt;-&lt;2214.0,349.0&gt;-&lt;2215.0,320.0&gt;&gt;/B&lt;&lt;2215.0,320.0&gt;-&lt;2219.0,343.0&gt;-&lt;2222.0,373.0&gt;&gt; = 11.840740953966337

* u1228E (U+1228E): L&lt;&lt;657.0,310.0&gt;--&lt;651.0,429.0&gt;&gt;/B&lt;&lt;651.0,429.0&gt;-&lt;647.0,407.0&gt;-&lt;644.0,377.0&gt;&gt; = 13.19126501263064

* u12290 (U+12290): B&lt;&lt;1003.0,604.0&gt;-&lt;1001.0,625.0&gt;-&lt;998.0,647.0&gt;&gt;/L&lt;&lt;998.0,647.0&gt;--&lt;998.0,644.0&gt;&gt; = 7.765166018425308

* u12290 (U+12290): L&lt;&lt;998.0,484.0&gt;--&lt;998.0,480.0&gt;&gt;/B&lt;&lt;998.0,480.0&gt;-&lt;1001.0,500.0&gt;-&lt;1003.0,520.5&gt;&gt; = 8.530765609948139

* u12298 (U+12298): B&lt;&lt;1118.5,483.0&gt;-&lt;1040.0,480.0&gt;-&lt;966.0,473.0&gt;&gt;/B&lt;&lt;966.0,473.0&gt;-&lt;1005.0,469.0&gt;-&lt;1057.0,465.5&gt;&gt; = 11.259804945678626

* u12298 (U+12298): B&lt;&lt;967.5,170.5&gt;-&lt;963.0,170.0&gt;-&lt;958.0,169.0&gt;&gt;/B&lt;&lt;958.0,169.0&gt;-&lt;963.0,169.0&gt;-&lt;967.5,168.5&gt;&gt; = 11.309932474020195

* u1229F (U+1229F): B&lt;&lt;963.5,419.5&gt;-&lt;964.0,443.0&gt;-&lt;961.0,466.0&gt;&gt;/B&lt;&lt;961.0,466.0&gt;-&lt;952.0,351.0&gt;-&lt;949.0,234.0&gt;&gt; = 11.906304477418587

* u122A0 (U+122A0): B&lt;&lt;1205.0,485.0&gt;-&lt;1235.0,482.0&gt;-&lt;1264.0,486.0&gt;&gt;/B&lt;&lt;1264.0,486.0&gt;-&lt;1249.0,486.0&gt;-&lt;1234.5,486.0&gt;&gt; = 7.853313301978193

* u122A0 (U+122A0): B&lt;&lt;1234.5,486.0&gt;-&lt;1220.0,486.0&gt;-&lt;1205.0,485.0&gt;&gt;/B&lt;&lt;1205.0,485.0&gt;-&lt;1235.0,482.0&gt;-&lt;1264.0,486.0&gt;&gt; = 9.52466797179

* u122A8 (U+122A8): B&lt;&lt;585.0,349.5&gt;-&lt;576.0,435.0&gt;-&lt;564.0,513.0&gt;&gt;/B&lt;&lt;564.0,513.0&gt;-&lt;560.0,464.0&gt;-&lt;555.5,400.5&gt;&gt; = 13.413020633994215

* u122AB (U+122AB): B&lt;&lt;415.0,597.0&gt;-&lt;331.0,592.0&gt;-&lt;287.0,585.0&gt;&gt;/B&lt;&lt;287.0,585.0&gt;-&lt;298.0,584.0&gt;-&lt;309.5,583.5&gt;&gt; = 14.233911711089915

* u122AB (U+122AB): B&lt;&lt;611.0,297.0&gt;-&lt;611.0,324.0&gt;-&lt;608.0,345.0&gt;&gt;/B&lt;&lt;608.0,345.0&gt;-&lt;604.0,288.0&gt;-&lt;600.0,219.5&gt;&gt; = 12.144278049566983

* u122AB (U+122AB): L&lt;&lt;565.0,56.0&gt;--&lt;559.0,137.0&gt;&gt;/L&lt;&lt;559.0,137.0&gt;--&lt;559.0,127.0&gt;&gt; = 4.236394799058849

* u122AE (U+122AE): B&lt;&lt;160.0,272.5&gt;-&lt;187.0,295.0&gt;-&lt;213.0,327.0&gt;&gt;/L&lt;&lt;213.0,327.0&gt;--&lt;205.0,320.0&gt;&gt; = 9.72021594806085

* u122AF (U+122AF): B&lt;&lt;160.0,272.5&gt;-&lt;187.0,295.0&gt;-&lt;213.0,327.0&gt;&gt;/L&lt;&lt;213.0,327.0&gt;--&lt;205.0,320.0&gt;&gt; = 9.72021594806085

* u122B0 (U+122B0): B&lt;&lt;160.0,272.5&gt;-&lt;187.0,295.0&gt;-&lt;213.0,327.0&gt;&gt;/L&lt;&lt;213.0,327.0&gt;--&lt;205.0,320.0&gt;&gt; = 9.72021594806085

* u122B1 (U+122B1): B&lt;&lt;160.0,272.5&gt;-&lt;187.0,295.0&gt;-&lt;213.0,327.0&gt;&gt;/L&lt;&lt;213.0,327.0&gt;--&lt;205.0,320.0&gt;&gt; = 9.72021594806085

* u122B2 (U+122B2): B&lt;&lt;160.0,272.5&gt;-&lt;187.0,295.0&gt;-&lt;213.0,327.0&gt;&gt;/L&lt;&lt;213.0,327.0&gt;--&lt;205.0,320.0&gt;&gt; = 9.72021594806085

* u122B3 (U+122B3): B&lt;&lt;160.0,272.5&gt;-&lt;187.0,295.0&gt;-&lt;213.0,327.0&gt;&gt;/L&lt;&lt;213.0,327.0&gt;--&lt;205.0,320.0&gt;&gt; = 9.72021594806085

* u122B4 (U+122B4): B&lt;&lt;160.0,272.5&gt;-&lt;187.0,295.0&gt;-&lt;213.0,327.0&gt;&gt;/L&lt;&lt;213.0,327.0&gt;--&lt;205.0,320.0&gt;&gt; = 9.72021594806085

* u122B5 (U+122B5): B&lt;&lt;160.0,272.5&gt;-&lt;187.0,295.0&gt;-&lt;213.0,327.0&gt;&gt;/L&lt;&lt;213.0,327.0&gt;--&lt;205.0,320.0&gt;&gt; = 9.72021594806085

* u122B6 (U+122B6): B&lt;&lt;160.0,272.5&gt;-&lt;187.0,295.0&gt;-&lt;213.0,327.0&gt;&gt;/L&lt;&lt;213.0,327.0&gt;--&lt;205.0,320.0&gt;&gt; = 9.72021594806085

* u122BB (U+122BB): B&lt;&lt;1581.0,278.0&gt;-&lt;1553.0,277.0&gt;-&lt;1523.0,275.0&gt;&gt;/L&lt;&lt;1523.0,275.0&gt;--&lt;1524.0,275.0&gt;&gt; = 3.8140748342903783

* u122BE (U+122BE): B&lt;&lt;455.0,163.0&gt;-&lt;369.0,156.0&gt;-&lt;294.0,148.0&gt;&gt;/B&lt;&lt;294.0,148.0&gt;-&lt;309.0,146.0&gt;-&lt;324.0,144.5&gt;&gt; = 13.683171522786594

* u122BF (U+122BF): B&lt;&lt;475.0,117.5&gt;-&lt;349.0,112.0&gt;-&lt;251.0,98.0&gt;&gt;/B&lt;&lt;251.0,98.0&gt;-&lt;280.0,95.0&gt;-&lt;319.0,101.0&gt;&gt; = 14.036243467926457

* u122BF (U+122BF): B&lt;&lt;475.0,657.5&gt;-&lt;349.0,652.0&gt;-&lt;251.0,638.0&gt;&gt;/B&lt;&lt;251.0,638.0&gt;-&lt;280.0,635.0&gt;-&lt;319.0,641.0&gt;&gt; = 14.036243467926457

* u122C1 (U+122C1): B&lt;&lt;1196.0,329.0&gt;-&lt;1049.0,319.0&gt;-&lt;937.0,300.0&gt;&gt;/B&lt;&lt;937.0,300.0&gt;-&lt;948.0,300.0&gt;-&lt;958.5,301.0&gt;&gt; = 9.62815612848671

* u122C1 (U+122C1): B&lt;&lt;471.0,94.0&gt;-&lt;424.0,89.0&gt;-&lt;387.0,84.0&gt;&gt;/B&lt;&lt;387.0,84.0&gt;-&lt;463.0,76.0&gt;-&lt;554.5,68.5&gt;&gt; = 13.705057679511077

* u122C1 (U+122C1): B&lt;&lt;532.0,592.0&gt;-&lt;454.0,586.0&gt;-&lt;385.0,577.0&gt;&gt;/B&lt;&lt;385.0,577.0&gt;-&lt;428.0,572.0&gt;-&lt;485.0,566.0&gt;&gt; = 14.06392258631096

* u122C3 (U+122C3): B&lt;&lt;540.0,645.0&gt;-&lt;431.0,639.0&gt;-&lt;338.0,631.0&gt;&gt;/B&lt;&lt;338.0,631.0&gt;-&lt;355.0,629.0&gt;-&lt;372.0,627.0&gt;&gt; = 11.626402813766926

* u122C3 (U+122C3): B&lt;&lt;848.0,319.0&gt;-&lt;750.0,316.0&gt;-&lt;649.0,311.0&gt;&gt;/B&lt;&lt;649.0,311.0&gt;-&lt;666.0,309.0&gt;-&lt;683.0,307.5&gt;&gt; = 9.543947824063387

* u122C4 (U+122C4): B&lt;&lt;848.0,319.0&gt;-&lt;750.0,316.0&gt;-&lt;649.0,311.0&gt;&gt;/B&lt;&lt;649.0,311.0&gt;-&lt;666.0,309.0&gt;-&lt;683.0,307.5&gt;&gt; = 9.543947824063387

* u122C5 (U+122C5): B&lt;&lt;848.0,319.0&gt;-&lt;750.0,316.0&gt;-&lt;649.0,311.0&gt;&gt;/B&lt;&lt;649.0,311.0&gt;-&lt;666.0,309.0&gt;-&lt;683.0,307.5&gt;&gt; = 9.543947824063387

* u122C8 (U+122C8): L&lt;&lt;1719.0,545.0&gt;--&lt;1719.0,558.0&gt;&gt;/B&lt;&lt;1719.0,558.0&gt;-&lt;1713.0,514.0&gt;-&lt;1707.5,466.5&gt;&gt; = 7.765166018425308

* u122CA (U+122CA): B&lt;&lt;1260.0,657.5&gt;-&lt;1379.0,567.0&gt;-&lt;1506.0,488.0&gt;&gt;/L&lt;&lt;1506.0,488.0&gt;--&lt;1453.0,537.0&gt;&gt; = 10.87069355949641

* u122CA (U+122CA): B&lt;&lt;1844.0,461.0&gt;-&lt;1901.0,516.0&gt;-&lt;1958.0,577.0&gt;&gt;/B&lt;&lt;1958.0,577.0&gt;-&lt;1894.0,527.0&gt;-&lt;1830.5,475.5&gt;&gt; = 8.942753948409704

* u122CF (U+122CF): B&lt;&lt;1574.0,771.0&gt;-&lt;1590.0,771.0&gt;-&lt;1605.0,774.0&gt;&gt;/L&lt;&lt;1605.0,774.0&gt;--&lt;1596.0,774.0&gt;&gt; = 11.309932474020195

* u122D1 (U+122D1): B&lt;&lt;1604.5,618.5&gt;-&lt;1605.0,641.0&gt;-&lt;1603.0,657.0&gt;&gt;/B&lt;&lt;1603.0,657.0&gt;-&lt;1599.0,608.0&gt;-&lt;1596.5,552.5&gt;&gt; = 11.791874720340756

* u122D3 (U+122D3): L&lt;&lt;811.0,758.0&gt;--&lt;807.0,753.0&gt;&gt;/B&lt;&lt;807.0,753.0&gt;-&lt;817.0,763.0&gt;-&lt;827.0,774.0&gt;&gt; = 6.34019174590985

* u122D4 (U+122D4): L&lt;&lt;715.0,564.0&gt;--&lt;700.0,548.0&gt;&gt;/B&lt;&lt;700.0,548.0&gt;-&lt;708.0,555.0&gt;-&lt;714.0,562.5&gt;&gt; = 5.661685100284876

* u122D5 (U+122D5): B&lt;&lt;1244.0,293.0&gt;-&lt;1258.0,304.0&gt;-&lt;1271.0,318.0&gt;&gt;/L&lt;&lt;1271.0,318.0&gt;--&lt;1265.0,313.0&gt;&gt; = 7.315525304396254

* u122D5 (U+122D5): L&lt;&lt;1527.0,23.0&gt;--&lt;1502.0,46.0&gt;&gt;/B&lt;&lt;1502.0,46.0&gt;-&lt;1520.0,22.0&gt;-&lt;1538.0,6.0&gt;&gt; = 10.516046384544797

* u122D5 (U+122D5): L&lt;&lt;1527.0,609.0&gt;--&lt;1502.0,632.0&gt;&gt;/B&lt;&lt;1502.0,632.0&gt;-&lt;1520.0,608.0&gt;-&lt;1538.0,592.0&gt;&gt; = 10.516046384544797

* u122D5 (U+122D5): L&lt;&lt;568.0,292.0&gt;--&lt;564.0,287.0&gt;&gt;/B&lt;&lt;564.0,287.0&gt;-&lt;566.0,289.0&gt;-&lt;568.0,291.0&gt;&gt; = 6.34019174590985

* u122D5 (U+122D5): L&lt;&lt;568.0,872.0&gt;--&lt;564.0,867.0&gt;&gt;/B&lt;&lt;564.0,867.0&gt;-&lt;577.0,880.0&gt;-&lt;592.0,898.0&gt;&gt; = 6.34019174590985

* u122D8 (U+122D8): B&lt;&lt;435.5,-46.5&gt;-&lt;484.0,-56.0&gt;-&lt;533.0,-62.0&gt;&gt;/L&lt;&lt;533.0,-62.0&gt;--&lt;506.0,-56.0&gt;&gt; = 5.547750302321764

* u122DF (U+122DF): B&lt;&lt;492.5,104.5&gt;-&lt;532.0,74.0&gt;-&lt;564.0,51.0&gt;&gt;/B&lt;&lt;564.0,51.0&gt;-&lt;563.0,52.0&gt;-&lt;563.0,53.0&gt;&gt; = 9.29330859939709

* u122F1 (U+122F1): B&lt;&lt;924.5,-62.5&gt;-&lt;933.0,-62.0&gt;-&lt;943.0,-61.0&gt;&gt;/B&lt;&lt;943.0,-61.0&gt;-&lt;740.0,-61.0&gt;-&lt;580.5,-75.0&gt;&gt; = 5.710593137499633

* u122F8 (U+122F8): L&lt;&lt;1195.0,196.0&gt;--&lt;1193.0,264.0&gt;&gt;/L&lt;&lt;1193.0,264.0&gt;--&lt;1193.0,246.0&gt;&gt; = 1.68468431789628

* u12302 (U+12302): B&lt;&lt;577.5,484.0&gt;-&lt;587.0,466.0&gt;-&lt;597.0,447.0&gt;&gt;/L&lt;&lt;597.0,447.0&gt;--&lt;591.0,468.0&gt;&gt; = 11.813144700137165

* u12316 (U+12316): B&lt;&lt;936.0,175.0&gt;-&lt;933.0,175.0&gt;-&lt;930.0,175.0&gt;&gt;/B&lt;&lt;930.0,175.0&gt;-&lt;935.0,174.0&gt;-&lt;940.0,173.5&gt;&gt; = 11.309932474020195

* u1231E (U+1231E): B&lt;&lt;698.0,257.0&gt;-&lt;695.0,307.0&gt;-&lt;690.0,345.0&gt;&gt;/B&lt;&lt;690.0,345.0&gt;-&lt;685.0,273.0&gt;-&lt;681.5,199.0&gt;&gt; = 11.468353580480475

* u1231F (U+1231F): B&lt;&lt;833.5,235.5&gt;-&lt;834.0,244.0&gt;-&lt;830.0,266.0&gt;&gt;/B&lt;&lt;830.0,266.0&gt;-&lt;829.0,240.0&gt;-&lt;828.0,214.0&gt;&gt; = 12.507444630531845

* u12322 (U+12322): L&lt;&lt;1280.0,206.0&gt;--&lt;1317.0,195.0&gt;&gt;/B&lt;&lt;1317.0,195.0&gt;-&lt;1292.0,206.0&gt;-&lt;1266.0,215.5&gt;&gt; = 7.1924231172300725

* u1232B (U+1232B): L&lt;&lt;719.0,206.0&gt;--&lt;753.0,197.0&gt;&gt;/B&lt;&lt;753.0,197.0&gt;-&lt;728.0,208.0&gt;-&lt;703.0,216.5&gt;&gt; = 8.923014522511027

* u1232D (U+1232D): B&lt;&lt;1533.0,145.5&gt;-&lt;1541.0,140.0&gt;-&lt;1549.0,135.0&gt;&gt;/B&lt;&lt;1549.0,135.0&gt;-&lt;1533.0,150.0&gt;-&lt;1515.5,166.0&gt;&gt; = 11.147006525921897

* u1232E (U+1232E): B&lt;&lt;1234.0,265.5&gt;-&lt;1269.0,277.0&gt;-&lt;1304.0,290.0&gt;&gt;/B&lt;&lt;1304.0,290.0&gt;-&lt;1235.0,280.0&gt;-&lt;1169.0,262.0&gt;&gt; = 12.13011439936783

* u1232E (U+1232E): L&lt;&lt;719.0,206.0&gt;--&lt;753.0,197.0&gt;&gt;/B&lt;&lt;753.0,197.0&gt;-&lt;728.0,208.0&gt;-&lt;703.0,216.5&gt;&gt; = 8.923014522511027

* u12334 (U+12334): B&lt;&lt;163.0,728.0&gt;-&lt;184.0,728.0&gt;-&lt;211.0,734.0&gt;&gt;/B&lt;&lt;211.0,734.0&gt;-&lt;210.0,734.0&gt;-&lt;210.0,736.0&gt;&gt; = 12.528807709151492

* u12334 (U+12334): B&lt;&lt;273.0,728.0&gt;-&lt;293.0,728.0&gt;-&lt;321.0,734.0&gt;&gt;/B&lt;&lt;321.0,734.0&gt;-&lt;320.0,734.0&gt;-&lt;320.0,736.0&gt;&gt; = 12.094757077012089

* u12334 (U+12334): B&lt;&lt;383.0,728.0&gt;-&lt;403.0,728.0&gt;-&lt;431.0,734.0&gt;&gt;/B&lt;&lt;431.0,734.0&gt;-&lt;430.0,734.0&gt;-&lt;430.0,736.0&gt;&gt; = 12.094757077012089

* u12337 (U+12337): B&lt;&lt;1172.0,805.0&gt;-&lt;1158.0,805.0&gt;-&lt;1144.0,804.0&gt;&gt;/B&lt;&lt;1144.0,804.0&gt;-&lt;1158.0,803.0&gt;-&lt;1172.5,803.5&gt;&gt; = 8.171233559949677

* u12337 (U+12337): B&lt;&lt;1172.5,803.5&gt;-&lt;1187.0,804.0&gt;-&lt;1201.0,805.0&gt;&gt;/B&lt;&lt;1201.0,805.0&gt;-&lt;1186.0,805.0&gt;-&lt;1172.0,805.0&gt;&gt; = 4.085616779974798

* u12338 (U+12338): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12338 (U+12338): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12339 (U+12339): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12339 (U+12339): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1233A (U+1233A): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1233A (U+1233A): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1233B (U+1233B): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1233B (U+1233B): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1233C (U+1233C): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1233C (U+1233C): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1233C (U+1233C): B&lt;&lt;750.5,357.0&gt;-&lt;751.0,362.0&gt;-&lt;751.0,367.0&gt;&gt;/B&lt;&lt;751.0,367.0&gt;-&lt;745.0,335.0&gt;-&lt;741.0,293.0&gt;&gt; = 10.61965527615514

* u1233D (U+1233D): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1233D (U+1233D): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1233E (U+1233E): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1233E (U+1233E): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1233F (U+1233F): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1233F (U+1233F): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12340 (U+12340): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12340 (U+12340): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12341 (U+12341): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12341 (U+12341): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12342 (U+12342): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12342 (U+12342): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12343 (U+12343): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12343 (U+12343): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12344 (U+12344): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12344 (U+12344): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12345 (U+12345): B&lt;&lt;1146.0,371.5&gt;-&lt;1158.0,362.0&gt;-&lt;1171.0,354.0&gt;&gt;/L&lt;&lt;1171.0,354.0&gt;--&lt;1130.0,392.0&gt;&gt; = 11.217753639140989

* u12345 (U+12345): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12345 (U+12345): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12346 (U+12346): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12346 (U+12346): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12347 (U+12347): B&lt;&lt;1172.0,805.0&gt;-&lt;1158.0,805.0&gt;-&lt;1144.0,804.0&gt;&gt;/B&lt;&lt;1144.0,804.0&gt;-&lt;1158.0,803.0&gt;-&lt;1172.5,803.5&gt;&gt; = 8.171233559949677

* u12347 (U+12347): B&lt;&lt;1172.5,803.5&gt;-&lt;1187.0,804.0&gt;-&lt;1201.0,805.0&gt;&gt;/B&lt;&lt;1201.0,805.0&gt;-&lt;1186.0,805.0&gt;-&lt;1172.0,805.0&gt;&gt; = 4.085616779974798

* u12348 (U+12348): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12348 (U+12348): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12349 (U+12349): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u12349 (U+12349): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1234A (U+1234A): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1234A (U+1234A): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1234A (U+1234A): L&lt;&lt;704.0,459.0&gt;--&lt;745.0,430.0&gt;&gt;/B&lt;&lt;745.0,430.0&gt;-&lt;743.0,432.0&gt;-&lt;743.0,433.0&gt;&gt; = 9.72757855140155

* u1234B (U+1234B): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1234B (U+1234B): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1234C (U+1234C): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1234C (U+1234C): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1234D (U+1234D): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1234D (U+1234D): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u1234E (U+1234E): B&lt;&lt;1242.5,803.5&gt;-&lt;1257.0,804.0&gt;-&lt;1271.0,805.0&gt;&gt;/B&lt;&lt;1271.0,805.0&gt;-&lt;1257.0,805.0&gt;-&lt;1242.5,805.0&gt;&gt; = 4.085616779974798

* u1234E (U+1234E): B&lt;&lt;1242.5,805.0&gt;-&lt;1228.0,805.0&gt;-&lt;1214.0,804.0&gt;&gt;/B&lt;&lt;1214.0,804.0&gt;-&lt;1228.0,803.0&gt;-&lt;1242.5,803.5&gt;&gt; = 8.171233559949677

* u12353 (U+12353): B&lt;&lt;770.0,479.5&gt;-&lt;709.0,471.0&gt;-&lt;675.0,460.0&gt;&gt;/L&lt;&lt;675.0,460.0&gt;--&lt;682.0,462.0&gt;&gt; = 1.9825238610842706

* u1235C (U+1235C): B&lt;&lt;629.5,-203.0&gt;-&lt;607.0,-176.0&gt;-&lt;575.0,-150.0&gt;&gt;/L&lt;&lt;575.0,-150.0&gt;--&lt;582.0,-158.0&gt;&gt; = 9.72021594806085

* u1235C (U+1235C): L&lt;&lt;582.0,719.0&gt;--&lt;579.0,716.0&gt;&gt;/B&lt;&lt;579.0,716.0&gt;-&lt;637.0,764.0&gt;-&lt;672.0,825.0&gt;&gt; = 5.389311759973421

* u1236B (U+1236B): B&lt;&lt;1153.0,612.5&gt;-&lt;1043.0,606.0&gt;-&lt;948.0,598.0&gt;&gt;/B&lt;&lt;948.0,598.0&gt;-&lt;956.0,597.0&gt;-&lt;964.0,597.0&gt;&gt; = 11.938567242608316

* u1236B (U+1236B): B&lt;&lt;345.0,423.5&gt;-&lt;353.0,424.0&gt;-&lt;360.0,425.0&gt;&gt;/B&lt;&lt;360.0,425.0&gt;-&lt;359.0,425.0&gt;-&lt;359.0,427.0&gt;&gt; = 8.13010235415596

* u1236B (U+1236B): B&lt;&lt;439.5,423.5&gt;-&lt;450.0,424.0&gt;-&lt;460.0,425.0&gt;&gt;/B&lt;&lt;460.0,425.0&gt;-&lt;459.0,425.0&gt;-&lt;459.0,427.0&gt;&gt; = 5.710593137499633

* u1236B (U+1236B): B&lt;&lt;442.5,444.5&gt;-&lt;377.0,435.0&gt;-&lt;329.0,423.0&gt;&gt;/B&lt;&lt;329.0,423.0&gt;-&lt;337.0,423.0&gt;-&lt;345.0,423.5&gt;&gt; = 14.036243467926457

* u1236B (U+1236B): B&lt;&lt;539.5,423.5&gt;-&lt;550.0,424.0&gt;-&lt;560.0,425.0&gt;&gt;/B&lt;&lt;560.0,425.0&gt;-&lt;559.0,425.0&gt;-&lt;559.0,427.0&gt;&gt; = 5.710593137499633

* u1236B (U+1236B): L&lt;&lt;660.0,424.0&gt;--&lt;656.0,454.0&gt;&gt;/B&lt;&lt;656.0,454.0&gt;-&lt;656.0,446.0&gt;-&lt;656.0,438.5&gt;&gt; = 7.594643368591447

* u1236C (U+1236C): B&lt;&lt;1153.0,612.5&gt;-&lt;1043.0,606.0&gt;-&lt;948.0,598.0&gt;&gt;/B&lt;&lt;948.0,598.0&gt;-&lt;956.0,597.0&gt;-&lt;964.0,597.0&gt;&gt; = 11.938567242608316

* u1236C (U+1236C): B&lt;&lt;345.0,423.5&gt;-&lt;353.0,424.0&gt;-&lt;360.0,425.0&gt;&gt;/B&lt;&lt;360.0,425.0&gt;-&lt;359.0,425.0&gt;-&lt;359.0,427.0&gt;&gt; = 8.13010235415596

* u1236C (U+1236C): B&lt;&lt;439.5,423.5&gt;-&lt;450.0,424.0&gt;-&lt;460.0,425.0&gt;&gt;/B&lt;&lt;460.0,425.0&gt;-&lt;459.0,425.0&gt;-&lt;459.0,427.0&gt;&gt; = 5.710593137499633

* u1236C (U+1236C): B&lt;&lt;442.5,444.5&gt;-&lt;377.0,435.0&gt;-&lt;329.0,423.0&gt;&gt;/B&lt;&lt;329.0,423.0&gt;-&lt;337.0,423.0&gt;-&lt;345.0,423.5&gt;&gt; = 14.036243467926457

* u1236C (U+1236C): B&lt;&lt;539.5,423.5&gt;-&lt;550.0,424.0&gt;-&lt;560.0,425.0&gt;&gt;/B&lt;&lt;560.0,425.0&gt;-&lt;559.0,425.0&gt;-&lt;559.0,427.0&gt;&gt; = 5.710593137499633

* u1236C (U+1236C): L&lt;&lt;660.0,425.0&gt;--&lt;656.0,453.0&gt;&gt;/B&lt;&lt;656.0,453.0&gt;-&lt;656.0,445.0&gt;-&lt;656.0,438.0&gt;&gt; = 8.13010235415596

* u12373 (U+12373): B&lt;&lt;210.5,292.5&gt;-&lt;206.0,356.0&gt;-&lt;200.0,409.0&gt;&gt;/B&lt;&lt;200.0,409.0&gt;-&lt;196.0,352.0&gt;-&lt;191.5,290.0&gt;&gt; = 10.472992074129678

* u12373 (U+12373): B&lt;&lt;278.0,246.0&gt;-&lt;273.0,296.0&gt;-&lt;267.0,338.0&gt;&gt;/B&lt;&lt;267.0,338.0&gt;-&lt;261.0,266.0&gt;-&lt;255.5,191.0&gt;&gt; = 12.893744044882132

* u12373 (U+12373): B&lt;&lt;348.0,359.5&gt;-&lt;349.0,367.0&gt;-&lt;349.0,375.0&gt;&gt;/L&lt;&lt;349.0,375.0&gt;--&lt;342.0,332.0&gt;&gt; = 9.24611274556323

* u12373 (U+12373): B&lt;&lt;414.5,256.0&gt;-&lt;415.0,259.0&gt;-&lt;415.0,262.0&gt;&gt;/B&lt;&lt;415.0,262.0&gt;-&lt;405.0,216.0&gt;-&lt;398.0,159.5&gt;&gt; = 12.2647737278924

* u1237E (U+1237E): B&lt;&lt;816.5,586.5&gt;-&lt;816.0,592.0&gt;-&lt;816.0,597.0&gt;&gt;/B&lt;&lt;816.0,597.0&gt;-&lt;792.0,480.0&gt;-&lt;774.5,319.5&gt;&gt; = 11.592175410291073

* u1237F (U+1237F): B&lt;&lt;816.5,586.5&gt;-&lt;816.0,592.0&gt;-&lt;816.0,597.0&gt;&gt;/B&lt;&lt;816.0,597.0&gt;-&lt;792.0,480.0&gt;-&lt;774.5,319.5&gt;&gt; = 11.592175410291073

* u12380 (U+12380): B&lt;&lt;816.5,586.5&gt;-&lt;816.0,592.0&gt;-&lt;816.0,597.0&gt;&gt;/B&lt;&lt;816.0,597.0&gt;-&lt;792.0,480.0&gt;-&lt;774.5,319.5&gt;&gt; = 11.592175410291073

* u12381 (U+12381): B&lt;&lt;816.5,586.5&gt;-&lt;816.0,592.0&gt;-&lt;816.0,597.0&gt;&gt;/B&lt;&lt;816.0,597.0&gt;-&lt;792.0,480.0&gt;-&lt;774.5,319.5&gt;&gt; = 11.592175410291073

* u12382 (U+12382): B&lt;&lt;816.5,586.5&gt;-&lt;816.0,592.0&gt;-&lt;816.0,597.0&gt;&gt;/B&lt;&lt;816.0,597.0&gt;-&lt;792.0,480.0&gt;-&lt;774.5,319.5&gt;&gt; = 11.592175410291073

* u12383 (U+12383): B&lt;&lt;816.5,586.5&gt;-&lt;816.0,592.0&gt;-&lt;816.0,597.0&gt;&gt;/B&lt;&lt;816.0,597.0&gt;-&lt;792.0,480.0&gt;-&lt;774.5,319.5&gt;&gt; = 11.592175410291073

* u12384 (U+12384): B&lt;&lt;816.5,586.5&gt;-&lt;816.0,592.0&gt;-&lt;816.0,597.0&gt;&gt;/B&lt;&lt;816.0,597.0&gt;-&lt;792.0,480.0&gt;-&lt;774.5,319.5&gt;&gt; = 11.592175410291073

* u12385 (U+12385): B&lt;&lt;816.5,586.5&gt;-&lt;816.0,592.0&gt;-&lt;816.0,597.0&gt;&gt;/B&lt;&lt;816.0,597.0&gt;-&lt;792.0,480.0&gt;-&lt;774.5,319.5&gt;&gt; = 11.592175410291073

* u12386 (U+12386): B&lt;&lt;816.5,586.5&gt;-&lt;816.0,592.0&gt;-&lt;816.0,597.0&gt;&gt;/B&lt;&lt;816.0,597.0&gt;-&lt;792.0,480.0&gt;-&lt;774.5,319.5&gt;&gt; = 11.592175410291073

* u12387 (U+12387): B&lt;&lt;816.5,586.5&gt;-&lt;816.0,592.0&gt;-&lt;816.0,597.0&gt;&gt;/B&lt;&lt;816.0,597.0&gt;-&lt;792.0,480.0&gt;-&lt;774.5,319.5&gt;&gt; = 11.592175410291073

* u12387 (U+12387): B&lt;&lt;959.0,422.0&gt;-&lt;959.0,432.0&gt;-&lt;959.0,454.0&gt;&gt;/B&lt;&lt;959.0,454.0&gt;-&lt;951.0,416.0&gt;-&lt;943.5,349.0&gt;&gt; = 11.888658039627968

* u1238A (U+1238A): B&lt;&lt;1088.0,188.5&gt;-&lt;1181.0,203.0&gt;-&lt;1273.0,218.0&gt;&gt;/B&lt;&lt;1273.0,218.0&gt;-&lt;1140.0,214.0&gt;-&lt;1056.5,206.0&gt;&gt; = 7.537559459548656

* u1238B (U+1238B): B&lt;&lt;1148.5,328.0&gt;-&lt;1200.0,321.0&gt;-&lt;1251.0,317.0&gt;&gt;/L&lt;&lt;1251.0,317.0&gt;--&lt;1142.0,353.0&gt;&gt; = 13.792503599675472

* u12484 (U+12484): B&lt;&lt;234.0,218.0&gt;-&lt;237.0,250.0&gt;-&lt;237.0,282.0&gt;&gt;/L&lt;&lt;237.0,282.0&gt;--&lt;231.0,219.0&gt;&gt; = 5.4403320310054815

* u12484 (U+12484): L&lt;&lt;233.0,206.0&gt;--&lt;231.0,218.0&gt;&gt;/B&lt;&lt;231.0,218.0&gt;-&lt;221.0,80.0&gt;-&lt;212.5,-58.0&gt;&gt; = 13.606945949129914

* u12485 (U+12485): B&lt;&lt;234.0,218.0&gt;-&lt;237.0,247.0&gt;-&lt;237.0,279.0&gt;&gt;/L&lt;&lt;237.0,279.0&gt;--&lt;231.0,219.0&gt;&gt; = 5.710593137499633

* u12486 (U+12486): B&lt;&lt;234.0,218.0&gt;-&lt;239.0,250.0&gt;-&lt;237.0,282.0&gt;&gt;/L&lt;&lt;237.0,282.0&gt;--&lt;231.0,219.0&gt;&gt; = 9.016666406002793

* u12486 (U+12486): L&lt;&lt;233.0,206.0&gt;--&lt;231.0,218.0&gt;&gt;/B&lt;&lt;231.0,218.0&gt;-&lt;221.0,80.0&gt;-&lt;212.5,-58.0&gt;&gt; = 13.606945949129914

* u12487 (U+12487): B&lt;&lt;1497.5,81.5&gt;-&lt;1431.0,72.0&gt;-&lt;1377.0,62.0&gt;&gt;/B&lt;&lt;1377.0,62.0&gt;-&lt;1562.0,56.0&gt;-&lt;1811.0,56.0&gt;&gt; = 12.349067382651846

* u12487 (U+12487): B&lt;&lt;1566.5,523.0&gt;-&lt;1454.0,522.0&gt;-&lt;1359.0,519.0&gt;&gt;/B&lt;&lt;1359.0,519.0&gt;-&lt;1412.0,508.0&gt;-&lt;1480.5,498.0&gt;&gt; = 13.533851337657154

* u12488 (U+12488): B&lt;&lt;392.0,567.0&gt;-&lt;329.0,561.0&gt;-&lt;275.0,555.0&gt;&gt;/B&lt;&lt;275.0,555.0&gt;-&lt;304.0,551.0&gt;-&lt;335.5,546.5&gt;&gt; = 14.193505047888126

* u12493 (U+12493): B&lt;&lt;1057.0,373.0&gt;-&lt;1016.0,370.0&gt;-&lt;993.0,368.0&gt;&gt;/B&lt;&lt;993.0,368.0&gt;-&lt;1016.0,365.0&gt;-&lt;1058.5,362.5&gt;&gt; = 12.401148699282784

* u12493 (U+12493): B&lt;&lt;1058.5,323.0&gt;-&lt;1016.0,320.0&gt;-&lt;993.0,318.0&gt;&gt;/B&lt;&lt;993.0,318.0&gt;-&lt;1017.0,315.0&gt;-&lt;1060.5,312.5&gt;&gt; = 12.094757077012089

* u12493 (U+12493): B&lt;&lt;1060.5,273.5&gt;-&lt;1017.0,271.0&gt;-&lt;993.0,268.0&gt;&gt;/B&lt;&lt;993.0,268.0&gt;-&lt;1012.0,266.0&gt;-&lt;1045.5,263.5&gt;&gt; = 13.13402230639627

* u1249C (U+1249C): B&lt;&lt;982.5,294.0&gt;-&lt;982.0,300.0&gt;-&lt;982.0,306.0&gt;&gt;/B&lt;&lt;982.0,306.0&gt;-&lt;976.0,254.0&gt;-&lt;972.0,201.0&gt;&gt; = 6.581944655178027

* u124A3 (U+124A3): B&lt;&lt;937.5,348.0&gt;-&lt;939.0,356.0&gt;-&lt;939.0,364.0&gt;&gt;/B&lt;&lt;939.0,364.0&gt;-&lt;931.0,325.0&gt;-&lt;927.5,269.0&gt;&gt; = 11.592175410291041

* u124AC (U+124AC): L&lt;&lt;765.0,339.0&gt;--&lt;626.0,476.0&gt;&gt;/L&lt;&lt;626.0,476.0&gt;--&lt;764.0,338.0&gt;&gt; = 0.4151795411446551

* u124AD (U+124AD): L&lt;&lt;767.0,696.0&gt;--&lt;767.0,698.0&gt;&gt;/B&lt;&lt;767.0,698.0&gt;-&lt;737.0,578.0&gt;-&lt;713.5,394.5&gt;&gt; = 14.036243467926484

* u124AE (U+124AE): L&lt;&lt;767.0,696.0&gt;--&lt;767.0,698.0&gt;&gt;/B&lt;&lt;767.0,698.0&gt;-&lt;737.0,578.0&gt;-&lt;713.5,394.5&gt;&gt; = 14.036243467926484

* u124AF (U+124AF): L&lt;&lt;767.0,696.0&gt;--&lt;767.0,698.0&gt;&gt;/B&lt;&lt;767.0,698.0&gt;-&lt;737.0,578.0&gt;-&lt;713.5,394.5&gt;&gt; = 14.036243467926484

* u124B0 (U+124B0): L&lt;&lt;767.0,696.0&gt;--&lt;767.0,698.0&gt;&gt;/B&lt;&lt;767.0,698.0&gt;-&lt;737.0,578.0&gt;-&lt;713.5,394.5&gt;&gt; = 14.036243467926484

* u124B1 (U+124B1): L&lt;&lt;767.0,696.0&gt;--&lt;767.0,698.0&gt;&gt;/B&lt;&lt;767.0,698.0&gt;-&lt;737.0,578.0&gt;-&lt;713.5,394.5&gt;&gt; = 14.036243467926484

* u124B2 (U+124B2): L&lt;&lt;767.0,696.0&gt;--&lt;767.0,698.0&gt;&gt;/B&lt;&lt;767.0,698.0&gt;-&lt;737.0,578.0&gt;-&lt;713.5,394.5&gt;&gt; = 14.036243467926484

* u124B3 (U+124B3): B&lt;&lt;823.0,316.5&gt;-&lt;824.0,326.0&gt;-&lt;825.0,336.0&gt;&gt;/B&lt;&lt;825.0,336.0&gt;-&lt;815.0,290.0&gt;-&lt;812.0,223.5&gt;&gt; = 6.554180590392762

* u124B3 (U+124B3): L&lt;&lt;767.0,696.0&gt;--&lt;767.0,698.0&gt;&gt;/B&lt;&lt;767.0,698.0&gt;-&lt;737.0,578.0&gt;-&lt;713.5,394.5&gt;&gt; = 14.036243467926484

* u124B4 (U+124B4): L&lt;&lt;767.0,696.0&gt;--&lt;767.0,698.0&gt;&gt;/B&lt;&lt;767.0,698.0&gt;-&lt;737.0,578.0&gt;-&lt;713.5,394.5&gt;&gt; = 14.036243467926484

* u124B5 (U+124B5): L&lt;&lt;767.0,696.0&gt;--&lt;767.0,698.0&gt;&gt;/B&lt;&lt;767.0,698.0&gt;-&lt;737.0,578.0&gt;-&lt;713.5,394.5&gt;&gt; = 14.036243467926484

* u124B6 (U+124B6): B&lt;&lt;1553.0,487.5&gt;-&lt;1555.0,472.0&gt;-&lt;1558.0,453.0&gt;&gt;/B&lt;&lt;1558.0,453.0&gt;-&lt;1558.0,458.0&gt;-&lt;1558.5,462.5&gt;&gt; = 8.972626614896358

* u124B6 (U+124B6): B&lt;&lt;671.5,313.5&gt;-&lt;672.0,322.0&gt;-&lt;671.0,329.0&gt;&gt;/B&lt;&lt;671.0,329.0&gt;-&lt;669.0,310.0&gt;-&lt;666.5,272.0&gt;&gt; = 14.139108311650475

* u124B6 (U+124B6): L&lt;&lt;1559.0,449.0&gt;--&lt;1565.0,411.0&gt;&gt;/L&lt;&lt;1565.0,411.0&gt;--&lt;1565.0,429.0&gt;&gt; = 8.972626614896399

* u124B6 (U+124B6): L&lt;&lt;1574.0,361.0&gt;--&lt;1583.0,320.0&gt;&gt;/B&lt;&lt;1583.0,320.0&gt;-&lt;1583.0,325.0&gt;-&lt;1583.5,330.0&gt;&gt; = 12.380756928807159

* u124B6 (U+124B6): L&lt;&lt;1583.0,317.0&gt;--&lt;1592.0,275.0&gt;&gt;/B&lt;&lt;1592.0,275.0&gt;-&lt;1592.0,280.0&gt;-&lt;1592.5,285.0&gt;&gt; = 12.094757077012089

* u124BB (U+124BB): B&lt;&lt;737.5,332.5&gt;-&lt;738.0,340.0&gt;-&lt;738.0,347.0&gt;&gt;/B&lt;&lt;738.0,347.0&gt;-&lt;730.0,301.0&gt;-&lt;724.0,240.0&gt;&gt; = 9.865806943084365

* u124BC (U+124BC): B&lt;&lt;1084.5,323.5&gt;-&lt;1100.0,336.0&gt;-&lt;1115.0,354.0&gt;&gt;/L&lt;&lt;1115.0,354.0&gt;--&lt;1110.0,350.0&gt;&gt; = 11.534620653644708

* u124D9 (U+124D9): L&lt;&lt;501.0,352.0&gt;--&lt;501.0,674.0&gt;&gt;/B&lt;&lt;501.0,674.0&gt;-&lt;486.0,611.0&gt;-&lt;471.0,533.0&gt;&gt; = 13.392497753751098

* u124DA (U+124DA): B&lt;&lt;408.0,483.0&gt;-&lt;409.0,497.0&gt;-&lt;409.0,510.0&gt;&gt;/B&lt;&lt;409.0,510.0&gt;-&lt;403.0,478.0&gt;-&lt;397.5,442.5&gt;&gt; = 10.61965527615514

* u124DB (U+124DB): B&lt;&lt;624.5,531.0&gt;-&lt;626.0,574.0&gt;-&lt;624.0,614.0&gt;&gt;/B&lt;&lt;624.0,614.0&gt;-&lt;599.0,484.0&gt;-&lt;581.5,308.0&gt;&gt; = 13.747932280770467

* u124DC (U+124DC): B&lt;&lt;1102.0,707.0&gt;-&lt;1035.0,705.0&gt;-&lt;965.0,703.0&gt;&gt;/B&lt;&lt;965.0,703.0&gt;-&lt;982.0,700.0&gt;-&lt;997.5,699.0&gt;&gt; = 11.644556843058036

* u124DC (U+124DC): B&lt;&lt;944.0,-92.0&gt;-&lt;903.0,-97.0&gt;-&lt;864.0,-105.0&gt;&gt;/B&lt;&lt;864.0,-105.0&gt;-&lt;902.0,-106.0&gt;-&lt;941.0,-108.0&gt;&gt; = 13.099611169065984

* u124E2 (U+124E2): L&lt;&lt;1519.0,697.0&gt;--&lt;1532.0,697.0&gt;&gt;/L&lt;&lt;1532.0,697.0&gt;--&lt;1520.0,700.0&gt;&gt; = 14.036243467926484

* u124E5 (U+124E5): B&lt;&lt;568.0,92.0&gt;-&lt;591.0,58.0&gt;-&lt;643.0,-2.0&gt;&gt;/B&lt;&lt;643.0,-2.0&gt;-&lt;621.0,36.0&gt;-&lt;592.5,78.5&gt;&gt; = 10.845800398162659

* u124E5 (U+124E5): B&lt;&lt;592.5,1027.5&gt;-&lt;621.0,1070.0&gt;-&lt;643.0,1108.0&gt;&gt;/B&lt;&lt;643.0,1108.0&gt;-&lt;591.0,1048.0&gt;-&lt;568.0,1014.0&gt;&gt; = 10.845800398162659

* u124ED (U+124ED): B&lt;&lt;735.0,532.5&gt;-&lt;735.0,539.0&gt;-&lt;734.0,546.0&gt;&gt;/B&lt;&lt;734.0,546.0&gt;-&lt;729.0,458.0&gt;-&lt;724.0,353.5&gt;&gt; = 11.382047954519823

* u124F0 (U+124F0): L&lt;&lt;1082.0,350.0&gt;--&lt;1079.0,353.0&gt;&gt;/B&lt;&lt;1079.0,353.0&gt;-&lt;1105.0,322.0&gt;-&lt;1131.0,300.5&gt;&gt; = 5.013113755035814

* u12505 (U+12505): B&lt;&lt;1248.5,248.0&gt;-&lt;1223.0,262.0&gt;-&lt;1205.0,271.0&gt;&gt;/B&lt;&lt;1205.0,271.0&gt;-&lt;1208.0,269.0&gt;-&lt;1212.0,267.0&gt;&gt; = 7.125016348901757

* u12505 (U+12505): L&lt;&lt;1232.0,288.0&gt;--&lt;1225.0,293.0&gt;&gt;/B&lt;&lt;1225.0,293.0&gt;-&lt;1248.0,274.0&gt;-&lt;1284.5,245.5&gt;&gt; = 4.021990177020057

* u1250F (U+1250F): L&lt;&lt;900.0,283.0&gt;--&lt;902.0,306.0&gt;&gt;/B&lt;&lt;902.0,306.0&gt;-&lt;895.0,267.0&gt;-&lt;890.0,216.0&gt;&gt; = 5.205770114932878

* u12514 (U+12514): B&lt;&lt;1823.5,263.5&gt;-&lt;1841.0,278.0&gt;-&lt;1858.0,299.0&gt;&gt;/L&lt;&lt;1858.0,299.0&gt;--&lt;1853.0,295.0&gt;&gt; = 12.34919770340444

* u1251B (U+1251B): B&lt;&lt;1451.0,548.0&gt;-&lt;1482.0,537.0&gt;-&lt;1513.0,528.0&gt;&gt;/B&lt;&lt;1513.0,528.0&gt;-&lt;1407.0,590.0&gt;-&lt;1315.0,641.0&gt;&gt; = 14.134400605523052

* u12520 (U+12520): L&lt;&lt;828.0,334.0&gt;--&lt;829.0,350.0&gt;&gt;/B&lt;&lt;829.0,350.0&gt;-&lt;824.0,324.0&gt;-&lt;820.5,290.5&gt;&gt; = 7.30919267966134

* u12526 (U+12526): B&lt;&lt;1240.5,482.5&gt;-&lt;1240.0,489.0&gt;-&lt;1239.0,496.0&gt;&gt;/B&lt;&lt;1239.0,496.0&gt;-&lt;1234.0,442.0&gt;-&lt;1230.0,370.0&gt;&gt; = 13.420183559527228

* u12526 (U+12526): B&lt;&lt;920.0,305.0&gt;-&lt;917.0,351.0&gt;-&lt;914.0,393.0&gt;&gt;/B&lt;&lt;914.0,393.0&gt;-&lt;908.0,354.0&gt;-&lt;904.0,302.5&gt;&gt; = 12.831779042530089

* u12526 (U+12526): B&lt;&lt;976.5,549.0&gt;-&lt;976.0,553.0&gt;-&lt;976.0,557.0&gt;&gt;/B&lt;&lt;976.0,557.0&gt;-&lt;973.0,540.0&gt;-&lt;970.5,519.0&gt;&gt; = 10.007979801441312

* u12527 (U+12527): L&lt;&lt;986.0,335.0&gt;--&lt;986.0,523.0&gt;&gt;/B&lt;&lt;986.0,523.0&gt;-&lt;977.0,486.0&gt;-&lt;968.5,440.5&gt;&gt; = 13.67130713219584

* u1252D (U+1252D): B&lt;&lt;585.0,349.5&gt;-&lt;576.0,435.0&gt;-&lt;564.0,513.0&gt;&gt;/B&lt;&lt;564.0,513.0&gt;-&lt;560.0,464.0&gt;-&lt;555.5,400.5&gt;&gt; = 13.413020633994215

* u1253C (U+1253C): B&lt;&lt;703.0,444.0&gt;-&lt;728.0,453.0&gt;-&lt;753.0,463.0&gt;&gt;/L&lt;&lt;753.0,463.0&gt;--&lt;719.0,454.0&gt;&gt; = 6.974929515996119

* u1253D (U+1253D): L&lt;&lt;719.0,206.0&gt;--&lt;753.0,197.0&gt;&gt;/B&lt;&lt;753.0,197.0&gt;-&lt;728.0,208.0&gt;-&lt;703.0,216.5&gt;&gt; = 8.923014522511027

* u1253E (U+1253E): B&lt;&lt;1248.5,-10.5&gt;-&lt;1248.0,3.0&gt;-&lt;1247.0,16.0&gt;&gt;/L&lt;&lt;1247.0,16.0&gt;--&lt;1247.0,13.0&gt;&gt; = 4.398705354995508

* u12543 (U+12543): B&lt;&lt;1153.0,612.5&gt;-&lt;1043.0,606.0&gt;-&lt;948.0,598.0&gt;&gt;/B&lt;&lt;948.0,598.0&gt;-&lt;956.0,597.0&gt;-&lt;964.0,597.0&gt;&gt; = 11.938567242608316

* u12543 (U+12543): B&lt;&lt;442.5,444.5&gt;-&lt;377.0,435.0&gt;-&lt;329.0,423.0&gt;&gt;/B&lt;&lt;329.0,423.0&gt;-&lt;337.0,423.0&gt;-&lt;345.0,423.5&gt;&gt; = 14.036243467926457

* u12543 (U+12543): L&lt;&lt;660.0,424.0&gt;--&lt;656.0,454.0&gt;&gt;/B&lt;&lt;656.0,454.0&gt;-&lt;656.0,446.0&gt;-&lt;656.0,438.5&gt;&gt; = 7.594643368591447
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure files are not too large. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Font file is 1.4Mb; ideally it should be less than 1.0Mb</p>
 [code: large-font]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 9 | 117 | 6 | 118 | 0 | 
| 0% | 0% | 0% | 4% | 47% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
