# Mathematics Web App using Flask

This repository contains a simple Flask-based web application for solving basic mathematical problems like addition, subtraction, and multiplication. The app demonstrates the use of Flask for creating a web interface and JavaScript for client-side interactivity.

---

## Repository Structure

```php
php
Copy code
Mathematics-Web-App-using-Flask/
│
├── Maths/                       # Mathematical logic implemented in Python
│   └── mathematics.py           # Functions for arithmetic operations
│
├── static/                      # Static files (JavaScript, CSS, etc.)
│   └── mywebscript.js           # JavaScript for handling client-side operations
│
├── templates/                   # HTML templates for rendering web pages
│   └── index.html               # Main web interface for the app
│
├── server.py                    # Flask application server
└── README.md                    # Project documentation

```

---

## Features

1. **Arithmetic Operations**
    - Addition
    - Subtraction
    - Multiplication
    - (Division and Power can be extended)
2. **Web-Based Interface**
    - Intuitive design using HTML, CSS, and Bootstrap.
    - User input handled through a dynamic front end with JavaScript.
3. **Server-Side Processing**
    - Routes for performing mathematical operations (sum, subtraction, multiplication) on the server using Flask.
4. **Interactive Frontend**
    - Live calculations using JavaScript for instant results without server interaction.

---

## Setup Instructions

### Prerequisites

- Python 3.7+
- Flask

### Installation

1. **Clone the Repository**
    
    ```bash
    git clone https://github.com/your-repo/Mathematics-Web-App-using-Flask.git
    cd Mathematics-Web-App-using-Flask
    ```
    
2. **Install Dependencies**
    
    ```bash
    pip install flask
    ```
    
3. **Run the Application**
    
    ```bash
    python server.py
    ```
    
4. **Access the Application**
    
    Open your browser and navigate to `http://127.0.0.1:8080`.
    

---

## Usage

### Frontend Interface

- Enter numbers in the provided fields.
- Use the buttons to perform operations like addition, subtraction, and multiplication.
- Results are displayed dynamically on the page.

### Backend Operations

The following routes handle server-side requests:

1. `/sum`: Performs addition of two numbers.
2. `/sub`: Performs subtraction of two numbers.
3. `/mul`: Performs multiplication of two numbers.

### Extending Functionality

To add more operations (e.g., division, power):

1. Implement the function in `Maths/mathematics.py`.
2. Add a corresponding route in `server.py`.
3. Update the frontend to call the new operation.

---

## Files Breakdown

1. **`server.py`**
    
    Hosts the Flask application, defines routes for arithmetic operations, and serves the HTML frontend.
    
2. **`Maths/mathematics.py`**
    
    Contains backend logic for arithmetic operations.
    
3. **`templates/index.html`**
    
    Main webpage for user interaction.
    
4. **`static/mywebscript.js`**
    
    Client-side JavaScript for performing live calculations.
    

---

## Example

1. **Performing Addition**:
    - Navigate to the home page.
    - Input two numbers.
    - Click "Add" to see the result.
2. **Server-Side Calculation**:
    - Access `/sum?num1=5&num2=3` to calculate the sum of 5 and 3.

---

## Contributing

1. Fork the repository.
2. Create a new branch for your changes.
3. Submit a pull request.

---

## License

This project is licensed under the MIT License. See `LICENSE` for details.

---

## Acknowledgments

- **Flask**: Framework for the web application.
- **Bootstrap**: Styling for the frontend interface.
- **JavaScript**: Dynamic client-side interaction.
