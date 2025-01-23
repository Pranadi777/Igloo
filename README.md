# Igloo Laboratory Management System

[View Demo Video](https://drive.google.com/file/d/1VJ05I40E-KRGjafK-0Qm0k_hMd4-R_fo/view?usp=drive_link)

**Igloo** is a sophisticated laboratory management system designed to streamline the organization and tracking of laboratory resources. This platform empowers researchers and lab administrators by offering a structured, user-friendly solution for managing items, metadata, and storage units within a collaborative environment.

## Key Features

- **Custom User Management**: Robust user authentication and authorization with lab-specific permissions, including roles for administrators, editors, and viewers.
- **Lab Associations**: Users can join or switch between multiple labs, manage memberships, and set an active lab for focused data access.
- **Metadata Management**: Flexible categorization and tagging of lab items with dynamic metadata creation and filtering capabilities.
- **Storage Organization**: Comprehensive support for storage hierarchies, including Cold Storage Units (CSUs), racks, and boxes, with customizable layouts and color coding.
- **Item Tracking**: Precise management of lab items, including metadata tagging, storage positions, and quick views of item locations within the storage hierarchy.
- **Interactive Search**: Powerful search capabilities for items and metadata, featuring tag-based filters, exportable results, and pagination.
- **HTMX and Alpine.js Integration**: Smooth and dynamic front-end interactions for forms, modals, and search results, enhancing user experience without reloading the entire page.
- **Extensive Test Coverage**: Comprehensive test suite ensuring functionality across key features, from user authentication to lab-specific operations.

## Technologies Used

- **Backend**: Django, Django HTMX, and Python.
- **Frontend**: HTMX, Alpine.js, and Bootstrap.
- **Database**: SQLite (configurable for other databases).
- **Testing**: Django’s TestCase framework for rigorous unit and integration testing.
- **Logging**: Integrated logging for better debugging and monitoring of application activities.

## Purpose

The Igloo Laboratory Management System is specifically designed for research laboratories, enabling efficient resource management and reducing the complexity of organizing and tracking materials in a shared environment. Its modular architecture and extensible design ensure that it can adapt to the unique needs of different labs.
