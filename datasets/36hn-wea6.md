# DYCD after-school programs: OSY Out Of School Youth Employment Programs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-osy-out-of-school-youth-employment-programs-b0b82) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/36hn-wea6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/36hn-wea6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/36hn-wea6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 36hn-wea6 |
| Name | DYCD after-school programs: OSY Out Of School Youth Employment Programs |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Education |
| Tags | jobs and economic mobility, education, services, youth, community, development, community development, school, child, children, after-school, after-school programs, programs, employment, internshi... |
| Created | 2011-09-01T20:39:32Z |
| Publication Date | 2011-09-01T20:39:32Z |
| Rows Updated | 2011-09-01T20:39:37Z |

## Description

Facilities in New York City, by agency and site, that offer ?Out-Of -School Youth Employment (OSY) Program? after-school  job and internship programs for young adults ages 16 to 21.
Update Frequency: Annually

## Columns

```ls
| Included | Schema Type | Field Name            | Name                    | Data Type | Render Type |
| ======== | =========== | ===================== | ======================= | ========= | =========== |
| No       | time        | :updated_at           | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | program_type          | PROGRAM TYPE            | text      | text        |
| Yes      | series tag  | program               | PROGRAM                 | text      | text        |
| Yes      | series tag  | site_name             | SITE NAME               | text      | text        |
| Yes      | series tag  | borough_community     | BOROUGH / COMMUNITY     | text      | text        |
| Yes      | series tag  | agency                | AGENCY                  | text      | text        |
| Yes      | series tag  | contact_number        | Contact Number          | text      | text        |
| Yes      | series tag  | grade_level_age_group | Grade Level / Age Group | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:36hn-wea6 l:"DYCD after-school programs: OSY Out Of School Youth Employment Programs" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/36hn-wea6

property e:36hn-wea6 t:meta.view v:id=36hn-wea6 v:category=Education v:averageRating=0 v:name="DYCD after-school programs: OSY Out Of School Youth Employment Programs" v:attribution="Department of Youth and Community Development (DYCD)"

property e:36hn-wea6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:displayName="NYC OpenData"

property e:36hn-wea6 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```