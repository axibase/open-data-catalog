# Community Submitted Events

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-submitted-events-5de2c) |
| Metadata | [Link](https://data.seattle.gov/api/views/t5mx-wchj) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/t5mx-wchj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/t5mx-wchj/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | t5mx-wchj |
| Name | Community Submitted Events |
| Category | Community |
| Tags | events |
| Created | 2013-03-08T00:53:01Z |
| Publication Date | 2013-07-23T08:33:15Z |

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                              | Data Type     | Render Type   |
| ======== | =========== | ================================= | ================================= | ============= | ============= |
| Yes      | series tag  | event                             | Event                             | text          | text          |
| Yes      | time        | start_time                        | Start time                        | calendar_date | calendar_date |
| No       |             | end_time                          | End time                          | calendar_date | calendar_date |
| Yes      | series tag  | building_name_room_number         | Building Name/Room Number         | text          | text          |
| Yes      | series tag  | website                           | Website                           | url           | url           |
| Yes      | series tag  | event_description_agenda          | Event Description/Agenda          | text          | text          |
| Yes      | series tag  | sponsoring_organization           | Sponsoring Organization           | text          | text          |
| Yes      | series tag  | event_contact                     | Event Contact                     | text          | text          |
| Yes      | series tag  | event_contact_position_department | Event Contact Position/Department | text          | text          |
| Yes      | series tag  | event_contact_phone               | Event Contact Phone               | text          | text          |
| Yes      | series tag  | event_contact_email               | Event Contact Email               | text          | text          |
| Yes      | series tag  | street_address                    | Street Address                    | text          | text          |
| No       |             | latitude                          | Latitude                          | number        | number        |
| No       |             | longitude                         | Longitude                         | number        | number        |
| Yes      | series tag  | event_info_url                    | Event Info Url                    | url           | url           |
```

## Time Field

```ls
Value = start_time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end_time,latitude,longitude
```

## Data Commands

```ls
series e:t5mx-wchj d:2013-07-23T00:00:00.000Z t:event_info_url="http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d106014398" t:event_contact="Jason Pecarich" t:website=http://www.nwwoodgallery.com/ t:event="Lost & Found" t:sponsoring_organization="Northwest Woodworkers Gallery" t:event_contact_email=contact@nwwoodgallery.com t:street_address="2111 1st Ave" t:event_description_agenda="Northwest Woodworkers Gallery<br /> Presents<br /> Lost & Found<br /> July 1st, 2013-August 31st, 2013<br /> <br /> Gallery Reception Show: July 12th 5-8pm<br /> <br /> Annual Member Showcase highlighting an experience of ""Re-Discovery"" in the idea that letting go is the portal to bringing forth something new.<br /> <br /> Inspiration and evolution are aspects vital to a studio Artisan. Though the path to creation in fine woodworking must be well conceived and requires detailed execution, it&#39;s clear that life&#39;s detours and obstacles often provide the most poignant revelations for a makers&#39; creative vision." t:event_contact_phone=206-625-0542 m:row_number.t5mx-wchj=1

series e:t5mx-wchj d:2013-07-23T00:00:00.000Z t:event_info_url="http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105513649" t:event_contact="Washington State History Museum" t:website=http://www.washingtonhistory.org/ t:event="Prized Northwest Native Arts Show Returns to Washington State History Museum" t:street_address="1911 Pacific Ave" t:event_description_agenda="On Saturday, June 8, the Washington State History Museum unveils the eighth annual In the Spirit: Contemporary Northwest Native Arts exhibit. The exhibit, which is on display through August 18, 2013, showcases work from more than 20 Northwest Native artisans and focuses on the distinctive cultures and stories of the region&#8217;s tribal groups. The two-month exhibit will culminate with the In the Spirit: Northwest Native Arts Market & Festival on Saturday, August 17, 2013." m:row_number.t5mx-wchj=2

series e:t5mx-wchj d:2013-07-23T00:00:00.000Z t:event_info_url="http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792932" t:event_contact="Josh Mahar" t:website=http://www.mohai.org/ t:event="Still Afloat: A Contemporary History of Seattle's Floating Homes" t:sponsoring_organization="MOHAI and Floating Homes Association" t:event_contact_email=information@mohai.org t:street_address="860 Terry Ave N" t:event_description_agenda="Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle&#39;s most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home." t:event_contact_phone=206-324-1126 m:row_number.t5mx-wchj=3
```

## Meta Commands

```ls
metric m:row_number.t5mx-wchj p:long l:"Row Number"

entity e:t5mx-wchj l:"Community Submitted Events" t:url=https://data.seattle.gov/api/views/t5mx-wchj

property e:t5mx-wchj t:meta.view v:id=t5mx-wchj v:category=Community v:averageRating=0 v:name="Community Submitted Events"

property e:t5mx-wchj t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:t5mx-wchj t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| event                                                                        | start_time          | end_time            | building_name_room_number | website                                       | event_description_agenda                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | sponsoring_organization              | event_contact                   | event_contact_position_department | event_contact_phone | event_contact_email        | street_address         | latitude | longitude  | event_info_url                                                                          | 
| ============================================================================ | =================== | =================== | ========================= | ============================================= | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ==================================== | =============================== | ================================= | =================== | ========================== | ====================== | ======== | ========== | ======================================================================================= | 
| Lost & Found                                                                 | 2013-07-23T00:00:00 |                     |                           | [http://www.nwwoodgallery.com/, null]         | Northwest Woodworkers Gallery
Presents
Lost & Found
July 1st, 2013-August 31st, 2013

Gallery Reception Show: July 12th 5-8pm

Annual Member Showcase highlighting an experience of "Re-Discovery" in the idea that letting go is the portal to bringing forth something new.

Inspiration and evolution are aspects vital to a studio Artisan. Though the path to creation in fine woodworking must be well conceived and requires detailed execution, it's clear that life's detours and obstacles often provide the most poignant revelations for a makers' creative vision.                                                                                                                                                                                                                                                                                                                                                                                                                                         | Northwest Woodworkers Gallery        | Jason Pecarich                  |                                   | 206-625-0542        | contact@nwwoodgallery.com  | 2111 1st Ave           | 47.61181 | -122.34417 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d106014398, null] | 
| Prized Northwest Native Arts Show Returns to Washington State History Museum | 2013-07-23T00:00:00 |                     |                           | [http://www.washingtonhistory.org/, null]     | On Saturday, June 8, the Washington State History Museum unveils the eighth annual In the Spirit: Contemporary Northwest Native Arts exhibit. The exhibit, which is on display through August 18, 2013, showcases work from more than 20 Northwest Native artisans and focuses on the distinctive cultures and stories of the region?s tribal groups. The two-month exhibit will culminate with the In the Spirit: Northwest Native Arts Market & Festival on Saturday, August 17, 2013.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                      | Washington State History Museum |                                   |                     |                            | 1911 Pacific Ave       |          |            | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105513649, null] | 
| Still Afloat: A Contemporary History of Seattle's Floating Homes             | 2013-07-23T00:00:00 |                     |                           | [http://www.mohai.org/, null]                 | Celebrate summer at MOHAI with a unique exhibit exploring one of Seattle's most iconic images: the floating home! Through photos, narratives, and objects, learn how this diverse community has grown and changed over the years. Also see the intricate systems that bring modern comforts to a house on the water through a scale model of a floating home.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | MOHAI and Floating Homes Association | Josh Mahar                      |                                   | 206-324-1126        | information@mohai.org      | 860 Terry Ave N        | 47.62759 | -122.33661 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104792932, null] | 
| Eastside Sings July Sing-A-Longs                                             | 2013-07-23T07:00:00 | 2013-07-23T21:30:00 |                           | [http://www.kirklandchoralsociety.org/, null] | The 2013 Eastside Sings events are presented by one of the sponsoring choral groups each week. The featured work is introduced, explained, practiced, and then performed. Meeting other singers, getting audition information, refreshments, and door prizes add to the delight and excitement of these evenings. This year?s reading sessions are:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Kirkland Choral Society              | George W. Tinker                |                                   | 425-239-3782        | george.tinker@gmail.com    | 1717 Bellevue Way NE   | 47.61769 | -122.32701 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105624097, null] | 
| Savor Seattle Pike Place Market Food & Cultural Tour                         | 2013-07-23T09:30:00 |                     |                           | [http://www.savorseattletours.com/, null]     | Our tour guides are past and present members of the Pike Place Market community. These intimate friendships with Market merchants ensure you will always receive special treatment. From Iron Chef winner Tom Douglas, to world famous fish throwers, come meet our Market family!                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                                      | Savor Seattle Tours             |                                   | 206-209-5485        | info@savorseattletours.com | 1501 Western Ave       | 47.60836 | -122.34157 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105092866, null] | 
| Experience Stories of Making a Difference with StoryCorps                    | 2013-07-23T10:00:00 | 2013-07-23T18:00:00 |                           | [null, null]                                  | Who has inspired you to make a difference? The Bill & Melinda Gates Foundation Visitor Center and StoryCorps are coming together to spark inspiration by sharing stories of making a difference. The StoryCorps MobileBooth will be onsite at the Visitor Center to record stories with select participants June 27-29 and we will share those stories throughout the year. Visitors are invited to listen to stories via our mobile listening station and to share their own stories about creating positive change through interactive activities, programs and social media, @GatesVC #InspirationStory. Note: the application period for StoryCorps has closed and participants for live interviews have been selected.                                                                                                                                                                                                                                                                                             | StoryCorps                           | Lorraine                        |                                   |                     |                            | 440 5th Ave N          | 47.62231 | -122.34708 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d106009731, null] | 
| Public Market Tours                                                          | 2013-07-23T10:00:00 | 2013-07-23T11:00:00 |                           | [http://www.publicmarkettours.com/, null]     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Public Market Tours                  | Customer Service/Ticketing      |                                   | 206-209-5488        | info@publicmarkettours.com | 1501 Western Ave       | 47.60836 | -122.34157 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105013987, null] | 
| Nytom: Makah Visions--Art Exhibit                                            | 2013-07-23T11:00:00 | 2013-07-23T17:00:00 |                           | [http://www.duwamishtribe.org/, null]         | Open Mon-Sat. Closed most Sundays. Nytom's art is deeply rooted within the rich culture of his Makah NW Native American heritage. Every piece tells a story based on a NW legend or on the artist?s own visions and dreams. "With my art, I can give back to my people and help keep our culture alive and vibrant."
Working since the 1970?s, Nytom creates art in his own design style in many mediums including limited editions serigraphs, painting cedar boxes, jewelry, and wood carving. Nytom ? "he who walks around" ? is the adult Indian name of the artist John Goodwin. The late NW artist, Art Thompson, was one of his mentors. His work has been shown in art galleries throughout North America.
Also featured is the work of Peter Dunthorne. Born September 2, 1951 in Mount Vernon, Washington, Peter completed a BFA degree in Graphic Design in 1975 from the University of Washington School of Art. Peter lives with his wife Susan on the Upper Skagit Indian Reservation near Sedro-Woolley. |                                      | Event Coordinator               |                                   | 206.431.1582        | dts@qwestoffice.net        | 4705 W Marginal Way SW | 47.5609  | -122.35209 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d105767338, null] | 
| Art Camp for Kids                                                            | 2013-07-23T13:00:00 | 2013-07-23T16:00:00 |                           | [http://kidz4art.wordpress.com/, null]        | Session 1 Learn Art Fundamentals While Exploring the World of Bugs & Animals
Session 2 Seeing Through The Eyes of Famous Artists & Making Art Using Their Techniques
Enroll for one or more sessions                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | KIDZ4ART                             | Karen MacKenzie                 |                                   | (206) 852-3815      | plaidrebel@gmail.com       | 4272 Fremont Ave N     | 47.65918 | -122.34965 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d104609140, null] | 
| KID'S LEAGUE at Green Lake Games                                             | 2013-07-23T14:00:00 | 2013-07-23T16:00:00 |                           | [http://www.greenlakegames.com/, null]        | Do you like to play games? Would you like to learn some new games? Are you 6 years old or older?

If you answered yes, bring your parents to Green Lake Games THIS TUESDAY at 2pm for Green Lake Games KID'S LEAGUE!

Try a new game each week for the next 6 weeks. For information on which game will be played each week, check our Facebook page.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Green Lake Games                     | Andrea                          |                                   | 206.922.3146        | andrea@greenlakegames.com  | 7509 Aurora Ave N      | 47.68361 | -122.34482 | [http://www.seattle.gov/calendar/?trumbaEmbed=view%3devent%26eventid%3d106146140, null] | 
```