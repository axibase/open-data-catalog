# DOF: Condominium Comparable Rental Income ? Queens ? FY 2008/2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dof-condominium-comparable-rental-income-queens-fy-2008-2009-15cd4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/m59i-mqex) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/m59i-mqex/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/m59i-mqex/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | m59i-mqex |
| Name | DOF: Condominium Comparable Rental Income ? Queens ? FY 2008/2009 |
| Attribution | Department of Finance (DOF) |
| Category | Housing & Development |
| Tags | department of finance, finance, dof, rental property, condominiums, cooperatives, residential, apartment, buildings, rental properties, queens, borough |
| Created | 2011-09-29T20:37:34Z |
| Publication Date | 2013-06-26T17:08:23Z |

## Description

The Department of Finance (DOF) is required by NY State law to value condominiums or cooperatives as if they were residential rental apartment buildings.   DOF uses income information from rental properties similar in physical features and location to the condominiums or cooperatives. DOF applies this income data to the condominium or cooperative and determine its value in the same way DOF values rental apartment buildings.
Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                                          | Name                                                | Data Type | Render Type |
| ======== | ============== | =================================================== | =================================================== | ========= | =========== |
| Yes      | series tag     | queens_condominium_property_boro_block_lot          | QUEENS CONDOMINIUM PROPERTY Boro-Block-Lot          | text      | text        |
| Yes      | series tag     | queens_condominium_property_condo_section           | QUEENS CONDOMINIUM PROPERTY Condo Section           | text      | text        |
| Yes      | series tag     | queens_condominium_property_neighborhood            | QUEENS CONDOMINIUM PROPERTY Neighborhood            | text      | text        |
| Yes      | series tag     | queens_condominium_property_building_classification | QUEENS CONDOMINIUM PROPERTY Building Classification | text      | text        |
| Yes      | numeric metric | queens_condominium_property_total_units             | QUEENS CONDOMINIUM PROPERTY Total Units             | number    | number      |
| Yes      | numeric metric | queens_condominium_property_year_built              | QUEENS CONDOMINIUM PROPERTY Year Built              | number    | number      |
| Yes      | numeric metric | queens_condominium_property_gross_sqft              | QUEENS CONDOMINIUM PROPERTY Gross SqFt              | number    | number      |
| Yes      | numeric metric | queens_condominium_property_est_gross_income        | QUEENS CONDOMINIUM PROPERTY Est. Gross Income       | number    | number      |
| Yes      | numeric metric | queens_condominium_property_gross_income_per_sqft   | QUEENS CONDOMINIUM PROPERTY Gross Income per SqFt   | number    | number      |
| Yes      | numeric metric | queens_condominium_property_full_market_value       | QUEENS CONDOMINIUM PROPERTY Full Market Value       | number    | number      |
| Yes      | numeric metric | queens_condominium_property_market_value_per_sqft   | QUEENS CONDOMINIUM PROPERTY Market Value per SqFt   | number    | number      |
| Yes      | series tag     | comparable_rental_1_boro_block_lot                  | COMPARABLE RENTAL 1 Boro-Block-Lot                  | text      | text        |
| Yes      | series tag     | comparable_rental_1_neighborhood                    | COMPARABLE RENTAL 1 Neighborhood                    | text      | text        |
| Yes      | series tag     | comparable_rental_1_building_classification         | COMPARABLE RENTAL 1 Building Classification         | text      | text        |
| Yes      | numeric metric | comparable_rental_1_total_units                     | COMPARABLE RENTAL 1 Total Units                     | number    | number      |
| Yes      | numeric metric | comparable_rental_1_year_built                      | COMPARABLE RENTAL 1 Year Built                      | number    | number      |
| Yes      | numeric metric | comparable_rental_1_gross_sqft                      | COMPARABLE RENTAL 1 Gross SqFt                      | number    | number      |
| Yes      | numeric metric | comparable_rental_1_est_gross_income                | COMPARABLE RENTAL 1 Est. Gross Income               | number    | number      |
| Yes      | numeric metric | comparable_rental_1_gross_income_per_sqft           | COMPARABLE RENTAL 1 Gross Income per SqFt           | number    | number      |
| Yes      | numeric metric | comparable_rental_1_full_market_value               | COMPARABLE RENTAL 1 Full Market Value               | number    | number      |
| Yes      | numeric metric | comparable_rental_1_market_value_per_sqft           | COMPARABLE RENTAL 1 Market Value per SqFt           | number    | number      |
| Yes      | numeric metric | comparable_rental_1_dist_from_coop_in_miles         | COMPARABLE RENTAL 1 Dist. from Coop in miles        | number    | number      |
| Yes      | series tag     | comparable_rental_2_boro_block_lot                  | COMPARABLE RENTAL 2 Boro-Block-Lot                  | text      | text        |
| Yes      | series tag     | comparable_rental_2_neighborhood                    | COMPARABLE RENTAL 2 Neighborhood                    | text      | text        |
| Yes      | series tag     | comparable_rental_2_building_classification         | COMPARABLE RENTAL 2 Building Classification         | text      | text        |
| Yes      | numeric metric | comparable_rental_2_total_units                     | COMPARABLE RENTAL 2 Total Units                     | number    | number      |
| Yes      | numeric metric | comparable_rental_2_year_built                      | COMPARABLE RENTAL 2 Year Built                      | number    | number      |
| Yes      | numeric metric | comparable_rental_2_gross_sqft                      | COMPARABLE RENTAL 2 Gross SqFt                      | number    | number      |
| Yes      | numeric metric | comparable_rental_2_est_gross_income                | COMPARABLE RENTAL 2 Est. Gross Income               | number    | number      |
| Yes      | numeric metric | comparable_rental_2_gross_income_per_sqft           | COMPARABLE RENTAL 2 Gross Income per SqFt           | number    | number      |
| Yes      | numeric metric | comparable_rental_2_full_market_value               | COMPARABLE RENTAL 2 Full Market Value               | number    | number      |
| Yes      | numeric metric | comparable_rental_2_market_value_per_sqft           | COMPARABLE RENTAL 2 Market Value per SqFt           | number    | number      |
| Yes      | numeric metric | comparable_rental_2_dist_from_coop_in_miles         | COMPARABLE RENTAL 2 Dist. from Coop in miles        | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m59i-mqex d:2008-01-01T00:00:00.000Z t:comparable_rental_2_boro_block_lot=4-00638-0025 t:queens_condominium_property_condo_section=478-R1 t:comparable_rental_1_building_classification=D7-ELEVATOR t:comparable_rental_1_boro_block_lot=4-00342-0024 t:queens_condominium_property_boro_block_lot=4-00031-7501 t:queens_condominium_property_building_classification=R2-WALK-UP t:queens_condominium_property_neighborhood="LONG ISLAND CITY" t:comparable_rental_1_neighborhood="LONG ISLAND CITY" t:comparable_rental_2_building_classification=C7-WALK-UP t:comparable_rental_2_neighborhood="LONG ISLAND CITY" m:comparable_rental_2_market_value_per_sqft=69 m:queens_condominium_property_full_market_value=9140004 m:comparable_rental_2_full_market_value=2970000 m:comparable_rental_1_total_units=66 m:queens_condominium_property_gross_income_per_sqft=30 m:comparable_rental_1_year_built=1929 m:comparable_rental_1_dist_from_coop_in_miles=1.5 m:comparable_rental_1_gross_sqft=61000 m:comparable_rental_2_year_built=1926 m:queens_condominium_property_gross_sqft=62866 m:comparable_rental_1_full_market_value=2800000 m:queens_condominium_property_year_built=2005 m:comparable_rental_1_gross_income_per_sqft=12.21 m:queens_condominium_property_market_value_per_sqft=145 m:comparable_rental_2_gross_income_per_sqft=16.87 m:queens_condominium_property_est_gross_income=1885980 m:comparable_rental_2_dist_from_coop_in_miles=1.7 m:comparable_rental_2_est_gross_income=730295 m:comparable_rental_1_market_value_per_sqft=45.9 m:comparable_rental_2_total_units=61 m:comparable_rental_2_gross_sqft=43300 m:comparable_rental_1_est_gross_income=745000 m:queens_condominium_property_total_units=47

