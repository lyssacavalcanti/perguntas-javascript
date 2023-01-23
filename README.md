![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

# PERGUNTAS DE JAVASCRIPT

Nesse repositório você vai encontrar questões técnicas e não técnicas para testar seus conhecimentos e se preparar para entrevistas.
Caso tenha dúvidas, as respostas com explicações estão logo abaixo das questões - antes de chegar nessa parte, tente resolver primeiro, seja honesto com você mesmo =)

Você pode encontrar muito mais conteúdos de programação e tecnologia por aqui:

<a href="https://www.instagram.com/techly.com.br/" target="_blank">
	<img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=flat-square&logo=instagram&logoColor=white" alt="Instagram">
</a>


### ⬛ 1

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
<details>
<summary>✅ RESPOSTA CERTA</summary>

```
Resposta: C
new Number() é um construtor de função integrado, tem vários recursos extras e é um objeto.1
Pode até parecer um número, mas não é.

Quando usamos o operador == (operador de igualdade), ele apenas verifica se tem o mesmo valor.
Ambos têm o valor de 3, então retorna true.

Mas quando usamos o operador === (operador de igualdade estrita), tanto o valor quanto o tipo devem ser iguais.
Nesse caso, new Number() não é um número, é um objeto, por isso os dois  retornam false.
```

</details>

