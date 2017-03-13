# Austin Water Authorized Irrigation Inspector List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-authorized-irrigation-inspector-list) |
| Metadata | [Link](https://data.austintexas.gov/api/views/dhvz-stgx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/dhvz-stgx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/dhvz-stgx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | dhvz-stgx |
| Name | Austin Water Authorized Irrigation Inspector List |
| Attribution | Austin Water |
| Category | Environmental |
| Tags | austin water, irrigation, inspector, water, code, property owner |
| Created | 2016-10-06T21:01:26Z |
| Publication Date | 2016-10-06T21:06:32Z |
| Rows Updated | 2016-10-06T21:01:32Z |

## Description

Austin Water?s authorized irrigation inspectors are approved to perform the irrigation evaluation required by City Code 6-4-10(A) Facilities Regulated. Each property owner/manager is responsible for selecting an inspector. Individuals on this list are provided as a resource without endorsement by the City of Austin.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | inspector_number | Inspector Number | text      | text        |
| Yes      | series tag  | first_name       | First Name       | text      | text        |
| Yes      | series tag  | last_name        | Last Name        | text      | text        |
| Yes      | series tag  | company          | Company          | text      | text        |
| Yes      | series tag  | telephone        | Telephone        | text      | text        |
| Yes      | series tag  | email            | Email            | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:dhvz-stgx l:"Austin Water Authorized Irrigation Inspector List" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/dhvz-stgx

property e:dhvz-stgx t:meta.view v:id=dhvz-stgx v:category=Environmental v:attributionLink=http://waterwiseaustin.org v:averageRating=0 v:name="Austin Water Authorized Irrigation Inspector List" v:attribution="Austin Water"

property e:dhvz-stgx t:meta.view.owner v:id=dg6c-4vht v:profileImageUrlMedium=/api/users/dg6c-4vht/profile_images/THUMB v:profileImageUrlLarge=/api/users/dg6c-4vht/profile_images/LARGE v:screenName="Austin Water" v:profileImageUrlSmall=/api/users/dg6c-4vht/profile_images/TINY v:roleName=editor v:displayName="Austin Water"

property e:dhvz-stgx t:meta.view.tableauthor v:id=dg6c-4vht v:profileImageUrlMedium=/api/users/dg6c-4vht/profile_images/THUMB v:profileImageUrlLarge=/api/users/dg6c-4vht/profile_images/LARGE v:screenName="Austin Water" v:profileImageUrlSmall=/api/users/dg6c-4vht/profile_images/TINY v:roleName=editor v:displayName="Austin Water"
```