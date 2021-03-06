# AADT Turning Traffic 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aadt-turning-traffic-2004) |
| Metadata | [Link](https://data.iowa.gov/api/views/x89d-qusv) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/x89d-qusv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/x89d-qusv/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | x89d-qusv |
| Name | AADT Turning Traffic 2004 |
| Attribution | Iowa Department of Transportation - Office of Systems Planning |
| Category | Transportation & Utilities |
| Tags | asset, classification, total aadt, passenger, single unit, combo unit, leg label, aadt, turning movement, traffic, iowa dot, iowa department of transportation |
| Created | 2016-09-29T18:59:19Z |
| Publication Date | 2016-09-29T19:00:48Z |

## Description

Iowa turning traffic data (AADT) for intersections on the primary, secondary and municipal roadway systems for 2004. The state is divided into 4 quadrants and each quadrant is counted every 4 years.

The Turning Movements application includes all AADT Turning Traffic data for years 1998-2015 and can be found on the Iowa DOT Interactive Map Portal: http://iowadot.maps.arcgis.com/apps/Viewer/index.html?appid=a29e44be6e314799b612335342a13f62

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag  | station              | STATION              | text      | text        |
| Yes      | series tag  | intersection_leg     | INTERSECTION_LEG     | text      | text        |
| Yes      | series tag  | total_aadt           | TOTAL_AADT           | text      | text        |
| Yes      | series tag  | passenger_aadt       | PASSENGER_AADT       | text      | text        |
| Yes      | series tag  | single_unit_aadt     | SINGLE_UNIT_AADT     | text      | text        |
| Yes      | series tag  | combo_unit_aadt      | COMBO_UNIT_AADT      | text      | text        |
| Yes      | series tag  | turning_movement_url | TURNING_MOVEMENT_URL | text      | text        |
| Yes      | series tag  | objectid             | OBJECTID             | text      | number      |
```

## Time Field

```ls
Value = 2004
Format & Zone = yyyy
```

## Data Commands

```ls
series e:x89d-qusv d:2004-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01114933099.pdf t:station=01114933099 t:objectid=1 m:row_number.x89d-qusv=1

series e:x89d-qusv d:2004-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01134949099.pdf t:station=01134949099 t:objectid=2 m:row_number.x89d-qusv=2

series e:x89d-qusv d:2004-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01225117099.pdf t:station=01225117099 t:objectid=3 m:row_number.x89d-qusv=3
```

## Meta Commands

```ls
metric m:row_number.x89d-qusv p:long l:"Row Number"

entity e:x89d-qusv l:"AADT Turning Traffic 2004" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/x89d-qusv

property e:x89d-qusv t:meta.view d:2017-06-09T13:52:07.869Z v:id=x89d-qusv v:category="Transportation & Utilities" v:averageRating=0 v:name="AADT Turning Traffic 2004" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:x89d-qusv t:meta.view.owner d:2017-06-09T13:52:07.869Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:x89d-qusv t:meta.view.tableauthor d:2017-06-09T13:52:07.869Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| station     | intersection_leg | total_aadt | passenger_aadt | single_unit_aadt | combo_unit_aadt | turning_movement_url                                                          | objectid | 
| =========== | ================ | ========== | ============== | ================ | =============== | ============================================================================= | ======== | 
| 01114933099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01114933099.pdf | 1        | 
| 01134949099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01134949099.pdf | 2        | 
| 01225117099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01225117099.pdf | 3        | 
| 01236711099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01236711099.pdf | 4        | 
| 01236717099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01236717099.pdf | 5        | 
| 01237417099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01237417099.pdf | 6        | 
| 01246501099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01246501099.pdf | 7        | 
| 01247834099 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01247834099.pdf | 8        | 
| 01418433199 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01418433199.pdf | 9        | 
| 01418433599 |                  |            |                |                  |                 | http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01418433599.pdf | 10       | 
```