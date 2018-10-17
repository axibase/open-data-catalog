# DOF: Cooperative Comparable Rental Income ? Queens ? FY 2009/2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-cooperative-comparable-rental-income-queens-fy-2009-2010-bc73d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ykx2-pdw8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ykx2-pdw8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ykx2-pdw8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ykx2-pdw8 |
| Name | DOF: Cooperative Comparable Rental Income ? Queens ? FY 2009/2010 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, rental property, cooperatives, residential, apartment, buildings, rental properties, borough, queens |
| Created | 2011-10-04T20:30:52Z |
| Publication Date | 2013-06-26T17:06:24Z |

## Description

The Department of Finance (DOF) is required by NY State law to value condominiums or cooperatives as if they were residential rental apartment buildings.   DOF uses income information from rental properties similar in physical features and location to the condominiums or cooperatives. DOF applies this income data to the condominium or cooperative and determine its value in the same way DOF values rental apartment buildings.
Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                                                        | Name                                                                  | Data Type | Render Type |
| ======== | ============== | ================================================================= | ===================================================================== | ========= | =========== |
| Yes      | series tag     | queens_cooperatives_comparable_properties_boro_block_lot          | QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Boro-Block-Lot          | text      | text        |
| Yes      | series tag     | queens_cooperatives_comparable_properties_neighborhood            | QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Neighborhood            | text      | text        |
| Yes      | series tag     | queens_cooperatives_comparable_properties_building_classification | QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Building Classification | text      | text        |
| Yes      | numeric metric | queens_cooperatives_comparable_properties_total_units             | QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Total Units             | number    | number      |
| Yes      | numeric metric | queens_cooperatives_comparable_properties_year_built              | QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Year Built              | number    | number      |
| Yes      | numeric metric | queens_cooperatives_comparable_properties_gross_sqft              | QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Gross SqFt              | number    | number      |
| Yes      | numeric metric | queens_cooperatives_comparable_properties_est_gross_income        | QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Est. Gross Income       | number    | number      |
| Yes      | numeric metric | queens_cooperatives_comparable_properties_gross_income_per_sqft   | QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Gross Income per SqFt   | number    | number      |
| Yes      | numeric metric | queens_cooperatives_comparable_properties_full_market_value       | QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Full Market Value       | number    | number      |
| Yes      | numeric metric | queens_cooperatives_comparable_properties_market_value_per_sqft   | QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Market Value per SqFt   | number    | number      |
| Yes      | series tag     | comparable_rental_1_boro_block_lot                                | COMPARABLE RENTAL ? 1 ?Boro-Block-Lot                                 | text      | text        |
| Yes      | series tag     | comparable_rental_1_neighborhood                                  | COMPARABLE RENTAL ? 1 ?Neighborhood                                   | text      | text        |
| Yes      | series tag     | comparable_rental_1_building_classification                       | COMPARABLE RENTAL ? 1 ?Building Classification                        | text      | text        |
| Yes      | numeric metric | comparable_rental_1_total_units                                   | COMPARABLE RENTAL ? 1 ?Total Units                                    | number    | number      |
| Yes      | numeric metric | comparable_rental_1_year_built                                    | COMPARABLE RENTAL ? 1 ?Year Built                                     | number    | number      |
| Yes      | numeric metric | comparable_rental_1_gross_sqft                                    | COMPARABLE RENTAL ? 1 ?Gross SqFt                                     | number    | number      |
| Yes      | numeric metric | comparable_rental_1_est_gross_income                              | COMPARABLE RENTAL ? 1 ?Est. Gross Income                              | number    | number      |
| Yes      | numeric metric | comparable_rental_1_gross_income_per_sqft                         | COMPARABLE RENTAL ? 1 ?Gross Income per SqFt                          | number    | number      |
| Yes      | numeric metric | comparable_rental_1_full_market_value                             | COMPARABLE RENTAL ? 1 ?Full Market Value                              | number    | number      |
| Yes      | numeric metric | comparable_rental_1_market_value_per_sqft                         | COMPARABLE RENTAL ? 1 ?Market Value per SqFt                          | number    | number      |
| Yes      | numeric metric | comparable_rental_1_dist_from_coop_in_miles                       | COMPARABLE RENTAL ? 1 ?Dist. from Coop in miles                       | number    | number      |
| Yes      | series tag     | comparable_rental_2_boro_block_lot                                | COMPARABLE RENTAL ? 2 ?Boro-Block-Lot                                 | text      | text        |
| Yes      | series tag     | comparable_rental_2_neighborhood                                  | COMPARABLE RENTAL ? 2 ?Neighborhood                                   | text      | text        |
| Yes      | series tag     | comparable_rental_2_building_classification                       | COMPARABLE RENTAL ? 2 ?Building Classification                        | text      | text        |
| Yes      | numeric metric | comparable_rental_2_total_units                                   | COMPARABLE RENTAL ? 2 ?Total Units                                    | number    | number      |
| Yes      | numeric metric | comparable_rental_2_year_built                                    | COMPARABLE RENTAL ? 2 ?Year Built                                     | number    | number      |
| Yes      | numeric metric | comparable_rental_2_gross_sqft                                    | COMPARABLE RENTAL ? 2 ?Gross SqFt                                     | number    | number      |
| Yes      | numeric metric | comparable_rental_2_est_gross_income                              | COMPARABLE RENTAL ? 2 ?Est. Gross Income                              | number    | number      |
| Yes      | numeric metric | comparable_rental_2_gross_income_per_sqft                         | COMPARABLE RENTAL ? 2 ?Gross Income per SqFt                          | number    | number      |
| Yes      | numeric metric | comparable_rental_2_full_market_value                             | COMPARABLE RENTAL ? 2 ?Full Market Value                              | number    | number      |
| Yes      | numeric metric | comparable_rental_2_market_value_per_sqft                         | COMPARABLE RENTAL ? 2 ?Market Value per SqFt                          | number    | number      |
| Yes      | numeric metric | comparable_rental_2_dist_from_coop_in_miles                       | COMPARABLE RENTAL ? 2 ?Dist. from Coop in miles                       | number    | number      |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ykx2-pdw8 d:2009-01-01T00:00:00.000Z t:comparable_rental_2_boro_block_lot=4-02319-0010 t:comparable_rental_1_building_classification=D7-ELEVATOR t:comparable_rental_1_boro_block_lot=4-02104-0001 t:queens_cooperatives_comparable_properties_boro_block_lot=4-00128-0007 t:queens_cooperatives_comparable_properties_neighborhood=WOODSIDE t:comparable_rental_1_neighborhood="REGO PARK" t:queens_cooperatives_comparable_properties_building_classification=D4-ELEVATOR t:comparable_rental_2_building_classification=D3-ELEVATOR t:comparable_rental_2_neighborhood=WOODSIDE m:comparable_rental_2_market_value_per_sqft=27.1 m:queens_cooperatives_comparable_properties_market_value_per_sqft=40.5 m:comparable_rental_2_full_market_value=6490000 m:queens_cooperatives_comparable_properties_total_units=426 m:comparable_rental_1_total_units=206 m:comparable_rental_1_year_built=1952 m:comparable_rental_1_gross_sqft=204340 m:comparable_rental_1_dist_from_coop_in_miles=3.25 m:comparable_rental_2_year_built=1970 m:comparable_rental_1_full_market_value=8280000 m:comparable_rental_1_gross_income_per_sqft=11.49 m:queens_cooperatives_comparable_properties_year_built=1951 m:comparable_rental_2_gross_income_per_sqft=9.6 m:comparable_rental_2_dist_from_coop_in_miles=0.6 m:comparable_rental_2_est_gross_income=2297319 m:queens_cooperatives_comparable_properties_gross_income_per_sqft=11.5 m:queens_cooperatives_comparable_properties_est_gross_income=4429800 m:comparable_rental_1_market_value_per_sqft=40.5 m:comparable_rental_2_total_units=233 m:queens_cooperatives_comparable_properties_gross_sqft=385200 m:comparable_rental_2_gross_sqft=239190 m:comparable_rental_1_est_gross_income=2347652 m:queens_cooperatives_comparable_properties_full_market_value=15600000

