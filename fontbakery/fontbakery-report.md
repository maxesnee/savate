## FontBakery report

fontbakery version: 0.13.2







## Check results



<details><summary>[22] Savate[wght].ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Familyname must be unique according to namecheck.fontdata.com <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontdata-namecheck">fontdata_namecheck</a></summary>
    <div>







* 💥 **ERROR** <p>Failed with TypeError: '&gt;' not supported between instances of 'NoneType' and 'int'</p>
<pre><code>  File &quot;/home/runner/work/savate/savate/venv-test/lib/python3.10/site-packages/fontbakery/checkrunner.py&quot;, line 222, in _run_check
    subresults = list(subresults)
  File &quot;/home/runner/work/savate/savate/venv-test/lib/python3.10/site-packages/fontbakery/checks/fontdata_namecheck.py&quot;, line 24, in check_fontdata_namecheck
    if data[&quot;data&quot;][&quot;confidence&quot;][&quot;1.0&quot;] &gt; 0:

</code></pre>
 [code: failed-check]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#case-mapping">case_mapping</a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+03BB: GREEK SMALL LETTER LAMDA</td>
<td align="left">U+039B: GREEK CAPITAL LETTER LAMDA</td>
</tr>
<tr>
<td align="left">U+03C7: GREEK SMALL LETTER CHI</td>
<td align="left">U+03A7: GREEK CAPITAL LETTER CHI</td>
</tr>
<tr>
<td align="left">U+1EA1: LATIN SMALL LETTER A WITH DOT BELOW</td>
<td align="left">U+1EA0: LATIN CAPITAL LETTER A WITH DOT BELOW</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 1105, but got 1004 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 344, but got 196 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoLineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: OS/2]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#os2-metrics-match-hhea">os2_metrics_match_hhea</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (772) and hhea ascent (1004) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to j when shaping the text 'íj́'</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01DD when shaping the text 'ǝ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01DD when shaping the text 'ǝ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01DD when shaping the text 'ǝ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01DD when shaping the text 'ǝ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left">bqv_Latn (Koro Wachi), bba_Latn (Baatonum) and ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni025B when shaping the text 'ɛ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0190 when shaping the text 'Ɛ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni025B when shaping the text 'ɛ̱'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0190 when shaping the text 'Ɛ̱'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni025B when shaping the text 'ɛ̱̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0331 when shaping the text 'ɛ̱̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0190 when shaping the text 'Ɛ̱̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0331 when shaping the text 'Ɛ̱̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0254 when shaping the text 'ɔ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0186 when shaping the text 'Ɔ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0254 when shaping the text 'ɔ̱'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0186 when shaping the text 'Ɔ̱'</td>
<td align="left">nus_Latn (Nuer)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0259 when shaping the text 'ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left">ybb_Latn (Yemba) and mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left">aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0327 when shaping the text 'ɛ̧̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0327 when shaping the text 'Ɛ̧̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni025B when shaping the text 'ɛ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0190 when shaping the text 'Ɛ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0327 when shaping the text 'ɔ̧̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0327 when shaping the text 'Ɔ̧̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0254 when shaping the text 'ɔ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0186 when shaping the text 'Ɔ̍'</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɤ́, Ɤ̏, ɤ̀, ɤ, Ɤ̄, ɤ̂, ɤ́, Ɤ, ɤ̏, Ɤ̂, Ɤ̀, ɤ̋, Ɤ̋, ɤ̄</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni025B when shaping the text 'ɛ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0190 when shaping the text 'Ɛ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni025B when shaping the text 'ɛ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni0190 when shaping the text 'Ɛ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to .notdef when shaping the text 'Ɤ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to .notdef when shaping the text 'Ɤ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to .notdef when shaping the text 'Ɤ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni026F when shaping the text 'ɯ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni019C when shaping the text 'Ɯ̏'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni026F when shaping the text 'ɯ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019C when shaping the text 'Ɯ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni026F when shaping the text 'ɯ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni019C when shaping the text 'Ɯ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni026F when shaping the text 'ɯ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019C when shaping the text 'Ɯ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni026F when shaping the text 'ɯ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni019C when shaping the text 'Ɯ̋'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni026F when shaping the text 'ɯ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019C when shaping the text 'Ɯ̂'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259 when shaping the text 'ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">bax_Latn (Bamun (Latin)) and bfd_Latn (Bafut)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A when shaping the text 'ɪ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7 when shaping the text 'ꞷ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6 when shaping the text 'Ꞷ̃'</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left">tik_Latn (Tikar)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left">dgi_Latn (Northern Dagara)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left">kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left">mgo_Latn (Metaʼ)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0269 when shaping the text 'ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0196 when shaping the text 'Ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0269 when shaping the text 'ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0196 when shaping the text 'Ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0269 when shaping the text 'ɩ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0196 when shaping the text 'Ɩ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B when shaping the text 'ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028B when shaping the text 'ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028B when shaping the text 'ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028B when shaping the text 'ʋ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2 when shaping the text 'Ʋ̌'</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɛ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɛ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'Ɛ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'Ɛ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259 when shaping the text 'ə̌'</td>
<td align="left">mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0196 when shaping the text 'Ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01DD when shaping the text 'ǝ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01DD when shaping the text 'ǝ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01DD when shaping the text 'ǝ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left">tuz_Latn (Turka)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left">yo_Latn_BJ (Yoruba, Benin), yav_Latn (Yangben), myk_Latn (Mamara Senoufo) and lu_Latn (Luba-Katanga)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left">ee_Latn (Ewe), bqp_Latn (Bisã) and bqc_Latn (Boko)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ɛ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ɛ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɔ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ɔ̧̂'</td>
<td align="left">pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0259 when shaping the text 'ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">ln_Latn (Lingala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01DD when shaping the text 'ǝ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left">ksf_Latn (Bafia)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0190 when shaping the text 'Ɛ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0186 when shaping the text 'Ɔ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259 when shaping the text 'ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni025B when shaping the text 'ɛ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0259 when shaping the text 'ə̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0254 when shaping the text 'ɔ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left">sbd_Latn (Southern Samo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259 when shaping the text 'ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259 when shaping the text 'ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259 when shaping the text 'ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left">dur_Latn (Dii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left">lom_Latn (Loma, Liberia), tcd_Latn (Tafi), nga_Latn (Ngbaka) and nyb_Latn (Nyangbo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196 when shaping the text 'Ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B when shaping the text 'ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269 when shaping the text 'ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028B when shaping the text 'ʋ̃'</td>
<td align="left">sld_Latn (Sissala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left">gnd_Latn (Zulgo-Gemzek)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left">etx_Latn (Iten)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196 when shaping the text 'Ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269 when shaping the text 'ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028B when shaping the text 'ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B when shaping the text 'ʋ́'</td>
<td align="left">kst_Latn (Winyé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: Ɤ́, ɤ, ɤ̂, Ɤ, Ɤ̂, ɤ́, Ɤ̀, ɤ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɤ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B when shaping the text 'ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0269 when shaping the text 'ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0196 when shaping the text 'Ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɤ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028B when shaping the text 'ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0269 when shaping the text 'ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0196 when shaping the text 'Ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɤ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028B when shaping the text 'ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni025B when shaping the text 'ɛ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0190 when shaping the text 'Ɛ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0254 when shaping the text 'ɔ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0186 when shaping the text 'Ɔ̈'</td>
<td align="left">din_Latn (Dinka) and dip_Latn (Dinka, Northeastern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left">dua_Latn (Duala), tvu_Latn (Tunen) and mdt_Latn (Mbere)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0259 when shaping the text 'ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0259 when shaping the text 'ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ə̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0259 when shaping the text 'ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ə̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ɔ̰́'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left">box_Latn (Buamu)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B when shaping the text 'ɛ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190 when shaping the text 'Ɛ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧'</td>
<td align="left">kkj_Latn (Kako)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196 when shaping the text 'Ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0196 when shaping the text 'Ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269 when shaping the text 'ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028B when shaping the text 'ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0269 when shaping the text 'ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028B when shaping the text 'ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B when shaping the text 'ʋ́'</td>
<td align="left">pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259 when shaping the text 'ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">bbj_Latn (Ghomala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ꟈ, Ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">bsq_Latn (Bassa (Latin))</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01DD when shaping the text 'ǝ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269 when shaping the text 'ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196 when shaping the text 'Ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028B when shaping the text 'ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left">lob_Latn (Lobi)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left">dya_Latn (Dyan), ife_Latn (Ifè) and gur_Latn (Frafra)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196 when shaping the text 'Ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269 when shaping the text 'ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028B when shaping the text 'ʋ̃'</td>
<td align="left">bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0269 when shaping the text 'ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0196 when shaping the text 'Ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0269 when shaping the text 'ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0196 when shaping the text 'Ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B when shaping the text 'ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028B when shaping the text 'ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2 when shaping the text 'Ʋ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028B when shaping the text 'ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left">neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left">etu_Latn (Ejagham)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left">nnw_Latn (Southern Nuni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left">agq_Latn (Aghem)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left">loq_Latn (Lobala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">lol_Latn (Mongo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259 when shaping the text 'ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɔ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ɔ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'ɔ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327 when shaping the text 'Ɔ̧̌'</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0269 when shaping the text 'ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0196 when shaping the text 'Ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269 when shaping the text 'ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196 when shaping the text 'Ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0269 when shaping the text 'ɩ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0196 when shaping the text 'Ɩ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B when shaping the text 'ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028B when shaping the text 'ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2 when shaping the text 'Ʋ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028B when shaping the text 'ʋ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2 when shaping the text 'Ʋ̃'</td>
<td align="left">gna_Latn (Kaansa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni025B when shaping the text 'ɛ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0190 when shaping the text 'Ɛ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0254 when shaping the text 'ɔ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0186 when shaping the text 'Ɔ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">krw_Latn (Western Krahn)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01DD when shaping the text 'ǝ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01DD when shaping the text 'ǝ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01DD when shaping the text 'ǝ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0269 when shaping the text 'ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0196 when shaping the text 'Ɩ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0269 when shaping the text 'ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0196 when shaping the text 'Ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A when shaping the text 'ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1 when shaping the text 'Ʊ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A when shaping the text 'ʊ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1 when shaping the text 'Ʊ̂'</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D when shaping the text 'Ɑ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0251 when shaping the text 'ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0251 when shaping the text 'ɑ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0251 when shaping the text 'ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259 when shaping the text 'ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">nnh_Latn (Ngiemboon) and bom_Latn (Berom)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259 when shaping the text 'ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259 when shaping the text 'ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ə̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259 when shaping the text 'ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ə̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259 when shaping the text 'ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ə̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327 when shaping the text 'Ɔ̧́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327 when shaping the text 'Ɔ̧̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254 when shaping the text 'ɔ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'ɔ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186 when shaping the text 'Ɔ̧̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327 when shaping the text 'Ɔ̧̂'</td>
<td align="left">vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left">mev_Latn (Mano)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259 when shaping the text 'ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">ewo_Latn (Ewondo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left">wwa_Latn (Waama)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: T͟H, t͟h</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following mark characters are missing from the font: ͟</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to p when shaping the text 'p̱'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to P when shaping the text 'P̱'</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0251 when shaping the text 'ɑ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D when shaping the text 'Ɑ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0251 when shaping the text 'ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D when shaping the text 'Ɑ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0251 when shaping the text 'ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D when shaping the text 'Ɑ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0251 when shaping the text 'ɑ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D when shaping the text 'Ɑ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259 when shaping the text 'ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0259 when shaping the text 'ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B when shaping the text 'ʋ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2 when shaping the text 'Ʋ́'</td>
<td align="left">xsm_Latn_BF (Kasem, Burkina Faso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269 when shaping the text 'ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196 when shaping the text 'Ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left">biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left">tbz_Latn (Ditammari) and emk_Latn (Maninkakan, Eastern)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01DD when shaping the text 'ǝ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01DD when shaping the text 'ǝ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01DD when shaping the text 'ǝ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01DD when shaping the text 'ǝ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275 when shaping the text 'ɵ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275 when shaping the text 'ɵ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275 when shaping the text 'ɵ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D when shaping the text 'Ɥ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D when shaping the text 'Ɥ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D when shaping the text 'Ɥ̂'</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259 when shaping the text 'ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left">lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left">vai_Latn (Vai (Latin)) and soy_Latn (Miyobe)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ɔ̰́'</td>
<td align="left">ntm_Latn (Nateni)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0259 when shaping the text 'ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ɛ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ɛ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ɔ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ɔ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ɔ̰̀'</td>
<td align="left">wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left">bwj_Latn (Láá Láá Bwamu)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259 when shaping the text 'ə̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">nfu_Latn (Mfumte)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left">bum_Latn (Bulu)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni025B when shaping the text 'ɛ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0190 when shaping the text 'Ɛ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0259 when shaping the text 'ə̈'</td>
<td align="left">lnl_Latn (South Central Banda)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left">ddn_Latn (Dendi)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259 when shaping the text 'ə̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0259 when shaping the text 'ə̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left">ksp_Latn (Kabba)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni025B when shaping the text 'ɛ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0190 when shaping the text 'Ɛ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0254 when shaping the text 'ɔ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0186 when shaping the text 'Ɔ̍'</td>
<td align="left">yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni025B when shaping the text 'ɛ᷆'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni025B when shaping the text 'ɛ᷇'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0190 when shaping the text 'Ɛ᷆'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0190 when shaping the text 'Ɛ᷇'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0254 when shaping the text 'ɔ᷆'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0254 when shaping the text 'ɔ᷇'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0186 when shaping the text 'Ɔ᷆'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0186 when shaping the text 'Ɔ᷇'</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃'</td>
<td align="left">kpe_Latn (Kpelle)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following base characters are missing from the font: ᶤ, ᵒ, ᵋ, ᵉ, ᶶ, ᵓ, ⁱ, ᵃ</td>
<td align="left">teo_Latn (Teso)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni025B when shaping the text 'ɛ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0190 when shaping the text 'Ɛ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0254 when shaping the text 'ɔ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0186 when shaping the text 'Ɔ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">grb_Latn (Grebo)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni025B when shaping the text 'ɛ̱'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0190 when shaping the text 'Ɛ̱'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0254 when shaping the text 'ɔ̱'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0186 when shaping the text 'Ɔ̱'</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Mandatory orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">jgo_Latn (Ngomba)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Phonetics_SinoExt glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ſ</td>
<td align="left">de_Latn (German) and fr_Latn (French)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to j when shaping the text 'j̃'</td>
<td align="left">lt_Latn (Lithuanian)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259 when shaping the text 'ə́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0259 when shaping the text 'ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0259 when shaping the text 'ə̈'</td>
<td align="left">ybb_Latn (Yemba)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni028B when shaping the text 'ʋ̈'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni01B2 when shaping the text 'Ʋ̈'</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0259 when shaping the text 'ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01DD when shaping the text 'ǝ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01DD when shaping the text 'ǝ̰'</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ƃ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ƃ</td>
<td align="left">lom_Latn (Loma, Liberia) and dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̀</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ́</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ɐ̂</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">The following auxiliary characters are missing from the font: Ⓐ</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to .notdef when shaping the text 'Ɐ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to .notdef when shaping the text 'Ɐ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'ɐ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to .notdef when shaping the text 'Ɐ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272 when shaping the text 'ɲ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019D when shaping the text 'Ɲ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272 when shaping the text 'ɲ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019D when shaping the text 'Ɲ́'</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0259 when shaping the text 'ə̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0259 when shaping the text 'ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F when shaping the text 'Ə̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ə̰̄'</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0259 when shaping the text 'ə̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0259 when shaping the text 'ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ə̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B when shaping the text 'ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190 when shaping the text 'Ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ɛ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254 when shaping the text 'ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186 when shaping the text 'Ɔ̨́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328 when shaping the text 'Ɔ̨́'</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left">gej_Latn (Gen)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269 when shaping the text 'ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196 when shaping the text 'Ɩ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0269 when shaping the text 'ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0196 when shaping the text 'Ɩ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269 when shaping the text 'ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196 when shaping the text 'Ɩ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0269 when shaping the text 'ɩ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0196 when shaping the text 'Ɩ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0269 when shaping the text 'ɩ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0196 when shaping the text 'Ɩ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0269 when shaping the text 'ɩ᷆'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0196 when shaping the text 'Ɩ᷆'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269 when shaping the text 'ɩ̃᷆'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196 when shaping the text 'Ɩ̃᷆'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0254 when shaping the text 'ɔ᷆'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0186 when shaping the text 'Ɔ᷆'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A when shaping the text 'ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1 when shaping the text 'Ʊ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A when shaping the text 'ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1 when shaping the text 'Ʊ̃'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A when shaping the text 'ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1 when shaping the text 'Ʊ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A when shaping the text 'ʊ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1 when shaping the text 'Ʊ̌'</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to F when shaping the text 'F̣'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to J when shaping the text 'J̣'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to f when shaping the text 'f̣'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to g when shaping the text 'g̣'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to j when shaping the text 'j̣'</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ɛ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ɛ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B when shaping the text 'ɛ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ɛ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190 when shaping the text 'Ɛ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ɛ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330 when shaping the text 'Ɔ̰̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330 when shaping the text 'Ɔ̰́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254 when shaping the text 'ɔ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'ɔ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186 when shaping the text 'Ɔ̰̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330 when shaping the text 'Ɔ̰̄'</td>
<td align="left">mev_Latn (Mano)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni025B when shaping the text 'ɛ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0190 when shaping the text 'Ɛ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0254 when shaping the text 'ɔ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0186 when shaping the text 'Ɔ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B when shaping the text 'ɛ̃̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190 when shaping the text 'Ɛ̃̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254 when shaping the text 'ɔ̃̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186 when shaping the text 'Ɔ̃̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B when shaping the text 'ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190 when shaping the text 'Ɛ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B when shaping the text 'ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190 when shaping the text 'Ɛ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B when shaping the text 'ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190 when shaping the text 'Ɛ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B when shaping the text 'ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190 when shaping the text 'Ɛ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni025B when shaping the text 'ɛ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0190 when shaping the text 'Ɛ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni025B when shaping the text 'ɛ᷄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0190 when shaping the text 'Ɛ᷄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni025B when shaping the text 'ɛ᷅'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0190 when shaping the text 'Ɛ᷅'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Eng when shaping the text 'Ŋ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254 when shaping the text 'ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186 when shaping the text 'Ɔ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254 when shaping the text 'ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186 when shaping the text 'Ɔ́'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254 when shaping the text 'ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186 when shaping the text 'Ɔ̂'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254 when shaping the text 'ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186 when shaping the text 'Ɔ̌'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254 when shaping the text 'ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186 when shaping the text 'Ɔ̄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0254 when shaping the text 'ɔ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0186 when shaping the text 'Ɔ̍'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0254 when shaping the text 'ɔ᷄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0186 when shaping the text 'Ɔ᷄'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0254 when shaping the text 'ɔ᷅'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0186 when shaping the text 'Ɔ᷅'</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259 when shaping the text 'ə̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B when shaping the text 'ɛ̀'</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190 when shaping the text 'Ɛ̀'</td>
<td align="left">gvl_Latn (Gulay)</td>
</tr>
<tr>
<td align="left">Auxiliary orthography codepoints:</td>
<td align="left"></td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to g when shaping the text 'g̣'</td>
<td align="left">tuq_Latn (Tedaga)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check copyright namerecords match license file. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-license">googlefonts/name/license</a></summary>
    <div>







* 🔥 **FAIL** <p>Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set.</p>
 [code: missing]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsType does not impose restrictions. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-fstype">googlefonts/fstype</a></summary>
    <div>







* 🔥 **FAIL** <p>In this font fsType is set to 8 meaning that:
The font may be embedded but must only be installed temporarily on other systems.</p>
<p>No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead.</p>
 [code: drm]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyph-coverage">googlefonts/glyph_coverage</a></summary>
    <div>







* 🔥 **FAIL** <p>Missing required codepoints:</p>
<pre><code>- 0x0025 (PERCENT SIGN)


- 0x002B (PLUS SIGN)


- 0x003C (LESS-THAN SIGN)


- 0x003D (EQUALS SIGN)


- 0x003E (GREATER-THAN SIGN)


- 0x005E (CIRCUMFLEX ACCENT)


- 0x007C (VERTICAL LINE)


- 0x007E (TILDE)


- 0x00A9 (COPYRIGHT SIGN)


- 0x00AE (REGISTERED SIGN)


- 0x00D7 (MULTIPLICATION SIGN)


- 0x00F7 (DIVISION SIGN)


- 0x2122 (TRADE MARK SIGN)


- 0x2212 (MINUS SIGN)
</code></pre>
 [code: missing-codepoints]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Validate STAT particle names and values match the fallback names in GFAxisRegistry. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-STAT-axisregistry">googlefonts/STAT/axisregistry</a></summary>
    <div>







* 🔥 **FAIL** <p>Axis Value for 'wght':'ExtraLight' is expected to be '200.0' but this font has 'ExtraLight'='100.0'.</p>
 [code: bad-coordinate]



* 🔥 **FAIL** <p>Axis Value for 'wght':'Light' is expected to be '300.0' but this font has 'Light'='200.0'.</p>
 [code: bad-coordinate]



* 🔥 **FAIL** <p>Axis Value for 'wght':'Regular' is expected to be '400.0' but this font has 'Regular'='350.0'.</p>
 [code: bad-coordinate]



* 🔥 **FAIL** <p>Axis Value for 'wght':'SemiBold' is expected to be '600.0' but this font has 'SemiBold'='550.0'.</p>
 [code: bad-coordinate]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics">googlefonts/vertical_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.sTypoLineGap is &quot;232&quot; it should be 0</p>
 [code: bad-OS/2.sTypoLineGap]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#alt-caron">alt_caron</a></summary>
    <div>









* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#interpolation-issues">interpolation_issues</a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 start point differs in glyph 'uni019A' between location wght=200 and location wght=593

- Contour 0 in glyph 'uni019A': becomes underweight between wght=200 and wght=593.

- Contour 0 start point differs in glyph 'asterisk' between location wght=200 and location wght=593

- Contour 0 in glyph 'asterisk': becomes underweight between wght=200 and wght=593.

- Contour 0 start point differs in glyph 'uni02BF' between location wght=200 and location wght=593

- Contour 0 in glyph 'uni02BF': becomes underweight between wght=200 and wght=593.

- Contour 0 start point differs in glyph 'uni02BE' between location wght=200 and location wght=593

- Contour 0 in glyph 'uni02BE': becomes underweight between wght=200 and wght=593.

- Contour 1 start point differs in glyph 'uni026A' between location wght=200 and location wght=593

- Contour 1 in glyph 'uni026A': becomes underweight between wght=200 and wght=593.

- Contour 2 start point differs in glyph 'uni026A' between location wght=200 and location wght=593

- Contour 2 in glyph 'uni026A': becomes underweight between wght=200 and wght=593.

- Contour order differs in glyph 'uni026A': [0, 1, 2] in wght=593, [0, 2, 1] in wght=900.
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#typoascender-exceeds-Agrave">typoascender_exceeds_Agrave</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2.sTypoAscender value should be greater than 949, but got 772 instead</p>
 [code: typoAscender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- dotlessi_ogonek

- eight.dnom

- eight.numr

- eight.osf

- five.dnom

- five.numr

- five.osf

- four.dnom

- four.numr

- four.osf

- nine.dnom

- nine.numr

- nine.osf

- one.dnom

- one.numr

- one.osf

- periodcentered.loclCAT

- periodcentered.loclCAT.case

- seven.dnom

- seven.numr

- seven.osf

- six.dnom

- six.numr

- six.osf

- three.dnom

- three.numr

- three.osf

- two.dnom

- two.numr

- two.osf

- uni03000304

- uni03010304

- uni03040300

- uni03040301

- zero.dnom

- zero.numr

- zero.osf
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-metadata-unreachable-subsetting">googlefonts/metadata/unreachable_subsetting</a></summary>
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
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, cherokee, math, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, tifinagh, canadian-aboriginal, math, coptic, old-permic, malayalam, todhri, duployan, hebrew, syriac</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: tai-le, cherokee</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0310 COMBINING CANDRABINDU: try adding one of: math, sunuwar</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding one of: old-permic, todhri</li>
<li>U+0315 COMBINING COMMA ABOVE RIGHT: try adding math</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, duployan, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: syriac, sunuwar</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: gothic, thai, tifinagh, caucasian-albanian, sunuwar, cherokee, syriac</li>
<li>U+0332 COMBINING LOW LINE: try adding math</li>
<li>U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0358 COMBINING DOT ABOVE RIGHT: try adding osage</li>
<li>U+0394 GREEK CAPITAL LETTER DELTA: try adding one of: greek, math, elbasan</li>
<li>U+03A9 GREEK CAPITAL LETTER OMEGA: try adding one of: greek, math, elbasan</li>
<li>U+03BB GREEK SMALL LETTER LAMDA: try adding one of: greek, math</li>
<li>U+03BC GREEK SMALL LETTER MU: try adding one of: greek, math</li>
<li>U+03C0 GREEK SMALL LETTER PI: try adding one of: greek, yi, math</li>
<li>U+03C7 GREEK SMALL LETTER CHI: try adding one of: greek, math</li>
<li>U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition</li>
<li>U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition</li>
<li>U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition</li>
<li>U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition</li>
<li>U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition</li>
<li>U+1EA1 LATIN SMALL LETTER A WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EAC LATIN CAPITAL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EAD LATIN SMALL LETTER A WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese</li>
<li>U+1EC6 LATIN CAPITAL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EC7 LATIN SMALL LETTER E WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ECA LATIN CAPITAL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECB LATIN SMALL LETTER I WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECC LATIN CAPITAL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ECD LATIN SMALL LETTER O WITH DOT BELOW: try adding vietnamese</li>
<li>U+1ED8 LATIN CAPITAL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1ED9 LATIN SMALL LETTER O WITH CIRCUMFLEX AND DOT BELOW: try adding vietnamese</li>
<li>U+1EE4 LATIN CAPITAL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+1EE5 LATIN SMALL LETTER U WITH DOT BELOW: try adding vietnamese</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+207F SUPERSCRIPT LATIN SMALL LETTER N: try adding math</li>
<li>U+2080 SUBSCRIPT ZERO: try adding math</li>
<li>U+2081 SUBSCRIPT ONE: try adding math</li>
<li>U+2082 SUBSCRIPT TWO: try adding math</li>
<li>U+2083 SUBSCRIPT THREE: try adding math</li>
<li>U+2084 SUBSCRIPT FOUR: try adding math</li>
<li>U+2085 SUBSCRIPT FIVE: try adding math</li>
<li>U+2086 SUBSCRIPT SIX: try adding math</li>
<li>U+2087 SUBSCRIPT SEVEN: try adding math</li>
<li>U+2088 SUBSCRIPT EIGHT: try adding math</li>
<li>U+2089 SUBSCRIPT NINE: try adding math</li>
<li>U+2144 TURNED SANS-SERIF CAPITAL Y: try adding math</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#dotted-circle">dotted_circle</a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ i̍ i̐ i̓ i᷆ i᷇ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̇ i̒ i᷄ i᷅ i̤̇ i̤̊ i̤̋ i̤̍ i̤̐ i̤̒ i̤̓ i̤᷄ i̤᷅ i̤᷆ i̤᷇ i̥̇ i̥̊ i̥̋ i̥̍ i̥̐</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-alignment-miss">outline_alignment_miss</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* uni1E00 (U+1E00): X=336.0,Y=-195.0 (should be at descender -196?)

* uni1E00 (U+1E00): X=336.0,Y=-195.0 (should be at descender -196?)

* uni0191 (U+0191): X=-11.0,Y=-197.0 (should be at descender -196?)

* uni1E2A (U+1E2A): X=359.0,Y=-195.0 (should be at descender -196?)

* uni1E2A (U+1E2A): X=359.0,Y=-195.0 (should be at descender -196?)

* uniA726 (U+A726): X=627.0,Y=2.0 (should be at baseline 0?)

* uni019D (U+019D): X=-11.0,Y=-197.0 (should be at descender -196?)

* uni024A (U+024A): X=751.0,Y=-195.5 (should be at descender -196?)

* uni1E9E (U+1E9E): X=486.0,Y=732.0 (should be at cap-height 730?)

* Uogonek (U+0172): X=494.0,Y=-2.0 (should be at baseline 0?)

* uni0251 (U+0251): X=580.5,Y=1.5 (should be at baseline 0?)

* uni1E01 (U+1E01): X=262.0,Y=-195.0 (should be at descender -196?)

* uni1E01 (U+1E01): X=262.0,Y=-195.0 (should be at descender -196?)

* atilde (U+00E3): X=196.0,Y=732.0 (should be at cap-height 730?)

* uni0256 (U+0256): X=605.5,Y=-195.5 (should be at descender -196?)

* eth (U+00F0): X=423.0,Y=732.0 (should be at cap-height 730?)

* uni1EBD (U+1EBD): X=209.0,Y=732.0 (should be at cap-height 730?)

* f (U+0066): X=355.0,Y=728.0 (should be at cap-height 730?)

* uni1E1F (U+1E1F): X=355.0,Y=728.0 (should be at cap-height 730?)

* g (U+0067): X=431.5,Y=-1.0 (should be at baseline 0?)

* uni01F5 (U+01F5): X=431.5,Y=-1.0 (should be at baseline 0?)

* gbreve (U+011F): X=431.5,Y=-1.0 (should be at baseline 0?)

* gcaron (U+01E7): X=431.5,Y=-1.0 (should be at baseline 0?)

* gcircumflex (U+011D): X=431.5,Y=-1.0 (should be at baseline 0?)

* uni0123 (U+0123): X=431.5,Y=-1.0 (should be at baseline 0?)

* uni0123 (U+0123): X=250.0,Y=771.0 (should be at ascender 772?)

* gdotaccent (U+0121): X=431.5,Y=-1.0 (should be at baseline 0?)

* uni0260 (U+0260): X=431.5,Y=-1.0 (should be at baseline 0?)

* uni0294 (U+0294): X=333.5,Y=730.5 (should be at cap-height 730?)

* uni1E21 (U+1E21): X=431.5,Y=-1.0 (should be at baseline 0?)

* uni01E5 (U+01E5): X=431.5,Y=-1.0 (should be at baseline 0?)

* uni1E2B (U+1E2B): X=276.0,Y=-195.0 (should be at descender -196?)

* uni1E2B (U+1E2B): X=276.0,Y=-195.0 (should be at descender -196?)

* itilde (U+0129): X=16.0,Y=732.0 (should be at cap-height 730?)

* uni019B (U+019B): X=-10.0,Y=729.0 (should be at cap-height 730?)

* ntilde (U+00F1): X=204.0,Y=732.0 (should be at cap-height 730?)

* otilde (U+00F5): X=204.0,Y=732.0 (should be at cap-height 730?)

* uni1E4D (U+1E4D): X=204.0,Y=732.0 (should be at cap-height 730?)

* uni1E4F (U+1E4F): X=204.0,Y=732.0 (should be at cap-height 730?)

* uni022D (U+022D): X=204.0,Y=732.0 (should be at cap-height 730?)

* uni027D (U+027D): X=223.5,Y=-195.5 (should be at descender -196?)

* utilde (U+0169): X=191.0,Y=732.0 (should be at cap-height 730?)

* uni1E79 (U+1E79): X=191.0,Y=732.0 (should be at cap-height 730?)

* uni1E7D (U+1E7D): X=177.0,Y=732.0 (should be at cap-height 730?)

* uni1EF9 (U+1EF9): X=171.0,Y=732.0 (should be at cap-height 730?)

* uniA78C (U+A78C): X=103.5,Y=730.5 (should be at cap-height 730?)

* uniA78C (U+A78C): X=140.5,Y=730.5 (should be at cap-height 730?)

* lambda (U+03BB): X=-10.0,Y=729.0 (should be at cap-height 730?)

* uni03BC (U+03BC): X=547.5,Y=1.5 (should be at baseline 0?)

* exclam (U+0021): X=87.5,Y=2.0 (should be at baseline 0?)

* exclam (U+0021): X=157.0,Y=2.0 (should be at baseline 0?)

* exclamdown (U+00A1): X=122.0,Y=-194.0 (should be at descender -196?)

* asterisk (U+002A): X=200.0,Y=731.5 (should be at cap-height 730?)

* braceleft (U+007B): X=386.0,Y=774.0 (should be at ascender 772?)

* braceright (U+007D): X=70.0,Y=774.0 (should be at ascender 772?)

* quotedbl (U+0022): X=103.5,Y=730.5 (should be at cap-height 730?)

* quotedbl (U+0022): X=140.5,Y=730.5 (should be at cap-height 730?)

* quotedbl (U+0022): X=218.5,Y=730.5 (should be at cap-height 730?)

* quotedbl (U+0022): X=255.5,Y=730.5 (should be at cap-height 730?)

* quotesingle (U+0027): X=103.5,Y=730.5 (should be at cap-height 730?)

* quotesingle (U+0027): X=140.5,Y=730.5 (should be at cap-height 730?)

* florin (U+0192): X=389.0,Y=728.0 (should be at cap-height 730?)

* section (U+00A7): X=542.0,Y=1.0 (should be at baseline 0?)

* tildecomb (U+0303): X=173.0,Y=732.0 (should be at cap-height 730?)

* uni0312 (U+0312): X=218.0,Y=771.0 (should be at ascender 772?)

* uni0313 (U+0313): X=278.0,Y=732.0 (should be at cap-height 730?)

* uni0313 (U+0313): X=283.0,Y=728.0 (should be at cap-height 730?)

* uni0315 (U+0315): X=278.0,Y=732.0 (should be at cap-height 730?)

* uni0315 (U+0315): X=283.0,Y=728.0 (should be at cap-height 730?)

* uni0325 (U+0325): X=250.0,Y=-195.0 (should be at descender -196?)

* uni0325 (U+0325): X=250.0,Y=-195.0 (should be at descender -196?)

* uni032E (U+032E): X=250.0,Y=-195.0 (should be at descender -196?)

* uni032E (U+032E): X=250.0,Y=-195.0 (should be at descender -196?)

* tilde (U+02DC): X=173.0,Y=732.0 (should be at cap-height 730?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-meta-script-lang-tags">googlefonts/meta/script_lang_tags</a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vendor-id">googlefonts/vendor_id</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 1 | 0 | 10 | 11 | 91 | 7 | 116 | 0 | 
| 0% | 0% | 4% | 5% | 39% | 3% | 49% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
