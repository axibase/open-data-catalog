# Building Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-violations-f0f5e) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/22u3-xenr) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/22u3-xenr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/22u3-xenr/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 22u3-xenr |
| Name | Building Violations |
| Attribution | City of Chicago |
| Category | Buildings |
| Tags | violations, inspections |
| Created | 2012-06-26T17:28:59Z |
| Publication Date | 2015-09-29T21:21:53Z |

## Description

Violations issued by the Department of Buildings from 2006 to the present.  Lenders and title companies, please note: These data are historical in nature and should not be relied upon for real estate transactions. For transactional purposes such as closings, please consult the title commitment for outstanding enforcement actions in the Circuit Court of Cook County or the Chicago Department of Administrative Hearings. Violations are always associated to an inspection and there can be multiple violation records to one inspection record. Related Applications: Building Data Warehouse http://www.cityofchicago.org/city/en/depts/bldgs/provdrs/inspect/svcs/building_violationsonline.html. The information presented on this website is informational only and does not necessarily reflect the current condition of the building or property. The dataset contains cases where a respondent has been found to be liable as well as cases where the respondent has been found to be not liable.

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | =========== | ============================ | ============================ | ============= | ============= |
| No       |             | id                           | ID                           | text          | text          |
| Yes      | time        | violation_last_modified_date | VIOLATION LAST MODIFIED DATE | calendar_date | calendar_date |
| No       |             | violation_date               | VIOLATION DATE               | calendar_date | calendar_date |
| Yes      | series tag  | violation_code               | VIOLATION CODE               | text          | text          |
| Yes      | series tag  | violation_status             | VIOLATION STATUS             | text          | text          |
| No       |             | violation_status_date        | VIOLATION STATUS DATE        | calendar_date | calendar_date |
| Yes      | series tag  | violation_description        | VIOLATION DESCRIPTION        | text          | text          |
| Yes      | series tag  | violation_location           | VIOLATION LOCATION           | text          | text          |
| Yes      | series tag  | violation_inspector_comments | VIOLATION INSPECTOR COMMENTS | text          | text          |
| Yes      | series tag  | violation_ordinance          | VIOLATION ORDINANCE          | text          | text          |
| Yes      | series tag  | inspector_id                 | INSPECTOR ID                 | text          | text          |
| Yes      | series tag  | inspection_number            | INSPECTION NUMBER            | text          | number        |
| Yes      | series tag  | inspection_status            | INSPECTION STATUS            | text          | text          |
| Yes      | series tag  | inspection_waived            | INSPECTION WAIVED            | text          | text          |
| Yes      | series tag  | inspection_category          | INSPECTION CATEGORY          | text          | text          |
| Yes      | series tag  | department_bureau            | DEPARTMENT BUREAU            | text          | text          |
| No       |             | address                      | ADDRESS                      | text          | text          |
| Yes      | series tag  | property_group               | PROPERTY GROUP               | text          | number        |
| Yes      | series tag  | ssa                          | SSA                          | text          | text          |
| No       |             | latitude                     | LATITUDE                     | number        | number        |
| No       |             | longitude                    | LONGITUDE                    | number        | number        |
```

## Time Field

```ls
Value = violation_last_modified_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,violation_date,violation_status_date,address,latitude,longitude
```

## Data Commands

```ls
series e:22u3-xenr d:2016-02-02T08:17:42.000Z t:violation_location="REWRITTEN ON 08/27/2014-INSPECTION #11320166-BL01041" t:violation_inspector_comments="REAR PORCH WARPED AND TWISTED BEAM 2ND FLR. 5448 LOOSE TREADS, 1ST TO 2ND FLR. REAR 415 LOOSE STRINGER 1ST TO 2ND FLR. ALSO SPLIT TREADS OBTAIN PERMIT AND PLANS." t:department_bureau=CONSERVATION t:violation_status=COMPLIED t:inspection_category=COMPLAINT t:inspection_waived=N t:inspector_id=BL00254 t:property_group=24447 t:violation_code=CN070024 t:violation_description="REPAIR PORCH SYSTEM" t:inspection_number=1950920 t:violation_ordinance="Failed to repair or replace defective or missing members of porch system.  (13-196-570, 13-196-641)" t:inspection_status=FAILED m:row_number.22u3-xenr=1

series e:22u3-xenr d:2016-02-02T08:12:02.000Z t:violation_location=1041 t:violation_inspector_comments="SOUTH ELEVATION-ABOVE ENTRANCE DOOR VERTICAL CRACKS IN STONE. VERTICAL CRACKS IN BRICKS WEST/SOUTH AT 3RD FL. NORTH ELEVATION- 3RD FL. BRICK MISSING, MORTAR MISSING." t:department_bureau=CONSERVATION t:violation_status=COMPLIED t:inspection_category=COMPLAINT t:inspection_waived=N t:inspector_id=BL00804 t:property_group=24447 t:violation_code=CN061014 t:violation_description="REPAIR EXTERIOR WALL" t:inspection_number=2280163 t:violation_ordinance="Failed to maintain the exterior walls of a building or structure free from holes, breaks, loose or rotting boards or timbers and any other conditions which might admit rain or dampness to the walls.  (13-196-530(b), 13-196-641)" t:inspection_status=FAILED m:row_number.22u3-xenr=2

