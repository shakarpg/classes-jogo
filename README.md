# 🧙‍♂️ Escrevendo as Classes de um Jogo

Projeto prático do bootcamp da DIO. O desafio consiste em criar uma classe que represente um herói de RPG e implemente um método de ataque baseado no tipo do personagem.

## 🚀 Tecnologias Usadas

- JavaScript
- Node.js

## 🎯 Objetivo

Criar uma classe `Heroi` com:

- `nome`
- `idade`
- `tipo` (guerreiro, mago, monge, ninja)

E um método `atacar()` que exibe:

- `"O {tipo} atacou usando {ataque}"`

## 🧠 Regras de Ataque

| Tipo      | Ataque              |
|-----------|---------------------|
| mago      | magia               |
| guerreiro | espada              |
| monge     | artes marciais      |
| ninja     | shuriken            |

## 📦 Exemplo de Uso

```javascript
const heroi1 = new Heroi('Arthas', 30, 'guerreiro');
heroi1.atacar(); // O guerreiro atacou usando espada

const heroi2 = new Heroi('Jaina', 28, 'mago');
heroi2.atacar(); // O mago atacou usando magia
```

## 🛠️ Como Executar

```bash
node classes-jogo.js
```

---

Feito com 💻 por [Seu Nome]
