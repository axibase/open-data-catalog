# DOF: Cooperative Comparable Rental Income ? Brooklyn ? FY 2010/2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-cooperative-comparable-rental-income-brooklyn-fy-2010-2011-c7dbf) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/f42p-xqaa) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/f42p-xqaa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/f42p-xqaa/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | f42p-xqaa |
| Name | DOF: Cooperative Comparable Rental Income ? Brooklyn ? FY 2010/2011 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, rental property, cooperatives, residential, apartment, buildings, rental properties, borough, brooklyn |
| Created | 2011-10-04T19:49:10Z |
| Publication Date | 2013-06-21T20:56:14Z |

## Description

The Department of Finance (DOF) is required by NY State law to value condominiums or cooperatives as if they were residential rental apartment buildings.   DOF uses income information from rental properties similar in physical features and location to the condominiums or cooperatives. DOF applies this income data to the condominium or cooperative and determine its value in the same way DOF values rental apartment buildings.
Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                                                          | Name                                                                    | Data Type | Render Type |
| ======== | ============== | =================================================================== | ======================================================================= | ========= | =========== |
| Yes      | series tag     | brooklyn_cooperatives_comparable_properties_boro_block_lot          | BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Boro-Block-Lot          | text      | text        |
| Yes      | series tag     | brooklyn_cooperatives_comparable_properties_neighborhood            | BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Neighborhood            | text      | text        |
| Yes      | series tag     | brooklyn_cooperatives_comparable_properties_building_classification | BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Building Classification | text      | text        |
| Yes      | numeric metric | brooklyn_cooperatives_comparable_properties_total_units             | BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Total Units             | number    | number      |
| Yes      | numeric metric | brooklyn_cooperatives_comparable_properties_year_built              | BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Year Built              | number    | number      |
| Yes      | numeric metric | brooklyn_cooperatives_comparable_properties_gross_sqft              | BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Gross SqFt              | number    | number      |
| Yes      | numeric metric | brooklyn_cooperatives_comparable_properties_est_gross_income        | BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Est. Gross Income       | number    | number      |
| Yes      | numeric metric | brooklyn_cooperatives_comparable_properties_gross_income_per_sqft   | BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Gross Income per SqFt   | number    | number      |
| Yes      | numeric metric | brooklyn_cooperatives_comparable_properties_full_market_value       | BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Full Market Value       | number    | number      |
| Yes      | numeric metric | brooklyn_cooperatives_comparable_properties_market_value_per_sqft   | BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Market Value per SqFt   | number    | number      |
| Yes      | series tag     | comparable_rental_1_boro_block_lot                                  | COMPARABLE RENTAL ? 1 ?Boro-Block-Lot                                   | text      | text        |
| Yes      | series tag     | comparable_rental_1_neighborhood                                    | COMPARABLE RENTAL ? 1 ?Neighborhood                                     | text      | text        |
| Yes      | series tag     | comparable_rental_1_building_classification                         | COMPARABLE RENTAL ? 1 ?Building Classification                          | text      | text        |
| Yes      | numeric metric | comparable_rental_1_total_units                                     | COMPARABLE RENTAL ? 1 ?Total Units                                      | number    | number      |
| Yes      | numeric metric | comparable_rental_1_year_built                                      | COMPARABLE RENTAL ? 1 ?Year Built                                       | number    | number      |
| Yes      | numeric metric | comparable_rental_1_gross_sqft                                      | COMPARABLE RENTAL ? 1 ?Gross SqFt                                       | number    | number      |
| Yes      | numeric metric | comparable_rental_1_est_gross_income                                | COMPARABLE RENTAL ? 1 ?Est. Gross Income                                | number    | number      |
| Yes      | numeric metric | comparable_rental_1_gross_income_per_sqft                           | COMPARABLE RENTAL ? 1 ?Gross Income per SqFt                            | number    | number      |
| Yes      | numeric metric | comparable_rental_1_full_market_value                               | COMPARABLE RENTAL ? 1 ?Full Market Value                                | number    | number      |
| Yes      | numeric metric | comparable_rental_1_market_value_per_sqft                           | COMPARABLE RENTAL ? 1 ?Market Value per SqFt                            | number    | number      |
| Yes      | numeric metric | comparable_rental_1_dist_from_coop_in_miles                         | COMPARABLE RENTAL ? 1 ?Dist. from Coop in miles                         | number    | number      |
| Yes      | series tag     | comparable_rental_2_boro_block_lot                                  | COMPARABLE RENTAL ? 2 ?Boro-Block-Lot                                   | text      | text        |
| Yes      | series tag     | comparable_rental_2_neighborhood                                    | COMPARABLE RENTAL ? 2 ?Neighborhood                                     | text      | text        |
| Yes      | series tag     | comparable_rental_2_building_classification                         | COMPARABLE RENTAL ? 2 ?Building Classification                          | text      | text        |
| Yes      | numeric metric | comparable_rental_2_total_units                                     | COMPARABLE RENTAL ? 2 ?Total Units                                      | number    | number      |
| Yes      | numeric metric | comparable_rental_2_year_built                                      | COMPARABLE RENTAL ? 2 ?Year Built                                       | number    | number      |
| Yes      | numeric metric | comparable_rental_2_gross_sqft                                      | COMPARABLE RENTAL ? 2 ?Gross SqFt                                       | number    | number      |
| Yes      | numeric metric | comparable_rental_2_est_gross_income                                | COMPARABLE RENTAL ? 2 ?Est. Gross Income                                | number    | number      |
| Yes      | numeric metric | comparable_rental_2_gross_income_per_sqft                           | COMPARABLE RENTAL ? 2 ?Gross Income per SqFt                            | number    | number      |
| Yes      | numeric metric | comparable_rental_2_full_market_value                               | COMPARABLE RENTAL ? 2 ?Full Market Value                                | number    | number      |
| Yes      | numeric metric | comparable_rental_2_market_value_per_sqft                           | COMPARABLE RENTAL ? 2 ?Market Value per SqFt                            | number    | number      |
| Yes      | numeric metric | comparable_rental_2_dist_from_coop_in_miles                         | COMPARABLE RENTAL ? 2 ?Dist. from Coop in miles                         | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:f42p-xqaa d:2010-01-01T00:00:00.000Z t:brooklyn_cooperatives_comparable_properties_boro_block_lot=3-00068-0107 t:comparable_rental_2_boro_block_lot=3-01798-0040 t:comparable_rental_1_building_classification=D5-ELEVATOR t:comparable_rental_1_boro_block_lot=3-00051-0001 t:brooklyn_cooperatives_comparable_properties_building_classification=D4-ELEVATOR t:brooklyn_cooperatives_comparable_properties_neighborhood=DOWNTOWN-METROTECH t:comparable_rental_1_neighborhood="DOWNTOWN-FULTON FERRY" t:comparable_rental_2_building_classification=D1-ELEVATOR t:comparable_rental_2_neighborhood="BEDFORD STUYVESANT" m:brooklyn_cooperatives_comparable_properties_full_market_value=8110000 m:comparable_rental_2_market_value_per_sqft=36.4 m:comparable_rental_2_full_market_value=4660000 m:comparable_rental_1_total_units=104 m:comparable_rental_1_year_built=1914 m:brooklyn_cooperatives_comparable_properties_est_gross_income=2169514 m:comparable_rental_1_gross_sqft=123700 m:comparable_rental_1_dist_from_coop_in_miles=0.3 m:comparable_rental_2_year_built=1984 m:comparable_rental_1_full_market_value=9300000 m:brooklyn_cooperatives_comparable_properties_year_built=1902 m:brooklyn_cooperatives_comparable_properties_gross_income_per_sqft=17.84 m:comparable_rental_1_gross_income_per_sqft=20.11 m:brooklyn_cooperatives_comparable_properties_gross_sqft=121580 m:comparable_rental_2_gross_income_per_sqft=17.17 m:comparable_rental_2_dist_from_coop_in_miles=2 m:comparable_rental_2_est_gross_income=2197508 m:comparable_rental_1_market_value_per_sqft=75 m:comparable_rental_2_total_units=151 m:comparable_rental_2_gross_sqft=128000 m:comparable_rental_1_est_gross_income=2487698 m:brooklyn_cooperatives_comparable_properties_market_value_per_sqft=67 m:brooklyn_cooperatives_comparable_properties_total_units=120

