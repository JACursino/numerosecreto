# 🎮 Jogo do Número Secreto

> Um jogo de adivinhação interativo desenvolvido com JavaScript, HTML5 e CSS3.

![Badge](https://img.shields.io/badge/status-concluído-success)
![Badge](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![Badge](https://img.shields.io/badge/HTML-5-orange)
![Badge](https://img.shields.io/badge/CSS-3-blue)

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Demonstração](#-demonstração)
- [Como Jogar](#-como-jogar)
- [Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [Instalação](#-instalação)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Melhorias Futuras](#-melhorias-futuras)
- [Contribuição](#-contribuição)
- [Licença](#-licença)
- [Contato](#-contato)

---

## 🎯 Sobre o Projeto

O **Jogo do Número Secreto** é um jogo interativo onde o jogador precisa adivinhar um número secreto gerado aleatoriamente entre **1 e 100**. O jogo fornece dicas após cada tentativa, indicando se o palpite está acima ou abaixo do número correto.

### Características principais:
- 🎲 Geração aleatória de números
- 🔊 Feedback por voz (Text-to-Speech em português)
- 📊 Contador de tentativas
- ♿ Interface acessível
- 📱 Design responsivo

---

## ✨ Funcionalidades

- ✅ **Geração Aleatória**: Número secreto gerado entre 1 e 10
- ✅ **Dicas Inteligentes**: Feedback se o palpite é "maior" ou "menor"
- ✅ **Contador de Tentativas**: Acompanha o número de palpites realizados
- ✅ **Sistema de Voz**: Narração em português brasileiro das mensagens
- ✅ **Histórico de Números**: Evita repetição de números em rodadas consecutivas
- ✅ **Reinício Rápido**: Botão para iniciar nova partida
- ✅ **Validação de Entrada**: Aceita apenas números dentro do intervalo permitido

---

## 🕹️ Como Jogar

1. **Acesse o jogo** abrindo o arquivo `index.html` no navegador
2. **Digite um número** entre 1 e 10 no campo de entrada
3. **Clique em "Chutar"** para enviar seu palpite
4. **Siga as dicas**:
   - 🔼 "O número secreto é maior" → tente um número maior
   - 🔽 "O número secreto é menor" → tente um número menor
5. **Acertou?** 🎉 Veja quantas tentativas você precisou
6. **Clique em "Novo Jogo"** para jogar novamente

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Finalidade |
|------------|-----------|
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Lógica do jogo, validações e interatividade |
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) | Estrutura e marcação semântica |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) | Estilização e design responsivo |
| **ResponsiveVoice** | Síntese de voz em português brasileiro |

---

## 💻 Instalação

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Edge, Safari)
- Conexão com internet (para carregar fontes e biblioteca de voz)

### Passos

1. **Clone o repositório**
```bash
git clone https://github.com/JACursino/numerosecreto.git
```

2. **Navegue até a pasta do projeto**
```bash
cd jogosecreto
```

3. **Abra o arquivo no navegador**
```bash
# No Windows
start index.html

# No macOS
open index.html

# No Linux
xdg-open index.html
```

Ou simplesmente arraste o arquivo `index.html` para o navegador.

---

## 📁 Estrutura do Projeto

```
jogo-numero-secreto/
│
├── index.html          # Estrutura HTML principal
├── style.css           # Estilos e design
├── app.js              # Lógica do jogo
├── README.md           # Documentação do projeto
│
└── img/
    ├── code.png        # Imagem de fundo
    ├── ia.png          # Ilustração da IA
    └── Ruido.png       # Textura de ruído
```

---

## 🚀 Melhorias Futuras

Ideias para expandir o projeto:

- [ ] Adicionar níveis de dificuldade (Fácil: 1-10, Médio: 1-50, Difícil: 1-100)
- [ ] Sistema de pontuação baseado no número de tentativas
- [ ] Ranking de melhores jogadores (localStorage)
- [ ] Tema claro/escuro
- [ ] Animações e efeitos sonoros
- [ ] Estatísticas do jogador

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas!

1. Faça um **Fork** do projeto
2. Crie uma **Branch** para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Faça o **Commit** das mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Faça o **Push** para a Branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um **Pull Request**

### Ideias de contribuição:
- 🐛 Reportar bugs
- 💡 Sugerir novas funcionalidades
- 📝 Melhorar a documentação
- 🎨 Aprimorar o design

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 📧 Contato

**José Antônio **
Link do Projeto: [https://github.com/JACursino/numerosecreto.git](https://github.com/JACursino/numerosecreto.git)

---

<div align="center">

### ⭐ Se este projeto foi útil para você, considere dar uma estrela!

[⬆ Voltar ao topo](#-jogo-do-número-secreto)

</div>
