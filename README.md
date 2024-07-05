# ES6 Javascript Assignment

## One
```
let age=30;
const name="Alice";
 name="bob";
 console.log(name)

```
## Output
![image](https://github.com/AshikaJubi/javascript/assets/129098066/affc537d-5124-4bf4-a5c3-0949948f8dc8)

## Two
```
const add=(a,b)=>{
    console.log(a+b) ;
}
add(9,11);


```
## Output
![image](https://github.com/AshikaJubi/javascript/assets/129098066/b7ff9f17-6bcc-4387-9f67-93f69421e9f5)



## Three
```
let name="Alice";
let age=30;
let txt=`Hello,${name} Your age is ${age}.`;
console.log(txt);

```
## Output

![image](https://github.com/AshikaJubi/javascript/assets/129098066/9113b391-0f33-4579-9535-eff6eb84c4d3)


## Four
```
const person={
    firstName: "Alice", 
    lastName: "Johnson"
}
const{firstName,lastName}=person;
console.log(firstName);
console.log(lastName)

```
## Output

![image](https://github.com/AshikaJubi/javascript/assets/129098066/6b96bb38-8d92-4ca9-90dc-f681e6ed934b)

## Five
```
const numbers = [1, 2, 3, 4, 5];

const [first, second] = numbers;

console.log(first);  
console.log(second);

```
## Output
![image](https://github.com/AshikaJubi/javascript/assets/129098066/4d9c4cf7-2d70-43d5-a726-ea9a3ad1a22e)


## Six
```
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];

const combined = [...arr1, ...arr2];

console.log(combined);

```
## Output

![image](https://github.com/AshikaJubi/javascript/assets/129098066/f86a9a92-8ac9-4e51-86a3-9467d6f232b6)


## Seven
```
const sum = (...numbers) => numbers.reduce((acc, current) => acc + current, 0);

console.log(sum(1, 2, 3, 4, 5)); 
console.log(sum(50, 40));        
console.log(sum());

```
## Output

![image](https://github.com/AshikaJubi/javascript/assets/129098066/663780b0-ff48-4543-8777-aff63449a766)


## Eight
```
const greet = (name, greeting = "Hello") => `${greeting}, ${name}!`;

console.log(greet("Alice"));          
console.log(greet("Bob", "Hi"));      
console.log(greet("Charlie", "Hey"));

```
## Output

![image](https://github.com/AshikaJubi/javascript/assets/129098066/d6569d73-0789-4e58-b047-7f7d6b112ac2)

## Nine
```

class Animal {
    constructor(name) {
      this.name = name;
    }
  }
  
  class Dog extends Animal {
    bark() {
      return `Woof! My name is ${this.name}`;
    }
  }
  
  const myDog = new Dog('Julie');
  console.log(myDog.bark());


```
## Output


![image](https://github.com/AshikaJubi/javascript/assets/129098066/92a90ace-8481-45f8-ab8e-56f7d8a5cfce)


## Ten
```
const waitAndReturn = () => 
    new Promise(resolve => setTimeout(() => resolve("Done"), 2000));
  
  async function run() {
    const result = await waitAndReturn();
    console.log(result); 
  }
  
  run();

```
## Output

![image](https://github.com/AshikaJubi/javascript/assets/129098066/c581b89a-109d-4ddf-8b03-f23921972d75)


