# Maryland Funding FY11 Payments Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-funding-fy11-payments-data-6fda1) |
| Metadata | [Link](https://data.maryland.gov/api/views/na74-jvan) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/na74-jvan/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/na74-jvan/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | na74-jvan |
| Name | Maryland Funding FY11 Payments Data |
| Attribution | Maryland Department of Budget and Management; Maryland Department of Information Technology |
| Category | Budget |
| Tags | spending, budget, vendor, payments |
| Created | 2013-01-18T17:42:56Z |
| Publication Date | 2014-08-22T15:52:22Z |

## Description

This dataset contains summary information on payments made to vendors that received $25,000 or more in fiscal year 2012.  The data is also published and searchable online on the www.spending.dbm.maryland.gov website.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | time           | year        | Year        | number    | text        |
| Yes      | series tag     | agency_name | Agency Name | text      | text        |
| Yes      | series tag     | vendor_name | Vendor Name | text      | text        |
| Yes      | series tag     | vendor_zip  | Vendor Zip  | text      | text        |
| Yes      | numeric metric | amount      | Amount      | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:na74-jvan d:2011-01-01T00:00:00.000Z t:agency_name="DHMH-GENERAL ACCOUNTING" t:vendor_name="PROCOAT, INC." t:vendor_zip=21802 m:amount=2390

series e:na74-jvan d:2011-01-01T00:00:00.000Z t:agency_name="ENERGY ADMINISTRATION" t:vendor_name=BITHENERGY,INC. t:vendor_zip=21201 m:amount=42750.2

series e:na74-jvan d:2011-01-01T00:00:00.000Z t:agency_name="MILITARY DEPARTMENT" t:vendor_name="SPRINT PCS" t:vendor_zip=60197 m:amount=28470.56
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:na74-jvan l:"Maryland Funding FY11 Payments Data" t:attribution="Maryland Department of Budget and Management; Maryland Department of Information Technology" t:url=https://data.maryland.gov/api/views/na74-jvan

property e:na74-jvan t:meta.view d:2017-09-25T07:31:01.052Z v:averageRating=0 v:name="Maryland Funding FY11 Payments Data" v:attribution="Maryland Department of Budget and Management; Maryland Department of Information Technology" v:attributionLink=http://www.spending.dbm.maryland.gov v:id=na74-jvan v:category=Budget

property e:na74-jvan t:meta.view.license d:2017-09-25T07:31:01.052Z v:name="Public Domain"

property e:na74-jvan t:meta.view.owner d:2017-09-25T07:31:01.052Z v:displayName="Teri Greene" v:id=kkuv-jqse v:screenName="Teri Greene"

property e:na74-jvan t:meta.view.tableauthor d:2017-09-25T07:31:01.052Z v:displayName="Teri Greene" v:roleName=editor v:id=kkuv-jqse v:screenName="Teri Greene"
```

## Top Records

```ls
| year | agency_name                     | vendor_name               | vendor_zip | amount    | 
| ==== | =============================== | ========================= | ========== | ========= | 
| 2011 | DHMH-GENERAL ACCOUNTING         | PROCOAT, INC.             | 21802      | 2390      | 
| 2011 | ENERGY ADMINISTRATION           | BITHENERGY,INC.           | 21201      | 42750.2   | 
| 2011 | MILITARY DEPARTMENT             | SPRINT PCS                | 60197      | 28470.56  | 
| 2011 | MILITARY DEPARTMENT             | ST AGNES HEALTHCARE       | 21229      | 134912.05 | 
| 2011 | STATE HIGHWAY ADMIN             | FRIENDS AWARE INC         | 21502      | 3265.5    | 
| 2011 | MARYLAND TRANSIT ADMINISTRATION | WMATA                     | 20001      | 757326.37 | 
| 2011 | MILITARY DEPARTMENT             | HUMANIM INC               | 21046      | 12423.71  | 
| 2011 | DHMH-GENERAL ACCOUNTING         | CINTAS CORP #042          | 45263      | 7269.21   | 
| 2011 | DEPARTMENT OF HUMAN RESOURCES   | PENINSULA CARDIOLOGY ASSC | 21804      | 943       | 
| 2011 | STATE HIGHWAY ADMIN             | THE AUTO BARN INC         | 21230      | 555       | 
```