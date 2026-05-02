# Hollow Track

**Idiomas / Languages:**
- [Português](#português)
- [English](#english)

---

## Português

Hollow Track é uma checklist leve e responsiva para acompanhar seu progresso em Hollow Knight. A interface foi desenvolvida em React + Vite e oferece suporte nativo para português e inglês, mantendo um visual inspirado na versão original de hollowknightchecklist.com.

### Recursos
- Checklist de coleções, equipamentos, feitiços e chefes
- Barra de progresso com porcentagem de conclusão
- Marcar/desmarcar todos os itens com um clique
- Alternância de idioma entre `pt` e `en`
- Persistência local via `localStorage`
- Links rápidos para as páginas do fandom em português
- Interface clean usando Tailwind CSS

### Como executar
```bash
npm install
npm run dev
```

Abra `http://localhost:5173` no navegador.

### Build para produção
```bash
npm run build
npm run preview
```

### Scripts úteis
- `npm run dev` — inicia o servidor de desenvolvimento
- `npm run build` — compila o app para produção
- `npm run preview` — executa uma pré-visualização do build
- `npm run lint` — verifica o código com ESLint

### Estrutura do projeto
- `src/App.tsx` — lógica principal da checklist
- `src/gameData.json` — dados do jogo e itens rastreados
- `src/components/` — componentes de UI reutilizáveis
- `src/lib/` — utilitários de tradução e links
- `src/index.css` / `tailwind.config.js` — estilo e tema

---

## English

Hollow Track is a lightweight, responsive checklist to track your progress in Hollow Knight. Built with React and Vite, the project supports both Portuguese and English and follows the design spirit of hollowknightchecklist.com.

### Features
- Progress tracking for bosses, equipment, spells and collectibles
- Completion percentage bar
- Check/uncheck all items with a single button
- Language toggle between `pt` and `en`
- Local persistence using `localStorage`
- Quick links to Portuguese fandom pages
- Clean UI powered by Tailwind CSS

### Run locally
```bash
npm install
npm run dev
```

Open `http://localhost:5173` in your browser.

### Production build
```bash
npm run build
npm run preview
```

### Useful scripts
- `npm run dev` — start development server
- `npm run build` — build the app for production
- `npm run preview` — preview the production build
- `npm run lint` — run ESLint checks

### Project structure
- `src/App.tsx` — main checklist logic
- `src/gameData.json` — game item data and tracking metadata
- `src/components/` — reusable UI components
- `src/lib/` — translation and URL helpers
- `src/index.css` / `tailwind.config.js` — styling and theme configuration
