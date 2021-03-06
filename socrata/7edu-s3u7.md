# Beach Weather Stations - Automated Sensors - 2016 - Humidity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://data.cityofchicago.org/Parks-Recreation/Beach-Weather-Stations-Automated-Sensors-2016-Humi/7edu-s3u7/about) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/7edu-s3u7) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/7edu-s3u7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/7edu-s3u7/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 7edu-s3u7 |
| Name | Beach Weather Stations - Automated Sensors - 2016 - Humidity |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | beaches, parks, chicago park district, open spaces, parks & recreation, recreation, water |
| Created | 2016-06-07T16:41:13Z |
| Publication Date | 2015-06-01T22:22:24Z |

## Description

The Chicago Park District maintains weather sensors at beaches along Chicago's Lake Michigan lakefront. These sensors generally capture the indicated measurements hourly while the sensors are in operation during the summer.  During other seasons and at some other times, information from the sensors may not be available.  See https://data.cityofchicago.org/id/qmqz-2xku for a dataset with similar measurements on the lake water, itself.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type     | Render Type   |
| ======== | ============== | =========================== | =========================== | ============= | ============= |
| Yes      | series tag     | station_name                | Station Name                | text          | text          |
| Yes      | time           | measurement_timestamp       | Measurement Timestamp       | calendar_date | calendar_date |
| Yes      | numeric metric | air_temperature             | Air Temperature             | number        | number        |
| Yes      | numeric metric | wet_bulb_temperature        | Wet Bulb Temperature        | number        | number        |
| Yes      | numeric metric | humidity                    | Humidity                    | number        | number        |
| Yes      | numeric metric | rain_intensity              | Rain Intensity              | number        | number        |
| Yes      | numeric metric | interval_rain               | Interval Rain               | number        | number        |
| Yes      | numeric metric | total_rain                  | Total Rain                  | number        | number        |
| Yes      | series tag     | precipitation_type          | Precipitation Type          | text          | number        |
| Yes      | numeric metric | wind_direction              | Wind Direction              | number        | number        |
| Yes      | numeric metric | wind_speed                  | Wind Speed                  | number        | number        |
| Yes      | numeric metric | maximum_wind_speed          | Maximum Wind Speed          | number        | number        |
| Yes      | numeric metric | barometric_pressure         | Barometric Pressure         | number        | number        |
| Yes      | numeric metric | solar_radiation             | Solar Radiation             | number        | number        |
| Yes      | numeric metric | heading                     | Heading                     | number        | number        |
| Yes      | numeric metric | battery_life                | Battery Life                | number        | number        |
| No       |                | measurement_timestamp_label | Measurement Timestamp Label | text          | text          |
| No       |                | measurement_id              | Measurement ID              | text          | text          |
```

## Time Field

```ls
Value = measurement_timestamp
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = measurement_timestamp_label,measurement_id
```

## Data Commands

```ls
series e:7edu-s3u7 d:2016-01-01T00:00:00.000Z t:station_name="Foster Weather Station" m:air_temperature=-3.67 m:interval_rain=0 m:humidity=62 m:maximum_wind_speed=5 m:battery_life=15.2 m:wind_direction=197 m:barometric_pressure=1000 m:wind_speed=3.6 m:solar_radiation=0

series e:7edu-s3u7 d:2016-01-01T00:00:00.000Z t:station_name="Oak Street Weather Station" t:precipitation_type=0.0 m:heading=359 m:rain_intensity=0 m:interval_rain=0 m:wind_direction=260 m:barometric_pressure=1000.5 m:air_temperature=-2.3 m:humidity=67 m:maximum_wind_speed=7.6 m:battery_life=12.1 m:wind_speed=4 m:total_rain=6.3 m:solar_radiation=3 m:wet_bulb_temperature=-4

series e:7edu-s3u7 d:2016-01-01T00:00:00.000Z t:station_name="63rd Street Weather Station" t:precipitation_type=0.0 m:heading=353 m:rain_intensity=0 m:interval_rain=0 m:wind_direction=255 m:barometric_pressure=1000.5 m:air_temperature=-2.8 m:humidity=69 m:maximum_wind_speed=6.4 m:battery_life=11.9 m:wind_speed=3.8 m:total_rain=6.7 m:solar_radiation=5 m:wet_bulb_temperature=-4.4
```

## Meta Commands

```ls
metric m:air_temperature p:float l:"Air Temperature" d:"Air Temperature in Celsius degrees." t:dataTypeName=number

metric m:wet_bulb_temperature p:float l:"Wet Bulb Temperature" d:"Wet bulb temperature in Celsius degrees." t:dataTypeName=number

metric m:humidity p:float l:Humidity d:"Percent relative humidity." t:dataTypeName=number

metric m:rain_intensity p:float l:"Rain Intensity" d:"Rain intensity in mm per hour." t:dataTypeName=number

metric m:interval_rain p:float l:"Interval Rain" d:"Rain since the last hourly measurement, in mm." t:dataTypeName=number

metric m:total_rain p:float l:"Total Rain" d:"Total rain since midnight in mm." t:dataTypeName=number

metric m:wind_direction p:float l:"Wind Direction" d:"Wind direction in degrees." t:dataTypeName=number

metric m:wind_speed p:float l:"Wind Speed" d:"Wind speed in meters per second." t:dataTypeName=number

metric m:maximum_wind_speed p:float l:"Maximum Wind Speed" d:"Maximum wind speed since midnight in meters per second." t:dataTypeName=number

metric m:barometric_pressure p:float l:"Barometric Pressure" d:"Barometric pressure in hPa." t:dataTypeName=number

