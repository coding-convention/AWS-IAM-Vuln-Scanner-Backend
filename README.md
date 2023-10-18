# AWS IAM Vulnerability Scanner Backend

This project serves as the backend component for the AWS IAM Vulnerability Scanner. It is designed for researching potential vulnerabilities within AWS Identity and Access Management (IAM) configurations.


## 📚 Table of Contents

- [AWS IAM Vulnerability Scanner Backend](#aws-iam-vulnerability-scanner-backend)
  - [📚 Table of Contents](#-table-of-contents)
  - [🛠 Requirements](#-requirements)
  - [📍 Scan Items Location](#-scan-items-location)
  - [🚀 Setup and Installation](#-setup-and-installation)
  - [🧑‍💻 Usage](#-usage)
  - [✅ Todo](#-todo)

## 🛠 Requirements

- Python 3.10
- boto3
- FastAPI
- AWS CLI

## 📍 Scan Items Location
You can see the scan scripts for the vulnerability scanner are located in  [here]([URL](https://github.com/coding-convention/AWS-IAM-Vuln-Scanner-Backend/tree/main/routers/scan/scanner)).

## 🚀 Setup and Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/coding-convention/AWS-IAM-Vuln-Scanner-Backend
    cd AWS-IAM-Vuln-Scanner-Backend-main
    ```

2. Install the required Python packages:
    ```bash
    pip install boto3 fastapi uvicorn
    ```

3. Configure the AWS CLI with your AWS credentials:
    ```bash
    aws configure
    ```

## 🧑‍💻 Usage

Run the backend server using the following command:

```bash
uvicorn main:app --reload --host=0.0.0.0 --port=8000
```

Once the server is up, you can access the API documentation by navigating to:
[http://localhost:8000/docs](http://localhost:8000/docs)

## ✅ Todo

- [ ] Add more documentation
- [ ] Refactor package structure
- [ ] Refactor code