# Fundamentos do JavaScript Clássico 

## INTEGRAÇÕES 

### Integrar JavaScript de forma interna 

~~~ html
./index.html

<!DOCTYPE html>

<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript</title>
</head>
<body>
    
    <script>
        console.log("Hello World!");
    </script>
</body>
</html>
~~~
    

### Integrar JavaScript de forma externa

- Criar diretório ***src*** na raiz do projeto 
- Criar arquivo ***script.js*** na raiz do diretório ***src***
- Integrar de forma externa o arquivo ***script.js*** no arquivo ***index.html***

~~~ html
./index.html

<!DOCTYPE html>

<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript</title>
</head>
<body>
    
  <script src="./src/script.js"></script>
</body>
</html>
~~~

## COMENTÁRIOS

### Comentários de linha 

~~~ javascript 
./src/script.js

// comentário de linha 

~~~

### Comentários de bloco simples 

~~~ javascript 
./src/script.js

/* comentário de bloco simples */

~~~

### Comentários de bloco com marcadores

~~~ javascript 
./src/script.js

/**
 * comentário de bloco com marcador 
 */

~~~

## VARIÁVEIS

### Declaração

~~~javascript 
./src/script.js

var number;

~~~

### Atribuiçaõ de valor 

~~~javascript 
./src/script.js

var number;

number = 5;

~~~

### Declaração e atribuiçaõ de valor 

~~~javascript 
./src/script.js

var number = 5;

~~~

### Reatribuiçaõ de valor 

~~~javascript 
./src/script.js

var number = 5;

number = 10;

~~~

### Nomenclaturas 

- Caracteres permitidos para iniciar a nomenclatura de um identificador 

~~~javascript 
./src/script.js
 
 // letras
 var number;
 var Number;

 // sublinhado
 var _number;

 // cifrão
 var $number;

~~~

- Case-sensitive

~~~javascript 
./src/script.js

// "number é diferente de "Number"

~~~

- Nomenclaturas compostas 

~~~javascript 
./src/script.js

// camel case
var myName;

// pascal case
var MyName;

// snake case
var my_name;

~~~

## TIPOS DE DADOS

### Tipos de dados primitivos 

~~~javascript 
./src/script.js


// string
var name = "Jhone"; 
var surname = 'Mello';

// number
var age = 29;
var weight = 85.6;

// boolean
var active = true;
var permission =  false;

// undefined 
var contains;
console.log(contains);

//null
var data = null;

~~~

### Não primitivo

~~~ javascript 
./src/script.js

// array
var values = [1, "Alex", true, null];

// object literal
var person = {name: "Mello", age: 47}

var person = {
  name: "Mello",
  age : 47
}

//function
var message = function(){};

~~~ 

### Inspecinar tipo

~~~ javascript 
./src/script.js

// typeof
var age = 29;
console.log(typeof age);

~~~

### Coerção de tipo 
-Implicíta

~~~ javascript 
./src/script.js

var age = 29;
var weight = "86.5";
var result = age + weight;
console.log(typeof result);

~~~

-Explícita 

~~~ javascript 
./src/script.js

// Number()
var weight = Number("85.6");
console.log(typeof weight);
//String()
var age = String(47);
console.log(typeof age);
//Boolean()
var active = Boolean(0);
console.log(typeof active);

~~~

//Operadores

// aritmético

var num1 = 10;
var num2 = 2;

// adição
var sum = num1 + num2;

// subtração
var sub = num1 - num2;

// multiplicação
var mult = num1 * num2;

// divisão
var div = num1 / num2;

// módulo/resto
var mod = num1 % num2;

//incremento
var result1 = 10++;


