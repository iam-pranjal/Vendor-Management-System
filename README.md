# Vendor-Management-System

# Vendor Management System

## Setup Instructions
1. **Cloning the Repository**: Start by cloning the repository using the command `git clone <repository_URL>`. Replace `<repository_URL>` with the actual URL of your GitHub repository. Navigate to the project directory with `cd vendorManagementSystem`.
2. 
3. **Virtual Environment Setup**: Create a virtual environment to isolate the project dependencies. If you haven't installed virtualenv, you can do so using `pip install virtualenv`. Then, create a virtual environment named `vmsenv` using `virtualenv vmsenv`. Activate the virtual environment with the appropriate command for your shell: `. vmsenv/Scripts/activate` for PowerShell or `source vmsenv/bin/activate` for Unix/Linux.
4. 
5. **Install Dependencies**: Once the virtual environment is activated, install the project dependencies listed in the `requirements.txt` file. Use the command `pip install -r requirements.txt` to install the required packages.

## Running the Server
To run the development server, use the command `python manage.py runserver`. The server will start running at `http://127.0.0.1:8000/`.

## Using the API Endpoints
The API endpoints provided allow users to perform CRUD operations on vendors and purchase orders. The available endpoints and their corresponding methods are as follows:
- **List Vendors**: `GET /api/vendors/`
- **Create Vendor**: `POST /api/vendors/`
- **Retrieve Vendor**: `GET /api/vendors/<vendor_id>/`
- **Update Vendor**: `PUT /api/vendors/<vendor_id>/`
- **Delete Vendor**: `DELETE /api/vendors/<vendor_id>/`

## Test Suite Instructions
To run the test suite, ensure that your virtual environment is activated. Then, navigate to the project directory and run the command `python manage.py test`. This will execute all tests in the project and display the results.
