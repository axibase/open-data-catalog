# Weekly Crime Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/weekly-crime-statistics) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/jiea-vc79) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/jiea-vc79/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/jiea-vc79/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | jiea-vc79 |
| Name | Weekly Crime Statistics |
| Category | Public Safety |
| Created | 2016-12-02T04:15:58Z |
| Publication Date | 2017-04-03T19:51:00Z |

## Description

This data set shows Part 1 Crime broken down by Precinct. This information helps us track crime activity by precinct and citywide. This data is updated weekly.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | crime_description | Crime Description | text          | text          |
| Yes      | numeric metric | precinct_1        | Precinct 1        | number        | number        |
| Yes      | numeric metric | precinct_2        | Precinct 2        | number        | number        |
| Yes      | numeric metric | precinct_3        | Precinct 3        | number        | number        |
| Yes      | numeric metric | precinct_4        | Precinct 4        | number        | number        |
| Yes      | numeric metric | total             | Total             | number        | number        |
| Yes      | time           | week_reported     | Week Reported     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = week_reported
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jiea-vc79 d:2016-10-06T00:00:00.000Z t:crime_description="Auto Burglary" m:total=44 m:precinct_1=2 m:precinct_2=22 m:precinct_3=5 m:precinct_4=15

series e:jiea-vc79 d:2016-10-06T00:00:00.000Z t:crime_description="Auto Theft" m:total=21 m:precinct_1=3 m:precinct_2=8 m:precinct_3=5 m:precinct_4=5

series e:jiea-vc79 d:2016-10-06T00:00:00.000Z t:crime_description="Business Burglary" m:total=9 m:precinct_1=4 m:precinct_2=2 m:precinct_3=2 m:precinct_4=1
```

## Meta Commands

```ls
metric m:precinct_1 p:integer l:"Precinct 1" t:dataTypeName=number

metric m:precinct_2 p:integer l:"Precinct 2" t:dataTypeName=number

metric m:precinct_3 p:integer l:"Precinct 3" t:dataTypeName=number

metric m:precinct_4 p:integer l:"Precinct 4" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:jiea-vc79 l:"Weekly Crime Statistics" t:url=https://data.jacksonms.gov/api/views/jiea-vc79

property e:jiea-vc79 t:meta.view d:2017-09-25T07:32:12.469Z v:averageRating=0 v:name="Weekly Crime Statistics" v:id=jiea-vc79 v:category="Public Safety"

property e:jiea-vc79 t:meta.view.owner d:2017-09-25T07:32:12.469Z v:displayName="Justin Bruce" v:lastNotificationSeenAt=1492180672 v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:id=6ngd-c2u2 v:screenName="Justin Bruce" v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB

property e:jiea-vc79 t:meta.view.tableauthor d:2017-09-25T07:32:12.469Z v:displayName="Justin Bruce" v:lastNotificationSeenAt=1492180672 v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:id=6ngd-c2u2 v:screenName="Justin Bruce" v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB
```

## Top Records

```ls
| crime_description | precinct_1 | precinct_2 | precinct_3 | precinct_4 | total | week_reported       | 
| ================= | ========== | ========== | ========== | ========== | ===== | =================== | 
| Auto Burglary     | 2          | 22         | 5          | 15         | 44    | 2016-10-06T00:00:00 | 
| Auto Theft        | 3          | 8          | 5          | 5          | 21    | 2016-10-06T00:00:00 | 
| Business Burglary | 4          | 2          | 2          | 1          | 9     | 2016-10-06T00:00:00 | 
| Grand Larceny     | 1          | 4          | 0          | 3          | 8     | 2016-10-06T00:00:00 | 
| House Burglary    | 4          | 3          | 4          | 8          | 19    | 2016-10-06T00:00:00 | 
| Property Crimes   | 14         | 39         | 16         | 32         | 101   | 2016-10-06T00:00:00 | 
| Agg Assault       | 2          | 1          | 2          | 1          | 6     | 2016-10-06T00:00:00 | 
| Armed Robbery     | 1          | 3          | 3          | 6          | 13    | 2016-10-06T00:00:00 | 
| Carjacking        | 1          | 0          | 1          | 0          | 2     | 2016-10-06T00:00:00 | 
| Homicide          | 0          | 1          | 0          | 0          | 1     | 2016-10-06T00:00:00 | 
```