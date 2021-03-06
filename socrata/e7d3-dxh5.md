# 2013 Housing Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-housing-inventory-b6675) |
| Metadata | [Link](https://data.sfgov.org/api/views/e7d3-dxh5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/e7d3-dxh5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/e7d3-dxh5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | e7d3-dxh5 |
| Name | 2013 Housing Inventory |
| Attribution | San Francisco Planning Department |
| Category | Housing and Buildings |
| Tags | 2013, housing, new housing construction, housing units, net new units, demolition, merger, conversion, alteration, housing stock, housing inventory, illegal units removed |
| Created | 2014-05-06T22:32:11Z |
| Publication Date | 2015-09-23T22:35:01Z |

## Description

Excel workbook of all housing construction from the 2013 Housing Inventory.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name       | Data Type     | Render Type   |
| ======== | ============== | =============== | ========== | ============= | ============= |
| No       |                | standardaddress | STDADDRESS | text          | text          |
| Yes      | series tag     | name            | PRJ_NAME   | text          | text          |
| Yes      | series tag     | block           | BLOCK      | text          | text          |
| Yes      | series tag     | lot             | LOT        | text          | number        |
| Yes      | numeric metric | units           | UNITS      | number        | number        |
| Yes      | numeric metric | netunits        | NETUNITS   | number        | number        |
| Yes      | numeric metric | aff_hsg         | AFF_HSG    | number        | number        |
| Yes      | series tag     | aff_cat         | AFF_TARGET | text          | text          |
| Yes      | series tag     | change_type     | CNG_TYPE   | text          | text          |
| Yes      | series tag     | existuse        | EXISTUSE   | text          | text          |
| Yes      | series tag     | propuse         | PROPUSE    | text          | text          |
| Yes      | time           | actdate         | ACTDATE    | calendar_date | calendar_date |
| Yes      | series tag     | zoning          | Zoning     | text          | text          |
| Yes      | series tag     | pd_no           | PD_NO      | text          | number        |
| Yes      | series tag     | supervisor      | SD_NO      | text          | number        |
| Yes      | series tag     | planarea        | PLANAREA   | text          | text          |
```

## Time Field

```ls
Value = actdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = standardaddress
```

## Data Commands

```ls
series e:e7d3-dxh5 d:2013-07-30T00:00:00.000Z t:lot=52 t:pd_no=12 t:zoning="RH-1 (D)" t:change_type=Demolition t:block=3702 t:aff_cat=LI t:supervisor=9 m:units=-418 m:netunits=-418

series e:e7d3-dxh5 d:2013-07-18T00:00:00.000Z t:lot=9 t:pd_no=14 t:zoning=RH-2 t:propuse=APARTMENTS t:change_type="New Construction" t:block=4624 t:aff_cat=VLI t:supervisor=5 m:aff_hsg=54 m:units=54 m:netunits=54

series e:e7d3-dxh5 d:2013-10-02T00:00:00.000Z t:lot=8 t:pd_no=14 t:zoning=RH-2 t:propuse=APARTMENTS t:change_type=Conversion t:existuse="TOURIST HOTEL/MOTEL" t:block=3753 t:aff_cat=LI t:supervisor=5 m:aff_hsg=44 m:units=44 m:netunits=44
```

## Meta Commands

```ls
metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:netunits p:integer l:NETUNITS t:dataTypeName=number

metric m:aff_hsg p:integer l:AFF_HSG t:dataTypeName=number

entity e:e7d3-dxh5 l:"2013 Housing Inventory" t:attribution="San Francisco Planning Department" t:url=https://data.sfgov.org/api/views/e7d3-dxh5

property e:e7d3-dxh5 t:meta.view d:2017-09-25T07:29:43.062Z v:averageRating=0 v:name="2013 Housing Inventory" v:attribution="San Francisco Planning Department" v:attributionLink=http://www.sf-planning.org/ftp/files/publications_reports/Housing_Inventory_2013.pdf v:id=e7d3-dxh5 v:category="Housing and Buildings"

property e:e7d3-dxh5 t:meta.view.license d:2017-09-25T07:29:43.062Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:e7d3-dxh5 t:meta.view.owner d:2017-09-25T07:29:43.062Z v:displayName="Information & Analysis Group (IAG) - SFPlanning" v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning"

property e:e7d3-dxh5 t:meta.view.tableauthor d:2017-09-25T07:29:43.062Z v:displayName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| standardaddress  | name                     | block | lot | units | netunits | aff_hsg | aff_cat | change_type      | existuse            | propuse    | actdate             | zoning   | pd_no | supervisor | planarea              | 
| ================ | ======================== | ===== | === | ===== | ======== | ======= | ======= | ================ | =================== | ========== | =================== | ======== | ===== | ========== | ===================== | 
| 1190 MISSION ST  |                          | 3702  | 52  | -418  | -418     |         | LI      | Demolition       |                     |            | 2013-07-30T00:00:00 | RH-1 (D) | 12    | 9          |                       | 
| 60 WEST POINT RD |                          | 4624  | 9   | 54    | 54       | 54      | VLI     | New Construction |                     | APARTMENTS | 2013-07-18T00:00:00 | RH-2     | 14    | 5          |                       | 
| 374 05TH ST      |                          | 3753  | 8   | 44    | 44       | 44      | LI      | Conversion       | TOURIST HOTEL/MOTEL | APARTMENTS | 2013-10-02T00:00:00 | RH-2     | 14    | 5          |                       | 
| 1461 PINE ST     |                          | 668   | 13  | 35    | 35       | 0       |         | New Construction |                     | APARTMENTS | 2013-03-14T00:00:00 | RH-1     | 12    | 9          |                       | 
| 48 HARRIET ST    |                          | 3731  | 102 | 23    | 23       | 0       |         | New Construction |                     | APARTMENTS | 2013-02-20T00:00:00 | RH-1     | 11    | 9          |                       | 
| 1190 MISSION ST  | Trinity Place            | 3702  | 52  | 418   | 418      | 63      | LI      | New Construction |                     |            | 2013-10-03T00:00:00 | RH-1 (D) | 12    | 9          |                       | 
| 333 HARRISON ST  | Rincon Green             | 3766  | 9   | 326   | 326      | 49      | LI      | New Construction |                     | APARTMENTS | 2013-02-27T00:00:00 | RM-4     | 3     | 3          |                       | 
| 1407 MARKET ST   | Nema                     | 3507  | 41  | 317   | 317      | 38      | LI      | New Construction |                     |            |                     | RH-2     | 9     | 10         | Eastern Neighborhoods | 
| 1880 MISSION ST  | Vara                     | 3547  | 29  | 202   | 202      | 40      | LI      | New Construction |                     | APARTMENTS | 2013-09-30T00:00:00 | RH-1     | 12    | 11         |                       | 
| 25 ESSEX ST      | Rene Cazenave Apartments | 3749  | 64  | 120   | 120      | 120     | VLI     | New Construction |                     | APARTMENTS | 2013-11-22T00:00:00 | RM-1     | 10    | 10         | Bayview               | 
```