AWS IAM Vuln Scanner Backend
----
### Description
This is the backend for the AWS IAM Vulnerability Scanner.</br>
This repository was developed to research potential vulnerabilities in AWS IAM.

### Requirements
- Python 3.10
- boto3
- FastAPI
- aws cli

### Usage
1. Clone the repository
2. Install the requirements
3. Set up the aws cli with your credentials
4. Run script "**uvicorn main:app --reload --host=0.0.0.0 --port=8000**"
5. Open your browser and go to **http://localhost:8000/docs**