# What is Variable?
In programming languages, variables are containers that hold/store value of a data.

e.g. `variable-name = value`


# What is data and data-type?
#### data refers to distinct pieces of information. on the ofer hard, data-type is a particular kind of data item, as define by the value it  can take, used or the operation can be performed on it.

## In javascript there are 7 types  of data-type available but most common are:

 **boolean type :** Represent a logical entity and can have two ***values: true*** and false
 
 **Null type :** The null type has exactly one ***value:  null***
                It means no value present by choce.
                
                
**Numeric type :** Represents number such as 10, 10.55, -20

**Undefined type :**  Represent a variable that has not been assigned any value yet.

**String type :** Represent textual data such as "Hi" "hello".  In JS we can represent string either by " "(double quote) or ' ' (single quote).


# How to write variable in Javascript

<**keyword**>   <**variable name**>   **=**   <**value**>

let myVariable = 10;

const MY-VARIABLE = 20;



**Note :** Avariable can be in two kinds ***Mutable*** and ***Immutable***.

**Mutable :** Mutable variable can change it's value

*exm:*  
- let myName = "sajeeb" <br>
let myName = "sajeeb sarkar"


**Immutable :** Immutable variable can never chang its value once assigned.

*exm:*
- const MY-NAME = "sajeeb" <br>
 MY-NAME = "sajeeb sarkar" ***error show***

so, let means mutable variable and const means immutable variable.

**Write a variable in code such as :**
*exm:*
- let cow = 'give milk'; <br> ***is called variable declaration***
 cow = 'has legs'; ***is variable manupulation***



# Type of a variable

**whene we declare a variable such as :**
- let sky = "blue";
- let age = 20;

1. the variable **age** become a numaric variable. **why?** because right now sky holds string data --->  "blue".

2. the variable **age** become a numaric variable. **why?** because age holds/stor a value of number which is numaric.

so, we can tell looking at line 1 that the ***variable sky is a type of string*** and line 2 we can call variable ***age is a type of number***



3. we can check a variable type by the folloing: <br>
- let sky = "blue"
console.log(typeof(sky)) 

***will return string***



**Note:**

## Escape chapter

We use escape charecter whene `identifire` appearse in the data. Exapmle: <br>
`"hello world i'm "feeling" good."`

here " denotes staring the string of a string but whene " apperse inside the string JS engine parse it as error to metigate this problem we use \"string/charecter\" here backslash \ is called escape charecter <br>
`"hello i'm \"sajeeb\" sarker"`

`Output :  hello i'm "sajeeb" sarkar`



**Note:**

`` backtick is a new feature is es6. We also caled it template string. We can insert variable value right inide it by:
`let X = "good";`

`let Y = 'i'm feeling ${X}'` `output: i'm feeling good`













