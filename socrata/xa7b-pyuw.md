# State Libraries Survey, FY 2000, Part 1: Operations & Workforce

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-libraries-survey-fy-2000-part-1-operations-workforce) |
| Metadata | [Link](https://data.imls.gov/api/views/xa7b-pyuw) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/xa7b-pyuw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/xa7b-pyuw/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | xa7b-pyuw |
| Name | State Libraries Survey, FY 2000, Part 1: Operations & Workforce |
| Attribution | IMLS |
| Category | State Library Administrative Agencies Survey |
| Tags | state library, slaa, 2000, operations, workforce |
| Created | 2016-12-20T20:45:37Z |
| Publication Date | 2016-12-20T21:42:48Z |

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
| Yes      | series tag     | nettrstf   | Internet access support thru staffing                      | text      | text        |
| Yes      | series tag     | nettrcus   | Internet access support thru st lib end-users              | text      | text        |
| Yes      | series tag     | netsub     | Internet access support thru direct funding                | text      | text        |
| Yes      | series tag     | netequip   | Intenet access support thru prov equip                     | text      | text        |
| Yes      | series tag     | netmount   | Internet access support thru online resrcs                 | text      | text        |
| Yes      | series tag     | netgoph    | Internet access support thru website/server/list mgmt      | text      | text        |
| Yes      | series tag     | ficsp      | Fastest internet speed                                     | text      | text        |
| Yes      | series tag     | ficspsp    | Other speed specified                                      | text      | text        |
| Yes      | series tag     | inrefreq   | Internet reference questions                               | text      | text        |
| Yes      | series tag     | accoldb    | DBs avail to other libr                                    | text      | text        |
| Yes      | series tag     | pubswdbl   | DBs avail to public libr                                   | text      | text        |
| Yes      | series tag     | acswdbl    | DBs avail to acad libr                                     | text      | text        |
| Yes      | series tag     | schswdbl   | DBs avail to sch libr                                      | text      | text        |
| Yes      | series tag     | spcswdbl   | DBs avail to special libr                                  | text      | text        |
| Yes      | series tag     | lcswdbl    | DBs avail to co-ops                                        | text      | text        |
| Yes      | series tag     | othswdbl   | DBs avail to state agencies                                | text      | text        |
| Yes      | series tag     | remoteac   | DBs avail to remote users                                  | text      | text        |
| Yes      | series tag     | acccdrom   | CDROM union catalog                                        | text      | text        |
| Yes      | series tag     | accoclc    | OCLC participation                                         | text      | text        |
| Yes      | series tag     | acctlnet   | Telnet gateway                                             | text      | text        |
| Yes      | series tag     | accwbcat   | Union catalog                                              | text      | text        |
| Yes      | series tag     | acczgway   | Z39.50 gateway                                             | text      | text        |
| Yes      | series tag     | accoth     | Other access to other libr                                 | text      | text        |
| Yes      | series tag     | othaccsp   | Other access specified                                     | text      | text        |
| Yes      | series tag     | erateapp   | E-rate discount                                            | text      | text        |
| Yes      | series tag     | iacoop     | Grants to assist/monitor cooperation                       | text      | text        |
| Yes      | series tag     | lpartnr    | Grants to assist/monitor partnerships                      | text      | text        |
| Yes      | series tag     | pub_fips   | FIPS state code                                            | text      | text        |
| Yes      | time           | fystart    | Fiscal year start date, mm/dd/yyyy                         | date      | date        |
| No       |                | fyend      | Fiscal year end date, mm/dd/yyyy                           | date      | date        |
| Yes      | numeric metric | tothrswk   | Hours open typical week                                    | number    | number      |
| Yes      | numeric metric | mon2fri    | Hours open M-F after 5pm                                   | number    | number      |
| Yes      | numeric metric | sat2sun    | Hours open Sat & Sun                                       | number    | number      |
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
| Yes      | series tag     | gencol     | General collection                                         | text      | text        |
| Yes      | numeric metric | circ       | Circulation                                                | number    | number      |
| Yes      | numeric metric | provto     | ILL out                                                    | number    | number      |
| Yes      | numeric metric | recfrom    | ILL in                                                     | number    | number      |
| Yes      | numeric metric | reftrans   | Reference transactions                                     | number    | number      |
| Yes      | numeric metric | libvists   | Library visits                                             | number    | number      |
| Yes      | numeric metric | events     | Number of events                                           | number    | number      |
| Yes      | numeric metric | atevents   | Total attendance                                           | number    | number      |
| Yes      | numeric metric | grantmon   | Grants monitored                                           | number    | number      |
| Yes      | numeric metric | onsitmon   | On-site monitoring visits                                  | number    | number      |
| Yes      | numeric metric | admserva   | Admin ALA-MLS                                              | number    | number      |
| Yes      | numeric metric | admservb   | Admin professional                                         | number    | number      |
| Yes      | numeric metric | admservc   | Admin other                                                | number    | number      |
| Yes      | numeric metric | admservd   | Admin TOTAL                                                | number    | number      |
| Yes      | numeric metric | ldpuba     | Libr Dev ALA-MLS                                           | number    | number      |
| Yes      | numeric metric | ldpubb     | Libr Dev professional                                      | number    | number      |
| Yes      | numeric metric | ldpubc     | Libr Dev other                                             | number    | number      |
| Yes      | numeric metric | ldpubd     | Libr Dev TOTAL                                             | number    | number      |
| Yes      | numeric metric | ldscha     | Libr Dev school ALA-MLS                                    | number    | number      |
| Yes      | numeric metric | ldschb     | Libr Dev school professional                               | number    | number      |
| Yes      | numeric metric | ldschc     | Libr Dev school other                                      | number    | number      |
| Yes      | numeric metric | ldschd     | Libr Dev school TOTAL                                      | number    | number      |
| Yes      | numeric metric | ldacada    | Libr Dev acad ALA-MLS                                      | number    | number      |
| Yes      | numeric metric | ldacadb    | Libr Dev acad professional                                 | number    | number      |
| Yes      | numeric metric | ldacadc    | Libr Dev acad other                                        | number    | number      |
| Yes      | numeric metric | ldacadd    | Libr Dev acad TOTAL                                        | number    | number      |
| Yes      | numeric metric | ldspeca    | Libr Dev special ALA-MLS                                   | number    | number      |
| Yes      | numeric metric | ldspecb    | Libr Dev special professional                              | number    | number      |
| Yes      | numeric metric | ldspecc    | Libr Dev special other                                     | number    | number      |
| Yes      | numeric metric | ldspecd    | Libr Dev special TOTAL                                     | number    | number      |
| Yes      | numeric metric | ldothlba   | Libr Dev other ALA-MLS                                     | number    | number      |
| Yes      | numeric metric | ldothlbb   | Libr Dev other professional                                | number    | number      |
| Yes      | numeric metric | ldothlbc   | Libr Dev other other                                       | number    | number      |
| Yes      | numeric metric | ldothlbd   | Libr Dev other TOTAL                                       | number    | number      |
| Yes      | numeric metric | totallda   | Libr Dev total ALA-MLS                                     | number    | number      |
| Yes      | numeric metric | totalldb   | Libr Dev total professional                                | number    | number      |
| Yes      | numeric metric | totalldc   | Libr Dev total other                                       | number    | number      |
| Yes      | numeric metric | totalldd   | Libr Dev total TOTAL                                       | number    | number      |
| Yes      | numeric metric | lspubsva   | Libr svcs public ALA-MLS                                   | number    | number      |
| Yes      | numeric metric | lspubsvb   | Libr svcs public professional                              | number    | number      |
| Yes      | numeric metric | lspubsvc   | Libr svcs public other                                     | number    | number      |
| Yes      | numeric metric | lspubsvd   | Libr svcs public TOTAL                                     | number    | number      |
| Yes      | numeric metric | lstecsva   | Libr svcs tech ALA-MLS                                     | number    | number      |
| Yes      | numeric metric | lstecsvb   | Libr svcs tech professional                                | number    | number      |
| Yes      | numeric metric | lstecsvc   | Libr svcs tech other                                       | number    | number      |
| Yes      | numeric metric | lstecsvd   | Libr svcs tech TOTAL                                       | number    | number      |
| Yes      | numeric metric | lsothlsa   | Libr svcs other ALA-MLS                                    | number    | number      |
| Yes      | numeric metric | lsothlsb   | Libr svcs other professional                               | number    | number      |
| Yes      | numeric metric | lsothlsc   | Libr svcs other other                                      | number    | number      |
| Yes      | numeric metric | lsothlsd   | Libr svcs other TOTAL                                      | number    | number      |
| Yes      | numeric metric | totallsa   | Libr svcs total ALA-MLS                                    | number    | number      |
| Yes      | numeric metric | totallsb   | Libr svcs total professional                               | number    | number      |
| Yes      | numeric metric | totallsc   | Libr svcs total other                                      | number    | number      |
| Yes      | numeric metric | totallsd   | Libr svcs total TOTAL                                      | number    | number      |
| Yes      | numeric metric | othersva   | Other svcs ALA-MLS                                         | number    | number      |
| Yes      | numeric metric | othersvb   | Other svcs professional                                    | number    | number      |
| Yes      | numeric metric | othersvc   | Other svcs other                                           | number    | number      |
| Yes      | numeric metric | othersvd   | Other svcs TOTAL                                           | number    | number      |
| Yes      | numeric metric | totstafa   | Total staff ALA-MLS                                        | number    | number      |
| Yes      | numeric metric | totstafb   | Total staff professional                                   | number    | number      |
| Yes      | numeric metric | totstafc   | Total staff other                                          | number    | number      |
| Yes      | numeric metric | totstafd   | Total staff TOTAL                                          | number    | number      |
| Yes      | numeric metric | lstasea    | Admin of LSTA grants ALA-MLS                               | number    | number      |
| Yes      | numeric metric | lstaseb    | Admin of LSTA grants professional                          | number    | number      |
| Yes      | numeric metric | lstasec    | Admin of LSTA grants other                                 | number    | number      |
| Yes      | numeric metric | lstased    | Admin of LSTA grants TOTAL                                 | number    | number      |
| Yes      | numeric metric | staidsea   | Admin of state aid ALA-MLS                                 | number    | number      |
| Yes      | numeric metric | staidseb   | Admin of state aid professional                            | number    | number      |
| Yes      | numeric metric | staidsec   | Admin of state aid other                                   | number    | number      |
| Yes      | numeric metric | staidsed   | Admin of state aid TOTAL                                   | number    | number      |
| Yes      | numeric metric | aendsea    | Automation/electronic dev ALA-MLS                          | number    | number      |
| Yes      | numeric metric | aendseb    | Automation/electronic dev professional                     | number    | number      |
| Yes      | numeric metric | aendsec    | Automation/electronic dev other                            | number    | number      |
| Yes      | numeric metric | aendsed    | Automation/electronic dev TOTAL                            | number    | number      |
| Yes      | numeric metric | bphsea     | Blind/phys hand svcs ALA-MLS                               | number    | number      |
| Yes      | numeric metric | bphseb     | Blind/phys hand svcs professional                          | number    | number      |
| Yes      | numeric metric | bphsec     | Blind/phys hand svcs other                                 | number    | number      |
| Yes      | numeric metric | bphsed     | Blind/phys hand svcs TOTAL                                 | number    | number      |
| Yes      | numeric metric | cyasea     | Childr/YA svcs ALA-MLS                                     | number    | number      |
| Yes      | numeric metric | cyaseb     | Childr/YA svcs professional                                | number    | number      |
| Yes      | numeric metric | cyasec     | Childr/YA svcs other                                       | number    | number      |
| Yes      | numeric metric | cyased     | Childr/YA svcs TOTAL                                       | number    | number      |
| Yes      | numeric metric | ilssea     | Inst libr svcs ALA-MLS                                     | number    | number      |
| Yes      | numeric metric | ilsseb     | Inst libr svcs professional                                | number    | number      |
| Yes      | numeric metric | ilssec     | Inst libr svcs other                                       | number    | number      |
| Yes      | numeric metric | ilssed     | Inst libr svcs TOTAL                                       | number    | number      |
| Yes      | numeric metric | lbstasea   | Libr statistics ALA-MLS                                    | number    | number      |
| Yes      | numeric metric | lbstaseb   | Libr statistics professional                               | number    | number      |
| Yes      | numeric metric | lbstasec   | Libr statistics other                                      | number    | number      |
| Yes      | numeric metric | lbstased   | Libr statistics TOTAL                                      | number    | number      |
| Yes      | numeric metric | litprsea   | Literacy support ALA-MLS                                   | number    | number      |
| Yes      | numeric metric | litprseb   | Literacy support professional                              | number    | number      |
| Yes      | numeric metric | litprsec   | Literacy support other                                     | number    | number      |
| Yes      | numeric metric | litprsed   | Literacy support TOTAL                                     | number    | number      |
| Yes      | numeric metric | markcoma   | Mktg/communications ALA-MLS                                | number    | number      |
| Yes      | numeric metric | markcomb   | Mktg/communications professional                           | number    | number      |
| Yes      | numeric metric | markcomc   | Mktg/communications other                                  | number    | number      |
| Yes      | numeric metric | markcomd   | Mktg/communications TOTAL                                  | number    | number      |
| Yes      | numeric metric | swdblica   | DB licensing exp federal                                   | number    | number      |
| Yes      | numeric metric | swdblicb   | DB licensing exp state                                     | number    | number      |
| Yes      | numeric metric | swdblicc   | DB licensing exp other                                     | number    | number      |
| Yes      | numeric metric | swdblicd   | DB licensing exp TOTAL                                     | number    | number      |
| Yes      | numeric metric | pubterms   | Public terminals                                           | number    | number      |
| Yes      | numeric metric | readsch    | Grants to assist/sch readiness                             | money     | money       |
| Yes      | numeric metric | adfamlit   | Grants to assist/adult & fam literacy                      | money     | money       |
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
series e:xa7b-pyuw d:1999-07-01T00:00:00.000Z t:stlacont=Y t:physaddr="333 WILLOUGHBY AVENUE" t:mailzip=99811 t:netmount=Y t:mailaddr="P.O. BOX 110571" t:acccdrom=N t:ficsp=T3 t:stlaname="DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS" t:physzip4=571 t:webaddr=WWW.STATE.AK.US/LAM/LIBRARY.HTML t:acctlnet=Y t:othallop=N t:netgoph=Y t:remoteac=Y t:lpartnr=N t:stdeplib=Y t:sthstmus=Y t:mail_st=AK t:iacoop=N t:phys_st=AK t:elecbibl=Y t:netsub=Y t:fddeplib=Y t:starchiv=Y t:strecmng=Y t:accoth=Y t:largerag=E t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:gencol=Y t:nettrstf=Y t:physcity=JUNEAU t:mailcity=JUNEAU t:pub_fips=2 t:inrefreq=Y t:elecoper=Y t:accoclc=Y t:accoldb=Y t:elecplan=Y t:physzip=99811 t:electext=Y t:othswdbl=Y t:lcswdbl=Y t:stlahost=N t:nettrcus=Y t:mailzip4=571 t:othaccsp="STATEWIDE ONLINE PERIODICALS DATABASE" t:netequip=Y t:spcswdbl=Y t:accwbcat=Y t:acczgway=N t:regional=N t:selectiv=Y t:stlegref=N t:acswdbl=Y m:totalldc=1 m:totalldb=0 m:totallda=5 m:othersva=0 m:othersvb=1 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=71446 m:othersvd=3 m:othersvc=2 m:lstecsva=2 m:lstecsvd=5 m:video=585 m:lstecsvc=3 m:lstecsvb=0 m:aendsea=2 m:aendseb=1 m:aendsec=2 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:atevents=730 m:lbstasea=0.5 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=0.5 m:mon2fri=0 m:otherout=1 m:aendsed=5 m:lsothlsb=0 m:lsothlsa=3 m:admservd=6 m:admserva=2 m:litprseb=0 m:litprsea=0 m:admservc=4 m:admservb=0 m:lspubsvb=0 m:lspubsva=5 m:lspubsvd=11 m:litprsed=0 m:lspubsvc=6 m:litprsec=0 m:coroutd=0 m:coroutb=0 m:swdblicb=0 m:coroutc=0 m:swdblicc=0 m:events=33 m:corouta=0 m:swdblica=0 m:lstasea=0.4 m:recfrom=1771 m:ilssed=0 m:bphoutc=0 m:lstased=0.4 m:bphoutb=1 m:ilsseb=0 m:lstasec=0 m:bphouta=0 m:lstaseb=0 m:ilssec=0 m:ldschc=0.5 m:ldschb=0 m:bphoutd=1 m:ldscha=1 m:popu_st=622000 m:ldschd=1.5 m:totalout=2 m:onsitmon=16 m:ilssea=0 m:readsch=0 m:circ=3430 m:tothrswk=40 m:ldpuba=1 m:ldpubb=0 m:ldpubc=0.5 m:ldpubd=1.5 m:pubterms=5 m:mainout=1 m:bkservol=107455 m:govdoc=89000 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:swdblicd=0 m:sat2sun=0 m:ldspecc=0 m:adfamlit=0 m:ldspecd=0 m:ldothlba=3 m:totallsd=22 m:totallsc=12 m:ldothlbb=0 m:ldothlbc=0 m:ldothlbd=3 m:markcomc=0 m:markcomb=0 m:gvemoutd=1 m:totallsb=0 m:markcoma=0 m:gvemoutc=0 m:totallsa=10 m:gvemoutb=0 m:gvemouta=1 m:provto=1769 m:markcomd=0 m:subscrip=1696 m:grantmon=143 m:bphsea=0.1 m:cyasea=0 m:cyaseb=0 m:bphsec=2 m:cyasec=0 m:reftrans=12208 m:bphseb=0 m:cyased=0 m:audio=119 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0.5 m:bphsed=2.1 m:staidseb=0 m:staidsec=0 m:staidsed=0.5 m:lsothlsd=6 m:lsothlsc=3 m:totstafc=19 m:totstafd=37 m:totstafa=17 m:totstafb=1

series e:xa7b-pyuw d:1999-10-01T00:00:00.000Z t:appbygov=X t:stlacont=N t:physaddr="6030 MONTICELLO DRIVE" t:mailzip=36130 t:netmount=Y t:mailaddr="6030 MONTICELLO DRIVE" t:acccdrom=Y t:ficsp=T1 t:stlaname="ALABAMA PUBLIC LIBRARY SERVICE" t:physzip4=1 t:webaddr=WWW.APLS.STATE.AL.US t:acctlnet=Y t:othallop=N t:netgoph=Y t:remoteac=N t:lpartnr=N t:stdeplib=N t:sthstmus=N t:mail_st=AL t:iacoop=N t:phys_st=AL t:elecbibl=Y t:netsub=Y t:fddeplib=Y t:starchiv=N t:strecmng=N t:accoth=N t:branch=E t:erateapp=N t:pubswdbl=N t:schswdbl=N t:gencol=Y t:nettrstf=Y t:physcity=MONTGOMERY t:mailcity=MONTGOMERY t:pub_fips=1 t:inrefreq=Y t:elecoper=N t:accoclc=Y t:accoldb=Y t:elecplan=Y t:physzip=36117 t:electext=N t:othswdbl=N t:lcswdbl=N t:stlahost=N t:nettrcus=Y t:mailzip4=1 t:netequip=N t:spcswdbl=N t:accwbcat=Y t:acczgway=Y t:regional=N t:selectiv=Y t:stlegref=N t:indagy=B t:acswdbl=N m:totalldc=1 m:totalldb=0 m:totallda=7 m:othersva=3 m:othersvb=0 m:totalldd=8 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=9082 m:othersvd=10.75 m:othersvc=7.75 m:lstecsva=1 m:lstecsvd=4 m:video=4471 m:lstecsvc=3 m:lstecsvb=0 m:aendsea=0 m:aendseb=0 m:aendsec=3.5 m:otstoutd=0 m:otstoutc=0 m:otstoutb=0 m:atevents=2216 m:lbstasea=2 m:otstouta=0 m:lbstaseb=0 m:lbstasec=0 m:lbstased=2 m:mon2fri=0 m:otherout=0 m:aendsed=3.5 m:lsothlsb=0 m:lsothlsa=0 m:admservd=13.5 m:admserva=1 m:litprseb=0 m:litprsea=0 m:admservc=10.5 m:admservb=2 m:lspubsvb=0 m:lspubsva=9 m:lspubsvd=21 m:litprsed=0 m:lspubsvc=12 m:litprsec=0 m:coroutd=0 m:coroutb=0 m:swdblicb=0 m:coroutc=0 m:swdblicc=0 m:events=145 m:corouta=0 m:swdblica=0 m:lstasea=2 m:recfrom=309 m:ilssed=0 m:bphoutc=0 m:lstased=5 m:bphoutb=0 m:ilsseb=0 m:lstasec=2 m:bphouta=1 m:lstaseb=1 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:bphoutd=1 m:ldscha=0 m:popu_st=4351999 m:ldschd=0 m:totalout=1 m:onsitmon=6 m:ilssea=0 m:readsch=0 m:circ=5195 m:tothrswk=45 m:ldpuba=7 m:ldpubb=0 m:ldpubc=1 m:ldpubd=8 m:pubterms=4 m:mainout=1 m:bkservol=177758 m:govdoc=2803 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:swdblicd=0 m:sat2sun=0 m:ldspecc=0 m:adfamlit=0 m:ldspecd=0 m:ldothlba=0 m:totallsd=25 m:totallsc=15 m:ldothlbb=0 m:ldothlbc=0 m:ldothlbd=0 m:markcomc=0 m:markcomb=0 m:gvemoutd=1 m:totallsb=0 m:markcoma=0 m:gvemoutc=0 m:totallsa=10 m:gvemoutb=0 m:gvemouta=1 m:provto=13049 m:markcomd=0 m:subscrip=1261 m:grantmon=197 m:bphsea=3 m:cyasea=1 m:cyaseb=0 m:bphsec=6 m:cyasec=0 m:reftrans=12682 m:bphseb=0 m:cyased=1 m:audio=274767 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=2 m:bphsed=9 m:staidseb=1 m:staidsec=1 m:staidsed=4 m:lsothlsd=0 m:lsothlsc=0 m:totstafc=34.25 m:totstafd=57.25 m:totstafa=21 m:totstafb=2

series e:xa7b-pyuw d:1999-07-01T00:00:00.000Z t:stlacont=N t:physaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:mailzip=72201 t:netmount=Y t:mailaddr="ONE CAPITOL MALL, FIFTH FLOOR" t:acccdrom=N t:ficsp=OTH t:stlaname="ARKANSAS STATE LIBRARY" t:physzip4=1085 t:webaddr=WWW.ASL.LIB.AR.US t:acctlnet=Y t:othallop=N t:netgoph=Y t:remoteac=Y t:lpartnr=N t:ficspsp=OC3-65MB/S t:stdeplib=Y t:sthstmus=N t:mail_st=AR t:iacoop=N t:phys_st=AR t:elecbibl=Y t:netsub=Y t:fddeplib=Y t:starchiv=N t:strecmng=N t:accoth=N t:largerag=E t:branch=E t:erateapp=N t:pubswdbl=Y t:schswdbl=Y t:gencol=Y t:nettrstf=Y t:physcity="LITTLE ROCK" t:mailcity="LITTLE ROCK" t:pub_fips=5 t:inrefreq=Y t:elecoper=Y t:accoclc=Y t:accoldb=Y t:elecplan=Y t:physzip=72201 t:electext=Y t:othswdbl=Y t:lcswdbl=Y t:stlahost=Y t:nettrcus=Y t:mailzip4=1085 t:netequip=Y t:spcswdbl=Y t:accwbcat=Y t:acczgway=Y t:regional=Y t:selectiv=N t:stlegref=N t:acswdbl=Y m:totalldc=2 m:totalldb=0 m:totallda=4 m:othersva=2 m:othersvb=2 m:totalldd=6 m:ldacada=0 m:ldacadb=0 m:ldacadc=0 m:ldacadd=0 m:libvists=9851 m:othersvd=5 m:othersvc=1 m:lstecsva=7 m:lstecsvd=17 m:video=662 m:lstecsvc=10 m:lstecsvb=0 m:aendsea=2 m:aendseb=1 m:aendsec=0 m:otstoutd=1 m:otstoutc=0 m:otstoutb=0 m:atevents=825 m:lbstasea=0.5 m:otstouta=1 m:lbstaseb=0 m:lbstasec=0 m:lbstased=0.5 m:mon2fri=0 m:otherout=0 m:aendsed=3 m:lsothlsb=0 m:lsothlsa=0 m:admservd=10 m:admserva=2 m:litprseb=0 m:litprsea=0.5 m:admservc=6 m:admservb=2 m:lspubsvb=1 m:lspubsva=5 m:lspubsvd=18 m:litprsed=0.5 m:lspubsvc=12 m:litprsec=0 m:coroutd=1 m:coroutb=0 m:swdblicb=0 m:coroutc=0 m:swdblicc=0 m:events=20 m:corouta=1 m:swdblica=707482 m:lstasea=1 m:recfrom=396 m:ilssed=0.5 m:bphoutc=0 m:lstased=1.5 m:bphoutb=0 m:ilsseb=0 m:lstasec=0 m:bphouta=1 m:lstaseb=0.5 m:ilssec=0 m:ldschc=0 m:ldschb=0 m:bphoutd=1 m:ldscha=0 m:popu_st=2538303 m:ldschd=0 m:totalout=1 m:onsitmon=25 m:ilssea=0.5 m:readsch=0 m:circ=11286 m:tothrswk=45 m:ldpuba=4 m:ldpubb=0 m:ldpubc=2 m:ldpubd=6 m:pubterms=4 m:mainout=1 m:bkservol=99972 m:govdoc=1583451 m:bkmobile=0 m:ldspecb=0 m:ldspeca=0 m:swdblicd=707482 m:sat2sun=0 m:ldspecc=0 m:adfamlit=0 m:ldspecd=0 m:ldothlba=0 m:totallsd=35 m:totallsc=22 m:ldothlbb=0 m:ldothlbc=0 m:ldothlbd=0 m:markcomc=0 m:markcomb=1 m:gvemoutd=1 m:totallsb=1 m:markcoma=0 m:gvemoutc=0 m:totallsa=12 m:gvemoutb=0 m:gvemouta=1 m:provto=12874 m:markcomd=1 m:subscrip=1500 m:grantmon=15 m:bphsea=2 m:cyasea=0.5 m:cyaseb=0 m:bphsec=6 m:cyasec=0 m:reftrans=3575 m:bphseb=1 m:cyased=0.5 m:audio=620 m:gpouta=1 m:gpoutb=0 m:gpoutc=0 m:gpoutd=1 m:staidsea=0 m:bphsed=9 m:staidseb=0.5 m:staidsec=0 m:staidsed=0.5 m:lsothlsd=0 m:lsothlsc=0 m:totstafc=31 m:totstafd=56 m:totstafa=20 m:totstafb=5
```

## Meta Commands

```ls
metric m:tothrswk p:float l:"Hours open typical week" t:dataTypeName=number

metric m:mon2fri p:float l:"Hours open M-F after 5pm" t:dataTypeName=number

metric m:sat2sun p:float l:"Hours open Sat & Sun" t:dataTypeName=number

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

metric m:events p:float l:"Number of events" t:dataTypeName=number

metric m:atevents p:float l:"Total attendance" t:dataTypeName=number

metric m:grantmon p:float l:"Grants monitored" t:dataTypeName=number

metric m:onsitmon p:float l:"On-site monitoring visits" t:dataTypeName=number

metric m:admserva p:float l:"Admin ALA-MLS" t:dataTypeName=number

metric m:admservb p:float l:"Admin professional" t:dataTypeName=number

metric m:admservc p:float l:"Admin other" t:dataTypeName=number

metric m:admservd p:float l:"Admin TOTAL" t:dataTypeName=number

metric m:ldpuba p:float l:"Libr Dev ALA-MLS" t:dataTypeName=number

metric m:ldpubb p:float l:"Libr Dev professional" t:dataTypeName=number

metric m:ldpubc p:float l:"Libr Dev other" t:dataTypeName=number

metric m:ldpubd p:float l:"Libr Dev TOTAL" t:dataTypeName=number

metric m:ldscha p:float l:"Libr Dev school ALA-MLS" t:dataTypeName=number

metric m:ldschb p:float l:"Libr Dev school professional" t:dataTypeName=number

metric m:ldschc p:float l:"Libr Dev school other" t:dataTypeName=number

metric m:ldschd p:float l:"Libr Dev school TOTAL" t:dataTypeName=number

metric m:ldacada p:float l:"Libr Dev acad ALA-MLS" t:dataTypeName=number

metric m:ldacadb p:float l:"Libr Dev acad professional" t:dataTypeName=number

metric m:ldacadc p:float l:"Libr Dev acad other" t:dataTypeName=number

metric m:ldacadd p:float l:"Libr Dev acad TOTAL" t:dataTypeName=number

metric m:ldspeca p:float l:"Libr Dev special ALA-MLS" t:dataTypeName=number

metric m:ldspecb p:float l:"Libr Dev special professional" t:dataTypeName=number

metric m:ldspecc p:float l:"Libr Dev special other" t:dataTypeName=number

metric m:ldspecd p:float l:"Libr Dev special TOTAL" t:dataTypeName=number

metric m:ldothlba p:float l:"Libr Dev other ALA-MLS" t:dataTypeName=number

metric m:ldothlbb p:float l:"Libr Dev other professional" t:dataTypeName=number

metric m:ldothlbc p:float l:"Libr Dev other other" t:dataTypeName=number

metric m:ldothlbd p:float l:"Libr Dev other TOTAL" t:dataTypeName=number

metric m:totallda p:float l:"Libr Dev total ALA-MLS" t:dataTypeName=number

metric m:totalldb p:float l:"Libr Dev total professional" t:dataTypeName=number

metric m:totalldc p:float l:"Libr Dev total other" t:dataTypeName=number

metric m:totalldd p:float l:"Libr Dev total TOTAL" t:dataTypeName=number

metric m:lspubsva p:float l:"Libr svcs public ALA-MLS" t:dataTypeName=number

metric m:lspubsvb p:float l:"Libr svcs public professional" t:dataTypeName=number

metric m:lspubsvc p:float l:"Libr svcs public other" t:dataTypeName=number

metric m:lspubsvd p:float l:"Libr svcs public TOTAL" t:dataTypeName=number

metric m:lstecsva p:float l:"Libr svcs tech ALA-MLS" t:dataTypeName=number

metric m:lstecsvb p:float l:"Libr svcs tech professional" t:dataTypeName=number

metric m:lstecsvc p:float l:"Libr svcs tech other" t:dataTypeName=number

metric m:lstecsvd p:float l:"Libr svcs tech TOTAL" t:dataTypeName=number

metric m:lsothlsa p:float l:"Libr svcs other ALA-MLS" t:dataTypeName=number

metric m:lsothlsb p:float l:"Libr svcs other professional" t:dataTypeName=number

metric m:lsothlsc p:float l:"Libr svcs other other" t:dataTypeName=number

metric m:lsothlsd p:float l:"Libr svcs other TOTAL" t:dataTypeName=number

metric m:totallsa p:float l:"Libr svcs total ALA-MLS" t:dataTypeName=number

metric m:totallsb p:float l:"Libr svcs total professional" t:dataTypeName=number

metric m:totallsc p:float l:"Libr svcs total other" t:dataTypeName=number

metric m:totallsd p:float l:"Libr svcs total TOTAL" t:dataTypeName=number

metric m:othersva p:float l:"Other svcs ALA-MLS" t:dataTypeName=number

metric m:othersvb p:float l:"Other svcs professional" t:dataTypeName=number

metric m:othersvc p:float l:"Other svcs other" t:dataTypeName=number

metric m:othersvd p:float l:"Other svcs TOTAL" t:dataTypeName=number

metric m:totstafa p:float l:"Total staff ALA-MLS" t:dataTypeName=number

metric m:totstafb p:float l:"Total staff professional" t:dataTypeName=number

metric m:totstafc p:float l:"Total staff other" t:dataTypeName=number

metric m:totstafd p:float l:"Total staff TOTAL" t:dataTypeName=number

metric m:lstasea p:float l:"Admin of LSTA grants ALA-MLS" t:dataTypeName=number

metric m:lstaseb p:float l:"Admin of LSTA grants professional" t:dataTypeName=number

metric m:lstasec p:float l:"Admin of LSTA grants other" t:dataTypeName=number

metric m:lstased p:float l:"Admin of LSTA grants TOTAL" t:dataTypeName=number

metric m:staidsea p:float l:"Admin of state aid ALA-MLS" t:dataTypeName=number

metric m:staidseb p:float l:"Admin of state aid professional" t:dataTypeName=number

metric m:staidsec p:float l:"Admin of state aid other" t:dataTypeName=number

metric m:staidsed p:float l:"Admin of state aid TOTAL" t:dataTypeName=number

metric m:aendsea p:float l:"Automation/electronic dev ALA-MLS" t:dataTypeName=number

metric m:aendseb p:float l:"Automation/electronic dev professional" t:dataTypeName=number

metric m:aendsec p:float l:"Automation/electronic dev other" t:dataTypeName=number

metric m:aendsed p:float l:"Automation/electronic dev TOTAL" t:dataTypeName=number

metric m:bphsea p:float l:"Blind/phys hand svcs ALA-MLS" t:dataTypeName=number

metric m:bphseb p:float l:"Blind/phys hand svcs professional" t:dataTypeName=number

metric m:bphsec p:float l:"Blind/phys hand svcs other" t:dataTypeName=number

metric m:bphsed p:float l:"Blind/phys hand svcs TOTAL" t:dataTypeName=number

metric m:cyasea p:float l:"Childr/YA svcs ALA-MLS" t:dataTypeName=number

metric m:cyaseb p:float l:"Childr/YA svcs professional" t:dataTypeName=number

metric m:cyasec p:float l:"Childr/YA svcs other" t:dataTypeName=number

metric m:cyased p:float l:"Childr/YA svcs TOTAL" t:dataTypeName=number

metric m:ilssea p:float l:"Inst libr svcs ALA-MLS" t:dataTypeName=number

metric m:ilsseb p:float l:"Inst libr svcs professional" t:dataTypeName=number

metric m:ilssec p:float l:"Inst libr svcs other" t:dataTypeName=number

metric m:ilssed p:float l:"Inst libr svcs TOTAL" t:dataTypeName=number

metric m:lbstasea p:float l:"Libr statistics ALA-MLS" t:dataTypeName=number

metric m:lbstaseb p:float l:"Libr statistics professional" t:dataTypeName=number

metric m:lbstasec p:float l:"Libr statistics other" t:dataTypeName=number

metric m:lbstased p:float l:"Libr statistics TOTAL" t:dataTypeName=number

metric m:litprsea p:float l:"Literacy support ALA-MLS" t:dataTypeName=number

metric m:litprseb p:float l:"Literacy support professional" t:dataTypeName=number

metric m:litprsec p:float l:"Literacy support other" t:dataTypeName=number

metric m:litprsed p:float l:"Literacy support TOTAL" t:dataTypeName=number

metric m:markcoma p:float l:"Mktg/communications ALA-MLS" t:dataTypeName=number

metric m:markcomb p:float l:"Mktg/communications professional" t:dataTypeName=number

metric m:markcomc p:float l:"Mktg/communications other" t:dataTypeName=number

metric m:markcomd p:float l:"Mktg/communications TOTAL" t:dataTypeName=number

metric m:swdblica p:integer l:"DB licensing exp federal" t:dataTypeName=number

metric m:swdblicb p:integer l:"DB licensing exp state" t:dataTypeName=number

metric m:swdblicc p:integer l:"DB licensing exp other" t:dataTypeName=number

metric m:swdblicd p:integer l:"DB licensing exp TOTAL" t:dataTypeName=number

metric m:pubterms p:float l:"Public terminals" t:dataTypeName=number

metric m:readsch p:double l:"Grants to assist/sch readiness" t:dataTypeName=money

metric m:adfamlit p:double l:"Grants to assist/adult & fam literacy" t:dataTypeName=money

metric m:popu_st p:float l:Population t:dataTypeName=number

entity e:xa7b-pyuw l:"State Libraries Survey, FY 2000, Part 1: Operations & Workforce" t:attribution=IMLS t:url=https://data.imls.gov/api/views/xa7b-pyuw

property e:xa7b-pyuw t:meta.view v:id=xa7b-pyuw v:category="State Library Administrative Agencies Survey" v:attributionLink=https://www.imls.gov/research-evaluation/data-collection/state-library-administrative-agency-survey v:averageRating=0 v:name="State Libraries Survey, FY 2000, Part 1: Operations & Workforce" v:attribution=IMLS

property e:xa7b-pyuw t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:xa7b-pyuw t:meta.view.owner v:id=xhhh-dddv v:screenName="Jason Enos" v:displayName="Jason Enos"

property e:xa7b-pyuw t:meta.view.tableauthor v:id=xhhh-dddv v:screenName="Jason Enos" v:roleName=administrator v:displayName="Jason Enos"

property e:xa7b-pyuw t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| stlaname                                           | physaddr                                      | physcity    | phys_st | physzip | physzip4 | mailaddr                      | mailcity    | mail_st | mailzip | mailzip4 | webaddr                               | branch | indagy | appbygov | appbyoth | largerag | othagsp | starchiv | stlegref | sthstmus | strecmng | othallop | othallsp        | stlacont | stlahost | stdeplib | fddeplib | regional | selectiv | elecplan | elecoper | elecbibl | electext | nettrstf | nettrcus | netsub | netequip | netmount | netgoph | ficsp | ficspsp    | inrefreq | accoldb | pubswdbl | acswdbl | schswdbl | spcswdbl | lcswdbl | othswdbl | remoteac | acccdrom | accoclc | acctlnet | accwbcat | acczgway | accoth | othaccsp                              | erateapp | iacoop | lpartnr | pub_fips | fystart   | fyend     | tothrswk | mon2fri | sat2sun | mainout | otherout | bkmobile | totalout | bphouta | bphoutb | bphoutc | bphoutd | corouta | coroutb | coroutc | coroutd | otstouta | otstoutb | otstoutc | otstoutd | gvemouta | gvemoutb | gvemoutc | gvemoutd | gpouta | gpoutb | gpoutc | gpoutd | bkservol  | audio    | video  | subscrip | govdoc    | gencol | circ    | provto  | recfrom | reftrans | libvists | events | atevents | grantmon | onsitmon | admserva | admservb | admservc | admservd | ldpuba | ldpubb | ldpubc | ldpubd | ldscha | ldschb | ldschc | ldschd | ldacada | ldacadb | ldacadc | ldacadd | ldspeca | ldspecb | ldspecc | ldspecd | ldothlba | ldothlbb | ldothlbc | ldothlbd | totallda | totalldb | totalldc | totalldd | lspubsva | lspubsvb | lspubsvc | lspubsvd | lstecsva | lstecsvb | lstecsvc | lstecsvd | lsothlsa | lsothlsb | lsothlsc | lsothlsd | totallsa | totallsb | totallsc | totallsd | othersva | othersvb | othersvc | othersvd | totstafa | totstafb | totstafc | totstafd | lstasea | lstaseb | lstasec | lstased | staidsea | staidseb | staidsec | staidsed | aendsea | aendseb | aendsec | aendsed | bphsea | bphseb | bphsec | bphsed | cyasea | cyaseb | cyasec | cyased | ilssea | ilsseb | ilssec | ilssed | lbstasea | lbstaseb | lbstasec | lbstased | litprsea | litprseb | litprsec | litprsed | markcoma | markcomb | markcomc | markcomd | swdblica | swdblicb | swdblicc | swdblicd | pubterms | readsch  | adfamlit  | popu_st    | 
| ================================================== | ============================================= | =========== | ======= | ======= | ======== | ============================= | =========== | ======= | ======= | ======== | ===================================== | ====== | ====== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======== | ======== | =============== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======== | ======== | ======= | ===== | ========== | ======== | ======= | ======== | ======= | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ====== | ===================================== | ======== | ====== | ======= | ======== | ========= | ========= | ======== | ======= | ======= | ======= | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ========= | ======== | ====== | ======== | ========= | ====== | ======= | ======= | ======= | ======== | ======== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ========= | ========== | 
| DIVISION OF LIBRARIES, ARCHIVES & MUSEUMS          | 333 WILLOUGHBY AVENUE                         | JUNEAU      | AK      | 99811   | 571      | P.O. BOX 110571               | JUNEAU      | AK      | 99811   | 571      | WWW.STATE.AK.US/LAM/LIBRARY.HTML      | E      |        |          |          | E        |         | Y        | N        | Y        | Y        | N        |                 | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T3    |            | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | Y       | Y        | Y        | N        | Y      | STATEWIDE ONLINE PERIODICALS DATABASE | N        | N      | N       | 2        | 930787200 | 962323200 | 40.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 107455.0  | 119.0    | 585.0  | 1696.0   | 89000.0   | Y      | 3430.0  | 1769.0  | 1771.0  | 12208.0  | 71446.0  | 33.0   | 730.0    | 143.0    | 16.0     | 2.0      | 0.0      | 4.0      | 6.0      | 1.0    | 0.0    | 0.5    | 1.5    | 1.0    | 0.0    | 0.5    | 1.5    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 0.0      | 0.0      | 3.0      | 5.0      | 0.0      | 1.0      | 6.0      | 5.0      | 0.0      | 6.0      | 11.0     | 2.0      | 0.0      | 3.0      | 5.0      | 3.0      | 0.0      | 3.0      | 6.0      | 10.0     | 0.0      | 12.0     | 22.0     | 0.0      | 1.0      | 2.0      | 3.0      | 17.0     | 1.0      | 19.0     | 37.0     | 0.4     | 0.0     | 0.0     | 0.4     | 0.5      | 0.0      | 0.0      | 0.5      | 2.0     | 1.0     | 2.0     | 5.0     | 0.1    | 0.0    | 2.0    | 2.1    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.5      | 0.0      | 0.0      | 0.5      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0        | 0        | 0        | 0        | 5.0      | 0.0      | 0.0       | 622000.0   | 
| ALABAMA PUBLIC LIBRARY SERVICE                     | 6030 MONTICELLO DRIVE                         | MONTGOMERY  | AL      | 36117   | 1        | 6030 MONTICELLO DRIVE         | MONTGOMERY  | AL      | 36130   | 1        | WWW.APLS.STATE.AL.US                  | E      | B      | X        |          |          |         | N        | N        | N        | N        | N        |                 | N        | N        | N        | Y        | N        | Y        | Y        | N        | Y        | N        | Y        | Y        | Y      | N        | Y        | Y       | T1    |            | Y        | Y       | N        | N       | N        | N        | N       | N        | N        | Y        | Y       | Y        | Y        | Y        | N      |                                       | N        | N      | N       | 1        | 938736000 | 970272000 | 45.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 177758.0  | 274767.0 | 4471.0 | 1261.0   | 2803.0    | Y      | 5195.0  | 13049.0 | 309.0   | 12682.0  | 9082.0   | 145.0  | 2216.0   | 197.0    | 6.0      | 1.0      | 2.0      | 10.5     | 13.5     | 7.0    | 0.0    | 1.0    | 8.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 7.0      | 0.0      | 1.0      | 8.0      | 9.0      | 0.0      | 12.0     | 21.0     | 1.0      | 0.0      | 3.0      | 4.0      | 0.0      | 0.0      | 0.0      | 0.0      | 10.0     | 0.0      | 15.0     | 25.0     | 3.0      | 0.0      | 7.75     | 10.75    | 21.0     | 2.0      | 34.25    | 57.25    | 2.0     | 1.0     | 2.0     | 5.0     | 2.0      | 1.0      | 1.0      | 4.0      | 0.0     | 0.0     | 3.5     | 3.5     | 3.0    | 0.0    | 6.0    | 9.0    | 1.0    | 0.0    | 0.0    | 1.0    | 0.0    | 0.0    | 0.0    | 0.0    | 2.0      | 0.0      | 0.0      | 2.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0        | 0        | 0        | 0        | 4.0      | 0.0      | 0.0       | 4351999.0  | 
| ARKANSAS STATE LIBRARY                             | ONE CAPITOL MALL, FIFTH FLOOR                 | LITTLE ROCK | AR      | 72201   | 1085     | ONE CAPITOL MALL, FIFTH FLOOR | LITTLE ROCK | AR      | 72201   | 1085     | WWW.ASL.LIB.AR.US                     | E      |        |          |          | E        |         | N        | N        | N        | N        | N        |                 | N        | Y        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | OTH   | OC3-65MB/S | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | N        | Y       | Y        | Y        | Y        | N      |                                       | N        | N      | N       | 5        | 930787200 | 962323200 | 45.0     | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 99972.0   | 620.0    | 662.0  | 1500.0   | 1583451.0 | Y      | 11286.0 | 12874.0 | 396.0   | 3575.0   | 9851.0   | 20.0   | 825.0    | 15.0     | 25.0     | 2.0      | 2.0      | 6.0      | 10.0     | 4.0    | 0.0    | 2.0    | 6.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 0.0      | 2.0      | 6.0      | 5.0      | 1.0      | 12.0     | 18.0     | 7.0      | 0.0      | 10.0     | 17.0     | 0.0      | 0.0      | 0.0      | 0.0      | 12.0     | 1.0      | 22.0     | 35.0     | 2.0      | 2.0      | 1.0      | 5.0      | 20.0     | 5.0      | 31.0     | 56.0     | 1.0     | 0.5     | 0.0     | 1.5     | 0.0      | 0.5      | 0.0      | 0.5      | 2.0     | 1.0     | 0.0     | 3.0     | 2.0    | 1.0    | 6.0    | 9.0    | 0.5    | 0.0    | 0.0    | 0.5    | 0.5    | 0.0    | 0.0    | 0.5    | 0.5      | 0.0      | 0.0      | 0.5      | 0.5      | 0.0      | 0.0      | 0.5      | 0.0      | 1.0      | 0.0      | 1.0      | 707482   | 0        | 0        | 707482   | 4.0      | 0.0      | 0.0       | 2538303.0  | 
| ARIZONA STATE LIBRARY, ARCHIVES AND PUBLIC RECORDS | 1700 WEST WASHINGTON - SUITE 200              | PHOENIX     | AZ      | 85007   | 2896     | 1100 WEST WASHINGTON STREET   | PHOENIX     | AZ      | 85007   | 2935     | WWW.LIB.AZ.US                         | L      |        |          |          |          |         | Y        | Y        | Y        | Y        | N        |                 | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T1    |            | Y        | Y       | Y        | Y       | N        | Y        | Y       | Y        | Y        | N        | Y       | Y        | Y        | Y        | N      |                                       | Y        | Y      | Y       | 4        | 930787200 | 962323200 | 135.0    | 0.0     | 0.0     | 4.0     | 0.0      | 0.0      | 4.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 4.0      | 0.0      | 0.0      | 4.0      | 1.0    | 0.0    | 0.0    | 1.0    | 460659.0  | 15526.0  | 457.0  | 721.0    | 499888.0  | Y      | 669.0   | 1381.0  | 968.0   | 29358.0  | 43166.0  | 193.0  | 5576.0   | 128.0    | 41.0     | 3.0      | 3.0      | 8.0      | 14.0     | 4.0    | 1.0    | 4.0    | 9.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 1.0      | 4.0      | 9.0      | 21.0     | 5.0      | 9.0      | 35.0     | 9.0      | 2.0      | 12.0     | 23.0     | 0.0      | 2.0      | 5.0      | 7.0      | 30.0     | 9.0      | 26.0     | 65.0     | 0.0      | 16.0     | 36.0     | 52.0     | 37.0     | 29.0     | 74.0     | 140.0    | 0.4     | 0.0     | 0.35    | 0.75    | 0.26     | 0.0      | 0.25     | 0.51     | 1.11    | 2.0     | 3.05    | 6.16    | 10.0   | 4.0    | 12.0   | 26.0   | 0.52   | 0.0    | 0.25   | 0.77   | 0.0    | 0.0    | 0.0    | 0.0    | 0.27     | 0.0      | 0.25     | 0.52     | 0.08     | 0.0      | 0.0      | 0.08     | 0.18     | 0.0      | 0.0      | 0.18     | 100000   | 0        | 0        | 100000   | 22.0     | 83541.0  | 155100.0  | 4678500.0  | 
| CALIFORNIA STATE LIBRARY                           | 914 CAPITOL MALL                              | SACRAMENTO  | CA      | 95814   | 4802     | P.O. BOX 942837               | SACRAMENTO  | CA      | 94237   | 1        | WWW.LIBRARY.CA.GOV                    | E      | G      |          |          |          |         | N        | Y        | N        | N        | N        |                 | Y        | Y        | Y        | Y        | Y        | N        | Y        | N        | Y        | N        | Y        | Y        | Y      | Y        | Y        | Y       | T1    |            | Y        | Y       | Y        | N       | N        | N        | N       | Y        | Y        | N        | Y       | Y        | Y        | Y        | N      |                                       | Y        | Y      | Y       | 6        | 930787200 | 962323200 | 115.0    | 0.0     | 7.0     | 1.0     | 2.0      | 0.0      | 3.0      | 1.0     | 0.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 2.0      | 0.0      | 3.0      | 1.0    | 1.0    | 0.0    | 2.0    | 768808.0  | 564.0    | 437.0  | 9641.0   | 4225679.0 | Y      | 35413.0 | 16440.0 | 503.0   | 88488.0  | 103565.0 | 116.0  | 3355.0   | 450.0    | 245.0    | 2.0      | 16.0     | 16.0     | 34.0     | 8.3    | 6.0    | 9.65   | 23.95  | 1.5    | 0.15   | 1.3    | 2.95   | 1.8     | 0.15    | 1.3     | 3.25    | 1.4     | 0.15    | 1.3     | 2.85    | 1.0      | 2.0      | 0.0      | 3.0      | 14.0     | 8.45     | 13.55    | 36.0     | 26.2     | 2.0      | 36.85    | 65.05    | 11.8     | 1.0      | 28.65    | 41.45    | 4.0      | 4.0      | 9.0      | 17.0     | 42.0     | 7.0      | 74.5     | 123.5    | 14.5     | 36.0     | 11.0     | 61.5     | 72.5     | 67.45    | 115.05   | 255.0    | 2.0     | 0.0     | 0.5     | 2.5     | 1.0      | 0.0      | 3.0      | 4.0      | 3.0     | 5.0     | 1.0     | 9.0     | 4.0    | 0.0    | 22.0   | 26.0   | 1.0    | 0.0    | 0.0    | 1.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.5      | 0.0      | 1.0      | 1.5      | 0.0      | 2.0      | 0.5      | 2.5      | 1.0      | 0.0      | 0.0      | 1.0      | 0        | 357771   | 0        | 357771   | 4.0      | 0.0      | 5823394.0 | 33773000.0 | 
| COLORADO STATE LIBRARY                             | 201 EAST COLFAX AVENUE, #309                  | DENVER      | CO      | 80203   | 1704     | 201 EAST COLFAX               | DENVER      | CO      | 80203   | 1704     | WWW.CDE.STATE.CO.US/LIBRARY_INDEX.HTM | E      |        |          |          | E        |         | N        | N        | N        | N        | N        |                 | Y        | Y        | Y        | N        | N        | N        | Y        | Y        | N        | N        | Y        | N        | N      | N        | Y        | Y       | T1    |            | Y        | Y       | N        | N       | N        | N        | N       | N        | N        | N        | N       | Y        | N        | Y        | N      |                                       | Y        | N      | N       | 8        | 930787200 | 962323200 | 45.0     | 0.0     | 0.0     | 0.0     | 2.0      | 0.0      | 2.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 1.0      | 0.0    | 1.0    | 0.0    | 1.0    | 17187.0   | 27.0     | 112.0  | 7521.0   | 325.0     | N      | 2067.0  | 403.0   | 0.0     | 1510.0   | 703.0    | 13.0   | 492.0    | 45.0     | 7.0      | 2.0      | 1.75     | 3.0      | 6.75     | 0.5    | 0.0    | 0.0    | 0.5    | 1.0    | 0.0    | 0.0    | 1.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 2.75     | 2.3      | 1.0      | 6.05     | 4.25     | 2.3      | 1.0      | 7.55     | 5.5      | 1.0      | 2.0      | 8.5      | 1.0      | 0.0      | 1.5      | 2.5      | 0.5      | 1.0      | 8.0      | 9.5      | 7.0      | 2.0      | 11.5     | 20.5     | 0.0      | 2.5      | 1.0      | 3.5      | 13.25    | 8.55     | 16.5     | 38.3     | 0.0     | 1.0     | 0.0     | 1.0     | 0.1      | 0.0      | 0.1      | 0.2      | 1.0     | 1.0     | 1.0     | 3.0     | 2.0    | 1.0    | 8.5    | 11.5   | 1.0    | 0.0    | 0.3    | 1.3    | 4.5    | 1.0    | 0.5    | 6.0    | 1.75     | 0.0      | 0.75     | 2.5      | 0.3      | 0.0      | 0.0      | 0.3      | 0.0      | 1.0      | 0.0      | 1.0      | 0        | 0        | 0        | 0        | 2.0      | 37430.0  | 63355.0   | 4154269.0  | 
| CONNECTICUT STATE LIBRARY                          | 231 CAPITOL AVENUE                            | HARTFORD    | CT      | 6106    | 1537     | 231 CAPITOL AVENUE            | HARTFORD    | CT      | 6106    | 1537     | WWW.CSLIB.ORG                         | E      |        |          |          | E        |         | Y        | N        | Y        | Y        | Y        | ARTS COMMISSION | N        | N        | Y        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T1    |            | Y        | Y       | Y        | Y       | Y        | N        | N       | N        | Y        | N        | N       | N        | Y        | N        | Y      | DIRECT T1 LINE TO DATABASE VENDOR     | Y        | N      | N       | 9        | 930787200 | 962323200 | 40.0     | 0.0     | 0.0     | 1.0     | 3.0      | 0.0      | 4.0      | 0.0     | 1.0     | 0.0     | 1.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 2.0    | 0.0    | 3.0    | 1045448.0 | 200.0    | 20.0   | 10060.0  | 1693160.0 | N      | 1829.0  | 862.0   | 200.0   | 77611.0  | 107193.0 | 50.0   | 600.0    | 98.0     | 15.0     | 3.0      | 5.0      | 5.0      | 13.0     | 7.0    | 0.0    | 7.0    | 14.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 3.0      | 0.0      | 1.0      | 4.0      | 10.0     | 0.0      | 8.0      | 18.0     | 21.0     | 0.0      | 19.0     | 40.0     | 5.0      | 5.0      | 4.0      | 14.0     | 2.0      | 0.0      | 2.0      | 4.0      | 28.0     | 5.0      | 25.0     | 58.0     | 3.0      | 15.0     | 21.0     | 39.0     | 44.0     | 25.0     | 59.0     | 128.0    | 1.0     | 1.0     | 0.0     | 2.0     | 1.0      | 1.0      | 0.0      | 2.0      | 3.0     | 0.0     | 1.0     | 4.0     | 2.0    | 0.0    | 9.0    | 11.0   | 2.0    | 0.0    | 0.0    | 2.0    | 0.0    | 0.0    | 0.0    | 0.0    | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 141000   | 0        | 0        | 141000   | 25.0     | 27168.0  | 52738.0   | 3282031.0  | 
| DISTRICT OF COLUMBIA PUBLIC LIBRARY                | 901 G STREET, N.W.                            | WASHINGTON  | DC      | 20001   | 4599     | 901 G STREET, N.W.            | WASHINGTON  | DC      | 20001   | 4599     | WWW.DCLIBRARY.ORG                     | E      | B      | X        |          |          |         | N        | N        | N        | N        | N        |                 | N        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | N        | N        | N      | Y        | Y        | Y       | T1    |            | N        | N       | N        | N       | N        | N        | N       | N        | N        | N        | Y       | N        | N        | N        | N      |                                       | Y        | N      | N       | 11       | 938736000 | 970272000 | 0.0      | 0.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0       | 0.0      | 0.0    | 0.0      | 0.0       | N      | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 56.0   | 906.0    | 0.0      | 0.0      | 1.0      | 0.0      | 0.0      | 1.0      | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 3.0      | 3.0      | 2.0      | 8.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 0.0      | 3.0      | 3.0      | 2.0      | 8.0      | 0.0      | 0.0      | 0.0      | 0.0      | 4.0      | 3.0      | 2.0      | 9.0      | 0.5     | 0.0     | 0.0     | 0.5     | 0.0      | 0.0      | 0.0      | 0.0      | 0.25    | 0.0     | 0.0     | 0.25    | 0.25   | 1.0    | 0.0    | 1.25   | 0.25   | 0.0    | 0.0    | 0.25   | 0.25   | 0.0    | 0.0    | 0.25   | 0.25     | 0.0      | 0.0      | 0.25     | 0.25     | 1.0      | 0.0      | 1.25     | 0.1      | 0.1      | 0.0      | 0.2      | 0        | 0        | 0        | 0        | 0.0      | 0.0      | 0.0       | 519000.0   | 
| DELAWARE DIVISION OF LIBRARIES                     | 43 SOUTH DUPONT HIGHWAY                       | DOVER       | DE      | 19901   | 7430     | 43 SOUTH DUPONT HIGHWAY       | DOVER       | DE      | 19901   | 7430     | WWW.LIB.DE.US                         | E      |        |          |          | S        |         | N        | N        | N        | N        | N        |                 | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T1    |            | N        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | Y        | Y        | Y       | Y        | N        | N        | Y      | WEB PAGE ACCESS                       | Y        | N      | N       | 10       | 930787200 | 962323200 | 47.0     | 4.0     | 0.0     | 1.0     | 0.0      | 0.0      | 1.0      | 1.0     | 0.0     | 0.0     | 1.0     | 1.0     | 0.0     | 0.0     | 1.0     | 1.0      | 0.0      | 0.0      | 1.0      | 1.0      | 0.0      | 0.0      | 1.0      | 1.0    | 0.0    | 0.0    | 1.0    | 1062.0    | 0.0      | 0.0    | 54.0     | 38958.0   | N      | 2142.0  | 0.0     | 50.0    | 1000.0   | 22000.0  | 18.0   | 212.0    | 38.0     | 50.0     | 2.0      | 1.0      | 1.0      | 4.0      | 2.0    | 0.5    | 0.0    | 2.5    | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 4.0      | 1.0      | 0.0      | 5.0      | 6.0      | 1.5      | 0.0      | 7.5      | 1.0      | 1.0      | 1.0      | 3.0      | 1.0      | 2.0      | 0.0      | 3.0      | 0.0      | 0.5      | 4.0      | 4.5      | 2.0      | 3.5      | 5.0      | 10.5     | 0.0      | 0.0      | 0.0      | 0.0      | 10.0     | 6.0      | 6.0      | 22.0     | 0.5     | 0.34    | 0.0     | 0.84    | 0.35     | 0.33     | 0.0      | 0.68     | 2.3     | 2.0     | 0.0     | 4.3     | 1.0    | 1.0    | 2.0    | 4.0    | 0.1    | 0.5    | 0.0    | 0.6    | 0.0    | 0.0    | 0.0    | 0.0    | 0.5      | 0.53     | 0.2      | 1.23     | 0.2      | 0.0      | 0.0      | 0.2      | 0.5      | 0.5      | 0.0      | 1.0      | 0        | 187498   | 0        | 187498   | 4.0      | 0.0      | 0.0       | 753538.0   | 
| STATE LIBRARY OF FLORIDA                           | R.A. GRAY BUILDING, 500 SOUTH BRONOUGH STREET | TALLAHASSEE | FL      | 32399   | 250      | 500 SOUTH BRONOUGH STREET     | TALLAHASSEE | FL      | 32399   | 250      | DLIS.DOS.STATE.FL.US                  | E      |        |          |          | S        |         | Y        | N        | N        | Y        | N        |                 | N        | N        | Y        | Y        | N        | Y        | Y        | N        | Y        | Y        | Y        | Y        | Y      | Y        | Y        | Y       | T1    |            | Y        | Y       | Y        | Y       | Y        | Y        | Y       | Y        | N        | N        | Y       | N        | N        | N        | N      |                                       | Y        | N      | N       | 12       | 930787200 | 962323200 | 146.0    | 3.0     | 6.0     | 1.0     | 2.0      | 0.0      | 3.0      | 1.0     | 2.0     | 0.0     | 3.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0      | 0.0      | 0.0      | 0.0      | 1.0      | 2.0      | 0.0      | 3.0      | 1.0    | 2.0    | 0.0    | 3.0    | 327284.0  | 454.0    | 8979.0 | 1404.0   | 347928.0  | Y      | 26183.0 | 19045.0 | 5794.0  | 43998.0  | 34324.0  | 59.0   | 2662.0   | 260.0    | 260.0    | 2.0      | 2.0      | 8.0      | 12.0     | 9.0    | 0.0    | 3.0    | 12.0   | 0.0    | 0.0    | 0.0    | 0.0    | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 0.0     | 4.0      | 0.0      | 3.0      | 7.0      | 13.0     | 0.0      | 6.0      | 19.0     | 10.0     | 1.0      | 11.0     | 22.0     | 5.5      | 0.0      | 5.0      | 10.5     | 2.0      | 1.0      | 3.0      | 6.0      | 17.5     | 2.0      | 19.0     | 38.5     | 0.0      | 20.5     | 30.0     | 50.5     | 32.5     | 24.5     | 63.0     | 120.0    | 2.0     | 0.0     | 1.85    | 3.85    | 0.85     | 0.0      | 0.65     | 1.5      | 1.85    | 1.5     | 2.0     | 5.35    | 0.1    | 0.0    | 0.0    | 0.1    | 0.75   | 0.0    | 0.25   | 1.0    | 0.0    | 0.0    | 0.0    | 0.0    | 0.5      | 0.0      | 0.5      | 1.0      | 0.2      | 0.0      | 0.1      | 0.3      | 0.0      | 1.0      | 0.0      | 1.0      | 193317   | 0        | 0        | 193317   | 28.0     | 294929.0 | 1128040.0 | 15322040.0 | 
```