series e:m59i-mqex d:2008-01-01T00:00:00.000Z t:comparable_rental_2_boro_block_lot=4-00192-0007 t:queens_condominium_property_condo_section=498-R1 t:comparable_rental_1_building_classification=C1-WALK-UP t:comparable_rental_1_boro_block_lot=4-02289-0020 t:queens_condominium_property_boro_block_lot=4-00134-7501 t:queens_condominium_property_building_classification=R4-ELEVATOR t:queens_condominium_property_neighborhood=SUNNYSIDE t:comparable_rental_1_neighborhood=SUNNYSIDE t:comparable_rental_2_building_classification=C1-WALK-UP t:comparable_rental_2_neighborhood=SUNNYSIDE m:comparable_rental_2_market_value_per_sqft=54 m:queens_condominium_property_full_market_value=878994 m:comparable_rental_2_full_market_value=908000 m:comparable_rental_1_total_units=23 m:queens_condominium_property_gross_income_per_sqft=14.2 m:comparable_rental_1_year_built=1928 m:comparable_rental_1_dist_from_coop_in_miles=0.55 m:comparable_rental_1_gross_sqft=16400 m:comparable_rental_2_year_built=1931 m:queens_condominium_property_gross_sqft=15610 m:comparable_rental_1_full_market_value=549000 m:queens_condominium_property_year_built=2005 m:comparable_rental_1_gross_income_per_sqft=9.9 m:queens_condominium_property_market_value_per_sqft=56 m:comparable_rental_2_gross_income_per_sqft=13.6 m:queens_condominium_property_est_gross_income=221662 m:comparable_rental_2_dist_from_coop_in_miles=0.45 m:comparable_rental_2_est_gross_income=229061 m:comparable_rental_1_market_value_per_sqft=33.5 m:comparable_rental_2_total_units=24 m:comparable_rental_2_gross_sqft=16840 m:comparable_rental_1_est_gross_income=162364 m:queens_condominium_property_total_units=15

