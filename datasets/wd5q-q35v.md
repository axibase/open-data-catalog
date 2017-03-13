# SDOT Road Temperature Stations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-road-temperature-stations-2afd8) |
| Metadata | [Link](https://data.seattle.gov/api/views/wd5q-q35v) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/wd5q-q35v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/wd5q-q35v/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | wd5q-q35v |
| Name | SDOT Road Temperature Stations |
| Tags | storm response |
| Created | 2016-12-08T22:55:45Z |
| Publication Date | 2016-12-14T16:05:31Z |
| Rows Updated | 2016-12-08T22:55:45Z |

## Description

Displays the location and data being collected from road temperature stations in the City of Seattle. This data shows the road temperature and the air temperature at the location of the sensor and maintains records of temperature data collected up to 2 hours beforehand.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | objectid          | OBJECTID          | text      | number      |
| Yes      | series tag     | rwis_station_name | RWIS_STATION_NAME | text      | text        |
| Yes      | series tag     | rwis_display_name | RWIS_DISPLAY_NAME | text      | text        |
| Yes      | series tag     | rwis_datetime     | RWIS_DATETIME     | text      | text        |
| Yes      | numeric metric | rstemp_current    | RSTEMP_CURRENT    | number    | number      |
| Yes      | numeric metric | airtemp_current   | AIRTEMP_CURRENT   | number    | number      |
| Yes      | numeric metric | rstemp_15min      | RSTEMP_15MIN      | number    | number      |
| Yes      | numeric metric | airtemp_15min     | AIRTEMP_15MIN     | number    | number      |
| Yes      | numeric metric | rstemp_30min      | RSTEMP_30MIN      | number    | number      |
| Yes      | numeric metric | airtemp_30min     | AIRTEMP_30MIN     | number    | number      |
| Yes      | numeric metric | rstemp_45min      | RSTEMP_45MIN      | number    | number      |
| Yes      | numeric metric | airtemp_45min     | AIRTEMP_45MIN     | number    | number      |
| Yes      | numeric metric | rstemp_60min      | RSTEMP_60MIN      | number    | number      |
| Yes      | numeric metric | airtemp_60min     | AIRTEMP_60MIN     | number    | number      |
| Yes      | numeric metric | rstemp_75min      | RSTEMP_75MIN      | number    | number      |
| Yes      | numeric metric | airtemp_75min     | AIRTEMP_75MIN     | number    | number      |
| Yes      | numeric metric | rstemp_90min      | RSTEMP_90MIN      | number    | number      |
| Yes      | numeric metric | airtemp_90min     | AIRTEMP_90MIN     | number    | number      |
| Yes      | numeric metric | rstemp_105min     | RSTEMP_105MIN     | number    | number      |
| Yes      | numeric metric | airtemp_105min    | AIRTEMP_105MIN    | number    | number      |
| Yes      | numeric metric | rstemp_120min     | RSTEMP_120MIN     | number    | number      |
| Yes      | numeric metric | airtemp_120min    | AIRTEMP_120MIN    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wd5q-q35v d:1970-01-01T00:00:00.000Z t:rwis_datetime="2017-03-12 04:30:00" t:objectid=1 t:rwis_station_name=35thAveSW_SWMyrtleSt t:rwis_display_name="35th Ave SW at SW Myrtle St" m:airtemp_60min=44.53 m:rstemp_30min=44.39 m:rstemp_75min=44.59 m:airtemp_45min=44.47 m:airtemp_15min=44.33 m:airtemp_30min=44.39 m:rstemp_15min=44.33 m:rstemp_current=44.33 m:airtemp_75min=44.59 m:airtemp_current=44.33 m:rstemp_90min=44.61 m:rstemp_45min=44.47 m:rstemp_60min=44.53 m:airtemp_90min=44.61

series e:wd5q-q35v d:1970-01-01T00:00:00.000Z t:rwis_datetime="2017-03-12 04:30:00" t:objectid=2 t:rwis_station_name=AlaskanWayViaduct_KingSt t:rwis_display_name="Alaskan Way Viaduct at King St" m:airtemp_60min=46.62 m:rstemp_30min=46.25 m:rstemp_75min=46.56 m:airtemp_45min=46.58 m:airtemp_15min=46.54 m:airtemp_30min=46.55 m:rstemp_15min=46.17 m:rstemp_current=46.12 m:airtemp_75min=46.66 m:airtemp_current=46.51 m:rstemp_90min=46.7 m:rstemp_45min=46.32 m:rstemp_60min=46.42 m:airtemp_90min=46.7

series e:wd5q-q35v d:1970-01-01T00:00:00.000Z t:rwis_datetime="2017-03-12 04:30:00" t:objectid=3 t:rwis_station_name=AlbroPlaceAirportWay t:rwis_display_name="Albro Place at Airport Way" m:airtemp_60min=46.93 m:rstemp_30min=45.66 m:rstemp_75min=45.93 m:airtemp_45min=46.93 m:airtemp_15min=47.04 m:airtemp_30min=46.96 m:rstemp_15min=45.54 m:rstemp_current=45.45 m:airtemp_75min=46.79 m:airtemp_current=47.09 m:rstemp_90min=46.04 m:rstemp_45min=45.74 m:rstemp_60min=45.82 m:airtemp_90min=46.95
```

## Meta Commands

```ls
metric m:rstemp_current l:RSTEMP_CURRENT d:RSTEMP_CURRENT t:dataTypeName=number

metric m:airtemp_current l:AIRTEMP_CURRENT d:AIRTEMP_CURRENT t:dataTypeName=number

metric m:rstemp_15min l:RSTEMP_15MIN d:RSTEMP_15MIN t:dataTypeName=number

metric m:airtemp_15min l:AIRTEMP_15MIN d:AIRTEMP_15MIN t:dataTypeName=number

metric m:rstemp_30min l:RSTEMP_30MIN d:RSTEMP_30MIN t:dataTypeName=number

metric m:airtemp_30min l:AIRTEMP_30MIN d:AIRTEMP_30MIN t:dataTypeName=number

metric m:rstemp_45min l:RSTEMP_45MIN d:RSTEMP_45MIN t:dataTypeName=number

metric m:airtemp_45min l:AIRTEMP_45MIN d:AIRTEMP_45MIN t:dataTypeName=number

metric m:rstemp_60min l:RSTEMP_60MIN d:RSTEMP_60MIN t:dataTypeName=number

metric m:airtemp_60min l:AIRTEMP_60MIN d:AIRTEMP_60MIN t:dataTypeName=number

metric m:rstemp_75min l:RSTEMP_75MIN d:RSTEMP_75MIN t:dataTypeName=number

metric m:airtemp_75min l:AIRTEMP_75MIN d:AIRTEMP_75MIN t:dataTypeName=number

metric m:rstemp_90min l:RSTEMP_90MIN d:RSTEMP_90MIN t:dataTypeName=number

metric m:airtemp_90min l:AIRTEMP_90MIN d:AIRTEMP_90MIN t:dataTypeName=number

metric m:rstemp_105min l:RSTEMP_105MIN d:RSTEMP_105MIN t:dataTypeName=number

metric m:airtemp_105min l:AIRTEMP_105MIN d:AIRTEMP_105MIN t:dataTypeName=number

metric m:rstemp_120min l:RSTEMP_120MIN d:RSTEMP_120MIN t:dataTypeName=number

metric m:airtemp_120min l:AIRTEMP_120MIN d:AIRTEMP_120MIN t:dataTypeName=number

entity e:wd5q-q35v l:"SDOT Road Temperature Stations" t:url=https://data.seattle.gov/api/views/wd5q-q35v

property e:wd5q-q35v t:meta.view v:id=wd5q-q35v v:averageRating=0 v:name="SDOT Road Temperature Stations"

property e:wd5q-q35v t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"

property e:wd5q-q35v t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```