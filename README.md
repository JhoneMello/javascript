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










~~~ javascript
./src/script.js

if(5=="5") {
    console.log("Verdadeiro");
} else {
    console.log("falso");
}
  



~~~ javascript
./src/script.js

var age =65;

if(age > 60) {
    console.log("Aposentado");
} else if (age > 30) {}
    console.log("CLT"); {

    }

  

~~~

#### Operador ternário

~~~ javascript
./src/script.js

var age = 16:

age >= 18 ? console.log("Adult") : console.log("Minor");


~~~

#### Curto-circuito Lógico

~~~ javascript
./src/script.js

var licensed = false

!licensed && console.log("Precisa tirar a carta de habilitação");

~~~




    
    


