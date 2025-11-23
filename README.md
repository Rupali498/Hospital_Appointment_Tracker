# Hospital_Appointment_Tracker
CLI for hospital scheduling. Features: Add, view, search, and cancel appointments.
<br>
A python based consol application for managing healthcare appointments efficiently.The systems uses in -memory storage with a list of dictionaries structure to handle appoinment data,providing full crud operations through an intuitive CLI interface
<br>

CORE ARCHITECTURE
<br>
1.data layer:  global appointments list storing dictionaries with patient,doctor,date,time and reason fields
<br>
Buisness Logic:Four main fuctions handling appointment creation,listing,filtering by date,and cancellation
<br>
Validation:Includes conflict detection preventing double-booking and input validation for user choices
<br>


FEATURES:
<br>
ADD appointment= Checks for doctors availability
<br>
VIEW appointment= display all entries or filter by specific date
<br>
CANCEL appointments=Remove by index with bounds checking and error handling
<br>
MENU system=Continous loop with five options and clean exit pathway
<br>


TECHNICAL SPECIFICATIONS:
<br>
1.Time Complexity=0(n) for conflict detection
<br>
2.Data persitence=Voltile storage-data lost on program
3.Input handling= basic validaton for integers and menu choices
<br>
4.Error Management=comprehensive error checking swith user friendly messages






