# American Recovery And Reinvestment Act Of 2009 ( ARRA)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/american-recovery-and-reinvestment-act-of-2009-arra) |
| Metadata | [Link](https://data.ct.gov/api/views/eugj-j27t) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/eugj-j27t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/eugj-j27t/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | eugj-j27t |
| Name | American Recovery And Reinvestment Act Of 2009 ( ARRA) |
| Category | Government |
| Tags | arra, opm |
| Created | 2014-06-26T14:59:44Z |
| Publication Date | 2014-06-26T15:57:24Z |
| Rows Updated | 2014-06-26T14:59:52Z |

## Description

Approximately $4.3 million of federal funds was distributed to 159 police departments/municipalities with the primary purpose to assist towns with participating in the American Recovery and Reinvestment Act of 2009 (ARRA) distribution of criminal justice grant funds.  Data fields include: (1) Town Name; (2) Total Award; (3) Total Expenditures; and (4) Summary description of goods and services procured.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | town_name        | Town_Name        | text      | text        |
| Yes      | series tag     | grant_number     | Grant_Number     | text      | text        |
| Yes      | numeric metric | fed_grant_award  | Fed_Grant_Award  | money     | money       |
| Yes      | numeric metric | tot_fed_expended | Tot_Fed_Expended | money     | money       |
| Yes      | series tag     | project_summary  | PROJECT_SUMMARY  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:eugj-j27t d:2014-06-26T07:59:48.000Z t:town_name=Andover t:grant_number=09RECJAGLO7511 t:project_summary="To enhance community safety and quality of life by enforcing Connecticut motor vehicle laws through special overtime." m:fed_grant_award=9100 m:tot_fed_expended=8842.42

series e:eugj-j27t d:2014-06-26T07:59:48.000Z t:town_name=Ansonia t:grant_number=09RECJAGLO7512 t:project_summary="To increase traffic safety by enforcing speeding laws and identify and address quality of life issues by means of plain cothes officers issigned to the Anti-Crime Unit." m:fed_grant_award=30000 m:tot_fed_expended=30000

series e:eugj-j27t d:2014-06-26T07:59:48.000Z t:town_name=Avon t:grant_number=09RECJAGLO7514 t:project_summary="To purchase Automatic External Defibillators (AED) and radar and laser units to be used in speed enforcement." m:fed_grant_award=30000 m:tot_fed_expended=30000
```

## Meta Commands

```ls
entity e:eugj-j27t l:"American Recovery And Reinvestment Act Of 2009 ( ARRA)" t:url=https://data.ct.gov/api/views/eugj-j27t

property e:eugj-j27t t:meta.view v:id=eugj-j27t v:category=Government v:averageRating=0 v:name="American Recovery And Reinvestment Act Of 2009 ( ARRA)"

property e:eugj-j27t t:meta.view.owner v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"

property e:eugj-j27t t:meta.view.tableauthor v:id=6ypf-grnx v:screenName="Jamie Gamble" v:roleName=editor v:displayName="Jamie Gamble"
```