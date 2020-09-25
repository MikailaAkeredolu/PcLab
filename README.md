# EmployeePieLab


Creating a payroll system (UML must be approved by Mikaila before you code)

### Part 1a - Create the following classes:
- Person
- Employee
- SalariedEmployee
- HourlyEmployee
- Entrepreneur
- HumanResources
- HireDate
- CheckCashingPlace
### Part 1b - Create the following interface:
- IPayable

### Part 2 - Things Objects have
- Every Person has a name
- Employees and Entrepreneurs are people
- Employees have an HireDate
- HireDate has a month, date and year that are all text
- SalariedEmployees have a salary
- HourlyEmployees have hourlyRate and HoursWorked

### Part 3a - Things Objects can do
- There should be a method to **printBadge()** for any type of Employee in this format. 
- There should be a way to **calculatePay()** for all types of people (Employees and Entrepreneurs)
<pre><code>
Name: James
Type of employee: SalariedEmployee
HireDate: 2/30/2020

Name: Mike
Type of employee: HourlyEmployee
HireDate: 3/19/1999
</pre></code>

**In the HumanResources Class, there should be methods that can:**
- **issueBadge(which takes an array of Employees)** and prints each employees badge
- **printPaymentInfo(Takes a payable person)** and prints out their payment information
- **payPerson(which takes an array of people that are payable)** and prints their payment info
<pre><code>
Prior to sorting people by pay....
SalariedEmployee should be paid : 1000.0
HourlyEmployee should be paid : 400.0
Entrepreneur should be paid : 20000.0
</pre></code>

### Part 3b - Implement a custom way and method
**sortPeopleByIncome(which takes an ArrayList of people that are payable)**
- Then sorts them by pay and print outs their paymentInfo after sorting them
<pre><code>
After sorting people by pay...
HourlyEmployee should be paid : 400.0
SalariedEmployee should be paid : 1000.0
Entrepreneur should be paid : 20000.0
</pre></code>


### Part 4 - In the CheckCashing class (PSVM) do the following:

- Create an Entrepreneur, Salaried andHourly Employee objects
- Create an instance of the HumanResources class


- Create an array of people that are Payable
- Create an array of Employees that are payable

- Invoke the issueBadge method that takes an array of  employees

- Print out the text - “Prior to sorting by pay..”
- Invoke the payPerson method that takes an array of  people

- Initialize a new  ArrayList of payable People called unSortedPeople;
- Add your Entrepreneur Object plus the  Salaried and Hourly Employee instances to your list.

- Print out a blank line

- Finally, invoke your sortPeopleByIncome method which accepts your list of unsortedPeople

**Final Output once done should look like like this**

<pre><code>
Name: James
Type of employee: SalariedEmployee
HireDate: 2/30/2020
 
Name: Mike
Type of employee: HourlyEmployee
HireDate: 3/19/1999
 
Prior to sorting by pay...
SalariedEmployee should be paid : 1000.0
HourlyEmployee should be paid : 400.0
Entrepreneur should be paid : 20000.0

After sorting by pay...
HourlyEmployee should be paid : 400.0
SalariedEmployee should be paid : 1000.0
Entrepreneur should be paid : 20000.0
</pre></code>

### Part 5 - You must now system out:
- I freakin killed it then take a nice lil 30 minute break once your code has been reviewed by Mikaila





