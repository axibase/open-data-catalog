# License Applications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/license-applications) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ptev-4hud) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ptev-4hud/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ptev-4hud/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ptev-4hud |
| Name | License Applications |
| Attribution | Department of Consumer Affairs (DCA) |
| Category | Business |
| Tags | city government, business, dca, department of consumer affairs, license, application |
| Created | 2016-01-26T14:50:15Z |
| Publication Date | 2016-02-08T16:50:47Z |

## Description

This data set features license applications received during the last and current calendar years, including applications where a license was issued, denied, withdrawn, or remains pending. For a list of legally operating businesses, please refer to the DCA – Legally Operating Businesses data set. This data set is updated on a weekly basis.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | =========== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag  | application_id            | Application ID            | text          | text          |
| Yes      | series tag  | license_number            | License Number            | text          | text          |
| Yes      | series tag  | license_type              | License Type              | text          | text          |
| Yes      | series tag  | application_or_renewal    | Application or Renewal    | text          | text          |
| Yes      | series tag  | business_name             | Business Name             | text          | text          |
| Yes      | series tag  | status                    | Status                    | text          | text          |
| Yes      | time        | start_date                | Start Date                | calendar_date | calendar_date |
| No       |             | end_date                  | End Date                  | calendar_date | calendar_date |
| Yes      | series tag  | temp_op_letter_issued     | Temp Op Letter Issued     | text          | text          |
| Yes      | series tag  | temp_op_letter_expiration | Temp Op Letter Expiration | text          | text          |
| Yes      | series tag  | license_category          | License Category          | text          | text          |
| Yes      | series tag  | application_category      | Application Category      | text          | text          |
| Yes      | series tag  | building_number           | Building Number           | text          | text          |
| Yes      | series tag  | street                    | Street                    | text          | text          |
| Yes      | series tag  | street_2                  | Street 2                  | text          | text          |
| Yes      | series tag  | unit_type                 | Unit Type                 | text          | text          |
| Yes      | series tag  | unit                      | Unit                      | text          | text          |
| Yes      | series tag  | description               | Description               | text          | text          |
| Yes      | series tag  | city                      | City                      | text          | text          |
| Yes      | series tag  | state                     | State                     | text          | text          |
| Yes      | series tag  | zip                       | Zip                       | text          | text          |
| Yes      | series tag  | contact_phone             | Contact Phone             | text          | text          |
| No       |             | longitude                 | Longitude                 | number        | number        |
| No       |             | latitude                  | Latitude                  | number        | number        |
| Yes      | series tag  | active_vehicles           | Active Vehicles           | text          | text          |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_date,longitude,latitude
```

## Data Commands

```ls
series e:ptev-4hud d:2017-01-09T00:00:00.000Z t:zip=10467 t:business_name="PEYKO TZENOV" t:application_category=Special t:contact_phone=9178047161 t:city=BRONX t:license_type=Business t:license_category="Home Improvement Contractor" t:application_id=1066-2017-RHIC t:license_number=1294131-DCA t:street="RESERVOIR OVAL E" t:state=NY t:application_or_renewal=Renewal t:building_number=3280 t:status=Issued m:row_number.ptev-4hud=1

series e:ptev-4hud d:2016-12-28T00:00:00.000Z t:zip=11201 t:business_name="T-MOBILE NORTHEAST LLC" t:application_category=Basic t:contact_phone=8009279801 t:city=BROOKLYN t:license_type=Business t:license_category="Electronics Store" t:application_id=33312-2016-RELE t:license_number=2010590-DCA t:street="FULTON ST" t:state=NY t:application_or_renewal=Renewal t:building_number=435 t:status=Issued m:row_number.ptev-4hud=2

series e:ptev-4hud d:2017-09-05T00:00:00.000Z t:zip=10027 t:business_name="L.L.I. LAUNDROMAT LTD." t:application_category=Basic t:contact_phone=347-302-4561 t:city="NEW YORK" t:license_type=Business t:license_category=Laundries t:application_id=12516-2017-ALAU t:street="LENOX AVE" t:state=NY t:application_or_renewal=Application t:building_number=361 t:status=Pending m:row_number.ptev-4hud=3
```

## Meta Commands

```ls
metric m:row_number.ptev-4hud p:long l:"Row Number"

entity e:ptev-4hud l:"License Applications" t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/ptev-4hud

property e:ptev-4hud t:meta.view d:2017-09-25T07:31:00.547Z v:averageRating=0 v:name="License Applications" v:attribution="Department of Consumer Affairs (DCA)" v:id=ptev-4hud v:category=Business

property e:ptev-4hud t:meta.view.owner d:2017-09-25T07:31:00.547Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:id=5fuc-pqz2 v:screenName="NYC OpenData"

