let num = 233;

let result

if (result ===0){
    console.log("num is even")}
else console.log("num is odd")

result = num%2===0? "Even" : "Odd"
console.log(result); 

//--------------------------------------

let day = "Thursday"

if (day==="Monday"){
    console.log("Wake up at 7am")
}
else if(day==="Tuesday" || day==="Wednesday" || day==="Thursday"){
    console.log("Wake up at 4 am")
}
else if (day==="Friday"){
    console.log("Wake up at 9 am")
}
else if(day==="Saturday" || day==="Sunday"){
    console.log("Wake up at 8 am")}

for(let i=0;i<100;i++){
    if(i%3===0){
        console.log([i]);
    };
}

//-----------------------------------------------

let num1 = 564782
let num2 = 0

while(num1>0){
    let remainder=num1%10;
    num1=parseInt(num1/10)
    num2=String(num2+remainder);//puts the result together as a string
}
// console.log(Number(num2)); //converts shows string num2 as number */

//----------------------------------------------------

//for in loop js
let alien = {
    name: 'Navin',
    tech: 'JS',
    laptop: { 
        cpu: 'i7',
        ram: 4,
        brand:'Asus',
        make: 'India'
    }
}

for (let key in alien.laptop){
    console.log(key,alien.laptop[key]);
}

//--------------------------------------------------

