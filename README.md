# Javascript_Data_Types_Object

<br/>

O tipo de dados Object no JavaScript é um dos tipos mais importantes e flexíveis da linguagem. Um objeto é uma coleção de propriedades, onde cada propriedade consiste em um nome (também chamado de chave) e um valor. O valor pode ser qualquer tipo de dado JavaScript, incluindo outros objetos.

Aqui está um exemplo simples de como criar e usar um objeto em JavaScript:

<br/>

```
// Criando um objeto vazio
const myObject = {};

// Adicionando propriedades ao objeto
myObject.name = 'João';
myObject.age = 30;

// Acessando propriedades do objeto
console.log(myObject.name); // Output: 'João'
console.log(myObject.age); // Output: 30
```

<br/>

Neste exemplo, um objeto vazio é criado usando chaves {} e armazenado na variável myObject. Em seguida, duas propriedades são adicionadas ao objeto usando a notação de ponto (.): name e age.

Ao acessar as propriedades do objeto usando a notação de ponto, o valor das propriedades são impressos no console.

Os objetos também podem ser criados usando a notação literal de objeto, que permite criar um objeto com propriedades iniciais:

<br/>

```
// Criando um objeto com propriedades iniciais
const person = {
  name: 'Maria',
  age: 25,
  address: {
    street: 'Rua A',
    number: 123
  }
};

// Acessando propriedades do objeto
console.log(person.name); // Output: 'Maria'
console.log(person.age); // Output: 25
console.log(person.address.street); // Output: 'Rua A'
console.log(person.address.number); // Output: 123
```

<br/>

Neste exemplo, um objeto é criado usando a notação literal de objeto e armazenado na variável person. O objeto tem três propriedades: name, age e address, sendo que address é um objeto aninhado com as propriedades street e number.

Ao acessar as propriedades do objeto e do objeto aninhado, os valores são impressos no console.

Além disso, é possível criar objetos usando o construtor Object() e também criar objetos a partir de classes e protótipos, que são conceitos avançados em JavaScript.
