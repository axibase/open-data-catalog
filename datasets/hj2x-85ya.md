# CDC STATE System Tobacco Legislation - Preemption Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cdc-state-system-tobacco-legislation-preemption-summary) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/hj2x-85ya) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/hj2x-85ya/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/hj2x-85ya/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | hj2x-85ya |
| Name | CDC STATE System Tobacco Legislation - Preemption Summary |
| Attribution | Office of Smoking and Health (OSH) |
| Category | Legislation |
| Tags | tobacco, osh, state system, legislation, policy, preemption |
| Created | 2014-12-16T18:54:59Z |
| Publication Date | 2017-02-07T18:35:59Z |
| Rows Updated | 2017-02-07T18:35:35Z |

## Description

1995-2016. Centers for Disease Control and Prevention (CDC). State Tobacco Activities Tracking and Evaluation (STATE) System. Legislation?Preemption. The STATE System houses current and historical state-level legislative data on tobacco use prevention and control policies. Data are reported on a quarterly basis. Data include information related to summary state preemption of more stringent local laws on advertising, smokefree indoor air, youth access and licensure.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | year                 | YEAR                 | number    | number      |
| Yes      | numeric metric | quarter              | Quarter              | number    | number      |
| Yes      | series tag     | locationabbr         | LocationAbbr         | text      | text        |
| Yes      | series tag     | locationdesc         | LocationDesc         | text      | text        |
| Yes      | series tag     | topictypedesc        | TopicTypeDesc        | text      | text        |
| Yes      | series tag     | topicdesc            | TopicDesc            | text      | text        |
| Yes      | series tag     | measuredesc          | MeasureDesc          | text      | text        |
| Yes      | series tag     | smokefree_indoor_air | Smokefree_Indoor_Air | text      | text        |
| Yes      | series tag     | youth_access         | Youth_Access         | text      | text        |
| Yes      | series tag     | advertising          | Advertising          | text      | text        |
| Yes      | series tag     | licensure            | Licensure            | text      | text        |
| Yes      | series tag     | preemption           | Preemption           | text      | text        |
| Yes      | numeric metric | preemptionaltvalue   | PreemptionAltValue   | number    | number      |
| Yes      | series tag     | topictypeid          | TopicTypeId          | text      | text        |
| Yes      | series tag     | topicid              | TopicId              | text      | number      |
| Yes      | series tag     | measureid            | MeasureId            | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hj2x-85ya d:1996-01-01T00:00:00.000Z t:locationabbr=NV t:locationdesc=Nevada t:topicid=630 t:topictypedesc=Legislation t:measureid=667COMB t:measuredesc="Smokefree Indoor Air, Youth Access, Advertising, Licensure ? OSH" t:advertising=Yes t:topicdesc=Preemption t:youth_access=Yes t:smokefree_indoor_air=Yes t:licensure=No t:preemption="Preemption for three policies" t:topictypeid=LEG m:preemptionaltvalue=3 m:quarter=4

series e:hj2x-85ya d:1997-01-01T00:00:00.000Z t:locationabbr=NV t:locationdesc=Nevada t:topicid=630 t:topictypedesc=Legislation t:measureid=667COMB t:measuredesc="Smokefree Indoor Air, Youth Access, Advertising, Licensure ? OSH" t:advertising=Yes t:topicdesc=Preemption t:youth_access=Yes t:smokefree_indoor_air=Yes t:licensure=No t:preemption="Preemption for three policies" t:topictypeid=LEG m:preemptionaltvalue=3 m:quarter=4

series e:hj2x-85ya d:1998-01-01T00:00:00.000Z t:locationabbr=NV t:locationdesc=Nevada t:topicid=630 t:topictypedesc=Legislation t:measureid=667COMB t:measuredesc="Smokefree Indoor Air, Youth Access, Advertising, Licensure ? OSH" t:advertising=Yes t:topicdesc=Preemption t:youth_access=Yes t:smokefree_indoor_air=Yes t:licensure=No t:preemption="Preemption for three policies" t:topictypeid=LEG m:preemptionaltvalue=3 m:quarter=4
```

## Meta Commands

```ls
metric m:quarter p:integer l:Quarter d:Quarter t:dataTypeName=number

metric m:preemptionaltvalue p:integer l:PreemptionAltValue d:"Alternate numeric value for non-numeric preemption value; used for mapping and graphing" t:dataTypeName=number

entity e:hj2x-85ya l:"CDC STATE System Tobacco Legislation - Preemption Summary" t:attribution="Office of Smoking and Health (OSH)" t:url=https://chronicdata.cdc.gov/api/views/hj2x-85ya

property e:hj2x-85ya t:meta.view v:id=hj2x-85ya v:category=Legislation v:attributionLink=http://www.cdc.gov/tobacco/statesystem v:averageRating=0 v:name="CDC STATE System Tobacco Legislation - Preemption Summary" v:attribution="Office of Smoking and Health (OSH)"

property e:hj2x-85ya t:meta.view.license v:name="Public Domain"

property e:hj2x-85ya t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:hj2x-85ya t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:hj2x-85ya t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:029
```