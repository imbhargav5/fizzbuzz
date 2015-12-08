# fizzbuzz

The "Fizz-Buzz test" is an interview question designed to help filter out the 99.5% of programming job candidates who can't seem to program their way out of a wet paper bag. The text of the programming assignment is as follows:
"Write a program that prints the numbers from 1 to 100. But for multiples of three print “Fizz” instead of the number and for the multiples of five print “Buzz”. For numbers which are multiples of both three and five print “FizzBuzz”."

Fizz Buzz One liner in Javascript. 

This snippet returns an array containing an array of length 100 and Fizz,Buzz and Fizzbuzz have replaced the numbers which are multiples of 3,5 and 15.

    Array.apply(null, {length: 100})
    .map(Number.call,Number)
    .map((i)=>{ 
          if(i%15===0){ return 'FizzBuzz'; } 
          if(i%5===0){ return 'Buzz' ;} 
          if(i%3===0){ return 'Fizz';}   
          return i  
    });
