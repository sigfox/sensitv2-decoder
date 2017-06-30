# sensitv2-decoder
Simple excel spreadsheet to decode Sensit v2 frames (uplink and downlink). 
Sensit v2 is a Sigfox device that can sense temperature, humidity, door opening, magnetic fields and has a button to press. It is super usefull for demos and tests. 
The website is : https://www.sensit.io/ 

The normal way of using it is with its application (mobile and web) that consumes the payloads and displays the values. However for development purpose, it is possible to detach the sensit from this application in order to gain direct access to the Sigfox backend and configure an integration with a customer made application. 

There are 3 tabs in this spreadsheet : 
* References : the tables used to understand the codes used in the Sensit frames. 
* Uplink : Type in the payload that you get out of the sensit v2 in the yellow cells in the top row, you can read the values below. 
* Downlink : Choose the values that you want to send to the Sensit in the left column, you will obtain the downlink payload. 
