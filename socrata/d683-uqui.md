# System Production Cost

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/system-production-cost) |
| Metadata | [Link](https://data.austintexas.gov/api/views/d683-uqui) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/d683-uqui/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/d683-uqui/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | d683-uqui |
| Name | System Production Cost |
| Attribution | Austin Energy |
| Category | Utilities and City Services |
| Tags | system production cost, average system production cost, energy production, cost, energy |
| Created | 2016-09-09T20:45:18Z |
| Publication Date | 2016-09-30T19:21:51Z |

## Description

Austin Energy’s system annual average production cost is total operations and maintenance costs divided by total generation in kilowatt-hours. Find more information at http://austinenergy.com/go/reports.

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                  | Data Type     | Render Type   |
| ======== | ============== | =================================================== | ===================================================== | ============= | ============= |
| Yes      | time           | fiscal_year_2                                       | Fiscal Year                                           | calendar_date | calendar_date |
| Yes      | numeric metric | system_annual_average_production_cost_cents_per_kwh | System annual average production cost (cents per kWh) | number        | number        |
```

## Time Field

```ls
Value = fiscal_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:d683-uqui d:2006-09-01T00:00:00.000Z m:system_annual_average_production_cost_cents_per_kwh=3.93

series e:d683-uqui d:2007-09-01T00:00:00.000Z m:system_annual_average_production_cost_cents_per_kwh=3.831

series e:d683-uqui d:2008-09-01T00:00:00.000Z m:system_annual_average_production_cost_cents_per_kwh=4.403
```

## Meta Commands

```ls
metric m:system_annual_average_production_cost_cents_per_kwh p:float l:"System annual average production cost (cents per kWh)" t:dataTypeName=number

entity e:d683-uqui l:"System Production Cost" t:attribution="Austin Energy" t:url=https://data.austintexas.gov/api/views/d683-uqui

property e:d683-uqui t:meta.view d:2017-09-25T07:24:17.512Z v:averageRating=0 v:name="System Production Cost" v:attribution="Austin Energy" v:id=d683-uqui v:category="Utilities and City Services"

property e:d683-uqui t:meta.view.license d:2017-09-25T07:24:17.512Z v:name="Public Domain"

property e:d683-uqui t:meta.view.owner d:2017-09-25T07:24:17.512Z v:displayName="Sarah Lambert" v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:id=c433-zrb5 v:screenName="Sarah Lambert" v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB

property e:d683-uqui t:meta.view.tableauthor d:2017-09-25T07:24:17.512Z v:displayName="Sarah Lambert" v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:id=c433-zrb5 v:screenName="Sarah Lambert" v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB
```

## Top Records

```ls
| fiscal_year_2       | system_annual_average_production_cost_cents_per_kwh | 
| =================== | =================================================== | 
| 2006-09-01T00:00:00 | 3.93                                                | 
| 2007-09-01T00:00:00 | 3.831                                               | 
| 2008-09-01T00:00:00 | 4.403                                               | 
| 2009-09-01T00:00:00 | 4.165                                               | 
| 2010-09-01T00:00:00 | 4.331                                               | 
| 2011-09-01T00:00:00 | 4.304                                               | 
| 2012-09-01T00:00:00 | 4.197                                               | 
| 2013-09-01T00:00:00 | 4.591                                               | 
| 2014-09-01T00:00:00 | 4.992                                               | 
| 2015-09-01T00:00:00 | 4.293                                               | 
```