series e:ykx2-pdw8 d:2009-01-01T00:00:00.000Z t:comparable_rental_2_boro_block_lot=4-02104-0001 t:comparable_rental_1_building_classification=D3-ELEVATOR t:comparable_rental_1_boro_block_lot=4-02319-0010 t:queens_cooperatives_comparable_properties_boro_block_lot=4-00125-0028 t:queens_cooperatives_comparable_properties_neighborhood=SUNNYSIDE t:comparable_rental_1_neighborhood=WOODSIDE t:queens_cooperatives_comparable_properties_building_classification=D4-ELEVATOR t:comparable_rental_2_building_classification=D7-ELEVATOR t:comparable_rental_2_neighborhood="REGO PARK" m:comparable_rental_2_market_value_per_sqft=40.5 m:queens_cooperatives_comparable_properties_market_value_per_sqft=40.5 m:comparable_rental_2_full_market_value=8280000 m:queens_cooperatives_comparable_properties_total_units=158 m:comparable_rental_1_total_units=233 m:comparable_rental_1_year_built=1970 m:comparable_rental_1_gross_sqft=239190 m:comparable_rental_1_dist_from_coop_in_miles=0.85 m:comparable_rental_2_year_built=1952 m:comparable_rental_1_full_market_value=6490000 m:comparable_rental_1_gross_income_per_sqft=9.6 m:queens_cooperatives_comparable_properties_year_built=1961 m:comparable_rental_2_gross_income_per_sqft=11.49 m:comparable_rental_2_dist_from_coop_in_miles=3.5 m:comparable_rental_2_est_gross_income=2347652 m:queens_cooperatives_comparable_properties_gross_income_per_sqft=11.5 m:queens_cooperatives_comparable_properties_est_gross_income=1791125 m:comparable_rental_1_market_value_per_sqft=27.1 m:comparable_rental_2_total_units=206 m:queens_cooperatives_comparable_properties_gross_sqft=155750 m:comparable_rental_2_gross_sqft=204340 m:comparable_rental_1_est_gross_income=2297319 m:queens_cooperatives_comparable_properties_full_market_value=6310000

