# NWU Tech Trends Telemetry Portal - Automation Bot

## Project Description

This project automates the process of User Acceptance Testing (UAT) for the NWU Tech Trends Telemetry Portal. The automation bot, developed using UiPath, interacts with the web application to input test data, submit new records, and verify that they have been successfully created. This automation saves time by eliminating the need for manual testing, allowing stakeholders to focus on higher-level tasks while ensuring that the system meets the required functionality.

## How to Use the Automation Bot

### Prerequisites

To use the automation bot, you need the following:

1. **UiPath Studio**: Install [UiPath Studio](https://www.uipath.com/start-trial) on your computer to develop and run the automation.
2. **UiPath Orchestrator**: Ensure your UiPath project is published to the Orchestrator for scheduling and managing automation tasks.
3. **Access to the Telemetry Portal**: The automation interacts with the NWU Tech Trends Telemetry Portal available at [Telemetry Portal](https://nwutechtrendstelemetryportal.azurewebsites.net).
4. **Test Data**: Prepare an Excel file with test data that includes the input fields and the expected output for each record.

### Steps to Run the Bot

1. **Launch UiPath Studio**: Open the project named `NWU Tech Trends Telemetry Portal - User Acceptance Testing`.
2. **Load Test Data**: The bot reads the input data from an Excel file and loads it into a data table.
3. **Automate Data Input**: The bot navigates to the telemetry portal, inputs the test data into the appropriate fields, and submits the form.
4. **Verify Records**: The bot then navigates to the records page and verifies if the records were created successfully.
5. **Update Test Results**: After each test, the Excel file is updated to indicate whether the record passed or failed the test.


