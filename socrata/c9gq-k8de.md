# FY 2016 Proposed Operating Budget Expenditures – Line Item Detail

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy-2016-proposed-operating-budget-expenditures-line-item-detail) |
| Metadata | [Link](https://data.austintexas.gov/api/views/c9gq-k8de) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/c9gq-k8de/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/c9gq-k8de/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | c9gq-k8de |
| Name | FY 2016 Proposed Operating Budget Expenditures – Line Item Detail |
| Attribution | City of Austin |
| Category | Budget and Finance |
| Tags | proposed budget |
| Created | 2015-08-14T21:37:06Z |
| Publication Date | 2015-08-14T21:52:16Z |

## Description

City of Austin FY 2016 Proposed operating budget showing expenditures by line item detail. The Proposed Budget is at the Fund, Department, Program, Activity, Unit and Expense Code level. The information contained in this data set is for informational purposes for viewing and downloading and includes personnel, contractual and commodities. Certain Austin Energy budget items have been excluded as competitive matters under Texas Government Code Section 552.133 and City Council Resolution 20051201-002.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | proposed_fiscal_year | PROPOSED_FISCAL_YEAR | number    | number      |
| Yes      | numeric metric | dept_rollup          | DEPT_ROLLUP          | number    | number      |
| Yes      | series tag     | dept_rollup_name     | DEPT_ROLLUP_NAME     | text      | text        |
| Yes      | series tag     | department_code      | DEPARTMENT_CODE      | text      | number      |
| Yes      | series tag     | department_name      | DEPARTMENT_NAME      | text      | text        |
| Yes      | series tag     | fund_code            | FUND_CODE            | text      | number      |
| Yes      | series tag     | fund_name            | FUND_NAME            | text      | text        |
| Yes      | series tag     | program_code         | PROGRAM_CODE         | text      | text        |
| Yes      | series tag     | program_name         | PROGRAM_NAME         | text      | text        |
| Yes      | series tag     | activity_code        | ACTIVITY_CODE        | text      | text        |
| Yes      | series tag     | activity_name        | ACTIVITY_NAME        | text      | text        |
| Yes      | series tag     | unit_code            | UNIT_CODE            | text      | number      |
| Yes      | series tag     | unit_name            | UNIT_NAME            | text      | text        |
| Yes      | series tag     | expense_code         | EXPENSE_CODE         | text      | number      |
| Yes      | series tag     | expense_name         | EXPENSE_NAME         | text      | text        |
| Yes      | numeric metric | proposed_budget      | PROPOSED_BUDGET      | number    | number      |
```

## Time Field

```ls
Value = proposed_fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:c9gq-k8de d:2016-01-01T00:00:00.000Z t:department_code=9200 t:activity_name="Field Services" t:department_name="Animal Services" t:program_name="Animal Services" t:expense_code=5001 t:dept_rollup_name="Animal Services" t:fund_name="General Fund" t:activity_code=2FDS t:fund_code=1000 t:unit_name="Animal Protection" t:expense_name="Regular wages - full-time" t:program_code=2ANL t:unit_code=2131 m:dept_rollup=92 m:proposed_budget=806489

series e:c9gq-k8de d:2016-01-01T00:00:00.000Z t:department_code=9200 t:activity_name="Field Services" t:department_name="Animal Services" t:program_name="Animal Services" t:expense_code=5002 t:dept_rollup_name="Animal Services" t:fund_name="General Fund" t:activity_code=2FDS t:fund_code=1000 t:unit_name="Animal Protection" t:expense_name="Regular wages - part-time" t:program_code=2ANL t:unit_code=2131 m:dept_rollup=92 m:proposed_budget=17879

series e:c9gq-k8de d:2016-01-01T00:00:00.000Z t:department_code=9200 t:activity_name="Field Services" t:department_name="Animal Services" t:program_name="Animal Services" t:expense_code=5005 t:dept_rollup_name="Animal Services" t:fund_name="General Fund" t:activity_code=2FDS t:fund_code=1000 t:unit_name="Animal Protection" t:expense_name=Overtime t:program_code=2ANL t:unit_code=2131 m:dept_rollup=92 m:proposed_budget=45664
```

## Meta Commands

```ls
metric m:dept_rollup p:integer l:DEPT_ROLLUP t:dataTypeName=number

metric m:proposed_budget p:integer l:PROPOSED_BUDGET t:dataTypeName=number

entity e:c9gq-k8de l:"FY 2016 Proposed Operating Budget Expenditures – Line Item Detail" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/c9gq-k8de

property e:c9gq-k8de t:meta.view d:2017-09-25T07:27:42.025Z v:averageRating=0 v:name="FY 2016 Proposed Operating Budget Expenditures – Line Item Detail" v:attribution="City of Austin" v:id=c9gq-k8de v:category="Budget and Finance"

property e:c9gq-k8de t:meta.view.license d:2017-09-25T07:27:42.025Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:c9gq-k8de t:meta.view.owner d:2017-09-25T07:27:42.025Z v:displayName="FSD - Controller's Office" v:id=mx9i-sxdu v:screenName="FSD - Controller's Office"

property e:c9gq-k8de t:meta.view.tableauthor d:2017-09-25T07:27:42.025Z v:displayName="FSD - Controller's Office" v:roleName=publisher v:id=mx9i-sxdu v:screenName="FSD - Controller's Office"
```

## Top Records

```ls
| proposed_fiscal_year | dept_rollup | dept_rollup_name | department_code | department_name | fund_code | fund_name    | program_code | program_name    | activity_code | activity_name  | unit_code | unit_name         | expense_code | expense_name                 | proposed_budget | 
| ==================== | =========== | ================ | =============== | =============== | ========= | ============ | ============ | =============== | ============= | ============== | ========= | ================= | ============ | ============================ | =============== | 
| 2016                 | 92          | Animal Services  | 9200            | Animal Services | 1000      | General Fund | 2ANL         | Animal Services | 2FDS          | Field Services | 2131      | Animal Protection | 5001         | Regular wages - full-time    | 806489          | 
| 2016                 | 92          | Animal Services  | 9200            | Animal Services | 1000      | General Fund | 2ANL         | Animal Services | 2FDS          | Field Services | 2131      | Animal Protection | 5002         | Regular wages - part-time    | 17879           | 
| 2016                 | 92          | Animal Services  | 9200            | Animal Services | 1000      | General Fund | 2ANL         | Animal Services | 2FDS          | Field Services | 2131      | Animal Protection | 5005         | Overtime                     | 45664           | 
| 2016                 | 92          | Animal Services  | 9200            | Animal Services | 1000      | General Fund | 2ANL         | Animal Services | 2FDS          | Field Services | 2131      | Animal Protection | 5018         | Holidays worked              | 6506            | 
| 2016                 | 92          | Animal Services  | 9200            | Animal Services | 1000      | General Fund | 2ANL         | Animal Services | 2FDS          | Field Services | 2131      | Animal Protection | 5026         | Stability pay                | 7154            | 
| 2016                 | 92          | Animal Services  | 9200            | Animal Services | 1000      | General Fund | 2ANL         | Animal Services | 2FDS          | Field Services | 2131      | Animal Protection | 5030         | On call hours                | 3470            | 
| 2016                 | 92          | Animal Services  | 9200            | Animal Services | 1000      | General Fund | 2ANL         | Animal Services | 2FDS          | Field Services | 2131      | Animal Protection | 5051         | Personnel savings            | -11386          | 
| 2016                 | 92          | Animal Services  | 9200            | Animal Services | 1000      | General Fund | 2ANL         | Animal Services | 2FDS          | Field Services | 2131      | Animal Protection | 5133         | Phone allowance              | 2280            | 
| 2016                 | 92          | Animal Services  | 9200            | Animal Services | 1000      | General Fund | 2ANL         | Animal Services | 2FDS          | Field Services | 2131      | Animal Protection | 5185         | Insurance-health/life/dental | 295650          | 
| 2016                 | 92          | Animal Services  | 9200            | Animal Services | 1000      | General Fund | 2ANL         | Animal Services | 2FDS          | Field Services | 2131      | Animal Protection | 5190         | FICA tax                     | 51693           | 
```