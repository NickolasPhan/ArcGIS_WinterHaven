<h1>ArcGIS Winter Haven</h1>

Winter Haven, Lake Elbert section of map inside Unreal using ESRI ArcGIS SDK Plugin, demonstrating layer use and featuring an implementation on how to import Feature Layer data into the Unreal game environment.

<h2>I. ArcGIS Maps SDK Plugin</h2>
This project requires the ArcGIS Maps SDK Plugin for Unreal Engine to run properly. To include this plugin in this project, follow these steps:

1. Download the ArcGIS Maps SDK Plugin.
2. Inside the Unreal project directory, create a folder named 'Plugins'.
3. Unzip the compressed file and move the folder 'ArcGISMapsSDK' inside the newly created 'Plugins' folder.

<h2>II. ArcGIS User Authentication App</h2>
This project requires the 'ArcGIS User Authentication App' (created by me in another repo) to run properly. To include this app in this project, follow these steps:

1. Clone the 'ArcGIS User Authentication App' into the project directory.
2. Run the app once to generate the access_token.txt file.
3. Periodically refresh the access token, as it expires in 30 minutes.
