# State Libraries Survey, FY 2007, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2007-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/inm4-3tsj) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/inm4-3tsj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/inm4-3tsj/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | inm4-3tsj |
| Name | State Libraries Survey, FY 2007, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2007, operations, workforce |
| Created | 2016-12-20T15:27:42Z |
| Publication Date | 2016-12-20T17:04:37Z |

## Description

Find key information on state library agencies.<br><br>These data include imputed values for state libraries that did not submit information in this data collection.<br><br>Imputation is a procedure for estimating a value for a specific data item where the response is missing.<br><br>Download SLAA data files to see imputation flag variables or learn more on the imputation methods at <a href="https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey"> https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey</a>

## Columns

```ls
| Included | Schema Type    | Field Name | Name                                                       | Data Type | Render Type |
| ======== | ============== | ========== | ========================================================== | ========= | =========== |
| Yes      | series tag     | stlaname   | STLA Name                                                  | text      | text        |
| Yes      | series tag     | physaddr   | Street                                                     | text      | text        |
| Yes      | series tag     | physcity   | City                                                       | text      | text        |
| Yes      | series tag     | phys_st    | State                                                      | text      | text        |
| Yes      | series tag     | physzip    | Zip                                                        | text      | text        |
| Yes      | series tag     | physzip4   | Zip+4                                                      | text      | text        |
| Yes      | series tag     | mailaddr   | Street (mail)                                              | text      | text        |
| Yes      | series tag     | mailcity   | City (mail)                                                | text      | text        |
| Yes      | series tag     | mail_st    | State (mail)                                               | text      | text        |
| Yes      | series tag     | mailzip    | Zip (mail)                                                 | text      | text        |
| Yes      | series tag     | mailzip4   | Zip+4 (mail)                                               | text      | text        |
| Yes      | series tag     | webaddr    | Web Address                                                | text      | text        |
| Yes      | series tag     | branch     | Branch of government [L]egis/[E]xec                        | text      | text        |
| Yes      | series tag     | indagy     | SLAA reports to [G]overnor/[B]oard                         | text      | text        |
| Yes      | series tag     | appbygov   | Appointed by governor [X]Yes/[P]n/a                        | text      | text        |
| Yes      | series tag     | appbyoth   | Appointed by other official [X]Yes/[P]n/a                  | text      | text        |
| Yes      | series tag     | largerag   | Part of Dept of [E]duc/[C]ult Resrc/[S]tate/[O]ther/[P]n/a | text      | text        |
| Yes      | series tag     | othagsp    | Other agency; [P]n/a                                       | text      | text        |
| Yes      | series tag     | pla_brco   | SLAA is sub-agency, has board [Y]es/[N]o/[P]n/a            | text      | text        |
| Yes      | series tag     | pla_gov    | Board appointed by Governor [X]Yes/[P]n/a                  | text      | text        |
| Yes      | series tag     | pld_oth    | Board appointed by other official [X]Yes/[P]n/a            | text      | text        |
| Yes      | series tag     | starchiv   | State archives                                             | text      | text        |
| Yes      | series tag     | stlegref   | Primary state legislative research organization            | text      | text        |
| Yes      | series tag     | sthstmus   | State history museum/art gallery                           | text      | text        |
| Yes      | series tag     | strecmng   | State records management service                           | text      | text        |
| Yes      | series tag     | othallop   | Other allied operation                                     | text      | text        |
| Yes      | series tag     | othallsp   | Other allied operation; [P]n/a                             | text      | text        |
| Yes      | series tag     | stlacont   | SLAA contracts with local/academic libraries               | text      | text        |
| Yes      | series tag     | stlahost   | SLAA hosts or funds State Center for the Book              | text      | text        |
| Yes      | series tag     | stdeplib   | State depository library                                   | text      | text        |
| Yes      | series tag     | fddeplib   | Federal depository library                                 | text      | text        |
| Yes      | series tag     | regional   | Regional fed dep library                                   | text      | text        |
| Yes      | series tag     | selectiv   | Selective fed dep library                                  | text      | text        |
| Yes      | series tag     | elecplan   | Network planning/monitoring                                | text      | text        |
| Yes      | series tag     | elecoper   | Network operation                                          | text      | text        |
| Yes      | series tag     | elecbibl   | DB/Bibliographic databases                                 | text      | text        |
| Yes      | series tag     | electext   | DB/Full text or data                                       | text      | text        |
| Yes      | series tag     | dig_stla   | Digitization support/STLA                                  | text      | text        |
| Yes      | series tag     | dig_ag     | Digitization support/Other agencies                        | text      | text        |
| Yes      | series tag     | dig_lib    | Digitization support/libraries                             | text      | text        |
| Yes      | series tag     | nettrstf   | Internet access support thru staffing                      | text      | text        |
| Yes      | series tag     | nettrcus   | Internet access support thru st lib end-users              | text      | text        |
| Yes      | series tag     | netsub     | Internet access support thru direct funding                | text      | text        |
| Yes      | series tag     | netequip   | Intenet access support thru prov equip                     | text      | text        |
| Yes      | series tag     | netmount   | Internet access support thru online resrcs                 | text      | text        |
| Yes      | series tag     | netgoph    | Internet access support thru website/server/list mgmt      | text      | text        |
| Yes      | series tag     | pubswdbl   | DBs avail to public libr                                   | text      | text        |
| Yes      | series tag     | acswdbl    | DBs avail to acad libr                                     | text      | text        |
| Yes      | series tag     | schswdbl   | DBs avail to sch libr                                      | text      | text        |
| Yes      | series tag     | spcswdbl   | DBs avail to special libr                                  | text      | text        |
| Yes      | series tag     | lcswdbl    | DBs avail to co-ops                                        | text      | text        |
| Yes      | series tag     | othswdbl   | DBs avail to state agencies                                | text      | text        |
| Yes      | series tag     | remoteac   | DBs avail to remote users                                  | text      | text        |
| Yes      | series tag     | acccdrom   | CDROM union catalog                                        | text      | text        |
| Yes      | series tag     | acctlnet   | Telnet gateway                                             | text      | text        |
| Yes      | series tag     | accwbcat   | Union catalog                                              | text      | text        |
| Yes      | series tag     | accoth     | Other access to other libr                                 | text      | text        |
| Yes      | series tag     | othaccsp   | Other access specified                                     | text      | text        |
| Yes      | series tag     | erateapp   | E-rate discount                                            | text      | text        |
| Yes      | series tag     | pub_fips   | FIPS state code                                            | text      | text        |
| Yes      | series tag     | obereg     | BEA code                                                   | text      | text        |
| Yes      | series tag     | rstatus    | Reporting Status                                           | text      | text        |
| Yes      | time           | fystart    | Fiscal year start date, mm/dd/yyyy                         | date      | date        |
| No       |                | fyend      | Fiscal year end date, mm/dd/yyyy                           | date      | date        |
| Yes      | numeric metric | tothrs     | Hours open typical week                                    | number    | number      |
| Yes      | numeric metric | tothrsce   | Hours open main outlet                                     | number    | number      |
| Yes      | numeric metric | mon2frce   | Hours open M-F after 5pm                                   | number    | number      |
| Yes      | numeric metric | satsunce   | Hours open Sat & Sun                                       | number    | number      |
| Yes      | numeric metric | mainout    | Outlets (main)                                             | number    | number      |
| Yes      | numeric metric | otherout   | Outlets (other)                                            | number    | number      |
| Yes      | numeric metric | bkmobile   | Outlets (bookmobile)                                       | number    | number      |
| Yes      | numeric metric | totalout   | Outlets (TOTAL)                                            | number    | number      |
| Yes      | numeric metric | bphouta    | BPH Outlets (main)                                         | number    | number      |
| Yes      | numeric metric | bphoutb    | BPH Outlets (other)                                        | number    | number      |
| Yes      | numeric metric | bphoutc    | BPH Outlets (bookmobile)                                   | number    | number      |
| Yes      | numeric metric | bphoutd    | BPH Outlets (TOTAL)                                        | number    | number      |
| Yes      | numeric metric | corouta    | Corr Outlets (main)                                        | number    | number      |
| Yes      | numeric metric | coroutb    | Corr Outlets (other)                                       | number    | number      |
| Yes      | numeric metric | coroutc    | Corr Outlets (bookmobile)                                  | number    | number      |
| Yes      | numeric metric | coroutd    | Corr Outlets (TOTAL)                                       | number    | number      |
| Yes      | numeric metric | otstouta   | Inst Outlets (main)                                        | number    | number      |
| Yes      | numeric metric | otstoutb   | Inst Outlets (other)                                       | number    | number      |
| Yes      | numeric metric | otstoutc   | Inst Outlets (bookmobile)                                  | number    | number      |
| Yes      | numeric metric | otstoutd   | Inst Outlets (TOTAL)                                       | number    | number      |
| Yes      | numeric metric | gvemouta   | Govt Outlets (main)                                        | number    | number      |
| Yes      | numeric metric | gvemoutb   | Govt Outlets (other)                                       | number    | number      |
| Yes      | numeric metric | gvemoutc   | Govt Outlets (bookmobile)                                  | number    | number      |
| Yes      | numeric metric | gvemoutd   | Govt Outlets (TOTAL)                                       | number    | number      |
| Yes      | numeric metric | gpouta     | Pub Outlets (main)                                         | number    | number      |
| Yes      | numeric metric | gpoutb     | Pub Outlets (other)                                        | number    | number      |
| Yes      | numeric metric | gpoutc     | Pub Outlets (bookmobile)                                   | number    | number      |
| Yes      | numeric metric | gpoutd     | Pub Outlets (TOTAL)                                        | number    | number      |
| Yes      | numeric metric | bkservol   | Volumes                                                    | number    | number      |
| Yes      | numeric metric | audio      | Audio Materials                                            | number    | number      |
| Yes      | numeric metric | video      | Video Materials                                            | number    | number      |
| Yes      | numeric metric | subscrip   | Serial Subs                                                | number    | number      |
| Yes      | numeric metric | govdoc     | Govt Documents                                             | number    | number      |
| Yes      | numeric metric | circ       | Circulation                                                | number    | number      |
| Yes      | numeric metric | provto     | ILL out                                                    | number    | number      |
| Yes      | numeric metric | recfrom    | ILL in                                                     | number    | number      |
| Yes      | numeric metric | reftrans   | Reference transactions                                     | number    | number      |
| Yes      | numeric metric | libvists   | Library visits                                             | number    | number      |
| Yes      | numeric metric | grantaw    | Grants awarded                                             | number    | number      |
| Yes      | numeric metric | events     | Number of events                                           | number    | number      |
| Yes      | numeric metric | atevents   | Total attendance                                           | number    | number      |
| Yes      | numeric metric | admin      | Admin TOTAL                                                | number    | number      |
| Yes      | numeric metric | libdev     | Dev TOTAL                                                  | number    | number      |
| Yes      | numeric metric | libserv    | Services TOTAL                                             | number    | number      |
| Yes      | numeric metric | othserv    | Other TOTAL                                                | number    | number      |
| Yes      | numeric metric | totstaff   | Total staff                                                | number    | number      |
| Yes      | numeric metric | pagiw_lo   | Internet access thru lib owned terminals                   | number    | number      |
| Yes      | numeric metric | paiw_oth   | Internet access thru other terminals                       | number    | number      |
| Yes      | numeric metric | swdblica   | DB licensing exp federal                                   | number    | number      |
| Yes      | numeric metric | swdblicb   | DB licensing exp state                                     | number    | number      |
| Yes      | numeric metric | swdblicc   | DB licensing exp other                                     | number    | number      |
| Yes      | numeric metric | swdblicd   | DB licensing exp TOTAL                                     | number    | number      |
| Yes      | numeric metric | popu_st    | Population                                                 | number    | number      |
```

