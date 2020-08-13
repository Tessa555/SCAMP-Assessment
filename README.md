# SCAMP-Assessment
Code submition for SheCode Africa
# let the function be called fibonacci
# Python 
def fibonacci(i):
    if i==0:
        return 0
    elif i==1:
        return 1
    else:
       return fibonacci (i-2) + fibonacci (i-1)
    
# I choose 24 as my unique number
for n in range(24):
    print (fibonacci(n))

#Php

<?php  
/* Print fiboancci series upto 12 elements. */  
$num = 12;  
echo "<h3>Fibonacci series using recursive function:</h3>";  
echo "\n";  
/* Recursive function for fibonacci series. */  
function series($num){  
    if($num == 0){  
    return 0;  
    }else if( $num == 1){  
return 1;  
}  else {  
return (series($num-1) + series($num-2));  
}   
}  
/* Call Function. */  
for ($i = 0; $i < $num; $i++){  
echo series($i);  
echo "\n";  
}


#Javascript
function F(n) {  if(n == 0) {    return 0;
 }  if(n == 1) {    return 1;
 }  else {    return F(n-1) + F(n-2);
 }}

#Java
public static int F(int n) {  if(n == 0) {    return 0;
 }  if(n == 1) {    return 1;
 }  else {    return F(n-1) + F(n-2);
 }}


