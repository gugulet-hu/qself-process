# Exercise flow

An [Automate](https://llamalab.com/automate/) flow to keep track of exercise and workout details. The metrics tracked per repetition by the flow are:

* Date
* Time
* Location
* Heart Rate
* Temperature
* Humidity
* Exercise
* Exercise Type
* Body Group
* Equipment Used
* Reps
* Time (s) or Quantity (kg)
* Rest
* Speed or Work Done

## Components

The flow currently has three fibres: one for intialising the flow, one for managing a workout session, and another for counting daily steps.

The flow uses [AutoWear](https://play.google.com/store/apps/details?id=com.joaomgcd.autowear&gl=US) to fetch information from a WearOS device.