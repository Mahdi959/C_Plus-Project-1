CS132 – Computer Science II  
Spring 2022  
Mr. MacKay  
Project 1 – due Monday, February 28th , at the beginning of class.

**General Description**:

A rational number is of the form a/b, where a and b are integers, and b is not equal 0.  Develop and test a class for processing rational numbers. 
Details:

1. Your program should have 3 files: a driver file to test the operations, a header file for the class definition and any operator overloads you need, and an implementation file with the definitions of the items in the header file.
    
2. Your program should have 3 files: a driver file to test the operations, a header file for the class definition and any operator overloads you need, and an implementation file with the definitions of the items in the header file.
    
    - except when b is 1, then it should just display a
    - or when b is 0, then it should display #div0
    - all results should be reduced to lowest terms
        

             i.  (i.e., 2/4 should be displayed as 1/2)

3. The operations that should be implemented for the rational numbers are:
     
     ![Alt text](./extra/table.jpg "Example Table")


4. All the operators must be overloaded to work with the class

5. The class must have
    - At least 2 private member variables, numerator and denominator
    - At least 4 public member functions
        
          i. getNum(), getDen(), setNum(value), setDen(value)

6. You must have internal documentation:
                                      
        1. See the handout on Documentation Standards    