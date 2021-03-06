# 2015 Green Taxi Trip Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-green-taxi-trip-data) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gi8d-wdg5) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gi8d-wdg5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gi8d-wdg5/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gi8d-wdg5 |
| Name | 2015 Green Taxi Trip Data |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Created | 2015-08-07T14:50:12Z |
| Publication Date | 2016-12-12T17:07:27Z |

## Description

This dataset includes trip records from all trips completed in green taxis in NYC in 2015. Records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The data used in the attached datasets were collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Livery Passenger Enhancement Program (LPEP). The trip data was not created by the TLC, and TLC makes no representations as to the accuracy of these data.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | vendorid              | vendorid              | text          | text          |
| Yes      | time           | lpep_pickup_datetime  | pickup_datetime       | calendar_date | calendar_date |
| No       |                | lpep_dropoff_datetime | dropoff_datetime      | calendar_date | calendar_date |
| Yes      | series tag     | store_and_fwd_flag    | Store_and_fwd_flag    | text          | text          |
| Yes      | series tag     | ratecodeid            | rate_code             | text          | number        |
| No       |                | pickup_longitude      | Pickup_longitude      | number        | number        |
| No       |                | pickup_latitude       | Pickup_latitude       | number        | number        |
| No       |                | dropoff_longitude     | Dropoff_longitude     | number        | number        |
| No       |                | dropoff_latitude      | Dropoff_latitude      | number        | number        |
| Yes      | numeric metric | passenger_count       | Passenger_count       | number        | number        |
| Yes      | numeric metric | trip_distance         | Trip_distance         | number        | number        |
| Yes      | numeric metric | fare_amount           | Fare_amount           | number        | number        |
| Yes      | numeric metric | extra                 | Extra                 | number        | number        |
| Yes      | numeric metric | mta_tax               | MTA_tax               | number        | number        |
| Yes      | numeric metric | tip_amount            | Tip_amount            | number        | number        |
| Yes      | numeric metric | tolls_amount          | Tolls_amount          | number        | number        |
| Yes      | numeric metric | ehail_fee             | Ehail_fee             | number        | number        |
| Yes      | numeric metric | improvement_surcharge | Improvement_surcharge | number        | number        |
| Yes      | numeric metric | total_amount          | Total_amount          | number        | number        |
| Yes      | series tag     | payment_type          | Payment_type          | text          | number        |
| Yes      | series tag     | trip_type             | Trip_type             | text          | number        |
```

## Time Field

```ls
Value = lpep_pickup_datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lpep_dropoff_datetime,pickup_longitude,pickup_latitude,dropoff_longitude,dropoff_latitude
```

## Data Commands

```ls
series e:gi8d-wdg5 d:2015-01-14T19:49:40.000Z t:store_and_fwd_flag=N t:payment_type=2 t:trip_type=1 t:ratecodeid=1 t:vendorid=1 m:fare_amount=5 m:total_amount=6.8 m:extra=1 m:passenger_count=1 m:tip_amount=0 m:tolls_amount=0 m:mta_tax=0.5 m:improvement_surcharge=0.3 m:trip_distance=0.9

series e:gi8d-wdg5 d:2015-01-14T19:49:29.000Z t:store_and_fwd_flag=N t:payment_type=2 t:trip_type=1 t:ratecodeid=1 t:vendorid=1 m:fare_amount=8.5 m:total_amount=10.3 m:extra=1 m:passenger_count=1 m:tip_amount=0 m:tolls_amount=0 m:mta_tax=0.5 m:improvement_surcharge=0.3 m:trip_distance=1.7

series e:gi8d-wdg5 d:2015-01-14T19:49:12.000Z t:store_and_fwd_flag=N t:payment_type=1 t:trip_type=1 t:ratecodeid=1 t:vendorid=1 m:fare_amount=19.5 m:total_amount=23.8 m:extra=0.5 m:passenger_count=1 m:tip_amount=3 m:tolls_amount=0 m:mta_tax=0.5 m:improvement_surcharge=0.3 m:trip_distance=4.6
```

## Meta Commands

```ls
metric m:passenger_count p:integer l:Passenger_count d:"The number of passengers in the vehicle. This is a driver-entered value." t:dataTypeName=number

metric m:trip_distance p:float l:Trip_distance d:"The elapsed trip distance in miles reported by the taximeter." t:dataTypeName=number

metric m:fare_amount p:float l:Fare_amount d:"The time-and-distance fare calculated by the meter. Extra Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges." t:dataTypeName=number

metric m:extra p:double l:Extra t:dataTypeName=number

metric m:mta_tax p:float l:MTA_tax d:"$0.50 MTA tax that is automatically triggered based on the metered rate in use." t:dataTypeName=number

metric m:tip_amount p:float l:Tip_amount d:"Tip amount – This field is automatically populated for credit card tips. Cash tips are not included." t:dataTypeName=number

metric m:tolls_amount p:float l:Tolls_amount d:"Total amount of all tolls paid in trip." t:dataTypeName=number

metric m:ehail_fee p:long l:Ehail_fee t:dataTypeName=number

