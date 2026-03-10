# 🎮 Jogo do Número Secreto

Um jogo simples desenvolvido com **HTML, CSS e JavaScript** onde o jogador deve adivinhar um número secreto gerado aleatoriamente pelo sistema.

O jogo fornece dicas informando se o número secreto é **maior ou menor** que o número digitado, até que o jogador acerte.

Além disso, o jogo utiliza **síntese de voz** para narrar as mensagens exibidas na tela.

---

# 📸 Demonstração

O jogador deve:

1. Escolher um número entre **1 e 100**
2. Clicar em **Chutar**
3. Receber dicas se o número é **maior ou menor**
4. Continuar tentando até acertar
5. Reiniciar o jogo ao final

---

# 🚀 Tecnologias Utilizadas

* **HTML5** → Estrutura da página
* **CSS3** → Estilização e layout responsivo
* **JavaScript** → Lógica do jogo
* **ResponsiveVoice.js** → Narração por voz das mensagens

---

# 🎯 Funcionalidades

✔ Geração aleatória do número secreto
✔ Controle de tentativas
✔ Dicas para ajudar o jogador (maior ou menor)
✔ Sistema de voz para leitura das mensagens
✔ Botão de reiniciar jogo
✔ Evita repetição de números sorteados

---

# 🧠 Lógica do Jogo

O jogo funciona da seguinte forma:

1️⃣ O sistema gera um **número aleatório entre 1 e 100**

2️⃣ O jogador digita um número no campo de entrada

3️⃣ O sistema verifica:

* Se acertou
* Se o número secreto é maior
* Se o número secreto é menor

4️⃣ A cada tentativa o contador aumenta

5️⃣ Quando o jogador acerta:

* O jogo mostra quantas tentativas foram necessárias
* O botão **Novo Jogo** é liberado

---

# 📂 Estrutura do Projeto

```
NUMERO-SECRETO
│
├── img/                 # Imagens utilizadas no projeto
│
├── numero-secreto/
│   └── atributos/       # Arquivos ou recursos adicionais do projeto
│
├── index.html           # Estrutura principal da página
├── style.css            # Estilização do jogo
├── app.js               # Lógica do jogo em JavaScript
└── README.md            # Documentação do projeto
```

---

# ▶️ Como Executar o Projeto

1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/numero-secreto.git
```

2. Entre na pasta do projeto

```bash
cd numero-secreto
```

3. Abra o arquivo **index.html** no navegador.

---

# 💡 Melhorias Futuras

Algumas melhorias que podem ser implementadas:

* 🎵 Adicionar efeitos sonoros
* 🏆 Criar ranking de menor número de tentativas
* 📱 Melhorar ainda mais a responsividade
* 🎨 Adicionar temas visuais
* 🌐 Publicar o jogo online (GitHub Pages)

---

# 👨‍💻 Autor

Projeto desenvolvido para prática de **JavaScript e lógica de programação**.

---

# 📜 Licença

Este projeto está sob a licença **MIT**.
