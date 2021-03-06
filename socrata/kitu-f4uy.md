# Stop and Search (Field Interviews)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stop-and-search-field-interviews) |
| Metadata | [Link](https://data.nola.gov/api/views/kitu-f4uy) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/kitu-f4uy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/kitu-f4uy/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | kitu-f4uy |
| Name | Stop and Search (Field Interviews) |
| Category | Public Safety and Preparedness |
| Tags | police, stop, search, field interview |
| Created | 2015-07-10T16:01:09Z |
| Publication Date | 2016-04-17T06:24:07Z |

## Description

A subset of data collected when individuals are interviewed by NOPD Officers (including individuals stopped for questioning and complainants).Disclaimer: The New Orleans Police Department does not guarantee (either expressed or implied) the accuracy, completeness, timeliness, or correct sequencing of the information. The New Orleans Police Department will not be responsible for any error or omission, or for the use of, or the results obtained from the use of this information. All data visualizations on maps should be considered approximate and attempts to derive specific addresses are strictly prohibited. The New Orleans Police Department is not responsible for the content of any off-site pages that are referenced by or that reference this web page other than an official City of New Orleans or New Orleans Police Department web page. The user specifically acknowledges that the New Orleans Police Department is not responsible for any defamatory, offensive, misleading, or illegal conduct of other users, links, or third parties and that the risk of injury from the foregoing rests entirely with the user. Any use of the information for commercial purposes is strictly prohibited. The unauthorized use of the words "New Orleans Police Department," "NOPD," or any colorable imitation of these words or the unauthorized use of the New Orleans Police Department logo is unlawful. This web page does not, in any way, authorize such use.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | fieldinterviewid      | FieldInterviewID      | text          | number        |
| Yes      | series tag     | nopd_item             | NOPD_Item             | text          | text          |
| Yes      | time           | eventdate             | EventDate             | calendar_date | calendar_date |
| Yes      | series tag     | district              | District              | text          | number        |
| Yes      | series tag     | zone                  | Zone                  | text          | text          |
| Yes      | series tag     | officerassignment     | OfficerAssignment     | text          | text          |
| Yes      | series tag     | stopdescription       | StopDescription       | text          | text          |
| Yes      | series tag     | actionstaken          | ActionsTaken          | text          | text          |
| Yes      | series tag     | vehicleyear           | VehicleYear           | text          | number        |
| Yes      | series tag     | vehiclemake           | VehicleMake           | text          | text          |
| Yes      | series tag     | vehiclemodel          | VehicleModel          | text          | text          |
| Yes      | series tag     | vehiclestyle          | VehicleStyle          | text          | text          |
| Yes      | series tag     | vehiclecolor          | VehicleColor          | text          | text          |
| Yes      | series tag     | subjectid             | SubjectID             | text          | number        |
| Yes      | series tag     | subjectrace           | SubjectRace           | text          | text          |
| Yes      | series tag     | subjectgender         | SubjectGender         | text          | text          |
| Yes      | numeric metric | subjectage            | SubjectAge            | number        | number        |
| Yes      | series tag     | subjecthasphotoid     | SubjectHasPhotoID     | text          | text          |
| Yes      | numeric metric | subjectheight         | SubjectHeight         | number        | number        |
| Yes      | numeric metric | subjectweight         | SubjectWeight         | number        | number        |
| Yes      | series tag     | subjecteyecolor       | SubjectEyeColor       | text          | text          |
| Yes      | series tag     | subjecthaircolor      | SubjectHairColor      | text          | text          |
| Yes      | series tag     | subjectdriverlicstate | SubjectDriverLicState | text          | text          |
| No       |                | createddatetime       | CreatedDateTime       | calendar_date | calendar_date |
| No       |                | lastmodifieddatetime  | LastModifiedDateTime  | calendar_date | calendar_date |
| No       |                | longitude             | Longitude             | number        | number        |
| No       |                | latitude              | Latitude              | number        | number        |
| Yes      | series tag     | zip                   | Zip                   | text          | number        |
| No       |                | blockaddress          | BlockAddress          | text          | text          |
```

## Time Field

```ls
Value = eventdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = createddatetime,lastmodifieddatetime,longitude,latitude,blockaddress
```

## Data Commands

```ls
series e:kitu-f4uy d:2010-01-01T01:11:00.000Z t:vehicleyear=2005 t:subjectgender=FEMALE t:subjectrace=BLACK t:vehiclecolor=BLACK t:officerassignment="6th  District" t:subjectid=20465 t:subjecteyecolor=Brown t:subjecthaircolor=Black t:zone=E t:fieldinterviewid=17415 t:district=6 t:stopdescription="TRAFFIC VIOLATION" t:vehiclemake=DODGE t:subjectdriverlicstate=LA t:vehiclemodel=CARAVAN t:vehiclestyle=MINIVAN t:subjecthasphotoid=Yes m:subjectheight=69 m:subjectage=26 m:subjectweight=160

series e:kitu-f4uy d:2010-01-01T02:06:00.000Z t:subjectgender=MALE t:subjecthaircolor=Black t:subjectrace=BLACK t:zone=D t:fieldinterviewid=17416 t:district=5 t:stopdescription="CALL FOR SERVICE" t:subjecthasphotoid=No t:officerassignment="5th  District" t:subjectid=20466 t:subjecteyecolor=Brown m:subjectheight=65 m:subjectage=17 m:subjectweight=140

series e:kitu-f4uy d:2010-01-01T02:06:00.000Z t:subjectgender=MALE t:subjecthaircolor=Black t:subjectrace=BLACK t:zone=D t:fieldinterviewid=17416 t:district=5 t:stopdescription="CALL FOR SERVICE" t:subjecthasphotoid=No t:officerassignment="5th  District" t:subjectid=20468 t:subjecteyecolor=Brown m:subjectheight=66 m:subjectage=18 m:subjectweight=140
```

## Meta Commands

```ls
metric m:subjectage p:integer l:SubjectAge t:dataTypeName=number

metric m:subjectheight p:integer l:SubjectHeight t:dataTypeName=number

metric m:subjectweight p:integer l:SubjectWeight t:dataTypeName=number

entity e:kitu-f4uy l:"Stop and Search (Field Interviews)" t:url=https://data.nola.gov/api/views/kitu-f4uy

property e:kitu-f4uy t:meta.view d:2017-09-25T07:29:47.503Z v:averageRating=0 v:name="Stop and Search (Field Interviews)" v:id=kitu-f4uy v:category="Public Safety and Preparedness"

property e:kitu-f4uy t:meta.view.license d:2017-09-25T07:29:47.503Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:kitu-f4uy t:meta.view.owner d:2017-09-25T07:29:47.503Z v:displayName="Enterprise Information Data Team" v:id=uqfu-rapx v:screenName="Enterprise Information Data Team"

property e:kitu-f4uy t:meta.view.tableauthor d:2017-09-25T07:29:47.503Z v:displayName="Enterprise Information Data Team" v:roleName=publisher v:id=uqfu-rapx v:screenName="Enterprise Information Data Team"

property e:kitu-f4uy t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:29:47.503Z v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| fieldinterviewid | nopd_item | eventdate           | district | zone | officerassignment | stopdescription    | actionstaken | vehicleyear | vehiclemake | vehiclemodel | vehiclestyle | vehiclecolor | subjectid | subjectrace | subjectgender | subjectage | subjecthasphotoid | subjectheight | subjectweight | subjecteyecolor | subjecthaircolor | subjectdriverlicstate | createddatetime     | lastmodifieddatetime | longitude | latitude | zip | blockaddress | 
| ================ | ========= | =================== | ======== | ==== | ================= | ================== | ============ | =========== | =========== | ============ | ============ | ============ | ========= | =========== | ============= | ========== | ================= | ============= | ============= | =============== | ================ | ===================== | =================== | ==================== | ========= | ======== | === | ============ | 
| 17415            |           | 2010-01-01T01:11:00 | 6        | E    | 6th District      | TRAFFIC VIOLATION  |              | 2005        | DODGE       | CARAVAN      | MINIVAN      | BLACK        | 20465     | BLACK       | FEMALE        | 26         | Yes               | 69            | 160           | Brown           | Black            | LA                    | 2010-01-01T01:26:26 |                      | 0.0       | 0.0      |     |              | 
| 17416            |           | 2010-01-01T02:06:00 | 5        | D    | 5th District      | CALL FOR SERVICE   |              |             |             |              |              |              | 20466     | BLACK       | MALE          | 17         | No                | 65            | 140           | Brown           | Black            |                       | 2010-01-01T02:27:38 |                      | 0.0       | 0.0      |     |              | 
| 17416            |           | 2010-01-01T02:06:00 | 5        | D    | 5th District      | CALL FOR SERVICE   |              |             |             |              |              |              | 20468     | BLACK       | MALE          | 18         | No                | 66            | 140           | Brown           | Black            |                       | 2010-01-01T02:27:38 |                      | 0.0       | 0.0      |     |              | 
| 17416            |           | 2010-01-01T02:06:00 | 5        | D    | 5th District      | CALL FOR SERVICE   |              |             |             |              |              |              | 20469     | BLACK       | MALE          | 30         | No                | 65            | 140           | Brown           | Black            |                       | 2010-01-01T02:27:38 |                      | 0.0       | 0.0      |     |              | 
| 17416            |           | 2010-01-01T02:06:00 | 5        | D    | 5th District      | CALL FOR SERVICE   |              |             |             |              |              |              | 20470     | BLACK       | MALE          | 21         | No                | 68            | 155           | Brown           | Black            |                       | 2010-01-01T02:27:38 |                      | 0.0       | 0.0      |     |              | 
| 17416            |           | 2010-01-01T02:06:00 | 5        | D    | 5th District      | CALL FOR SERVICE   |              |             |             |              |              |              | 20472     | BLACK       | MALE          | 20         | No                | 67            | 150           | Brown           | Black            |                       | 2010-01-01T02:27:38 |                      | 0.0       | 0.0      |     |              | 
| 17416            |           | 2010-01-01T02:06:00 | 5        | D    | 5th District      | CALL FOR SERVICE   |              |             |             |              |              |              | 20467     | BLACK       | MALE          | 18         | No                | 67            | 145           | Brown           | Black            |                       | 2010-01-01T02:27:38 |                      | 0.0       | 0.0      |     |              | 
| 17416            |           | 2010-01-01T02:06:00 | 5        | D    | 5th District      | CALL FOR SERVICE   |              |             |             |              |              |              | 20471     | BLACK       | MALE          | 23         | No                | 68            | 160           | Brown           | Black            |                       | 2010-01-01T02:27:38 |                      | 0.0       | 0.0      |     |              | 
| 17417            |           | 2009-12-31T22:23:00 | 5        | L    | 5th District      | CRIMINAL VIOLATION |              |             |             |              |              |              | 20473     | BLACK       | FEMALE        | 17         | No                | 63            | 120           | Brown           | Black            |                       | 2010-01-01T05:39:26 |                      | 0.0       | 0.0      |     |              | 
| 17418            |           | 2010-01-01T07:54:00 | 6        | I    | 6th District      | TRAFFIC VIOLATION  |              | 1995        | TOYOTA      |              | FOUR DOOR    | GREEN        | 20474     | BLACK       | MALE          | 54         | Yes               | 76            | 270           | Brown           | Black            | LA                    | 2010-01-01T07:58:00 |                      | 0.0       | 0.0      |     |              | 
```