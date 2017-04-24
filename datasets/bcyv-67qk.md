# FOIA Request Log - Procurement Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-procurement-services-89e7a) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/bcyv-67qk) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/bcyv-67qk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/bcyv-67qk/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | bcyv-67qk |
| Name | FOIA Request Log - Procurement Services |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2011-09-29T19:46:39Z |
| Publication Date | 2017-03-13T19:55:25Z |

## Description

FOIA requests received by Procurement Services as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name         | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization           | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request | DESCRIPTION OF REQUEST | text          | text          |
| Yes      | time        | date_received          | DATE RECEIVED          | calendar_date | calendar_date |
| No       |             | due_date               | DUE DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = due_date
```

## Data Commands

```ls
series e:bcyv-67qk d:2015-05-15T00:00:00.000Z t:description_of_request="I write to request access to and a copy of the following, which I understand to be held by your agency.

Electronic records of all incidents of possible gunshots recorded by ShotSpotter Flex sensors used to generate summary reports for the city from January 1, 2013 to the date this request is processed, including:

- Date and time of the incident (with detail to the minute if available -- for example, 1/1/13 4:32pm)
- Location (latitude and longitude)Pl
- Address
- Incident type (multiple gunshots, single gunshot, or possible gunshot(s))
- Beat (for example, ?25X?) 

Please provide the data in a machine-readable format (for example, Excel [XLS, XLSX], comma-separated value [CSV], or ESRI ArcGIS files). In addition, I?d like copies of the most recent contract between the city and ShotSpotter and any and all supporting materials that document the city?s efforts to verify the accuracy of the data provided by ShotSpotter.

For your reference, I have attached a sample view of ShotSpotter?s incident report, which includes all of the fields above as well as instructions for how to export the data.

I would like these records in electronic form transmitted via email, CD or otherwise. Please refrain from sending paper copies of the records. If your agency does not maintain these public records, please let me know who does and include the proper custodian's name and address." t:organization="The Center for Investigative Reporting" t:requestor_name="Matthew Drange" m:row_number.bcyv-67qk=1

series e:bcyv-67qk d:2015-05-15T00:00:00.000Z t:description_of_request="O'Hare International Airport Terminal 2 & 3 Vestibules, Chicago, IL.  As provided for in the Illinois Freedom of Information Act, please provide us with a certified copy of the General/Prime Contractor's payment bond (or performance & payment bond) and the first five pages and signature page of the general contract between McDonagh Demolition and/or C A R E Plus, LLC and the City of Chicago for the above mentioned construction project(s)." t:organization="Contractors Adjustment Company" t:requestor_name="Linda Cole" m:row_number.bcyv-67qk=2

series e:bcyv-67qk d:2015-05-11T00:00:00.000Z t:description_of_request="I am writing to request the complete and current contract for contract 120173; From the City of Chicago Department of Finance and the Chicago Fire Department." t:requestor_name="Neenah Powell" m:row_number.bcyv-67qk=3
```

## Meta Commands

```ls
metric m:row_number.bcyv-67qk p:long l:"Row Number"

entity e:bcyv-67qk l:"FOIA Request Log - Procurement Services" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/bcyv-67qk

property e:bcyv-67qk t:meta.view v:id=bcyv-67qk v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Procurement Services" v:attribution="City of Chicago"

