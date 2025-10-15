# Gringozin+optimizervtx

Interface para Gringozin+optimizervtx

## 🚀 Deploy no Netlify

### Método 1: Via Netlify CLI

1. Instale as dependências:
```bash
npm install
```

2. Faça login no Netlify:
```bash
npx netlify login
```

3. Inicie o projeto:
```bash
npx netlify init
```

4. Deploy:
```bash
npm run deploy
```

### Método 2: Via GitHub

1. Crie um repositório no GitHub
2. Faça push do código:
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git
git push -u origin main
```

3. Vá em [Netlify](https://netlify.com) e conecte seu repositório

## 📁 Estrutura do Projeto

```
.
├── public/
│   └── index.html
├── netlify/
│   └── functions/
│       └── hello.js
├── package.json
├── netlify.toml
└── README.md
```

## 🔧 Desenvolvimento Local

```bash
npm run dev
```

Acesse: http://localhost:8888
