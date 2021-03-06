# Maryland Ozone Exceedance Days in 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-ozone-exceedance-days-in-2011-b0844) |
| Metadata | [Link](https://data.maryland.gov/api/views/iusd-kqc6) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/iusd-kqc6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/iusd-kqc6/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | iusd-kqc6 |
| Name | Maryland Ozone Exceedance Days in 2011 |
| Category | Energy and Environment |
| Tags | air quality, ozone, mde |
| Created | 2012-11-27T21:45:55Z |
| Publication Date | 2014-09-30T18:15:39Z |

## Description

Maryland 8-Hour Ozone Concentrations Exceeding 2008 Health-Based Standard in ppb, Finalized Data. In 2008 EPA set the ozone standard to 75 ppb. High levels of ozone can cause health effects including increased asthma attacks and other respiratory effects. You can get more information about the health effects at http://www.epa.gov/air/ozonepollution/. This data set details which monitoring locations in Maryland exceeded the standard during the year and the maximum concentrations on the dates the standard was exceeded. More information on Maryland's air quality monitoring is available at http://www.mde.state.md.us/programs/Air/AirQualityMonitoring/Pages/index.aspx.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                          | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================= | ============= | ============= |
| Yes      | time           | date                         | Date                          | calendar_date | calendar_date |
| Yes      | numeric metric | aldino                       | Aldino                        | number        | number        |
| Yes      | numeric metric | essex                        | Essex                         | number        | number        |
| Yes      | numeric metric | calvert_co_barstow           | Calvert Co / Barstow          | number        | number        |
| Yes      | numeric metric | davidsonville                | Davidsonville                 | number        | number        |
| Yes      | numeric metric | edgewood                     | Edgewood                      | number        | number        |
| Yes      | numeric metric | fairhill                     | Fairhill                      | number        | number        |
| Yes      | numeric metric | frederick_airport            | Frederick Airport             | number        | number        |
| Yes      | numeric metric | furley_e_s_recreation_center | Furley E.S. Recreation Center | number        | number        |
| Yes      | numeric metric | hagerstown                   | Hagerstown                    | number        | text          |
| Yes      | numeric metric | hu_beltsville                | HU-Beltsville                 | number        | number        |
| Yes      | numeric metric | millington                   | Millington                    | number        | number        |
| Yes      | numeric metric | padonia                      | Padonia                       | number        | number        |
| Yes      | numeric metric | pg_equestrian_center         | PG Equestrian Center          | number        | number        |
| Yes      | numeric metric | piney_run                    | Piney Run                     | number        | text          |
| Yes      | numeric metric | rockville                    | Rockville                     | number        | number        |
| Yes      | numeric metric | south_carroll                | South Carroll                 | number        | number        |
| Yes      | numeric metric | southern_maryland            | Southern Maryland             | number        | number        |
| Yes      | numeric metric | state_wide_max               | State-wide Max                | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:iusd-kqc6 d:2011-05-26T00:00:00.000Z m:padonia=76 m:state_wide_max=76

series e:iusd-kqc6 d:2011-05-30T00:00:00.000Z m:calvert_co_barstow=76 m:state_wide_max=76

series e:iusd-kqc6 d:2011-05-31T00:00:00.000Z m:edgewood=80 m:frederick_airport=77 m:furley_e_s_recreation_center=77 m:hagerstown=76 m:essex=79 m:millington=76 m:state_wide_max=83 m:hu_beltsville=83
```

## Meta Commands

```ls
metric m:aldino p:integer l:Aldino t:dataTypeName=number

metric m:essex p:integer l:Essex t:dataTypeName=number

metric m:calvert_co_barstow p:integer l:"Calvert Co / Barstow" t:dataTypeName=number

metric m:davidsonville p:integer l:Davidsonville t:dataTypeName=number

metric m:edgewood p:integer l:Edgewood t:dataTypeName=number

metric m:fairhill p:integer l:Fairhill t:dataTypeName=number

metric m:frederick_airport p:integer l:"Frederick Airport" t:dataTypeName=number

metric m:furley_e_s_recreation_center p:integer l:"Furley E.S. Recreation Center" t:dataTypeName=number

metric m:hagerstown p:integer l:Hagerstown t:dataTypeName=number

metric m:hu_beltsville p:integer l:HU-Beltsville t:dataTypeName=number

metric m:millington p:integer l:Millington t:dataTypeName=number

metric m:padonia p:integer l:Padonia t:dataTypeName=number

metric m:pg_equestrian_center p:integer l:"PG Equestrian Center" t:dataTypeName=number

metric m:piney_run p:integer l:"Piney Run" t:dataTypeName=number

metric m:rockville p:integer l:Rockville t:dataTypeName=number

metric m:south_carroll p:integer l:"South Carroll" t:dataTypeName=number

metric m:southern_maryland p:integer l:"Southern Maryland" t:dataTypeName=number

metric m:state_wide_max p:integer l:"State-wide Max" t:dataTypeName=number

entity e:iusd-kqc6 l:"Maryland Ozone Exceedance Days in 2011" t:url=https://data.maryland.gov/api/views/iusd-kqc6

property e:iusd-kqc6 t:meta.view v:id=iusd-kqc6 v:category="Energy and Environment" v:averageRating=0 v:name="Maryland Ozone Exceedance Days in 2011"

property e:iusd-kqc6 t:meta.view.license v:name="Public Domain"

property e:iusd-kqc6 t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:iusd-kqc6 t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| date                | aldino | essex | calvert_co_barstow | davidsonville | edgewood | fairhill | frederick_airport | furley_e_s_recreation_center | hagerstown | hu_beltsville | millington | padonia | pg_equestrian_center | piney_run | rockville | south_carroll | southern_maryland | state_wide_max | 
| =================== | ====== | ===== | ================== | ============= | ======== | ======== | ================= | ============================ | ========== | ============= | ========== | ======= | ==================== | ========= | ========= | ============= | ================= | ============== | 
| 2011-05-26T00:00:00 |        |       |                    |               |          |          |                   |                              |            |               |            | 76      |                      |           |           |               |                   | 76             | 
| 2011-05-30T00:00:00 |        |       | 76                 |               |          |          |                   |                              |            |               |            |         |                      |           |           |               |                   | 76             | 
| 2011-05-31T00:00:00 |        | 79    |                    |               | 80       |          | 77                | 77                           | 76         | 83            | 76         |         |                      |           |           |               |                   | 83             | 
| 2011-06-01T00:00:00 |        |       |                    |               | 79       | 92       |                   |                              |            |               | 81         |         |                      |           |           |               |                   | 92             | 
| 2011-06-07T00:00:00 |        | 83    |                    |               | 89       | 89       |                   |                              |            | 76            | 77         | 76      |                      |           |           |               |                   | 89             | 
| 2011-06-08T00:00:00 |        | 101   | 87                 | 88            | 114      | 94       | 82                | 87                           | 76         | 82            | 91         | 83      | 95                   |           | 81        | 79            | 77                | 114            | 
| 2011-06-09T00:00:00 |        | 83    | 93                 | 87            | 106      | 96       | 76                | 76                           |            | 80            | 100        | 82      | 86                   |           |           | 77            | 86                | 106            | 
| 2011-06-10T00:00:00 |        | 81    | 92                 | 94            | 87       | 76       |                   | 77                           |            | 91            | 78         | 86      | 92                   |           |           |               | 98                | 98             | 
| 2011-06-18T00:00:00 |        |       |                    |               |          |          |                   |                              |            |               | 76         |         | 76                   |           |           |               |                   | 76             | 
| 2010-06-28T00:00:00 |        |       |                    |               |          |          |                   |                              |            |               |            |         | 76                   |           |           |               |                   | 76             | 
```