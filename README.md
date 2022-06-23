﻿# Group Expense Tracker

## Getting Started with the project

 1. **Install Libraries** -The first step after cloning the repository is installing the libraries from requirements.txt `pip install -r requirements.txt`

2. **Run the project**- To start the server run the command `python app.py` in the command line.

## How to

 1. **Create a Group-** <br>
 Link-http://127.0.0.1:5000/groups/<u>\<int:groupId></u> <br>
 JSON Structure

     {
    "name": "",
    "members": []
    }

 
 2. **View a Group/ Groups** <br>
 View all Groups- http://127.0.0.1:5000/groups <br>
 View a single Group- http://127.0.0.1:5000/groups/<u>\<int:groupId></u>
 
 3. **Add/Update an expense** <br>
 Add Link-http://127.0.0.1:5000/addexpense/<u>\<int:groupId></u> <br>
 Update Link -  http://127.0.0.1:5000/updateexpense/<u>\<int:groupId>/\<string:ExpenseName></u> <br>
JSON Structure <br>

     {
	    "name": "",
	    "value": ,
	    "paid_by": {},
	    "paid_for": {}
    }

 4. **Delete an Expense** <br>
Link- http://127.0.0.1:5000/deleteexpense/<u>\<int:groupId>/\<string:ExpenseName></u>

5. **View Balance** <br>
Link-http://127.0.0.1:5000/balance/<u>\<int:groupId></u>
 

 





