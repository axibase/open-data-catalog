# DOB Job Application Filings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dob-job-application-filings-05eff) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ic3t-wcy2) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ic3t-wcy2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ic3t-wcy2/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ic3t-wcy2 |
| Name | DOB Job Application Filings |
| Attribution | Department of Buildings (DOB) |
| Category | Housing & Development |
| Tags | job, dob, buildings |
| Created | 2013-04-18T15:18:56Z |
| Publication Date | 2014-01-16T21:15:37Z |

## Description

A list of job applications filed for a particular day and associated data. Prior weekly and monthly reports are archived at DOB and are not available on NYC Open Data.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | job__                        | Job #                        | text          | text          |
| Yes      | series tag     | doc__                        | Doc #                        | text          | text          |
| Yes      | series tag     | borough                      | Borough                      | text          | text          |
| Yes      | series tag     | house__                      | House #                      | text          | text          |
| Yes      | series tag     | street_name                  | Street Name                  | text          | text          |
| Yes      | series tag     | block                        | Block                        | text          | text          |
| Yes      | series tag     | lot                          | Lot                          | text          | text          |
| Yes      | series tag     | bin__                        | Bin #                        | text          | text          |
| Yes      | series tag     | job_type                     | Job Type                     | text          | text          |
| Yes      | series tag     | job_status                   | Job Status                   | text          | text          |
| Yes      | series tag     | job_status_descrp            | Job Status Descrp            | text          | text          |
| No       |                | latest_action_date           | Latest Action Date           | text          | text          |
| Yes      | series tag     | building_type                | Building Type                | text          | text          |
| Yes      | series tag     | community___board            | Community - Board            | text          | text          |
| Yes      | series tag     | cluster                      | Cluster                      | text          | text          |
| Yes      | series tag     | landmarked                   | Landmarked                   | text          | text          |
| Yes      | series tag     | adult_estab                  | Adult Estab                  | text          | text          |
| Yes      | series tag     | loft_board                   | Loft Board                   | text          | text          |
| Yes      | series tag     | city_owned                   | City Owned                   | text          | text          |
| Yes      | series tag     | little_e                     | Little e                     | text          | text          |
| Yes      | series tag     | pc_filed                     | PC Filed                     | text          | text          |
| Yes      | series tag     | efiling_filed                | eFiling Filed                | text          | text          |
| Yes      | series tag     | plumbing                     | Plumbing                     | text          | text          |
| Yes      | series tag     | mechanical                   | Mechanical                   | text          | text          |
| Yes      | series tag     | boiler                       | Boiler                       | text          | text          |
| Yes      | series tag     | fuel_burning                 | Fuel Burning                 | text          | text          |
| Yes      | series tag     | fuel_storage                 | Fuel Storage                 | text          | text          |
| Yes      | series tag     | standpipe                    | Standpipe                    | text          | text          |
| Yes      | series tag     | sprinkler                    | Sprinkler                    | text          | text          |
| Yes      | series tag     | fire_alarm                   | Fire Alarm                   | text          | text          |
| Yes      | series tag     | equipment                    | Equipment                    | text          | text          |
| Yes      | series tag     | fire_suppression             | Fire Suppression             | text          | text          |
| Yes      | series tag     | curb_cut                     | Curb Cut                     | text          | text          |
| Yes      | series tag     | other                        | Other                        | text          | text          |
| Yes      | series tag     | other_description            | Other Description            | text          | text          |
| Yes      | series tag     | applicant_s_first_name       | Applicant's First Name       | text          | text          |
| Yes      | series tag     | applicant_s_last_name        | Applicant's Last Name        | text          | text          |
| Yes      | series tag     | applicant_professional_title | Applicant Professional Title | text          | text          |
| Yes      | series tag     | applicant_license__          | Applicant License #          | text          | text          |
| Yes      | series tag     | professional_cert            | Professional Cert            | text          | text          |
| No       |                | pre__filing_date             | Pre- Filing Date             | text          | text          |
| Yes      | series tag     | paid                         | Paid                         | text          | text          |
| Yes      | series tag     | fully_paid                   | Fully Paid                   | text          | text          |
| Yes      | series tag     | assigned                     | Assigned                     | text          | text          |
| Yes      | series tag     | approved                     | Approved                     | text          | text          |
| Yes      | series tag     | fully_permitted              | Fully Permitted              | text          | text          |
| Yes      | numeric metric | initial_cost                 | Initial Cost                 | money         | text          |
| Yes      | numeric metric | total_est__fee               | Total Est. Fee               | money         | text          |
| Yes      | series tag     | fee_status                   | Fee Status                   | text          | text          |
| Yes      | numeric metric | existing_zoning_sqft         | Existing Zoning Sqft         | number        | number        |
| Yes      | numeric metric | proposed_zoning_sqft         | Proposed Zoning Sqft         | number        | number        |
| Yes      | series tag     | horizontal_enlrgmt           | Horizontal Enlrgmt           | text          | text          |
| Yes      | series tag     | vertical_enlrgmt             | Vertical Enlrgmt             | text          | text          |
| Yes      | numeric metric | enlargement_sq_footage       | Enlargement SQ Footage       | number        | number        |
| Yes      | series tag     | street_frontage              | Street Frontage              | text          | number        |
| Yes      | numeric metric | existingno_of_stories        | ExistingNo. of Stories       | number        | number        |
| Yes      | numeric metric | proposed_no_of_stories       | Proposed No. of Stories      | number        | number        |
| Yes      | numeric metric | existing_height              | Existing Height              | number        | number        |
| Yes      | numeric metric | proposed_height              | Proposed Height              | number        | number        |
| Yes      | series tag     | existing_dwelling_units      | Existing Dwelling Units      | text          | text          |
| Yes      | series tag     | proposed_dwelling_units      | Proposed Dwelling Units      | text          | text          |
| Yes      | series tag     | existing_occupancy           | Existing Occupancy           | text          | text          |
| Yes      | series tag     | proposed_occupancy           | Proposed Occupancy           | text          | text          |
| Yes      | series tag     | site_fill                    | Site Fill                    | text          | text          |
| Yes      | series tag     | zoning_dist1                 | Zoning Dist1                 | text          | text          |
| Yes      | series tag     | zoning_dist2                 | Zoning Dist2                 | text          | text          |
| Yes      | series tag     | zoning_dist3                 | Zoning Dist3                 | text          | text          |
| Yes      | series tag     | special_district_1           | Special District 1           | text          | text          |
| Yes      | series tag     | special_district_2           | Special District 2           | text          | text          |
| Yes      | series tag     | owner_type                   | Owner Type                   | text          | text          |
| Yes      | series tag     | non_profit                   | Non-Profit                   | text          | text          |
| Yes      | series tag     | owner_s_first_name           | Owner's First Name           | text          | text          |
| Yes      | series tag     | owner_s_last_name            | Owner's Last Name            | text          | text          |
| Yes      | series tag     | owner_s_business_name        | Owner's Business Name        | text          | text          |
| Yes      | series tag     | owner_s_house_number         | Owner's House Number         | text          | text          |
| Yes      | series tag     | owner_shouse_street_name     | Owner'sHouse Street Name     | text          | text          |
| Yes      | series tag     | city_                        | City                         | text          | text          |
| Yes      | series tag     | state                        | State                        | text          | text          |
| Yes      | series tag     | zip                          | Zip                          | text          | text          |
| Yes      | series tag     | owner_sphone__               | Owner'sPhone #               | text          | text          |
| Yes      | series tag     | job_description              | Job Description              | text          | text          |
| Yes      | time           | dobrundate                   | DOBRunDate                   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dobrundate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latest_action_date,pre__filing_date
```

## Data Commands

```ls
series e:ic3t-wcy2 d:2013-04-26T00:00:00.000Z t:street_name="PARK AVENUE SOUTH" t:state=NY t:block=00857 t:job_status_descrp="APPLICATION PROCESSED - ENTIRE" t:building_type=OTHER t:job_status=D t:fee_status=STANDARD t:bin_=1016890 t:applicant_s_first_name=DOUGLAS t:owner_shouse_street_name="EAST 56TH STREET" t:paid=04/25/2013 t:job_type=A2 t:house_=386 t:owner_s_business_name="MACKLOWE MANAGEMENT" t:mechanical=X t:owner_s_house_number=126 t:fully_paid=04/25/2013 t:applicant_professional_title=PE t:doc_=02 t:zip=10222 t:owner_s_first_name=JAMES t:owner_s_last_name=MIGLIORE t:street_frontage=0 t:borough=MANHATTAN t:efiling_filed=Y t:applicant_license_=0058375 t:community__board=105 t:job_=121577873 t:applicant_s_last_name=MASS t:plumbing=X t:owner_sphone_=2125545837 t:lot=00038 t:job_description="GENERAL MECHANICAL & PLUMBING MODIFICATIONS AS PER PLANS FILED HEREWITH. NO      CHANGE TO USE, EGRESS OR OCCUPANCY" t:city_="NEW YORK" m:initial_cost=75000 m:proposed_zoning_sqft=0 m:existingno_of_stories=0 m:proposed_height=0 m:proposed_no_of_stories=0 m:existing_zoning_sqft=0 m:existing_height=0 m:total_est__fee=986 m:enlargement_sq_footage=0

