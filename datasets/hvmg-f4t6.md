# Survey Markers - Retired

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/survey-markers-retired) |
| Metadata | [Link](https://data.iowa.gov/api/views/hvmg-f4t6) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/hvmg-f4t6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/hvmg-f4t6/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | hvmg-f4t6 |
| Name | Survey Markers - Retired |
| Attribution | Iowa Department of Transportation - Office of Design |
| Category | Transportation & Utilities |
| Tags | reference, survey, retired, control monument, cadastre, iowa dot, iowa department of transportation |
| Created | 2016-07-06T18:42:17Z |
| Publication Date | 2016-07-06T18:56:50Z |
| Rows Updated | 2016-07-06T18:42:17Z |

## Description

This layer contains the archived records for survey markers that are considered retired.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       |                | id                | ID                | text      | number      |
| Yes      | series tag     | survey_id         | SURVEY_ID         | text      | text        |
| No       |                | xcoord            | XCOORD            | number    | number      |
| No       |                | ycoord            | YCOORD            | number    | number      |
| Yes      | numeric metric | zcoord            | ZCOORD            | number    | number      |
| Yes      | series tag     | feature_type      | FEATURE_TYPE      | text      | text        |
| Yes      | series tag     | description       | DESCRIPTION       | text      | text        |
| Yes      | series tag     | project_number    | PROJECT_NUMBER    | text      | text        |
| Yes      | series tag     | proj_dir_url      | PROJ_DIR_URL      | text      | text        |
| Yes      | series tag     | horiz_datum       | HORIZ_DATUM       | text      | text        |
| Yes      | series tag     | network           | NETWORK           | text      | text        |
| Yes      | series tag     | coord_system      | COORD_SYSTEM      | text      | text        |
| Yes      | series tag     | vert_datum        | VERT_DATUM        | text      | text        |
| Yes      | series tag     | owner             | OWNER             | text      | text        |
| Yes      | series tag     | date_added        | DATE_ADDED        | text      | text        |
| Yes      | series tag     | uploader_name     | UPLOADER_NAME     | text      | text        |
| Yes      | numeric metric | precision_quality | PRECISION_QUALITY | number    | text        |
| Yes      | numeric metric | ls_certified      | LS_CERTIFIED      | number    | text        |
| Yes      | numeric metric | status            | STATUS            | number    | text        |
| Yes      | time           | capturedateyear   | CAPTUREDATEYEAR   | number    | number      |
| Yes      | numeric metric | capturedatemonth  | CAPTUREDATEMONTH  | number    | number      |
| Yes      | numeric metric | capturedateday    | CAPTUREDATEDAY    | number    | number      |
```

## Time Field

```ls
Value = capturedateyear
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id,ycoord,xcoord
```

## Data Commands

```ls
series e:hvmg-f4t6 d:2014-01-01T00:00:00.000Z t:feature_type=CP t:status=R t:project_number="STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2" t:vert_datum="NAVD88 (Computed using Geoid12A)" t:network="IaRTN 2013 Adjustment" t:horiz_datum="NAD83(2011) (EPOCH2010.00)" t:precision_quality=A t:proj_dir_url=pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ t:coord_system="IA North US Feet" t:date_added="08/18/2015 15:27" t:description="FND WRIGHT CO. SURVEY MONUMENT 0011" t:ls_certified=N t:owner="Office of Design" t:survey_id=11 m:zcoord=1180.421 m:capturedatemonth=12 m:capturedateday=16

series e:hvmg-f4t6 d:2014-01-01T00:00:00.000Z t:feature_type=FENO t:status=R t:project_number="STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2" t:vert_datum="NAVD88 (Computed using Geoid12A)" t:network="IaRTN 2013 Adjustment" t:horiz_datum="NAD83(2011) (EPOCH2010.00)" t:precision_quality=A t:proj_dir_url=pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ t:coord_system="IA North US Feet" t:date_added="08/18/2015 15:27" t:description="O SET FENO TYPE MONUMENT" t:ls_certified=N t:owner="Office of Design" t:survey_id=2 m:zcoord=1172.748 m:capturedatemonth=12 m:capturedateday=16

series e:hvmg-f4t6 d:2014-01-01T00:00:00.000Z t:feature_type=CP t:status=R t:project_number="STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2" t:vert_datum="NAVD88 (Computed using Geoid12A)" t:network="IaRTN 2013 Adjustment" t:horiz_datum="NAD83(2011) (EPOCH2010.00)" t:precision_quality=A t:proj_dir_url=pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ t:coord_system="IA North US Feet" t:date_added="08/18/2015 15:31" t:description="FND WRIGHT CO. SURVEY MONUMENT 0011" t:ls_certified=N t:owner="Office of Design" t:survey_id=11 m:zcoord=1180.421 m:capturedatemonth=12 m:capturedateday=16
```

## Meta Commands

```ls
metric m:zcoord l:ZCOORDeName=number

metric m:capturedatemonth p:integer l:CAPTUREDATEMONTH:dataTypeName=number

metric m:capturedateday p:integer l:CAPTUREDATEDAYataTypeName=number

entity e:hvmg-f4t6 l:"Survey Markers - Retired" t:attribution="Iowa Department of Transportation - Office of Design" t:url=https://data.iowa.gov/api/views/hvmg-f4t6

property e:hvmg-f4t6 t:meta.view v:id=hvmg-f4t6 v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Survey/Survey_Markers/MapServer/1 v:averageRating=0 v:name="Survey Markers - Retired" v:attribution="Iowa Department of Transportation - Office of Design"

property e:hvmg-f4t6 t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"

property e:hvmg-f4t6 t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```