## Time Field

```ls
Value = fystart
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = fyend
```

## Data Commands

```ls
series e:inm4-3tsj d:2006-07-01T00:00:00.000Z t:appbygov=P t:physaddr="333 WILLOUGHBY AVENUE" t:stlacont=Y t:mailzip=99811 t:netmount=Y t:acccdrom=N t:mailaddr="P.O. BOX 110571" t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:acctlnet=Y t:webaddr=WWW.LIBRARY.STATE.AK.US t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=Y t:mail_st=AK t:obereg=8 t:elecbibl=Y t:phys_st=AK t:pla_gov=X t:netsub=Y t:fddeplib=Y t:othallsp=P t:dig_ag=N t:starchiv=Y t:pld_oth=P t:strecmng=Y t:accoth=Y t:largerag=E t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:physcity=JUNEAU t:nettrstf=Y t:mailcity=JUNEAU t:pub_fips=2 t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=99811 t:dig_stla=Y t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=N t:nettrcus=Y t:mailzip4=571 t:othaccsp="STATEWIDE ONLINE PERIODICALS DATABASE" t:netequip=Y t:pla_brco=Y t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=Y t:indagy=P t:acswdbl=Y m:libserv=22 m:mainout=1 m:bkservol=134299 m:govdoc=601224 m:othserv=3 m:libvists=56331 m:bkmobile=0 m:mon2frce=0 m:video=1031 m:otstoutd=0 m:otstoutc=0 m:atevents=952 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=1 m:grantaw=194 m:swdblicd=33000 m:tothrsce=38 m:coroutd=0 m:coroutb=0 m:swdblicb=0 m:coroutc=0 m:swdblicc=0 m:events=43 m:swdblica=33000 m:corouta=0 m:recfrom=1950 m:gvemoutd=1 m:gvemoutc=0 m:bphoutc=0 m:gvemoutb=0 m:bphoutb=1 m:gvemouta=1 m:bphouta=0 m:provto=777 m:bphoutd=1 m:popu_st=683478 m:subscrip=1503 m:paiw_oth=0 m:reftrans=15867 m:audio=138 m:gpouta=1 m:pagiw_lo=7 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:totalout=2 m:circ=2884 m:admin=5 m:totstaff=35.5 m:libdev=5.5 m:tothrs=75

series e:inm4-3tsj d:2006-10-01T00:00:00.000Z t:appbygov=X t:physaddr="6030 MONTICELLO DRIVE" t:stlacont=N t:mailzip=36130 t:netmount=Y t:acccdrom=N t:mailaddr="6030 MONTICELLO DRIVE" t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:acctlnet=N t:webaddr=statelibrary.alabama.gov/Content/Index.aspx t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=N t:sthstmus=N t:mail_st=AL t:obereg=5 t:elecbibl=Y t:phys_st=AL t:pla_gov=P t:netsub=Y t:fddeplib=N t:othallsp=P t:dig_ag=N t:starchiv=N t:pld_oth=P t:strecmng=N t:accoth=N t:largerag=P t:dig_lib=Y t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:physcity=MONTGOMERY t:nettrstf=Y t:mailcity=MONTGOMERY t:pub_fips=1 t:elecoper=N t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=36117 t:dig_stla=N t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=N t:nettrcus=Y t:mailzip4=1 t:othaccsp=P t:netequip=N t:pla_brco=P t:spcswdbl=Y t:accwbcat=Y t:regional=N t:stlegref=N t:selectiv=N t:indagy=B t:acswdbl=Y m:libserv=22 m:mainout=1 m:bkservol=93426 m:govdoc=0 m:othserv=7 m:libvists=12274 m:bkmobile=0 m:mon2frce=0 m:video=1135 m:otstoutd=0 m:otstoutc=0 m:atevents=5467 m:otstoutb=0 m:otstouta=0 m:satsunce=0 m:otherout=0 m:grantaw=130 m:swdblicd=3844375 m:tothrsce=40 m:coroutd=0 m:coroutb=0 m:swdblicb=3757600 m:coroutc=0 m:swdblicc=0 m:events=275 m:swdblica=86775 m:corouta=0 m:recfrom=429 m:gvemoutd=1 m:gvemoutc=0 m:bphoutc=0 m:gvemoutb=0 m:bphoutb=0 m:gvemouta=1 m:bphouta=1 m:provto=4721 m:bphoutd=1 m:popu_st=4627851 m:subscrip=344 m:paiw_oth=0 m:reftrans=12623 m:audio=0 m:gpouta=1 m:pagiw_lo=21 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:totalout=1 m:circ=6416 m:admin=10 m:totstaff=47 m:libdev=8 m:tothrs=40

series e:inm4-3tsj d:2006-07-01T00:00:00.000Z t:appbygov=P t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlacont=N t:mailzip=72201 t:netmount=Y t:acccdrom=N t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1013 t:acctlnet=Y t:webaddr=WWW.ASL.LIB.AR.US t:othallop=N t:netgoph=Y t:remoteac=Y t:stdeplib=Y t:sthstmus=N t:mail_st=AR t:obereg=5 t:elecbibl=Y t:phys_st=AR t:pla_gov=X t:netsub=N t:fddeplib=Y t:othallsp=P t:dig_ag=N t:starchiv=N t:pld_oth=P t:strecmng=N t:accoth=N t:largerag=E t:dig_lib=N t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:physcity="LITTLE ROCK" t:nettrstf=Y t:mailcity="LITTLE ROCK" t:pub_fips=5 t:elecoper=Y t:othagsp=P t:appbyoth=P t:elecplan=Y t:rstatus=1 t:physzip=72201 t:dig_stla=N t:electext=Y t:lcswdbl=Y t:othswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=1013 t:othaccsp=P t:netequip=N t:pla_brco=Y t:spcswdbl=Y t:accwbcat=Y t:regional=Y t:stlegref=N t:selectiv=N t:indagy=P t:acswdbl=Y m:libserv=37 m:mainout=1 m:bkservol=102025 m:govdoc=2804457 m:othserv=4 m:libvists=8449 m:bkmobile=0 m:mon2frce=0 m:video=1143 m:otstoutd=1 m:otstoutc=0 m:atevents=3326 m:otstoutb=0 m:otstouta=1 m:satsunce=0 m:otherout=0 m:grantaw=0 m:swdblicd=810516 m:tothrsce=45 m:coroutd=1 m:coroutb=0 m:swdblicb=105381 m:coroutc=0 m:swdblicc=0 m:events=78 m:swdblica=705135 m:corouta=1 m:recfrom=263 m:gvemoutd=1 m:gvemoutc=0 m:bphoutc=0 m:gvemoutb=0 m:bphoutb=0 m:gvemouta=1 m:bphouta=1 m:provto=1803 m:bphoutd=1 m:popu_st=2834797 m:subscrip=1213 m:paiw_oth=0 m:reftrans=3196 m:audio=660 m:gpouta=1 m:pagiw_lo=11 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:totalout=1 m:circ=1838 m:admin=12 m:totstaff=58 m:libdev=5 m:tothrs=45
```