series e:22u3-xenr d:2016-02-02T08:12:23.000Z t:violation_location=1041 t:violation_inspector_comments="SOUTH ELEVATION- 5450/AT ROOF STONE/BROKE/ MORTAR MISSING." t:department_bureau=CONSERVATION t:violation_status=COMPLIED t:inspection_category=COMPLAINT t:inspection_waived=N t:inspector_id=BL00804 t:property_group=24447 t:violation_code=CN065024 t:violation_description="MAINTAIN PROJECTIONS" t:inspection_number=2280163 t:violation_ordinance="Failed to maintain projection from wall of building in good repair and free from cracks and defects.  (13-196-530(e), 13-196-641)" t:inspection_status=FAILED m:row_number.22u3-xenr=3
```

## Meta Commands

```ls
metric m:row_number.22u3-xenr p:long l:"Row Number"

entity e:22u3-xenr l:"Building Violations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/22u3-xenr

property e:22u3-xenr t:meta.view d:2017-09-25T07:30:50.633Z v:averageRating=0 v:name="Building Violations" v:attribution="City of Chicago" v:attributionLink=http://www.cityofchicago.org v:id=22u3-xenr v:category=Buildings

property e:22u3-xenr t:meta.view.owner d:2017-09-25T07:30:50.633Z v:displayName=cocadmin v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:id=scy9-9wg4 v:screenName=cocadmin v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB

