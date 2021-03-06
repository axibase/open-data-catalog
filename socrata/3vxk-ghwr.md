# Criminal Justice

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/criminal-justice-7854d) |
| Metadata | [Link](https://data.wa.gov/api/views/3vxk-ghwr) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/3vxk-ghwr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/3vxk-ghwr/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 3vxk-ghwr |
| Name | Criminal Justice |
| Category | Public Safety |
| Created | 2013-06-21T16:35:46Z |
| Publication Date | 2013-06-21T16:37:42Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | time           | year             | YEAR             | calendar_date | calendar_date |
| Yes      | series tag     | county           | COUNTY           | text          | text          |
| Yes      | numeric metric | pop_f_0to11      | POP_F_0TO11      | number        | number        |
| Yes      | numeric metric | pop_f_12to17     | POP_F_12TO17     | number        | number        |
| Yes      | numeric metric | pop_f_18to39     | POP_F_18TO39     | number        | number        |
| Yes      | numeric metric | pop_f_40up       | POP_F_40UP       | number        | number        |
| Yes      | numeric metric | pop_f_total      | POP_F_TOTAL      | number        | number        |
| Yes      | numeric metric | pop_m_0to11      | POP_M_0TO11      | number        | number        |
| Yes      | numeric metric | pop_m_12to17     | POP_M_12TO17     | number        | number        |
| Yes      | numeric metric | pop_m_18to39     | POP_M_18TO39     | number        | number        |
| Yes      | numeric metric | pop_m_40up       | POP_M_40UP       | number        | number        |
| Yes      | numeric metric | pop_m_total      | POP_M_TOTAL      | number        | number        |
| Yes      | numeric metric | ucr_ag_asslt     | UCR_AG_ASSLT     | number        | number        |
| Yes      | numeric metric | ucr_arson        | UCR_ARSON        | number        | number        |
| Yes      | numeric metric | ucr_burglary     | UCR_BURGLARY     | number        | number        |
| Yes      | numeric metric | ucr_murder       | UCR_MURDER       | number        | number        |
| Yes      | numeric metric | ucr_mvt          | UCR_MVT          | number        | number        |
| Yes      | numeric metric | ucr_rape         | UCR_RAPE         | number        | number        |
| Yes      | numeric metric | ucr_robbery      | UCR_ROBBERY      | number        | number        |
| Yes      | numeric metric | ucr_theft        | UCR_THEFT        | number        | number        |
| Yes      | numeric metric | ucr_total        | UCR_TOTAL        | number        | number        |
| Yes      | numeric metric | arr_ag_asslt     | ARR_AG_ASSLT     | number        | number        |
| Yes      | numeric metric | arr_arson        | ARR_ARSON        | number        | number        |
| Yes      | numeric metric | arr_burglary     | ARR_BURGLARY     | number        | number        |
| Yes      | numeric metric | arr_drug_cr      | ARR_DRUG_CR      | number        | number        |
| Yes      | numeric metric | arr_murder       | ARR_MURDER       | number        | number        |
| Yes      | numeric metric | arr_mvt          | ARR_MVT          | number        | number        |
| Yes      | numeric metric | arr_othcrime     | ARR_OTHCRIME     | number        | number        |
| Yes      | numeric metric | arr_rape         | ARR_RAPE         | number        | number        |
| Yes      | numeric metric | arr_robbery      | ARR_ROBBERY      | number        | number        |
| Yes      | numeric metric | arr_theft        | ARR_THEFT        | number        | number        |
| Yes      | numeric metric | arr_total        | ARR_TOTAL        | number        | number        |
| Yes      | numeric metric | scf_assault      | SCF_ASSAULT      | number        | number        |
| Yes      | numeric metric | scf_drug_cr      | SCF_DRUG_CR      | number        | number        |
| Yes      | numeric metric | scf_homicide     | SCF_HOMICIDE     | number        | number        |
| Yes      | numeric metric | scf_othfelon     | SCF_OTHFELON     | number        | number        |
| Yes      | numeric metric | scf_propcr       | SCF_PROPCR       | number        | number        |
| Yes      | numeric metric | scf_robbery      | SCF_ROBBERY      | number        | number        |
| Yes      | numeric metric | scf_sexcr        | SCF_SEXCR        | number        | number        |
| Yes      | numeric metric | scf_total        | SCF_TOTAL        | number        | number        |
| Yes      | numeric metric | jdp_othradp      | JDP_OTHRADP      | number        | number        |
| Yes      | numeric metric | jdp_post_adp     | JDP_POST_ADP     | number        | number        |
| Yes      | numeric metric | jdp_pre_adp      | JDP_PRE_ADP      | number        | number        |
| Yes      | numeric metric | jdp_capacity     | JDP_CAPACITY     | number        | number        |
| Yes      | numeric metric | jdp_totaladp     | JDP_TOTALADP     | number        | number        |
| Yes      | numeric metric | jst_assault      | JST_ASSAULT      | number        | number        |
| Yes      | numeric metric | jst_burglary     | JST_BURGLARY     | number        | number        |
| Yes      | numeric metric | jst_drug_cr      | JST_DRUG_CR      | number        | number        |
| Yes      | numeric metric | jst_mnslghtr     | JST_MNSLGHTR     | number        | number        |
| Yes      | numeric metric | jst_murder       | JST_MURDER       | number        | number        |
| Yes      | numeric metric | jst_othcrime     | JST_OTHCRIME     | number        | number        |
| Yes      | numeric metric | jst_othpropcr    | JST_OTHPROPCR    | number        | number        |
| Yes      | numeric metric | jst_robbery      | JST_ROBBERY      | number        | number        |
| Yes      | numeric metric | jst_sexcr        | JST_SEXCR        | number        | number        |
| Yes      | numeric metric | jst_total        | JST_TOTAL        | number        | number        |
| Yes      | numeric metric | jst_unknown      | JST_UNKNOWN      | number        | number        |
| Yes      | numeric metric | ajs_assault      | AJS_ASSAULT      | number        | number        |
| Yes      | numeric metric | ajs_avg_sent     | AJS_AVG_SENT     | number        | number        |
| Yes      | numeric metric | ajs_burglary     | AJS_BURGLARY     | number        | number        |
| Yes      | numeric metric | ajs_drug_cr      | AJS_DRUG_CR      | number        | number        |
| Yes      | numeric metric | ajs_mnslghtr     | AJS_MNSLGHTR     | number        | number        |
| Yes      | numeric metric | ajs_murder       | AJS_MURDER       | number        | number        |
| Yes      | numeric metric | ajs_othcrime     | AJS_OTHCRIME     | number        | number        |
| Yes      | numeric metric | ajs_othpropcr    | AJS_OTHPROPCR    | number        | number        |
| Yes      | numeric metric | ajs_robbery      | AJS_ROBBERY      | number        | number        |
| Yes      | numeric metric | ajs_sexcr        | AJS_SEXCR        | number        | number        |
| Yes      | numeric metric | ajs_unknown      | AJS_UNKNOWN      | number        | number        |
| Yes      | numeric metric | pdp_new_adm      | PDP_NEW_ADM      | number        | number        |
| Yes      | numeric metric | pdp_other        | PDP_OTHER        | number        | number        |
| Yes      | numeric metric | pdp_parole_v     | PDP_PAROLE_V     | number        | number        |
| Yes      | numeric metric | pdp_readm        | PDP_READM        | number        | number        |
| Yes      | numeric metric | pdp_total        | PDP_TOTAL        | number        | number        |
| Yes      | numeric metric | pst_assault      | PST_ASSAULT      | number        | number        |
| Yes      | numeric metric | pst_burglary     | PST_BURGLARY     | number        | number        |
| Yes      | numeric metric | pst_drug_cr      | PST_DRUG_CR      | number        | number        |
| Yes      | numeric metric | pst_mnslghtr     | PST_MNSLGHTR     | number        | number        |
| Yes      | numeric metric | pst_murder       | PST_MURDER       | number        | number        |
| Yes      | numeric metric | pst_othcrime     | PST_OTHCRIME     | number        | number        |
| Yes      | numeric metric | pst_othpropcr    | PST_OTHPROPCR    | number        | number        |
| Yes      | numeric metric | pst_robbery      | PST_ROBBERY      | number        | number        |
| Yes      | numeric metric | pst_sexcr        | PST_SEXCR        | number        | number        |
| Yes      | numeric metric | pst_total        | PST_TOTAL        | number        | number        |
| Yes      | numeric metric | pst_unknown      | PST_UNKNOWN      | number        | number        |
| Yes      | numeric metric | aps_assault      | APS_ASSAULT      | number        | number        |
| Yes      | numeric metric | aps_avg_sent     | APS_AVG_SENT     | number        | number        |
| Yes      | numeric metric | aps_burglary     | APS_BURGLARY     | number        | number        |
| Yes      | numeric metric | aps_drug_cr      | APS_DRUG_CR      | number        | number        |
| Yes      | numeric metric | aps_mnslghtr     | APS_MNSLGHTR     | number        | number        |
| Yes      | numeric metric | aps_murder       | APS_MURDER       | number        | number        |
| Yes      | numeric metric | aps_othcrime     | APS_OTHCRIME     | number        | number        |
| Yes      | numeric metric | aps_othpropcr    | APS_OTHPROPCR    | number        | number        |
| Yes      | numeric metric | aps_robbery      | APS_ROBBERY      | number        | number        |
| Yes      | numeric metric | aps_sexcr        | APS_SEXCR        | number        | number        |
| Yes      | numeric metric | aps_unknown      | APS_UNKNOWN      | number        | number        |
| Yes      | numeric metric | jrr_ag_asslt     | JRR_AG_ASSLT     | number        | number        |
| Yes      | numeric metric | jrr_arson        | JRR_ARSON        | number        | number        |
| Yes      | numeric metric | jrr_burglary     | JRR_BURGLARY     | number        | number        |
| Yes      | numeric metric | jrr_drug_cr      | JRR_DRUG_CR      | number        | number        |
| Yes      | numeric metric | jrr_murder       | JRR_MURDER       | number        | number        |
| Yes      | numeric metric | jrr_mvt          | JRR_MVT          | number        | number        |
| Yes      | numeric metric | jrr_othfelcrime  | JRR_OTHFELCRIME  | number        | number        |
| Yes      | numeric metric | jrr_rape         | JRR_RAPE         | number        | number        |
| Yes      | numeric metric | jrr_robbery      | JRR_ROBBERY      | number        | number        |
| Yes      | numeric metric | jrr_theft        | JRR_THEFT        | number        | number        |
| Yes      | numeric metric | jrr_total        | JRR_TOTAL        | number        | number        |
| Yes      | numeric metric | jad_doc_adm      | JAD_DOC_ADM      | number        | number        |
| Yes      | numeric metric | jad_new_adm      | JAD_NEW_ADM      | number        | number        |
| Yes      | numeric metric | jad_readm        | JAD_READM        | number        | number        |
| Yes      | numeric metric | jad_parole_r     | JAD_PAROLE_R     | number        | number        |
| Yes      | numeric metric | jad_total        | JAD_TOTAL        | number        | number        |
| Yes      | numeric metric | juv_assault      | JUV_ASSAULT      | number        | number        |
| Yes      | numeric metric | juv_burglary     | JUV_BURGLARY     | number        | number        |
| Yes      | numeric metric | juv_drug_cr      | JUV_DRUG_CR      | number        | number        |
| Yes      | numeric metric | juv_g_msdmnr     | JUV_G_MSDMNR     | number        | number        |
| Yes      | numeric metric | juv_mnslghtr     | JUV_MNSLGHTR     | number        | number        |
| Yes      | numeric metric | juv_msdmnr       | JUV_MSDMNR       | number        | number        |
| Yes      | numeric metric | juv_murder       | JUV_MURDER       | number        | number        |
| Yes      | numeric metric | juv_othfelcrime  | JUV_OTHFELCRIME  | number        | number        |
| Yes      | numeric metric | juv_othpropcr    | JUV_OTHPROPCR    | number        | number        |
| Yes      | numeric metric | juv_robbery      | JUV_ROBBERY      | number        | number        |
| Yes      | numeric metric | juv_sexcr        | JUV_SEXCR        | number        | number        |
| Yes      | numeric metric | juv_total        | JUV_TOTAL        | number        | number        |
| Yes      | numeric metric | min_assault      | MIN_ASSAULT      | number        | number        |
| Yes      | numeric metric | min_avg_min_disp | MIN_AVG_MIN_DISP | number        | number        |
| Yes      | numeric metric | min_burglary     | MIN_BURGLARY     | number        | number        |
| Yes      | numeric metric | min_drug_cr      | MIN_DRUG_CR      | number        | number        |
| Yes      | numeric metric | min_g_msdmnr     | MIN_G_MSDMNR     | number        | number        |
| Yes      | numeric metric | min_mnslghtr     | MIN_MNSLGHTR     | number        | number        |
| Yes      | numeric metric | min_msdmnr       | MIN_MSDMNR       | number        | number        |
| Yes      | numeric metric | min_murder       | MIN_MURDER       | number        | number        |
| Yes      | numeric metric | min_othfelcrime  | MIN_OTHFELCRIME  | number        | number        |
| Yes      | numeric metric | min_othpropcr    | MIN_OTHPROPCR    | number        | number        |
| Yes      | numeric metric | min_robbery      | MIN_ROBBERY      | number        | number        |
| Yes      | numeric metric | min_sexcr        | MIN_SEXCR        | number        | number        |
| Yes      | numeric metric | max_assault      | MAX_ASSAULT      | number        | number        |
| Yes      | numeric metric | max_avg_max_disp | MAX_AVG_MAX_DISP | number        | number        |
| Yes      | numeric metric | max_burglary     | MAX_BURGLARY     | number        | number        |
| Yes      | numeric metric | max_drug_cr      | MAX_DRUG_CR      | number        | number        |
| Yes      | numeric metric | max_g_msdmnr     | MAX_G_MSDMNR     | number        | number        |
| Yes      | numeric metric | max_mnslghtr     | MAX_MNSLGHTR     | number        | number        |
| Yes      | numeric metric | max_msdmnr       | MAX_MSDMNR       | number        | number        |
| Yes      | numeric metric | max_murder       | MAX_MURDER       | number        | number        |
| Yes      | numeric metric | max_othfelcrime  | MAX_OTHFELCRIME  | number        | number        |
| Yes      | numeric metric | max_othpropcr    | MAX_OTHPROPCR    | number        | number        |
| Yes      | numeric metric | max_robbery      | MAX_ROBBERY      | number        | number        |
| Yes      | numeric metric | max_sexcr        | MAX_SEXCR        | number        | number        |
| Yes      | numeric metric | pop_total        | POP_TOTAL        | number        | number        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:3vxk-ghwr d:1990-01-01T00:00:00.000Z t:county=ADAMS m:aps_robbery=51 m:scf_assault=13 m:juv_sexcr=0 m:jrr_ag_asslt=0 m:ajs_mnslghtr=3 m:juv_robbery=0 m:ucr_ag_asslt=80 m:juv_g_msdmnr=0 m:max_othpropcr=0 m:max_sexcr=0 m:ucr_arson=3 m:max_robbery=0 m:aps_othcrime=14 m:ucr_theft=464 m:max_mnslghtr=0 m:pst_unknown=0 m:pop_f_12to17=716 m:ucr_rape=14 m:max_drug_cr=0 m:juv_murder=0 m:jad_readm=0 m:pst_robbery=1 m:min_robbery=0 m:max_burglary=0 m:ajs_robbery=3 m:pdp_readm=1 m:jdp_othradp=1 m:ajs_drug_cr=1.4 m:jad_total=0 m:pop_m_40up=2405 m:jrr_arson=0 m:jad_parole_r=0 m:aps_mnslghtr=0 m:aps_assault=18.4 m:arr_arson=1 m:pst_mnslghtr=0 m:ucr_robbery=4 m:juv_msdmnr=0 m:min_burglary=0 m:scf_drug_cr=32 m:scf_othfelon=41 m:ajs_othpropcr=1.7 m:arr_murder=1 m:pst_assault=2 m:juv_drug_cr=0 m:max_othfelcrime=0 m:jrr_murder=0 m:jrr_robbery=0 m:jst_total=68 m:arr_othcrime=1288 m:max_avg_max_disp=0 m:ajs_othcrime=1.7 m:arr_mvt=1 m:min_othpropcr=0 m:ajs_assault=1.6 m:min_othfelcrime=0 m:jst_burglary=6 m:jst_mnslghtr=1 m:pdp_other=0 m:ajs_burglary=3.5 m:jrr_theft=0 m:jad_doc_adm=0 m:jst_robbery=1 m:jst_murder=0 m:ajs_murder=0 m:jst_othpropcr=19 m:pop_total=13603 m:jrr_rape=0 m:scf_total=151 m:pop_f_0to11=1547 m:juv_assault=0 m:juv_total=0 m:pop_f_18to39=2015 m:max_assault=0 m:scf_robbery=1 m:jrr_othfelcrime=0 m:jdp_pre_adp=6 m:jrr_drug_cr=0 m:max_murder=0 m:pst_drug_cr=3 m:arr_total=1398 m:juv_mnslghtr=0 m:pst_othpropcr=0 m:pop_m_18to39=2067 m:aps_drug_cr=16.3 m:arr_theft=54 m:pop_m_12to17=761 m:min_drug_cr=0 m:max_msdmnr=0 m:ajs_unknown=0 m:pdp_total=12 m:min_g_msdmnr=0 m:max_g_msdmnr=0 m:ucr_murder=3 m:pst_burglary=2 m:ajs_avg_sent=1.9 m:ucr_total=724 m:pst_total=12 m:min_mnslghtr=0 m:jst_assault=8 m:jrr_burglary=0 m:pdp_new_adm=11 m:jst_othcrime=4 m:pop_f_total=6745 m:scf_homicide=3 m:min_assault=0 m:arr_robbery=1 m:scf_sexcr=10 m:pop_f_40up=2467 m:jrr_total=0 m:aps_sexcr=31.3 m:arr_rape=1 m:juv_othfelcrime=0 m:ucr_mvt=20 m:pst_othcrime=1 m:jrr_mvt=0 m:pop_m_total=6858 m:aps_avg_sent=23.7 m:ucr_burglary=136 m:jdp_totaladp=17 m:aps_othpropcr=0 m:jst_sexcr=4 m:scf_propcr=51 m:min_msdmnr=0 m:min_avg_min_disp=0 m:jad_new_adm=0 m:juv_burglary=0 m:jdp_post_adp=10 m:aps_murder=0 m:juv_othpropcr=0 m:jst_unknown=0 m:min_sexcr=0 m:aps_unknown=0 m:pop_m_0to11=1625 m:pdp_parole_v=1 m:ajs_sexcr=3.1 m:jdp_capacity=20 m:aps_burglary=20 m:arr_drug_cr=27 m:jst_drug_cr=25 m:pst_sexcr=3 m:pst_murder=0 m:arr_burglary=10 m:min_murder=0 m:arr_ag_asslt=14

series e:3vxk-ghwr d:1991-01-01T00:00:00.000Z t:county=ADAMS m:aps_robbery=0 m:scf_assault=15 m:juv_sexcr=0 m:jrr_ag_asslt=0 m:ajs_mnslghtr=0 m:juv_robbery=0 m:ucr_ag_asslt=52 m:juv_g_msdmnr=0 m:max_othpropcr=0 m:max_sexcr=0 m:ucr_arson=0 m:max_robbery=0 m:aps_othcrime=14.5 m:ucr_theft=516 m:max_mnslghtr=0 m:pst_unknown=0 m:pop_f_12to17=725 m:ucr_rape=6 m:max_drug_cr=0 m:juv_murder=0 m:jad_readm=0 m:pst_robbery=0 m:min_robbery=0 m:max_burglary=0 m:ajs_robbery=0 m:pdp_readm=2 m:jdp_othradp=3 m:ajs_drug_cr=1.4 m:jad_total=0 m:pop_m_40up=2425 m:jrr_arson=0 m:jad_parole_r=0 m:aps_mnslghtr=0 m:aps_assault=17.5 m:arr_arson=0 m:pst_mnslghtr=0 m:ucr_robbery=2 m:juv_msdmnr=0 m:min_burglary=0 m:scf_drug_cr=49 m:scf_othfelon=31 m:ajs_othpropcr=1.5 m:arr_murder=1 m:pst_assault=2 m:juv_drug_cr=0 m:max_othfelcrime=0 m:jrr_murder=0 m:jrr_robbery=0 m:jst_total=60 m:arr_othcrime=1365 m:max_avg_max_disp=0 m:ajs_othcrime=2.4 m:arr_mvt=4 m:min_othpropcr=0 m:ajs_assault=3 m:min_othfelcrime=0 m:jst_burglary=9 m:jst_mnslghtr=0 m:pdp_other=0 m:ajs_burglary=2 m:jrr_theft=0 m:jad_doc_adm=0 m:jst_robbery=0 m:jst_murder=0 m:ajs_murder=0 m:jst_othpropcr=15 m:pop_total=13798 m:jrr_rape=0 m:scf_total=155 m:pop_f_0to11=1582 m:juv_assault=0 m:juv_total=0 m:pop_f_18to39=2027 m:max_assault=0 m:scf_robbery=0 m:jrr_othfelcrime=0 m:jdp_pre_adp=9 m:jrr_drug_cr=0 m:max_murder=0 m:pst_drug_cr=0 m:arr_total=1538 m:juv_mnslghtr=0 m:pst_othpropcr=1 m:pop_m_18to39=2101 m:aps_drug_cr=0 m:arr_theft=72 m:pop_m_12to17=779 m:min_drug_cr=0 m:max_msdmnr=0 m:ajs_unknown=0 m:pdp_total=8 m:min_g_msdmnr=0 m:max_g_msdmnr=0 m:ucr_murder=0 m:pst_burglary=0 m:ajs_avg_sent=1.7 m:ucr_total=743 m:pst_total=8 m:min_mnslghtr=0 m:jst_assault=5 m:jrr_burglary=0 m:pdp_new_adm=6 m:jst_othcrime=6 m:pop_f_total=6827 m:scf_homicide=0 m:min_assault=0 m:arr_robbery=0 m:scf_sexcr=13 m:pop_f_40up=2488 m:jrr_total=0 m:aps_sexcr=20 m:arr_rape=6 m:juv_othfelcrime=0 m:ucr_mvt=24 m:pst_othcrime=2 m:jrr_mvt=0 m:pop_m_total=6971 m:aps_avg_sent=97.1 m:ucr_burglary=143 m:jdp_totaladp=23 m:aps_othpropcr=12 m:jst_sexcr=4 m:scf_propcr=47 m:min_msdmnr=0 m:min_avg_min_disp=0 m:jad_new_adm=0 m:juv_burglary=0 m:jdp_post_adp=11 m:aps_murder=340.5 m:juv_othpropcr=0 m:jst_unknown=0 m:min_sexcr=0 m:aps_unknown=0 m:pop_m_0to11=1666 m:pdp_parole_v=4 m:ajs_sexcr=1.7 m:jdp_capacity=20 m:aps_burglary=0 m:arr_drug_cr=45 m:jst_drug_cr=21 m:pst_sexcr=1 m:pst_murder=2 m:arr_burglary=12 m:min_murder=0 m:arr_ag_asslt=33

series e:3vxk-ghwr d:1992-01-01T00:00:00.000Z t:county=ADAMS m:aps_robbery=0 m:scf_assault=10 m:juv_sexcr=0 m:jrr_ag_asslt=0 m:ajs_mnslghtr=0 m:juv_robbery=0 m:ucr_ag_asslt=28 m:juv_g_msdmnr=0 m:max_othpropcr=0 m:max_sexcr=0 m:ucr_arson=9 m:max_robbery=0 m:aps_othcrime=0 m:ucr_theft=561 m:max_mnslghtr=0 m:pst_unknown=0 m:pop_f_12to17=749 m:ucr_rape=13 m:max_drug_cr=0 m:juv_murder=0 m:jad_readm=0 m:pst_robbery=0 m:min_robbery=0 m:max_burglary=0 m:ajs_robbery=0 m:pdp_readm=0 m:jdp_othradp=4 m:ajs_drug_cr=1.5 m:jad_total=0 m:pop_m_40up=2475 m:jrr_arson=0 m:jad_parole_r=0 m:aps_mnslghtr=0 m:aps_assault=14.5 m:arr_arson=0 m:pst_mnslghtr=0 m:ucr_robbery=2 m:juv_msdmnr=0 m:min_burglary=0 m:scf_drug_cr=47 m:scf_othfelon=39 m:ajs_othpropcr=1.9 m:arr_murder=1 m:pst_assault=2 m:juv_drug_cr=0 m:max_othfelcrime=0 m:jrr_murder=0 m:jrr_robbery=0 m:jst_total=76 m:arr_othcrime=962 m:max_avg_max_disp=0 m:ajs_othcrime=3.7 m:arr_mvt=7 m:min_othpropcr=0 m:ajs_assault=2.1 m:min_othfelcrime=0 m:jst_burglary=4 m:jst_mnslghtr=0 m:pdp_other=0 m:ajs_burglary=2.3 m:jrr_theft=0 m:jad_doc_adm=0 m:jst_robbery=0 m:jst_murder=0 m:ajs_murder=0 m:jst_othpropcr=27 m:pop_total=14143 m:jrr_rape=0 m:scf_total=183 m:pop_f_0to11=1631 m:juv_assault=0 m:juv_total=0 m:pop_f_18to39=2061 m:max_assault=0 m:scf_robbery=1 m:jrr_othfelcrime=0 m:jdp_pre_adp=7 m:jrr_drug_cr=0 m:max_murder=0 m:pst_drug_cr=2 m:arr_total=1175 m:juv_mnslghtr=0 m:pst_othpropcr=1 m:pop_m_18to39=2152 m:aps_drug_cr=23.5 m:arr_theft=110 m:pop_m_12to17=808 m:min_drug_cr=0 m:max_msdmnr=0 m:ajs_unknown=0 m:pdp_total=5 m:min_g_msdmnr=0 m:max_g_msdmnr=0 m:ucr_murder=2 m:pst_burglary=2 m:ajs_avg_sent=2.1 m:ucr_total=824 m:pst_total=8 m:min_mnslghtr=0 m:jst_assault=8 m:jrr_burglary=0 m:pdp_new_adm=5 m:jst_othcrime=8 m:pop_f_total=6985 m:scf_homicide=3 m:min_assault=0 m:arr_robbery=0 m:scf_sexcr=12 m:pop_f_40up=2542 m:jrr_total=0 m:aps_sexcr=20 m:arr_rape=11 m:juv_othfelcrime=0 m:ucr_mvt=38 m:pst_othcrime=0 m:jrr_mvt=0 m:pop_m_total=7158 m:aps_avg_sent=18.3 m:ucr_burglary=171 m:jdp_totaladp=17 m:aps_othpropcr=17 m:jst_sexcr=4 m:scf_propcr=71 m:min_msdmnr=0 m:min_avg_min_disp=0 m:jad_new_adm=0 m:juv_burglary=0 m:jdp_post_adp=6 m:aps_murder=0 m:juv_othpropcr=0 m:jst_unknown=0 m:min_sexcr=0 m:aps_unknown=0 m:pop_m_0to11=1722 m:pdp_parole_v=3 m:ajs_sexcr=3.5 m:jdp_capacity=20 m:aps_burglary=16.5 m:arr_drug_cr=45 m:jst_drug_cr=25 m:pst_sexcr=1 m:pst_murder=0 m:arr_burglary=25 m:min_murder=0 m:arr_ag_asslt=14
```

## Meta Commands

```ls
metric m:pop_f_0to11 p:integer l:POP_F_0TO11 t:dataTypeName=number

metric m:pop_f_12to17 p:integer l:POP_F_12TO17 t:dataTypeName=number

metric m:pop_f_18to39 p:integer l:POP_F_18TO39 t:dataTypeName=number

metric m:pop_f_40up p:integer l:POP_F_40UP t:dataTypeName=number

metric m:pop_f_total p:integer l:POP_F_TOTAL t:dataTypeName=number

metric m:pop_m_0to11 p:integer l:POP_M_0TO11 t:dataTypeName=number

metric m:pop_m_12to17 p:integer l:POP_M_12TO17 t:dataTypeName=number

metric m:pop_m_18to39 p:integer l:POP_M_18TO39 t:dataTypeName=number

metric m:pop_m_40up p:integer l:POP_M_40UP t:dataTypeName=number

metric m:pop_m_total p:integer l:POP_M_TOTAL t:dataTypeName=number

metric m:ucr_ag_asslt p:integer l:UCR_AG_ASSLT t:dataTypeName=number

metric m:ucr_arson p:integer l:UCR_ARSON t:dataTypeName=number

metric m:ucr_burglary p:integer l:UCR_BURGLARY t:dataTypeName=number

metric m:ucr_murder p:integer l:UCR_MURDER t:dataTypeName=number

metric m:ucr_mvt p:integer l:UCR_MVT t:dataTypeName=number

metric m:ucr_rape p:integer l:UCR_RAPE t:dataTypeName=number

metric m:ucr_robbery p:integer l:UCR_ROBBERY t:dataTypeName=number

metric m:ucr_theft p:integer l:UCR_THEFT t:dataTypeName=number

metric m:ucr_total p:integer l:UCR_TOTAL t:dataTypeName=number

metric m:arr_ag_asslt p:integer l:ARR_AG_ASSLT t:dataTypeName=number

metric m:arr_arson p:integer l:ARR_ARSON t:dataTypeName=number

metric m:arr_burglary p:integer l:ARR_BURGLARY t:dataTypeName=number

metric m:arr_drug_cr p:integer l:ARR_DRUG_CR t:dataTypeName=number

metric m:arr_murder p:integer l:ARR_MURDER t:dataTypeName=number

metric m:arr_mvt p:integer l:ARR_MVT t:dataTypeName=number

metric m:arr_othcrime p:integer l:ARR_OTHCRIME t:dataTypeName=number

metric m:arr_rape p:integer l:ARR_RAPE t:dataTypeName=number

metric m:arr_robbery p:integer l:ARR_ROBBERY t:dataTypeName=number

metric m:arr_theft p:integer l:ARR_THEFT t:dataTypeName=number

metric m:arr_total p:integer l:ARR_TOTAL t:dataTypeName=number

metric m:scf_assault p:integer l:SCF_ASSAULT t:dataTypeName=number

metric m:scf_drug_cr p:integer l:SCF_DRUG_CR t:dataTypeName=number

metric m:scf_homicide p:integer l:SCF_HOMICIDE t:dataTypeName=number

metric m:scf_othfelon p:integer l:SCF_OTHFELON t:dataTypeName=number

metric m:scf_propcr p:integer l:SCF_PROPCR t:dataTypeName=number

metric m:scf_robbery p:integer l:SCF_ROBBERY t:dataTypeName=number

metric m:scf_sexcr p:integer l:SCF_SEXCR t:dataTypeName=number

metric m:scf_total p:integer l:SCF_TOTAL t:dataTypeName=number

metric m:jdp_othradp p:float l:JDP_OTHRADP t:dataTypeName=number

metric m:jdp_post_adp p:integer l:JDP_POST_ADP t:dataTypeName=number

metric m:jdp_pre_adp p:integer l:JDP_PRE_ADP t:dataTypeName=number

metric m:jdp_capacity p:integer l:JDP_CAPACITY t:dataTypeName=number

metric m:jdp_totaladp p:double l:JDP_TOTALADP t:dataTypeName=number

metric m:jst_assault p:integer l:JST_ASSAULT t:dataTypeName=number

metric m:jst_burglary p:integer l:JST_BURGLARY t:dataTypeName=number

metric m:jst_drug_cr p:integer l:JST_DRUG_CR t:dataTypeName=number

metric m:jst_mnslghtr p:integer l:JST_MNSLGHTR t:dataTypeName=number

metric m:jst_murder p:integer l:JST_MURDER t:dataTypeName=number

metric m:jst_othcrime p:integer l:JST_OTHCRIME t:dataTypeName=number

metric m:jst_othpropcr p:integer l:JST_OTHPROPCR t:dataTypeName=number

metric m:jst_robbery p:integer l:JST_ROBBERY t:dataTypeName=number

metric m:jst_sexcr p:integer l:JST_SEXCR t:dataTypeName=number

metric m:jst_total p:integer l:JST_TOTAL t:dataTypeName=number

metric m:jst_unknown p:integer l:JST_UNKNOWN t:dataTypeName=number

metric m:ajs_assault p:double l:AJS_ASSAULT t:dataTypeName=number

metric m:ajs_avg_sent p:double l:AJS_AVG_SENT t:dataTypeName=number

metric m:ajs_burglary p:double l:AJS_BURGLARY t:dataTypeName=number

metric m:ajs_drug_cr p:double l:AJS_DRUG_CR t:dataTypeName=number

metric m:ajs_mnslghtr p:double l:AJS_MNSLGHTR t:dataTypeName=number

metric m:ajs_murder p:double l:AJS_MURDER t:dataTypeName=number

metric m:ajs_othcrime p:double l:AJS_OTHCRIME t:dataTypeName=number

metric m:ajs_othpropcr p:float l:AJS_OTHPROPCR t:dataTypeName=number

metric m:ajs_robbery p:double l:AJS_ROBBERY t:dataTypeName=number

metric m:ajs_sexcr p:double l:AJS_SEXCR t:dataTypeName=number

metric m:ajs_unknown p:double l:AJS_UNKNOWN t:dataTypeName=number

metric m:pdp_new_adm p:integer l:PDP_NEW_ADM t:dataTypeName=number

metric m:pdp_other p:integer l:PDP_OTHER t:dataTypeName=number

metric m:pdp_parole_v p:integer l:PDP_PAROLE_V t:dataTypeName=number

metric m:pdp_readm p:integer l:PDP_READM t:dataTypeName=number

metric m:pdp_total p:integer l:PDP_TOTAL t:dataTypeName=number

metric m:pst_assault p:integer l:PST_ASSAULT t:dataTypeName=number

metric m:pst_burglary p:integer l:PST_BURGLARY t:dataTypeName=number

metric m:pst_drug_cr p:integer l:PST_DRUG_CR t:dataTypeName=number

metric m:pst_mnslghtr p:integer l:PST_MNSLGHTR t:dataTypeName=number

metric m:pst_murder p:integer l:PST_MURDER t:dataTypeName=number

metric m:pst_othcrime p:integer l:PST_OTHCRIME t:dataTypeName=number

metric m:pst_othpropcr p:integer l:PST_OTHPROPCR t:dataTypeName=number

metric m:pst_robbery p:integer l:PST_ROBBERY t:dataTypeName=number

metric m:pst_sexcr p:integer l:PST_SEXCR t:dataTypeName=number

metric m:pst_total p:integer l:PST_TOTAL t:dataTypeName=number

metric m:pst_unknown p:integer l:PST_UNKNOWN t:dataTypeName=number

metric m:aps_assault p:double l:APS_ASSAULT t:dataTypeName=number

metric m:aps_avg_sent p:double l:APS_AVG_SENT t:dataTypeName=number

metric m:aps_burglary p:float l:APS_BURGLARY t:dataTypeName=number

metric m:aps_drug_cr p:double l:APS_DRUG_CR t:dataTypeName=number

metric m:aps_mnslghtr p:double l:APS_MNSLGHTR t:dataTypeName=number

metric m:aps_murder p:double l:APS_MURDER t:dataTypeName=number

metric m:aps_othcrime p:double l:APS_OTHCRIME t:dataTypeName=number

metric m:aps_othpropcr p:float l:APS_OTHPROPCR t:dataTypeName=number

metric m:aps_robbery p:double l:APS_ROBBERY t:dataTypeName=number

metric m:aps_sexcr p:double l:APS_SEXCR t:dataTypeName=number

metric m:aps_unknown p:double l:APS_UNKNOWN t:dataTypeName=number

metric m:jrr_ag_asslt p:integer l:JRR_AG_ASSLT t:dataTypeName=number

metric m:jrr_arson p:integer l:JRR_ARSON t:dataTypeName=number

metric m:jrr_burglary p:integer l:JRR_BURGLARY t:dataTypeName=number

metric m:jrr_drug_cr p:integer l:JRR_DRUG_CR t:dataTypeName=number

metric m:jrr_murder p:integer l:JRR_MURDER t:dataTypeName=number

metric m:jrr_mvt p:integer l:JRR_MVT t:dataTypeName=number

metric m:jrr_othfelcrime p:integer l:JRR_OTHFELCRIME t:dataTypeName=number

metric m:jrr_rape p:integer l:JRR_RAPE t:dataTypeName=number

metric m:jrr_robbery p:integer l:JRR_ROBBERY t:dataTypeName=number

metric m:jrr_theft p:integer l:JRR_THEFT t:dataTypeName=number

metric m:jrr_total p:integer l:JRR_TOTAL t:dataTypeName=number

metric m:jad_doc_adm p:integer l:JAD_DOC_ADM t:dataTypeName=number

metric m:jad_new_adm p:integer l:JAD_NEW_ADM t:dataTypeName=number

metric m:jad_readm p:integer l:JAD_READM t:dataTypeName=number

metric m:jad_parole_r p:integer l:JAD_PAROLE_R t:dataTypeName=number

metric m:jad_total p:integer l:JAD_TOTAL t:dataTypeName=number

metric m:juv_assault p:integer l:JUV_ASSAULT t:dataTypeName=number

metric m:juv_burglary p:integer l:JUV_BURGLARY t:dataTypeName=number

metric m:juv_drug_cr p:integer l:JUV_DRUG_CR t:dataTypeName=number

metric m:juv_g_msdmnr p:integer l:JUV_G_MSDMNR t:dataTypeName=number

metric m:juv_mnslghtr p:integer l:JUV_MNSLGHTR t:dataTypeName=number

metric m:juv_msdmnr p:integer l:JUV_MSDMNR t:dataTypeName=number

metric m:juv_murder p:integer l:JUV_MURDER t:dataTypeName=number

metric m:juv_othfelcrime p:integer l:JUV_OTHFELCRIME t:dataTypeName=number

metric m:juv_othpropcr p:integer l:JUV_OTHPROPCR t:dataTypeName=number

metric m:juv_robbery p:integer l:JUV_ROBBERY t:dataTypeName=number

metric m:juv_sexcr p:integer l:JUV_SEXCR t:dataTypeName=number

metric m:juv_total p:integer l:JUV_TOTAL t:dataTypeName=number

metric m:min_assault p:float l:MIN_ASSAULT t:dataTypeName=number

metric m:min_avg_min_disp p:float l:MIN_AVG_MIN_DISP t:dataTypeName=number

metric m:min_burglary p:double l:MIN_BURGLARY t:dataTypeName=number

metric m:min_drug_cr p:double l:MIN_DRUG_CR t:dataTypeName=number

metric m:min_g_msdmnr p:float l:MIN_G_MSDMNR t:dataTypeName=number

metric m:min_mnslghtr p:double l:MIN_MNSLGHTR t:dataTypeName=number

metric m:min_msdmnr p:float l:MIN_MSDMNR t:dataTypeName=number

metric m:min_murder p:integer l:MIN_MURDER t:dataTypeName=number

metric m:min_othfelcrime p:double l:MIN_OTHFELCRIME t:dataTypeName=number

metric m:min_othpropcr p:double l:MIN_OTHPROPCR t:dataTypeName=number

metric m:min_robbery p:double l:MIN_ROBBERY t:dataTypeName=number

metric m:min_sexcr p:double l:MIN_SEXCR t:dataTypeName=number

metric m:max_assault p:float l:MAX_ASSAULT t:dataTypeName=number

metric m:max_avg_max_disp p:float l:MAX_AVG_MAX_DISP t:dataTypeName=number

metric m:max_burglary p:double l:MAX_BURGLARY t:dataTypeName=number

metric m:max_drug_cr p:double l:MAX_DRUG_CR t:dataTypeName=number

metric m:max_g_msdmnr p:float l:MAX_G_MSDMNR t:dataTypeName=number

metric m:max_mnslghtr p:double l:MAX_MNSLGHTR t:dataTypeName=number

metric m:max_msdmnr p:float l:MAX_MSDMNR t:dataTypeName=number

metric m:max_murder p:integer l:MAX_MURDER t:dataTypeName=number

metric m:max_othfelcrime p:float l:MAX_OTHFELCRIME t:dataTypeName=number

metric m:max_othpropcr p:double l:MAX_OTHPROPCR t:dataTypeName=number

metric m:max_robbery p:float l:MAX_ROBBERY t:dataTypeName=number

metric m:max_sexcr p:double l:MAX_SEXCR t:dataTypeName=number

metric m:pop_total p:integer l:POP_TOTAL t:dataTypeName=number

entity e:3vxk-ghwr l:"Criminal Justice" t:url=https://data.wa.gov/api/views/3vxk-ghwr

property e:3vxk-ghwr t:meta.view v:id=3vxk-ghwr v:category="Public Safety" v:averageRating=0 v:name="Criminal Justice"

property e:3vxk-ghwr t:meta.view.owner v:id=7q3z-xwey v:screenName=Stephen v:displayName=Stephen

property e:3vxk-ghwr t:meta.view.tableauthor v:id=7q3z-xwey v:screenName=Stephen v:roleName=publisher v:displayName=Stephen
```

## Top Records

```ls
| year                | county | pop_f_0to11 | pop_f_12to17 | pop_f_18to39 | pop_f_40up | pop_f_total | pop_m_0to11 | pop_m_12to17 | pop_m_18to39 | pop_m_40up | pop_m_total | ucr_ag_asslt | ucr_arson | ucr_burglary | ucr_murder | ucr_mvt | ucr_rape | ucr_robbery | ucr_theft | ucr_total | arr_ag_asslt | arr_arson | arr_burglary | arr_drug_cr | arr_murder | arr_mvt | arr_othcrime | arr_rape | arr_robbery | arr_theft | arr_total | scf_assault | scf_drug_cr | scf_homicide | scf_othfelon | scf_propcr | scf_robbery | scf_sexcr | scf_total | jdp_othradp | jdp_post_adp | jdp_pre_adp | jdp_capacity | jdp_totaladp | jst_assault | jst_burglary | jst_drug_cr | jst_mnslghtr | jst_murder | jst_othcrime | jst_othpropcr | jst_robbery | jst_sexcr | jst_total | jst_unknown | ajs_assault | ajs_avg_sent | ajs_burglary | ajs_drug_cr | ajs_mnslghtr | ajs_murder | ajs_othcrime | ajs_othpropcr | ajs_robbery | ajs_sexcr | ajs_unknown | pdp_new_adm | pdp_other | pdp_parole_v | pdp_readm | pdp_total | pst_assault | pst_burglary | pst_drug_cr | pst_mnslghtr | pst_murder | pst_othcrime | pst_othpropcr | pst_robbery | pst_sexcr | pst_total | pst_unknown | aps_assault | aps_avg_sent | aps_burglary | aps_drug_cr | aps_mnslghtr | aps_murder | aps_othcrime | aps_othpropcr | aps_robbery | aps_sexcr | aps_unknown | jrr_ag_asslt | jrr_arson | jrr_burglary | jrr_drug_cr | jrr_murder | jrr_mvt | jrr_othfelcrime | jrr_rape | jrr_robbery | jrr_theft | jrr_total | jad_doc_adm | jad_new_adm | jad_readm | jad_parole_r | jad_total | juv_assault | juv_burglary | juv_drug_cr | juv_g_msdmnr | juv_mnslghtr | juv_msdmnr | juv_murder | juv_othfelcrime | juv_othpropcr | juv_robbery | juv_sexcr | juv_total | min_assault | min_avg_min_disp | min_burglary | min_drug_cr | min_g_msdmnr | min_mnslghtr | min_msdmnr | min_murder | min_othfelcrime | min_othpropcr | min_robbery | min_sexcr | max_assault | max_avg_max_disp | max_burglary | max_drug_cr | max_g_msdmnr | max_mnslghtr | max_msdmnr | max_murder | max_othfelcrime | max_othpropcr | max_robbery | max_sexcr | pop_total | 
| =================== | ====== | =========== | ============ | ============ | ========== | =========== | =========== | ============ | ============ | ========== | =========== | ============ | ========= | ============ | ========== | ======= | ======== | =========== | ========= | ========= | ============ | ========= | ============ | =========== | ========== | ======= | ============ | ======== | =========== | ========= | ========= | =========== | =========== | ============ | ============ | ========== | =========== | ========= | ========= | =========== | ============ | =========== | ============ | ============ | =========== | ============ | =========== | ============ | ========== | ============ | ============= | =========== | ========= | ========= | =========== | =========== | ============ | ============ | =========== | ============ | ========== | ============ | ============= | =========== | ========= | =========== | =========== | ========= | ============ | ========= | ========= | =========== | ============ | =========== | ============ | ========== | ============ | ============= | =========== | ========= | ========= | =========== | =========== | ============ | ============ | =========== | ============ | ========== | ============ | ============= | =========== | ========= | =========== | ============ | ========= | ============ | =========== | ========== | ======= | =============== | ======== | =========== | ========= | ========= | =========== | =========== | ========= | ============ | ========= | =========== | ============ | =========== | ============ | ============ | ========== | ========== | =============== | ============= | =========== | ========= | ========= | =========== | ================ | ============ | =========== | ============ | ============ | ========== | ========== | =============== | ============= | =========== | ========= | =========== | ================ | ============ | =========== | ============ | ============ | ========== | ========== | =============== | ============= | =========== | ========= | ========= | 
| 1990-01-01T00:00:00 | ADAMS  | 1547        | 716          | 2015         | 2467       | 6745        | 1625        | 761          | 2067         | 2405       | 6858        | 80           | 3         | 136          | 3          | 20      | 14       | 4           | 464       | 724       | 14           | 1         | 10           | 27          | 1          | 1       | 1288         | 1        | 1           | 54        | 1398      | 13          | 32          | 3            | 41           | 51         | 1           | 10        | 151       | 1           | 10           | 6           | 20           | 17           | 8           | 6            | 25          | 1            | 0          | 4            | 19            | 1           | 4         | 68        | 0           | 1.6         | 1.9          | 3.5          | 1.4         | 3            | 0          | 1.7          | 1.7           | 3           | 3.1       | 0           | 11          | 0         | 1            | 1         | 12        | 2           | 2            | 3           | 0            | 0          | 1            | 0             | 1           | 3         | 12        | 0           | 18.4        | 23.7         | 20           | 16.3        | 0            | 0          | 14           | 0             | 51          | 31.3      | 0           | 0            | 0         | 0            | 0           | 0          | 0       | 0               | 0        | 0           | 0         | 0         | 0           | 0           | 0         | 0            | 0         | 0           | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 13603     | 
| 1991-01-01T00:00:00 | ADAMS  | 1582        | 725          | 2027         | 2488       | 6827        | 1666        | 779          | 2101         | 2425       | 6971        | 52           | 0         | 143          | 0          | 24      | 6        | 2           | 516       | 743       | 33           | 0         | 12           | 45          | 1          | 4       | 1365         | 6        | 0           | 72        | 1538      | 15          | 49          | 0            | 31           | 47         | 0           | 13        | 155       | 3           | 11           | 9           | 20           | 23           | 5           | 9            | 21          | 0            | 0          | 6            | 15            | 0           | 4         | 60        | 0           | 3           | 1.7          | 2            | 1.4         | 0            | 0          | 2.4          | 1.5           | 0           | 1.7       | 0           | 6           | 0         | 4            | 2         | 8         | 2           | 0            | 0           | 0            | 2          | 2            | 1             | 0           | 1         | 8         | 0           | 17.5        | 97.1         | 0            | 0           | 0            | 340.5      | 14.5         | 12            | 0           | 20        | 0           | 0            | 0         | 0            | 0           | 0          | 0       | 0               | 0        | 0           | 0         | 0         | 0           | 0           | 0         | 0            | 0         | 0           | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 13798     | 
| 1992-01-01T00:00:00 | ADAMS  | 1631        | 749          | 2061         | 2542       | 6985        | 1722        | 808          | 2152         | 2475       | 7158        | 28           | 9         | 171          | 2          | 38      | 13       | 2           | 561       | 824       | 14           | 0         | 25           | 45          | 1          | 7       | 962          | 11       | 0           | 110       | 1175      | 10          | 47          | 3            | 39           | 71         | 1           | 12        | 183       | 4           | 6            | 7           | 20           | 17           | 8           | 4            | 25          | 0            | 0          | 8            | 27            | 0           | 4         | 76        | 0           | 2.1         | 2.1          | 2.3          | 1.5         | 0            | 0          | 3.7          | 1.9           | 0           | 3.5       | 0           | 5           | 0         | 3            | 0         | 5         | 2           | 2            | 2           | 0            | 0          | 0            | 1             | 0           | 1         | 8         | 0           | 14.5        | 18.3         | 16.5         | 23.5        | 0            | 0          | 0            | 17            | 0           | 20        | 0           | 0            | 0         | 0            | 0           | 0          | 0       | 0               | 0        | 0           | 0         | 0         | 0           | 0           | 0         | 0            | 0         | 0           | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 14143     | 
| 1993-01-01T00:00:00 | ADAMS  | 1677        | 778          | 2095         | 2611       | 7167        | 1776        | 845          | 2207         | 2539       | 7368        | 45           | 6         | 141          | 0          | 33      | 3        | 3           | 660       | 891       | 29           | 0         | 6            | 37          | 0          | 10      | 915          | 2        | 4           | 126       | 1129      | 19          | 34          | 2            | 29           | 57         | 3           | 12        | 156       | 3           | 6            | 8           | 20           | 17           | 11          | 13           | 19          | 0            | 0          | 4            | 20            | 0           | 2         | 69        | 0           | 3.8         | 2.8          | 4.8          | 1.3         | 0            | 0          | 2            | 2.4           | 0           | 3.1       | 0           | 10          | 0         | 0            | 2         | 12        | 0           | 3            | 2           | 0            | 0          | 0            | 1             | 1           | 4         | 11        | 0           | 0           | 54.3         | 37           | 27.5        | 0            | 0          | 0            | 14            | 41          | 94        | 0           | 0            | 0         | 0            | 0           | 0          | 0       | 0               | 0        | 0           | 0         | 0         | 0           | 0           | 0         | 0            | 0         | 0           | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 14535     | 
| 1994-01-01T00:00:00 | ADAMS  | 1731        | 809          | 2142         | 2704       | 7389        | 1836        | 887          | 2274         | 2620       | 7617        | 57           | 7         | 132          | 0          | 54      | 5        | 5           | 628       | 888       | 36           | 1         | 12           | 37          | 0          | 6       | 899          | 5        | 4           | 47        | 1047      | 22          | 29          | 3            | 21           | 39         | 4           | 11        | 129       | 4           | 7            | 6           | 20           | 17           | 9           | 2            | 24          | 1            | 0          | 4            | 30            | 2           | 1         | 73        | 0           | 3           | 2.4          | 7.5          | 2.4         | 3            | 0          | 1.9          | 2.2           | 0.7         | 2         | 0           | 7           | 0         | 0            | 4         | 11        | 2           | 1            | 2           | 1            | 1          | 1            | 4             | 0           | 2         | 14        | 0           | 32.5        | 50.2         | 24.8         | 32.5        | 27           | 164        | 17           | 18            | 0           | 134       | 0           | 0            | 0         | 0            | 0           | 0          | 0       | 0               | 0        | 0           | 0         | 0         | 0           | 0           | 0         | 0            | 0         | 0           | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 15006     | 
| 1995-01-01T00:00:00 | ADAMS  | 1764        | 836          | 2174         | 2778       | 7555        | 1874        | 924          | 2323         | 2685       | 7811        | 34           | 3         | 150          | 4          | 35      | 5        | 3           | 733       | 967       | 26           | 1         | 23           | 38          | 2          | 4       | 939          | 1        | 1           | 134       | 1169      | 15          | 49          | 2            | 33           | 59         | 0           | 6         | 164       | 5           | 5            | 7           | 20           | 17           | 8           | 1            | 15          | 1            | 0          | 3            | 10            | 0           | 0         | 38        | 0           | 2.8         | 1.9          | 3            | 1.6         | 3            | 0          | 2.3          | 1.3           | 0           | 0         | 0           | 6           | 0         | 1            | 2         | 8         | 2           | 3            | 2           | 0            | 0          | 0            | 0             | 0           | 4         | 11        | 0           | 18.5        | 34.7         | 31           | 22          | 0            | 0          | 0            | 0             | 0           | 52        | 0           | 0            | 0         | 0            | 0           | 0          | 0       | 0               | 0        | 0           | 0         | 0         | 0           | 0           | 0         | 0            | 0         | 0           | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 15366     | 
| 1996-01-01T00:00:00 | ADAMS  | 1786        | 860          | 2199         | 2845       | 7696        | 1902        | 960          | 2366         | 2746       | 7978        | 42           | 11        | 142          | 1          | 43      | 6        | 5           | 653       | 903       | 26           | 0         | 20           | 59          | 1          | 3       | 883          | 4        | 5           | 77        | 1078      | 25          | 38          | 1            | 23           | 34         | 2           | 12        | 135       | 6           | 6            | 10          | 20           | 22           | 15          | 7            | 25          | 0            | 0          | 2            | 25            | 0           | 1         | 75        | 0           | 2.8         | 2            | 3            | 1.7         | 0            | 0          | 3            | 1.5           | 0           | 1         | 0           | 15          | 0         | 0            | 5         | 20        | 4           | 4            | 5           | 1            | 1          | 2            | 4             | 1           | 4         | 26        | 0           | 18          | 44.8         | 24.3         | 27.2        | 60           | 387        | 12           | 13            | 41          | 73.8      | 0           | 0            | 0         | 0            | 0           | 0          | 0       | 0               | 0        | 0           | 0         | 0         | 0           | 0           | 0         | 0            | 0         | 0           | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 15674     | 
| 1997-01-01T00:00:00 | ADAMS  | 1815        | 878          | 2231         | 2915       | 7841        | 1939        | 987          | 2418         | 2801       | 8148        | 46           | 8         | 185          | 1          | 36      | 9        | 2           | 479       | 766       | 24           | 2         | 14           | 55          | 0          | 3       | 787          | 2        | 0           | 54        | 941       | 22          | 43          | 0            | 40           | 50         | 0           | 5         | 160       | 6           | 6            | 8           | 20           | 20           | 8           | 4            | 19          | 0            | 0          | 5            | 15            | 0           | 0         | 51        | 0           | 3.6         | 2.5          | 6.8          | 1.8         | 0            | 0          | 3.4          | 1.3           | 0           | 0         | 0           | 22          | 0         | 0            | 6         | 28        | 6           | 3            | 14          | 1            | 0          | 0            | 3             | 0           | 4         | 31        | 0           | 35.8        | 42.3         | 21           | 19.9        | 54           | 0          | 0            | 13.7          | 0           | 164.8     | 0           | 0            | 0         | 0            | 0           | 0          | 0       | 0               | 0        | 0           | 0         | 0         | 0           | 0           | 0         | 0            | 0         | 0           | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 15989     | 
| 1998-01-01T00:00:00 | ADAMS  | 1816        | 876          | 2233         | 2949       | 7880        | 1943        | 994          | 2442         | 2829       | 8211        | 32           | 15        | 205          | 0          | 37      | 10       | 5           | 447       | 751       | 21           | 0         | 26           | 46          | 0          | 8       | 786          | 3        | 5           | 36        | 931       | 26          | 31          | 0            | 28           | 55         | 5           | 2         | 147       | 1           | 8            | 14          | 28           | 23           | 14          | 6            | 17          | 0            | 0          | 7            | 27            | 1           | 1         | 73        | 0           | 3           | 2.2          | 1.7          | 1.8         | 0            | 0          | 3.6          | 1.7           | 6           | 1         | 0           | 13          | 0         | 1            | 8         | 21        | 4           | 6            | 5           | 0            | 0          | 2            | 8             | 2           | 1         | 28        | 0           | 29.3        | 22.7         | 21.2         | 22.4        | 0            | 0          | 19.5         | 21.8          | 23          | 20        | 0           | 0            | 0         | 0            | 0           | 0          | 0       | 0               | 0        | 0           | 0         | 0         | 0           | 0           | 0         | 0            | 0         | 0           | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 16091     | 
| 1999-01-01T00:00:00 | ADAMS  | 1815        | 873          | 2246         | 2981       | 7918        | 1945        | 998          | 2473         | 2853       | 8272        | 42           | 6         | 168          | 1          | 26      | 4        | 4           | 411       | 662       | 18           | 1         | 28           | 45          | 0          | 2       | 689          | 0        | 0           | 29        | 812       | 29          | 31          | 3            | 12           | 55         | 0           | 10        | 140       | 1           | 10           | 11          | 28           | 22           | 7           | 3            | 8           | 0            | 0          | 6            | 12            | 0           | 1         | 37        | 0           | 5.6         | 2.6          | 2.3          | 2.4         | 0            | 0          | 1.6          | 1.7           | 0           | 1         | 0           | 12          | 0         | 0            | 4         | 16        | 6           | 8            | 5           | 0            | 0          | 1            | 1             | 0           | 2         | 23        | 0           | 23.5        | 31.8         | 29.9         | 18          | 0            | 0          | 43           | 12            | 0           | 103       | 0           | 0            | 0         | 0            | 0           | 0          | 0       | 0               | 0        | 0           | 0         | 0         | 0           | 0           | 0         | 0            | 0         | 0           | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 0           | 0                | 0            | 0           | 0            | 0            | 0          | 0          | 0               | 0             | 0           | 0         | 16190     | 
```