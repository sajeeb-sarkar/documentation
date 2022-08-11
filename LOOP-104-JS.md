# LOOP
```
A.                                                                                    B.
♦♦♦♦♦ --> suger cubes                                                                   ♦♦♦♦♦♦♦♦♦♦
♦♦♦♦ ♦ 🐜🐜🐜♦🐜🐜🐜🐜🐜🐜🐜🐜♦🐜🐜🐜🐜🐜♦🐜🐜🐜🐜🐜♦🐜🐜🐜♦🐜🐜🐜♦🐜🐜🐜♦♦♦♦♦♦♦♦♦♦ <---sugger cubes
♦♦♦                            ^ant^                                                    ♦♦♦♦♦♦♦♦♦♦
```

Lets say this ant take a suger cube from A and place it in B this process contanues until no suger cube <br> left in A now imagine this process as loop.
Which is repeating somthing over and over until we as a <br> programmer tell it no to.

## while loop
```
    <keyword> <expression/value> {
      //code block
     }
    
     let i = 0
     while(i <= 10) {
      console.log(i)
      i++
     }
 ```
## For loop
```
  for(let i = 0 (variable); i <= 10 (condition); i++/i-- (incriment/decriment)) {
    console.log(i)
  }
```
## continue/break
```
    for(let i = 0; i <= 10; i++){
        if( i === 5 ) {
            console.log("ok")
            
            continue/break
        }
        
        console.log("no ok")
    }
 ```
 **continue:** if you use continue in condition, the loop will print for 5 inside of if condition console.log("ok") and continue for 6,7,8,9,10 
 
 **Break:** if use break in condition, the loop will stop execute after 5. it will never loop for 6,7,8,9,10
