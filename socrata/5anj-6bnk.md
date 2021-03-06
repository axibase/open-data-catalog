# Joseph Creek Summer Steelhead -- 1112015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/joseph-creek-summer-steelhead-1112015-ced11) |
| Metadata | [Link](https://data.wa.gov/api/views/5anj-6bnk) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/5anj-6bnk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/5anj-6bnk/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 5anj-6bnk |
| Name | Joseph Creek Summer Steelhead -- 1112015 |
| Created | 2015-01-12T04:48:16Z |
| Publication Date | 2015-01-12T04:49:15Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | population_stock_number | Population/Stock Number | text      | number      |
| Yes      | time           | year                    | Year                    | number    | number      |
| Yes      | numeric metric | wild                    | Wild                    | number    | number      |
| Yes      | numeric metric | hatchery                | Hatchery                | number    | number      |
| Yes      | numeric metric | wild_hatchery           | Wild + Hatchery         | number    | number      |
| Yes      | numeric metric | goal_wild               | Goal (Wild)             | number    | number      |
| Yes      | series tag     | population_stock_name   | Population/Stock Name   | text      | text        |
| No       |                | listing_year            | Listing Year            | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = listing_year
```

## Data Commands

```ls
series e:5anj-6bnk d:1997-01-01T00:00:00.000Z t:population_stock_name="Joseph Creek Summer Steelhead" t:population_stock_number=6884 m:wild_hatchery=1251 m:goal_wild=1000 m:wild=1251

series e:5anj-6bnk d:1998-01-01T00:00:00.000Z t:population_stock_name="Joseph Creek Summer Steelhead" t:population_stock_number=6884 m:wild_hatchery=3171 m:goal_wild=1000 m:wild=3171

series e:5anj-6bnk d:1999-01-01T00:00:00.000Z t:population_stock_name="Joseph Creek Summer Steelhead" t:population_stock_number=6884 m:wild_hatchery=2133 m:goal_wild=1000 m:wild=2133
```

## Meta Commands

```ls
metric m:wild p:integer l:Wild t:dataTypeName=number

metric m:hatchery p:long l:Hatchery t:dataTypeName=number

metric m:wild_hatchery p:integer l:"Wild + Hatchery" t:dataTypeName=number

metric m:goal_wild p:integer l:"Goal (Wild)" t:dataTypeName=number

entity e:5anj-6bnk l:"Joseph Creek Summer Steelhead -- 1112015" t:url=https://data.wa.gov/api/views/5anj-6bnk

property e:5anj-6bnk t:meta.view d:2017-09-25T07:22:28.687Z v:averageRating=0 v:name="Joseph Creek Summer Steelhead -- 1112015" v:id=5anj-6bnk

property e:5anj-6bnk t:meta.view.owner d:2017-09-25T07:22:28.687Z v:displayName="Jennifer Johnson" v:profileImageUrlLarge=/api/users/fuyk-waw8/profile_images/LARGE v:profileImageUrlSmall=/api/users/fuyk-waw8/profile_images/TINY v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:profileImageUrlMedium=/api/users/fuyk-waw8/profile_images/THUMB

property e:5anj-6bnk t:meta.view.tableauthor d:2017-09-25T07:22:28.687Z v:displayName="Jennifer Johnson" v:profileImageUrlLarge=/api/users/fuyk-waw8/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/fuyk-waw8/profile_images/TINY v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:profileImageUrlMedium=/api/users/fuyk-waw8/profile_images/THUMB
```

## Top Records

```ls
| population_stock_number | year | wild | hatchery | wild_hatchery | goal_wild | population_stock_name         | listing_year | 
| ======================= | ==== | ==== | ======== | ============= | ========= | ============================= | ============ | 
| 6884                    | 1997 | 1251 |          | 1251          | 1000      | Joseph Creek Summer Steelhead | 1997         | 
| 6884                    | 1998 | 3171 |          | 3171          | 1000      | Joseph Creek Summer Steelhead | 1997         | 
| 6884                    | 1999 | 2133 |          | 2133          | 1000      | Joseph Creek Summer Steelhead | 1997         | 
| 6884                    | 2000 | 2020 |          | 2020          | 1000      | Joseph Creek Summer Steelhead | 1997         | 
| 6884                    | 2001 | 2596 |          | 2596          | 1000      | Joseph Creek Summer Steelhead | 1997         | 
| 6884                    | 2002 | 4752 |          | 4752          | 1000      | Joseph Creek Summer Steelhead | 1997         | 
| 6884                    | 2003 | 2381 |          | 2381          | 1000      | Joseph Creek Summer Steelhead | 1997         | 
| 6884                    | 2004 | 1756 |          | 1756          | 1000      | Joseph Creek Summer Steelhead | 1997         | 
| 6884                    | 2005 | 1832 |          | 1832          | 1000      | Joseph Creek Summer Steelhead | 1997         | 
| 6884                    | 2006 | 1428 |          | 1428          | 1000      | Joseph Creek Summer Steelhead | 1997         | 
```