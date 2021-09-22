# let-us-c-4
Q.(d) Temperature of a City in Fahrenheit degree is input through the keyboard. Write a program to convert this temperature into centigrade degree.


      
       #include <stdio.h>
       int main()
     {
	        float F,C;
	        printf("enter the fahrenheit temperature of city=",F);
          scanf("%f",&F);
  
          C=((F-32)*5)/9;
          printf("temperature in centigrate=%f",C);
    
      return 0;
	    }
