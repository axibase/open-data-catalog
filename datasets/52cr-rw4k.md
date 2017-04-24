# NNDSS - Table II. Salmonellosis to Shigellosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-salmonellosis-to-shigellosis-1af88) |
| Metadata | [Link](https://data.cdc.gov/api/views/52cr-rw4k) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/52cr-rw4k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/52cr-rw4k/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 52cr-rw4k |
| Name | NNDSS - Table II. Salmonellosis to Shigellosis |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2014, mmwr, nndss, wonder, nedss, netss, salmonellosis, shiga toxin-producing e. coli, stec, shigellosis |
| Created | 2014-03-09T23:01:42Z |
| Publication Date | 2015-01-08T16:41:55Z |

## Description

NNDSS - Table II. Salmonellosis to Shigellosis - 2014.In this Table, all conditions with a 5-year average annual national total of more than or equals 1,000 cases but less than or equals 10,000 cases will be displayed (??? 1,000 and ??_ 10,000). The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories. Note:These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. Footnotes:C.N.M.I.: Commonwealth of Northern Mariana Islands. U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable    Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum. * Case counts for reporting years 2013 and 2014 are provisional and subject to change. For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf. Data for TB are displayed in Table IV, which appears quarterly. ??? Includes E. coli O157:H7; Shiga toxin positive, serogroup non-O157; and Shiga toxin positive, not serogrouped.More information on NNDSS is available at http://wwwn.cdc.gov/nndss/.

## Columns

```ls
| Included | Schema Type    | Field Name                                                   | Name                                                               | Data Type | Render Type |
| ======== | ============== | ============================================================ | ================================================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                                               | Reporting Area                                                     | text      | text        |
| No       |                | mmwr_year                                                    | MMWR Year                                                          | number    | number      |
| No       |                | mmwr_week                                                    | MMWR Week                                                          | number    | number      |
| Yes      | numeric metric | salmonellosis_current_week                                   | Salmonellosis, Current week                                        | number    | number      |
| No       |                | salmonellosis_current_week_flag                              | Salmonellosis, Current week, flag                                  | text      | text        |
| Yes      | numeric metric | salmonellosis_previous_52_weeks_med                          | Salmonellosis, Previous 52 weeks Med                               | number    | number      |
| No       |                | salmonellosis_previous_52_weeks_med_flag                     | Salmonellosis, Previous 52 weeks Med, flag                         | text      | text        |
| Yes      | numeric metric | salmonellosis_previous_52_weeks_max                          | Salmonellosis, Previous 52 weeks Max                               | number    | number      |
| No       |                | salmonellosis_previous_52_weeks_max_flag                     | Salmonellosis, Previous 52 weeks Max, flag                         | text      | text        |
| Yes      | numeric metric | salmonellosis_cum_2014                                       | Salmonellosis, Cum 2014                                            | number    | number      |
| No       |                | salmonellosis_cum_2014_flag                                  | Salmonellosis, Cum 2014, flag                                      | text      | text        |
| Yes      | numeric metric | salmonellosis_cum_2013                                       | Salmonellosis, Cum 2013                                            | number    | number      |
| No       |                | salmonellosis_cum_2013_flag                                  | Salmonellosis, Cum 2013, flag                                      | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_current_week               | Shiga toxin-producing E. coli (STEC)?, Current week                | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_current_week_flag          | Shiga toxin-producing E. coli (STEC)?, Current week, flag          | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med      | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med       | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max      | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max       | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag | Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_cum_2014                   | Shiga toxin-producing E. coli (STEC)?, Cum 2014                    | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_cum_2014_flag              | Shiga toxin-producing E. coli (STEC)?, Cum 2014, flag              | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_cum_2013                   | Shiga toxin-producing E. coli (STEC)?, Cum 2013                    | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_cum_2013_flag              | Shiga toxin-producing E. coli (STEC)?, Cum 2013, flag              | text      | text        |
| Yes      | numeric metric | shigellosis_current_week                                     | Shigellosis, Current week                                          | number    | number      |
| No       |                | shigellosis_current_week_flag                                | Shigellosis, Current week, flag                                    | text      | text        |
| Yes      | numeric metric | shigellosis_previous_52_weeks_med                            | Shigellosis, Previous 52 weeks Med                                 | number    | number      |
| No       |                | shigellosis_previous_52_weeks_med_flag                       | Shigellosis, Previous 52 weeks Med, flag                           | text      | text        |
| Yes      | numeric metric | shigellosis_previous_52_weeks_max                            | Shigellosis, Previous 52 weeks Max                                 | number    | number      |
| No       |                | shigellosis_previous_52_weeks_max_flag                       | Shigellosis, Previous 52 weeks Max, flag                           | text      | text        |
| Yes      | numeric metric | shigellosis_cum_2014                                         | Shigellosis, Cum 2014                                              | number    | number      |
| No       |                | shigellosis_cum_2014_flag                                    | Shigellosis, Cum 2014, flag                                        | text      | text        |
| Yes      | numeric metric | shigellosis_cum_2013                                         | Shigellosis, Cum 2013                                              | number    | number      |
| No       |                | shigellosis_cum_2013_flag                                    | Shigellosis, Cum 2013, flag                                        | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = salmonellosis_current_week_flag,salmonellosis_previous_52_weeks_med_flag,salmonellosis_previous_52_weeks_max_flag,salmonellosis_cum_2014_flag,salmonellosis_cum_2013_flag,shiga_toxin_producing_e_coli_stec_current_week_flag,shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag,shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag,shiga_toxin_producing_e_coli_stec_cum_2014_flag,shiga_toxin_producing_e_coli_stec_cum_2013_flag,shigellosis_current_week_flag,shigellosis_previous_52_weeks_med_flag,shigellosis_previous_52_weeks_max_flag,shigellosis_cum_2014_flag,shigellosis_cum_2013_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:52cr-rw4k d:2013-12-29T00:00:00.000Z t:reporting_area="UNITED STATES" m:shiga_toxin_producing_e_coli_stec_current_week=10 m:shiga_toxin_producing_e_coli_stec_cum_2013=59 m:shiga_toxin_producing_e_coli_stec_cum_2014=10 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=232 m:salmonellosis_previous_52_weeks_max=1513 m:salmonellosis_cum_2013=406 m:salmonellosis_cum_2014=176 m:salmonellosis_previous_52_weeks_med=869 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=110 m:shigellosis_current_week=202 m:shigellosis_previous_52_weeks_max=351 m:shigellosis_previous_52_weeks_med=187 m:shigellosis_cum_2013=132 m:shigellosis_cum_2014=202 m:salmonellosis_current_week=176

series e:52cr-rw4k d:2013-12-29T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:shiga_toxin_producing_e_coli_stec_cum_2013=3 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=12 m:salmonellosis_previous_52_weeks_max=81 m:salmonellosis_cum_2013=19 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=4 m:shigellosis_previous_52_weeks_med=4 m:shigellosis_previous_52_weeks_max=94 m:salmonellosis_previous_52_weeks_med=39 m:shigellosis_cum_2013=8

series e:52cr-rw4k d:2013-12-29T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:shiga_toxin_producing_e_coli_stec_current_week=2 m:shiga_toxin_producing_e_coli_stec_cum_2013=10 m:shiga_toxin_producing_e_coli_stec_cum_2014=2 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=37 m:salmonellosis_previous_52_weeks_max=196 m:salmonellosis_cum_2013=40 m:salmonellosis_cum_2014=12 m:salmonellosis_previous_52_weeks_med=94 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=13 m:shigellosis_current_week=4 m:shigellosis_previous_52_weeks_max=28 m:shigellosis_previous_52_weeks_med=15 m:shigellosis_cum_2013=13 m:shigellosis_cum_2014=4 m:salmonellosis_current_week=12
```

## Meta Commands

```ls
metric m:salmonellosis_current_week p:integer l:"Salmonellosis, Current week" t:dataTypeName=number

metric m:salmonellosis_previous_52_weeks_med p:integer l:"Salmonellosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:salmonellosis_previous_52_weeks_max p:integer l:"Salmonellosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:salmonellosis_cum_2014 p:integer l:"Salmonellosis, Cum 2014" t:dataTypeName=number

metric m:salmonellosis_cum_2013 p:integer l:"Salmonellosis, Cum 2013" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_current_week p:integer l:"Shiga toxin-producing E. coli (STEC)?, Current week" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med p:integer l:"Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Med" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max p:integer l:"Shiga toxin-producing E. coli (STEC)?, Previous 52 weeks Max" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_cum_2014 p:integer l:"Shiga toxin-producing E. coli (STEC)?, Cum 2014" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_cum_2013 p:integer l:"Shiga toxin-producing E. coli (STEC)?, Cum 2013" t:dataTypeName=number

metric m:shigellosis_current_week p:integer l:"Shigellosis, Current week" t:dataTypeName=number

metric m:shigellosis_previous_52_weeks_med p:integer l:"Shigellosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:shigellosis_previous_52_weeks_max p:integer l:"Shigellosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:shigellosis_cum_2014 p:integer l:"Shigellosis, Cum 2014" t:dataTypeName=number

metric m:shigellosis_cum_2013 p:integer l:"Shigellosis, Cum 2013" t:dataTypeName=number

entity e:52cr-rw4k l:"NNDSS - Table II. Salmonellosis to Shigellosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/52cr-rw4k

property e:52cr-rw4k t:meta.view v:id=52cr-rw4k v:category=NNDSS v:averageRating=0 v:name="NNDSS - Table II. Salmonellosis to Shigellosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention"

property e:52cr-rw4k t:meta.view.owner v:id=2fth-98hd v:screenName=wja0@cdc.gov v:displayName=wja0@cdc.gov

property e:52cr-rw4k t:meta.view.tableauthor v:id=2fth-98hd v:screenName=wja0@cdc.gov v:roleName=editor v:displayName=wja0@cdc.gov

property e:52cr-rw4k t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | salmonellosis_current_week | salmonellosis_current_week_flag | salmonellosis_previous_52_weeks_med | salmonellosis_previous_52_weeks_med_flag | salmonellosis_previous_52_weeks_max | salmonellosis_previous_52_weeks_max_flag | salmonellosis_cum_2014 | salmonellosis_cum_2014_flag | salmonellosis_cum_2013 | salmonellosis_cum_2013_flag | shiga_toxin_producing_e_coli_stec_current_week | shiga_toxin_producing_e_coli_stec_current_week_flag | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag | shiga_toxin_producing_e_coli_stec_cum_2014 | shiga_toxin_producing_e_coli_stec_cum_2014_flag | shiga_toxin_producing_e_coli_stec_cum_2013 | shiga_toxin_producing_e_coli_stec_cum_2013_flag | shigellosis_current_week | shigellosis_current_week_flag | shigellosis_previous_52_weeks_med | shigellosis_previous_52_weeks_med_flag | shigellosis_previous_52_weeks_max | shigellosis_previous_52_weeks_max_flag | shigellosis_cum_2014 | shigellosis_cum_2014_flag | shigellosis_cum_2013 | shigellosis_cum_2013_flag | 
| ============== | ========= | ========= | ========================== | =============================== | =================================== | ======================================== | =================================== | ======================================== | ====================== | =========================== | ====================== | =========================== | ============================================== | =================================================== | ======================================================= | ============================================================ | ======================================================= | ============================================================ | ========================================== | =============================================== | ========================================== | =============================================== | ======================== | ============================= | ================================= | ====================================== | ================================= | ====================================== | ==================== | ========================= | ==================== | ========================= | 
| UNITED STATES  | 2014      | 1         | 176                        |                                 | 869                                 |                                          | 1513                                |                                          | 176                    |                             | 406                    |                             | 10                                             |                                                     | 110                                                     |                                                              | 232                                                     |                                                              | 10                                         |                                                 | 59                                         |                                                 | 202                      |                               | 187                               |                                        | 351                               |                                        | 202                  |                           | 132                  |                           | 
| NEW ENGLAND    | 2014      | 1         |                            | -                               | 39                                  |                                          | 81                                  |                                          |                        | -                           | 19                     |                             |                                                | -                                                   | 4                                                       |                                                              | 12                                                      |                                                              |                                            | -                                               | 3                                          |                                                 |                          | -                             | 4                                 |                                        | 94                                |                                        |                      | -                         | 8                    |                           | 
| MID. ATLANTIC  | 2014      | 1         | 12                         |                                 | 94                                  |                                          | 196                                 |                                          | 12                     |                             | 40                     |                             | 2                                              |                                                     | 13                                                      |                                                              | 37                                                      |                                                              | 2                                          |                                                 | 10                                         |                                                 | 4                        |                               | 15                                |                                        | 28                                |                                        | 4                    |                           | 13                   |                           | 
| E.N. CENTRAL   | 2014      | 1         | 11                         |                                 | 90                                  |                                          | 166                                 |                                          | 11                     |                             | 60                     |                             |                                                | -                                                   | 15                                                      |                                                              | 45                                                      |                                                              |                                            | -                                               | 15                                         |                                                 | 12                       |                               | 22                                |                                        | 74                                |                                        | 12                   |                           | 41                   |                           | 
| W.N. CENTRAL   | 2014      | 1         | 7                          |                                 | 46                                  |                                          | 93                                  |                                          | 7                      |                             | 30                     |                             |                                                | -                                                   | 12                                                      |                                                              | 38                                                      |                                                              |                                            | -                                               | 5                                          |                                                 | 6                        |                               | 6                                 |                                        | 74                                |                                        | 6                    |                           | 6                    |                           | 
| S. ATLANTIC    | 2014      | 1         | 109                        |                                 | 223                                 |                                          | 432                                 |                                          | 109                    |                             | 109                    |                             | 5                                              |                                                     | 9                                                       |                                                              | 18                                                      |                                                              | 5                                          |                                                 | 5                                          |                                                 | 147                      |                               | 46                                |                                        | 92                                |                                        | 147                  |                           | 15                   |                           | 
| E.S. CENTRAL   | 2014      | 1         | 9                          |                                 | 56                                  |                                          | 136                                 |                                          | 9                      |                             | 40                     |                             | 2                                              |                                                     | 5                                                       |                                                              | 18                                                      |                                                              | 2                                          |                                                 | 6                                          |                                                 | 26                       |                               | 19                                |                                        | 65                                |                                        | 26                   |                           | 9                    |                           | 
| W.S. CENTRAL   | 2014      | 1         | 1                          |                                 | 116                                 |                                          | 243                                 |                                          | 1                      |                             | 16                     |                             |                                                | -                                                   | 13                                                      |                                                              | 33                                                      |                                                              |                                            | -                                               | 1                                          |                                                 | 1                        |                               | 46                                |                                        | 93                                |                                        | 1                    |                           | 6                    |                           | 
| MOUNTAIN       | 2014      | 1         | 7                          |                                 | 51                                  |                                          | 248                                 |                                          | 7                      |                             | 18                     |                             |                                                | -                                                   | 9                                                       |                                                              | 33                                                      |                                                              |                                            | -                                               | 4                                          |                                                 | 2                        |                               | 9                                 |                                        | 38                                |                                        | 2                    |                           | 6                    |                           | 
| PACIFIC        | 2014      | 1         | 20                         |                                 | 109                                 |                                          | 215                                 |                                          | 20                     |                             | 74                     |                             | 1                                              |                                                     | 17                                                      |                                                              | 51                                                      |                                                              | 1                                          |                                                 | 10                                         |                                                 | 4                        |                               | 20                                |                                        | 47                                |                                        | 4                    |                           | 28                   |                           | 
```