series e:ic3t-wcy2 d:2013-04-26T00:00:00.000Z t:other=X t:street_name="KNOX PLACE" t:state=NY t:block=00342 t:job_status_descrp=PRE-FILING t:building_type="1-2-3 FAMILY" t:job_status=A t:fee_status=STANDARD t:bin_=5161350 t:other_description=BPP t:applicant_s_first_name=STEVEN t:owner_shouse_street_name="KNOX PLACE" t:job_type=A3 t:house_=107 t:owner_s_business_name=NA t:owner_s_house_number=107 t:applicant_professional_title=RA t:doc_=01 t:zip=10314 t:owner_s_first_name=DAVID t:owner_s_last_name=BLUMENBERG t:street_frontage=143 t:borough="STATEN ISLAND" t:efiling_filed=Y t:applicant_license_=0025259 t:community__board=501 t:job_=520129502 t:zoning_dist1=R2 t:applicant_s_last_name=SAVINO t:owner_sphone_=3477398892 t:lot=00001 t:job_description="BUILDERS PAVEMENT PLAN 143 LF." t:city_="STATEN ISLAND" m:initial_cost=0 m:proposed_zoning_sqft=0 m:existingno_of_stories=0 m:proposed_height=0 m:proposed_no_of_stories=0 m:existing_zoning_sqft=0 m:existing_height=0 m:total_est__fee=1144 m:enlargement_sq_footage=0

