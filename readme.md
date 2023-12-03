Larus Sensor Box
===

<table style="width:80%">
  <tr>
    <th style="width:50%">Firstname</th>
    <th style="width:20%">Lastname</th>
    <th style="width:10%">Age</th>
  </tr>
  <tr>
    <td>Jill</td>
    <td>Smith</td>
    <td>50</td>
  </tr>
  <tr>
    <td>Eve</td>
    <td>Jackson</td>
    <td>94</td>
  </tr>
</table>


|Name|Value
|---|---
|name|larus_sensor_box
|object_id|1
|comment|Definition of CAN bus datagrams of the Larus Sensor Box

**Datapoints**

---
**0x10 roll_nick:** roll-angle, nick-angle (front-right-down system)

|datapoint|              type|           unit 
|---|---|---
|roll_angle|f32|radian_angle
|nick_angle|f32|radian_angle


---
**0x11 heading:** heading, magnetic declination

|datapoint|type|unit 
|---|---|---
|heading|f32|radian_angle
|magnetic_declination|f32|radian_angle


---
**0x12 airspeed:** TAS true airspeed, IAS indicated airspeed

|datapoint|type|unit 
|---|---|---
|tas|f32|meter_per_second
|ias|f32|meter_per_second


