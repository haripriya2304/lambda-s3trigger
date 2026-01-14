# lambda-s3trigger
# AWS Lambda CSV Processing Project ☁️

## 📌 Project Overview
This project demonstrates a **simple serverless application using AWS Lambda and Amazon S3**.  
The Lambda function reads a **CSV file stored in an S3 bucket**, processes the data, and returns the output in **JSON format** using a **Lambda Function URL**.

The purpose of this project is to understand **serverless computing basics**, IAM permissions, and how AWS services interact without managing servers.

---

## 🛠️ Technologies Used
- **AWS Lambda** – Serverless compute
- **Amazon S3** – Storage for CSV file
- **Python 3.x** – Lambda runtime
- **IAM** – Access control
- **boto3** – AWS SDK for Python

---

## ⚙️ How the Project Works
1. A CSV file is uploaded to an **Amazon S3 bucket**
2. An **AWS Lambda function** is created using Python
3. The Lambda function:
   - Reads the CSV file from S3
   - Converts CSV rows into JSON format
4. The output is returned via a **Lambda Function URL**
5. No server management is required (serverless)

---

## 📂 Project Structure 
├── lambda_function.py   # Lambda function code ├── sample.csv           # Sample CSV file ├── README.md            # Project documentation

---

## 🔐 IAM Permissions Required
The Lambda execution role must have permission to read the CSV file from Amazon S3.

---

## 🌐 Lambda Function URL
The Lambda function is exposed using a **https://hus43qb6xow7bv2rztulv5bhf40crjzi.lambda-url.ap-south-1.on.aws/**.

---

## 🚀 How to Run / Test
1. Upload a CSV file to Amazon S3  
2. Deploy the Lambda function  
3. Verify IAM permissions  
4. Open the Lambda Function URL in a browser or Postman  
5. View the JSON output  

---

## 📘 What I Learned
- Basics of serverless architecture  
- How AWS Lambda works internally  
- Importance of IAM permissions  
- Reading and processing files from Amazon S3  
- Debugging common AWS errors like `AccessDenied`  

---

## 🔮 Future Improvements
- Add API Gateway  
- Filter or validate CSV data  
- Store data in DynamoDB  
- Improve error handling  
- Support large CSV files  

---

## 👩‍💻 Author
Haripriya Venkatesh

---

## 📄 License
This project is created for learning and educational purposes.
