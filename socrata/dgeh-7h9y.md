# Libraries - 2013 Holds Placed by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2013-holds-placed-by-location-aafc4) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/dgeh-7h9y) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/dgeh-7h9y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/dgeh-7h9y/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | dgeh-7h9y |
| Name | Libraries - 2013 Holds Placed by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, holds |
| Created | 2013-03-13T15:42:19Z |
| Publication Date | 2014-01-16T19:07:43Z |

## Description

Patrons may place holds on desired materials either online or by contacting any CPL location. The Chicago Public Library consists of the Harold Washington Library Center, Sulzer and Woodson regional libraries and over 70 neighborhood branches. Edgewater Branch reopened in a new, 2-story facility on 6/22/2013. Humboldt Park Branch closed 3/26/2012 for construction of a 5,000-square-foot addition; it reopened 2/9/2013. Albany Park Branch closed 9/22/2012 for construction of a new branch expected to open in 2014. Interim services are being provided in the Albany Park community. Gage Park Branch closed 2/22/2013-3/1/2013 for full carpet replacement and South Shore Branch was closed from 5/13/2013-6/29/2013 for repairs and renovation. Many locations experience sporadic emergency closures due to heating or air conditioning issues, or area power outages.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | location   | LOCATION  | text      | text        |
| No       |                | address    | ADDRESS   | text      | text        |
| Yes      | series tag     | city       | CITY      | text      | text        |
| Yes      | series tag     | zip        | ZIP       | text      | text        |
| Yes      | numeric metric | january    | JANUARY   | number    | number      |
| Yes      | numeric metric | february   | FEBRUARY  | number    | number      |
| Yes      | numeric metric | march      | MARCH     | number    | number      |
| Yes      | numeric metric | april      | APRIL     | number    | number      |
| Yes      | numeric metric | may        | MAY       | number    | number      |
| Yes      | numeric metric | june       | JUNE      | number    | number      |
| Yes      | numeric metric | july       | JULY      | number    | number      |
| Yes      | numeric metric | august     | AUGUST    | number    | number      |
| Yes      | numeric metric | september  | SEPTEMBER | number    | number      |
| Yes      | numeric metric | october    | OCTOBER   | number    | number      |
| Yes      | numeric metric | november   | NOVEMBER  | number    | number      |
| Yes      | numeric metric | december   | DECEMBER  | number    | number      |
| Yes      | numeric metric | ytd        | YTD       | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:dgeh-7h9y d:2013-01-01T00:00:00.000Z t:zip=60625 t:city=CHICAGO t:location="Albany Park" m:november=18 m:may=0 m:august=7 m:february=0 m:ytd=63 m:july=0 m:april=0 m:march=0 m:june=0 m:september=8 m:january=0 m:december=4 m:october=26

series e:dgeh-7h9y d:2013-01-01T00:00:00.000Z t:zip=60827 t:city=CHICAGO t:location=Altgeld m:november=11 m:may=7 m:august=12 m:february=12 m:ytd=152 m:july=9 m:april=8 m:march=14 m:june=16 m:september=11 m:january=17 m:december=23 m:october=12

series e:dgeh-7h9y d:2013-01-01T00:00:00.000Z t:zip=60632 t:city=CHICAGO t:location="Archer Heights" m:november=73 m:may=90 m:august=116 m:february=92 m:ytd=1128 m:july=114 m:april=110 m:march=85 m:june=85 m:september=60 m:january=110 m:december=110 m:october=83
```

## Meta Commands

```ls
metric m:january p:integer l:JANUARY t:dataTypeName=number

metric m:february p:integer l:FEBRUARY t:dataTypeName=number

metric m:march p:integer l:MARCH t:dataTypeName=number

metric m:april p:integer l:APRIL t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:june p:integer l:JUNE t:dataTypeName=number

metric m:july p:integer l:JULY t:dataTypeName=number

metric m:august p:long l:AUGUST t:dataTypeName=number

metric m:september p:integer l:SEPTEMBER t:dataTypeName=number

metric m:october p:integer l:OCTOBER t:dataTypeName=number

metric m:november p:integer l:NOVEMBER t:dataTypeName=number

metric m:december p:integer l:DECEMBER t:dataTypeName=number

metric m:ytd p:long l:YTD t:dataTypeName=number

entity e:dgeh-7h9y l:"Libraries - 2013 Holds Placed by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/dgeh-7h9y

property e:dgeh-7h9y t:meta.view d:2017-09-25T07:25:18.824Z v:averageRating=0 v:name="Libraries - 2013 Holds Placed by Location" v:attribution="Chicago Public Library" v:attributionLink=http://chipublib.org v:id=dgeh-7h9y v:category=Education

property e:dgeh-7h9y t:meta.view.owner d:2017-09-25T07:25:18.824Z v:displayName="Ebony Jones" v:id=cmhs-sm84 v:screenName="Ebony Jones"

property e:dgeh-7h9y t:meta.view.tableauthor d:2017-09-25T07:25:18.824Z v:displayName="Ebony Jones" v:roleName=editor v:id=cmhs-sm84 v:screenName="Ebony Jones"
```

## Top Records

```ls
| location          | address                     | city    | zip   | january | february | march | april | may | june | july | august | september | october | november | december | ytd  | 
| ================= | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | === | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ==== | 
| Albany Park       | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 0       | 0        | 0     | 0     | 0   | 0    | 0    | 7      | 8         | 26      | 18       | 4        | 63   | 
| Altgeld           | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 17      | 12       | 14    | 8     | 7   | 16   | 9    | 12     | 11        | 12      | 11       | 23       | 152  | 
| Archer Heights    | 5055 S. Archer Avenue       | CHICAGO | 60632 | 110     | 92       | 85    | 110   | 90  | 85   | 114  | 116    | 60        | 83      | 73       | 110      | 1128 | 
| Austin            | 5615 W. Race Avenue         | CHICAGO | 60644 | 33      | 55       | 28    | 37    | 30  | 33   | 27   | 19     | 57        | 20      | 20       | 35       | 394  | 
| Austin-Irving     | 6100 W. Irving Park Road    | CHICAGO | 60634 | 205     | 159      | 139   | 134   | 161 | 128  | 152  | 138    | 132       | 86      | 108      | 83       | 1625 | 
| Avalon            | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 225     | 219      | 267   | 338   | 284 | 214  | 280  | 227    | 196       | 180     | 177      | 139      | 2746 | 
| Back of the Yards | 2111 W. 47th Street         | CHICAGO | 60609 | 0       | 0        | 0     | 0     | 0   | 0    | 0    | 6      | 14        | 39      | 38       | 37       | 134  | 
| Beverly           | 1962 W. 95th Street         | CHICAGO | 60643 | 232     | 170      | 183   | 212   | 124 | 145  | 245  | 222    | 216       | 217     | 201      | 141      | 2308 | 
| Bezazian          | 1226 W. Ainslie Street      | CHICAGO | 60640 | 353     | 266      | 277   | 264   | 354 | 315  | 236  | 218    | 215       | 191     | 217      | 144      | 3050 | 
| Blackstone        | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 174     | 185      | 172   | 182   | 161 | 115  | 147  | 144    | 154       | 212     | 139      | 117      | 1902 | 
```