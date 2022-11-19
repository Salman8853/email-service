# email-service
Email client Rest API --- send email via Go Lang
Email client Rest API

Tech Stack: GoLang, MongoDB

Create an REST endpoint which will take the following inputs 

emailTo array[]
emailCC array[]
emailBCC array[]
subject text
emailBody text

API will get these parameters 

emailTo, subject and emailBody would be required, validation would apply.
This will send email to the provided to emails. Also store the complete email history into database.
