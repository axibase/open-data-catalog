# Jackson Capital Budget Project Phases List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jackson-capital-budget-project-phases-list) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/7f3h-pm6e) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/7f3h-pm6e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/7f3h-pm6e/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | 7f3h-pm6e |
| Name | Jackson Capital Budget Project Phases List |
| Category | Public Works |
| Created | 2016-12-22T17:10:32Z |
| Publication Date | 2016-12-22T17:21:53Z |

## Description

Budget data that describes the Projects and Phases of the Infrastructure Master Plan.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | phase_step_name        | Phase Step Name        | text      | text        |
| Yes      | series tag  | phase_step_number      | Phase Step Number      | text      | number      |
| Yes      | series tag  | phase_step_description | Phase Step Description | text      | text        |
| Yes      | series tag  | phase_type             | Phase Type             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7f3h-pm6e d:2016-12-22T17:21:35.000Z t:phase_step_name=Planning t:phase_type=IMP t:phase_step_description="Identify the needs, scope and goals of the project." t:phase_step_number=1 m:row_number.7f3h-pm6e=1

series e:7f3h-pm6e d:2016-12-22T17:21:37.000Z t:phase_step_name=Design t:phase_type=IMP t:phase_step_description="Architects and engineers work from the defined scope and budget to develop the design, and produce construction drawings, etc." t:phase_step_number=2 m:row_number.7f3h-pm6e=2

series e:7f3h-pm6e d:2016-12-22T17:21:39.000Z t:phase_step_name="RoW Acquisition" t:phase_type=IMP t:phase_step_description="If Right of Way acquisition is required, the proper documentation is put forth during this time." t:phase_step_number=3 m:row_number.7f3h-pm6e=3
```

## Meta Commands

```ls
metric m:row_number.7f3h-pm6e p:long l:"Row Number"

entity e:7f3h-pm6e l:"Jackson Capital Budget Project Phases List" t:url=https://data.jacksonms.gov/api/views/7f3h-pm6e

property e:7f3h-pm6e t:meta.view d:2017-09-25T07:31:07.614Z v:averageRating=0 v:name="Jackson Capital Budget Project Phases List" v:id=7f3h-pm6e v:category="Public Works"

property e:7f3h-pm6e t:meta.view.owner d:2017-09-25T07:31:07.614Z v:displayName="Justin Bruce" v:lastNotificationSeenAt=1492180672 v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:id=6ngd-c2u2 v:screenName="Justin Bruce" v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB

property e:7f3h-pm6e t:meta.view.tableauthor d:2017-09-25T07:31:07.614Z v:displayName="Justin Bruce" v:lastNotificationSeenAt=1492180672 v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:id=6ngd-c2u2 v:screenName="Justin Bruce" v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB
```

## Top Records

```ls
| :updated_at | phase_step_name | phase_step_number | phase_step_description                                                                                                         | phase_type | 
| =========== | =============== | ================= | ============================================================================================================================== | ========== | 
| 1482427295  | Planning        | 1                 | Identify the needs, scope and goals of the project.                                                                            | IMP        | 
| 1482427297  | Design          | 2                 | Architects and engineers work from the defined scope and budget to develop the design, and produce construction drawings, etc. | IMP        | 
| 1482427299  | RoW Acquisition | 3                 | If Right of Way acquisition is required, the proper documentation is put forth during this time.                               | IMP        | 
| 1482427301  | Construction    | 4                 | Contractors currently working from the instructions contained in the design documents.                                         | IMP        | 
| 1482427304  | Completed       | 5                 | All project activities have been completed and paid for.                                                                       | IMP        | 
```