metric m:improvement_surcharge p:float l:Improvement_surcharge d:"$0.30 improvement surcharge assessed trips at the flag drop. The improvement surcharge began being levied in 2015." t:dataTypeName=number

metric m:total_amount p:double l:Total_amount d:"The total amount charged to passengers. Does not include cash tips." t:dataTypeName=number

entity e:gi8d-wdg5 l:"2015 Green Taxi Trip Data" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/gi8d-wdg5

property e:gi8d-wdg5 t:meta.view d:2017-09-25T07:25:53.505Z v:averageRating=0 v:name="2015 Green Taxi Trip Data" v:attribution="Taxi and Limousine Commission (TLC)" v:id=gi8d-wdg5 v:category=Transportation

property e:gi8d-wdg5 t:meta.view.owner d:2017-09-25T07:25:53.505Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:gi8d-wdg5 t:meta.view.tableauthor d:2017-09-25T07:25:53.505Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| vendorid | lpep_pickup_datetime | lpep_dropoff_datetime | store_and_fwd_flag | ratecodeid | pickup_longitude    | pickup_latitude    | dropoff_longitude   | dropoff_latitude   | passenger_count | trip_distance | fare_amount | extra | mta_tax | tip_amount | tolls_amount | ehail_fee | improvement_surcharge | total_amount | payment_type | trip_type | 
| ======== | ==================== | ===================== | ================== | ========== | =================== | ================== | =================== | ================== | =============== | ============= | =========== | ===== | ======= | ========== | ============ | ========= | ===================== | ============ | ============ | ========= | 
| 1        | 2015-01-14T19:49:40  | 2015-01-14T19:54:00   | N                  | 1          | -73.957603454589844 | 40.717960357666016 | -73.953079223632812 | 40.727703094482422 | 1               | 0.90          | 5           | 1     | 0.5     | 0          | 0            |           | 0.3                   | 6.8          | 2            | 1         | 
| 1        | 2015-01-14T19:49:29  | 2015-01-14T19:58:40   | N                  | 1          | -73.883827209472656 | 40.746921539306641 | -73.898452758789063 | 40.732078552246094 | 1               | 1.70          | 8.5         | 1     | 0.5     | 0          | 0            |           | 0.3                   | 10.3         | 2            | 1         | 
| 1        | 2015-01-14T19:49:12  | 2015-01-14T20:14:07   | N                  | 1          | -73.931129455566406 | 40.6697998046875   | -73.949722290039062 | 40.724102020263672 | 1               | 4.60          | 19.5        | 0.5   | 0.5     | 3          | 0            |           | 0.3                   | 23.8         | 1            | 1         | 
| 1        | 2015-01-14T19:49:08  | 2015-01-14T19:56:08   | N                  | 1          | -73.903480529785156 | 40.745765686035156 | -73.915016174316406 | 40.752574920654297 | 1               | 1.20          | 7           | 1     | 0.5     | 0          | 0            |           | 0.3                   | 8.8          | 2            | 1         | 
| 1        | 2015-01-14T19:49:14  | 2015-01-14T20:06:02   | N                  | 1          | -73.959671020507813 | 40.691585540771484 | -73.998138427734375 | 40.677875518798828 | 3               | 3.30          | 13.5        | 1     | 0.5     | 3.05       | 0            |           | 0.3                   | 18.35        | 1            | 1         | 
| 1        | 2015-01-14T19:48:19  | 2015-01-14T20:00:45   | N                  | 1          | -73.960098266601563 | 40.806713104248047 | -73.958282470703125 | 40.779815673828125 | 1               | 2.60          | 11.5        | 1     | 0.5     | 1.5        | 0            |           | 0.3                   | 14.8         | 1            | 1         | 
| 1        | 2015-01-14T19:48:00  | 2015-01-14T19:59:25   | N                  | 1          | -73.966636657714844 | 40.804004669189453 | -73.937675476074219 | 40.797000885009766 | 2               | 1.90          | 10          | 1     | 0.5     | 2.35       | 0            |           | 0.3                   | 14.15        | 1            | 1         | 
| 1        | 2015-01-14T19:47:56  | 2015-01-14T20:19:51   | N                  | 1          | -73.949478149414063 | 40.680263519287109 | -74.003585815429688 | 40.742828369140625 | 1               | 6.30          | 25          | 1     | 0.5     | 5.35       | 0            |           | 0.3                   | 32.15        | 1            | 1         | 
| 1        | 2015-01-14T19:47:54  | 2015-01-14T19:53:29   | N                  | 1          | -73.959983825683594 | 40.715839385986328 | -73.966484069824219 | 40.713146209716797 | 1               | 0.90          | 5.5         | 1     | 0.5     | 0          | 0            |           | 0.3                   | 7.3          | 2            | 1         | 
| 1        | 2015-01-14T19:47:27  | 2015-01-14T19:51:50   | N                  | 1          | -73.944290161132812 | 40.834640502929688 | -73.94854736328125  | 40.824043273925781 | 1               | 0.90          | 5.5         | 0.5   | 0.5     | 1.35       | 0            |           | 0.3                   | 8.15         | 1            | 1         | 
```