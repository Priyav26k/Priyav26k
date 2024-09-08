# Clone the repository
git clone https://github.com/yourusername/ecom-flow-automation.git

# Navigate to the project directory
cd ecom-flow-automation

# Install dependencies
pip install -r requirements.txt

# Run all tests
pytest -n 4 --html=report.html --self-contained-html

# Build Docker image
docker build -t ecom-tests .

# Run Docker container
docker run ecom-tests

# Ecom Flow Automation

## Description
Ecom Flow Automation is a test automation framework designed to validate key user journey flows in an e-commerce webshop. The project leverages Python, Selenium, and pytest, incorporating design patterns and best practices to ensure scalable, maintainable, and efficient test automation.

## Features
- Automated test cases for browsing, adding items to cart, and checkout flows.
- Utilizes Page Object Model (POM) design pattern.
- Parallel test execution using pytest-xdist.
- Detailed HTML reporting using pytest-html.
- Dockerized setup for ease of deployment and execution.

## Setup and Installation
### Prerequisites
- Python 3.8+
- Docker (Optional)

### Installation
```bash
git clone https://github.com/yourusername/ecom-flow-automation.git
cd ecom-flow-automation
pip install -r requirements.txt
