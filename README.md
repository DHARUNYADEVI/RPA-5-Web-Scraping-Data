# RPA-5-Web-Scraping-Data
## NAME:DHARUNYADEVI S
## REGISTER NUMBER:212223220018
## AIM:
To create a UiPath workflow that scrapes structured data from a website and saves it into a CSV file.

## ALGORITHM:
### Step 1:
Create a New Process Open UiPath Studio and create a new process named WebScrapingExample.

### Step 2:
Open the Target Website Open your web browser and go to: [https://www.amazon.com]

### Step 3: 
Use Data Scraping Wizard In UiPath Studio, click on "Data Scraping" from the Design tab.

When the wizard opens:
Click on the first product title.
Then click on the second product title to teach the pattern.
When prompted, extract URL as well (optional).
Click Next, then Finish.
The extracted data will be stored in a DataTable variable (e.g., ExtractDataTable).

### Step 4: 
Write Data to CSV After the Data Scraping activity, drag a Write CSV activity.
Properties: Input: ExtractDataTable FilePath: "BooksData.csv" (you can choose your own name) Include Headers: checked
### Step 5:
Run the Workflow
Save the workflow. Click Run.

## PROGRAM:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/da734c0f-99a9-407b-bcd9-50e1fee584ab" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a863aed3-2c5c-4bbe-a6fc-f73440348759" />


## OUTPUT:

<img width="1917" height="786" alt="image" src="https://github.com/user-attachments/assets/10b173a5-1405-4006-8ef8-e3b0252798f5" />

## RESULT:
The workflow successfully scrapes data from the website and saves it into a CSV file using UiPath's Data Scraping and File I/O activities.
