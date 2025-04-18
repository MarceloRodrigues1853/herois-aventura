# 🦸‍♂️ Heróis de Aventura - DIO 🦸‍♀️

Seja bem-vindo ao mundo dos **Heróis de Aventura**! 🌟 Aqui você encontra **magos, guerreiros, monges e ninjas** prontos para viver grandes aventuras 🗡️⚡🥋🎯.

Este projeto foi desenvolvido como parte do desafio da [DIO](https://www.dio.me/), explorando conceitos fundamentais de JavaScript em um projeto épico! 🚀

---

## 🔍 **Sobre o Projeto**

Neste jogo, você vai:
- Criar heróis incríveis com **nome**, **idade** e **tipo**.
- Dar vida aos seus heróis com o método **atacar**, que exibe mensagens épicas como:
  - Mago: "O mago atacou usando magia."
  - Guerreiro: "O guerreiro atacou usando espada."
  - Monge: "O monge atacou usando artes marciais."
  - Ninja: "O ninja atacou usando shuriken."

E muito mais! 📜

## 🎨 Visual

### ⚡ Inspiração Épica
![Herói Épico](./src/assets/heroi-epico.jpg)

*Este é o visual inspirado no mundo dos heróis de aventura! 🦸‍♂️⚔️*

---

Pronto para explorar e criar os heróis mais incríveis do universo!

## 🛠️ **Tecnologias Utilizadas**

- 💻 JavaScript ES6
- 🧠 Lógica de programação
- 🎨 Criatividade e diversão!

---

## ✨ **Exemplo de Código**

Aqui vai um gostinho do que você pode criar:
```javascript
class Heroi {
  constructor(nome, idade, tipo) {
    this.nome = nome;
    this.idade = idade;
    this.tipo = tipo;
  }

  atacar() {
    let ataque;
    switch (this.tipo.toLowerCase()) {
      case "mago":
        ataque = "usou magia";
        break;
      case "guerreiro":
        ataque = "usou espada";
        break;
      case "monge":
        ataque = "usou artes marciais";
        break;
      case "ninja":
        ataque = "usou shuriken";
        break;
      default:
        ataque = "realizou um ataque indefinido";
    }
    console.log(`O ${this.tipo} atacou usando ${ataque}.`);
  }
}

const mago = new Heroi("Merlin", 35, "Mago");
mago.atacar(); // O mago atacou usando magia.
```

#

## 📂 Estrutura do Repositório

* `src/:` Código fonte do jogo.

* `assets/:` Imagens e recursos extras.

* `README.md:` Arquivo com todas as informações do projeto.