series e:f42p-xqaa d:2010-01-01T00:00:00.000Z t:brooklyn_cooperatives_comparable_properties_boro_block_lot=3-08722-0474 t:comparable_rental_2_boro_block_lot=3-08710-0035 t:comparable_rental_1_building_classification=D7-ELEVATOR t:comparable_rental_1_boro_block_lot=3-07282-0062 t:brooklyn_cooperatives_comparable_properties_building_classification=D4-ELEVATOR t:brooklyn_cooperatives_comparable_properties_neighborhood="BRIGHTON BEACH" t:comparable_rental_1_neighborhood="CONEY ISLAND" t:comparable_rental_2_building_classification=D7-ELEVATOR t:comparable_rental_2_neighborhood="SHEEPSHEAD BAY" m:brooklyn_cooperatives_comparable_properties_full_market_value=5690000 m:comparable_rental_2_market_value_per_sqft=32.2 m:comparable_rental_2_full_market_value=6060000 m:comparable_rental_1_total_units=169 m:comparable_rental_1_year_built=1932 m:brooklyn_cooperatives_comparable_properties_est_gross_income=2025556 m:comparable_rental_1_gross_sqft=192000 m:comparable_rental_1_dist_from_coop_in_miles=0.75 m:comparable_rental_2_year_built=1938 m:comparable_rental_1_full_market_value=5320000 m:brooklyn_cooperatives_comparable_properties_year_built=1935 m:brooklyn_cooperatives_comparable_properties_gross_income_per_sqft=12.43 m:comparable_rental_1_gross_income_per_sqft=10.69 m:brooklyn_cooperatives_comparable_properties_gross_sqft=162957 m:comparable_rental_2_gross_income_per_sqft=11.47 m:comparable_rental_2_dist_from_coop_in_miles=0.4 m:comparable_rental_2_est_gross_income=2156234 m:comparable_rental_1_market_value_per_sqft=27.7 m:comparable_rental_2_total_units=148 m:comparable_rental_2_gross_sqft=188000 m:comparable_rental_1_est_gross_income=2052100 m:brooklyn_cooperatives_comparable_properties_market_value_per_sqft=34.9 m:brooklyn_cooperatives_comparable_properties_total_units=159

