# Strategic Investment Program - Fiscal Year 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/strategic-investment-program-fiscal-year-2013-35561) |
| Metadata | [Link](https://data.oregon.gov/api/views/7hk7-2gdq) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/7hk7-2gdq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/7hk7-2gdq/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 7hk7-2gdq |
| Name | Strategic Investment Program - Fiscal Year 2013 |
| Category | Revenue & Expense |
| Tags | oregon investment, oregon strategic investment, oregon strategic investment program |
| Created | 2013-11-06T22:47:25Z |
| Publication Date | 2013-11-06T22:49:05Z |

## Columns

```ls
| Included | Schema Type | Field Name                                                 | Name                                                         | Data Type | Render Type |
| ======== | =========== | ========================================================== | ============================================================ | ========= | =========== |
| Yes      | series tag  | agency_issuing_tax_expenditure                             | Agency Issuing Tax Expenditure                               | text      | text        |
| Yes      | time        | report_period_end_date                                     | Report Period End Date                                       | text      | text        |
| Yes      | series tag  | business_firm_name                                         | Business Firm Name                                           | text      | text        |
| No       |             | mailing_address                                            | Mailing Address                                              | text      | text        |
| Yes      | series tag  | zip_code                                                   | ZIP Code                                                     | text      | text        |
| Yes      | series tag  | project_location_county_code                               | Project Location County Code                                 | text      | text        |
| Yes      | series tag  | project_location_congressional_district                    | Project Location Congressional District                      | text      | text        |
| Yes      | series tag  | name_of_proposed_project                                   | Name of Proposed Project                                     | text      | text        |
| Yes      | series tag  | estimated_total_investment                                 | Estimated Total Investment                                   | text      | text        |
| Yes      | series tag  | anticipated_first_tax_year_of_exemption                    | Anticipated First Tax Year of Exemption                      | text      | text        |
| Yes      | series tag  | property_tax_benefit_not_a_credit                          | Property Tax Benefit**(not a credit)                         | text      | text        |
| Yes      | series tag  | specific_outcomes_of_the_program_and_taxpayer_requirements | Specific Outcomes of the Program and Taxpayer Requirements** | text      | text        |
| Yes      | series tag  | statistics_and_methodology_employed                        | Statistics and Methodology Employed                          | text      | text        |
| Yes      | series tag  | agency_s_certification_decision                            | Agency's Certification Decision                              | text      | text        |
```

## Time Field

```ls
Value = report_period_end_date
Format & Zone = MM/dd/yy
```

## Series Fields

```ls
Excluded Fields = mailing_address
```

## Data Commands

```ls
series e:7hk7-2gdq d:2013-06-30T00:00:00.000Z t:project_location_congressional_district=n/a t:specific_outcomes_of_the_program_and_taxpayer_requirements="Project benefits traded-sector industry 
Full disclosure of concurrent, statewide employment changes 
Investment costs exceed taxable portion 
Local approval pursuant to?
 - County public hearing 
 - Written agreement with business firm
 - Vote by county governing body" t:zip_code=n/a t:agency_issuing_tax_expenditure="County Assessor (Oregon Department of Revenue)" t:business_firm_name="NO APPROVALS WERE MADE DURING PRECEDING FISCAL YEAR" t:anticipated_first_tax_year_of_exemption=n/a t:statistics_and_methodology_employed="Not applicable" t:agency_s_certification_decision="Commission determination of eligibility based on review of local process, proposed investment & operations, and other evidence." t:project_location_county_code=n/a t:property_tax_benefit_not_a_credit="UNREALIZED - Project property with market value in excess of taxable portion exempt for 15 years, less community service fee and locally negotiated requirements" t:estimated_total_investment=n/a t:name_of_proposed_project=n/a m:row_number.7hk7-2gdq=1
```

## Meta Commands

```ls
metric m:row_number.7hk7-2gdq p:long l:"Row Number"

entity e:7hk7-2gdq l:"Strategic Investment Program - Fiscal Year 2013" t:url=https://data.oregon.gov/api/views/7hk7-2gdq

property e:7hk7-2gdq t:meta.view v:id=7hk7-2gdq v:category="Revenue & Expense" v:averageRating=0 v:name="Strategic Investment Program - Fiscal Year 2013"

property e:7hk7-2gdq t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."

property e:7hk7-2gdq t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:lastNotificationSeenAt=1492617591 v:displayName="Paula N."
```

## Top Records

```ls
| agency_issuing_tax_expenditure                 | report_period_end_date | business_firm_name                                  | mailing_address | zip_code | project_location_county_code | project_location_congressional_district | name_of_proposed_project | estimated_total_investment | anticipated_first_tax_year_of_exemption | property_tax_benefit_not_a_credit                                                                                                                                | specific_outcomes_of_the_program_and_taxpayer_requirements                                                                                                                                                                                                             | statistics_and_methodology_employed | agency_s_certification_decision                                                                                                 | 
| ============================================== | ====================== | =================================================== | =============== | ======== | ============================ | ======================================= | ======================== | ========================== | ======================================= | ================================================================================================================================================================ | ====================================================================================================================================================================================================================================================================== | =================================== | =============================================================================================================================== | 
| County Assessor (Oregon Department of Revenue) | 6/30/13                | NO APPROVALS WERE MADE DURING PRECEDING FISCAL YEAR | n/a             | n/a      | n/a                          | n/a                                     | n/a                      | n/a                        | n/a                                     | UNREALIZED - Project property with market value in excess of taxable portion exempt for 15 years, less community service fee and locally negotiated requirements | Project benefits traded-sector industry Full disclosure of concurrent, statewide employment changes Investment costs exceed taxable portion Local approval pursuant to? - County public hearing - Written agreement with business firm - Vote by county governing body | Not applicable                      | Commission determination of eligibility based on review of local process, proposed investment & operations, and other evidence. | 
```