series e:ic3t-wcy2 d:2013-04-26T00:00:00.000Z t:other=X t:proposed_occupancy=RES t:site_fill="NOT APPLICABLE" t:street_name="WEST 131 STREET" t:state=NY t:block=01729 t:job_status_descrp="PERMIT ISSUED - PARTIAL JOB" t:building_type=OTHER t:job_status=Q t:fee_status=STANDARD t:bin_=1053831 t:other_description="GEN. CONSTR." t:applicant_s_first_name=ASHRAF t:professional_cert=Y t:owner_shouse_street_name="WEST 54TH STREET" t:paid=04/25/2013 t:approved=04/25/2013 t:job_type=A2 t:house_=63 t:owner_s_business_name="635 RIVERSIDE DRIVE NY LLC" t:existing_dwelling_units=20 t:owner_s_house_number=619 t:existing_occupancy=RES t:applicant_professional_title=PE t:fully_paid=04/25/2013 t:doc_=01 t:zip=10016 t:owner_s_first_name=JEREMIE t:owner_s_last_name=MARKOWITZ t:street_frontage=0 t:borough=MANHATTAN t:efiling_filed=Y t:applicant_license_=0084178 t:community__board=110 t:job_=121601560 t:zoning_dist1=R7-2 t:applicant_s_last_name=ALI t:plumbing=X t:proposed_dwelling_units=20 t:lot=00009 t:owner_sphone_=2127652555 t:job_description="GENERAL CONSTRUCTION TO INCLUDE NEW PARTITIONS, REPLACE EXISTING PLUMBING        FIXTURES WITH NEW, NO CHANGE IN USE, EGRESS OR OCCUPANCY." t:city_="NEW YORK" m:initial_cost=30000 m:proposed_zoning_sqft=0 m:existingno_of_stories=5 m:proposed_height=54 m:proposed_no_of_stories=5 m:existing_zoning_sqft=0 m:existing_height=54 m:total_est__fee=522.5 m:enlargement_sq_footage=0
```

## Meta Commands

```ls
metric m:initial_cost p:long l:"Initial Cost" d:"Estimated cost of job" t:dataTypeName=money

