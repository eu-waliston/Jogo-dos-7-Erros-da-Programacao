# 🐞 Jogo dos 7 Erros da Programação

Um jogo educativo interativo inspirado no clássico "7 erros", aplicado ao ensino de programação.

O projeto permite que o usuário compare dois códigos (correto vs com erros) e identifique falhas clicando diretamente na interface — aprendendo de forma visual, prática e divertida.

---

## 🎯 Objetivo

Desenvolver uma ferramenta interativa que auxilie no aprendizado de programação através da identificação de erros, estimulando:

- 🧠 Raciocínio lógico  
- 🔍 Atenção a detalhes  
- 💻 Compreensão de sintaxe e lógica  
- 🎓 Alfabetização digital  

---

## 💡 Conceito

O jogo apresenta dois lados:

- ✅ Código correto  
- ❌ Código com erros  

O usuário deve clicar nos pontos onde existem erros (representados por círculos), como em jogos tradicionais de “7 erros”.

Ao acertar:
- O erro é marcado
- Uma explicação é exibida

Ao errar:
- O sistema informa que não há erro naquele ponto

---

## 🎮 Funcionalidades

- Sistema de níveis:
  - Iniciante
  - Intermediário
  - Avançado

- Detecção de clique por coordenadas (Canvas)
- Feedback visual (acerto/erro)
- Contador de tentativas
- Contador de erros encontrados/restantes
- Sistema de ajuda (mostrar/esconder círculos)
- Tela de parabéns com:
  - Lista de erros explicados
  - Número de tentativas
- Progressão entre níveis

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** → Estrutura do projeto  
- **CSS3** → Estilização moderna e responsiva  
- **JavaScript (Vanilla)** → Lógica do jogo  
- **Canvas API** → Renderização gráfica e interação  

---

## 🧠 Como Funciona (Resumo Técnico)

- O código é desenhado usando `Canvas`
- Cada erro possui:
  - Linha (`line`)
  - Posição (`charPos`)
- O sistema calcula a posição exata na tela
- Cada erro vira uma **hitbox circular**
- Quando o usuário clica:
  - O sistema calcula a distância do clique até o erro
  - Se estiver dentro da área → acerto
  - Caso contrário → erro

---

## 📂 Estrutura do Projeto

```
/projeto
├── index.html
└── README.md
```


---

## 🚀 Como Executar

1. Baixe ou clone o repositório
2. Abra o arquivo:


3. Execute no navegador (Chrome, Edge, etc.)

---

## 👥 Integrantes do Projeto

- 👨‍💻 Waliston Eurípedes  [ eu-waliston ] 

- 👨‍💻 Pedro [ pedro-henrique-jv ]

- 👩‍💻 Isabela  [ isabelaacr]


---

## 🧩 Níveis do Jogo

### 🟢 Iniciante
- Erros visuais:
  - Aspas
  - Dois pontos
  - Indentação

### 🟡 Intermediário
- Erros de lógica:
  - Condições incorretas
  - Estruturas incompletas

### 🔴 Avançado
- Estruturas de controle:
  - `if/else`
  - loops
  - comparações

---

## 🎓 Aplicação Educacional

Este projeto pode ser utilizado como:

- Ferramenta de apoio em aulas de programação
- Introdução à lógica computacional
- Recurso para alfabetização digital
- Método lúdico de ensino em escolas

---

## 🔮 Possíveis Melhorias Futuras

- 🎵 Adicionar sons e efeitos
- 🏆 Sistema de pontuação
- 📱 Versão mobile otimizada
- 👨‍🏫 Modo professor (controle de níveis e conteúdo)
- 🧠 Sistema de perguntas mais avançado

---

## 🧪 Status do Projeto

✅ Funcional  
🚧 Em evolução  

---

## 📜 Licença

Este projeto é de uso educacional.

---

## ✨ Visão

Mais do que um jogo, este projeto representa uma nova forma de aprender programação:

> menos teoria travada, mais interação viva.

Aprender errando, clicando, descobrindo — como um jogo deve ser.

---
