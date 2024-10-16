# File-Wizard
An open-source file conversion web app built with ReactJs, Python, and AWS for 
        the HTTP API, Lambda functions, and S3 object storage.
                 Converts .docx files to .pdf
                 
# Features   
* Website
- [NextJs](https://nextjs.org) App Router
- [Amazon Web Services](https://aws.amazon.com) for backend functionality
- Support for `HTTP API`, `S3` File Storage, and `Lambda` functions
- Edge runtime-ready

* AWS Infrastructure
 - Amazon S3 Allows for object storage and static site hosting
 - API Gateway hosts the HTTP API
 - AWS Lambda for processing JSON and filtering required data
 - Amazon EC2 for provisioning VM instances

# Overview 
![architecture- FW](https://github.com/user-attachments/assets/0d0bde69-6798-4654-8dad-e0728ef4f5c7)

A static site is hosted on `S3` with a document upload form. We use API Gateway to create an API which makes a GET request to a Lambda function after the user clicks  [![Upload File](https://img.shields.io/badge/Upload_File-007BFF?style=for-the-badge)](https://example.com/upload) on the form.