series e:ykx2-pdw8 d:2009-01-01T00:00:00.000Z t:comparable_rental_2_boro_block_lot=4-06797-0054 t:comparable_rental_1_building_classification=D8-ELEVATOR t:comparable_rental_1_boro_block_lot=4-06809-0001 t:queens_cooperatives_comparable_properties_boro_block_lot=4-00018-0001 t:queens_cooperatives_comparable_properties_neighborhood="LONG ISLAND CITY" t:comparable_rental_1_neighborhood=FLUSHING-SOUTH t:queens_cooperatives_comparable_properties_building_classification=D4-ELEVATOR t:comparable_rental_2_building_classification=D6-ELEVATOR t:comparable_rental_2_neighborhood=FLUSHING-SOUTH m:comparable_rental_2_market_value_per_sqft=126 m:queens_cooperatives_comparable_properties_market_value_per_sqft=62 m:comparable_rental_2_full_market_value=26300000 m:queens_cooperatives_comparable_properties_total_units=536 m:comparable_rental_1_total_units=388 m:comparable_rental_1_year_built=2004 m:comparable_rental_1_gross_sqft=534846 m:comparable_rental_1_dist_from_coop_in_miles=7.8 m:comparable_rental_2_year_built=2000 m:comparable_rental_1_full_market_value=86700000 m:comparable_rental_1_gross_income_per_sqft=33.5 m:queens_cooperatives_comparable_properties_year_built=1996 m:comparable_rental_2_gross_income_per_sqft=25.9 m:comparable_rental_2_dist_from_coop_in_miles=7.9 m:comparable_rental_2_est_gross_income=5430133 m:queens_cooperatives_comparable_properties_gross_income_per_sqft=15.3 m:queens_cooperatives_comparable_properties_est_gross_income=11084467 m:comparable_rental_1_market_value_per_sqft=162 m:comparable_rental_2_total_units=142 m:queens_cooperatives_comparable_properties_gross_sqft=724475 m:comparable_rental_2_gross_sqft=209525 m:comparable_rental_1_est_gross_income=17900000 m:queens_cooperatives_comparable_properties_full_market_value=45100000
```

## Meta Commands

```ls
metric m:queens_cooperatives_comparable_properties_total_units p:integer l:"QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Total Units" t:dataTypeName=number

metric m:queens_cooperatives_comparable_properties_year_built p:integer l:"QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Year Built" t:dataTypeName=number

