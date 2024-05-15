This is the inital version of the UiBank E2E demo.

TestCase is UiBank_E2E_CreateUser_Verify_Transactions_PL located in the main folder.

Flow consists of: 

1. Performing enviornment setup
2. Creation of user mailbox using Mailinator (temp inbox)
3. Creating user in UiBank via API
4. Log into UiBank Desktop application -> verify user created via API
4. Verify the new UiBank user email using the Mailinator (temp inbox)
5. Log on to UiBank Web
	5.1 Create a Checking account 
	5.2 Create a Savings account
	5.3 Transfer money between accounts
	5.4 Download transacation pdf
	5.5 Validate content of PDF

UiBank Resouces Here: https://uipath.atlassian.net/wiki/spaces/TS/pages/2030075971/UiBank

Key Requirements:

1. Need to have Acrobat Reader installed (either 32 bits or 64 bits)

2. Need to have copy of the UiBank Mainframe batch file in C:\UiBank\UiBank_Mainframe
	UiBank Resouces Here: https://uipath.atlassian.net/wiki/spaces/TS/pages/2030075971/UiBank