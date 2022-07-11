# OEE Simulated Dataset


## Data Set Information
Simulated dataset for OEE calculation. The CSV file contains the status of the process line (normal, idle, planned_stop, or fault), and also the number of good and bad units produced. The status is saved when it is changed. Units produced are saved when the status changes from 'normal' to any other possible status. Data were simulated over a period of one month.

## Attribute Information
Measurement - status, bad_count, or good_count.
Value - the value of the measurement.
Timestamp - timestamp in format 2022-07-01 00:00:00.000000.
Line - line from where the measurement comes from (line_1 or line_2).
Time - the total time the process line spent in the current status or production of good and bad units.
