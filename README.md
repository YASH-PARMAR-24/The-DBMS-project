                                                                             # The-DBMS-project
Write a program in c++ to built a Student Database Management System

                                                                             HEADERFILES USED
#include <iostream>
#include <stdio.h>
#include <string.h>
#include <stdlib.h>
#include <conio.h>
#include <iomanip>
  
                                                                             THINGS USED IN PROGRMMING 
                                                                          
                                                                          -> POINTER
                                                                          ->STRUCTURE
                                                                          ->TEXT FILE
                                                                          ->SWITCH CASE 
                                                                          
                                                                            WHAT ARE POINTERS ?
                                                                            
   Pointer is a variable in C++ that holds the address of another variable. They have data type just like variables, for example an integer type pointer can hold the address of an integer variable and an character type pointer can hold the address of char variable.                                                         
                                                                             USE OF POINTERS
       
  *fp and *ft are the two pointers used in this progeam -
       
   FILE *fp, *ft;
    char another, choice;
   
                                                                             WHAT ARE STRUCTURE ?
                                                                             
  Structure is a collection of variables of different data types under a single name. It is similar to a class in that, both holds a collecion of data of different data types.
  
  
                                                                             USE OF STRUCTURE        
   
   struct student {
        char first_name[50], last_name[50];
        char course[100];
        int section;
    };

   struct student e;
    char xfirst_name[50], xlast_name[50];
    long int recsize;

   fp=fopen("users.txt","rb+");

   if (fp == NULL) {
        fp = fopen("users.txt","wb+");

   if (fp==NULL)
        {
             puts("Cannot open file");
             return 0;
        }
   
   
                                                                   WHAT IS A TEXT FILE ?
                                                                   
   A text file is a file containing data you wish to use in your program. A text file does not contain any C++ declarations or statements – just the data. Enter the CodeWarrior editor and create your text file.                                                           
                                                               USE OF TEXT FILE
                                                             
                                                               
  fp=fopen("users.txt","rb+");

if (fp == NULL) {
        fp = fopen("users.txt","wb+");

  if (fp==NULL)
        {
             puts("Cannot open file");
             return 0;
        }                                               
           
                                                                 SWITCH CASE 
                                                                 
 A switch statement allows a variable to be tested for equality against a list of values. Each value is called a case, and the variable being switched on is checked for each case                                                             
                                                                  
                                                                USE OF SWITCH CASE
                                                                
   switch(expression) {
   case constant-expression  :
      statement(s);
      break; //optional
   case constant-expression  :
      statement(s);
      break; //optional
  
   // you can have any number of case statements.
   default : //Optional
      statement(s);
}                 

This is relatable with the context of the program 