property e:bcyv-67qk t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:bcyv-67qk t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name    | organization                              | description_of_request                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | date_received       | due_date            | 
| ================= | ========================================= | ===================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =================== | =================== | 
| Matthew Drange    | The Center for Investigative Reporting    | I write to request access to and a copy of the following, which I understand to be held by your agency. Electronic records of all incidents of possible gunshots recorded by ShotSpotter Flex sensors used to generate summary reports for the city from January 1, 2013 to the date this request is processed, including: - Date and time of the incident (with detail to the minute if available -- for example, 1/1/13 4:32pm) - Location (latitude and longitude)Pl - Address - Incident type (multiple gunshots, single gunshot, or possible gunshot(s)) - Beat (for example, ?25X?) Please provide the data in a machine-readable format (for example, Excel [XLS, XLSX], comma-separated value [CSV], or ESRI ArcGIS files). In addition, I?d like copies of the most recent contract between the city and ShotSpotter and any and all supporting materials that document the city?s efforts to verify the accuracy of the data provided by ShotSpotter. For your reference, I have attached a sample view of ShotSpotter?s incident report, which includes all of the fields above as well as instructions for how to export the data. I would like these records in electronic form transmitted via email, CD or otherwise. Please refrain from sending paper copies of the records. If your agency does not maintain these public records, please let me know who does and include the proper custodian's name and address. | 2015-05-15T00:00:00 | 2015-05-22T00:00:00 | 
| Linda Cole        | Contractors Adjustment Company            | O'Hare International Airport Terminal 2 & 3 Vestibules, Chicago, IL. As provided for in the Illinois Freedom of Information Act, please provide us with a certified copy of the General/Prime Contractor's payment bond (or performance & payment bond) and the first five pages and signature page of the general contract between McDonagh Demolition and/or C A R E Plus, LLC and the City of Chicago for the above mentioned construction project(s).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 2015-05-15T00:00:00 | 2015-05-22T00:00:00 | 
| Neenah Powell     |                                           | I am writing to request the complete and current contract for contract 120173; From the City of Chicago Department of Finance and the Chicago Fire Department.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 2015-05-11T00:00:00 | 2015-05-26T00:00:00 | 
| Paul Geske        |                                           | Any public records that relate to the Concession Redevelopment and Management Lease Agreement entered into between the City of Chicago and Westfield Concession Management, LLC during 2011, including but not limited to the executed lease agreement itself                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 2015-05-19T00:00:00 | 2015-05-27T00:00:00 | 
| Millicent Liggins | Veolia                                    | I am submitting a FOIA Request for Hazardous / Non Hazardous Waste Disposal for Police Department Project Ref # ANT:70168406 located in Chicago, IL., and am looking for a copy of previous or current contracts in place for this work. If available please forward copy(s) of contract documents with pricing to my attention.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 2015-05-20T00:00:00 | 2015-05-28T00:00:00 | 
| Ralph Kindred     | StratzGroup                               | I am requesting the RFQ and RFP responses received to the City of Chicago's 2006 Chicago Downtown Public Parking System RFQ and RFP.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 2015-05-27T00:00:00 | 2015-06-03T00:00:00 | 
| Maribel Rivera    | Continental Painting and Decorating, Inc. | Continental Painting and Decorating, Inc. is requesting copies of the bids submitted by Pressure Washing and Oosterbaan & Sons, Co. on 2/19/15 for the Pole Painting Services (Specification No. 123879). Continental Painting participated in the bidding process for the Pole Painting Services, and we believe that the two lowest bidders, Pressure Washing and Oosterbaan & Sons, Co., have not met the MBE Requirements specified in the bid documents.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | 2015-05-27T00:00:00 | 2015-06-03T00:00:00 | 
| Steve Stoynoff    | Laborers District Council-LMCC            | Please supply the following information for the 125th Street Sewer Improvement Project. -Certified Payroll from all Contractors and all Sub Contractors on this Project from June 1, 2014 to May 2015.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 2015-05-08T00:00:00 | 2015-06-04T00:00:00 | 
| Steve Stoynoff    | Laborers District Council-LMCC            | Please supply the following information for the South Water Purification Plant Filter Building Glass Block Wall Replacement Project. -Certified Payroll from all Contractors and all Sub Contractors on this Project from June 1, 2014 to May 2015.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 2015-05-28T00:00:00 | 2015-06-04T00:00:00 | 
| Steve Stoynoff    | Laborers District Council-LMCC            | Please supply the following for the West Ridge Nature Preserve Project. -Certified Payroll for all Contractors and Sub Contractors on this Project from June 1, 2014 thru May 2015.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 2015-05-28T00:00:00 | 2015-06-04T00:00:00 | 
```