# [RFID Blocking System]

## Overview
The RFID Blocking System is designed to identify and restrict unauthorized scanning of RFID tags in credit and debit cards, passports, and other sensitive documents. This project simulates the process of detecting and blocking unauthorized RFID scans to prevent potential data theft through contactless payments.

## Features:
1. Simulates the scanning of RFID tags.
2. Identifies authorized and unauthorized RFID tags.
3. Logs unauthorized RFID scans.
4. Notifies the user of unauthorized RFID scans.


## How It Works:
The system uses a simulated list of authorized RFID tags and scans randomly selected RFID tags from a pre-defined list. If an unauthorized RFID tag is scanned, the system logs the scan and notifies the user.

## Usage:
- Clone the repository.
- Run the RFID.py script.

## Example:
To run the RFID Blocking System simulation:
> python RFID.py


## Code Explanation:
### Dependencies:
- time: Used to add a delay between scans.
- random: Used to randomly select RFID tags for scanning.
- logging: Used to log unauthorized RFID scans.

### Functions:
- scan_rfid(): Simulates scanning an RFID tag by randomly selecting a tag from a list of simulated tags.
- is_authorized(tag): Checks if the scanned tag is in the list of authorized tags.
- log_unauthorized_scan(tag): Logs the unauthorized scan using the logging module.
- notify_user(tag): Notifies the user of the unauthorized scan (simulated with a print statement).
- rfid_blocking_system(num_scans): Runs the RFID blocking system simulation for a specified number of scans.


## Main Execution:
The script runs the RFID blocking system simulation with a default of 5 scans. This can be adjusted as needed.

## Customization:
- Modify the authorized_tags list to add or remove authorized RFID tags.
- Adjust the simulated_tags list in the scan_rfid function to simulate different scenarios.
- Change the number of scans by modifying the num_scans parameter in the rfid_blocking_system function call.

## Logging:
Unauthorized scans are logged in a file named rfid_log.txt.

## Dharmaveer Bhaskar:

