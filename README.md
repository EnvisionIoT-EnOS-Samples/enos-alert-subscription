# enos-ecosystem-demo

## Introduction
This is a sample codes to demonstrate how to subscribe to an EnOS data subscription job. You need to use with enos-simple-device-mqtt sample codes.


## Techology stack
- Python
- EnOS Platform
- https://github.com/EnvisionIot/enos-subscription-service-sdk-python

## Prerequitsites

### Get the subscription url and port, save to .env file
Make sure you are using the model and measurement point created in enos-simple-device-mqtt.

Follow the instructions below to get the subscription url and port:
https://www.envisioniot.com/docs/enos/en/latest/getting_started_with_enos/planning.html?highlight=environment%20information#getting-environment-information

### Create a data subscription job, save the subscription id to .env file
Follow the instructions below to create a data subscription job:
https://www.envisioniot.com/docs/data-asset/en/latest/howto/obtain/managing_data_subscription.html

### Register an EnOS application, save app access key and secret to .env file
Follow the instructions below to register an EnOS application:
https://www.envisioniot.com/docs/app-development/en/latest/app_management/managing_apps.html#registering-an-application

### Run the init shell script to build the python dependencies
```bash
./init.sh
```

## How to run
To run the demo, run the following command in a new terminal.
```bash
python index.py
```