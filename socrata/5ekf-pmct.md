# BRFSS Prevalence And Trends Data: Health Care Access/Coverage for 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/brfss-prevalence-and-trends-data-health-care-access-coverage-for-2011) |
| Metadata | [Link](https://data.cdc.gov/api/views/5ekf-pmct) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/5ekf-pmct/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/5ekf-pmct/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 5ekf-pmct |
| Name | BRFSS Prevalence And Trends Data: Health Care Access/Coverage for 2011 |
| Attribution | Behavioral Risk Factor Surveillance System |
| Category | Health Statistics |
| Tags | brfss, heath care access, adults, health care coverage |
| Created | 2013-08-02T15:04:36Z |
| Publication Date | 2013-08-02T15:06:43Z |

## Description

The 2011 BRFSS data reflects a change in weighting methodology (raking) and the addition of cell phone only respondents. Shifts in observed prevalence from 2010 to 2011 for BRFSS measures will likely reflect the new methods of measuring risk factors, rather than true trends in risk-factor prevalence. A break in trend lines after 2010 is used to reflect this change in methodolgy. Percentages are weighted to population characteristics. Data are not available if it did not meet BRFSS stability requirements. For more information on these requirements, as well as risk factors and calculated variables, see the Technical Documents and Survey Data for a specific year - http://www.cdc.gov/brfss/annual_data/annual_data.htm. Recommended citation: Centers for Disease Control and Prevention (CDC). Behavioral Risk Factor Surveillance System. Atlanta, Georgia: U.S. Department of Health and Human Services, Centers for Disease Control and Prevention, [appropriate year].

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | time           | year       | Year      | number    | number      |
| Yes      | series tag     | state      | State     | text      | text        |
| Yes      | numeric metric | yes        | Yes       | percent   | percent     |
| No       |                | no         | No        | percent   | percent     |
| Yes      | series tag     | category   | Category  | text      | text        |
| Yes      | series tag     | condition  | Condition | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = no
```

## Data Commands

```ls
series e:5ekf-pmct d:2011-01-01T00:00:00.000Z t:condition="Do you have any kind of health care coverage?" t:state="Nationwide (States, DC, and Territories)" t:category="Health Care Access/Coverage" m:yes=82.1

series e:5ekf-pmct d:2011-01-01T00:00:00.000Z t:condition="Do you have any kind of health care coverage?" t:state="Nationwide (States and DC)" t:category="Health Care Access/Coverage" m:yes=82.1

series e:5ekf-pmct d:2011-01-01T00:00:00.000Z t:condition="Do you have any kind of health care coverage?" t:state=Guam t:category="Health Care Access/Coverage" m:yes=72
```

## Meta Commands

```ls
metric m:yes p:float l:Yes t:dataTypeName=percent

entity e:5ekf-pmct l:"BRFSS Prevalence And Trends Data: Health Care Access/Coverage for 2011" t:attribution="Behavioral Risk Factor Surveillance System" t:url=https://data.cdc.gov/api/views/5ekf-pmct

property e:5ekf-pmct t:meta.view d:2017-09-25T07:27:34.607Z v:averageRating=0 v:name="BRFSS Prevalence And Trends Data: Health Care Access/Coverage for 2011" v:attribution="Behavioral Risk Factor Surveillance System" v:attributionLink=http://www.cdc.gov/brfss/ v:id=5ekf-pmct v:category="Health Statistics"

property e:5ekf-pmct t:meta.view.owner d:2017-09-25T07:27:34.607Z v:displayName=CDC v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:id=g3fc-zmqn v:screenName=CDC v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB

property e:5ekf-pmct t:meta.view.tableauthor d:2017-09-25T07:27:34.607Z v:displayName=CDC v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:id=g3fc-zmqn v:screenName=CDC v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB

property e:5ekf-pmct t:meta.view.metadata.custom_fields.common_core d:2017-09-25T07:27:34.607Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Program_Code=009:020 v:Bureau_Code=009:00
```

## Top Records

```ls
| year | state                                    | yes  | no   | category                    | condition                                                   | 
| ==== | ======================================== | ==== | ==== | =========================== | =========================================================== | 
| 2011 | Nationwide (States, DC, and Territories) | 82.1 | 17.9 | Health Care Access/Coverage | Do you have any kind of health care coverage?               | 
| 2011 | Nationwide (States and DC)               | 82.1 | 17.9 | Health Care Access/Coverage | Do you have any kind of health care coverage?               | 
| 2011 | Guam                                     | 72   | 28   | Health Care Access/Coverage | Do you have any kind of health care coverage?               | 
| 2011 | Puerto Rico                              | 90.5 | 9.5  | Health Care Access/Coverage | Do you have any kind of health care coverage?               | 
| 2011 | Nationwide (States, DC, and Territories) | 78.7 | 21.3 | Health Care Access/Coverage | Adults aged 18-64 who have any kind of health care coverage | 
| 2011 | Nationwide (States and DC)               | 78.7 | 21.3 | Health Care Access/Coverage | Adults aged 18-64 who have any kind of health care coverage | 
| 2011 | Guam                                     | 69.8 | 30.2 | Health Care Access/Coverage | Adults aged 18-64 who have any kind of health care coverage | 
| 2011 | Puerto Rico                              | 88.8 | 11.2 | Health Care Access/Coverage | Adults aged 18-64 who have any kind of health care coverage | 
| 2011 | Kentucky                                 | 77.7 | 22.3 | Health Care Access/Coverage | Adults aged 18-64 who have any kind of health care coverage | 
| 2011 | Maryland                                 | 84.7 | 15.3 | Health Care Access/Coverage | Adults aged 18-64 who have any kind of health care coverage | 
```