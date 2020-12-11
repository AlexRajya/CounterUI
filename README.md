# Counter API UI
This is a user interface which makes use of a simple counter API. The interface was made with reactJS.

#Installation:
1. Copy index.html in to the static directory of the API, replacing any existing index.html
2. Deploy app with 'gcloud deploy app' in the cloud shell when in main API directory
3. View the UI on the url provided with 'gcloud app browse -s serviceName' in the cloud shell

#Usage guide:
1. Type the name of a new counter and click add button to either bring up the counter if it exists, or create a new one. 
2. Enter a value in the input box and click set button to set the counter register to a specific value
3. Press the '+1' button to add 1 to the counter
4. Press the delete button to remove the counter from the datastore, pressing any other button will create the register again. 
5. The registers update once per second
