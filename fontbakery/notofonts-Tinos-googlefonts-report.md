## FontBakery report

fontbakery version: 0.13.1







## Check results



<details><summary>[3] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Fonts have consistent underline thickness? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-family-underline-thickness">opentype/family/underline_thickness</a></summary>
    <div>







* 🔥 **FAIL** <p>Thickness of the underline is not the same across this family. In order to fix this, please make sure that the underlineThickness value is the same in the 'post' table of all of this family font files.
Detected underlineThickness values are:
fonts/Tinos/googlefonts/ttf/Tinos-BoldItalic.ttf: 195
fonts/Tinos/googlefonts/ttf/Tinos-Italic.ttf: 100
fonts/Tinos/googlefonts/ttf/Tinos-Regular.ttf: 100
fonts/Tinos/googlefonts/ttf/Tinos-Bold.ttf: 195</p>
 [code: inconsistent-underline-thickness]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Each font in a family must have the same set of vertical metrics values. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-vertical-metrics">family/vertical_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>sTypoAscender is not the same across the family:
Tinos Bold Italic: 1387
Tinos Italic: 1422
Tinos: 1420
Tinos Bold: 1387</p>
 [code: sTypoAscender-mismatch]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-use-typo-metrics">googlefonts/use_typo_metrics</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/Tinos/googlefonts/ttf/Tinos-BoldItalic.ttf', 'fonts/Tinos/googlefonts/ttf/Tinos-Italic.ttf', 'fonts/Tinos/googlefonts/ttf/Tinos-Regular.ttf', 'fonts/Tinos/googlefonts/ttf/Tinos-Bold.ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>

<details><summary>[22] Tinos-BoldItalic.ttf</summary>
<div>
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
<td align="left">U+1D8E: LATIN SMALL LETTER Z WITH PALATAL HOOK</td>
<td align="left">U+A7C6: LATIN CAPITAL LETTER Z WITH PALATAL HOOK</td>
</tr>
<tr>
<td align="left">U+2184: LATIN SMALL LETTER REVERSED C</td>
<td align="left">U+2183: ROMAN NUMERAL REVERSED ONE HUNDRED</td>
</tr>
<tr>
<td align="left">U+A794: LATIN SMALL LETTER C WITH PALATAL HOOK</td>
<td align="left">U+A7C4: LATIN CAPITAL LETTER C WITH PALATAL HOOK</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 2068, but got 1825 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 797, but got 443 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.13.1, while a newer 0.13.2 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#os2-metrics-match-hhea">os2_metrics_match_hhea</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (1387) and hhea ascent (1825) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check tabular widths don't have kerning. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#tabular-kerning">tabular_kerning</a></summary>
    <div>







* 🔥 **FAIL** <p>Kerning between one and one is -113, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -113, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -113, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -113, should be 0</p>
 [code: has-tabular-kerning]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Whitespace glyphs have ink? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#whitespace-ink">whitespace_ink</a></summary>
    <div>







* 🔥 **FAIL** <p>Glyph 'uni2028' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni2029' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni205F' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni2060' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uniFEFF' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Greek_Expert glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Shaper didn't attach acutecomb to j</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to J</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">The locl feature did not affect Eng</td>
<td align="left">bm_Latn (Bambara), dyu_Latn (Dyula), ig_Latn (Igbo), lg_Latn (Ganda), mnf_Latn (Mundani), las_Latn (Lama, Togo), dtm_Latn (Tomo Kan Dogon), dnj_Latn (Dan), nnh_Latn (Ngiemboon), ttq_Latn (Tawallammat Tamajaq), snk_Latn (Soninke), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nfr_Latn (Nafaanra), nus_Latn (Nuer), bsc_Latn (Bassari), dur_Latn (Dii), naw_Latn (Nawuri), fmp_Latn (Fe’fe’), sav_Latn (Saafi-Saafi), mne_Latn (Naba), azo_Latn (Awing), ig_Latn (Igbo), bzw_Latn (Basa), fuc_Latn (Pulaar), yat_Latn (Yambeta), nnw_Latn (Southern Nuni), kpo_Latn (Ikposo), log_Latn (Logo), dip_Latn (Dinka, Northeastern), twq_Latn (Tasawaq), nfu_Latn (Mfumte), ajg_Latn (Aja), xwe_Latn (Gbe, Xwela), loq_Latn (Lobala), bsp_Latn (Baga Sitemu), wan_Latn (Wan), bcw_Latn (Bana), maw_Latn (Mampruli), myk_Latn (Mamara Senoufo), mfv_Latn (Mandjak), tuq_Latn (Tedaga), agc_Latn (Agatu), krs_Latn (Gbaya, Sudan), bbo_Latn (Northern Bobo Madaré), mfd_Latn (Mendankwe-Nkwen), etu_Latn (Ejagham), xuo_Latn (Kuo), xon_Latn (Konkomba), sok_Latn (Sokoro), adj_Latn (Adioukrou), avn_Latn (Avatime), nku_Latn (Kulango, Bouna), mcn_Latn (Masana), nym_Latn (Nyamwezi), shz_Latn (Syenara Senoufo), lun_Latn (Lunda), ade_Latn (Adele), mdj_Latn (Mangbetu), gur_Latn (Frafra), gna_Latn (Kaansa), mua_Latn (Mundang), bex_Latn (Jur Modo), fvr_Latn (Fur), lam_Latn (Lamba), bza_Latn (Bandi), wci_Latn (Gbe, Waci), mcu_Latn (Mambila, Cameroon), taq_Latn (Tamasheq (Latin)), kvf_Latn (Kabalai), blo_Latn (Anii), gde_Latn (Gude), tik_Latn (Tikar), nmg_Latn (Kwasio), sig_Latn (Paasaal), dow_Latn (Doyayo), dag_Latn (Dagbani), keu_Latn (Akebu), giz_Latn (Southern Giziga), bfd_Latn (Bafut), dno_Latn (Ndrulo), bud_Latn (Ntcham), dyo_Latn (Jola-Fonyi), ybb_Latn (Yemba), tvu_Latn (Tunen), kus_Latn (Kusaal), agq_Latn (Aghem), kzc_Latn (Bondoukou Kulango), ksf_Latn (Bafia), wwa_Latn (Waama), khq_Latn (Koyra Chiini), tod_Latn (Toma), ewo_Latn (Ewondo), muy_Latn (Muyang), cae_Latn (Lehar), vut_Latn (Vute), bzx_Latn (Bozo, Hainyaxo), xsm_Latn (Kasem), xrb_Latn (Karaboro, Eastern), gmm_Latn (Gbaya-Mbodomo), gnd_Latn (Zulgo-Gemzek), nmz_Latn (Nawdm), kpz_Latn (Sapiny), dyu_Latn (Dyula), kdj_Latn (Karamojong), mbu_Latn (Mbula-Bwazza), cou_Latn (Wamey), ny_Latn (Nyanja), avu_Latn (Avokaya), mev_Latn (Mano), bib_Latn (Bissa), ntr_Latn (Delo), udu_Latn (Uduk), ahl_Latn (Igo), spp_Latn (Sénoufo, Supyire), ife_Latn (Ifè), mfi_Latn (Wandala), srr_Latn (Serer), fuf_Latn (Pular), kyq_Latn (Kenga), ikx_Latn (Ik), pbi_Latn (Parkwa), cko_Latn (Anufo), kye_Latn (Krache), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), ken_Latn (Kenyang), tcd_Latn (Tafi), vag_Latn (Vagla), yam_Latn (Yamba), saf_Latn (Safaliba), pil_Latn (Yom), mgc_Latn (Morokodo), mmu_Latn (Mmaala), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), ndz_Latn (Ndogo), cme_Latn (Cerma), kqp_Latn (Kimré), ffm_Latn (Maasina Fulfulde), pnz_Latn (Pana, Central African Republic), kao_Latn (Xaasongaxango), knf_Latn (Mankanya), mur_Latn (Murle), nhu_Latn (Noone), neb_Latn (Toura), lg_Latn (Ganda), ses_Latn (Koyraboro Senni), daa_Latn (Dangaléat), fub_Latn (Fulfulde, Adamawa), ahs_Latn (Ashe), mwk_Latn (Kita Maninkakan), ddn_Latn (Dendi), acd_Latn (Gikyode), xed_Latn (Hdi), kss_Latn (Southern Kisi), kqs_Latn (Kissi, Northern), sef_Latn (Cebaara Senoufo), dgi_Latn (Northern Dagara), ncu_Latn (Chumburung), kmy_Latn (Koma), lee_Latn (Lyélé), bbj_Latn (Ghomala), lmp_Latn (Limbum), kib_Latn (Koalib), wok_Latn (Longto), bav_Latn (Vengo), byv_Latn (Medumba), bqv_Latn (Koro Wachi), kyf_Latn (Kouya), dzg_Latn (Dazaga), yas_Latn (Nugunu), ekm_Latn (Elip), snf_Latn (Noon), sxw_Latn (Saxwe Gbe), nza_Latn (Tigon Mbembe), toq_Latn (Toposa), gej_Latn (Gen), tnr_Latn (Ménik), jgo_Latn (Ngomba), ktj_Latn (Krumen, Plapo), gjn_Latn (Gonja), fuq_Latn (Central-Eastern Niger Fulfulde), bum_Latn (Bulu), fue_Latn (Fulfulde, Borgu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), mgo_Latn (Metaʼ), nko_Latn (Nkonya), ebo_Latn (Teke-Ebo), fan_Latn (Fang), ozm_Latn (Koonzime), dop_Latn (Lukpa), mcp_Latn (Makaa), mls_Latn (Masalit), god_Latn (Godié), bss_Latn (Akoose), mor_Latn (Moro), kbo_Latn (Keliko), kia_Latn (Kim), bfa_Latn (Bari), kdh_Latn (Tem), lok_Latn (Loko), ach_Latn (Acoli), sil_Latn (Sisaala, Tumulung), lns_Latn (Lamnso’), bze_Latn (Jenaama Bozo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), lig_Latn (Ligbi), csk_Latn (Jola-Kasa), anv_Latn (Denya), rub_Latn (Gungu), mnk_Latn (Mandinka), mgd_Latn (Moru), moa_Latn (Mwan), gng_Latn (Ngangam), mas_Latn (Masai), dje_Latn (Zarma), mbo_Latn (Mbo), yav_Latn (Yangben), dua_Latn (Duala), ted_Latn (Krumen, Tepo), tem_Latn (Timne), fod_Latn (Foodo), soy_Latn (Miyobe), wo_Latn (Wolof), mdt_Latn (Mbere), boz_Latn (Tiéyaxo Bozo), gud_Latn (Dida, Yocoboué), nhb_Latn (Beng), fuh_Latn (Fulfulde, Western Niger), bim_Latn (Bimoba), kzr_Latn (Karang), kbp_Latn (Kabiyé), mfq_Latn (Moba), gux_Latn (Gourmanchéma), bjt_Latn (Balanta-Ganja), knp_Latn (Kwanja), dyi_Latn (Sénoufo, Djimini), gaa_Latn (Ga), tpm_Latn (Tampulma), idu_Latn (Idoma), bm_Latn (Bambara), lem_Latn (Nomaande), emk_Latn (Maninkakan, Eastern), meq_Latn (Merey), bkm_Latn (Kom), mzw_Latn (Deg), nuv_Latn (Nuni, Northern), bqj_Latn (Bandial), lia_Latn (Limba, West-Central), pug_Latn (Phuie), aks_Latn (Akeselem), dts_Latn (Dogon, Toro So), ndv_Latn (Ndut), hag_Latn (Hanga), bas_Latn (Basaa), laj_Latn (Lango, Uganda), gkp_Latn (Kpelle, Guinea) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to r</td>
<td align="left">ha_Latn (Hausa) and ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to R</td>
<td align="left">ha_Latn (Hausa) and ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), avu_Latn (Avokaya), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), avu_Latn (Avokaya), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to m</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), ig_Latn (Igbo), yo_Latn_BJ (Yoruba, Benin), yo_Latn (Yoruba), tik_Latn (Tikar), bud_Latn (Ntcham), mev_Latn (Mano), kyq_Latn (Kenga), ikw_Latn (Ikwere), tbz_Latn (Ditammari), jgo_Latn (Ngomba), gvl_Latn (Gulay) and nup_Latn (Nupe-Nupe-Tako)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to M</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), ig_Latn (Igbo), yo_Latn_BJ (Yoruba, Benin), yo_Latn (Yoruba), tik_Latn (Tikar), bud_Latn (Ntcham), mev_Latn (Mano), kyq_Latn (Kenga), ikw_Latn (Ikwere), tbz_Latn (Ditammari), jgo_Latn (Ngomba), gvl_Latn (Gulay) and nup_Latn (Nupe-Nupe-Tako)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere), ann_Latn (Obolo) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere), ann_Latn (Obolo) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to O</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ocircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), nzk_Latn (Nzakara), ozm_Latn (Koonzime), mcp_Latn (Makaa), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D2</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), nfu_Latn (Mfumte), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), tcd_Latn (Tafi), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), gov_Latn (Goo), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Agrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to o</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0197</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), nyb_Latn (Nyangbo), yav_Latn (Yangben), mge_Latn (Mango), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to U</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0197</td>
<td align="left">mnf_Latn (Mundani) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ugrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to A</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ograve</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to a</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ucircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0228</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ugrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), bfd_Latn (Bafut), ewo_Latn (Ewondo), ksp_Latn (Kabba), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
<td align="left">mnf_Latn (Mundani), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0229</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), nyb_Latn (Nyangbo), yav_Latn (Yangben), mge_Latn (Mango), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), gnd_Latn (Zulgo-Gemzek), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), byv_Latn (Medumba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), gvl_Latn (Gulay), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ocircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0229</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), bfd_Latn (Bafut), ewo_Latn (Ewondo), ksp_Latn (Kabba), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0268</td>
<td align="left">mnf_Latn (Mundani) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D3</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to u</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), gnd_Latn (Zulgo-Gemzek), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), byv_Latn (Medumba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), gvl_Latn (Gulay), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0197</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), nzk_Latn (Nzakara), ozm_Latn (Koonzime), mcp_Latn (Makaa), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to acircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01CE</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0197</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), nfu_Latn (Mfumte), bfd_Latn (Bafut), agq_Latn (Aghem), gvl_Latn (Gulay), mge_Latn (Mango), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ucircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Acircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), nfu_Latn (Mfumte), bfd_Latn (Bafut), agq_Latn (Aghem), gvl_Latn (Gulay), mge_Latn (Mango), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), nfu_Latn (Mfumte), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), tcd_Latn (Tafi), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D4</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to agrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0228</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0229</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D1</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
<td align="left">mnf_Latn (Mundani), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01CD</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0228</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ograve</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni025B</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to a</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to A</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to ae</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to AE</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to ae</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to AE</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to ae</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to AE</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to ae</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to AE</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to e</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to E</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0190</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), tik_Latn (Tikar), dow_Latn (Doyayo), bfd_Latn (Bafut), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), nyb_Latn (Nyangbo), gov_Latn (Goo), yav_Latn (Yangben), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), tik_Latn (Tikar), dow_Latn (Doyayo), bfd_Latn (Bafut), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), nyb_Latn (Nyangbo), yav_Latn (Yangben), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
<td align="left">dnj_Latn (Dan), nmg_Latn (Kwasio), dow_Latn (Doyayo), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
<td align="left">dnj_Latn (Dan), nmg_Latn (Kwasio), dow_Latn (Doyayo), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mdt_Latn (Mbere), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mdt_Latn (Mbere), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni025B</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni0190</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), kpe_Latn (Kpelle), lnl_Latn (South Central Banda), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), gov_Latn (Goo), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), kpe_Latn (Kpelle), lnl_Latn (South Central Banda), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to i</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to I</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0264</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), fvr_Latn (Fur), agq_Latn (Aghem), nzk_Latn (Nzakara), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), fvr_Latn (Fur), agq_Latn (Aghem), nzk_Latn (Nzakara), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), ybb_Latn (Yemba), bbj_Latn (Ghomala), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), mas_Latn (Masai) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), fvr_Latn (Fur), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), ybb_Latn (Yemba), bbj_Latn (Ghomala), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), mas_Latn (Masai) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), ybb_Latn (Yemba), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), mwm_Latn (Sar), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mge_Latn (Mango), mdt_Latn (Mbere), kzr_Latn (Karang), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), fvr_Latn (Fur), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), ybb_Latn (Yemba), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), mwm_Latn (Sar), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mge_Latn (Mango), mdt_Latn (Mbere), kzr_Latn (Karang), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to J</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq), taq_Latn (Tamasheq (Latin)) and tmh_Latn (Tamashek)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), dgi_Latn (Northern Dagara), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), dgi_Latn (Northern Dagara), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Utilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to a</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to A</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to e</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to E</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to i</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to I</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to o</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to O</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0254</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0186</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to u</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to U</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to atilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Atilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to tildecomb</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to itilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Itilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to utilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Utilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), dnj_Latn_LR (Liberian Dan), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to itilde</td>
<td align="left">nga_Latn (Ngbaka) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Itilde</td>
<td align="left">nga_Latn (Ngbaka) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to utilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Utilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to itilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Itilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to utilde</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Utilde</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to e</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to E</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to o</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to O</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), sba_Latn (Ngambay), blo_Latn (Anii), nmg_Latn (Kwasio) and ksf_Latn (Bafia)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and lob_Latn (Lobi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), sba_Latn (Ngambay), blo_Latn (Anii), nmg_Latn (Kwasio) and ksf_Latn (Bafia)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to otilde</td>
<td align="left">tuz_Latn (Turka), lom_Latn (Loma, Liberia), lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and lob_Latn (Lobi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0196</td>
<td align="left">tuz_Latn (Turka), goa_Latn (Guro), blo_Latn (Anii), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Otilde</td>
<td align="left">tuz_Latn (Turka), lom_Latn (Loma, Liberia), lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196</td>
<td align="left">tuz_Latn (Turka), goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), xsm_Latn_BF (Kasem, Burkina Faso), tcd_Latn (Tafi), neb_Latn (Toura), sld_Latn (Sissala), pug_Latn (Phuie) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EE4</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EB9</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECA</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EE5</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECA</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), avu_Latn (Avokaya), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EE4</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECD</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EB8</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECC</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EE5</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), avu_Latn (Avokaya), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EB9</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EB8</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECA</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECD</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECC</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EE5</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EE4</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to i</td>
<td align="left">kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
<td align="left">kkj_Latn (Kako), dow_Latn (Doyayo), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to I</td>
<td align="left">kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
<td align="left">kkj_Latn (Kako), dow_Latn (Doyayo), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to a</td>
<td align="left">nus_Latn (Nuer), asg_Latn (Cishingini), fvr_Latn (Fur), kdj_Latn (Karamojong), kaj_Latn (Jju) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), lnl_Latn (South Central Banda), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0254</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
<td align="left">nus_Latn (Nuer)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to A</td>
<td align="left">nus_Latn (Nuer), asg_Latn (Cishingini), fvr_Latn (Fur), kdj_Latn (Karamojong), kaj_Latn (Jju) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), lnl_Latn (South Central Banda), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0190</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to i</td>
<td align="left">nus_Latn (Nuer), kdj_Latn (Karamojong), kcg_Latn (Tyap) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0254</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0186</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0186</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to I</td>
<td align="left">nus_Latn (Nuer), kdj_Latn (Karamojong), kcg_Latn (Tyap) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to h</td>
<td align="left">bsc_Latn (Bassari)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to H</td>
<td align="left">bsc_Latn (Bassari)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to w</td>
<td align="left">bsc_Latn (Bassari) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to W</td>
<td align="left">bsc_Latn (Bassari) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
<td align="left">dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), etu_Latn (Ejagham), sba_Latn (Ngambay), bfd_Latn (Bafut), ybb_Latn (Yemba), ewo_Latn (Ewondo), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), mwm_Latn (Sar), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), mcp_Latn (Makaa), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Oacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Igrave</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
<td align="left">dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Uacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0228</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0229</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0197</td>
<td align="left">dur_Latn (Dii), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), bfd_Latn (Bafut), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), mge_Latn (Mango) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Iacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
<td align="left">dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), etu_Latn (Ejagham), sba_Latn (Ngambay), bfd_Latn (Bafut), ybb_Latn (Yemba), ewo_Latn (Ewondo), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), mwm_Latn (Sar), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), mcp_Latn (Makaa), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to aacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268</td>
<td align="left">dur_Latn (Dii), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), bfd_Latn (Bafut), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), mge_Latn (Mango) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F</td>
<td align="left">dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to igrave</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to iacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to oacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Aacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), kyq_Latn (Kenga), mwm_Latn (Sar), wok_Latn (Longto), bax_Latn (Bamun (Latin)) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
<td align="left">fmp_Latn (Fe’fe’), nmg_Latn (Kwasio), dow_Latn (Doyayo), ybb_Latn (Yemba), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), mwm_Latn (Sar), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0289</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), agq_Latn (Aghem) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0244</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), agq_Latn (Aghem) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186</td>
<td align="left">fmp_Latn (Fe’fe’), nmg_Latn (Kwasio), dow_Latn (Doyayo), ybb_Latn (Yemba), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), mwm_Latn (Sar), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), kyq_Latn (Kenga), mwm_Latn (Sar), wok_Latn (Longto), bax_Latn (Bamun (Latin)) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to n</td>
<td align="left">mne_Latn (Naba), kyq_Latn (Kenga), daa_Latn (Dangaléat), mls_Latn (Masalit) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to N</td>
<td align="left">mne_Latn (Naba), kyq_Latn (Kenga), daa_Latn (Dangaléat), mls_Latn (Masalit) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to U</td>
<td align="left">uth_Latn (ut-Hun), kdj_Latn (Karamojong), kaj_Latn (Jju) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to u</td>
<td align="left">uth_Latn (ut-Hun), kdj_Latn (Karamojong), kaj_Latn (Jju) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Oslash</td>
<td align="left">nfu_Latn (Mfumte) and ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oslash</td>
<td align="left">nfu_Latn (Mfumte) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Oslash</td>
<td align="left">nfu_Latn (Mfumte), ozm_Latn (Koonzime) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Oslash</td>
<td align="left">nfu_Latn (Mfumte) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oslash</td>
<td align="left">nfu_Latn (Mfumte), ozm_Latn (Koonzime) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oslash</td>
<td align="left">nfu_Latn (Mfumte) and ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018E</td>
<td align="left">dnj_Latn_LR (Liberian Dan), blo_Latn (Anii) and nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
<td align="left">dnj_Latn_LR (Liberian Dan), blo_Latn (Anii) and nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to n</td>
<td align="left">mg_Latn (Malagasy), etu_Latn (Ejagham), ksp_Latn (Kabba), ikw_Latn (Ikwere) and gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to N</td>
<td align="left">mg_Latn (Malagasy), etu_Latn (Ejagham), ksp_Latn (Kabba) and ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to n</td>
<td align="left">mg_Latn (Malagasy) and nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to N</td>
<td align="left">mg_Latn (Malagasy) and nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to g</td>
<td align="left">tuq_Latn (Tedaga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to G</td>
<td align="left">tuq_Latn (Tedaga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F</td>
<td align="left">lnl_Latn (South Central Banda), ybb_Latn (Yemba), ksp_Latn (Kabba) and sbd_Latn (Southern Samo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268</td>
<td align="left">lnl_Latn (South Central Banda) and nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0197</td>
<td align="left">lnl_Latn (South Central Banda) and nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
<td align="left">lnl_Latn (South Central Banda), ybb_Latn (Yemba), ksp_Latn (Kabba) and sbd_Latn (Southern Samo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0244</td>
<td align="left">lnl_Latn (South Central Banda), nzk_Latn (Nzakara) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0289</td>
<td align="left">lnl_Latn (South Central Banda), nzk_Latn (Nzakara) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
<td align="left">goa_Latn (Guro), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), xsm_Latn_BF (Kasem, Burkina Faso), neb_Latn (Toura), sld_Latn (Sissala) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), xsm_Latn_BF (Kasem, Burkina Faso), neb_Latn (Toura), sld_Latn (Sissala) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
<td align="left">goa_Latn (Guro), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
<td align="left">goa_Latn (Guro), blo_Latn (Anii), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0196</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tcd_Latn (Tafi) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tcd_Latn (Tafi) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028B</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0196</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), xsm_Latn_BF (Kasem, Burkina Faso), tcd_Latn (Tafi), neb_Latn (Toura), sld_Latn (Sissala), pug_Latn (Phuie) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EE4</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECD</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EB8</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECA</td>
<td align="left">mhi_Latn (Ma’di), avu_Latn (Avokaya) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECC</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EB9</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EE5</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB</td>
<td align="left">mhi_Latn (Ma’di), avu_Latn (Avokaya) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to o</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and kia_Latn (Kim)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E1A</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to A</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto), kia_Latn (Kim) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E1B</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E1A</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E1B</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to a</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto), kia_Latn (Kim) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to O</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and kia_Latn (Kim)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01DD</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018E</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), sld_Latn (Sissala), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), tcd_Latn (Tafi), sld_Latn (Sissala), biv_Latn (Birifor, Southern), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), sld_Latn (Sissala), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), tcd_Latn (Tafi), sld_Latn (Sissala), biv_Latn (Birifor, Southern), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni01CE</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Aacute</td>
<td align="left">fvr_Latn (Fur) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to aacute</td>
<td align="left">fvr_Latn (Fur) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to acircumflex</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Acircumflex</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni01CD</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EBC</td>
<td align="left">kst_Latn (Winyé), lee_Latn (Lyélé), sld_Latn (Sissala), soy_Latn (Miyobe), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EBD</td>
<td align="left">kst_Latn (Winyé), lee_Latn (Lyélé), sld_Latn (Sissala), soy_Latn (Miyobe), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A</td>
<td align="left">blo_Latn (Anii), tcd_Latn (Tafi) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1</td>
<td align="left">blo_Latn (Anii), tcd_Latn (Tafi) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to AE</td>
<td align="left">tik_Latn (Tikar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to eng</td>
<td align="left">tik_Latn (Tikar), mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
<td align="left">tik_Latn (Tikar), mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to ae</td>
<td align="left">tik_Latn (Tikar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01DD</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01DD</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018E</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018E</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to V</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to v</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to v</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to V</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to umacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to amacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Umacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Amacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Imacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0327</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0327</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to imacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to R</td>
<td align="left">dno_Latn (Ndrulo), kyq_Latn (Kenga) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to r</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to R</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to s</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to r</td>
<td align="left">dno_Latn (Ndrulo), kyq_Latn (Kenga) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to S</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to b</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to B</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to l</td>
<td align="left">bud_Latn (Ntcham) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to B</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to L</td>
<td align="left">bud_Latn (Ntcham) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to b</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Idieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to edieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Edieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to udieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to idieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Udieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268</td>
<td align="left">agq_Latn (Aghem) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0197</td>
<td align="left">agq_Latn (Aghem) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7AE</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EA1</td>
<td align="left">abn_Latn (Abua) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EA0</td>
<td align="left">abn_Latn (Abua) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EA1</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EA0</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Idieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to udieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to idieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Udieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Icircumflex</td>
<td align="left">vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to icircumflex</td>
<td align="left">vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to Eng</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to eng</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to G</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to g</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0289</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0268</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0197</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0244</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EA1</td>
<td align="left">avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EA0</td>
<td align="left">avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Agrave</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Amacron</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), wok_Latn (Longto), jgo_Latn (Ngomba), gov_Latn (Goo) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), wok_Latn (Longto), jgo_Latn (Ngomba) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), kss_Latn (Southern Kisi), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), kss_Latn (Southern Kisi), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E75</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E74</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E75</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E74</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E75</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E74</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to C</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni035F to T</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to c</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to p</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to P</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni035F to t</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to H</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to nacute</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Nacute</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01F9</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01F8</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to m</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), tcd_Latn (Tafi), mwm_Latn (Sar), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to M</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), tcd_Latn (Tafi), mwm_Latn (Sar), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to n</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), ann_Latn (Obolo), mwm_Latn (Sar), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to N</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), ann_Latn (Obolo), mwm_Latn (Sar), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to r</td>
<td align="left">kyq_Latn (Kenga), mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to R</td>
<td align="left">kyq_Latn (Kenga), mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to m</td>
<td align="left">ikw_Latn (Ikwere) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to M</td>
<td align="left">ikw_Latn (Ikwere) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019D</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019D</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to a</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to A</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to atilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Atilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to e</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to E</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EBD</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EBC</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0269</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0196</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0269</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0196</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to tildecomb</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to o</td>
<td align="left">tcd_Latn (Tafi), kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to O</td>
<td align="left">tcd_Latn (Tafi), kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to o</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to O</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to otilde</td>
<td align="left">tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Otilde</td>
<td align="left">tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0254</td>
<td align="left">tcd_Latn (Tafi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0186</td>
<td align="left">tcd_Latn (Tafi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to tildecomb</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to u</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to U</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to Utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A</td>
<td align="left">tcd_Latn (Tafi) and biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1</td>
<td align="left">tcd_Latn (Tafi) and biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E2D</td>
<td align="left">mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to w</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E2C</td>
<td align="left">mwm_Latn (Sar), ntm_Latn (Nateni) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E1A</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to omacron</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E2D</td>
<td align="left">mwm_Latn (Sar), ntm_Latn (Nateni) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to oacute</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Omacron</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E2C</td>
<td align="left">mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to W</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E1B</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Oacute</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to otilde</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni1EBC</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Otilde</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni1EBD</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to a</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to A</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to a</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to A</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to e</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to E</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to e</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to E</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni025B</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0190</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni025B</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0190</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to i</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to I</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to i</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to I</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to eng</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Eng</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to o</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to O</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0254</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0186</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0254</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0186</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to u</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to U</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to u</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to U</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EBC</td>
<td align="left">lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EBC</td>
<td align="left">lee_Latn (Lyélé) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EBD</td>
<td align="left">lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EBD</td>
<td align="left">lee_Latn (Lyélé) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Iacute</td>
<td align="left">kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to iacute</td>
<td align="left">kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E2C</td>
<td align="left">ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E2D</td>
<td align="left">ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to L</td>
<td align="left">wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to l</td>
<td align="left">wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0251</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Udieresis</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to udieresis</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0289</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0197</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0244</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0324 to W</td>
<td align="left">fan_Latn (Fang) and mdt_Latn (Mbere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0324 to w</td>
<td align="left">fan_Latn (Fang) and mdt_Latn (Mbere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to OE</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to OE</td>
<td align="left">ozm_Latn (Koonzime) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to OE</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe</td>
<td align="left">ozm_Latn (Koonzime) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ꟈ, ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0325 to l</td>
<td align="left">csk_Latn (Jola-Kasa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0325 to L</td>
<td align="left">csk_Latn (Jola-Kasa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to b</td>
<td align="left">rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to B</td>
<td align="left">rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Adieresis</td>
<td align="left">mgd_Latn (Moru)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to adieresis</td>
<td align="left">mgd_Latn (Moru)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to T</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to t</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to d</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to D</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ɤ, Ɤ̀, Ɤ́, Ɤ̂</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to ograve</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Ograve</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to OE</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to i</td>
<td align="left">btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to I</td>
<td align="left">btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EBD</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EBC</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to otilde</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Otilde</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to Oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to O</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to i</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni025B</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to A</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0186</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to I</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to e</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to o</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0254</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to u</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to U</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni025B</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0190</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to a</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0190</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to E</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to aogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Aogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0259</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Iogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Uogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Greek_Expert glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">No variant glyphs were found for uni0181</td>
<td align="left">dnj_Latn (Dan) and lom_Latn (Loma, Liberia)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Amo</td>
<td align="left">amo_Latn (Amo)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Koro</td>
<td align="left">kfo_Latn (Koro)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni028B</td>
<td align="left">tod_Latn (Toma)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01B2</td>
<td align="left">tod_Latn (Toma)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Seki</td>
<td align="left">syi_Latn (Seki)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Mina</td>
<td align="left">hna_Latn (Mina)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ⓐ, ⓐ</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Mbunga</td>
<td align="left">mgy_Latn (Mbunga)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Eastern Gurung, Latin</td>
<td align="left">ggn_Latn (Eastern Gurung, Latin)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01A9</td>
<td align="left">gaa_Latn (Ga)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01B7</td>
<td align="left">gaa_Latn (Ga)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Atsam</td>
<td align="left">cch_Latn (Atsam)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2010 Google Inc. All Rights Reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 🔥 **FAIL** <p>Tinos Regular: OS/2 sTypoAscender is 1420 when it should be 1825</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Tinos Regular: OS/2 sTypoDescender is -442 when it should be -443</p>
 [code: bad-typo-descender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671), uniA672 (U+A672), uniFE20 (U+FE20), uniFE21 (U+FE21), uniFE27 (U+FE27) and uniFE28 (U+FE28)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: hyphen	Contours detected: 1	Expected: 0

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni01EA	Contours detected: 3	Expected: 2

- Glyph name: uni01EB	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni023A	Contours detected: 4	Expected: 3

- Glyph name: uni023E	Contours detected: 3	Expected: 2

- Glyph name: uni0246	Contours detected: 2	Expected: 3

- Glyph name: uni0247	Contours detected: 3	Expected: 4

- Glyph name: uni04B5	Contours detected: 2	Expected: 1

- Glyph name: uni1D4D	Contours detected: 2	Expected: 3

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uni204B	Contours detected: 1	Expected: 2

- Glyph name: uni205F	Contours detected: 15	Expected: 0

- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

- Glyph name: uni210A	Contours detected: 3	Expected: 2

- Glyph name: uni210D	Contours detected: 3	Expected: 2

- Glyph name: uni2119	Contours detected: 4	Expected: 2

- Glyph name: uni211A	Contours detected: 5	Expected: 3

- Glyph name: uni211D	Contours detected: 5	Expected: 3

- Glyph name: uni2E18	Contours detected: 3	Expected: 2

- Glyph name: uniFEFF	Contours detected: 19	Expected: 0

- Glyph name: uniFFFC	Contours detected: 16	Expected: 22

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: uni01EC	Contours detected: 4	Expected: 3

- Glyph name: uni01ED	Contours detected: 4	Expected: 3

- Glyph name: uni0228	Contours detected: 2	Expected: 1

- Glyph name: uni0229	Contours detected: 3	Expected: 2

- Glyph name: uni023A	Contours detected: 4	Expected: 3

- Glyph name: uni023E	Contours detected: 3	Expected: 2

- Glyph name: uni0246	Contours detected: 2	Expected: 3

- Glyph name: uni0247	Contours detected: 3	Expected: 4

- Glyph name: uni04B5	Contours detected: 2	Expected: 1

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni1E1C	Contours detected: 3	Expected: 2

- Glyph name: uni1E1D	Contours detected: 4	Expected: 3

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uni204B	Contours detected: 1	Expected: 2

- Glyph name: uni205F	Contours detected: 15	Expected: 0

- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

- Glyph name: uni210A	Contours detected: 3	Expected: 2

- Glyph name: uni210D	Contours detected: 3	Expected: 2

- Glyph name: uni2119	Contours detected: 4	Expected: 2

- Glyph name: uni211A	Contours detected: 5	Expected: 3

- Glyph name: uni211D	Contours detected: 5	Expected: 3

- Glyph name: uni2E18	Contours detected: 3	Expected: 2

- Glyph name: uniFEFF	Contours detected: 19	Expected: 0

- Glyph name: uniFFFC	Contours detected: 16	Expected: 22

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 1167 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 1241:
logicalnot, minus</p>
<p>Width = 1124:
plusminus, divide, lessequal, approxequal, notequal, greaterequal</p>
<p>Width = 2005:
orthogonal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#typoascender-exceeds-Agrave">typoascender_exceeds_Agrave</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2.sTypoAscender value should be greater than 1757, but got 1387 instead</p>
 [code: typoAscender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Eng.alt1

- Eng.alt2

- Eng.alt3

- Lcommaaccent.loclMAH

- Ncommaaccent.loclMAH

- Ohm

- UNI2206

- acute.alt1

- acute.alt2

- acute.alt3

- acute.alt4

- acute.alt5

- alefdagesh

- aleflamedhatafsegol

- aleflamedsegol

- aleflamedtsere

- alternativelamed

- bari.dotless

- breve.alt1

- breve.cyr

- circumflex.alt1

- dotbelow.alt1

- dotbelow.alt10

- dotbelow.alt11

- dotbelow.alt12

- dotbelow.alt13

- dotbelow.alt14

- dotbelow.alt15

- dotbelow.alt2

- dotbelow.alt3

- dotbelow.alt4

- dotbelow.alt5

- dotbelow.alt6

- dotbelow.alt7

- dotbelow.alt8

- dotbelow.alt9

- dotlessi.alt1

- dottediacute

- eight.alt

- finalkafqamats

- finalkafsheva

- five.alt

- four.alt

- glyph3289

- grave.alt1

- grave.alt2

- grave.alt3

- grave.alt4

- grave.alt5

- hookabove.alt1

- hookabove.alt2

- hookabove.alt3

- hookabove.alt4

- hookabove.alt5

- lamedholam

- lamedholamdagesh

- lcommaaccent.loclMAH

- ncommaaccent.loclMAH

- nine.alt

- one.alt

- pi1

- radicalex.x

- seven.alt

- six.alt

- three.alt

- tilde.alt1

- tilde.alt10

- tilde.alt11

- tilde.alt12

- tilde.alt13

- tilde.alt2

- tilde.alt3

- tilde.alt4

- tilde.alt5

- tilde.alt6

- tilde.alt7

- tilde.alt8

- tilde.alt9

- two.alt

- uni00AD

- uni02E502E502E6

- uni02E502E502E7

- uni02E502E502E8

- uni02E502E502E9

- uni02E502E6

- uni02E502E602E5

- uni02E502E602E6

- uni02E502E602E7

- uni02E502E602E8

- uni02E502E602E9

- uni02E502E7

- uni02E502E702E5

- uni02E502E702E6

- uni02E502E702E7

- uni02E502E702E8

- uni02E502E702E9

- uni02E502E8

- uni02E502E802E5

- uni02E502E802E6

- uni02E502E802E7

- uni02E502E802E8

- uni02E502E802E9

- uni02E502E9

- uni02E502E902E5

- uni02E502E902E6

- uni02E502E902E7

- uni02E502E902E8

- uni02E502E902E9

- uni02E602E5

- uni02E602E502E5

- uni02E602E502E6

- uni02E602E502E7

- uni02E602E502E8

- uni02E602E502E9

- uni02E602E602E5

- uni02E602E602E7

- uni02E602E602E8

- uni02E602E602E9

- uni02E602E7

- uni02E602E702E5

- uni02E602E702E6

- uni02E602E702E7

- uni02E602E702E8

- uni02E602E702E9

- uni02E602E8

- uni02E602E802E5

- uni02E602E802E6

- uni02E602E802E7

- uni02E602E802E8

- uni02E602E802E9

- uni02E602E9

- uni02E602E902E5

- uni02E602E902E6

- uni02E602E902E7

- uni02E602E902E8

- uni02E602E902E9

- uni02E702E5

- uni02E702E502E5

- uni02E702E502E6

- uni02E702E502E7

- uni02E702E502E8

- uni02E702E502E9

- uni02E702E6

- uni02E702E602E5

- uni02E702E602E6

- uni02E702E602E7

- uni02E702E602E8

- uni02E702E602E9

- uni02E702E702E5

- uni02E702E702E6

- uni02E702E702E8

- uni02E702E702E9

- uni02E702E8

- uni02E702E802E5

- uni02E702E802E6

- uni02E702E802E7

- uni02E702E802E8

- uni02E702E802E9

- uni02E702E9

- uni02E702E902E5

- uni02E702E902E6

- uni02E702E902E7

- uni02E702E902E8

- uni02E702E902E9

- uni02E802E5

- uni02E802E502E5

- uni02E802E502E6

- uni02E802E502E7

- uni02E802E502E8

- uni02E802E502E9

- uni02E802E6

- uni02E802E602E5

- uni02E802E602E6

- uni02E802E602E7

- uni02E802E602E8

- uni02E802E602E9

- uni02E802E7

- uni02E802E702E5

- uni02E802E702E6

- uni02E802E702E7

- uni02E802E702E8

- uni02E802E702E9

- uni02E802E802E5

- uni02E802E802E6

- uni02E802E802E7

- uni02E802E802E9

- uni02E802E9

- uni02E802E902E5

- uni02E802E902E6

- uni02E802E902E7

- uni02E802E902E8

- uni02E802E902E9

- uni02E902E5

- uni02E902E502E5

- uni02E902E502E6

- uni02E902E502E7

- uni02E902E502E8

- uni02E902E502E9

- uni02E902E6

- uni02E902E602E5

- uni02E902E602E6

- uni02E902E602E7

- uni02E902E602E8

- uni02E902E602E9

- uni02E902E7

- uni02E902E702E5

- uni02E902E702E6

- uni02E902E702E7

- uni02E902E702E8

- uni02E902E702E9

- uni02E902E8

- uni02E902E802E5

- uni02E902E802E6

- uni02E902E802E7

- uni02E902E802E8

- uni02E902E802E9

- uni02E902E902E5

- uni02E902E902E6

- uni02E902E902E7

- uni02E902E902E8

- uni03B1030403130300

- uni03B1030403130301

- uni03B1030403140300

- uni03B1030403140301

- uni03B1030603130300

- uni03B1030603130301

- uni03B1030603140300

- uni03B1030603140301

- uni03B9030403130300

- uni03B9030403130301

- uni03B9030403140300

- uni03B9030403140301

- uni03B9030603130300

- uni03B9030603130301

- uni03B9030603140300

- uni03B9030603140301

- uni03B9030803040300

- uni03B9030803040301

- uni03B9030803060300

- uni03B9030803060301

- uni03C5030403130300

- uni03C5030403130301

- uni03C5030403140300

- uni03C5030403140301

- uni03C5030603130300

- uni03C5030603130301

- uni03C5030603140300

- uni03C5030603140301

- uni03C5030803040300

- uni03C5030803040301

- uni03C5030803060300

- uni03C5030803060301

- uni0431.loclSRB

- uni0433.loclSRB

- uni0434.loclSRB

- uni043F.loclSRB

- uni0441.loclSRB

- uni0448.loclSRB

- uni05B105BD

- uni05B205BD

- uni05B305BD

- zero.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/Tinos/googlefonts/ttf does not have an article.</p>
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
<li>U+02CD MODIFIER LETTER LOW MACRON: try adding lisu</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: elbasan, glagolitic, math, coptic, gothic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar</li>
<li>U+030E COMBINING DOUBLE VERTICAL LINE ABOVE: try adding ethiopic</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0310 COMBINING CANDRABINDU: try adding one of: math, sunuwar</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding one of: old-permic, todhri</li>
<li>U+0314 COMBINING REVERSED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0315 COMBINING COMMA ABOVE RIGHT: try adding math</li>
<li>U+0316 COMBINING GRAVE ACCENT BELOW: not included in any glyphset definition</li>
<li>U+0317 COMBINING ACUTE ACCENT BELOW: not included in any glyphset definition</li>
<li>U+0318 COMBINING LEFT TACK BELOW: not included in any glyphset definition</li>
<li>U+0319 COMBINING RIGHT TACK BELOW: not included in any glyphset definition</li>
<li>U+031A COMBINING LEFT ANGLE ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+031C COMBINING LEFT HALF RING BELOW: not included in any glyphset definition</li>
<li>U+031D COMBINING UP TACK BELOW: not included in any glyphset definition</li>
<li>U+031E COMBINING DOWN TACK BELOW: not included in any glyphset definition</li>
<li>U+031F COMBINING PLUS SIGN BELOW: not included in any glyphset definition</li>
<li>U+0320 COMBINING MINUS SIGN BELOW: try adding syriac</li>
<li>U+0321 COMBINING PALATALIZED HOOK BELOW: not included in any glyphset definition</li>
<li>U+0322 COMBINING RETROFLEX HOOK BELOW: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, duployan, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032A COMBINING BRIDGE BELOW: not included in any glyphset definition</li>
<li>U+032B COMBINING INVERTED DOUBLE ARCH BELOW: not included in any glyphset definition</li>
<li>U+032C COMBINING CARON BELOW: try adding math</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, thai, caucasian-albanian, gothic, sunuwar, tifinagh, syriac</li>
<li>U+0332 COMBINING LOW LINE: try adding math</li>
<li>U+0333 COMBINING DOUBLE LOW LINE: try adding math</li>
<li>U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+0339 COMBINING RIGHT HALF RING BELOW: not included in any glyphset definition</li>
<li>U+033A COMBINING INVERTED BRIDGE BELOW: try adding math</li>
<li>U+033B COMBINING SQUARE BELOW: not included in any glyphset definition</li>
<li>U+033C COMBINING SEAGULL BELOW: not included in any glyphset definition</li>
<li>U+033D COMBINING X ABOVE: not included in any glyphset definition</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+033F COMBINING DOUBLE OVERLINE: try adding coptic</li>
<li>U+0340 COMBINING GRAVE TONE MARK: not included in any glyphset definition</li>
<li>U+0341 COMBINING ACUTE TONE MARK: not included in any glyphset definition</li>
<li>U+0342 COMBINING GREEK PERISPOMENI: not included in any glyphset definition</li>
<li>U+0343 COMBINING GREEK KORONIS: not included in any glyphset definition</li>
<li>U+0344 COMBINING GREEK DIALYTIKA TONOS: not included in any glyphset definition</li>
<li>U+0345 COMBINING GREEK YPOGEGRAMMENI: not included in any glyphset definition</li>
<li>U+0346 COMBINING BRIDGE ABOVE: try adding math</li>
<li>U+0347 COMBINING EQUALS SIGN BELOW: not included in any glyphset definition</li>
<li>U+0348 COMBINING DOUBLE VERTICAL LINE BELOW: not included in any glyphset definition</li>
<li>U+0349 COMBINING LEFT ANGLE BELOW: not included in any glyphset definition</li>
<li>U+034A COMBINING NOT TILDE ABOVE: not included in any glyphset definition</li>
<li>U+034B COMBINING HOMOTHETIC ABOVE: not included in any glyphset definition</li>
<li>U+034C COMBINING ALMOST EQUAL TO ABOVE: not included in any glyphset definition</li>
<li>U+034D COMBINING LEFT RIGHT ARROW BELOW: try adding math</li>
<li>U+034E COMBINING UPWARDS ARROW BELOW: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+0350 COMBINING RIGHT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+0351 COMBINING LEFT HALF RING ABOVE: not included in any glyphset definition</li>
<li>U+0352 COMBINING FERMATA: not included in any glyphset definition</li>
<li>U+0353 COMBINING X BELOW: not included in any glyphset definition</li>
<li>U+0354 COMBINING LEFT ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0355 COMBINING RIGHT ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0356 COMBINING RIGHT ARROWHEAD AND UP ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0357 COMBINING RIGHT HALF RING ABOVE: not included in any glyphset definition</li>
<li>U+0358 COMBINING DOT ABOVE RIGHT: try adding osage</li>
<li>U+0359 COMBINING ASTERISK BELOW: not included in any glyphset definition</li>
<li>U+035A COMBINING DOUBLE RING BELOW: not included in any glyphset definition</li>
<li>U+035B COMBINING ZIGZAG ABOVE: not included in any glyphset definition</li>
<li>U+035C COMBINING DOUBLE BREVE BELOW: not included in any glyphset definition</li>
<li>U+035D COMBINING DOUBLE BREVE: not included in any glyphset definition</li>
<li>U+035E COMBINING DOUBLE MACRON: try adding one of: todhri, coptic, caucasian-albanian</li>
<li>U+035F COMBINING DOUBLE MACRON BELOW: not included in any glyphset definition</li>
<li>U+0360 COMBINING DOUBLE TILDE: not included in any glyphset definition</li>
<li>U+0361 COMBINING DOUBLE INVERTED BREVE: try adding coptic</li>
<li>U+0362 COMBINING DOUBLE RIGHTWARDS ARROW BELOW: not included in any glyphset definition</li>
<li>U+0363 COMBINING LATIN SMALL LETTER A: not included in any glyphset definition</li>
<li>U+0364 COMBINING LATIN SMALL LETTER E: not included in any glyphset definition</li>
<li>U+0365 COMBINING LATIN SMALL LETTER I: not included in any glyphset definition</li>
<li>U+0366 COMBINING LATIN SMALL LETTER O: not included in any glyphset definition</li>
<li>U+0367 COMBINING LATIN SMALL LETTER U: not included in any glyphset definition</li>
<li>U+0368 COMBINING LATIN SMALL LETTER C: not included in any glyphset definition</li>
<li>U+0369 COMBINING LATIN SMALL LETTER D: not included in any glyphset definition</li>
<li>U+036A COMBINING LATIN SMALL LETTER H: not included in any glyphset definition</li>
<li>U+036B COMBINING LATIN SMALL LETTER M: not included in any glyphset definition</li>
<li>U+036C COMBINING LATIN SMALL LETTER R: not included in any glyphset definition</li>
<li>U+036D COMBINING LATIN SMALL LETTER T: not included in any glyphset definition</li>
<li>U+036E COMBINING LATIN SMALL LETTER V: not included in any glyphset definition</li>
<li>U+036F COMBINING LATIN SMALL LETTER X: not included in any glyphset definition</li>
<li>U+1AB0 COMBINING DOUBLED CIRCUMFLEX ACCENT: not included in any glyphset definition</li>
<li>U+1AB1 COMBINING DIAERESIS-RING: not included in any glyphset definition</li>
<li>U+1AB2 COMBINING INFINITY: not included in any glyphset definition</li>
<li>U+1AB3 COMBINING DOWNWARDS ARROW: not included in any glyphset definition</li>
<li>U+1AB4 COMBINING TRIPLE DOT: not included in any glyphset definition</li>
<li>U+1AB5 COMBINING X-X BELOW: not included in any glyphset definition</li>
<li>U+1AB6 COMBINING WIGGLY LINE BELOW: not included in any glyphset definition</li>
<li>U+1AB7 COMBINING OPEN MARK BELOW: not included in any glyphset definition</li>
<li>U+1AB8 COMBINING DOUBLE OPEN MARK BELOW: not included in any glyphset definition</li>
<li>U+1AB9 COMBINING LIGHT CENTRALIZATION STROKE BELOW: not included in any glyphset definition</li>
<li>U+1ABA COMBINING STRONG CENTRALIZATION STROKE BELOW: not included in any glyphset definition</li>
<li>U+1ABB COMBINING PARENTHESES ABOVE: not included in any glyphset definition</li>
<li>U+1ABC COMBINING DOUBLE PARENTHESES ABOVE: not included in any glyphset definition</li>
<li>U+1ABD COMBINING PARENTHESES BELOW: not included in any glyphset definition</li>
<li>U+1ABE COMBINING PARENTHESES OVERLAY: not included in any glyphset definition</li>
<li>U+1DC0 COMBINING DOTTED GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+1DC1 COMBINING DOTTED ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+1DC2 COMBINING SNAKE BELOW: not included in any glyphset definition</li>
<li>U+1DC3 COMBINING SUSPENSION MARK: not included in any glyphset definition</li>
<li>U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition</li>
<li>U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition</li>
<li>U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition</li>
<li>U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition</li>
<li>U+1DC8 COMBINING GRAVE-ACUTE-GRAVE: not included in any glyphset definition</li>
<li>U+1DC9 COMBINING ACUTE-GRAVE-ACUTE: not included in any glyphset definition</li>
<li>U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition</li>
<li>U+1DCB COMBINING BREVE-MACRON: not included in any glyphset definition</li>
<li>U+1DCC COMBINING MACRON-BREVE: not included in any glyphset definition</li>
<li>U+1DCD COMBINING DOUBLE CIRCUMFLEX ABOVE: try adding coptic</li>
<li>U+1DCE COMBINING OGONEK ABOVE: not included in any glyphset definition</li>
<li>U+1DCF COMBINING ZIGZAG BELOW: not included in any glyphset definition</li>
<li>U+1DD0 COMBINING IS BELOW: not included in any glyphset definition</li>
<li>U+1DD1 COMBINING UR ABOVE: not included in any glyphset definition</li>
<li>U+1DD2 COMBINING US ABOVE: not included in any glyphset definition</li>
<li>U+1DD3 COMBINING LATIN SMALL LETTER FLATTENED OPEN A ABOVE: not included in any glyphset definition</li>
<li>U+1DD4 COMBINING LATIN SMALL LETTER AE: not included in any glyphset definition</li>
<li>U+1DD5 COMBINING LATIN SMALL LETTER AO: not included in any glyphset definition</li>
<li>U+1DD6 COMBINING LATIN SMALL LETTER AV: not included in any glyphset definition</li>
<li>U+1DD7 COMBINING LATIN SMALL LETTER C CEDILLA: not included in any glyphset definition</li>
<li>U+1DD8 COMBINING LATIN SMALL LETTER INSULAR D: not included in any glyphset definition</li>
<li>U+1DD9 COMBINING LATIN SMALL LETTER ETH: not included in any glyphset definition</li>
<li>U+1DDA COMBINING LATIN SMALL LETTER G: not included in any glyphset definition</li>
<li>U+1DDB COMBINING LATIN LETTER SMALL CAPITAL G: not included in any glyphset definition</li>
<li>U+1DDC COMBINING LATIN SMALL LETTER K: not included in any glyphset definition</li>
<li>U+1DDD COMBINING LATIN SMALL LETTER L: not included in any glyphset definition</li>
<li>U+1DDE COMBINING LATIN LETTER SMALL CAPITAL L: not included in any glyphset definition</li>
<li>U+1DDF COMBINING LATIN LETTER SMALL CAPITAL M: not included in any glyphset definition</li>
<li>U+1DE0 COMBINING LATIN SMALL LETTER N: not included in any glyphset definition</li>
<li>U+1DE1 COMBINING LATIN LETTER SMALL CAPITAL N: not included in any glyphset definition</li>
<li>U+1DE2 COMBINING LATIN LETTER SMALL CAPITAL R: not included in any glyphset definition</li>
<li>U+1DE3 COMBINING LATIN SMALL LETTER R ROTUNDA: not included in any glyphset definition</li>
<li>U+1DE4 COMBINING LATIN SMALL LETTER S: not included in any glyphset definition</li>
<li>U+1DE5 COMBINING LATIN SMALL LETTER LONG S: not included in any glyphset definition</li>
<li>U+1DE6 COMBINING LATIN SMALL LETTER Z: not included in any glyphset definition</li>
<li>U+1DE7 COMBINING LATIN SMALL LETTER ALPHA: not included in any glyphset definition</li>
<li>U+1DE8 COMBINING LATIN SMALL LETTER B: not included in any glyphset definition</li>
<li>U+1DE9 COMBINING LATIN SMALL LETTER BETA: not included in any glyphset definition</li>
<li>U+1DEA COMBINING LATIN SMALL LETTER SCHWA: not included in any glyphset definition</li>
<li>U+1DEB COMBINING LATIN SMALL LETTER F: not included in any glyphset definition</li>
<li>U+1DEC COMBINING LATIN SMALL LETTER L WITH DOUBLE MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+1DED COMBINING LATIN SMALL LETTER O WITH LIGHT CENTRALIZATION STROKE: not included in any glyphset definition</li>
<li>U+1DEE COMBINING LATIN SMALL LETTER P: not included in any glyphset definition</li>
<li>U+1DEF COMBINING LATIN SMALL LETTER ESH: not included in any glyphset definition</li>
<li>U+1DF0 COMBINING LATIN SMALL LETTER U WITH LIGHT CENTRALIZATION STROKE: not included in any glyphset definition</li>
<li>U+1DF1 COMBINING LATIN SMALL LETTER W: not included in any glyphset definition</li>
<li>U+1DF2 COMBINING LATIN SMALL LETTER A WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF3 COMBINING LATIN SMALL LETTER O WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF4 COMBINING LATIN SMALL LETTER U WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF5 COMBINING UP TACK ABOVE: not included in any glyphset definition</li>
<li>U+1DFB COMBINING DELETION MARK: try adding newa</li>
<li>U+1DFC COMBINING DOUBLE INVERTED BREVE BELOW: not included in any glyphset definition</li>
<li>U+1DFD COMBINING ALMOST EQUAL TO BELOW: not included in any glyphset definition</li>
<li>U+1DFE COMBINING LEFT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+1DFF COMBINING RIGHT ARROWHEAD AND DOWN ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, arabic, yi</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2016 DOUBLE VERTICAL LINE: try adding math</li>
<li>U+2017 DOUBLE LOW LINE: try adding math</li>
<li>U+201B SINGLE HIGH-REVERSED-9 QUOTATION MARK: try adding adlam</li>
<li>U+201F DOUBLE HIGH-REVERSED-9 QUOTATION MARK: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2023 TRIANGULAR BULLET: not included in any glyphset definition</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+2028 LINE SEPARATOR: not included in any glyphset definition</li>
<li>U+2029 PARAGRAPH SEPARATOR: not included in any glyphset definition</li>
<li>U+202A LEFT-TO-RIGHT EMBEDDING: not included in any glyphset definition</li>
<li>U+202B RIGHT-TO-LEFT EMBEDDING: not included in any glyphset definition</li>
<li>U+202C POP DIRECTIONAL FORMATTING: not included in any glyphset definition</li>
<li>U+202D LEFT-TO-RIGHT OVERRIDE: not included in any glyphset definition</li>
<li>U+202E RIGHT-TO-LEFT OVERRIDE: try adding tifinagh</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: phags-pa, yi, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2031 PER TEN THOUSAND SIGN: not included in any glyphset definition</li>
<li>U+2034 TRIPLE PRIME: try adding math</li>
<li>U+2035 REVERSED PRIME: try adding math</li>
<li>U+2036 REVERSED DOUBLE PRIME: try adding math</li>
<li>U+2037 REVERSED TRIPLE PRIME: try adding math</li>
<li>U+2038 CARET: try adding math</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+203C DOUBLE EXCLAMATION MARK: try adding math</li>
<li>U+203D INTERROBANG: not included in any glyphset definition</li>
<li>U+203E OVERLINE: not included in any glyphset definition</li>
<li>U+203F UNDERTIE: not included in any glyphset definition</li>
<li>U+2040 CHARACTER TIE: try adding math</li>
<li>U+2041 CARET INSERTION POINT: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+2043 HYPHEN BULLET: try adding math</li>
<li>U+2045 LEFT SQUARE BRACKET WITH QUILL: not included in any glyphset definition</li>
<li>U+2046 RIGHT SQUARE BRACKET WITH QUILL: not included in any glyphset definition</li>
<li>U+2047 DOUBLE QUESTION MARK: try adding math</li>
<li>U+2048 QUESTION EXCLAMATION MARK: try adding mongolian</li>
<li>U+2049 EXCLAMATION QUESTION MARK: try adding mongolian</li>
<li>U+204A TIRONIAN SIGN ET: not included in any glyphset definition</li>
<li>U+204B REVERSED PILCROW SIGN: not included in any glyphset definition</li>
<li>U+204C BLACK LEFTWARDS BULLET: not included in any glyphset definition</li>
<li>U+204D BLACK RIGHTWARDS BULLET: not included in any glyphset definition</li>
<li>U+204E LOW ASTERISK: not included in any glyphset definition</li>
<li>U+204F REVERSED SEMICOLON: try adding one of: arabic, adlam</li>
<li>U+2050 CLOSE UP: try adding math</li>
<li>U+2051 TWO ASTERISKS ALIGNED VERTICALLY: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2053 SWUNG DASH: try adding coptic</li>
<li>U+2054 INVERTED UNDERTIE: not included in any glyphset definition</li>
<li>U+2055 FLOWER PUNCTUATION MARK: try adding syloti-nagri</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2057 QUADRUPLE PRIME: try adding math</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205A TWO DOT PUNCTUATION: try adding one of: lycian, old-hungarian, glagolitic, georgian, old-turkic, carian</li>
<li>U+205B FOUR DOT MARK: not included in any glyphset definition</li>
<li>U+205C DOTTED CROSS: not included in any glyphset definition</li>
<li>U+205D TRICOLON: try adding one of: old-hungarian, carian, meroitic-hieroglyphs, meroitic</li>
<li>U+205E VERTICAL FOUR DOTS: try adding old-hungarian</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2060 WORD JOINER: not included in any glyphset definition</li>
<li>U+2061 FUNCTION APPLICATION: not included in any glyphset definition</li>
<li>U+2062 INVISIBLE TIMES: not included in any glyphset definition</li>
<li>U+2063 INVISIBLE SEPARATOR: not included in any glyphset definition</li>
<li>U+2064 INVISIBLE PLUS: not included in any glyphset definition</li>
<li>U+2066 LEFT-TO-RIGHT ISOLATE: not included in any glyphset definition</li>
<li>U+2067 RIGHT-TO-LEFT ISOLATE: not included in any glyphset definition</li>
<li>U+2068 FIRST STRONG ISOLATE: not included in any glyphset definition</li>
<li>U+2069 POP DIRECTIONAL ISOLATE: not included in any glyphset definition</li>
<li>U+206A INHIBIT SYMMETRIC SWAPPING: not included in any glyphset definition</li>
<li>U+206B ACTIVATE SYMMETRIC SWAPPING: not included in any glyphset definition</li>
<li>U+206C INHIBIT ARABIC FORM SHAPING: not included in any glyphset definition</li>
<li>U+206D ACTIVATE ARABIC FORM SHAPING: not included in any glyphset definition</li>
<li>U+206E NATIONAL DIGIT SHAPES: not included in any glyphset definition</li>
<li>U+206F NOMINAL DIGIT SHAPES: not included in any glyphset definition</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2071 SUPERSCRIPT LATIN SMALL LETTER I: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+207A SUPERSCRIPT PLUS SIGN: try adding math</li>
<li>U+207B SUPERSCRIPT MINUS: try adding math</li>
<li>U+207C SUPERSCRIPT EQUALS SIGN: try adding math</li>
<li>U+207D SUPERSCRIPT LEFT PARENTHESIS: try adding math</li>
<li>U+207E SUPERSCRIPT RIGHT PARENTHESIS: try adding math</li>
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
<li>U+208A SUBSCRIPT PLUS SIGN: try adding math</li>
<li>U+208B SUBSCRIPT MINUS: try adding math</li>
<li>U+208C SUBSCRIPT EQUALS SIGN: try adding math</li>
<li>U+208D SUBSCRIPT LEFT PARENTHESIS: try adding math</li>
<li>U+208E SUBSCRIPT RIGHT PARENTHESIS: try adding math</li>
<li>U+2090 LATIN SUBSCRIPT SMALL LETTER A: try adding math</li>
<li>U+2091 LATIN SUBSCRIPT SMALL LETTER E: try adding math</li>
<li>U+2092 LATIN SUBSCRIPT SMALL LETTER O: try adding math</li>
<li>U+2093 LATIN SUBSCRIPT SMALL LETTER X: try adding math</li>
<li>U+2094 LATIN SUBSCRIPT SMALL LETTER SCHWA: try adding math</li>
<li>U+2095 LATIN SUBSCRIPT SMALL LETTER H: try adding math</li>
<li>U+2096 LATIN SUBSCRIPT SMALL LETTER K: try adding math</li>
<li>U+2097 LATIN SUBSCRIPT SMALL LETTER L: try adding math</li>
<li>U+2098 LATIN SUBSCRIPT SMALL LETTER M: try adding math</li>
<li>U+2099 LATIN SUBSCRIPT SMALL LETTER N: try adding math</li>
<li>U+209A LATIN SUBSCRIPT SMALL LETTER P: try adding math</li>
<li>U+209B LATIN SUBSCRIPT SMALL LETTER S: try adding math</li>
<li>U+209C LATIN SUBSCRIPT SMALL LETTER T: try adding math</li>
<li>U+20F0 COMBINING ASTERISK ABOVE: try adding one of: grantha, devanagari</li>
<li>U+2100 ACCOUNT OF: try adding math</li>
<li>U+2101 ADDRESSED TO THE SUBJECT: try adding math</li>
<li>U+2102 DOUBLE-STRUCK CAPITAL C: try adding math</li>
<li>U+2103 DEGREE CELSIUS: try adding math</li>
<li>U+2104 CENTRE LINE SYMBOL: try adding math</li>
<li>U+2105 CARE OF: try adding math</li>
<li>U+2106 CADA UNA: try adding math</li>
<li>U+2107 EULER CONSTANT: try adding math</li>
<li>U+2108 SCRUPLE: try adding math</li>
<li>U+2109 DEGREE FAHRENHEIT: try adding math</li>
<li>U+210A SCRIPT SMALL G: try adding math</li>
<li>U+210B SCRIPT CAPITAL H: try adding math</li>
<li>U+210C BLACK-LETTER CAPITAL H: try adding math</li>
<li>U+210D DOUBLE-STRUCK CAPITAL H: try adding math</li>
<li>U+210E PLANCK CONSTANT: try adding math</li>
<li>U+210F PLANCK CONSTANT OVER TWO PI: try adding math</li>
<li>U+2110 SCRIPT CAPITAL I: try adding math</li>
<li>U+2111 BLACK-LETTER CAPITAL I: try adding math</li>
<li>U+2112 SCRIPT CAPITAL L: try adding math</li>
<li>U+2114 L B BAR SYMBOL: try adding math</li>
<li>U+2115 DOUBLE-STRUCK CAPITAL N: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2118 SCRIPT CAPITAL P: try adding math</li>
<li>U+2119 DOUBLE-STRUCK CAPITAL P: try adding math</li>
<li>U+211A DOUBLE-STRUCK CAPITAL Q: try adding math</li>
<li>U+211B SCRIPT CAPITAL R: try adding math</li>
<li>U+211C BLACK-LETTER CAPITAL R: try adding math</li>
<li>U+211D DOUBLE-STRUCK CAPITAL R: try adding math</li>
<li>U+211E PRESCRIPTION TAKE: try adding math</li>
<li>U+211F RESPONSE: try adding math</li>
<li>U+2120 SERVICE MARK: try adding math</li>
<li>U+2121 TELEPHONE SIGN: try adding math</li>
<li>U+2123 VERSICLE: try adding math</li>
<li>U+2124 DOUBLE-STRUCK CAPITAL Z: try adding math</li>
<li>U+2125 OUNCE SIGN: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2127 INVERTED OHM SIGN: try adding math</li>
<li>U+2128 BLACK-LETTER CAPITAL Z: try adding math</li>
<li>U+2129 TURNED GREEK SMALL LETTER IOTA: try adding math</li>
<li>U+212A KELVIN SIGN: try adding math</li>
<li>U+212B ANGSTROM SIGN: try adding math</li>
<li>U+212C SCRIPT CAPITAL B: try adding math</li>
<li>U+212D BLACK-LETTER CAPITAL C: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+212F SCRIPT SMALL E: try adding math</li>
<li>U+2130 SCRIPT CAPITAL E: try adding math</li>
<li>U+2131 SCRIPT CAPITAL F: try adding math</li>
<li>U+2132 TURNED CAPITAL F: try adding math</li>
<li>U+2133 SCRIPT CAPITAL M: try adding math</li>
<li>U+2134 SCRIPT SMALL O: try adding math</li>
<li>U+2135 ALEF SYMBOL: try adding math</li>
<li>U+2136 BET SYMBOL: try adding math</li>
<li>U+2137 GIMEL SYMBOL: try adding math</li>
<li>U+2138 DALET SYMBOL: try adding math</li>
<li>U+2139 INFORMATION SOURCE: try adding math</li>
<li>U+213A ROTATED CAPITAL Q: try adding math</li>
<li>U+213B FACSIMILE SIGN: try adding math</li>
<li>U+213C DOUBLE-STRUCK SMALL PI: try adding math</li>
<li>U+213D DOUBLE-STRUCK SMALL GAMMA: try adding math</li>
<li>U+213E DOUBLE-STRUCK CAPITAL GAMMA: try adding math</li>
<li>U+213F DOUBLE-STRUCK CAPITAL PI: try adding math</li>
<li>U+2140 DOUBLE-STRUCK N-ARY SUMMATION: try adding math</li>
<li>U+2141 TURNED SANS-SERIF CAPITAL G: try adding math</li>
<li>U+2142 TURNED SANS-SERIF CAPITAL L: try adding math</li>
<li>U+2143 REVERSED SANS-SERIF CAPITAL L: try adding math</li>
<li>U+2144 TURNED SANS-SERIF CAPITAL Y: try adding math</li>
<li>U+2145 DOUBLE-STRUCK ITALIC CAPITAL D: try adding math</li>
<li>U+2146 DOUBLE-STRUCK ITALIC SMALL D: try adding math</li>
<li>U+2147 DOUBLE-STRUCK ITALIC SMALL E: try adding math</li>
<li>U+2148 DOUBLE-STRUCK ITALIC SMALL I: try adding math</li>
<li>U+2149 DOUBLE-STRUCK ITALIC SMALL J: try adding math</li>
<li>U+214A PROPERTY LINE: try adding math</li>
<li>U+214B TURNED AMPERSAND: try adding math</li>
<li>U+214C PER SIGN: try adding math</li>
<li>U+214D AKTIESELSKAB: try adding math</li>
<li>U+214E TURNED SMALL F: try adding math</li>
<li>U+214F SYMBOL FOR SAMARITAN SOURCE: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2184 LATIN SMALL LETTER REVERSED C: not included in any glyphset definition</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+21A8 UP DOWN ARROW WITH BASE: try adding math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, math, yi, tai-tham</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+221F RIGHT ANGLE: try adding math</li>
<li>U+2229 INTERSECTION: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2261 IDENTICAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+2302 HOUSE: try adding symbols</li>
<li>U+2310 REVERSED NOT SIGN: try adding math</li>
<li>U+2320 TOP HALF INTEGRAL: try adding math</li>
<li>U+2321 BOTTOM HALF INTEGRAL: try adding math</li>
<li>U+2500 BOX DRAWINGS LIGHT HORIZONTAL: try adding symbols2</li>
<li>U+2502 BOX DRAWINGS LIGHT VERTICAL: try adding symbols2</li>
<li>U+250C BOX DRAWINGS LIGHT DOWN AND RIGHT: try adding symbols2</li>
<li>U+2510 BOX DRAWINGS LIGHT DOWN AND LEFT: try adding symbols2</li>
<li>U+2514 BOX DRAWINGS LIGHT UP AND RIGHT: try adding symbols2</li>
<li>U+2518 BOX DRAWINGS LIGHT UP AND LEFT: try adding symbols2</li>
<li>U+251C BOX DRAWINGS LIGHT VERTICAL AND RIGHT: try adding symbols2</li>
<li>U+2524 BOX DRAWINGS LIGHT VERTICAL AND LEFT: try adding symbols2</li>
<li>U+252C BOX DRAWINGS LIGHT DOWN AND HORIZONTAL: try adding symbols2</li>
<li>U+2534 BOX DRAWINGS LIGHT UP AND HORIZONTAL: try adding symbols2</li>
<li>U+253C BOX DRAWINGS LIGHT VERTICAL AND HORIZONTAL: try adding symbols2</li>
<li>U+2550 BOX DRAWINGS DOUBLE HORIZONTAL: try adding symbols2</li>
<li>U+2551 BOX DRAWINGS DOUBLE VERTICAL: try adding symbols2</li>
<li>U+2552 BOX DRAWINGS DOWN SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+2553 BOX DRAWINGS DOWN DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+2554 BOX DRAWINGS DOUBLE DOWN AND RIGHT: try adding symbols2</li>
<li>U+2555 BOX DRAWINGS DOWN SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+2556 BOX DRAWINGS DOWN DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+2557 BOX DRAWINGS DOUBLE DOWN AND LEFT: try adding symbols2</li>
<li>U+2558 BOX DRAWINGS UP SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+2559 BOX DRAWINGS UP DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+255A BOX DRAWINGS DOUBLE UP AND RIGHT: try adding symbols2</li>
<li>U+255B BOX DRAWINGS UP SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+255C BOX DRAWINGS UP DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+255D BOX DRAWINGS DOUBLE UP AND LEFT: try adding symbols2</li>
<li>U+255E BOX DRAWINGS VERTICAL SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+255F BOX DRAWINGS VERTICAL DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+2560 BOX DRAWINGS DOUBLE VERTICAL AND RIGHT: try adding symbols2</li>
<li>U+2561 BOX DRAWINGS VERTICAL SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+2562 BOX DRAWINGS VERTICAL DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+2563 BOX DRAWINGS DOUBLE VERTICAL AND LEFT: try adding symbols2</li>
<li>U+2564 BOX DRAWINGS DOWN SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+2565 BOX DRAWINGS DOWN DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+2566 BOX DRAWINGS DOUBLE DOWN AND HORIZONTAL: try adding symbols2</li>
<li>U+2567 BOX DRAWINGS UP SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+2568 BOX DRAWINGS UP DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+2569 BOX DRAWINGS DOUBLE UP AND HORIZONTAL: try adding symbols2</li>
<li>U+256A BOX DRAWINGS VERTICAL SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+256B BOX DRAWINGS VERTICAL DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+256C BOX DRAWINGS DOUBLE VERTICAL AND HORIZONTAL: try adding symbols2</li>
<li>U+2580 UPPER HALF BLOCK: try adding symbols2</li>
<li>U+2584 LOWER HALF BLOCK: try adding symbols2</li>
<li>U+2588 FULL BLOCK: try adding symbols2</li>
<li>U+258C LEFT HALF BLOCK: try adding symbols2</li>
<li>U+2590 RIGHT HALF BLOCK: try adding symbols2</li>
<li>U+2591 LIGHT SHADE: try adding symbols2</li>
<li>U+2592 MEDIUM SHADE: try adding symbols2</li>
<li>U+2593 DARK SHADE: try adding symbols2</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25AA BLACK SMALL SQUARE: try adding symbols</li>
<li>U+25AB WHITE SMALL SQUARE: try adding symbols</li>
<li>U+25AC BLACK RECTANGLE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BA BLACK RIGHT-POINTING POINTER: try adding symbols</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C4 BLACK LEFT-POINTING POINTER: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+25D8 INVERSE BULLET: try adding symbols</li>
<li>U+25D9 INVERSE WHITE CIRCLE: try adding symbols</li>
<li>U+25E6 WHITE BULLET: try adding symbols</li>
<li>U+263A WHITE SMILING FACE: try adding symbols</li>
<li>U+263B BLACK SMILING FACE: try adding symbols</li>
<li>U+263C WHITE SUN WITH RAYS: try adding symbols</li>
<li>U+2640 FEMALE SIGN: try adding symbols</li>
<li>U+2642 MALE SIGN: try adding symbols</li>
<li>U+2660 BLACK SPADE SUIT: try adding symbols</li>
<li>U+2663 BLACK CLUB SUIT: try adding symbols</li>
<li>U+2665 BLACK HEART SUIT: try adding symbols</li>
<li>U+2666 BLACK DIAMOND SUIT: try adding symbols</li>
<li>U+266A EIGHTH NOTE: try adding one of: symbols, music</li>
<li>U+266B BEAMED EIGHTH NOTES: try adding one of: symbols, music</li>
<li>U+266F MUSIC SHARP SIGN: try adding one of: symbols, music, math</li>
<li>U+2E00 RIGHT ANGLE SUBSTITUTION MARKER: not included in any glyphset definition</li>
<li>U+2E01 RIGHT ANGLE DOTTED SUBSTITUTION MARKER: not included in any glyphset definition</li>
<li>U+2E02 LEFT SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E03 RIGHT SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E04 LEFT DOTTED SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E05 RIGHT DOTTED SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E06 RAISED INTERPOLATION MARKER: not included in any glyphset definition</li>
<li>U+2E07 RAISED DOTTED INTERPOLATION MARKER: not included in any glyphset definition</li>
<li>U+2E08 DOTTED TRANSPOSITION MARKER: not included in any glyphset definition</li>
<li>U+2E09 LEFT TRANSPOSITION BRACKET: not included in any glyphset definition</li>
<li>U+2E0A RIGHT TRANSPOSITION BRACKET: not included in any glyphset definition</li>
<li>U+2E0B RAISED SQUARE: not included in any glyphset definition</li>
<li>U+2E0C LEFT RAISED OMISSION BRACKET: not included in any glyphset definition</li>
<li>U+2E0D RIGHT RAISED OMISSION BRACKET: not included in any glyphset definition</li>
<li>U+2E0E EDITORIAL CORONIS: not included in any glyphset definition</li>
<li>U+2E0F PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E10 FORKED PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E11 REVERSED FORKED PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E12 HYPODIASTOLE: not included in any glyphset definition</li>
<li>U+2E13 DOTTED OBELOS: not included in any glyphset definition</li>
<li>U+2E14 DOWNWARDS ANCORA: not included in any glyphset definition</li>
<li>U+2E15 UPWARDS ANCORA: not included in any glyphset definition</li>
<li>U+2E16 DOTTED RIGHT-POINTING ANGLE: not included in any glyphset definition</li>
<li>U+2E17 DOUBLE OBLIQUE HYPHEN: try adding coptic</li>
<li>U+2E18 INVERTED INTERROBANG: not included in any glyphset definition</li>
<li>U+2E19 PALM BRANCH: not included in any glyphset definition</li>
<li>U+2E1A HYPHEN WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+2E1B TILDE WITH RING ABOVE: not included in any glyphset definition</li>
<li>U+2E1C LEFT LOW PARAPHRASE BRACKET: try adding nko</li>
<li>U+2E1D RIGHT LOW PARAPHRASE BRACKET: try adding nko</li>
<li>U+2E1E TILDE WITH DOT ABOVE: not included in any glyphset definition</li>
<li>U+2E1F TILDE WITH DOT BELOW: not included in any glyphset definition</li>
<li>U+2E20 LEFT VERTICAL BAR WITH QUILL: not included in any glyphset definition</li>
<li>U+2E21 RIGHT VERTICAL BAR WITH QUILL: not included in any glyphset definition</li>
<li>U+2E22 TOP LEFT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E23 TOP RIGHT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E24 BOTTOM LEFT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E25 BOTTOM RIGHT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E26 LEFT SIDEWAYS U BRACKET: not included in any glyphset definition</li>
<li>U+2E27 RIGHT SIDEWAYS U BRACKET: not included in any glyphset definition</li>
<li>U+2E28 LEFT DOUBLE PARENTHESIS: try adding adlam</li>
<li>U+2E29 RIGHT DOUBLE PARENTHESIS: try adding adlam</li>
<li>U+2E2A TWO DOTS OVER ONE DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2B ONE DOT OVER TWO DOTS PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2C SQUARED FOUR DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2D FIVE DOT MARK: not included in any glyphset definition</li>
<li>U+2E2E REVERSED QUESTION MARK: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E30 RING POINT: try adding one of: avestan, old-turkic</li>
<li>U+2E31 WORD SEPARATOR MIDDLE DOT: try adding one of: avestan, old-hungarian, kaithi, georgian, samaritan, carian, lydian</li>
<li>U+2E32 TURNED COMMA: not included in any glyphset definition</li>
<li>U+2E33 RAISED DOT: try adding coptic</li>
<li>U+2E34 RAISED COMMA: try adding coptic</li>
<li>U+2E35 TURNED SEMICOLON: not included in any glyphset definition</li>
<li>U+2E36 DAGGER WITH LEFT GUARD: not included in any glyphset definition</li>
<li>U+2E37 DAGGER WITH RIGHT GUARD: not included in any glyphset definition</li>
<li>U+2E38 TURNED DAGGER: not included in any glyphset definition</li>
<li>U+2E39 TOP HALF SECTION SIGN: not included in any glyphset definition</li>
<li>U+2E3A TWO-EM DASH: not included in any glyphset definition</li>
<li>U+2E3B THREE-EM DASH: not included in any glyphset definition</li>
<li>U+2E3C STENOGRAPHIC FULL STOP: try adding duployan</li>
<li>U+2E3D VERTICAL SIX DOTS: not included in any glyphset definition</li>
<li>U+2E3E WIGGLY VERTICAL LINE: not included in any glyphset definition</li>
<li>U+2E3F CAPITULUM: not included in any glyphset definition</li>
<li>U+2E40 DOUBLE HYPHEN: not included in any glyphset definition</li>
<li>U+2E41 REVERSED COMMA: try adding one of: arabic, old-hungarian, adlam</li>
<li>U+2E42 DOUBLE LOW-REVERSED-9 QUOTATION MARK: not included in any glyphset definition</li>
<li>U+A717 MODIFIER LETTER DOT VERTICAL BAR: not included in any glyphset definition</li>
<li>U+A718 MODIFIER LETTER DOT SLASH: not included in any glyphset definition</li>
<li>U+A719 MODIFIER LETTER DOT HORIZONTAL BAR: not included in any glyphset definition</li>
<li>U+A71A MODIFIER LETTER LOWER RIGHT CORNER ANGLE: not included in any glyphset definition</li>
<li>U+A71B MODIFIER LETTER RAISED UP ARROW: not included in any glyphset definition</li>
<li>U+A71C MODIFIER LETTER RAISED DOWN ARROW: not included in any glyphset definition</li>
<li>U+A71D MODIFIER LETTER RAISED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+A71E MODIFIER LETTER RAISED INVERTED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+A71F MODIFIER LETTER LOW INVERTED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+AB30 LATIN SMALL LETTER BARRED ALPHA: not included in any glyphset definition</li>
<li>U+AB31 LATIN SMALL LETTER A REVERSED-SCHWA: not included in any glyphset definition</li>
<li>U+AB32 LATIN SMALL LETTER BLACKLETTER E: not included in any glyphset definition</li>
<li>U+AB33 LATIN SMALL LETTER BARRED E: not included in any glyphset definition</li>
<li>U+AB34 LATIN SMALL LETTER E WITH FLOURISH: not included in any glyphset definition</li>
<li>U+AB35 LATIN SMALL LETTER LENIS F: not included in any glyphset definition</li>
<li>U+AB36 LATIN SMALL LETTER SCRIPT G WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB37 LATIN SMALL LETTER L WITH INVERTED LAZY S: not included in any glyphset definition</li>
<li>U+AB38 LATIN SMALL LETTER L WITH DOUBLE MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+AB39 LATIN SMALL LETTER L WITH MIDDLE RING: not included in any glyphset definition</li>
<li>U+AB3A LATIN SMALL LETTER M WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3B LATIN SMALL LETTER N WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3C LATIN SMALL LETTER ENG WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3D LATIN SMALL LETTER BLACKLETTER O: not included in any glyphset definition</li>
<li>U+AB3E LATIN SMALL LETTER BLACKLETTER O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB3F LATIN SMALL LETTER OPEN O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB40 LATIN SMALL LETTER INVERTED OE: not included in any glyphset definition</li>
<li>U+AB41 LATIN SMALL LETTER TURNED OE WITH STROKE: not included in any glyphset definition</li>
<li>U+AB42 LATIN SMALL LETTER TURNED OE WITH HORIZONTAL STROKE: not included in any glyphset definition</li>
<li>U+AB43 LATIN SMALL LETTER TURNED O OPEN-O: not included in any glyphset definition</li>
<li>U+AB44 LATIN SMALL LETTER TURNED O OPEN-O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB45 LATIN SMALL LETTER STIRRUP R: not included in any glyphset definition</li>
<li>U+AB46 LATIN LETTER SMALL CAPITAL R WITH RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB47 LATIN SMALL LETTER R WITHOUT HANDLE: not included in any glyphset definition</li>
<li>U+AB48 LATIN SMALL LETTER DOUBLE R: not included in any glyphset definition</li>
<li>U+AB49 LATIN SMALL LETTER R WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB4A LATIN SMALL LETTER DOUBLE R WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB4B LATIN SMALL LETTER SCRIPT R: not included in any glyphset definition</li>
<li>U+AB4C LATIN SMALL LETTER SCRIPT R WITH RING: not included in any glyphset definition</li>
<li>U+AB4D LATIN SMALL LETTER BASELINE ESH: not included in any glyphset definition</li>
<li>U+AB4E LATIN SMALL LETTER U WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB4F LATIN SMALL LETTER U BAR WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB50 LATIN SMALL LETTER UI: not included in any glyphset definition</li>
<li>U+AB51 LATIN SMALL LETTER TURNED UI: not included in any glyphset definition</li>
<li>U+AB52 LATIN SMALL LETTER U WITH LEFT HOOK: not included in any glyphset definition</li>
<li>U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition</li>
<li>U+AB54 LATIN SMALL LETTER CHI WITH LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB55 LATIN SMALL LETTER CHI WITH LOW LEFT SERIF: not included in any glyphset definition</li>
<li>U+AB56 LATIN SMALL LETTER X WITH LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB57 LATIN SMALL LETTER X WITH LONG LEFT LEG: not included in any glyphset definition</li>
<li>U+AB58 LATIN SMALL LETTER X WITH LONG LEFT LEG AND LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB59 LATIN SMALL LETTER X WITH LONG LEFT LEG WITH SERIF: not included in any glyphset definition</li>
<li>U+AB5A LATIN SMALL LETTER Y WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB5B MODIFIER BREVE WITH INVERTED BREVE: not included in any glyphset definition</li>
<li>U+AB5C MODIFIER LETTER SMALL HENG: not included in any glyphset definition</li>
<li>U+AB5D MODIFIER LETTER SMALL L WITH INVERTED LAZY S: not included in any glyphset definition</li>
<li>U+AB5E MODIFIER LETTER SMALL L WITH MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+AB5F MODIFIER LETTER SMALL U WITH LEFT HOOK: not included in any glyphset definition</li>
<li>U+AB60 LATIN SMALL LETTER SAKHA YAT: not included in any glyphset definition</li>
<li>U+AB61 LATIN SMALL LETTER IOTIFIED E: not included in any glyphset definition</li>
<li>U+AB62 LATIN SMALL LETTER OPEN OE: not included in any glyphset definition</li>
<li>U+AB63 LATIN SMALL LETTER UO: not included in any glyphset definition</li>
<li>U+AB64 LATIN SMALL LETTER INVERTED ALPHA: not included in any glyphset definition</li>
<li>U+AB65 GREEK LETTER SMALL CAPITAL OMEGA: not included in any glyphset definition</li>
<li>U+F001 : not included in any glyphset definition</li>
<li>U+F002 : not included in any glyphset definition</li>
<li>U+F004 : not included in any glyphset definition</li>
<li>U+F005 : not included in any glyphset definition</li>
<li>U+F00A : not included in any glyphset definition</li>
<li>U+F00B : not included in any glyphset definition</li>
<li>U+F00C : not included in any glyphset definition</li>
<li>U+F00D : not included in any glyphset definition</li>
<li>U+F00E : not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FE20 COMBINING LIGATURE LEFT HALF: try adding caucasian-albanian</li>
<li>U+FE21 COMBINING LIGATURE RIGHT HALF: try adding caucasian-albanian</li>
<li>U+FE22 COMBINING DOUBLE TILDE LEFT HALF: try adding caucasian-albanian</li>
<li>U+FE23 COMBINING DOUBLE TILDE RIGHT HALF: try adding caucasian-albanian</li>
<li>U+FE24 COMBINING MACRON LEFT HALF: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE25 COMBINING MACRON RIGHT HALF: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE26 COMBINING CONJOINING MACRON: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE27 COMBINING LIGATURE LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE28 COMBINING LIGATURE RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE29 COMBINING TILDE LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2A COMBINING TILDE RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2B COMBINING MACRON LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2C COMBINING MACRON RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2D COMBINING CONJOINING MACRON BELOW: try adding caucasian-albanian</li>
<li>U+FFFC OBJECT REPLACEMENT CHARACTER: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>greek</code>, <code>greek-ext</code>, <code>hebrew</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ i̍ i̐ i̓ i᷆ i᷇ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̅ i̇ i̎ i̒ i̔ i̽ i̾ i̿ i͂ i͆ i͊ i͋ i͌ i͐ i͑ i͒ i͗ i͛ iͣ iͤ</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Belarusian (Cyrl, 10,064,517 speakers), Zapotec (Latn, 490,000 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Gulay (Latn, 250,478 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Longto (Latn, 5,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Fur (Latn, 1,230,163 speakers), Ejagham (Latn, 120,000 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Cicipu (Latn, 44,000 speakers), Aghem (Latn, 38,843 speakers), Kaska (Latn, 125 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Bafut (Latn, 158,146 speakers), Avokaya (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Dutch (Latn, 31,709,104 speakers), Ekpeye (Latn, 226,000 speakers), Makaa (Latn, 221,000 speakers), Northern Tutchone (Latn, 85 speakers), Yala (Latn, 200,000 speakers), Keliko (Latn, 63,000 speakers), Navajo (Latn, 166,319 speakers), Lugbara (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Bete-Bendi (Latn, 100,000 speakers), Mfumte (Latn, 79,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Teke-Ebo (Latn, 260,000 speakers), South Central Banda (Latn, 244,000 speakers), Abua (Latn, 25,000 speakers), Han (Latn, 6 speakers), Ikwere (Latn, 717,000 speakers), Nzakara (Latn, 50,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* B (U+0042): B&lt;&lt;1201.5,822.5&gt;-&lt;1113.0,738.0&gt;-&lt;953.0,716.0&gt;&gt;/B&lt;&lt;953.0,716.0&gt;-&lt;1105.0,703.0&gt;-&lt;1191.5,619.5&gt;&gt; = 12.717477458184327

* Beta (U+0392): B&lt;&lt;1201.5,822.5&gt;-&lt;1113.0,738.0&gt;-&lt;953.0,716.0&gt;&gt;/B&lt;&lt;953.0,716.0&gt;-&lt;1105.0,703.0&gt;-&lt;1191.5,619.5&gt;&gt; = 12.717477458184327

* uni0181 (U+0181): B&lt;&lt;1299.5,822.5&gt;-&lt;1211.0,738.0&gt;-&lt;1051.0,716.0&gt;&gt;/B&lt;&lt;1051.0,716.0&gt;-&lt;1203.0,703.0&gt;-&lt;1289.5,619.5&gt;&gt; = 12.717477458184327

* uni023A (U+023A): L&lt;&lt;338.0,447.0&gt;--&lt;172.0,135.0&gt;&gt;/L&lt;&lt;172.0,135.0&gt;--&lt;430.0,447.0&gt;&gt; = 11.57286337967148

* uni0243 (U+0243): B&lt;&lt;1201.5,822.5&gt;-&lt;1113.0,738.0&gt;-&lt;953.0,716.0&gt;&gt;/B&lt;&lt;953.0,716.0&gt;-&lt;1105.0,703.0&gt;-&lt;1191.5,619.5&gt;&gt; = 12.717477458184327

* uni03D2 (U+03D2): B&lt;&lt;782.5,726.5&gt;-&lt;781.0,701.0&gt;-&lt;779.0,675.0&gt;&gt;/B&lt;&lt;779.0,675.0&gt;-&lt;877.0,1006.0&gt;-&lt;1033.0,1181.0&gt;&gt; = 12.093867984643525

* uni03D3 (U+03D3): B&lt;&lt;1020.5,726.5&gt;-&lt;1019.0,701.0&gt;-&lt;1017.0,675.0&gt;&gt;/B&lt;&lt;1017.0,675.0&gt;-&lt;1115.0,1006.0&gt;-&lt;1271.0,1181.0&gt;&gt; = 12.093867984643525

* uni03D4 (U+03D4): B&lt;&lt;782.5,726.5&gt;-&lt;781.0,701.0&gt;-&lt;779.0,675.0&gt;&gt;/B&lt;&lt;779.0,675.0&gt;-&lt;877.0,1006.0&gt;-&lt;1033.0,1181.0&gt;&gt; = 12.093867984643525

* uni0412 (U+0412): B&lt;&lt;1201.5,822.5&gt;-&lt;1113.0,738.0&gt;-&lt;953.0,716.0&gt;&gt;/B&lt;&lt;953.0,716.0&gt;-&lt;1105.0,703.0&gt;-&lt;1191.5,619.5&gt;&gt; = 12.717477458184327

* uni1D2E (U+1D2E): B&lt;&lt;763.5,1057.0&gt;-&lt;711.0,1006.0&gt;-&lt;614.0,992.0&gt;&gt;/B&lt;&lt;614.0,992.0&gt;-&lt;705.0,983.0&gt;-&lt;757.0,933.5&gt;&gt; = 13.861027563021148

* uni1E02 (U+1E02): B&lt;&lt;1201.5,822.5&gt;-&lt;1113.0,738.0&gt;-&lt;953.0,716.0&gt;&gt;/B&lt;&lt;953.0,716.0&gt;-&lt;1105.0,703.0&gt;-&lt;1191.5,619.5&gt;&gt; = 12.717477458184327

* uni1E04 (U+1E04): B&lt;&lt;1201.5,822.5&gt;-&lt;1113.0,738.0&gt;-&lt;953.0,716.0&gt;&gt;/B&lt;&lt;953.0,716.0&gt;-&lt;1105.0,703.0&gt;-&lt;1191.5,619.5&gt;&gt; = 12.717477458184327

* uni1E06 (U+1E06): B&lt;&lt;1201.5,822.5&gt;-&lt;1113.0,738.0&gt;-&lt;953.0,716.0&gt;&gt;/B&lt;&lt;953.0,716.0&gt;-&lt;1105.0,703.0&gt;-&lt;1191.5,619.5&gt;&gt; = 12.717477458184327

* uni210A (U+210A): B&lt;&lt;190.5,333.0&gt;-&lt;211.0,390.0&gt;-&lt;240.0,428.0&gt;&gt;/L&lt;&lt;240.0,428.0&gt;--&lt;106.0,297.0&gt;&gt; = 8.29925471425042

* uni210B (U+210B): B&lt;&lt;1054.5,1043.5&gt;-&lt;1109.0,1122.0&gt;-&lt;1165.0,1190.0&gt;&gt;/B&lt;&lt;1165.0,1190.0&gt;-&lt;1095.0,1126.0&gt;-&lt;1031.0,1075.0&gt;&gt; = 8.09131036312114

* uni211F (U+211F): L&lt;&lt;552.0,568.0&gt;--&lt;502.0,285.0&gt;&gt;/L&lt;&lt;502.0,285.0&gt;--&lt;605.0,568.0&gt;&gt; = 9.97983160205228

* uni2133 (U+2133): B&lt;&lt;2033.0,1106.0&gt;-&lt;2137.0,1230.0&gt;-&lt;2304.0,1421.0&gt;&gt;/B&lt;&lt;2304.0,1421.0&gt;-&lt;2197.0,1345.0&gt;-&lt;2071.0,1224.0&gt;&gt; = 13.449888368034253

* uni2E3F (U+2E3F): L&lt;&lt;924.0,1066.0&gt;--&lt;928.0,1062.0&gt;&gt;/B&lt;&lt;928.0,1062.0&gt;-&lt;902.0,1103.0&gt;-&lt;825.0,1127.0&gt;&gt; = 12.61932229343077

* uniA65F (U+A65F): L&lt;&lt;848.0,320.0&gt;--&lt;822.0,499.0&gt;&gt;/B&lt;&lt;822.0,499.0&gt;-&lt;820.0,477.0&gt;-&lt;813.5,434.0&gt;&gt; = 13.458922992393378

* uniA796 (U+A796): B&lt;&lt;1406.5,822.5&gt;-&lt;1318.0,738.0&gt;-&lt;1158.0,716.0&gt;&gt;/B&lt;&lt;1158.0,716.0&gt;-&lt;1310.0,703.0&gt;-&lt;1396.5,619.5&gt;&gt; = 12.717477458184327

* uniA7B4 (U+A7B4): B&lt;&lt;1201.5,822.5&gt;-&lt;1113.0,738.0&gt;-&lt;953.0,716.0&gt;&gt;/B&lt;&lt;953.0,716.0&gt;-&lt;1105.0,703.0&gt;-&lt;1191.5,619.5&gt;&gt; = 12.717477458184327
</code></pre>
 [code: found-jaggy-segments]



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
    <summary>⚠️ <b>WARN</b> Description strings in the name table must not exceed 200 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-description-max-length">googlefonts/name/description_max_length</a></summary>
    <div>







* ⚠️ **WARN** <p>A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries.</p>
 [code: too-long]



</div>
</details>
</div>
</details>

<details><summary>[23] Tinos-Italic.ttf</summary>
<div>
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
<td align="left">U+1D8E: LATIN SMALL LETTER Z WITH PALATAL HOOK</td>
<td align="left">U+A7C6: LATIN CAPITAL LETTER Z WITH PALATAL HOOK</td>
</tr>
<tr>
<td align="left">U+2184: LATIN SMALL LETTER REVERSED C</td>
<td align="left">U+2183: ROMAN NUMERAL REVERSED ONE HUNDRED</td>
</tr>
<tr>
<td align="left">U+A794: LATIN SMALL LETTER C WITH PALATAL HOOK</td>
<td align="left">U+A7C4: LATIN CAPITAL LETTER C WITH PALATAL HOOK</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 2068, but got 1825 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 797, but got 443 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.13.1, while a newer 0.13.2 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#os2-metrics-match-hhea">os2_metrics_match_hhea</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (1422) and hhea ascent (1825) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check tabular widths don't have kerning. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#tabular-kerning">tabular_kerning</a></summary>
    <div>







* 🔥 **FAIL** <p>Kerning between one and one is -152, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -152, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -152, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -152, should be 0</p>
 [code: has-tabular-kerning]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Whitespace glyphs have ink? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#whitespace-ink">whitespace_ink</a></summary>
    <div>







* 🔥 **FAIL** <p>Glyph 'uni2028' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni2029' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni205F' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni2060' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uniFEFF' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Greek_Expert glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Shaper didn't attach acutecomb to j</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to J</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">The locl feature did not affect Eng</td>
<td align="left">bm_Latn (Bambara), dyu_Latn (Dyula), ig_Latn (Igbo), lg_Latn (Ganda), mnf_Latn (Mundani), las_Latn (Lama, Togo), dtm_Latn (Tomo Kan Dogon), dnj_Latn (Dan), nnh_Latn (Ngiemboon), ttq_Latn (Tawallammat Tamajaq), snk_Latn (Soninke), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nfr_Latn (Nafaanra), nus_Latn (Nuer), bsc_Latn (Bassari), dur_Latn (Dii), naw_Latn (Nawuri), fmp_Latn (Fe’fe’), sav_Latn (Saafi-Saafi), mne_Latn (Naba), azo_Latn (Awing), ig_Latn (Igbo), bzw_Latn (Basa), fuc_Latn (Pulaar), yat_Latn (Yambeta), nnw_Latn (Southern Nuni), kpo_Latn (Ikposo), log_Latn (Logo), dip_Latn (Dinka, Northeastern), twq_Latn (Tasawaq), nfu_Latn (Mfumte), ajg_Latn (Aja), xwe_Latn (Gbe, Xwela), loq_Latn (Lobala), bsp_Latn (Baga Sitemu), wan_Latn (Wan), bcw_Latn (Bana), maw_Latn (Mampruli), myk_Latn (Mamara Senoufo), mfv_Latn (Mandjak), tuq_Latn (Tedaga), agc_Latn (Agatu), krs_Latn (Gbaya, Sudan), bbo_Latn (Northern Bobo Madaré), mfd_Latn (Mendankwe-Nkwen), etu_Latn (Ejagham), xuo_Latn (Kuo), xon_Latn (Konkomba), sok_Latn (Sokoro), adj_Latn (Adioukrou), avn_Latn (Avatime), nku_Latn (Kulango, Bouna), mcn_Latn (Masana), nym_Latn (Nyamwezi), shz_Latn (Syenara Senoufo), lun_Latn (Lunda), ade_Latn (Adele), mdj_Latn (Mangbetu), gur_Latn (Frafra), gna_Latn (Kaansa), mua_Latn (Mundang), bex_Latn (Jur Modo), fvr_Latn (Fur), lam_Latn (Lamba), bza_Latn (Bandi), wci_Latn (Gbe, Waci), mcu_Latn (Mambila, Cameroon), taq_Latn (Tamasheq (Latin)), kvf_Latn (Kabalai), blo_Latn (Anii), gde_Latn (Gude), tik_Latn (Tikar), nmg_Latn (Kwasio), sig_Latn (Paasaal), dow_Latn (Doyayo), dag_Latn (Dagbani), keu_Latn (Akebu), giz_Latn (Southern Giziga), bfd_Latn (Bafut), dno_Latn (Ndrulo), bud_Latn (Ntcham), dyo_Latn (Jola-Fonyi), ybb_Latn (Yemba), tvu_Latn (Tunen), kus_Latn (Kusaal), agq_Latn (Aghem), kzc_Latn (Bondoukou Kulango), ksf_Latn (Bafia), wwa_Latn (Waama), khq_Latn (Koyra Chiini), tod_Latn (Toma), ewo_Latn (Ewondo), muy_Latn (Muyang), cae_Latn (Lehar), vut_Latn (Vute), bzx_Latn (Bozo, Hainyaxo), xsm_Latn (Kasem), xrb_Latn (Karaboro, Eastern), gmm_Latn (Gbaya-Mbodomo), gnd_Latn (Zulgo-Gemzek), nmz_Latn (Nawdm), kpz_Latn (Sapiny), dyu_Latn (Dyula), kdj_Latn (Karamojong), mbu_Latn (Mbula-Bwazza), cou_Latn (Wamey), ny_Latn (Nyanja), avu_Latn (Avokaya), mev_Latn (Mano), bib_Latn (Bissa), ntr_Latn (Delo), udu_Latn (Uduk), ahl_Latn (Igo), spp_Latn (Sénoufo, Supyire), ife_Latn (Ifè), mfi_Latn (Wandala), srr_Latn (Serer), fuf_Latn (Pular), kyq_Latn (Kenga), ikx_Latn (Ik), pbi_Latn (Parkwa), cko_Latn (Anufo), kye_Latn (Krache), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), ken_Latn (Kenyang), tcd_Latn (Tafi), vag_Latn (Vagla), yam_Latn (Yamba), saf_Latn (Safaliba), pil_Latn (Yom), mgc_Latn (Morokodo), mmu_Latn (Mmaala), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), ndz_Latn (Ndogo), cme_Latn (Cerma), kqp_Latn (Kimré), ffm_Latn (Maasina Fulfulde), pnz_Latn (Pana, Central African Republic), kao_Latn (Xaasongaxango), knf_Latn (Mankanya), mur_Latn (Murle), nhu_Latn (Noone), neb_Latn (Toura), lg_Latn (Ganda), ses_Latn (Koyraboro Senni), daa_Latn (Dangaléat), fub_Latn (Fulfulde, Adamawa), ahs_Latn (Ashe), mwk_Latn (Kita Maninkakan), ddn_Latn (Dendi), acd_Latn (Gikyode), xed_Latn (Hdi), kss_Latn (Southern Kisi), kqs_Latn (Kissi, Northern), sef_Latn (Cebaara Senoufo), dgi_Latn (Northern Dagara), ncu_Latn (Chumburung), kmy_Latn (Koma), lee_Latn (Lyélé), bbj_Latn (Ghomala), lmp_Latn (Limbum), kib_Latn (Koalib), wok_Latn (Longto), bav_Latn (Vengo), byv_Latn (Medumba), bqv_Latn (Koro Wachi), kyf_Latn (Kouya), dzg_Latn (Dazaga), yas_Latn (Nugunu), ekm_Latn (Elip), snf_Latn (Noon), sxw_Latn (Saxwe Gbe), nza_Latn (Tigon Mbembe), toq_Latn (Toposa), gej_Latn (Gen), tnr_Latn (Ménik), jgo_Latn (Ngomba), ktj_Latn (Krumen, Plapo), gjn_Latn (Gonja), fuq_Latn (Central-Eastern Niger Fulfulde), bum_Latn (Bulu), fue_Latn (Fulfulde, Borgu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), mgo_Latn (Metaʼ), nko_Latn (Nkonya), ebo_Latn (Teke-Ebo), fan_Latn (Fang), ozm_Latn (Koonzime), dop_Latn (Lukpa), mcp_Latn (Makaa), mls_Latn (Masalit), god_Latn (Godié), bss_Latn (Akoose), mor_Latn (Moro), kbo_Latn (Keliko), kia_Latn (Kim), bfa_Latn (Bari), kdh_Latn (Tem), lok_Latn (Loko), ach_Latn (Acoli), sil_Latn (Sisaala, Tumulung), lns_Latn (Lamnso’), bze_Latn (Jenaama Bozo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), lig_Latn (Ligbi), csk_Latn (Jola-Kasa), anv_Latn (Denya), rub_Latn (Gungu), mnk_Latn (Mandinka), mgd_Latn (Moru), moa_Latn (Mwan), gng_Latn (Ngangam), mas_Latn (Masai), dje_Latn (Zarma), mbo_Latn (Mbo), yav_Latn (Yangben), dua_Latn (Duala), ted_Latn (Krumen, Tepo), tem_Latn (Timne), fod_Latn (Foodo), soy_Latn (Miyobe), wo_Latn (Wolof), mdt_Latn (Mbere), boz_Latn (Tiéyaxo Bozo), gud_Latn (Dida, Yocoboué), nhb_Latn (Beng), fuh_Latn (Fulfulde, Western Niger), bim_Latn (Bimoba), kzr_Latn (Karang), kbp_Latn (Kabiyé), mfq_Latn (Moba), gux_Latn (Gourmanchéma), bjt_Latn (Balanta-Ganja), knp_Latn (Kwanja), dyi_Latn (Sénoufo, Djimini), gaa_Latn (Ga), tpm_Latn (Tampulma), idu_Latn (Idoma), bm_Latn (Bambara), lem_Latn (Nomaande), emk_Latn (Maninkakan, Eastern), meq_Latn (Merey), bkm_Latn (Kom), mzw_Latn (Deg), nuv_Latn (Nuni, Northern), bqj_Latn (Bandial), lia_Latn (Limba, West-Central), pug_Latn (Phuie), aks_Latn (Akeselem), dts_Latn (Dogon, Toro So), ndv_Latn (Ndut), hag_Latn (Hanga), bas_Latn (Basaa), laj_Latn (Lango, Uganda), gkp_Latn (Kpelle, Guinea) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to r</td>
<td align="left">ha_Latn (Hausa) and ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to R</td>
<td align="left">ha_Latn (Hausa) and ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), avu_Latn (Avokaya), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), avu_Latn (Avokaya), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to m</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), ig_Latn (Igbo), yo_Latn_BJ (Yoruba, Benin), yo_Latn (Yoruba), tik_Latn (Tikar), bud_Latn (Ntcham), mev_Latn (Mano), kyq_Latn (Kenga), ikw_Latn (Ikwere), tbz_Latn (Ditammari), jgo_Latn (Ngomba), gvl_Latn (Gulay) and nup_Latn (Nupe-Nupe-Tako)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to M</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), ig_Latn (Igbo), yo_Latn_BJ (Yoruba, Benin), yo_Latn (Yoruba), tik_Latn (Tikar), bud_Latn (Ntcham), mev_Latn (Mano), kyq_Latn (Kenga), ikw_Latn (Ikwere), tbz_Latn (Ditammari), jgo_Latn (Ngomba), gvl_Latn (Gulay) and nup_Latn (Nupe-Nupe-Tako)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere), ann_Latn (Obolo) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere), ann_Latn (Obolo) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to O</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ocircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), nzk_Latn (Nzakara), ozm_Latn (Koonzime), mcp_Latn (Makaa), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D2</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), nfu_Latn (Mfumte), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), tcd_Latn (Tafi), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), gov_Latn (Goo), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Agrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to o</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0197</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), nyb_Latn (Nyangbo), yav_Latn (Yangben), mge_Latn (Mango), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to U</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0197</td>
<td align="left">mnf_Latn (Mundani) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ugrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to A</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ograve</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to a</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ucircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0228</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ugrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), bfd_Latn (Bafut), ewo_Latn (Ewondo), ksp_Latn (Kabba), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
<td align="left">mnf_Latn (Mundani), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0229</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), nyb_Latn (Nyangbo), yav_Latn (Yangben), mge_Latn (Mango), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), gnd_Latn (Zulgo-Gemzek), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), byv_Latn (Medumba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), gvl_Latn (Gulay), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ocircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0229</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), bfd_Latn (Bafut), ewo_Latn (Ewondo), ksp_Latn (Kabba), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0268</td>
<td align="left">mnf_Latn (Mundani) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D3</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to u</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), gnd_Latn (Zulgo-Gemzek), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), byv_Latn (Medumba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), gvl_Latn (Gulay), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0197</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), nzk_Latn (Nzakara), ozm_Latn (Koonzime), mcp_Latn (Makaa), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to acircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01CE</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0197</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), nfu_Latn (Mfumte), bfd_Latn (Bafut), agq_Latn (Aghem), gvl_Latn (Gulay), mge_Latn (Mango), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ucircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Acircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), nfu_Latn (Mfumte), bfd_Latn (Bafut), agq_Latn (Aghem), gvl_Latn (Gulay), mge_Latn (Mango), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), nfu_Latn (Mfumte), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), tcd_Latn (Tafi), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D4</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to agrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0228</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0229</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D1</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
<td align="left">mnf_Latn (Mundani), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01CD</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0228</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ograve</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni025B</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to a</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to A</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to ae</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to AE</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to ae</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to AE</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to ae</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to AE</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to ae</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to AE</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to e</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to E</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0190</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), tik_Latn (Tikar), dow_Latn (Doyayo), bfd_Latn (Bafut), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), nyb_Latn (Nyangbo), gov_Latn (Goo), yav_Latn (Yangben), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), tik_Latn (Tikar), dow_Latn (Doyayo), bfd_Latn (Bafut), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), nyb_Latn (Nyangbo), yav_Latn (Yangben), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
<td align="left">dnj_Latn (Dan), nmg_Latn (Kwasio), dow_Latn (Doyayo), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
<td align="left">dnj_Latn (Dan), nmg_Latn (Kwasio), dow_Latn (Doyayo), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mdt_Latn (Mbere), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mdt_Latn (Mbere), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni025B</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni0190</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), kpe_Latn (Kpelle), lnl_Latn (South Central Banda), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), gov_Latn (Goo), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), kpe_Latn (Kpelle), lnl_Latn (South Central Banda), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to i</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to I</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0264</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), fvr_Latn (Fur), agq_Latn (Aghem), nzk_Latn (Nzakara), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), fvr_Latn (Fur), agq_Latn (Aghem), nzk_Latn (Nzakara), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), ybb_Latn (Yemba), bbj_Latn (Ghomala), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), mas_Latn (Masai) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), fvr_Latn (Fur), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), ybb_Latn (Yemba), bbj_Latn (Ghomala), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), mas_Latn (Masai) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), ybb_Latn (Yemba), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), mwm_Latn (Sar), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mge_Latn (Mango), mdt_Latn (Mbere), kzr_Latn (Karang), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), fvr_Latn (Fur), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), ybb_Latn (Yemba), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), mwm_Latn (Sar), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mge_Latn (Mango), mdt_Latn (Mbere), kzr_Latn (Karang), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to J</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq), taq_Latn (Tamasheq (Latin)) and tmh_Latn (Tamashek)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), dgi_Latn (Northern Dagara), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), dgi_Latn (Northern Dagara), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Utilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to a</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to A</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to e</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to E</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to i</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to I</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to o</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to O</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0254</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0186</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to u</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to U</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to atilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Atilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to tildecomb</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to itilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Itilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to utilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Utilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), dnj_Latn_LR (Liberian Dan), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to itilde</td>
<td align="left">nga_Latn (Ngbaka) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Itilde</td>
<td align="left">nga_Latn (Ngbaka) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to utilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Utilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to itilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Itilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to utilde</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Utilde</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to e</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to E</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to o</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to O</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), sba_Latn (Ngambay), blo_Latn (Anii), nmg_Latn (Kwasio) and ksf_Latn (Bafia)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and lob_Latn (Lobi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), sba_Latn (Ngambay), blo_Latn (Anii), nmg_Latn (Kwasio) and ksf_Latn (Bafia)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to otilde</td>
<td align="left">tuz_Latn (Turka), lom_Latn (Loma, Liberia), lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and lob_Latn (Lobi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0196</td>
<td align="left">tuz_Latn (Turka), goa_Latn (Guro), blo_Latn (Anii), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Otilde</td>
<td align="left">tuz_Latn (Turka), lom_Latn (Loma, Liberia), lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196</td>
<td align="left">tuz_Latn (Turka), goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), xsm_Latn_BF (Kasem, Burkina Faso), tcd_Latn (Tafi), neb_Latn (Toura), sld_Latn (Sissala), pug_Latn (Phuie) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EE4</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EB9</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECA</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EE5</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECA</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), avu_Latn (Avokaya), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EE4</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECD</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EB8</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECC</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EE5</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), avu_Latn (Avokaya), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EB9</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EB8</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECA</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECD</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECC</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EE5</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EE4</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to i</td>
<td align="left">kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
<td align="left">kkj_Latn (Kako), dow_Latn (Doyayo), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to I</td>
<td align="left">kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
<td align="left">kkj_Latn (Kako), dow_Latn (Doyayo), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to a</td>
<td align="left">nus_Latn (Nuer), asg_Latn (Cishingini), fvr_Latn (Fur), kdj_Latn (Karamojong), kaj_Latn (Jju) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), lnl_Latn (South Central Banda), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0254</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
<td align="left">nus_Latn (Nuer)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to A</td>
<td align="left">nus_Latn (Nuer), asg_Latn (Cishingini), fvr_Latn (Fur), kdj_Latn (Karamojong), kaj_Latn (Jju) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), lnl_Latn (South Central Banda), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0190</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to i</td>
<td align="left">nus_Latn (Nuer), kdj_Latn (Karamojong), kcg_Latn (Tyap) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0254</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0186</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0186</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to I</td>
<td align="left">nus_Latn (Nuer), kdj_Latn (Karamojong), kcg_Latn (Tyap) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to h</td>
<td align="left">bsc_Latn (Bassari)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to H</td>
<td align="left">bsc_Latn (Bassari)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to w</td>
<td align="left">bsc_Latn (Bassari) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to W</td>
<td align="left">bsc_Latn (Bassari) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
<td align="left">dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), etu_Latn (Ejagham), sba_Latn (Ngambay), bfd_Latn (Bafut), ybb_Latn (Yemba), ewo_Latn (Ewondo), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), mwm_Latn (Sar), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), mcp_Latn (Makaa), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Oacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Igrave</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
<td align="left">dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Uacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0228</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0229</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0197</td>
<td align="left">dur_Latn (Dii), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), bfd_Latn (Bafut), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), mge_Latn (Mango) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Iacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
<td align="left">dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), etu_Latn (Ejagham), sba_Latn (Ngambay), bfd_Latn (Bafut), ybb_Latn (Yemba), ewo_Latn (Ewondo), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), mwm_Latn (Sar), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), mcp_Latn (Makaa), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to aacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268</td>
<td align="left">dur_Latn (Dii), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), bfd_Latn (Bafut), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), mge_Latn (Mango) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F</td>
<td align="left">dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to igrave</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to iacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to oacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Aacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), kyq_Latn (Kenga), mwm_Latn (Sar), wok_Latn (Longto), bax_Latn (Bamun (Latin)) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
<td align="left">fmp_Latn (Fe’fe’), nmg_Latn (Kwasio), dow_Latn (Doyayo), ybb_Latn (Yemba), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), mwm_Latn (Sar), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0289</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), agq_Latn (Aghem) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0244</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), agq_Latn (Aghem) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186</td>
<td align="left">fmp_Latn (Fe’fe’), nmg_Latn (Kwasio), dow_Latn (Doyayo), ybb_Latn (Yemba), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), mwm_Latn (Sar), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), kyq_Latn (Kenga), mwm_Latn (Sar), wok_Latn (Longto), bax_Latn (Bamun (Latin)) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to n</td>
<td align="left">mne_Latn (Naba), kyq_Latn (Kenga), daa_Latn (Dangaléat), mls_Latn (Masalit) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to N</td>
<td align="left">mne_Latn (Naba), kyq_Latn (Kenga), daa_Latn (Dangaléat), mls_Latn (Masalit) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to U</td>
<td align="left">uth_Latn (ut-Hun), kdj_Latn (Karamojong), kaj_Latn (Jju) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to u</td>
<td align="left">uth_Latn (ut-Hun), kdj_Latn (Karamojong), kaj_Latn (Jju) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Oslash</td>
<td align="left">nfu_Latn (Mfumte) and ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oslash</td>
<td align="left">nfu_Latn (Mfumte) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Oslash</td>
<td align="left">nfu_Latn (Mfumte), ozm_Latn (Koonzime) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Oslash</td>
<td align="left">nfu_Latn (Mfumte) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oslash</td>
<td align="left">nfu_Latn (Mfumte), ozm_Latn (Koonzime) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oslash</td>
<td align="left">nfu_Latn (Mfumte) and ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018E</td>
<td align="left">dnj_Latn_LR (Liberian Dan), blo_Latn (Anii) and nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
<td align="left">dnj_Latn_LR (Liberian Dan), blo_Latn (Anii) and nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to n</td>
<td align="left">mg_Latn (Malagasy), etu_Latn (Ejagham), ksp_Latn (Kabba), ikw_Latn (Ikwere) and gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to N</td>
<td align="left">mg_Latn (Malagasy), etu_Latn (Ejagham), ksp_Latn (Kabba) and ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to n</td>
<td align="left">mg_Latn (Malagasy) and nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to N</td>
<td align="left">mg_Latn (Malagasy) and nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to g</td>
<td align="left">tuq_Latn (Tedaga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to G</td>
<td align="left">tuq_Latn (Tedaga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F</td>
<td align="left">lnl_Latn (South Central Banda), ybb_Latn (Yemba), ksp_Latn (Kabba) and sbd_Latn (Southern Samo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268</td>
<td align="left">lnl_Latn (South Central Banda) and nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0197</td>
<td align="left">lnl_Latn (South Central Banda) and nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
<td align="left">lnl_Latn (South Central Banda), ybb_Latn (Yemba), ksp_Latn (Kabba) and sbd_Latn (Southern Samo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0244</td>
<td align="left">lnl_Latn (South Central Banda), nzk_Latn (Nzakara) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0289</td>
<td align="left">lnl_Latn (South Central Banda), nzk_Latn (Nzakara) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
<td align="left">goa_Latn (Guro), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), xsm_Latn_BF (Kasem, Burkina Faso), neb_Latn (Toura), sld_Latn (Sissala) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), xsm_Latn_BF (Kasem, Burkina Faso), neb_Latn (Toura), sld_Latn (Sissala) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
<td align="left">goa_Latn (Guro), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
<td align="left">goa_Latn (Guro), blo_Latn (Anii), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0196</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tcd_Latn (Tafi) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tcd_Latn (Tafi) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028B</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0196</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), xsm_Latn_BF (Kasem, Burkina Faso), tcd_Latn (Tafi), neb_Latn (Toura), sld_Latn (Sissala), pug_Latn (Phuie) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EE4</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECD</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EB8</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECA</td>
<td align="left">mhi_Latn (Ma’di), avu_Latn (Avokaya) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECC</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EB9</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EE5</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB</td>
<td align="left">mhi_Latn (Ma’di), avu_Latn (Avokaya) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to o</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and kia_Latn (Kim)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E1A</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to A</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto), kia_Latn (Kim) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E1B</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E1A</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E1B</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to a</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto), kia_Latn (Kim) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to O</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and kia_Latn (Kim)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01DD</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018E</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), sld_Latn (Sissala), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), tcd_Latn (Tafi), sld_Latn (Sissala), biv_Latn (Birifor, Southern), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), sld_Latn (Sissala), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), tcd_Latn (Tafi), sld_Latn (Sissala), biv_Latn (Birifor, Southern), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni01CE</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Aacute</td>
<td align="left">fvr_Latn (Fur) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to aacute</td>
<td align="left">fvr_Latn (Fur) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to acircumflex</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Acircumflex</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni01CD</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EBC</td>
<td align="left">kst_Latn (Winyé), lee_Latn (Lyélé), sld_Latn (Sissala), soy_Latn (Miyobe), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EBD</td>
<td align="left">kst_Latn (Winyé), lee_Latn (Lyélé), sld_Latn (Sissala), soy_Latn (Miyobe), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A</td>
<td align="left">blo_Latn (Anii), tcd_Latn (Tafi) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1</td>
<td align="left">blo_Latn (Anii), tcd_Latn (Tafi) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to AE</td>
<td align="left">tik_Latn (Tikar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to eng</td>
<td align="left">tik_Latn (Tikar), mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
<td align="left">tik_Latn (Tikar), mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to ae</td>
<td align="left">tik_Latn (Tikar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01DD</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01DD</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018E</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018E</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to V</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to v</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to v</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to V</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to umacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to amacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Umacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Amacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Imacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0327</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0327</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to imacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to R</td>
<td align="left">dno_Latn (Ndrulo), kyq_Latn (Kenga) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to r</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to R</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to s</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to r</td>
<td align="left">dno_Latn (Ndrulo), kyq_Latn (Kenga) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to S</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to b</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to B</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to l</td>
<td align="left">bud_Latn (Ntcham) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to B</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to L</td>
<td align="left">bud_Latn (Ntcham) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to b</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Idieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to edieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Edieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to udieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to idieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Udieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268</td>
<td align="left">agq_Latn (Aghem) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0197</td>
<td align="left">agq_Latn (Aghem) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7AE</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EA1</td>
<td align="left">abn_Latn (Abua) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EA0</td>
<td align="left">abn_Latn (Abua) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EA1</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EA0</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Idieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to udieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to idieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Udieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Icircumflex</td>
<td align="left">vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to icircumflex</td>
<td align="left">vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to Eng</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to eng</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to G</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to g</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0289</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0268</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0197</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0244</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EA1</td>
<td align="left">avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EA0</td>
<td align="left">avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Agrave</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Amacron</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), wok_Latn (Longto), jgo_Latn (Ngomba), gov_Latn (Goo) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), wok_Latn (Longto), jgo_Latn (Ngomba) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), kss_Latn (Southern Kisi), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), kss_Latn (Southern Kisi), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E75</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E74</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E75</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E74</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E75</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E74</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to C</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni035F to T</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to c</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to p</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to P</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni035F to t</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to H</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to nacute</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Nacute</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01F9</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01F8</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to m</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), tcd_Latn (Tafi), mwm_Latn (Sar), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to M</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), tcd_Latn (Tafi), mwm_Latn (Sar), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to n</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), ann_Latn (Obolo), mwm_Latn (Sar), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to N</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), ann_Latn (Obolo), mwm_Latn (Sar), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to r</td>
<td align="left">kyq_Latn (Kenga), mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to R</td>
<td align="left">kyq_Latn (Kenga), mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to m</td>
<td align="left">ikw_Latn (Ikwere) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to M</td>
<td align="left">ikw_Latn (Ikwere) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019D</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019D</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to a</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to A</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to atilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Atilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to e</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to E</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EBD</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EBC</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0269</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0196</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0269</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0196</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to tildecomb</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to o</td>
<td align="left">tcd_Latn (Tafi), kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to O</td>
<td align="left">tcd_Latn (Tafi), kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to o</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to O</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to otilde</td>
<td align="left">tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Otilde</td>
<td align="left">tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0254</td>
<td align="left">tcd_Latn (Tafi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0186</td>
<td align="left">tcd_Latn (Tafi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to tildecomb</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to u</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to U</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to Utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A</td>
<td align="left">tcd_Latn (Tafi) and biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1</td>
<td align="left">tcd_Latn (Tafi) and biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E2D</td>
<td align="left">mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to w</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E2C</td>
<td align="left">mwm_Latn (Sar), ntm_Latn (Nateni) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E1A</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to omacron</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E2D</td>
<td align="left">mwm_Latn (Sar), ntm_Latn (Nateni) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to oacute</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Omacron</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E2C</td>
<td align="left">mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to W</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E1B</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Oacute</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to otilde</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni1EBC</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Otilde</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni1EBD</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to a</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to A</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to a</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to A</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to e</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to E</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to e</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to E</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni025B</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0190</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni025B</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0190</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to i</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to I</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to i</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to I</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to eng</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Eng</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to o</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to O</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0254</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0186</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0254</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0186</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to u</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to U</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to u</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to U</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EBC</td>
<td align="left">lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EBC</td>
<td align="left">lee_Latn (Lyélé) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EBD</td>
<td align="left">lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EBD</td>
<td align="left">lee_Latn (Lyélé) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Iacute</td>
<td align="left">kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to iacute</td>
<td align="left">kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E2C</td>
<td align="left">ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E2D</td>
<td align="left">ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to L</td>
<td align="left">wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to l</td>
<td align="left">wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0251</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Udieresis</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to udieresis</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0289</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0197</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0244</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0324 to W</td>
<td align="left">fan_Latn (Fang) and mdt_Latn (Mbere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0324 to w</td>
<td align="left">fan_Latn (Fang) and mdt_Latn (Mbere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to OE</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to OE</td>
<td align="left">ozm_Latn (Koonzime) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to OE</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe</td>
<td align="left">ozm_Latn (Koonzime) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ꟈ, ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0325 to l</td>
<td align="left">csk_Latn (Jola-Kasa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0325 to L</td>
<td align="left">csk_Latn (Jola-Kasa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to b</td>
<td align="left">rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to B</td>
<td align="left">rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Adieresis</td>
<td align="left">mgd_Latn (Moru)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to adieresis</td>
<td align="left">mgd_Latn (Moru)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to T</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to t</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to d</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to D</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ɤ, Ɤ̀, Ɤ́, Ɤ̂</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to ograve</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Ograve</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to OE</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to i</td>
<td align="left">btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to I</td>
<td align="left">btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EBD</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EBC</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to otilde</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Otilde</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to Oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to O</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to i</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni025B</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to A</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0186</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to I</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to e</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to o</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0254</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to u</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to U</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni025B</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0190</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to a</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0190</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to E</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to aogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Aogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0259</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Iogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Uogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Greek_Expert glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">No variant glyphs were found for uni0181</td>
<td align="left">dnj_Latn (Dan) and lom_Latn (Loma, Liberia)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Amo</td>
<td align="left">amo_Latn (Amo)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Koro</td>
<td align="left">kfo_Latn (Koro)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni028B</td>
<td align="left">tod_Latn (Toma)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01B2</td>
<td align="left">tod_Latn (Toma)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Seki</td>
<td align="left">syi_Latn (Seki)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Mina</td>
<td align="left">hna_Latn (Mina)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ⓐ, ⓐ</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Mbunga</td>
<td align="left">mgy_Latn (Mbunga)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Eastern Gurung, Latin</td>
<td align="left">ggn_Latn (Eastern Gurung, Latin)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01A9</td>
<td align="left">gaa_Latn (Ga)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01B7</td>
<td align="left">gaa_Latn (Ga)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Atsam</td>
<td align="left">cch_Latn (Atsam)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2010 Google Inc. All Rights Reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 🔥 **FAIL** <p>Tinos Regular: OS/2 sTypoAscender is 1420 when it should be 1825</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Tinos Regular: OS/2 sTypoDescender is -442 when it should be -443</p>
 [code: bad-typo-descender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671), uniA672 (U+A672), uniFE20 (U+FE20), uniFE21 (U+FE21), uniFE27 (U+FE27) and uniFE28 (U+FE28)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: hyphen	Contours detected: 1	Expected: 0

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni023A	Contours detected: 4	Expected: 3

- Glyph name: uni04B5	Contours detected: 2	Expected: 1

- Glyph name: uni1D4D	Contours detected: 2	Expected: 3

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uni204B	Contours detected: 1	Expected: 2

- Glyph name: uni205F	Contours detected: 15	Expected: 0

- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

- Glyph name: uni210A	Contours detected: 3	Expected: 2

- Glyph name: uni210D	Contours detected: 3	Expected: 2

- Glyph name: uni2119	Contours detected: 4	Expected: 2

- Glyph name: uni211A	Contours detected: 5	Expected: 3

- Glyph name: uni211D	Contours detected: 5	Expected: 3

- Glyph name: uni2E18	Contours detected: 3	Expected: 2

- Glyph name: uniFEFF	Contours detected: 19	Expected: 0

- Glyph name: uniFFFC	Contours detected: 16	Expected: 22

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: uni023A	Contours detected: 4	Expected: 3

- Glyph name: uni04B5	Contours detected: 2	Expected: 1

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uni204B	Contours detected: 1	Expected: 2

- Glyph name: uni205F	Contours detected: 15	Expected: 0

- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

- Glyph name: uni210A	Contours detected: 3	Expected: 2

- Glyph name: uni210D	Contours detected: 3	Expected: 2

- Glyph name: uni2119	Contours detected: 4	Expected: 2

- Glyph name: uni211A	Contours detected: 5	Expected: 3

- Glyph name: uni211D	Contours detected: 5	Expected: 3

- Glyph name: uni2E18	Contours detected: 3	Expected: 2

- Glyph name: uniFEFF	Contours detected: 19	Expected: 0

- Glyph name: uniFFFC	Contours detected: 16	Expected: 22

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 1382 among a set of 8 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 1124:
plusminus, divide, lessequal, approxequal, notequal, greaterequal</p>
<p>Width = 2005:
orthogonal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* uni1DD3 (U+1DD3): L&lt;&lt;137.0,1399.0&gt;--&lt;211.0,1399.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#typoascender-exceeds-Agrave">typoascender_exceeds_Agrave</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2.sTypoAscender value should be greater than 1757, but got 1422 instead</p>
 [code: typoAscender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Eng.alt1

- Eng.alt2

- Eng.alt3

- Lcommaaccent.loclMAH

- Ncommaaccent.loclMAH

- Ohm

- UNI2206

- acute.alt1

- acute.alt2

- acute.alt3

- acute.alt4

- acute.alt5

- alefdagesh

- aleflamedhatafsegol

- aleflamedsegol

- aleflamedtsere

- alternativelamed

- bari.dotless

- breve.alt1

- breve.cyr

- circumflex.alt1

- dotbelow.alt1

- dotbelow.alt10

- dotbelow.alt11

- dotbelow.alt12

- dotbelow.alt13

- dotbelow.alt14

- dotbelow.alt15

- dotbelow.alt2

- dotbelow.alt3

- dotbelow.alt4

- dotbelow.alt5

- dotbelow.alt6

- dotbelow.alt7

- dotbelow.alt8

- dotbelow.alt9

- dotlessi.alt1

- dottediacute

- eight.alt

- finalkafqamats

- finalkafsheva

- five.alt

- four.alt

- glyph3289

- grave.alt1

- grave.alt2

- grave.alt3

- grave.alt4

- grave.alt5

- hookabove.alt1

- hookabove.alt2

- hookabove.alt3

- hookabove.alt4

- hookabove.alt5

- lamedholam

- lamedholamdagesh

- lcommaaccent.loclMAH

- ncommaaccent.loclMAH

- nine.alt

- one.alt

- pi1

- radicalex.x

- seven.alt

- six.alt

- three.alt

- tilde.alt1

- tilde.alt10

- tilde.alt11

- tilde.alt12

- tilde.alt13

- tilde.alt2

- tilde.alt3

- tilde.alt4

- tilde.alt5

- tilde.alt6

- tilde.alt7

- tilde.alt8

- tilde.alt9

- two.alt

- uni00AD

- uni02E502E502E6

- uni02E502E502E7

- uni02E502E502E8

- uni02E502E502E9

- uni02E502E6

- uni02E502E602E5

- uni02E502E602E6

- uni02E502E602E7

- uni02E502E602E8

- uni02E502E602E9

- uni02E502E7

- uni02E502E702E5

- uni02E502E702E6

- uni02E502E702E7

- uni02E502E702E8

- uni02E502E702E9

- uni02E502E8

- uni02E502E802E5

- uni02E502E802E6

- uni02E502E802E7

- uni02E502E802E8

- uni02E502E802E9

- uni02E502E9

- uni02E502E902E5

- uni02E502E902E6

- uni02E502E902E7

- uni02E502E902E8

- uni02E502E902E9

- uni02E602E5

- uni02E602E502E5

- uni02E602E502E6

- uni02E602E502E7

- uni02E602E502E8

- uni02E602E502E9

- uni02E602E602E5

- uni02E602E602E7

- uni02E602E602E8

- uni02E602E602E9

- uni02E602E7

- uni02E602E702E5

- uni02E602E702E6

- uni02E602E702E7

- uni02E602E702E8

- uni02E602E702E9

- uni02E602E8

- uni02E602E802E5

- uni02E602E802E6

- uni02E602E802E7

- uni02E602E802E8

- uni02E602E802E9

- uni02E602E9

- uni02E602E902E5

- uni02E602E902E6

- uni02E602E902E7

- uni02E602E902E8

- uni02E602E902E9

- uni02E702E5

- uni02E702E502E5

- uni02E702E502E6

- uni02E702E502E7

- uni02E702E502E8

- uni02E702E502E9

- uni02E702E6

- uni02E702E602E5

- uni02E702E602E6

- uni02E702E602E7

- uni02E702E602E8

- uni02E702E602E9

- uni02E702E702E5

- uni02E702E702E6

- uni02E702E702E8

- uni02E702E702E9

- uni02E702E8

- uni02E702E802E5

- uni02E702E802E6

- uni02E702E802E7

- uni02E702E802E8

- uni02E702E802E9

- uni02E702E9

- uni02E702E902E5

- uni02E702E902E6

- uni02E702E902E7

- uni02E702E902E8

- uni02E702E902E9

- uni02E802E5

- uni02E802E502E5

- uni02E802E502E6

- uni02E802E502E7

- uni02E802E502E8

- uni02E802E502E9

- uni02E802E6

- uni02E802E602E5

- uni02E802E602E6

- uni02E802E602E7

- uni02E802E602E8

- uni02E802E602E9

- uni02E802E7

- uni02E802E702E5

- uni02E802E702E6

- uni02E802E702E7

- uni02E802E702E8

- uni02E802E702E9

- uni02E802E802E5

- uni02E802E802E6

- uni02E802E802E7

- uni02E802E802E9

- uni02E802E9

- uni02E802E902E5

- uni02E802E902E6

- uni02E802E902E7

- uni02E802E902E8

- uni02E802E902E9

- uni02E902E5

- uni02E902E502E5

- uni02E902E502E6

- uni02E902E502E7

- uni02E902E502E8

- uni02E902E502E9

- uni02E902E6

- uni02E902E602E5

- uni02E902E602E6

- uni02E902E602E7

- uni02E902E602E8

- uni02E902E602E9

- uni02E902E7

- uni02E902E702E5

- uni02E902E702E6

- uni02E902E702E7

- uni02E902E702E8

- uni02E902E702E9

- uni02E902E8

- uni02E902E802E5

- uni02E902E802E6

- uni02E902E802E7

- uni02E902E802E8

- uni02E902E802E9

- uni02E902E902E5

- uni02E902E902E6

- uni02E902E902E7

- uni02E902E902E8

- uni03B1030403130300

- uni03B1030403130301

- uni03B1030403140300

- uni03B1030403140301

- uni03B1030603130300

- uni03B1030603130301

- uni03B1030603140300

- uni03B1030603140301

- uni03B9030403130300

- uni03B9030403130301

- uni03B9030403140300

- uni03B9030403140301

- uni03B9030603130300

- uni03B9030603130301

- uni03B9030603140300

- uni03B9030603140301

- uni03B9030803040300

- uni03B9030803040301

- uni03B9030803060300

- uni03B9030803060301

- uni03C5030403130300

- uni03C5030403130301

- uni03C5030403140300

- uni03C5030403140301

- uni03C5030603130300

- uni03C5030603130301

- uni03C5030603140300

- uni03C5030603140301

- uni03C5030803040300

- uni03C5030803040301

- uni03C5030803060300

- uni03C5030803060301

- uni0431.loclSRB

- uni0433.loclSRB

- uni0434.loclSRB

- uni043F.loclSRB

- uni0441.loclSRB

- uni0448.loclSRB

- uni05B105BD

- uni05B205BD

- uni05B305BD

- zero.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/Tinos/googlefonts/ttf does not have an article.</p>
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
<li>U+02CD MODIFIER LETTER LOW MACRON: try adding lisu</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: elbasan, glagolitic, math, coptic, gothic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar</li>
<li>U+030E COMBINING DOUBLE VERTICAL LINE ABOVE: try adding ethiopic</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0310 COMBINING CANDRABINDU: try adding one of: math, sunuwar</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding one of: old-permic, todhri</li>
<li>U+0314 COMBINING REVERSED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0315 COMBINING COMMA ABOVE RIGHT: try adding math</li>
<li>U+0316 COMBINING GRAVE ACCENT BELOW: not included in any glyphset definition</li>
<li>U+0317 COMBINING ACUTE ACCENT BELOW: not included in any glyphset definition</li>
<li>U+0318 COMBINING LEFT TACK BELOW: not included in any glyphset definition</li>
<li>U+0319 COMBINING RIGHT TACK BELOW: not included in any glyphset definition</li>
<li>U+031A COMBINING LEFT ANGLE ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+031C COMBINING LEFT HALF RING BELOW: not included in any glyphset definition</li>
<li>U+031D COMBINING UP TACK BELOW: not included in any glyphset definition</li>
<li>U+031E COMBINING DOWN TACK BELOW: not included in any glyphset definition</li>
<li>U+031F COMBINING PLUS SIGN BELOW: not included in any glyphset definition</li>
<li>U+0320 COMBINING MINUS SIGN BELOW: try adding syriac</li>
<li>U+0321 COMBINING PALATALIZED HOOK BELOW: not included in any glyphset definition</li>
<li>U+0322 COMBINING RETROFLEX HOOK BELOW: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, duployan, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032A COMBINING BRIDGE BELOW: not included in any glyphset definition</li>
<li>U+032B COMBINING INVERTED DOUBLE ARCH BELOW: not included in any glyphset definition</li>
<li>U+032C COMBINING CARON BELOW: try adding math</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, thai, caucasian-albanian, gothic, sunuwar, tifinagh, syriac</li>
<li>U+0332 COMBINING LOW LINE: try adding math</li>
<li>U+0333 COMBINING DOUBLE LOW LINE: try adding math</li>
<li>U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+0339 COMBINING RIGHT HALF RING BELOW: not included in any glyphset definition</li>
<li>U+033A COMBINING INVERTED BRIDGE BELOW: try adding math</li>
<li>U+033B COMBINING SQUARE BELOW: not included in any glyphset definition</li>
<li>U+033C COMBINING SEAGULL BELOW: not included in any glyphset definition</li>
<li>U+033D COMBINING X ABOVE: not included in any glyphset definition</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+033F COMBINING DOUBLE OVERLINE: try adding coptic</li>
<li>U+0340 COMBINING GRAVE TONE MARK: not included in any glyphset definition</li>
<li>U+0341 COMBINING ACUTE TONE MARK: not included in any glyphset definition</li>
<li>U+0342 COMBINING GREEK PERISPOMENI: not included in any glyphset definition</li>
<li>U+0343 COMBINING GREEK KORONIS: not included in any glyphset definition</li>
<li>U+0344 COMBINING GREEK DIALYTIKA TONOS: not included in any glyphset definition</li>
<li>U+0345 COMBINING GREEK YPOGEGRAMMENI: not included in any glyphset definition</li>
<li>U+0346 COMBINING BRIDGE ABOVE: try adding math</li>
<li>U+0347 COMBINING EQUALS SIGN BELOW: not included in any glyphset definition</li>
<li>U+0348 COMBINING DOUBLE VERTICAL LINE BELOW: not included in any glyphset definition</li>
<li>U+0349 COMBINING LEFT ANGLE BELOW: not included in any glyphset definition</li>
<li>U+034A COMBINING NOT TILDE ABOVE: not included in any glyphset definition</li>
<li>U+034B COMBINING HOMOTHETIC ABOVE: not included in any glyphset definition</li>
<li>U+034C COMBINING ALMOST EQUAL TO ABOVE: not included in any glyphset definition</li>
<li>U+034D COMBINING LEFT RIGHT ARROW BELOW: try adding math</li>
<li>U+034E COMBINING UPWARDS ARROW BELOW: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+0350 COMBINING RIGHT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+0351 COMBINING LEFT HALF RING ABOVE: not included in any glyphset definition</li>
<li>U+0352 COMBINING FERMATA: not included in any glyphset definition</li>
<li>U+0353 COMBINING X BELOW: not included in any glyphset definition</li>
<li>U+0354 COMBINING LEFT ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0355 COMBINING RIGHT ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0356 COMBINING RIGHT ARROWHEAD AND UP ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0357 COMBINING RIGHT HALF RING ABOVE: not included in any glyphset definition</li>
<li>U+0358 COMBINING DOT ABOVE RIGHT: try adding osage</li>
<li>U+0359 COMBINING ASTERISK BELOW: not included in any glyphset definition</li>
<li>U+035A COMBINING DOUBLE RING BELOW: not included in any glyphset definition</li>
<li>U+035B COMBINING ZIGZAG ABOVE: not included in any glyphset definition</li>
<li>U+035C COMBINING DOUBLE BREVE BELOW: not included in any glyphset definition</li>
<li>U+035D COMBINING DOUBLE BREVE: not included in any glyphset definition</li>
<li>U+035E COMBINING DOUBLE MACRON: try adding one of: todhri, coptic, caucasian-albanian</li>
<li>U+035F COMBINING DOUBLE MACRON BELOW: not included in any glyphset definition</li>
<li>U+0360 COMBINING DOUBLE TILDE: not included in any glyphset definition</li>
<li>U+0361 COMBINING DOUBLE INVERTED BREVE: try adding coptic</li>
<li>U+0362 COMBINING DOUBLE RIGHTWARDS ARROW BELOW: not included in any glyphset definition</li>
<li>U+0363 COMBINING LATIN SMALL LETTER A: not included in any glyphset definition</li>
<li>U+0364 COMBINING LATIN SMALL LETTER E: not included in any glyphset definition</li>
<li>U+0365 COMBINING LATIN SMALL LETTER I: not included in any glyphset definition</li>
<li>U+0366 COMBINING LATIN SMALL LETTER O: not included in any glyphset definition</li>
<li>U+0367 COMBINING LATIN SMALL LETTER U: not included in any glyphset definition</li>
<li>U+0368 COMBINING LATIN SMALL LETTER C: not included in any glyphset definition</li>
<li>U+0369 COMBINING LATIN SMALL LETTER D: not included in any glyphset definition</li>
<li>U+036A COMBINING LATIN SMALL LETTER H: not included in any glyphset definition</li>
<li>U+036B COMBINING LATIN SMALL LETTER M: not included in any glyphset definition</li>
<li>U+036C COMBINING LATIN SMALL LETTER R: not included in any glyphset definition</li>
<li>U+036D COMBINING LATIN SMALL LETTER T: not included in any glyphset definition</li>
<li>U+036E COMBINING LATIN SMALL LETTER V: not included in any glyphset definition</li>
<li>U+036F COMBINING LATIN SMALL LETTER X: not included in any glyphset definition</li>
<li>U+1AB0 COMBINING DOUBLED CIRCUMFLEX ACCENT: not included in any glyphset definition</li>
<li>U+1AB1 COMBINING DIAERESIS-RING: not included in any glyphset definition</li>
<li>U+1AB2 COMBINING INFINITY: not included in any glyphset definition</li>
<li>U+1AB3 COMBINING DOWNWARDS ARROW: not included in any glyphset definition</li>
<li>U+1AB4 COMBINING TRIPLE DOT: not included in any glyphset definition</li>
<li>U+1AB5 COMBINING X-X BELOW: not included in any glyphset definition</li>
<li>U+1AB6 COMBINING WIGGLY LINE BELOW: not included in any glyphset definition</li>
<li>U+1AB7 COMBINING OPEN MARK BELOW: not included in any glyphset definition</li>
<li>U+1AB8 COMBINING DOUBLE OPEN MARK BELOW: not included in any glyphset definition</li>
<li>U+1AB9 COMBINING LIGHT CENTRALIZATION STROKE BELOW: not included in any glyphset definition</li>
<li>U+1ABA COMBINING STRONG CENTRALIZATION STROKE BELOW: not included in any glyphset definition</li>
<li>U+1ABB COMBINING PARENTHESES ABOVE: not included in any glyphset definition</li>
<li>U+1ABC COMBINING DOUBLE PARENTHESES ABOVE: not included in any glyphset definition</li>
<li>U+1ABD COMBINING PARENTHESES BELOW: not included in any glyphset definition</li>
<li>U+1ABE COMBINING PARENTHESES OVERLAY: not included in any glyphset definition</li>
<li>U+1DC0 COMBINING DOTTED GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+1DC1 COMBINING DOTTED ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+1DC2 COMBINING SNAKE BELOW: not included in any glyphset definition</li>
<li>U+1DC3 COMBINING SUSPENSION MARK: not included in any glyphset definition</li>
<li>U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition</li>
<li>U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition</li>
<li>U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition</li>
<li>U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition</li>
<li>U+1DC8 COMBINING GRAVE-ACUTE-GRAVE: not included in any glyphset definition</li>
<li>U+1DC9 COMBINING ACUTE-GRAVE-ACUTE: not included in any glyphset definition</li>
<li>U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition</li>
<li>U+1DCB COMBINING BREVE-MACRON: not included in any glyphset definition</li>
<li>U+1DCC COMBINING MACRON-BREVE: not included in any glyphset definition</li>
<li>U+1DCD COMBINING DOUBLE CIRCUMFLEX ABOVE: try adding coptic</li>
<li>U+1DCE COMBINING OGONEK ABOVE: not included in any glyphset definition</li>
<li>U+1DCF COMBINING ZIGZAG BELOW: not included in any glyphset definition</li>
<li>U+1DD0 COMBINING IS BELOW: not included in any glyphset definition</li>
<li>U+1DD1 COMBINING UR ABOVE: not included in any glyphset definition</li>
<li>U+1DD2 COMBINING US ABOVE: not included in any glyphset definition</li>
<li>U+1DD3 COMBINING LATIN SMALL LETTER FLATTENED OPEN A ABOVE: not included in any glyphset definition</li>
<li>U+1DD4 COMBINING LATIN SMALL LETTER AE: not included in any glyphset definition</li>
<li>U+1DD5 COMBINING LATIN SMALL LETTER AO: not included in any glyphset definition</li>
<li>U+1DD6 COMBINING LATIN SMALL LETTER AV: not included in any glyphset definition</li>
<li>U+1DD7 COMBINING LATIN SMALL LETTER C CEDILLA: not included in any glyphset definition</li>
<li>U+1DD8 COMBINING LATIN SMALL LETTER INSULAR D: not included in any glyphset definition</li>
<li>U+1DD9 COMBINING LATIN SMALL LETTER ETH: not included in any glyphset definition</li>
<li>U+1DDA COMBINING LATIN SMALL LETTER G: not included in any glyphset definition</li>
<li>U+1DDB COMBINING LATIN LETTER SMALL CAPITAL G: not included in any glyphset definition</li>
<li>U+1DDC COMBINING LATIN SMALL LETTER K: not included in any glyphset definition</li>
<li>U+1DDD COMBINING LATIN SMALL LETTER L: not included in any glyphset definition</li>
<li>U+1DDE COMBINING LATIN LETTER SMALL CAPITAL L: not included in any glyphset definition</li>
<li>U+1DDF COMBINING LATIN LETTER SMALL CAPITAL M: not included in any glyphset definition</li>
<li>U+1DE0 COMBINING LATIN SMALL LETTER N: not included in any glyphset definition</li>
<li>U+1DE1 COMBINING LATIN LETTER SMALL CAPITAL N: not included in any glyphset definition</li>
<li>U+1DE2 COMBINING LATIN LETTER SMALL CAPITAL R: not included in any glyphset definition</li>
<li>U+1DE3 COMBINING LATIN SMALL LETTER R ROTUNDA: not included in any glyphset definition</li>
<li>U+1DE4 COMBINING LATIN SMALL LETTER S: not included in any glyphset definition</li>
<li>U+1DE5 COMBINING LATIN SMALL LETTER LONG S: not included in any glyphset definition</li>
<li>U+1DE6 COMBINING LATIN SMALL LETTER Z: not included in any glyphset definition</li>
<li>U+1DE7 COMBINING LATIN SMALL LETTER ALPHA: not included in any glyphset definition</li>
<li>U+1DE8 COMBINING LATIN SMALL LETTER B: not included in any glyphset definition</li>
<li>U+1DE9 COMBINING LATIN SMALL LETTER BETA: not included in any glyphset definition</li>
<li>U+1DEA COMBINING LATIN SMALL LETTER SCHWA: not included in any glyphset definition</li>
<li>U+1DEB COMBINING LATIN SMALL LETTER F: not included in any glyphset definition</li>
<li>U+1DEC COMBINING LATIN SMALL LETTER L WITH DOUBLE MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+1DED COMBINING LATIN SMALL LETTER O WITH LIGHT CENTRALIZATION STROKE: not included in any glyphset definition</li>
<li>U+1DEE COMBINING LATIN SMALL LETTER P: not included in any glyphset definition</li>
<li>U+1DEF COMBINING LATIN SMALL LETTER ESH: not included in any glyphset definition</li>
<li>U+1DF0 COMBINING LATIN SMALL LETTER U WITH LIGHT CENTRALIZATION STROKE: not included in any glyphset definition</li>
<li>U+1DF1 COMBINING LATIN SMALL LETTER W: not included in any glyphset definition</li>
<li>U+1DF2 COMBINING LATIN SMALL LETTER A WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF3 COMBINING LATIN SMALL LETTER O WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF4 COMBINING LATIN SMALL LETTER U WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF5 COMBINING UP TACK ABOVE: not included in any glyphset definition</li>
<li>U+1DFB COMBINING DELETION MARK: try adding newa</li>
<li>U+1DFC COMBINING DOUBLE INVERTED BREVE BELOW: not included in any glyphset definition</li>
<li>U+1DFD COMBINING ALMOST EQUAL TO BELOW: not included in any glyphset definition</li>
<li>U+1DFE COMBINING LEFT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+1DFF COMBINING RIGHT ARROWHEAD AND DOWN ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, arabic, yi</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2016 DOUBLE VERTICAL LINE: try adding math</li>
<li>U+2017 DOUBLE LOW LINE: try adding math</li>
<li>U+201B SINGLE HIGH-REVERSED-9 QUOTATION MARK: try adding adlam</li>
<li>U+201F DOUBLE HIGH-REVERSED-9 QUOTATION MARK: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2023 TRIANGULAR BULLET: not included in any glyphset definition</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+2028 LINE SEPARATOR: not included in any glyphset definition</li>
<li>U+2029 PARAGRAPH SEPARATOR: not included in any glyphset definition</li>
<li>U+202A LEFT-TO-RIGHT EMBEDDING: not included in any glyphset definition</li>
<li>U+202B RIGHT-TO-LEFT EMBEDDING: not included in any glyphset definition</li>
<li>U+202C POP DIRECTIONAL FORMATTING: not included in any glyphset definition</li>
<li>U+202D LEFT-TO-RIGHT OVERRIDE: not included in any glyphset definition</li>
<li>U+202E RIGHT-TO-LEFT OVERRIDE: try adding tifinagh</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: phags-pa, yi, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2031 PER TEN THOUSAND SIGN: not included in any glyphset definition</li>
<li>U+2034 TRIPLE PRIME: try adding math</li>
<li>U+2035 REVERSED PRIME: try adding math</li>
<li>U+2036 REVERSED DOUBLE PRIME: try adding math</li>
<li>U+2037 REVERSED TRIPLE PRIME: try adding math</li>
<li>U+2038 CARET: try adding math</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+203C DOUBLE EXCLAMATION MARK: try adding math</li>
<li>U+203D INTERROBANG: not included in any glyphset definition</li>
<li>U+203E OVERLINE: not included in any glyphset definition</li>
<li>U+203F UNDERTIE: not included in any glyphset definition</li>
<li>U+2040 CHARACTER TIE: try adding math</li>
<li>U+2041 CARET INSERTION POINT: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+2043 HYPHEN BULLET: try adding math</li>
<li>U+2045 LEFT SQUARE BRACKET WITH QUILL: not included in any glyphset definition</li>
<li>U+2046 RIGHT SQUARE BRACKET WITH QUILL: not included in any glyphset definition</li>
<li>U+2047 DOUBLE QUESTION MARK: try adding math</li>
<li>U+2048 QUESTION EXCLAMATION MARK: try adding mongolian</li>
<li>U+2049 EXCLAMATION QUESTION MARK: try adding mongolian</li>
<li>U+204A TIRONIAN SIGN ET: not included in any glyphset definition</li>
<li>U+204B REVERSED PILCROW SIGN: not included in any glyphset definition</li>
<li>U+204C BLACK LEFTWARDS BULLET: not included in any glyphset definition</li>
<li>U+204D BLACK RIGHTWARDS BULLET: not included in any glyphset definition</li>
<li>U+204E LOW ASTERISK: not included in any glyphset definition</li>
<li>U+204F REVERSED SEMICOLON: try adding one of: arabic, adlam</li>
<li>U+2050 CLOSE UP: try adding math</li>
<li>U+2051 TWO ASTERISKS ALIGNED VERTICALLY: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2053 SWUNG DASH: try adding coptic</li>
<li>U+2054 INVERTED UNDERTIE: not included in any glyphset definition</li>
<li>U+2055 FLOWER PUNCTUATION MARK: try adding syloti-nagri</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2057 QUADRUPLE PRIME: try adding math</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205A TWO DOT PUNCTUATION: try adding one of: lycian, old-hungarian, glagolitic, georgian, old-turkic, carian</li>
<li>U+205B FOUR DOT MARK: not included in any glyphset definition</li>
<li>U+205C DOTTED CROSS: not included in any glyphset definition</li>
<li>U+205D TRICOLON: try adding one of: old-hungarian, carian, meroitic-hieroglyphs, meroitic</li>
<li>U+205E VERTICAL FOUR DOTS: try adding old-hungarian</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2060 WORD JOINER: not included in any glyphset definition</li>
<li>U+2061 FUNCTION APPLICATION: not included in any glyphset definition</li>
<li>U+2062 INVISIBLE TIMES: not included in any glyphset definition</li>
<li>U+2063 INVISIBLE SEPARATOR: not included in any glyphset definition</li>
<li>U+2064 INVISIBLE PLUS: not included in any glyphset definition</li>
<li>U+2066 LEFT-TO-RIGHT ISOLATE: not included in any glyphset definition</li>
<li>U+2067 RIGHT-TO-LEFT ISOLATE: not included in any glyphset definition</li>
<li>U+2068 FIRST STRONG ISOLATE: not included in any glyphset definition</li>
<li>U+2069 POP DIRECTIONAL ISOLATE: not included in any glyphset definition</li>
<li>U+206A INHIBIT SYMMETRIC SWAPPING: not included in any glyphset definition</li>
<li>U+206B ACTIVATE SYMMETRIC SWAPPING: not included in any glyphset definition</li>
<li>U+206C INHIBIT ARABIC FORM SHAPING: not included in any glyphset definition</li>
<li>U+206D ACTIVATE ARABIC FORM SHAPING: not included in any glyphset definition</li>
<li>U+206E NATIONAL DIGIT SHAPES: not included in any glyphset definition</li>
<li>U+206F NOMINAL DIGIT SHAPES: not included in any glyphset definition</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2071 SUPERSCRIPT LATIN SMALL LETTER I: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+207A SUPERSCRIPT PLUS SIGN: try adding math</li>
<li>U+207B SUPERSCRIPT MINUS: try adding math</li>
<li>U+207C SUPERSCRIPT EQUALS SIGN: try adding math</li>
<li>U+207D SUPERSCRIPT LEFT PARENTHESIS: try adding math</li>
<li>U+207E SUPERSCRIPT RIGHT PARENTHESIS: try adding math</li>
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
<li>U+208A SUBSCRIPT PLUS SIGN: try adding math</li>
<li>U+208B SUBSCRIPT MINUS: try adding math</li>
<li>U+208C SUBSCRIPT EQUALS SIGN: try adding math</li>
<li>U+208D SUBSCRIPT LEFT PARENTHESIS: try adding math</li>
<li>U+208E SUBSCRIPT RIGHT PARENTHESIS: try adding math</li>
<li>U+2090 LATIN SUBSCRIPT SMALL LETTER A: try adding math</li>
<li>U+2091 LATIN SUBSCRIPT SMALL LETTER E: try adding math</li>
<li>U+2092 LATIN SUBSCRIPT SMALL LETTER O: try adding math</li>
<li>U+2093 LATIN SUBSCRIPT SMALL LETTER X: try adding math</li>
<li>U+2094 LATIN SUBSCRIPT SMALL LETTER SCHWA: try adding math</li>
<li>U+2095 LATIN SUBSCRIPT SMALL LETTER H: try adding math</li>
<li>U+2096 LATIN SUBSCRIPT SMALL LETTER K: try adding math</li>
<li>U+2097 LATIN SUBSCRIPT SMALL LETTER L: try adding math</li>
<li>U+2098 LATIN SUBSCRIPT SMALL LETTER M: try adding math</li>
<li>U+2099 LATIN SUBSCRIPT SMALL LETTER N: try adding math</li>
<li>U+209A LATIN SUBSCRIPT SMALL LETTER P: try adding math</li>
<li>U+209B LATIN SUBSCRIPT SMALL LETTER S: try adding math</li>
<li>U+209C LATIN SUBSCRIPT SMALL LETTER T: try adding math</li>
<li>U+20F0 COMBINING ASTERISK ABOVE: try adding one of: grantha, devanagari</li>
<li>U+2100 ACCOUNT OF: try adding math</li>
<li>U+2101 ADDRESSED TO THE SUBJECT: try adding math</li>
<li>U+2102 DOUBLE-STRUCK CAPITAL C: try adding math</li>
<li>U+2103 DEGREE CELSIUS: try adding math</li>
<li>U+2104 CENTRE LINE SYMBOL: try adding math</li>
<li>U+2105 CARE OF: try adding math</li>
<li>U+2106 CADA UNA: try adding math</li>
<li>U+2107 EULER CONSTANT: try adding math</li>
<li>U+2108 SCRUPLE: try adding math</li>
<li>U+2109 DEGREE FAHRENHEIT: try adding math</li>
<li>U+210A SCRIPT SMALL G: try adding math</li>
<li>U+210B SCRIPT CAPITAL H: try adding math</li>
<li>U+210C BLACK-LETTER CAPITAL H: try adding math</li>
<li>U+210D DOUBLE-STRUCK CAPITAL H: try adding math</li>
<li>U+210E PLANCK CONSTANT: try adding math</li>
<li>U+210F PLANCK CONSTANT OVER TWO PI: try adding math</li>
<li>U+2110 SCRIPT CAPITAL I: try adding math</li>
<li>U+2111 BLACK-LETTER CAPITAL I: try adding math</li>
<li>U+2112 SCRIPT CAPITAL L: try adding math</li>
<li>U+2114 L B BAR SYMBOL: try adding math</li>
<li>U+2115 DOUBLE-STRUCK CAPITAL N: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2118 SCRIPT CAPITAL P: try adding math</li>
<li>U+2119 DOUBLE-STRUCK CAPITAL P: try adding math</li>
<li>U+211A DOUBLE-STRUCK CAPITAL Q: try adding math</li>
<li>U+211B SCRIPT CAPITAL R: try adding math</li>
<li>U+211C BLACK-LETTER CAPITAL R: try adding math</li>
<li>U+211D DOUBLE-STRUCK CAPITAL R: try adding math</li>
<li>U+211E PRESCRIPTION TAKE: try adding math</li>
<li>U+211F RESPONSE: try adding math</li>
<li>U+2120 SERVICE MARK: try adding math</li>
<li>U+2121 TELEPHONE SIGN: try adding math</li>
<li>U+2123 VERSICLE: try adding math</li>
<li>U+2124 DOUBLE-STRUCK CAPITAL Z: try adding math</li>
<li>U+2125 OUNCE SIGN: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2127 INVERTED OHM SIGN: try adding math</li>
<li>U+2128 BLACK-LETTER CAPITAL Z: try adding math</li>
<li>U+2129 TURNED GREEK SMALL LETTER IOTA: try adding math</li>
<li>U+212A KELVIN SIGN: try adding math</li>
<li>U+212B ANGSTROM SIGN: try adding math</li>
<li>U+212C SCRIPT CAPITAL B: try adding math</li>
<li>U+212D BLACK-LETTER CAPITAL C: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+212F SCRIPT SMALL E: try adding math</li>
<li>U+2130 SCRIPT CAPITAL E: try adding math</li>
<li>U+2131 SCRIPT CAPITAL F: try adding math</li>
<li>U+2132 TURNED CAPITAL F: try adding math</li>
<li>U+2133 SCRIPT CAPITAL M: try adding math</li>
<li>U+2134 SCRIPT SMALL O: try adding math</li>
<li>U+2135 ALEF SYMBOL: try adding math</li>
<li>U+2136 BET SYMBOL: try adding math</li>
<li>U+2137 GIMEL SYMBOL: try adding math</li>
<li>U+2138 DALET SYMBOL: try adding math</li>
<li>U+2139 INFORMATION SOURCE: try adding math</li>
<li>U+213A ROTATED CAPITAL Q: try adding math</li>
<li>U+213B FACSIMILE SIGN: try adding math</li>
<li>U+213C DOUBLE-STRUCK SMALL PI: try adding math</li>
<li>U+213D DOUBLE-STRUCK SMALL GAMMA: try adding math</li>
<li>U+213E DOUBLE-STRUCK CAPITAL GAMMA: try adding math</li>
<li>U+213F DOUBLE-STRUCK CAPITAL PI: try adding math</li>
<li>U+2140 DOUBLE-STRUCK N-ARY SUMMATION: try adding math</li>
<li>U+2141 TURNED SANS-SERIF CAPITAL G: try adding math</li>
<li>U+2142 TURNED SANS-SERIF CAPITAL L: try adding math</li>
<li>U+2143 REVERSED SANS-SERIF CAPITAL L: try adding math</li>
<li>U+2144 TURNED SANS-SERIF CAPITAL Y: try adding math</li>
<li>U+2145 DOUBLE-STRUCK ITALIC CAPITAL D: try adding math</li>
<li>U+2146 DOUBLE-STRUCK ITALIC SMALL D: try adding math</li>
<li>U+2147 DOUBLE-STRUCK ITALIC SMALL E: try adding math</li>
<li>U+2148 DOUBLE-STRUCK ITALIC SMALL I: try adding math</li>
<li>U+2149 DOUBLE-STRUCK ITALIC SMALL J: try adding math</li>
<li>U+214A PROPERTY LINE: try adding math</li>
<li>U+214B TURNED AMPERSAND: try adding math</li>
<li>U+214C PER SIGN: try adding math</li>
<li>U+214D AKTIESELSKAB: try adding math</li>
<li>U+214E TURNED SMALL F: try adding math</li>
<li>U+214F SYMBOL FOR SAMARITAN SOURCE: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2184 LATIN SMALL LETTER REVERSED C: not included in any glyphset definition</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+21A8 UP DOWN ARROW WITH BASE: try adding math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, math, yi, tai-tham</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+221F RIGHT ANGLE: try adding math</li>
<li>U+2229 INTERSECTION: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2261 IDENTICAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+2302 HOUSE: try adding symbols</li>
<li>U+2310 REVERSED NOT SIGN: try adding math</li>
<li>U+2320 TOP HALF INTEGRAL: try adding math</li>
<li>U+2321 BOTTOM HALF INTEGRAL: try adding math</li>
<li>U+2500 BOX DRAWINGS LIGHT HORIZONTAL: try adding symbols2</li>
<li>U+2502 BOX DRAWINGS LIGHT VERTICAL: try adding symbols2</li>
<li>U+250C BOX DRAWINGS LIGHT DOWN AND RIGHT: try adding symbols2</li>
<li>U+2510 BOX DRAWINGS LIGHT DOWN AND LEFT: try adding symbols2</li>
<li>U+2514 BOX DRAWINGS LIGHT UP AND RIGHT: try adding symbols2</li>
<li>U+2518 BOX DRAWINGS LIGHT UP AND LEFT: try adding symbols2</li>
<li>U+251C BOX DRAWINGS LIGHT VERTICAL AND RIGHT: try adding symbols2</li>
<li>U+2524 BOX DRAWINGS LIGHT VERTICAL AND LEFT: try adding symbols2</li>
<li>U+252C BOX DRAWINGS LIGHT DOWN AND HORIZONTAL: try adding symbols2</li>
<li>U+2534 BOX DRAWINGS LIGHT UP AND HORIZONTAL: try adding symbols2</li>
<li>U+253C BOX DRAWINGS LIGHT VERTICAL AND HORIZONTAL: try adding symbols2</li>
<li>U+2550 BOX DRAWINGS DOUBLE HORIZONTAL: try adding symbols2</li>
<li>U+2551 BOX DRAWINGS DOUBLE VERTICAL: try adding symbols2</li>
<li>U+2552 BOX DRAWINGS DOWN SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+2553 BOX DRAWINGS DOWN DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+2554 BOX DRAWINGS DOUBLE DOWN AND RIGHT: try adding symbols2</li>
<li>U+2555 BOX DRAWINGS DOWN SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+2556 BOX DRAWINGS DOWN DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+2557 BOX DRAWINGS DOUBLE DOWN AND LEFT: try adding symbols2</li>
<li>U+2558 BOX DRAWINGS UP SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+2559 BOX DRAWINGS UP DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+255A BOX DRAWINGS DOUBLE UP AND RIGHT: try adding symbols2</li>
<li>U+255B BOX DRAWINGS UP SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+255C BOX DRAWINGS UP DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+255D BOX DRAWINGS DOUBLE UP AND LEFT: try adding symbols2</li>
<li>U+255E BOX DRAWINGS VERTICAL SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+255F BOX DRAWINGS VERTICAL DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+2560 BOX DRAWINGS DOUBLE VERTICAL AND RIGHT: try adding symbols2</li>
<li>U+2561 BOX DRAWINGS VERTICAL SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+2562 BOX DRAWINGS VERTICAL DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+2563 BOX DRAWINGS DOUBLE VERTICAL AND LEFT: try adding symbols2</li>
<li>U+2564 BOX DRAWINGS DOWN SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+2565 BOX DRAWINGS DOWN DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+2566 BOX DRAWINGS DOUBLE DOWN AND HORIZONTAL: try adding symbols2</li>
<li>U+2567 BOX DRAWINGS UP SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+2568 BOX DRAWINGS UP DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+2569 BOX DRAWINGS DOUBLE UP AND HORIZONTAL: try adding symbols2</li>
<li>U+256A BOX DRAWINGS VERTICAL SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+256B BOX DRAWINGS VERTICAL DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+256C BOX DRAWINGS DOUBLE VERTICAL AND HORIZONTAL: try adding symbols2</li>
<li>U+2580 UPPER HALF BLOCK: try adding symbols2</li>
<li>U+2584 LOWER HALF BLOCK: try adding symbols2</li>
<li>U+2588 FULL BLOCK: try adding symbols2</li>
<li>U+258C LEFT HALF BLOCK: try adding symbols2</li>
<li>U+2590 RIGHT HALF BLOCK: try adding symbols2</li>
<li>U+2591 LIGHT SHADE: try adding symbols2</li>
<li>U+2592 MEDIUM SHADE: try adding symbols2</li>
<li>U+2593 DARK SHADE: try adding symbols2</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25AA BLACK SMALL SQUARE: try adding symbols</li>
<li>U+25AB WHITE SMALL SQUARE: try adding symbols</li>
<li>U+25AC BLACK RECTANGLE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BA BLACK RIGHT-POINTING POINTER: try adding symbols</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C4 BLACK LEFT-POINTING POINTER: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+25D8 INVERSE BULLET: try adding symbols</li>
<li>U+25D9 INVERSE WHITE CIRCLE: try adding symbols</li>
<li>U+25E6 WHITE BULLET: try adding symbols</li>
<li>U+263A WHITE SMILING FACE: try adding symbols</li>
<li>U+263B BLACK SMILING FACE: try adding symbols</li>
<li>U+263C WHITE SUN WITH RAYS: try adding symbols</li>
<li>U+2640 FEMALE SIGN: try adding symbols</li>
<li>U+2642 MALE SIGN: try adding symbols</li>
<li>U+2660 BLACK SPADE SUIT: try adding symbols</li>
<li>U+2663 BLACK CLUB SUIT: try adding symbols</li>
<li>U+2665 BLACK HEART SUIT: try adding symbols</li>
<li>U+2666 BLACK DIAMOND SUIT: try adding symbols</li>
<li>U+266A EIGHTH NOTE: try adding one of: symbols, music</li>
<li>U+266B BEAMED EIGHTH NOTES: try adding one of: symbols, music</li>
<li>U+266F MUSIC SHARP SIGN: try adding one of: symbols, music, math</li>
<li>U+2E00 RIGHT ANGLE SUBSTITUTION MARKER: not included in any glyphset definition</li>
<li>U+2E01 RIGHT ANGLE DOTTED SUBSTITUTION MARKER: not included in any glyphset definition</li>
<li>U+2E02 LEFT SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E03 RIGHT SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E04 LEFT DOTTED SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E05 RIGHT DOTTED SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E06 RAISED INTERPOLATION MARKER: not included in any glyphset definition</li>
<li>U+2E07 RAISED DOTTED INTERPOLATION MARKER: not included in any glyphset definition</li>
<li>U+2E08 DOTTED TRANSPOSITION MARKER: not included in any glyphset definition</li>
<li>U+2E09 LEFT TRANSPOSITION BRACKET: not included in any glyphset definition</li>
<li>U+2E0A RIGHT TRANSPOSITION BRACKET: not included in any glyphset definition</li>
<li>U+2E0B RAISED SQUARE: not included in any glyphset definition</li>
<li>U+2E0C LEFT RAISED OMISSION BRACKET: not included in any glyphset definition</li>
<li>U+2E0D RIGHT RAISED OMISSION BRACKET: not included in any glyphset definition</li>
<li>U+2E0E EDITORIAL CORONIS: not included in any glyphset definition</li>
<li>U+2E0F PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E10 FORKED PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E11 REVERSED FORKED PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E12 HYPODIASTOLE: not included in any glyphset definition</li>
<li>U+2E13 DOTTED OBELOS: not included in any glyphset definition</li>
<li>U+2E14 DOWNWARDS ANCORA: not included in any glyphset definition</li>
<li>U+2E15 UPWARDS ANCORA: not included in any glyphset definition</li>
<li>U+2E16 DOTTED RIGHT-POINTING ANGLE: not included in any glyphset definition</li>
<li>U+2E17 DOUBLE OBLIQUE HYPHEN: try adding coptic</li>
<li>U+2E18 INVERTED INTERROBANG: not included in any glyphset definition</li>
<li>U+2E19 PALM BRANCH: not included in any glyphset definition</li>
<li>U+2E1A HYPHEN WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+2E1B TILDE WITH RING ABOVE: not included in any glyphset definition</li>
<li>U+2E1C LEFT LOW PARAPHRASE BRACKET: try adding nko</li>
<li>U+2E1D RIGHT LOW PARAPHRASE BRACKET: try adding nko</li>
<li>U+2E1E TILDE WITH DOT ABOVE: not included in any glyphset definition</li>
<li>U+2E1F TILDE WITH DOT BELOW: not included in any glyphset definition</li>
<li>U+2E20 LEFT VERTICAL BAR WITH QUILL: not included in any glyphset definition</li>
<li>U+2E21 RIGHT VERTICAL BAR WITH QUILL: not included in any glyphset definition</li>
<li>U+2E22 TOP LEFT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E23 TOP RIGHT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E24 BOTTOM LEFT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E25 BOTTOM RIGHT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E26 LEFT SIDEWAYS U BRACKET: not included in any glyphset definition</li>
<li>U+2E27 RIGHT SIDEWAYS U BRACKET: not included in any glyphset definition</li>
<li>U+2E28 LEFT DOUBLE PARENTHESIS: try adding adlam</li>
<li>U+2E29 RIGHT DOUBLE PARENTHESIS: try adding adlam</li>
<li>U+2E2A TWO DOTS OVER ONE DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2B ONE DOT OVER TWO DOTS PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2C SQUARED FOUR DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2D FIVE DOT MARK: not included in any glyphset definition</li>
<li>U+2E2E REVERSED QUESTION MARK: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E30 RING POINT: try adding one of: avestan, old-turkic</li>
<li>U+2E31 WORD SEPARATOR MIDDLE DOT: try adding one of: avestan, old-hungarian, kaithi, georgian, samaritan, carian, lydian</li>
<li>U+2E32 TURNED COMMA: not included in any glyphset definition</li>
<li>U+2E33 RAISED DOT: try adding coptic</li>
<li>U+2E34 RAISED COMMA: try adding coptic</li>
<li>U+2E35 TURNED SEMICOLON: not included in any glyphset definition</li>
<li>U+2E36 DAGGER WITH LEFT GUARD: not included in any glyphset definition</li>
<li>U+2E37 DAGGER WITH RIGHT GUARD: not included in any glyphset definition</li>
<li>U+2E38 TURNED DAGGER: not included in any glyphset definition</li>
<li>U+2E39 TOP HALF SECTION SIGN: not included in any glyphset definition</li>
<li>U+2E3A TWO-EM DASH: not included in any glyphset definition</li>
<li>U+2E3B THREE-EM DASH: not included in any glyphset definition</li>
<li>U+2E3C STENOGRAPHIC FULL STOP: try adding duployan</li>
<li>U+2E3D VERTICAL SIX DOTS: not included in any glyphset definition</li>
<li>U+2E3E WIGGLY VERTICAL LINE: not included in any glyphset definition</li>
<li>U+2E3F CAPITULUM: not included in any glyphset definition</li>
<li>U+2E40 DOUBLE HYPHEN: not included in any glyphset definition</li>
<li>U+2E41 REVERSED COMMA: try adding one of: arabic, old-hungarian, adlam</li>
<li>U+2E42 DOUBLE LOW-REVERSED-9 QUOTATION MARK: not included in any glyphset definition</li>
<li>U+A717 MODIFIER LETTER DOT VERTICAL BAR: not included in any glyphset definition</li>
<li>U+A718 MODIFIER LETTER DOT SLASH: not included in any glyphset definition</li>
<li>U+A719 MODIFIER LETTER DOT HORIZONTAL BAR: not included in any glyphset definition</li>
<li>U+A71A MODIFIER LETTER LOWER RIGHT CORNER ANGLE: not included in any glyphset definition</li>
<li>U+A71B MODIFIER LETTER RAISED UP ARROW: not included in any glyphset definition</li>
<li>U+A71C MODIFIER LETTER RAISED DOWN ARROW: not included in any glyphset definition</li>
<li>U+A71D MODIFIER LETTER RAISED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+A71E MODIFIER LETTER RAISED INVERTED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+A71F MODIFIER LETTER LOW INVERTED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+AB30 LATIN SMALL LETTER BARRED ALPHA: not included in any glyphset definition</li>
<li>U+AB31 LATIN SMALL LETTER A REVERSED-SCHWA: not included in any glyphset definition</li>
<li>U+AB32 LATIN SMALL LETTER BLACKLETTER E: not included in any glyphset definition</li>
<li>U+AB33 LATIN SMALL LETTER BARRED E: not included in any glyphset definition</li>
<li>U+AB34 LATIN SMALL LETTER E WITH FLOURISH: not included in any glyphset definition</li>
<li>U+AB35 LATIN SMALL LETTER LENIS F: not included in any glyphset definition</li>
<li>U+AB36 LATIN SMALL LETTER SCRIPT G WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB37 LATIN SMALL LETTER L WITH INVERTED LAZY S: not included in any glyphset definition</li>
<li>U+AB38 LATIN SMALL LETTER L WITH DOUBLE MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+AB39 LATIN SMALL LETTER L WITH MIDDLE RING: not included in any glyphset definition</li>
<li>U+AB3A LATIN SMALL LETTER M WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3B LATIN SMALL LETTER N WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3C LATIN SMALL LETTER ENG WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3D LATIN SMALL LETTER BLACKLETTER O: not included in any glyphset definition</li>
<li>U+AB3E LATIN SMALL LETTER BLACKLETTER O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB3F LATIN SMALL LETTER OPEN O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB40 LATIN SMALL LETTER INVERTED OE: not included in any glyphset definition</li>
<li>U+AB41 LATIN SMALL LETTER TURNED OE WITH STROKE: not included in any glyphset definition</li>
<li>U+AB42 LATIN SMALL LETTER TURNED OE WITH HORIZONTAL STROKE: not included in any glyphset definition</li>
<li>U+AB43 LATIN SMALL LETTER TURNED O OPEN-O: not included in any glyphset definition</li>
<li>U+AB44 LATIN SMALL LETTER TURNED O OPEN-O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB45 LATIN SMALL LETTER STIRRUP R: not included in any glyphset definition</li>
<li>U+AB46 LATIN LETTER SMALL CAPITAL R WITH RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB47 LATIN SMALL LETTER R WITHOUT HANDLE: not included in any glyphset definition</li>
<li>U+AB48 LATIN SMALL LETTER DOUBLE R: not included in any glyphset definition</li>
<li>U+AB49 LATIN SMALL LETTER R WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB4A LATIN SMALL LETTER DOUBLE R WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB4B LATIN SMALL LETTER SCRIPT R: not included in any glyphset definition</li>
<li>U+AB4C LATIN SMALL LETTER SCRIPT R WITH RING: not included in any glyphset definition</li>
<li>U+AB4D LATIN SMALL LETTER BASELINE ESH: not included in any glyphset definition</li>
<li>U+AB4E LATIN SMALL LETTER U WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB4F LATIN SMALL LETTER U BAR WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB50 LATIN SMALL LETTER UI: not included in any glyphset definition</li>
<li>U+AB51 LATIN SMALL LETTER TURNED UI: not included in any glyphset definition</li>
<li>U+AB52 LATIN SMALL LETTER U WITH LEFT HOOK: not included in any glyphset definition</li>
<li>U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition</li>
<li>U+AB54 LATIN SMALL LETTER CHI WITH LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB55 LATIN SMALL LETTER CHI WITH LOW LEFT SERIF: not included in any glyphset definition</li>
<li>U+AB56 LATIN SMALL LETTER X WITH LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB57 LATIN SMALL LETTER X WITH LONG LEFT LEG: not included in any glyphset definition</li>
<li>U+AB58 LATIN SMALL LETTER X WITH LONG LEFT LEG AND LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB59 LATIN SMALL LETTER X WITH LONG LEFT LEG WITH SERIF: not included in any glyphset definition</li>
<li>U+AB5A LATIN SMALL LETTER Y WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB5B MODIFIER BREVE WITH INVERTED BREVE: not included in any glyphset definition</li>
<li>U+AB5C MODIFIER LETTER SMALL HENG: not included in any glyphset definition</li>
<li>U+AB5D MODIFIER LETTER SMALL L WITH INVERTED LAZY S: not included in any glyphset definition</li>
<li>U+AB5E MODIFIER LETTER SMALL L WITH MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+AB5F MODIFIER LETTER SMALL U WITH LEFT HOOK: not included in any glyphset definition</li>
<li>U+AB60 LATIN SMALL LETTER SAKHA YAT: not included in any glyphset definition</li>
<li>U+AB61 LATIN SMALL LETTER IOTIFIED E: not included in any glyphset definition</li>
<li>U+AB62 LATIN SMALL LETTER OPEN OE: not included in any glyphset definition</li>
<li>U+AB63 LATIN SMALL LETTER UO: not included in any glyphset definition</li>
<li>U+AB64 LATIN SMALL LETTER INVERTED ALPHA: not included in any glyphset definition</li>
<li>U+AB65 GREEK LETTER SMALL CAPITAL OMEGA: not included in any glyphset definition</li>
<li>U+F001 : not included in any glyphset definition</li>
<li>U+F002 : not included in any glyphset definition</li>
<li>U+F004 : not included in any glyphset definition</li>
<li>U+F005 : not included in any glyphset definition</li>
<li>U+F00A : not included in any glyphset definition</li>
<li>U+F00B : not included in any glyphset definition</li>
<li>U+F00C : not included in any glyphset definition</li>
<li>U+F00D : not included in any glyphset definition</li>
<li>U+F00E : not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FE20 COMBINING LIGATURE LEFT HALF: try adding caucasian-albanian</li>
<li>U+FE21 COMBINING LIGATURE RIGHT HALF: try adding caucasian-albanian</li>
<li>U+FE22 COMBINING DOUBLE TILDE LEFT HALF: try adding caucasian-albanian</li>
<li>U+FE23 COMBINING DOUBLE TILDE RIGHT HALF: try adding caucasian-albanian</li>
<li>U+FE24 COMBINING MACRON LEFT HALF: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE25 COMBINING MACRON RIGHT HALF: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE26 COMBINING CONJOINING MACRON: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE27 COMBINING LIGATURE LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE28 COMBINING LIGATURE RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE29 COMBINING TILDE LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2A COMBINING TILDE RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2B COMBINING MACRON LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2C COMBINING MACRON RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2D COMBINING CONJOINING MACRON BELOW: try adding caucasian-albanian</li>
<li>U+FFFC OBJECT REPLACEMENT CHARACTER: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>greek</code>, <code>greek-ext</code>, <code>hebrew</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ i̍ i̐ i̓ i᷆ i᷇ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̅ i̇ i̎ i̒ i̔ i̽ i̾ i̿ i͂ i͆ i͊ i͋ i͌ i͐ i͑ i͒ i͗ i͛ iͣ iͤ</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Belarusian (Cyrl, 10,064,517 speakers), Zapotec (Latn, 490,000 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Gulay (Latn, 250,478 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Longto (Latn, 5,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Fur (Latn, 1,230,163 speakers), Ejagham (Latn, 120,000 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Cicipu (Latn, 44,000 speakers), Aghem (Latn, 38,843 speakers), Kaska (Latn, 125 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Bafut (Latn, 158,146 speakers), Avokaya (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Dutch (Latn, 31,709,104 speakers), Ekpeye (Latn, 226,000 speakers), Makaa (Latn, 221,000 speakers), Northern Tutchone (Latn, 85 speakers), Yala (Latn, 200,000 speakers), Keliko (Latn, 63,000 speakers), Navajo (Latn, 166,319 speakers), Lugbara (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Bete-Bendi (Latn, 100,000 speakers), Mfumte (Latn, 79,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Teke-Ebo (Latn, 260,000 speakers), South Central Banda (Latn, 244,000 speakers), Abua (Latn, 25,000 speakers), Han (Latn, 6 speakers), Ikwere (Latn, 717,000 speakers), Nzakara (Latn, 50,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* B (U+0042): B&lt;&lt;1117.5,826.0&gt;-&lt;1029.0,734.0&gt;-&lt;871.0,713.0&gt;&gt;/B&lt;&lt;871.0,713.0&gt;-&lt;1026.0,700.0&gt;-&lt;1111.0,620.5&gt;&gt; = 12.365120967464875

* Beta (U+0392): B&lt;&lt;1117.5,826.0&gt;-&lt;1029.0,734.0&gt;-&lt;871.0,713.0&gt;&gt;/B&lt;&lt;871.0,713.0&gt;-&lt;1026.0,700.0&gt;-&lt;1111.0,620.5&gt;&gt; = 12.365120967464875

* uni0181 (U+0181): B&lt;&lt;1221.5,826.0&gt;-&lt;1133.0,734.0&gt;-&lt;975.0,713.0&gt;&gt;/B&lt;&lt;975.0,713.0&gt;-&lt;1130.0,700.0&gt;-&lt;1215.0,620.5&gt;&gt; = 12.365120967464875

* uni0243 (U+0243): B&lt;&lt;1117.5,826.0&gt;-&lt;1029.0,734.0&gt;-&lt;871.0,713.0&gt;&gt;/B&lt;&lt;871.0,713.0&gt;-&lt;1026.0,700.0&gt;-&lt;1111.0,620.5&gt;&gt; = 12.365120967464875

* uni03D2 (U+03D2): L&lt;&lt;714.0,718.0&gt;--&lt;709.0,675.0&gt;&gt;/B&lt;&lt;709.0,675.0&gt;-&lt;761.0,870.0&gt;-&lt;854.0,1027.0&gt;&gt; = 8.29890256299905

* uni03D3 (U+03D3): L&lt;&lt;965.0,718.0&gt;--&lt;960.0,675.0&gt;&gt;/B&lt;&lt;960.0,675.0&gt;-&lt;1012.0,870.0&gt;-&lt;1105.0,1027.0&gt;&gt; = 8.29890256299905

* uni03D4 (U+03D4): L&lt;&lt;714.0,718.0&gt;--&lt;709.0,675.0&gt;&gt;/B&lt;&lt;709.0,675.0&gt;-&lt;761.0,870.0&gt;-&lt;854.0,1027.0&gt;&gt; = 8.29890256299905

* uni0412 (U+0412): B&lt;&lt;1117.5,826.0&gt;-&lt;1029.0,734.0&gt;-&lt;871.0,713.0&gt;&gt;/B&lt;&lt;871.0,713.0&gt;-&lt;1026.0,700.0&gt;-&lt;1111.0,620.5&gt;&gt; = 12.365120967464875

* uni1D2E (U+1D2E): B&lt;&lt;751.5,1058.0&gt;-&lt;699.0,1003.0&gt;-&lt;604.0,990.0&gt;&gt;/B&lt;&lt;604.0,990.0&gt;-&lt;696.0,983.0&gt;-&lt;747.0,935.0&gt;&gt; = 12.143156029792268

* uni1DF0 (U+1DF0): B&lt;&lt;25.0,1228.0&gt;-&lt;66.0,1258.0&gt;-&lt;93.0,1304.0&gt;&gt;/L&lt;&lt;93.0,1304.0&gt;--&lt;91.0,1301.0&gt;&gt; = 3.2789862588543652

* uni1DF4 (U+1DF4): B&lt;&lt;-2.0,1228.0&gt;-&lt;39.0,1258.0&gt;-&lt;66.0,1304.0&gt;&gt;/L&lt;&lt;66.0,1304.0&gt;--&lt;64.0,1301.0&gt;&gt; = 3.2789862588543652

* uni1E02 (U+1E02): B&lt;&lt;1117.5,826.0&gt;-&lt;1029.0,734.0&gt;-&lt;871.0,713.0&gt;&gt;/B&lt;&lt;871.0,713.0&gt;-&lt;1026.0,700.0&gt;-&lt;1111.0,620.5&gt;&gt; = 12.365120967464875

* uni1E04 (U+1E04): B&lt;&lt;1117.5,826.0&gt;-&lt;1029.0,734.0&gt;-&lt;871.0,713.0&gt;&gt;/B&lt;&lt;871.0,713.0&gt;-&lt;1026.0,700.0&gt;-&lt;1111.0,620.5&gt;&gt; = 12.365120967464875

* uni1E06 (U+1E06): B&lt;&lt;1117.5,826.0&gt;-&lt;1029.0,734.0&gt;-&lt;871.0,713.0&gt;&gt;/B&lt;&lt;871.0,713.0&gt;-&lt;1026.0,700.0&gt;-&lt;1111.0,620.5&gt;&gt; = 12.365120967464875

* uni1E9E (U+1E9E): B&lt;&lt;1269.5,833.0&gt;-&lt;1178.0,741.0&gt;-&lt;1026.0,720.0&gt;&gt;/B&lt;&lt;1026.0,720.0&gt;-&lt;1173.0,707.0&gt;-&lt;1262.0,625.5&gt;&gt; = 12.919894422961184

* uni210A (U+210A): B&lt;&lt;190.5,333.0&gt;-&lt;211.0,390.0&gt;-&lt;240.0,428.0&gt;&gt;/L&lt;&lt;240.0,428.0&gt;--&lt;106.0,297.0&gt;&gt; = 8.29925471425042

* uni210B (U+210B): B&lt;&lt;1054.0,1043.0&gt;-&lt;1108.0,1121.0&gt;-&lt;1165.0,1190.0&gt;&gt;/B&lt;&lt;1165.0,1190.0&gt;-&lt;1025.0,1063.0&gt;-&lt;909.0,985.0&gt;&gt; = 8.227812873037514

* uni211F (U+211F): L&lt;&lt;444.0,588.0&gt;--&lt;354.0,80.0&gt;&gt;/L&lt;&lt;354.0,80.0&gt;--&lt;545.0,588.0&gt;&gt; = 10.558889935324098

* uni2133 (U+2133): B&lt;&lt;1888.0,926.0&gt;-&lt;1970.0,1038.0&gt;-&lt;2304.0,1421.0&gt;&gt;/B&lt;&lt;2304.0,1421.0&gt;-&lt;2197.0,1345.0&gt;-&lt;2071.0,1224.0&gt;&gt; = 13.524101628054543

* uniA796 (U+A796): B&lt;&lt;1337.5,826.0&gt;-&lt;1249.0,734.0&gt;-&lt;1091.0,713.0&gt;&gt;/B&lt;&lt;1091.0,713.0&gt;-&lt;1246.0,700.0&gt;-&lt;1331.0,620.5&gt;&gt; = 12.365120967464875

* uniA7B4 (U+A7B4): B&lt;&lt;1117.5,826.0&gt;-&lt;1029.0,734.0&gt;-&lt;871.0,713.0&gt;&gt;/B&lt;&lt;871.0,713.0&gt;-&lt;1026.0,700.0&gt;-&lt;1111.0,620.5&gt;&gt; = 12.365120967464875

* uniAB5F (U+AB5F): B&lt;&lt;490.5,1224.5&gt;-&lt;531.0,1254.0&gt;-&lt;560.0,1301.0&gt;&gt;/L&lt;&lt;560.0,1301.0&gt;--&lt;558.0,1298.0&gt;&gt; = 2.014598787870492
</code></pre>
 [code: found-jaggy-segments]



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
    <summary>⚠️ <b>WARN</b> Description strings in the name table must not exceed 200 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-description-max-length">googlefonts/name/description_max_length</a></summary>
    <div>







* ⚠️ **WARN** <p>A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries.</p>
 [code: too-long]



</div>
</details>
</div>
</details>

<details><summary>[24] Tinos-Regular.ttf</summary>
<div>
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
<td align="left">U+1D8E: LATIN SMALL LETTER Z WITH PALATAL HOOK</td>
<td align="left">U+A7C6: LATIN CAPITAL LETTER Z WITH PALATAL HOOK</td>
</tr>
<tr>
<td align="left">U+2184: LATIN SMALL LETTER REVERSED C</td>
<td align="left">U+2183: ROMAN NUMERAL REVERSED ONE HUNDRED</td>
</tr>
<tr>
<td align="left">U+A794: LATIN SMALL LETTER C WITH PALATAL HOOK</td>
<td align="left">U+A7C4: LATIN CAPITAL LETTER C WITH PALATAL HOOK</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 2068, but got 1825 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 797, but got 443 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.13.1, while a newer 0.13.2 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#os2-metrics-match-hhea">os2_metrics_match_hhea</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (1420) and hhea ascent (1825) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check tabular widths don't have kerning. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#tabular-kerning">tabular_kerning</a></summary>
    <div>







* 🔥 **FAIL** <p>Kerning between one and one is -76, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -76, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -76, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -76, should be 0</p>
 [code: has-tabular-kerning]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Whitespace glyphs have ink? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#whitespace-ink">whitespace_ink</a></summary>
    <div>







* 🔥 **FAIL** <p>Glyph 'uni2028' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni2029' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni205F' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni2060' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uniFEFF' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Greek_Expert glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Shaper didn't attach acutecomb to j</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to J</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">The locl feature did not affect Eng</td>
<td align="left">bm_Latn (Bambara), dyu_Latn (Dyula), ig_Latn (Igbo), lg_Latn (Ganda), mnf_Latn (Mundani), las_Latn (Lama, Togo), dtm_Latn (Tomo Kan Dogon), dnj_Latn (Dan), nnh_Latn (Ngiemboon), ttq_Latn (Tawallammat Tamajaq), snk_Latn (Soninke), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nfr_Latn (Nafaanra), nus_Latn (Nuer), bsc_Latn (Bassari), dur_Latn (Dii), naw_Latn (Nawuri), fmp_Latn (Fe’fe’), sav_Latn (Saafi-Saafi), mne_Latn (Naba), azo_Latn (Awing), ig_Latn (Igbo), bzw_Latn (Basa), fuc_Latn (Pulaar), yat_Latn (Yambeta), nnw_Latn (Southern Nuni), kpo_Latn (Ikposo), log_Latn (Logo), dip_Latn (Dinka, Northeastern), twq_Latn (Tasawaq), nfu_Latn (Mfumte), ajg_Latn (Aja), xwe_Latn (Gbe, Xwela), loq_Latn (Lobala), bsp_Latn (Baga Sitemu), wan_Latn (Wan), bcw_Latn (Bana), maw_Latn (Mampruli), myk_Latn (Mamara Senoufo), mfv_Latn (Mandjak), tuq_Latn (Tedaga), agc_Latn (Agatu), krs_Latn (Gbaya, Sudan), bbo_Latn (Northern Bobo Madaré), mfd_Latn (Mendankwe-Nkwen), etu_Latn (Ejagham), xuo_Latn (Kuo), xon_Latn (Konkomba), sok_Latn (Sokoro), adj_Latn (Adioukrou), avn_Latn (Avatime), nku_Latn (Kulango, Bouna), mcn_Latn (Masana), nym_Latn (Nyamwezi), shz_Latn (Syenara Senoufo), lun_Latn (Lunda), ade_Latn (Adele), mdj_Latn (Mangbetu), gur_Latn (Frafra), gna_Latn (Kaansa), mua_Latn (Mundang), bex_Latn (Jur Modo), fvr_Latn (Fur), lam_Latn (Lamba), bza_Latn (Bandi), wci_Latn (Gbe, Waci), mcu_Latn (Mambila, Cameroon), taq_Latn (Tamasheq (Latin)), kvf_Latn (Kabalai), blo_Latn (Anii), gde_Latn (Gude), tik_Latn (Tikar), nmg_Latn (Kwasio), sig_Latn (Paasaal), dow_Latn (Doyayo), dag_Latn (Dagbani), keu_Latn (Akebu), giz_Latn (Southern Giziga), bfd_Latn (Bafut), dno_Latn (Ndrulo), bud_Latn (Ntcham), dyo_Latn (Jola-Fonyi), ybb_Latn (Yemba), tvu_Latn (Tunen), kus_Latn (Kusaal), agq_Latn (Aghem), kzc_Latn (Bondoukou Kulango), ksf_Latn (Bafia), wwa_Latn (Waama), khq_Latn (Koyra Chiini), tod_Latn (Toma), ewo_Latn (Ewondo), muy_Latn (Muyang), cae_Latn (Lehar), vut_Latn (Vute), bzx_Latn (Bozo, Hainyaxo), xsm_Latn (Kasem), xrb_Latn (Karaboro, Eastern), gmm_Latn (Gbaya-Mbodomo), gnd_Latn (Zulgo-Gemzek), nmz_Latn (Nawdm), kpz_Latn (Sapiny), dyu_Latn (Dyula), kdj_Latn (Karamojong), mbu_Latn (Mbula-Bwazza), cou_Latn (Wamey), ny_Latn (Nyanja), avu_Latn (Avokaya), mev_Latn (Mano), bib_Latn (Bissa), ntr_Latn (Delo), udu_Latn (Uduk), ahl_Latn (Igo), spp_Latn (Sénoufo, Supyire), ife_Latn (Ifè), mfi_Latn (Wandala), srr_Latn (Serer), fuf_Latn (Pular), kyq_Latn (Kenga), ikx_Latn (Ik), pbi_Latn (Parkwa), cko_Latn (Anufo), kye_Latn (Krache), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), ken_Latn (Kenyang), tcd_Latn (Tafi), vag_Latn (Vagla), yam_Latn (Yamba), saf_Latn (Safaliba), pil_Latn (Yom), mgc_Latn (Morokodo), mmu_Latn (Mmaala), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), ndz_Latn (Ndogo), cme_Latn (Cerma), kqp_Latn (Kimré), ffm_Latn (Maasina Fulfulde), pnz_Latn (Pana, Central African Republic), kao_Latn (Xaasongaxango), knf_Latn (Mankanya), mur_Latn (Murle), nhu_Latn (Noone), neb_Latn (Toura), lg_Latn (Ganda), ses_Latn (Koyraboro Senni), daa_Latn (Dangaléat), fub_Latn (Fulfulde, Adamawa), ahs_Latn (Ashe), mwk_Latn (Kita Maninkakan), ddn_Latn (Dendi), acd_Latn (Gikyode), xed_Latn (Hdi), kss_Latn (Southern Kisi), kqs_Latn (Kissi, Northern), sef_Latn (Cebaara Senoufo), dgi_Latn (Northern Dagara), ncu_Latn (Chumburung), kmy_Latn (Koma), lee_Latn (Lyélé), bbj_Latn (Ghomala), lmp_Latn (Limbum), kib_Latn (Koalib), wok_Latn (Longto), bav_Latn (Vengo), byv_Latn (Medumba), bqv_Latn (Koro Wachi), kyf_Latn (Kouya), dzg_Latn (Dazaga), yas_Latn (Nugunu), ekm_Latn (Elip), snf_Latn (Noon), sxw_Latn (Saxwe Gbe), nza_Latn (Tigon Mbembe), toq_Latn (Toposa), gej_Latn (Gen), tnr_Latn (Ménik), jgo_Latn (Ngomba), ktj_Latn (Krumen, Plapo), gjn_Latn (Gonja), fuq_Latn (Central-Eastern Niger Fulfulde), bum_Latn (Bulu), fue_Latn (Fulfulde, Borgu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), mgo_Latn (Metaʼ), nko_Latn (Nkonya), ebo_Latn (Teke-Ebo), fan_Latn (Fang), ozm_Latn (Koonzime), dop_Latn (Lukpa), mcp_Latn (Makaa), mls_Latn (Masalit), god_Latn (Godié), bss_Latn (Akoose), mor_Latn (Moro), kbo_Latn (Keliko), kia_Latn (Kim), bfa_Latn (Bari), kdh_Latn (Tem), lok_Latn (Loko), ach_Latn (Acoli), sil_Latn (Sisaala, Tumulung), lns_Latn (Lamnso’), bze_Latn (Jenaama Bozo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), lig_Latn (Ligbi), csk_Latn (Jola-Kasa), anv_Latn (Denya), rub_Latn (Gungu), mnk_Latn (Mandinka), mgd_Latn (Moru), moa_Latn (Mwan), gng_Latn (Ngangam), mas_Latn (Masai), dje_Latn (Zarma), mbo_Latn (Mbo), yav_Latn (Yangben), dua_Latn (Duala), ted_Latn (Krumen, Tepo), tem_Latn (Timne), fod_Latn (Foodo), soy_Latn (Miyobe), wo_Latn (Wolof), mdt_Latn (Mbere), boz_Latn (Tiéyaxo Bozo), gud_Latn (Dida, Yocoboué), nhb_Latn (Beng), fuh_Latn (Fulfulde, Western Niger), bim_Latn (Bimoba), kzr_Latn (Karang), kbp_Latn (Kabiyé), mfq_Latn (Moba), gux_Latn (Gourmanchéma), bjt_Latn (Balanta-Ganja), knp_Latn (Kwanja), dyi_Latn (Sénoufo, Djimini), gaa_Latn (Ga), tpm_Latn (Tampulma), idu_Latn (Idoma), bm_Latn (Bambara), lem_Latn (Nomaande), emk_Latn (Maninkakan, Eastern), meq_Latn (Merey), bkm_Latn (Kom), mzw_Latn (Deg), nuv_Latn (Nuni, Northern), bqj_Latn (Bandial), lia_Latn (Limba, West-Central), pug_Latn (Phuie), aks_Latn (Akeselem), dts_Latn (Dogon, Toro So), ndv_Latn (Ndut), hag_Latn (Hanga), bas_Latn (Basaa), laj_Latn (Lango, Uganda), gkp_Latn (Kpelle, Guinea) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to r</td>
<td align="left">ha_Latn (Hausa) and ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to R</td>
<td align="left">ha_Latn (Hausa) and ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), avu_Latn (Avokaya), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), avu_Latn (Avokaya), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to m</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), ig_Latn (Igbo), yo_Latn_BJ (Yoruba, Benin), yo_Latn (Yoruba), tik_Latn (Tikar), bud_Latn (Ntcham), mev_Latn (Mano), kyq_Latn (Kenga), ikw_Latn (Ikwere), tbz_Latn (Ditammari), jgo_Latn (Ngomba), gvl_Latn (Gulay) and nup_Latn (Nupe-Nupe-Tako)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to M</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), ig_Latn (Igbo), yo_Latn_BJ (Yoruba, Benin), yo_Latn (Yoruba), tik_Latn (Tikar), bud_Latn (Ntcham), mev_Latn (Mano), kyq_Latn (Kenga), ikw_Latn (Ikwere), tbz_Latn (Ditammari), jgo_Latn (Ngomba), gvl_Latn (Gulay) and nup_Latn (Nupe-Nupe-Tako)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere), ann_Latn (Obolo) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere), ann_Latn (Obolo) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to O</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ocircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), nzk_Latn (Nzakara), ozm_Latn (Koonzime), mcp_Latn (Makaa), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D2</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), nfu_Latn (Mfumte), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), tcd_Latn (Tafi), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), gov_Latn (Goo), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Agrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to o</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0197</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), nyb_Latn (Nyangbo), yav_Latn (Yangben), mge_Latn (Mango), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to U</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0197</td>
<td align="left">mnf_Latn (Mundani) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ugrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to A</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ograve</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to a</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ucircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0228</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ugrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), bfd_Latn (Bafut), ewo_Latn (Ewondo), ksp_Latn (Kabba), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
<td align="left">mnf_Latn (Mundani), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0229</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), nyb_Latn (Nyangbo), yav_Latn (Yangben), mge_Latn (Mango), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), gnd_Latn (Zulgo-Gemzek), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), byv_Latn (Medumba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), gvl_Latn (Gulay), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ocircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0229</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), bfd_Latn (Bafut), ewo_Latn (Ewondo), ksp_Latn (Kabba), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0268</td>
<td align="left">mnf_Latn (Mundani) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D3</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to u</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), gnd_Latn (Zulgo-Gemzek), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), byv_Latn (Medumba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), gvl_Latn (Gulay), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0197</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), nzk_Latn (Nzakara), ozm_Latn (Koonzime), mcp_Latn (Makaa), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to acircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01CE</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0197</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), nfu_Latn (Mfumte), bfd_Latn (Bafut), agq_Latn (Aghem), gvl_Latn (Gulay), mge_Latn (Mango), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ucircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Acircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), nfu_Latn (Mfumte), bfd_Latn (Bafut), agq_Latn (Aghem), gvl_Latn (Gulay), mge_Latn (Mango), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), nfu_Latn (Mfumte), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), tcd_Latn (Tafi), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D4</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to agrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0228</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0229</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D1</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
<td align="left">mnf_Latn (Mundani), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01CD</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0228</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ograve</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni025B</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to a</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to A</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to ae</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to AE</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to ae</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to AE</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to ae</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to AE</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to ae</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to AE</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to e</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to E</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0190</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), tik_Latn (Tikar), dow_Latn (Doyayo), bfd_Latn (Bafut), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), nyb_Latn (Nyangbo), gov_Latn (Goo), yav_Latn (Yangben), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), tik_Latn (Tikar), dow_Latn (Doyayo), bfd_Latn (Bafut), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), nyb_Latn (Nyangbo), yav_Latn (Yangben), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
<td align="left">dnj_Latn (Dan), nmg_Latn (Kwasio), dow_Latn (Doyayo), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
<td align="left">dnj_Latn (Dan), nmg_Latn (Kwasio), dow_Latn (Doyayo), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mdt_Latn (Mbere), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mdt_Latn (Mbere), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni025B</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni0190</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), kpe_Latn (Kpelle), lnl_Latn (South Central Banda), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), gov_Latn (Goo), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), kpe_Latn (Kpelle), lnl_Latn (South Central Banda), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to i</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to I</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0264</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), fvr_Latn (Fur), agq_Latn (Aghem), nzk_Latn (Nzakara), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), fvr_Latn (Fur), agq_Latn (Aghem), nzk_Latn (Nzakara), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), ybb_Latn (Yemba), bbj_Latn (Ghomala), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), mas_Latn (Masai) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), fvr_Latn (Fur), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), ybb_Latn (Yemba), bbj_Latn (Ghomala), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), mas_Latn (Masai) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), ybb_Latn (Yemba), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), mwm_Latn (Sar), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mge_Latn (Mango), mdt_Latn (Mbere), kzr_Latn (Karang), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), fvr_Latn (Fur), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), ybb_Latn (Yemba), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), mwm_Latn (Sar), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mge_Latn (Mango), mdt_Latn (Mbere), kzr_Latn (Karang), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to J</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq), taq_Latn (Tamasheq (Latin)) and tmh_Latn (Tamashek)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), dgi_Latn (Northern Dagara), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), dgi_Latn (Northern Dagara), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Utilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to a</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to A</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to e</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to E</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to i</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to I</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to o</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to O</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0254</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0186</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to u</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to U</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to atilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Atilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to tildecomb</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to itilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Itilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to utilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Utilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), dnj_Latn_LR (Liberian Dan), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to itilde</td>
<td align="left">nga_Latn (Ngbaka) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Itilde</td>
<td align="left">nga_Latn (Ngbaka) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to utilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Utilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to itilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Itilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to utilde</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Utilde</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to e</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to E</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to o</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to O</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), sba_Latn (Ngambay), blo_Latn (Anii), nmg_Latn (Kwasio) and ksf_Latn (Bafia)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and lob_Latn (Lobi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), sba_Latn (Ngambay), blo_Latn (Anii), nmg_Latn (Kwasio) and ksf_Latn (Bafia)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to otilde</td>
<td align="left">tuz_Latn (Turka), lom_Latn (Loma, Liberia), lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and lob_Latn (Lobi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0196</td>
<td align="left">tuz_Latn (Turka), goa_Latn (Guro), blo_Latn (Anii), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Otilde</td>
<td align="left">tuz_Latn (Turka), lom_Latn (Loma, Liberia), lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196</td>
<td align="left">tuz_Latn (Turka), goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), xsm_Latn_BF (Kasem, Burkina Faso), tcd_Latn (Tafi), neb_Latn (Toura), sld_Latn (Sissala), pug_Latn (Phuie) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EE4</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EB9</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECA</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EE5</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECA</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), avu_Latn (Avokaya), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EE4</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECD</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EB8</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECC</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EE5</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), avu_Latn (Avokaya), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EB9</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EB8</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECA</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECD</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECC</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EE5</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EE4</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to i</td>
<td align="left">kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
<td align="left">kkj_Latn (Kako), dow_Latn (Doyayo), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to I</td>
<td align="left">kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
<td align="left">kkj_Latn (Kako), dow_Latn (Doyayo), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to a</td>
<td align="left">nus_Latn (Nuer), asg_Latn (Cishingini), fvr_Latn (Fur), kdj_Latn (Karamojong), kaj_Latn (Jju) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), lnl_Latn (South Central Banda), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0254</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
<td align="left">nus_Latn (Nuer)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to A</td>
<td align="left">nus_Latn (Nuer), asg_Latn (Cishingini), fvr_Latn (Fur), kdj_Latn (Karamojong), kaj_Latn (Jju) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), lnl_Latn (South Central Banda), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0190</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to i</td>
<td align="left">nus_Latn (Nuer), kdj_Latn (Karamojong), kcg_Latn (Tyap) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0254</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0186</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0186</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to I</td>
<td align="left">nus_Latn (Nuer), kdj_Latn (Karamojong), kcg_Latn (Tyap) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to h</td>
<td align="left">bsc_Latn (Bassari)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to H</td>
<td align="left">bsc_Latn (Bassari)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to w</td>
<td align="left">bsc_Latn (Bassari) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to W</td>
<td align="left">bsc_Latn (Bassari) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
<td align="left">dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), etu_Latn (Ejagham), sba_Latn (Ngambay), bfd_Latn (Bafut), ybb_Latn (Yemba), ewo_Latn (Ewondo), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), mwm_Latn (Sar), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), mcp_Latn (Makaa), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Oacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Igrave</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
<td align="left">dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Uacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0228</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0229</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0197</td>
<td align="left">dur_Latn (Dii), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), bfd_Latn (Bafut), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), mge_Latn (Mango) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Iacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
<td align="left">dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), etu_Latn (Ejagham), sba_Latn (Ngambay), bfd_Latn (Bafut), ybb_Latn (Yemba), ewo_Latn (Ewondo), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), mwm_Latn (Sar), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), mcp_Latn (Makaa), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to aacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268</td>
<td align="left">dur_Latn (Dii), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), bfd_Latn (Bafut), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), mge_Latn (Mango) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F</td>
<td align="left">dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to igrave</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to iacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to oacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Aacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), kyq_Latn (Kenga), mwm_Latn (Sar), wok_Latn (Longto), bax_Latn (Bamun (Latin)) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
<td align="left">fmp_Latn (Fe’fe’), nmg_Latn (Kwasio), dow_Latn (Doyayo), ybb_Latn (Yemba), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), mwm_Latn (Sar), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0289</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), agq_Latn (Aghem) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0244</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), agq_Latn (Aghem) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186</td>
<td align="left">fmp_Latn (Fe’fe’), nmg_Latn (Kwasio), dow_Latn (Doyayo), ybb_Latn (Yemba), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), mwm_Latn (Sar), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), kyq_Latn (Kenga), mwm_Latn (Sar), wok_Latn (Longto), bax_Latn (Bamun (Latin)) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to n</td>
<td align="left">mne_Latn (Naba), kyq_Latn (Kenga), daa_Latn (Dangaléat), mls_Latn (Masalit) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to N</td>
<td align="left">mne_Latn (Naba), kyq_Latn (Kenga), daa_Latn (Dangaléat), mls_Latn (Masalit) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to U</td>
<td align="left">uth_Latn (ut-Hun), kdj_Latn (Karamojong), kaj_Latn (Jju) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to u</td>
<td align="left">uth_Latn (ut-Hun), kdj_Latn (Karamojong), kaj_Latn (Jju) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Oslash</td>
<td align="left">nfu_Latn (Mfumte) and ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oslash</td>
<td align="left">nfu_Latn (Mfumte) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Oslash</td>
<td align="left">nfu_Latn (Mfumte), ozm_Latn (Koonzime) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Oslash</td>
<td align="left">nfu_Latn (Mfumte) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oslash</td>
<td align="left">nfu_Latn (Mfumte), ozm_Latn (Koonzime) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oslash</td>
<td align="left">nfu_Latn (Mfumte) and ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018E</td>
<td align="left">dnj_Latn_LR (Liberian Dan), blo_Latn (Anii) and nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
<td align="left">dnj_Latn_LR (Liberian Dan), blo_Latn (Anii) and nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to n</td>
<td align="left">mg_Latn (Malagasy), etu_Latn (Ejagham), ksp_Latn (Kabba), ikw_Latn (Ikwere) and gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to N</td>
<td align="left">mg_Latn (Malagasy), etu_Latn (Ejagham), ksp_Latn (Kabba) and ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to n</td>
<td align="left">mg_Latn (Malagasy) and nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to N</td>
<td align="left">mg_Latn (Malagasy) and nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to g</td>
<td align="left">tuq_Latn (Tedaga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to G</td>
<td align="left">tuq_Latn (Tedaga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F</td>
<td align="left">lnl_Latn (South Central Banda), ybb_Latn (Yemba), ksp_Latn (Kabba) and sbd_Latn (Southern Samo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268</td>
<td align="left">lnl_Latn (South Central Banda) and nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0197</td>
<td align="left">lnl_Latn (South Central Banda) and nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
<td align="left">lnl_Latn (South Central Banda), ybb_Latn (Yemba), ksp_Latn (Kabba) and sbd_Latn (Southern Samo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0244</td>
<td align="left">lnl_Latn (South Central Banda), nzk_Latn (Nzakara) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0289</td>
<td align="left">lnl_Latn (South Central Banda), nzk_Latn (Nzakara) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
<td align="left">goa_Latn (Guro), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), xsm_Latn_BF (Kasem, Burkina Faso), neb_Latn (Toura), sld_Latn (Sissala) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), xsm_Latn_BF (Kasem, Burkina Faso), neb_Latn (Toura), sld_Latn (Sissala) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
<td align="left">goa_Latn (Guro), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
<td align="left">goa_Latn (Guro), blo_Latn (Anii), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0196</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tcd_Latn (Tafi) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tcd_Latn (Tafi) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028B</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0196</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), xsm_Latn_BF (Kasem, Burkina Faso), tcd_Latn (Tafi), neb_Latn (Toura), sld_Latn (Sissala), pug_Latn (Phuie) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EE4</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECD</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EB8</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECA</td>
<td align="left">mhi_Latn (Ma’di), avu_Latn (Avokaya) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECC</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EB9</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EE5</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB</td>
<td align="left">mhi_Latn (Ma’di), avu_Latn (Avokaya) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to o</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and kia_Latn (Kim)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E1A</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to A</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto), kia_Latn (Kim) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E1B</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E1A</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E1B</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to a</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto), kia_Latn (Kim) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to O</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and kia_Latn (Kim)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01DD</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018E</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), sld_Latn (Sissala), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), tcd_Latn (Tafi), sld_Latn (Sissala), biv_Latn (Birifor, Southern), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), sld_Latn (Sissala), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), tcd_Latn (Tafi), sld_Latn (Sissala), biv_Latn (Birifor, Southern), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni01CE</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Aacute</td>
<td align="left">fvr_Latn (Fur) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to aacute</td>
<td align="left">fvr_Latn (Fur) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to acircumflex</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Acircumflex</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni01CD</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EBC</td>
<td align="left">kst_Latn (Winyé), lee_Latn (Lyélé), sld_Latn (Sissala), soy_Latn (Miyobe), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EBD</td>
<td align="left">kst_Latn (Winyé), lee_Latn (Lyélé), sld_Latn (Sissala), soy_Latn (Miyobe), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A</td>
<td align="left">blo_Latn (Anii), tcd_Latn (Tafi) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1</td>
<td align="left">blo_Latn (Anii), tcd_Latn (Tafi) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to AE</td>
<td align="left">tik_Latn (Tikar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to eng</td>
<td align="left">tik_Latn (Tikar), mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
<td align="left">tik_Latn (Tikar), mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to ae</td>
<td align="left">tik_Latn (Tikar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01DD</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01DD</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018E</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018E</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to V</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to v</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to v</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to V</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to umacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to amacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Umacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Amacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Imacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0327</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0327</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to imacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to R</td>
<td align="left">dno_Latn (Ndrulo), kyq_Latn (Kenga) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to r</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to R</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to s</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to r</td>
<td align="left">dno_Latn (Ndrulo), kyq_Latn (Kenga) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to S</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to b</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to B</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to l</td>
<td align="left">bud_Latn (Ntcham) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to B</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to L</td>
<td align="left">bud_Latn (Ntcham) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to b</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Idieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to edieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Edieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to udieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to idieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Udieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268</td>
<td align="left">agq_Latn (Aghem) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0197</td>
<td align="left">agq_Latn (Aghem) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7AE</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EA1</td>
<td align="left">abn_Latn (Abua) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EA0</td>
<td align="left">abn_Latn (Abua) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EA1</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EA0</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Idieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to udieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to idieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Udieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Icircumflex</td>
<td align="left">vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to icircumflex</td>
<td align="left">vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to Eng</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to eng</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to G</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to g</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0289</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0268</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0197</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0244</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EA1</td>
<td align="left">avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EA0</td>
<td align="left">avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Agrave</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Amacron</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), wok_Latn (Longto), jgo_Latn (Ngomba), gov_Latn (Goo) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), wok_Latn (Longto), jgo_Latn (Ngomba) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), kss_Latn (Southern Kisi), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), kss_Latn (Southern Kisi), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E75</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E74</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E75</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E74</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E75</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E74</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to C</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni035F to T</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to c</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to p</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to P</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni035F to t</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to H</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to nacute</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Nacute</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01F9</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01F8</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to m</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), tcd_Latn (Tafi), mwm_Latn (Sar), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to M</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), tcd_Latn (Tafi), mwm_Latn (Sar), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to n</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), ann_Latn (Obolo), mwm_Latn (Sar), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to N</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), ann_Latn (Obolo), mwm_Latn (Sar), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to r</td>
<td align="left">kyq_Latn (Kenga), mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to R</td>
<td align="left">kyq_Latn (Kenga), mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to m</td>
<td align="left">ikw_Latn (Ikwere) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to M</td>
<td align="left">ikw_Latn (Ikwere) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019D</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019D</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to a</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to A</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to atilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Atilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to e</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to E</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EBD</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EBC</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0269</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0196</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0269</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0196</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to tildecomb</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to o</td>
<td align="left">tcd_Latn (Tafi), kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to O</td>
<td align="left">tcd_Latn (Tafi), kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to o</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to O</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to otilde</td>
<td align="left">tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Otilde</td>
<td align="left">tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0254</td>
<td align="left">tcd_Latn (Tafi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0186</td>
<td align="left">tcd_Latn (Tafi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to tildecomb</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to u</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to U</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to Utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A</td>
<td align="left">tcd_Latn (Tafi) and biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1</td>
<td align="left">tcd_Latn (Tafi) and biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E2D</td>
<td align="left">mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to w</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E2C</td>
<td align="left">mwm_Latn (Sar), ntm_Latn (Nateni) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E1A</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to omacron</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E2D</td>
<td align="left">mwm_Latn (Sar), ntm_Latn (Nateni) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to oacute</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Omacron</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E2C</td>
<td align="left">mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to W</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E1B</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Oacute</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to otilde</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni1EBC</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Otilde</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni1EBD</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to a</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to A</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to a</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to A</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to e</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to E</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to e</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to E</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni025B</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0190</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni025B</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0190</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to i</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to I</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to i</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to I</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to eng</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Eng</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to o</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to O</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0254</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0186</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0254</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0186</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to u</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to U</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to u</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to U</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EBC</td>
<td align="left">lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EBC</td>
<td align="left">lee_Latn (Lyélé) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EBD</td>
<td align="left">lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EBD</td>
<td align="left">lee_Latn (Lyélé) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Iacute</td>
<td align="left">kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to iacute</td>
<td align="left">kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E2C</td>
<td align="left">ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E2D</td>
<td align="left">ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to L</td>
<td align="left">wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to l</td>
<td align="left">wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0251</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Udieresis</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to udieresis</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0289</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0197</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0244</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0324 to W</td>
<td align="left">fan_Latn (Fang) and mdt_Latn (Mbere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0324 to w</td>
<td align="left">fan_Latn (Fang) and mdt_Latn (Mbere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to OE</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to OE</td>
<td align="left">ozm_Latn (Koonzime) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to OE</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe</td>
<td align="left">ozm_Latn (Koonzime) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ꟈ, ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0325 to l</td>
<td align="left">csk_Latn (Jola-Kasa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0325 to L</td>
<td align="left">csk_Latn (Jola-Kasa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to b</td>
<td align="left">rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to B</td>
<td align="left">rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Adieresis</td>
<td align="left">mgd_Latn (Moru)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to adieresis</td>
<td align="left">mgd_Latn (Moru)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to T</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to t</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to d</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to D</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ɤ, Ɤ̀, Ɤ́, Ɤ̂</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to ograve</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Ograve</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to OE</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to i</td>
<td align="left">btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to I</td>
<td align="left">btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EBD</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EBC</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to otilde</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Otilde</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to Oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to O</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to i</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni025B</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to A</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0186</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to I</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to e</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to o</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0254</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to u</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to U</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni025B</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0190</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to a</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0190</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to E</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to aogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Aogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0259</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Iogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Uogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Greek_Expert glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">No variant glyphs were found for uni0181</td>
<td align="left">dnj_Latn (Dan) and lom_Latn (Loma, Liberia)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Amo</td>
<td align="left">amo_Latn (Amo)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Koro</td>
<td align="left">kfo_Latn (Koro)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni028B</td>
<td align="left">tod_Latn (Toma)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01B2</td>
<td align="left">tod_Latn (Toma)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Seki</td>
<td align="left">syi_Latn (Seki)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Mina</td>
<td align="left">hna_Latn (Mina)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ⓐ, ⓐ</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Mbunga</td>
<td align="left">mgy_Latn (Mbunga)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Eastern Gurung, Latin</td>
<td align="left">ggn_Latn (Eastern Gurung, Latin)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01A9</td>
<td align="left">gaa_Latn (Ga)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01B7</td>
<td align="left">gaa_Latn (Ga)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Atsam</td>
<td align="left">cch_Latn (Atsam)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2010 Google Inc. All Rights Reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 🔥 **FAIL** <p>Tinos Regular: OS/2 sTypoAscender is 1420 when it should be 1825</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Tinos Regular: OS/2 sTypoDescender is -442 when it should be -443</p>
 [code: bad-typo-descender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671), uniA672 (U+A672), uniFE20 (U+FE20), uniFE21 (U+FE21), uniFE27 (U+FE27) and uniFE28 (U+FE28)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: hyphen	Contours detected: 1	Expected: 0

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni01E5	Contours detected: 4	Expected: 2

- Glyph name: uni01F5	Contours detected: 4	Expected: 3

- Glyph name: uni023A	Contours detected: 4	Expected: 3

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uni204B	Contours detected: 1	Expected: 2

- Glyph name: uni205F	Contours detected: 15	Expected: 0

- Glyph name: uni210A	Contours detected: 3	Expected: 2

- Glyph name: uni210D	Contours detected: 3	Expected: 2

- Glyph name: uni2119	Contours detected: 4	Expected: 2

- Glyph name: uni211A	Contours detected: 5	Expected: 3

- Glyph name: uni211D	Contours detected: 5	Expected: 3

- Glyph name: uni2E18	Contours detected: 3	Expected: 2

- Glyph name: uniFEFF	Contours detected: 19	Expected: 0

- Glyph name: uniFFFC	Contours detected: 16	Expected: 22

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: uni01E5	Contours detected: 4	Expected: 2

- Glyph name: uni023A	Contours detected: 4	Expected: 3

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uni204B	Contours detected: 1	Expected: 2

- Glyph name: uni205F	Contours detected: 15	Expected: 0

- Glyph name: uni210A	Contours detected: 3	Expected: 2

- Glyph name: uni210D	Contours detected: 3	Expected: 2

- Glyph name: uni2119	Contours detected: 4	Expected: 2

- Glyph name: uni211A	Contours detected: 5	Expected: 3

- Glyph name: uni211D	Contours detected: 5	Expected: 3

- Glyph name: uni2E18	Contours detected: 3	Expected: 2

- Glyph name: uniFEFF	Contours detected: 19	Expected: 0

- Glyph name: uniFFFC	Contours detected: 16	Expected: 22

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 1155 among a set of 8 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 1124:
plusminus, divide, lessequal, approxequal, notequal, greaterequal</p>
<p>Width = 2005:
orthogonal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#overlapping-path-segments">overlapping_path_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have overlapping path segments:</p>
<pre><code>* uni1DD3 (U+1DD3): L&lt;&lt;-37.0,1399.0&gt;--&lt;37.0,1399.0&gt;&gt; has the same coordinates as a previous segment.
</code></pre>
 [code: overlapping-path-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#typoascender-exceeds-Agrave">typoascender_exceeds_Agrave</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2.sTypoAscender value should be greater than 1758, but got 1420 instead</p>
 [code: typoAscender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Eng.alt1

- Eng.alt2

- Eng.alt3

- Lcommaaccent.loclMAH

- Ncommaaccent.loclMAH

- Ohm

- UNI2206

- acute.alt1

- acute.alt2

- acute.alt3

- acute.alt4

- acute.alt5

- alefdagesh

- aleflamedhatafsegol

- aleflamedsegol

- aleflamedtsere

- alternativelamed

- bari.dotless

- breve.alt1

- breve.cyr

- circumflex.alt1

- dotbelow.alt1

- dotbelow.alt10

- dotbelow.alt11

- dotbelow.alt12

- dotbelow.alt13

- dotbelow.alt14

- dotbelow.alt15

- dotbelow.alt2

- dotbelow.alt3

- dotbelow.alt4

- dotbelow.alt5

- dotbelow.alt6

- dotbelow.alt7

- dotbelow.alt8

- dotbelow.alt9

- dotlessi.alt1

- dottediacute

- eight.alt

- finalkafqamats

- finalkafsheva

- five.alt

- four.alt

- glyph3284

- grave.alt1

- grave.alt2

- grave.alt3

- grave.alt4

- grave.alt5

- hookabove.alt1

- hookabove.alt2

- hookabove.alt3

- hookabove.alt4

- hookabove.alt5

- lamedholam

- lamedholamdagesh

- lcommaaccent.loclMAH

- ncommaaccent.loclMAH

- nine.alt

- one.alt

- pi1

- radicalex.x

- seven.alt

- six.alt

- three.alt

- tilde.alt1

- tilde.alt10

- tilde.alt11

- tilde.alt12

- tilde.alt13

- tilde.alt2

- tilde.alt3

- tilde.alt4

- tilde.alt5

- tilde.alt6

- tilde.alt7

- tilde.alt8

- tilde.alt9

- two.alt

- uni00AD

- uni02E502E502E6

- uni02E502E502E7

- uni02E502E502E8

- uni02E502E502E9

- uni02E502E6

- uni02E502E602E5

- uni02E502E602E6

- uni02E502E602E7

- uni02E502E602E8

- uni02E502E602E9

- uni02E502E7

- uni02E502E702E5

- uni02E502E702E6

- uni02E502E702E7

- uni02E502E702E8

- uni02E502E702E9

- uni02E502E8

- uni02E502E802E5

- uni02E502E802E6

- uni02E502E802E7

- uni02E502E802E8

- uni02E502E802E9

- uni02E502E9

- uni02E502E902E5

- uni02E502E902E6

- uni02E502E902E7

- uni02E502E902E8

- uni02E502E902E9

- uni02E602E5

- uni02E602E502E5

- uni02E602E502E6

- uni02E602E502E7

- uni02E602E502E8

- uni02E602E502E9

- uni02E602E602E5

- uni02E602E602E7

- uni02E602E602E8

- uni02E602E602E9

- uni02E602E7

- uni02E602E702E5

- uni02E602E702E6

- uni02E602E702E7

- uni02E602E702E8

- uni02E602E702E9

- uni02E602E8

- uni02E602E802E5

- uni02E602E802E6

- uni02E602E802E7

- uni02E602E802E8

- uni02E602E802E9

- uni02E602E9

- uni02E602E902E5

- uni02E602E902E6

- uni02E602E902E7

- uni02E602E902E8

- uni02E602E902E9

- uni02E702E5

- uni02E702E502E5

- uni02E702E502E6

- uni02E702E502E7

- uni02E702E502E8

- uni02E702E502E9

- uni02E702E6

- uni02E702E602E5

- uni02E702E602E6

- uni02E702E602E7

- uni02E702E602E8

- uni02E702E602E9

- uni02E702E702E5

- uni02E702E702E6

- uni02E702E702E8

- uni02E702E702E9

- uni02E702E8

- uni02E702E802E5

- uni02E702E802E6

- uni02E702E802E7

- uni02E702E802E8

- uni02E702E802E9

- uni02E702E9

- uni02E702E902E5

- uni02E702E902E6

- uni02E702E902E7

- uni02E702E902E8

- uni02E702E902E9

- uni02E802E5

- uni02E802E502E5

- uni02E802E502E6

- uni02E802E502E7

- uni02E802E502E8

- uni02E802E502E9

- uni02E802E6

- uni02E802E602E5

- uni02E802E602E6

- uni02E802E602E7

- uni02E802E602E8

- uni02E802E602E9

- uni02E802E7

- uni02E802E702E5

- uni02E802E702E6

- uni02E802E702E7

- uni02E802E702E8

- uni02E802E702E9

- uni02E802E802E5

- uni02E802E802E6

- uni02E802E802E7

- uni02E802E802E9

- uni02E802E9

- uni02E802E902E5

- uni02E802E902E6

- uni02E802E902E7

- uni02E802E902E8

- uni02E802E902E9

- uni02E902E5

- uni02E902E502E5

- uni02E902E502E6

- uni02E902E502E7

- uni02E902E502E8

- uni02E902E502E9

- uni02E902E6

- uni02E902E602E5

- uni02E902E602E6

- uni02E902E602E7

- uni02E902E602E8

- uni02E902E602E9

- uni02E902E7

- uni02E902E702E5

- uni02E902E702E6

- uni02E902E702E7

- uni02E902E702E8

- uni02E902E702E9

- uni02E902E8

- uni02E902E802E5

- uni02E902E802E6

- uni02E902E802E7

- uni02E902E802E8

- uni02E902E802E9

- uni02E902E902E5

- uni02E902E902E6

- uni02E902E902E7

- uni02E902E902E8

- uni03B1030403130300

- uni03B1030403130301

- uni03B1030403140300

- uni03B1030403140301

- uni03B1030603130300

- uni03B1030603130301

- uni03B1030603140300

- uni03B1030603140301

- uni03B9030403130300

- uni03B9030403130301

- uni03B9030403140300

- uni03B9030403140301

- uni03B9030603130300

- uni03B9030603130301

- uni03B9030603140300

- uni03B9030603140301

- uni03B9030803040300

- uni03B9030803040301

- uni03B9030803060300

- uni03B9030803060301

- uni03C5030403130300

- uni03C5030403130301

- uni03C5030403140300

- uni03C5030403140301

- uni03C5030603130300

- uni03C5030603130301

- uni03C5030603140300

- uni03C5030603140301

- uni03C5030803040300

- uni03C5030803040301

- uni03C5030803060300

- uni03C5030803060301

- uni0431.loclSRB

- uni05B105BD

- uni05B205BD

- uni05B305BD

- zero.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/Tinos/googlefonts/ttf does not have an article.</p>
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
<li>U+02CD MODIFIER LETTER LOW MACRON: try adding lisu</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: elbasan, glagolitic, math, coptic, gothic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar</li>
<li>U+030E COMBINING DOUBLE VERTICAL LINE ABOVE: try adding ethiopic</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0310 COMBINING CANDRABINDU: try adding one of: math, sunuwar</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding one of: old-permic, todhri</li>
<li>U+0314 COMBINING REVERSED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0315 COMBINING COMMA ABOVE RIGHT: try adding math</li>
<li>U+0316 COMBINING GRAVE ACCENT BELOW: not included in any glyphset definition</li>
<li>U+0317 COMBINING ACUTE ACCENT BELOW: not included in any glyphset definition</li>
<li>U+0318 COMBINING LEFT TACK BELOW: not included in any glyphset definition</li>
<li>U+0319 COMBINING RIGHT TACK BELOW: not included in any glyphset definition</li>
<li>U+031A COMBINING LEFT ANGLE ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+031C COMBINING LEFT HALF RING BELOW: not included in any glyphset definition</li>
<li>U+031D COMBINING UP TACK BELOW: not included in any glyphset definition</li>
<li>U+031E COMBINING DOWN TACK BELOW: not included in any glyphset definition</li>
<li>U+031F COMBINING PLUS SIGN BELOW: not included in any glyphset definition</li>
<li>U+0320 COMBINING MINUS SIGN BELOW: try adding syriac</li>
<li>U+0321 COMBINING PALATALIZED HOOK BELOW: not included in any glyphset definition</li>
<li>U+0322 COMBINING RETROFLEX HOOK BELOW: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, duployan, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032A COMBINING BRIDGE BELOW: not included in any glyphset definition</li>
<li>U+032B COMBINING INVERTED DOUBLE ARCH BELOW: not included in any glyphset definition</li>
<li>U+032C COMBINING CARON BELOW: try adding math</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, thai, caucasian-albanian, gothic, sunuwar, tifinagh, syriac</li>
<li>U+0332 COMBINING LOW LINE: try adding math</li>
<li>U+0333 COMBINING DOUBLE LOW LINE: try adding math</li>
<li>U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+0339 COMBINING RIGHT HALF RING BELOW: not included in any glyphset definition</li>
<li>U+033A COMBINING INVERTED BRIDGE BELOW: try adding math</li>
<li>U+033B COMBINING SQUARE BELOW: not included in any glyphset definition</li>
<li>U+033C COMBINING SEAGULL BELOW: not included in any glyphset definition</li>
<li>U+033D COMBINING X ABOVE: not included in any glyphset definition</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+033F COMBINING DOUBLE OVERLINE: try adding coptic</li>
<li>U+0340 COMBINING GRAVE TONE MARK: not included in any glyphset definition</li>
<li>U+0341 COMBINING ACUTE TONE MARK: not included in any glyphset definition</li>
<li>U+0342 COMBINING GREEK PERISPOMENI: not included in any glyphset definition</li>
<li>U+0343 COMBINING GREEK KORONIS: not included in any glyphset definition</li>
<li>U+0344 COMBINING GREEK DIALYTIKA TONOS: not included in any glyphset definition</li>
<li>U+0345 COMBINING GREEK YPOGEGRAMMENI: not included in any glyphset definition</li>
<li>U+0346 COMBINING BRIDGE ABOVE: try adding math</li>
<li>U+0347 COMBINING EQUALS SIGN BELOW: not included in any glyphset definition</li>
<li>U+0348 COMBINING DOUBLE VERTICAL LINE BELOW: not included in any glyphset definition</li>
<li>U+0349 COMBINING LEFT ANGLE BELOW: not included in any glyphset definition</li>
<li>U+034A COMBINING NOT TILDE ABOVE: not included in any glyphset definition</li>
<li>U+034B COMBINING HOMOTHETIC ABOVE: not included in any glyphset definition</li>
<li>U+034C COMBINING ALMOST EQUAL TO ABOVE: not included in any glyphset definition</li>
<li>U+034D COMBINING LEFT RIGHT ARROW BELOW: try adding math</li>
<li>U+034E COMBINING UPWARDS ARROW BELOW: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+0350 COMBINING RIGHT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+0351 COMBINING LEFT HALF RING ABOVE: not included in any glyphset definition</li>
<li>U+0352 COMBINING FERMATA: not included in any glyphset definition</li>
<li>U+0353 COMBINING X BELOW: not included in any glyphset definition</li>
<li>U+0354 COMBINING LEFT ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0355 COMBINING RIGHT ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0356 COMBINING RIGHT ARROWHEAD AND UP ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0357 COMBINING RIGHT HALF RING ABOVE: not included in any glyphset definition</li>
<li>U+0358 COMBINING DOT ABOVE RIGHT: try adding osage</li>
<li>U+0359 COMBINING ASTERISK BELOW: not included in any glyphset definition</li>
<li>U+035A COMBINING DOUBLE RING BELOW: not included in any glyphset definition</li>
<li>U+035B COMBINING ZIGZAG ABOVE: not included in any glyphset definition</li>
<li>U+035C COMBINING DOUBLE BREVE BELOW: not included in any glyphset definition</li>
<li>U+035D COMBINING DOUBLE BREVE: not included in any glyphset definition</li>
<li>U+035E COMBINING DOUBLE MACRON: try adding one of: todhri, coptic, caucasian-albanian</li>
<li>U+035F COMBINING DOUBLE MACRON BELOW: not included in any glyphset definition</li>
<li>U+0360 COMBINING DOUBLE TILDE: not included in any glyphset definition</li>
<li>U+0361 COMBINING DOUBLE INVERTED BREVE: try adding coptic</li>
<li>U+0362 COMBINING DOUBLE RIGHTWARDS ARROW BELOW: not included in any glyphset definition</li>
<li>U+0363 COMBINING LATIN SMALL LETTER A: not included in any glyphset definition</li>
<li>U+0364 COMBINING LATIN SMALL LETTER E: not included in any glyphset definition</li>
<li>U+0365 COMBINING LATIN SMALL LETTER I: not included in any glyphset definition</li>
<li>U+0366 COMBINING LATIN SMALL LETTER O: not included in any glyphset definition</li>
<li>U+0367 COMBINING LATIN SMALL LETTER U: not included in any glyphset definition</li>
<li>U+0368 COMBINING LATIN SMALL LETTER C: not included in any glyphset definition</li>
<li>U+0369 COMBINING LATIN SMALL LETTER D: not included in any glyphset definition</li>
<li>U+036A COMBINING LATIN SMALL LETTER H: not included in any glyphset definition</li>
<li>U+036B COMBINING LATIN SMALL LETTER M: not included in any glyphset definition</li>
<li>U+036C COMBINING LATIN SMALL LETTER R: not included in any glyphset definition</li>
<li>U+036D COMBINING LATIN SMALL LETTER T: not included in any glyphset definition</li>
<li>U+036E COMBINING LATIN SMALL LETTER V: not included in any glyphset definition</li>
<li>U+036F COMBINING LATIN SMALL LETTER X: not included in any glyphset definition</li>
<li>U+1AB0 COMBINING DOUBLED CIRCUMFLEX ACCENT: not included in any glyphset definition</li>
<li>U+1AB1 COMBINING DIAERESIS-RING: not included in any glyphset definition</li>
<li>U+1AB2 COMBINING INFINITY: not included in any glyphset definition</li>
<li>U+1AB3 COMBINING DOWNWARDS ARROW: not included in any glyphset definition</li>
<li>U+1AB4 COMBINING TRIPLE DOT: not included in any glyphset definition</li>
<li>U+1AB5 COMBINING X-X BELOW: not included in any glyphset definition</li>
<li>U+1AB6 COMBINING WIGGLY LINE BELOW: not included in any glyphset definition</li>
<li>U+1AB7 COMBINING OPEN MARK BELOW: not included in any glyphset definition</li>
<li>U+1AB8 COMBINING DOUBLE OPEN MARK BELOW: not included in any glyphset definition</li>
<li>U+1AB9 COMBINING LIGHT CENTRALIZATION STROKE BELOW: not included in any glyphset definition</li>
<li>U+1ABA COMBINING STRONG CENTRALIZATION STROKE BELOW: not included in any glyphset definition</li>
<li>U+1ABB COMBINING PARENTHESES ABOVE: not included in any glyphset definition</li>
<li>U+1ABC COMBINING DOUBLE PARENTHESES ABOVE: not included in any glyphset definition</li>
<li>U+1ABD COMBINING PARENTHESES BELOW: not included in any glyphset definition</li>
<li>U+1ABE COMBINING PARENTHESES OVERLAY: not included in any glyphset definition</li>
<li>U+1DC0 COMBINING DOTTED GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+1DC1 COMBINING DOTTED ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+1DC2 COMBINING SNAKE BELOW: not included in any glyphset definition</li>
<li>U+1DC3 COMBINING SUSPENSION MARK: not included in any glyphset definition</li>
<li>U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition</li>
<li>U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition</li>
<li>U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition</li>
<li>U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition</li>
<li>U+1DC8 COMBINING GRAVE-ACUTE-GRAVE: not included in any glyphset definition</li>
<li>U+1DC9 COMBINING ACUTE-GRAVE-ACUTE: not included in any glyphset definition</li>
<li>U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition</li>
<li>U+1DCB COMBINING BREVE-MACRON: not included in any glyphset definition</li>
<li>U+1DCC COMBINING MACRON-BREVE: not included in any glyphset definition</li>
<li>U+1DCD COMBINING DOUBLE CIRCUMFLEX ABOVE: try adding coptic</li>
<li>U+1DCE COMBINING OGONEK ABOVE: not included in any glyphset definition</li>
<li>U+1DCF COMBINING ZIGZAG BELOW: not included in any glyphset definition</li>
<li>U+1DD0 COMBINING IS BELOW: not included in any glyphset definition</li>
<li>U+1DD1 COMBINING UR ABOVE: not included in any glyphset definition</li>
<li>U+1DD2 COMBINING US ABOVE: not included in any glyphset definition</li>
<li>U+1DD3 COMBINING LATIN SMALL LETTER FLATTENED OPEN A ABOVE: not included in any glyphset definition</li>
<li>U+1DD4 COMBINING LATIN SMALL LETTER AE: not included in any glyphset definition</li>
<li>U+1DD5 COMBINING LATIN SMALL LETTER AO: not included in any glyphset definition</li>
<li>U+1DD6 COMBINING LATIN SMALL LETTER AV: not included in any glyphset definition</li>
<li>U+1DD7 COMBINING LATIN SMALL LETTER C CEDILLA: not included in any glyphset definition</li>
<li>U+1DD8 COMBINING LATIN SMALL LETTER INSULAR D: not included in any glyphset definition</li>
<li>U+1DD9 COMBINING LATIN SMALL LETTER ETH: not included in any glyphset definition</li>
<li>U+1DDA COMBINING LATIN SMALL LETTER G: not included in any glyphset definition</li>
<li>U+1DDB COMBINING LATIN LETTER SMALL CAPITAL G: not included in any glyphset definition</li>
<li>U+1DDC COMBINING LATIN SMALL LETTER K: not included in any glyphset definition</li>
<li>U+1DDD COMBINING LATIN SMALL LETTER L: not included in any glyphset definition</li>
<li>U+1DDE COMBINING LATIN LETTER SMALL CAPITAL L: not included in any glyphset definition</li>
<li>U+1DDF COMBINING LATIN LETTER SMALL CAPITAL M: not included in any glyphset definition</li>
<li>U+1DE0 COMBINING LATIN SMALL LETTER N: not included in any glyphset definition</li>
<li>U+1DE1 COMBINING LATIN LETTER SMALL CAPITAL N: not included in any glyphset definition</li>
<li>U+1DE2 COMBINING LATIN LETTER SMALL CAPITAL R: not included in any glyphset definition</li>
<li>U+1DE3 COMBINING LATIN SMALL LETTER R ROTUNDA: not included in any glyphset definition</li>
<li>U+1DE4 COMBINING LATIN SMALL LETTER S: not included in any glyphset definition</li>
<li>U+1DE5 COMBINING LATIN SMALL LETTER LONG S: not included in any glyphset definition</li>
<li>U+1DE6 COMBINING LATIN SMALL LETTER Z: not included in any glyphset definition</li>
<li>U+1DE7 COMBINING LATIN SMALL LETTER ALPHA: not included in any glyphset definition</li>
<li>U+1DE8 COMBINING LATIN SMALL LETTER B: not included in any glyphset definition</li>
<li>U+1DE9 COMBINING LATIN SMALL LETTER BETA: not included in any glyphset definition</li>
<li>U+1DEA COMBINING LATIN SMALL LETTER SCHWA: not included in any glyphset definition</li>
<li>U+1DEB COMBINING LATIN SMALL LETTER F: not included in any glyphset definition</li>
<li>U+1DEC COMBINING LATIN SMALL LETTER L WITH DOUBLE MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+1DED COMBINING LATIN SMALL LETTER O WITH LIGHT CENTRALIZATION STROKE: not included in any glyphset definition</li>
<li>U+1DEE COMBINING LATIN SMALL LETTER P: not included in any glyphset definition</li>
<li>U+1DEF COMBINING LATIN SMALL LETTER ESH: not included in any glyphset definition</li>
<li>U+1DF0 COMBINING LATIN SMALL LETTER U WITH LIGHT CENTRALIZATION STROKE: not included in any glyphset definition</li>
<li>U+1DF1 COMBINING LATIN SMALL LETTER W: not included in any glyphset definition</li>
<li>U+1DF2 COMBINING LATIN SMALL LETTER A WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF3 COMBINING LATIN SMALL LETTER O WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF4 COMBINING LATIN SMALL LETTER U WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF5 COMBINING UP TACK ABOVE: not included in any glyphset definition</li>
<li>U+1DFB COMBINING DELETION MARK: try adding newa</li>
<li>U+1DFC COMBINING DOUBLE INVERTED BREVE BELOW: not included in any glyphset definition</li>
<li>U+1DFD COMBINING ALMOST EQUAL TO BELOW: not included in any glyphset definition</li>
<li>U+1DFE COMBINING LEFT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+1DFF COMBINING RIGHT ARROWHEAD AND DOWN ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, arabic, yi</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2016 DOUBLE VERTICAL LINE: try adding math</li>
<li>U+2017 DOUBLE LOW LINE: try adding math</li>
<li>U+201B SINGLE HIGH-REVERSED-9 QUOTATION MARK: try adding adlam</li>
<li>U+201F DOUBLE HIGH-REVERSED-9 QUOTATION MARK: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2023 TRIANGULAR BULLET: not included in any glyphset definition</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+2028 LINE SEPARATOR: not included in any glyphset definition</li>
<li>U+2029 PARAGRAPH SEPARATOR: not included in any glyphset definition</li>
<li>U+202A LEFT-TO-RIGHT EMBEDDING: not included in any glyphset definition</li>
<li>U+202B RIGHT-TO-LEFT EMBEDDING: not included in any glyphset definition</li>
<li>U+202C POP DIRECTIONAL FORMATTING: not included in any glyphset definition</li>
<li>U+202D LEFT-TO-RIGHT OVERRIDE: not included in any glyphset definition</li>
<li>U+202E RIGHT-TO-LEFT OVERRIDE: try adding tifinagh</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: phags-pa, yi, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2031 PER TEN THOUSAND SIGN: not included in any glyphset definition</li>
<li>U+2034 TRIPLE PRIME: try adding math</li>
<li>U+2035 REVERSED PRIME: try adding math</li>
<li>U+2036 REVERSED DOUBLE PRIME: try adding math</li>
<li>U+2037 REVERSED TRIPLE PRIME: try adding math</li>
<li>U+2038 CARET: try adding math</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+203C DOUBLE EXCLAMATION MARK: try adding math</li>
<li>U+203D INTERROBANG: not included in any glyphset definition</li>
<li>U+203E OVERLINE: not included in any glyphset definition</li>
<li>U+203F UNDERTIE: not included in any glyphset definition</li>
<li>U+2040 CHARACTER TIE: try adding math</li>
<li>U+2041 CARET INSERTION POINT: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+2043 HYPHEN BULLET: try adding math</li>
<li>U+2045 LEFT SQUARE BRACKET WITH QUILL: not included in any glyphset definition</li>
<li>U+2046 RIGHT SQUARE BRACKET WITH QUILL: not included in any glyphset definition</li>
<li>U+2047 DOUBLE QUESTION MARK: try adding math</li>
<li>U+2048 QUESTION EXCLAMATION MARK: try adding mongolian</li>
<li>U+2049 EXCLAMATION QUESTION MARK: try adding mongolian</li>
<li>U+204A TIRONIAN SIGN ET: not included in any glyphset definition</li>
<li>U+204B REVERSED PILCROW SIGN: not included in any glyphset definition</li>
<li>U+204C BLACK LEFTWARDS BULLET: not included in any glyphset definition</li>
<li>U+204D BLACK RIGHTWARDS BULLET: not included in any glyphset definition</li>
<li>U+204E LOW ASTERISK: not included in any glyphset definition</li>
<li>U+204F REVERSED SEMICOLON: try adding one of: arabic, adlam</li>
<li>U+2050 CLOSE UP: try adding math</li>
<li>U+2051 TWO ASTERISKS ALIGNED VERTICALLY: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2053 SWUNG DASH: try adding coptic</li>
<li>U+2054 INVERTED UNDERTIE: not included in any glyphset definition</li>
<li>U+2055 FLOWER PUNCTUATION MARK: try adding syloti-nagri</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2057 QUADRUPLE PRIME: try adding math</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205A TWO DOT PUNCTUATION: try adding one of: lycian, old-hungarian, glagolitic, georgian, old-turkic, carian</li>
<li>U+205B FOUR DOT MARK: not included in any glyphset definition</li>
<li>U+205C DOTTED CROSS: not included in any glyphset definition</li>
<li>U+205D TRICOLON: try adding one of: old-hungarian, carian, meroitic-hieroglyphs, meroitic</li>
<li>U+205E VERTICAL FOUR DOTS: try adding old-hungarian</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2060 WORD JOINER: not included in any glyphset definition</li>
<li>U+2061 FUNCTION APPLICATION: not included in any glyphset definition</li>
<li>U+2062 INVISIBLE TIMES: not included in any glyphset definition</li>
<li>U+2063 INVISIBLE SEPARATOR: not included in any glyphset definition</li>
<li>U+2064 INVISIBLE PLUS: not included in any glyphset definition</li>
<li>U+2066 LEFT-TO-RIGHT ISOLATE: not included in any glyphset definition</li>
<li>U+2067 RIGHT-TO-LEFT ISOLATE: not included in any glyphset definition</li>
<li>U+2068 FIRST STRONG ISOLATE: not included in any glyphset definition</li>
<li>U+2069 POP DIRECTIONAL ISOLATE: not included in any glyphset definition</li>
<li>U+206A INHIBIT SYMMETRIC SWAPPING: not included in any glyphset definition</li>
<li>U+206B ACTIVATE SYMMETRIC SWAPPING: not included in any glyphset definition</li>
<li>U+206C INHIBIT ARABIC FORM SHAPING: not included in any glyphset definition</li>
<li>U+206D ACTIVATE ARABIC FORM SHAPING: not included in any glyphset definition</li>
<li>U+206E NATIONAL DIGIT SHAPES: not included in any glyphset definition</li>
<li>U+206F NOMINAL DIGIT SHAPES: not included in any glyphset definition</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2071 SUPERSCRIPT LATIN SMALL LETTER I: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+207A SUPERSCRIPT PLUS SIGN: try adding math</li>
<li>U+207B SUPERSCRIPT MINUS: try adding math</li>
<li>U+207C SUPERSCRIPT EQUALS SIGN: try adding math</li>
<li>U+207D SUPERSCRIPT LEFT PARENTHESIS: try adding math</li>
<li>U+207E SUPERSCRIPT RIGHT PARENTHESIS: try adding math</li>
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
<li>U+208A SUBSCRIPT PLUS SIGN: try adding math</li>
<li>U+208B SUBSCRIPT MINUS: try adding math</li>
<li>U+208C SUBSCRIPT EQUALS SIGN: try adding math</li>
<li>U+208D SUBSCRIPT LEFT PARENTHESIS: try adding math</li>
<li>U+208E SUBSCRIPT RIGHT PARENTHESIS: try adding math</li>
<li>U+2090 LATIN SUBSCRIPT SMALL LETTER A: try adding math</li>
<li>U+2091 LATIN SUBSCRIPT SMALL LETTER E: try adding math</li>
<li>U+2092 LATIN SUBSCRIPT SMALL LETTER O: try adding math</li>
<li>U+2093 LATIN SUBSCRIPT SMALL LETTER X: try adding math</li>
<li>U+2094 LATIN SUBSCRIPT SMALL LETTER SCHWA: try adding math</li>
<li>U+2095 LATIN SUBSCRIPT SMALL LETTER H: try adding math</li>
<li>U+2096 LATIN SUBSCRIPT SMALL LETTER K: try adding math</li>
<li>U+2097 LATIN SUBSCRIPT SMALL LETTER L: try adding math</li>
<li>U+2098 LATIN SUBSCRIPT SMALL LETTER M: try adding math</li>
<li>U+2099 LATIN SUBSCRIPT SMALL LETTER N: try adding math</li>
<li>U+209A LATIN SUBSCRIPT SMALL LETTER P: try adding math</li>
<li>U+209B LATIN SUBSCRIPT SMALL LETTER S: try adding math</li>
<li>U+209C LATIN SUBSCRIPT SMALL LETTER T: try adding math</li>
<li>U+20F0 COMBINING ASTERISK ABOVE: try adding one of: grantha, devanagari</li>
<li>U+2100 ACCOUNT OF: try adding math</li>
<li>U+2101 ADDRESSED TO THE SUBJECT: try adding math</li>
<li>U+2102 DOUBLE-STRUCK CAPITAL C: try adding math</li>
<li>U+2103 DEGREE CELSIUS: try adding math</li>
<li>U+2104 CENTRE LINE SYMBOL: try adding math</li>
<li>U+2105 CARE OF: try adding math</li>
<li>U+2106 CADA UNA: try adding math</li>
<li>U+2107 EULER CONSTANT: try adding math</li>
<li>U+2108 SCRUPLE: try adding math</li>
<li>U+2109 DEGREE FAHRENHEIT: try adding math</li>
<li>U+210A SCRIPT SMALL G: try adding math</li>
<li>U+210B SCRIPT CAPITAL H: try adding math</li>
<li>U+210C BLACK-LETTER CAPITAL H: try adding math</li>
<li>U+210D DOUBLE-STRUCK CAPITAL H: try adding math</li>
<li>U+210E PLANCK CONSTANT: try adding math</li>
<li>U+210F PLANCK CONSTANT OVER TWO PI: try adding math</li>
<li>U+2110 SCRIPT CAPITAL I: try adding math</li>
<li>U+2111 BLACK-LETTER CAPITAL I: try adding math</li>
<li>U+2112 SCRIPT CAPITAL L: try adding math</li>
<li>U+2114 L B BAR SYMBOL: try adding math</li>
<li>U+2115 DOUBLE-STRUCK CAPITAL N: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2118 SCRIPT CAPITAL P: try adding math</li>
<li>U+2119 DOUBLE-STRUCK CAPITAL P: try adding math</li>
<li>U+211A DOUBLE-STRUCK CAPITAL Q: try adding math</li>
<li>U+211B SCRIPT CAPITAL R: try adding math</li>
<li>U+211C BLACK-LETTER CAPITAL R: try adding math</li>
<li>U+211D DOUBLE-STRUCK CAPITAL R: try adding math</li>
<li>U+211E PRESCRIPTION TAKE: try adding math</li>
<li>U+211F RESPONSE: try adding math</li>
<li>U+2120 SERVICE MARK: try adding math</li>
<li>U+2121 TELEPHONE SIGN: try adding math</li>
<li>U+2123 VERSICLE: try adding math</li>
<li>U+2124 DOUBLE-STRUCK CAPITAL Z: try adding math</li>
<li>U+2125 OUNCE SIGN: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2127 INVERTED OHM SIGN: try adding math</li>
<li>U+2128 BLACK-LETTER CAPITAL Z: try adding math</li>
<li>U+2129 TURNED GREEK SMALL LETTER IOTA: try adding math</li>
<li>U+212A KELVIN SIGN: try adding math</li>
<li>U+212B ANGSTROM SIGN: try adding math</li>
<li>U+212C SCRIPT CAPITAL B: try adding math</li>
<li>U+212D BLACK-LETTER CAPITAL C: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+212F SCRIPT SMALL E: try adding math</li>
<li>U+2130 SCRIPT CAPITAL E: try adding math</li>
<li>U+2131 SCRIPT CAPITAL F: try adding math</li>
<li>U+2132 TURNED CAPITAL F: try adding math</li>
<li>U+2133 SCRIPT CAPITAL M: try adding math</li>
<li>U+2134 SCRIPT SMALL O: try adding math</li>
<li>U+2135 ALEF SYMBOL: try adding math</li>
<li>U+2136 BET SYMBOL: try adding math</li>
<li>U+2137 GIMEL SYMBOL: try adding math</li>
<li>U+2138 DALET SYMBOL: try adding math</li>
<li>U+2139 INFORMATION SOURCE: try adding math</li>
<li>U+213A ROTATED CAPITAL Q: try adding math</li>
<li>U+213B FACSIMILE SIGN: try adding math</li>
<li>U+213C DOUBLE-STRUCK SMALL PI: try adding math</li>
<li>U+213D DOUBLE-STRUCK SMALL GAMMA: try adding math</li>
<li>U+213E DOUBLE-STRUCK CAPITAL GAMMA: try adding math</li>
<li>U+213F DOUBLE-STRUCK CAPITAL PI: try adding math</li>
<li>U+2140 DOUBLE-STRUCK N-ARY SUMMATION: try adding math</li>
<li>U+2141 TURNED SANS-SERIF CAPITAL G: try adding math</li>
<li>U+2142 TURNED SANS-SERIF CAPITAL L: try adding math</li>
<li>U+2143 REVERSED SANS-SERIF CAPITAL L: try adding math</li>
<li>U+2144 TURNED SANS-SERIF CAPITAL Y: try adding math</li>
<li>U+2145 DOUBLE-STRUCK ITALIC CAPITAL D: try adding math</li>
<li>U+2146 DOUBLE-STRUCK ITALIC SMALL D: try adding math</li>
<li>U+2147 DOUBLE-STRUCK ITALIC SMALL E: try adding math</li>
<li>U+2148 DOUBLE-STRUCK ITALIC SMALL I: try adding math</li>
<li>U+2149 DOUBLE-STRUCK ITALIC SMALL J: try adding math</li>
<li>U+214A PROPERTY LINE: try adding math</li>
<li>U+214B TURNED AMPERSAND: try adding math</li>
<li>U+214C PER SIGN: try adding math</li>
<li>U+214D AKTIESELSKAB: try adding math</li>
<li>U+214E TURNED SMALL F: try adding math</li>
<li>U+214F SYMBOL FOR SAMARITAN SOURCE: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2184 LATIN SMALL LETTER REVERSED C: not included in any glyphset definition</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+21A8 UP DOWN ARROW WITH BASE: try adding math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, math, yi, tai-tham</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+221F RIGHT ANGLE: try adding math</li>
<li>U+2229 INTERSECTION: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2261 IDENTICAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+2302 HOUSE: try adding symbols</li>
<li>U+2310 REVERSED NOT SIGN: try adding math</li>
<li>U+2320 TOP HALF INTEGRAL: try adding math</li>
<li>U+2321 BOTTOM HALF INTEGRAL: try adding math</li>
<li>U+2500 BOX DRAWINGS LIGHT HORIZONTAL: try adding symbols2</li>
<li>U+2502 BOX DRAWINGS LIGHT VERTICAL: try adding symbols2</li>
<li>U+250C BOX DRAWINGS LIGHT DOWN AND RIGHT: try adding symbols2</li>
<li>U+2510 BOX DRAWINGS LIGHT DOWN AND LEFT: try adding symbols2</li>
<li>U+2514 BOX DRAWINGS LIGHT UP AND RIGHT: try adding symbols2</li>
<li>U+2518 BOX DRAWINGS LIGHT UP AND LEFT: try adding symbols2</li>
<li>U+251C BOX DRAWINGS LIGHT VERTICAL AND RIGHT: try adding symbols2</li>
<li>U+2524 BOX DRAWINGS LIGHT VERTICAL AND LEFT: try adding symbols2</li>
<li>U+252C BOX DRAWINGS LIGHT DOWN AND HORIZONTAL: try adding symbols2</li>
<li>U+2534 BOX DRAWINGS LIGHT UP AND HORIZONTAL: try adding symbols2</li>
<li>U+253C BOX DRAWINGS LIGHT VERTICAL AND HORIZONTAL: try adding symbols2</li>
<li>U+2550 BOX DRAWINGS DOUBLE HORIZONTAL: try adding symbols2</li>
<li>U+2551 BOX DRAWINGS DOUBLE VERTICAL: try adding symbols2</li>
<li>U+2552 BOX DRAWINGS DOWN SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+2553 BOX DRAWINGS DOWN DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+2554 BOX DRAWINGS DOUBLE DOWN AND RIGHT: try adding symbols2</li>
<li>U+2555 BOX DRAWINGS DOWN SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+2556 BOX DRAWINGS DOWN DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+2557 BOX DRAWINGS DOUBLE DOWN AND LEFT: try adding symbols2</li>
<li>U+2558 BOX DRAWINGS UP SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+2559 BOX DRAWINGS UP DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+255A BOX DRAWINGS DOUBLE UP AND RIGHT: try adding symbols2</li>
<li>U+255B BOX DRAWINGS UP SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+255C BOX DRAWINGS UP DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+255D BOX DRAWINGS DOUBLE UP AND LEFT: try adding symbols2</li>
<li>U+255E BOX DRAWINGS VERTICAL SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+255F BOX DRAWINGS VERTICAL DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+2560 BOX DRAWINGS DOUBLE VERTICAL AND RIGHT: try adding symbols2</li>
<li>U+2561 BOX DRAWINGS VERTICAL SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+2562 BOX DRAWINGS VERTICAL DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+2563 BOX DRAWINGS DOUBLE VERTICAL AND LEFT: try adding symbols2</li>
<li>U+2564 BOX DRAWINGS DOWN SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+2565 BOX DRAWINGS DOWN DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+2566 BOX DRAWINGS DOUBLE DOWN AND HORIZONTAL: try adding symbols2</li>
<li>U+2567 BOX DRAWINGS UP SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+2568 BOX DRAWINGS UP DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+2569 BOX DRAWINGS DOUBLE UP AND HORIZONTAL: try adding symbols2</li>
<li>U+256A BOX DRAWINGS VERTICAL SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+256B BOX DRAWINGS VERTICAL DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+256C BOX DRAWINGS DOUBLE VERTICAL AND HORIZONTAL: try adding symbols2</li>
<li>U+2580 UPPER HALF BLOCK: try adding symbols2</li>
<li>U+2584 LOWER HALF BLOCK: try adding symbols2</li>
<li>U+2588 FULL BLOCK: try adding symbols2</li>
<li>U+258C LEFT HALF BLOCK: try adding symbols2</li>
<li>U+2590 RIGHT HALF BLOCK: try adding symbols2</li>
<li>U+2591 LIGHT SHADE: try adding symbols2</li>
<li>U+2592 MEDIUM SHADE: try adding symbols2</li>
<li>U+2593 DARK SHADE: try adding symbols2</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25AA BLACK SMALL SQUARE: try adding symbols</li>
<li>U+25AB WHITE SMALL SQUARE: try adding symbols</li>
<li>U+25AC BLACK RECTANGLE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BA BLACK RIGHT-POINTING POINTER: try adding symbols</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C4 BLACK LEFT-POINTING POINTER: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+25D8 INVERSE BULLET: try adding symbols</li>
<li>U+25D9 INVERSE WHITE CIRCLE: try adding symbols</li>
<li>U+25E6 WHITE BULLET: try adding symbols</li>
<li>U+263A WHITE SMILING FACE: try adding symbols</li>
<li>U+263B BLACK SMILING FACE: try adding symbols</li>
<li>U+263C WHITE SUN WITH RAYS: try adding symbols</li>
<li>U+2640 FEMALE SIGN: try adding symbols</li>
<li>U+2642 MALE SIGN: try adding symbols</li>
<li>U+2660 BLACK SPADE SUIT: try adding symbols</li>
<li>U+2663 BLACK CLUB SUIT: try adding symbols</li>
<li>U+2665 BLACK HEART SUIT: try adding symbols</li>
<li>U+2666 BLACK DIAMOND SUIT: try adding symbols</li>
<li>U+266A EIGHTH NOTE: try adding one of: symbols, music</li>
<li>U+266B BEAMED EIGHTH NOTES: try adding one of: symbols, music</li>
<li>U+266F MUSIC SHARP SIGN: try adding one of: symbols, music, math</li>
<li>U+2E00 RIGHT ANGLE SUBSTITUTION MARKER: not included in any glyphset definition</li>
<li>U+2E01 RIGHT ANGLE DOTTED SUBSTITUTION MARKER: not included in any glyphset definition</li>
<li>U+2E02 LEFT SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E03 RIGHT SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E04 LEFT DOTTED SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E05 RIGHT DOTTED SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E06 RAISED INTERPOLATION MARKER: not included in any glyphset definition</li>
<li>U+2E07 RAISED DOTTED INTERPOLATION MARKER: not included in any glyphset definition</li>
<li>U+2E08 DOTTED TRANSPOSITION MARKER: not included in any glyphset definition</li>
<li>U+2E09 LEFT TRANSPOSITION BRACKET: not included in any glyphset definition</li>
<li>U+2E0A RIGHT TRANSPOSITION BRACKET: not included in any glyphset definition</li>
<li>U+2E0B RAISED SQUARE: not included in any glyphset definition</li>
<li>U+2E0C LEFT RAISED OMISSION BRACKET: not included in any glyphset definition</li>
<li>U+2E0D RIGHT RAISED OMISSION BRACKET: not included in any glyphset definition</li>
<li>U+2E0E EDITORIAL CORONIS: not included in any glyphset definition</li>
<li>U+2E0F PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E10 FORKED PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E11 REVERSED FORKED PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E12 HYPODIASTOLE: not included in any glyphset definition</li>
<li>U+2E13 DOTTED OBELOS: not included in any glyphset definition</li>
<li>U+2E14 DOWNWARDS ANCORA: not included in any glyphset definition</li>
<li>U+2E15 UPWARDS ANCORA: not included in any glyphset definition</li>
<li>U+2E16 DOTTED RIGHT-POINTING ANGLE: not included in any glyphset definition</li>
<li>U+2E17 DOUBLE OBLIQUE HYPHEN: try adding coptic</li>
<li>U+2E18 INVERTED INTERROBANG: not included in any glyphset definition</li>
<li>U+2E19 PALM BRANCH: not included in any glyphset definition</li>
<li>U+2E1A HYPHEN WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+2E1B TILDE WITH RING ABOVE: not included in any glyphset definition</li>
<li>U+2E1C LEFT LOW PARAPHRASE BRACKET: try adding nko</li>
<li>U+2E1D RIGHT LOW PARAPHRASE BRACKET: try adding nko</li>
<li>U+2E1E TILDE WITH DOT ABOVE: not included in any glyphset definition</li>
<li>U+2E1F TILDE WITH DOT BELOW: not included in any glyphset definition</li>
<li>U+2E20 LEFT VERTICAL BAR WITH QUILL: not included in any glyphset definition</li>
<li>U+2E21 RIGHT VERTICAL BAR WITH QUILL: not included in any glyphset definition</li>
<li>U+2E22 TOP LEFT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E23 TOP RIGHT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E24 BOTTOM LEFT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E25 BOTTOM RIGHT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E26 LEFT SIDEWAYS U BRACKET: not included in any glyphset definition</li>
<li>U+2E27 RIGHT SIDEWAYS U BRACKET: not included in any glyphset definition</li>
<li>U+2E28 LEFT DOUBLE PARENTHESIS: try adding adlam</li>
<li>U+2E29 RIGHT DOUBLE PARENTHESIS: try adding adlam</li>
<li>U+2E2A TWO DOTS OVER ONE DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2B ONE DOT OVER TWO DOTS PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2C SQUARED FOUR DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2D FIVE DOT MARK: not included in any glyphset definition</li>
<li>U+2E2E REVERSED QUESTION MARK: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E30 RING POINT: try adding one of: avestan, old-turkic</li>
<li>U+2E31 WORD SEPARATOR MIDDLE DOT: try adding one of: avestan, old-hungarian, kaithi, georgian, samaritan, carian, lydian</li>
<li>U+2E32 TURNED COMMA: not included in any glyphset definition</li>
<li>U+2E33 RAISED DOT: try adding coptic</li>
<li>U+2E34 RAISED COMMA: try adding coptic</li>
<li>U+2E35 TURNED SEMICOLON: not included in any glyphset definition</li>
<li>U+2E36 DAGGER WITH LEFT GUARD: not included in any glyphset definition</li>
<li>U+2E37 DAGGER WITH RIGHT GUARD: not included in any glyphset definition</li>
<li>U+2E38 TURNED DAGGER: not included in any glyphset definition</li>
<li>U+2E39 TOP HALF SECTION SIGN: not included in any glyphset definition</li>
<li>U+2E3A TWO-EM DASH: not included in any glyphset definition</li>
<li>U+2E3B THREE-EM DASH: not included in any glyphset definition</li>
<li>U+2E3C STENOGRAPHIC FULL STOP: try adding duployan</li>
<li>U+2E3D VERTICAL SIX DOTS: not included in any glyphset definition</li>
<li>U+2E3E WIGGLY VERTICAL LINE: not included in any glyphset definition</li>
<li>U+2E3F CAPITULUM: not included in any glyphset definition</li>
<li>U+2E40 DOUBLE HYPHEN: not included in any glyphset definition</li>
<li>U+2E41 REVERSED COMMA: try adding one of: arabic, old-hungarian, adlam</li>
<li>U+2E42 DOUBLE LOW-REVERSED-9 QUOTATION MARK: not included in any glyphset definition</li>
<li>U+A717 MODIFIER LETTER DOT VERTICAL BAR: not included in any glyphset definition</li>
<li>U+A718 MODIFIER LETTER DOT SLASH: not included in any glyphset definition</li>
<li>U+A719 MODIFIER LETTER DOT HORIZONTAL BAR: not included in any glyphset definition</li>
<li>U+A71A MODIFIER LETTER LOWER RIGHT CORNER ANGLE: not included in any glyphset definition</li>
<li>U+A71B MODIFIER LETTER RAISED UP ARROW: not included in any glyphset definition</li>
<li>U+A71C MODIFIER LETTER RAISED DOWN ARROW: not included in any glyphset definition</li>
<li>U+A71D MODIFIER LETTER RAISED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+A71E MODIFIER LETTER RAISED INVERTED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+A71F MODIFIER LETTER LOW INVERTED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+AB30 LATIN SMALL LETTER BARRED ALPHA: not included in any glyphset definition</li>
<li>U+AB31 LATIN SMALL LETTER A REVERSED-SCHWA: not included in any glyphset definition</li>
<li>U+AB32 LATIN SMALL LETTER BLACKLETTER E: not included in any glyphset definition</li>
<li>U+AB33 LATIN SMALL LETTER BARRED E: not included in any glyphset definition</li>
<li>U+AB34 LATIN SMALL LETTER E WITH FLOURISH: not included in any glyphset definition</li>
<li>U+AB35 LATIN SMALL LETTER LENIS F: not included in any glyphset definition</li>
<li>U+AB36 LATIN SMALL LETTER SCRIPT G WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB37 LATIN SMALL LETTER L WITH INVERTED LAZY S: not included in any glyphset definition</li>
<li>U+AB38 LATIN SMALL LETTER L WITH DOUBLE MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+AB39 LATIN SMALL LETTER L WITH MIDDLE RING: not included in any glyphset definition</li>
<li>U+AB3A LATIN SMALL LETTER M WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3B LATIN SMALL LETTER N WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3C LATIN SMALL LETTER ENG WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3D LATIN SMALL LETTER BLACKLETTER O: not included in any glyphset definition</li>
<li>U+AB3E LATIN SMALL LETTER BLACKLETTER O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB3F LATIN SMALL LETTER OPEN O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB40 LATIN SMALL LETTER INVERTED OE: not included in any glyphset definition</li>
<li>U+AB41 LATIN SMALL LETTER TURNED OE WITH STROKE: not included in any glyphset definition</li>
<li>U+AB42 LATIN SMALL LETTER TURNED OE WITH HORIZONTAL STROKE: not included in any glyphset definition</li>
<li>U+AB43 LATIN SMALL LETTER TURNED O OPEN-O: not included in any glyphset definition</li>
<li>U+AB44 LATIN SMALL LETTER TURNED O OPEN-O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB45 LATIN SMALL LETTER STIRRUP R: not included in any glyphset definition</li>
<li>U+AB46 LATIN LETTER SMALL CAPITAL R WITH RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB47 LATIN SMALL LETTER R WITHOUT HANDLE: not included in any glyphset definition</li>
<li>U+AB48 LATIN SMALL LETTER DOUBLE R: not included in any glyphset definition</li>
<li>U+AB49 LATIN SMALL LETTER R WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB4A LATIN SMALL LETTER DOUBLE R WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB4B LATIN SMALL LETTER SCRIPT R: not included in any glyphset definition</li>
<li>U+AB4C LATIN SMALL LETTER SCRIPT R WITH RING: not included in any glyphset definition</li>
<li>U+AB4D LATIN SMALL LETTER BASELINE ESH: not included in any glyphset definition</li>
<li>U+AB4E LATIN SMALL LETTER U WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB4F LATIN SMALL LETTER U BAR WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB50 LATIN SMALL LETTER UI: not included in any glyphset definition</li>
<li>U+AB51 LATIN SMALL LETTER TURNED UI: not included in any glyphset definition</li>
<li>U+AB52 LATIN SMALL LETTER U WITH LEFT HOOK: not included in any glyphset definition</li>
<li>U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition</li>
<li>U+AB54 LATIN SMALL LETTER CHI WITH LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB55 LATIN SMALL LETTER CHI WITH LOW LEFT SERIF: not included in any glyphset definition</li>
<li>U+AB56 LATIN SMALL LETTER X WITH LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB57 LATIN SMALL LETTER X WITH LONG LEFT LEG: not included in any glyphset definition</li>
<li>U+AB58 LATIN SMALL LETTER X WITH LONG LEFT LEG AND LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB59 LATIN SMALL LETTER X WITH LONG LEFT LEG WITH SERIF: not included in any glyphset definition</li>
<li>U+AB5A LATIN SMALL LETTER Y WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB5B MODIFIER BREVE WITH INVERTED BREVE: not included in any glyphset definition</li>
<li>U+AB5C MODIFIER LETTER SMALL HENG: not included in any glyphset definition</li>
<li>U+AB5D MODIFIER LETTER SMALL L WITH INVERTED LAZY S: not included in any glyphset definition</li>
<li>U+AB5E MODIFIER LETTER SMALL L WITH MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+AB5F MODIFIER LETTER SMALL U WITH LEFT HOOK: not included in any glyphset definition</li>
<li>U+AB60 LATIN SMALL LETTER SAKHA YAT: not included in any glyphset definition</li>
<li>U+AB61 LATIN SMALL LETTER IOTIFIED E: not included in any glyphset definition</li>
<li>U+AB62 LATIN SMALL LETTER OPEN OE: not included in any glyphset definition</li>
<li>U+AB63 LATIN SMALL LETTER UO: not included in any glyphset definition</li>
<li>U+AB64 LATIN SMALL LETTER INVERTED ALPHA: not included in any glyphset definition</li>
<li>U+AB65 GREEK LETTER SMALL CAPITAL OMEGA: not included in any glyphset definition</li>
<li>U+F001 : not included in any glyphset definition</li>
<li>U+F002 : not included in any glyphset definition</li>
<li>U+F004 : not included in any glyphset definition</li>
<li>U+F005 : not included in any glyphset definition</li>
<li>U+F00A : not included in any glyphset definition</li>
<li>U+F00B : not included in any glyphset definition</li>
<li>U+F00C : not included in any glyphset definition</li>
<li>U+F00D : not included in any glyphset definition</li>
<li>U+F00E : not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FE20 COMBINING LIGATURE LEFT HALF: try adding caucasian-albanian</li>
<li>U+FE21 COMBINING LIGATURE RIGHT HALF: try adding caucasian-albanian</li>
<li>U+FE22 COMBINING DOUBLE TILDE LEFT HALF: try adding caucasian-albanian</li>
<li>U+FE23 COMBINING DOUBLE TILDE RIGHT HALF: try adding caucasian-albanian</li>
<li>U+FE24 COMBINING MACRON LEFT HALF: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE25 COMBINING MACRON RIGHT HALF: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE26 COMBINING CONJOINING MACRON: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE27 COMBINING LIGATURE LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE28 COMBINING LIGATURE RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE29 COMBINING TILDE LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2A COMBINING TILDE RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2B COMBINING MACRON LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2C COMBINING MACRON RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2D COMBINING CONJOINING MACRON BELOW: try adding caucasian-albanian</li>
<li>U+FFFC OBJECT REPLACEMENT CHARACTER: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>greek</code>, <code>greek-ext</code>, <code>hebrew</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ i̍ i̐ i̓ i᷆ i᷇ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̅ i̇ i̎ i̒ i̔ i̽ i̾ i̿ i͂ i͆ i͊ i͋ i͌ i͐ i͑ i͒ i͗ i͛ iͣ iͤ</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Belarusian (Cyrl, 10,064,517 speakers), Zapotec (Latn, 490,000 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Gulay (Latn, 250,478 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Longto (Latn, 5,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Fur (Latn, 1,230,163 speakers), Ejagham (Latn, 120,000 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Cicipu (Latn, 44,000 speakers), Aghem (Latn, 38,843 speakers), Kaska (Latn, 125 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Bafut (Latn, 158,146 speakers), Avokaya (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Dutch (Latn, 31,709,104 speakers), Ekpeye (Latn, 226,000 speakers), Makaa (Latn, 221,000 speakers), Northern Tutchone (Latn, 85 speakers), Yala (Latn, 200,000 speakers), Keliko (Latn, 63,000 speakers), Navajo (Latn, 166,319 speakers), Lugbara (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Bete-Bendi (Latn, 100,000 speakers), Mfumte (Latn, 79,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Teke-Ebo (Latn, 260,000 speakers), South Central Banda (Latn, 244,000 speakers), Abua (Latn, 25,000 speakers), Han (Latn, 6 speakers), Ikwere (Latn, 717,000 speakers), Nzakara (Latn, 50,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni03D2 (U+03D2): B&lt;&lt;573.5,1169.5&gt;-&lt;766.0,998.0&gt;-&lt;793.0,675.0&gt;&gt;/B&lt;&lt;793.0,675.0&gt;-&lt;811.0,872.0&gt;-&lt;881.0,1028.0&gt;&gt; = 9.998972854288642

* uni03D3 (U+03D3): B&lt;&lt;877.5,1169.5&gt;-&lt;1070.0,998.0&gt;-&lt;1097.0,675.0&gt;&gt;/B&lt;&lt;1097.0,675.0&gt;-&lt;1115.0,872.0&gt;-&lt;1185.0,1028.0&gt;&gt; = 9.998972854288642

* uni03D4 (U+03D4): B&lt;&lt;573.5,1169.5&gt;-&lt;766.0,998.0&gt;-&lt;793.0,675.0&gt;&gt;/B&lt;&lt;793.0,675.0&gt;-&lt;811.0,872.0&gt;-&lt;881.0,1028.0&gt;&gt; = 9.998972854288642

* uni210A (U+210A): B&lt;&lt;190.5,333.0&gt;-&lt;211.0,390.0&gt;-&lt;240.0,428.0&gt;&gt;/L&lt;&lt;240.0,428.0&gt;--&lt;106.0,297.0&gt;&gt; = 8.29925471425042

* uni210B (U+210B): B&lt;&lt;1054.5,1043.5&gt;-&lt;1109.0,1122.0&gt;-&lt;1165.0,1190.0&gt;&gt;/B&lt;&lt;1165.0,1190.0&gt;-&lt;1095.0,1126.0&gt;-&lt;1031.0,1075.0&gt;&gt; = 8.09131036312114

* uni2133 (U+2133): B&lt;&lt;2033.0,1106.0&gt;-&lt;2137.0,1230.0&gt;-&lt;2304.0,1421.0&gt;&gt;/B&lt;&lt;2304.0,1421.0&gt;-&lt;2197.0,1345.0&gt;-&lt;2071.0,1224.0&gt;&gt; = 13.449888368034253

* uniA731 (U+A731): L&lt;&lt;204.0,152.0&gt;--&lt;202.0,154.0&gt;&gt;/B&lt;&lt;202.0,154.0&gt;-&lt;235.0,114.0&gt;-&lt;307.5,86.5&gt;&gt; = 5.47736872882884
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* D (U+0044): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* Dcaron (U+010E): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* Eth (U+00D0): L&lt;&lt;733.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* epsilon (U+03B5): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* epsilontonos (U+03AD): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* finalmem (U+05DD): L&lt;&lt;180.0,0.0&gt;--&lt;178.0,541.0&gt;&gt;

* finalmemwide (U+FB26): L&lt;&lt;180.0,0.0&gt;--&lt;178.0,541.0&gt;&gt;

* finalnun (U+05DF): L&lt;&lt;219.0,-161.0&gt;--&lt;221.0,584.0&gt;&gt;

* integral (U+222B): L&lt;&lt;360.0,1079.0&gt;--&lt;364.0,541.0&gt;&gt;

* paragraph (U+00B6): L&lt;&lt;453.0,-258.0&gt;--&lt;455.0,565.0&gt;&gt;

* summation (U+2211): L&lt;&lt;782.0,1249.0&gt;--&lt;378.0,1251.0&gt;&gt;

* uni0110 (U+0110): L&lt;&lt;733.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni0189 (U+0189): L&lt;&lt;733.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni018A (U+018A): L&lt;&lt;903.0,-4.0&gt;--&lt;253.0,0.0&gt;&gt;

* uni0191 (U+0191): L&lt;&lt;230.0,-167.0&gt;--&lt;231.0,1262.0&gt;&gt;

* uni01C4 (U+01C4): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni01C5 (U+01C5): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni01F1 (U+01F1): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni01F2 (U+01F2): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni025B (U+025B): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* uni025C (U+025C): L&lt;&lt;88.0,733.0&gt;--&lt;87.0,929.0&gt;&gt;

* uni025D (U+025D): L&lt;&lt;88.0,733.0&gt;--&lt;87.0,929.0&gt;&gt;

* uni0278 (U+0278): L&lt;&lt;483.0,961.0&gt;--&lt;484.0,1351.0&gt;&gt;

* uni0286 (U+0286): L&lt;&lt;260.0,-87.0&gt;--&lt;259.0,989.0&gt;&gt;

* uni0286 (U+0286): L&lt;&lt;425.0,1075.0&gt;--&lt;426.0,-144.0&gt;&gt;

* uni03E2 (U+03E2): L&lt;&lt;1321.0,-167.0&gt;--&lt;1323.0,76.0&gt;&gt;

* uni0490 (U+0490): L&lt;&lt;901.0,1254.0&gt;--&lt;424.0,1255.0&gt;&gt;

* uni0528 (U+0528): L&lt;&lt;230.0,-167.0&gt;--&lt;231.0,1262.0&gt;&gt;

* uni1D08 (U+1D08): L&lt;&lt;63.0,16.0&gt;--&lt;64.0,212.0&gt;&gt;

* uni1D30 (U+1D30): L&lt;&lt;432.0,560.0&gt;--&lt;42.0,562.0&gt;&gt;

* uni1D4B (U+1D4B): L&lt;&lt;445.0,1119.0&gt;--&lt;444.0,1002.0&gt;&gt;

* uni1D4C (U+1D4C): L&lt;&lt;50.0,1002.0&gt;--&lt;49.0,1119.0&gt;&gt;

* uni1D93 (U+1D93): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* uni1D94 (U+1D94): L&lt;&lt;88.0,733.0&gt;--&lt;87.0,929.0&gt;&gt;

* uni1D9F (U+1D9F): L&lt;&lt;49.0,1002.0&gt;--&lt;48.0,1119.0&gt;&gt;

* uni1E0A (U+1E0A): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni1E0C (U+1E0C): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni1E0E (U+1E0E): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni1E10 (U+1E10): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni1E12 (U+1E12): L&lt;&lt;709.0,-4.0&gt;--&lt;59.0,0.0&gt;&gt;

* uni1F10 (U+1F10): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* uni1F11 (U+1F11): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* uni1F12 (U+1F12): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* uni1F13 (U+1F13): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* uni1F14 (U+1F14): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* uni1F15 (U+1F15): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* uni1F72 (U+1F72): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* uni1F73 (U+1F73): L&lt;&lt;773.0,929.0&gt;--&lt;772.0,733.0&gt;&gt;

* uniA717 (U+A717): L&lt;&lt;198.0,1824.0&gt;--&lt;197.0,1196.0&gt;&gt;

* uniA717 (U+A717): L&lt;&lt;88.0,1196.0&gt;--&lt;89.0,1824.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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
    <summary>⚠️ <b>WARN</b> Description strings in the name table must not exceed 200 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-description-max-length">googlefonts/name/description_max_length</a></summary>
    <div>







* ⚠️ **WARN** <p>A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries.</p>
 [code: too-long]



</div>
</details>
</div>
</details>

<details><summary>[23] Tinos-Bold.ttf</summary>
<div>
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
<td align="left">U+1D8E: LATIN SMALL LETTER Z WITH PALATAL HOOK</td>
<td align="left">U+A7C6: LATIN CAPITAL LETTER Z WITH PALATAL HOOK</td>
</tr>
<tr>
<td align="left">U+2184: LATIN SMALL LETTER REVERSED C</td>
<td align="left">U+2183: ROMAN NUMERAL REVERSED ONE HUNDRED</td>
</tr>
<tr>
<td align="left">U+A794: LATIN SMALL LETTER C WITH PALATAL HOOK</td>
<td align="left">U+A7C4: LATIN CAPITAL LETTER C WITH PALATAL HOOK</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#family-win-ascent-and-descent">family/win_ascent_and_descent</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.usWinAscent value should be equal or greater than 2068, but got 1825 instead</p>
 [code: ascent]



* 🔥 **FAIL** <p>OS/2.usWinDescent value should be equal or greater than 797, but got 443 instead</p>
 [code: descent]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Do we have the latest version of FontBakery installed? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#fontbakery-version">fontbakery_version</a></summary>
    <div>







* 🔥 **FAIL** <p>Current FontBakery version is 0.13.1, while a newer 0.13.2 is already available. Please upgrade it with 'pip install -U fontbakery'</p>
 [code: outdated-fontbakery]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking Vertical Metric Linegaps. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#linegaps">linegaps</a></summary>
    <div>







* 🔥 **FAIL** <p>hhea lineGap is not equal to 0.</p>
<p><em>Overridden</em>: This check was originally a WARN but was
overridden by the universal profile:
For Google Fonts, all messages from this check are considered FAILs.</p>
 [code: hhea]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 Metrics match hhea Metrics. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#os2-metrics-match-hhea">os2_metrics_match_hhea</a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 sTypoAscender (1387) and hhea ascent (1825) must be equal.</p>
 [code: ascender]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check tabular widths don't have kerning. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#tabular-kerning">tabular_kerning</a></summary>
    <div>







* 🔥 **FAIL** <p>Kerning between one and one is -113, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -113, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -113, should be 0</p>
 [code: has-tabular-kerning]



* 🔥 **FAIL** <p>Kerning between one and one is -113, should be 0</p>
 [code: has-tabular-kerning]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Whitespace glyphs have ink? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#whitespace-ink">whitespace_ink</a></summary>
    <div>







* 🔥 **FAIL** <p>Glyph 'uni2028' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni2029' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni205F' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uni2060' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



* 🔥 **FAIL** <p>Glyph 'uniFEFF' has ink. It needs to be replaced by an empty glyph.</p>
 [code: has-ink]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-glyphsets-shape-languages">googlefonts/glyphsets/shape_languages</a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Greek_Expert glyphset:</p>
<table>
<thead>
<tr>
<th align="left">FAIL messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Shaper didn't attach acutecomb to j</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to J</td>
<td align="left">nl_Latn (Dutch)</td>
</tr>
<tr>
<td align="left">The locl feature did not affect Eng</td>
<td align="left">bm_Latn (Bambara), dyu_Latn (Dyula), ig_Latn (Igbo), lg_Latn (Ganda), mnf_Latn (Mundani), las_Latn (Lama, Togo), dtm_Latn (Tomo Kan Dogon), dnj_Latn (Dan), nnh_Latn (Ngiemboon), ttq_Latn (Tawallammat Tamajaq), snk_Latn (Soninke), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nfr_Latn (Nafaanra), nus_Latn (Nuer), bsc_Latn (Bassari), dur_Latn (Dii), naw_Latn (Nawuri), fmp_Latn (Fe’fe’), sav_Latn (Saafi-Saafi), mne_Latn (Naba), azo_Latn (Awing), ig_Latn (Igbo), bzw_Latn (Basa), fuc_Latn (Pulaar), yat_Latn (Yambeta), nnw_Latn (Southern Nuni), kpo_Latn (Ikposo), log_Latn (Logo), dip_Latn (Dinka, Northeastern), twq_Latn (Tasawaq), nfu_Latn (Mfumte), ajg_Latn (Aja), xwe_Latn (Gbe, Xwela), loq_Latn (Lobala), bsp_Latn (Baga Sitemu), wan_Latn (Wan), bcw_Latn (Bana), maw_Latn (Mampruli), myk_Latn (Mamara Senoufo), mfv_Latn (Mandjak), tuq_Latn (Tedaga), agc_Latn (Agatu), krs_Latn (Gbaya, Sudan), bbo_Latn (Northern Bobo Madaré), mfd_Latn (Mendankwe-Nkwen), etu_Latn (Ejagham), xuo_Latn (Kuo), xon_Latn (Konkomba), sok_Latn (Sokoro), adj_Latn (Adioukrou), avn_Latn (Avatime), nku_Latn (Kulango, Bouna), mcn_Latn (Masana), nym_Latn (Nyamwezi), shz_Latn (Syenara Senoufo), lun_Latn (Lunda), ade_Latn (Adele), mdj_Latn (Mangbetu), gur_Latn (Frafra), gna_Latn (Kaansa), mua_Latn (Mundang), bex_Latn (Jur Modo), fvr_Latn (Fur), lam_Latn (Lamba), bza_Latn (Bandi), wci_Latn (Gbe, Waci), mcu_Latn (Mambila, Cameroon), taq_Latn (Tamasheq (Latin)), kvf_Latn (Kabalai), blo_Latn (Anii), gde_Latn (Gude), tik_Latn (Tikar), nmg_Latn (Kwasio), sig_Latn (Paasaal), dow_Latn (Doyayo), dag_Latn (Dagbani), keu_Latn (Akebu), giz_Latn (Southern Giziga), bfd_Latn (Bafut), dno_Latn (Ndrulo), bud_Latn (Ntcham), dyo_Latn (Jola-Fonyi), ybb_Latn (Yemba), tvu_Latn (Tunen), kus_Latn (Kusaal), agq_Latn (Aghem), kzc_Latn (Bondoukou Kulango), ksf_Latn (Bafia), wwa_Latn (Waama), khq_Latn (Koyra Chiini), tod_Latn (Toma), ewo_Latn (Ewondo), muy_Latn (Muyang), cae_Latn (Lehar), vut_Latn (Vute), bzx_Latn (Bozo, Hainyaxo), xsm_Latn (Kasem), xrb_Latn (Karaboro, Eastern), gmm_Latn (Gbaya-Mbodomo), gnd_Latn (Zulgo-Gemzek), nmz_Latn (Nawdm), kpz_Latn (Sapiny), dyu_Latn (Dyula), kdj_Latn (Karamojong), mbu_Latn (Mbula-Bwazza), cou_Latn (Wamey), ny_Latn (Nyanja), avu_Latn (Avokaya), mev_Latn (Mano), bib_Latn (Bissa), ntr_Latn (Delo), udu_Latn (Uduk), ahl_Latn (Igo), spp_Latn (Sénoufo, Supyire), ife_Latn (Ifè), mfi_Latn (Wandala), srr_Latn (Serer), fuf_Latn (Pular), kyq_Latn (Kenga), ikx_Latn (Ik), pbi_Latn (Parkwa), cko_Latn (Anufo), kye_Latn (Krache), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), ken_Latn (Kenyang), tcd_Latn (Tafi), vag_Latn (Vagla), yam_Latn (Yamba), saf_Latn (Safaliba), pil_Latn (Yom), mgc_Latn (Morokodo), mmu_Latn (Mmaala), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), ndz_Latn (Ndogo), cme_Latn (Cerma), kqp_Latn (Kimré), ffm_Latn (Maasina Fulfulde), pnz_Latn (Pana, Central African Republic), kao_Latn (Xaasongaxango), knf_Latn (Mankanya), mur_Latn (Murle), nhu_Latn (Noone), neb_Latn (Toura), lg_Latn (Ganda), ses_Latn (Koyraboro Senni), daa_Latn (Dangaléat), fub_Latn (Fulfulde, Adamawa), ahs_Latn (Ashe), mwk_Latn (Kita Maninkakan), ddn_Latn (Dendi), acd_Latn (Gikyode), xed_Latn (Hdi), kss_Latn (Southern Kisi), kqs_Latn (Kissi, Northern), sef_Latn (Cebaara Senoufo), dgi_Latn (Northern Dagara), ncu_Latn (Chumburung), kmy_Latn (Koma), lee_Latn (Lyélé), bbj_Latn (Ghomala), lmp_Latn (Limbum), kib_Latn (Koalib), wok_Latn (Longto), bav_Latn (Vengo), byv_Latn (Medumba), bqv_Latn (Koro Wachi), kyf_Latn (Kouya), dzg_Latn (Dazaga), yas_Latn (Nugunu), ekm_Latn (Elip), snf_Latn (Noon), sxw_Latn (Saxwe Gbe), nza_Latn (Tigon Mbembe), toq_Latn (Toposa), gej_Latn (Gen), tnr_Latn (Ménik), jgo_Latn (Ngomba), ktj_Latn (Krumen, Plapo), gjn_Latn (Gonja), fuq_Latn (Central-Eastern Niger Fulfulde), bum_Latn (Bulu), fue_Latn (Fulfulde, Borgu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), mgo_Latn (Metaʼ), nko_Latn (Nkonya), ebo_Latn (Teke-Ebo), fan_Latn (Fang), ozm_Latn (Koonzime), dop_Latn (Lukpa), mcp_Latn (Makaa), mls_Latn (Masalit), god_Latn (Godié), bss_Latn (Akoose), mor_Latn (Moro), kbo_Latn (Keliko), kia_Latn (Kim), bfa_Latn (Bari), kdh_Latn (Tem), lok_Latn (Loko), ach_Latn (Acoli), sil_Latn (Sisaala, Tumulung), lns_Latn (Lamnso’), bze_Latn (Jenaama Bozo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), lig_Latn (Ligbi), csk_Latn (Jola-Kasa), anv_Latn (Denya), rub_Latn (Gungu), mnk_Latn (Mandinka), mgd_Latn (Moru), moa_Latn (Mwan), gng_Latn (Ngangam), mas_Latn (Masai), dje_Latn (Zarma), mbo_Latn (Mbo), yav_Latn (Yangben), dua_Latn (Duala), ted_Latn (Krumen, Tepo), tem_Latn (Timne), fod_Latn (Foodo), soy_Latn (Miyobe), wo_Latn (Wolof), mdt_Latn (Mbere), boz_Latn (Tiéyaxo Bozo), gud_Latn (Dida, Yocoboué), nhb_Latn (Beng), fuh_Latn (Fulfulde, Western Niger), bim_Latn (Bimoba), kzr_Latn (Karang), kbp_Latn (Kabiyé), mfq_Latn (Moba), gux_Latn (Gourmanchéma), bjt_Latn (Balanta-Ganja), knp_Latn (Kwanja), dyi_Latn (Sénoufo, Djimini), gaa_Latn (Ga), tpm_Latn (Tampulma), idu_Latn (Idoma), bm_Latn (Bambara), lem_Latn (Nomaande), emk_Latn (Maninkakan, Eastern), meq_Latn (Merey), bkm_Latn (Kom), mzw_Latn (Deg), nuv_Latn (Nuni, Northern), bqj_Latn (Bandial), lia_Latn (Limba, West-Central), pug_Latn (Phuie), aks_Latn (Akeselem), dts_Latn (Dogon, Toro So), ndv_Latn (Ndut), hag_Latn (Hanga), bas_Latn (Basaa), laj_Latn (Lango, Uganda), gkp_Latn (Kpelle, Guinea) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to r</td>
<td align="left">ha_Latn (Hausa) and ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to R</td>
<td align="left">ha_Latn (Hausa) and ha_Latn (Hausa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECB</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), avu_Latn (Avokaya), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECA</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), avu_Latn (Avokaya), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECB</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECA</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to m</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), ig_Latn (Igbo), yo_Latn_BJ (Yoruba, Benin), yo_Latn (Yoruba), tik_Latn (Tikar), bud_Latn (Ntcham), mev_Latn (Mano), kyq_Latn (Kenga), ikw_Latn (Ikwere), tbz_Latn (Ditammari), jgo_Latn (Ngomba), gvl_Latn (Gulay) and nup_Latn (Nupe-Nupe-Tako)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to M</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), ig_Latn (Igbo), yo_Latn_BJ (Yoruba, Benin), yo_Latn (Yoruba), tik_Latn (Tikar), bud_Latn (Ntcham), mev_Latn (Mano), kyq_Latn (Kenga), ikw_Latn (Ikwere), tbz_Latn (Ditammari), jgo_Latn (Ngomba), gvl_Latn (Gulay) and nup_Latn (Nupe-Nupe-Tako)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECD</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1ECC</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECD</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere), ann_Latn (Obolo) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1ECC</td>
<td align="left">ig_Latn (Igbo), yo_Latn (Yoruba), igb_Latn (Ebira), ig_Latn (Igbo), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere), ann_Latn (Obolo) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EE5</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EE4</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), mhi_Latn (Ma’di), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EE5</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EE4</td>
<td align="left">ig_Latn (Igbo), igb_Latn (Ebira), ig_Latn (Igbo), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EB9</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EB9</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EB8</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), mhi_Latn (Ma’di), ish_Latn (Esan), ijs_Latn (Ijo, Southeast), abn_Latn (Abua), ikw_Latn (Ikwere), kbo_Latn (Keliko) and pcm_Latn (Nigerian Pidgin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EB8</td>
<td align="left">yo_Latn (Yoruba), igb_Latn (Ebira), yo_Latn (Yoruba), ish_Latn (Esan), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to O</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ocircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0268</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), nzk_Latn (Nzakara), ozm_Latn (Koonzime), mcp_Latn (Makaa), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D2</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), nfu_Latn (Mfumte), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), tcd_Latn (Tafi), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), gov_Latn (Goo), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Agrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0186</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0327</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0254</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to o</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0197</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), nyb_Latn (Nyangbo), yav_Latn (Yangben), mge_Latn (Mango), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to U</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0268</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0197</td>
<td align="left">mnf_Latn (Mundani) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ugrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to A</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ograve</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to a</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ucircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0228</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to ugrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0327</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0259</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), bfd_Latn (Bafut), ewo_Latn (Ewondo), ksp_Latn (Kabba), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0327</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0259</td>
<td align="left">mnf_Latn (Mundani), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0229</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), nyb_Latn (Nyangbo), yav_Latn (Yangben), mge_Latn (Mango), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018F</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), gnd_Latn (Zulgo-Gemzek), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), byv_Latn (Medumba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), gvl_Latn (Gulay), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ocircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0229</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018F</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), bfd_Latn (Bafut), ewo_Latn (Ewondo), ksp_Latn (Kabba), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0268</td>
<td align="left">mnf_Latn (Mundani) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D3</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to u</td>
<td align="left">mnf_Latn (Mundani), kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0259</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), gnd_Latn (Zulgo-Gemzek), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), byv_Latn (Medumba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), mgo_Latn (Metaʼ), gvl_Latn (Gulay), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0197</td>
<td align="left">mnf_Latn (Mundani), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), fvr_Latn (Fur), bfd_Latn (Bafut), agq_Latn (Aghem), nzk_Latn (Nzakara), ozm_Latn (Koonzime), mcp_Latn (Makaa), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to acircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01CE</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0197</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), nfu_Latn (Mfumte), bfd_Latn (Bafut), agq_Latn (Aghem), gvl_Latn (Gulay), mge_Latn (Mango), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ucircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0186</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Acircumflex</td>
<td align="left">mnf_Latn (Mundani), vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0268</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), nfu_Latn (Mfumte), bfd_Latn (Bafut), agq_Latn (Aghem), gvl_Latn (Gulay), mge_Latn (Mango), bkm_Latn (Kom) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0254</td>
<td align="left">mnf_Latn (Mundani), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), nfu_Latn (Mfumte), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), tcd_Latn (Tafi), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D4</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to agrave</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0228</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0229</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01D1</td>
<td align="left">mnf_Latn (Mundani) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018F</td>
<td align="left">mnf_Latn (Mundani), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), bfd_Latn (Bafut), ewo_Latn (Ewondo), sbd_Latn (Southern Samo), lee_Latn (Lyélé), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni01CD</td>
<td align="left">mnf_Latn (Mundani)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0228</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Ograve</td>
<td align="left">mnf_Latn (Mundani), dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ɤ, Ɤ̀, Ɤ́, Ɤ̂, Ɤ̄, Ɤ̋, Ɤ̏</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni025B</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to a</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to A</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to ae</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to AE</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to ae</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to AE</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to ae</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to AE</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to ae</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to AE</td>
<td align="left">dnj_Latn (Dan), tik_Latn (Tikar) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028C</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0245</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to e</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to E</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0190</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), tik_Latn (Tikar), dow_Latn (Doyayo), bfd_Latn (Bafut), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), nyb_Latn (Nyangbo), gov_Latn (Goo), yav_Latn (Yangben), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), grb_Latn (Grebo), blo_Latn (Anii), tik_Latn (Tikar), dow_Latn (Doyayo), bfd_Latn (Bafut), agq_Latn (Aghem), wwa_Latn (Waama), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), sbd_Latn (Southern Samo), bqp_Latn (Bisã), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), nyb_Latn (Nyangbo), yav_Latn (Yangben), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni025B</td>
<td align="left">dnj_Latn (Dan), nmg_Latn (Kwasio), dow_Latn (Doyayo), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0190</td>
<td align="left">dnj_Latn (Dan), nmg_Latn (Kwasio), dow_Latn (Doyayo), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mdt_Latn (Mbere), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), etx_Latn (Iten), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), nnw_Latn (Southern Nuni), loq_Latn (Lobala), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mdt_Latn (Mbere), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni025B</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to uni0190</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni025B</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), kpe_Latn (Kpelle), lnl_Latn (South Central Banda), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), gov_Latn (Goo), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0190</td>
<td align="left">dnj_Latn (Dan), nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), kkj_Latn (Kako), kpe_Latn (Kpelle), lnl_Latn (South Central Banda), goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), ksp_Latn (Kabba), bom_Latn (Berom), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), lol_Latn (Mongo), kss_Latn (Southern Kisi), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to i</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to I</td>
<td align="left">dnj_Latn (Dan) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030F to uni0264</td>
<td align="left">dnj_Latn (Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0190</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), fvr_Latn (Fur), agq_Latn (Aghem), nzk_Latn (Nzakara), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), nfu_Latn (Mfumte), lnl_Latn (South Central Banda), etu_Latn (Ejagham), fvr_Latn (Fur), agq_Latn (Aghem), nzk_Latn (Nzakara), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni025B</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), goa_Latn (Guro), grb_Latn (Grebo), gna_Latn (Kaansa), tik_Latn (Tikar), nmg_Latn (Kwasio), bfd_Latn (Bafut), agq_Latn (Aghem), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), bom_Latn (Berom), tcd_Latn (Tafi), sbd_Latn (Southern Samo), lol_Latn (Mongo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn), lee_Latn (Lyélé), bbj_Latn (Ghomala), kib_Latn (Koalib), byv_Latn (Medumba), gej_Latn (Gen), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), ybb_Latn (Yemba), bbj_Latn (Ghomala), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), mas_Latn (Masai) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), fvr_Latn (Fur), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), ybb_Latn (Yemba), bbj_Latn (Ghomala), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa), mas_Latn (Masai) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0244</td>
<td align="left">nnh_Latn (Ngiemboon), dur_Latn (Dii), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), bax_Latn (Bamun (Latin)) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0186</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), ybb_Latn (Yemba), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), mwm_Latn (Sar), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mge_Latn (Mango), mdt_Latn (Mbere), kzr_Latn (Karang), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0289</td>
<td align="left">nnh_Latn (Ngiemboon), fmp_Latn (Fe’fe’), nfu_Latn (Mfumte), fvr_Latn (Fur), agq_Latn (Aghem), bbj_Latn (Ghomala), byv_Latn (Medumba), jgo_Latn (Ngomba), bax_Latn (Bamun (Latin)), ozm_Latn (Koonzime), mcp_Latn (Makaa) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0254</td>
<td align="left">nnh_Latn (Ngiemboon), nga_Latn (Ngbaka), ln_Latn (Lingala), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kkj_Latn (Kako), dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), yo_Latn_BJ (Yoruba, Benin), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), myk_Latn (Mamara Senoufo), goa_Latn (Guro), box_Latn (Buamu), gna_Latn (Kaansa), blo_Latn (Anii), nmg_Latn (Kwasio), dow_Latn (Doyayo), bfd_Latn (Bafut), bud_Latn (Ntcham), ybb_Latn (Yemba), tvu_Latn (Tunen), ksf_Latn (Bafia), ewo_Latn (Ewondo), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), bom_Latn (Berom), kyq_Latn (Kenga), ee_Latn (Ewe), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), mwm_Latn (Sar), pnz_Latn (Pana, Central African Republic), neb_Latn (Toura), ddn_Latn (Dendi), lol_Latn (Mongo), kss_Latn (Southern Kisi), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), bbj_Latn (Ghomala), tbz_Latn (Ditammari), kib_Latn (Koalib), ntm_Latn (Nateni), wok_Latn (Longto), gej_Latn (Gen), jgo_Latn (Ngomba), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), sld_Latn (Sissala), gvl_Latn (Gulay), ozm_Latn (Koonzime), nyb_Latn (Nyangbo), yav_Latn (Yangben), dua_Latn (Duala), soy_Latn (Miyobe), mge_Latn (Mango), mdt_Latn (Mbere), kzr_Latn (Karang), emk_Latn (Maninkakan, Eastern), bqc_Latn (Boko), pug_Latn (Phuie), lu_Latn (Luba-Katanga), aks_Latn (Akeselem), bas_Latn (Basaa) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to J</td>
<td align="left">ttq_Latn (Tawallammat Tamajaq), taq_Latn (Tamasheq (Latin)) and tmh_Latn (Tamashek)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0186</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), dgi_Latn (Northern Dagara), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0254</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), sbd_Latn (Southern Samo), bqp_Latn (Bisã), dgi_Latn (Northern Dagara), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Utilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), soy_Latn (Miyobe), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni025B</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0190</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), kpe_Latn (Kpelle), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gur_Latn (Frafra), gna_Latn (Kaansa), kst_Latn (Winyé), wwa_Latn (Waama), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), lob_Latn (Lobi), ee_Latn (Ewe), tcd_Latn (Tafi), vai_Latn (Vai (Latin)), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), dgi_Latn (Northern Dagara), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqv_Latn (Koro Wachi), bba_Latn (Baatonum), sld_Latn (Sissala), ebo_Latn (Teke-Ebo), biv_Latn (Birifor, Southern), nyb_Latn (Nyangbo), soy_Latn (Miyobe), dya_Latn (Dyan), bqc_Latn (Boko), pug_Latn (Phuie), bfo_Latn (Malba Birifor) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), gna_Latn (Kaansa), kst_Latn (Winyé), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), tcd_Latn (Tafi), lee_Latn (Lyélé), tbz_Latn (Ditammari), sld_Latn (Sissala), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Itilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Atilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to utilde</td>
<td align="left">nga_Latn (Ngbaka), tuz_Latn (Turka), lom_Latn (Loma, Liberia), dnj_Latn_LR (Liberian Dan), box_Latn (Buamu), bsq_Latn (Bassa (Latin)), mev_Latn (Mano), ife_Latn (Ifè), bqp_Latn (Bisã), bwj_Latn (Láá Láá Bwamu), lee_Latn (Lyélé), tbz_Latn (Ditammari), bqc_Latn (Boko), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to a</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to A</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to e</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to E</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni025B</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0190</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to i</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to I</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to o</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to O</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0254</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0186</td>
<td align="left">nga_Latn (Ngbaka), dow_Latn (Doyayo), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to u</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to U</td>
<td align="left">nga_Latn (Ngbaka), kss_Latn (Southern Kisi), krw_Latn (Western Krahn) and yba_Latn (Yala)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to atilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Atilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to tildecomb</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to itilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Itilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to utilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Utilde</td>
<td align="left">nga_Latn (Ngbaka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), dnj_Latn_LR (Liberian Dan), gna_Latn (Kaansa), tcd_Latn (Tafi) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to itilde</td>
<td align="left">nga_Latn (Ngbaka) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Itilde</td>
<td align="left">nga_Latn (Ngbaka) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to utilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Utilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Atilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to tildecomb</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to itilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Itilde</td>
<td align="left">nga_Latn (Ngbaka), gna_Latn (Kaansa), bsq_Latn (Bassa (Latin)), tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to utilde</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Utilde</td>
<td align="left">nga_Latn (Ngbaka), bsq_Latn (Bassa (Latin)) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to e</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to E</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to o</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to O</td>
<td align="left">etx_Latn (Iten), nus_Latn (Nuer), uth_Latn (ut-Hun), kdj_Latn (Karamojong), saf_Latn (Safaliba) and ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), sba_Latn (Ngambay), blo_Latn (Anii), nmg_Latn (Kwasio) and ksf_Latn (Bafia)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and lob_Latn (Lobi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan), sba_Latn (Ngambay), blo_Latn (Anii), nmg_Latn (Kwasio) and ksf_Latn (Bafia)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to otilde</td>
<td align="left">tuz_Latn (Turka), lom_Latn (Loma, Liberia), lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and lob_Latn (Lobi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01DD</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0196</td>
<td align="left">tuz_Latn (Turka), goa_Latn (Guro), blo_Latn (Anii), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Otilde</td>
<td align="left">tuz_Latn (Turka), lom_Latn (Loma, Liberia), lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni018E</td>
<td align="left">tuz_Latn (Turka), dnj_Latn_LR (Liberian Dan) and blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0196</td>
<td align="left">tuz_Latn (Turka), goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), xsm_Latn_BF (Kasem, Burkina Faso), tcd_Latn (Tafi), neb_Latn (Toura), sld_Latn (Sissala), pug_Latn (Phuie) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EE4</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EB9</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECA</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EE5</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECA</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), avu_Latn (Avokaya), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EE4</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECB</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECD</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EB8</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1ECC</td>
<td align="left">igb_Latn (Ebira), abn_Latn (Abua), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EE5</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1ECB</td>
<td align="left">igb_Latn (Ebira), mhi_Latn (Ma’di), avu_Latn (Avokaya), ikw_Latn (Ikwere) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EB9</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EB8</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECB</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECA</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECD</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1ECC</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EE5</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EE4</td>
<td align="left">igb_Latn (Ebira) and ekp_Latn (Ekpeye)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to i</td>
<td align="left">kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0190</td>
<td align="left">kkj_Latn (Kako), dow_Latn (Doyayo), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to I</td>
<td align="left">kkj_Latn (Kako), dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni025B</td>
<td align="left">kkj_Latn (Kako), dow_Latn (Doyayo), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to a</td>
<td align="left">nus_Latn (Nuer), asg_Latn (Cishingini), fvr_Latn (Fur), kdj_Latn (Karamojong), kaj_Latn (Jju) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0190</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), lnl_Latn (South Central Banda), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0254</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni025B</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0331</td>
<td align="left">nus_Latn (Nuer)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to A</td>
<td align="left">nus_Latn (Nuer), asg_Latn (Cishingini), fvr_Latn (Fur), kdj_Latn (Karamojong), kaj_Latn (Jju) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni025B</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), lnl_Latn (South Central Banda), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0190</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to i</td>
<td align="left">nus_Latn (Nuer), kdj_Latn (Karamojong), kcg_Latn (Tyap) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0254</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0186</td>
<td align="left">nus_Latn (Nuer) and kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0186</td>
<td align="left">nus_Latn (Nuer), dip_Latn (Dinka, Northeastern), grb_Latn (Grebo), sbd_Latn (Southern Samo) and din_Latn (Dinka)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to I</td>
<td align="left">nus_Latn (Nuer), kdj_Latn (Karamojong), kcg_Latn (Tyap) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to h</td>
<td align="left">bsc_Latn (Bassari)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to H</td>
<td align="left">bsc_Latn (Bassari)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to w</td>
<td align="left">bsc_Latn (Bassari) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to W</td>
<td align="left">bsc_Latn (Bassari) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni018F</td>
<td align="left">dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), etu_Latn (Ejagham), sba_Latn (Ngambay), bfd_Latn (Bafut), ybb_Latn (Yemba), ewo_Latn (Ewondo), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), mwm_Latn (Sar), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), mcp_Latn (Makaa), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Oacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Igrave</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni0259</td>
<td align="left">dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Uacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0228</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0229</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0197</td>
<td align="left">dur_Latn (Dii), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), bfd_Latn (Bafut), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), mge_Latn (Mango) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Iacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0259</td>
<td align="left">dur_Latn (Dii), fmp_Latn (Fe’fe’), nnw_Latn (Southern Nuni), nfu_Latn (Mfumte), etu_Latn (Ejagham), sba_Latn (Ngambay), bfd_Latn (Bafut), ybb_Latn (Yemba), ewo_Latn (Ewondo), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), sbd_Latn (Southern Samo), mwm_Latn (Sar), lee_Latn (Lyélé), bbj_Latn (Ghomala), wok_Latn (Longto), bum_Latn (Bulu), bax_Latn (Bamun (Latin)), gvl_Latn (Gulay), mcp_Latn (Makaa), mge_Latn (Mango) and gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to aacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0268</td>
<td align="left">dur_Latn (Dii), nfu_Latn (Mfumte), etu_Latn (Ejagham), fvr_Latn (Fur), bfd_Latn (Bafut), gvl_Latn (Gulay), ozm_Latn (Koonzime), mcp_Latn (Makaa), mge_Latn (Mango) and lgg_Latn (Lugbara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uni018F</td>
<td align="left">dur_Latn (Dii) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to igrave</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo) and vut_Latn (Vute)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0327</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and mcp_Latn (Makaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to iacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to oacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic), mcp_Latn (Makaa) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Aacute</td>
<td align="left">dur_Latn (Dii), dow_Latn (Doyayo), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to uacute</td>
<td align="left">dur_Latn (Dii), vut_Latn (Vute), pnz_Latn (Pana, Central African Republic) and kzr_Latn (Karang)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018F</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), kyq_Latn (Kenga), mwm_Latn (Sar), wok_Latn (Longto), bax_Latn (Bamun (Latin)) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0254</td>
<td align="left">fmp_Latn (Fe’fe’), nmg_Latn (Kwasio), dow_Latn (Doyayo), ybb_Latn (Yemba), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), mwm_Latn (Sar), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0289</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), agq_Latn (Aghem) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0244</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), agq_Latn (Aghem) and bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0251</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0186</td>
<td align="left">fmp_Latn (Fe’fe’), nmg_Latn (Kwasio), dow_Latn (Doyayo), ybb_Latn (Yemba), agq_Latn (Aghem), kyq_Latn (Kenga), tcd_Latn (Tafi), mwm_Latn (Sar), ddn_Latn (Dendi), kss_Latn (Southern Kisi), wok_Latn (Longto), bax_Latn (Bamun (Latin)), yba_Latn (Yala) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’) and byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6D</td>
<td align="left">fmp_Latn (Fe’fe’)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0259</td>
<td align="left">fmp_Latn (Fe’fe’), ybb_Latn (Yemba), kyq_Latn (Kenga), mwm_Latn (Sar), wok_Latn (Longto), bax_Latn (Bamun (Latin)) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to n</td>
<td align="left">mne_Latn (Naba), kyq_Latn (Kenga), daa_Latn (Dangaléat), mls_Latn (Masalit) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to N</td>
<td align="left">mne_Latn (Naba), kyq_Latn (Kenga), daa_Latn (Dangaléat), mls_Latn (Masalit) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to U</td>
<td align="left">uth_Latn (ut-Hun), kdj_Latn (Karamojong), kaj_Latn (Jju) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to u</td>
<td align="left">uth_Latn (ut-Hun), kdj_Latn (Karamojong), kaj_Latn (Jju) and rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Oslash</td>
<td align="left">nfu_Latn (Mfumte) and ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oslash</td>
<td align="left">nfu_Latn (Mfumte) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Oslash</td>
<td align="left">nfu_Latn (Mfumte), ozm_Latn (Koonzime) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Oslash</td>
<td align="left">nfu_Latn (Mfumte) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oslash</td>
<td align="left">nfu_Latn (Mfumte), ozm_Latn (Koonzime) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oslash</td>
<td align="left">nfu_Latn (Mfumte) and ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni018E</td>
<td align="left">dnj_Latn_LR (Liberian Dan), blo_Latn (Anii) and nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01DD</td>
<td align="left">dnj_Latn_LR (Liberian Dan), blo_Latn (Anii) and nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0275</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uniA78D</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni019F</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0265</td>
<td align="left">dnj_Latn_LR (Liberian Dan)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to n</td>
<td align="left">mg_Latn (Malagasy), etu_Latn (Ejagham), ksp_Latn (Kabba), ikw_Latn (Ikwere) and gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to N</td>
<td align="left">mg_Latn (Malagasy), etu_Latn (Ejagham), ksp_Latn (Kabba) and ikw_Latn (Ikwere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to n</td>
<td align="left">mg_Latn (Malagasy) and nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to N</td>
<td align="left">mg_Latn (Malagasy) and nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to g</td>
<td align="left">tuq_Latn (Tedaga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach dotbelowcomb to G</td>
<td align="left">tuq_Latn (Tedaga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni018F</td>
<td align="left">lnl_Latn (South Central Banda), ybb_Latn (Yemba), ksp_Latn (Kabba) and sbd_Latn (Southern Samo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0268</td>
<td align="left">lnl_Latn (South Central Banda) and nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0197</td>
<td align="left">lnl_Latn (South Central Banda) and nzk_Latn (Nzakara)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0259</td>
<td align="left">lnl_Latn (South Central Banda), ybb_Latn (Yemba), ksp_Latn (Kabba) and sbd_Latn (Southern Samo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0244</td>
<td align="left">lnl_Latn (South Central Banda), nzk_Latn (Nzakara) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to uni0289</td>
<td align="left">lnl_Latn (South Central Banda), nzk_Latn (Nzakara) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028B</td>
<td align="left">goa_Latn (Guro), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B2</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), xsm_Latn_BF (Kasem, Burkina Faso), neb_Latn (Toura), sld_Latn (Sissala) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B2</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028B</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), xsm_Latn_BF (Kasem, Burkina Faso), neb_Latn (Toura), sld_Latn (Sissala) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B2</td>
<td align="left">goa_Latn (Guro), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B2</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0269</td>
<td align="left">goa_Latn (Guro), blo_Latn (Anii), neb_Latn (Toura) and pug_Latn (Phuie)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028B</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0196</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tcd_Latn (Tafi) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), blo_Latn (Anii), tcd_Latn (Tafi) and neb_Latn (Toura)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028B</td>
<td align="left">goa_Latn (Guro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni0196</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0269</td>
<td align="left">goa_Latn (Guro), gna_Latn (Kaansa), kst_Latn (Winyé), blo_Latn (Anii), xsm_Latn_BF (Kasem, Burkina Faso), tcd_Latn (Tafi), neb_Latn (Toura), sld_Latn (Sissala), pug_Latn (Phuie) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EE4</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECD</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EB8</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECA</td>
<td align="left">mhi_Latn (Ma’di), avu_Latn (Avokaya) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECC</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EB9</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EE5</td>
<td align="left">mhi_Latn (Ma’di) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1ECB</td>
<td align="left">mhi_Latn (Ma’di), avu_Latn (Avokaya) and kbo_Latn (Keliko)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to o</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and kia_Latn (Kim)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E1A</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to A</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto), kia_Latn (Kim) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E1B</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E1A</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to aacute</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E1B</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0259</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018F</td>
<td align="left">sba_Latn (Ngambay) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to a</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto), kia_Latn (Kim) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to O</td>
<td align="left">sba_Latn (Ngambay), mwm_Latn (Sar) and kia_Latn (Kim)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Aacute</td>
<td align="left">sba_Latn (Ngambay), mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01DD</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni018E</td>
<td align="left">sba_Latn (Ngambay)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028B</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), sld_Latn (Sissala), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0269</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), tcd_Latn (Tafi), sld_Latn (Sissala), biv_Latn (Birifor, Southern), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B2</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), sld_Latn (Sissala), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0196</td>
<td align="left">gna_Latn (Kaansa), kst_Latn (Winyé), lob_Latn (Lobi), tcd_Latn (Tafi), sld_Latn (Sissala), biv_Latn (Birifor, Southern), pug_Latn (Phuie) and bfo_Latn (Malba Birifor)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni01CE</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Aacute</td>
<td align="left">fvr_Latn (Fur) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to aacute</td>
<td align="left">fvr_Latn (Fur) and kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to acircumflex</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Acircumflex</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni01CD</td>
<td align="left">fvr_Latn (Fur)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EBC</td>
<td align="left">kst_Latn (Winyé), lee_Latn (Lyélé), sld_Latn (Sissala), soy_Latn (Miyobe), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EBD</td>
<td align="left">kst_Latn (Winyé), lee_Latn (Lyélé), sld_Latn (Sissala), soy_Latn (Miyobe), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni01B1</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni01B1</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni028A</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni028A</td>
<td align="left">blo_Latn (Anii)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni028A</td>
<td align="left">blo_Latn (Anii), tcd_Latn (Tafi) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni01B1</td>
<td align="left">blo_Latn (Anii), tcd_Latn (Tafi) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to AE</td>
<td align="left">tik_Latn (Tikar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to eng</td>
<td align="left">tik_Latn (Tikar), mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Eng</td>
<td align="left">tik_Latn (Tikar), mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to ae</td>
<td align="left">tik_Latn (Tikar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01DD</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01DD</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni018E</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni018E</td>
<td align="left">nmg_Latn (Kwasio)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to V</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to v</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to v</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to V</td>
<td align="left">swb_Latn (Maore Comorian, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to umacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to amacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Umacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Amacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Imacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0327</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to uni0327</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to imacron</td>
<td align="left">dow_Latn (Doyayo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to R</td>
<td align="left">dno_Latn (Ndrulo), kyq_Latn (Kenga) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to r</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to R</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to s</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to r</td>
<td align="left">dno_Latn (Ndrulo), kyq_Latn (Kenga) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to S</td>
<td align="left">dno_Latn (Ndrulo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to b</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to B</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to l</td>
<td align="left">bud_Latn (Ntcham) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to B</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to L</td>
<td align="left">bud_Latn (Ntcham) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to b</td>
<td align="left">bud_Latn (Ntcham)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Idieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to edieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Edieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to udieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to idieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Udieresis</td>
<td align="left">bot_Latn (Bongo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0268</td>
<td align="left">agq_Latn (Aghem) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0197</td>
<td align="left">agq_Latn (Aghem) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B7</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7B6</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni026A</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uniA7AE</td>
<td align="left">kzc_Latn (Bondoukou Kulango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EA1</td>
<td align="left">abn_Latn (Abua) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1EA0</td>
<td align="left">abn_Latn (Abua) and avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EA1</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EA0</td>
<td align="left">abn_Latn (Abua)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Idieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to udieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to idieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Udieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to edieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to odieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Adieresis</td>
<td align="left">bvi_Latn (Belanda Viri, Latin)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to Icircumflex</td>
<td align="left">vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0327 to icircumflex</td>
<td align="left">vut_Latn (Vute) and pnz_Latn (Pana, Central African Republic)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to Eng</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to eng</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to G</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0308 to g</td>
<td align="left">nmz_Latn (Nawdm)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0289</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0268</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0197</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni0244</td>
<td align="left">kdj_Latn (Karamojong)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EA1</td>
<td align="left">avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni1EA0</td>
<td align="left">avu_Latn (Avokaya)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to agrave</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Agrave</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to amacron</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Amacron</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni025B</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0190</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0330</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0330</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0330</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), wok_Latn (Longto), jgo_Latn (Ngomba), gov_Latn (Goo) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), eto_Latn (Eton, Cameroon), tcd_Latn (Tafi), wok_Latn (Longto), jgo_Latn (Ngomba) and aks_Latn (Akeselem)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), kss_Latn (Southern Kisi), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Eng</td>
<td align="left">mev_Latn (Mano), kyq_Latn (Kenga), kss_Latn (Southern Kisi), wok_Latn (Longto) and jgo_Latn (Ngomba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0254</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni0186</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E75</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E74</td>
<td align="left">mev_Latn (Mano), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E75</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E74</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar), ntm_Latn (Nateni) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E75</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E74</td>
<td align="left">mev_Latn (Mano), mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to C</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni035F to T</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to c</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to p</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to P</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni035F to t</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to H</td>
<td align="left">udu_Latn (Uduk)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to nacute</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Nacute</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01F9</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to uni01F8</td>
<td align="left">kyq_Latn (Kenga)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to m</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), tcd_Latn (Tafi), mwm_Latn (Sar), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to M</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), tcd_Latn (Tafi), mwm_Latn (Sar), kss_Latn (Southern Kisi), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to n</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), ann_Latn (Obolo), mwm_Latn (Sar), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to N</td>
<td align="left">kyq_Latn (Kenga), ikw_Latn (Ikwere), ann_Latn (Obolo), mwm_Latn (Sar), wok_Latn (Longto), jgo_Latn (Ngomba) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to r</td>
<td align="left">kyq_Latn (Kenga), mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to R</td>
<td align="left">kyq_Latn (Kenga), mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to m</td>
<td align="left">ikw_Latn (Ikwere) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to M</td>
<td align="left">ikw_Latn (Ikwere) and tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0272</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni019D</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0272</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni019D</td>
<td align="left">eto_Latn (Eton, Cameroon)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to a</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to A</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to atilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Atilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to e</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to E</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EBD</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1EBC</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0269</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni0196</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0269</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0196</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to tildecomb</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to o</td>
<td align="left">tcd_Latn (Tafi), kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to O</td>
<td align="left">tcd_Latn (Tafi), kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to o</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to O</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to otilde</td>
<td align="left">tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to Otilde</td>
<td align="left">tcd_Latn (Tafi) and lee_Latn (Lyélé)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0254</td>
<td align="left">tcd_Latn (Tafi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0186</td>
<td align="left">tcd_Latn (Tafi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to tildecomb</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to u</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to U</td>
<td align="left">tcd_Latn (Tafi), btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to Utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to Utilde</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni028A</td>
<td align="left">tcd_Latn (Tafi) and biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni01B1</td>
<td align="left">tcd_Latn (Tafi) and biv_Latn (Birifor, Southern)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni028A</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni01B1</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni028A</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni01B1</td>
<td align="left">tcd_Latn (Tafi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E2D</td>
<td align="left">mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to w</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E2C</td>
<td align="left">mwm_Latn (Sar), ntm_Latn (Nateni) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E1A</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to omacron</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni1E2D</td>
<td align="left">mwm_Latn (Sar), ntm_Latn (Nateni) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to oacute</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Omacron</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E2C</td>
<td align="left">mwm_Latn (Sar) and wok_Latn (Longto)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to W</td>
<td align="left">mwm_Latn (Sar)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to uni1E1B</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Oacute</td>
<td align="left">mwm_Latn (Sar) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to otilde</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni1EBC</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Otilde</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to uni1EBD</td>
<td align="left">ema_Latn (Emai-Iuleha-Ora)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to a</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to A</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to a</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to A</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to e</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to E</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to e</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to E</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni025B</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0190</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni025B</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0190</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to i</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to I</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to i</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to I</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to eng</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030D to Eng</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to o</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to O</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0254</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to uni0186</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0254</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to uni0186</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to u</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC4 to U</td>
<td align="left">kss_Latn (Southern Kisi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to u</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC5 to U</td>
<td align="left">kss_Latn (Southern Kisi) and btt_Latn (Bete-Bendi)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EBC</td>
<td align="left">lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EBC</td>
<td align="left">lee_Latn (Lyélé) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1EBD</td>
<td align="left">lee_Latn (Lyélé), pug_Latn (Phuie) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to uni1EBD</td>
<td align="left">lee_Latn (Lyélé) and awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to Iacute</td>
<td align="left">kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0331 to iacute</td>
<td align="left">kcg_Latn (Tyap)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0250</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6F</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E2C</td>
<td align="left">ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to uni1E2D</td>
<td align="left">ntm_Latn (Nateni), wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to L</td>
<td align="left">wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0304 to l</td>
<td align="left">wok_Latn (Longto) and mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni2C6D</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni0251</td>
<td align="left">byv_Latn (Medumba)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Udieresis</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to udieresis</td>
<td align="left">bax_Latn (Bamun (Latin))</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0289</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0197</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0268</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to uni0244</td>
<td align="left">ebo_Latn (Teke-Ebo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0324 to W</td>
<td align="left">fan_Latn (Fang) and mdt_Latn (Mbere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0324 to w</td>
<td align="left">fan_Latn (Fang) and mdt_Latn (Mbere)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to OE</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to OE</td>
<td align="left">ozm_Latn (Koonzime) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to oe</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030C to OE</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to oe</td>
<td align="left">ozm_Latn (Koonzime) and bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to oe</td>
<td align="left">ozm_Latn (Koonzime)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ꟈ, ꟈ</td>
<td align="left">mor_Latn (Moro)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0325 to l</td>
<td align="left">csk_Latn (Jola-Kasa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0325 to L</td>
<td align="left">csk_Latn (Jola-Kasa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to b</td>
<td align="left">rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to B</td>
<td align="left">rub_Latn (Gungu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to Adieresis</td>
<td align="left">mgd_Latn (Moru)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to adieresis</td>
<td align="left">mgd_Latn (Moru)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to T</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to t</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to d</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni032F to D</td>
<td align="left">pkb_Latn (Pokomo)</td>
</tr>
<tr>
<td align="left">Some base glyphs were missing: Ɤ, Ɤ̀, Ɤ́, Ɤ̂</td>
<td align="left">gov_Latn (Goo)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to ograve</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0330 to Ograve</td>
<td align="left">mge_Latn (Mango)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to oe</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach gravecomb to OE</td>
<td align="left">bkm_Latn (Kom)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to i</td>
<td align="left">btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to I</td>
<td align="left">btt_Latn (Bete-Bendi) and bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach tildecomb to Oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EBD</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to uni1EBC</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to otilde</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0302 to Otilde</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni030B to Oslash</td>
<td align="left">awc_Latn (Cicipu)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to O</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to i</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni025B</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to A</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0186</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to I</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to e</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to o</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0254</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to u</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to U</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni025B</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC6 to uni0190</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to a</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to uni0190</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni1DC7 to E</td>
<td align="left">bas_Latn (Basaa)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to aogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Aogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0259</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni018F</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uni0328</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni025B</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0190</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to iogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Iogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0254</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach uni0328 to uni0186</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to uogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
<tr>
<td align="left">Shaper didn't attach acutecomb to Uogonek</td>
<td align="left">gkp_Latn (Kpelle, Guinea)</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



* ⚠️ **WARN** <p>GF_Greek_Expert glyphset:</p>
<table>
<thead>
<tr>
<th align="left">WARN messages</th>
<th align="left">Languages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">No variant glyphs were found for uni0181</td>
<td align="left">dnj_Latn (Dan) and lom_Latn (Loma, Liberia)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Amo</td>
<td align="left">amo_Latn (Amo)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Koro</td>
<td align="left">kfo_Latn (Koro)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni028B</td>
<td align="left">tod_Latn (Toma)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01B2</td>
<td align="left">tod_Latn (Toma)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Seki</td>
<td align="left">syi_Latn (Seki)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Mina</td>
<td align="left">hna_Latn (Mina)</td>
</tr>
<tr>
<td align="left">Some auxiliary glyphs were missing: Ⓐ, ⓐ</td>
<td align="left">kib_Latn (Koalib)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Mbunga</td>
<td align="left">mgy_Latn (Mbunga)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Eastern Gurung, Latin</td>
<td align="left">ggn_Latn (Eastern Gurung, Latin)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01A9</td>
<td align="left">gaa_Latn (Ga)</td>
</tr>
<tr>
<td align="left">No variant glyphs were found for uni01B7</td>
<td align="left">gaa_Latn (Ga)</td>
</tr>
<tr>
<td align="left">No exemplar glyphs were defined for language Atsam</td>
<td align="left">cch_Latn (Atsam)</td>
</tr>
</tbody>
</table>
 [code: warning-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-font-copyright">googlefonts/font_copyright</a></summary>
    <div>







* 🔥 **FAIL** <p>Name Table entry: Copyright notices should match a pattern similar to:</p>
<p>&quot;Copyright 2020 The Familyname Project Authors (git url)&quot;</p>
<p>But instead we have got:</p>
<p>&quot;Copyright 2010 Google Inc. All Rights Reserved.&quot;</p>
 [code: bad-notice-format]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check if the vertical metrics of a family are similar to the same family hosted on Google Fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-vertical-metrics-regressions">googlefonts/vertical_metrics_regressions</a></summary>
    <div>







* 🔥 **FAIL** <p>Tinos Regular: OS/2 sTypoAscender is 1420 when it should be 1825</p>
 [code: bad-typo-ascender]



* 🔥 **FAIL** <p>Tinos Regular: OS/2 sTypoDescender is -442 when it should be -443</p>
 [code: bad-typo-descender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check mark characters are in GDEF mark glyph class. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.html#opentype-gdef-mark-chars">opentype/gdef_mark_chars</a></summary>
    <div>







* ⚠️ **WARN** <p>The following mark characters could be in the GDEF mark glyph class:
uni0488 (U+0488), uni0489 (U+0489), uni1ABE (U+1ABE), uniA670 (U+A670), uniA671 (U+A671), uniA672 (U+A672), uniFE20 (U+FE20), uniFE21 (U+FE21), uniFE27 (U+FE27) and uniFE28 (U+FE28)</p>
 [code: mark-chars]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#contour-count">contour_count</a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: hyphen	Contours detected: 1	Expected: 0

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: uni01E5	Contours detected: 4	Expected: 2

- Glyph name: uni01F5	Contours detected: 4	Expected: 3

- Glyph name: uni023A	Contours detected: 4	Expected: 3

- Glyph name: uni023E	Contours detected: 3	Expected: 2

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uni204B	Contours detected: 1	Expected: 2

- Glyph name: uni205F	Contours detected: 15	Expected: 0

- Glyph name: uni20A6	Contours detected: 4	Expected: 1, 3 or 5

- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

- Glyph name: uni210A	Contours detected: 3	Expected: 2

- Glyph name: uni210D	Contours detected: 3	Expected: 2

- Glyph name: uni2119	Contours detected: 4	Expected: 2

- Glyph name: uni211A	Contours detected: 5	Expected: 3

- Glyph name: uni211D	Contours detected: 5	Expected: 3

- Glyph name: uni2E18	Contours detected: 3	Expected: 2

- Glyph name: uniFEFF	Contours detected: 19	Expected: 0

- Glyph name: uniFFFC	Contours detected: 16	Expected: 22

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: eogonek	Contours detected: 3	Expected: 2

- Glyph name: uni01E5	Contours detected: 4	Expected: 2

- Glyph name: uni023A	Contours detected: 4	Expected: 3

- Glyph name: uni023E	Contours detected: 3	Expected: 2

- Glyph name: uni1E08	Contours detected: 3	Expected: 2

- Glyph name: uni1E09	Contours detected: 3	Expected: 2

- Glyph name: uni203D	Contours detected: 3	Expected: 2

- Glyph name: uni204B	Contours detected: 1	Expected: 2

- Glyph name: uni205F	Contours detected: 15	Expected: 0

- Glyph name: uni20A6	Contours detected: 4	Expected: 1, 3 or 5

- Glyph name: uni20A9	Contours detected: 6	Expected: 1, 3, 4 or 7

- Glyph name: uni210A	Contours detected: 3	Expected: 2

- Glyph name: uni210D	Contours detected: 3	Expected: 2

- Glyph name: uni2119	Contours detected: 4	Expected: 2

- Glyph name: uni211A	Contours detected: 5	Expected: 3

- Glyph name: uni211D	Contours detected: 5	Expected: 3

- Glyph name: uni2E18	Contours detected: 3	Expected: 2

- Glyph name: uniFEFF	Contours detected: 19	Expected: 0

- Glyph name: uniFFFC	Contours detected: 16	Expected: 22

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#math-signs-width">math_signs_width</a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 1167 among a set of 8 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 1124:
plusminus, divide, lessequal, approxequal, notequal, greaterequal</p>
<p>Width = 2005:
orthogonal</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Does the font contain a soft hyphen? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-hyphen">soft_hyphen</a></summary>
    <div>







* ⚠️ **WARN** <p>This font has a 'Soft Hyphen' character.</p>
 [code: softhyphen]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#typoascender-exceeds-Agrave">typoascender_exceeds_Agrave</a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2.sTypoAscender value should be greater than 1757, but got 1387 instead</p>
 [code: typoAscender]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#unreachable-glyphs">unreachable_glyphs</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Eng.alt1

- Eng.alt2

- Eng.alt3

- Lcommaaccent.loclMAH

- Ncommaaccent.loclMAH

- Ohm

- UNI2206

- acute.alt1

- acute.alt2

- acute.alt3

- acute.alt4

- acute.alt5

- alefdagesh

- aleflamedhatafsegol

- aleflamedsegol

- aleflamedtsere

- alternativelamed

- bari.dotless

- breve.alt1

- circumflex.alt1

- dotbelow.alt1

- dotbelow.alt10

- dotbelow.alt11

- dotbelow.alt12

- dotbelow.alt13

- dotbelow.alt14

- dotbelow.alt15

- dotbelow.alt2

- dotbelow.alt3

- dotbelow.alt4

- dotbelow.alt5

- dotbelow.alt6

- dotbelow.alt7

- dotbelow.alt8

- dotbelow.alt9

- dotlessi.alt1

- dottediacute

- eight.alt

- finalkafqamats

- finalkafsheva

- five.alt

- four.alt

- glyph3284

- grave.alt1

- grave.alt2

- grave.alt3

- grave.alt4

- grave.alt5

- hookabove.alt1

- hookabove.alt2

- hookabove.alt3

- hookabove.alt4

- hookabove.alt5

- lamedholam

- lamedholamdagesh

- lcommaaccent.loclMAH

- ncommaaccent.loclMAH

- nine.alt

- one.alt

- pi1

- radicalex.x

- seven.alt

- six.alt

- three.alt

- tilde.alt1

- tilde.alt10

- tilde.alt11

- tilde.alt12

- tilde.alt13

- tilde.alt2

- tilde.alt3

- tilde.alt4

- tilde.alt5

- tilde.alt6

- tilde.alt7

- tilde.alt8

- tilde.alt9

- two.alt

- uni00AD

- uni02E502E502E6

- uni02E502E502E7

- uni02E502E502E8

- uni02E502E502E9

- uni02E502E6

- uni02E502E602E5

- uni02E502E602E6

- uni02E502E602E7

- uni02E502E602E8

- uni02E502E602E9

- uni02E502E7

- uni02E502E702E5

- uni02E502E702E6

- uni02E502E702E7

- uni02E502E702E8

- uni02E502E702E9

- uni02E502E8

- uni02E502E802E5

- uni02E502E802E6

- uni02E502E802E7

- uni02E502E802E8

- uni02E502E802E9

- uni02E502E9

- uni02E502E902E5

- uni02E502E902E6

- uni02E502E902E7

- uni02E502E902E8

- uni02E502E902E9

- uni02E602E5

- uni02E602E502E5

- uni02E602E502E6

- uni02E602E502E7

- uni02E602E502E8

- uni02E602E502E9

- uni02E602E602E5

- uni02E602E602E7

- uni02E602E602E8

- uni02E602E602E9

- uni02E602E7

- uni02E602E702E5

- uni02E602E702E6

- uni02E602E702E7

- uni02E602E702E8

- uni02E602E702E9

- uni02E602E8

- uni02E602E802E5

- uni02E602E802E6

- uni02E602E802E7

- uni02E602E802E8

- uni02E602E802E9

- uni02E602E9

- uni02E602E902E5

- uni02E602E902E6

- uni02E602E902E7

- uni02E602E902E8

- uni02E602E902E9

- uni02E702E5

- uni02E702E502E5

- uni02E702E502E6

- uni02E702E502E7

- uni02E702E502E8

- uni02E702E502E9

- uni02E702E6

- uni02E702E602E5

- uni02E702E602E6

- uni02E702E602E7

- uni02E702E602E8

- uni02E702E602E9

- uni02E702E702E5

- uni02E702E702E6

- uni02E702E702E8

- uni02E702E702E9

- uni02E702E8

- uni02E702E802E5

- uni02E702E802E6

- uni02E702E802E7

- uni02E702E802E8

- uni02E702E802E9

- uni02E702E9

- uni02E702E902E5

- uni02E702E902E6

- uni02E702E902E7

- uni02E702E902E8

- uni02E702E902E9

- uni02E802E5

- uni02E802E502E5

- uni02E802E502E6

- uni02E802E502E7

- uni02E802E502E8

- uni02E802E502E9

- uni02E802E6

- uni02E802E602E5

- uni02E802E602E6

- uni02E802E602E7

- uni02E802E602E8

- uni02E802E602E9

- uni02E802E7

- uni02E802E702E5

- uni02E802E702E6

- uni02E802E702E7

- uni02E802E702E8

- uni02E802E702E9

- uni02E802E802E5

- uni02E802E802E6

- uni02E802E802E7

- uni02E802E802E9

- uni02E802E9

- uni02E802E902E5

- uni02E802E902E6

- uni02E802E902E7

- uni02E802E902E8

- uni02E802E902E9

- uni02E902E5

- uni02E902E502E5

- uni02E902E502E6

- uni02E902E502E7

- uni02E902E502E8

- uni02E902E502E9

- uni02E902E6

- uni02E902E602E5

- uni02E902E602E6

- uni02E902E602E7

- uni02E902E602E8

- uni02E902E602E9

- uni02E902E7

- uni02E902E702E5

- uni02E902E702E6

- uni02E902E702E7

- uni02E902E702E8

- uni02E902E702E9

- uni02E902E8

- uni02E902E802E5

- uni02E902E802E6

- uni02E902E802E7

- uni02E902E802E8

- uni02E902E802E9

- uni02E902E902E5

- uni02E902E902E6

- uni02E902E902E7

- uni02E902E902E8

- uni03B1030403130300

- uni03B1030403130301

- uni03B1030403140300

- uni03B1030403140301

- uni03B1030603130300

- uni03B1030603130301

- uni03B1030603140300

- uni03B1030603140301

- uni03B9030403130300

- uni03B9030403130301

- uni03B9030403140300

- uni03B9030403140301

- uni03B9030603130300

- uni03B9030603130301

- uni03B9030603140300

- uni03B9030603140301

- uni03B9030803040300

- uni03B9030803040301

- uni03B9030803060300

- uni03B9030803060301

- uni03C5030403130300

- uni03C5030403130301

- uni03C5030403140300

- uni03C5030403140301

- uni03C5030603130300

- uni03C5030603130301

- uni03C5030603140300

- uni03C5030603140301

- uni03C5030803040300

- uni03C5030803040301

- uni03C5030803060300

- uni03C5030803060301

- uni0431.loclSRB

- uni05B105BD

- uni05B205BD

- uni05B305BD

- zero.alt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-article-images">googlefonts/article/images</a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/Tinos/googlefonts/ttf does not have an article.</p>
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
<li>U+02CD MODIFIER LETTER LOW MACRON: try adding lisu</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, tifinagh, coptic</li>
<li>U+0305 COMBINING OVERLINE: try adding one of: elbasan, glagolitic, math, coptic, gothic</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: duployan, syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+030D COMBINING VERTICAL LINE ABOVE: try adding sunuwar</li>
<li>U+030E COMBINING DOUBLE VERTICAL LINE ABOVE: try adding ethiopic</li>
<li>U+030F COMBINING DOUBLE GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+0310 COMBINING CANDRABINDU: try adding one of: math, sunuwar</li>
<li>U+0311 COMBINING INVERTED BREVE: try adding one of: todhri, coptic</li>
<li>U+0312 COMBINING TURNED COMMA ABOVE: try adding math</li>
<li>U+0313 COMBINING COMMA ABOVE: try adding one of: old-permic, todhri</li>
<li>U+0314 COMBINING REVERSED COMMA ABOVE: not included in any glyphset definition</li>
<li>U+0315 COMBINING COMMA ABOVE RIGHT: try adding math</li>
<li>U+0316 COMBINING GRAVE ACCENT BELOW: not included in any glyphset definition</li>
<li>U+0317 COMBINING ACUTE ACCENT BELOW: not included in any glyphset definition</li>
<li>U+0318 COMBINING LEFT TACK BELOW: not included in any glyphset definition</li>
<li>U+0319 COMBINING RIGHT TACK BELOW: not included in any glyphset definition</li>
<li>U+031A COMBINING LEFT ANGLE ABOVE: try adding math</li>
<li>U+031B COMBINING HORN: not included in any glyphset definition</li>
<li>U+031C COMBINING LEFT HALF RING BELOW: not included in any glyphset definition</li>
<li>U+031D COMBINING UP TACK BELOW: not included in any glyphset definition</li>
<li>U+031E COMBINING DOWN TACK BELOW: not included in any glyphset definition</li>
<li>U+031F COMBINING PLUS SIGN BELOW: not included in any glyphset definition</li>
<li>U+0320 COMBINING MINUS SIGN BELOW: try adding syriac</li>
<li>U+0321 COMBINING PALATALIZED HOOK BELOW: not included in any glyphset definition</li>
<li>U+0322 COMBINING RETROFLEX HOOK BELOW: not included in any glyphset definition</li>
<li>U+0324 COMBINING DIAERESIS BELOW: try adding one of: cherokee, duployan, syriac</li>
<li>U+0325 COMBINING RING BELOW: try adding syriac</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+032A COMBINING BRIDGE BELOW: not included in any glyphset definition</li>
<li>U+032B COMBINING INVERTED DOUBLE ARCH BELOW: not included in any glyphset definition</li>
<li>U+032C COMBINING CARON BELOW: try adding math</li>
<li>U+032D COMBINING CIRCUMFLEX ACCENT BELOW: try adding one of: sunuwar, syriac</li>
<li>U+032E COMBINING BREVE BELOW: try adding syriac</li>
<li>U+032F COMBINING INVERTED BREVE BELOW: try adding math</li>
<li>U+0330 COMBINING TILDE BELOW: try adding one of: cherokee, math, syriac</li>
<li>U+0331 COMBINING MACRON BELOW: try adding one of: cherokee, thai, caucasian-albanian, gothic, sunuwar, tifinagh, syriac</li>
<li>U+0332 COMBINING LOW LINE: try adding math</li>
<li>U+0333 COMBINING DOUBLE LOW LINE: try adding math</li>
<li>U+0334 COMBINING TILDE OVERLAY: not included in any glyphset definition</li>
<li>U+0335 COMBINING SHORT STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0336 COMBINING LONG STROKE OVERLAY: not included in any glyphset definition</li>
<li>U+0337 COMBINING SHORT SOLIDUS OVERLAY: not included in any glyphset definition</li>
<li>U+0338 COMBINING LONG SOLIDUS OVERLAY: try adding math</li>
<li>U+0339 COMBINING RIGHT HALF RING BELOW: not included in any glyphset definition</li>
<li>U+033A COMBINING INVERTED BRIDGE BELOW: try adding math</li>
<li>U+033B COMBINING SQUARE BELOW: not included in any glyphset definition</li>
<li>U+033C COMBINING SEAGULL BELOW: not included in any glyphset definition</li>
<li>U+033D COMBINING X ABOVE: not included in any glyphset definition</li>
<li>U+033E COMBINING VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+033F COMBINING DOUBLE OVERLINE: try adding coptic</li>
<li>U+0340 COMBINING GRAVE TONE MARK: not included in any glyphset definition</li>
<li>U+0341 COMBINING ACUTE TONE MARK: not included in any glyphset definition</li>
<li>U+0342 COMBINING GREEK PERISPOMENI: not included in any glyphset definition</li>
<li>U+0343 COMBINING GREEK KORONIS: not included in any glyphset definition</li>
<li>U+0344 COMBINING GREEK DIALYTIKA TONOS: not included in any glyphset definition</li>
<li>U+0345 COMBINING GREEK YPOGEGRAMMENI: not included in any glyphset definition</li>
<li>U+0346 COMBINING BRIDGE ABOVE: try adding math</li>
<li>U+0347 COMBINING EQUALS SIGN BELOW: not included in any glyphset definition</li>
<li>U+0348 COMBINING DOUBLE VERTICAL LINE BELOW: not included in any glyphset definition</li>
<li>U+0349 COMBINING LEFT ANGLE BELOW: not included in any glyphset definition</li>
<li>U+034A COMBINING NOT TILDE ABOVE: not included in any glyphset definition</li>
<li>U+034B COMBINING HOMOTHETIC ABOVE: not included in any glyphset definition</li>
<li>U+034C COMBINING ALMOST EQUAL TO ABOVE: not included in any glyphset definition</li>
<li>U+034D COMBINING LEFT RIGHT ARROW BELOW: try adding math</li>
<li>U+034E COMBINING UPWARDS ARROW BELOW: not included in any glyphset definition</li>
<li>U+034F COMBINING GRAPHEME JOINER: not included in any glyphset definition</li>
<li>U+0350 COMBINING RIGHT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+0351 COMBINING LEFT HALF RING ABOVE: not included in any glyphset definition</li>
<li>U+0352 COMBINING FERMATA: not included in any glyphset definition</li>
<li>U+0353 COMBINING X BELOW: not included in any glyphset definition</li>
<li>U+0354 COMBINING LEFT ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0355 COMBINING RIGHT ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0356 COMBINING RIGHT ARROWHEAD AND UP ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+0357 COMBINING RIGHT HALF RING ABOVE: not included in any glyphset definition</li>
<li>U+0358 COMBINING DOT ABOVE RIGHT: try adding osage</li>
<li>U+0359 COMBINING ASTERISK BELOW: not included in any glyphset definition</li>
<li>U+035A COMBINING DOUBLE RING BELOW: not included in any glyphset definition</li>
<li>U+035B COMBINING ZIGZAG ABOVE: not included in any glyphset definition</li>
<li>U+035C COMBINING DOUBLE BREVE BELOW: not included in any glyphset definition</li>
<li>U+035D COMBINING DOUBLE BREVE: not included in any glyphset definition</li>
<li>U+035E COMBINING DOUBLE MACRON: try adding one of: todhri, coptic, caucasian-albanian</li>
<li>U+035F COMBINING DOUBLE MACRON BELOW: not included in any glyphset definition</li>
<li>U+0360 COMBINING DOUBLE TILDE: not included in any glyphset definition</li>
<li>U+0361 COMBINING DOUBLE INVERTED BREVE: try adding coptic</li>
<li>U+0362 COMBINING DOUBLE RIGHTWARDS ARROW BELOW: not included in any glyphset definition</li>
<li>U+0363 COMBINING LATIN SMALL LETTER A: not included in any glyphset definition</li>
<li>U+0364 COMBINING LATIN SMALL LETTER E: not included in any glyphset definition</li>
<li>U+0365 COMBINING LATIN SMALL LETTER I: not included in any glyphset definition</li>
<li>U+0366 COMBINING LATIN SMALL LETTER O: not included in any glyphset definition</li>
<li>U+0367 COMBINING LATIN SMALL LETTER U: not included in any glyphset definition</li>
<li>U+0368 COMBINING LATIN SMALL LETTER C: not included in any glyphset definition</li>
<li>U+0369 COMBINING LATIN SMALL LETTER D: not included in any glyphset definition</li>
<li>U+036A COMBINING LATIN SMALL LETTER H: not included in any glyphset definition</li>
<li>U+036B COMBINING LATIN SMALL LETTER M: not included in any glyphset definition</li>
<li>U+036C COMBINING LATIN SMALL LETTER R: not included in any glyphset definition</li>
<li>U+036D COMBINING LATIN SMALL LETTER T: not included in any glyphset definition</li>
<li>U+036E COMBINING LATIN SMALL LETTER V: not included in any glyphset definition</li>
<li>U+036F COMBINING LATIN SMALL LETTER X: not included in any glyphset definition</li>
<li>U+1AB0 COMBINING DOUBLED CIRCUMFLEX ACCENT: not included in any glyphset definition</li>
<li>U+1AB1 COMBINING DIAERESIS-RING: not included in any glyphset definition</li>
<li>U+1AB2 COMBINING INFINITY: not included in any glyphset definition</li>
<li>U+1AB3 COMBINING DOWNWARDS ARROW: not included in any glyphset definition</li>
<li>U+1AB4 COMBINING TRIPLE DOT: not included in any glyphset definition</li>
<li>U+1AB5 COMBINING X-X BELOW: not included in any glyphset definition</li>
<li>U+1AB6 COMBINING WIGGLY LINE BELOW: not included in any glyphset definition</li>
<li>U+1AB7 COMBINING OPEN MARK BELOW: not included in any glyphset definition</li>
<li>U+1AB8 COMBINING DOUBLE OPEN MARK BELOW: not included in any glyphset definition</li>
<li>U+1AB9 COMBINING LIGHT CENTRALIZATION STROKE BELOW: not included in any glyphset definition</li>
<li>U+1ABA COMBINING STRONG CENTRALIZATION STROKE BELOW: not included in any glyphset definition</li>
<li>U+1ABB COMBINING PARENTHESES ABOVE: not included in any glyphset definition</li>
<li>U+1ABC COMBINING DOUBLE PARENTHESES ABOVE: not included in any glyphset definition</li>
<li>U+1ABD COMBINING PARENTHESES BELOW: not included in any glyphset definition</li>
<li>U+1ABE COMBINING PARENTHESES OVERLAY: not included in any glyphset definition</li>
<li>U+1DC0 COMBINING DOTTED GRAVE ACCENT: not included in any glyphset definition</li>
<li>U+1DC1 COMBINING DOTTED ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+1DC2 COMBINING SNAKE BELOW: not included in any glyphset definition</li>
<li>U+1DC3 COMBINING SUSPENSION MARK: not included in any glyphset definition</li>
<li>U+1DC4 COMBINING MACRON-ACUTE: not included in any glyphset definition</li>
<li>U+1DC5 COMBINING GRAVE-MACRON: not included in any glyphset definition</li>
<li>U+1DC6 COMBINING MACRON-GRAVE: not included in any glyphset definition</li>
<li>U+1DC7 COMBINING ACUTE-MACRON: not included in any glyphset definition</li>
<li>U+1DC8 COMBINING GRAVE-ACUTE-GRAVE: not included in any glyphset definition</li>
<li>U+1DC9 COMBINING ACUTE-GRAVE-ACUTE: not included in any glyphset definition</li>
<li>U+1DCA COMBINING LATIN SMALL LETTER R BELOW: not included in any glyphset definition</li>
<li>U+1DCB COMBINING BREVE-MACRON: not included in any glyphset definition</li>
<li>U+1DCC COMBINING MACRON-BREVE: not included in any glyphset definition</li>
<li>U+1DCD COMBINING DOUBLE CIRCUMFLEX ABOVE: try adding coptic</li>
<li>U+1DCE COMBINING OGONEK ABOVE: not included in any glyphset definition</li>
<li>U+1DCF COMBINING ZIGZAG BELOW: not included in any glyphset definition</li>
<li>U+1DD0 COMBINING IS BELOW: not included in any glyphset definition</li>
<li>U+1DD1 COMBINING UR ABOVE: not included in any glyphset definition</li>
<li>U+1DD2 COMBINING US ABOVE: not included in any glyphset definition</li>
<li>U+1DD3 COMBINING LATIN SMALL LETTER FLATTENED OPEN A ABOVE: not included in any glyphset definition</li>
<li>U+1DD4 COMBINING LATIN SMALL LETTER AE: not included in any glyphset definition</li>
<li>U+1DD5 COMBINING LATIN SMALL LETTER AO: not included in any glyphset definition</li>
<li>U+1DD6 COMBINING LATIN SMALL LETTER AV: not included in any glyphset definition</li>
<li>U+1DD7 COMBINING LATIN SMALL LETTER C CEDILLA: not included in any glyphset definition</li>
<li>U+1DD8 COMBINING LATIN SMALL LETTER INSULAR D: not included in any glyphset definition</li>
<li>U+1DD9 COMBINING LATIN SMALL LETTER ETH: not included in any glyphset definition</li>
<li>U+1DDA COMBINING LATIN SMALL LETTER G: not included in any glyphset definition</li>
<li>U+1DDB COMBINING LATIN LETTER SMALL CAPITAL G: not included in any glyphset definition</li>
<li>U+1DDC COMBINING LATIN SMALL LETTER K: not included in any glyphset definition</li>
<li>U+1DDD COMBINING LATIN SMALL LETTER L: not included in any glyphset definition</li>
<li>U+1DDE COMBINING LATIN LETTER SMALL CAPITAL L: not included in any glyphset definition</li>
<li>U+1DDF COMBINING LATIN LETTER SMALL CAPITAL M: not included in any glyphset definition</li>
<li>U+1DE0 COMBINING LATIN SMALL LETTER N: not included in any glyphset definition</li>
<li>U+1DE1 COMBINING LATIN LETTER SMALL CAPITAL N: not included in any glyphset definition</li>
<li>U+1DE2 COMBINING LATIN LETTER SMALL CAPITAL R: not included in any glyphset definition</li>
<li>U+1DE3 COMBINING LATIN SMALL LETTER R ROTUNDA: not included in any glyphset definition</li>
<li>U+1DE4 COMBINING LATIN SMALL LETTER S: not included in any glyphset definition</li>
<li>U+1DE5 COMBINING LATIN SMALL LETTER LONG S: not included in any glyphset definition</li>
<li>U+1DE6 COMBINING LATIN SMALL LETTER Z: not included in any glyphset definition</li>
<li>U+1DE7 COMBINING LATIN SMALL LETTER ALPHA: not included in any glyphset definition</li>
<li>U+1DE8 COMBINING LATIN SMALL LETTER B: not included in any glyphset definition</li>
<li>U+1DE9 COMBINING LATIN SMALL LETTER BETA: not included in any glyphset definition</li>
<li>U+1DEA COMBINING LATIN SMALL LETTER SCHWA: not included in any glyphset definition</li>
<li>U+1DEB COMBINING LATIN SMALL LETTER F: not included in any glyphset definition</li>
<li>U+1DEC COMBINING LATIN SMALL LETTER L WITH DOUBLE MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+1DED COMBINING LATIN SMALL LETTER O WITH LIGHT CENTRALIZATION STROKE: not included in any glyphset definition</li>
<li>U+1DEE COMBINING LATIN SMALL LETTER P: not included in any glyphset definition</li>
<li>U+1DEF COMBINING LATIN SMALL LETTER ESH: not included in any glyphset definition</li>
<li>U+1DF0 COMBINING LATIN SMALL LETTER U WITH LIGHT CENTRALIZATION STROKE: not included in any glyphset definition</li>
<li>U+1DF1 COMBINING LATIN SMALL LETTER W: not included in any glyphset definition</li>
<li>U+1DF2 COMBINING LATIN SMALL LETTER A WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF3 COMBINING LATIN SMALL LETTER O WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF4 COMBINING LATIN SMALL LETTER U WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+1DF5 COMBINING UP TACK ABOVE: not included in any glyphset definition</li>
<li>U+1DFB COMBINING DELETION MARK: try adding newa</li>
<li>U+1DFC COMBINING DOUBLE INVERTED BREVE BELOW: not included in any glyphset definition</li>
<li>U+1DFD COMBINING ALMOST EQUAL TO BELOW: not included in any glyphset definition</li>
<li>U+1DFE COMBINING LEFT ARROWHEAD ABOVE: not included in any glyphset definition</li>
<li>U+1DFF COMBINING RIGHT ARROWHEAD AND DOWN ARROWHEAD BELOW: not included in any glyphset definition</li>
<li>U+2000 EN QUAD: try adding symbols2</li>
<li>U+2001 EM QUAD: try adding symbols2</li>
<li>U+2003 EM SPACE: try adding nushu</li>
<li>U+2004 THREE-PER-EM SPACE: try adding symbols2</li>
<li>U+2005 FOUR-PER-EM SPACE: try adding symbols2</li>
<li>U+2006 SIX-PER-EM SPACE: try adding symbols2</li>
<li>U+2007 FIGURE SPACE: try adding symbols2</li>
<li>U+2008 PUNCTUATION SPACE: try adding symbols2</li>
<li>U+200A HAIR SPACE: try adding symbols2</li>
<li>U+2011 NON-BREAKING HYPHEN: try adding one of: syloti-nagri, arabic, yi</li>
<li>U+2012 FIGURE DASH: not included in any glyphset definition</li>
<li>U+2015 HORIZONTAL BAR: try adding adlam</li>
<li>U+2016 DOUBLE VERTICAL LINE: try adding math</li>
<li>U+2017 DOUBLE LOW LINE: try adding math</li>
<li>U+201B SINGLE HIGH-REVERSED-9 QUOTATION MARK: try adding adlam</li>
<li>U+201F DOUBLE HIGH-REVERSED-9 QUOTATION MARK: not included in any glyphset definition</li>
<li>U+2021 DOUBLE DAGGER: try adding adlam</li>
<li>U+2023 TRIANGULAR BULLET: not included in any glyphset definition</li>
<li>U+2024 ONE DOT LEADER: try adding armenian</li>
<li>U+2025 TWO DOT LEADER: try adding phags-pa</li>
<li>U+2027 HYPHENATION POINT: not included in any glyphset definition</li>
<li>U+2028 LINE SEPARATOR: not included in any glyphset definition</li>
<li>U+2029 PARAGRAPH SEPARATOR: not included in any glyphset definition</li>
<li>U+202A LEFT-TO-RIGHT EMBEDDING: not included in any glyphset definition</li>
<li>U+202B RIGHT-TO-LEFT EMBEDDING: not included in any glyphset definition</li>
<li>U+202C POP DIRECTIONAL FORMATTING: not included in any glyphset definition</li>
<li>U+202D LEFT-TO-RIGHT OVERRIDE: not included in any glyphset definition</li>
<li>U+202E RIGHT-TO-LEFT OVERRIDE: try adding tifinagh</li>
<li>U+202F NARROW NO-BREAK SPACE: try adding one of: phags-pa, yi, mongolian</li>
<li>U+2030 PER MILLE SIGN: try adding adlam</li>
<li>U+2031 PER TEN THOUSAND SIGN: not included in any glyphset definition</li>
<li>U+2034 TRIPLE PRIME: try adding math</li>
<li>U+2035 REVERSED PRIME: try adding math</li>
<li>U+2036 REVERSED DOUBLE PRIME: try adding math</li>
<li>U+2037 REVERSED TRIPLE PRIME: try adding math</li>
<li>U+2038 CARET: try adding math</li>
<li>U+203B REFERENCE MARK: not included in any glyphset definition</li>
<li>U+203C DOUBLE EXCLAMATION MARK: try adding math</li>
<li>U+203D INTERROBANG: not included in any glyphset definition</li>
<li>U+203E OVERLINE: not included in any glyphset definition</li>
<li>U+203F UNDERTIE: not included in any glyphset definition</li>
<li>U+2040 CHARACTER TIE: try adding math</li>
<li>U+2041 CARET INSERTION POINT: not included in any glyphset definition</li>
<li>U+2042 ASTERISM: not included in any glyphset definition</li>
<li>U+2043 HYPHEN BULLET: try adding math</li>
<li>U+2045 LEFT SQUARE BRACKET WITH QUILL: not included in any glyphset definition</li>
<li>U+2046 RIGHT SQUARE BRACKET WITH QUILL: not included in any glyphset definition</li>
<li>U+2047 DOUBLE QUESTION MARK: try adding math</li>
<li>U+2048 QUESTION EXCLAMATION MARK: try adding mongolian</li>
<li>U+2049 EXCLAMATION QUESTION MARK: try adding mongolian</li>
<li>U+204A TIRONIAN SIGN ET: not included in any glyphset definition</li>
<li>U+204B REVERSED PILCROW SIGN: not included in any glyphset definition</li>
<li>U+204C BLACK LEFTWARDS BULLET: not included in any glyphset definition</li>
<li>U+204D BLACK RIGHTWARDS BULLET: not included in any glyphset definition</li>
<li>U+204E LOW ASTERISK: not included in any glyphset definition</li>
<li>U+204F REVERSED SEMICOLON: try adding one of: arabic, adlam</li>
<li>U+2050 CLOSE UP: try adding math</li>
<li>U+2051 TWO ASTERISKS ALIGNED VERTICALLY: not included in any glyphset definition</li>
<li>U+2052 COMMERCIAL MINUS SIGN: not included in any glyphset definition</li>
<li>U+2053 SWUNG DASH: try adding coptic</li>
<li>U+2054 INVERTED UNDERTIE: not included in any glyphset definition</li>
<li>U+2055 FLOWER PUNCTUATION MARK: try adding syloti-nagri</li>
<li>U+2056 THREE DOT PUNCTUATION: try adding coptic</li>
<li>U+2057 QUADRUPLE PRIME: try adding math</li>
<li>U+2058 FOUR DOT PUNCTUATION: try adding coptic</li>
<li>U+2059 FIVE DOT PUNCTUATION: try adding coptic</li>
<li>U+205A TWO DOT PUNCTUATION: try adding one of: lycian, old-hungarian, glagolitic, georgian, old-turkic, carian</li>
<li>U+205B FOUR DOT MARK: not included in any glyphset definition</li>
<li>U+205C DOTTED CROSS: not included in any glyphset definition</li>
<li>U+205D TRICOLON: try adding one of: old-hungarian, carian, meroitic-hieroglyphs, meroitic</li>
<li>U+205E VERTICAL FOUR DOTS: try adding old-hungarian</li>
<li>U+205F MEDIUM MATHEMATICAL SPACE: try adding math</li>
<li>U+2060 WORD JOINER: not included in any glyphset definition</li>
<li>U+2061 FUNCTION APPLICATION: not included in any glyphset definition</li>
<li>U+2062 INVISIBLE TIMES: not included in any glyphset definition</li>
<li>U+2063 INVISIBLE SEPARATOR: not included in any glyphset definition</li>
<li>U+2064 INVISIBLE PLUS: not included in any glyphset definition</li>
<li>U+2066 LEFT-TO-RIGHT ISOLATE: not included in any glyphset definition</li>
<li>U+2067 RIGHT-TO-LEFT ISOLATE: not included in any glyphset definition</li>
<li>U+2068 FIRST STRONG ISOLATE: not included in any glyphset definition</li>
<li>U+2069 POP DIRECTIONAL ISOLATE: not included in any glyphset definition</li>
<li>U+206A INHIBIT SYMMETRIC SWAPPING: not included in any glyphset definition</li>
<li>U+206B ACTIVATE SYMMETRIC SWAPPING: not included in any glyphset definition</li>
<li>U+206C INHIBIT ARABIC FORM SHAPING: not included in any glyphset definition</li>
<li>U+206D ACTIVATE ARABIC FORM SHAPING: not included in any glyphset definition</li>
<li>U+206E NATIONAL DIGIT SHAPES: not included in any glyphset definition</li>
<li>U+206F NOMINAL DIGIT SHAPES: not included in any glyphset definition</li>
<li>U+2070 SUPERSCRIPT ZERO: try adding math</li>
<li>U+2071 SUPERSCRIPT LATIN SMALL LETTER I: try adding math</li>
<li>U+2074 SUPERSCRIPT FOUR: try adding math</li>
<li>U+2075 SUPERSCRIPT FIVE: try adding math</li>
<li>U+2076 SUPERSCRIPT SIX: try adding math</li>
<li>U+2077 SUPERSCRIPT SEVEN: try adding math</li>
<li>U+2078 SUPERSCRIPT EIGHT: try adding math</li>
<li>U+2079 SUPERSCRIPT NINE: try adding math</li>
<li>U+207A SUPERSCRIPT PLUS SIGN: try adding math</li>
<li>U+207B SUPERSCRIPT MINUS: try adding math</li>
<li>U+207C SUPERSCRIPT EQUALS SIGN: try adding math</li>
<li>U+207D SUPERSCRIPT LEFT PARENTHESIS: try adding math</li>
<li>U+207E SUPERSCRIPT RIGHT PARENTHESIS: try adding math</li>
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
<li>U+208A SUBSCRIPT PLUS SIGN: try adding math</li>
<li>U+208B SUBSCRIPT MINUS: try adding math</li>
<li>U+208C SUBSCRIPT EQUALS SIGN: try adding math</li>
<li>U+208D SUBSCRIPT LEFT PARENTHESIS: try adding math</li>
<li>U+208E SUBSCRIPT RIGHT PARENTHESIS: try adding math</li>
<li>U+2090 LATIN SUBSCRIPT SMALL LETTER A: try adding math</li>
<li>U+2091 LATIN SUBSCRIPT SMALL LETTER E: try adding math</li>
<li>U+2092 LATIN SUBSCRIPT SMALL LETTER O: try adding math</li>
<li>U+2093 LATIN SUBSCRIPT SMALL LETTER X: try adding math</li>
<li>U+2094 LATIN SUBSCRIPT SMALL LETTER SCHWA: try adding math</li>
<li>U+2095 LATIN SUBSCRIPT SMALL LETTER H: try adding math</li>
<li>U+2096 LATIN SUBSCRIPT SMALL LETTER K: try adding math</li>
<li>U+2097 LATIN SUBSCRIPT SMALL LETTER L: try adding math</li>
<li>U+2098 LATIN SUBSCRIPT SMALL LETTER M: try adding math</li>
<li>U+2099 LATIN SUBSCRIPT SMALL LETTER N: try adding math</li>
<li>U+209A LATIN SUBSCRIPT SMALL LETTER P: try adding math</li>
<li>U+209B LATIN SUBSCRIPT SMALL LETTER S: try adding math</li>
<li>U+209C LATIN SUBSCRIPT SMALL LETTER T: try adding math</li>
<li>U+20F0 COMBINING ASTERISK ABOVE: try adding one of: grantha, devanagari</li>
<li>U+2100 ACCOUNT OF: try adding math</li>
<li>U+2101 ADDRESSED TO THE SUBJECT: try adding math</li>
<li>U+2102 DOUBLE-STRUCK CAPITAL C: try adding math</li>
<li>U+2103 DEGREE CELSIUS: try adding math</li>
<li>U+2104 CENTRE LINE SYMBOL: try adding math</li>
<li>U+2105 CARE OF: try adding math</li>
<li>U+2106 CADA UNA: try adding math</li>
<li>U+2107 EULER CONSTANT: try adding math</li>
<li>U+2108 SCRUPLE: try adding math</li>
<li>U+2109 DEGREE FAHRENHEIT: try adding math</li>
<li>U+210A SCRIPT SMALL G: try adding math</li>
<li>U+210B SCRIPT CAPITAL H: try adding math</li>
<li>U+210C BLACK-LETTER CAPITAL H: try adding math</li>
<li>U+210D DOUBLE-STRUCK CAPITAL H: try adding math</li>
<li>U+210E PLANCK CONSTANT: try adding math</li>
<li>U+210F PLANCK CONSTANT OVER TWO PI: try adding math</li>
<li>U+2110 SCRIPT CAPITAL I: try adding math</li>
<li>U+2111 BLACK-LETTER CAPITAL I: try adding math</li>
<li>U+2112 SCRIPT CAPITAL L: try adding math</li>
<li>U+2114 L B BAR SYMBOL: try adding math</li>
<li>U+2115 DOUBLE-STRUCK CAPITAL N: try adding math</li>
<li>U+2117 SOUND RECORDING COPYRIGHT: try adding math</li>
<li>U+2118 SCRIPT CAPITAL P: try adding math</li>
<li>U+2119 DOUBLE-STRUCK CAPITAL P: try adding math</li>
<li>U+211A DOUBLE-STRUCK CAPITAL Q: try adding math</li>
<li>U+211B SCRIPT CAPITAL R: try adding math</li>
<li>U+211C BLACK-LETTER CAPITAL R: try adding math</li>
<li>U+211D DOUBLE-STRUCK CAPITAL R: try adding math</li>
<li>U+211E PRESCRIPTION TAKE: try adding math</li>
<li>U+211F RESPONSE: try adding math</li>
<li>U+2120 SERVICE MARK: try adding math</li>
<li>U+2121 TELEPHONE SIGN: try adding math</li>
<li>U+2123 VERSICLE: try adding math</li>
<li>U+2124 DOUBLE-STRUCK CAPITAL Z: try adding math</li>
<li>U+2125 OUNCE SIGN: try adding math</li>
<li>U+2126 OHM SIGN: try adding math</li>
<li>U+2127 INVERTED OHM SIGN: try adding math</li>
<li>U+2128 BLACK-LETTER CAPITAL Z: try adding math</li>
<li>U+2129 TURNED GREEK SMALL LETTER IOTA: try adding math</li>
<li>U+212A KELVIN SIGN: try adding math</li>
<li>U+212B ANGSTROM SIGN: try adding math</li>
<li>U+212C SCRIPT CAPITAL B: try adding math</li>
<li>U+212D BLACK-LETTER CAPITAL C: try adding math</li>
<li>U+212E ESTIMATED SYMBOL: try adding math</li>
<li>U+212F SCRIPT SMALL E: try adding math</li>
<li>U+2130 SCRIPT CAPITAL E: try adding math</li>
<li>U+2131 SCRIPT CAPITAL F: try adding math</li>
<li>U+2132 TURNED CAPITAL F: try adding math</li>
<li>U+2133 SCRIPT CAPITAL M: try adding math</li>
<li>U+2134 SCRIPT SMALL O: try adding math</li>
<li>U+2135 ALEF SYMBOL: try adding math</li>
<li>U+2136 BET SYMBOL: try adding math</li>
<li>U+2137 GIMEL SYMBOL: try adding math</li>
<li>U+2138 DALET SYMBOL: try adding math</li>
<li>U+2139 INFORMATION SOURCE: try adding math</li>
<li>U+213A ROTATED CAPITAL Q: try adding math</li>
<li>U+213B FACSIMILE SIGN: try adding math</li>
<li>U+213C DOUBLE-STRUCK SMALL PI: try adding math</li>
<li>U+213D DOUBLE-STRUCK SMALL GAMMA: try adding math</li>
<li>U+213E DOUBLE-STRUCK CAPITAL GAMMA: try adding math</li>
<li>U+213F DOUBLE-STRUCK CAPITAL PI: try adding math</li>
<li>U+2140 DOUBLE-STRUCK N-ARY SUMMATION: try adding math</li>
<li>U+2141 TURNED SANS-SERIF CAPITAL G: try adding math</li>
<li>U+2142 TURNED SANS-SERIF CAPITAL L: try adding math</li>
<li>U+2143 REVERSED SANS-SERIF CAPITAL L: try adding math</li>
<li>U+2144 TURNED SANS-SERIF CAPITAL Y: try adding math</li>
<li>U+2145 DOUBLE-STRUCK ITALIC CAPITAL D: try adding math</li>
<li>U+2146 DOUBLE-STRUCK ITALIC SMALL D: try adding math</li>
<li>U+2147 DOUBLE-STRUCK ITALIC SMALL E: try adding math</li>
<li>U+2148 DOUBLE-STRUCK ITALIC SMALL I: try adding math</li>
<li>U+2149 DOUBLE-STRUCK ITALIC SMALL J: try adding math</li>
<li>U+214A PROPERTY LINE: try adding math</li>
<li>U+214B TURNED AMPERSAND: try adding math</li>
<li>U+214C PER SIGN: try adding math</li>
<li>U+214D AKTIESELSKAB: try adding math</li>
<li>U+214E TURNED SMALL F: try adding math</li>
<li>U+214F SYMBOL FOR SAMARITAN SOURCE: try adding math</li>
<li>U+2153 VULGAR FRACTION ONE THIRD: try adding symbols</li>
<li>U+2154 VULGAR FRACTION TWO THIRDS: try adding symbols</li>
<li>U+215B VULGAR FRACTION ONE EIGHTH: try adding symbols</li>
<li>U+215C VULGAR FRACTION THREE EIGHTHS: try adding symbols</li>
<li>U+215D VULGAR FRACTION FIVE EIGHTHS: try adding symbols</li>
<li>U+215E VULGAR FRACTION SEVEN EIGHTHS: try adding symbols</li>
<li>U+2184 LATIN SMALL LETTER REVERSED C: not included in any glyphset definition</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+21A8 UP DOWN ARROW WITH BASE: try adding math</li>
<li>U+2202 PARTIAL DIFFERENTIAL: try adding math</li>
<li>U+2206 INCREMENT: try adding math</li>
<li>U+220F N-ARY PRODUCT: try adding math</li>
<li>U+2211 N-ARY SUMMATION: try adding math</li>
<li>U+2219 BULLET OPERATOR: try adding one of: symbols, math, yi, tai-tham</li>
<li>U+221A SQUARE ROOT: try adding math</li>
<li>U+221E INFINITY: try adding math</li>
<li>U+221F RIGHT ANGLE: try adding math</li>
<li>U+2229 INTERSECTION: try adding math</li>
<li>U+222B INTEGRAL: try adding math</li>
<li>U+2248 ALMOST EQUAL TO: try adding math</li>
<li>U+2260 NOT EQUAL TO: try adding math</li>
<li>U+2261 IDENTICAL TO: try adding math</li>
<li>U+2264 LESS-THAN OR EQUAL TO: try adding math</li>
<li>U+2265 GREATER-THAN OR EQUAL TO: try adding math</li>
<li>U+2302 HOUSE: try adding symbols</li>
<li>U+2310 REVERSED NOT SIGN: try adding math</li>
<li>U+2320 TOP HALF INTEGRAL: try adding math</li>
<li>U+2321 BOTTOM HALF INTEGRAL: try adding math</li>
<li>U+2500 BOX DRAWINGS LIGHT HORIZONTAL: try adding symbols2</li>
<li>U+2502 BOX DRAWINGS LIGHT VERTICAL: try adding symbols2</li>
<li>U+250C BOX DRAWINGS LIGHT DOWN AND RIGHT: try adding symbols2</li>
<li>U+2510 BOX DRAWINGS LIGHT DOWN AND LEFT: try adding symbols2</li>
<li>U+2514 BOX DRAWINGS LIGHT UP AND RIGHT: try adding symbols2</li>
<li>U+2518 BOX DRAWINGS LIGHT UP AND LEFT: try adding symbols2</li>
<li>U+251C BOX DRAWINGS LIGHT VERTICAL AND RIGHT: try adding symbols2</li>
<li>U+2524 BOX DRAWINGS LIGHT VERTICAL AND LEFT: try adding symbols2</li>
<li>U+252C BOX DRAWINGS LIGHT DOWN AND HORIZONTAL: try adding symbols2</li>
<li>U+2534 BOX DRAWINGS LIGHT UP AND HORIZONTAL: try adding symbols2</li>
<li>U+253C BOX DRAWINGS LIGHT VERTICAL AND HORIZONTAL: try adding symbols2</li>
<li>U+2550 BOX DRAWINGS DOUBLE HORIZONTAL: try adding symbols2</li>
<li>U+2551 BOX DRAWINGS DOUBLE VERTICAL: try adding symbols2</li>
<li>U+2552 BOX DRAWINGS DOWN SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+2553 BOX DRAWINGS DOWN DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+2554 BOX DRAWINGS DOUBLE DOWN AND RIGHT: try adding symbols2</li>
<li>U+2555 BOX DRAWINGS DOWN SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+2556 BOX DRAWINGS DOWN DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+2557 BOX DRAWINGS DOUBLE DOWN AND LEFT: try adding symbols2</li>
<li>U+2558 BOX DRAWINGS UP SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+2559 BOX DRAWINGS UP DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+255A BOX DRAWINGS DOUBLE UP AND RIGHT: try adding symbols2</li>
<li>U+255B BOX DRAWINGS UP SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+255C BOX DRAWINGS UP DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+255D BOX DRAWINGS DOUBLE UP AND LEFT: try adding symbols2</li>
<li>U+255E BOX DRAWINGS VERTICAL SINGLE AND RIGHT DOUBLE: try adding symbols2</li>
<li>U+255F BOX DRAWINGS VERTICAL DOUBLE AND RIGHT SINGLE: try adding symbols2</li>
<li>U+2560 BOX DRAWINGS DOUBLE VERTICAL AND RIGHT: try adding symbols2</li>
<li>U+2561 BOX DRAWINGS VERTICAL SINGLE AND LEFT DOUBLE: try adding symbols2</li>
<li>U+2562 BOX DRAWINGS VERTICAL DOUBLE AND LEFT SINGLE: try adding symbols2</li>
<li>U+2563 BOX DRAWINGS DOUBLE VERTICAL AND LEFT: try adding symbols2</li>
<li>U+2564 BOX DRAWINGS DOWN SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+2565 BOX DRAWINGS DOWN DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+2566 BOX DRAWINGS DOUBLE DOWN AND HORIZONTAL: try adding symbols2</li>
<li>U+2567 BOX DRAWINGS UP SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+2568 BOX DRAWINGS UP DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+2569 BOX DRAWINGS DOUBLE UP AND HORIZONTAL: try adding symbols2</li>
<li>U+256A BOX DRAWINGS VERTICAL SINGLE AND HORIZONTAL DOUBLE: try adding symbols2</li>
<li>U+256B BOX DRAWINGS VERTICAL DOUBLE AND HORIZONTAL SINGLE: try adding symbols2</li>
<li>U+256C BOX DRAWINGS DOUBLE VERTICAL AND HORIZONTAL: try adding symbols2</li>
<li>U+2580 UPPER HALF BLOCK: try adding symbols2</li>
<li>U+2584 LOWER HALF BLOCK: try adding symbols2</li>
<li>U+2588 FULL BLOCK: try adding symbols2</li>
<li>U+258C LEFT HALF BLOCK: try adding symbols2</li>
<li>U+2590 RIGHT HALF BLOCK: try adding symbols2</li>
<li>U+2591 LIGHT SHADE: try adding symbols2</li>
<li>U+2592 MEDIUM SHADE: try adding symbols2</li>
<li>U+2593 DARK SHADE: try adding symbols2</li>
<li>U+25A0 BLACK SQUARE: try adding symbols</li>
<li>U+25A1 WHITE SQUARE: try adding symbols</li>
<li>U+25AA BLACK SMALL SQUARE: try adding symbols</li>
<li>U+25AB WHITE SMALL SQUARE: try adding symbols</li>
<li>U+25AC BLACK RECTANGLE: try adding symbols</li>
<li>U+25B2 BLACK UP-POINTING TRIANGLE: try adding symbols</li>
<li>U+25BA BLACK RIGHT-POINTING POINTER: try adding symbols</li>
<li>U+25BC BLACK DOWN-POINTING TRIANGLE: try adding symbols</li>
<li>U+25C4 BLACK LEFT-POINTING POINTER: try adding symbols</li>
<li>U+25CA LOZENGE: try adding one of: symbols, math</li>
<li>U+25CB WHITE CIRCLE: try adding symbols</li>
<li>U+25CF BLACK CIRCLE: try adding symbols</li>
<li>U+25D8 INVERSE BULLET: try adding symbols</li>
<li>U+25D9 INVERSE WHITE CIRCLE: try adding symbols</li>
<li>U+25E6 WHITE BULLET: try adding symbols</li>
<li>U+263A WHITE SMILING FACE: try adding symbols</li>
<li>U+263B BLACK SMILING FACE: try adding symbols</li>
<li>U+263C WHITE SUN WITH RAYS: try adding symbols</li>
<li>U+2640 FEMALE SIGN: try adding symbols</li>
<li>U+2642 MALE SIGN: try adding symbols</li>
<li>U+2660 BLACK SPADE SUIT: try adding symbols</li>
<li>U+2663 BLACK CLUB SUIT: try adding symbols</li>
<li>U+2665 BLACK HEART SUIT: try adding symbols</li>
<li>U+2666 BLACK DIAMOND SUIT: try adding symbols</li>
<li>U+266A EIGHTH NOTE: try adding one of: symbols, music</li>
<li>U+266B BEAMED EIGHTH NOTES: try adding one of: symbols, music</li>
<li>U+266F MUSIC SHARP SIGN: try adding one of: symbols, music, math</li>
<li>U+2E00 RIGHT ANGLE SUBSTITUTION MARKER: not included in any glyphset definition</li>
<li>U+2E01 RIGHT ANGLE DOTTED SUBSTITUTION MARKER: not included in any glyphset definition</li>
<li>U+2E02 LEFT SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E03 RIGHT SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E04 LEFT DOTTED SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E05 RIGHT DOTTED SUBSTITUTION BRACKET: not included in any glyphset definition</li>
<li>U+2E06 RAISED INTERPOLATION MARKER: not included in any glyphset definition</li>
<li>U+2E07 RAISED DOTTED INTERPOLATION MARKER: not included in any glyphset definition</li>
<li>U+2E08 DOTTED TRANSPOSITION MARKER: not included in any glyphset definition</li>
<li>U+2E09 LEFT TRANSPOSITION BRACKET: not included in any glyphset definition</li>
<li>U+2E0A RIGHT TRANSPOSITION BRACKET: not included in any glyphset definition</li>
<li>U+2E0B RAISED SQUARE: not included in any glyphset definition</li>
<li>U+2E0C LEFT RAISED OMISSION BRACKET: not included in any glyphset definition</li>
<li>U+2E0D RIGHT RAISED OMISSION BRACKET: not included in any glyphset definition</li>
<li>U+2E0E EDITORIAL CORONIS: not included in any glyphset definition</li>
<li>U+2E0F PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E10 FORKED PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E11 REVERSED FORKED PARAGRAPHOS: not included in any glyphset definition</li>
<li>U+2E12 HYPODIASTOLE: not included in any glyphset definition</li>
<li>U+2E13 DOTTED OBELOS: not included in any glyphset definition</li>
<li>U+2E14 DOWNWARDS ANCORA: not included in any glyphset definition</li>
<li>U+2E15 UPWARDS ANCORA: not included in any glyphset definition</li>
<li>U+2E16 DOTTED RIGHT-POINTING ANGLE: not included in any glyphset definition</li>
<li>U+2E17 DOUBLE OBLIQUE HYPHEN: try adding coptic</li>
<li>U+2E18 INVERTED INTERROBANG: not included in any glyphset definition</li>
<li>U+2E19 PALM BRANCH: not included in any glyphset definition</li>
<li>U+2E1A HYPHEN WITH DIAERESIS: not included in any glyphset definition</li>
<li>U+2E1B TILDE WITH RING ABOVE: not included in any glyphset definition</li>
<li>U+2E1C LEFT LOW PARAPHRASE BRACKET: try adding nko</li>
<li>U+2E1D RIGHT LOW PARAPHRASE BRACKET: try adding nko</li>
<li>U+2E1E TILDE WITH DOT ABOVE: not included in any glyphset definition</li>
<li>U+2E1F TILDE WITH DOT BELOW: not included in any glyphset definition</li>
<li>U+2E20 LEFT VERTICAL BAR WITH QUILL: not included in any glyphset definition</li>
<li>U+2E21 RIGHT VERTICAL BAR WITH QUILL: not included in any glyphset definition</li>
<li>U+2E22 TOP LEFT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E23 TOP RIGHT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E24 BOTTOM LEFT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E25 BOTTOM RIGHT HALF BRACKET: not included in any glyphset definition</li>
<li>U+2E26 LEFT SIDEWAYS U BRACKET: not included in any glyphset definition</li>
<li>U+2E27 RIGHT SIDEWAYS U BRACKET: not included in any glyphset definition</li>
<li>U+2E28 LEFT DOUBLE PARENTHESIS: try adding adlam</li>
<li>U+2E29 RIGHT DOUBLE PARENTHESIS: try adding adlam</li>
<li>U+2E2A TWO DOTS OVER ONE DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2B ONE DOT OVER TWO DOTS PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2C SQUARED FOUR DOT PUNCTUATION: not included in any glyphset definition</li>
<li>U+2E2D FIVE DOT MARK: not included in any glyphset definition</li>
<li>U+2E2E REVERSED QUESTION MARK: not included in any glyphset definition</li>
<li>U+2E2F VERTICAL TILDE: not included in any glyphset definition</li>
<li>U+2E30 RING POINT: try adding one of: avestan, old-turkic</li>
<li>U+2E31 WORD SEPARATOR MIDDLE DOT: try adding one of: avestan, old-hungarian, kaithi, georgian, samaritan, carian, lydian</li>
<li>U+2E32 TURNED COMMA: not included in any glyphset definition</li>
<li>U+2E33 RAISED DOT: try adding coptic</li>
<li>U+2E34 RAISED COMMA: try adding coptic</li>
<li>U+2E35 TURNED SEMICOLON: not included in any glyphset definition</li>
<li>U+2E36 DAGGER WITH LEFT GUARD: not included in any glyphset definition</li>
<li>U+2E37 DAGGER WITH RIGHT GUARD: not included in any glyphset definition</li>
<li>U+2E38 TURNED DAGGER: not included in any glyphset definition</li>
<li>U+2E39 TOP HALF SECTION SIGN: not included in any glyphset definition</li>
<li>U+2E3A TWO-EM DASH: not included in any glyphset definition</li>
<li>U+2E3B THREE-EM DASH: not included in any glyphset definition</li>
<li>U+2E3C STENOGRAPHIC FULL STOP: try adding duployan</li>
<li>U+2E3D VERTICAL SIX DOTS: not included in any glyphset definition</li>
<li>U+2E3E WIGGLY VERTICAL LINE: not included in any glyphset definition</li>
<li>U+2E3F CAPITULUM: not included in any glyphset definition</li>
<li>U+2E40 DOUBLE HYPHEN: not included in any glyphset definition</li>
<li>U+2E41 REVERSED COMMA: try adding one of: arabic, old-hungarian, adlam</li>
<li>U+2E42 DOUBLE LOW-REVERSED-9 QUOTATION MARK: not included in any glyphset definition</li>
<li>U+A717 MODIFIER LETTER DOT VERTICAL BAR: not included in any glyphset definition</li>
<li>U+A718 MODIFIER LETTER DOT SLASH: not included in any glyphset definition</li>
<li>U+A719 MODIFIER LETTER DOT HORIZONTAL BAR: not included in any glyphset definition</li>
<li>U+A71A MODIFIER LETTER LOWER RIGHT CORNER ANGLE: not included in any glyphset definition</li>
<li>U+A71B MODIFIER LETTER RAISED UP ARROW: not included in any glyphset definition</li>
<li>U+A71C MODIFIER LETTER RAISED DOWN ARROW: not included in any glyphset definition</li>
<li>U+A71D MODIFIER LETTER RAISED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+A71E MODIFIER LETTER RAISED INVERTED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+A71F MODIFIER LETTER LOW INVERTED EXCLAMATION MARK: not included in any glyphset definition</li>
<li>U+AB30 LATIN SMALL LETTER BARRED ALPHA: not included in any glyphset definition</li>
<li>U+AB31 LATIN SMALL LETTER A REVERSED-SCHWA: not included in any glyphset definition</li>
<li>U+AB32 LATIN SMALL LETTER BLACKLETTER E: not included in any glyphset definition</li>
<li>U+AB33 LATIN SMALL LETTER BARRED E: not included in any glyphset definition</li>
<li>U+AB34 LATIN SMALL LETTER E WITH FLOURISH: not included in any glyphset definition</li>
<li>U+AB35 LATIN SMALL LETTER LENIS F: not included in any glyphset definition</li>
<li>U+AB36 LATIN SMALL LETTER SCRIPT G WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB37 LATIN SMALL LETTER L WITH INVERTED LAZY S: not included in any glyphset definition</li>
<li>U+AB38 LATIN SMALL LETTER L WITH DOUBLE MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+AB39 LATIN SMALL LETTER L WITH MIDDLE RING: not included in any glyphset definition</li>
<li>U+AB3A LATIN SMALL LETTER M WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3B LATIN SMALL LETTER N WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3C LATIN SMALL LETTER ENG WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB3D LATIN SMALL LETTER BLACKLETTER O: not included in any glyphset definition</li>
<li>U+AB3E LATIN SMALL LETTER BLACKLETTER O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB3F LATIN SMALL LETTER OPEN O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB40 LATIN SMALL LETTER INVERTED OE: not included in any glyphset definition</li>
<li>U+AB41 LATIN SMALL LETTER TURNED OE WITH STROKE: not included in any glyphset definition</li>
<li>U+AB42 LATIN SMALL LETTER TURNED OE WITH HORIZONTAL STROKE: not included in any glyphset definition</li>
<li>U+AB43 LATIN SMALL LETTER TURNED O OPEN-O: not included in any glyphset definition</li>
<li>U+AB44 LATIN SMALL LETTER TURNED O OPEN-O WITH STROKE: not included in any glyphset definition</li>
<li>U+AB45 LATIN SMALL LETTER STIRRUP R: not included in any glyphset definition</li>
<li>U+AB46 LATIN LETTER SMALL CAPITAL R WITH RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB47 LATIN SMALL LETTER R WITHOUT HANDLE: not included in any glyphset definition</li>
<li>U+AB48 LATIN SMALL LETTER DOUBLE R: not included in any glyphset definition</li>
<li>U+AB49 LATIN SMALL LETTER R WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB4A LATIN SMALL LETTER DOUBLE R WITH CROSSED-TAIL: not included in any glyphset definition</li>
<li>U+AB4B LATIN SMALL LETTER SCRIPT R: not included in any glyphset definition</li>
<li>U+AB4C LATIN SMALL LETTER SCRIPT R WITH RING: not included in any glyphset definition</li>
<li>U+AB4D LATIN SMALL LETTER BASELINE ESH: not included in any glyphset definition</li>
<li>U+AB4E LATIN SMALL LETTER U WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB4F LATIN SMALL LETTER U BAR WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB50 LATIN SMALL LETTER UI: not included in any glyphset definition</li>
<li>U+AB51 LATIN SMALL LETTER TURNED UI: not included in any glyphset definition</li>
<li>U+AB52 LATIN SMALL LETTER U WITH LEFT HOOK: not included in any glyphset definition</li>
<li>U+AB53 LATIN SMALL LETTER CHI: not included in any glyphset definition</li>
<li>U+AB54 LATIN SMALL LETTER CHI WITH LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB55 LATIN SMALL LETTER CHI WITH LOW LEFT SERIF: not included in any glyphset definition</li>
<li>U+AB56 LATIN SMALL LETTER X WITH LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB57 LATIN SMALL LETTER X WITH LONG LEFT LEG: not included in any glyphset definition</li>
<li>U+AB58 LATIN SMALL LETTER X WITH LONG LEFT LEG AND LOW RIGHT RING: not included in any glyphset definition</li>
<li>U+AB59 LATIN SMALL LETTER X WITH LONG LEFT LEG WITH SERIF: not included in any glyphset definition</li>
<li>U+AB5A LATIN SMALL LETTER Y WITH SHORT RIGHT LEG: not included in any glyphset definition</li>
<li>U+AB5B MODIFIER BREVE WITH INVERTED BREVE: not included in any glyphset definition</li>
<li>U+AB5C MODIFIER LETTER SMALL HENG: not included in any glyphset definition</li>
<li>U+AB5D MODIFIER LETTER SMALL L WITH INVERTED LAZY S: not included in any glyphset definition</li>
<li>U+AB5E MODIFIER LETTER SMALL L WITH MIDDLE TILDE: not included in any glyphset definition</li>
<li>U+AB5F MODIFIER LETTER SMALL U WITH LEFT HOOK: not included in any glyphset definition</li>
<li>U+AB60 LATIN SMALL LETTER SAKHA YAT: not included in any glyphset definition</li>
<li>U+AB61 LATIN SMALL LETTER IOTIFIED E: not included in any glyphset definition</li>
<li>U+AB62 LATIN SMALL LETTER OPEN OE: not included in any glyphset definition</li>
<li>U+AB63 LATIN SMALL LETTER UO: not included in any glyphset definition</li>
<li>U+AB64 LATIN SMALL LETTER INVERTED ALPHA: not included in any glyphset definition</li>
<li>U+AB65 GREEK LETTER SMALL CAPITAL OMEGA: not included in any glyphset definition</li>
<li>U+F001 : not included in any glyphset definition</li>
<li>U+F002 : not included in any glyphset definition</li>
<li>U+F004 : not included in any glyphset definition</li>
<li>U+F005 : not included in any glyphset definition</li>
<li>U+F00A : not included in any glyphset definition</li>
<li>U+F00B : not included in any glyphset definition</li>
<li>U+F00C : not included in any glyphset definition</li>
<li>U+F00D : not included in any glyphset definition</li>
<li>U+F00E : not included in any glyphset definition</li>
<li>U+FB01 LATIN SMALL LIGATURE FI: not included in any glyphset definition</li>
<li>U+FB02 LATIN SMALL LIGATURE FL: not included in any glyphset definition</li>
<li>U+FB03 LATIN SMALL LIGATURE FFI: not included in any glyphset definition</li>
<li>U+FB04 LATIN SMALL LIGATURE FFL: not included in any glyphset definition</li>
<li>U+FE20 COMBINING LIGATURE LEFT HALF: try adding caucasian-albanian</li>
<li>U+FE21 COMBINING LIGATURE RIGHT HALF: try adding caucasian-albanian</li>
<li>U+FE22 COMBINING DOUBLE TILDE LEFT HALF: try adding caucasian-albanian</li>
<li>U+FE23 COMBINING DOUBLE TILDE RIGHT HALF: try adding caucasian-albanian</li>
<li>U+FE24 COMBINING MACRON LEFT HALF: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE25 COMBINING MACRON RIGHT HALF: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE26 COMBINING CONJOINING MACRON: try adding one of: coptic, caucasian-albanian</li>
<li>U+FE27 COMBINING LIGATURE LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE28 COMBINING LIGATURE RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE29 COMBINING TILDE LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2A COMBINING TILDE RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2B COMBINING MACRON LEFT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2C COMBINING MACRON RIGHT HALF BELOW: try adding caucasian-albanian</li>
<li>U+FE2D COMBINING CONJOINING MACRON BELOW: try adding caucasian-albanian</li>
<li>U+FFFC OBJECT REPLACEMENT CHARACTER: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic</code>, <code>cyrillic-ext</code>, <code>greek</code>, <code>greek-ext</code>, <code>hebrew</code>, <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#soft-dotted">soft_dotted</a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: i̊ i̋ i̍ i̐ i̓ i᷆ i᷇ j̀ j́ j̃ j̄ j̈ j̑ į̀ į́ į̂ į̃ į̄ į̌ ɨ̀ ɨ́ ɨ̂ ɨ̃ ɨ̄ ɨ̈ ɨ̋ ɨ̌ ɨ̏ ɨ̧̀ ɨ̧́ ɨ̧̂ ɨ̧̌ ɨ̱̀ ɨ̱́ ɨ̱̈ і́ ḭ̀ ḭ́ ḭ̄ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: i̅ i̇ i̎ i̒ i̔ i̽ i̾ i̿ i͂ i͆ i͊ i͋ i͌ i͐ i͑ i͒ i͗ i͛ iͣ iͤ</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Ukrainian (Cyrl, 29,273,587 speakers), Belarusian (Cyrl, 10,064,517 speakers), Zapotec (Latn, 490,000 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Gulay (Latn, 250,478 speakers), Mundani (Latn, 34,000 speakers), Vute (Latn, 21,000 speakers), Longto (Latn, 5,000 speakers), Southern Tutchone (Latn, 65 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Fur (Latn, 1,230,163 speakers), Ejagham (Latn, 120,000 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Cicipu (Latn, 44,000 speakers), Aghem (Latn, 38,843 speakers), Kaska (Latn, 125 speakers), Ma’di (Latn, 584,000 speakers), Ebira (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Western Krahn (Latn, 97,800 speakers), Southern Kisi (Latn, 360,000 speakers), Bafut (Latn, 158,146 speakers), Avokaya (Latn, 100,000 speakers), Igbo (Latn, 27,823,640 speakers), Dutch (Latn, 31,709,104 speakers), Ekpeye (Latn, 226,000 speakers), Makaa (Latn, 221,000 speakers), Northern Tutchone (Latn, 85 speakers), Yala (Latn, 200,000 speakers), Keliko (Latn, 63,000 speakers), Navajo (Latn, 166,319 speakers), Lugbara (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Ngbaka (Latn, 1,020,000 speakers), Heiltsuk (Latn, 300 speakers), Bete-Bendi (Latn, 100,000 speakers), Mfumte (Latn, 79,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Teke-Ebo (Latn, 260,000 speakers), South Central Banda (Latn, 244,000 speakers), Abua (Latn, 25,000 speakers), Han (Latn, 6 speakers), Ikwere (Latn, 717,000 speakers), Nzakara (Latn, 50,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any jaggy segments? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-jaggy-segments">outline_jaggy_segments</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have jaggy segments:</p>
<pre><code>* uni03D2 (U+03D2): B&lt;&lt;553.5,1169.5&gt;-&lt;746.0,998.0&gt;-&lt;773.0,675.0&gt;&gt;/B&lt;&lt;773.0,675.0&gt;-&lt;812.0,1002.0&gt;-&lt;940.0,1179.0&gt;&gt; = 11.579636447646337

* uni03D3 (U+03D3): B&lt;&lt;965.5,1169.5&gt;-&lt;1158.0,998.0&gt;-&lt;1185.0,675.0&gt;&gt;/B&lt;&lt;1185.0,675.0&gt;-&lt;1224.0,1002.0&gt;-&lt;1352.0,1179.0&gt;&gt; = 11.579636447646337

* uni03D4 (U+03D4): B&lt;&lt;553.5,1169.5&gt;-&lt;746.0,998.0&gt;-&lt;773.0,675.0&gt;&gt;/B&lt;&lt;773.0,675.0&gt;-&lt;812.0,1002.0&gt;-&lt;940.0,1179.0&gt;&gt; = 11.579636447646337

* uni1DDB (U+1DDB): L&lt;&lt;109.0,1546.0&gt;--&lt;112.0,1544.0&gt;&gt;/B&lt;&lt;112.0,1544.0&gt;-&lt;72.0,1575.0&gt;-&lt;21.0,1575.0&gt;&gt; = 4.085616779974798

* uni210A (U+210A): B&lt;&lt;190.5,333.0&gt;-&lt;211.0,390.0&gt;-&lt;240.0,428.0&gt;&gt;/L&lt;&lt;240.0,428.0&gt;--&lt;106.0,297.0&gt;&gt; = 8.29925471425042

* uni210B (U+210B): B&lt;&lt;1054.5,1043.5&gt;-&lt;1109.0,1122.0&gt;-&lt;1165.0,1190.0&gt;&gt;/B&lt;&lt;1165.0,1190.0&gt;-&lt;1095.0,1126.0&gt;-&lt;1031.0,1075.0&gt;&gt; = 8.09131036312114

* uni2133 (U+2133): B&lt;&lt;2033.0,1106.0&gt;-&lt;2137.0,1230.0&gt;-&lt;2304.0,1421.0&gt;&gt;/B&lt;&lt;2304.0,1421.0&gt;-&lt;2197.0,1345.0&gt;-&lt;2071.0,1224.0&gt;&gt; = 13.449888368034253

* uni2E3F (U+2E3F): L&lt;&lt;829.0,1066.0&gt;--&lt;834.0,1062.0&gt;&gt;/B&lt;&lt;834.0,1062.0&gt;-&lt;799.0,1103.0&gt;-&lt;719.0,1127.0&gt;&gt; = 10.854180203911149
</code></pre>
 [code: found-jaggy-segments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do outlines contain any semi-vertical or semi-horizontal lines? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#outline-semi-vertical">outline_semi_vertical</a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have semi-vertical/semi-horizontal lines:</p>
<pre><code>* D (U+0044): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* Dcaron (U+010E): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* Eth (U+00D0): L&lt;&lt;737.0,-4.0&gt;--&lt;80.0,0.0&gt;&gt;

* finalmem (U+05DD): L&lt;&lt;180.0,0.0&gt;--&lt;178.0,483.0&gt;&gt;

* finalmemwide (U+FB26): L&lt;&lt;180.0,0.0&gt;--&lt;178.0,483.0&gt;&gt;

* finalnun (U+05DF): L&lt;&lt;207.0,22.0&gt;--&lt;209.0,372.0&gt;&gt;

* he (U+05D4): L&lt;&lt;156.0,178.0&gt;--&lt;154.0,416.0&gt;&gt;

* hedagesh (U+FB34): L&lt;&lt;156.0,178.0&gt;--&lt;154.0,416.0&gt;&gt;

* hewide (U+FB23): L&lt;&lt;156.0,178.0&gt;--&lt;154.0,416.0&gt;&gt;

* integral (U+222B): L&lt;&lt;360.0,1079.0&gt;--&lt;364.0,541.0&gt;&gt;

* lira (U+20A4): L&lt;&lt;360.0,222.0&gt;--&lt;960.0,223.0&gt;&gt;

* sterling (U+00A3): L&lt;&lt;360.0,222.0&gt;--&lt;960.0,223.0&gt;&gt;

* uni0110 (U+0110): L&lt;&lt;737.0,-4.0&gt;--&lt;80.0,0.0&gt;&gt;

* uni0189 (U+0189): L&lt;&lt;737.0,-4.0&gt;--&lt;80.0,0.0&gt;&gt;

* uni018A (U+018A): L&lt;&lt;923.0,-4.0&gt;--&lt;244.0,0.0&gt;&gt;

* uni019C (U+019C): L&lt;&lt;1691.0,1242.0&gt;--&lt;1690.0,100.0&gt;&gt;

* uni01C4 (U+01C4): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* uni01C5 (U+01C5): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* uni01F1 (U+01F1): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* uni01F2 (U+01F2): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* uni025B (U+025B): L&lt;&lt;814.0,929.0&gt;--&lt;813.0,692.0&gt;&gt;

* uni025C (U+025C): L&lt;&lt;62.0,692.0&gt;--&lt;61.0,929.0&gt;&gt;

* uni025D (U+025D): L&lt;&lt;62.0,692.0&gt;--&lt;61.0,929.0&gt;&gt;

* uni03E2 (U+03E2): L&lt;&lt;1645.0,1242.0&gt;--&lt;1644.0,19.0&gt;&gt;

* uni04CD (U+04CD): L&lt;&lt;1585.0,-1.0&gt;--&lt;1207.0,0.0&gt;&gt;

* uni1D08 (U+1D08): L&lt;&lt;75.0,16.0&gt;--&lt;76.0,253.0&gt;&gt;

* uni1D93 (U+1D93): L&lt;&lt;814.0,929.0&gt;--&lt;813.0,692.0&gt;&gt;

* uni1D94 (U+1D94): L&lt;&lt;62.0,692.0&gt;--&lt;61.0,929.0&gt;&gt;

* uni1E0A (U+1E0A): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* uni1E0C (U+1E0C): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* uni1E0E (U+1E0E): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* uni1E10 (U+1E10): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* uni1E12 (U+1E12): L&lt;&lt;715.0,-4.0&gt;--&lt;36.0,0.0&gt;&gt;

* uni1E9E (U+1E9E): L&lt;&lt;735.0,639.0&gt;--&lt;734.0,759.0&gt;&gt;

* uni2C76 (U+2C76): L&lt;&lt;54.0,940.0&gt;--&lt;579.0,941.0&gt;&gt;

* uniA641 (U+A641): L&lt;&lt;380.0,90.0&gt;--&lt;539.0,89.0&gt;&gt;

* uniA717 (U+A717): L&lt;&lt;208.0,1834.0&gt;--&lt;207.0,1186.0&gt;&gt;

* uniA717 (U+A717): L&lt;&lt;78.0,1186.0&gt;--&lt;79.0,1834.0&gt;&gt;

* uniA786 (U+A786): L&lt;&lt;1251.0,165.0&gt;--&lt;1252.0,42.0&gt;&gt;
</code></pre>
 [code: found-semi-vertical]



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
    <summary>⚠️ <b>WARN</b> Description strings in the name table must not exceed 200 characters. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.html#googlefonts-name-description-max-length">googlefonts/name/description_max_length</a></summary>
    <div>







* ⚠️ **WARN** <p>A few name table entries with ID=10 (NameID.DESCRIPTION) are longer than 200 characters. Please check whether those entries are copyright notices mistakenly stored in the description string entries by a bug in an old FontLab version. If that's the case, then such copyright notices must be removed from these entries.</p>
 [code: too-long]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 43 | 52 | 415 | 25 | 358 | 0 | 
| 0% | 0% | 5% | 6% | 46% | 3% | 40% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
