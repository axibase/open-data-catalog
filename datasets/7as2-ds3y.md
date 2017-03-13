# 311 Service Requests - Pot Holes Reported

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/311-service-requests-pot-holes-reported-c4116) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/7as2-ds3y) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/7as2-ds3y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/7as2-ds3y/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 7as2-ds3y |
| Name | 311 Service Requests - Pot Holes Reported |
| Attribution | City of Chicago |
| Category | Service Requests |
| Tags | streets, pot holes |
| Created | 2011-09-30T09:11:02Z |
| Publication Date | 2017-03-11T11:40:26Z |
| Rows Updated | 2017-03-11T11:39:08Z |

## Description

The Chicago Department of Transportation (CDOT) oversees the patching of potholes on over 4,000 miles of arterial and residential streets in Chicago. CDOT receives reports of potholes through the 311 call center and uses a computerized mapping and tracking system to identify pothole locations and efficiently schedule crews.  One call to 311 can generate multiple pothole repairs. When a crew arrives to repair a 311 pothole, it fills all the other potholes within the block.  Pothole repairs are generally completed within 7 days from the first report of a pothole to 311. Weather conditions, particularly frigid temps and precipitation, influence how long a repair takes.  On days when weather is cooperative and there is no precipitation, crews can fill several thousand potholes.  

If a previous request is already open for a buffer of 4 addresses the request is given the status of "Duplicate (Open)".  For example, if there is an existing CSR for 6535 N Western and a new request is received for 6531 N Western (which is within four addresses of the original CSR) then the new request is given a status of "Duplicate (Open)".

Once the street is repaired, the status in CSR will read ?Completed? for the original request and "Duplicate (Closed)" for any duplicate requests.  A service request also receives the status of ?Completed? when the reported address is inspected but no potholes are found or have already been filled.  If another issue is found with the street, such as a ?cave-in? or ?failed utility cut?, then it is directed to the appropriate department or contractor. 

Data Owner: Transportation. Time Period: All open requests and all completed requests since January 1, 2011. Frequency: Data is updated daily.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type     | Render Type   |
| ======== | ============== | ================================== | ================================== | ============= | ============= |
| Yes      | time           | creation_date                      | CREATION DATE                      | calendar_date | calendar_date |
| Yes      | series tag     | status                             | STATUS                             | text          | text          |
| No       |                | completion_date                    | COMPLETION DATE                    | calendar_date | calendar_date |
| Yes      | series tag     | service_request_number             | SERVICE REQUEST NUMBER             | text          | text          |
| Yes      | series tag     | type_of_service_request            | TYPE OF SERVICE REQUEST            | text          | text          |
| Yes      | series tag     | current_activity                   | CURRENT ACTIVITY                   | text          | text          |
| Yes      | series tag     | most_recent_action                 | MOST RECENT ACTION                 | text          | text          |
| Yes      | numeric metric | number_of_potholes_filled_on_block | NUMBER OF POTHOLES FILLED ON BLOCK | number        | number        |
| No       |                | street_address                     | STREET ADDRESS                     | text          | text          |
| Yes      | series tag     | zip                                | ZIP                                | text          | number        |
| No       |                | x_coordinate                       | X COORDINATE                       | number        | number        |
| No       |                | y_coordinate                       | Y COORDINATE                       | number        | number        |
| Yes      | series tag     | ward                               | Ward                               | text          | number        |
| Yes      | series tag     | police_district                    | Police District                    | text          | number        |
| Yes      | numeric metric | community_area                     | Community Area                     | number        | number        |
| Yes      | numeric metric | ssa                                | SSA                                | number        | text          |
| No       |                | latitude                           | LATITUDE                           | number        | number        |
| No       |                | longitude                          | LONGITUDE                          | number        | number        |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = y_coordinate,x_coordinate,longitude,latitude,completion_date,street_address
```

## Data Commands

```ls
series e:7as2-ds3y d:2011-01-01T00:00:00.000Z t:zip=60620 t:ward=17 t:police_district=6 t:status="Completed - Dup" t:service_request_number=11-00002110 t:type_of_service_request="Pot Hole in Street" m:community_area=69

series e:7as2-ds3y d:2011-01-01T00:00:00.000Z t:zip=60629 t:ward=13 t:police_district=8 t:status="Completed - Dup" t:service_request_number=11-00002209 t:type_of_service_request="Pot Hole in Street" m:ssa=3 m:community_area=65

series e:7as2-ds3y d:2011-01-01T00:00:00.000Z t:zip=60647 t:ward=1 t:police_district=14 t:status="Completed - Dup" t:service_request_number=11-00002224 t:type_of_service_request="Pot Hole in Street" m:community_area=22
```

## Meta Commands

```ls
metric m:number_of_potholes_filled_on_block p:integer l:"NUMBER OF POTHOLES FILLED ON BLOCK" t:dataTypeName=number

metric m:community_area l:"Community Area" t:dataTypeName=number

metric m:ssa p:integer l:SSA d:"Special Service Areas are local tax districts that fund expanded services and programs, to foster commercial and economic development, through a localized property tax. In other cities these areas are sometimes called Business Improvement Districts (BIDs). This portal contains a map of all Chicago SSAs" t:dataTypeName=number

entity e:7as2-ds3y l:"311 Service Requests - Pot Holes Reported" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/7as2-ds3y

property e:7as2-ds3y t:meta.view v:id=7as2-ds3y v:category="Service Requests" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="311 Service Requests - Pot Holes Reported" v:attribution="City of Chicago"

property e:7as2-ds3y t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false

property e:7as2-ds3y t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```