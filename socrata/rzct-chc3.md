# Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/business-energy-tax-credit-program-fiscal-year-2014-0e49c) |
| Metadata | [Link](https://data.oregon.gov/api/views/rzct-chc3) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/rzct-chc3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/rzct-chc3/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | rzct-chc3 |
| Name | Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14) |
| Category | Revenue & Expense |
| Tags | tax credit, busiess energy tax credit, tax credit program 2014, 2014 |
| Created | 2014-12-31T03:21:39Z |
| Publication Date | 2015-12-27T22:27:10Z |

## Description

Business Energy Tax Credit Program—Oregon Department of Energy  The Business Energy Tax Credit program ended July 1, 2014  (HB 3672 in 2011 and HB 4079 in 2012) and tax credits are no longer being awarded under this program.  
For more information go to: http://www.oregon.gov/transparency/Pages/Tax-Expenditures.aspx#Department_of_Revenue_%28DOR%29_-_Reports_and_Resource_Links%C2%A0_

------------------
Historical Info
--------------------
•	This spreadsheet covers July 1, 2013 through June 30, 2014.
•	Per statute, this list does not include final certificates issued for Combined Heat and Power or High Performance Homes projects. Withdrawn, Denied, Inactive, Rejected, and Revoked Projects are also excluded.
•	Every effort has been made to ensure the data are complete, but these records reflect information reported to this agency by others. The Oregon Department of Energy is not responsible for data that is misinterpreted or altered in any way.
•	If errors are discovered after publication of the records, the data are corrected in the electronic files.  It is estimated that there is a margin of error of less than one percent.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================== | ============================== | ============= | ============= |
| Yes      | series tag     | agency_issuing_tax_expenditure | Agency Issuing Tax Expenditure | text          | text          |
| No       |                | final_year                     | Final Year                     | number        | number        |
| Yes      | time           | final_date                     | Final Date                     | calendar_date | calendar_date |
| Yes      | series tag     | applicant_business_name        | Applicant Business Name        | text          | text          |
| Yes      | series tag     | site_city                      | Site City                      | text          | text          |
| Yes      | series tag     | site_zip                       | Site Zip                       | text          | number        |
| Yes      | series tag     | site_county                    | Site County                    | text          | text          |
| Yes      | series tag     | system                         | System                         | text          | text          |
| Yes      | series tag     | system_name                    | System Name                    | text          | text          |
| Yes      | numeric metric | final_month                    | Final Month                    | number        | number        |
| Yes      | numeric metric | final_certified_project_cost   | Final Certified Project Cost   | money         | money         |
| Yes      | numeric metric | final_tax_credit               | Final Tax Credit               | money         | money         |
| Yes      | numeric metric | total_energy_million_btu       | Total Energy (Million Btu)     | number        | number        |
| Yes      | numeric metric | tax_credit_ratepercentage      | Tax Credit Rate                | number        | number        |
| Yes      | series tag     | application                    | Application #                  | text          | number        |
```

## Time Field

```ls
Value = final_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = final_year
```

## Data Commands

```ls
series e:rzct-chc3 d:2014-06-06T00:00:00.000Z t:system=Conservation t:application=32077 t:site_county=Mult t:system_name="HVAC System" t:applicant_business_name="SOO Portland State University" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:site_zip=97201 t:site_city=Portland m:final_tax_credit=85260 m:tax_credit_ratepercentage=0.35 m:final_certified_project_cost=243600 m:total_energy_million_btu=2352 m:final_month=6

series e:rzct-chc3 d:2013-07-01T00:00:00.000Z t:system="Sustainable Building" t:application=30191 t:site_county=Mult t:system_name="USGBC LEED (CI) Gold" t:applicant_business_name="Northwest Evaluation Association" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:site_zip=97209 t:site_city=Portland m:final_tax_credit=43398 m:tax_credit_ratepercentage=0.34999798378966895 m:final_certified_project_cost=123995 m:total_energy_million_btu=0 m:final_month=7

series e:rzct-chc3 d:2013-07-31T00:00:00.000Z t:system="Sustainable Building" t:application=30849 t:site_county=Clac t:system_name="USGBC LEED (NC) Silver" t:applicant_business_name="Stafford Hills Racquet & Fitness Club" t:agency_issuing_tax_expenditure="Oregon Department of Energy" t:site_zip=97062 t:site_city=Tualatin m:final_tax_credit=131508 m:tax_credit_ratepercentage=0.3500010645772564 m:final_certified_project_cost=375736 m:total_energy_million_btu=0 m:final_month=7
```

## Meta Commands

```ls
metric m:final_month p:integer l:"Final Month" t:dataTypeName=number

metric m:final_certified_project_cost p:integer l:"Final Certified Project Cost" t:dataTypeName=money

