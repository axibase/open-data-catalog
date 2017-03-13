# Budget - FTE

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/budget-fte-ab7fd) |
| Metadata | [Link](https://data.sfgov.org/api/views/4zfx-f2ts) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/4zfx-f2ts/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/4zfx-f2ts/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 4zfx-f2ts |
| Name | Budget - FTE |
| Attribution | SF Controller's Office |
| Category | City Management and Ethics |
| Tags | budget, fte, staffing, sfopenbook, open book, openbook |
| Created | 2014-06-16T21:46:43Z |
| Publication Date | 2016-05-05T20:06:55Z |
| Rows Updated | 2016-08-08T21:09:58Z |

## Description

The San Francisco Controller's Office maintains a database of budgetary staffing data that appears in summarized form in each Annual Salary Ordinance (ASO). This data is presented on the Budget report hosted at http://openbook.sfgov.org, and is also available in this dataset in CSV format. New data is added on an annual basis when the ASO is published for each new fiscal year. Data is available from fiscal year 2010 forward.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | fiscal_year             | Fiscal Year             | number    | number      |
| Yes      | series tag     | related_gov_t_units     | Related Gov't Units     | text      | text        |
| Yes      | series tag     | organization_group_code | Organization Group Code | text      | text        |
| Yes      | series tag     | organization_group      | Organization Group      | text      | text        |
| Yes      | series tag     | department_code         | Department Code         | text      | text        |
| Yes      | series tag     | department              | Department              | text      | text        |
| Yes      | series tag     | program_code            | Program Code            | text      | text        |
| Yes      | series tag     | program                 | Program                 | text      | text        |
| Yes      | series tag     | character_code          | Character Code          | text      | text        |
| Yes      | series tag     | character               | Character               | text      | text        |
| Yes      | series tag     | object_code             | Object Code             | text      | text        |
| Yes      | series tag     | object                  | Object                  | text      | text        |
| Yes      | series tag     | sub_object_code         | Sub-object Code         | text      | text        |
| Yes      | series tag     | sub_object              | Sub-object              | text      | text        |
| Yes      | series tag     | fund_type_code          | Fund Type Code          | text      | text        |
| Yes      | series tag     | fund_type               | Fund Type               | text      | text        |
| Yes      | series tag     | fund_code               | Fund Code               | text      | text        |
| Yes      | series tag     | fund                    | Fund                    | text      | text        |
| Yes      | series tag     | fund_category_code      | Fund Category Code      | text      | text        |
| Yes      | series tag     | fund_category           | Fund Category           | text      | text        |
| Yes      | series tag     | job_family_code         | Job Family Code         | text      | text        |
| Yes      | series tag     | job_family              | Job Family              | text      | text        |
| Yes      | series tag     | job_code                | Job Code                | text      | text        |
| Yes      | series tag     | job                     | Job                     | text      | text        |
| Yes      | numeric metric | fte                     | FTE                     | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4zfx-f2ts d:2015-01-01T00:00:00.000Z t:organization_group="Public Protection" t:fund_code=1GAGF t:fund_type="General Fund" t:program_code=ACB t:department=Police t:job_family=Management t:job_family_code=0900 t:sub_object=Misc-Regular t:job="Manager I" t:object="Permanent Salaries-Misc" t:object_code=001 t:fund_type_code=1G t:character=Salaries t:job_code=0922 t:character_code=001 t:fund_category_code=1 t:program=Investigations t:sub_object_code=00101 t:fund_category=Operating t:department_code=POL t:fund="General Fund" t:organization_group_code=01 t:related_gov_t_units=No m:fte=1

series e:4zfx-f2ts d:2017-01-01T00:00:00.000Z t:organization_group="Culture & Recreation" t:fund_code=1GAGF t:fund_type="General Fund" t:program_code=ECU t:department="Recreation and Park Commission" t:job_family=Management t:job_family_code=0900 t:sub_object=Misc-Regular t:job="Manager I" t:object="Permanent Salaries-Misc" t:object_code=001 t:fund_type_code=1G t:character=Salaries t:job_code=0922 t:character_code=001 t:fund_category_code=1 t:program=Recreation t:sub_object_code=00101 t:fund_category=Operating t:department_code=REC t:fund="General Fund" t:organization_group_code=05 t:related_gov_t_units=No m:fte=1

series e:4zfx-f2ts d:2012-01-01T00:00:00.000Z t:organization_group="Public Works, Transportation & Commerce" t:fund_code=5TAAA t:fund_type="PUC Hetch Hetchy Funds" t:program_code=BDA t:department="PUC Hetch Hetchy" t:job_family="Budget, Admn & Stats Analysis" t:job_family_code=1800 t:sub_object=Misc-Regular t:job="Senior Administrative Analyst" t:object="Permanent Salaries-Misc" t:object_code=001 t:fund_type_code=5T t:character=Salaries t:job_code=1823 t:character_code=001 t:fund_category_code=1 t:program=Administration t:sub_object_code=00101 t:fund_category=Operating t:department_code=HHP t:fund="Hetch Hetchy Operating Fund" t:organization_group_code=02 t:related_gov_t_units=No m:fte=1
```

## Meta Commands

```ls
metric m:fte l:FTE d:"Staffing level is represented by ""Full Time Equivalent (FTE)"". One FTE equals one or more employees who together work 40 hours per week. For instance, an employee who works 40 hours per week is counted as one FTE, and two part-time employees who each work 20 hours per week are also counted as one FTE. Overtime hours are excluded from this calculation. FTE is relative to the time period. Annual FTEs are based on 2080, 2088 or 2096 hours per year depending on how week days and leap day affect a particular year." t:dataTypeName=number

entity e:4zfx-f2ts l:"Budget - FTE" t:attribution="SF Controller's Office" t:url=https://data.sfgov.org/api/views/4zfx-f2ts

property e:4zfx-f2ts t:meta.view v:id=4zfx-f2ts v:category="City Management and Ethics" v:attributionLink=http://openbook.sfgov.org v:averageRating=0 v:name="Budget - FTE" v:attribution="SF Controller's Office"

property e:4zfx-f2ts t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:4zfx-f2ts t:meta.view.owner v:id=9ufn-6bwh v:screenName="Jeff Pera" v:roleName=editor v:displayName="Jeff Pera"

property e:4zfx-f2ts t:meta.view.tableauthor v:id=9ufn-6bwh v:screenName="Jeff Pera" v:roleName=editor v:displayName="Jeff Pera"
```