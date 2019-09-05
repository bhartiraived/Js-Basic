# Js-Basic
#Javascrict basic


let str1="John"; //this create a String
let str2=new String("Bharti");//this creates an object
let str3=new String("Bhumi");//this creates another object

console.log(typeof(str1));
console.log(typeof(str2));
//Dynamic datatypes in JavaScript
var x;           // Now x is undefined
x = 5;           // Now x is a Number
x = "John";      // Now x is a String

//Events in JavaSCripts
function displayDate(){
    document.getElementById('demo').innerHTML=Date();
}

//SOme fact
var x = 16 + 4 + "Volvo";//results in 20Volvo
var x = "Volvo" + 16 + 4;//results in Volvo20
                        //since the first operand is a string,
                        //all operands are treated as strings.
                        
