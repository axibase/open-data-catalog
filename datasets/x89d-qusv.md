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
| Rows Updated | 2016-09-29T18:59:19Z |

## Description

Iowa turning traffic data (AADT) for intersections on the primary, secondary and municipal roadway systems for 2004. The state is divided into 4 quadrants and each quadrant is counted every 4 years.

The Turning Movements application includes all AADT Turning Traffic data for years 1998-2015 and can be found on the Iowa DOT Interactive Map Portal: http://iowadot.maps.arcgis.com/apps/Viewer/index.html?appid=a29e44be6e314799b612335342a13f62

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | numeric metric | station              | STATION              | number    | text        |
| Yes      | numeric metric | intersection_leg     | INTERSECTION_LEG     | number    | text        |
| Yes      | numeric metric | total_aadt           | TOTAL_AADT           | number    | text        |
| Yes      | numeric metric | passenger_aadt       | PASSENGER_AADT       | number    | text        |
| Yes      | numeric metric | single_unit_aadt     | SINGLE_UNIT_AADT     | number    | text        |
| Yes      | numeric metric | combo_unit_aadt      | COMBO_UNIT_AADT      | number    | text        |
| Yes      | series tag     | turning_movement_url | TURNING_MOVEMENT_URL | text      | text        |
| Yes      | series tag     | objectid             | OBJECTID             | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:x89d-qusv d:1970-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01114933099.pdf t:objectid=1 m:station=1114933099

series e:x89d-qusv d:1970-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01134949099.pdf t:objectid=2 m:station=1134949099

series e:x89d-qusv d:1970-01-01T00:00:00.000Z t:turning_movement_url=http://www.iowadotmaps.com/msp/traffic/turning_movements/2004/01225117099.pdf t:objectid=3 m:station=1225117099
```

## Meta Commands

```ls
metric m:station p:long l:STATION d:Station t:dataTypeName=number

metric m:intersection_leg l:INTERSECTION_LEG d:"Intersection Leg" t:dataTypeName=number

metric m:total_aadt l:TOTAL_AADT d:"Total AADT" t:dataTypeName=number

metric m:passenger_aadt l:PASSENGER_AADT d:"Passenger AADT" t:dataTypeName=number

metric m:single_unit_aadt l:SINGLE_UNIT_AADT d:"Single Unit AADT" t:dataTypeName=number

metric m:combo_unit_aadt l:COMBO_UNIT_AADT d:"Combo Unit AADT" t:dataTypeName=number

entity e:x89d-qusv l:"AADT Turning Traffic 2004" t:attribution="Iowa Department of Transportation - Office of Systems Planning" t:url=https://data.iowa.gov/api/views/x89d-qusv

property e:x89d-qusv t:meta.view v:id=x89d-qusv v:category="Transportation & Utilities" v:averageRating=0 v:name="AADT Turning Traffic 2004" v:attribution="Iowa Department of Transportation - Office of Systems Planning"

property e:x89d-qusv t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"

property e:x89d-qusv t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```