metric m:total_est__fee p:double l:"Total Est. Fee" d:"Estimated fee of job" t:dataTypeName=money

metric m:existing_zoning_sqft p:integer l:"Existing Zoning Sqft" d:"Existing Zoning Sqft" t:dataTypeName=number

metric m:proposed_zoning_sqft p:integer l:"Proposed Zoning Sqft" d:"Proposed Zoning Sqft" t:dataTypeName=number

metric m:enlargement_sq_footage p:integer l:"Enlargement SQ Footage" d:"Enlargement SQ Footage" t:dataTypeName=number

metric m:existingno_of_stories p:integer l:"ExistingNo. of Stories" d:"ExistingNo. of Stories" t:dataTypeName=number

metric m:proposed_no_of_stories p:integer l:"Proposed No. of Stories" d:"Proposed No. of Stories" t:dataTypeName=number

metric m:existing_height p:integer l:"Existing Height" d:"Existing Height" t:dataTypeName=number

metric m:proposed_height p:integer l:"Proposed Height" d:"Proposed Height" t:dataTypeName=number

entity e:ic3t-wcy2 l:"DOB Job Application Filings" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/ic3t-wcy2

property e:ic3t-wcy2 t:meta.view v:id=ic3t-wcy2 v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dob/html/codes_and_reference_materials/foilmonthly.shtml#job v:averageRating=0 v:name="DOB Job Application Filings" v:attribution="Department of Buildings (DOB)"

