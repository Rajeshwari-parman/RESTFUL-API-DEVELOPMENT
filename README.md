# RESTFUL-API-DEVELOPMENT

COMPANY: CODTECH IT SOLUTIONS

NAME: RAJESHWARI B

INTERN ID: CT4MVTW

DOMAIN: SOFTWARE DEVELOPMENT

DURATION: 4 MONTHS (16 WEEKS)

MENTOR: NEELA SANTOSH

🧾 Inventory Management System

A responsive, web-based inventory dashboard designed for managing product stock efficiently. It enables users to add, update, and delete inventory items with an intuitive UI. Built with modern frontend technologies and styled using Bootstrap 5, this project focuses on delivering a clean, user-friendly experience while interacting dynamically with a RESTful API backend.

📌 Description

This system provides a lightweight, functional interface to manage inventory data, including product names, quantities, and prices. All operations are performed via real-time communication with a backend API, ensuring that the interface stays synchronized with the database. Features such as client-side validation, responsive layout, modals for editing, and loading indicators make the application both robust and easy to use. The goal is to streamline inventory management tasks for small to medium-sized operations, ensuring accuracy and speed in item tracking.

🔧 Tools & Technologies Used

# Frontend:

HTML5

CSS3

JavaScript (ES6)

Bootstrap 5

# Backend:

FastAPI (tested via Postman)

✨ Key Features:-

🚀 Add, update, and delete inventory items

🔒 Validation to prevent negative quantities or prices

⚡ AJAX-based communication with the backend (no page reloads)

📱 Fully responsive design adaptable to all devices

🔄 Loading spinners and toast notifications for real-time feedback

🧼 Client-side form validation for clean input

🧠 Reusable modal forms for seamless editing

🎨 Design Philosophy:-

Clean & Minimal UI: The design is focused on usability, using soft shadows and accessible colors to create a visually pleasing interface.

Responsive First: Built with Bootstrap's grid system to ensure smooth functionality across desktops, tablets, and mobile devices.

Code Reusability: Utilizes component-like structures such as modal forms and dynamic table rendering for maintainability.

User Feedback Oriented: Real-time toast messages and loading indicators enhance the interaction flow and keep users informed.

🛠️ Steps to Run the Project

1. Clone the Repository

       git clone https://github.com/Rajeshwari-parman/RESTFUL-API-DEVELOPMENT.git
   
       cd RESTFUL-API-DEVELOPMENT
   
3. Start the Backend API
   
  If you're using FastAPI:

        uvicorn main:app --reload
        
  If you're using Django REST Framework (alternative setup):

        python manage.py runserver
        
  Ensure the API is running at http://127.0.0.1:8000

🔌 API Endpoints

| Method | Endpoint      | Description        |
| ------ | ------------- | ------------------ |
| GET    | `/items/`     | Retrieve all items |
| POST   | `/items/`     | Add a new item     |
| PUT    | `/items/{id}` | Update item by ID  |
| DELETE | `/items/{id}` | Delete item by ID  |

# Output

1. Dashboard:
   
  ![Image](https://github.com/user-attachments/assets/aeab17a3-d5e2-4ba6-8065-fb71cfcabe58)

2. Adding Item:
   
  ![Image](https://github.com/user-attachments/assets/502cdb89-257c-4b9d-9a8a-832861c34794)

3. Update Item:

  ![Image](https://github.com/user-attachments/assets/0f4db88e-efad-4f8d-b352-0b75ede115a0)

4. Delete Item:
   
  ![Image](https://github.com/user-attachments/assets/9ddaffaf-15d3-4d67-b875-9d4aa1bbf5e3)
