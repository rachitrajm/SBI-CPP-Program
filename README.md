# SBI-CPP-Program

In today’s world there is a great need for data storage. To that end, this is a rudimentary prototype for a database. Using these ideas, databases can be created which can have real-world applications.

This is a project on SBI Bank Management System which creates, modifies and deletes accounts of the customers. It manages two types of accounts savings and current. Accordingly it modifies the existing database.

### LIST Of HEADER FILES USED

#include<fstream.h>

#include<ctype.h>

#include<iomanip.h>

#include<conio.h>

#include<stdio.h>

### LIST OF FUNCTIONS USED

void create_account();		      //function to get data from user

void show_account();		        //function to show data on screen

void modify();          	      //function to get new data from user

void dep(int);  			          //function to accept amount and add to balance amount

void draw(int);			            //function to accept amount and subtract from balance amount

void report();			            //function to show data in tabular format

int retacno();			            //function to return account number

int retdeposit();			          //function to return balance amount

char rettype();                 //function to return type of account

void write_account();		        //function to write record in binary file

void display_sp(int);		        //function to display account details given by user

void modify_account(int);	      //function to modify record of file

void delete_account(int);       //function to delete record of file

void display_all();	            //function to display all account details

void deposit_withdraw(int, int);// function to desposit/withdraw amount for given account

void intro();

### SUGGESTIONS FOR FURTHER IMPROVEMENTS

It could have more details on the accounts like people’s birth date, last transactions, phone number and address details etc. It could have management of transaction system like depositing and withdrawing cheques. It could have a function for the updation of the profile of a user.