series e:m59i-mqex d:2008-01-01T00:00:00.000Z t:comparable_rental_2_boro_block_lot=4-00531-0059 t:queens_condominium_property_condo_section=487-R1 t:comparable_rental_1_building_classification=D1-ELEVATOR t:comparable_rental_1_boro_block_lot=4-00531-0060 t:queens_condominium_property_boro_block_lot=4-00032-7501 t:queens_condominium_property_building_classification=R4-ELEVATOR t:queens_condominium_property_neighborhood="LONG ISLAND CITY" t:comparable_rental_1_neighborhood=ASTORIA t:comparable_rental_2_building_classification=D6-ELEVATOR t:comparable_rental_2_neighborhood=ASTORIA m:comparable_rental_2_market_value_per_sqft=92 m:queens_condominium_property_full_market_value=1699509 m:comparable_rental_2_full_market_value=5690000 m:comparable_rental_1_total_units=52 m:queens_condominium_property_gross_income_per_sqft=20.62 m:comparable_rental_1_year_built=2002 m:comparable_rental_1_dist_from_coop_in_miles=2 m:comparable_rental_1_gross_sqft=46333 m:comparable_rental_2_year_built=2001 m:queens_condominium_property_gross_sqft=18375 m:comparable_rental_1_full_market_value=3470000 m:queens_condominium_property_year_built=2006 m:comparable_rental_1_gross_income_per_sqft=18.41 m:queens_condominium_property_market_value_per_sqft=92 m:comparable_rental_2_gross_income_per_sqft=20.62 m:queens_condominium_property_est_gross_income=378900 m:comparable_rental_2_dist_from_coop_in_miles=2 m:comparable_rental_2_est_gross_income=1272343 m:comparable_rental_1_market_value_per_sqft=75 m:comparable_rental_2_total_units=63 m:comparable_rental_2_gross_sqft=61700 m:comparable_rental_1_est_gross_income=852831 m:queens_condominium_property_total_units=13
```

## Meta Commands

```ls
metric m:queens_condominium_property_total_units p:integer l:"QUEENS CONDOMINIUM PROPERTY Total Units" t:dataTypeName=number

metric m:queens_condominium_property_year_built p:integer l:"QUEENS CONDOMINIUM PROPERTY Year Built" t:dataTypeName=number