property e:ic3t-wcy2 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ic3t-wcy2 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| job__     | doc__ | borough       | house__ | street_name       | block | lot   | bin__   | job_type | job_status | job_status_descrp              | latest_action_date | building_type | community___board | cluster | landmarked | adult_estab | loft_board | city_owned | little_e | pc_filed | efiling_filed | plumbing | mechanical | boiler | fuel_burning | fuel_storage | standpipe | sprinkler | fire_alarm | equipment | fire_suppression | curb_cut | other | other_description | applicant_s_first_name | applicant_s_last_name | applicant_professional_title | applicant_license__ | professional_cert | pre__filing_date | paid       | fully_paid | assigned | approved   | fully_permitted | initial_cost | total_est__fee | fee_status | existing_zoning_sqft | proposed_zoning_sqft | horizontal_enlrgmt | vertical_enlrgmt | enlargement_sq_footage | street_frontage | existingno_of_stories | proposed_no_of_stories | existing_height | proposed_height | existing_dwelling_units | proposed_dwelling_units | existing_occupancy | proposed_occupancy | site_fill      | zoning_dist1 | zoning_dist2 | zoning_dist3 | special_district_1 | special_district_2 | owner_type | non_profit | owner_s_first_name | owner_s_last_name | owner_s_business_name          | owner_s_house_number | owner_shouse_street_name | city_         | state | zip   | owner_sphone__ | job_description                                                                                                                                                                                                                                                                                                                                                | dobrundate          | 
| ========= | ===== | ============= | ======= | ================= | ===== | ===== | ======= | ======== | ========== | ============================== | ================== | ============= | ================= | ======= | ========== | =========== | ========== | ========== | ======== | ======== | ============= | ======== | ========== | ====== | ============ | ============ | ========= | ========= | ========== | ========= | ================ | ======== | ===== | ================= | ====================== | ===================== | ============================ | =================== | ================= | ================ | ========== | ========== | ======== | ========== | =============== | ============ | ============== | ========== | ==================== | ==================== | ================== | ================ | ====================== | =============== | ===================== | ====================== | =============== | =============== | ======================= | ======================= | ================== | ================== | ============== | ============ | ============ | ============ | ================== | ================== | ========== | ========== | ================== | ================= | ============================== | ==================== | ======================== | ============= | ===== | ===== | ============== | ============================================================================================================================================================================================================================================================================================================================================================== | =================== | 
| 121577873 | 02    | MANHATTAN     | 386     | PARK AVENUE SOUTH | 00857 | 00038 | 1016890 | A2       | D          | APPLICATION PROCESSED - ENTIRE | 04/25/2013         | OTHER         | 105               |         |            |             |            |            |          |          | Y             | X        | X          |        |              |              |           |           |            |           |                  |          |       |                   | DOUGLAS                | MASS                  | PE                           | 0058375             |                   | 04/25/2013       | 04/25/2013 | 04/25/2013 |          |            |                 | $75000.00    | $986.00        | STANDARD   | 0                    | 0                    |                    |                  | 0                      | 0               | 0                     | 0                      | 0               | 0               |                         |                         |                    |                    |                |              |              |              |                    |                    |            |            | JAMES              | MIGLIORE          | MACKLOWE MANAGEMENT            | 126                  | EAST 56TH STREET         | NEW YORK      | NY    | 10222 | 2125545837     | GENERAL MECHANICAL & PLUMBING MODIFICATIONS AS PER PLANS FILED HEREWITH. NO CHANGE TO USE, EGRESS OR OCCUPANCY                                                                                                                                                                                                                                                 | 2013-04-26T00:00:00 | 
| 520129502 | 01    | STATEN ISLAND | 107     | KNOX PLACE        | 00342 | 00001 | 5161350 | A3       | A          | PRE-FILING                     | 04/25/2013         | 1-2-3 FAMILY  | 501               |         |            |             |            |            |          |          | Y             |          |            |        |              |              |           |           |            |           |                  |          | X     | BPP               | STEVEN                 | SAVINO                | RA                           | 0025259             |                   | 04/25/2013       |            |            |          |            |                 | $0.00        | $1144.00       | STANDARD   | 0                    | 0                    |                    |                  | 0                      | 143             | 0                     | 0                      | 0               | 0               |                         |                         |                    |                    |                | R2           |              |              |                    |                    |            |            | DAVID              | BLUMENBERG        | NA                             | 107                  | KNOX PLACE               | STATEN ISLAND | NY    | 10314 | 3477398892     | BUILDERS PAVEMENT PLAN 143 LF.                                                                                                                                                                                                                                                                                                                                 | 2013-04-26T00:00:00 | 
| 121601560 | 01    | MANHATTAN     | 63      | WEST 131 STREET   | 01729 | 00009 | 1053831 | A2       | Q          | PERMIT ISSUED - PARTIAL JOB    | 04/25/2013         | OTHER         | 110               |         |            |             |            |            |          |          | Y             | X        |            |        |              |              |           |           |            |           |                  |          | X     | GEN. CONSTR.      | ASHRAF                 | ALI                   | PE                           | 0084178             | Y                 | 04/25/2013       | 04/25/2013 | 04/25/2013 |          | 04/25/2013 |                 | $30000.00    | $522.50        | STANDARD   | 0                    | 0                    |                    |                  | 0                      | 0               | 5                     | 5                      | 54              | 54              | 20                      | 20                      | RES                | RES                | NOT APPLICABLE | R7-2         |              |              |                    |                    |            |            | JEREMIE            | MARKOWITZ         | 635 RIVERSIDE DRIVE NY LLC     | 619                  | WEST 54TH STREET         | NEW YORK      | NY    | 10016 | 2127652555     | GENERAL CONSTRUCTION TO INCLUDE NEW PARTITIONS, REPLACE EXISTING PLUMBING FIXTURES WITH NEW, NO CHANGE IN USE, EGRESS OR OCCUPANCY.                                                                                                                                                                                                                            | 2013-04-26T00:00:00 | 
| 121601203 | 01    | MANHATTAN     | 48      | WEST 25TH STREET  | 00826 | 00069 | 1015610 | A2       | D          | APPLICATION PROCESSED - ENTIRE | 04/25/2013         | OTHER         | 105               |         |            |             |            |            |          |          | Y             |          |            |        |              |              |           |           |            |           |                  |          | X     | STRUCTURAL        | J. BUTCH               | MACUTAY JR.           | PE                           | 0078226             |                   | 04/25/2013       | 04/25/2013 | 04/25/2013 |          |            |                 | $1500.00     | $225.00        | STANDARD   | 0                    | 0                    |                    |                  | 0                      | 0               | 12                    | 12                     | 120             | 120             |                         |                         | E                  | E                  | NOT APPLICABLE | C6-4X        | M1-6         |              |                    |                    |            |            | CARMINE            | CASALE            | 48 W 25 ST LLC C/O BERNSTEIN   | 150                  | WEST 30TH STREET         | NEW YORK      | NY    | 10001 | 2125941414     | STRUCTURAL CHANGES ON THE 5TH FLOOR (MOONDOG EDIT) AS INDICATED ON DRAWINGS. NO CHANGE IN USE, EGRESS OR OCCUPANCY.                                                                                                                                                                                                                                            | 2013-04-26T00:00:00 | 
| 121601338 | 01    | MANHATTAN     | 45      | WEST 29 STREET    | 00831 | 00007 | 1015754 | A3       | D          | APPLICATION PROCESSED - ENTIRE | 04/25/2013         | OTHER         | 105               |         |            |             |            |            |          |          | Y             |          |            |        |              |              |           |           |            |           |                  |          | X     | GEN. CONSTR.      | JUNHUI                 | JIA                   | PE                           | 0086781             |                   | 04/25/2013       | 04/25/2013 | 04/25/2013 |          |            |                 | $19500.00    | $389.50        | STANDARD   | 0                    | 0                    |                    |                  | 0                      | 0               | 6                     | 6                      | 64              | 64              |                         |                         | COM                | COM                |                | C6-4X        | M1-6         |              |                    |                    |            |            | HYUNG RO           | LEE               | HYUNG-HYANG REALTY CORP        | 614                  | 8 AVENUE                 | NEW YORK      | NY    | 10001 | 2019881222     | FILING HEREWITH FACADE REPAIR PLANS. WORK SCOPE TO INCLUDE BRICK, MORTAR, LINTEL, AND WINDOW SILL WORK AT VARIOUS LOCATIONS AND FLOORS. NO CHANGE IN USE, EGRESS, AND OCCUPANCY INVOLVED UNDER THIS APPLICATION.                                                                                                                                               | 2013-04-26T00:00:00 | 
| 121589753 | 01    | MANHATTAN     | 350     | FIFTH AVENUE      | 00835 | 00041 | 1015862 | A2       | Q          | PERMIT ISSUED - PARTIAL JOB    | 04/25/2013         | OTHER         | 105               |         | Y          |             |            |            |          |          | Y             |          |            |        |              |              |           |           |            |           |                  |          | X     | GEN. CONSTR.      | SCOTT                  | SPECTOR               | RA                           | 0023178             | Y                 | 04/25/2013       | 04/25/2013 | 04/25/2013 |          | 04/25/2013 |                 | $3062400.00  | $31762.40      | STANDARD   | 0                    | 0                    |                    |                  | 0                      | 0               | 102                   | 102                    | 1250            | 1250            |                         |                         | COM                | COM                | NOT APPLICABLE | C5-3         | C6-4.5       |              | MID                |                    |            |            | PIA                | SILVESTRI         | EMPIRE STATE BUILDING CO., LLC | 350                  | FIFTH AVENUE             | NEW YORK      | NY    | 10118 | 2127363100     | GENERAL CONSTRUCTION CHANGES TAKING PLACE ON THE 23RD FLOOR AS INDICATED ON DRAWINGS. NO CHANGE IN USE, EGRESS, OR OCCUPANCY.                                                                                                                                                                                                                                  | 2013-04-26T00:00:00 | 
| 320738001 | 01    | BROOKLYN      | 437     | TOMPKINS AVENUE   | 01846 | 00009 | 3331251 | A2       | P          | PLAN EXAM - APPROVED           | 04/25/2013         | OTHER         | 303               |         |            |             |            |            |          |          | Y             |          | X          |        |              |              |           |           |            |           |                  |          |       |                   | GIOVANNI,JR            | SODANO                | RA                           | 0029413             | Y                 | 04/25/2013       | 04/25/2013 | 04/25/2013 |          | 04/25/2013 |                 | $10000.00    | $316.50        | STANDARD   | 0                    | 0                    |                    |                  | 0                      | 0               | 3                     | 3                      | 36              | 36              | 2                       | 2                       | RES                | RES                | NOT APPLICABLE | R6A          |              |              |                    |                    |            |            | ABDU               | SALEH             | TOMPKINS DELI                  | 437                  | TOMPKINS AVENUE          | BROOKLYN      | NY    | 11216 | 6462675576     | APPLICATION FILED TO INSTALL A EXHAUST HOOD, DUCT WORK, AND EXTERIOR FLUE FOR COMMERCIAL COOKING EQUIPMENT.                                                                                                                                                                                                                                                    | 2013-04-26T00:00:00 | 
| 121601374 | 01    | MANHATTAN     | 99      | JOHN ST           | 00076 | 07502 | 1087867 | A2       | D          | APPLICATION PROCESSED - ENTIRE | 04/25/2013         | OTHER         | 101               |         |            |             |            |            |          |          | Y             | X        |            |        |              |              |           |           |            |           |                  |          | X     | GEN. CONSTR.      | RAYNOR                 | WARNER                | RA                           | 0035548             |                   | 04/25/2013       | 04/25/2013 | 04/25/2013 |          |            |                 | $146800.00   | $1727.60       | STANDARD   | 0                    | 0                    |                    |                  | 0                      | 0               | 27                    | 27                     | 300             | 300             | 444                     | 444                     | J-2                | J-2                | NOT APPLICABLE | C6-4         |              |              | LM                 |                    |            |            | LUIGI              | FRANCESE          | SKYLINE REALTY                 | 75                   | MAIDEN LANE              | NY            | NY    | 10038 | 6464219861     | COMBINE APT 502 AND 503 MINOR PARTITION WORK AND PLUMBING FIXTURES AS NOTED ON SCH. B. NO CHANGE IN USE OCCUPANCY OR EGRESS                                                                                                                                                                                                                                    | 2013-04-26T00:00:00 | 
| 121583054 | 01    | MANHATTAN     | 1355    | FIRST AVENUE      | 01447 | 00027 | 1088591 | A2       | D          | APPLICATION PROCESSED - ENTIRE | 04/25/2013         | OTHER         | 108               |         |            |             |            |            |          |          | Y             |          |            |        |              |              |           |           |            | X         |                  |          |       |                   | JOHN                   | O'CONNOR              | PE                           | 0084781             |                   | 04/25/2013       | 04/25/2013 | 04/25/2013 |          |            |                 | $0.00        | $160.00        | STANDARD   | 0                    | 0                    |                    |                  | 0                      | 0               | 34                    | 34                     | 398             | 398             | 51                      | 51                      | J-2                | J-2                | NOT APPLICABLE | C1-9         |              |              |                    |                    |            |            | PHILIP             | MENDLOW           | BLUE ROCK REAL ESTATE          | 70                   | EAST 55 STREET           | NEW YORK      | NY    | 10022 | 2128431601     | INSTALLATION OF TEMPORARY VERTICAL NETTING (COCOON) SYSTEM AS PER PLANS IN CONJUNCTION WITH NB CONSTRUCTION. NO CHANGE IN USE, EGRESS OR OCCUPANCY.                                                                                                                                                                                                            | 2013-04-26T00:00:00 | 
| 121601392 | 01    | MANHATTAN     | 1       | MANHATTAN PLAZA   | 09999 | 00001 | 1813346 | A2       | P          | PLAN EXAM - APPROVED           | 04/25/2013         | OTHER         | 118               |         |            |             |            |            |          |          | Y             |          |            |        |              |              |           |           |            |           |                  |          | X     | TEMP INSTALL      | ANDREW                 | FORMICHELLA           | RA                           | 0017578             | Y                 | 04/25/2013       | 04/25/2013 | 04/25/2013 |          | 04/25/2013 |                 | $5000.00     | $265.00        | STANDARD   | 0                    | 0                    |                    |                  | 0                      | 0               | 1                     | 1                      | 16              | 16              |                         |                         | A-5                | A-5                | NOT APPLICABLE | C5-3         |              |              |                    |                    |            |            | EM                 | PORTER            | CARAVENTS INC.                 | 337                  | S ROBERSON BLVD.         | BEVERLY HILLS | CA    | 90211 | 3108559595     | INSTALLATION OF POTENTIAL TEMPORARY RAIN CONTINGENCY TENTS ON THE SIDEWALK OF MARQUEE NYC, 289 10TH AVENUE, FOR THE EVENT KNOWN AS PEOPLE ESPANOL LOS 50 MOS BELLOS, SCHEDULED FOR MAY 13, 2013. A TEMPORARY PLACE OF ASSEMBLY PERMIT IS NOT REQUIRED. ALL PRODUCTION EQUIPMENT SHALL BE REMOVED UPON EVENT COMPLETION. NO CHANGE TO USE, EGRESS OR OCCUPANCY. | 2013-04-26T00:00:00 | 
```