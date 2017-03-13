# Board of Regents' Vendor Payments By Institution, Fiscal Year And Vendor

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-regents-vendor-payments-by-institution-fiscal-year-and-vendor) |
| Metadata | [Link](https://data.iowa.gov/api/views/y3id-d73d) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/y3id-d73d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/y3id-d73d/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | y3id-d73d |
| Name | Board of Regents' Vendor Payments By Institution, Fiscal Year And Vendor |
| Attribution | Iowa Board of Regents |
| Category | Education |
| Tags | vendor, payments, expenditures |
| Created | 2014-12-23T16:26:41Z |
| Publication Date | 2016-08-30T20:02:57Z |
| Rows Updated | 2016-08-30T19:59:22Z |

## Description

The dataset provides aggregate payments made to vendors by institution and fiscal year starting with FY 2012.  Payments made by the Board of Regents are assigned to fiscal years that run from July 1 to the following June 30, and are numbered for the calendar year in which they end (e.g. FY 2014 is July 1, 2013 ? June 30, 2014).

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | numeric metric | bfy         | BFY         | number    | number      |
| Yes      | series tag     | institution | Institution | text      | text        |
| Yes      | series tag     | vendor_name | Vendor Name | text      | text        |
| Yes      | numeric metric | amount      | Amount      | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:y3id-d73d d:2014-12-23T08:26:44.000Z t:vendor_name="Aaron & Midori Gingerich" t:institution="IA Braille and Sight Saving School" m:amount=100 m:bfy=2012

series e:y3id-d73d d:2014-12-23T08:26:44.000Z t:vendor_name="Abby Smith" t:institution="IA Braille and Sight Saving School" m:amount=450 m:bfy=2012

series e:y3id-d73d d:2014-12-23T08:26:44.000Z t:vendor_name="Access Systems" t:institution="IA Braille and Sight Saving School" m:amount=165 m:bfy=2012
```

## Meta Commands

```ls
metric m:bfy p:integer l:BFY d:"Fiscal year payment was assigned to. As the State of Iowa operates on modified cash basis of budgeting, the fiscal year includes a hold-over period for payments made after year end for good and services received on or before June 30." t:dataTypeName=number

entity e:y3id-d73d l:"Board of Regents' Vendor Payments By Institution, Fiscal Year And Vendor" t:attribution="Iowa Board of Regents" t:url=https://data.iowa.gov/api/views/y3id-d73d

property e:y3id-d73d t:meta.view v:id=y3id-d73d v:category=Education v:averageRating=0 v:name="Board of Regents' Vendor Payments By Institution, Fiscal Year And Vendor" v:attribution="Iowa Board of Regents"

property e:y3id-d73d t:meta.view.license v:name="Public Domain"

property e:y3id-d73d t:meta.view.owner v:id=ym7w-2hjx v:profileImageUrlMedium=/api/users/ym7w-2hjx/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym7w-2hjx/profile_images/LARGE v:screenName="Iowa Board of Regents" v:profileImageUrlSmall=/api/users/ym7w-2hjx/profile_images/TINY v:roleName=editor v:displayName="Iowa Board of Regents"

property e:y3id-d73d t:meta.view.tableauthor v:id=ym7w-2hjx v:profileImageUrlMedium=/api/users/ym7w-2hjx/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym7w-2hjx/profile_images/LARGE v:screenName="Iowa Board of Regents" v:profileImageUrlSmall=/api/users/ym7w-2hjx/profile_images/TINY v:roleName=editor v:displayName="Iowa Board of Regents"
```