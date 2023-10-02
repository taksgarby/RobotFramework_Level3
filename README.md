```diff
# RPA Certification Level 3

The main goals is to learn:

- To automate a process where target systems don't have a GUI
- To use the producer - consumer pattern
- To split the robot code into multipble logical pieces for easier maintainance
- To refactor the robot code constantly to keep it tidy and easy to maintain
- Extract, Transform, Load business data
- To validate data and handle exceptions using work items
- To communitate with HTTP API and handle the responses
- To manage work data in Control Room

Learning highlights:

<b>+ 1. Using WORK ITEMS</b>

A work item contains a payload of JSON-based data and optionally attached files.
There are 2 approach with work items:<br/>
(1) - default & more powerful - each step of the process creates output items, with the option of creating multiple items at once.<br/>
(2) one work item for each process run is passed between steps and optionally modified at each stage. <br/>

- By default, the RPA.Robocorp.WorkItems library uses Control Room to store the work items and pass them between steps.<br/>

<b>+ 2. Producer - Consumer model </b>

The producer robot<br/>

- downloads the raw traffic data.
- transforms the raw data into a business data format.
- saves the business data as work items that can be consumed later.

The consumer robot<br/>

- loops all the work items one by one.
- validates teh data.
- posts the data to the sales system API.
- handles successful responses.
- handles application exceptioins.
- handles business exceptions.

I have completed the exam and obtained Level III Automation Developer certificate.
```
