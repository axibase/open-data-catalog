# Sidebarinformation 2017-18 Proposed

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sidebarinformation-2017-18-proposed) |
| Metadata | [Link](https://data.seattle.gov/api/views/wend-zjdf) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/wend-zjdf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/wend-zjdf/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | wend-zjdf |
| Name | Sidebarinformation 2017-18 Proposed |
| Attribution | City of Seattle |
| Category | City Business |
| Tags | sidebarinformation 2017-18 proposed |
| Created | 2016-09-23T18:41:31Z |
| Publication Date | 2016-09-23T18:47:36Z |

## Description

Sidebarinformation 2017-18 Proposed

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                                 | Data Type | Render Type |
| ======== | ============== | ================================== | ==================================== | ========= | =========== |
| Yes      | series tag     | dept_code                          | DEPT CODE                            | text      | text        |
| Yes      | series tag     | department_or_fund_name            | Department or Fund Name              | text      | text        |
| Yes      | series tag     | adopted_budget_executive_overview  | Adopted Budget - Executive Overview  | text      | text        |
| Yes      | series tag     | proposed_budget_executive_overview | Proposed Budget - Executive Overview | text      | text        |
| Yes      | series tag     | city_budget_book                   | City Budget Book                     | text      | text        |
| Yes      | series tag     | capital_budget_book                | Capital Budget Book                  | text      | text        |
| Yes      | series tag     | city_financial_plans               | City Financial Plans                 | text      | text        |
| Yes      | numeric metric | 2017_proposed_budget               | 2017 Proposed Budget                 | number    | number      |
| Yes      | series tag     | 2017_proposed_fte                  | 2017 Proposed FTE                    | text      | text        |
| Yes      | series tag     | department_director_name           | Department Director Name             | text      | text        |
| Yes      | series tag     | department_director_title          | Department Director Title            | text      | text        |
| Yes      | series tag     | department_website                 | Department Website                   | text      | text        |
| Yes      | series tag     | department_budget_book             | Department Budget Book               | text      | text        |
| Yes      | series tag     | department_capital_budget_book     | Department Capital Budget Book       | text      | text        |
| Yes      | series tag     | department_or_fund_description     | Department or Fund Description       | text      | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wend-zjdf d:2017-01-01T00:00:00.000Z t:2017_proposed_fte=n/a t:department_website=www.spl.org/levy t:department_budget_book=http://www.seattle.gov/financedepartment/17proposedbudget/documents/12LIBLEVY.pdf t:proposed_budget_executive_overview=http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf t:capital_budget_book=http://www.seattle.gov/financedepartment/1722proposedcip/ t:dept_code=12LIBLEVY t:department_or_fund_description="The 2012 Library Levy collects $123 million in property taxes over seven years to support, maintain and improve core Library services." t:city_financial_plans=http://www.seattle.gov/financedepartment/financialplans.htm t:department_director_name=n/a t:department_director_title=n/a t:department_or_fund_name="2012 Library Levy" t:city_budget_book=http://www.seattle.gov/financedepartment/17proposedbudget/ m:2017_proposed_budget=18176161

series e:wend-zjdf d:2017-01-01T00:00:00.000Z t:2017_proposed_fte=31.09 t:department_website=www.seattle.gov/arts t:department_budget_book=http://www.seattle.gov/financedepartment/17proposedbudget/documents/ARTS.pdf t:proposed_budget_executive_overview=http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf t:capital_budget_book=http://www.seattle.gov/financedepartment/1722proposedcip/ t:dept_code=ARTS t:department_or_fund_description="The mission of the Office of Arts and Culture (Arts) is to support the value of arts and culture in communities throughout Seattle. Arts promotes Seattle as a cultural destination and invests in Seattle's arts and cultural sector to ensure the City has a wide range of high-quality programs, exhibits and public art." t:city_financial_plans=http://www.seattle.gov/financedepartment/financialplans.htm t:department_director_name="Randy Engstrom" t:department_director_title=Director t:department_or_fund_name="Arts and Culture" t:city_budget_book=http://www.seattle.gov/financedepartment/17proposedbudget/ m:2017_proposed_budget=12687413

series e:wend-zjdf d:2017-01-01T00:00:00.000Z t:2017_proposed_fte=9.50 t:department_website=www.seattle.gov/audit t:department_budget_book=http://www.seattle.gov/financedepartment/17proposedbudget/documents/AUD.pdf t:proposed_budget_executive_overview=http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf t:capital_budget_book=http://www.seattle.gov/financedepartment/1722proposedcip/ t:dept_code=AUD t:department_or_fund_description="The Office of City Auditor is Seattle's independent audit function, and seeks to promote honest, efficient management, and full accountability throughout City government. It serves the public interest by providing the Mayor, the City Council, and City executive and management staff with accurate information, unbiased analyses, and objective recommendations on how best to use public resources." t:city_financial_plans=http://www.seattle.gov/financedepartment/financialplans.htm t:department_director_name="David G. Jones" t:department_director_title="City Auditor" t:department_or_fund_name=Auditor t:city_budget_book=http://www.seattle.gov/financedepartment/17proposedbudget/ m:2017_proposed_budget=1947748
```

## Meta Commands

```ls
metric m:2017_proposed_budget p:double l:"2017 Proposed Budget" t:dataTypeName=number

entity e:wend-zjdf l:"Sidebarinformation 2017-18 Proposed" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/wend-zjdf

property e:wend-zjdf t:meta.view v:id=wend-zjdf v:category="City Business" v:attributionLink=http://www.seattle.gov v:averageRating=0 v:name="Sidebarinformation 2017-18 Proposed" v:attribution="City of Seattle"

property e:wend-zjdf t:meta.view.owner v:id=58et-jnvx v:screenName="Butler, Mark" v:lastNotificationSeenAt=1491575928 v:displayName="Butler, Mark"

property e:wend-zjdf t:meta.view.tableauthor v:id=58et-jnvx v:screenName="Butler, Mark" v:roleName=administrator v:lastNotificationSeenAt=1491575928 v:displayName="Butler, Mark"
```

## Top Records

```ls
| dept_code | department_or_fund_name              | adopted_budget_executive_overview | proposed_budget_executive_overview                                                                | city_budget_book                                           | capital_budget_book                                       | city_financial_plans                                        | 2017_proposed_budget | 2017_proposed_fte | department_director_name | department_director_title           | department_website                              | department_budget_book                                                            | department_capital_budget_book                                                | department_or_fund_description                                                                                                                                                                                                                                                                                                                                                                              | 
| ========= | ==================================== | ================================= | ================================================================================================= | ========================================================== | ========================================================= | =========================================================== | ==================== | ================= | ======================== | =================================== | =============================================== | ================================================================================= | ============================================================================= | =========================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 12LIBLEVY | 2012 Library Levy                    |                                   | http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf | http://www.seattle.gov/financedepartment/17proposedbudget/ | http://www.seattle.gov/financedepartment/1722proposedcip/ | http://www.seattle.gov/financedepartment/financialplans.htm | 18176161             | n/a               | n/a                      | n/a                                 | www.spl.org/levy                                | http://www.seattle.gov/financedepartment/17proposedbudget/documents/12LIBLEVY.pdf |                                                                               | The 2012 Library Levy collects $123 million in property taxes over seven years to support, maintain and improve core Library services.                                                                                                                                                                                                                                                                      | 
| ARTS      | Arts and Culture                     |                                   | http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf | http://www.seattle.gov/financedepartment/17proposedbudget/ | http://www.seattle.gov/financedepartment/1722proposedcip/ | http://www.seattle.gov/financedepartment/financialplans.htm | 12687413             | 31.09             | Randy Engstrom           | Director                            | www.seattle.gov/arts                            | http://www.seattle.gov/financedepartment/17proposedbudget/documents/ARTS.pdf      |                                                                               | The mission of the Office of Arts and Culture (Arts) is to support the value of arts and culture in communities throughout Seattle. Arts promotes Seattle as a cultural destination and invests in Seattle's arts and cultural sector to ensure the City has a wide range of high-quality programs, exhibits and public art.                                                                                | 
| AUD       | Auditor                              |                                   | http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf | http://www.seattle.gov/financedepartment/17proposedbudget/ | http://www.seattle.gov/financedepartment/1722proposedcip/ | http://www.seattle.gov/financedepartment/financialplans.htm | 1947748              | 9.50              | David G. Jones           | City Auditor                        | www.seattle.gov/audit                           | http://www.seattle.gov/financedepartment/17proposedbudget/documents/AUD.pdf       |                                                                               | The Office of City Auditor is Seattle's independent audit function, and seeks to promote honest, efficient management, and full accountability throughout City government. It serves the public interest by providing the Mayor, the City Council, and City executive and management staff with accurate information, unbiased analyses, and objective recommendations on how best to use public resources. | 
| CBLFEE    | Cable Fund                           |                                   | http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf | http://www.seattle.gov/financedepartment/17proposedbudget/ | http://www.seattle.gov/financedepartment/1722proposedcip/ | http://www.seattle.gov/financedepartment/financialplans.htm | 10353466             | n/a               | Michael Mattmiller       | Director & Chief Technology Officer | www.seattle.gov/seattleit                       | http://www.seattle.gov/financedepartment/17proposedbudget/documents/CBLFEE.pdf    |                                                                               | The Cable Television Franchise Subfund collects the revenues generated by franchise fees from cable television providers and manages the expenditure of those funds.                                                                                                                                                                                                                                        | 
| CBO       | City Budget Office                   |                                   | http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf | http://www.seattle.gov/financedepartment/17proposedbudget/ | http://www.seattle.gov/financedepartment/1722proposedcip/ | http://www.seattle.gov/financedepartment/financialplans.htm | 6206560              | 35.00             | Ben Noble                | Director                            | www.seattle.gov/budgetoffice                    | http://www.seattle.gov/financedepartment/17proposedbudget/documents/CBO.pdf       |                                                                               | The City Budget Office is responsible for developing and monitoring the City's annual budget, carrying out budget-related functions, and overseeing fiscal policy and financial planning activities.                                                                                                                                                                                                        | 
| CEN       | Seattle Center                       |                                   | http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf | http://www.seattle.gov/financedepartment/17proposedbudget/ | http://www.seattle.gov/financedepartment/1722proposedcip/ | http://www.seattle.gov/financedepartment/financialplans.htm | 42874753             | 241.73            | Robert Nellams           | Director                            | www.seattlecenter.com                           | http://www.seattle.gov/financedepartment/17proposedbudget/documents/CEN.pdf       | http://www.seattle.gov/financedepartment/1722proposedcip/documents/CENCAP.pdf | Seattle Center is a premier urban park and is home to cultural and education organizations, sports teams, festivals, community programs (including cultural and community celebrations), and entertainment facilities.                                                                                                                                                                                      | 
| CIV       | Civil Service Commissions            |                                   | http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf | http://www.seattle.gov/financedepartment/17proposedbudget/ | http://www.seattle.gov/financedepartment/1722proposedcip/ | http://www.seattle.gov/financedepartment/financialplans.htm | 489344               | 2.60              | Jennifer Greenlee        | Executive Director                  | http://www.seattle.gov/CivilServiceCommissions/ | http://www.seattle.gov/financedepartment/17proposedbudget/documents/CIV.pdf       |                                                                               | The Civil Service Commissions (CIV) is the administrative entity serving both the Civil Service Commission and the Public Safety Civil Service Commission, quasi-judicial bodies charged with providing fair and impartial hearings of alleged violations of the City's personnel rules.                                                                                                                    | 
| CJCS      | Criminal Justice Contracted Services |                                   | http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf | http://www.seattle.gov/financedepartment/17proposedbudget/ | http://www.seattle.gov/financedepartment/1722proposedcip/ | http://www.seattle.gov/financedepartment/financialplans.htm | 28338283             | n/a               | Linda Taylor-Manning     | City Budget Office                  | n/a                                             | http://www.seattle.gov/financedepartment/17proposedbudget/documents/CJCS.pdf      |                                                                               | Criminal Justice Contracted Services (CJCS) provides funding for both public defense and jail services for individuals arrested, prosecuted, and/or convicted of misdemeanor criminal code violations in Seattle.                                                                                                                                                                                           | 
| CPC       | Community Police Commission          |                                   | http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf | http://www.seattle.gov/financedepartment/17proposedbudget/ | http://www.seattle.gov/financedepartment/1722proposedcip/ | http://www.seattle.gov/financedepartment/financialplans.htm | 878557               | 4.00              | F? Lopez                 | Executive Director                  | http://www.seattle.gov/policecommission/        | http://www.seattle.gov/financedepartment/17proposedbudget/documents/CPC.pdf       |                                                                               | The Office of the Community Police Commission is the administrative and policy support entity of the Community Police Commission (CPC), the body charged with providing community oversight of the Settlement Agreement between the City of Seattle and the Department of Justice.                                                                                                                          | 
| LAW       | Law                                  |                                   | http://www.seattle.gov/financedepartment/17proposedbudget/documents/proposedbudgetexecsummary.pdf | http://www.seattle.gov/financedepartment/17proposedbudget/ | http://www.seattle.gov/financedepartment/1722proposedcip/ | http://www.seattle.gov/financedepartment/financialplans.htm | 26836380             | 181.60            | Peter S. Holmes          | City Attorney                       | http://www.seattle.gov/cityattorney             | http://www.seattle.gov/financedepartment/17proposedbudget/documents/LAW.pdf       |                                                                               | The Law Department serves as counsel to the City?s elected officials and agencies, and as the prosecutor in Seattle Municipal Court. Peter S. Homes, the Seattle City Attorney, is a nonpartisan elected official.                                                                                                                                                                                          | 
```