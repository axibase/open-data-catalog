# NNDSS - Table II. Shiga toxin to Shigellosis

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nndss-table-ii-shiga-toxin-to-shigellosis) |
| Metadata | [Link](https://data.cdc.gov/api/views/xv7k-8e7s) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/xv7k-8e7s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/xv7k-8e7s/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | xv7k-8e7s |
| Name | NNDSS - Table II. Shiga toxin to Shigellosis |
| Attribution | Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention |
| Category | NNDSS |
| Tags | 2016, mmwr, nndss, wonder, nedss, netss, shiga toxin-producing e. coli, stec, shigellosis |
| Created | 2016-01-12T13:20:18Z |
| Publication Date | 2017-01-05T17:34:30Z |

## Description

NNDSS - Table II. Shiga toxin to Shigellosis - 2016.  In this Table, provisional* cases of selected† notifiable diseases (≥1,000 cases reported during the preceding year), and selected low frequency diseases are displayed. The Table includes total number of cases reported in the United States, by region and by states, in accordance with the current method of displaying MMWR data.  Data on United States exclude counts from US territories.
Note:
These are provisional cases of selected national notifiable diseases, from the National Notifiable Diseases Surveillance System (NNDSS). NNDSS data reported by the 50 states, New York City, the District of Columbia, and the U.S. territories are collated and published weekly as numbered tables printed in the back of the Morbidity and Mortality Weekly Report (MMWR). Cases reported by state health departments to CDC for weekly publication are provisional because of ongoing revision of information and delayed reporting. 

Case counts in this table are presented as they were published in the MMWR issues. Therefore, numbers listed in later MMWR weeks may reflect changes made to these counts as additional information becomes available. 

Footnotes:
C.N.M.I.: Commonwealth of Northern Mariana Islands. 
U: Unavailable.    -: No reported cases.    N: Not reportable.    NN: Not Nationally Notifiable.   NP:  Nationally notifiable but not published.   Cum: Cumulative year-to-date counts.    Med: Median.    Max: Maximum.
 
* Case counts for reporting year 2016 are provisional and subject to change.   For further information on interpretation of these data, see http://wwwn.cdc.gov/nndss/document/ ProvisionalNationaNotifiableDiseasesSurveillanceData20100927.pdf.   Data for TB are displayed in Table IV, which appears quarterly.  
† Three low incidence conditions, rubella, rubella congenital, and tetanus, have been moved to Table II to facilitate case count verification with reporting jurisdictions.
§ Includes E. coli O157:H7; Shiga toxin-positive, serogroup non-O157; and Shiga toxin-positive, not serogrouped.

## Columns

```ls
| Included | Schema Type    | Field Name                                                   | Name                                                               | Data Type | Render Type |
| ======== | ============== | ============================================================ | ================================================================== | ========= | =========== |
| Yes      | series tag     | reporting_area                                               | Reporting Area                                                     | text      | text        |
| No       |                | mmwr_year                                                    | MMWR Year                                                          | number    | number      |
| No       |                | mmwr_week                                                    | MMWR Week                                                          | number    | number      |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_current_week               | Shiga toxin-producing E. coli (STEC)§, Current week                | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_current_week_flag          | Shiga toxin-producing E. coli (STEC)§, Current week, flag          | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med      | Shiga toxin-producing E. coli (STEC)§, Previous 52 weeks Med       | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag | Shiga toxin-producing E. coli (STEC)§, Previous 52 weeks Med, flag | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max      | Shiga toxin-producing E. coli (STEC)§, Previous 52 weeks Max       | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag | Shiga toxin-producing E. coli (STEC)§, Previous 52 weeks Max, flag | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_cum_2016                   | Shiga toxin-producing E. coli (STEC)§, Cum 2016                    | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_cum_2016_flag              | Shiga toxin-producing E. coli (STEC)§, Cum 2016, flag              | text      | text        |
| Yes      | numeric metric | shiga_toxin_producing_e_coli_stec_cum_2015                   | Shiga toxin-producing E. coli (STEC)§, Cum 2015                    | number    | number      |
| No       |                | shiga_toxin_producing_e_coli_stec_cum_2015_flag              | Shiga toxin-producing E. coli (STEC)§, Cum 2015, flag              | text      | text        |
| Yes      | numeric metric | shigellosis_current_week                                     | Shigellosis, Current week                                          | number    | number      |
| No       |                | shigellosis_current_week_flag                                | Shigellosis, Current week, flag                                    | text      | text        |
| Yes      | numeric metric | shigellosis_previous_52_weeks_med                            | Shigellosis, Previous 52 weeks Med                                 | number    | number      |
| No       |                | shigellosis_previous_52_weeks_med_flag                       | Shigellosis, Previous 52 weeks Med, flag                           | text      | text        |
| Yes      | numeric metric | shigellosis_previous_52_weeks_max                            | Shigellosis, Previous 52 weeks Max                                 | number    | number      |
| No       |                | shigellosis_previous_52_weeks_max_flag                       | Shigellosis, Previous 52 weeks Max, flag                           | text      | text        |
| Yes      | numeric metric | shigellosis_cum_2016                                         | Shigellosis, Cum 2016                                              | number    | number      |
| No       |                | shigellosis_cum_2016_flag                                    | Shigellosis, Cum 2016, flag                                        | text      | text        |
| Yes      | numeric metric | shigellosis_cum_2015                                         | Shigellosis, Cum 2015                                              | number    | number      |
| No       |                | shigellosis_cum_2015_flag                                    | Shigellosis, Cum 2015, flag                                        | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = shiga_toxin_producing_e_coli_stec_current_week_flag,shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag,shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag,shiga_toxin_producing_e_coli_stec_cum_2016_flag,shiga_toxin_producing_e_coli_stec_cum_2015_flag,shigellosis_current_week_flag,shigellosis_previous_52_weeks_med_flag,shigellosis_previous_52_weeks_max_flag,shigellosis_cum_2016_flag,shigellosis_cum_2015_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:xv7k-8e7s d:2015-12-27T00:00:00.000Z t:reporting_area="UNITED STATES" m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=194 m:shigellosis_cum_2015=332 m:shigellosis_cum_2016=166 m:shigellosis_previous_52_weeks_med=408 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=111 m:shigellosis_current_week=166 m:shiga_toxin_producing_e_coli_stec_cum_2015=56 m:shigellosis_previous_52_weeks_max=610 m:shiga_toxin_producing_e_coli_stec_cum_2016=16 m:shiga_toxin_producing_e_coli_stec_current_week=16

series e:xv7k-8e7s d:2015-12-27T00:00:00.000Z t:reporting_area="NEW ENGLAND" m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=17 m:shigellosis_cum_2015=2 m:shigellosis_cum_2016=1 m:shigellosis_previous_52_weeks_med=5 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=3 m:shigellosis_current_week=1 m:shiga_toxin_producing_e_coli_stec_cum_2015=3 m:shigellosis_previous_52_weeks_max=17

series e:xv7k-8e7s d:2015-12-27T00:00:00.000Z t:reporting_area="MID. ATLANTIC" m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max=23 m:shigellosis_cum_2015=49 m:shigellosis_cum_2016=12 m:shigellosis_previous_52_weeks_med=28 m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med=12 m:shigellosis_current_week=12 m:shiga_toxin_producing_e_coli_stec_cum_2015=4 m:shigellosis_previous_52_weeks_max=82 m:shiga_toxin_producing_e_coli_stec_cum_2016=2 m:shiga_toxin_producing_e_coli_stec_current_week=2
```

## Meta Commands

```ls
metric m:shiga_toxin_producing_e_coli_stec_current_week p:integer l:"Shiga toxin-producing E. coli (STEC)§, Current week" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_med p:integer l:"Shiga toxin-producing E. coli (STEC)§, Previous 52 weeks Med" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_previous_52_weeks_max p:integer l:"Shiga toxin-producing E. coli (STEC)§, Previous 52 weeks Max" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_cum_2016 p:integer l:"Shiga toxin-producing E. coli (STEC)§, Cum 2016" t:dataTypeName=number

metric m:shiga_toxin_producing_e_coli_stec_cum_2015 p:integer l:"Shiga toxin-producing E. coli (STEC)§, Cum 2015" t:dataTypeName=number

metric m:shigellosis_current_week p:integer l:"Shigellosis, Current week" t:dataTypeName=number

metric m:shigellosis_previous_52_weeks_med p:integer l:"Shigellosis, Previous 52 weeks Med" t:dataTypeName=number

metric m:shigellosis_previous_52_weeks_max p:integer l:"Shigellosis, Previous 52 weeks Max" t:dataTypeName=number

metric m:shigellosis_cum_2016 p:integer l:"Shigellosis, Cum 2016" t:dataTypeName=number

metric m:shigellosis_cum_2015 p:integer l:"Shigellosis, Cum 2015" t:dataTypeName=number

entity e:xv7k-8e7s l:"NNDSS - Table II. Shiga toxin to Shigellosis" t:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" t:url=https://data.cdc.gov/api/views/xv7k-8e7s

property e:xv7k-8e7s t:meta.view d:2017-09-25T07:23:11.362Z v:averageRating=0 v:name="NNDSS - Table II. Shiga toxin to Shigellosis" v:attribution="Division of Health Informatics and Surveillance (DHIS), Centers for Disease Control and Prevention" v:id=xv7k-8e7s v:category=NNDSS

property e:xv7k-8e7s t:meta.view.owner d:2017-09-25T07:23:11.362Z v:displayName=wja0@cdc.gov v:id=2fth-98hd v:screenName=wja0@cdc.gov

property e:xv7k-8e7s t:meta.view.tableauthor d:2017-09-25T07:23:11.362Z v:displayName=wja0@cdc.gov v:roleName=editor v:id=2fth-98hd v:screenName=wja0@cdc.gov

property e:xv7k-8e7s t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:23:11.362Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Program_Code=009:020 v:Bureau_Code=009:00
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | shiga_toxin_producing_e_coli_stec_current_week | shiga_toxin_producing_e_coli_stec_current_week_flag | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med | shiga_toxin_producing_e_coli_stec_previous_52_weeks_med_flag | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max | shiga_toxin_producing_e_coli_stec_previous_52_weeks_max_flag | shiga_toxin_producing_e_coli_stec_cum_2016 | shiga_toxin_producing_e_coli_stec_cum_2016_flag | shiga_toxin_producing_e_coli_stec_cum_2015 | shiga_toxin_producing_e_coli_stec_cum_2015_flag | shigellosis_current_week | shigellosis_current_week_flag | shigellosis_previous_52_weeks_med | shigellosis_previous_52_weeks_med_flag | shigellosis_previous_52_weeks_max | shigellosis_previous_52_weeks_max_flag | shigellosis_cum_2016 | shigellosis_cum_2016_flag | shigellosis_cum_2015 | shigellosis_cum_2015_flag | 
| ============== | ========= | ========= | ============================================== | =================================================== | ======================================================= | ============================================================ | ======================================================= | ============================================================ | ========================================== | =============================================== | ========================================== | =============================================== | ======================== | ============================= | ================================= | ====================================== | ================================= | ====================================== | ==================== | ========================= | ==================== | ========================= | 
| UNITED STATES  | 2016      | 1         | 16                                             |                                                     | 111                                                     |                                                              | 194                                                     |                                                              | 16                                         |                                                 | 56                                         |                                                 | 166                      |                               | 408                               |                                        | 610                               |                                        | 166                  |                           | 332                  |                           | 
| NEW ENGLAND    | 2016      | 1         |                                                | -                                                   | 3                                                       |                                                              | 17                                                      |                                                              |                                            | -                                               | 3                                          |                                                 | 1                        |                               | 5                                 |                                        | 17                                |                                        | 1                    |                           | 2                    |                           | 
| MID. ATLANTIC  | 2016      | 1         | 2                                              |                                                     | 12                                                      |                                                              | 23                                                      |                                                              | 2                                          |                                                 | 4                                          |                                                 | 12                       |                               | 28                                |                                        | 82                                |                                        | 12                   |                           | 49                   |                           | 
| NEW YORK CITY  | 2016      | 1         | 1                                              |                                                     | 2                                                       |                                                              | 8                                                       |                                                              | 1                                          |                                                 | 1                                          |                                                 | 7                        |                               | 11                                |                                        | 51                                |                                        | 7                    |                           | 30                   |                           | 
| E.N. CENTRAL   | 2016      | 1         | 3                                              |                                                     | 13                                                      |                                                              | 31                                                      |                                                              | 3                                          |                                                 | 5                                          |                                                 | 34                       |                               | 44                                |                                        | 85                                |                                        | 34                   |                           | 56                   |                           | 
| W.N. CENTRAL   | 2016      | 1         | 2                                              |                                                     | 9                                                       |                                                              | 22                                                      |                                                              | 2                                          |                                                 | 4                                          |                                                 | 8                        |                               | 25                                |                                        | 61                                |                                        | 8                    |                           | 32                   |                           | 
| S. ATLANTIC    | 2016      | 1         | 4                                              |                                                     | 10                                                      |                                                              | 21                                                      |                                                              | 4                                          |                                                 | 6                                          |                                                 | 53                       |                               | 76                                |                                        | 153                               |                                        | 53                   |                           | 65                   |                           | 
| DIST. OF COL.  | 2016      | 1         |                                                | -                                                   | 0                                                       |                                                              | 1                                                       |                                                              |                                            | -                                               |                                            | -                                               |                          | -                             | 0                                 |                                        | 4                                 |                                        |                      | -                         | 2                    |                           | 
| E.S. CENTRAL   | 2016      | 1         | 2                                              |                                                     | 5                                                       |                                                              | 14                                                      |                                                              | 2                                          |                                                 | 1                                          |                                                 | 19                       |                               | 25                                |                                        | 50                                |                                        | 19                   |                           | 48                   |                           | 
| W.S. CENTRAL   | 2016      | 1         | 1                                              |                                                     | 15                                                      |                                                              | 38                                                      |                                                              | 1                                          |                                                 | 6                                          |                                                 | 19                       |                               | 120                               |                                        | 268                               |                                        | 19                   |                           | 21                   |                           | 
```