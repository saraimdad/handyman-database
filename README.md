### Project Overview

Handyman is a database connected to a website designed for a fictional company, with the primary goal of offering handyman services within a city. The company aims to bridge the gap between the demand and supply of these services, ultimately enhancing the lives of local residents.

Clients have the option to submit their service requests, specifying the type of service needed, either through the company website or by making a phone call, which is then directed to the relevant department. Subsequently, the department manager assigns the task to the appropriate employees, who are dispatched to the client's location. Once the job is completed, the assigned employees generate a bill based on the standard pricing for the provided service(s). Payments for the bill can be made to the company through various methods, including cash, easy-paisa, or bank transfer. An accountant is responsible for tracking payments and generating employee salaries.

### Project Requirements

- Establish distinct departments for each service.
- Assign a manager, accountant, and workers to each department.
- Enable clients to submit service requests.
- Implement a managerial approval process for each service.
- Ensure that an accountant generates a bill for each service.
- Allow for multiple payments to be associated with each bill.
- Incorporate a client feedback system.

### Database Overview
#### Tables
- Company
- Department
- Employee
- Manager
- Accountant
- Worker
- TypeOfPay
- EmployeeSalary
- Clients
- Services
- Payments
- PaymentVerification
- Orders
- OrderHasServices
- WorkersOnOrder
- MethodOfPayment
- Feedback

#### Relational Model
<p align="center" width="100%"><img width="554" src="https://github.com/saraimdad/handyman-database/assets/157117492/b0b4c0a8-325a-4170-8c3f-4b8b006bedde"></p>


#### Queries
- What are is the address of each branch of the company?
- How many departments are there in handyman?
- How many workers work in each department?
- List all the services provided by each department in handyman.
- What are the basic pay of services provided by each department?
- Extract all the feedbacks given to employee along with the department name and work description to check the overall performance of the company.
- What is the average rating of each employee who works in the company?
- Who is the highest rated employee? (for bonus)
- What is the contact information of to the clients who have not made a single order yet? (to give them disconut etc.)
- Who is the most active client and the number of orders they made?
- From which area were the most orders received? (for advertisement campaign etc.)

- What is the base pay and bonus pay rate of each employee post?
- What is the base pay, bonus pay and extra bonus (for employees having rating above 4.8) of each employee?
- Who is the highest paid employee and what is their department name?
- List all payment details with service description.
- What is the total payment budget of the company?

### Conclusion
In conclusion, the Handyman database not only ensures data security but also minimizes redundancy. Furthermore, it maintains comprehensive records of employees, clients, and client-generated service orders. The database includes a system for assessing worker performance through client feedback and also manages employee salaries. Lastly, it facilitates seamless data retrieval and insertion, contributing to the overall efficiency of the system.
