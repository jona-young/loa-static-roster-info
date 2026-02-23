You will need the following to run this script
  1. Python..this works on 3.13 but should work on earlier versions as well
  2. pip, the package manager for python, usually default installed with Python
    - The following packages installed,
        - gspread
        - BeautifulSoup
        - selenium
  3. Chrome web browser
  4. A Google Sheet for the script to write data
  5. Google Service Account
     - Go to https://console.cloud.google.com/ and create a new project
     - Enable the Google Sheets API and Google Drive API for that project
     - Create a service account for that project and download the JSON key file (e.g. "credentials.json")
     - Share your target Google Sheet with the service account email (found in the JSON key file) with Editor permissions
  5.1 credentials.json from Step 5 in the same directory as this script 
  6. Task Scheduler if you want to automate the script to run at specific instances