metric m:queens_cooperatives_comparable_properties_gross_sqft p:integer l:"QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Gross SqFt" t:dataTypeName=number

metric m:queens_cooperatives_comparable_properties_est_gross_income p:integer l:"QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Est. Gross Income" t:dataTypeName=number

metric m:queens_cooperatives_comparable_properties_gross_income_per_sqft p:float l:"QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Gross Income per SqFt" t:dataTypeName=number

metric m:queens_cooperatives_comparable_properties_full_market_value p:integer l:"QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Full Market Value" t:dataTypeName=number

metric m:queens_cooperatives_comparable_properties_market_value_per_sqft p:double l:"QUEENS ? COOPERATIVES COMPARABLE PROPERTIES ? Market Value per SqFt" t:dataTypeName=number

metric m:comparable_rental_1_total_units p:integer l:"COMPARABLE RENTAL ? 1 ?Total Units" t:dataTypeName=number

metric m:comparable_rental_1_year_built p:integer l:"COMPARABLE RENTAL ? 1 ?Year Built" t:dataTypeName=number

metric m:comparable_rental_1_gross_sqft p:integer l:"COMPARABLE RENTAL ? 1 ?Gross SqFt" t:dataTypeName=number

metric m:comparable_rental_1_est_gross_income p:integer l:"COMPARABLE RENTAL ? 1 ?Est. Gross Income" t:dataTypeName=number

metric m:comparable_rental_1_gross_income_per_sqft p:float l:"COMPARABLE RENTAL ? 1 ?Gross Income per SqFt" t:dataTypeName=number

metric m:comparable_rental_1_full_market_value p:integer l:"COMPARABLE RENTAL ? 1 ?Full Market Value" t:dataTypeName=number

metric m:comparable_rental_1_market_value_per_sqft p:double l:"COMPARABLE RENTAL ? 1 ?Market Value per SqFt" t:dataTypeName=number

metric m:comparable_rental_1_dist_from_coop_in_miles p:float l:"COMPARABLE RENTAL ? 1 ?Dist. from Coop in miles" t:dataTypeName=number

metric m:comparable_rental_2_total_units p:integer l:"COMPARABLE RENTAL ? 2 ?Total Units" t:dataTypeName=number

metric m:comparable_rental_2_year_built p:integer l:"COMPARABLE RENTAL ? 2 ?Year Built" t:dataTypeName=number

metric m:comparable_rental_2_gross_sqft p:integer l:"COMPARABLE RENTAL ? 2 ?Gross SqFt" t:dataTypeName=number

metric m:comparable_rental_2_est_gross_income p:integer l:"COMPARABLE RENTAL ? 2 ?Est. Gross Income" t:dataTypeName=number

metric m:comparable_rental_2_gross_income_per_sqft p:float l:"COMPARABLE RENTAL ? 2 ?Gross Income per SqFt" t:dataTypeName=number

metric m:comparable_rental_2_full_market_value p:integer l:"COMPARABLE RENTAL ? 2 ?Full Market Value" t:dataTypeName=number

metric m:comparable_rental_2_market_value_per_sqft p:double l:"COMPARABLE RENTAL ? 2 ?Market Value per SqFt" t:dataTypeName=number

metric m:comparable_rental_2_dist_from_coop_in_miles p:float l:"COMPARABLE RENTAL ? 2 ?Dist. from Coop in miles" t:dataTypeName=number

entity e:ykx2-pdw8 l:"DOF: Cooperative Comparable Rental Income ? Queens ? FY 2009/2010" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/ykx2-pdw8

property e:ykx2-pdw8 t:meta.view v:id=ykx2-pdw8 v:category="Housing & Development" v:averageRating=0 v:name="DOF: Cooperative Comparable Rental Income ? Queens ? FY 2009/2010" v:attribution="Department of Finance (DOF)"