series e:f42p-xqaa d:2010-01-01T00:00:00.000Z t:brooklyn_cooperatives_comparable_properties_boro_block_lot=3-01071-0004 t:comparable_rental_2_boro_block_lot=3-08722-0475 t:comparable_rental_1_building_classification=D1-ELEVATOR t:comparable_rental_1_boro_block_lot=3-05279-0043 t:brooklyn_cooperatives_comparable_properties_building_classification=D4-ELEVATOR t:brooklyn_cooperatives_comparable_properties_neighborhood="PARK SLOPE" t:comparable_rental_1_neighborhood="WINDSOR TERRACE" t:comparable_rental_2_building_classification=D1-ELEVATOR t:comparable_rental_2_neighborhood="BRIGHTON BEACH" m:brooklyn_cooperatives_comparable_properties_full_market_value=9880000 m:comparable_rental_2_market_value_per_sqft=117 m:comparable_rental_2_full_market_value=11300000 m:comparable_rental_1_total_units=135 m:comparable_rental_1_year_built=1982 m:brooklyn_cooperatives_comparable_properties_est_gross_income=2385608 m:comparable_rental_1_gross_sqft=104640 m:comparable_rental_1_dist_from_coop_in_miles=1.3 m:comparable_rental_2_year_built=1951 m:comparable_rental_1_full_market_value=9220000 m:brooklyn_cooperatives_comparable_properties_year_built=1936 m:brooklyn_cooperatives_comparable_properties_gross_income_per_sqft=24.4 m:comparable_rental_1_gross_income_per_sqft=21.27 m:brooklyn_cooperatives_comparable_properties_gross_sqft=97768 m:comparable_rental_2_gross_income_per_sqft=28.3 m:comparable_rental_2_dist_from_coop_in_miles=6.6 m:comparable_rental_2_est_gross_income=2734487 m:comparable_rental_1_market_value_per_sqft=88 m:comparable_rental_2_total_units=96 m:comparable_rental_2_gross_sqft=96600 m:comparable_rental_1_est_gross_income=2225685 m:brooklyn_cooperatives_comparable_properties_market_value_per_sqft=101 m:brooklyn_cooperatives_comparable_properties_total_units=94
```

## Meta Commands

```ls
metric m:brooklyn_cooperatives_comparable_properties_total_units p:integer l:"BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Total Units" t:dataTypeName=number

metric m:brooklyn_cooperatives_comparable_properties_year_built p:integer l:"BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Year Built" t:dataTypeName=number

