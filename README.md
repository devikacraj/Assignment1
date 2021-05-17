# Assignments
#HALLOW TRIANGLE

This program will print the given below star pattern

                 *
              *     *
           *           *
        *                 *
     *  *  *  *  *  *  *  *  *

The code to obtain the above mentioned pattern:
First we have created a class for pattern and to take input from the user we used Scanner that we have to import from java object class.

          import java.util.Scanner;
          
To get the user input we use scanner

             Scanner sc=new Scanner(System.in);
             System.out.print("Enter the rows: ");
             int rows=sc.nextInt();  
             
To print each row we use this for loop

            for(int i=rows; i>=1; i--)
            
To print space for pyramid shape we use this for loop

            for(int j=rows; j>i; j--)
            System.out.print(" "); 
            
To print the star in the required position we will give conditions if the condition passes then we will get * printed or else space will be printed.            
   
             for(int k=1; k<2*i; k++){//print *
             if(i==rows || (k==1 || k==2*i-1))
            System.out.print("*"); 
             else {
            System.out.print(" ");
            
To move next line we use this line of code

          System.out.println(""); 
          
          
          
