# Stock Manager Desktop Application  
This application was created using Python and its tkinter library along with the matplotlib library to generate charts to display historical data for stocks.
Historical reports can be downloaded from Yahoo Finance as CSV files and then imported and analyzied by the program to then output an easy to read summary of the stock's movement. If you are using an IDE like VS Code, then a vritual environment is required and matplotlib needs to be installed for the code to run properly. The other libraries used are ones that already come with Python.    
### The basic interface  
Here we can see the fields to add information for a new stock and a button to add it to the list and an option to delete the highlighted stock from the list on the left.
![main](https://user-images.githubusercontent.com/100933440/213666928-cb6cb1bc-5904-4078-8316-465d955e8cb6.PNG)

### To obtain the CSV files from Yahoo Finance  
You can search your stocks on Yahoo Finance and download the historical data on a CSV file.
![YahooFinance](https://user-images.githubusercontent.com/100933440/213667872-32eacc84-013a-4b45-b08a-5fe6fe4107c2.PNG)

### Importing your CSV  
After you download your historical data, you can import it into the app and it will analyze the information.  
![Import CSV option](https://user-images.githubusercontent.com/100933440/213668278-93b8039e-402f-43c3-bb98-2fba97d4c3a3.png)

### History tab and Report tab  
![historyandsummary](https://user-images.githubusercontent.com/100933440/213668664-aaefb74c-9690-4be8-aa98-fe82c1616f1a.PNG)

### Chart Display
Using the matplotlib library, we can create a chart of the highlight stock. Multiple stocks can be selected and different colored line line appear to represent each stock.  
![Chart (2)](https://user-images.githubusercontent.com/100933440/213668965-6c1d3598-c8b3-459d-a3eb-430f3fff624b.png)
