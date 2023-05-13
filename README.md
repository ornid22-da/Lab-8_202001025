# Lab-8_202001025
Lab 8 : Unit Testing with JUnit   
Name : Nilav Shah   
S.ID: 202001025   
Lab Exercises   

1.I created a new Java project in eclipse with name Lab8 and created a package inside it with name mypackage   
![image](https://github.com/ornid22-da/Lab-8_202001025/assets/122976431/80d2b55c-ca0d-4608-908e-cd53de548743)   
   
   
2.I then created a class with name Boa and then added the given code inside it.   
![image](https://github.com/ornid22-da/Lab-8_202001025/assets/122976431/12c27528-b192-4669-ac46-b54d963dae85)    
   
   
3.Then I created a JUnit test file for the Boa Class with name BoaTest    
![image](https://github.com/ornid22-da/Lab-8_202001025/assets/122976431/82ad0826-769e-4d9c-b1be-80b7d24babe1)     
    
    
4.Then I modified the setUp method to initialize the variables.     
     
5.Then I also implemented tests for the given two functions testIsHealthy() and testFitsInCage().     
![image](https://github.com/ornid22-da/Lab-8_202001025/assets/122976431/03ebccdf-9644-46b7-8339-5c6b7bc6aec3)
For testing thee fitsInCage() function, there is no need to write tests for both jen and ken objects as the function is same for both and the output of test cases depends only whether the given lenght is greater than,less than or equal to actual length of object.The behaviour will be similar in both cases.
    
6.Then I ran the Junit test file and all the tests are passed.There are no red bars in the output.    
![image](https://github.com/ornid22-da/Lab-8_202001025/assets/122976431/f5760a76-dc3c-4c24-bce6-233a65917552)
It can be seen that 2 out of 2 test cases have been passed.    
     
7.Then I added a new method to the Boa class with name lenghtInInches() to get the length in inches.     
![image](https://github.com/ornid22-da/Lab-8_202001025/assets/122976431/caef063d-a114-4737-b5ce-fd2a5f7170e4)
As the length of the Boa is given in feet, to convert it into inches, I had multiplied length with 12 and returned the value.    
     
8.Then I wrote another test case for this new method and ran the 3 test cases together.     
![image](https://github.com/ornid22-da/Lab-8_202001025/assets/122976431/01255261-50e0-41a0-9c61-16cb7e0f5945)
    
    
Thus, test cases have been written for the given Boa class and all the three methods have been tested with required Junit test cases.
