Development of an Offline Data Storage and Synchronization Application

Tools & Technologies Used: C#, SQL Server, Razor Pages, ApexCharts, Entity Framework Core, Windows Forms

Project Overview:
In this individual project, I designed and implemented a robust application capable of collecting data offline and synchronizing it with a central SQL Server database upon re-establishing a connection. The application manages data from devices categorized into GPS, Electric, Water, and Gas types, and visualizes this data through a dynamic business intelligence dashboard.

Responsibilities:

Schema Design and Data Storage:
Developed a schema to effectively organize and store data, facilitating quick access and efficient management. The schema accommodated various measurements related to Device Name, Device Type, Timestamp, and measurement units, tailored to handle inputs from GPS, Electric, Water, and Gas devices.
Implemented local data storage using Entity Framework Core with SQL Server, enabling the application to function offline by caching data locally.

Data Collection and Processing:
Created a Windows Forms application to randomly generate realistic device data, simulating real-world inputs for testing and demonstration purposes.
Engineered the data collection logic within the Razor Pages application that captures real-time data, supported by comprehensive validation and processing to ensure data integrity before storage.

Synchronization with SQL Server:
Developed a synchronization module that detects network availability and conducts batch uploads of the locally stored data to SQL Server, ensuring consistency and minimizing data loss.
Utilized advanced data management techniques including transactional updates and conflict resolution to maintain database integrity.

Data Visualization and Reporting:
Built a standalone application using Razor Pages and ApexCharts for the business intelligence dashboard, providing interactive and insightful visualizations of the collected data through various chart types.
The dashboard aids in the easy interpretation of data trends and performance metrics across different device types.

Presentation and Documentation:
Presented the architecture and functionality of the application, demonstrating the offline data collection capabilities, synchronization logic, and visualization tools.

Concise Resume Summary:

Developed a standalone C# application that collects data offline and synchronizes with a SQL Server database using Entity Framework Core and Windows Forms for data generation. Implemented a business intelligence dashboard with Razor Pages and ApexCharts to visualize data from various device types (GPS, Electric, Water, Gas), showcasing advanced capabilities in handling and visualizing large datasets. The project highlights skills in full-stack development, database management, and application design.