metric m:queens_condominium_property_gross_sqft p:integer l:"QUEENS CONDOMINIUM PROPERTY Gross SqFt" t:dataTypeName=number

metric m:queens_condominium_property_est_gross_income p:integer l:"QUEENS CONDOMINIUM PROPERTY Est. Gross Income" t:dataTypeName=number

metric m:queens_condominium_property_gross_income_per_sqft p:double l:"QUEENS CONDOMINIUM PROPERTY Gross Income per SqFt" t:dataTypeName=number

metric m:queens_condominium_property_full_market_value p:integer l:"QUEENS CONDOMINIUM PROPERTY Full Market Value" t:dataTypeName=number

metric m:queens_condominium_property_market_value_per_sqft p:double l:"QUEENS CONDOMINIUM PROPERTY Market Value per SqFt" t:dataTypeName=number

metric m:comparable_rental_1_total_units p:integer l:"COMPARABLE RENTAL 1 Total Units" t:dataTypeName=number

metric m:comparable_rental_1_year_built p:integer l:"COMPARABLE RENTAL 1 Year Built" t:dataTypeName=number

metric m:comparable_rental_1_gross_sqft p:integer l:"COMPARABLE RENTAL 1 Gross SqFt" t:dataTypeName=number

metric m:comparable_rental_1_est_gross_income p:integer l:"COMPARABLE RENTAL 1 Est. Gross Income" t:dataTypeName=number

metric m:comparable_rental_1_gross_income_per_sqft p:float l:"COMPARABLE RENTAL 1 Gross Income per SqFt" t:dataTypeName=number

metric m:comparable_rental_1_full_market_value p:integer l:"COMPARABLE RENTAL 1 Full Market Value" t:dataTypeName=number

metric m:comparable_rental_1_market_value_per_sqft p:double l:"COMPARABLE RENTAL 1 Market Value per SqFt" t:dataTypeName=number

metric m:comparable_rental_1_dist_from_coop_in_miles p:float l:"COMPARABLE RENTAL 1 Dist. from Coop in miles" t:dataTypeName=number

metric m:comparable_rental_2_total_units p:integer l:"COMPARABLE RENTAL 2 Total Units" t:dataTypeName=number

metric m:comparable_rental_2_year_built p:integer l:"COMPARABLE RENTAL 2 Year Built" t:dataTypeName=number

metric m:comparable_rental_2_gross_sqft p:integer l:"COMPARABLE RENTAL 2 Gross SqFt" t:dataTypeName=number

metric m:comparable_rental_2_est_gross_income p:integer l:"COMPARABLE RENTAL 2 Est. Gross Income" t:dataTypeName=number

metric m:comparable_rental_2_gross_income_per_sqft p:float l:"COMPARABLE RENTAL 2 Gross Income per SqFt" t:dataTypeName=number

metric m:comparable_rental_2_full_market_value p:integer l:"COMPARABLE RENTAL 2 Full Market Value" t:dataTypeName=number

metric m:comparable_rental_2_market_value_per_sqft p:double l:"COMPARABLE RENTAL 2 Market Value per SqFt" t:dataTypeName=number

metric m:comparable_rental_2_dist_from_coop_in_miles p:float l:"COMPARABLE RENTAL 2 Dist. from Coop in miles" t:dataTypeName=number

entity e:m59i-mqex l:"DOF: Condominium Comparable Rental Income ? Queens ? FY 2008/2009" t:attribution="Department of Finance (DOF)" t:url=https://data.cityofnewyork.us/api/views/m59i-mqex

property e:m59i-mqex t:meta.view v:id=m59i-mqex v:category="Housing & Development" v:averageRating=0 v:name="DOF: Condominium Comparable Rental Income ? Queens ? FY 2008/2009" v:attribution="Department of Finance (DOF)"

