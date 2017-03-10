# Salaries of State Agencies FY 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/salaries-of-state-agencies-fy-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/25mj-qtvj) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/25mj-qtvj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/25mj-qtvj/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | 25mj-qtvj |
| Name | Salaries of State Agencies FY 2016 |
| Category | Revenue & Expense |
| Tags | 2016, salaries, state employees, salaries of state employees, wages, salaries 2016 |
| Created | 2016-11-24T08:23:20Z |
| Publication Date | 2016-11-24T08:30:31Z |
| Rows Updated | 2016-11-24T08:24:02Z |

## Description

Salaries of state work force sorted by agency - 2016. For more information go to http://www.oregon.gov/transparency/Pages/state_workforce.aspx

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | fiscal_year    | FISCAL YEAR    | number    | number      |
| Yes      | numeric metric | agency         | AGENCY #       | number    | text        |
| Yes      | series tag     | agency_title   | AGENCY TITLE   | text      | text        |
| Yes      | series tag     | classification | CLASSIFICATION | text      | text        |
| Yes      | series tag     | service_type   | SERVICE TYPE   | text      | text        |
| Yes      | series tag     | full_part_time | FULL/PART TIME | text      | text        |
| Yes      | numeric metric | annual_salary  | ANNUAL SALARY  | money     | money       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:25mj-qtvj d:2016-01-01T00:00:00.000Z t:service_type="AGENCY HEAD" t:classification="PRINCIPAL EXECUTIVE/MANAGER D" t:agency_title="ACCOUNTANCY, OREGON BOARD OF" t:full_part_time=FULL-TIME m:annual_salary=96036 m:agency=12000

series e:25mj-qtvj d:2016-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="OFFICE SPECIALIST 1" t:agency_title="ACCOUNTANCY, OREGON BOARD OF" t:full_part_time=FULL-TIME m:annual_salary=38712 m:agency=12000

series e:25mj-qtvj d:2016-01-01T00:00:00.000Z t:service_type=UNREPRESENTED t:classification="ADMINISTRATIVE SPECIALIST 1" t:agency_title="ACCOUNTANCY, OREGON BOARD OF" t:full_part_time=FULL-TIME m:annual_salary=35268 m:agency=12000
```

## Meta Commands

```ls
metric m:agency p:integer l:"AGENCY #" t:dataTypeName=number

entity e:25mj-qtvj l:"Salaries of State Agencies FY 2016" t:url=https://data.oregon.gov/api/views/25mj-qtvj

property e:25mj-qtvj t:meta.view v:id=25mj-qtvj v:category="Revenue & Expense" v:averageRating=0 v:name="Salaries of State Agencies FY 2016"

property e:25mj-qtvj t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:25mj-qtvj t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```