property e:22u3-xenr t:meta.view.tableauthor d:2017-09-25T07:30:50.633Z v:displayName=cocadmin v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:roleName=administrator v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:id=scy9-9wg4 v:screenName=cocadmin v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB
```

## Top Records

```ls
| id      | violation_last_modified_date | violation_date      | violation_code | violation_status | violation_status_date | violation_description      | violation_location                                   | violation_inspector_comments                                                                                                                                          | violation_ordinance                                                                                                                                                                                                                 | inspector_id | inspection_number | inspection_status | inspection_waived | inspection_category | department_bureau | address         | property_group | ssa | latitude     | longitude     | 
| ======= | ============================ | =================== | ============== | ================ | ===================== | ========================== | ==================================================== | ===================================================================================================================================================================== | =================================================================================================================================================================================================================================== | ============ | ================= | ================= | ================= | =================== | ================= | =============== | ============== | === | ============ | ============= | 
| 2128406 | 2016-02-02T08:17:42          | 2007-07-24T00:00:00 | CN070024       | COMPLIED         | 2016-02-01T00:00:00   | REPAIR PORCH SYSTEM        | REWRITTEN ON 08/27/2014-INSPECTION #11320166-BL01041 | REAR PORCH WARPED AND TWISTED BEAM 2ND FLR. 5448 LOOSE TREADS, 1ST TO 2ND FLR. REAR 415 LOOSE STRINGER 1ST TO 2ND FLR. ALSO SPLIT TREADS OBTAIN PERMIT AND PLANS.     | Failed to repair or replace defective or missing members of porch system. (13-196-570, 13-196-641)                                                                                                                                  | BL00254      | 1950920           | FAILED            | N                 | COMPLAINT           | CONSERVATION      | 415 S LOTUS AVE | 24447          |     | 41.874250343 | -87.761454612 | 
| 2513822 | 2016-02-02T08:12:02          | 2008-04-01T00:00:00 | CN061014       | COMPLIED         | 2016-02-01T00:00:00   | REPAIR EXTERIOR WALL       | 1041                                                 | SOUTH ELEVATION-ABOVE ENTRANCE DOOR VERTICAL CRACKS IN STONE. VERTICAL CRACKS IN BRICKS WEST/SOUTH AT 3RD FL. NORTH ELEVATION- 3RD FL. BRICK MISSING, MORTAR MISSING. | Failed to maintain the exterior walls of a building or structure free from holes, breaks, loose or rotting boards or timbers and any other conditions which might admit rain or dampness to the walls. (13-196-530(b), 13-196-641)  | BL00804      | 2280163           | FAILED            | N                 | COMPLAINT           | CONSERVATION      | 415 S LOTUS AVE | 24447          |     | 41.874250343 | -87.761454612 | 
| 2513836 | 2016-02-02T08:12:23          | 2008-04-01T00:00:00 | CN065024       | COMPLIED         | 2016-02-01T00:00:00   | MAINTAIN PROJECTIONS       | 1041                                                 | SOUTH ELEVATION- 5450/AT ROOF STONE/BROKE/ MORTAR MISSING.                                                                                                            | Failed to maintain projection from wall of building in good repair and free from cracks and defects. (13-196-530(e), 13-196-641)                                                                                                    | BL00804      | 2280163           | FAILED            | N                 | COMPLAINT           | CONSERVATION      | 415 S LOTUS AVE | 24447          |     | 41.874250343 | -87.761454612 | 
| 2513838 | 2016-02-02T08:12:40          | 2008-04-01T00:00:00 | CN063014       | COMPLIED         | 2016-02-01T00:00:00   | CHIMNEY                    | 1041                                                 | EAST ELEVATION- CHIMNEY MORTAR MISSING-ALL AROUND.                                                                                                                    | Failed to maintain chimney in safe and sound working condition. (13-196-590, 13-196-530(b) and (c), 13-196-641)                                                                                                                     | BL00804      | 2280163           | FAILED            | N                 | COMPLAINT           | CONSERVATION      | 415 S LOTUS AVE | 24447          |     | 41.874250343 | -87.761454612 | 
| 2513839 | 2016-02-02T08:12:57          | 2008-04-01T00:00:00 | CN063024       | COMPLIED         | 2016-02-01T00:00:00   | CHIMNEY CAPPING            | 1041                                                 | CHIMNEY CAP MISSING-USING COPING AS CAPPING/SOME OF THOSE ARE BROKE.                                                                                                  | Cap masonry chimney with non-combustible, water proof materials. (13-152-250 B, 13-152-240, 13-196-590)                                                                                                                             | BL00804      | 2280163           | FAILED            | N                 | COMPLAINT           | CONSERVATION      | 415 S LOTUS AVE | 24447          |     | 41.874250343 | -87.761454612 | 
| 2513842 | 2016-02-02T08:13:16          | 2008-04-01T00:00:00 | CN073024       | COMPLIED         | 2016-02-01T00:00:00   | REPAIR EXTERIOR DOOR FRAME | 1041                                                 | SOUTH ELEVATION- 5448 ENTRANCE DOOR FRAME ROTTED WOOD AT BOTTOM.                                                                                                      | Failed to maintain exterior door frames to exclude rain and wind from entering building and otherwise in sound condition and repair. (13-196-550, 13-196-550(f), 13-196-641)                                                        | BL00804      | 2280163           | FAILED            | N                 | COMPLAINT           | CONSERVATION      | 415 S LOTUS AVE | 24447          |     | 41.874250343 | -87.761454612 | 
| 2513843 | 2016-02-02T08:13:33          | 2008-04-01T00:00:00 | CN073014       | COMPLIED         | 2016-02-01T00:00:00   | REPAIR EXTERIOR DOOR       | 1041                                                 | 415-ENTRANCE DOOR-PANE BROKE.                                                                                                                                         | Failed to maintain exterior door in sound condition and repair. (13-196-550(d) and (e), 13-196-641)                                                                                                                                 | BL00804      | 2280163           | FAILED            | N                 | COMPLAINT           | CONSERVATION      | 415 S LOTUS AVE | 24447          |     | 41.874250343 | -87.761454612 | 
| 2513845 | 2016-02-02T08:13:53          | 2008-04-01T00:00:00 | CN061034       | COMPLIED         | 2016-02-01T00:00:00   | FLAKY INTERIOR PAINT       | 1041                                                 | ALL ELEVATIONS, ALL LEVELS FLAKING CHIPPED PAINT ON EXTERIOR WOOD SURFACES AND WINDOWS. SOUTH REAR PORCH AT TOP ROOF/GUTTERS.                                         | Failed to maintain all interior walls, ceilings and interior woodwork free of flaking, peeling, chipped or loose paint, plaster or structural material. (13-196-540(d), 13-196-641)                                                 | BL00804      | 2280163           | FAILED            | N                 | COMPLAINT           | CONSERVATION      | 415 S LOTUS AVE | 24447          |     | 41.874250343 | -87.761454612 | 
| 2513854 | 2016-02-02T08:14:24          | 2008-04-01T00:00:00 | CN104055       | COMPLIED         | 2016-02-01T00:00:00   | REPUTTY WINDOW PANES       | 1041                                                 | ALL ELEVATIONS, ALL LEVELS CHIPPED PUTTY.                                                                                                                             | Failed to retrim or reputty window panes. (13-196-550)                                                                                                                                                                              | BL00804      | 2280163           | FAILED            | N                 | COMPLAINT           | CONSERVATION      | 415 S LOTUS AVE | 24447          |     | 41.874250343 | -87.761454612 | 
| 2513885 | 2016-02-02T08:14:49          | 2008-04-01T00:00:00 | CN196029       | COMPLIED         | 2016-02-01T00:00:00   | POST OWNER/MANAGERS NAME/# | 1041                                                 | OWNER'S ID SIGN NOT POSTED.                                                                                                                                           | Post name, address, and telephone of owner, owner's agent for managing, controlling or collecting rents, and any other person managing or controlling building conspicuously where accessible or visible to public way. (13-12-030) | BL00804      | 2280163           | FAILED            | N                 | COMPLAINT           | CONSERVATION      | 415 S LOTUS AVE | 24447          |     | 41.874250343 | -87.761454612 | 
```