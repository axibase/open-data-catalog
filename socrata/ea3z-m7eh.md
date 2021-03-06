# Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 7 - Kansas City

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/impaired-driving-death-rate-by-age-and-gender-2012-region-7-kansas-city) |
| Metadata | [Link](https://data.cdc.gov/api/views/ea3z-m7eh) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/ea3z-m7eh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/ea3z-m7eh/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | ea3z-m7eh |
| Name | Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 7 - Kansas City |
| Attribution | CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention |
| Category | Motor Vehicle |
| Tags | centers for disease control and prevention, cdc |
| Created | 2014-12-17T15:52:15Z |
| Publication Date | 2016-09-14T14:54:18Z |

## Description

Rate of deaths by age/gender (per 100,000 population) for people killed in crashes involving a driver with BAC =>0.08%, 2012, 2014. 2012 Source: Fatality Analysis Reporting System (FARS). 2014 Source: National Highway Traffic Administration's (NHTSA) Fatality Analysis Reporting System (FARS), 2014 Annual Report File. Note: Blank cells indicate data are suppressed. Fatality rates based on fewer than 20 deaths are suppressed.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name             | Data Type | Render Type |
| ======== | ============== | =============== | ================ | ========= | =========== |
| Yes      | series tag     | state           | State            | text      | text        |
| Yes      | numeric metric | all_ages        | All Ages, 2012   | number    | number      |
| Yes      | numeric metric | all_ages_2014   | All Ages, 2014   | number    | number      |
| Yes      | numeric metric | ages_0_20       | Ages 0-20, 2012  | number    | number      |
| Yes      | numeric metric | ages_0_20_2014  | Ages 0-20, 2014  | number    | number      |
| Yes      | numeric metric | ages_21_34      | Ages 21-34, 2012 | number    | number      |
| Yes      | numeric metric | ages_21_34_2014 | Ages 21-34, 2014 | number    | number      |
| Yes      | numeric metric | ages_35         | Ages 35+, 2012   | number    | number      |
| Yes      | numeric metric | ages_35_2014    | Ages 35+, 2014   | number    | number      |
| Yes      | numeric metric | male            | Male, 2012       | number    | number      |
| Yes      | numeric metric | male_2014       | Male, 2014       | number    | number      |
| Yes      | numeric metric | female          | Female, 2012     | number    | number      |
| Yes      | numeric metric | female_2014     | Female, 2014     | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ea3z-m7eh d:2012-01-01T00:00:00.000Z t:state=Iowa m:all_ages_2014=3 m:ages_21_34=5.9 m:male_2014=4.8 m:ages_21_34_2014=4.6 m:all_ages=3.2 m:ages_35_2014=3.4 m:ages_35=2.9 m:male=5.1

series e:ea3z-m7eh d:2012-01-01T00:00:00.000Z t:state=Nebraska m:all_ages_2014=3.3 m:ages_21_34=6.5 m:male_2014=5 m:ages_21_34_2014=7 m:all_ages=4 m:ages_35_2014=3 m:ages_35=3.5 m:male=6.4

series e:ea3z-m7eh d:2012-01-01T00:00:00.000Z t:state="United States" m:all_ages_2014=3.1 m:ages_21_34=6.7 m:male_2014=4.9 m:ages_0_20_2014=1.2 m:ages_21_34_2014=6.2 m:ages_0_20=1.3 m:all_ages=3.3 m:ages_35_2014=3 m:ages_35=3.1 m:female=1.5 m:female_2014=1.4 m:male=5.2
```

## Meta Commands

```ls
metric m:all_ages p:float l:"All Ages, 2012" t:dataTypeName=number

metric m:all_ages_2014 p:float l:"All Ages, 2014" t:dataTypeName=number

metric m:ages_0_20 p:float l:"Ages 0-20, 2012" t:dataTypeName=number

metric m:ages_0_20_2014 p:float l:"Ages 0-20, 2014" t:dataTypeName=number

metric m:ages_21_34 p:float l:"Ages 21-34, 2012" t:dataTypeName=number

metric m:ages_21_34_2014 p:float l:"Ages 21-34, 2014" t:dataTypeName=number

metric m:ages_35 p:float l:"Ages 35+, 2012" t:dataTypeName=number

metric m:ages_35_2014 p:float l:"Ages 35+, 2014" t:dataTypeName=number

metric m:male p:float l:"Male, 2012" t:dataTypeName=number

metric m:male_2014 p:float l:"Male, 2014" t:dataTypeName=number

metric m:female p:float l:"Female, 2012" t:dataTypeName=number

metric m:female_2014 p:float l:"Female, 2014" t:dataTypeName=number

entity e:ea3z-m7eh l:"Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 7 - Kansas City" t:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" t:url=https://data.cdc.gov/api/views/ea3z-m7eh

property e:ea3z-m7eh t:meta.view d:2017-09-25T07:26:15.580Z v:averageRating=0 v:name="Impaired Driving Death Rate, by Age and Gender, 2012 & 2014, Region 7 - Kansas City" v:attribution="CDC National Center for Injury Prevention and Control, Division of Unintentional Injury Prevention" v:attributionLink=http://www.cdc.gov/motorvehiclesafety/ v:id=ea3z-m7eh v:category="Motor Vehicle"

property e:ea3z-m7eh t:meta.view.owner d:2017-09-25T07:26:15.580Z v:displayName=iqw7@cdc.gov v:id=cg4e-25jx v:screenName=iqw7@cdc.gov

property e:ea3z-m7eh t:meta.view.tableauthor d:2017-09-25T07:26:15.580Z v:displayName=iqw7@cdc.gov v:roleName=publisher v:id=cg4e-25jx v:screenName=iqw7@cdc.gov

property e:ea3z-m7eh t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:26:15.580Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Program_Code=009:020 v:Bureau_Code=009:00
```

## Top Records

```ls
| state         | all_ages | all_ages_2014 | ages_0_20 | ages_0_20_2014 | ages_21_34 | ages_21_34_2014 | ages_35 | ages_35_2014 | male | male_2014 | female | female_2014 | 
| ============= | ======== | ============= | ========= | ============== | ========== | =============== | ======= | ============ | ==== | ========= | ====== | =========== | 
| Iowa          | 3.2      | 3             |           |                | 5.9        | 4.6             | 2.9     | 3.4          | 5.1  | 4.8       |        |             | 
| Nebraska      | 4.0      | 3.3           |           |                | 6.5        | 7               | 3.5     | 3            | 6.4  | 5         |        |             | 
| United States | 3.3      | 3.1           | 1.3       | 1.2            | 6.7        | 6.2             | 3.1     | 3            | 5.2  | 4.9       | 1.5    | 1.4         | 
| Kansas        | 3.4      | 3.6           | 2.3       |                | 6.0        | 7.4             | 3.0     | 3.3          | 6.0  | 5.8       |        | 1.4         | 
| Missouri      | 4.8      | 3.4           | 1.9       |                | 9.5        | 6.9             | 4.4     | 3.2          | 7.8  | 5.6       | 1.8    | 1.3         | 
```