# Basic Flask Application with Health Check Endpoint

## What is Flask?

Flask is a lightweight and flexible web framework for Python. It is designed for building web applications quickly and efficiently, offering simplicity and minimalism while allowing developers to extend its functionality using extensions.

## Features of Flask:
- Lightweight and easy to use.
- Built-in development server and debugger.
- Supports URL routing.
- Highly extensible through plugins and extensions.

---

## How to Set Up the Application

### Prerequisites
- Python 3.7 or higher.
- `pip`, the Python package manager.

### Installation
1. Clone this repository or create the `flask-app.py` file with the provided code.
2. Install Flask using `pip`:
   ```bash
   pip install flask
   ```

### Usage
![image](https://github.com/user-attachments/assets/335bcb70-7241-4487-bece-8ff33db52275)

Visit the /health endpoint in your browser
```bash
http://127.0.0.1:5000/health
```
**Example response:**
```
{
  "status": "healthy",
  "message": "The application is running smoothly."
}
```
### Pros and Cons of Using Flask
**Pros**
- Lightweight: Minimalist design for small to medium applications.
- Flexibility: Easy to customize and extend.
- Built-in Tools: Provides built-in development server and debugging tools.
- Community Support: Well-documented and has a large developer community.
  
**Cons**
- Not Opinionated: Requires additional setup for larger applications, like database integrations or user management.
- Limited Built-in Features: Lacks advanced features available in more heavyweight frameworks like Django.
- Scalability: Best suited for smaller projects; scaling large applications might require additional effort.

