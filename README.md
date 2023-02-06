![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

# PERGUNTAS DE JAVASCRIPT

Nesse repositório você vai encontrar questões técnicas e não técnicas para testar seus conhecimentos e se preparar para entrevistas.
Caso tenha dúvidas, as respostas com explicações estão logo abaixo das questões - antes de chegar nessa parte, tente resolver primeiro, seja honesto com você mesmo =)

Você pode encontrar muito mais conteúdos de programação e tecnologia por aqui:

<a href="https://www.instagram.com/techly.com.br/" target="_blank">
	<img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=flat-square&logo=instagram&logoColor=white" alt="Instagram">
</a>


## ⬛ 1

Qual é o output?

```js
let a = 5;
let b = new Number(5);
let c = 5;

console.log(a == b);
console.log(a === b);
console.log(b === c);
```

- A: `true` `false` `true`
- B: `false` `false` `true`
- C: `true` `false` `false`
- D: `false` `true` `true`
<details><summary><b> ✅ RESPOSTA CERTA<b></summary>
<p>

#### Resposta: C
new Number() é um construtor de função integrado, tem vários recursos extras e é um objeto.1
Pode até parecer um número, mas não é.

Quando usamos o operador == (operador de igualdade), ele apenas verifica se tem o mesmo valor.
Ambos têm o valor de 3, então retorna true.

Mas quando usamos o operador === (operador de igualdade estrita), tanto o valor quanto o tipo devem ser iguais.
Nesse caso, new Number() não é um número, é um objeto, por isso os dois  retornam false.
</p>
</details>

---
## ⬛ 2

Qual é o output?

```javascript
console.log('🤜' + '🤛');
```

- A: Uma string com unicode dos emojis
- B: `'🤜🤛"`
- C: Undefined
- D: `'🤜 + 🤛''`

<details><summary><b>✅ RESPOSTA CERTA</b></summary>
<p>

#### Resposta B

Você pode concatenar strings usando o operador `+`. No exemplo acima, os emojis foram contcatenados em forma de string. Por isso, output é '🤜🤛" 
</p>
</details>

---

## ⬛ 3

Qual será o retorno?

```javascript
[...'Lyssa'];
```

- A: ["L","y","s","s","a"]
- B: [["L","y","s","s","a"]]
- C: ["Lyssa"]
- D: [[],"Lyssa"]

<details><summary><b>✅ RESPOSTA CERTA</b></summary>
<p>

#### Resposta A

A palavra "Lyssa" é um string e toda string é iterável, ou seja, pode ser repetida.

Iteração é uma execução repetida de uma sequência de instruções, coisa que os computadores fazem muito bem.

O operador spread [...] mapeia cada caractere de um iterável para um elemento.

Portanto, senhores, o retorno do spread cria um array com cada letra separada.

</p>
</details>

---