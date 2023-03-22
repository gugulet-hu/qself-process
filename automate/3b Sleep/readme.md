# Sleep flow

An [Automate](https://llamalab.com/automate/) flow to track sleep patterns and phases. The flow tracks:

* Sleep Start
* Sleep End
* Location
* Temperature
* Humidity
* Ambient Light
* Sleep Duration
* Awake Time
* Light Sleep Time
* Deep Sleep Time
* REM Sleep Time

## Components

The flow currently has a fibre to intialise the flow, a fibre to track sleep, and a sub-flow to track sleep phases.

The flow uses [AutoWear](https://play.google.com/store/apps/details?id=com.joaomgcd.autowear&gl=US) to fetch information from a WearOS device.