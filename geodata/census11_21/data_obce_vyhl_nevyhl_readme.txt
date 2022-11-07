1) Úvod
    Upravená data ze sčítání lidu 2011 a 2021 na úrovni obcí.
    Data by se dala rozdělit do 11 skupin (v závorce vždy uvedeno, jak daný sloupec začíná):
    1) děti (deti)
    2) domy materiál (domy_mat)
    3) domy období výstavby/rekonstrukce (domy_obd)
    4) domy vlastník (domy_vlast)
    5) mateřský jazyk (jazyk)
    6) národnost (narod)
    7) občanství (obcanstvi)
    8) rodinný stav (rod_stav)
    9) věk (vek) - možnost buď celkově věk (muži a ženy dohromady) nebo možnost podrozdělit na pouze muže (vek_muzi) nebo pouze ženy (vek_zeny)
    10) náboženská víra (vira)
    11) vzdělání (vzdelani)

    Poté následuje konkrétní kategorie dané skupiny, tedy např. "deti_3" značí 3 děti, "domy_vlast_byt_dr" jsou domy vlastněné bytovým družstvem 
    Může následovat "_vyhl", což znamená, že je daná featura vyhlazena.
    Nakonec následuje buď
                          2011, což jsou data z roku 2011 (pokud jsme pro dané kategorie měli data pouze z roku 2011)
                      nebo 
                          2021, což jsou data z roku 2021 (pokud jsme pro dané kategorie měli data pouze z roku 2021)
                      nebo
                          mean - průměr z dat 2011 a 2021
                      nebo
                          diff - rozdíl 2021 a 2011


