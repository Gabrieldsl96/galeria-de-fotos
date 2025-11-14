# 🚀 Galeria de Fotos Intergaláticas

Uma aplicação web moderna de galeria de fotos construída com Next.js, React e TypeScript. Este projeto exibe uma coleção de fotos intergaláticas em um layout responsivo com modal para visualização ampliada.

🔗 **[Acesse o site aqui](https://galeria-de-fotos.gbcmtecnologia.com.br/)**

## ✨ Funcionalidades

- 📸 Galeria de fotos em grid responsivo
- 🔍 Modal para visualização ampliada das imagens
- 📱 Design responsivo (mobile, tablet e desktop)
- ⚡ Performance otimizada com Next.js
- 🎨 Interface moderna com Tailwind CSS

## 🛠️ Tecnologias Utilizadas

- **Next.js 15.5.6** - Framework React com App Router
- **React 19.1.0** - Biblioteca JavaScript para interfaces
- **TypeScript** - Tipagem estática para JavaScript
- **Tailwind CSS 4** - Framework CSS utilitário
- **Geist Font** - Fonte otimizada do Vercel

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- Node.js (versão 18 ou superior)
- npm, yarn, pnpm ou bun

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone <url-do-repositorio>
cd galeria-de-fotos
```

2. Instale as dependências:
```bash
npm install
# ou
yarn install
# ou
pnpm install
```

3. Execute o servidor de desenvolvimento:
```bash
npm run dev
# ou
yarn dev
# ou
pnpm dev
# ou
bun dev
```

4. Abra [http://localhost:3000](http://localhost:3000) no seu navegador.

## 📁 Estrutura do Projeto

```
galeria-de-fotos/
├── public/
│   └── assets/          # Imagens da galeria
├── src/
│   ├── app/
│   │   ├── layout.tsx   # Layout principal
│   │   ├── page.tsx     # Página principal
│   │   └── globals.css  # Estilos globais
│   ├── components/
│   │   ├── Modal.tsx    # Componente de modal
│   │   └── PhotoItem.tsx # Componente de item de foto
│   ├── data/
│   │   └── photoList.ts # Lista de fotos
│   └── types/
│       └── Photo.ts     # Tipos TypeScript
├── package.json
└── README.md
```

## 🎯 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento com Turbopack
- `npm run build` - Cria a build de produção com Turbopack
- `npm run start` - Inicia o servidor de produção
- `npm run lint` - Executa o linter ESLint

## 📝 Como Usar

1. A galeria exibe todas as fotos em um grid responsivo
2. Clique em qualquer foto para abrir o modal de visualização ampliada
3. Clique no "X" ou fora da imagem para fechar o modal

## 🔧 Personalização

Para adicionar novas fotos:

1. Adicione a imagem na pasta `public/assets/`
2. Atualize o arquivo `src/data/photoList.ts` com o novo item:

```typescript
{ id: 10, url: '10.jpg'}
```

## 👨‍💻 Autor

Gabriel Lemos


