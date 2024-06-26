Welcome to our user-friendly app designed to help you easily search for businesses based on business activities. Whether you're looking for construction services, specific business activities, or detailed company information, our app is here to assist you. Below, we've outlined the key features and functionalities that you can utilize while using our app.
*Note: Our ABN numbers may yield a list indicating that they were obtained from a government tool for looking up ABNs, where the postcode entered differs from the postcode returned by the tool.

Key Features:

 1. Business Activity Search: 
Our app allows you to search for businesses based on a wide range of business activities. Currently available activities for search include:

- Garage Construction
- House Construction
- House Alteration
- House Renovation
- Apartment Construction
- Duplex House Construction
- Flat Construction
- Semi-Detached House Construction
- Commercial Building Construction
- Industrial Building Construction
- Office Building Construction
- And many more...

 2. Postcode Search:
You can search for businesses based on their specific postcode. Enter the postcode you're interested in, and the app will provide you with relevant results.

 3. Website Information:
Our app provides you with the website details of the companies you're searching for. You can easily access their online presence and learn more about their services and offerings.

 4. Location Details:
Find the exact location of the company you're interested in. The app provides location information to help you locate the businesses on the map.

 5. Company Name:
Easily search for companies by their name. If you have a specific company in mind, simply enter the name, and our app will fetch the relevant information for you.

6. Download as CSV:
Users can save their searches as a downloadable.csv file from within our application.

7. Update ABN to up to date:
Our application may re-scrape the business website in response to your search for the most recent ABN numbers; if no such number is found, we will re-search using an ABN lookup utility provided by the Australian government.

How to deploy our application:

The user could then navigate to our project and execute the command below to deploy our application to their local network: 

"python database/create_load.py" (Make sure you have the local postgreSQL drive and change the database credentials in the database/create_load.py and streamlit/search.py)

“streamlit run streamlit/main.py”

 How to Use:

1. Business Activity Search:
   - Click on the search bar and start typing the name of the business activity you're interested in.
   - Select from the suggestions provided or enter the complete activity name.
   - Hit enter or click the search button to see the results.

2. Postcode Search:
   - Enter the desired postcode in the provided search field.
   - Hit enter or click the search button to find businesses in that area.

3. Website Information:
   - After performing a search, click on the company name to view detailed information.
   - Look for the "Website" section to find the company's official website link.

4. Location Details:
   - In the company information section, find the "Location" field to see the exact address of the business.

5. Company Name Search:
   - Click on the search bar and enter the name of the company you're looking for.
   - Select from the suggestions provided or enter the complete company name.
   - Hit enter or click the search button to see the results.
6. Download as CSV:
   - Click to “Download data as CSV” button which will appear after the search is complete. 
7. Update ABN to up to date:
  - Click to “Get up-to-date ABN numbers” button which will appear after the search is complete.
---

Our app is designed to make your business search experience smooth and efficient. If you have any questions or need further assistance, feel free to reach out to our support team. Happy searching!
