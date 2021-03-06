# 2 -- Government $$ By Biennium

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2-government-by-biennium-9914b) |
| Metadata | [Link](https://data.wa.gov/api/views/dbre-5vfk) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/dbre-5vfk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/dbre-5vfk/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | dbre-5vfk |
| Name | 2 -- Government $$ By Biennium |
| Created | 2012-10-17T12:37:48Z |
| Publication Date | 2012-10-17T12:38:16Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | biennium         | Biennium         | text      | text        |
| Yes      | numeric metric | state_all        | State -- All     | money     | money       |
| Yes      | numeric metric | local_all        | Local -- All     | money     | money       |
| Yes      | numeric metric | federal_all      | Federal -- All   | money     | money       |
| Yes      | numeric metric | total            | Total            | money     | money       |
| Yes      | numeric metric | cumulative_total | Cumulative Total | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dbre-5vfk d:2012-10-17T05:37:50.000Z t:biennium=1999-01 m:total=169990013 m:state_all=37040000 m:local_all=57645939 m:federal_all=75304074 m:cumulative_total=169990013

series e:dbre-5vfk d:2012-10-17T05:37:50.000Z t:biennium=2001-03 m:total=106139000 m:state_all=26351000 m:local_all=11986684 m:federal_all=67801316 m:cumulative_total=276129012

series e:dbre-5vfk d:2012-10-17T05:37:50.000Z t:biennium=2003-05 m:total=98357563 m:state_all=14000000 m:local_all=29054957 m:federal_all=55302606 m:cumulative_total=374486575
```

## Meta Commands

```ls
metric m:state_all p:integer l:"State -- All" t:dataTypeName=money

metric m:local_all p:integer l:"Local -- All" t:dataTypeName=money

metric m:federal_all p:integer l:"Federal -- All" t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

metric m:cumulative_total p:integer l:"Cumulative Total" t:dataTypeName=money

entity e:dbre-5vfk l:"2 -- Government $$ By Biennium" t:url=https://data.wa.gov/api/views/dbre-5vfk

property e:dbre-5vfk t:meta.view d:2017-09-25T07:30:08.198Z v:averageRating=0 v:name="2 -- Government $$ By Biennium" v:id=dbre-5vfk

property e:dbre-5vfk t:meta.view.owner d:2017-09-25T07:30:08.198Z v:displayName="Jennifer Johnson" v:profileImageUrlLarge=/api/users/fuyk-waw8/profile_images/LARGE v:profileImageUrlSmall=/api/users/fuyk-waw8/profile_images/TINY v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:profileImageUrlMedium=/api/users/fuyk-waw8/profile_images/THUMB

property e:dbre-5vfk t:meta.view.tableauthor d:2017-09-25T07:30:08.198Z v:displayName="Jennifer Johnson" v:profileImageUrlLarge=/api/users/fuyk-waw8/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/fuyk-waw8/profile_images/TINY v:id=fuyk-waw8 v:screenName="Jennifer Johnson" v:profileImageUrlMedium=/api/users/fuyk-waw8/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | biennium | state_all | local_all | federal_all | total     | cumulative_total | 
| =========== | ======== | ========= | ========= | =========== | ========= | ================ | 
| 1350452270  | 1999-01  | 37040000  | 57645939  | 75304074    | 169990013 | 169990013        | 
| 1350452270  | 2001-03  | 26351000  | 11986684  | 67801316    | 106139000 | 276129012        | 
| 1350452270  | 2003-05  | 14000000  | 29054957  | 55302606    | 98357563  | 374486575        | 
| 1350452270  | 2005-07  | 22150000  | 43538018  | 47381625    | 113069643 | 487556218        | 
| 1350452270  | 2007-09  | 64750000  | 41817529  | 50769260    | 157336789 | 644893007        | 
| 1350452270  | 2009-11  | 55000000  | 27226196  | 60506361    | 142732557 | 787625564        | 
| 1350452270  | 2011-13  | 42000000  | 11765     | 22287814    | 64299579  | 851925143        | 
```