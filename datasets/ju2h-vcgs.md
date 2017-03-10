# State Drug Utilization Data 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-drug-utilization-data-2015) |
| Metadata | [Link](https://data.medicaid.gov/api/views/ju2h-vcgs) |
| Data: JSON | [100 Rows](https://data.medicaid.gov/api/views/ju2h-vcgs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicaid.gov/api/views/ju2h-vcgs/rows.csv?max_rows=100) |
| Host | data.medicaid.gov |
| Id | ju2h-vcgs |
| Name | State Drug Utilization Data 2015 |
| Attribution | Centers for Medicare and Medicaid |
| Category | State Drug Utilization |
| Tags | drug utilization, medicaid reimbursements, pharmacy |
| Created | 2015-09-04T10:48:02Z |
| Publication Date | 2016-11-01T15:31:56Z |
| Rows Updated | 2017-02-02T23:48:56Z |

## Description

Drug utilization data are reported by states for covered outpatient drugs that are paid for by state Medicaid agencies since the start of the Medicaid Drug Rebate Program. The data includes state, drug name, National Drug Code, number of prescriptions and dollars reimbursed.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | record_id                      | Utilization Type               | text          | text          |
| Yes      | series tag     | state_code                     | State                          | text          | text          |
| Yes      | series tag     | labeler_code                   | Labeler Code                   | text          | text          |
| Yes      | series tag     | product_code                   | Product Code                   | text          | text          |
| Yes      | numeric metric | package_size                   | Package Size                   | number        | text          |
| Yes      | numeric metric | period_covered                 | Year                           | number        | text          |
| Yes      | numeric metric | quarter                        | Quarter                        | number        | text          |
| Yes      | series tag     | product_fda_list_name          | Product Name                   | text          | text          |
| Yes      | series tag     | suppression_used               | Suppression Used               | checkbox      | checkbox      |
| Yes      | numeric metric | units_reimbursed               | Units Reimbursed               | number        | number        |
| Yes      | numeric metric | number_of_prescriptions        | Number of Prescriptions        | number        | number        |
| Yes      | numeric metric | total_amount_reimbursed        | Total Amount Reimbursed        | number        | number        |
| Yes      | numeric metric | medicaid_amount_reimbursed     | Medicaid Amount Reimbursed     | number        | number        |
| Yes      | numeric metric | non_medicaid_amount_reimbursed | Non Medicaid Amount Reimbursed | number        | number        |
| Yes      | series tag     | quarter_begin                  | Quarter Begin                  | text          | text          |
| Yes      | time           | quarter_begin_date             | Quarter Begin Date             | calendar_date | calendar_date |
| No       |                | latitude                       | Latitude                       | number        | number        |
| No       |                | longitude                      | Longitude                      | number        | number        |
| Yes      | numeric metric | ndc                            | NDC                            | number        | text          |
```

## Time Field

```ls
Value = quarter_begin_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = longitude,latitude
```

## Data Commands

```ls
series e:ju2h-vcgs d:2015-07-01T00:00:00.000Z t:product_fda_list_name="ZYPREXA ZY" t:quarter_begin=7/1 t:state_code=AK t:labeler_code=00002 t:product_code=4453 t:suppression_used=true t:record_id=FFSU m:package_size=85 m:ndc=2445385 m:period_covered=2015 m:quarter=3

series e:ju2h-vcgs d:2015-10-01T00:00:00.000Z t:product_fda_list_name="ZYPREXA ZY" t:quarter_begin=10/1 t:state_code=AK t:labeler_code=00002 t:product_code=4453 t:suppression_used=true t:record_id=FFSU m:package_size=1 m:ndc=2445301 m:period_covered=2015 m:quarter=4

series e:ju2h-vcgs d:2015-01-01T00:00:00.000Z t:product_fda_list_name="ZYPREXA ZY" t:quarter_begin=1/1 t:state_code=AK t:labeler_code=00002 t:product_code=4453 t:suppression_used=true t:record_id=FFSU m:package_size=85 m:ndc=2445385 m:period_covered=2015 m:quarter=1
```

## Meta Commands

```ls
metric m:package_size p:integer l:"Package Size"al Drug Code (NDC3) identifies package forms and sizes." t:dataTypeName=number

metric m:period_covered p:integer l:YearpeName=number

metric m:quarter p:integer l:Quarter = January 1 ? March 31, 2 = April 1 ? June 30, 3 = July 1 ? September 30, 4 = October 1 ? December 31" t:dataTypeName=number

metric m:units_reimbursed l:"Units Reimbursed"ts (based on Unit Type) of the drug (11-digit NDC level) reimbursed by the state during the period covered." t:dataTypeName=number

metric m:number_of_prescriptions p:integer l:"Number of Prescriptions"ions reimbursed (by the Medicaid Program ONLY) to pharmacists for the (11-digit NDC) drug for the period covered." t:dataTypeName=number

metric m:total_amount_reimbursed l:"Total Amount Reimbursed"rsed by both Medicaid and non-Medicaid entities to pharmacies for the (11-digit NDC) drug in the period covered (two below fields added together). This total is not reduced or affected by Medicaid rebates paid to the state. This amount represents both the Federal and State Reimbursement and is inclusive of dispensing fees." t:dataTypeName=number

metric m:medicaid_amount_reimbursed l:"Medicaid Amount Reimbursed"by the Medicaid Program ONLY) to pharmacies for the (11-digit NDC) drug in the period covered." t:dataTypeName=number

metric m:non_medicaid_amount_reimbursed l:"Non Medicaid Amount Reimbursed"by non-Medicaid entities) to pharmacies for the (11-digit NDC) drug in the period covered. The Non-Medicaid Amount Reimbursed includes any reimbursement amount for which the state is not eligible for Federal Matching Funds." t:dataTypeName=number

metric m:ndc p:long l:NDC t:dataTypeName=number

entity e:ju2h-vcgs l:"State Drug Utilization Data 2015" t:attribution="Centers for Medicare and Medicaid" t:url=https://data.medicaid.gov/api/views/ju2h-vcgs

property e:ju2h-vcgs t:meta.view v:id=ju2h-vcgs v:category="State Drug Utilization" v:attributionLink=https://medicaid.gov v:averageRating=0 v:name="State Drug Utilization Data 2015" v:attribution="Centers for Medicare and Medicaid"

property e:ju2h-vcgs t:meta.view.license v:name="Public Domain"

property e:ju2h-vcgs t:meta.view.owner v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:displayName="Jeff Chamblee"

property e:ju2h-vcgs t:meta.view.tableauthor v:id=nmzs-t286 v:profileImageUrlMedium=/api/users/nmzs-t286/profile_images/THUMB v:profileImageUrlLarge=/api/users/nmzs-t286/profile_images/LARGE v:screenName="Jeff Chamblee" v:profileImageUrlSmall=/api/users/nmzs-t286/profile_images/TINY v:roleName=administrator v:displayName="Jeff Chamblee"

property e:ju2h-vcgs t:meta.view.metadata.custom_fields.common_core v:Bureau_Code=009:00 v:Program_Code=009:076
```