metric m:solar_radiation p:float l:"Solar Radiation" d:"Solar radiation in watts per square meter." t:dataTypeName=number

metric m:heading p:float l:Heading d:"The current heading of the wind-measurement unit. The ideal value to get the most accurate measurements is true north (0 degrees) and the unit is manually adjusted, as necessary, to keep it close to this heading" t:dataTypeName=number

metric m:battery_life p:float l:"Battery Life" d:"Battery voltage, an indicator of remaining battery life used by the Chicago Park District to know when batteries should be replaced." t:dataTypeName=number

entity e:7edu-s3u7 l:"Beach Weather Stations - Automated Sensors - 2016 - Humidity" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/7edu-s3u7

property e:7edu-s3u7 t:meta.view d:2017-09-25T07:23:27.732Z v:averageRating=0 v:name="Beach Weather Stations - Automated Sensors - 2016 - Humidity" v:attribution="Chicago Park District" v:attributionLink=http://www.chicagoparkdistrict.com v:id=7edu-s3u7 v:category="Parks & Recreation"

property e:7edu-s3u7 t:meta.view.owner d:2017-09-25T07:23:27.732Z v:displayName="Jonathan Levy" v:lastNotificationSeenAt=1505253103 v:id=vewm-vupz v:screenName="Jonathan Levy"

property e:7edu-s3u7 t:meta.view.tableauthor d:2017-09-25T07:23:27.732Z v:displayName="Jonathan Levy" v:lastNotificationSeenAt=1505253103 v:roleName=administrator v:id=vewm-vupz v:screenName="Jonathan Levy"
```

## Top Records

```ls
| station_name                | measurement_timestamp | air_temperature | wet_bulb_temperature | humidity | rain_intensity | interval_rain | total_rain | precipitation_type | wind_direction | wind_speed | maximum_wind_speed | barometric_pressure | solar_radiation | heading | battery_life | measurement_timestamp_label | measurement_id                       | 
| =========================== | ===================== | =============== | ==================== | ======== | ============== | ============= | ========== | ================== | ============== | ========== | ================== | =================== | =============== | ======= | ============ | =========================== | ==================================== | 
| Foster Weather Station      | 2016-01-01T00:00:00   | -3.67           |                      | 62.0     |                | 0.0           |            |                    | 197.0          | 3.6        | 5.0                | 1000.0              | 0.0             |         | 15.2         | 01/01/2016 12:00 AM         | FosterWeatherStation201601012400     | 
| Oak Street Weather Station  | 2016-01-01T00:00:00   | -2.3            | -4.0                 | 67.0     | 0.0            | 0.0           | 6.3        | 0.0                | 260.0          | 4.0        | 7.6                | 1000.5              | 3.0             | 359.0   | 12.1         | 01/01/2016 12:00 AM         | OakStreetWeatherStation201601012400  | 
| 63rd Street Weather Station | 2016-01-01T00:00:00   | -2.8            | -4.4                 | 69.0     | 0.0            | 0.0           | 6.7        | 0.0                | 255.0          | 3.8        | 6.4                | 1000.5              | 5.0             | 353.0   | 11.9         | 01/01/2016 12:00 AM         | 63rdStreetWeatherStation201601012400 | 
| Foster Weather Station      | 2016-01-01T01:00:00   | -4.56           |                      | 63.0     |                | 0.0           |            |                    | 290.0          | 5.9        | 6.6                | 999.3               | 0.0             |         | 14.8         | 01/01/2016 1:00 AM          | FosterWeatherStation201601010100     | 
| Oak Street Weather Station  | 2016-01-01T01:00:00   | -3.2            | -4.8                 | 67.0     | 0.0            | 0.0           | 6.3        | 0.0                | 286.0          | 1.5        | 5.6                | 1000.0              | 4.0             | 359.0   | 12.0         | 01/01/2016 1:00 AM          | OakStreetWeatherStation201601010100  | 
| 63rd Street Weather Station | 2016-01-01T01:00:00   | -3.4            | -4.8                 | 72.0     | 0.0            | 0.0           | 6.7        | 0.0                | 273.0          | 6.4        | 9.4                | 999.9               | 5.0             | 353.0   | 11.9         | 01/01/2016 1:00 AM          | 63rdStreetWeatherStation201601010100 | 
| Foster Weather Station      | 2016-01-01T02:00:00   | -5.5            |                      | 60.0     |                | 0.0           |            |                    | 247.0          | 2.5        | 3.1                | 999.0               | 0.0             |         | 15.2         | 01/01/2016 2:00 AM          | FosterWeatherStation201601010200     | 
| Oak Street Weather Station  | 2016-01-01T02:00:00   | -4.0            | -5.7                 | 64.0     | 0.0            | 0.0           | 6.3        | 0.0                | 288.0          | 1.6        | 3.4                | 1000.0              | 4.0             | 359.0   | 12.1         | 01/01/2016 2:00 AM          | OakStreetWeatherStation201601010200  | 
| 63rd Street Weather Station | 2016-01-01T02:00:00   | -4.2            | -5.5                 | 71.0     | 0.0            | 0.0           | 6.7        | 0.0                | 261.0          | 6.2        | 9.8                | 999.6               | 5.0             | 354.0   | 11.9         | 01/01/2016 2:00 AM          | 63rdStreetWeatherStation201601010200 | 
| Foster Weather Station      | 2016-01-01T03:00:00   | -6.28           |                      | 64.0     |                | 0.0           |            |                    | 271.0          | 3.8        | 4.5                | 999.0               | 0.0             |         | 14.8         | 01/01/2016 3:00 AM          | FosterWeatherStation201601010300     | 
```