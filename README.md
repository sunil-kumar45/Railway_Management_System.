# Railway_Management_System.
# Description
The railway management system allows passengers to enquire about available trains based on their boarding station and arrival station, purchase and cancel tickets, and check the status of their booked tickets, among other things. The goal of this case study is to design and develop a database that stores information about various trains, train status, and passengers. The number, name, source, destination, and days on which the train is available are all included in the train record, whereas the train status record includes the dates for which tickets can be booked, the total number of seats available, and the number of seats already booked.

Passengers may look for trains by entering the boarding station, arrival station, and date of travel. If there are any trains available, they will be displayed. Following that, passengers may book their tickets. A ticket with the Passenger Details will be generated, and a confirmation email with the ticket details will be issued to the user. If a passenger wishes to cancel their tickets, they must first input their PNR number and then cancel them.Passengers can also search the running status of the train by entering train number and date of journey.

# How to use the website
Create a database with the above sql code, then download all the html files from the Template folder and the web.py file. Install all the necessary dependencies - libraries. Then run the python file on the terminal - python web.py.

When you run the program, you will be directed to the homepage, where you may login, register, read the Terms and Conditions, and opt out of the Privacy Policy.

You need to release the general and tatkal tickets using the admin login (Username="Ram", Password="1234").

To register, click the Register button, where you will be asked to provide the required details.

After successfully registering, you will be directed to the login page, where you must enter your registered username and password.

Then, you may search for trains by entering information such as the boarding station, arrival station, and date of travel. You will search trains based on the details you input and then book tickets of the required class. When you book the tickets, you will be requested to provide the passenger information. After successfully booking, a ticket will be generated, which may be downloaded by choosing the "Generate PDF" option, and a confirmation email will be sent to the user automatically.

By selecting the "Return home" option, you will be sent to the home page, where you can cancel your ticket by selecting the "Cancel Ticket" button. You will be asked to provide the ticket's PNR number. After entering the PNR number, you will be brought to a page with ticket information such as the PNR number, number of tickets, boarding station, arrival station, and date. You can cancel the ticket by selecting "Cancel Ticket." If the Cancellation is successful, the message "Cancelled Successfully" will display. Because tatkal tickets cannot be cancelled, the message "Cancellation not allowed" will display on the screen.

The running status can be viewed by heading to the home page and clicking on the "Check Running Status" button, where the user will be asked to provide the train number and date.
