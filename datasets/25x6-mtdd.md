# Interstate Closure Gates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/interstate-closure-gates) |
| Metadata | [Link](https://data.iowa.gov/api/views/25x6-mtdd) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/25x6-mtdd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/25x6-mtdd/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 25x6-mtdd |
| Name | Interstate Closure Gates |
| Attribution | Iowa Department of Transportation - Office of Maintenance |
| Category | Transportation & Utilities |
| Tags | asset, inventory, operations, gates, maintenance, iowa dot, iowa department of transportation |
| Created | 2016-06-08T19:09:21Z |
| Publication Date | 2016-06-08T19:11:20Z |
| Rows Updated | 2016-06-08T19:09:21Z |

## Description

This is a representation of all gates and barricades that prevent access to the interstates. It consists of mainline barricades (left and right) that are physically located in the median and shoulder of the interstate that can be automatically lowered to prevent travel in the event of a road closure. It also includes ramp barricades that prevent travel onto the interstate by means of the entrance ramps, denoted with a "Road Closed" sign posted on a gate.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | gate_id             | GATE_ID             | text      | text        |
| Yes      | series tag     | district            | DISTRICT            | text      | number      |
| Yes      | numeric metric | cost_center         | COST_CENTER         | number    | text        |
| Yes      | numeric metric | route               | ROUTE               | number    | number      |
| Yes      | series tag     | dirtravel           | DIRTRAVEL           | text      | text        |
| Yes      | series tag     | sideofroad          | SIDEOFROAD          | text      | text        |
| Yes      | numeric metric | milepost            | MILEPOST            | number    | text        |
| Yes      | numeric metric | milepost_offset     | MILEPOST_OFFSET     | number    | number      |
| No       |                | latitude            | LATITUDE            | number    | number      |
| No       |                | longitude           | LONGITUDE           | number    | number      |
| Yes      | series tag     | sign_face_direction | SIGN_FACE_DIRECTION | text      | text        |
| Yes      | series tag     | signtype            | SIGNTYPE            | text      | text        |
| Yes      | series tag     | subcategory         | SUBCATEGORY         | text      | text        |
| Yes      | series tag     | description         | DESCRIPTION         | text      | text        |
| Yes      | series tag     | remarks             | REMARKS             | text      | text        |
| Yes      | series tag     | activation_type     | ACTIVATION_TYPE     | text      | text        |
| Yes      | series tag     | objectid            | OBJECTID            | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
series e:25x6-mtdd d:1970-01-01T00:00:00.000Z t:gate_id=A91341ADAF9244C890920563507EC3F4 t:activation_type=Manual t:description="Ramp Barricade" t:dirtravel=Ramp t:sideofroad=Left t:objectid=1 t:district=1 t:sign_face_direction=N t:signtype=Regulatory m:cost_center=551609 m:milepost=159 m:route=35 m:milepost_offset=0

series e:25x6-mtdd d:1970-01-01T00:00:00.000Z t:gate_id=0FA20C59470E43D88F65A88F67A49F2E t:activation_type=Remote t:description="Right Mainline Barricade" t:subcategory="No Subcategory" t:dirtravel="With Milepost (increasing in number)" t:sideofroad=Right t:objectid=2 t:district=4 t:sign_face_direction=S t:signtype=Guide m:cost_center=554810 m:milepost=75 m:route=29 m:milepost_offset=0.557

series e:25x6-mtdd d:1970-01-01T00:00:00.000Z t:gate_id=7EF1FEF2035948EEB2C197E3593193A1 t:activation_type=Manual t:description="Ramp Barricade" t:dirtravel=Ramp t:remarks="Sign face SE when gate is CLOSED" t:sideofroad=Right t:objectid=3 t:district=4 t:sign_face_direction=SE t:signtype=Regulatory m:cost_center=554810 m:milepost=75 m:route=29 m:milepost_offset=0
```

## Meta Commands

```ls
metric m:cost_center p:integer l:COST_CENTER d:"Cost Center" t:dataTypeName=number

metric m:route p:integer l:ROUTE d:Route t:dataTypeName=number

metric m:milepost p:integer l:MILEPOST d:"Mile Post" t:dataTypeName=number

metric m:milepost_offset p:decimal l:MILEPOST_OFFSET d:Offset t:dataTypeName=number

entity e:25x6-mtdd l:"Interstate Closure Gates" t:attribution="Iowa Department of Transportation - Office of Maintenance" t:url=https://data.iowa.gov/api/views/25x6-mtdd

property e:25x6-mtdd t:meta.view v:id=25x6-mtdd v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Maintenance/Closure_Gates/MapServer/0 v:averageRating=0 v:name="Interstate Closure Gates" v:attribution="Iowa Department of Transportation - Office of Maintenance"

property e:25x6-mtdd t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"

property e:25x6-mtdd t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```