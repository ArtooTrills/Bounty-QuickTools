# Task 1: Deep Merge
There are 2 different datasets and you need to merge them into a single response. Write a program that accepts 2 different datasets and checks if they can merged. The output needs to be a single dataset

### Example 1
**Input DataSet 1**
```
Name: Ravi Kumar
Source: Provider1
Phone: 
  Mobile1: 9998887770
  Landline: 099-444123
DOB: 01-02-1990
```

**Input DataSet 2**
```
Name: Ravi Kumar
Source: Provider2
Phone: 
  Mobile2: 8887776660
  Landline: 099-444123
Address: Jayanagar, Bangalore
```

**Output**
```
Name: Ravi Kumar
Source: Combined
Phone: 
  Mobile1: 9998887770
  Mobile2: 8887776660
  Landline: 099-444123
DOB: 01-02-1990
Address: Jayanagar, Bangalore
```

### Example 2
**Input DataSet 1**
```
Name: Ravi Kumar
Source: Provider1
Phone: 
  Mobile1: 9998887770
  Landline: 099-444123
DOB: 01-02-1990
```
**Input DataSet 2**
```
Name: Ravi Kiran
Source: Provider2
Phone: 
  Mobile2: 8887776661
  Landline: 099-444123
Address: Jayanagar, Bangalore
```
In this example "Name" and "Mobile2" have slightly different values and hence cannot be merged directly. We need to keep them separate

**Conflicted Output**
```
Name: Ravi Kumar, Ravi Kiran
Source: Combined
Phone: 
  Mobile1: 9998887770
  Mobile2: 8887776660, 8887776661
  Landline: 099-444123
DOB: 01-02-1990
Address: Jayanagar, Bangalore
```

**Note** 
- Use a JSON structure for your input and output
- Your program should run for any kind of data structure
- Do not use any libraries

# Task 2: User details
Create a schema in MySQL that captures employee details, 

- employee basic details - employee_id, name, phone, email
- employee designation - designation title, designation start_date, designation end_date
- office location - loaction_id, location address

- employee offices - employee_id, office_location_id
- employee login - employee_id, office_location_id, login_time

Write a script which takes employee_id as an input parameter and shows all details for that employee - name, phone, designation, login_time and office_location address of login

**Note** 
- Write your program in node.js or python
- Do not use any libraries. Your script should run a terminal command

## Final Words

When you are done, just create a pull request on this repo. We would like you to come in and present your code to the whole team.

May the force be with you!
