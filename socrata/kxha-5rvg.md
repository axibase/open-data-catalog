# Toxics Water Quality Standards Comments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/toxics-water-quality-standards-comments-4920f) |
| Metadata | [Link](https://data.oregon.gov/api/views/kxha-5rvg) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/kxha-5rvg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/kxha-5rvg/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | kxha-5rvg |
| Name | Toxics Water Quality Standards Comments |
| Created | 2013-08-09T17:43:21Z |
| Publication Date | 2013-09-19T21:37:35Z |

## Description

Corrections and Clarifications to Toxics Water Quality Standards Comment Form

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | first_name           | First Name           | text      | text        |
| Yes      | series tag  | last_name            | Last Name            | text      | text        |
| Yes      | series tag  | email_address        | Email Address        | email     | email       |
| Yes      | series tag  | organization         | Organization         | text      | text        |
| Yes      | series tag  | state                | State                | text      | text        |
| Yes      | series tag  | comment              | Comment              | html      | html        |
| Yes      | series tag  | additional_documents | Additional Documents | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kxha-5rvg d:2013-09-19T13:54:47.000Z t:first_name=Kathleen t:organization=EPA t:additional_documents.file_id=-JbHnoaLevQSurKNN5yNF_QN4bpCNCbFyNSuVK6tzog t:additional_documents.filename="4  EPA comment ltr 9 18 2013.pdf" t:additional_documents.content_type=application/pdf t:additional_documents.size=240489 t:state=NA t:last_name=Collins t:comment="See attached letter." t:email_address=collins.kathleen@epa.gov m:row_number.kxha-5rvg=1

series e:kxha-5rvg d:2013-09-20T16:47:38.000Z t:first_name=Kathryn t:organization="Northwest Pulp & Paper Assn." t:additional_documents.file_id=xnMWbpc3wKfv1M45MGTBOaZlnnyxorWrhJYTgcZaRXY t:additional_documents.filename="NWPPPA Cmt DEQ Toxics WQS RM 9- 20-13.pdf" t:additional_documents.content_type=application/pdf t:additional_documents.size=96895 t:state=OR t:last_name=VanNatta t:comment="See attached comment letter dated September 20, 2013 from NWPPA.  Thank you." t:email_address=Kathryn@nwpulpandpaper.org m:row_number.kxha-5rvg=2

series e:kxha-5rvg d:2014-10-10T00:36:03.000Z t:first_name=clothWaxy t:organization=clothWaxy t:comment="http://groglug.fulba.com/magazin-list.html &Ntilde;&hellip;&ETH;&deg;&ETH;&raquo;&ETH;&deg;&Ntilde;&sbquo;&Ntilde;&lsaquo; &Ntilde;&hellip;&ETH;&plusmn; http://veldsur.fulba.com/vodolazki-dlya-detey-kupit.html &ETH;&frac34;&Ntilde;&circ;&ETH;&cedil; &ETH;&frac14;&ETH;&deg;&ETH;&frac14;&Ntilde;&fnof;&ETH;&raquo;&Ntilde;&#65533; &ETH;&iquest;&ETH;&micro;&ETH;&iquest;&ETH;&raquo;&ETH;&frac34;&ETH;&frac14;  [url=http://warpdut.fulba.com/francuzskiy-internet-magazin-odezhdy.html] richenna [/url] <a target=""_blank"" href=""http://warpdut.fulba.com/odezhda-bystraya-dostavka.html""> blu byblos</a>" t:email_address=somersanog@ziza.ru m:row_number.kxha-5rvg=3
```

## Meta Commands

```ls
metric m:row_number.kxha-5rvg p:long l:"Row Number"

entity e:kxha-5rvg l:"Toxics Water Quality Standards Comments" t:url=https://data.oregon.gov/api/views/kxha-5rvg

property e:kxha-5rvg t:meta.view v:id=kxha-5rvg v:averageRating=0 v:name="Toxics Water Quality Standards Comments"

property e:kxha-5rvg t:meta.view.owner v:id=7f2t-e4kt v:screenName="Mary-Frances Makichen" v:displayName="Mary-Frances Makichen"

property e:kxha-5rvg t:meta.view.tableauthor v:id=7f2t-e4kt v:screenName="Mary-Frances Makichen" v:displayName="Mary-Frances Makichen"
```

## Top Records

```ls
| :updated_at | first_name                                  | last_name                                                                                                   | email_address              | organization                                | state                                       | comment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | additional_documents                                                                                             | 
| =========== | =========================================== | =========================================================================================================== | ========================== | =========================================== | =========================================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ================================================================================================================ | 
| 1379598887  | Kathleen                                    | Collins                                                                                                     | collins.kathleen@epa.gov   | EPA                                         | NA                                          | See attached letter.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | [application/pdf, -JbHnoaLevQSurKNN5yNF_QN4bpCNCbFyNSuVK6tzog, 4 EPA comment ltr 9 18 2013.pdf, 240489]          | 
| 1379695658  | Kathryn                                     | VanNatta                                                                                                    | Kathryn@nwpulpandpaper.org | Northwest Pulp & Paper Assn.                | OR                                          | See attached comment letter dated September 20, 2013 from NWPPA. Thank you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | [application/pdf, xnMWbpc3wKfv1M45MGTBOaZlnnyxorWrhJYTgcZaRXY, NWPPPA Cmt DEQ Toxics WQS RM 9- 20-13.pdf, 96895] | 
| 1412901363  | clothWaxy                                   |                                                                                                             | somersanog@ziza.ru         | clothWaxy                                   |                                             | http://groglug.fulba.com/magazin-list.html ???????????? ???? http://veldsur.fulba.com/vodolazki-dlya-detey-kupit.html ?????? ???????????? ???????????? [url=http://warpdut.fulba.com/francuzskiy-internet-magazin-odezhdy.html] richenna [/url] blu byblos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | [null, null, null, null]                                                                                         | 
| 1423183232  | Cartier love jewellery lady white gold cost | http://theshanzhi.wordpress.com/                                                                            | wccnjkuyzq@hotmail.com     | Cartier love jewellery lady white gold cost | Cartier love jewellery lady white gold cost | How to restore computer when my computer just randomly shuts off? Cartier love jewellery lady white gold cost http://theshanzhi.wordpress.com/                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | [null, null, null, null]                                                                                         | 
| 1459668250  | ? ???? ??? ??? ??????                       | ? ??? ??? ??? ??? ??????                                                                                    | pacmanspb@mail.ru          | azabedrab                                   |                                             | http://google.com                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | [null, null, null, null]                                                                                         | 
| 1460894602  | ? ??? ??????? ??? ??????? ??                | ? ??? ??? ??? ??? ??????                                                                                    | mg.solo-solo@mail.ru       | soloallen                                   |                                             | http://google.com mg.solo-solo@mail.ru                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | [null, null, null, null]                                                                                         | 
| 1466418068  | vintage cartier love bracelet               | http://www.thislovebangle.cn/                                                                               | gnpizc@gmail.com           | vintage cartier love bracelet               | vintage cartier love bracelet               | Our tenth wedding anniversary is fast approaching! I would finally make a photobook of our wedding pictures, and hopefully add some new memories? vintage cartier love bracelet http://www.thislovebangle.cn/                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | [null, null, null, null]                                                                                         | 
| 1466419291  | imitazioni orologi cartier oro              | http://www.ventemarquemontre.com/it/replica-cl?-de-cartier-40mm-18k-white-gold-watch-for-men-wgcl0006-p644/ | njxgpsjmgc@gmail.com       | imitazioni orologi cartier oro              | imitazioni orologi cartier oro              | There were massive changes found in the North Atlantic Ocean during this period with a gyre of Arctic polar water moving as far south as Spain. This indicated that the Gulf Stream and NAD were moving towards Spain instead of Norway and the Arctic. This massive energy loss towards to the Arctic Ocean easily caused this event, but what caused this has been suggested to be melting ice sheets from North America into the Atlantic Ocean. This likely rules out a comet because how could one change ocean circulation especially over 1000 years with just one impact. Dust would be just around for a few years, so the atmosphere would warm back up again soon after. imitazioni orologi cartier oro http://www.ventemarquemontre.com/it/replica-cl?-de-cartier-40mm-18k-white-gold-watch-for-men-wgcl0006-p644/ | [null, null, null, null]                                                                                         | 
| 1466427058  | cartier love bracelet men replica           | http://www.islovebracelets.com/tag/cartier-rose-gold-bracelet/                                              | migrggp@gmail.com          | cartier love bracelet men replica           | cartier love bracelet men replica           | Love your site and shared on facebook and liked eddieandevas. Love the bath bomb. cartier love bracelet men replica http://www.islovebracelets.com/tag/cartier-rose-gold-bracelet/                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | [null, null, null, null]                                                                                         | 
| 1470442729  | arpels van cleef                            | http://www.simulationschmuck.net/alhambra-necklace-replica-c3_87.html                                       | lrtmxd@gmail.com           | arpels van cleef                            | arpels van cleef                            | cartierlovejesduas Men with a strong sense of self esteem are not threatened by feminism. arpels van cleef                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | [null, null, null, null]                                                                                         | 
```