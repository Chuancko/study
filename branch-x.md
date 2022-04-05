# 这是分支x里的文件
## 用了一些markdown标记语言
```JavaScript
function Person(name,age){
    this.name = name;
    this.age = age;
}

Person.prototype.sayHi = function(){
    return console.log("你好，我叫" + this.name);
}
………略
```

* 这个是class版本
```JavaScript
class Person{
    constructor(name,age){
        this.name = name;
        this.age = age;
    }

    sayHi(){
        console.log("你好，我叫" + this.name);
    }
}
let person1 = new Person('Chuancko',18)
person1.name === 'Chuancko'
person1.age === 18
person1.sayHi()
```