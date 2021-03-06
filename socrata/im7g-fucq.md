# Missouri Zip Codes by County/City

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-zip-codes-by-county-city-a85bf) |
| Metadata | [Link](https://data.mo.gov/api/views/im7g-fucq) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/im7g-fucq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/im7g-fucq/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | im7g-fucq |
| Name | Missouri Zip Codes by County/City |
| Category | Geography |
| Created | 2012-02-15T18:41:53Z |
| Publication Date | 2013-06-27T15:17:49Z |

## Description

List of cities, zip codes and counties in Missouri

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | county      | county     | text      | text        |
| Yes      | series tag  | zip_code    | zip code   | text      | text        |
| Yes      | series tag  | city        | city       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:im7g-fucq d:2012-02-15T10:41:59.000Z t:city=Acornridge t:county=Stoddard t:zip_code=63960 m:row_number.im7g-fucq=1

series e:im7g-fucq d:2012-02-15T10:41:59.000Z t:city=Adair t:county=Adair t:zip_code=63533 m:row_number.im7g-fucq=2

series e:im7g-fucq d:2012-02-15T10:41:59.000Z t:city=Adrian t:county=Bates t:zip_code=64720 m:row_number.im7g-fucq=3
```

## Meta Commands

```ls
metric m:row_number.im7g-fucq p:long l:"Row Number"

entity e:im7g-fucq l:"Missouri Zip Codes by County/City" t:url=https://data.mo.gov/api/views/im7g-fucq

property e:im7g-fucq t:meta.view d:2017-09-25T07:31:40.321Z v:averageRating=0 v:name="Missouri Zip Codes by County/City" v:id=im7g-fucq v:category=Geography

property e:im7g-fucq t:meta.view.owner d:2017-09-25T07:31:40.321Z v:displayName=Breanna v:lastNotificationSeenAt=1504107758 v:id=jzbz-iqr6 v:screenName=Breanna

property e:im7g-fucq t:meta.view.tableauthor d:2017-09-25T07:31:40.321Z v:displayName="Rodney Distler" v:profileImageUrlLarge=/api/users/8xqn-4t42/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/8xqn-4t42/profile_images/TINY v:id=8xqn-4t42 v:screenName="Rodney Distler" v:profileImageUrlMedium=/api/users/8xqn-4t42/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | county      | zip_code | city       | 
| =========== | =========== | ======== | ========== | 
| 1329302519  | Stoddard    | 63960    | Acornridge | 
| 1329302519  | Adair       | 63533    | Adair      | 
| 1329302519  | Bates       | 64720    | Adrian     | 
| 1329302519  | Stoddard    | 63730    | Advance    | 
| 1329302519  | Saint Louis | 63123    | Affton     | 
| 1329302519  | Buchanan    | 64401    | Agency     | 
| 1329302519  | Jasper      | 64830    | Alba       | 
| 1329302519  | Gentry      | 64402    | Albany     | 
| 1329302519  | Polk        | 65601    | Aldrich    | 
| 1329302519  | Clark       | 63430    | Alexandria | 
```