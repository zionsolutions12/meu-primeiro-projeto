# Meu Primeiro Projeto 🚀

Projeto de aprendizado criado ao vivo durante um vídeo, com a ajuda do **Claude Code**.

## 🌐 Sobre o site

Este repositório contém uma **página inicial de boas-vindas em 3D**, feita para receber a galera que está assistindo ao vídeo.

A página (`index.html`) é uma **cena 3D interativa** construída com [Three.js](https://threejs.org/) — uma biblioteca de gráficos 3D para a web. Tudo roda direto no navegador, sem precisar instalar nada.

### ✨ O que tem na cena

- 💎 **Núcleo central** — um icosaedro com material físico (metálico/clearcoat) que pulsa e gira lentamente, com um wireframe luminoso por cima.
- 🪐 **Anéis orbitais** coloridos em ângulos diferentes, girando continuamente ao redor do núcleo.
- ⚪ **Esferas brilhantes** orbitando o centro em trajetórias variadas.
- ✨ **Campo de ~1.400 partículas/estrelas** coloridas envolvendo toda a cena.
- 💡 **Luzes dinâmicas** (roxo, rosa e ciano) que orbitam e criam reflexos que mudam o tempo todo.
- 🌫️ **Neblina (fog)** para dar sensação de profundidade.
- 📝 Texto de boas-vindas e botão sobrepostos, com animações de entrada.

### 🖱️ Interatividade

- **Mexer o mouse** → a câmera e os objetos seguem o movimento com um efeito de *parallax* suave.
- **Rolar o scroll** → aproxima e afasta o zoom da cena.
- **Responsivo** → se adapta automaticamente ao tamanho da janela / tela.

## ▶️ Como executar

Não precisa de servidor nem instalação. Basta abrir o arquivo `index.html` no navegador:

- **Windows:** dê dois cliques no `index.html`, ou rode `start index.html`.
- Ou arraste o arquivo para uma aba do navegador.

> ⚠️ A página carrega o Three.js de uma CDN (unpkg), então é necessária **conexão com a internet** na primeira vez.

## 🛠️ Tecnologias

- **HTML5** + **CSS3** (animações, gradientes, efeito *glassmorphism* no texto)
- **JavaScript (ES Modules)**
- **[Three.js](https://threejs.org/)** v0.160 — renderização 3D via WebGL

## 📁 Estrutura

```
meu-primeiro-projeto/
├── index.html      # A página de boas-vindas em 3D
├── .gitignore      # Ignora .env e arquivos sensíveis
└── README.md       # Este arquivo
```

---

Feito com 💜 durante o vídeo, com o **Claude Code**.
