# Budget - 2015 Budget Recommendations - Appropriations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-2015-budget-recommendations-appropriations-68f61) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/kzbi-spm5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/kzbi-spm5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/kzbi-spm5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | kzbi-spm5 |
| Name | Budget - 2015 Budget Recommendations - Appropriations |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | budget, 2015 |
| Created | 2014-10-15T15:06:10Z |
| Publication Date | 2014-10-15T15:41:22Z |
| Rows Updated | 2014-10-15T15:40:17Z |

## Description

The dataset details 2015 Budget Recommendations, which is the line-item budget document proposed by the Mayor to the City Council for approval. Budgeted expenditures are identified by department, appropriation account, and funding type: Local, Community Development Block Grant Program (CDBG), and other Grants. ?Local? funds refer to those line items that are balanced with locally-generated revenue sources, including but not limited to the Corporate Fund, Water Fund, Midway and O?Hare Airport funds, Vehicle Tax Fund, Library Fund and General Obligation Bond funds. Owner: Budget and Management. Frequency: Data are updated annually. For more information about the budget process, visit the Budget Documents page: http://j.mp/lPotWf.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| No       | time           | :updated_at                         | updated_at                          | meta_data | meta_data   |
| Yes      | series tag     | fund_type                           | FUND TYPE                           | text      | text        |
| Yes      | series tag     | fund_code                           | FUND CODE                           | text      | text        |
| Yes      | series tag     | fund_description                    | FUND DESCRIPTION                    | text      | text        |
| Yes      | numeric metric | department_number                   | DEPARTMENT NUMBER                   | number    | number      |
| Yes      | series tag     | department_description              | DEPARTMENT DESCRIPTION              | text      | text        |
| Yes      | numeric metric | appropriation_authority             | APPROPRIATION AUTHORITY             | number    | number      |
| Yes      | series tag     | appropriation_authority_description | APPROPRIATION AUTHORITY DESCRIPTION | text      | text        |
| Yes      | numeric metric | appropriation_account               | APPROPRIATION ACCOUNT               | number    | number      |
| Yes      | series tag     | appropriation_account_description   | APPROPRIATION ACCOUNT DESCRIPTION   | text      | text        |
| Yes      | numeric metric | appropration                        | 2014 APPROPRATION                   | money     | money       |
| Yes      | numeric metric | revised_appropriation               | 2014 REVISED APPROPRIATION          | money     | money       |
| Yes      | numeric metric | recommendation                      | 2015 RECOMMENDATION                 | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kzbi-spm5 d:2014-10-15T08:40:01.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_type=LOCAL t:fund_code=0100 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_account_description="SALARIES AND WAGES - ON PAYROLL" t:fund_description="CORPORATE FUND" m:appropriation_account=5 m:appropration=5511957 m:appropriation_authority=2005 m:department_number=1 m:revised_appropriation=5511957 m:recommendation=5550657

series e:kzbi-spm5 d:2014-10-15T08:40:01.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_type=LOCAL t:fund_code=0100 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_account_description="OFFICE CONVENIENCES" t:fund_description="CORPORATE FUND" m:appropriation_account=126 m:appropration=1200 m:appropriation_authority=2005 m:department_number=1 m:revised_appropriation=1200 m:recommendation=1000

series e:kzbi-spm5 d:2014-10-15T08:40:01.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_type=LOCAL t:fund_code=0100 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_account_description=POSTAGE t:fund_description="CORPORATE FUND" m:appropriation_account=130 m:appropration=10000 m:appropriation_authority=2005 m:department_number=1 m:revised_appropriation=10000 m:recommendation=5019
```

## Meta Commands

```ls
metric m:department_number p:integer l:"DEPARTMENT NUMBER" t:dataTypeName=number

metric m:appropriation_authority p:integer l:"APPROPRIATION AUTHORITY" t:dataTypeName=number

metric m:appropriation_account p:integer l:"APPROPRIATION ACCOUNT" t:dataTypeName=number

entity e:kzbi-spm5 l:"Budget - 2015 Budget Recommendations - Appropriations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/kzbi-spm5

property e:kzbi-spm5 t:meta.view v:id=kzbi-spm5 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/budget v:averageRating=0 v:name="Budget - 2015 Budget Recommendations - Appropriations" v:attribution="City of Chicago"

property e:kzbi-spm5 t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"

property e:kzbi-spm5 t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```