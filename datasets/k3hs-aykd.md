# City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-seattle-wages-comparison-by-gender-discretionary-pay-titles-by-department-eafb4) |
| Metadata | [Link](https://data.seattle.gov/api/views/k3hs-aykd) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/k3hs-aykd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/k3hs-aykd/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | k3hs-aykd |
| Name | City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department |
| Category | City Business |
| Tags | wages, salary, salaries, job, classifications, government, gender, comparison by gender, gender wage study |
| Created | 2013-07-16T20:42:14Z |
| Publication Date | 2013-07-16T20:48:20Z |
| Rows Updated | 2013-07-16T20:42:29Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| No       | time           | :updated_at                                | updated_at                                 | meta_data | meta_data   |
| Yes      | series tag     | department                                 | DEPARTMENT                                 | text      | text        |
| Yes      | series tag     | descr                                      | DESCR                                      | text      | text        |
| Yes      | series tag     | gender_descr                               | GENDER DESCR                               | text      | text        |
| Yes      | numeric metric | admin_support_ee                           | Admin Support # EE                         | number    | number      |
| Yes      | numeric metric | admin_support_gender                       | Admin Support % Gender                     | percent   | percent     |
| Yes      | numeric metric | admin_support_avg_hrly                     | Admin Support Avg Hrly                     | number    | number      |
| Yes      | numeric metric | admin_support_avg_yrs_in_current_job       | Admin Support Avg Yrs in Current Job       | number    | number      |
| Yes      | numeric metric | officials_admin_ee                         | Officials/Admin # EE                       | number    | number      |
| Yes      | numeric metric | officials_admin_gender                     | Officials/Admin % Gender                   | percent   | percent     |
| Yes      | numeric metric | officials_admin_avg_hrly                   | Officials/Admin Avg Hrly                   | number    | number      |
| Yes      | numeric metric | officials_admin_avg_yrs_in_current_job     | Officials/Admin Avg Yrs in Current Job     | number    | number      |
| Yes      | numeric metric | para_professionals_ee                      | Para-Professionals # EE                    | number    | number      |
| Yes      | numeric metric | para_professionals_gender                  | Para-Professionals % Gender                | percent   | percent     |
| Yes      | numeric metric | para_professionals_avg_hrly                | Para-Professionals Avg Hrly                | number    | number      |
| Yes      | numeric metric | para_professionals_avg_yrs_in_current_job  | Para-Professionals Avg Yrs in Current Job  | number    | number      |
| Yes      | numeric metric | professionals_ee                           | Professionals # EE                         | number    | number      |
| Yes      | numeric metric | professionals_gender                       | Professionals % Gender                     | percent   | percent     |
| Yes      | numeric metric | professionals_avg_hrly                     | Professionals Avg Hrly                     | number    | number      |
| Yes      | numeric metric | professionals_avg_yrs_in_current_job       | Professionals Avg Yrs in Current Job       | number    | number      |
| Yes      | numeric metric | protected_services_ee                      | Protected Services # EE                    | number    | number      |
| Yes      | numeric metric | protected_services_gender                  | Protected Services % Gender                | percent   | percent     |
| Yes      | numeric metric | protected_services_avg_hrly                | Protected Services Avg Hrly                | number    | number      |
| Yes      | numeric metric | protected_services_avg_yrs_in_current_job  | Protected Services Avg Yrs in Current Job  | number    | number      |
| Yes      | numeric metric | service_maintenance_ee                     | Service/Maintenance # EE                   | number    | number      |
| Yes      | numeric metric | service_maintenance_gender                 | Service/Maintenance % Gender               | percent   | percent     |
| Yes      | numeric metric | service_maintenance_avg_hrly               | Service/Maintenance Avg Hrly               | number    | number      |
| Yes      | numeric metric | service_maintenance_avg_yrs_in_current_job | Service/Maintenance Avg Yrs in Current Job | number    | number      |
| Yes      | numeric metric | skilled_craft_ee                           | Skilled Craft # EE                         | number    | number      |
| Yes      | numeric metric | skilled_craft_gender                       | Skilled Craft % Gender                     | percent   | percent     |
| Yes      | numeric metric | skilled_craft_avg_hrly                     | Skilled Craft Avg Hrly                     | number    | number      |
| Yes      | numeric metric | skilled_craft_avg_yrs_in_current_job       | Skilled Craft Avg Yrs in Current Job       | number    | number      |
| Yes      | numeric metric | technicians_ee                             | Technicians # EE                           | number    | number      |
| Yes      | numeric metric | technicians_gender                         | Technicians % Gender                       | percent   | percent     |
| Yes      | numeric metric | technicians_avg_hrly                       | Technicians Avg Hrly                       | number    | number      |
| Yes      | numeric metric | technicians_avg_yrs_in_current_job         | Technicians Avg Yrs in Current Job         | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:k3hs-aykd d:2013-07-16T13:42:18.000Z t:gender_descr=Female t:department="Arts and Cultural Affairs" m:professionals_avg_hrly=35 m:service_maintenance_ee=1 m:technicians_gender=0 m:protected_services_ee=0 m:admin_support_avg_hrly=26.53 m:service_maintenance_avg_hrly=27.78 m:professionals_gender=79 m:service_maintenance_gender=33 m:technicians_ee=0 m:professionals_ee=15 m:skilled_craft_ee=0 m:para_professionals_ee=0 m:officials_admin_avg_hrly=49.97 m:officials_admin_ee=2 m:officials_admin_gender=67 m:admin_support_ee=2 m:admin_support_gender=100

series e:k3hs-aykd d:2013-07-16T13:42:18.000Z t:gender_descr=Male t:department="Arts and Cultural Affairs" m:professionals_avg_hrly=32.64 m:service_maintenance_ee=2 m:technicians_gender=100 m:protected_services_ee=0 m:service_maintenance_avg_hrly=20.73 m:professionals_gender=21 m:service_maintenance_gender=67 m:technicians_ee=1 m:professionals_ee=4 m:skilled_craft_ee=0 m:technicians_avg_hrly=29.04 m:para_professionals_ee=0 m:officials_admin_avg_hrly=51.95 m:officials_admin_ee=1 m:officials_admin_gender=33 m:admin_support_ee=0 m:admin_support_gender=0

series e:k3hs-aykd d:2013-07-16T13:42:18.000Z t:department="Arts and Cultural Affairs" t:descr="Total Employees" m:technicians_ee=1 m:professionals_ee=19 m:service_maintenance_ee=3 m:officials_admin_ee=3 m:admin_support_ee=2
```

## Meta Commands

```ls
metric m:admin_support_ee p:integer l:"Admin Support # EE" t:dataTypeName=number

metric m:admin_support_avg_hrly l:"Admin Support Avg Hrly" t:dataTypeName=number

metric m:admin_support_avg_yrs_in_current_job l:"Admin Support Avg Yrs in Current Job" t:dataTypeName=number

metric m:officials_admin_ee p:integer l:"Officials/Admin # EE" t:dataTypeName=number

metric m:officials_admin_avg_hrly l:"Officials/Admin Avg Hrly" t:dataTypeName=number

metric m:officials_admin_avg_yrs_in_current_job l:"Officials/Admin Avg Yrs in Current Job" t:dataTypeName=number

metric m:para_professionals_ee p:integer l:"Para-Professionals # EE" t:dataTypeName=number

metric m:para_professionals_avg_hrly l:"Para-Professionals Avg Hrly" t:dataTypeName=number

metric m:para_professionals_avg_yrs_in_current_job l:"Para-Professionals Avg Yrs in Current Job" t:dataTypeName=number

metric m:professionals_ee p:integer l:"Professionals # EE" t:dataTypeName=number

metric m:professionals_avg_hrly l:"Professionals Avg Hrly" t:dataTypeName=number

metric m:professionals_avg_yrs_in_current_job l:"Professionals Avg Yrs in Current Job" t:dataTypeName=number

metric m:protected_services_ee p:integer l:"Protected Services # EE" t:dataTypeName=number

metric m:protected_services_avg_hrly l:"Protected Services Avg Hrly" t:dataTypeName=number

metric m:protected_services_avg_yrs_in_current_job l:"Protected Services Avg Yrs in Current Job" t:dataTypeName=number

metric m:service_maintenance_ee p:integer l:"Service/Maintenance # EE" t:dataTypeName=number

metric m:service_maintenance_avg_hrly l:"Service/Maintenance Avg Hrly" t:dataTypeName=number

metric m:service_maintenance_avg_yrs_in_current_job l:"Service/Maintenance Avg Yrs in Current Job" t:dataTypeName=number

metric m:skilled_craft_ee p:integer l:"Skilled Craft # EE" t:dataTypeName=number

metric m:skilled_craft_avg_hrly l:"Skilled Craft Avg Hrly" t:dataTypeName=number

metric m:skilled_craft_avg_yrs_in_current_job l:"Skilled Craft Avg Yrs in Current Job" t:dataTypeName=number

metric m:technicians_ee p:integer l:"Technicians # EE" t:dataTypeName=number

metric m:technicians_avg_hrly l:"Technicians Avg Hrly" t:dataTypeName=number

metric m:technicians_avg_yrs_in_current_job l:"Technicians Avg Yrs in Current Job" t:dataTypeName=number

entity e:k3hs-aykd l:"City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department" t:url=https://data.seattle.gov/api/views/k3hs-aykd

property e:k3hs-aykd t:meta.view v:id=k3hs-aykd v:category="City Business" v:attributionLink=http://mayormcginn.wpengine.netdna-cdn.com/wp-content/uploads/2013/07/Appendix-4-EEO-Final.pdf v:averageRating=0 v:name="City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department"

property e:k3hs-aykd t:meta.view.license v:name="Public Domain"

property e:k3hs-aykd t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"

property e:k3hs-aykd t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```