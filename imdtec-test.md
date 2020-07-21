# [Aula 03] *Arrays* em Javascript

### Criação de *arrays* em Javascript

Criamos um *array* envolvendo seus itens com colchetes e separando seus itens por vírgula:

```javascript
var arrayHomogenea = ['segunda', 'terça', 'quarta'];
var arrayHeterogeneo = ['domingo', 3, true];
```

> **Dica:** Note que *arrays* em Javascript podem armazenar dados de qualquer tipo --- podemos ter um *array* que armazena o mesmo tipo de dados (homogênea), ou podemos ter um *array* que armazena diferentes tipos de dados (heterogênea).

### Acessando elementos de um *array*

Cada elemento em um *array* tem uma posição numérica chamada **índice**. Nós podemos acessar itens individualmente em um *array* usando o seu índice:

```javascript
const cidades = ['Natal', 'Fortaleza', 'Recife'];

var minhaCidade = cidades[0];

console.log(minhaCidade)
console.log(cidades[2]);
```

### Atualizando itens de um *array*

Uma vez que você tem acesso ao elemento em um *array*, você pode atualizar o valor armazenado:

```javascript
let cursosTecnicos = ['web', 'eletrônica', 'redes'];

cursosTecnicos[1] = 'jogos';
```

### Propriedade `length`

Por fim, uma das propriedades nativas do *array* é a propriedade `length`, que retorna o seu comprimento, ou seja, o número de elementos armazenados no *array* em questão:

```javascript
const listaDeCompras = ['ovos', 'leite', 'manteiga'];
console.log(listaDeCompras.length);

const novaListaDeCompras = ['ovos', 'leite', 'manteiga', 'chocolate', 'pão'];
console.log(novaListaDeCompras.length);
```

## Código-fonte

Todos os códigos-fontes vistos nesta vídeo-aula podem ser baixados no repositório a seguir:

1. [Repositório de Desenvolvimento Front End II](https://github.com/danilocurvelo/IMD0043)

## Material Complementar

1. [Documentação MDN - Arrays em Javascript](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array)


