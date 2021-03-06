# Current Medallion Drivers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-medallion-drivers-acc0e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/s22f-jsd4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/s22f-jsd4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/s22f-jsd4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | s22f-jsd4 |
| Name | Current Medallion Drivers |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | tlc, taxi, medallion, cab, license, driver |
| Created | 2012-09-06T14:30:32Z |
| Publication Date | 2013-04-24T19:39:45Z |

## Description

This dataset is no longer being updated by the New York City Taxi and Limousine Commission. Please update your links to the links listed below. Thank you.

Medallion Drivers - Active:
https://data.cityofnewyork.us/Transportation/Medallion-Drivers-Active/n776-dsqy

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type     | Render Type   |
| ======== | =========== | ======================= | ======================= | ============= | ============= |
| Yes      | time        | date_updated            | Date Updated            | calendar_date | calendar_date |
| Yes      | series tag  | license_number          | License Number          | text          | text          |
| Yes      | series tag  | name_of_licensee        | Name of Licensee        | text          | text          |
| Yes      | series tag  | license_type            | License Type            | text          | text          |
| Yes      | series tag  | license_expiration_date | License Expiration Date | text          | text          |
```

## Time Field

```ls
Value = date_updated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:s22f-jsd4 d:2012-09-06T00:00:00.000Z t:license_expiration_date=08/06/2014 t:license_type="MEDALLION TAXI DRIVER" t:license_number=427586 t:name_of_licensee=FILS-AIME,CHARITE m:row_number.s22f-jsd4=1

series e:s22f-jsd4 d:2012-09-06T00:00:00.000Z t:license_expiration_date=05/10/2013 t:license_type="MEDALLION TAXI DRIVER" t:license_number=5195097 t:name_of_licensee=TOKI,ABDELHAK m:row_number.s22f-jsd4=2

series e:s22f-jsd4 d:2012-09-06T00:00:00.000Z t:license_expiration_date=10/30/2012 t:license_type="MEDALLION TAXI DRIVER" t:license_number=5054307 t:name_of_licensee=SINGH,RAJDEEP m:row_number.s22f-jsd4=3
```

## Meta Commands

```ls
metric m:row_number.s22f-jsd4 p:long l:"Row Number"

entity e:s22f-jsd4 l:"Current Medallion Drivers" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/s22f-jsd4

property e:s22f-jsd4 t:meta.view d:2017-06-09T14:00:18.419Z v:id=s22f-jsd4 v:category=Transportation v:averageRating=0 v:name="Current Medallion Drivers" v:attribution="Taxi and Limousine Commission (TLC)"

property e:s22f-jsd4 t:meta.view.owner d:2017-06-09T14:00:18.419Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"

property e:s22f-jsd4 t:meta.view.tableauthor d:2017-06-09T14:00:18.419Z v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1496414226 v:displayName="NYC OpenData"
```

## Top Records

```ls
| date_updated        | license_number | name_of_licensee  | license_type          | license_expiration_date | 
| =================== | ============== | ================= | ===================== | ======================= | 
| 2012-09-06T00:00:00 | 427586         | FILS-AIME,CHARITE | MEDALLION TAXI DRIVER | 08/06/2014              | 
| 2012-09-06T00:00:00 | 5195097        | TOKI,ABDELHAK     | MEDALLION TAXI DRIVER | 05/10/2013              | 
| 2012-09-06T00:00:00 | 5054307        | SINGH,RAJDEEP     | MEDALLION TAXI DRIVER | 10/30/2012              | 
| 2012-09-06T00:00:00 | 5206638        | ANDERSON,SVETLANA | MEDALLION TAXI DRIVER | 09/12/2013              | 
| 2012-09-06T00:00:00 | 5438593        | POPKO,TIMOTHY,A   | MEDALLION TAXI DRIVER | 07/11/2013              | 
| 2012-09-06T00:00:00 | 5026436        | AHMED,KHANDAKER,S | MEDALLION TAXI DRIVER | 01/24/2014              | 
| 2012-09-06T00:00:00 | 5348440        | SATOROV,NOSIRDJON | MEDALLION TAXI DRIVER | 01/19/2013              | 
| 2012-09-06T00:00:00 | 5150179        | NASIM,MOHAMMAD,D  | MEDALLION TAXI DRIVER | 10/31/2013              | 
| 2012-09-06T00:00:00 | 460974         | RAJA,ALTAF        | MEDALLION TAXI DRIVER | 04/28/2013              | 
| 2012-09-06T00:00:00 | 5211857        | DIALLO,IBRAHIMA,S | MEDALLION TAXI DRIVER | 02/28/2014              | 
```