property e:m59i-mqex t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:m59i-mqex t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| queens_condominium_property_boro_block_lot | queens_condominium_property_condo_section | queens_condominium_property_neighborhood | queens_condominium_property_building_classification | queens_condominium_property_total_units | queens_condominium_property_year_built | queens_condominium_property_gross_sqft | queens_condominium_property_est_gross_income | queens_condominium_property_gross_income_per_sqft | queens_condominium_property_full_market_value | queens_condominium_property_market_value_per_sqft | comparable_rental_1_boro_block_lot | comparable_rental_1_neighborhood | comparable_rental_1_building_classification | comparable_rental_1_total_units | comparable_rental_1_year_built | comparable_rental_1_gross_sqft | comparable_rental_1_est_gross_income | comparable_rental_1_gross_income_per_sqft | comparable_rental_1_full_market_value | comparable_rental_1_market_value_per_sqft | comparable_rental_1_dist_from_coop_in_miles | comparable_rental_2_boro_block_lot | comparable_rental_2_neighborhood | comparable_rental_2_building_classification | comparable_rental_2_total_units | comparable_rental_2_year_built | comparable_rental_2_gross_sqft | comparable_rental_2_est_gross_income | comparable_rental_2_gross_income_per_sqft | comparable_rental_2_full_market_value | comparable_rental_2_market_value_per_sqft | comparable_rental_2_dist_from_coop_in_miles | 
| ========================================== | ========================================= | ======================================== | =================================================== | ======================================= | ====================================== | ====================================== | ============================================ | ================================================= | ============================================= | ================================================= | ================================== | ================================ | =========================================== | =============================== | ============================== | ============================== | ==================================== | ========================================= | ===================================== | ========================================= | =========================================== | ================================== | ================================ | =========================================== | =============================== | ============================== | ============================== | ==================================== | ========================================= | ===================================== | ========================================= | =========================================== | 
| 4-00031-7501                               | 478-R1                                    | LONG ISLAND CITY                         | R2-WALK-UP                                          | 47                                      | 2005                                   | 62866                                  | 1885980                                      | 30                                                | 9140004                                       | 145                                               | 4-00342-0024                       | LONG ISLAND CITY                 | D7-ELEVATOR                                 | 66                              | 1929                           | 61000                          | 745000                               | 12.21                                     | 2800000                               | 45.9                                      | 1.5                                         | 4-00638-0025                       | LONG ISLAND CITY                 | C7-WALK-UP                                  | 61                              | 1926                           | 43300                          | 730295                               | 16.87                                     | 2970000                               | 69                                        | 1.7                                         | 
| 4-00134-7501                               | 498-R1                                    | SUNNYSIDE                                | R4-ELEVATOR                                         | 15                                      | 2005                                   | 15610                                  | 221662                                       | 14.2                                              | 878994                                        | 56                                                | 4-02289-0020                       | SUNNYSIDE                        | C1-WALK-UP                                  | 23                              | 1928                           | 16400                          | 162364                               | 9.9                                       | 549000                                | 33.5                                      | 0.55                                        | 4-00192-0007                       | SUNNYSIDE                        | C1-WALK-UP                                  | 24                              | 1931                           | 16840                          | 229061                               | 13.6                                      | 908000                                | 54                                        | 0.45                                        | 
| 4-00032-7501                               | 487-R1                                    | LONG ISLAND CITY                         | R4-ELEVATOR                                         | 13                                      | 2006                                   | 18375                                  | 378900                                       | 20.62                                             | 1699509                                       | 92                                                | 4-00531-0060                       | ASTORIA                          | D1-ELEVATOR                                 | 52                              | 2002                           | 46333                          | 852831                               | 18.41                                     | 3470000                               | 75                                        | 2                                           | 4-00531-0059                       | ASTORIA                          | D6-ELEVATOR                                 | 63                              | 2001                           | 61700                          | 1272343                              | 20.62                                     | 5690000                               | 92                                        | 2                                           | 
| 4-09177-7501                               | 184-R1                                    | WOODHAVEN                                | R2-WALK-UP                                          | 15                                      | 1959                                   | 12208                                  | 39140                                        | 3.21                                              | 120000                                        | 9.83                                              | 4-09181-0026                       | WOODHAVEN                        | C1-WALK-UP                                  | 18                              | 1938                           | 15231                          | 157362                               | 10.33                                     | 532000                                | 34.9                                      | 0.1                                         | 4-08877-0025                       | WOODHAVEN                        | C1-WALK-UP                                  | 12                              | 1942                           | 11500                          | 107000                               | 9.3                                       | 353000                                | 30.7                                      | 0.35                                        | 
| 4-03342-7501                               | 289-R1                                    | FOREST HILLS                             | R4-ELEVATOR                                         | 39                                      | 1939                                   | 31511                                  | 430125                                       | 13.65                                             | 1710002                                       | 54                                                | 4-02236-0027                       | FOREST HILLS                     | D1-ELEVATOR                                 | 48                              | 1967                           | 36436                          | 605695                               | 16.62                                     | 2460000                               | 68                                        | 0.45                                        | 4-03255-0033                       | FOREST HILLS                     | C7-WALK-UP                                  | 36                              | 1937                           | 25550                          | 591135                               | 23.14                                     | 2640000                               | 103                                       | 0.5                                         | 
| 4-09668-7501                               | 251-R1                                    | BRIARWOOD                                | R4-ELEVATOR                                         | 20                                      | 1990                                   | 19000                                  | 285000                                       | 15                                                | 1130001                                       | 59                                                | 4-09651-0061                       | BRIARWOOD                        | C7-WALK-UP                                  | 30                              | 1928                           | 21220                          | 287450                               | 13.55                                     | 1080000                               | 51                                        | 0.35                                        | 4-09710-0094                       | BRIARWOOD                        | D1-ELEVATOR                                 | 60                              | 1959                           | 38394                          | 607701                               | 15.83                                     | 2470000                               | 64                                        | 0.55                                        | 
| 4-03171-7502                               | 419-R1                                    | REGO PARK                                | R9-CONDOPS                                          | 31                                      | 1964                                   | 26930                                  | 533214                                       | 19.8                                              | 2380000                                       | 88                                                | 4-03117-0017                       | REGO PARK                        | D1-ELEVATOR                                 | 36                              | 1957                           | 23100                          | 314559                               | 13.62                                     | 1180000                               | 51                                        | 0.65                                        | 4-03083-0079                       | REGO PARK                        | C1-WALK-UP                                  | 32                              | 1993                           | 27907                          | 467120                               | 16.74                                     | 1900000                               | 68                                        | 0.55                                        | 
| 4-05193-7501                               | 403-R1                                    | FLUSHING-NORTH                           | R4-ELEVATOR                                         | 23                                      | 1999                                   | 16383                                  | 254264                                       | 15.52                                             | 1030000                                       | 63                                                | 4-05053-0011                       | FLUSHING-NORTH                   | D1-ELEVATOR                                 | 90                              | 1963                           | 73649                          | 735017                               | 9.98                                      | 2480000                               | 33.7                                      | 0.5                                         | 4-05294-0013                       | FLUSHING-NORTH                   | D1-ELEVATOR                                 | 65                              | 1938                           | 70569                          | 768173                               | 10.89                                     | 2710000                               | 38.4                                      | 1.3                                         | 
| 4-05027-7502                               | 261-R1                                    | FLUSHING-NORTH                           | R2-WALK-UP                                          | 36                                      | 1988                                   | 36340                                  | 563270                                       | 15.5                                              | 2289996                                       | 63                                                | 4-04995-0024                       | FLUSHING-NORTH                   | C1-WALK-UP                                  | 14                              | 1976                           | 10032                          | 136440                               | 13.6                                      | 541000                                | 54                                        | 0.4                                         | 4-05005-0042                       | FLUSHING-NORTH                   | C1-WALK-UP                                  | 14                              | 1996                           | 10500                          | 150583                               | 14.34                                     | 597000                                | 57                                        | 0.25                                        | 
| 4-03340-7501                               | 63-R1                                     | FOREST HILLS                             | R4-ELEVATOR                                         | 95                                      | 1938                                   | 84954                                  | 1146879                                      | 13.5                                              | 4310000                                       | 51                                                | 4-02222-0001                       | FOREST HILLS                     | D1-ELEVATOR                                 | 78                              | 1939                           | 73020                          | 1205642                              | 16.51                                     | 4900000                               | 67                                        | 0.55                                        | 4-02225-0006                       | FOREST HILLS                     | D1-ELEVATOR                                 | 65                              | 1936                           | 72800                          | 972531                               | 13.36                                     | 3660000                               | 50                                        | 0.45                                        | 
```