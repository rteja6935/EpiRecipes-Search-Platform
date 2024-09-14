# EpiRecipes-Search-Platform
#Project Description
--------------------
I developed a full-stack web application that indexes the "EpiRecipes" dataset into OpenSearch. It features a user-friendly interface for recipe search and filtering using React for the frontend and Python (Flask) for the backend.

#Opensearch Installation:
--------------------------
1.Download OpenSearch: Go to the OpenSearch website and download the latest version suitable for your operating system (Windows, macOS, or Linux).

2.Extract the Files: Once downloaded, extract the files from the ZIP or TAR archive to your preferred directory.

3.Install Java: OpenSearch requires Java 11 or higher. If you don’t have it installed, download and install Java from the Oracle website.

4.Start OpenSearch: Navigate to the OpenSearch folder in your terminal or command prompt and run the command:
                      Command: (./bin/opensearch).This will start the OpenSearch server.
5.Verify Installation: Once the server is running, you can verify the installation by opening a browser and visiting:http://localhost:9200

Backend Development:
--------------------
following packages are installed:
----------------------------------
1.Flask: For creating the web server and handling API routes.
2.OpenSearch-Py: For connecting and querying the OpenSearch server.
3.Flask-CORS: To allow cross-origin requests from the frontend (React).
4.jsonify: For converting Python objects to JSON to send responses back to the frontend.

Frontend Development:
----------------------
you should install the following packages:
-------------------------------------------
1.react-router-dom: For managing routes and navigation between pages.
Copy code: npm install react-router-dom
2.fetch API: Built-in with modern browsers, no need for installation, used for making requests to the Flask backend.
3.React useState and useEffect: Built-in with React for managing component state and side effects.
4.Optionally, you can install CORS on the backend to allow connections between your React app and Flask API.
5.Make sure your Flask backend is running and accessible at http://localhost:5000.


Link to the demo video on YouTube.
-----------------------------------
LINK:https://youtu.be/B6nd6_aLEYo










