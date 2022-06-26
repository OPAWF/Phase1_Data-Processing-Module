# Phase1
Data Processing Module

Global ocean and weather data(sensor + satellite) are fetched archives available from
NASA’s official website.The daily spatial data is take from satellite sources ICODAS,GPCP
V2 on a global scale. The Feature values selected are Sea Surface Temperature(SST), Scalar
Wind, Sea Level Pressure(SLP), Humidity, and Precipitation.The input used is NetCDF data
Format. The major components are variables and dimensions. Variables can have multiple
dimensions. The metaphorical data are streamed until the required time span is reached. The
data is used to create the data frame

![fe](https://user-images.githubusercontent.com/62131312/175823674-c69fc0f9-a6e6-4cb8-8a57-58c2f4c20d3d.png)
