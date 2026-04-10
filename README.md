# 👗 Vista o Personagem!

Jogo interativo de vestir personagem com arrastar e soltar (drag and drop), desenvolvido como página estática HTML. Sem dependências externas — tudo em um único arquivo.

---

## 🎮 Como Jogar

- **Tela de Boas-vindas:** clique em **Começar** para iniciar.
- **Navegar personagens:** use as setas **◀ ▶** para trocar entre Guerreiro, Ninja e Mago.
- **Vestir o boneco:** arraste qualquer peça de roupa do painel direito e solte no slot correspondente do boneco (Chapéu, Camisa, Calça ou Sapato).
- **Duplo clique:** dê duplo clique em uma peça do guarda-roupa para equipá-la rapidamente.
- **Remover peça:** dê duplo clique no slot ocupado para remover a peça.
- **🗑 Limpar:** remove todas as roupas do boneco.
- **🎲 Aleatório:** veste o boneco com peças escolhidas aleatoriamente.
- **Suporte a touch:** funciona em celular — arraste com o dedo normalmente.

---

## 🚀 Como Rodar Localmente

### Pré-requisitos
- [Node.js](https://nodejs.org/) instalado (versão 14 ou superior)

### Passos

```bash
# 1. Clone o repositório
git clone https://github.com/7505504/front.page.nico.git

# 2. Entre na pasta
cd front.page.nico

# 3. Inicie o servidor
npm start

# 4. Abra no navegador
# http://localhost:3000
```

### Alternativa sem Node.js
Basta abrir o arquivo `index.html` diretamente no navegador — o jogo funciona sem servidor.

---

## 🌐 Deploy no GitHub Pages

1. Faça fork deste repositório (ou use o seu próprio).
2. Vá em **Settings → Pages**.
3. Em **Source**, selecione **GitHub Actions**.
4. Clique em **Save** — o workflow `.github/workflows/deploy.yml` já cuida do resto.
5. Após o deploy, acesse: `https://{seu-usuario}.github.io/front.page.nico/`

---

## 📁 Estrutura do Projeto

```
front.page.nico/
├── index.html                  # Jogo completo (HTML + CSS + JS inline)
├── server.js                   # Servidor Node.js simples
├── package.json                # Metadados e scripts npm
├── .github/
│   └── workflows/
│       └── deploy.yml          # GitHub Actions — deploy automático no Pages
└── README.md                   # Esta documentação
```

---

## 🛠 Tecnologias

| Tecnologia       | Uso                                   |
|------------------|---------------------------------------|
| HTML5            | Estrutura e SVG do boneco             |
| CSS3             | Estilização, animações, responsivo    |
| JavaScript       | Drag & drop, touch, lógica do jogo    |
| Node.js          | Servidor local simples                |
| GitHub Actions   | Deploy automático no GitHub Pages     |

---

## 📝 Licença

MIT — use à vontade! 🎉
