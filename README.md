# Terraza-restaurant-website.github.io

## ***Please open folder Terraza for the source code.***
The following are the major use cases associated with this 
project:
Our Project’s goals are:
• Fulfill the demands of our online customers, providing them 
with an easy interface to get their desired meal items.

• Make it possible for customers to click a button to purchase 
the needed items from anywhere in Gwalior.

• To satisfy their daily demands, provide on-time delivery to 
patrons like students, family, workers, etc. 

• Make the payment interface as seamless, quick, and safe as 
you can.

• Verify the web application's mobile friendliness.

• Implement an open review process.

• Implement a mechanism for tracking deliveries.

• Create a loyalty program to reward loyal consumers with 
exclusive offers and discounts.

• Comprehensive classification of the many items on the menu 
and sophisticated filtering tools.

• Make sure that the products' quality meets the guidelines set 
up by India's Food Safety and Standards Authority

1. Supplier Side:
Our project's supplier is our client, Annapurna 
Restaurant. The project gives the restaurant a platform 
to advertise its services and goods. This ensures a 
diverse audience. It also allows for efficiency gains 
because the platform fee is significantly lower than 
that charged by the mediators. The loyalty plan 
ensures that the restaurant has a consistent income 
stream. The review system would give Annapurna 
valuable feedback, allowing them to enhance their 
menu items.
2. Customer Side:
Because of the wide variety of items on the platform, 
the consumer's options grow exponentially. It enables 
them to compare and obtain the best meals based on 
their preferences. The numerous options also foster a 
healthy competitive environment, which helps our 
client and their expansion of restaurants throughout 
the city.

There are numerous subsections in this document of software 
requirements specifications. The purpose, scope, and organization of 
the document are all explained in the first section. The definition of 
project-specific terms, acronyms, and abbreviations utilized in the 
document is also covered in the first section.
The functionalities of the software are described in non-technical 
terms in the second section of the document. It serves as a preface to 
the section on technical requirements in the third part of the 
document and describes the informal requirements.
All of the specifications outlined for this system are enumerated in 
the third section. It explains the software's intricate functionality in 
technical terms and is primarily aimed at developers.

An overview of the topic AMOS is given in the next section. A thorough 
review of the system, user, hardware, software, and transceiver, memory 
considerations, operational modes, and site adaptation requirements has 
worked to put the product into perspective. Beyond the identified system 
constraints and assumptions, the discussion includes the final features of 
the system. The section has been finished with a breakdown of the 
requirements.

A full AMOS system is software described in this SRS. The model 
utilizes various pieces of hardware and software and additionally 
connects to external systems. Thus, even though the software handles 
the majority of the system's functionality, it also physically interacts 
with people and relies on several external interfaces for persistence 
and unhandled tasks.
System Interfaces
To handle customer billing quickly and easily, AMOS interfaces with 
an existing payment system, such as a cash register and softwareaccessible credit system. The payment system must be functional to 
inform the AMOS system whether the payment was successful or 
unsuccessful.
Surface computer UI
Customers of restaurants interact with the Surface Computer UI. 
Users of AMOS can move items such as food items, dietary needs, 
tips, and menus around on their PC. These objects can be 
transferred into objects, like meals and payments, to carry out a 
range of tasks. In regards to this paradigm for object 
manipulation, a constrained system menu is required. Using a 
simple touch gesture, a double-tap on the touch surface, users 
will call up their restaurant menu, which is combined with a 
scheme menu, and will dismiss it with similar gesture or by 
tapping a close button GUI element.

● Inputs:
1. Pattron’s details (username and password) to access their 
account. (Simple)
2. Update Profile. (Simple)
3. ‘Browse Menus’ search bar. (Simple)
4. Browse Items (Simple)
5. Sorting preference. (Average)
6. Adding/Removing the desired amount of a product that is on 
hand to the shopping cart. (Simple)
7. Promo codes for availing cash discounts. (Simple)
8. Ratings and written reviews for the products. (Simple)
9. Item details (including images) for listing an item in the store. 
(Average)
10. Replying to the customer reviews. (Simple)
11. Order details by the seller (Average).
12. Register/Login Admin or restaurants. (Average)
13. Add/Remove Admins. (Average)

● Outputs:
1. Confirmation message: “Login successful”. (Simple)
2. Confirmation message: “You are successfully logged out”. 
(Simple)
3. Confirmation message: “Review added successfully”. (Simple)
4. Confirmation message: “Item successfully added to the menu”. 
(Average)
5. Error message: “Invalid login credentials”. (Simple)
6. Error message: “Review cannot be blank”. (Simple)
7. Error message: “Reply cannot be blank”. (Simple)
8. Error message: “Shopping cart cannot be null to checkout”. 
(Simple)
9. Logout Confirmation Prompt: “Please confirm the logout 
attempt (Simple)
10.Confirmation Prompt: “Please confirm to proceed with 
payment” (Simple)
11. Weekly Report to Admins generated by the system. (Complex) 
12. Confirmation message: “Update Profile successful”. (Simple)
13. Error message: “Payment Error”. (Average)
14.Confirmation message: “Admin Login successful”. (Simple)
15. Confirmation message: “Admin are successfully logged out”. 
(Simple)
16. Add/Remove Menu Successfully. (Simple)
17. Error Message: Login Invalid. (Simple)

● Inquiries:
1. View items. (Average)
2. View Menus. (Simple)
3. Order status (tracking order). (Average)
4. Contact (Average)
Number of inquiries: 4

● Files:
1. List of registered patrons. (Average)
2. List of registered Admins/Restaurant. (Average)
3. List of items on menus. (Average)
4. Shipping and payment information. (Complex)
5. Stock and items amount left. (Average)
6. Order and sales details for weekly report. (Complex)
7. Allotting Orders to our delivery partner Entrega. (Complex)
Number of files: 7

● Interface/External Logical Files:
1. Customer module. (Complex)
2. Admins/Restaurants module. (Complex)
3. Payment gateway API (PayGO) for facilitating payments. 
(Average)

The following technique should be utilised when designing the 
AMOS: The waterfall model will be the most appropriate 
language for this type of system. This is due to the waterfall 
model's suitability for visualising, designing, creating, and 
documenting system aspects. The following approach will be 
taken in the design:
1. Creating the database.
2. Establishing relationships.
3. Creating user interfaces and system processes.

User Interface Design
1.  Principles
The Structural Concept - UI is designed in such a way that 
related things are combined and unrelated things are separated.
The Simplicity Concept - The offered interface is simple to use. 
In the event of a problem, the system shows an error message.
The Visibility Concept - All system functionalities are accessible 
via the UI. It does not overburden users with too many options.
The Feedback Concept - The design keeps users informed of 
actions, problems, or exceptions via a message system.
The Concept of Reusability - In order to eliminate ambiguity, 
the same names were used in design to conduct the same 
operations with different objects.
