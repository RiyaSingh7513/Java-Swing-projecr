# Java-Swing-project
This is a billing application. It can be used to add items to cart and generate bills. It is written in Java, GUI is implemented using Java swing and the application is connected to MySQL using JDBC.
# Requirements
MySQL server containing billing database (which can be found in data directory of this project)
# Project Design
In the main project directory there is a src sub directory which contains two directories; bills and images.
Bills is a package which contains all the java files having the classes which implement the main functionalities required for this project.
Images contains the background image used in the GUI.
The project directory contains an .iml file which contains the module configuration for the project.
# Functions
## Homepage
This window presents three options: login, signup and exit.
![homepage](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/0acadad7-06fa-4d3b-a5d8-82551a3a8c89)
## Signup
Signup form consists of 5 inputs all of which are required to signup.
![signup](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/dc46ae68-928a-41de-ac70-1be59babfbee)
## Login
Login form requires username and password to validate the user.
![login](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/ede3419b-0213-491e-85b0-db6dd3f699fd)
## User Profile
Login and signup both will be redirected to this window on successful validation of user. User profile contains the date of last transaction. If null, "You haven't made any transactions yet" is displayed. A button to show previous user transactions. Also, a button to take you to the shop or exit.
![profile](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/1d723473-1e30-4d9f-aaaf-1cd7a3f550f1)
![lasttransaction](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/28ec18f6-ded0-4c99-8ed0-ed7ae8d38d6e)
## Menu
This window contains a product GUI on the left side and a checkout GUI on the right side. On checking out, a bill will be generated. When the SHOW button will be clicked then the transaction will be final.
![menu](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/8867d9be-c6a9-4d00-86eb-08862ab7880c)
![showmessage](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/a3ae6966-f223-4253-a1cc-d234181750f9)
![bill](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/611d9a75-7dd8-426f-ba93-216cc5277ef2)
## Previous Bills
On clicking View Previous Bills on the user profile page, the window will show a table consisting of past transactions. If null, "No Transactions yet" will be displayed.
![prevbills](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/2ac79b58-c60d-4ccf-a1d8-3ccc2a620c2e)
![transactions](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/2ce3c989-93e7-493d-99e4-e181d3a7b116)
## Database Connectivity
A singleton class is created to instantiate a single database object to use throughout the project.
## Database
2 tables are used in this project: customers and bills.
![db](https://github.com/RiyaSingh7513/Java-Swing-projecr/assets/95078406/43715de8-5f84-4223-b53c-03626bf147d1)





