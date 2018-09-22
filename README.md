# LabRetriever
Lab Retriever is an app that allows users to upload an image of a handwritten/hand drawn data table.  Once uploaded, the image file is processed to return an equivalent data table in Excel.  

Web App

Using Python Flask to handle Post requests.  The web app is serviced through AWS EC2.  Accepts one parameter which is checked on client side to be a valid image file.  The web app then runs the python files to process the image and returns the excel document that has the handwritten digits in different cells.  

Mobile App

Using React Native to be the client side.  Asks the user for input in the form of a valid image file type.  Prompts user to make sure the data table is delimitted with lines for rows and columns.  The python file will only translate the numbers.  