# MedNavi

Our medical application is a comprehensive platform designed to provide symptom diagnosis for patients, recommend the type of doctor, and empower students with general medical knowledge.

## Features
![Welcome](https://github.com/Tyouhn/WHE-Health/assets/30061954/7f611215-e5e9-44ca-b54d-eaae45fec8c5)

https://github.com/Tyouhn/MedNavi/assets/30061954/b550c1ba-c77d-432f-8bdd-e3acd2bc24a6
- Medical advice
  	- Using modern AI technology the program can generate <br>
  	  a medically accurate list of possible diseases and <br>
  	  advice on who to visit for a proper diagnosis.
- Medical Term 
- User security
	- Users may ask whatever medical questions they want and <br>
	  not worry about other users viewing as it is password-protected.
- Save searches
  	- Store previous responses in a database, users can retrieve <br>
  	  them with the drop-down list.
![Search](https://github.com/Tyouhn/WHE-Health/assets/30061954/29d60963-3156-4965-8c81-3cbc915e4dcd)
![History](https://github.com/Tyouhn/WHE-Health/assets/30061954/8070c62c-6257-4009-a028-6a55a25be200)
- Local map
   	- From the application, users can access Google Maps to <br>
   	  find a doctor in their area.
![GoogleMap](https://github.com/Tyouhn/WHE-Health/assets/30061954/62afec2e-9a94-4511-b73e-ae0337413b69)

## Setup

- To get started prepare your ChatGpt API key, JxBrowser license key, <br>
Google Maps API key, and import LoginTable.sql to your database. Also, <br>
ensure to incorporate all the libraries located within the Java Lib <br>
folder into your Java project path.

- Then open with notepad or text editor:
  	- MySQLConnector.java
		Substitute all instances of "url", "user," and "pass" with your specific <br>
		local database server information at lines 12, 13  and 14. <br>
   		
	- ChatGPTAPI.java <br>
	        Add your ChatGPT key on line 18 after "String apikey = " <br>
	- GoogleMapAPI.java <br>
	        Add your JxBrowser license key on line 39 after ".licenseKey"
   	- GoogleMap.html <br>
  	        Replace "YOUR_API_KEY" with your Google Map API key on lines 27 and 146
	- ZipCodeConverter.java <br>
   		Add your Google Map key on line 14 after "String apikey = "
- Run Portal.java

## Requirements

- Java 8 or higher
- Google Maps API Key
- ChatGPT API Key
- JxBrowser License Key
- Database
  	- MySql Workbench and Community Server <br>
	                  Or
	- Xampp



