CAMS Event Management System | Built with Django

As part of my latest project, I developed the CAMS Event Management System, a comprehensive platform designed to streamline event management processes. The system is constructed using Django, a robust web framework, and features a multi-user structure to facilitate various functionalities.

Key Features:

User Roles:

Admin (Superuser): The admin holds the highest level of control within the system. They can add and manage venue details, register and manage managers, resolve customer queries, and oversee all activities within the system.

Manager (User Group Created by Admin): Managers have restricted permissions compared to admins. They can update event statuses, view user-registered events, manage customer queries, update their availability status, and access venue details.

User: Users can create accounts, log in, and access a dedicated user interface. They can view venue details, including descriptions, prices, and locations (integrated with Google Maps), access the manager contact information, register for events, and check their order statuses (pending, confirmed, completed, or cancelled). They can also contact customer support and log out as needed. User Interface:

Home Page: Displays comprehensive details about venues, including prices and locations, enhanced with Google Maps integration for easy navigation.

Manager List Page: Shows a list of managers along with their contact information as registered by the admin.

Event Registration & Order Page: Allows users to register for events and view their booking orders along with their statuses (pending, confirmed, completed, or cancelled).

Customer Support: Provides users with a channel to address their queries and receive support.

Admin Capabilities:# Event-Management-System
