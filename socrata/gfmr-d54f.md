# Budget - 2013 Budget Recommendations - Positions and Salaries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2013-budget-recommendations-positions-and-salaries-7c335) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/gfmr-d54f) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/gfmr-d54f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/gfmr-d54f/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | gfmr-d54f |
| Name | Budget - 2013 Budget Recommendations - Positions and Salaries |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, 2013 |
| Created | 2012-10-09T23:15:50Z |
| Publication Date | 2012-10-10T22:28:24Z |

## Description

This dataset includes recommended positions and salaries for 2013 by title (without names) and salary. The dataset is excerpted from the 2013 Budget Recommendations, which is the line-item budget proposed by the Mayor to the City Council for approval. Disclaimer: the ?Total Budgeted Units? column displays either A) the number of employees AND vacancies associated with a given position, or B) the number of budgeted units (ie. hours/months) for that position. ?Position Control? determines whether Total Budgeted Units column will count employees and vacancies or hours/months. If a Position Control is 1, then employees and vacancies are displayed; if a Position Control is 0, then the total number of hours/months recorded is displayed. Owner: Budget and Management. Frequency: Data is updated annually. For more information about the budget process, visit the Budget Documents page: http://j.mp/lPotWf.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | fund_type                | FUND TYPE                | text      | text        |
| Yes      | series tag     | department_code          | DEPARTMENT CODE          | text      | number      |
| Yes      | series tag     | department_description   | DEPARTMENT DESCRIPTION   | text      | text        |
| Yes      | series tag     | fund_code                | FUND CODE                | text      | text        |
| Yes      | series tag     | fund_description         | FUND DESCRIPTION         | text      | text        |
| Yes      | series tag     | organization_code        | ORGANIZATION CODE        | text      | number      |
| Yes      | series tag     | organization_description | ORGANIZATION DESCRIPTION | text      | text        |
| Yes      | series tag     | division_code            | DIVISION CODE            | text      | number      |
| Yes      | series tag     | division_description     | DIVISION DESCRIPTION     | text      | text        |
| Yes      | series tag     | section_code             | SECTION CODE             | text      | number      |
| Yes      | series tag     | section_description      | SECTION DESCRIPTION      | text      | text        |
| Yes      | series tag     | subsection_code          | SUBSECTION CODE          | text      | number      |
| Yes      | series tag     | sub_section_description  | SUB-SECTION DESCRIPTION  | text      | text        |
| Yes      | series tag     | schedule_grade           | SCHEDULE / GRADE         | text      | text        |
| Yes      | numeric metric | bargaining_unit          | BARGAINING UNIT          | number    | number      |
| Yes      | series tag     | title_code               | TITLE CODE               | text      | text        |
| Yes      | series tag     | title_description        | TITLE DESCRIPTION        | text      | text        |
| Yes      | series tag     | budgeted_unit            | BUDGETED UNIT            | text      | text        |
| Yes      | numeric metric | total_budgeted_unit      | TOTAL BUDGETED UNIT      | number    | number      |
| Yes      | numeric metric | position_control         | POSITION CONTROL         | number    | number      |
| Yes      | numeric metric | budgeted_pay_rate        | BUDGETED PAY RATE        | money     | money       |
| Yes      | numeric metric | total_budgeted_amount    | TOTAL BUDGETED AMOUNT    | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gfmr-d54f d:2013-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:subsection_code=0 t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:organization_description="OFFICE OF THE MAYOR" t:schedule_grade="1 00" t:division_description="OFFICE OF THE MAYOR" t:title_code=9901 t:section_description=Executive t:title_description=Mayor t:department_code=1 m:total_budgeted_amount=216210 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=216210 m:bargaining_unit=9

series e:gfmr-d54f d:2013-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:subsection_code=0 t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:organization_description="OFFICE OF THE MAYOR" t:schedule_grade="1 00" t:division_description="OFFICE OF THE MAYOR" t:title_code=9637 t:section_description=Executive t:title_description="Administrative Assistant" t:department_code=1 m:total_budgeted_amount=48000 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=48000 m:bargaining_unit=0

