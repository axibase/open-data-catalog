# Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/coach-bus-passengers-per-month-at-port-authority-of-ny-nj-airports-beginning-2002) |
| Metadata | [Link](https://data.ny.gov/api/views/39r6-cbzf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/39r6-cbzf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/39r6-cbzf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 39r6-cbzf |
| Name | Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002 |
| Attribution | The Port Authority of New York & New Jersey |
| Category | Transportation |
| Tags | the port authority of new york & new jersey, airport, coach bus, bus passengers, ground transportation |
| Created | 2014-02-10T20:00:53Z |
| Publication Date | 2016-11-10T20:05:22Z |

## Description

The Port Authority of New York & New Jersey quarterly produces a data file and provides information on monthly in-bound, out-bound, and connecting Coach Bus passengers between John F. Kennedy International Airport, LaGuardia Airport, and Newark Liberty International Airport; and between aforementioned airports and NYC bus stations beginning in 2002. The dataset represents aggregate numbers of single destination (e.g. A -> B) Coach Bus ticket sale by the Coach Bus companies.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | airport          | Airport          | text      | text        |
| No       |                | year             | Year             | number    | number      |
| No       |                | month            | Month            | number    | number      |
| Yes      | numeric metric | coach_passengers | Coach Passengers | number    | number      |
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
series e:39r6-cbzf d:2002-01-01T00:00:00.000Z t:airport="Kennedy International Airport" m:coach_passengers=30338

series e:39r6-cbzf d:2002-02-01T00:00:00.000Z t:airport="Kennedy International Airport" m:coach_passengers=26409

series e:39r6-cbzf d:2002-03-01T00:00:00.000Z t:airport="Kennedy International Airport" m:coach_passengers=36206
```

## Meta Commands

```ls
metric m:coach_passengers p:integer l:"Coach Passengers" t:dataTypeName=number

entity e:39r6-cbzf l:"Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002" t:attribution="The Port Authority of New York & New Jersey" t:url=https://data.ny.gov/api/views/39r6-cbzf

property e:39r6-cbzf t:meta.view d:2017-09-25T07:25:01.968Z v:averageRating=0 v:name="Coach Bus Passengers per Month at Port Authority of NY NJ Airports: Beginning 2002" v:attribution="The Port Authority of New York & New Jersey" v:attributionLink=http://www.panynj.gov/airports/ewr-public-transportation.html v:id=39r6-cbzf v:category=Transportation

property e:39r6-cbzf t:meta.view.owner d:2017-09-25T07:25:01.968Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:39r6-cbzf t:meta.view.tableauthor d:2017-09-25T07:25:01.968Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:39r6-cbzf t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:25:01.968Z v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY" v:Publisher="State of New York"
```

## Top Records

```ls
| airport                       | year | month | coach_passengers | 
| ============================= | ==== | ===== | ================ | 
| Kennedy International Airport | 2002 | 1     | 30338            | 
| Kennedy International Airport | 2002 | 2     | 26409            | 
| Kennedy International Airport | 2002 | 3     | 36206            | 
| Kennedy International Airport | 2002 | 4     | 29482            | 
| Kennedy International Airport | 2002 | 5     | 42262            | 
| Kennedy International Airport | 2002 | 6     | 44453            | 
| Kennedy International Airport | 2002 | 7     | 44043            | 
| Kennedy International Airport | 2002 | 8     | 48439            | 
| Kennedy International Airport | 2002 | 9     | 47167            | 
| Kennedy International Airport | 2002 | 10    | 46684            | 
```