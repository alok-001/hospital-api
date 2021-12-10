# hospital-api
API for Doctors of a Hospital which has been allocated by the govt. for testing, quarantine as well as well being of COVID-19 patients.

<h3>Setup the Project</h3>
<br>
Clone or Download the Repo.<br>
cd covid19-api goto the Repo using Terminal.<br>
Run mongod to start the MongoDB Database.<br>
Run npm start to ignite the project.<br>
Use<b> Postman<b> to test the api.<br>
<br>
<h3>Routes</h3>
<br>
Register a Doctor: [POST]: /api/v1/doctors/register<br>
Login for Doctor: [POST]: /api/v1/doctors/login<br>
Register a patient: [POST]: /api/v1/patients/register<br>
Create Patient report: [POST]: /api/v1/patients/:id/create_report<br>
Fetch All Reports of a Patient [GET]: /api/v1/patients/:id/all_reports<br>
Fetch All Reports Based on a Status: [GET]: /api/v1/reports/:status<br>
