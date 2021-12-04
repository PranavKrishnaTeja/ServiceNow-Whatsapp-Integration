# ServiceNow-Whatsapp-Integration
# This Step by Step Process is just an Overview.

Step-1 Create a Twilio Account

Step-2 Configure Whatsapp Sandbox and Copy the Curl code for Account SID and Auth Token along with the Connection URL

Step-3 Create a new application through Studio

Step-4 Add a basic Auth credentials to the application and the username will be Account SID and Password would be Auth token(Caution: in case your auth token is shown as redacted just log out of twilio console and log back in and under project details you would get the auth token)

Step –5 Create a new credential and aliases and under connections related list create a new https connection and paste your api link in the connection url link page

Step-6 Go to Flow designer and Create new Action and under inputs define from and to also make them mandatory and the field type should be as phone number not String also define a new input as BODY of field type string.

Step-7 Create a new script to remove the special characters

Step-8 Create a Rest Script and under response tab select POST and after selecting POST under response tab define inputs and later define outputs in the both remove special characters and Rest script

Step-9 Create a custom script to handle errors

Step-10 Create outputs and test the action

Step-11 after creating the action go to create new flow and define trigger conditions and under configuration tab enable show draft application spokes.

Step-12 Now select your own created application scope and select its action and give required inputs.

For More Information Visit https://bit.ly/3EoizpK
