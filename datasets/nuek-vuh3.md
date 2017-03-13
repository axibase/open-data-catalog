# Fire Department Calls for Service

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-department-calls-for-service) |
| Metadata | [Link](https://data.sfgov.org/api/views/nuek-vuh3) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/nuek-vuh3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/nuek-vuh3/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | nuek-vuh3 |
| Name | Fire Department Calls for Service |
| Category | Public Safety |
| Tags | calls, fire, 911, medical |
| Created | 2015-12-17T16:07:05Z |
| Publication Date | 2016-05-09T22:15:02Z |
| Rows Updated | 2017-03-12T10:08:01Z |

## Description

Fire Calls-For-Service includes all fire units responses to calls. Each record includes the call number, incident number, address, unit identifier, call type, and disposition. All relevant time intervals are also included. Because this dataset is based on responses, and since most calls involved multiple units, there are multiple records for each call number. Addresses are associated with a block number, intersection or call box, not a specific address.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | numeric metric | call_number                    | Call Number                    | number        | text          |
| Yes      | series tag     | unit_id                        | Unit ID                        | text          | text          |
| Yes      | numeric metric | incident_number                | Incident Number                | number        | text          |
| Yes      | series tag     | call_type                      | Call Type                      | text          | text          |
| Yes      | time           | call_date                      | Call Date                      | calendar_date | calendar_date |
| No       |                | watch_date                     | Watch Date                     | calendar_date | calendar_date |
| No       |                | received_dttm                  | Received DtTm                  | calendar_date | calendar_date |
| No       |                | entry_dttm                     | Entry DtTm                     | calendar_date | calendar_date |
| No       |                | dispatch_dttm                  | Dispatch DtTm                  | calendar_date | calendar_date |
| No       |                | response_dttm                  | Response DtTm                  | calendar_date | calendar_date |
| No       |                | on_scene_dttm                  | On Scene DtTm                  | calendar_date | calendar_date |
| No       |                | transport_dttm                 | Transport DtTm                 | calendar_date | calendar_date |
| No       |                | hospital_dttm                  | Hospital DtTm                  | calendar_date | calendar_date |
| Yes      | series tag     | call_final_disposition         | Call Final Disposition         | text          | text          |
| No       |                | available_dttm                 | Available DtTm                 | calendar_date | calendar_date |
| No       |                | address                        | Address                        | text          | text          |
| Yes      | series tag     | city                           | City                           | text          | text          |
| Yes      | series tag     | zipcode_of_incident            | Zipcode of Incident            | text          | text          |
| Yes      | series tag     | battalion                      | Battalion                      | text          | text          |
| Yes      | series tag     | station_area                   | Station Area                   | text          | text          |
| Yes      | series tag     | box                            | Box                            | text          | text          |
| Yes      | numeric metric | original_priority              | Original Priority              | number        | text          |
| Yes      | numeric metric | priority                       | Priority                       | number        | text          |
| Yes      | numeric metric | final_priority                 | Final Priority                 | number        | text          |
| Yes      | series tag     | als_unit                       | ALS Unit                       | checkbox      | checkbox      |
| Yes      | series tag     | call_type_group                | Call Type Group                | text          | text          |
| Yes      | numeric metric | number_of_alarms               | Number of Alarms               | number        | number        |
| Yes      | series tag     | unit_type                      | Unit Type                      | text          | text          |
| Yes      | numeric metric | unit_sequence_in_call_dispatch | Unit sequence in call dispatch | number        | number        |
| Yes      | series tag     | fire_prevention_district       | Fire Prevention District       | text          | text          |
| Yes      | series tag     | supervisor_district            | Supervisor District            | text          | text          |
| Yes      | series tag     | neighborhood_district          | Neighborhood District          | text          | text          |
| Yes      | series tag     | rowid                          | RowID                          | text          | text          |
```

## Time Field

```ls
Value = call_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = transport_dttm,dispatch_dttm,received_dttm,address,hospital_dttm,response_dttm,on_scene_dttm,available_dttm,watch_date,entry_dttm
```

## Data Commands

```ls
series e:nuek-vuh3 d:2014-09-05T00:00:00.000Z t:call_type_group=Alarm t:station_area=12 t:neighborhood_district="Haight Ashbury" t:unit_id=B02 t:call_final_disposition=Fire t:supervisor_district=5 t:city="San Francisco" t:zipcode_of_incident=94117 t:als_unit=true t:call_type=Alarms t:battalion=B05 t:fire_prevention_district=5 t:unit_type=CHIEF t:box=4525 t:rowid=142480332-B02 m:call_number=142480332 m:final_priority=3 m:priority=3 m:original_priority=3 m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=3 m:incident_number=14086309

series e:nuek-vuh3 d:2015-10-29T00:00:00.000Z t:call_type_group=Alarm t:station_area=13 t:neighborhood_district="Financial District/South Beach" t:unit_id=T02 t:call_final_disposition=Fire t:supervisor_district=3 t:city="San Francisco" t:zipcode_of_incident=94111 t:als_unit=false t:call_type="Structure Fire" t:battalion=B01 t:fire_prevention_district=1 t:unit_type=TRUCK t:box=1155 t:rowid=153022542-T02 m:call_number=153022542 m:final_priority=3 m:priority=3 m:original_priority=3 m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=4 m:incident_number=15115908

series e:nuek-vuh3 d:2014-12-11T00:00:00.000Z t:call_type_group="Potentially Life-Threatening" t:station_area=21 t:neighborhood_district="Castro/Upper Market" t:unit_id=AM04 t:call_final_disposition="Code 2 Transport" t:supervisor_district=8 t:city="San Francisco" t:zipcode_of_incident=94117 t:als_unit=false t:call_type="Medical Incident" t:battalion=B05 t:fire_prevention_district=5 t:unit_type=PRIVATE t:box=5136 t:rowid=143451112-AM04 m:call_number=143451112 m:final_priority=3 m:priority=3 m:original_priority=3 m:number_of_alarms=1 m:unit_sequence_in_call_dispatch=1 m:incident_number=14122741
```

## Meta Commands

```ls
metric m:call_number p:integer l:"Call Number" d:"A unique 9-digit number assigned by the 911 Dispatch Center (DEM) to this call. These number are used for both Police and Fire calls." t:dataTypeName=number

metric m:incident_number p:integer l:"Incident Number" d:"A unique 8-digit number assigned by DEM to this Fire incident." t:dataTypeName=number

metric m:final_priority p:integer l:"Final Priority" d:"Final call priority (Code 2: Non-Emergency or Code 3:Emergency)." t:dataTypeName=number

metric m:number_of_alarms p:integer l:"Number of Alarms" d:"Number of alarms associated with the incident. This is a number between 1 and 5." t:dataTypeName=number

metric m:unit_sequence_in_call_dispatch p:integer l:"Unit sequence in call dispatch" d:"A number that indicates the order this unit was assigned to this call" t:dataTypeName=number

entity e:nuek-vuh3 l:"Fire Department Calls for Service" t:url=https://data.sfgov.org/api/views/nuek-vuh3

property e:nuek-vuh3 t:meta.view v:id=nuek-vuh3 v:category="Public Safety" v:averageRating=0 v:name="Fire Department Calls for Service"

property e:nuek-vuh3 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:nuek-vuh3 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:nuek-vuh3 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```