# Smart-Serving-Robot
. PROBLEM STATEMENT
To develop a restaurant serving robot that can efficiently move between the kitchen and customers to serve their orders, while being connected to a Wi-Fi connectivity.

Software specification:

1.	User Interface (UI)

•	Responsive Design: Compatible with various devices (desktops, tablets, smartphones).
•	User-Friendly Layout: Easy navigation with intuitive menus and buttons.
•	Order Placement: Simple and clear order placement process.
•	Order Status: Real-time display of order status (e.g., received, in preparation, being served).
•  Order Input Interface (Kitchen Interface)
•	Keypad Input:
o	HTML form elements for keypad input to insert and identify table numbers.
o	CSS for styling the keypad interface to make it user-friendly.
•	Order Display:
o	An LCD-like display area to show customer orders using HTML and CSS.
o	The display will update dynamically to reflect real-time order statuses.
•  Robot Control Interface (Robot Interface)
•	Status Monitoring:
o	HTML elements to display the current status of the serving robot (e.g., idle, delivering, recharging).
o	CSS to ensure the status indicators are clear and easily interpretable.
•	Manual Control:
o	Buttons and controls implemented using HTML and CSS to manually override robot operations if necessary.
•	Route Visualization:
o	Optional: Integration of JavaScript for a dynamic map showing the robot’s current location and route.


     
•  Table Management Interface (Table Interface)
•	RFID Detection:
o	HTML elements to display the detected table numbers and their order status.
o	CSS to organize the table information clearly and concisely.
•	Order Tracking:
o	Real-time updates on order status for each table using HTML and possibly JavaScript for dynamic content updates.
2.	Backend Services
	
•	Database Integration: Manages menu items, orders, user data, and robot status.
•	Real-Time Updates: Websockets or similar technology for instant order updates and status changes.
•	APIs: RESTful APIs to facilitate communication between the webpage, robot, and backend server.
•	User Authentication: Secure login for both customers and staff.
    • C Language:
•	Usage: The C language is used for programming the microcontrollers within the system, including those in the Kitchen Interface and Robot Interface. This involves low-level control of hardware components such as motors, RFID readers, and keypad inputs.
•	Key Features:
o	Efficient memory management
o	Direct hardware manipulation
o	Real-time performance
      • HTML (HyperText Markup Language):
•	Usage: HTML is utilized to create the structure of web-based user interfaces for remote monitoring and control of the robot system. This can include dashboards for kitchen staff to input orders or management interfaces for overseeing system performance.


•	Key Features:
o	Defines the layout and structure of web pages
o	Supports multimedia integration (images, videos)
 •  CSS (Cascading Style Sheets):
•	Usage: CSS is used in conjunction with HTML to style and format the web-based interfaces, ensuring a user-friendly and visually appealing design. It enhances the usability and accessibility of the interfaces used by kitchen staff and management.
•	Key Features:
o	Controls the visual presentation of web pages
o	Allows for responsive design

. ALGORITHM
1.	Start.
2.	Select food item through webpage.
3.	Check availability of food
4.	if food is available then order display on kitchen module
5.	if food is not available then display not available
6.	After completion of order chef click table number
7.	Robot take order and server specific table
8.	End

•	Future Scope:
•	Enhanced Autonomy: Future smart serving robots may feature advanced navigation systems, enabling them to navigate complex environments autonomously with greater precision and efficiency. This could include improved obstacle detection and avoidance capabilities, allowing robots to navigate crowded spaces safely.
•	Customization and Personalization: There could be a trend towards customization and personalization of smart serving robots to meet specific needs and preferences. This might involve the ability to tailor interactions, such as greeting customers by name or remembering their previous orders, enhancing the user experience.

CONCLUSION
This project presents a novel approach to enhancing the dining experience for customers through the integration of a Serving robot and a smart restaurant system.
In this project, System created two key components: a waiter robot and a smart restaurant, both aimed at improving the dining experience for customers.
The smart restaurant encompasses four main areas: the reception, tables, waiter robot, and a designated track for the robot to follow. This well-coordinated system efficiently manages the order process, thereby streamlining and optimizing the overall dining experience for patrons. By integrating technology and automation into the restaurant setting, this project represents a forward-thinking approach to dining service, ensuring both efficiency and convenience for customers

