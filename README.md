Codecademy Medical Insurance Project: Python Syntax.

This project analyses a medical insurance data using basic Python syntax.

Data is stored in CSV format. Each column is extracted to lists and numbers stored as strings are converted to numeric datatypes to assist data analysis.

A patient ID list is added to the data. The number / id is used to make sure each variable stays together as functions are carried out, and also serves as a means of returning a specific profile.

An interactive form is built with tkinter for user to input their details and generate a medical insurance quote (although this data is not yet collected / stored).

The _PatientData_ class analyses the data in each column.  There is a method to convert each list to a dictionary datatype with the patient ID as the key, and the patient profile as the value.  

The _Patient_ class allows us to simulate a new patient profile. We can generate a new ID and calculate the cost of their insurance policy.

Several functions are provided to read a CSV file, and to write and append to a CSV datastore.
