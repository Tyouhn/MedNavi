# Find Your Doctor

A medical application that helps diagnose people and find nearby doctors.


## Features
- Medical advice
  	- Using modern AI technology the program can generate
  	  a medically accurate list of possible diseases and
  	  advice on who to visit for a proper diagnosis.
- User security
	- Users may ask whatever medical questions they want and
	  not worry about other users viewing as it is password-protected.
 - Local map
   	- From the application, users can access Google Maps to
   	  find a doctor in their area.
- Save searches
  	- Store previous responses in a database, users can retrieve them with
  	  the drop-down list.

## Setup

- To get started prepare your ChatGpt API key, JxBrowser license key, 
Google Maps API key, and import LoginTable.sql to your database.

- Then open with notepad or text editor: 
	- ChatGPTAPI.java <br>
	        Add your ChatGPT Key on line 22 after "String apikey = " 
	- GoogleMapAPI.java <br>
	        Add your JxBrowser license key on line 38 after ".licenseKey"
   	- GoogleMap.html <br>
  	        Replace "YOUR_API_KEY" with your Google Map API key on lines 27 and 147

- Run InfoUI.java

## Requirements

- Java 8 or higher
- Google Maps API Key
- ChatGPT API Key
- JxBrowser License Key
- Database
  	- MySql Workbench and Community Server <br>
	                  Or
	- Xampp



