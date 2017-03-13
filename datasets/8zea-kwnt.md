# CDC STATE System E-Cigarette Legislation - Youth Access

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-e-cigarette-legislation-youth-access-69fa9) |
| Metadata | [Link](https://data.cdc.gov/api/views/8zea-kwnt) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/8zea-kwnt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/8zea-kwnt/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 8zea-kwnt |
| Name | CDC STATE System E-Cigarette Legislation - Youth Access |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Legislation |
| Tags | osh, state system, legislation, policy, youth access, e-cigarette |
| Created | 2015-05-04T14:09:53Z |
| Publication Date | 2017-02-16T17:15:19Z |
| Rows Updated | 2017-03-01T17:36:11Z |

## Description

1995-2016. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System. E-Cigarette Legislation?Youth Access. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies.  Data are reported on a quarterly basis. Data include information related to restrictions, enforcement and penalties associated with the sale of e-cigarettes to youth through retail sales and vending machines.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | year               | YEAR               | number    | number      |
| Yes      | numeric metric | quarter            | Quarter            | number    | number      |
| Yes      | series tag     | locationabbr       | LocationAbbr       | text      | text        |
| Yes      | series tag     | locationdesc       | LocationDesc       | text      | text        |
| Yes      | series tag     | topicdesc          | TopicDesc          | text      | text        |
| Yes      | series tag     | measuredesc        | MeasureDesc        | text      | text        |
| Yes      | series tag     | datasource         | DataSource         | text      | text        |
| Yes      | series tag     | provisiongroupdesc | ProvisionGroupDesc | text      | text        |
| Yes      | series tag     | provisiondesc      | ProvisionDesc      | text      | text        |
| Yes      | series tag     | provisionvalue     | ProvisionValue     | text      | text        |
| Yes      | series tag     | citation           | Citation           | text      | text        |
| Yes      | numeric metric | provisionaltvalue  | ProvisionAltValue  | number    | number      |
| Yes      | series tag     | datatype           | DataType           | text      | text        |
| Yes      | series tag     | comments           | Comments           | text      | text        |
| Yes      | series tag     | enacted_date       | Enacted_Date       | text      | text        |
| Yes      | series tag     | effective_date     | Effective_Date     | text      | text        |
| No       |                | displayorder       | DisplayOrder       | number    | text        |
| Yes      | series tag     | topictypeid        | TopicTypeId        | text      | text        |
| Yes      | series tag     | topicid            | TopicId            | text      | text        |
| Yes      | series tag     | measureid          | MeasureId          | text      | text        |
| Yes      | series tag     | provisiongroupid   | ProvisionGroupID   | text      | text        |
| Yes      | series tag     | provisionid        | ProvisionID        | text      | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = displayorder
```

## Data Commands

```ls
series e:8zea-kwnt d:1995-01-01T00:00:00.000Z t:locationabbr=AK t:locationdesc=Alaska t:topicid=1045LEG t:provisiondesc="Restriction on Access" t:measureid=1024EVM t:measuredesc="E-Cigarette Vending Machines" t:provisiongroupdesc=Restrictions t:provisiongroupid=10GRP t:provisionvalue="No Provision" t:provisionid=495 t:topicdesc="Legislation - E-Cigarette - Youth Access" t:datatype=Ranking t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0 m:quarter=4

series e:8zea-kwnt d:2006-01-01T00:00:00.000Z t:locationabbr=MT t:locationdesc=Montana t:topicid=1045LEG t:provisiondesc="Maximum Penalty ($)" t:measureid=1024EVM t:measuredesc="E-Cigarette Vending Machines" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="No Provision" t:provisionid=506 t:topicdesc="Legislation - E-Cigarette - Youth Access" t:datatype=Money t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0 m:quarter=4

series e:8zea-kwnt d:2008-01-01T00:00:00.000Z t:locationabbr=DC t:locationdesc="District of Columbia" t:topicid=1045LEG t:provisiondesc="Minimum Penalty ($)" t:measureid=1024EVM t:measuredesc="E-Cigarette Vending Machines" t:provisiongroupdesc=Penalties t:provisiongroupid=60GRP t:provisionvalue="No Provision" t:provisionid=505 t:topicdesc="Legislation - E-Cigarette - Youth Access" t:datatype=Money t:datasource=OSH t:topictypeid=LEG m:provisionaltvalue=0 m:quarter=1
```

## Meta Commands

```ls
metric m:quarter p:integer l:Quarter d:Quarter t:dataTypeName=number

metric m:provisionaltvalue p:integer l:ProvisionAltValue d:"Alternate numeric value for non-numeric provision value; used for mapping and graphing" t:dataTypeName=number

entity e:8zea-kwnt l:"CDC STATE System E-Cigarette Legislation - Youth Access" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/8zea-kwnt

property e:8zea-kwnt t:meta.view v:id=8zea-kwnt v:category=Legislation v:attributionLink=http://www.cdc.gov/STATESystem v:averageRating=0 v:name="CDC STATE System E-Cigarette Legislation - Youth Access" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:8zea-kwnt t:meta.view.license v:name="Public Domain"

property e:8zea-kwnt t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:8zea-kwnt t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:8zea-kwnt t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```