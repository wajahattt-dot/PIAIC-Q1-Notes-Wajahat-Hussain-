# 🚀 PIAIC Sunday Class 04 - Bahria Auditorium - 18th August 2024

👋 **Instructor:** `Wajahat Hussain`

---

### 📘 Topics Covered:

1. **Software Defined Networking (SDN):**  
   SDN is a method of managing networks using software to control hardware. This allows for more flexible and efficient network management.

2. **Python as an Interface Language:**  
   Python is commonly used as a bridge between systems, allowing them to communicate effectively. It's versatile and widely used for:
   - Web Development
   - Desktop Applications
   - Command Line Interface (CLI) Tools
   - Cloud Toolkits

3. **FastAPI:**  
   FastAPI is a high-performance framework for building APIs in Python. It supports asynchronous programming, crucial for high-performance applications.

4. **Creating Interfaces:**  
   Use of HTML, CSS, JavaScript, and JSON to build user interfaces, with Python integration for dynamic applications.

   - **Streamlit:**  
     A Python library to easily create custom web apps for machine learning and data science projects.

5. **Large Language Models (LLMs) and Deep Learning:**  
   LLMs are advanced AI models built using deep learning. Python, supported by frameworks like PyTorch (Meta's contribution), is the default language for AI.

6. **The Zen of Python:**  
   A collection of principles that emphasize simplicity, readability, and elegance in writing Python code.

7. **Compiler vs. Interpreter:**
   - **Compiler:** Translates the entire program to machine code before execution.
   - **Interpreter:** Translates and executes code line by line (Python is an interpreted language).

---

### 💻 Code Example: Hello World in Python

Here’s how you can write and run a 'Hello World' program in Python using VS Code:

```python
# app.py
print("Hello, World!")
```

## 🐋 Docker - Building and Running a Container

### Creating a Dockerfile:
```
# Dockerfile
FROM python:3.9-slim
WORKDIR /app
COPY . /app
CMD ["python", "app.py"]
```

### Building the Docker Image:
Run the following command to build the Docker image:
```
docker build -t hello-world-app .
```

### Running the Docker Container:
To run the container and see "Hello, World!" in the terminal:
```
docker run hello-world-app
```
🚀 Happy Learning! 😃
### Made By Wajahat 🤝

