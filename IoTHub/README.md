![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/iothub.jpg "Header Image")
# Create IoTHub and Prepare IoTHub for End to End Solution

### IoTHub: Connect, monitor, and manage billions of IoT assets
- Establish bi-directional communication with billions of IoT devices
- Authenticate per device for security-enhanced IoT solutions
- Register devices at scale with IoT Hub Device Provisioning Service
- Manage your IoT devices at scale with device management
- Extend the power of the cloud to your edge device


## Create Resource Group

####

#### Create a resource group collect and manage all your application resources for this lab

####

![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/01_Create_Resource_Group.png "Resource Group")

####

#### Click on Create button

####

![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/02_Create_Resource_Group_Create.png "Create Resource Group")

####

#### Select subscription and region

####

![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/03_Create_Resource_Group_Submit.png "Create Resource Group")



## Create IoThub

####

#### Your device will connect to this IoTHub and start sending data

####

![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/04_Create_IoTHub.png "Create IoThub")

####

#### Make sure you select the resource group you created in previous step

####

![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/05_Create_IoTHub_Submit_2.png "Create IoTHub")


## Connect Device and Send Data to IoThub

####

#### This Lab assumes you are using MXChip as the Device

####

![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/MxChip.jpg "MXChip")

####

### Prepare the MXChip by 
- updating firmware
- connecting to Wifi
- connecting to Azure to select a subscription and IoTHub
- uploading device code

####

[Prepare MXChip to Connect to IoTHub](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-arduino-iot-devkit-az3166-get-started)

####

### Once Device Connects to IoTHub, messages flow into IoThub

####

![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/06_IoTHub_DeviceCreated_Data_Flowing.png "Data Flow")


## Create Consumer Groups

#### In order to allow several consumer applications to read data from the IoT Hub independently at their own pace a Consumer Group must be configured for each one. 

![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/07_IotHub_Endpoints.png "Create Consumer Greoups")

####

#### Pick your IoTHub, go to Endpoint and Events

####

![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/08_Iothub_Events.png "Create Consumer Greoups")

####

#### Add a new consumer group and save

####

![Imported Script](https://github.com/rangv/AzureIoTLabs/blob/master/IoTHub/images/09_IoTHub_Consumer_Groups.png "Create Consumer Greoups")
