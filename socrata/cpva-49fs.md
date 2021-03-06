# Libraries - 2012 Holds Placed by Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-2012-holds-placed-by-location-7fc19) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/cpva-49fs) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/cpva-49fs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/cpva-49fs/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | cpva-49fs |
| Name | Libraries - 2012 Holds Placed by Location |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, holds |
| Created | 2012-02-17T21:26:21Z |
| Publication Date | 2013-04-08T21:31:48Z |

## Description

Patrons may place holds on desired materials either online or by contacting any CPL location.  In January all branch locations were closed on Monday, January 9, Monday, January 23 and Monday, January 30. Beginning in February, all branch locations restored partial Monday hours, from 2 p.m. to 6 p.m. On June 18, all branch locations restored full Monday hours. Edgewater closed 6/16/11 for construction of a new branch scheduled to open in mid-2013. The library’s bookmobile opened 6/24/11 for Edgewater holds pickup and returns. Douglass closed for 10 days in February for roof repairs. Humboldt Park closed 3/26/12 for facility improvements and expansion. Lincoln Park closed for four days in August for replacement of the air conditioning system. Many locations experienced sporadic closures in summer 2012 due to air conditioning issues and area power outages. Albany Park closed 9/22/12 for construction of a new branch and will remain closed until 2014. Brighton Park, Jefferson Park and Portage Cragin were closed 11/26/12-12/7/12 for replacement of their HVAC systems.

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
Value = 2012
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:cpva-49fs d:2012-01-01T00:00:00.000Z t:zip=60625 t:city=CHICAGO t:location="Albany Park" m:november=0 m:may=195 m:august=137 m:february=224 m:ytd=1719 m:july=254 m:april=239 m:march=230 m:june=197 m:september=44 m:january=198 m:december=0 m:october=1

series e:cpva-49fs d:2012-01-01T00:00:00.000Z t:zip=60827 t:city=CHICAGO t:location=Altgeld m:november=12 m:may=8 m:august=9 m:february=20 m:ytd=216 m:july=19 m:april=21 m:march=16 m:june=5 m:september=34 m:january=30 m:december=29 m:october=13

series e:cpva-49fs d:2012-01-01T00:00:00.000Z t:zip=60632 t:city=CHICAGO t:location="Archer Heights" m:november=122 m:may=139 m:august=143 m:february=76 m:ytd=1344 m:july=136 m:april=122 m:march=109 m:june=106 m:september=102 m:january=88 m:december=73 m:october=128
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

metric m:august p:integer l:AUGUST t:dataTypeName=number

metric m:september p:integer l:SEPTEMBER t:dataTypeName=number

metric m:october p:integer l:OCTOBER t:dataTypeName=number

metric m:november p:integer l:NOVEMBER t:dataTypeName=number

metric m:december p:integer l:DECEMBER t:dataTypeName=number

metric m:ytd p:integer l:YTD t:dataTypeName=number

entity e:cpva-49fs l:"Libraries - 2012 Holds Placed by Location" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/cpva-49fs

property e:cpva-49fs t:meta.view d:2017-09-25T07:27:21.195Z v:averageRating=0 v:name="Libraries - 2012 Holds Placed by Location" v:attribution="Chicago Public Library" v:attributionLink=http://chipublib.org v:id=cpva-49fs v:category=Education

property e:cpva-49fs t:meta.view.owner d:2017-09-25T07:27:21.195Z v:displayName=GPeck v:id=jitu-w2pw v:screenName=GPeck

property e:cpva-49fs t:meta.view.tableauthor d:2017-09-25T07:27:21.195Z v:displayName=GPeck v:roleName=editor v:id=jitu-w2pw v:screenName=GPeck
```

## Top Records

```ls
| location       | address                     | city    | zip   | january | february | march | april | may | june | july | august | september | october | november | december | ytd  | 
| ============== | =========================== | ======= | ===== | ======= | ======== | ===== | ===== | === | ==== | ==== | ====== | ========= | ======= | ======== | ======== | ==== | 
| Albany Park    | 5150 N. Kimball Avenue      | CHICAGO | 60625 | 198     | 224      | 230   | 239   | 195 | 197  | 254  | 137    | 44        | 1       | 0        | 0        | 1719 | 
| Altgeld        | 13281 S. Corliss Avenue     | CHICAGO | 60827 | 30      | 20       | 16    | 21    | 8   | 5    | 19   | 9      | 34        | 13      | 12       | 29       | 216  | 
| Archer Heights | 5055 S. Archer Avenue       | CHICAGO | 60632 | 88      | 76       | 109   | 122   | 139 | 106  | 136  | 143    | 102       | 128     | 122      | 73       | 1344 | 
| Austin         | 5615 W. Race Avenue         | CHICAGO | 60644 | 18      | 12       | 24    | 27    | 40  | 27   | 41   | 52     | 54        | 61      | 45       | 37       | 438  | 
| Austin-Irving  | 6100 W. Irving Park Road    | CHICAGO | 60634 | 123     | 149      | 138   | 148   | 135 | 183  | 215  | 186    | 158       | 172     | 164      | 115      | 1886 | 
| Avalon         | 8148 S. Stony Island Avenue | CHICAGO | 60617 | 198     | 259      | 213   | 198   | 238 | 221  | 282  | 246    | 224       | 259     | 204      | 191      | 2733 | 
| Beverly        | 1962 W. 95th Street         | CHICAGO | 60643 | 185     | 162      | 183   | 184   | 173 | 232  | 160  | 192    | 134       | 215     | 143      | 102      | 2065 | 
| Bezazian       | 1226 W. Ainslie Street      | CHICAGO | 60640 | 386     | 388      | 414   | 384   | 352 | 397  | 339  | 433    | 405       | 423     | 273      | 257      | 4451 | 
| Blackstone     | 4904 S. Lake Park Avenue    | CHICAGO | 60615 | 149     | 120      | 152   | 174   | 140 | 202  | 217  | 155    | 164       | 205     | 170      | 146      | 1994 | 
| Brainerd       | 1350 W. 89th Street         | CHICAGO | 60620 | 33      | 37       | 30    | 50    | 56  | 61   | 65   | 60     | 52        | 64      | 54       | 48       | 610  | 
```