# Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/contracts-ous-capital-construction-retainer-program-csr-supplements-fiscal-year-2012-05ea1) |
| Metadata | [Link](https://data.oregon.gov/api/views/uyku-r7g5) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/uyku-r7g5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/uyku-r7g5/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | uyku-r7g5 |
| Name | Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012 |
| Category | Revenue & Expense |
| Created | 2012-12-18T17:02:49Z |
| Publication Date | 2012-12-18T17:03:30Z |
| Rows Updated | 2012-12-18T17:02:53Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | supplement_number   | Supplement Number   | text      | text        |
| Yes      | series tag     | project             | Project             | text      | text        |
| Yes      | series tag     | organization        | Organization        | text      | text        |
| Yes      | series tag     | contractor          | Contractor          | text      | text        |
| Yes      | series tag     | mwesb               | MWESB               | text      | text        |
| Yes      | series tag     | retainer_period     | Retainer Period     | text      | text        |
| Yes      | series tag     | issue_date          | Issue Date          | text      | text        |
| Yes      | numeric metric | price               | Price               | money     | money       |
| Yes      | series tag     | compensation_method | Compensation Method | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uyku-r7g5 d:2012-12-18T09:02:51.000Z t:compensation_method=Fixed t:retainer_period="June 2011 - June 2012" t:project="CARSON HALL PLASTER REPAIR PROJECT" t:organization="University of Oregon" t:contractor="Oregon Ceiling & Acoustics, LLC" t:supplement_number=UO-390-C-11-5 t:issue_date=7/1/11 t:mwesb="MBE, ESB" m:price=46200

series e:uyku-r7g5 d:2012-12-18T09:02:51.000Z t:compensation_method=Fixed t:retainer_period="June 2011 - June 2012" t:project="Heritage Hall Door Replacement" t:organization="Western Oregon University" t:contractor="Robert Gray Partners, Inc." t:supplement_number=WOU-409-C-11-2 t:issue_date=7/5/11 t:mwesb=No m:price=54828

series e:uyku-r7g5 d:2012-12-18T09:02:51.000Z t:compensation_method=Fixed t:retainer_period=2010-2012 t:project="Residence Hall Infrastructure Upgrade" t:organization="Oregon State University" t:contractor="Jimco Electrical Contracting, Inc." t:supplement_number=OSU-16-C-10-151 t:issue_date=7/5/11 t:mwesb=No m:price=207750
```

## Meta Commands

```ls
entity e:uyku-r7g5 l:"Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012" t:url=https://data.oregon.gov/api/views/uyku-r7g5

property e:uyku-r7g5 t:meta.view v:id=uyku-r7g5 v:category="Revenue & Expense" v:averageRating=0 v:name="Contracts: OUS: Capital Construction Retainer Program: CSR Supplements: Fiscal Year 2012"

property e:uyku-r7g5 t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:uyku-r7g5 t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```