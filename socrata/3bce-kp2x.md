# Property and Taxation: Q3 2012 Performance Management Goal Assessment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/property-and-taxation-q3-2012-performance-management-goal-assessment-d6592) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/3bce-kp2x) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3bce-kp2x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/3bce-kp2x/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | 3bce-kp2x |
| Name | Property and Taxation: Q3 2012 Performance Management Goal Assessment |
| Category | Property & Taxation |
| Created | 2012-10-18T03:11:01Z |
| Publication Date | 2014-10-27T16:38:55Z |

## Columns

```ls
| Included | Schema Type | Field Name                                                       | Name                                                                    | Data Type | Render Type |
| ======== | =========== | ================================================================ | ======================================================================= | ========= | =========== |
| Yes      | series tag  | goal_1_ensure_a_fair_accurate_property_valuation_appeals_process | Goal 1: Ensure A Fair & Accurate Property Valuation & Appeals Process * | text      | text        |
| Yes      | series tag  | reporting_office                                                 | Reporting Office                                                        | text      | text        |
| Yes      | series tag  | tax_year_2009                                                    | Tax Year 2009                                                           | text      | text        |
| Yes      | series tag  | tax_year_2011                                                    | Tax Year 2011                                                           | text      | text        |
| Yes      | series tag  | ty2012_ytd                                                       | TY2012 YTD                                                              | text      | text        |
| Yes      | series tag  | ty2012_target                                                    | TY2012 Target                                                           | text      | text        |
| Yes      | series tag  | ty2012_variance                                                  | TY2012 Variance                                                         | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:3bce-kp2x d:2012-01-01T00:00:00.000Z t:goal_1_ensure_a_fair_accurate_property_valuation_appeals_process="# of parcels reassessed" t:ty2012_variance=- t:ty2012_target=TBD t:tax_year_2011=527,490 t:reporting_office=Assessor t:tax_year_2009=869,663 t:ty2012_ytd=875,000 m:row_number.3bce-kp2x=1

series e:3bce-kp2x d:2012-01-01T00:00:00.000Z t:goal_1_ensure_a_fair_accurate_property_valuation_appeals_process="# of property tax exemptions received" t:ty2012_variance=- t:ty2012_target=TBD t:tax_year_2011=1,093,220 t:reporting_office=Assessor t:tax_year_2009=1,101,937 t:ty2012_ytd=1,101,000 m:row_number.3bce-kp2x=2

series e:3bce-kp2x d:2012-01-01T00:00:00.000Z t:goal_1_ensure_a_fair_accurate_property_valuation_appeals_process="# of appeals filed" t:ty2012_variance=- t:ty2012_target=TBD t:tax_year_2011=109,860 t:reporting_office=Assessor t:tax_year_2009=134,975 t:ty2012_ytd=135,000 m:row_number.3bce-kp2x=3
```

## Meta Commands

```ls
metric m:row_number.3bce-kp2x p:long l:"Row Number"

entity e:3bce-kp2x l:"Property and Taxation: Q3 2012 Performance Management Goal Assessment" t:url=https://datacatalog.cookcountyil.gov/api/views/3bce-kp2x

property e:3bce-kp2x t:meta.view d:2017-09-25T07:24:43.855Z v:averageRating=0 v:name="Property and Taxation: Q3 2012 Performance Management Goal Assessment" v:id=3bce-kp2x v:category="Property & Taxation"

property e:3bce-kp2x t:meta.view.license d:2017-09-25T07:24:43.855Z v:name="Public Domain"

property e:3bce-kp2x t:meta.view.owner d:2017-09-25T07:24:43.855Z v:displayName="Cook County Government" v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:id=wyzd-r23j v:screenName="Cook County Government" v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB

property e:3bce-kp2x t:meta.view.tableauthor d:2017-09-25T07:24:43.855Z v:displayName="Cook County Government" v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:id=wyzd-r23j v:screenName="Cook County Government" v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB
```

## Top Records

```ls
| goal_1_ensure_a_fair_accurate_property_valuation_appeals_process                                                         | reporting_office | tax_year_2009 | tax_year_2011 | ty2012_ytd | ty2012_target | ty2012_variance | 
| ======================================================================================================================== | ================ | ============= | ============= | ========== | ============= | =============== | 
| # of parcels reassessed                                                                                                  | Assessor         | 869,663       | 527,490       | 875,000    | TBD           | -               | 
| # of property tax exemptions received                                                                                    | Assessor         | 1,101,937     | 1,093,220     | 1,101,000  | TBD           | -               | 
| # of appeals filed                                                                                                       | Assessor         | 134,975       | 109,860       | 135,000    | TBD           | -               | 
| # of hearings requested                                                                                                  | Board of Review  | 295,108       | 265,152       | 300,000    | TBD           | -               | 
| # of compalints heard                                                                                                    | Board of Review  | 158,740       | 145,630       | 160,000    | TBD           | -               | 
| Goal 2: Ensure Efficient, Timely & Effective Assessment & Billing                                                        |                  |               |               |            |               |                 | 
| Efficient and timely processing results in lower costs to the County and a predictable billing cycle to property owners. |                  |               |               |            |               |                 | 
| Date second instalment tax bills are mailed                                                                              | Countywide       | 11/10/2010    | 6/26/2012     | TBD        | 6/26/2013     | -               | 
| Days to hear and close all appeals                                                                                       | Assessor         | 364           | 193           | 244        | TBD           | -               | 
| Days to hear and close all appeals                                                                                       | Board of Review  | 315           | 225           | 256        | TBD           | -               | 
```