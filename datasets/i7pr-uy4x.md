# DBEDT Hawaii De Facto Population By County 2000-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-de-facto-population-by-county-2000-2010-a67b7) |
| Metadata | [Link](https://data.hawaii.gov/api/views/i7pr-uy4x) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/i7pr-uy4x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/i7pr-uy4x/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | i7pr-uy4x |
| Name | DBEDT Hawaii De Facto Population By County 2000-2010 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | people, population |
| Created | 2012-08-28T19:43:49Z |
| Publication Date | 2012-08-29T01:28:08Z |
| Rows Updated | 2012-08-28T19:44:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| No       | time           | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | numeric metric | x_values                    | X Values                    | number    | number      |
| Yes      | numeric metric | city_and_county_of_honolulu | City and County of Honolulu | number    | number      |
| Yes      | numeric metric | hawaii_county               | Hawaii County               | number    | number      |
| Yes      | numeric metric | kauai_county                | Kauai County                | number    | number      |
| Yes      | numeric metric | maui_county                 | Maui County                 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:i7pr-uy4x d:2012-08-28T12:43:50.000Z m:hawaii_county=137103 m:city_and_county_of_honolulu=913268 m:maui_county=138390 m:x_values=1990 m:kauai_county=68558

series e:i7pr-uy4x d:2012-08-28T12:43:50.000Z m:hawaii_county=141240 m:city_and_county_of_honolulu=901717 m:maui_county=139703 m:x_values=1991 m:kauai_county=69605

series e:i7pr-uy4x d:2012-08-28T12:43:50.000Z m:hawaii_county=146421 m:city_and_county_of_honolulu=912514 m:maui_county=146651 m:x_values=1992 m:kauai_county=66076
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:city_and_county_of_honolulu p:integer l:"City and County of Honolulu" t:dataTypeName=number

metric m:hawaii_county p:integer l:"Hawaii County" t:dataTypeName=number

metric m:kauai_county p:integer l:"Kauai County" t:dataTypeName=number

metric m:maui_county p:integer l:"Maui County" t:dataTypeName=number

entity e:i7pr-uy4x l:"DBEDT Hawaii De Facto Population By County 2000-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/i7pr-uy4x

property e:i7pr-uy4x t:meta.view v:id=i7pr-uy4x v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii De Facto Population By County 2000-2010" v:attribution="Department of Economic Development and Tourism"

property e:i7pr-uy4x t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:i7pr-uy4x t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:i7pr-uy4x t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```