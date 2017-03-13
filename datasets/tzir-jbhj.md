# Department Open Data Inventory and Plan Status

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-open-data-inventory-and-plan-status) |
| Metadata | [Link](https://data.sfgov.org/api/views/tzir-jbhj) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/tzir-jbhj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/tzir-jbhj/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | tzir-jbhj |
| Name | Department Open Data Inventory and Plan Status |
| Category | City Management and Ethics |
| Tags | inventory, publishing plans, open data program |
| Created | 2015-07-13T18:57:52Z |
| Publication Date | 2017-02-14T19:27:31Z |
| Rows Updated | 2017-02-14T19:27:15Z |

## Description

This dataset tracks the status of departments as they move through the inventory process. The dataset will be maintained until all departments are complete, at which point tracking of departmental publishing can be done in the companion dataset inventory.

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | department_code                 | Department Code                 | text      | text        |
| Yes      | series tag     | department_or_division          | Department or Division          | text      | text        |
| Yes      | series tag     | inventory_status                | Inventory Status                | text      | text        |
| Yes      | series tag     | publishing_plan_status          | Publishing Plan Status          | text      | text        |
| Yes      | numeric metric | target_december_2015            | Target December 2015            | number    | number      |
| Yes      | numeric metric | published_through_december_2015 | Published through December 2015 | number    | number      |
| Yes      | numeric metric | target_june_2016                | Target June 2016                | number    | number      |
| Yes      | numeric metric | published_through_june_2016     | Published Through June 2016     | number    | number      |
| Yes      | numeric metric | target_december_2016            | Target December 2016            | number    | number      |
| Yes      | numeric metric | published_through_december_2016 | Published through December 2016 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:tzir-jbhj d:2017-02-14T19:27:08.000Z t:inventory_status=Complete t:publishing_plan_status=Complete t:department_or_division=311 t:department_code=311 m:target_june_2016=0 m:published_through_december_2015=0 m:published_through_december_2016=0 m:published_through_june_2016=0 m:target_december_2015=0 m:target_december_2016=0

series e:tzir-jbhj d:2017-02-14T19:27:08.000Z t:inventory_status=Incomplete t:publishing_plan_status=Incomplete t:department_or_division="Academy of Sciences" t:department_code=SCI m:target_june_2016=0 m:published_through_december_2015=0 m:published_through_december_2016=0 m:published_through_june_2016=0 m:target_december_2015=0 m:target_december_2016=0

series e:tzir-jbhj d:2017-02-14T19:27:08.000Z t:inventory_status=Complete t:publishing_plan_status=Incomplete t:department_or_division="Adult Probation" t:department_code=ADP m:target_june_2016=2 m:published_through_december_2015=0 m:published_through_december_2016=0 m:published_through_june_2016=0 m:target_december_2015=2 m:target_december_2016=0
```

## Meta Commands

```ls
metric m:target_december_2015 p:integer l:"Target December 2015" d:"The department target set for publishing through end of 2015." t:dataTypeName=number

metric m:published_through_december_2015 p:integer l:"Published through December 2015" d:"Number of datasets published through the end of 2015. This is variable until the end of the publishing period." t:dataTypeName=number

metric m:target_june_2016 p:integer l:"Target June 2016" d:"The department target set for publishing through end of June 2016" t:dataTypeName=number

metric m:published_through_june_2016 p:integer l:"Published Through June 2016" d:"Number of datasets published through the end of June 2016. This is variable until the end of the publishing period." t:dataTypeName=number

metric m:target_december_2016 p:integer l:"Target December 2016" d:"The department target set for publishing through end of 2016." t:dataTypeName=number

metric m:published_through_december_2016 p:integer l:"Published through December 2016" d:"Number of datasets published through the end of 2016. This is variable until the end of the publishing period." t:dataTypeName=number

entity e:tzir-jbhj l:"Department Open Data Inventory and Plan Status" t:url=https://data.sfgov.org/api/views/tzir-jbhj

property e:tzir-jbhj t:meta.view v:id=tzir-jbhj v:category="City Management and Ethics" v:averageRating=0 v:name="Department Open Data Inventory and Plan Status"

property e:tzir-jbhj t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:tzir-jbhj t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData

property e:tzir-jbhj t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```