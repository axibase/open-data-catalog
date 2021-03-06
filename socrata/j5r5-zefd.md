# 2012 Age 0-17 Youth Population by Race/Ethnicity by County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-age-0-17-youth-population-by-race-ethnicity-by-county) |
| Metadata | [Link](https://data.wa.gov/api/views/j5r5-zefd) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/j5r5-zefd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/j5r5-zefd/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | j5r5-zefd |
| Name | 2012 Age 0-17 Youth Population by Race/Ethnicity by County |
| Attribution | Office of Juvenile Justice |
| Created | 2015-11-17T04:24:05Z |
| Publication Date | 2015-11-17T04:26:44Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                  | Data Type | Render Type |
| ======== | ============== | =================== | ===================== | ========= | =========== |
| Yes      | series tag     | county              | County                | text      | text        |
| Yes      | numeric metric | white_non_hispanic  | White (Non-Hispanic)  | number    | number      |
| Yes      | numeric metric | black_non_hispanic  | Black (Non-Hispanic)  | number    | number      |
| Yes      | numeric metric | indian_non_hispanic | Indian (Non-Hispanic) | number    | number      |
| Yes      | numeric metric | asian_non_hispanic  | Asian (Non-Hispanic)  | number    | number      |
| Yes      | numeric metric | hispanic            | Hispanic              | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j5r5-zefd d:2012-01-01T00:00:00.000Z t:county=Adams m:indian_non_hispanic=31 m:black_non_hispanic=46 m:hispanic=4932 m:asian_non_hispanic=37 m:white_non_hispanic=1574

series e:j5r5-zefd d:2012-01-01T00:00:00.000Z t:county=Asotin m:indian_non_hispanic=112 m:black_non_hispanic=75 m:hispanic=293 m:asian_non_hispanic=52 m:white_non_hispanic=4131

series e:j5r5-zefd d:2012-01-01T00:00:00.000Z t:county=Benton m:indian_non_hispanic=453 m:black_non_hispanic=1110 m:hispanic=14429 m:asian_non_hispanic=1474 m:white_non_hispanic=30847
```

## Meta Commands

```ls
metric m:white_non_hispanic p:integer l:"White (Non-Hispanic)" t:dataTypeName=number

metric m:black_non_hispanic p:integer l:"Black (Non-Hispanic)" t:dataTypeName=number

metric m:indian_non_hispanic p:integer l:"Indian (Non-Hispanic)" t:dataTypeName=number

metric m:asian_non_hispanic p:integer l:"Asian (Non-Hispanic)" t:dataTypeName=number

metric m:hispanic p:integer l:Hispanic t:dataTypeName=number

entity e:j5r5-zefd l:"2012 Age 0-17 Youth Population by Race/Ethnicity by County" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/j5r5-zefd

property e:j5r5-zefd t:meta.view d:2017-09-25T07:28:23.391Z v:averageRating=100 v:name="2012 Age 0-17 Youth Population by Race/Ethnicity by County" v:attribution="Office of Juvenile Justice" v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:id=j5r5-zefd

property e:j5r5-zefd t:meta.view.license d:2017-09-25T07:28:23.391Z v:name="Public Domain"

property e:j5r5-zefd t:meta.view.owner d:2017-09-25T07:28:23.391Z v:displayName="Alysa Kipersztok" v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:id=6p7r-jviv v:screenName="Alysa Kipersztok" v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB

property e:j5r5-zefd t:meta.view.tableauthor d:2017-09-25T07:28:23.391Z v:displayName="Alysa Kipersztok" v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:roleName=viewer v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:id=6p7r-jviv v:screenName="Alysa Kipersztok" v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB
```

## Top Records

```ls
| county   | white_non_hispanic | black_non_hispanic | indian_non_hispanic | asian_non_hispanic | hispanic | 
| ======== | ================== | ================== | =================== | ================== | ======== | 
| Adams    | 1574               | 46                 | 31                  | 37                 | 4932     | 
| Asotin   | 4131               | 75                 | 112                 | 52                 | 293      | 
| Benton   | 30847              | 1110               | 453                 | 1474               | 14429    | 
| Chelan   | 9699               | 133                | 154                 | 230                | 7923     | 
| Clallam  | 9752               | 246                | 1121                | 264                | 1427     | 
| Clark    | 86408              | 4143               | 1053                | 6956               | 14154    | 
| Columbia | 653                | 11                 | 11                  | 9                  | 89       | 
| Cowlitz  | 19246              | 409                | 525                 | 511                | 3749     | 
| Douglas  | 5372               | 101                | 122                 | 104                | 4665     | 
| Ferry    | 956                | 29                 | 403                 | 25                 | 87       | 
```