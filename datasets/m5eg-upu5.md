# Home Health Care - Zip Codes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-health-care-zip-codes-0c0fb) |
| Metadata | [Link](https://data.medicare.gov/api/views/m5eg-upu5) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/m5eg-upu5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/m5eg-upu5/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | m5eg-upu5 |
| Name | Home Health Care - Zip Codes |
| Category | Home Health Compare |
| Tags | hhc, general information |
| Created | 2012-10-17T19:56:31Z |
| Publication Date | 2017-01-26T01:48:47Z |
| Rows Updated | 2017-01-05T16:42:03Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name                            | Data Type | Render Type |
| ======== | ============== | =============== | =============================== | ========= | =========== |
| No       | time           | :updated_at     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | state           | State                           | text      | text        |
| Yes      | numeric metric | provider_number | CMS Certification Number (CCN)* | number    | text        |
| Yes      | series tag     | zip_code        | ZIP Code                        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:m5eg-upu5 d:2017-01-05T16:16:55.000Z t:zip_code=36104 t:state=AL m:provider_number=17000

series e:m5eg-upu5 d:2017-01-05T16:16:55.000Z t:zip_code=35005 t:state=AL m:provider_number=17008

series e:m5eg-upu5 d:2017-01-05T16:16:55.000Z t:zip_code=35020 t:state=AL m:provider_number=17008
```

## Meta Commands

```ls
metric m:provider_number p:integer l:"CMS Certification Number (CCN)*" d:"formerly Medicare Provider Number" t:dataTypeName=number

entity e:m5eg-upu5 l:"Home Health Care - Zip Codes" t:url=https://data.medicare.gov/api/views/m5eg-upu5

property e:m5eg-upu5 t:meta.view v:id=m5eg-upu5 v:category="Home Health Compare" v:averageRating=0 v:name="Home Health Care - Zip Codes"

property e:m5eg-upu5 t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:m5eg-upu5 t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:m5eg-upu5 t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HomeHealthQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```