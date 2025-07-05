# Stock Market Kafka Real Time Data Engineering Project

## Introduction 
In this project, you will execute an End-To-End Project on Real-Time Stock Market Data using Kafka.

We are going to use different technologies such as **Python**, **Amazon Web Services (AWS)**, **Apache Kafka**, **Glue**, **Athena**, and **SQL**.

## Architecture 
![Architecture Diagram](./assets/Arch_diagram.png)

## 🛠️ Technology Used

- **Programming Language**: **Python**

- **Amazon Web Services (AWS)**:
  1. **S3 (Simple Storage Service)**
  2. **Athena**
  3. **Glue Crawler**
  4. **Glue Catalog**
  5. **EC2**

- **Apache Kafka**

## 🚀 Step 1: Setting Up EC2 Instance

- Launch an **Amazon EC2** instance using the **t2.large** instance type (Amazon Linux 2).
- Configure the **security group**:
  - Allow **All traffic** (inbound and outbound) — for development/testing purposes only.
  - Make sure port `22` (SSH) is open so you can connect.

 ![EC2_machine Diagram](./assets/ec2.png)

## 📦 Step 2: Download and Extract Kafka

- Download the Kafka binary:
  ```bash
  wget https://downloads.apache.org/kafka/3.7.2/kafka_2.12-3.7.2.tgz
  tar -xvf kafka_2.12-3.7.2.tgz
  ```

 ![Download_and_untar](./assets/download_the_kafka.png)

## ☕ Step 3: Install Java

Kafka requires Java to run. Use the following commands to install and verify Java on your EC2 instance:

```bash
# Check if Java is already installed
java -version

# Install OpenJDK 1.8
sudo yum install java-1.8.0-openjdk -y

# Verify Java installation
java -version
```





## Dataset Used
You can use any dataset, we are mainly interested in operation side of Data Engineering (building data pipeline) 

Here is the dataset used in the video - https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv


## Complete Video Tutorial 

Video Link - https://www.youtube.com/embed/KerNf0NANMo
