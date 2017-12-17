# CaptCC
A tiny C compiler written purely in JavaScript.   
It's been a while that I learned JS and it has worked for me in many different scenarios.      
I actually learned JS while analyzing a piece of malware written in JS. Then I got really interested.      
I was always curious if I can write a compiler; a tiny one. (I changed my mind. Turns out you don't need a master degree to   build one. So, I decided to really work on this compiler.)  
But there was a problem. I didn't know OCaml or Bison or Flex. I wondered why not just write it in JS?   


Parts of this project is derived from James Kyle talk at EmberConf 2016 (https://www.youtube.com/watch?v=Tar4WgAfMr4).  
I appreciate his effort to make this concept fairly easy to understand instead of writing a giant book   
which no ones's gonna read.    
He made a Lisp Compiler to convert the Lisp syntax to JS.   
I want to convert C to ASM.   

The parts below are almost complete: 

1. tokenizer.js   
2. parser.js   
3. traverser.js   
4. processor.js   

To be added and/or completed:   
   
5. verifier.js   
6. codeGenerator.js   
