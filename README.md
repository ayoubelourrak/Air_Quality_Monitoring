# Air_Quality_Monitoring
## TP1 - Air Quality Monitoring (airborne particulate matter)

The goal of this project is to analyze data provided by a set of air quality sensors. The sensors present in the dataset are located in Portugal. Each sensor provides two values: measuring particles less than 10 µm (P1) in μg/m³.

The sensor data, covers the month of March 2022, and is streamed of Kafka.

Each data sample has the following schema:

timestamp | sensor_id | sensor_type | location | latitude | longitude | P1
----------|-------------|----------|----------|-----------|-----------|----
timestamp | string  | string | string | float | float|  float

## Questions

For each sensor, separately:

1. Compute the cummulative average for P1, updated on a hourly basis.

2. Compute the minumum, average and maximum of P1 (particles smaller than 10 µm) values, for the last two hours, updated every 10 minutes.

3. Compute the (signed) deviation of P1 between the cummulative average and
the two hour average (obtained in the previous step), updated hourly.

## Each File solve the respective question
