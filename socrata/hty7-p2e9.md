# 2014 Elections - Contributions Received (more than $100) by Contibutor Type

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-elections-contributions-received-more-than-100-by-contibutor-type-99b7e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/hty7-p2e9) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/hty7-p2e9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/hty7-p2e9/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | hty7-p2e9 |
| Name | 2014 Elections - Contributions Received (more than $100) by Contibutor Type |
| Category | Community |
| Tags | cmapaign spending commission |
| Created | 2015-01-12T21:24:48Z |
| Publication Date | 2015-01-12T21:45:56Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| Yes      | series tag     | contributor_type                           | Contributor Type                           | text      | text        |
| Yes      | numeric metric | count                                      | Count                                      | number    | number      |
| Yes      | numeric metric | percentage_of_total_count                  | Percentage of Total Count                  | percent   | percent     |
| Yes      | numeric metric | total_contribution_received                | Total Contribution Received                | money     | money       |
| Yes      | numeric metric | percentage_of_total_contributions_received | Percentage of Total Contributions Received | percent   | percent     |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hty7-p2e9 d:2014-01-01T00:00:00.000Z t:contributor_type="Candidate Committee" m:percentage_of_total_contributions_received=0.34 m:count=128 m:percentage_of_total_count=0.64 m:total_contribution_received=39575.16

series e:hty7-p2e9 d:2014-01-01T00:00:00.000Z t:contributor_type="Immediate Family" m:percentage_of_total_contributions_received=2.06 m:count=310 m:percentage_of_total_count=1.54 m:total_contribution_received=238752.53

series e:hty7-p2e9 d:2014-01-01T00:00:00.000Z t:contributor_type=Individual m:percentage_of_total_contributions_received=68.21 m:count=14966 m:percentage_of_total_count=74.57 m:total_contribution_received=7912040.29
```

## Meta Commands

```ls
metric m:count p:integer l:Count t:dataTypeName=number

metric m:percentage_of_total_count p:float l:"Percentage of Total Count" t:dataTypeName=percent

metric m:total_contribution_received p:double l:"Total Contribution Received" t:dataTypeName=money

metric m:percentage_of_total_contributions_received p:float l:"Percentage of Total Contributions Received" t:dataTypeName=percent

entity e:hty7-p2e9 l:"2014 Elections - Contributions Received (more than $100) by Contibutor Type" t:url=https://data.hawaii.gov/api/views/hty7-p2e9

property e:hty7-p2e9 t:meta.view d:2017-09-25T07:31:40.976Z v:averageRating=0 v:name="2014 Elections - Contributions Received (more than $100) by Contibutor Type" v:id=hty7-p2e9 v:category=Community

property e:hty7-p2e9 t:meta.view.license d:2017-09-25T07:31:40.976Z v:name="Public Domain"

property e:hty7-p2e9 t:meta.view.owner d:2017-09-25T07:31:40.976Z v:displayName="Hawaii Campaign Spending Commission" v:lastNotificationSeenAt=1505521909 v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:id=g6c2-gabj v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB

property e:hty7-p2e9 t:meta.view.tableauthor d:2017-09-25T07:31:40.976Z v:displayName="Hawaii Campaign Spending Commission" v:lastNotificationSeenAt=1505521909 v:profileImageUrlLarge=/api/users/g6c2-gabj/profile_images/LARGE v:roleName=editor v:profileImageUrlSmall=/api/users/g6c2-gabj/profile_images/TINY v:id=g6c2-gabj v:screenName="Hawaii Campaign Spending Commission" v:profileImageUrlMedium=/api/users/g6c2-gabj/profile_images/THUMB
```

## Top Records

```ls
| contributor_type       | count | percentage_of_total_count | total_contribution_received | percentage_of_total_contributions_received | 
| ====================== | ===== | ========================= | =========================== | ========================================== | 
| Candidate Committee    | 128   | 0.64                      | 39575.16                    | 0.34                                       | 
| Immediate Family       | 310   | 1.54                      | 238752.53                   | 2.06                                       | 
| Individual             | 14966 | 74.57                     | 7912040.29                  | 68.21                                      | 
| Noncandidate Committee | 1220  | 6.08                      | 867293.57                   | 7.48                                       | 
| Other Entity           | 3414  | 17.01                     | 2522529.24                  | 21.75                                      | 
| Political Party        | 33    | 0.16                      | 19000                       | 0.16                                       | 
```