2) Podrobný popis sloupců:
    OBEC_KOD - kód obce
    OBEC_NAZEV - název obce

    deti_0_2021 - bezdětné (data z roku 2021)
    deti_1_2021 - jedno dítě (data z roku 2021)
    deti_2_2021 - dvě děti (data z roku 2021)
    deti_3_2021 - tři děti (data z roku 2021)
    deti_4_2021 - čtyři děti (data z roku 2021)
    deti_5_vice_2021 - pět a více dětí (data z roku 2021)
    deti_nezj_2021  - počet dětí nezjištěn (data z roku 2021)

    domy_mat_drevo_2021 - domy ze dřeva (data z roku 2021)
    domy_mat_kamen_cihly_2021 - domy z kamene/cihel/tvárnic (data z roku 2021)
    domy_mat_nep_cihly_2021 - domy z nepálených cihel (data z roku 2021)
    domy_mat_nezj_2021  - domy s nezjištěným materiálem (data z roku 2021)
    domy_mat_ostatni_2021 - domy z jiného materiálu (data z roku 2021)
    domy_mat_panel_2021 - domy z panelu (data z roku 2021)

    domy_obd_1919_2021 - domy z období výstavby či rekonstrukce z roku 1919 a dříve (data z roku 2021)
    domy_obd_1920_1945_2021 - domy z období výstavby či rekontrukce z let 1920 až 1945 (data z roku 2021)
    domy_obd_1946_1970_2021 - domy z období výstavby či rekontrukce z let 1946 až 1970 (data z roku 2021)
    domy_obd_1971_1980_2021
    domy_obd_1981_1990_2021
    domy_obd_1991_2000_2021
    domy_obd_2001_2010_2021
    domy_obd_2011_2015_2021
    domy_obd_2016_2021 - domy z období výstavby či rekonstrukce z roku 2016 a později (data z roku 2021)
    domy_obd_nezj_2021 - domy pro které období výstavby či rekontrukce nebylo zjištěno (data z roku 2021)

    domy_vlast_byt_dr_mean - domy s vlatníkem bytové družstvo (průměr z dat 2011 a 2021)
    domy_vlast_byt_dr_diff - domy s vlastníkem bytové družstvo (hodnoty z 2021 mínus hodnoty z 2011)
    domy_vlast_fyz_mean - domy s vlastníkem fyzická osoba (průměr z dat 2011 a 2021)
    domy_vlast_fyz_diff
    domy_vlast_obec_stat_mean - domy s vlastníkem obec/stát (průměr z dat 2011 a 2021)
    domy_vlast_obec_stat_diff
    domy_vlast_spol_mean - domy s vlastníkem spoluvlastnictví vlastníků bytů (jednotek) (průměr z dat 2011 a 2021) 
    domy_vlast_spol_diff

    jazyk_cesky_2021 - mateřský jazyk český (data z roku 2021)
    jazyk_nezj_2021 - mateřský jazyk nezjištěn (data z roku 2021)
    jazyk_slov_2021 - mateřský jazyk slovenský (data z roku 2021)
    jazyk_ukr_2021 - mateřský jazyk ukrajinský (data z roku 2021)

    narod_ceska_mean - národnost česká (průměr z dat 2011 a 2021) 
    narod_ceska_diff - národnost česká (hodnoty z 2021 mínus hodnoty z 2011)
    narod_morav_mean - národnost moravská (průměr z dat 2011 a 2021)
    narod_morav_diff
    narod_nezj_2011 - národnost nezjištěna (data z roku 2011)
    narod_slov_mean - národnost slovenská (průměr z dat 2011 a 2021) 
    narod_slov_diff
    narod_ukr_mean - národnost ukrajinská (průměr z dat 2011 a 2021)
    narod_ukr_diff

    obcanstvi_cesko_2021 - občanství české (data z roku 2021)
    obcanstvi_nezj_2021 - občanství nezjištěno (data z roku 2021)
    obcanstvi_slov_2021 - občanství slovenské (data z roku 2021)
    obcanstvi_ukr_2021  - občanství ukrajinské (data z roku 2021)

    rod_stav_nezj_2021 - rodinný stav nezjištěn (data z roku 2021)
    rod_stav_rozv_mean - rodinný stav rozvedený/rozvedená (průměr z dat 2011 a 2021)
    rod_stav_rozv_diff - rodinný stav rozvedený/rozvedená (hodnoty z 2021 mínus hodnoty z 2011)
    rod_stav_svob_mean - rodinný stav svobodný/svobodná (průměr z dat 2011 a 2021)
    rod_stav_svob_diff
    rod_stav_vdov_mean - rodinný stav vdovec/vdova (průměr z dat 2011 a 2021)
    rod_stav_vdov_diff
    rod_stav_zen_vdana_mean - rodinný stav ženatý/vdaná (průměr z dat 2011 a 2021)
    rod_stav_zen_vdana_diff

    vek_0_14_mean - věk 0 až 14 (průměr z dat 2011 a 2021)
    vek_0_14_diff - věk 0 až 14 (hodnoty z 2021 mínus hodnoty z 2011)
    vek_15_19_mean - věk 15 až 19 (průměr z dat 2011 a 2021)
    vek_15_19_diff
    vek_20_29_mean
    vek_20_29_diff
    vek_30_39_mean
    vek_30_39_diff
    vek_40_49_mean
    vek_40_49_diff
    vek_50_59_mean
    vek_50_59_diff
    vek_60_64_mean
    vek_60_64_diff
    vek_65_69_mean
    vek_65_69_diff
    vek_70_79_mean
    vek_70_79_diff
    vek_80_inf_mean - věk 80 a více (průměr z dat 2011 a 2021) 
    vek_80_inf_diff - věk 80 a více (hodnoty z 2021 mínus hodnoty z 2011)
    vek_muzi_0_14_mean - muži ve věku 0 až 14  (průměr z dat 2011 a 2021)
    vek_muzi_0_14_diff - muži ve věku 0 až 14 (hodnoty z 2021 mínus hodnoty z 2011)
    vek_muzi_15_19_mean
    vek_muzi_15_19_diff
    vek_muzi_20_29_mean
    vek_muzi_20_29_diff
    vek_muzi_30_39_mean
    vek_muzi_30_39_diff
    vek_muzi_40_49_mean
    vek_muzi_40_49_diff
    vek_muzi_50_59_mean
    vek_muzi_50_59_diff
    vek_muzi_60_64_mean
    vek_muzi_60_64_diff
    vek_muzi_65_69_mean
    vek_muzi_65_69_diff
    vek_muzi_70_79_mean
    vek_muzi_70_79_diff
    vek_muzi_80_inf_mean
    vek_muzi_80_inf_diff
    vek_zeny_0_14_mean - ženy ve věku 0 až 14 (průměr z dat 2011 a 2021)
    vek_zeny_0_14_diff - ženy ve věku 0 až 14 (hodnoty z 2021 mínus hodnoty z 2011)
    vek_zeny_15_19_mean
    vek_zeny_15_19_diff
    vek_zeny_20_29_mean
    vek_zeny_20_29_diff
    vek_zeny_30_39_mean
    vek_zeny_30_39_diff
    vek_zeny_40_49_mean
    vek_zeny_40_49_diff
    vek_zeny_50_59_mean
    vek_zeny_50_59_diff
    vek_zeny_60_64_mean
    vek_zeny_60_64_diff
    vek_zeny_65_69_mean
    vek_zeny_65_69_diff
    vek_zeny_70_79_mean
    vek_zeny_70_79_diff
    vek_zeny_80_inf_mean
    vek_zeny_80_inf_diff

    vira_ateisti_mean - bez náboženské víry (průměr z dat 2011 a 2021)
    vira_ateisti_diff - bez náboženské víry (hodnoty z 2021 mínus hodnoty z 2011)
    vira_evangelici_mean - Českobratrská církev evangelická (průměr z dat 2011 a 2021)
    vira_evangelici_diff
    vira_hlasici_mean - věřící hlásící se k církvi nebo náboženské společnosti (průměr z dat 2011 a 2021)
    vira_hlasici_diff
    vira_husiti_mean - Církev československá husitská (průměr z dat 2011 a 2021)
    vira_husiti_diff 
    vira_katolici_mean - Církev římskokatolická (průměr z dat 2011 a 2021)
    vira_katolici_diff
    vira_nehlasici_mean - věřící, ale nehlásící se k žádné církvi ani náboženské společnosti (průměr z dat 2011 a 2021)
    vira_nehlasici_diff
    vira_nezj_mean - víra nezjištěna (průměr z dat 2011 a 2021)
    vira_nezj_diff

    vzdelani_bez_mean - bez vzdělání (průměr z dat 2011 a 2021)
    vzdelani_bez_diff - bez vzdělání (hodnoty z 2021 mínus hodnoty z 2011)
    vzdelani_nezj_2021 - vzdělání nezjištěno (data z roku 2021)
    vzdelani_str_bm_mean - vzdělání střední vč. vyučení (bez maturity)  (průměr z dat 2011 a 2021)
    vzdelani_str_bm_diff
    vzdelani_str_np_mean - vzdělání střední (s maturitou), vč. nástavbového a pomaturitního (průměr z dat 2011 a 2021)
    vzdelani_str_np_diff
    vzdelani_vo_mean - vzdělání vyšší odborné/konzervatoř (průměr z dat 2011 a 2021)
    vzdelani_vo_diff
    vzdelani_vys_mean - vzdělání vysokoškolské (průměr z dat 2011 a 2021)
    vzdelani_vys_diff
    vzdelani_zakl_mean - vzdělání základní vč. neukončeného (průměr z dat 2011 a 2021)
    vzdelani_zakl_diff

    vzdelani_nezj_vyhl_2021 - vyhlazená featura vzdelani_nezj_2021
    jazyk_nezj_vyhl_2021 - vyhlazená featura jazyk_nezj_2021
    jazyk_cesky_vyhl_2021 - vyhlazená featura jazyk_cesky_2021
    deti_5_vice_vyhl_2021 - vyhlazená featura deti_5_vice_2021
    domy_obd_1919_vyhl_2021 - vyhlazená featura domy_obd_1919_2021
    rod_stav_rozv_vyhl_mean - vyhlazená featura rod_stav_rozv_mean
    vzdelani_zakl_vyhl_mean - vyhlazená featura vzdelani_zakl_mean
    rod_stav_zen_vdana_vyhl_mean - vyhlazená featura rod_stav_zen_vdana_mean
    vzdelani_str_np_vyhl_mean - vyhlazená featura vzdelani_str_np_mean
    vzdelani_vys_vyhl_mean - vyhlazená featura vzdelani_vys_mean
    vira_ateisti_vyhl_mean - vyhlazená featura vira_ateisti_mean
    vek_80_inf_vyhl_mean - vyhlazená featura vek_80_inf_mean
    domy_vlast_obec_stat_vyhl_mean - vyhlazená featura domy_vlast_obec_stat_mean
    domy_vlast_fyz_vyhl_mean - vyhlazená featura domy_vlast_fyz_mean



3) Více detailů - jak jsme k hodnotám dospěli:
     Nejprve jsme napočítali poměry pro všechny obce a všechny kategorie, tedy např. jsme si vzali danou obec, podívali jsme se kolik v ní žije lidí ve věku 0-14 a toto číslo jsme
     vydělili počtem lidí v obci.
     Vzdělání je počítáno ku počtu obyvatel 15+.
     Počet dětí je počítán ku počtu žen 15+.
     Pokud jsme měli pro určité kategorie hodnoty pro roky 2011 i 2021, tak jsme spočítali průměr těchto hodnot (mean) a rozdíl těchto hodnot (diff).
     Featury, které se zdály být nejlepší, jsme ještě vyhladili pomocí beta rozdělení (vyhl v názvu).