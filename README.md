# Help, help! Where am I?

Node-RED flow that contains functionality for figuring out where a patient is located, and dispatching ambulances to the location by sending navigation details to ambulance drivers

## Getting started

 

### Deploy the example
1. Register for a trial account at http://bluemix.net (IBM's new PaaS offering)
2. Log in
3. Click on **CREATE AN APP** and **WEB** and **BROWSE BOILERPLATES**
4. Choose the **Node-RED Starter**
5. Give your app a name and click **Create**
6. After a few minutes your app will be running (App Health: Your app is running)
7. Go to **https://\<your_app_name\>.mybluemix.net**
8. Click on **Go to your Node-RED flow editor**
9. Copy the text in **[application.flow](application.flow)**
10. In your Node-RED flow editor click on the menu button (top right)
11. Choose **Import From - Clipboard**
12. Paste the text your copied in **9.**
13. Click **Deploy**

### Running the example
1. Open a browser and go to **https://\<your_app_name\>.mybluemix.net/map**
  * Some firewalls block websocket packets. It is recommended to use HTTPS in the URL to avoid this
2. Open a browser on your cellphone and go to **http://\<your_app_name\>.mybluemix.net/client/\<your_phone_number\>**
3. In **/client/\<your_phone_number\>** enter the patient's name and click **Start tracking**
4. View the patient's position in **/map**

