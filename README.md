# API Demo App for Harvard HCS Bootcamp

A simple banking dashboard showing a user's accounts and transfers.  It also allows users to create new transfers.  This app demonstrates basic usage of APIs in a Python Flask application.  Makes use of the Nessie API for all data.  

For step-by-step implementation instructions, see the [Wiki](https://github.com/nessieisreal/api-demo-starter/wiki).

## Requirements  

* Python 3.6
* Pip for the appropriate version of Python (https://pip.pypa.io/en/stable/installing/)

## Installation

1. Clone the project.

	```
	git clone https://github.com/nessieisreal/api-demo-starter.git
	```  
2. create file  config.py in main directory 

3. Open the file (config.py) and add your Nessie API key as a variable.
	
	```
	API_KEY = "my_api_key"
	```  

	Retrieve your API key by creating an account at http://api.reimaginebanking.com.

4. Install required packages.
	
	```
	pip install -r requirements.txt
	```  
	
If you run into errors with this command, try upgrading Pip.  

* Mac  
    ```
    pip install -U pip
    ```  
* Windows  
    ```
    python -m pip install -U pip
    ```  
Also, using `sudo` in front of these commands may solve some issues. 

## Running the Application

Navigate to the root of the project and run:

```
python run.py
```  
	
Navigate to **localhost:5000** to view the dashboard.

![Starter App](/app/img/starter.jpg)  
  

Once completed, the application should look like this:

![Finished Home Screen](/app/img/home-screen.jpg)

![Finished Transfer List](/app/img/transfer-list.jpg)
