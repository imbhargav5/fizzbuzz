# fizzbuzz
Fizz Buzz One liner in Javascript 

    Array.apply(null, {length: 45})
    .map(Number.call,Number)
    .map((i)=>{ 
          if(i%15===0){ return 'FizzBuzz'; } 
          if(i%5===0){ return 'Buzz' ;} 
          if(i%3===0){ return 'Fizz';}   
          return i  
    });
