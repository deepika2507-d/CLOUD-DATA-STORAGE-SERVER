# CLOUD-DATA-STORAGE-SERVER
CLOUD DATA STORAGE SERVER

REG NO : 212224240030
NAME : DEEPIKA V
AIM
To create and configure an Amazon RDS MySQL DB instance with Multi-AZ deployment, connect it to a web application using a security group and DB subnet group, and perform CRUD (Create, Read, Update, Delete) operations on the database through the application.

ALGORITHM
1.Log in to the AWS Management Console.
2.Create a DB Security Group allowing MySQL (3306) access from the Web Security Group.
3.Create a DB Subnet Group with subnets in two Availability Zones.
4.Launch an Amazon RDS MySQL Multi-AZ DB instance.
5.Configure the DB instance with the required username, password, and database name. Wait until the database status becomes Available and copy the endpoint.
6.Open the provided web application using the Web Server IP.
7.Enter the RDS endpoint, database name, username, and password.
8.Connect the application to the database.
9.Test the application by adding, editing, viewing, and deleting records.

OUTPUT

<img width="602" height="524" alt="image" src="https://github.com/user-attachments/assets/f7c14900-8ef4-4734-a4b1-ac9a5dca9eaa" />

<img width="600" height="523" alt="image" src="https://github.com/user-attachments/assets/270ef79c-7bff-486d-8e80-2cda6902586b" />

<img width="602" height="581" alt="image" src="https://github.com/user-attachments/assets/6b307e44-4f3a-40b1-afc0-e5a718c9cfbf" />

<img width="598" height="520" alt="image" src="https://github.com/user-attachments/assets/db1ab7a0-ebab-4e7f-8e58-4c2f853ab072" />


<img width="599" height="570" alt="image" src="https://github.com/user-attachments/assets/2650d135-beef-4a84-a18b-9678f75a0493" />

<img width="1011" height="596" alt="image" src="https://github.com/user-attachments/assets/77cd8ab4-05cd-4e65-8dbe-3fda0c6c060d" />



RESULT
The Amazon RDS MySQL Multi-AZ DB instance was successfully created and connected to the web application, and CRUD operations were performed successfully on the database.
