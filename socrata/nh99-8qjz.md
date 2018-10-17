# RAMS - Route Signing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rams-route-signing) |
| Metadata | [Link](https://data.iowa.gov/api/views/nh99-8qjz) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/nh99-8qjz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/nh99-8qjz/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | nh99-8qjz |
| Name | RAMS - Route Signing |
| Attribution | Iowa Department of Transportation - Office of Research & Analytics |
| Category | Transportation & Utilities |
| Tags | iowa dot, iowa department of transportation, rams, route signing, asset, classification |
| Created | 2016-12-06T20:03:04Z |
| Publication Date | 2016-12-06T20:07:53Z |

## Description

Route Signing data maintained inside the Roadway Asset Management System (RAMS).

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type  | Render Type |
| ======== | ============== | ==================== | ==================== | ========== | =========== |
| Yes      | series tag     | event_id             | EVENT_ID             | text       | text        |
| Yes      | series tag     | route_id             | ROUTE_ID             | text       | text        |
| Yes      | numeric metric | from_measure         | FROM_MEASURE         | number     | number      |
| Yes      | numeric metric | to_measure           | TO_MEASURE           | number     | number      |
| Yes      | time           | business_date        | BUSINESS_DATE        | date       | date        |
| No       |                | effective_start_date | EFFECTIVE_START_DATE | date       | date        |
| No       |                | effective_end_date   | EFFECTIVE_END_DATE   | date       | date        |
| Yes      | series tag     | user_create          | USER_CREATE          | text       | text        |
| Yes      | series tag     | user_mod             | USER_MOD             | text       | text        |
| No       |                | system_create_date   | SYSTEM_CREATE_DATE   | date       | date        |
| No       |                | system_mod_date      | SYSTEM_MOD_DATE      | date       | date        |
| Yes      | numeric metric | route_signing        | ROUTE_SIGNING        | number     | number      |
| Yes      | series tag     | locerror             | LOCERROR             | text       | text        |
| Yes      | numeric metric | shape_len            | SHAPE.LEN            | number     | number      |
| Yes      | series tag     | objectid             | OBJECTID             | text       | number      |
| No       |                | shape                | SHAPE                | geospatial | geospatial  |
```

## Time Field

```ls
Value = business_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = effective_start_date,effective_end_date,system_create_date,system_mod_date,shape
```

## Data Commands

```ls
series e:nh99-8qjz d:2016-01-01T06:00:00.000Z t:shape.longitude=-90.69264660299996 t:shape.needs_recoding=false t:route_id=C003143010N t:event_id=0000002767 t:user_create=JRENFRO t:locerror="NO ERROR" t:shape.latitude=42.54240643000003 t:objectid=1 m:route_signing=6 m:to_measure=1.599882 m:from_measure=0.011229

series e:nh99-8qjz d:2016-01-01T06:00:00.000Z t:shape.longitude=-90.68282486499999 t:shape.needs_recoding=false t:route_id=C003143130N t:event_id=0000001960 t:user_create=JRENFRO t:locerror="NO ERROR" t:shape.latitude=42.43911925500004 t:objectid=2 m:route_signing=6 m:to_measure=1.231226 m:from_measure=0.098468

series e:nh99-8qjz d:2016-01-01T06:00:00.000Z t:shape.longitude=-90.71092551099997 t:shape.needs_recoding=false t:route_id=C003147580E t:event_id=0000002829 t:user_create=JRENFRO t:locerror="NO ERROR" t:shape.latitude=42.55858122400008 t:objectid=3 m:route_signing=6 m:to_measure=1.008738 m:from_measure=0
```

## Meta Commands

```ls
metric m:from_measure p:decimal l:FROM_MEASURE d:"From Measure" t:dataTypeName=number

metric m:to_measure p:decimal l:TO_MEASURE d:"To Measure" t:dataTypeName=number

metric m:route_signing p:integer l:ROUTE_SIGNING d:"Route Signing" t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:"Length (Meter)" t:dataTypeName=number

entity e:nh99-8qjz l:"RAMS - Route Signing" t:attribution="Iowa Department of Transportation - Office of Research & Analytics" t:url=https://data.iowa.gov/api/views/nh99-8qjz

property e:nh99-8qjz t:meta.view v:id=nh99-8qjz v:category="Transportation & Utilities" v:averageRating=0 v:name="RAMS - Route Signing" v:attribution="Iowa Department of Transportation - Office of Research & Analytics"

property e:nh99-8qjz t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:nh99-8qjz t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| event_id   | route_id    | from_measure                                                 | to_measure                                              | business_date | effective_start_date | effective_end_date | user_create | user_mod | system_create_date | system_mod_date | route_signing | locerror                         | shape_len | objectid | shape                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| ========== | =========== | ============================================================ | ======================================================= | ============= | ==================== | ================== | =========== | ======== | ================== | =============== | ============= | ================================ | ========= | ======== | ===================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 0000002767 | C003143010N | 0.0112289999999999993984811652580901863984763622283935546875 | 1.59988200000000002631850293255411088466644287109375    | 1451628000    | 1451606401           |                    | JRENFRO     |          | 1463747571         |                 | 6             | NO ERROR                         |           | 1        | [null, 42.54240643000003, -90.69264660299996, null, false, {paths=[[[-90.69264660299996, 42.54240643000003], [-90.69262742299998, 42.54242918800003], [-90.69254289999998, 42.54254214700006], [-90.69246641499996, 42.54265819500006], [-90.69239817499994, 42.54277702300004], [-90.69233836799998, 42.542898308000076], [-90.69227108799998, 42.54313268900006], [-90.69224227199999, 42.54323307100003], [-90.69208754599998, 42.544177182000055], [-90.69199655399996, 42.54474734200005], [-90.69194375699999, 42.54507817100006], [-90.69191957299995, 42.54552147800007], [-90.69189931199998, 42.54577464000005], [-90.69187417699999, 42.545934233000025], [-90.69175192399996, 42.54657513800004], [-90.69171160999997, 42.54673960800005], [-90.69166812499998, 42.546956686000044], [-90.69164522999995, 42.547145656000055], [-90.69164094299998, 42.54746023600006], [-90.69164710899997, 42.54775718900004], [-90.69166769199995, 42.54794721300004], [-90.69167946299996, 42.54803416500005], [-90.69169682999996, 42.54816247600007], [-90.69173871799995, 42.54841738500005], [-90.69179707499995, 42.548737060000065], [-90.69185970799998, 42.54917842000003], [-90.69190962599998, 42.54949331800003], [-90.69195417199995, 42.54977431800006], [-90.69201577899997, 42.55012983200004], [-90.69213218399995, 42.55077632500007], [-90.69225777999998, 42.55143376900003], [-90.69231875499997, 42.55180356900007], [-90.69233102999999, 42.551888990000066], [-90.69240744699994, 42.55242078300006], [-90.69244878299997, 42.552797258000055], [-90.69247615999996, 42.553038779000076], [-90.69250295899997, 42.55327518100006], [-90.69254958799996, 42.55368653600004], [-90.69260834499994, 42.55432447800007], [-90.69270686099998, 42.555156485000055], [-90.69277306399994, 42.555844670000056], [-90.69287680599996, 42.556995061000066], [-90.69292115399998, 42.55752179700005], [-90.69295877299999, 42.55787315100008], [-90.69298165799995, 42.55833857700003], [-90.69301214999996, 42.558632544000034], [-90.69305159199996, 42.55905188400004], [-90.69307422399999, 42.55932245300005], [-90.69312112799997, 42.559883186000036], [-90.69316088899996, 42.56029538100006], [-90.69323692299997, 42.56119835700008], [-90.69328088299994, 42.56162495900003], [-90.69336373099998, 42.56259246700006], [-90.69346868399998, 42.56360699800007], [-90.69351209099995, 42.56415516800007], [-90.69356856899998, 42.56473583700006], [-90.69362779499994, 42.56527776200005]]]}] | 
| 0000001960 | C003143130N | 0.098467999999999999971578290569595992565155029296875        | 1.231225999999999931588945401017554104328155517578125   | 1451628000    | 1451606401           |                    | JRENFRO     |          | 1463747571         |                 | 6             | NO ERROR                         |           | 2        | [null, 42.43911925500004, -90.68282486499999, null, false, {paths=[[[-90.68282486499999, 42.43911925500004], [-90.68293764199996, 42.43927931400003], [-90.68314573899994, 42.439534871000035], [-90.68321690899995, 42.439622274000044], [-90.68334734299998, 42.43972916000007], [-90.68378030899999, 42.440090170000076], [-90.68413998699998, 42.440470849000064], [-90.68437998399997, 42.440719870000066], [-90.68456455499995, 42.44102118300003], [-90.68470327399996, 42.441267735000054], [-90.68481984799996, 42.44157811800005], [-90.68490739399994, 42.44199865200005], [-90.68503847299996, 42.44263481300004], [-90.68517548899996, 42.44324608200003], [-90.68528658199995, 42.443788776000076], [-90.68549890499997, 42.44477021600005], [-90.68559080599994, 42.44520158300003], [-90.68574017399999, 42.445752361000075], [-90.68586054099995, 42.44619514900006], [-90.68576716699994, 42.44624454500007], [-90.68556446799994, 42.44656860600003], [-90.68539838499998, 42.44682919100006], [-90.68487807099996, 42.447563915000046], [-90.68485623099997, 42.44759488600005], [-90.68435244599999, 42.448309238000036], [-90.68380592699998, 42.44908980800005], [-90.68285054999996, 42.45048622300004], [-90.68211890499998, 42.451519751000035], [-90.68186777499994, 42.45184620200007], [-90.68149690099995, 42.45225913500008], [-90.68109495599998, 42.45261051400007], [-90.68079025199995, 42.45284658300005], [-90.68075486299995, 42.452874001000055], [-90.68050975199998, 42.45303390000004], [-90.68007848599996, 42.45331523600004], [-90.67966555299995, 42.45358766800007], [-90.67961460099997, 42.453621705000046]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 
| 0000002829 | C003147580E | 0                                                            | 1.0087379999999999125037675185012631118297576904296875  | 1451628000    | 1451606401           |                    | JRENFRO     |          | 1463747571         |                 | 6             | NO ERROR                         |           | 3        | [null, 42.55858122400008, -90.71092551099997, null, false, {paths=[[[-90.71092551099997, 42.55858122400008], [-90.71091924699994, 42.55858462400005], [-90.71046486999995, 42.558836265000025], [-90.71016319299997, 42.55898633600003], [-90.70993168199999, 42.559080882000046], [-90.70973572699995, 42.55913694900005], [-90.70956487599994, 42.559172165000064], [-90.70938467899998, 42.559200006000026], [-90.70920463699997, 42.55922427300004], [-90.70889912199999, 42.55924194000005], [-90.70872937399997, 42.55925215000008], [-90.70834077099994, 42.55928926800004], [-90.70777600899999, 42.55937219700007], [-90.70735667899999, 42.55944790400008], [-90.70684254499997, 42.55958926500006], [-90.70641664499999, 42.55970414500007], [-90.70609736199998, 42.559814446000075], [-90.70576216099994, 42.559956544000045], [-90.70513057199997, 42.56023809800007], [-90.70418824599994, 42.56065518300005], [-90.70365533499995, 42.56089262800003], [-90.70024961999997, 42.562430207000034], [-90.69773784199998, 42.56354949200005], [-90.69678543699996, 42.56397342500003], [-90.69481103299995, 42.56486249500006], [-90.69404554499994, 42.56521584300003], [-90.69364423899998, 42.565428215000054]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | 
| 0000002823 | C003246220E | 1.899907999999999930196281638927757740020751953125           | 2.752947999999999950659912428818643093109130859375      | 1451628000    | 1451606401           |                    | JRENFRO     |          | 1463747571         |                 | 6             | NO ERROR                         |           | 4        | [null, 43.40316595400003, -94.87650451399998, null, false, {paths=[[[-94.87650451399998, 43.40316595400003], [-94.87595508799996, 43.403204706000054], [-94.87531407899996, 43.40321841000008], [-94.87350556099994, 43.403251967000074], [-94.87298768799997, 43.40326421800006], [-94.87223641999998, 43.40328538600005], [-94.87132372199994, 43.40329605000005], [-94.87062294099997, 43.40330423200004], [-94.86961246099997, 43.40331912100004], [-94.86878044799994, 43.40333811200003], [-94.86777421299996, 43.40335293600003], [-94.86745981999997, 43.40335982800008], [-94.86687001999996, 43.40337275500008], [-94.86546890699998, 43.40339215400007], [-94.86451341999998, 43.40339706800006], [-94.86349437799998, 43.40340890700003], [-94.86222893099995, 43.40341740300005], [-94.86107003999996, 43.40344322900006], [-94.86008900599995, 43.40344530800007], [-94.85956215999994, 43.40345299000006]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 
| 0000001007 | C003341260N | 0                                                            | 0.72854199999999991188559533838997595012187957763671875 | 1451628000    | 1451606401           |                    | JRENFRO     |          | 1463747570         |                 | 6             | NO ERROR                         |           | 5        | [null, 42.67840553600007, -91.94322828399999, null, false, {paths=[[[-91.94322828399999, 42.67840553600007], [-91.94696621999998, 42.67840701800003], [-91.94706752599996, 42.67840620800007], [-91.94716849499997, 42.67841234900004], [-91.94726825799995, 42.67842538800005], [-91.94736594399996, 42.67844521200004], [-91.94746070899998, 42.67847165000006], [-91.94755173399994, 42.678504470000064], [-91.94763823099998, 42.67854339100006], [-91.94771945399998, 42.67858807500005], [-91.94779469399998, 42.678638136000075], [-91.94786330499994, 42.678693140000064], [-91.94792468699995, 42.67875261100005], [-91.94797831699998, 42.67881603300003], [-91.94802372099997, 42.678882860000044], [-91.94806051399996, 42.678952509000055], [-91.94808837599999, 42.679024380000044], [-91.94810705999998, 42.67909785300003], [-91.94811159599999, 42.67970199300004], [-91.94805132499994, 42.681563469000025], [-91.94803115799994, 42.68277850800007], [-91.94797616499994, 42.684622180000076], [-91.94800083399997, 42.68480123300003], [-91.94806442599997, 42.68497365600007], [-91.94811964899998, 42.68509235200003], [-91.94823255299997, 42.68522969000003], [-91.94834615899998, 42.685338442000045], [-91.94849349299994, 42.685454794000066], [-91.94864384099998, 42.685535712000046]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 
| 0000000653 | C003441940N | 0                                                            | 1.059178999999999870595956963370554149150848388671875   | 1451628000    | 1451606401           |                    | JRENFRO     |          | 1463747570         |                 | 6             | NO ERROR                         |           | 6        | [null, 42.965745844000025, -92.55417429799996, null, false, {paths=[[[-92.55417429799996, 42.965745844000025], [-92.55417899099996, 42.96575223600007], [-92.55439842699997, 42.96606351100007], [-92.55458981799995, 42.966348906000064], [-92.55477402999998, 42.966636838000056], [-92.55495099899997, 42.96692720900006], [-92.55525872199996, 42.967497912000056], [-92.55614401899999, 42.96914180700003], [-92.55699675099999, 42.97068894000006], [-92.55793929999999, 42.97241547600004], [-92.55869233599998, 42.973800975000074], [-92.55873913599999, 42.97388489200006], [-92.55879314599997, 42.97396644100007], [-92.55885414599999, 42.97404528900006], [-92.55897159499995, 42.974207413000045], [-92.55909687999997, 42.97436634700006], [-92.55922983799996, 42.974521881000044], [-92.55937029899997, 42.97467381900003], [-92.55951808199995, 42.97482196400006], [-92.55967299799994, 42.97496612600003], [-92.55983484899997, 42.975106123000046], [-92.56000342699997, 42.975241770000025], [-92.56017851399997, 42.97537289700006], [-92.56035988699995, 42.97549933200003], [-92.56054730899996, 42.975620916000025], [-92.56074054599998, 42.975737493000054], [-92.56093934499995, 42.975848910000025], [-92.56114833099997, 42.97595880600005], [-92.56136251099997, 42.97606316800005], [-92.56158161899998, 42.97616186400006], [-92.56180537199998, 42.97625476800005], [-92.56203349099997, 42.97634176100007], [-92.56226568499994, 42.976422736000075], [-92.56250165899996, 42.97649758700004], [-92.56303786699999, 42.97663702600005], [-92.56306888199998, 42.97664509100008], [-92.56424746099998, 42.97691900400008], [-92.56588445299997, 42.977300323000065], [-92.56593898499995, 42.97731302500006]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| 0000000807 | C003646510E | 0.361830999999999958216534423627308569848537445068359375     | 0.57783200000000001228528390129213221371173858642578125 | 1451628000    | 1451606401           |                    | JRENFRO     |          | 1463747570         |                 | 6             | NO ERROR                         |           | 7        | [null, 40.768143432000045, -95.38924929699994, null, false, {paths=[[[-95.38924929699994, 40.768143432000045], [-95.38907176599997, 40.76792452800004], [-95.38881653499999, 40.76759798100005], [-95.38859471699999, 40.76732123800008], [-95.38836752899994, 40.76707105500003], [-95.38818734099999, 40.766896846000066], [-95.38795351399995, 40.76672615100006], [-95.38765544899996, 40.76652793200003], [-95.38745845299997, 40.76641418500003], [-95.38720747299999, 40.76629434000006], [-95.38698324199999, 40.76621482000007], [-95.38668810499996, 40.76609829500006], [-95.38656287199996, 40.76606466100003], [-95.38638750299998, 40.76601818200004]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 
| 0000000428 | C004141520N | 12.0689960000000002793285602820105850696563720703125         | 12.1829739999999997479562807711772620677947998046875    | 1451628000    | 1451606401           |                    | JRENFRO     |          | 1463747570         |                 | 3             | NO ERROR                         |           | 8        | [null, 43.10495023800007, -93.63606324299997, null, false, {paths=[[[-93.63606324299997, 43.10495023800007], [-93.63607008099996, 43.104989809000074], [-93.63606614099996, 43.105422169000065], [-93.63605835899995, 43.106329765000055], [-93.63605705499998, 43.106601375000025]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 
| 0000001667 | C004341620N | 10.17633599999999916008164291270077228546142578125           | 10.6819879999999987063574735657311975955963134765625    | 1451628000    | 1451606401           |                    | JRENFRO     |          | 1463747570         |                 | 4             | NO ERROR                         |           | 9        | [null, 41.66098285500004, -95.92998642299995, null, false, {paths=[[[-95.92998642299995, 41.66098285500004], [-95.92998209799998, 41.661526071000026], [-95.92997863899996, 41.66231646600005], [-95.92995485699998, 41.66382966700007], [-95.92995351399998, 41.66656542100003], [-95.92997909699994, 41.66774499100006], [-95.92999441699999, 41.66831210700008]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 
| 0000002653 | C004441610N | 0.84254200000000001313793518420425243675708770751953125      | 1.0900259999999999394049154943786561489105224609375     | 1451628000    | 1451606401           |                    | JRENFRO     |          | 1463747571         |                 | 6             | PARTIAL MATCH FOR THE TO-MEASURE |           | 10       | [null, 40.984234565000065, -91.54147457799996, null, false, {paths=[[[-91.54147457799996, 40.984234565000065], [-91.54213527299999, 40.985805639000034], [-91.54265809999998, 40.98703514600004], [-91.54291529699998, 40.987649618000034]]]}]                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
```