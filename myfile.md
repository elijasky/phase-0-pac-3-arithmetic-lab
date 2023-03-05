function add(a,b){
    return a + b
}

function subtract(a,b){
    return a - b;

}

function multiply(a,b){
    return a * b;
}

function divide(a,b){
    return a / b;
}

const additionMessage = add(539,539)

console.log(additionMessage);

let n = 5;

function increment(n){
    return ++n
}

let incremation = increment(831);

console.log(incremation);

function decrement(n){
    return --n
}

function makeInt(n){
    return parseInt(n,10);
   }
   
   let numParseInt = makeInt("2");
   
   console.log(numParseInt);

   function preserveDecimal(n){
    return parseFloat(n,10);
  }
  
  let presDeci = preserveDecimal("2.3433");
  
  console.log(presDeci);