# 2014 Employee Wage Detail By Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-employee-wage-detail-by-type) |
| Metadata | [Link](https://data.srcity.org/api/views/4xtp-hh3v) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/4xtp-hh3v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/4xtp-hh3v/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | 4xtp-hh3v |
| Name | 2014 Employee Wage Detail By Type |
| Attribution | California State Controllers Office |
| Category | Finances |
| Tags | salary, pay, compensation |
| Created | 2016-02-10T01:04:09Z |
| Publication Date | 2016-02-10T01:14:42Z |
| Rows Updated | 2016-02-10T01:13:34Z |

## Description

Calendar year 2014 City of Santa Rosa employee wage data from the State of CA Controller's Office Government Compensation in California website.

http://publicpay.ca.gov/Reports/Cities/City.aspx?entityid=497&fiscalyear=2014

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type | Render Type |
| ======== | ============== | ============================ | ============================== | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | position                     | Position                       | text      | text        |
| Yes      | series tag     | department                   | Department                     | text      | text        |
| Yes      | numeric metric | total_wages                  | Total Wages                    | money     | money       |
| Yes      | numeric metric | total_retirement_health_cost | Total Retirement & Health Cost | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:4xtp-hh3v d:2016-02-09T17:04:11.000Z t:position="Activity Specialist" t:department="Recreation And Parks" m:total_retirement_health_cost=7 m:total_wages=12

series e:4xtp-hh3v d:2016-02-09T17:04:11.000Z t:position="Activity Specialist" t:department="Recreation And Parks" m:total_retirement_health_cost=133 m:total_wages=706

series e:4xtp-hh3v d:2016-02-09T17:04:11.000Z t:position="Police Technician" t:department="Police Department" m:total_retirement_health_cost=169 m:total_wages=1506
```

## Meta Commands

```ls
entity e:4xtp-hh3v l:"2014 Employee Wage Detail By Type" t:attribution="California State Controllers Office" t:url=https://data.srcity.org/api/views/4xtp-hh3v

property e:4xtp-hh3v t:meta.view v:id=4xtp-hh3v v:category=Finances v:attributionLink="http://publicpay.ca.gov/Reports/Cities/City.aspx?entityid=497&fiscalyear=2014" v:averageRating=0 v:name="2014 Employee Wage Detail By Type" v:attribution="California State Controllers Office"

property e:4xtp-hh3v t:meta.view.owner v:id=xdif-r3mr v:screenName=Admin v:roleName=administrator v:displayName=Admin

property e:4xtp-hh3v t:meta.view.tableauthor v:id=xdif-r3mr v:screenName=Admin v:roleName=administrator v:displayName=Admin
```