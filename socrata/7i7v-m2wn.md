# Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/campaign-finance-summary-of-third-party-disclosure-forms-regarding-san-francisco-candidat-) |
| Metadata | [Link](https://data.sfgov.org/api/views/7i7v-m2wn) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/7i7v-m2wn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/7i7v-m2wn/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 7i7v-m2wn |
| Name | Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016 |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | campaign finance dashboards 2016 |
| Created | 2016-08-18T20:50:38Z |
| Publication Date | 2016-08-18T21:00:00Z |

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================ | ============= | ============= |
| Yes      | series tag     | form_type                        | Form Type                        | text          | text          |
| Yes      | series tag     | report_number                    | Report Number                    | text          | text          |
| Yes      | time           | date_filed                       | Date Filed                       | calendar_date | calendar_date |
| Yes      | series tag     | filer                            | Filer                            | text          | text          |
| Yes      | series tag     | filer_id                         | Filer Id                         | text          | text          |
| Yes      | numeric metric | amount                           | Amount                           | money         | money         |
| Yes      | series tag     | candidate_identified             | Candidate Identified             | text          | text          |
| Yes      | series tag     | district                         | District                         | text          | text          |
| Yes      | series tag     | support_oppose_or_neutral        | Support Oppose or Neutral        | text          | text          |
| No       |                | start_date_of_distribution       | Start Date of Distribution       | calendar_date | calendar_date |
| No       |                | end_or_only_date_of_distribution | End or Only Date of Distribution | calendar_date | calendar_date |
| Yes      | series tag     | notes                            | Notes                            | text          | text          |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = start_date_of_distribution,end_or_only_date_of_distribution
```

## Data Commands

```ls
series e:7i7v-m2wn d:2016-08-26T00:00:00.000Z t:support_oppose_or_neutral=Support t:filer_id=1384192 t:notes="Web Ads" t:report_number=VA-G16-013 t:district="Board of Supervisors District 9" t:filer="San Franciscans for a City that Works" t:candidate_identified="Joshua Arce" t:form_type=496 m:amount=5000

series e:7i7v-m2wn d:2016-08-18T00:00:00.000Z t:support_oppose_or_neutral=Support t:filer_id=1384192 t:notes="Web Ads" t:report_number=VA-G16-008 t:district="Board of Supervisors District 1" t:filer="San Franciscans for a City that Works" t:candidate_identified="Marjan Philhour" t:form_type=496 m:amount=5000

series e:7i7v-m2wn d:2016-08-26T00:00:00.000Z t:support_oppose_or_neutral=Support t:filer_id=1384192 t:notes="Web Ads" t:report_number=VA-G16-012 t:district="Board of Supervisors District 1" t:filer="San Franciscans for a City that Works" t:candidate_identified="Marjan Philhour" t:form_type=496 m:amount=5000
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:7i7v-m2wn l:"Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/7i7v-m2wn

property e:7i7v-m2wn t:meta.view d:2017-09-25T07:29:31.663Z v:averageRating=0 v:name="Campaign Finance - Summary Of Third Party Disclosure Forms Regarding San Francisco Candidates - November 8, 2016" v:attribution="San Francisco Ethics Commission" v:attributionLink=http://www.sfethics.org v:id=7i7v-m2wn v:category="City Management and Ethics"

property e:7i7v-m2wn t:meta.view.license d:2017-09-25T07:29:31.663Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:7i7v-m2wn t:meta.view.owner d:2017-09-25T07:29:31.663Z v:displayName="Steven Massey" v:lastNotificationSeenAt=1498669627 v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:id=vm9c-ykir v:screenName="Steven Massey" v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB

property e:7i7v-m2wn t:meta.view.tableauthor d:2017-09-25T07:29:31.663Z v:displayName="Steven Massey" v:lastNotificationSeenAt=1498669627 v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:id=vm9c-ykir v:screenName="Steven Massey" v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB
```

## Top Records

```ls
| form_type | report_number | date_filed          | filer                                 | filer_id | amount  | candidate_identified | district                        | support_oppose_or_neutral | start_date_of_distribution | end_or_only_date_of_distribution | notes                                | 
| ========= | ============= | =================== | ===================================== | ======== | ======= | ==================== | =============================== | ========================= | ========================== | ================================ | ==================================== | 
| 496       | VA-G16-013    | 2016-08-26T00:00:00 | San Franciscans for a City that Works | 1384192  | 5000    | Joshua Arce          | Board of Supervisors District 9 | Support                   | 2016-08-25T00:00:00        |                                  | Web Ads                              | 
| 496       | VA-G16-008    | 2016-08-18T00:00:00 | San Franciscans for a City that Works | 1384192  | 5000    | Marjan Philhour      | Board of Supervisors District 1 | Support                   | 2016-08-17T00:00:00        |                                  | Web Ads                              | 
| 496       | VA-G16-012    | 2016-08-26T00:00:00 | San Franciscans for a City that Works | 1384192  | 5000    | Marjan Philhour      | Board of Supervisors District 1 | Support                   | 2016-08-25T00:00:00        |                                  | Web Ads                              | 
| 496       | VA-G16-018    | 2016-08-31T00:00:00 | San Franciscans for a City that Works | 1384192  | 3115    | Marjan Philhour      | Board of Supervisors District 1 | Support                   | 2016-08-30T00:00:00        |                                  | Canvassing                           | 
| 496       | VA-G16-019    | 2016-08-31T00:00:00 | San Franciscans for a City that Works | 1384192  | 2612    | Joshua Arce          | Board of Supervisors District 9 | Support                   | 2016-08-30T00:00:00        |                                  | Canvassing                           | 
| 496       | VA-G16-023    | 2016-09-02T00:00:00 | San Franciscans for a City that Works | 1384192  | 1500    | Marjan Philhour      | Board of Supervisors District 1 | Support                   | 2016-09-01T00:00:00        |                                  | Consulting                           | 
| 496       | VA-G16-024    | 2016-09-02T00:00:00 | San Franciscans for a City that Works | 1384192  | 1500    | Joshua Arce          | Board of Supervisors District 9 | Support                   | 2016-09-01T00:00:00        |                                  | Consulting                           | 
| 496       | VA-G16-026    | 2016-09-06T00:00:00 | San Franciscans for a City that Works | 1384192  | 1674.37 | Marjan Philhour      | Board of Supervisors District 1 | Support                   | 2016-09-03T00:00:00        |                                  | Door Hangers                         | 
| 496       | VA-G16-021    | 2016-09-02T00:00:00 | San Franciscans for a City that Works | 1384192  | 2930    | Marjan Philhour      | Board of Supervisors District 1 | Support                   | 2016-08-31T00:00:00        |                                  | Staff Time                           | 
| 496       | VA-G16-027    | 2016-09-06T00:00:00 | San Franciscans for a City that Works | 1384192  | 2484.01 | Joshua Arce          | Board of Supervisors District 9 | Support                   | 2016-09-03T00:00:00        |                                  | Campaign Literature and Door Hangers | 
```