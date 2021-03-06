# Post- Employment Restriction Waivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/post-employment-restriction-waivers-4d068) |
| Metadata | [Link](https://data.sfgov.org/api/views/qwnt-35i6) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/qwnt-35i6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/qwnt-35i6/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | qwnt-35i6 |
| Name | Post- Employment Restriction Waivers |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | ethics, post-employment restriction waivers, conflict of interest |
| Created | 2013-05-31T18:23:41Z |
| Publication Date | 2016-05-25T23:20:49Z |

## Description

Under section 3.234(a)(1) of the San Francisco Campaign and Governmental Conduct Code, no former officer or employee of the City and County of San Francisco may make communications before any court or public agency in connection with any particular matter in which the City is a party or has a direct and substantial interest, in which the former officer or employee participated personally and substantially, and which involved specific parties at the time of such participation.  Under section 3.234(a)(2), no current or former officer or employee may, for one year after termination of service or employment, communicate with his or her former department to influence a government decision on behalf of any other person.  Under section 3.234(a)(3), no current or former officer or employee may be employed by or otherwise receive compensation from a person or entity that entered into a contract with the city within the past 12 months where the officer or employee personally and substantially participated in the award of the contract. Under section 3.234(c)(1), the Ethics Commission may waive the restrictions in subsections (a)(1) and (a)(2) if the Commission determines that granting a waiver would not create the potential for undue influence or unfair advantage.  Under section 3.234(c)(2), the Commission may grant a waiver from the restrictions in subsections (a)(1) and (a)(2) for members of City boards and commissions who, by law, must be appointed to represent any profession, trade, business union or association.  Under section 3.234(c)(3), the Commission may waive the ban in subsection (a)(3) if the Commission determines that imposing the restriction would cause extreme hardship for the City officer or employee. This is a table of the waivers that have been granted under section 3.234(c).

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | time        | date_of_request   | Date of request   | calendar_date | calendar_date |
| Yes      | series tag  | name_of_requestor | Name of requestor | text          | text          |
| Yes      | series tag  | relevant_law      | Relevant law      | text          | text          |
```

## Time Field

```ls
Value = date_of_request
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:qwnt-35i6 d:2004-03-10T00:00:00.000Z t:name_of_requestor="Terrence Hallinan" t:relevant_law="one-year post-employment ban" m:row_number.qwnt-35i6=1

series e:qwnt-35i6 d:2004-07-30T00:00:00.000Z t:name_of_requestor="Anthony P. Hall" t:relevant_law="one-year post-employment ban" m:row_number.qwnt-35i6=2

series e:qwnt-35i6 d:2004-08-30T00:00:00.000Z t:name_of_requestor="Ruth Edelstein" t:relevant_law="one-year post-employment ban" m:row_number.qwnt-35i6=3
```

## Meta Commands

```ls
metric m:row_number.qwnt-35i6 p:long l:"Row Number"

entity e:qwnt-35i6 l:"Post- Employment Restriction Waivers" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/qwnt-35i6

property e:qwnt-35i6 t:meta.view d:2017-09-25T07:26:48.416Z v:averageRating=0 v:name="Post- Employment Restriction Waivers" v:attribution="San Francisco Ethics Commission" v:attributionLink=http://www.sfethics.org v:id=qwnt-35i6 v:category="City Management and Ethics"

property e:qwnt-35i6 t:meta.view.license d:2017-09-25T07:26:48.416Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:qwnt-35i6 t:meta.view.owner d:2017-09-25T07:26:48.416Z v:displayName="San Francisco Ethics Commission" v:lastNotificationSeenAt=1500665894 v:id=kcqd-yeev v:screenName="San Francisco Ethics Commission"

property e:qwnt-35i6 t:meta.view.tableauthor d:2017-09-25T07:26:48.416Z v:displayName="San Francisco Ethics Commission" v:lastNotificationSeenAt=1500665894 v:roleName=publisher v:id=kcqd-yeev v:screenName="San Francisco Ethics Commission"
```

## Top Records

```ls
| date_of_request     | name_of_requestor | relevant_law                 | 
| =================== | ================= | ============================ | 
| 2004-03-10T00:00:00 | Terrence Hallinan | one-year post-employment ban | 
| 2004-07-30T00:00:00 | Anthony P. Hall   | one-year post-employment ban | 
| 2004-08-30T00:00:00 | Ruth Edelstein    | one-year post-employment ban | 
| 2004-10-21T00:00:00 | David Campos      | one-year post-employment ban | 
| 2005-03-09T00:00:00 | Matt Gonzalez     | one-year post-employment ban | 
| 2006-01-24T00:00:00 | Barbara Selby     | one-year post-employment ban | 
| 2006-09-01T00:00:00 | Miguel Marquez    | one-year post-employment ban | 
| 2006-09-01T00:00:00 | Rio Foster        | one-year post-employment ban | 
| 2007-11-02T00:00:00 | Steve Kawa        | one-year post-employment ban | 
| 2010-02-15T00:00:00 | Zachary Nathan    | one-year post-employment ban | 
```