# 🧙‍♂️ Projeto: Classes de um Jogo em Python

Este é um projeto simples de Python com foco em conceitos fundamentais de programação orientada a objetos. O objetivo é criar uma classe genérica que represente um herói em um jogo de aventura, com comportamento personalizado de ataque conforme seu tipo.

---

## 📚 Conceitos Utilizados

- ✅ Variáveis  
- ✅ Operadores  
- ✅ Laços de repetição  
- ✅ Estruturas de decisão  
- ✅ Funções  
- ✅ Classes e Objetos  

---

## 🎯 Objetivo

Criar uma **classe `Heroi`** com as seguintes propriedades:

- `nome` (str): nome do herói  
- `idade` (int): idade do herói  
- `tipo` (str): tipo do herói (`guerreiro`, `mago`, `monge`, `ninja`)  

E um método chamado `atacar()`, que exibe uma mensagem diferente conforme o tipo do herói:

### 💥 Saídas esperadas:

| Tipo     | Ataque               |
|----------|----------------------|
| mago     | usou magia           |
| guerreiro| usou espada          |
| monge    | usou artes marciais  |
| ninja    | usou shuriken        |

**Exemplo de saída:**  

O mago atacou usando magia
O guerreiro atacou usando espada

---

## 🧪 Exemplo de Uso

```python
from heroi import Heroi

heroi1 = Heroi("Aragorn", 35, "guerreiro")
heroi2 = Heroi("Gandalf", 99, "mago")
heroi3 = Heroi("Bruce", 29, "monge")
heroi4 = Heroi("Hanzo", 27, "ninja")

heroi1.atacar()
heroi2.atacar()
heroi3.atacar()
heroi4.atacar()

🛠 Como Rodar o Projeto

1. Clone este repositório:

git clone https://github.com/seu-usuario/nome-do-repo.git

2. Execute com Python 3:

python nome_do_arquivo.py

3. 
📁 Estrutura Sugerida

📦 classes-jogo-python
├── heroi.py
├── main.py
└── README.md

📌 Licença
Este projeto está sob a licença MIT.

Feito com 💻 por Wiliam Gomide






