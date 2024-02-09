## Dataset Information

### Raw Data Properties

Sample motor data is collected using SpectraQuest Machinery Fault Simulator that has general setup view: 

<p align="center">
    <img src="docs/SampleMotorDataLimerick_generalSetup.png" width="200">
</p>

Faults tested include a variety of mechanical faults as follows:

<span style="font-size:0.8em;">

- Very Light Imbalance
- Light Imbalance
- Heavy Imbalance
- Very Heavy Imbalance
- Bent Shaft
- Misaligned Shaft (Angular)
- Light Inner Race Fault
- Heavy Inner Race Fault
- Light Outer Race Fault
- Heavy Outer Race Fault
- Light Ball Bearing Fault
- Heavy Ball Bearing Fault

</span>

For the imbalance faults, varying loads are placed in the setup, sample can be seen as follows:
<p align="center">
    <img src="docs/SampleMotorDataLimerick_sampleImbalance.png" width="200">

</p>

For the other fault types, details can be seen from the below Figure:
<p align="center">
    <img src="docs/SampleMotorDataLimerick_otherFaults.png" width="400">

</p>


Each fault was tested at 600, 1200, 1800, 2400 & 3000 RPM and tested both with and without an additional 11lb load on the shaft. ADXL356 sensor data is used for vibration raw data.

For ADXL356 sensor, the sampling frequency was **20kHz** and data csv files recorded for **2 sec** in X, Y and Z direction.

Data files are saved in.csv format with the following naming convention:

<p align="center">
    <img src="docs/SampleMotorDataLimerick_fileNamingConvention.png" width="500">
</p>