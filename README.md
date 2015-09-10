# SensorTag Azure
This project is designed to demonstrate how from a device via Microsoft Azure can display information in PowerBI. (This project got much inspiration from the following project [SensorTagToEventHub]( https://github.com/Azure/azure-stream-analytics/tree/master/Samples/SensorDataAnalytics/SensorTagToEventHub).)

## Overview
A *Universal Windows App* connects to the *SensorTag* with *Bluetooth*. This app reads the sensor each second and sends the data to *Azure EventHub*. An *Azure Stream Analytics* job analyse the data and send it to *PowerBI*.

## What you need
* Windows 10 computer
* TI SensorTag
* Windows Azure Account using Org Id (Power BI works with Org ID only. Org ID is your work or business email address e.g. xyz@mycompany.com. Personal emails like xyz@hotmail.com are not org ids. [You can learn more about org id here](https://www.arin.net/resources/request/org.html) )

## Getting started

### 1. Pair the TI SensorTag in the *Manage Bluetooth devices* settings

### 2. Download the source code or the compiled executable.

### 3. Create EventHub and Stream Analytics services in Azure
1\. Open [http://manage.windowsazure.com](http://manage.windowsazure.com)

2\. Navigate to the *Service Bus pane*.

![Service Bus](https://github.com/buzzfrog/SensorTag-Azure/blob/master/images/service-bus.png)

3\. Click on the plus sign to create a new *Service Bus Namespace*.

![New Service Bus Namespace](https://github.com/buzzfrog/SensorTag-Azure/blob/master/images/service-bus-create-namespace.png)

### 4. Create a PowerBI report


