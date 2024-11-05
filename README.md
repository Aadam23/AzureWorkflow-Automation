<h1>Azure Logic Apps Workflow Automation</h1>
<b>Project Overview</b>
<br />
<br />

<p>This project demonstrates the implementation of an automated workflow using **Azure Logic Apps** to streamline form submissions. The workflow triggers an email notification upon receiving data from an online form, enhancing communication efficiency.</p>


<h2>Form Submission Email Workflow</h2>
<p align="center"><img width="924" alt="EmailConfirmation" src="https://github.com/user-attachments/assets/1d0c81bf-8912-4986-ad28-f305632a3093"></p>

<br>
<br>


<h2>Tools & Technologies Used</h2>

- **Azure Logic Apps**: A cloud service for automating workflows and integrating applications and services without extensive coding.
- **Office 365 Outlook**: Microsoft’s email service, utilized to send automated email notifications upon form submission.
- **JSON**: A lightweight data format for structuring data, used to validate and transmit information in HTTP requests.
- **HTTP Requests**: A protocol for sending data over the web, used to trigger workflows in response to form submissions.
- **Postman**: An API testing tool that allows users to send requests and view responses, used to test the Logic App’s HTTP trigger.
- **Azure Portal**: A web-based management interface for Microsoft Azure, enabling users to create and manage Logic Apps and resources.
- **Runs History in Azure**: A feature for monitoring workflow executions, providing logs and details on success or failure for troubleshooting.
<br />


<h2>Steps</h2>

Setup Instructions

1. **Create a Logic App**:
   - In the Azure portal, create a new Logic App and select the **Consumption Plan**.

2. **Define the Trigger**:
   - Use the **When an HTTP request is received** trigger to start the workflow.
<p align="center"><img width="1123" alt="HTTPrequest" src="https://github.com/user-attachments/assets/f5cc4fb7-22c9-4ccf-b8d7-736b192053ae"></p>

3. **Configure the Email Action**:
   - Add the **Send an email (V2)** action using the **Office 365 Outlook** connector.
<p align="center"><img width="1123" alt="sendemail" src="https://github.com/user-attachments/assets/30572f28-73a2-4eab-ad27-4374ccab7fc4"></p>

4. **Testing the Workflow**:
   - Use tools like Postman to send HTTP POST requests to test the workflow and verify email receipt.
<p align="center"><img width="1440" alt="Postman" src="https://github.com/user-attachments/assets/657094af-42e5-4d71-aa63-91c07d81ab79"></p>

5. **Monitor and Troubleshoot**:
   - Utilize the **Runs history** feature in Azure to monitor the workflow execution and troubleshoot any issues.
