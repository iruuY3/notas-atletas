# 🏅 Projeto: Notas dos Atletas

Este projeto foi desenvolvido para calcular a **média válida de notas** de atletas em uma competição de ginástica artística, considerando uma regra específica de avaliação.

## 📌 Descrição

Na competição, cinco jurados avaliam cada atleta com notas de **1 a 10**. Porém, **apenas as três notas do meio são consideradas** para o cálculo da média — ou seja, **a menor e a maior nota são descartadas**.

Este script JavaScript recebe um conjunto de atletas com suas respectivas notas e imprime no console:
- Nome do atleta
- Notas obtidas
- Média válida calculada com base nas três notas centrais

## 📊 Exemplo de Entrada

```javascript
let atletas = [
  {
    nome: "Cesar Abascal",
    notas: [10, 9.34, 8.42, 10, 7.88]
  },
  {
    nome: "Fernando Puntel",
    notas: [8, 10, 10, 7, 9.33]
  },
  {
    nome: "Daiane Jelinsky",
    notas: [7, 10, 9.5, 9.5, 8]
  },
  {
    nome: "Bruno Castro",
    notas: [10, 10, 10, 9, 9.5]
  }
];
```
## ✅ Saída Esperada
```
Atleta: Cesar Abascal
Notas Obtidas: 10,10,7.88,8.42,9.34
Média Válida: 9,253333

Atleta: Fernando Puntel
Notas Obtidas: 10,10,7,8,9.33
Média Válida: 9.11

Atleta: Daiane Jelinsky
Notas Obtidas: 10,7,8,9.5,9.5
Média Válida: 9

Atleta: Bruno Castro
Notas Obtidas: 10,10,10,9,9.5
Média Válida: 9.83333333333

```
## Resultado

```
Atleta: Cesar Abascal
Notas Obtidas: 7.88,8.42,9.34,10,10
Média Válida: 9.253333333333332

Atleta: Fernando Puntel
Notas Obtidas: 7,8,9.33,10,10
Média Válida: 9.11

Atleta: Daiane Jelinsky
Notas Obtidas: 7,8,9.5,9.5,10
Média Válida: 9

Atleta: Bruno Castro
Notas Obtidas: 9,9.5,10,10,10
Média Válida: 9.833333333333334
```
A ordem das notas está difente pelo uso do **.sort((a,b) => a - b)** a qual ordena do menor para o maior

## 👨‍💻 Autor
Desenvolvido por Yuri Fernando da Cruz

GitHub
