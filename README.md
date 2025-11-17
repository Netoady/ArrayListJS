# ArrayListJs

Este projeto é um tutorial prático sobre como manipular coleções (listas) em **JavaScript** utilizando os métodos **map**, **filter** e **reduce**.

---

## 📖 Introdução

Arrays são estruturas fundamentais em JavaScript para armazenar coleções de dados.  
Os métodos `map`, `filter` e `reduce` permitem transformar, filtrar e reduzir listas de forma simples e expressiva.

---

## 🔧 Métodos explicados

### 1. `map()`
- **Função:** percorre cada elemento da lista e retorna um novo array com os valores transformados.
- **Exemplo:**
```js
const numeros = [1, 2, 3, 4];
const dobrados = numeros.map(n => n * 2);
console.log(dobrados); // [2, 4, 6, 8]

### 2. `filter()`
- **Função:** retorna um novo array apenas com os elementos que passam em uma condição.
- **Exemplo:**
```js
const numeros = [1, 2, 3, 4, 5];
const pares = numeros.filter(n => n % 2 === 0);
console.log(pares); // [2, 4]

### 1. `reduce()`
- **Função:** Reduz o array a um único valor, acumulando os elementos conforme uma função.
- **Exemplo:**
```js
const numeros = [1, 2, 3, 4, 5];
const soma = numeros.reduce((acumulador, valor) => acumulador + valor, 0);
console.log(soma); // 15

