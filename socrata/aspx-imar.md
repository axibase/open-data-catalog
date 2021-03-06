# No. of Transactions VS No. of Customers For FY 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/no-of-transactions-vs-no-of-customers-for-fy-2014) |
| Metadata | [Link](https://data.ct.gov/api/views/aspx-imar) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/aspx-imar/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/aspx-imar/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | aspx-imar |
| Name | No. of Transactions VS No. of Customers For FY 2014 |
| Attribution | Department of Motor Vehicles |
| Category | Transportation |
| Tags | dmv |
| Created | 2014-10-01T12:44:47Z |
| Publication Date | 2014-10-02T20:02:32Z |

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                | Data Type | Render Type |
| ======== | ============== | ================== | =================== | ========= | =========== |
| Yes      | series tag     | branch             | BRANCH              | text      | text        |
| Yes      | numeric metric | no_of_transactions | No. of Transactions | number    | number      |
| Yes      | numeric metric | no_of_customers    | No. of Customers    | number    | number      |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:aspx-imar d:2014-01-01T00:00:00.000Z t:branch="Middletown PLC" m:no_of_transactions=9065 m:no_of_customers=8574

series e:aspx-imar d:2014-01-01T00:00:00.000Z t:branch="Milford PLC" m:no_of_transactions=13506 m:no_of_customers=12757

series e:aspx-imar d:2014-01-01T00:00:00.000Z t:branch="Derby PLC" m:no_of_transactions=16588 m:no_of_customers=15325
```

## Meta Commands

```ls
metric m:no_of_transactions p:integer l:"No. of Transactions" t:dataTypeName=number

metric m:no_of_customers p:integer l:"No. of Customers" t:dataTypeName=number

entity e:aspx-imar l:"No. of Transactions VS No. of Customers For FY 2014" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/aspx-imar

property e:aspx-imar t:meta.view d:2017-09-25T07:27:53.302Z v:averageRating=0 v:name="No. of Transactions VS No. of Customers For FY 2014" v:attribution="Department of Motor Vehicles" v:attributionLink=http://www.ct.gov/dmv v:id=aspx-imar v:category=Transportation

property e:aspx-imar t:meta.view.owner d:2017-09-25T07:27:53.302Z v:displayName=APatel v:id=fd5k-6njr v:screenName=APatel

property e:aspx-imar t:meta.view.tableauthor d:2017-09-25T07:27:53.302Z v:displayName=APatel v:roleName=editor v:id=fd5k-6njr v:screenName=APatel
```

## Top Records

```ls
| branch           | no_of_transactions | no_of_customers | 
| ================ | ================== | =============== | 
| Middletown PLC   | 9065               | 8574            | 
| Milford PLC      | 13506              | 12757           | 
| Derby PLC        | 16588              | 15325           | 
| Cheshire         | 17280              | 17280           | 
| Putnam SAT       | 27653              | 24927           | 
| Northwestern SAT | 42873              | 37623           | 
| Old Saybrook     | 68886              | 58066           | 
| Enfield          | 76737              | 66543           | 
| Norwich          | 77372              | 68628           | 
| Willimantic      | 95083              | 87306           | 
```