# City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-university-of-new-york-cuny-university-retention-and-graduation-rates-beginning-1990) |
| Metadata | [Link](https://data.ny.gov/api/views/ba86-tr5c) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ba86-tr5c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ba86-tr5c/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ba86-tr5c |
| Name | City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990 |
| Attribution | City University of New York |
| Category | Education |
| Tags | higher education, enrollment |
| Created | 2014-01-17T17:03:53Z |
| Publication Date | 2015-12-23T17:44:26Z |
| Rows Updated | 2015-12-21T18:40:31Z |

## Description

Data set contains one year retention rates and 150 time graduation rates (3yr rates for associate degree seekers and 6yr rates for baccalaureate seekers) for all CUNY colleges from 1990 through present where applicable for first-time, full-time freshmen.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | college                 | College                 | text      | text        |
| Yes      | series tag     | fall_term               | Fall Term               | text      | text        |
| Yes      | series tag     | record_type_code        | Record Type Code        | text      | number      |
| Yes      | series tag     | record_type_description | Record Type Description | text      | text        |
| Yes      | numeric metric | head_count              | Head Count              | number    | number      |
| Yes      | numeric metric | percentage              | Percentage              | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ba86-tr5c d:2014-01-17T09:03:56.000Z t:record_type_code=1 t:record_type_description="1 Year Retention" t:college="CUNY Baruch College" t:fall_term="Fall 1990" m:percentage=81.8 m:head_count=1278

series e:ba86-tr5c d:2014-01-17T09:03:56.000Z t:record_type_code=2 t:record_type_description="150 Time Graduation" t:college="CUNY Baruch College" t:fall_term="Fall 1990" m:percentage=39.3 m:head_count=1278

series e:ba86-tr5c d:2014-01-17T09:03:56.000Z t:record_type_code=1 t:record_type_description="1 Year Retention" t:college="CUNY Baruch College" t:fall_term="Fall 1991" m:percentage=84.4 m:head_count=1170
```

## Meta Commands

```ls
metric m:head_count p:integer l:"Head Count" t:dataTypeName=number

entity e:ba86-tr5c l:"City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990" t:attribution="City University of New York" t:url=https://data.ny.gov/api/views/ba86-tr5c

property e:ba86-tr5c t:meta.view v:id=ba86-tr5c v:category=Education v:averageRating=0 v:name="City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990" v:attribution="City University of New York"

property e:ba86-tr5c t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ba86-tr5c t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ba86-tr5c t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```