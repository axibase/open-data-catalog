# Election Maps - Statewide

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-maps-statewide) |
| Metadata | [Link](https://data.hawaii.gov/api/views/qjpr-gyut) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/qjpr-gyut/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/qjpr-gyut/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | qjpr-gyut |
| Name | Election Maps - Statewide |
| Created | 2015-02-27T20:54:58Z |
| Publication Date | 2016-01-25T20:27:26Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | map_name    | MAP NAME    | html      | html        |
| Yes      | series tag  | description | DESCRIPTION | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qjpr-gyut d:2016-01-25T12:25:37.000Z t:map_name="<a target=""_blank"" href=""http://files.hawaii.gov/elections/files/maps/electionmaps/ISLAND_OF_HAWAII.pdf""> Hawaii Map: Island view</a>" t:description="Hawaii Island" m:row_number.qjpr-gyut=1

series e:qjpr-gyut d:2016-01-25T12:25:37.000Z t:map_name="<a target=""_blank"" href=""http://files.hawaii.gov/elections/files/maps/electionmaps/HAWAII1.pdf""> Hawaii #1: Waipio - Kohala Mountain</a>" t:description="Waipio - Kohala Mountain" m:row_number.qjpr-gyut=2

series e:qjpr-gyut d:2016-01-25T12:25:37.000Z t:map_name="<a target=""_blank"" href=""http://files.hawaii.gov/elections/files/maps/electionmaps/HAWAII2.pdf""> Hawaii #2: Hilo</a>" t:description=Hilo m:row_number.qjpr-gyut=3
```

## Meta Commands

```ls
metric m:row_number.qjpr-gyut p:long l:"Row Number"

entity e:qjpr-gyut l:"Election Maps - Statewide" t:url=https://data.hawaii.gov/api/views/qjpr-gyut

property e:qjpr-gyut t:meta.view d:2017-09-25T07:25:25.725Z v:averageRating=0 v:name="Election Maps - Statewide" v:id=qjpr-gyut

property e:qjpr-gyut t:meta.view.owner d:2017-09-25T07:25:25.725Z v:displayName="Office of Elections" v:id=a7h7-u2zq v:screenName="Office of Elections"

property e:qjpr-gyut t:meta.view.tableauthor d:2017-09-25T07:25:25.725Z v:displayName="Office of Elections" v:roleName=publisher v:id=a7h7-u2zq v:screenName="Office of Elections"
```

## Top Records

```ls
| :updated_at | map_name                            | description              | 
| =========== | =================================== | ======================== | 
| 1453724737  | Hawaii Map: Island view             | Hawaii Island            | 
| 1453724737  | Hawaii #1: Waipio - Kohala Mountain | Waipio - Kohala Mountain | 
| 1453724737  | Hawaii #2: Hilo                     | Hilo                     | 
| 1453724737  | Hawaii #3: Keaau                    | Keaau                    | 
| 1453724737  | Hawaii #4: Volcano - Glenwood       | Volcano - Glenwood       | 
| 1453724737  | Hawaii #5: Puna - Pahoa             | Puna - Pahoa             | 
| 1453724737  | Hawaii #6: Captain Cook - Honaunau  | Captain Cook - Honaunau  | 
| 1453724737  | Hawaii #7: Kailua-Kona              | Kailua-Kona              | 
| 1453724737  | Hawaii #8: Honokohau                | Honokohau                | 
| 1453724737  | Hawaii #9: Kalaoa - Puunahulu       | Kalaoa - Puunahulu       | 
```