# marchmonth
/*Assignment 1
**Create 4 functions for addition,subtraction,multiplication,division
*/

function sum(num1,num2){
	
	let result = num1+num2;
	return result
}
function sub(num1,num2){
	
	let result = num1-num2;
	return result
}
function mul(num1,num2){
	
	let result = num1*num2;
	return result
}
function div(num1,num2){
	
	let result = num1/num2;
	return result
}

t = sum(7,8);
console.log(t)
u = sub(9,7);
console.log(u)
v = mul(15,12);
console.log(v)
w = div(12,02);
console.log(w)

/*assignment 2
******create (a+b)square2 function
*/


let squaredNumber = Math.pow(5,2);
console.log("5*5 = ",squaredNumber);

let variable = 5 ;
let squaredNumber2 = Math.pow(variable,2);
console.log("5*5 = ",squaredNumber2);



/* Assignment 3
*****print fibonacci series
*/


function fibonacci(num){
  let n1=0,n2=1,n3,i    
   console.log("Fibonnacci:")        
   console.log(n1,n2) //printing 0 and 1    
   for(i=2;i<num;++i) //loop starts from 2 because 0 and 1 are already printed    
   {    
    n3=n1+n2;    
    console.log(n3)    
    n1=n2;    
    n2=n3;    
   }    
  }
    fibonacci(10); //calling of fibonnacci
