# Tools flow

An [Automate](https://llamalab.com/automate/) flow containing tools to manipulate JSON files, and backup and initialise flows.

## Components

The flow currently has the following fibres:

* A fibre to intialise other flows.
* A fibre to self-initialise using the first fibre.
* A fibre to add missing sessions to a primary JSON file.
* A fibre to add a summary to sessions.
* A fibre to create period summaries.
