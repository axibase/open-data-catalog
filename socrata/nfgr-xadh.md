# Animal Control - Species by City And Gender - Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-species-by-city-and-gender-fiscal-year-2010-60e6b) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/nfgr-xadh) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nfgr-xadh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/nfgr-xadh/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | nfgr-xadh |
| Name | Animal Control - Species by City And Gender - Fiscal Year 2010 |
| Attribution | Cook County Department of Animal Control |
| Category | Finance & Administration |
| Created | 2011-09-23T17:45:43Z |
| Publication Date | 2014-10-09T22:16:21Z |

## Description

A breakdown of registered animals by City and gender in Fiscal Year 2010

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | time           | year       | Year      | number    | number      |
| Yes      | series tag     | sex        | Sex       | text      | text        |
| Yes      | numeric metric | cat        | CAT       | number    | number      |
| Yes      | numeric metric | cow        | COW       | number    | number      |
| Yes      | numeric metric | dog        | DOG       | number    | number      |
| Yes      | numeric metric | ferret     | FERRET    | number    | number      |
| Yes      | numeric metric | guard_dog  | GUARD DOG | number    | number      |
| Yes      | numeric metric | rabbit     | RABBIT    | number    | number      |
| Yes      | numeric metric | unknown    | UNKNOWN   | number    | number      |
| Yes      | numeric metric | totals     | Totals    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nfgr-xadh d:2010-01-01T00:00:00.000Z t:sex=FEMALE m:rabbit=0 m:cat=3 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=21 m:dog=18 m:ferret=0

series e:nfgr-xadh d:2010-01-01T00:00:00.000Z t:sex="FEMALE SPAYED" m:rabbit=0 m:cat=17 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=51 m:dog=34 m:ferret=0

series e:nfgr-xadh d:2010-01-01T00:00:00.000Z t:sex=MALE m:rabbit=0 m:cat=2 m:cow=0 m:guard_dog=0 m:unknown=0 m:totals=21 m:dog=19 m:ferret=0
```

## Meta Commands

```ls
metric m:cat p:integer l:CAT t:dataTypeName=number

metric m:cow p:integer l:COW t:dataTypeName=number

metric m:dog p:integer l:DOG t:dataTypeName=number

metric m:ferret p:integer l:FERRET t:dataTypeName=number

metric m:guard_dog p:integer l:"GUARD DOG" t:dataTypeName=number

metric m:rabbit p:integer l:RABBIT t:dataTypeName=number

metric m:unknown p:integer l:UNKNOWN t:dataTypeName=number

metric m:totals p:integer l:Totals t:dataTypeName=number

entity e:nfgr-xadh l:"Animal Control - Species by City And Gender - Fiscal Year 2010" t:attribution="Cook County Department of Animal Control" t:url=https://datacatalog.cookcountyil.gov/api/views/nfgr-xadh

property e:nfgr-xadh t:meta.view v:id=nfgr-xadh v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/animal___rabies_control/247 v:averageRating=0 v:name="Animal Control - Species by City And Gender - Fiscal Year 2010" v:attribution="Cook County Department of Animal Control"

property e:nfgr-xadh t:meta.view.license v:name="Public Domain"

property e:nfgr-xadh t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:nfgr-xadh t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| year | sex           | cat | cow | dog | ferret | guard_dog | rabbit | unknown | totals | 
| ==== | ============= | === | === | === | ====== | ========= | ====== | ======= | ====== | 
| 2010 | FEMALE        | 3   | 0   | 18  | 0      | 0         | 0      | 0       | 21     | 
| 2010 | FEMALE SPAYED | 17  | 0   | 34  | 0      | 0         | 0      | 0       | 51     | 
| 2010 | MALE          | 2   | 0   | 19  | 0      | 0         | 0      | 0       | 21     | 
| 2010 | MALE CAST     | 7   | 0   | 26  | 0      | 0         | 0      | 0       | 33     | 
| 2010 | UNKNOWN       | 1   | 0   | 6   | 0      | 0         | 0      | 0       | 7      | 
| 2010 | FEMALE        | 0   | 0   | 8   | 0      | 0         | 0      | 0       | 8      | 
| 2010 | FEMALE SPAYED | 4   | 0   | 15  | 0      | 0         | 0      | 1       | 20     | 
| 2010 | MALE          | 0   | 0   | 9   | 0      | 0         | 0      | 0       | 9      | 
| 2010 | MALE CAST     | 2   | 0   | 13  | 0      | 0         | 0      | 0       | 15     | 
| 2010 | UNKNOWN       | 0   | 0   | 1   | 0      | 0         | 0      | 0       | 1      | 
```