series e:gfmr-d54f d:2013-01-01T00:00:00.000Z t:fund_code=100 t:fund_type=Local t:division_code=2005 t:organization_code=1005 t:budgeted_unit=Annual t:subsection_code=0 t:section_code=3005 t:fund_description="CORPORATE FUND" t:department_description="OFFICE OF THE MAYOR" t:organization_description="OFFICE OF THE MAYOR" t:schedule_grade="1 00" t:division_description="OFFICE OF THE MAYOR" t:title_code=9637 t:section_description=Executive t:title_description="Administrative Assistant" t:department_code=1 m:total_budgeted_amount=44004 m:position_control=1 m:total_budgeted_unit=1 m:budgeted_pay_rate=44004 m:bargaining_unit=0
```

## Meta Commands

```ls
metric m:bargaining_unit p:integer l:"BARGAINING UNIT" t:dataTypeName=number

metric m:total_budgeted_unit p:integer l:"TOTAL BUDGETED UNIT" t:dataTypeName=number

metric m:position_control p:integer l:"POSITION CONTROL" t:dataTypeName=number

metric m:budgeted_pay_rate p:double l:"BUDGETED PAY RATE" t:dataTypeName=money

metric m:total_budgeted_amount p:double l:"TOTAL BUDGETED AMOUNT" t:dataTypeName=money

entity e:gfmr-d54f l:"Budget - 2013 Budget Recommendations - Positions and Salaries" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/gfmr-d54f

property e:gfmr-d54f t:meta.view v:id=gfmr-d54f v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/city/en/depts/obm.html v:averageRating=0 v:name="Budget - 2013 Budget Recommendations - Positions and Salaries" v:attribution="City of Chicago"

property e:gfmr-d54f t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:gfmr-d54f t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| fund_type | department_code | department_description | fund_code | fund_description | organization_code | organization_description | division_code | division_description | section_code | section_description | subsection_code | sub_section_description | schedule_grade | bargaining_unit | title_code | title_description                               | budgeted_unit | total_budgeted_unit | position_control | budgeted_pay_rate | total_budgeted_amount | 
| ========= | =============== | ====================== | ========= | ================ | ================= | ======================== | ============= | ==================== | ============ | =================== | =============== | ======================= | ============== | =============== | ========== | =============================================== | ============= | =================== | ================ | ================= | ===================== | 
| Local     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0               |                         | 1 00           | 9               | 9901       | Mayor                                           | Annual        | 1                   | 1                | 216210.00         | 216210.00             | 
| Local     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0               |                         | 1 00           | 0               | 9637       | Administrative Assistant                        | Annual        | 1                   | 1                | 48000.00          | 48000.00              | 
| Local     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0               |                         | 1 00           | 0               | 9637       | Administrative Assistant                        | Annual        | 1                   | 1                | 44004.00          | 44004.00              | 
| Local     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3005         | Executive           | 0               |                         | 1 00           | 9               | 9617       | Administrative Secretary                        | Annual        | 1                   | 1                | 74988.00          | 74988.00              | 
| Local     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0               |                         | 1 00           | 9               | 9899       | Chief of Staff                                  | Annual        | 1                   | 1                | 174996.00         | 174996.00             | 
| Local     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0               |                         | 1 00           | 9               | 9898       | Deputy Chief of Staff                           | Annual        | 1                   | 1                | 154992.00         | 154992.00             | 
| Local     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0               |                         | 1 00           | 9               | 9898       | Deputy Chief of Staff                           | Annual        | 1                   | 1                | 120000.00         | 120000.00             | 
| Local     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0               |                         | 1 00           | 9               | 9896       | Chief Financial Officer                         | Annual        | 1                   | 1                | 169992.00         | 169992.00             | 
| Local     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0               |                         | 1 00           | 9               | 9891       | Administrative Assistant - Office Administrator | Annual        | 1                   | 1                | 85596.00          | 85596.00              | 
| Local     | 1               | OFFICE OF THE MAYOR    | 100       | CORPORATE FUND   | 1005              | OFFICE OF THE MAYOR      | 2005          | OFFICE OF THE MAYOR  | 3010         | Administrative      | 0               |                         | 1 00           | 9               | 9889       | First Deputy Chief of Staff                     | Annual        | 1                   | 1                | 154992.00         | 154992.00             | 
```