//  TODO: <<<<<<<print the value of a&b<<<<<<<<<< 

 
// #include<stdio.h>

// int main() {
//     int a;
//     int b;
//     printf("enter the value of a : ");
//     scanf("%d", &a);
//     printf("enter the value of b  :");
//     scanf("%d", &b);
//     printf("the value of a is %d\n", a);  
//     printf("the value of b is %d", b);  
//     return 0;
// }

//  TODO: >>>>>>>>>>>>>>>>>how to print the size of format specifier<<<<<<<<<<<<<<

// #include<stdio.h>

// int main() {
//     int integer;
//     char character;
//     float floating ;
//     double doub;
//     printf("the size of integer is %d\n", sizeof(integer)); 
//     printf("the size of character is %d\n", sizeof(character));
//     printf("the size of floating is %d\n", sizeof(floating));
//     printf("the size of doub is %d\n", sizeof(doub));

//     return 0;
// }   

// FIXME: >>>>>>>>>>>>>>>>swap two number<<<<<<<<<<<<<<<<<<<<<

// #include<stdio.h>

// int main() {
//     int first,second ,temp;
//     printf("enter the value of first : ");
//     scanf("%d",&first);
//     printf("enter the value of second : ");
//     scanf("%d",&second);    
    
//      temp=first;
//      first=second;
//      second=temp;
//     printf("the value of first is %d\n and second is %d",first,second);
    
     
//     return 0;
// }

// FIXME: <<<<<<<<<HOW TO CONVERT INTEGER TO FLOAT ANY NUMBER >>>>>>>>>>>>>>>   

// #include<stdio.h>

// int main() {
//     int number;
//     printf("enter the value of number : ");
//     scanf("%d",&number);

//     double doub = number;
//     printf("\n original number is : %d", number);
//     printf("\n converted number is : %f", doub); 
//     // another to type here: float    
//     printf("\n converted number is : %f", (double)number);
//     return 0; 
// }
// //FIXME:  question 6 -- check compound interset

// #include<stdio.h>
// #include<math.h>

// int main() {
//     float principal,rate,time;
//     printf("Enter the principal value : ");
//     scanf("%f", &principal);

//     printf("Enter the rate value : ");
//     scanf("%f", &rate);
 
//     printf("Enter the time value : ");
//     scanf("%f",&time);
//     printf("the value of compound intrest is %f ", principal * (pow((1 + rate / 100), time))); 
    
//     return 0;
// }

// FIXME: question 6 -- check   odd or even or negative&positive

// #include<stdio.h>

// int main() {
//     int number;
//     printf("enter the value of number : ");
//     scanf("%d",&number);

//     if(number>0,number % 2 == 0){
//         printf("the number is positive and number is even");
//     }
//     else if(number<0,number % 2 != 0){
//         printf(" the number is negative and the number is odd");   
//     }
     
     
//     return 0;
// }

//  TODO: Leap Year Yes or Not

// #include<stdio.h>

// int main() {
//     int year;
//     printf("enter the value of year : ");
//     scanf("%d",&year);

//     if(year % 400 == 0){
//         printf("%d is a Leap Year ",year);
//     }   
//     else if(year % 100 == 0){
//         printf("%d is not a Leap Year ",year);
//     }
//     else if(year % 4 == 0){
//         printf("%d is a Leap Year ",year);
//     }
//     else{
//         printf("%d is not a Leap Year ",year);
//     }
//     return 0;
// } 

//  TODO: percentage calculator on your subjectwise  -->>... check 

// #include<stdio.h>

// int main() {
//     int physics,chemistry,math,english,hindi;
//     float total;

//     printf("enter your physics marks\n");
//     scanf("%d",&physics); 

//     printf("enter your chemistry marks\n"); 
//     scanf("%d",&chemistry);

//     printf("enter your math marks\n");
//     scanf("%d",&math);
    
//     printf("enter your english marks\n");
//     scanf("%d",&english);

//     printf("enter your hindi marks\n");
//     scanf("%d",&hindi);

//     total = (physics+chemistry+math+english+hindi) / 5;
    
//     if((total<40) || physics < 33 || chemistry < 33 ||math < 33 ||english < 33 || hindi < 33) 
//     {
//         printf(" your total percentage is %f and you are fail",total );
//     }
//     else{
//         printf(" your total percentage is %f and you are pass",total );
//     }
//     return 0;
// }

// TODO:  print the month and get name of month on the entering the number

// #include<stdio.h>

// int main() {
//     int month;
//     printf("enter the value of month : ");
//     scanf("%d",&month);
//     switch (month)
//     {
//         case 1: printf("january");
//           break;
//         case 2: printf("february");
//           break;
//         case 3: printf("march");
//           break;
//         case 4: printf("april");
//           break;
//         case 5: printf("may");
//           break;
//         case 6: printf("june");
//           break;
//         case 7: printf("july");
//           break;
//         case 8: printf("august");
//           break;
//         case 9: printf("september");
//           break;
//         case 10: printf("october");
//           break;
//         case 11: printf("november");
//           break;
//         case 12: printf("december");
//           break;
//         default: 
//           printf("invalid month please enter btw (1-12)");
//           break; 
//     }
//     return 0;
// }


       
  
