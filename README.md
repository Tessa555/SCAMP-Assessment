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

/* Print fiboancci series upto 12 elements. */  
num = 12;  
document.writeln("<h3>Fibonacci series using recursive function: </h3>")

/* Recursive function for fibonacci series. */  
function series(num){  
    if(num == 0){  
    return 0;  
    }else if( num == 1){  
return 1;  
}  else {  
return (series(num-1) + series(num-2));  
}   
}  
/* Call Function. */  
for (i = 0; i < num; i++){  
document.writeln(series(i));  
}

#Java

class FibonacciExample1{
public static void main(String args[])
{  
 int n1=0,n2=1,n3,i,count=10;  
 System.out.print(n1+" "+n2);//printing 0 and 1  
  
 for(i=2;i<count;++i)//loop starts from 2 because 0 and 1 are already printed  
 {  
  n3=n1+n2;  
  System.out.print(" "+n3);  
  n1=n2;  
  n2=n3;  
 }  

}}