property e:ptev-4hud t:meta.view.tableauthor d:2017-09-25T07:31:00.547Z v:displayName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:roleName=administrator v:id=5fuc-pqz2 v:screenName="NYC OpenData"
```

## Top Records

```ls
| application_id  | license_number | license_type | application_or_renewal | business_name              | status  | start_date          | end_date            | temp_op_letter_issued | temp_op_letter_expiration | license_category             | application_category | building_number | street           | street_2 | unit_type | unit | description | city      | state | zip   | contact_phone | longitude  | latitude   | active_vehicles | 
| =============== | ============== | ============ | ====================== | ========================== | ======= | =================== | =================== | ===================== | ========================= | ============================ | ==================== | =============== | ================ | ======== | ========= | ==== | =========== | ========= | ===== | ===== | ============= | ========== | ========== | =============== | 
| 1066-2017-RHIC  | 1294131-DCA    | Business     | Renewal                | PEYKO TZENOV               | Issued  | 2017-01-09T00:00:00 | 2017-01-10T00:00:00 |                       |                           | Home Improvement Contractor  | Special              | 3280            | RESERVOIR OVAL E |          |           |      |             | BRONX     | NY    | 10467 | 9178047161    | -73.877091 | 40.876214  |                 | 
| 33312-2016-RELE | 2010590-DCA    | Business     | Renewal                | T-MOBILE NORTHEAST LLC     | Issued  | 2016-12-28T00:00:00 | 2017-01-07T00:00:00 |                       |                           | Electronics Store            | Basic                | 435             | FULTON ST        |          |           |      |             | BROOKLYN  | NY    | 11201 | 8009279801    | -73.987746 | 40.6916296 |                 | 
| 12516-2017-ALAU |                | Business     | Application            | L.L.I. LAUNDROMAT LTD.     | Pending | 2017-09-05T00:00:00 |                     |                       |                           | Laundries                    | Basic                | 361             | LENOX AVE        |          |           |      |             | NEW YORK  | NY    | 10027 | 347-302-4561  | -73.944025 | 40.8097918 |                 | 
| 33701-2016-RELE | 2025971-DCA    | Business     | Renewal                | LUCAS ELECTRONICS INC      | Issued  | 2016-12-31T00:00:00 | 2017-01-10T00:00:00 |                       |                           | Electronics Store            | Basic                | 886             | MANHATTAN AVE    |          |           |      |             | BROOKLYN  | NY    | 11222 | 347-987-3235  | -73.954098 | 40.7298694 |                 | 
| 1223-2017-RHIS  | 1217547-DCA    | Individual   | Renewal                | JUSTINIANO SALDIVAR        | Issued  | 2017-01-09T00:00:00 | 2017-01-10T00:00:00 |                       |                           | Home Improvement Salesperson | Special              | 25419           | 82ND RD          |          |           |      |             | GLEN OAKS | NY    | 11004 | 7189748124    |            |            |                 | 
| 387-2017-RELE   | 1421338-DCA    | Business     | Renewal                | WILLY'S SOUND DESIGN CORP. | Issued  | 2017-01-04T00:00:00 | 2017-01-11T00:00:00 |                       |                           | Electronics Store            | Basic                | 1301            | WESTCHESTER AVE  |          |           |      | FL 1        | BRONX     | NY    | 10459 | 9177924799    | -73.886359 | 40.8275324 |                 | 
| 1217-2017-RHIS  | 1342032-DCA    | Individual   | Renewal                | MELBIN GUARDADO            | Issued  | 2017-01-09T00:00:00 | 2017-01-10T00:00:00 |                       |                           | Home Improvement Salesperson | Special              | 72              | WELLINGTON ST    |          |           |      |             | HEMPSTEAD | NY    | 11550 | 347-512-6439  |            |            |                 | 
| 12418-2017-AELE | 2057790-DCA    | Business     | Application            | RIDGE WIRELESS CORP        | Issued  | 2017-08-31T00:00:00 | 2017-09-02T00:00:00 |                       |                           | Electronics Store            | Basic                | 9514            | 4TH AVE          |          |           |      |             | BROOKLYN  | NY    | 11209 |               | -74.031289 | 40.6156532 |                 | 
| 949-2017-RHIC   | 1338463-DCA    | Business     | Renewal                | TAORMINA, MICHAEL          | Issued  | 2017-01-06T00:00:00 | 2017-01-07T00:00:00 |                       |                           | Home Improvement Contractor  | Special              | 17              | CENTERPORT RD    |          |           |      |             | GREENLAWN | NY    | 11740 | 6312362914    |            |            |                 | 
| 348-2017-RDEB   | 1325842-DCA    | Business     | Renewal                | CREDIGY RECEIVABLES INC.   | Issued  | 2017-01-09T00:00:00 | 2017-01-11T00:00:00 |                       |                           | Debt Collection Agency       | Basic                | 2877            | PARADISE RD      |          | UNIT      | 303  |             | LAS VEGAS | NV    | 89109 | 702-543-3036  |            |            |                 | 
```