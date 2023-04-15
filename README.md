# Extracting-Business-Card-Data-with-OCR

Problem Statement:
Developing a Streamlit application that allows users to
upload an image of a business card and extract relevant information from it using
easyOCR. 
The extracted information should include details. The extracted information should then be displayed in the application's
graphical user interface (GUI).
In addition, the application should allow users to save the extracted information into
a database along with the uploaded business card image. The database should be
able to store multiple entries, each with its own business card image and extracted
information.


[Page sample](![Screenshot (29)](https://user-images.githubusercontent.com/120344718/232187119-dee0ab9c-8ff8-430c-ab92-aeac0d4a8746.png)
)

Approach:
1. Install the required packages: You will need to install Python, Streamlit,
easyOCR, and a database management system like SQLite or MySQL.
2. Design the user interface: Create a simple and intuitive user interface using
Streamlit that guides users through the process of uploading the business
card image and extracting its information. You can use widgets like file
uploader, buttons, and text boxes to make the interface more interactive.
3. Implement the image processing and OCR: Use easyOCR to extract the
relevant information from the uploaded business card image. You can use
image processing techniques like resizing, cropping, and thresholding to
enhance the image quality before passing it to the OCR engine.
4. Display the extracted information: Once the information has been extracted,
display it in a clean and organized manner in the Streamlit GUI. You can use
widgets like tables, text boxes, and labels to present the information.
5. Implement database integration: Use a database management system like
SQLite or MySQL to store the extracted information along with the uploaded
business card image. You can use SQL queries to create tables, insert data,
and retrieve data from the database, Update the data and Allow the user to
delete the data through the streamlit UI