property e:ykx2-pdw8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ykx2-pdw8 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| queens_cooperatives_comparable_properties_boro_block_lot | queens_cooperatives_comparable_properties_neighborhood | queens_cooperatives_comparable_properties_building_classification | queens_cooperatives_comparable_properties_total_units | queens_cooperatives_comparable_properties_year_built | queens_cooperatives_comparable_properties_gross_sqft | queens_cooperatives_comparable_properties_est_gross_income | queens_cooperatives_comparable_properties_gross_income_per_sqft | queens_cooperatives_comparable_properties_full_market_value | queens_cooperatives_comparable_properties_market_value_per_sqft | comparable_rental_1_boro_block_lot | comparable_rental_1_neighborhood | comparable_rental_1_building_classification | comparable_rental_1_total_units | comparable_rental_1_year_built | comparable_rental_1_gross_sqft | comparable_rental_1_est_gross_income | comparable_rental_1_gross_income_per_sqft | comparable_rental_1_full_market_value | comparable_rental_1_market_value_per_sqft | comparable_rental_1_dist_from_coop_in_miles | comparable_rental_2_boro_block_lot | comparable_rental_2_neighborhood | comparable_rental_2_building_classification | comparable_rental_2_total_units | comparable_rental_2_year_built | comparable_rental_2_gross_sqft | comparable_rental_2_est_gross_income | comparable_rental_2_gross_income_per_sqft | comparable_rental_2_full_market_value | comparable_rental_2_market_value_per_sqft | comparable_rental_2_dist_from_coop_in_miles | 
| ======================================================== | ====================================================== | ================================================================= | ===================================================== | ==================================================== | ==================================================== | ========================================================== | =============================================================== | =========================================================== | =============================================================== | ================================== | ================================ | =========================================== | =============================== | ============================== | ============================== | ==================================== | ========================================= | ===================================== | ========================================= | =========================================== | ================================== | ================================ | =========================================== | =============================== | ============================== | ============================== | ==================================== | ========================================= | ===================================== | ========================================= | =========================================== | 
| 4-00128-0007                                             | WOODSIDE                                               | D4-ELEVATOR                                                       | 426                                                   | 1951                                                 | 385200                                               | 4429800                                                    | 11.5                                                            | 15600000                                                    | 40.5                                                            | 4-02104-0001                       | REGO PARK                        | D7-ELEVATOR                                 | 206                             | 1952                           | 204340                         | 2347652                              | 11.49                                     | 8280000                               | 40.5                                      | 3.25                                        | 4-02319-0010                       | WOODSIDE                         | D3-ELEVATOR                                 | 233                             | 1970                           | 239190                         | 2297319                              | 9.6                                       | 6490000                               | 27.1                                      | 0.6                                         | 
| 4-00125-0028                                             | SUNNYSIDE                                              | D4-ELEVATOR                                                       | 158                                                   | 1961                                                 | 155750                                               | 1791125                                                    | 11.5                                                            | 6310000                                                     | 40.5                                                            | 4-02319-0010                       | WOODSIDE                         | D3-ELEVATOR                                 | 233                             | 1970                           | 239190                         | 2297319                              | 9.6                                       | 6490000                               | 27.1                                      | 0.85                                        | 4-02104-0001                       | REGO PARK                        | D7-ELEVATOR                                 | 206                             | 1952                           | 204340                         | 2347652                              | 11.49                                     | 8280000                               | 40.5                                      | 3.5                                         | 
| 4-00018-0001                                             | LONG ISLAND CITY                                       | D4-ELEVATOR                                                       | 536                                                   | 1996                                                 | 724475                                               | 11084467                                                   | 15.3                                                            | 45100000                                                    | 62                                                              | 4-06809-0001                       | FLUSHING-SOUTH                   | D8-ELEVATOR                                 | 388                             | 2004                           | 534846                         | 17900000                             | 33.5                                      | 86700000                              | 162                                       | 7.8                                         | 4-06797-0054                       | FLUSHING-SOUTH                   | D6-ELEVATOR                                 | 142                             | 2000                           | 209525                         | 5430133                              | 25.9                                      | 26300000                              | 126                                       | 7.9                                         | 
| 4-08929-0106                                             | WOODHAVEN                                              | D4-ELEVATOR                                                       | 66                                                    | 1938                                                 | 64512                                                | 709632                                                     | 11                                                              | 2500000                                                     | 38.8                                                            | 4-09677-0167                       | JAMAICA                          | D1-ELEVATOR                                 | 54                              | 1928                           | 61000                          | 677927                               | 11.11                                     | 2390000                               | 39.2                                      | 2.5                                         | 4-10461-0057                       | HOLLIS                           | D1-ELEVATOR                                 | 62                              | 1939                           | 53200                          | 584966                               | 11                                        | 2060000                               | 38.7                                      | 4.75                                        | 
| 4-03099-0025                                             | REGO PARK                                              | D4-ELEVATOR                                                       | 47                                                    | 1947                                                 | 39600                                                | 514800                                                     | 13                                                              | 1940000                                                     | 49                                                              | 4-03083-0085                       | REGO PARK                        | D1-ELEVATOR                                 | 62                              | 1937                           | 62400                          | 748781                               | 12                                        | 2640000                               | 42.3                                      | 0.25                                        | 4-03094-0034                       | REGO PARK                        | D1-ELEVATOR                                 | 72                              | 1936                           | 73620                          | 940500                               | 12.78                                     | 3540000                               | 48.1                                      | 0.4                                         | 
| 4-01279-0058                                             | JACKSON HEIGHTS                                        | D4-ELEVATOR                                                       | 82                                                    | 1948                                                 | 70000                                                | 790300                                                     | 11.29                                                           | 2790000                                                     | 39.9                                                            | 4-16083-0037                       | ARVERNE                          | D3-ELEVATOR                                 | 174                             | 1964                           | 155000                         | 4256300                              | 27.5                                      | 20600000                              | 133                                       | 11.9                                        | 4-00490-0101                       | ASTORIA                          | D1-ELEVATOR                                 | 1104                            | 1950                           | 1116500                        | 11310145                             | 10.13                                     | 38200000                              | 34.2                                      | 2.95                                        | 
| 4-02186-0002                                             | FOREST HILLS                                           | C6-WALK-UP                                                        | 138                                                   | 1949                                                 | 105201                                               | 1341312                                                    | 12.75                                                           | 5040000                                                     | 47.9                                                            | 4-01743-0047                       | CORONA                           | C1-WALK-UP                                  | 20                              | 1926                           | 15752                          | 192140                               | 12.2                                      | 722000                                | 45.8                                      | 1.85                                        | 4-01532-0016                       | ELMHURST                         | C1-WALK-UP                                  | 16                              | 1933                           | 14952                          | 194104                               | 12.98                                     | 730000                                | 48.8                                      | 2.2                                         | 
| 4-04588-0024                                             | BEECHHURST                                             | D4-ELEVATOR                                                       | 32                                                    | 1958                                                 | 40692                                                | 467958                                                     | 11.5                                                            | 1650000                                                     | 40.5                                                            | 4-05013-0031                       | FLUSHING-NORTH                   | D1-ELEVATOR                                 | 42                              | 1957                           | 43000                          | 453667                               | 10.55                                     | 1530000                               | 35.6                                      | 2.5                                         | 4-05022-0008                       | FLUSHING-NORTH                   | D1-ELEVATOR                                 | 62                              | 1962                           | 48786                          | 607904                               | 12.46                                     | 2290000                               | 46.9                                      | 2.55                                        | 
| 4-01679-0001                                             | EAST ELMHURST                                          | D4-ELEVATOR                                                       | 40                                                    | 1965                                                 | 39267                                                | 471204                                                     | 12                                                              | 1660000                                                     | 42.3                                                            | 4-01492-0032                       | ELMHURST                         | D7-ELEVATOR                                 | 53                              | 1963                           | 33600                          | 406614                               | 12.1                                      | 1430000                               | 42.6                                      | 1.6                                         | 4-01459-0040                       | JACKSON HEIGHTS                  | D7-ELEVATOR                                 | 66                              | 1957                           | 48300                          | 643345                               | 13.32                                     | 2420000                               | 50                                        | 1.3                                         | 
| 4-02235-0004                                             | FOREST HILLS                                           | D4-ELEVATOR                                                       | 188                                                   | 1956                                                 | 215735                                               | 3128157                                                    | 14.5                                                            | 12400000                                                    | 57                                                              | 4-02236-0012                       | FOREST HILLS                     | D1-ELEVATOR                                 | 108                             | 1951                           | 95644                          | 1418367                              | 14.83                                     | 5620000                               | 59                                        | 0.05                                        | 4-04994-0078                       | FLUSHING-NORTH                   | D1-ELEVATOR                                 | 90                              | 1967                           | 79050                          | 1089693                              | 13.78                                     | 4320000                               | 55                                        | 3.15                                        | 
```