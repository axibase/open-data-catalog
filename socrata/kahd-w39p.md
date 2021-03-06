# Campaign Finance - Status of Voluntary Expenditure Ceiling (VECs) in November 5, 2013 Election

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-status-of-voluntary-expenditure-ceiling-vecs-in-november-5-2013-election-6e5b2) |
| Metadata | [Link](https://data.sfgov.org/api/views/kahd-w39p) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/kahd-w39p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/kahd-w39p/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | kahd-w39p |
| Name | Campaign Finance - Status of Voluntary Expenditure Ceiling (VECs) in November 5, 2013 Election |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | voluntary, expenditure, ceiling, campaign, finance, ethics, vec, november 5, 2013, election |
| Created | 2013-06-03T17:17:10Z |
| Publication Date | 2013-06-03T17:19:08Z |

## Description

Under S.F. Campaign and Governmental Conduct Code 1.128, a candidate who wishes to accept the voluntary expenditure ceiling must file Form SFEC-128 no later than the August 9, 2013 deadline for filing nomination papers. In a race where at least one candidate has accepted the VEC, all candidates running for office in the same race must file Form SFEC 134(b) within 24 hours of receiving contributions, making expenditures, or having funds that exceed 100 percent of the applicable VEC. In addition, any person other than a candidate committee who makes or incurs expenditures for the purpose of distributing independent expenditures, electioneering communications, or member communications that clearly identify any candidate that equals or exceeds $5,000 per candidate, must within 24 hours of each time it reaches the $5,000 threshold file a Third Party Disclosure Form.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | city_elective_office | City Elective Office | text      | text        |
| Yes      | numeric metric | amount_of_vec        | Amount of VEC        | money     | money       |
| Yes      | series tag     | status_of_vec        | Status of VEC        | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:kahd-w39p d:2013-01-01T00:00:00.000Z t:status_of_vec="The ceiling is not in place." t:city_elective_office=Treasurer m:amount_of_vec=243000

series e:kahd-w39p d:2013-01-01T00:00:00.000Z t:status_of_vec="The ceiling is not in place." t:city_elective_office="City Attorney" m:amount_of_vec=243000

series e:kahd-w39p d:2013-01-01T00:00:00.000Z t:status_of_vec="The ceiling is not in place." t:city_elective_office=Assessor m:amount_of_vec=243000
```

## Meta Commands

```ls
metric m:amount_of_vec p:integer l:"Amount of VEC" t:dataTypeName=money

entity e:kahd-w39p l:"Campaign Finance - Status of Voluntary Expenditure Ceiling (VECs) in November 5, 2013 Election" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/kahd-w39p

property e:kahd-w39p t:meta.view v:id=kahd-w39p v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Finance - Status of Voluntary Expenditure Ceiling (VECs) in November 5, 2013 Election" v:attribution="San Francisco Ethics Commission"

property e:kahd-w39p t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:kahd-w39p t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:kahd-w39p t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| city_elective_office | amount_of_vec | status_of_vec                | 
| ==================== | ============= | ============================ | 
| Treasurer            | 243000        | The ceiling is not in place. | 
| City Attorney        | 243000        | The ceiling is not in place. | 
| Assessor             | 243000        | The ceiling is not in place. | 
```