metric m:brooklyn_cooperatives_comparable_properties_gross_sqft p:integer l:"BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Gross SqFt" t:dataTypeName=number

metric m:brooklyn_cooperatives_comparable_properties_est_gross_income p:integer l:"BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Est. Gross Income" t:dataTypeName=number

metric m:brooklyn_cooperatives_comparable_properties_gross_income_per_sqft p:float l:"BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Gross Income per SqFt" t:dataTypeName=number

metric m:brooklyn_cooperatives_comparable_properties_full_market_value p:integer l:"BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Full Market Value" t:dataTypeName=number

metric m:brooklyn_cooperatives_comparable_properties_market_value_per_sqft p:double l:"BROOKLYN ? COOPERATIVES COMPARABLE PROPERTIES ? Market Value per SqFt" t:dataTypeName=number

metric m:comparable_rental_1_total_units p:integer l:"COMPARABLE RENTAL ? 1 ?Total Units" t:dataTypeName=number

metric m:comparable_rental_1_year_built p:integer l:"COMPARABLE RENTAL ? 1 ?Year Built" t:dataTypeName=number

metric m:comparable_rental_1_gross_sqft p:integer l:"COMPARABLE RENTAL ? 1 ?Gross SqFt" t:dataTypeName=number

metric m:comparable_rental_1_est_gross_income p:integer l:"COMPARABLE RENTAL ? 1 ?Est. Gross Income" t:dataTypeName=number

metric m:comparable_rental_1_gross_income_per_sqft p:double l:"COMPARABLE RENTAL ? 1 ?Gross Income per SqFt" t:dataTypeName=number

metric m:comparable_rental_1_full_market_value p:integer l:"COMPARABLE RENTAL ? 1 ?Full Market Value" t:dataTypeName=number

metric m:comparable_rental_1_market_value_per_sqft p:double l:"COMPARABLE RENTAL ? 1 ?Market Value per SqFt" t:dataTypeName=number

metric m:comparable_rental_1_dist_from_coop_in_miles p:double l:"COMPARABLE RENTAL ? 1 ?Dist. from Coop in miles" t:dataTypeName=number

metric m:comparable_rental_2_total_units p:integer l:"COMPARABLE RENTAL ? 2 ?Total Units" t:dataTypeName=number

metric m:comparable_rental_2_year_built p:integer l:"COMPARABLE RENTAL ? 2 ?Year Built" t:dataTypeName=number

metric m:comparable_rental_2_gross_sqft p:integer l:"COMPARABLE RENTAL ? 2 ?Gross SqFt" t:dataTypeName=number

metric m:comparable_rental_2_est_gross_income p:integer l:"COMPARABLE RENTAL ? 2 ?Est. Gross Income" t:dataTypeName=number

metric m:comparable_rental_2_gross_income_per_sqft p:float l:"COMPARABLE RENTAL ? 2 ?Gross Income per SqFt" t:dataTypeName=number

metric m:comparable_rental_2_full_market_value p:integer l:"COMPARABLE RENTAL ? 2 ?Full Market Value" t:dataTypeName=number

metric m:comparable_rental_2_market_value_per_sqft p:double l:"COMPARABLE RENTAL ? 2 ?Market Value per SqFt" t:dataTypeName=number

metric m:comparable_rental_2_dist_from_coop_in_miles p:float l:"COMPARABLE RENTAL ? 2 ?Dist. from Coop in miles" t:dataTypeName=number

entity e:f42p-xqaa l:"DOF: Cooperative Comparable Rental Income ? Brooklyn ? FY 2010/2011" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/f42p-xqaa

property e:f42p-xqaa t:meta.view v:id=f42p-xqaa v:category="Housing & Development" v:averageRating=0 v:name="DOF: Cooperative Comparable Rental Income ? Brooklyn ? FY 2010/2011" v:attribution="Department of Finance (DOF)"

