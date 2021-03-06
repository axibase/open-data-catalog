# Comment on North Fork Smith River 2017 Rulemaking

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/comment-on-north-fork-smith-river-2017-rulemaking) |
| Metadata | [Link](https://data.oregon.gov/api/views/ae4z-2pnm) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/ae4z-2pnm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/ae4z-2pnm/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | ae4z-2pnm |
| Name | Comment on North Fork Smith River 2017 Rulemaking |
| Created | 2017-01-13T01:19:51Z |
| Publication Date | 2017-02-14T00:45:24Z |

## Description

DEQ invites the public to submit comment on the North Fork Smith River 2017 rulemaking. Comments will be accepted 1/13/17 through 4 p.m. 2/28/17. Comments submitted outside this period will not be considered.

## Columns

```ls
| Included | Schema Type | Field Name          | Name                | Data Type | Render Type |
| ======== | =========== | =================== | =================== | ========= | =========== |
| Yes      | series tag  | first_name          | First Name          | text      | text        |
| Yes      | series tag  | last_name           | Last Name           | text      | text        |
| Yes      | series tag  | email               | Email               | email     | email       |
| Yes      | series tag  | organization        | Organization        | text      | text        |
| Yes      | series tag  | state               | State               | text      | text        |
| Yes      | series tag  | comment             | Comment             | html      | html        |
| Yes      | series tag  | additional_document | Additional document | document  | document    |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ae4z-2pnm d:2017-01-01T00:00:00.000Z t:first_name=Angelina t:email=Eena_b@hotmail.com t:state=Oregon t:last_name=Mcclean t:comment="I support the proposed rules for the North Fork of the Smith river. Thank you." m:row_number.ae4z-2pnm=1

series e:ae4z-2pnm d:2017-01-01T00:00:00.000Z t:first_name=Katharine t:organization="Eastside Portland Air Coalition" t:email=katharinesalzmann@gmail.com t:state=Or t:last_name=Salzmann t:comment="Hello, I support any and all moves by the DEQ and EQC to strengthen rules that will empower DEQ staff to fully implement their primary mission of restoring, maintaining and enhancing the quality of Oregon's air, land and water. And by &quot;quality&quot; of course we mean air, land and water that fully support the health of all species and the ecosystems where they reside.  Anything that prevents the further degradation of our essential sources of clean air, water &amp; soil will have my full support. Any moves by the DEQ &amp; EQC to restore our essential sources of air, water &amp; soil have my full support. I want to DEQ under the wing of the EQC to have real authority &amp; the chutzpah to exercise the vigorous clean up and prevention of pollution generated by human activities. I support the OMW designation for the North Fork of the Smith River." m:row_number.ae4z-2pnm=2

series e:ae4z-2pnm d:2017-01-01T00:00:00.000Z t:first_name=Kirsten t:organization="Oregon State University" t:email=kirsten.wert@gmail.com t:state=OR t:last_name=Wert t:comment="YAY! I heartily approve this designation. We need more protections from dredging and other destructive practices for the streams and rivers of Oregon." m:row_number.ae4z-2pnm=3
```

## Meta Commands

```ls
metric m:row_number.ae4z-2pnm p:long l:"Row Number"

entity e:ae4z-2pnm l:"Comment on North Fork Smith River 2017 Rulemaking" t:url=https://data.oregon.gov/api/views/ae4z-2pnm

property e:ae4z-2pnm t:meta.view v:id=ae4z-2pnm v:averageRating=0 v:name="Comment on North Fork Smith River 2017 Rulemaking"

property e:ae4z-2pnm t:meta.view.owner v:id=44u9-wper v:screenName="MT Oregon DEQ" v:displayName="MT Oregon DEQ"

property e:ae4z-2pnm t:meta.view.tableauthor v:id=44u9-wper v:screenName="MT Oregon DEQ" v:roleName=editor v:displayName="MT Oregon DEQ"
```

## Top Records

```ls
| first_name | last_name | email                       | organization                          | state  | comment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | additional_document      | 
| ========== | ========= | =========================== | ===================================== | ====== | ================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ======================== | 
| Angelina   | Mcclean   | Eena_b@hotmail.com          |                                       | Oregon | I support the proposed rules for the North Fork of the Smith river. Thank you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | [null, null, null, null] | 
| Katharine  | Salzmann  | katharinesalzmann@gmail.com | Eastside Portland Air Coalition       | Or     | Hello, I support any and all moves by the DEQ and EQC to strengthen rules that will empower DEQ staff to fully implement their primary mission of restoring, maintaining and enhancing the quality of Oregon's air, land and water. And by "quality" of course we mean air, land and water that fully support the health of all species and the ecosystems where they reside. Anything that prevents the further degradation of our essential sources of clean air, water & soil will have my full support. Any moves by the DEQ & EQC to restore our essential sources of air, water & soil have my full support. I want to DEQ under the wing of the EQC to have real authority & the chutzpah to exercise the vigorous clean up and prevention of pollution generated by human activities. I support the OMW designation for the North Fork of the Smith River. | [null, null, null, null] | 
| Kirsten    | Wert      | kirsten.wert@gmail.com      | Oregon State University               | OR     | YAY! I heartily approve this designation. We need more protections from dredging and other destructive practices for the streams and rivers of Oregon.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | [null, null, null, null] | 
| Sunny      | Bourdon   | sunny.bourdon@gmail.com     | Native Fish Society, Brookings Oregon | Oregon | I support the designation of the North Fork Smith River as an Outstanding Water Resource. The pristine headwaters of this remarkable watershed, the rare ecosystems, and the communities downstream deserve the protection of this rulemaking. Thank you                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | [null, null, null, null] | 
| Sunny      | Bourdon   | sunny.bourdon@gmail.com     | Native Fish Society, Brookings Oregon | Oregon | I support the designation of the North Fork Smith River as an Outstanding Water Resource. Downstream residents, rare ecosystems, fish and wildlife, and our future generations deserve the protection of these pristine headwaters of a remarkable watershed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | [null, null, null, null] | 
| David      | Hoffman   | fixit@efn.org               | Citizen                               | OR     | Water is life. Protect it! Plus, keep Nestle from bottling it for profit.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | [null, null, null, null] | 
| Denise     | Christine | snawg@gmail.com             |                                       | Oregon | At this point in human evolution, and considering the population pressures sure to hit the PNW over the next 100 years, it is more important than ever that we protect our natural resources. Wars are already being fought over water around the world. Please protect our water resources by designating the North Fork of the Smith River as an Outstanding Resource Water.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | [null, null, null, null] | 
| Zachary    | Collier   | zach@nwrafting.ocm          | Northwest Rafting Company             | OR     | I have kayaked and rafted the North Fork of the Smith River as well as it's tributaries Diamond Creek and Baldface Creek. These are among the most beautiful and clean rivers in the world. I've read the state statute regarding "Outstanding Resource Waters Policy" and can attest to the high quality of these waters. I can't imagine a higher quality waters.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | [null, null, null, null] | 
| Zachary    | Collier   | zach@nwrafting.ocm          | Northwest Rafting Company             | OR     | I have kayaked and rafted the North Fork of the Smith River as well as it's tributaries Diamond Creek and Baldface Creek. These are among the most beautiful and clean rivers in the world. I've read the state statute regarding "Outstanding Resource Waters Policy" and can attest to the high quality of these waters. I can't imagine a higher quality waters.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | [null, null, null, null] | 
| Zachary    | Collier   | zcollier@gmail.com          | Northwest Rafting Company             | OR     | I have kayaked and rafted the North Fork of the Smith River as well as it's tributaries Diamond Creek and Baldface Creek. These are among the most beautiful and clean rivers in the world. I've read the state statute regarding "Outstanding Resource Waters Policy" and can attest to the high quality of these waters. I can't imagine a higher quality waters.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | [null, null, null, null] | 
```