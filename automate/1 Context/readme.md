# Context flow

An [Automate](https://llamalab.com/automate/) flow to control other flows and run them depending on time or location context. This is an ever-running flow to keep resource use down.

## Components

The flow currently has a fibre to initialise the flow, a fibre to run beginning-of-day flows, to run end-of-day flows, to start the sleep flow, and to check heart rate and step count throughout the day.