property e:f42p-xqaa t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:f42p-xqaa t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| brooklyn_cooperatives_comparable_properties_boro_block_lot | brooklyn_cooperatives_comparable_properties_neighborhood | brooklyn_cooperatives_comparable_properties_building_classification | brooklyn_cooperatives_comparable_properties_total_units | brooklyn_cooperatives_comparable_properties_year_built | brooklyn_cooperatives_comparable_properties_gross_sqft | brooklyn_cooperatives_comparable_properties_est_gross_income | brooklyn_cooperatives_comparable_properties_gross_income_per_sqft | brooklyn_cooperatives_comparable_properties_full_market_value | brooklyn_cooperatives_comparable_properties_market_value_per_sqft | comparable_rental_1_boro_block_lot | comparable_rental_1_neighborhood | comparable_rental_1_building_classification | comparable_rental_1_total_units | comparable_rental_1_year_built | comparable_rental_1_gross_sqft | comparable_rental_1_est_gross_income | comparable_rental_1_gross_income_per_sqft | comparable_rental_1_full_market_value | comparable_rental_1_market_value_per_sqft | comparable_rental_1_dist_from_coop_in_miles | comparable_rental_2_boro_block_lot | comparable_rental_2_neighborhood | comparable_rental_2_building_classification | comparable_rental_2_total_units | comparable_rental_2_year_built | comparable_rental_2_gross_sqft | comparable_rental_2_est_gross_income | comparable_rental_2_gross_income_per_sqft | comparable_rental_2_full_market_value | comparable_rental_2_market_value_per_sqft | comparable_rental_2_dist_from_coop_in_miles | 
| ========================================================== | ======================================================== | =================================================================== | ======================================================= | ====================================================== | ====================================================== | ============================================================ | ================================================================= | ============================================================= | ================================================================= | ================================== | ================================ | =========================================== | =============================== | ============================== | ============================== | ==================================== | ========================================= | ===================================== | ========================================= | =========================================== | ================================== | ================================ | =========================================== | =============================== | ============================== | ============================== | ==================================== | ========================================= | ===================================== | ========================================= | =========================================== | 
| 3-00068-0107                                               | DOWNTOWN-METROTECH                                       | D4-ELEVATOR                                                         | 120                                                     | 1902                                                   | 121580                                                 | 2169514                                                      | 17.84                                                             | 8110000                                                       | 67                                                                | 3-00051-0001                       | DOWNTOWN-FULTON FERRY            | D5-ELEVATOR                                 | 104                             | 1914                           | 123700                         | 2487698                              | 20.11                                     | 9300000                               | 75                                        | 0.3                                         | 3-01798-0040                       | BEDFORD STUYVESANT               | D1-ELEVATOR                                 | 151                             | 1984                           | 128000                         | 2197508                              | 17.17                                     | 4660000                               | 36.4                                      | 2                                           | 
| 3-08722-0474                                               | BRIGHTON BEACH                                           | D4-ELEVATOR                                                         | 159                                                     | 1935                                                   | 162957                                                 | 2025556                                                      | 12.43                                                             | 5690000                                                       | 34.9                                                              | 3-07282-0062                       | CONEY ISLAND                     | D7-ELEVATOR                                 | 169                             | 1932                           | 192000                         | 2052100                              | 10.69                                     | 5320000                               | 27.7                                      | 0.75                                        | 3-08710-0035                       | SHEEPSHEAD BAY                   | D7-ELEVATOR                                 | 148                             | 1938                           | 188000                         | 2156234                              | 11.47                                     | 6060000                               | 32.2                                      | 0.4                                         | 
| 3-01071-0004                                               | PARK SLOPE                                               | D4-ELEVATOR                                                         | 94                                                      | 1936                                                   | 97768                                                  | 2385608                                                      | 24.4                                                              | 9880000                                                       | 101                                                               | 3-05279-0043                       | WINDSOR TERRACE                  | D1-ELEVATOR                                 | 135                             | 1982                           | 104640                         | 2225685                              | 21.27                                     | 9220000                               | 88                                        | 1.3                                         | 3-08722-0475                       | BRIGHTON BEACH                   | D1-ELEVATOR                                 | 96                              | 1951                           | 96600                          | 2734487                              | 28.3                                      | 11300000                              | 117                                       | 6.6                                         | 
| 3-06746-0044                                               | MIDWOOD                                                  | D4-ELEVATOR                                                         | 84                                                      | 1938                                                   | 90000                                                  | 890855                                                       | 9.9                                                               | 2120000                                                       | 23.56                                                             | 3-06683-0052                       | OCEAN PARKWAY-SOUTH              | D1-ELEVATOR                                 | 35                              | 1931                           | 25075                          | 340920                               | 13.6                                      | 723000                                | 28.8                                      | 1                                           | 3-08470-1018                       | MILL BASIN                       | D9-ELEVATOR                                 | 98                              | 2000                           | 107569                         | 4596080                              | 42.7                                      | 22600000                              | 210                                       | 2.15                                        | 
| 3-07423-0011                                               | SHEEPSHEAD BAY                                           | D4-ELEVATOR                                                         | 240                                                     | 1953                                                   | 242160                                                 | 3562770                                                      | 14.71                                                             | 12000000                                                      | 49.6                                                              | 3-06683-0052                       | OCEAN PARKWAY-SOUTH              | D1-ELEVATOR                                 | 35                              | 1931                           | 25075                          | 340920                               | 13.6                                      | 723000                                | 28.8                                      | 1.55                                        | 3-08470-1018                       | MILL BASIN                       | D9-ELEVATOR                                 | 98                              | 2000                           | 107569                         | 4596080                              | 42.7                                      | 22600000                              | 210                                       | 1.7                                         | 
| 3-01165-0012                                               | PROSPECT HEIGHTS                                         | C6-WALK-UP                                                          | 14                                                      | 1910                                                   | 9340                                                   | 192032                                                       | 20.56                                                             | 795000                                                        | 85                                                                | 3-01162-0010                       | CROWN HEIGHTS                    | C1-WALK-UP                                  | 11                              | 1931                           | 6924                           | 160881                               | 23.24                                     | 666000                                | 96                                        | 0.35                                        | 3-01162-0011                       | CROWN HEIGHTS                    | C1-WALK-UP                                  | 11                              | 1931                           | 7280                           | 162270                               | 22.29                                     | 672000                                | 92                                        | 0.35                                        | 
| 3-04905-0001                                               | FLATBUSH-EAST                                            | D4-ELEVATOR                                                         | 129                                                     | 1956                                                   | 114346                                                 | 1019001                                                      | 8.91                                                              | 2160000                                                       | 18.89                                                             | 3-03806-0017                       | EAST NEW YORK                    | C1-WALK-UP                                  | 16                              | 1930                           | 14784                          | 187372                               | 12.67                                     | 397000                                | 26.9                                      | 2.95                                        | 3-03806-0019                       | EAST NEW YORK                    | C1-WALK-UP                                  | 16                              | 1930                           | 14784                          | 187372                               | 12.67                                     | 397000                                | 26.9                                      | 2.95                                        | 
| 3-05357-0030                                               | OCEAN PARKWAY-NORTH                                      | D4-ELEVATOR                                                         | 94                                                      | 1941                                                   | 106500                                                 | 778473                                                       | 7.31                                                              | 1650000                                                       | 15.49                                                             | 3-05360-0082                       | OCEAN PARKWAY-NORTH              | C1-WALK-UP                                  | 16                              | 1930                           | 11000                          | 107491                               | 9.77                                      | 256000                                | 23.27                                     | 0.2                                         | 3-05362-0002                       | BOROUGH PARK                     | C1-WALK-UP                                  | 12                              | 1930                           | 12800                          | 138510                               | 10.82                                     | 359000                                | 28                                        | 0.65                                        | 
| 3-02100-0072                                               | FORT GREENE                                              | D4-ELEVATOR                                                         | 202                                                     | 1931                                                   | 134500                                                 | 2376762                                                      | 17.67                                                             | 8890000                                                       | 66                                                                | 3-00051-0001                       | DOWNTOWN-FULTON FERRY            | D5-ELEVATOR                                 | 104                             | 1914                           | 123700                         | 2487698                              | 20.11                                     | 9300000                               | 75                                        | 1.25                                        | 3-01798-0040                       | BEDFORD STUYVESANT               | D1-ELEVATOR                                 | 151                             | 1984                           | 128000                         | 2197508                              | 17.17                                     | 4660000                               | 36.4                                      | 1.3                                         | 
| 3-05894-0001                                               | BAY RIDGE                                                | D4-ELEVATOR                                                         | 59                                                      | 1950                                                   | 54432                                                  | 906837                                                       | 16.66                                                             | 3070000                                                       | 56                                                                | 3-06083-0041                       | BAY RIDGE                        | D1-ELEVATOR                                 | 69                              | 1949                           | 66800                          | 1155987                              | 17.31                                     | 4320000                               | 65                                        | 1.3                                         | 3-05881-0038                       | BAY RIDGE                        | D1-ELEVATOR                                 | 69                              | 1960                           | 50400                          | 806953                               | 16.01                                     | 2730000                               | 54                                        | 1                                           | 
```