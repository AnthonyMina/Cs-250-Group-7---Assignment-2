# Cs-250-Group-7---Assignment-2
System Description:

The Mountain Lion Detection System uses noise detection sensors throughout the San Diego County Parks and Recreation Department placed within a 5 square miles area. The device detects various animal noises and sends alert messages to the control computer located in the park ranger station. Alert messages contain the strength of the noise, the type of animal detected and location to within 3 miles. The alert message triggers an alarm that will sound in the park ranger station until a park ranger responds to the alert and the alarm will not sound again until another, separate noise is detected in another location. Rangers will be able to classify an alert as definite, suspected, or false, indicating the probability that a real mountain lion was detected. The control computer will save all mountain lion alerts received within 30 days and a summary of alert messages for data older than 30 days but received within the year. Rangers will be able to request reports showing all mountain lion detections by date detected and classification or by specific location of sensor; geographical report showing detection on a map of the park and 2 miles outside of the park; classification report by ranger.


Software Architecture Overview:


The System has Three pages and a database. The Alarm Detection page collects information from the Sensors if an Animal/Mountain Lion is detected. Information such as the sensor's location(that detected the animal and the strength of the noise detected. The Alarm Detection class also keeps track of the date and time the animal was detected and the name of the Ranger responsible for the area of the sensor. All this information then gets sent as a report to the Control Page. The operator of the Control page can disable the alarm, send the data to the Database and look up previous reports from the report's page. The database retrieves and saves the reports for documentation and future reference. The Get Reports page is where all the reports would be stored and archived to help predict and manage future incidents.

Development Plan and Timeline:

Tasks are partitioned by major components.

Anthony Mina-
Halah Salman-
Kaitlyn Nguyen- responsible for the report component
Remy Huynh-

Commit's For Credit:
1. Anthony Mina
2. Kaitlyn Nguyen
3. Halah Salman

