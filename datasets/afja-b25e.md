# NNDSS - Table II. Giardiasis to Haemophilus influenza

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-giardiasis-to-haemophilus-influenza) |
| Metadata | [Link](https://data.cdc.gov/api/views/afja-b25e) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/afja-b25e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/afja-b25e/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | afja-b25e |
| Name | NNDSS - Table II. Giardiasis to Haemophilus influenza |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2016, mmwr, nndss, wonder, nedss, netss, giardiasis, gonorrhea, haemophilus influenzae |
| Created | 2016-01-11T23:44:09Z |
| Publication Date | 2017-01-05T16:58:16Z |

## Description

NNDSS - Table II. Giardiasis to Haemophilus influenza - 2016.  In this Table, provisional* cases of selected? notifiable diseases (?1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.
Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
C.N.M.I.: Commonwealth of Northern Mariana Islands. 
U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.  NP:  Nationally notifiable but not published.    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum.

* Case counts for reporting year 2016 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly. 
? Three low incidence conditions, rubella, rubella congenital, and tetanus, are in Table II to facilitate case count verification with reporting jurisdictions. 
? Data for H. influenzae (age <5 years for serotype b, nonserotype b, and unknown serotype) are available in Table I.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                        | Name                                                                                    | Data Type | Render Type |
| ======== | ============== | ================================================================================= | ======================================================================================= | ========= | =========== |
| Yes      | series tag     | reporting_area                                                                    | Reporting Area                                                                          | text      | text        |
| No       |                | mmwr_year                                                                         | MMWR Year                                                                               | number    | number      |
| No       |                | mmwr_week                                                                         | MMWR Week                                                                               | number    | number      |
| Yes      | numeric metric | giardiasis_current_week                                                           | Giardiasis, Current week                                                                | number    | number      |
| No       |                | giardiasis_current_week_flag                                                      | Giardiasis, Current week, flag                                                          | text      | text        |
| Yes      | numeric metric | giardiasis_previous_52_weeks_med                                                  | Giardiasis, Previous 52 weeks Med                                                       | number    | number      |
| No       |                | giardiasis_previous_52_weeks_med_flag                                             | Giardiasis, Previous 52 weeks Med, flag                                                 | text      | text        |
| Yes      | numeric metric | giardiasis_previous_52_weeks_max                                                  | Giardiasis, Previous 52 weeks Max                                                       | number    | number      |
| No       |                | giardiasis_previous_52_weeks_max_flag                                             | Giardiasis, Previous 52 weeks Max, flag                                                 | text      | text        |
| Yes      | numeric metric | giardiasis_cum_2016                                                               | Giardiasis, Cum 2016                                                                    | number    | number      |
| No       |                | giardiasis_cum_2016_flag                                                          | Giardiasis, Cum 2016, flag                                                              | text      | text        |
| Yes      | numeric metric | giardiasis_cum_2015                                                               | Giardiasis, Cum 2015                                                                    | number    | number      |
| No       |                | giardiasis_cum_2015_flag                                                          | Giardiasis, Cum 2015, flag                                                              | text      | text        |
| Yes      | numeric metric | gonorrhea_current_week                                                            | Gonorrhea,Current week                                                                  | number    | number      |
| No       |                | gonorrhea_current_week_flag                                                       | Gonorrhea,Current week, flag                                                            | text      | text        |
| Yes      | numeric metric | gonorrhea_previous_52_weeks_med                                                   | Gonorrhea,Previous 52 weeks Med                                                         | number    | number      |
| No       |                | gonorrhea_previous_52_weeks_med_flag                                              | Gonorrhea,Previous 52 weeks Med, flag                                                   | text      | text        |
| Yes      | numeric metric | gonorrhea_previous_52_weeks_max                                                   | Gonorrhea, Previous 52 weeks Max                                                        | number    | number      |
| No       |                | gonorrhea_previous_52_weeks_max_flag                                              | Gonorrhea, Previous 52 weeks Max, flag                                                  | text      | text        |
| Yes      | numeric metric | gonorrhea_cum_2016                                                                | Gonorrhea, Cum 2016                                                                     | number    | number      |
| No       |                | gonorrhea_cum_2016_flag                                                           | Gonorrhea, Cum 2016, flag                                                               | text      | text        |
| Yes      | numeric metric | gonorrhea_cum_2015                                                                | Gonorrhea, Cum 2015                                                                     | number    | number      |
| No       |                | gonorrhea_cum_2015_flag                                                           | Gonorrhea, Cum 2015, flag                                                               | text      | text        |
| Yes      | numeric metric | haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week               | Haemophilus influenzae, invasive?, All ages, all serotypes,Current week                 | number    | number      |
| No       |                | haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week_flag          | Haemophilus influenzae, invasive?, All ages, all serotypes,Current week, flag           | text      | text        |
| Yes      | numeric metric | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med      | Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Med       | number    | number      |
| No       |                | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med_flag | Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max      | Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Max       | number    | number      |
| No       |                | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max_flag | Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2016                   | Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2016                    | number    | number      |
| No       |                | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2016_flag              | Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015                   | Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2015                    | number    | number      |
| No       |                | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015_flag              | Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2015, flag              | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = giardiasis_current_week_flag,giardiasis_previous_52_weeks_med_flag,giardiasis_previous_52_weeks_max_flag,giardiasis_cum_2016_flag,giardiasis_cum_2015_flag,gonorrhea_current_week_flag,gonorrhea_previous_52_weeks_med_flag,gonorrhea_previous_52_weeks_max_flag,gonorrhea_cum_2016_flag,gonorrhea_cum_2015_flag,haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week_flag,haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med_flag,haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max_flag,haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2016_flag,haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:afja-b25e d:2015-12-27T00:00:00.000Z t:reporting_area="UNITED STATES" m:gonorrhea_cum_2016=3871 m:gonorrhea_cum_2015=6941 m:gonorrhea_current_week=3871 m:giardiasis_current_week=84 m:giardiasis_previous_52_weeks_max=335 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015=128 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2016=55 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med=69 m:gonorrhea_previous_52_weeks_max=8306 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max=128 m:giardiasis_previous_52_weeks_med=227 m:giardiasis_cum_2015=189 m:giardiasis_cum_2016=84 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week=55 m:gonorrhea_previous_52_weeks_med=7155

series e:afja-b25e d:2015-12-27T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:gonorrhea_cum_2016=52 m:gonorrhea_cum_2015=119 m:gonorrhea_current_week=52 m:giardiasis_current_week=10 m:giardiasis_previous_52_weeks_max=40 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015=6 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2016=2 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med=5 m:gonorrhea_previous_52_weeks_max=196 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max=10 m:giardiasis_previous_52_weeks_med=20 m:giardiasis_cum_2015=16 m:giardiasis_cum_2016=10 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week=2 m:gonorrhea_previous_52_weeks_med=136

series e:afja-b25e d:2015-12-27T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:gonorrhea_cum_2016=510 m:gonorrhea_cum_2015=816 m:gonorrhea_current_week=510 m:giardiasis_current_week=22 m:giardiasis_previous_52_weeks_max=74 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015=16 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2016=7 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med=11 m:gonorrhea_previous_52_weeks_max=1036 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max=18 m:giardiasis_previous_52_weeks_med=47 m:giardiasis_cum_2015=40 m:giardiasis_cum_2016=22 m:haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week=7 m:gonorrhea_previous_52_weeks_med=876
```

## Meta Commands

```ls
metric m:giardiasis_current_week p:integer l:"Giardiasis, Current week" t:dataTypeName=number

metric m:giardiasis_previous_52_weeks_med p:integer l:"Giardiasis, Previous 52 weeks Med" t:dataTypeName=number

metric m:giardiasis_previous_52_weeks_max p:integer l:"Giardiasis, Previous 52 weeks Max" t:dataTypeName=number

metric m:giardiasis_cum_2016 p:integer l:"Giardiasis, Cum 2016" t:dataTypeName=number

metric m:giardiasis_cum_2015 p:integer l:"Giardiasis, Cum 2015" t:dataTypeName=number

metric m:gonorrhea_current_week p:integer l:"Gonorrhea,Current week" t:dataTypeName=number

metric m:gonorrhea_previous_52_weeks_med p:integer l:"Gonorrhea,Previous 52 weeks Med" t:dataTypeName=number

metric m:gonorrhea_previous_52_weeks_max p:integer l:"Gonorrhea, Previous 52 weeks Max" t:dataTypeName=number

metric m:gonorrhea_cum_2016 p:integer l:"Gonorrhea, Cum 2016" t:dataTypeName=number

metric m:gonorrhea_cum_2015 p:integer l:"Gonorrhea, Cum 2015" t:dataTypeName=number

metric m:haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week p:integer l:"Haemophilus influenzae, invasive?, All ages, all serotypes,Current week" t:dataTypeName=number

metric m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med p:integer l:"Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Med" t:dataTypeName=number

metric m:haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max p:integer l:"Haemophilus influenzae, invasive?, All ages, all serotypes, Previous 52 weeks Max" t:dataTypeName=number

metric m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2016 p:integer l:"Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2016" t:dataTypeName=number

metric m:haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015 p:integer l:"Haemophilus influenzae, invasive?, All ages, all serotypes, Cum 2015" t:dataTypeName=number

entity e:afja-b25e l:"NNDSS - Table II. Giardiasis to Haemophilus influenza" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/afja-b25e

property e:afja-b25e t:meta.view v:id=afja-b25e v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Giardiasis to Haemophilus influenza" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:afja-b25e t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:afja-b25e t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:afja-b25e t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | giardiasis_current_week | giardiasis_current_week_flag | giardiasis_previous_52_weeks_med | giardiasis_previous_52_weeks_med_flag | giardiasis_previous_52_weeks_max | giardiasis_previous_52_weeks_max_flag | giardiasis_cum_2016 | giardiasis_cum_2016_flag | giardiasis_cum_2015 | giardiasis_cum_2015_flag | gonorrhea_current_week | gonorrhea_current_week_flag | gonorrhea_previous_52_weeks_med | gonorrhea_previous_52_weeks_med_flag | gonorrhea_previous_52_weeks_max | gonorrhea_previous_52_weeks_max_flag | gonorrhea_cum_2016 | gonorrhea_cum_2016_flag | gonorrhea_cum_2015 | gonorrhea_cum_2015_flag | haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week | haemophilus_influenzae_invasive_all_ages_all_serotypes_current_week_flag | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_med_flag | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max | haemophilus_influenzae_invasive_all_ages_all_serotypes_previous_52_weeks_max_flag | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2016 | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2016_flag | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015 | haemophilus_influenzae_invasive_all_ages_all_serotypes_cum_2015_flag | 
| ============== | ========= | ========= | ======================= | ============================ | ================================ | ===================================== | ================================ | ===================================== | =================== | ======================== | =================== | ======================== | ====================== | =========================== | =============================== | ==================================== | =============================== | ==================================== | ================== | ======================= | ================== | ======================= | =================================================================== | ======================================================================== | ============================================================================ | ================================================================================= | ============================================================================ | ================================================================================= | =============================================================== | ==================================================================== | =============================================================== | ==================================================================== | 
| UNITED STATES  | 2016      | 1         | 84                      |                              | 227                              |                                       | 335                              |                                       | 84                  |                          | 189                 |                          | 3871                   |                             | 7155                            |                                      | 8306                            |                                      | 3871               |                         | 6941               |                         | 55                                                                  |                                                                          | 69                                                                           |                                                                                   | 128                                                                          |                                                                                   | 55                                                              |                                                                      | 128                                                             |                                                                      | 
| NEW ENGLAND    | 2016      | 1         | 10                      |                              | 20                               |                                       | 40                               |                                       | 10                  |                          | 16                  |                          | 52                     |                             | 136                             |                                      | 196                             |                                      | 52                 |                         | 119                |                         | 2                                                                   |                                                                          | 5                                                                            |                                                                                   | 10                                                                           |                                                                                   | 2                                                               |                                                                      | 6                                                               |                                                                      | 
| MID. ATLANTIC  | 2016      | 1         | 22                      |                              | 47                               |                                       | 74                               |                                       | 22                  |                          | 40                  |                          | 510                    |                             | 876                             |                                      | 1036                            |                                      | 510                |                         | 816                |                         | 7                                                                   |                                                                          | 11                                                                           |                                                                                   | 18                                                                           |                                                                                   | 7                                                               |                                                                      | 16                                                              |                                                                      | 
| NEW YORK CITY  | 2016      | 1         | 13                      |                              | 16                               |                                       | 29                               |                                       | 13                  |                          | 12                  |                          | 96                     |                             | 329                             |                                      | 399                             |                                      | 96                 |                         | 379                |                         | 2                                                                   |                                                                          | 1                                                                            |                                                                                   | 6                                                                            |                                                                                   | 2                                                               |                                                                      | 3                                                               |                                                                      | 
| E.N. CENTRAL   | 2016      | 1         | 11                      |                              | 25                               |                                       | 58                               |                                       | 11                  |                          | 22                  |                          | 468                    |                             | 1014                            |                                      | 1288                            |                                      | 468                |                         | 1037               |                         | 13                                                                  |                                                                          | 13                                                                           |                                                                                   | 27                                                                           |                                                                                   | 13                                                              |                                                                      | 27                                                              |                                                                      | 
| W.N. CENTRAL   | 2016      | 1         | 4                       |                              | 9                                |                                       | 30                               |                                       | 4                   |                          | 8                   |                          | 224                    |                             | 402                             |                                      | 479                             |                                      | 224                |                         | 416                |                         |                                                                     | -                                                                        | 3                                                                            |                                                                                   | 12                                                                           |                                                                                   |                                                                 | -                                                                    | 11                                                              |                                                                      | 
| S. ATLANTIC    | 2016      | 1         | 17                      |                              | 41                               |                                       | 64                               |                                       | 17                  |                          | 34                  |                          | 638                    |                             | 1612                            |                                      | 2227                            |                                      | 638                |                         | 1305               |                         | 16                                                                  |                                                                          | 17                                                                           |                                                                                   | 67                                                                           |                                                                                   | 16                                                              |                                                                      | 29                                                              |                                                                      | 
| DIST. OF COL.  | 2016      | 1         |                         | -                            | 0                                |                                       | 4                                |                                       |                     | -                        |                     | -                        |                        | -                           | 45                              |                                      | 137                             |                                      |                    | -                       | 28                 |                         |                                                                     | -                                                                        | 0                                                                            |                                                                                   | 3                                                                            |                                                                                   |                                                                 | -                                                                    |                                                                 | -                                                                    | 
| E.S. CENTRAL   | 2016      | 1         | 2                       |                              | 3                                |                                       | 10                               |                                       | 2                   |                          | 3                   |                          | 52                     |                             | 424                             |                                      | 646                             |                                      | 52                 |                         | 309                |                         | 9                                                                   |                                                                          | 5                                                                            |                                                                                   | 15                                                                           |                                                                                   | 9                                                               |                                                                      | 15                                                              |                                                                      | 
| W.S. CENTRAL   | 2016      | 1         | 1                       |                              | 6                                |                                       | 15                               |                                       | 1                   |                          | 3                   |                          | 1024                   |                             | 1056                            |                                      | 1786                            |                                      | 1024               |                         | 1172               |                         | 1                                                                   |                                                                          | 4                                                                            |                                                                                   | 11                                                                           |                                                                                   | 1                                                               |                                                                      | 6                                                               |                                                                      | 
```