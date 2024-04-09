# JavaScript and Typescript

## Javascript 
|Javascript|
|-|
|Javascript is Protoype based programming language|
|JavaScript doesn't require the explicit declaration of the variables before they're used.|

## Typescript 
|Typescript|
|-|
|TypeScript is referred to as an Object-oriented programming language|
|`JavaScript  + More features = Typescript`|


``` javascript
var person = {"name" : "Harsha", "age" : 26}

console.log(person.name);
```


### Class
Class is a template which contains 
1. attributes : defines property of class `For Person, name and age are the attributes`
2. methods: functions which can change the attribute values `For Person, increaseAge(age) is a method`
3. contructor: Is used to create object of a class.    ` For person, to create a person named Harsha with age 26 = new Person("harsha", 26)` 

``` typescript
var person =  {"name" : "Harsha", "age" : 26};
// error not type found

var person: {name: string, age: number} =  {"name" : "Harsha", "age" : 26};



class Person {
    // attributes
    name: string;
    age: number;

    // constructure
    constructor(name: string, age: number) {
        this.name = name;
        this.age = age;
    }

    // member functions
    function getName(): string {
        return this.name;
    }

    function getAge(): number {
        /*
        let gAge: number = this.age;
        return gAge;
        */
        return this.age;
    }

    function setNameWithInitials(name: string, initial:string) {
        this.name = initial + " " + name;
    }
}


// create a person name : Bob age 10
let bPerson: Person = new Person("Bob",10);
let b2Person: Person = new Person(bPerson.getName(), bPerson.getAge()); // coping the name and age. 

```
# Creating React Project

- Open cmd/terminal/powershell.
- Check if node and npm installed. If not install it.
- run `npx create-react-app postify-ui --template typescript` . By defalut javascript will be enabled. So enable typescript.