## Meta Commands

```ls
metric m:tothrs p:float l:"Hours open typical week" t:dataTypeName=number

metric m:tothrsce p:float l:"Hours open main outlet" t:dataTypeName=number

metric m:mon2frce p:float l:"Hours open M-F after 5pm" t:dataTypeName=number

metric m:satsunce p:float l:"Hours open Sat & Sun" t:dataTypeName=number

metric m:mainout p:float l:"Outlets (main)" t:dataTypeName=number

metric m:otherout p:float l:"Outlets (other)" t:dataTypeName=number

metric m:bkmobile p:float l:"Outlets (bookmobile)" t:dataTypeName=number

metric m:totalout p:float l:"Outlets (TOTAL)" t:dataTypeName=number

metric m:bphouta p:float l:"BPH Outlets (main)" t:dataTypeName=number

metric m:bphoutb p:float l:"BPH Outlets (other)" t:dataTypeName=number

metric m:bphoutc p:float l:"BPH Outlets (bookmobile)" t:dataTypeName=number

metric m:bphoutd p:float l:"BPH Outlets (TOTAL)" t:dataTypeName=number

metric m:corouta p:float l:"Corr Outlets (main)" t:dataTypeName=number

metric m:coroutb p:float l:"Corr Outlets (other)" t:dataTypeName=number

metric m:coroutc p:float l:"Corr Outlets (bookmobile)" t:dataTypeName=number

metric m:coroutd p:float l:"Corr Outlets (TOTAL)" t:dataTypeName=number

metric m:otstouta p:float l:"Inst Outlets (main)" t:dataTypeName=number

metric m:otstoutb p:float l:"Inst Outlets (other)" t:dataTypeName=number

metric m:otstoutc p:float l:"Inst Outlets (bookmobile)" t:dataTypeName=number

metric m:otstoutd p:float l:"Inst Outlets (TOTAL)" t:dataTypeName=number

metric m:gvemouta p:float l:"Govt Outlets (main)" t:dataTypeName=number

metric m:gvemoutb p:float l:"Govt Outlets (other)" t:dataTypeName=number

metric m:gvemoutc p:float l:"Govt Outlets (bookmobile)" t:dataTypeName=number

metric m:gvemoutd p:float l:"Govt Outlets (TOTAL)" t:dataTypeName=number

metric m:gpouta p:float l:"Pub Outlets (main)" t:dataTypeName=number

metric m:gpoutb p:float l:"Pub Outlets (other)" t:dataTypeName=number

metric m:gpoutc p:float l:"Pub Outlets (bookmobile)" t:dataTypeName=number

metric m:gpoutd p:float l:"Pub Outlets (TOTAL)" t:dataTypeName=number

metric m:bkservol p:float l:Volumes t:dataTypeName=number

metric m:audio p:float l:"Audio Materials" t:dataTypeName=number

metric m:video p:float l:"Video Materials" t:dataTypeName=number

metric m:subscrip p:float l:"Serial Subs" t:dataTypeName=number

metric m:govdoc p:float l:"Govt Documents" t:dataTypeName=number

metric m:circ p:float l:Circulation t:dataTypeName=number

metric m:provto p:float l:"ILL out" t:dataTypeName=number

metric m:recfrom p:float l:"ILL in" t:dataTypeName=number

metric m:reftrans p:float l:"Reference transactions" t:dataTypeName=number

metric m:libvists p:float l:"Library visits" t:dataTypeName=number

metric m:grantaw p:float l:"Grants awarded" t:dataTypeName=number

metric m:events p:float l:"Number of events" t:dataTypeName=number

metric m:atevents p:float l:"Total attendance" t:dataTypeName=number

metric m:admin p:float l:"Admin TOTAL" t:dataTypeName=number

metric m:libdev p:float l:"Dev TOTAL" t:dataTypeName=number

metric m:libserv p:float l:"Services TOTAL" t:dataTypeName=number

metric m:othserv p:float l:"Other TOTAL" t:dataTypeName=number

metric m:totstaff p:float l:"Total staff" t:dataTypeName=number

metric m:pagiw_lo p:float l:"Internet access thru lib owned terminals" t:dataTypeName=number

metric m:paiw_oth p:float l:"Internet access thru other terminals" t:dataTypeName=number

metric m:swdblica p:integer l:"DB licensing exp federal" t:dataTypeName=number

metric m:swdblicb p:integer l:"DB licensing exp state" t:dataTypeName=number

metric m:swdblicc p:integer l:"DB licensing exp other" t:dataTypeName=number

metric m:swdblicd p:integer l:"DB licensing exp TOTAL" t:dataTypeName=number

metric m:popu_st p:double l:Population t:dataTypeName=number

entity e:inm4-3tsj l:"State Libraries Survey, FY 2007, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/inm4-3tsj

property e:inm4-3tsj t:meta.view v:id=inm4-3tsj v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2007, Part 1: Operations & Workforce" v:attribution=IMLS

property e:inm4-3tsj t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:inm4-3tsj t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:inm4-3tsj t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:inm4-3tsj t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                              | mailcity    | mail_st | mailzip | mailzip4 | webaddr                                     | branch | indagy | appbygov | appbyoth | largerag | othagsp | pla_brco | pla_gov | pld_oth | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp                    | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | elecplan | elecoper | elecbibl | electext | dig_stla | dig_ag | dig_lib | nettrstf | nettrcus | netsub | netequip | netmount | netgoph | pubswdbl | acswdbl | schswdbl | spcswdbl | lcswdbl | othswdbl | remoteac | acccdrom | acctlnet | accwbcat | accoth | othaccsp                              | erateapp | pub_fips | obereg | rstatus | fystart    | fyend      | tothrs | tothrsce | mon2frce | satsunce | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol  | audio   | video   | subscrip | govdoc    | circ    | provto  | recfrom | reftrans | libvists | grantaw | events | atevents | admin | libdev | libserv | othserv | totstaff | pagiw_lo | paiw_oth | swdblica | swdblicb | swdblicc | swdblicd | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ===================================== | =========== | ======= | ======= | ======== | =========================================== | ====== | ====== | ======== | ======== | ======== | ======= | ======== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | =========================== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======= | ======== | ======== | ====== | ======== | ======== | ======= | ======== | ======= | ======== | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ====== | ===================================== | ======== | ======== | ====== | ======= | ========== | ========== | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ========= | ======= | ======= | ======== | ========= | ======= | ======= | ======= | ======== | ======== | ======= | ====== | ======== | ===== | ====== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571                       | JUNEAU      | AK      | 99811   | 571      | WWW.LIBRARY.STATE.AK.US                     | E      | P      | P        | P        | E        | P       | Y        | X       | P       | Y        | N        | Y        | Y        | N        | P                           | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | N      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | Y        | Y        | Y      | STATEWIDE ONLINE PERIODICALS DATABASE | N        | 2        | 8      | 1       | 1151712000 | 1183161600 | 75.0   | 38.0     | 0.0      | 0.0      | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 134299.0  | 138.0   | 1031.0  | 1503.0   | 601224.0  | 2884.0  | 777.0   | 1950.0  | 15867.0  | 56331.0  | 194.0   | 43.0   | 952.0    | 5.0   | 5.5    | 22.0    | 3.0     | 35.5     | 7.0      | 0.0      | 33000    | 0        | 0        | 33000    | 683478.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE                 | MONTGOMERY  | AL      | 36130   | 1        | statelibrary.alabama.gov/Content/Index.aspx | E      | B      | X        | P        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | N        | N        | N        | N        | N        | Y        | N        | Y        | Y        | N        | N      | Y       | Y        | Y        | Y      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | N        | Y        | N      | P                                     | N        | 1        | 5      | 1       | 1159660800 | 1191110400 | 40.0   | 40.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 93426.0   | 0.0     | 1135.0  | 344.0    | 0.0       | 6416.0  | 4721.0  | 429.0   | 12623.0  | 12274.0  | 130.0   | 275.0  | 5467.0   | 10.0  | 8.0    | 22.0    | 7.0     | 47.0     | 21.0     | 0.0      | 86775    | 3757600  | 0        | 3844375  | 4627851.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR                 | LITTLE ROCK | AR      | 72201   | 1013     | ONE CAPITOL MALL, FIFTH FLOOR         | LITTLE ROCK | AR      | 72201   | 1013     | WWW.ASL.LIB.AR.US                           | E      | P      | P        | P        | E        | P       | Y        | X       | P       | N        | N        | N        | N        | N        | P                           | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | N        | N      | N       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | Y        | Y        | N      | P                                     | N        | 5        | 5      | 1       | 1151712000 | 1183161600 | 45.0   | 45.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 102025.0  | 660.0   | 1143.0  | 1213.0   | 2804457.0 | 1838.0  | 1803.0  | 263.0   | 3196.0   | 8449.0   | 0.0     | 78.0   | 3326.0   | 12.0  | 5.0    | 37.0    | 4.0     | 58.0     | 11.0     | 0.0      | 705135   | 105381   | 0        | 810516   | 2834797.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1700 WEST WASHINGTON STREET SUITE 200 | PHOENIX     | AZ      | 85007   | 2896     | WWW.LIB.AZ.US                               | L      | P      | P        | P        | P        | P       | P        | P       | P       | Y        | Y        | Y        | Y        | N        | P                           | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | N       | N        | Y        | Y       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | 4        | 6      | 1       | 1151712000 | 1183161600 | 90.0   | 45.0     | 0.0      | 0.0      | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 1.0     | 1.0     | 0.0     | 2.0     | 1.0      | 1.0      | 0.0      | 2.0      | 1.0      | 1.0      | 0.0      | 2.0      | 1.0    | 1.0    | 0.0    | 2.0    | 699158.0  | 17171.0 | 502.0   | 1044.0   | 498710.0  | 40023.0 | 2887.0  | 1174.0  | 17155.0  | 11664.0  | 74.0    | 150.0  | 4111.0   | 16.8  | 12.0   | 50.8    | 45.0    | 124.6    | 11.0     | 0.0      | 428654   | 0        | 0        | 428654   | 6338755.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837                       | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                          | E      | G      | P        | P        | P        | P       | P        | P       | P       | N        | Y        | N        | N        | N        | P                           | Y        | Y        | Y        | Y        | Y        | N        | Y        | N        | Y        | N        | Y        | N      | Y       | Y        | Y        | Y      | N        | Y        | Y       | Y        | N       | N        | N        | N       | N        | Y        | N        | N        | Y        | N      | P                                     | N        | 6        | 8      | 2       | 1151712000 | 1183161600 | 108.0  | 32.0     | 0.0      | 0.0      | 1.0     | 2.0      | 0.0      | 3.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 2.0      | 0.0      | 3.0      | 1.0    | 1.0    | 0.0    | 2.0    | 892481.0  | 870.0   | 1604.0  | 3016.0   | 4561592.0 | 48874.0 | 21256.0 | 395.0   | 30988.0  | 73707.0  | 156.0   | 532.0  | 12634.0  | 36.0  | 27.0   | 90.0    | 28.5    | 181.5    | 15.0     | 0.0      | 1171794  | 0        | 0        | 1171794  | 36553215.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1799     | 201 EAST COLFAX, #309                 | DENVER      | CO      | 80203   | 1799     | WWW.CDE.STATE.CO.US/INDEX_LIBRARY.HTM       | E      | P      | P        | P        | E        | P       | N        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | N        | Y        | N        | N        | N        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | N      | N        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | 8        | 7      | 1       | 1151712000 | 1183161600 | 90.0   | 0.0      | 0.0      | 0.0      | 0.0     | 2.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 1.0      | 0.0    | 2.0    | 0.0    | 2.0    | 93771.0   | 10174.0 | 669.0   | 42.0     | 0.0       | 918.0   | 474.0   | 387.0   | 414.0    | 2289.0   | 99.0    | 316.0  | 6320.0   | 8.0   | 13.5   | 17.0    | 2.0     | 40.5     | 2.0      | 0.0      | 125200   | 0        | 0        | 125200   | 4861515.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE                    | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                               | E      | B      | X        | X        | P        | P       | P        | P       | P       | Y        | N        | Y        | Y        | N        | P                           | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N      | N       | Y        | Y        | N      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | N       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | 9        | 1      | 1       | 1151712000 | 1183161600 | 155.0  | 45.0     | 0.0      | 5.0      | 1.0     | 3.0      | 0.0      | 4.0      | 0.0     | 1.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 1.0      | 0.0      | 2.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 1.0    | 0.0    | 2.0    | 1209699.0 | 509.0   | 1189.0  | 5581.0   | 1739788.0 | 1511.0  | 1247.0  | 108.0   | 38527.0  | 57920.0  | 348.0   | 178.0  | 2543.0   | 16.0  | 20.0   | 60.0    | 22.0    | 118.0    | 39.0     | 0.0      | 69905    | 1758656  | 11956    | 1840517  | 3502309.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.                    | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                           | E      | B      | P        | X        | P        | P       | P        | P       | P       | N        | N        | N        | N        | N        | P                           | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N        | N      | N       | N        | N        | N      | Y        | Y        | Y       | N        | N       | N        | N        | N       | N        | N        | N        | N        | N        | N      | P                                     | Y        | 11       | 2      | 1       | 1159660800 | 1191110400 | 40.0   | 0.0      | 0.0      | 0.0      | 0.0     | 1.0      | 0.0      | 1.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0       | 0.0     | 0.0     | 0.0      | 0.0       | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 3.0     | 0.0    | 0.0      | 1.0   | 0.0    | 8.0     | 0.0     | 9.0      | 0.0      | 0.0      | 0        | 0        | 0        | 0        | 588292.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY               | DOVER       | DE      | 19901   | 7430     | WWW.STATE.LIB.DE.US                         | E      | P      | P        | P        | S        | P       | Y        | X       | X       | N        | N        | N        | N        | N        | P                           | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | N      | N       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | Y        | Y       | N        | Y        | N        | N        | Y        | Y      | WEB PAGE ACCESS                       | N        | 10       | 2      | 1       | 1151712000 | 1183161600 | 42.0   | 42.0     | 0.0      | 0.0      | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 2079.0    | 0.0     | 3.0     | 45.0     | 261.0     | 19893.0 | 0.0     | 31.0    | 3682.0   | 8400.0   | 81.0    | 50.0   | 1629.0   | 6.0   | 5.0    | 10.0    | 1.0     | 22.0     | 16.0     | 0.0      | 0        | 451983   | 0        | 451983   | 864764.0   | 
| STATE LIBRARY AND ARCHIVES OF FLORIDA              | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET             | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                        | E      | P      | P        | P        | S        | P       | Y        | P       | X       | Y        | N        | N        | Y        | Y        | FLORIDA ADMINISTRATIVE CODE | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y       | Y        | Y        | Y      | Y        | Y        | Y       | Y        | Y       | Y        | N        | Y       | Y        | Y        | N        | N        | Y        | N      | P                                     | Y        | 12       | 5      | 1       | 1151712000 | 1183161600 | 152.0  | 51.0     | 0.0      | 6.0      | 1.0     | 2.0      | 0.0      | 3.0      | 1.0     | 2.0     | 0.0     | 3.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 2.0      | 0.0      | 3.0      | 1.0    | 2.0    | 0.0    | 3.0    | 259826.0  | 60062.0 | 16107.0 | 1636.0   | 36389.0   | 16035.0 | 20599.0 | 3863.0  | 100869.0 | 16873.0  | 269.0   | 157.0  | 4952.0   | 5.5   | 18.0   | 21.0    | 74.5    | 119.0    | 21.0     | 3.0      | 2004000  | 0        | 0        | 2004000  | 18251243.0 | 
```