metric m:final_tax_credit p:integer l:"Final Tax Credit" t:dataTypeName=money

metric m:total_energy_million_btu p:integer l:"Total Energy (Million Btu)" t:dataTypeName=number

metric m:tax_credit_ratepercentage p:decimal l:"Tax Credit Rate" t:dataTypeName=number

entity e:rzct-chc3 l:"Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14)" t:url=https://data.oregon.gov/api/views/rzct-chc3

property e:rzct-chc3 t:meta.view d:2017-09-25T07:25:40.772Z v:averageRating=0 v:name="Business Energy Tax Credit Program: Fiscal Year 2014 (Ended 7/1/14)" v:id=rzct-chc3 v:category="Revenue & Expense"

property e:rzct-chc3 t:meta.view.owner d:2017-09-25T07:25:40.772Z v:displayName="Paula N." v:lastNotificationSeenAt=1500509429 v:id=d6zz-js5q v:screenName="Paula N."

property e:rzct-chc3 t:meta.view.tableauthor d:2017-09-25T07:25:40.772Z v:displayName="Paula N." v:lastNotificationSeenAt=1500509429 v:roleName=administrator v:id=d6zz-js5q v:screenName="Paula N."
```

## Top Records

```ls
| agency_issuing_tax_expenditure | final_year | final_date          | applicant_business_name                            | site_city     | site_zip | site_county | system               | system_name                               | final_month | final_certified_project_cost | final_tax_credit | total_energy_million_btu | tax_credit_ratepercentage | application | 
| ============================== | ========== | =================== | ================================================== | ============= | ======== | =========== | ==================== | ========================================= | =========== | ============================ | ================ | ======================== | ========================= | =========== | 
| Oregon Department of Energy    | 2014       | 2014-06-06T00:00:00 | SOO Portland State University                      | Portland      | 97201    | Mult        | Conservation         | HVAC System                               | 6           | 243600                       | 85260            | 2352                     | 0.35                      | 32077       | 
| Oregon Department of Energy    | 2013       | 2013-07-01T00:00:00 | Northwest Evaluation Association                   | Portland      | 97209    | Mult        | Sustainable Building | USGBC LEED (CI) Gold                      | 7           | 123995                       | 43398            | 0                        | 0.34999798378966895       | 30191       | 
| Oregon Department of Energy    | 2013       | 2013-07-31T00:00:00 | Stafford Hills Racquet & Fitness Club              | Tualatin      | 97062    | Clac        | Sustainable Building | USGBC LEED (NC) Silver                    | 7           | 375736                       | 131508           | 0                        | 0.35000106457725638       | 30849       | 
| Oregon Department of Energy    | 2013       | 2013-07-31T00:00:00 | B & W Moore Farms                                  | Klamath Falls | 97603    | Klam        | Conservation         | VFDs                                      | 7           | 16020                        | 5607             | 152                      | 0.35                      | 31008       | 
| Oregon Department of Energy    | 2013       | 2013-07-31T00:00:00 | Cyrk Building, LLC                                 | Portland      | 97202    | Mult        | Sustainable Building | USGBC LEED (NC) Platinum                  | 7           | 218826                       | 76589            | 0                        | 0.34999954301591218       | 31103       | 
| Oregon Department of Energy    | 2013       | 2013-08-14T00:00:00 | Oregon Trail School District                       | Sandy         | 97055    | Clac        | Sustainable Building | USGBC LEED (NC) Gold                      | 8           | 1098448                      | 384457           | 0                        | 0.35000018207507322       | 29662       | 
| Oregon Department of Energy    | 2013       | 2013-08-15T00:00:00 | Vitesse, LLC. c/o Paul, Hastins, Janofsky & Walker | Prineville    | 97754    | Croo        | Sustainable Building | USGBC LEED (NC) Gold                      | 8           | 678700                       | 237545           | 0                        | 0.35                      | 34518       | 
| Oregon Department of Energy    | 2013       | 2013-08-28T00:00:00 | Umatilla County Juvenile Detention Center          | Pendleton     | 97801    | Umat        | Conservation         | HVAC System                               | 8           | 279525                       | 97834            | 1058                     | 0.35000089437438514       | 31165       | 
| Oregon Department of Energy    | 2013       | 2013-09-10T00:00:00 | Davis Tool                                         | Hillsboro     | 97124    | Wash        | Conservation         | VFDs                                      | 9           | 33592                        | 11757            | 791                      | 0.34999404620147656       | 31504       | 
| Oregon Department of Energy    | 2013       | 2013-10-29T00:00:00 | Lebanon Transportation Program                     | Lebanon       | 97355    | Linn        | Transportation       | Transit Providers/Transportation Services | 10          | 66725                        | 23354            | 492                      | 0.3500037467216186        | 33558       | 
```