class ClassName{
    constructor(prop1, prop2){
        this.prop1 = prop1;
        this.prop2 = prop2;
    }
}
let obj = new ClassName("arg1", "arg2");
console.log(obj.prop1); // Output: arg1
console.log(obj.prop2); // Output: arg2
class Dog{
    constructor(name ,age, breed, color){
        this.name = name;
        this.age = age;
        this.breed = breed;
        this.color = color;
    }
    bark(){
        console.log("Woof! Woof!");
    }
}
let dog1 = new Dog("Buddy", 3, "Golden Retriever", "Golden");
let dog2 = new Dog("Max", 5, "Labrador", "Black");
console.log(dog1.name); // Output: Buddy
console.log(dog2.age); // Output: 5
let p = dog1.bark(); // Output: Woof! Woof!
dog2.bark(); // Output: Woof! Woof!
console.log(p)
class Person{
    #firstname
    #lastname
    constructor(firstname, lastname){
        this.#firstname = firstname;
        this.#lastname = lastname;
    }
    constructor(firstname, lastname){
        this.#firstname = firstname;
        this.#lastname = lastname;
    }
    get firstname(){
        return this.#firstname;
    }
    set firstname(John){
        this.#firstname = John;
    }
    get lastname(){
        return this.#lastname
    }
    set lastname(Doe){
        this.#lastname = Doe;
    }
}
let x = new Person("John", "Doe");
console.log(x.firstname); // Output: John

