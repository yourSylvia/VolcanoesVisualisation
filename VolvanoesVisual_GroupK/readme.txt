README

------------------------------------------------------------------------------------
This is the readme for CesiumJS (Environment configuration)
1. Since the limitation of uploading file size, Cesiums is needed to be downloaded in advance.
2. Download Cesiums from into the folder "Visualisation_website":
	https://cesiumjs.org/downloads/
(You can follow the instruction on the website)
3. Download Node.js and NPM to the Cesiums root file ("Cesium-1.44")
	$ npm install
3. Put the file "volcano.png" into ~/Visualization_website/Cesium-1.44/Build/Cesium/Assets/Textures/maki
4. Put files in the folder "GeoJsonFile" to ~/Visualization_website/Cesium-1.44/Apps
5. Put test.html to the same place
4. Execute the server:
	$ node server.js
5. Test if your browser is ready for CesuimJS:
Launch the browser and navigate to, which should be a single Cesium page:
	http://localhost:8080/Apps/test.html.  

"If it doesn't work please contact sylvia221b@gmail.com. Thanks"

------------------------------------------------------------------------------------
This is the readme part for website,
Go to the "Visualization_website" file, and then click the home.html website.
In the website:
1. Make sure that you have already execute the server!
2. Click the centre link 
	"Click here to interact"
Which is the above link to the Cesiums page for visualisation of overall volcanoes's information.
3. Click the navigation buttons, 
   they will separately jump to corresponding module to show these visualisations.
4. Except the last module, 
   For every module, it contains a title with brief description 
   and a link for presenting interactive visualisation.
5. For the last module, it contains a animated gif global with description.




