We made this Pharmacy Management Web Application for CISC327. I wanted to continue work on the project and add more functionality to further polish the site so I forked it from the original repository.
I would like to credit my other group mates: James Song and Adwait Srivastava who worked extensively on the project with me.

We were able to achieve A+ grade in the course :)

# Recommended
To see finish product, navigate to [This Link](https://pharma-cisc327-group-45.netlify.app/)

This allows for Firebase Integration (backend database) while keeping API keys private.
The project works as intended, using our Firebase database.

# Locally
On a local machine, the backend Firebase Integration will not work immediately since you do not have our
API keys and information. You will have to insert the .env file into the root layer of our project.

Once that is done, ensure that all dependencies are installed on your local machine by running ```npm install```.

Next, you may start the development server by running ```npm start```.

## Brief Introduction to Implemented Requirements
- Requirement 1: The user shall be able to view a summary of the inventory and sales on a dashboard. On
startup, you will be presented with the dashboard. You can see a summary of the inventory, including the number
of medicines in stock, and the number of medicine groups there are. You can also see a summary of the sales,
with the number of medicines sold shown as well as the number of invoices generated.

- Requirement 2: Users shall be able to add a new medicine to the inventory. After startup, you may use the left
sidebar to navigate to the Add Medicines page. You will be presented with a form to fill out, and upon successfull 
completion, you will be able to add a new medicine to the inventory. The changes are reflected in the inventory page.

- Requirement 3: Users shall be able to search for a medicine by name. After navigating to the inventory page
you will see a search bar with the text "Search Medicine Inventory...". You are able to type into
this search bar, and then click the search icon on the right of the searchbar. After clicking the search icon,
only relevant medicines that are in the inventory will be displayed. You may reset the search by removing the text in the searchbar and clicking on the search icon again.

- Requirement 4: Users shall be able to update medicine details. On the Inventory page, you can see a blue 
edit button. Upon clicking this button, you will be allowed to edit the medicine information that it correspondes to. You may then click on the medicine's name, the medicine's ID, or the stock number and edit it. Finally, you are able to save the new information.

- Requirement 5: Users shall be able to delete a medicine from the inventory. On the Inventory page, you can 
see a red remove button. Upon clicking this button, it will remove the medicine that it corresponds to from the inventory.

- Requirement 6: Users shall be able to view sales reports. On the Sales page, you can see a summary of all 
of the sales of the pharmacy. You can see information such as the Order Id, the date in which it was ordered, the name of the medicine, the quantity, the price per unit, as well as the total revenue.

- Requirement 7: Users shall be able to view inventory. By navigating to the Inventory page, you can see
a summary of all of the medicines currently in stock. This allows the user to see what is in the inventory.

- Requirement 8: Users shall be able to make orders. By navigating to the Order page, the user will be
presented with a form to fill. After filling this form, the user can submit the order and the changes
will be reflected in the sales report.

### Install Dependencies
Once inside the project directory, install the necessary packages using:
```bash
npm install
```
This will download and install all the dependencies which will be listed in the ```package.json``` file.

# Running the Application
### Start the Development Server
To start the React app, use the following command:
```bash
npm start
```
This will start the server, and you can view the app in your browser by navigating to http://localhost:3000.

### Running Tests
To execute the test scripts, which are written with react-testing-library and Jest, launch a terminal server. After you have installed the dependencies, run:
```bash
npm test
```
And then select the option for running all tests. This will run all the tests in the project.
