# LADWP Solar Incentive Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ladwp-solar-incentive-program-b0ebd) |
| Metadata | [Link](https://data.lacity.org/api/views/2yrw-q8tw) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/2yrw-q8tw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/2yrw-q8tw/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 2yrw-q8tw |
| Name | LADWP Solar Incentive Program |
| Attribution | LADWP |
| Category | A Livable and Sustainable City |
| Tags | local solar, sip |
| Created | 2014-05-14T00:01:26Z |
| Publication Date | 2017-02-21T22:04:12Z |

## Description

Installed Capacity from Solar Incentive Program (Kilowatts).  The program offers customers an incentive to offset the cost of installing a solar rooftop system on their home or business.  LADWP has been helping customers to go solar since 1999.

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                      | Data Type | Render Type |
| ======== | ============== | ============================================================= | ========================================================= | ========= | =========== |
| Yes      | time           | quarter_fiscalyear                                            | Quarter-Fiscal Year                                       | text      | text        |
| Yes      | numeric metric | installed_capacity_from_solar_incentive_program_in_quarter_kw | Solar Incentive Program Cumulative Installed Capacity(kW) | number    | number      |
```

## Time Field

```ls
Value = quarter_fiscalyear
Format & Zone = QQQ 'FY'yy
```

## Data Commands

```ls
series e:2yrw-q8tw d:2008-01-01T00:00:00.000Z m:installed_capacity_from_solar_incentive_program_in_quarter_kw=10901.66

series e:2yrw-q8tw d:2008-04-01T00:00:00.000Z m:installed_capacity_from_solar_incentive_program_in_quarter_kw=11316.87

series e:2yrw-q8tw d:2008-07-01T00:00:00.000Z m:installed_capacity_from_solar_incentive_program_in_quarter_kw=11938.39
```

## Meta Commands

```ls
metric m:installed_capacity_from_solar_incentive_program_in_quarter_kw p:float l:"Solar Incentive Program Cumulative Installed Capacity(kW)" d:"Cumulative Installed Capacity for Solar Incentive Program" t:dataTypeName=number

entity e:2yrw-q8tw l:"LADWP Solar Incentive Program" t:attribution=LADWP t:url=https://data.lacity.org/api/views/2yrw-q8tw

property e:2yrw-q8tw t:meta.view d:2017-09-25T07:25:06.556Z v:averageRating=0 v:name="LADWP Solar Incentive Program" v:attribution=LADWP v:attributionLink="https://www.ladwp.com/ladwp/faces/ladwp/commercial/c-gogreen/c-gg-installsolar?_afrLoop=487268705452986&_afrWindowMode=0&_afrWindowId=16vdo6czx2_1#%40%3F_afrWindowId%3D16vdo6czx2_1%26_afrLoop%3D487268705452986%26_afrWindowMode%3D0%26_adf.ctrl-state%3D16vdo6czx2_49" v:id=2yrw-q8tw v:category="A Livable and Sustainable City"

property e:2yrw-q8tw t:meta.view.license d:2017-09-25T07:25:06.556Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:2yrw-q8tw t:meta.view.owner d:2017-09-25T07:25:06.556Z v:displayName="LA DWP OpenData" v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:id=hb8e-gdsp v:screenName="LA DWP OpenData" v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB

property e:2yrw-q8tw t:meta.view.tableauthor d:2017-09-25T07:25:06.556Z v:displayName="LA DWP OpenData" v:profileImageUrlLarge=/api/users/hb8e-gdsp/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/hb8e-gdsp/profile_images/TINY v:id=hb8e-gdsp v:screenName="LA DWP OpenData" v:profileImageUrlMedium=/api/users/hb8e-gdsp/profile_images/THUMB
```

## Top Records

```ls
| quarter_fiscalyear | installed_capacity_from_solar_incentive_program_in_quarter_kw | 
| ================== | ============================================================= | 
| Q1 FY08            | 10901.66                                                      | 
| Q2 FY08            | 11316.87                                                      | 
| Q3 FY08            | 11938.39                                                      | 
| Q4 FY08            | 12548.94                                                      | 
| Q1 FY09            | 13069.42                                                      | 
| Q2 FY09            | 14383.83                                                      | 
| Q3 FY09            | 16368.35                                                      | 
| Q4 FY09            | 17247.50                                                      | 
| Q1 FY10            | 18089.01                                                      | 
| Q2 FY10            | 19322.20                                                      | 
```