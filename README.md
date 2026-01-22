# PyDashServe
PyDashServe is a Python project template integrating FastAPI for backend services with Streamlit for interactive dashboards. Built with Poetry for dependency management, it provides a structured foundation for developing data-driven web applications with minimal setup time.

# Features
- FastAPI backend with automatic OpenAPI documentation
- Streamlit interactive dashboard
- Poetry for dependency management
- Structured project layout following best practices
# Getting Started
## Prerequisites
```
Python 3.12+
Poetry
```
## Installation
Clone the repository:
    
    git clone https://github.com/MELGABSI/PyDashServe.git
    cd pydashserve
Install dependencies with Poetry:
    
    poetry install
Run the FastAPI backend:
    
    poetry run TODO
In a separate terminal, run the Streamlit dashboard:
    
    poetry run TODO
Access the applications:
    
        FastAPI: http://localhost:8000
        FastAPI docs: http://localhost:8000/docs
        Streamlit dashboard: http://localhost:8501
## Project Structure
    app/api/: FastAPI application and endpoints
    app/dashboard/: Streamlit dashboard
    app/core/: Core functionality and configuration
    app/utils/: Utility functions
    tests/: Test modules
## License
This project is licensed under the MIT License - see the LICENSE file for details.