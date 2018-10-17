# Calendar for Energy Efficient Schools Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/calendar-for-energy-efficient-schools-program-26910) |
| Metadata | [Link](https://data.oregon.gov/api/views/p2jz-uvs7) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/p2jz-uvs7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/p2jz-uvs7/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | p2jz-uvs7 |
| Name | Calendar for Energy Efficient Schools Program |
| Attribution | Oregon Department of Energy - School Program |
| Tags | schools, energy, efficiency, calendar |
| Created | 2010-11-16T22:14:21Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | time        | date              | Date              | calendar_date | calendar_date |
| Yes      | series tag  | time              | Time              | text          | text          |
| Yes      | series tag  | event_name        | Event Name        | text          | text          |
| Yes      | series tag  | event_type        | Event Type        | text          | text          |
| Yes      | series tag  | event_description | Event Description | text          | text          |
| Yes      | series tag  | event_link        | Event Link        | url           | url           |
| Yes      | series tag  | contact_1         | Contact           | text          | text          |
| Yes      | series tag  | contact_2         | Contact #         | phone         | phone         |
| Yes      | series tag  | contact_email     | Contact Email     | email         | email         |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:p2jz-uvs7 d:2010-11-18T00:00:00.000Z t:time="9:00am - 10:00" t:phone_number=7077789930 t:contact_email=umsken@comcast.net t:event_link="https://lpbenergy.webex.com/lpbenergy/j.php?ED=143388032&UID=0&PW=NYmQ3MTdlOTZj&RT=MiM0" t:contact_1="Ken Egel" t:event_type=Demo t:event_description="Learn more about the Utility Manager Pro software for managing your energy use
Audio conference
------------------------------------------------------- 
Call-in number: 1-650-429-3300 
Access code: 808 976 469 

To join the online meeting 
------------------------------------------------------- 
1. Go to https://lpbenergy.webex.com/lpbenergy/j.php?ED=143388032&UID=0&PW=NYmQ3MTdlOTZj&RT=MiM0 
2. Enter your name and email address. 
3. Enter the meeting password: UMdemo1 
4. Click ""Join Now""." t:event_name="Utility Manager Pro Webinar" m:row_number.p2jz-uvs7=1

series e:p2jz-uvs7 d:2010-12-07T00:00:00.000Z t:time="9:30am -10:30" t:phone_number=5033785054 t:contact_email=jp.batmale@odoe.state.or.us t:contact_1="JP Batmale" t:event_type=Training t:event_description="Start - 9:30am. Find out how to use your existing data on the School Program's database to reduce your energy consumption and costs today." t:event_name="School Program Database Training" m:row_number.p2jz-uvs7=2

series e:p2jz-uvs7 d:2010-12-03T00:00:00.000Z t:time="9:00am - 11:30" t:phone_number=5033785054 t:contact_email=jp.batmale@odoe.state.or.us t:contact_1="JP Batmale" t:event_type=Training t:event_description="Start - 9am. For schools with Utility Manager Pro, learn the basics of creating reports. Training is free. Contact ODOE to enroll." t:event_name="Utility Manager Pro Training" m:row_number.p2jz-uvs7=3
```

## Meta Commands

```ls
metric m:row_number.p2jz-uvs7 p:long l:"Row Number"

entity e:p2jz-uvs7 l:"Calendar for Energy Efficient Schools Program" t:attribution="Oregon Department of Energy - School Program" t:url=https://data.oregon.gov/api/views/p2jz-uvs7

property e:p2jz-uvs7 t:meta.view v:id=p2jz-uvs7 v:attributionLink=http://www.oregon.gov/ENERGY/CONS/SB1149/Schools/ v:averageRating=0 v:name="Calendar for Energy Efficient Schools Program" v:attribution="Oregon Department of Energy - School Program"

property e:p2jz-uvs7 t:meta.view.license v:name="Public Domain"

property e:p2jz-uvs7 t:meta.view.owner v:id=dqn3-kzqx v:screenName=allan.bates v:displayName=allan.bates
```

## Top Records

```ls
| date                | time           | event_name                                                        | event_type | event_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | event_link                                                                                      | contact_1       | contact_2          | contact_email               | 
| =================== | ============== | ================================================================= | ========== | ===================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =============================================================================================== | =============== | ================== | =========================== | 
| 2010-11-18T00:00:00 | 9:00am - 10:00 | Utility Manager Pro Webinar                                       | Demo       | Learn more about the Utility Manager Pro software for managing your energy use Audio conference ------------------------------------------------------- Call-in number: 1-650-429-3300 Access code: 808 976 469 To join the online meeting ------------------------------------------------------- 1. Go to https://lpbenergy.webex.com/lpbenergy/j.php?ED=143388032&UID=0&PW=NYmQ3MTdlOTZj&RT=MiM0 2. Enter your name and email address. 3. Enter the meeting password: UMdemo1 4. Click "Join Now".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | [https://lpbenergy.webex.com/lpbenergy/j.php?ED=143388032&UID=0&PW=NYmQ3MTdlOTZj&RT=MiM0, null] | Ken Egel        | [7077789930, null] | umsken@comcast.net          | 
| 2010-12-07T00:00:00 | 9:30am -10:30  | School Program Database Training                                  | Training   | Start - 9:30am. Find out how to use your existing data on the School Program's database to reduce your energy consumption and costs today.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | [null, null]                                                                                    | JP Batmale      | [5033785054, null] | jp.batmale@odoe.state.or.us | 
| 2010-12-03T00:00:00 | 9:00am - 11:30 | Utility Manager Pro Training                                      | Training   | Start - 9am. For schools with Utility Manager Pro, learn the basics of creating reports. Training is free. Contact ODOE to enroll.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | [null, null]                                                                                    | JP Batmale      | [5033785054, null] | jp.batmale@odoe.state.or.us | 
| 2010-12-02T00:00:00 | 9:00am - 11:30 | Utility Manager Pro Training                                      | Training   | Start - 9am. For schools with Utility Manager Pro, learn the basics of data entry. Training is free. Topic: Utility Manager Pro Training #1: ODOE Date: Thursday, December 2, 2010 Time: 9:00 am, Pacific Standard Time Meeting Number: 801 451 679 Meeting Password: UMtraining1 Please click the link below to join the meeting. ------------------------------------------------------- To join the online meeting ------------------------------------------------------- 1. Go to https://lpbenergy.webex.com/lpbenergy/j.php?ED=141668377&UID=0&PW=NN2YzNzczMDAx&RT=MiM0 2. Enter your name and email address. 3. Enter the meeting password: UMtraining1 4. Click "Join Now". ------------------------------------------------------- To join the audio conference ------------------------------------------------------- Call-in number: 1-650-429-3300 Access code: 801 451 679 This training is focused on data entry and database maintenance ("Getting data into of Utility Manager"). I expect the training to take 2 - 2.5 hours. Below is a link to some sample bills that Beaverton SD provided me. Please distribute this link to expected participants of the session and ask them to download and print the sample bills because we'll be referring to them during the training. http://www.box.net/shared/static/490bsnuxxj.pdf Thanks, and please let me know if you have any questions. Ken Ken Egel Utility Management Services 707-778-9930 http://www.utilityaccounting.com | [null, null]                                                                                    | JP Batmale      | [5033785054, null] | jp.batmale@odoe.state.or.us | 
| 2010-11-30T00:00:00 | 1:00pm - 2:30  | School Dude's Utility Direct Webinar                              | Demo       | Start - 1pm. Learn more about School Dude's Utility Direct an online utility tracking, management, analysis and reporting tool. Click this link to find out more: http://discover.schooldude.com/forms/2010-11-OR-UDStateWebcast                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | [null, null]                                                                                    | Mrs. Scott Hair | [9193958421, null] | shair@schooldude.com        | 
| 2010-11-22T00:00:00 | 9:30am - 10:30 | School Program Database Training                                  | Training   | Start - 9:30am. Find out how to use your existing data on the School Program's database to reduce your energy consumption and costs today.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | [null, null]                                                                                    | JP Batmale      | [5033785054, null] | jp.batmale@odoe.state.or.us | 
| 2010-12-20T00:00:00 | 9:30am -10:30  | School Program Database Training                                  | Training   | Start - 9:30am. Find out how to use your existing data on the School Program's database to reduce your energy consumption and costs today.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | [null, null]                                                                                    | JP Batmale      | [5033785054, null] | jp.batmale@odoe.state.or.us | 
| 2011-02-16T00:00:00 | 7:30am -12pm   | PGE Seminar: Industrial Fan Systems - WILSONVILLE                 | Training   | Start - 7:30am. This half-day free seminar provides an overview of the principles of industrial fan, blower, and dust collection systems and how to save energy without reducing production. To register, send an email to PGE.Seminars@pgn.com or call 503-464-8020. Visit our website at PortlandGeneral.com/Classes for a complete class listing. http://www.portlandgeneral.com/business/news_classes/classes/docs/class_schedule.pdf                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | [http://www.portlandgeneral.com/classes, null]                                                  |                 | [null, null]       | PGE.Seminars@pgn.com        | 
| 2011-02-17T00:00:00 | 7:30am -12pm   | PGE Seminar: Industrial Pump Systems - WILSONVILLE                | Training   | Start - 7:30am. This free half-day seminar provides an understanding of motors, pumps and variable-speed drives that can reduce energy use and improve process control in systems with varying loads. To register, send an email to PGE.Seminars@pgn.com or call 503-464-8020. Visit our website at PortlandGeneral.com/Classes for a complete class listing.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | [http://www.portlandgeneral.com/classes, null]                                                  |                 | [null, null]       | PGE.Seminars@pgn.com        | 
| 2011-01-27T00:00:00 | 7:30am -12pm   | PGE Seminar: Fundamentals of Energy & Managing Costs PORTLAND, OR | Training   | Start - 7:30am. This free half-day seminar provides an overview of electricity concepts and the components of a utility electrical system, from generation to distribution. It offers best practices for energy using equipment and operations, as well as maximizing operating improvements and dollar savings from energy efficiency projects. To register, send an email to PGE.Seminars@pgn.com or call 503-464-8020. Visit our website at PortlandGeneral.com/Classes for a complete class listing. http://www.portlandgeneral.com/business/news_classes/classes/docs/class_schedule.pdf                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | [http://www.portlandgeneral.com/classes, null]                                                  |                 | [null, null]       | PGE.Seminars@pgn.com        | 
```