
# Sensor Data Analysis

## Overview
This dataset contains sensor readings from various sensors installed on a machine. The data is collected at one-minute intervals and includes the status of the machine (NORMAL, BROKEN, RECOVERING). The purpose of this dataset is to perform anomaly detection and monitor the machine's health.


## Data Structure

### Files
sensor_data.csv: The main data file containing sensor readings and machine status.

### Data Columns Explanation
The dataset consists of the following columns:

1. **timestamp**: The date and time when the data was recorded.
2. **sensor_00 to sensor_54**: Sensor readings from various sensors installed on the machine.
3. **machine_status**: The status of the machine, which can be one of the following:
4. **NORMAL**: The machine is operating normally.
5. **BROKEN**: The machine has encountered a problem and is not operating correctly.
6. **RECOVERING** : The machine is in the process of recovering from a problem (merged with BROKEN for analysis).

## Example Data

```csv
,timestamp,sensor_00,sensor_01,sensor_02,sensor_03,sensor_04,sensor_05,sensor_06,sensor_07,sensor_08,sensor_09,sensor_10,sensor_11,sensor_12,sensor_13,sensor_14,sensor_15,sensor_16,sensor_17,sensor_18,sensor_19,sensor_20,sensor_21,sensor_22,sensor_23,sensor_24,sensor_25,sensor_26,sensor_27,sensor_28,sensor_29,sensor_30,sensor_31,sensor_32,sensor_33,sensor_34,sensor_35,sensor_36,sensor_37,sensor_38,sensor_39,sensor_40,sensor_41,sensor_42,sensor_43,sensor_44,sensor_45,sensor_46,sensor_47,sensor_48,sensor_49,sensor_50,sensor_51,machine_status
0,2018-04-01 00:00:00,2.465394,47.092009999999995,53.2118,46.310759999999995,634.375,76.45975,13.41146,16.13136,15.567129999999999,15.053529999999999,37.2274,47.52422,31.11716,1.6813529999999999,419.5747,,461.8781,466.3284,2.565284,665.3993,398.9862,880.0001,498.8926,975.9409,627.674,741.7151,848.0708,429.0377,785.1935,684.9443,594.4445,682.8125,680.4416,433.7037,171.9375,341.9039,195.0655,90.32386,40.36458,31.51042,70.57291,30.98958,31.770832061767603,41.92708,39.6412,65.68287,50.92593,38.19444,157.9861,67.70834,243.0556,201.3889,NORMAL
1,2018-04-01 00:01:00,2.465394,47.092009999999995,53.2118,46.310759999999995,634.375,76.45975,13.41146,16.13136,15.567129999999999,15.053529999999999,37.2274,47.52422,31.11716,1.6813529999999999,419.5747,,461.8781,466.3284,2.565284,665.3993,398.9862,880.0001,498.8926,975.9409,627.674,741.7151,848.0708,429.0377,785.1935,684.9443,594.4445,682.8125,680.4416,433.7037,171.9375,341.9039,195.0655,90.32386,40.36458,31.51042,70.57291,30.98958,31.770832061767603,41.92708,39.6412,65.68287,50.92593,38.19444,157.9861,67.70834,243.0556,201.3889,NORMAL
```

## Usage

This dataset is useful for performing anomaly detection and monitoring the health of a machine using sensor data. By merging the BROKEN and RECOVERING statuses and focusing on key sensors, we can gain insights into the machine's condition and identify potential issues.

## License
Unknown  [csv](https://www.kaggle.com/datasets/nphantawee/pump-sensor-data/data)
