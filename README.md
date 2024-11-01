# BHPC Manager

**BHPC Manager** is a comprehensive solution for overseeing a substantial part of the procedures involved in the distribution of our foreign partner's products across Europe and Latin America.

### Version 4.1 Features

#### Order and Shipment Control Features

- **Order Creation**: Create sales, sampling, and supply orders.
- **Product Line Input**: Add products to orders, specifying if they are for sale, discounted, or offered as F.O.C. (free of charge).
- **Shipment Details Userform**: A dedicated userform to view details of each shipment (whether supply, sampling, or sales), allowing users to save all logistical details, preparation status, payment status, import/export document drafting status, and additional notes.
- **Currency Conversion**: Convert orders in foreign currencies to euros.
- **Automatic Document Generation**: Automatically generate key documents for customers and transporters, including:
  - **Invoice**
  - **Packing List**
  - **Multimodal Form**

#### Warehouse Control Features

- **Warehouse Section**: Added a dedicated section to track product movements within the warehouse.
- **Product Management Userform**: Userform for managing BHPC products:
  - Create or modify products.
  - Create/modify bill of materials (BOM) for composite products, such as gift sets.
  - Define and assign risk classes to hazardous products for correct automatic generation of multimodal forms.
- **Production Management**: Execute production orders and preview production to check the availability of all necessary components for composite products.
- **Stock Availability Tracking**: Track product availability in the warehouse to quickly determine if customer demands can be met.
- **Gift Set Production**: Implemented functionality to execute the production of gift sets.

#### Administration Features

- **Administration Section Update**: Completely updated the administration section.
- **Data Import/Export**: Allow users to export and import data as needed.
- **Database Access**: Allow users direct access to databases for making corrections directly to records.

#### Customers / Suppliers Features

- **Customer/Supplier Management Userform**: Implemented a userform to create or modify customer and supplier details.

### Future Features

#### Planned Features for Future Versions

- **Bug Fixes and Exception Handling**: Implement comprehensive bug fixes and exception management to enhance system stability.
- **UI/UX Improvements**: Improve various aspects of the user interface and user experience to make the application more intuitive and efficient.
- **Migration to Access Database**: Transition to an Access database for application data. As the application has expanded and grown more complex, the original tables have become too large and challenging to manage. The plan is to implement a dedicated Access database and use VBA to facilitate data access (both read and write).
- **Product Management Userform Enhancement**: Modify the userform for product management to include warehouse details, such as stock levels and average cost.

### Status and Usage

Currently, the application is still a work in progress but is functional enough to be used for creating a consistent dataset of outgoing orders (sales and sampling) and for quickly generating documentation. This eliminates the need for manual, slow, and error-prone document creation processes.

