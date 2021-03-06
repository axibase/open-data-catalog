# Port Authority Trans-Hudson Corporation (PATH) Average Weekday and Weekend Ridership: Beginning 1996

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/port-authority-trans-hudson-corporation-path-average-weekday-and-weekend-ridership-beginni) |
| Metadata | [Link](https://data.ny.gov/api/views/p7e4-ipty) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/p7e4-ipty/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/p7e4-ipty/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | p7e4-ipty |
| Name | Port Authority Trans-Hudson Corporation (PATH) Average Weekday and Weekend Ridership: Beginning 1996 |
| Attribution | Port Authority NY & NJ |
| Category | Transportation |
| Tags | port authority of ny & nj, rail, path, transit |
| Created | 2013-05-10T17:35:02Z |
| Publication Date | 2016-10-28T19:01:47Z |

## Description

PATH System average weekday and weekend linked passenger trips, by month beginning 1996 through current year period.  Trips are based on station turnstile entry counts for weekdays and weekends operating under normal weekday schedule (excludes holidays).

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       |                | year                   | Year                   | number    | number      |
| No       |                | month                  | Month                  | number    | text        |
| Yes      | numeric metric | average_weekday_trips  | Average Weekday Trips  | number    | number      |
| Yes      | numeric metric | average_saturday_trips | Average Saturday Trips | number    | number      |
| Yes      | numeric metric | average_sunday_trips   | Average Sunday Trips   | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:p7e4-ipty d:2015-01-01T00:00:00.000Z m:average_sunday_trips=65718 m:average_saturday_trips=88875 m:average_weekday_trips=227560

series e:p7e4-ipty d:2015-02-01T00:00:00.000Z m:average_sunday_trips=69433 m:average_saturday_trips=94726 m:average_weekday_trips=245222

series e:p7e4-ipty d:2015-03-01T00:00:00.000Z m:average_sunday_trips=80341 m:average_saturday_trips=107723 m:average_weekday_trips=250436
```

## Meta Commands

```ls
metric m:average_weekday_trips p:integer l:"Average Weekday Trips" d:"Identifies passenger trip volumes on weekdays" t:dataTypeName=number

metric m:average_saturday_trips p:integer l:"Average Saturday Trips" d:"Identifies passenger trip volumes on Saturdays" t:dataTypeName=number

metric m:average_sunday_trips p:integer l:"Average Sunday Trips" d:"Identifies passenger trip volumes on Sundays" t:dataTypeName=number

entity e:p7e4-ipty l:"Port Authority Trans-Hudson Corporation (PATH) Average Weekday and Weekend Ridership: Beginning 1996" t:attribution="Port Authority NY & NJ" t:url=https://data.ny.gov/api/views/p7e4-ipty

property e:p7e4-ipty t:meta.view d:2017-09-25T07:28:32.894Z v:averageRating=0 v:name="Port Authority Trans-Hudson Corporation (PATH) Average Weekday and Weekend Ridership: Beginning 1996" v:attribution="Port Authority NY & NJ" v:id=p7e4-ipty v:category=Transportation

property e:p7e4-ipty t:meta.view.owner d:2017-09-25T07:28:32.894Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:p7e4-ipty t:meta.view.tableauthor d:2017-09-25T07:28:32.894Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:p7e4-ipty t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:28:32.894Z v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY" v:Publisher="State of New York"
```

## Top Records

```ls
| year | month | average_weekday_trips | average_saturday_trips | average_sunday_trips | 
| ==== | ===== | ===================== | ====================== | ==================== | 
| 2015 | 1     | 227560                | 88875                  | 65718                | 
| 2015 | 2     | 245222                | 94726                  | 69433                | 
| 2015 | 3     | 250436                | 107723                 | 80341                | 
| 2015 | 4     | 258345                | 122703                 | 89890                | 
| 2015 | 5     | 264326                | 119435                 | 95415                | 
| 2015 | 6     | 267048                | 116406                 | 97617                | 
| 2015 | 7     | 261749                | 121592                 | 91506                | 
| 2015 | 8     | 259288                | 119474                 | 95663                | 
| 2015 | 9     | 269025                | 124025                 | 95915                | 
| 2015 | 10    | 271211                | 121593                 | 92086                | 
```