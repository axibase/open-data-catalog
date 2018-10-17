# Recreation Spring Programs 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recreation-spring-programs-2016) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/imqa-htns) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/imqa-htns/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/imqa-htns/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | imqa-htns |
| Name | Recreation Spring Programs 2016 |
| Attribution | Montgomery County, MD |
| Category | Community/Recreation |
| Tags | programs, activities, swimming, volleyball, ping pong |
| Created | 2016-02-23T22:59:20Z |
| Publication Date | 2016-03-10T18:27:14Z |

## Description

List of all programs (Register here: https://apm.activecommunities.com/montgomerycounty/Home) to include Aquatics, Senior and Tiny Tot Activities, Dance, Martial Arts, Music,Arts and Crafts and more.    Dates, Times, Age Requirements, and Locations included.
Update Frequency:  Annually

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | session            | Session            | text      | text        |
| Yes      | series tag     | primary_category   | Primary Category   | text      | text        |
| Yes      | series tag     | secondary_category | Secondary Category | text      | text        |
| Yes      | series tag     | activityname       | ActivityName       | text      | text        |
| Yes      | series tag     | description        | Description        | text      | text        |
| Yes      | series tag     | activitynumber     | ActivityNumber     | text      | text        |
| Yes      | series tag     | ages               | Ages               | text      | text        |
| Yes      | series tag     | location           | Location           | text      | text        |
| No       |                | address            | Address            | text      | text        |
| Yes      | series tag     | city               | City               | text      | text        |
| Yes      | series tag     | state              | State              | text      | text        |
| Yes      | series tag     | zip                | Zip                | text      | text        |
| Yes      | time           | start_date         | Start Date         | text      | text        |
| No       |                | end_date           | End Date           | text      | text        |
| No       |                | start_time         | Start Time         | text      | text        |
| No       |                | end_time           | End Time           | text      | text        |
| Yes      | numeric metric | sessions           | Sessions           | number    | text        |
| No       |                | days_of_week       | Days of the Week   | text      | text        |
| Yes      | numeric metric | cost               | Cost               | money     | text        |
```

## Time Field

```ls
Value = start_date
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = address,end_date,end_time,days_of_week,start_time
```

## Data Commands

```ls
series e:imqa-htns d:2016-02-23T00:00:00.000Z t:zip=20832 t:primary_category=Aquatics t:session="Spring 2016" t:location="Olney Swim Center" t:description="Designed for children 4-6 years of age. Parents DO NOT accompany children. This class is for students who need to learn basic water adjustment skills.  Please read the course  descriptions carefully. Select the course  level for which the students has mastered all prerequisite skills. By choosing the appropriate level, the  student will be more likely to succeed. Please check all course dates to determine which classed will best accommodate  their needs. THERE ARE NO MAKE-UPS OR  REFUNDS FOR MISSED CLASSES. Courses meet for six (6) 30 minute sessions. Class  size is limited to 5 students. Screening is available to evaluate the student's abilities at each pool  if you are unsure of which class to register for. Call the pool of your choice and speak with  the Lesson Supervisor for evaluation dates and times (bring a swim suit and  towel)." t:state=MD t:activityname="Beginner 1" t:secondary_category="Pre-Beginner Swim Lessons" t:activitynumber=14502 t:ages="At least 4 but less than 7" t:city=Olney m:sessions=6 m:cost=64

series e:imqa-htns d:2016-03-14T00:00:00.000Z t:zip=20904 t:primary_category=Aquatics t:session="Spring 2016" t:location="Martin Luther King Jr. Swim Center" t:description="This is an invitation  only program designed to prepare athletes for collegiate competition.  Participants will train for and compete in AAU Diving meets around the area.  Our competitive goal will be to qualify for the AAU National Championships each  summer. Contact MDCBeavers@gmail.com  for info on how to try out for the program. Participants pay an annual  membership fee of $300 directly to MDC in addition to the training fee listed  here. . Admission into this class requires the permission of the program director, Doug Beavers   Practices are offered 3x a week: Monday-Wednesday-Friday  7-9pm at MLK." t:state=MD t:activityname="AAU National team" t:secondary_category=Diving t:activitynumber=15457 t:ages="At least 6 but less than 19" t:city="Silver Spring" m:sessions=27 m:cost=675

series e:imqa-htns d:2016-04-12T00:00:00.000Z t:zip=20854 t:primary_category="Tiny Tots" t:session="Spring 2016" t:location="Potomac Community Recreation Center" t:description="Let Young Rembrandt help prepare your preschooler for Kindergarten. We teach your children skills that will help them grow, develop and excel all while having fun! We'll concentrate on the skills of drawing and coloring wile we develop fine motor skills, focus, listening, staying on task, patience and spatial organization. Each session contains all new lessons. Adult Participation not Required." t:state=MD t:activityname="Young Rembrandts: PreSchool Drawing" t:secondary_category=Arts t:activitynumber=16742 t:ages="At least 3 1/2 but less than 6" t:city=Potomac m:sessions=6 m:cost=69
```

## Meta Commands

```ls
metric m:sessions p:integer l:Sessions d:Sessions t:dataTypeName=number

metric m:cost p:long l:Cost d:Cost t:dataTypeName=money

entity e:imqa-htns l:"Recreation Spring Programs 2016" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/imqa-htns

property e:imqa-htns t:meta.view v:id=imqa-htns v:category=Community/Recreation v:averageRating=0 v:name="Recreation Spring Programs 2016" v:attribution="Montgomery County, MD"

property e:imqa-htns t:meta.view.license v:name="Public Domain"

property e:imqa-htns t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:imqa-htns t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| session     | primary_category             | secondary_category        | activityname                        | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | activitynumber | ages                           | location                              | address                   | city          | state | zip   | start_date | end_date   | start_time | end_time | sessions | days_of_week | cost | 
| =========== | ============================ | ========================= | =================================== | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ============== | ============================== | ===================================== | ========================= | ============= | ===== | ===== | ========== | ========== | ========== | ======== | ======== | ============ | ==== | 
| Spring 2016 | Aquatics                     | Pre-Beginner Swim Lessons | Beginner 1                          | Designed for children 4-6 years of age. Parents DO NOT accompany children. This class is for students who need to learn basic water adjustment skills. Please read the course descriptions carefully. Select the course level for which the students has mastered all prerequisite skills. By choosing the appropriate level, the student will be more likely to succeed. Please check all course dates to determine which classed will best accommodate their needs. THERE ARE NO MAKE-UPS OR REFUNDS FOR MISSED CLASSES. Courses meet for six (6) 30 minute sessions. Class size is limited to 5 students. Screening is available to evaluate the student's abilities at each pool if you are unsure of which class to register for. Call the pool of your choice and speak with the Lesson Supervisor for evaluation dates and times (bring a swim suit and towel).                    | 14502          | At least 4 but less than 7     | Olney Swim Center                     | 16605 Georgia Avenue      | Olney         | MD    | 20832 | 02/23/2016 | 04/05/2016 | 6:00 PM    | 6:30 PM  | 6        | T            | $64  | 
| Spring 2016 | Aquatics                     | Diving                    | AAU National team                   | This is an invitation only program designed to prepare athletes for collegiate competition. Participants will train for and compete in AAU Diving meets around the area. Our competitive goal will be to qualify for the AAU National Championships each summer. Contact MDCBeavers@gmail.com for info on how to try out for the program. Participants pay an annual membership fee of $300 directly to MDC in addition to the training fee listed here. . Admission into this class requires the permission of the program director, Doug Beavers Practices are offered 3x a week: Monday-Wednesday-Friday 7-9pm at MLK.                                                                                                                                                                                                                                                                 | 15457          | At least 6 but less than 19    | Martin Luther King Jr. Swim Center    | 1201 Jackson Road         | Silver Spring | MD    | 20904 | 03/14/2016 | 05/20/2016 | 7:00 PM    | 9:00 PM  | 27       | M,W,F        | $675 | 
| Spring 2016 | Tiny Tots                    | Arts                      | Young Rembrandts: PreSchool Drawing | Let Young Rembrandt help prepare your preschooler for Kindergarten. We teach your children skills that will help them grow, develop and excel all while having fun! We'll concentrate on the skills of drawing and coloring wile we develop fine motor skills, focus, listening, staying on task, patience and spatial organization. Each session contains all new lessons. Adult Participation not Required.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 16742          | At least 3 1/2 but less than 6 | Potomac Community Recreation Center   | 11315 Falls Road          | Potomac       | MD    | 20854 | 04/12/2016 | 05/24/2016 | 10:45 AM   | 11:30 AM | 6        | T            | $69  | 
| Spring 2016 | Aquatics                     | Adult Swim Lessons        | Adult Level 3                       | Designed for teenagers and adults (14yrs and older) who can already swim a combined stroke on their front and back, using a kick and arm stroke for a minimum of 5 yards. Please read the course descriptions carefully. Select the course level for which the students has mastered all prerequisite skills. By choosing the appropriate level, the student will be more likely to succeed. Please check all course dates to determine which classed will best accommodate their needs. THERE ARE NO MAKE-UPS OR REFUNDS FOR MISSED CLASSES. Courses meet for six (6) 30 minute sessions. Class size is limited to 10 students. Screening is available to evaluate the student's abilities at each pool if you are unsure of which class to register for.Call the pool of your choice and speak with the Lesson Supervisor for evaluation dates and times (bring a swim suit and towel). | 16329          | 14 and up                      | Kennedy Shriver Aquatic Center        | 5900 Executive Boulevard  | N Bethesda    | MD    | 20852 | 03/05/2016 | 04/16/2016 | 9:40 AM    | 10:10 AM | 6        | Sa           | $62  | 
| Spring 2016 | Travel                       | General Trips             | Bloomin' Winefest, Winchester, VA   | Bloomin? Wine Fest Enjoy live entertainment, great food, spectacular Virginia wines, and wonderful company. Join us to "Uncork the Bloom" at the United Bank Bloomin? Wine Fest, the official kick-off of the 89th Shenandoah Apple Blossom Festival. This truly unique outdoor wine festival is situated in downtown Winchester?s original marketplace. There will be three distinctive wine gardens nestled between centuries old buildings and Virginia?s first pedestrian mall. The event features 20 of Virginia?s finest wineries offering wine tastings and wines sold by the glass or bottle and craft beers to taste and purchase by the glass. There will also be artisans bringing their own special flair, Tasty Festival foods and three stages presenting regional musical talents. Fee includes: transportation, wine tasting and show admission! Meals are on your own!   | 12392          | 21 and up                      | Olney Manor Recreational Park         | 16601 Georgia Avenue      | Olney         | MD    | 20832 | 04/22/2016 | 04/22/2016 | 12:45 PM   | 9:45 PM  | 1        | F            | $69  | 
| Spring 2016 | Exercise, Fitness & Wellness | Aerobic Exercise          | Movin with Millie                   | Set to positive, upbeat music. A unique exercise experience beginning with a total body warm up, aerobic conditioning for cardiovascular fitness, and floor exercise for toning hips, thighs, abdominals, and glutes. Program provides flexibility, endurance and strength training. Please bring a mat, exercise bands, and hand weights to class. Questions call Millie at 301-588-3577 or email at millietrimble3@gmail.com                                                                                                                                                                                                                                                                                                                                                                                                                                                            | 16179          | 16 and up                      | Pilgrim Hills Local Park              | 1615 E. Randolph Road     | Colesville    | MD    | 20904 | 04/06/2016 | 06/08/2016 | 9:30 AM    | 10:45 AM | 10       | W            | $80  | 
| Spring 2016 | Aquatics                     | Diving                    | Level 3: Human Springs              | These 90 minute classes are for kids with past diving experience from summer diving or Level 2. divers must have the ability to do forward, backward, and inward dive tuck, a hurdle, back press, as well as safe come-out skills. All SPRINGS participants must pay a $15.00 fee per session. To complete your registration, visit www.montgomerydiveclub.org.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 15348          | At least 8 but less than 19    | Germantown Indoor Swim Center         | 18000 Central Park Circle | Boyds         | MD    | 20841 | 03/15/2016 | 05/24/2016 | 5:30 PM    | 7:00 PM  | 10       | T            | $270 | 
| Spring 2016 | Music Classes                | Piano                     | Adult Group Piano III               | Intermediate level - Some piano skills and knowledge of note reading, theory and rhythm patterns required. Improve your ability to move freely over the keyboard and develop rhythmic, harmonic and theoretical concepts. Major and minor scales are taught progressively. Duet, ensemble and solo literature will be performed in all classes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 16630          | 17 and up                      | Holiday Park Senior Center            | 3950 Ferrara Drive        | Wheaton       | MD    | 20906 | 04/12/2016 | 06/07/2016 | 8:15 PM    | 9:05 PM  | 8        | T            | $125 | 
| Spring 2016 | Aquatics                     | Water Fitness             | Abs & Glutes & More                 | Shallow water aerobics class with high energy packed with power that will sculpt your abs, glutes, and more. Gloves are recommended and can be purchased at the class.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 15388          | 14 and up                      | Martin Luther King Jr. Swim Center    | 1201 Jackson Road         | Silver Spring | MD    | 20904 | 03/16/2016 | 05/18/2016 | 10:00 AM   | 10:50 AM | 9        | W            | $54  | 
| Spring 2016 | Exercise, Fitness & Wellness | Aerobic Exercise          | New York City Workout-Ballet Dance  | Ballet dancers are slim, lean and graceful. You will practice low-impact Ballet steps and Yoga and Pilates stretches. This class is based on the New York City Ballet Workout for adults who want a good workout, but are not dancers. You will be moving, extending, reaching through the legs and arms, which helps build long, learn muscles. Great class to help with balance. Fore more information contact Juliet at: jcverdi@gmail.com                                                                                                                                                                                                                                                                                                                                                                                                                                             | 16013          | 18 and up                      | White Oak Community Recreation Center | 1700 April Lane           | Silver Spring | MD    | 20904 | 04/13/2016 | 06/08/2016 | 6:00 PM    | 7:00 PM  | 9        | W            | $72  | 
```