# Deep Merge
There are 2 different datasets and you need to merge them into a single response. Write a program that accepts 2 different datasets and checks if they can merged. The output needs to be a single dataset

### Example 1
**Input DataSet 1**
Name: Ravi Kumar
Source: Provider1
Phone: 
  Mobile1: 9998887770
  Landline: 099-444123
DOB: 01-02-1990

**Input DataSet 2**
Name: Ravi Kumar
Source: Provider2
Phone: 
  Mobile2: 8887776660
  Landline: 099-444123
Address: Jayanagar, Bangalore

**Output**
Name: Ravi Kumar
Source: Combined
Phone: 
  Mobile1: 9998887770
  Mobile2: 8887776660
  Landline: 099-444123
DOB: 01-02-1990
Address: Jayanagar, Bangalore


### Example 2
**Input DataSet 1**
Name: Ravi Kumar
Source: Provider1
Phone: 
  Mobile1: 9998887770
  Landline: 099-444123
DOB: 01-02-1990

**Input DataSet 2**
Name: Ravi Kiran
Source: Provider2
Phone: 
  Mobile2: 8887776661
  Landline: 099-444123
Address: Jayanagar, Bangalore

In this example "Name" and "Mobile2" have slightly different values and hence cannot be merged directly. We need to keep them separate

**Conflicted Output**
Name: Ravi Kumar, Ravi Kiran
Source: Combined
Phone: 
  Mobile1: 9998887770
  Mobile2: 8887776660, 8887776661
  Landline: 099-444123
DOB: 01-02-1990
Address: Jayanagar, Bangalore

**Notes** Use a JSON structure for your input and output

## Final Words

When you are done, just create a pull request on this repo. We would like you to come in and present your code to the whole team.

May the force be with you!
