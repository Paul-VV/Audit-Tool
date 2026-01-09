# Audit-Tool
An e-cornell certificate final python project containing a program that helps audit datasets which may include JSON and CSV files. This project is a multi-file application under the folder Auditor which is required to be initially executed for this python application. My goal for this project was to take on the role of an insurance auditor, designing a program that helps automate auditing a year of fictional records from a flight school, inspecting weather conditions, record keeping conditions, timezone conditions, determining pilots, and indicating violations in these records. The app also includes CSV and JSON content reading functions. This project showcases all of the functions I designed, which displays my understanding of scripting in python and does not include all scripts/datasets needed to operate this tool, since I didn't design them. 

All specifications/pseudocode are outlined by e-cornell

This tool involves one main folder and four files:

Folder = 

1. Auditor

Files = 

1. app.py = This is the main module that makes validations on the flight school records and the function execute(args) provides the output of violations if the app is not executed

2. pilots.py = A module that ascertains pilot certification, a helper function for get_minimums that helps determine what values are advantagous, and the function get_minimums which returns the most advantagous values for CEILING, VISIBILITY, WIND, CROSSWIND which for WIND/CROSSWIND, a higher value is better, and for CEILING/VISIBILITY, lower values are best

3. utils.py = This module determines the time of day, provides a copy of a table with the included id, and functions that help read content from JSON and CSV files

4. violations.py = Module helps validate whether a flight lesson is violating the insurance regulations by checking for bad visibility, bad wind speed, bad cloud ceiling measurements, bad takeoff reports which get listed as a string in get_weather_violation to determine the type of violation, and list_weather_violations identifies which lists from all flights violate weather minimums from get_weather_violation


Copyright Statement:
I don't have a preference to what licensing this project gets, however, if you'd like to contribute or have any questions you can reach out to me at **skinnerwelms@gmail.com**
