# TABLE III. Deaths in 122 U.S. cities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-iii-deaths-in-122-u-s-cities) |
| Metadata | [Link](https://data.cdc.gov/api/views/rpjd-ejph) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/rpjd-ejph/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/rpjd-ejph/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | rpjd-ejph |
| Name | TABLE III. Deaths in 122 U.S. cities |
| Attribution | National Center for Immunization and Respiratory Diseases (NCIRD) |
| Category | NNDSS |
| Tags | 2016, 122 cities, mortality, death, pneumonia, influenza |
| Created | 2016-01-12T14:32:29Z |
| Publication Date | 2016-10-06T16:10:10Z |

## Description

TABLE III. Deaths in 122 U.S. cities – 2016.  122 Cities Mortality Reporting System — Each week, the vital statistics offices of 122 cities across the United States report the total number of death certificates processed and the number of those for which pneumonia or influenza was listed as the underlying or contributing cause of death by age group (Under 28 days, 28 days –1 year, 1-14 years, 15-24 years, 25-44 years, 45-64 years, 65-74 years, 75-84 years, and ≥ 85 years).

FOOTNOTE:
U: Unavailable. —: No reported cases.
* Mortality data in this table are voluntarily reported from 122 cities in the United States, most of which have populations of 100,000 or more. A death is reported by the place of its occurrence and by the week that the death certificate was filed. Fetal deaths are not included. 

† Pneumonia and influenza. 

§ Total includes unknown ages.

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                         | Data Type | Render Type |
| ======== | ============== | ===================================== | ============================================ | ========= | =========== |
| Yes      | series tag     | reporting_area                        | Reporting Area                               | text      | text        |
| No       |                | mmwr_year                             | MMWR YEAR                                    | number    | number      |
| No       |                | mmwr_week                             | MMWR WEEK                                    | number    | number      |
| Yes      | numeric metric | all_causes_by_age_years_all_ages      | All causes, by age (years), All Ages**       | number    | number      |
| No       |                | all_causes_by_age_years_all_ages_flag | All causes, by age (years), All Ages**, flag | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_65            | All causes, by age (years), ≥65              | number    | number      |
| No       |                | all_causes_by_age_years_65_flag       | All causes, by age (years), ≥65, flag        | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_45_64         | All causes, by age (years), 45–64            | number    | number      |
| No       |                | all_causes_by_age_years_45_64_flag    | All causes, by age (years), 45–64, flag      | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_25_44         | All causes, by age (years), 25–44            | number    | number      |
| No       |                | all_causes_by_age_years_25_44_flag    | All causes, by age (years), 25–44, flag      | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_1_24          | All causes, by age (years), 1–24             | number    | number      |
| No       |                | all_causes_by_age_years_1_24_flag     | All causes, by age (years), 1–24, flag       | text      | text        |
| Yes      | numeric metric | all_causes_by_age_years_lt_1          | All causes, by age (years), LT 1             | number    | number      |
| No       |                | all_causes_by_age_years_lt_1_flag     | All causes, by age (years), LT 1, flag       | text      | text        |
| Yes      | numeric metric | p_i_total                             | P&I† Total                                   | number    | number      |
| No       |                | p_i_total_flag                        | P&I† Total, flag                             | text      | text        |
```

## Time Field

```ls
Value = mmwr_year-mmwr_week
Format & Zone = yyyy-w
```

## Series Fields

```ls
Excluded Fields = all_causes_by_age_years_all_ages_flag,all_causes_by_age_years_65_flag,all_causes_by_age_years_45_64_flag,all_causes_by_age_years_25_44_flag,all_causes_by_age_years_1_24_flag,all_causes_by_age_years_lt_1_flag,p_i_total_flag,mmwr_year,mmwr_week
```

## Data Commands

```ls
series e:rpjd-ejph d:2015-12-27T00:00:00.000Z t:reporting_area="New England" m:all_causes_by_age_years_25_44=28 m:all_causes_by_age_years_lt_1=9 m:all_causes_by_age_years_all_ages=600 m:all_causes_by_age_years_65=426 m:all_causes_by_age_years_1_24=12 m:p_i_total=47 m:all_causes_by_age_years_45_64=125

series e:rpjd-ejph d:2015-12-27T00:00:00.000Z t:reporting_area="Mid. Atlantic" m:all_causes_by_age_years_25_44=32 m:all_causes_by_age_years_lt_1=18 m:all_causes_by_age_years_all_ages=807 m:all_causes_by_age_years_65=563 m:all_causes_by_age_years_1_24=13 m:p_i_total=32 m:all_causes_by_age_years_45_64=181

series e:rpjd-ejph d:2015-12-27T00:00:00.000Z t:reporting_area="E.N. Central" m:all_causes_by_age_years_25_44=167 m:all_causes_by_age_years_lt_1=34 m:all_causes_by_age_years_all_ages=2468 m:all_causes_by_age_years_65=1611 m:all_causes_by_age_years_1_24=62 m:p_i_total=159 m:all_causes_by_age_years_45_64=594
```

## Meta Commands

```ls
metric m:all_causes_by_age_years_all_ages p:integer l:"All causes, by age (years), All Ages**" t:dataTypeName=number

metric m:all_causes_by_age_years_65 p:integer l:"All causes, by age (years), ≥65" t:dataTypeName=number

metric m:all_causes_by_age_years_45_64 p:integer l:"All causes, by age (years), 45–64" t:dataTypeName=number

metric m:all_causes_by_age_years_25_44 p:integer l:"All causes, by age (years), 25–44" t:dataTypeName=number

metric m:all_causes_by_age_years_1_24 p:integer l:"All causes, by age (years), 1–24" t:dataTypeName=number

metric m:all_causes_by_age_years_lt_1 p:integer l:"All causes, by age (years), LT 1" t:dataTypeName=number

metric m:p_i_total p:integer l:"P&I† Total" t:dataTypeName=number

entity e:rpjd-ejph l:"TABLE III. Deaths in 122 U.S. cities" t:attribution="National Center for Immunization and Respiratory Diseases (NCIRD)" t:url=https://data.cdc.gov/api/views/rpjd-ejph

property e:rpjd-ejph t:meta.view d:2017-09-25T07:27:19.438Z v:averageRating=0 v:name="TABLE III. Deaths in 122 U.S. cities" v:attribution="National Center for Immunization and Respiratory Diseases (NCIRD)" v:id=rpjd-ejph v:category=NNDSS

property e:rpjd-ejph t:meta.view.owner d:2017-09-25T07:27:19.438Z v:displayName=wja0@cdc.gov v:id=2fth-98hd v:screenName=wja0@cdc.gov

property e:rpjd-ejph t:meta.view.tableauthor d:2017-09-25T07:27:19.438Z v:displayName=wja0@cdc.gov v:roleName=editor v:id=2fth-98hd v:screenName=wja0@cdc.gov

property e:rpjd-ejph t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:27:19.438Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Program_Code=009:020 v:Bureau_Code=009:00
```

## Top Records

```ls
| reporting_area | mmwr_year | mmwr_week | all_causes_by_age_years_all_ages | all_causes_by_age_years_all_ages_flag | all_causes_by_age_years_65 | all_causes_by_age_years_65_flag | all_causes_by_age_years_45_64 | all_causes_by_age_years_45_64_flag | all_causes_by_age_years_25_44 | all_causes_by_age_years_25_44_flag | all_causes_by_age_years_1_24 | all_causes_by_age_years_1_24_flag | all_causes_by_age_years_lt_1 | all_causes_by_age_years_lt_1_flag | p_i_total | p_i_total_flag | 
| ============== | ========= | ========= | ================================ | ===================================== | ========================== | =============================== | ============================= | ================================== | ============================= | ================================== | ============================ | ================================= | ============================ | ================================= | ========= | ============== | 
| New England    | 2016      | 1         | 600                              |                                       | 426                        |                                 | 125                           |                                    | 28                            |                                    | 12                           |                                   | 9                            |                                   | 47        |                | 
| Mid. Atlantic  | 2016      | 1         | 807                              |                                       | 563                        |                                 | 181                           |                                    | 32                            |                                    | 13                           |                                   | 18                           |                                   | 32        |                | 
| E.N. Central   | 2016      | 1         | 2468                             |                                       | 1611                       |                                 | 594                           |                                    | 167                           |                                    | 62                           |                                   | 34                           |                                   | 159       |                | 
| W.N. Central   | 2016      | 1         | 634                              |                                       | 432                        |                                 | 150                           |                                    | 31                            |                                    | 9                            |                                   | 11                           |                                   | 37        |                | 
| S. Atlantic    | 2016      | 1         | 1402                             |                                       | 893                        |                                 | 343                           |                                    | 92                            |                                    | 32                           |                                   | 41                           |                                   | 88        |                | 
| E.S. Central   | 2016      | 1         | 1230                             |                                       | 790                        |                                 | 296                           |                                    | 97                            |                                    | 22                           |                                   | 25                           |                                   | 76        |                | 
| W.S. Central   | 2016      | 1         | 2167                             |                                       | 1408                       |                                 | 542                           |                                    | 148                           |                                    | 40                           |                                   | 29                           |                                   | 124       |                | 
| Mountain       | 2016      | 1         | 1460                             |                                       | 997                        |                                 | 316                           |                                    | 103                           |                                    | 26                           |                                   | 18                           |                                   | 95        |                | 
| Pacific        | 2016      | 1         | 2021                             |                                       | 1480                       |                                 | 401                           |                                    | 99                            |                                    | 26                           |                                   | 15                           |                                   | 156       |                | 
| Total¶         | 2016      | 1         | 12789                            |                                       | 8600                       |                                 | 2948                          |                                    | 797                           |                                    | 242                          |                                   | 200                          |                                   | 814       |                | 
```