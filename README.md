# LAT_LONG_FROM_PLACE

This Python script allows you to find the latitude and longitude of a place name using the OpenStreetMap API. 
It takes input from an Excel file and outputs the latitude and longitude in a new Excel file.

Getting Started

Prerequisites
To run the script, you'll need to have Python 3.x installed on your machine. You'll also need to install the following packages:

pandas
requests
You can install these packages using pip:

Copy code
pip install pandas
pip install requests

Usage
To use the script, you'll need to provide an input Excel file containing a list of place names in a column called "Place".
you can also manually enter places.
The script will then use the OpenStreetMap API to find the latitude and longitude of each place, and output the results in a new
Excel file called "Place_LL.xlsx".

You can run the script using the following command:

Copy code
python lat_long_from_place.py Punjab.xlsx
Sample Input
The repository includes a sample Excel file called "Punjab.xlsx", which you can use to test the script.

Sample Output
After running the script with the "Punjab.xlsx" input file, you should see a new Excel file called "Place_LL.xlsx" in the same directory.
This file will contain three new columns called "Latitude","Longitude","District_Name" , which will contain the latitude and longitude values 
for each place in the input file.

Contributing
If you'd like to contribute to this project, please create a pull request with your changes.
We welcome any contributions that improve the script's functionality or usability.


Contact
If you have any questions or feedback, please feel free to reach out to us at pgill.singh07@gmail.com.
