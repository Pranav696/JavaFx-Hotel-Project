***Introduction***
==================

### 

**1. *Purpose*** 
-----------------

The purpose of this document is to build a portal to manage day to day
working of a Hotel.

This application can be used to manage room bookings, food ordering, and
keeping track of food order history as well as room history.

  DB           Database
  ------------ ---------------------------
  ER diagram   Entity Relational Diagram

#### **1.1 INTENDED AUDIENCE AND READING SUGGESTIONS**

This Application is a prototype of the Hotel Management System. This
Application can be used in the Hotel’s Reception so as they are able to
manage all the working of the hotel efficiently.

Intended audience of this application are guests who are booking rooms
or ordering food from the hotel.

#### **1.2 PROJECT SCOPE**

The hotel industry, also known as the people's industry, is presently
undergoing a skilled and knowledgeable labor shortage. According to
projections, this industry will require more than lakhs of workers over
the next five years. Based on this theory, the chances of getting a
respectable position in this sector are incredibly high.

Therefore in order to gain advantage over the competitor we have this
application. This application provides ease in the management of the
hotel services and serves a great purpose in the day to day working of
the Hotel.

**1.5 Software Development Mode**

#### ![](media/image1.png){width="7.189535214348206in" height="4.302171916010499in"}

Software Development life cycle used in this project is the waterfall
model. The entire software development process is divided into phases in
"The Waterfall" approach. Typically, the result of one phase serves as
the input to the next layer in this Waterfall model.

Advantages of Waterfall Model

1)  Clearly Defined stages

2)  Good for beginners

3)  Process are well defined

4)  Every stage has to be complete before going to the next stage

**2. *OVERALL DESCRIPTION***
----------------------------

####  

####  **2.1 PRODUCT PERSPECTIVE**

The distributed hotel management database stores the following data:

1)  Current hotel booking

2)  Checking in/out

3)  Hotel’s Menu

4)  Food Ordering

5)  Hotel Rooms availability

#### ***2.2 PRODUCT FEATURES***

Majority of the features are outlined in the Entity Relationship diagram

![](media/image2.png){width="7.25in" height="4.2987718722659665in"}

#### 

#### ***2.3 CHARACTERISTICS***

-   Users of the system will be able to manage the food orders from
    > the customer. They can also edit the menu.

-   It helps the management to keep track of all the previous visitors.

-   It also keeps track of all the current visitors and the rooms
    > allotted to them.

-   Realtime track of available rooms.

-   Check-in and check-out options are available.

-   Real Time editing of the list of orders for food.

#### ***2.4 OPERATING ENVIRONMENT***

Operating Environment for this Hotel Management system are as follows:

1)  Distributed Database

2)  Operating System: Windows 11/ Linux

3)  Database: SQLite

4)  Platform: Java 11

**3. *SYSTEM FEATURES***
------------------------

-   #### ***DESCRIPTION and PRIORITY***

> The fundamental purpose of hotel management is to maintain a regular
> stream of visitors and guests throughout the year, as well as to use
> marketing campaigns to advertise the hotel's vast variety of services
> and USPs and how they benefit visiting consumers.

-   #### ***STIMULUS/RESPONSE SEQUENCES***

<!-- -->

-   Customer Information

-   Rooms

-   Booking

-   Food

-   Other Items

-   Check Out and Payment

<!-- -->

-   ***DISTRIBUTED DATABASE:***

> The term "distributed database" refers to the ability of a single
> programme to function transparently on data that is scattered over
> several databases and connected by a communication network.

**4. *EXTERNAL INTERFACE REQUIREMENTS***
----------------------------------------

#### **4.1 *USER INTERFACES***

-   Front-end software: Java

-   Back-end software: SQLite

***\
5. NONFUNCTIONAL REQUIREMENTS***
--------------------------------

#### **5.1 *PERFORMANCE REQUIREMENTS***

The E-R Diagram is a method for visually expressing the logical
structure of a database. After that, this analysis is utilized to
arrange data as a relation, normalize the relation, and create a
relational database.

-   **ENTITIES:** Which specify distinct real-world items in
    > an application.

-   **PROPERTIES/ATTRIBUTES:** Which specify properties of an entity
    > and relationships.

-   **RELATIONSHIPS:** Which connect entities and represent meaningful
    > dependencies between them.

#### **5.2 *SECURITY REQUIREMENTS***

Security systems, like many other applications, require database
storage. However, due to the unique needs of the security sector,
suppliers must carefully select their database partner.

#### **5.3 *SOFTWARE QUALITY ATTRIBUTES***

**AVAILABILITY:** The software should know if any rooms are available
and to whom all they are allotted to at a moment in time. It should also
be able to tell the availability of food items and their prices.

**CORRECTNESS:** The room should be allotted to the right guest at the
right time. All the food orders should add up to the right room.

**MAINTAINABILITY:** The concierge should commit to the system and be
honest with billing and everything to create a transparent log book ITR.

**USABILITY:** The software should make day to day log management and
billing of the hotel more efficiently and easily.
