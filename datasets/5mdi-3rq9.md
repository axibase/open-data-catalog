# Public Assistance Cases with Earned Income: Beginning April 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-assistance-cases-with-earned-income-beginning-april-2006) |
| Metadata | [Link](https://data.ny.gov/api/views/5mdi-3rq9) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/5mdi-3rq9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/5mdi-3rq9/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 5mdi-3rq9 |
| Name | Public Assistance Cases with Earned Income: Beginning April 2006 |
| Attribution | New York State Office of Temporary and Disability Assistance (OTDA) |
| Category | Human Services |
| Tags | public assistance |
| Created | 2015-04-01T17:52:27Z |
| Publication Date | 2017-02-02T23:02:48Z |
| Rows Updated | 2017-02-02T23:02:46Z |

## Description

The data in this dataset are monthly listings of the number of Temporary Assistance for Needy Families (TANF), Safety Net Assistance-Maintenance of Effort (SNA-MOE), and Safety Net Assistance Non-Maintenance of Effort (SNA Non-MOE) cash assistance cases with earned monthly income, and the average gross earned monthly income and average net earned monthly income (after applying earned income disregards) for these cases.  Data is presented by case type for each local social services district.  The dataset is from the NYS Office of Temporary and Disability Assistance (OTDA) and is updated monthly.

## Columns

```ls
| Included | Schema Type    | Field Name                              | Name                                    | Data Type | Render Type |
| ======== | ============== | ======================================= | ======================================= | ========= | =========== |
| No       |                | year                                    | Year                                    | number    | number      |
| No       |                | month                                   | Month                                   | text      | text        |
| Yes      | series tag     | month_code                              | Month Code                              | text      | number      |
| Yes      | series tag     | district_code                           | District Code                           | text      | number      |
| Yes      | series tag     | district                                | District                                | text      | text        |
| Yes      | numeric metric | tanf_cases_with_earned_income           | TANF Cases with Earned Income           | number    | number      |
| Yes      | numeric metric | tanf_average_gross_earned_income        | TANF Average Gross Earned Income        | money     | money       |
| Yes      | numeric metric | tanf_average_net_earned_income          | TANF Average Net Earned Income          | money     | money       |
| Yes      | numeric metric | sna_moe_cases_with_earned_income        | SNA MOE Cases with Earned Income        | number    | number      |
| Yes      | numeric metric | sna_moe_average_gross_earned_income     | SNA MOE Average Gross Earned Income     | money     | money       |
| Yes      | numeric metric | sna_moe_average_net_earned_income       | SNA MOE Average Net Earned Income       | money     | money       |
| Yes      | numeric metric | sna_non_moe_cases_with_earned_income    | SNA Non-MOE Cases with Earned Income    | number    | number      |
| Yes      | numeric metric | sna_non_moe_average_gross_earned_income | SNA Non-MOE Average Gross Earned Income | money     | money       |
| Yes      | numeric metric | sna_non_moe_average_net_earned_income   | SNA Non-MOE Average Net Earned Income   | money     | money       |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = month,year
```

## Data Commands

```ls
series e:5mdi-3rq9 d:2006-04-01T00:00:00.000Z t:district_code=66 t:month_code=4 t:district="New York City" m:tanf_cases_with_earned_income=9382 m:sna_moe_cases_with_earned_income=10399 m:tanf_average_gross_earned_income=765 m:sna_non_moe_average_net_earned_income=546 m:sna_moe_average_net_earned_income=330 m:tanf_average_net_earned_income=369 m:sna_non_moe_average_gross_earned_income=796 m:sna_moe_average_gross_earned_income=718 m:sna_non_moe_cases_with_earned_income=4622

series e:5mdi-3rq9 d:2006-04-01T00:00:00.000Z t:district_code=1 t:month_code=4 t:district=Albany m:tanf_cases_with_earned_income=162 m:sna_moe_cases_with_earned_income=47 m:tanf_average_gross_earned_income=754 m:sna_non_moe_average_net_earned_income=151 m:sna_moe_average_net_earned_income=352 m:tanf_average_net_earned_income=356 m:sna_non_moe_average_gross_earned_income=226 m:sna_moe_average_gross_earned_income=744 m:sna_non_moe_cases_with_earned_income=10

series e:5mdi-3rq9 d:2006-04-01T00:00:00.000Z t:district_code=2 t:month_code=4 t:district=Allegany m:tanf_cases_with_earned_income=48 m:sna_moe_cases_with_earned_income=13 m:tanf_average_gross_earned_income=677 m:sna_non_moe_average_net_earned_income=136 m:sna_moe_average_net_earned_income=400 m:tanf_average_net_earned_income=292 m:sna_non_moe_average_gross_earned_income=226 m:sna_moe_average_gross_earned_income=751 m:sna_non_moe_cases_with_earned_income=9
```

## Meta Commands

```ls
metric m:tanf_cases_with_earned_income p:integer l:"TANF Cases with Earned Income"orary Assistance for Needy Families (TANF) cases with earned monthly income. TANF is the federally-funded cash assistance program for households consisting of children living with related adults, and certain foster care cases (the latter cases are not examined for earned income)." t:dataTypeName=number

metric m:sna_moe_cases_with_earned_income p:integer l:"SNA MOE Cases with Earned Income"ty Net Assistance-Maintenance of Effort (SNA-MOE) cases with earned monthly income. SNA MOE is a state-funded cash assistance program consisting of cases that would qualify for TANF except that they are barred from TANF assistance because they have exceeded the 60-month lifetime limit on that assistance or because they are a qualified alien but in the country for less than five years." t:dataTypeName=number

metric m:sna_non_moe_cases_with_earned_income p:integer l:"SNA Non-MOE Cases with Earned Income"ty Net Assistance Non-Maintenance of Effort (SNA Non-MOE) cases with earned monthly income. SNA Non-MOE is a state-funded cash assistance program primarily for childless adults and two-parent families with children where both parents are non-disabled" t:dataTypeName=number

entity e:5mdi-3rq9 l:"Public Assistance Cases with Earned Income:  Beginning April 2006" t:attribution="New York State Office of Temporary and Disability Assistance (OTDA)" t:url=https://data.ny.gov/api/views/5mdi-3rq9

property e:5mdi-3rq9 t:meta.view v:id=5mdi-3rq9 v:category="Human Services" v:attributionLink=http://otda.ny.gov/resources/caseload/ v:averageRating=0 v:name="Public Assistance Cases with Earned Income:  Beginning April 2006" v:attribution="New York State Office of Temporary and Disability Assistance (OTDA)"

property e:5mdi-3rq9 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:5mdi-3rq9 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:5mdi-3rq9 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```