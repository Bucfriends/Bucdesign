# BUC — Laboratório de Design

Bem-vindo ao repositório de **" BUC"**, um laboratório de design autêntico focado em materialidade, intenção e acesso democrático ao design de qualidade.

## O que é " BUC"?

" BUC" é mais que uma marca — é um laboratório. Cada peça é um estudo sobre material, cor e intencionalidade. Nasceu da necessidade de democratizar design, mostrando que qualidade e beleza não são privilégio.

### Pilares Fundamentais

- **Material First** — A matéria-prima define tudo. Antes da estética, a estrutura.
- **Intenção** — Cada detalhe existe por razão. Nada é acaso.
- **Acesso** — Design deve ser para todos. Sem gatekeeping, sem exclusão.

---

## Estrutura do Projeto

```
Bucdesign/
├── index.html          // Home — Drops e fila de espera
├── marca.html          // Página sobre a marca e filosofia
├── api/                // Endpoints para gerenciar waitlist
└── README.md           // Este arquivo
```

### Páginas Principais

- **`index.html`** — Home. Apresentação dos drops, formulário de inscrição, cards dos estudos.
- **`marca.html`** — Sobre " BUC". Storytelling, valores, processo criativo e identidade visual.

---

## Design & Identidade

### Tipografia

- **Display (Títulos)**: Typeka Mix + Wicked Bold + Helvetica
- **Body**: Typeka Mix + Helvetica Neue
- **Mono**: Space Mono

### Paleta de Cores

```css
--void: #080808              /* Fundo principal */
--concrete: #e8e4de          /* Texto principal */
--ash: #bdb8b2               /* Texto secundário */
--ghost: #222222             /* Texto terciário */
--line: #161616              /* Bordas */
--ultramarine: #001ba8       /* Cor de marca */
```

### Características Visuais

✓ Espaços negativos generosos  
✓ Tipografia premium com respiro  
✓ Todos os botões funcionais e interativos  
✓ Design responsivo (mobile-first)  
✓ Acessibilidade em primeiro plano  

---

## Como Usar

### Desenvolvimento Local

1. Clone o repositório:
```bash
git clone https://github.com/Bucfriends/Bucdesign.git
cd Bucdesign
```

2. Abra `index.html` em seu navegador (ou use um servidor local):
```bash
python -m http.server 8000
# ou
npx http-server
```

3. Navegue para `http://localhost:8000`

### Deploy

O site está hospedado em: **https://bucdesign.vercel.app**

---

## Funcionalidades

### Formulário de Waitlist

- Validação de e-mail em tempo real
- Fallback local (localStorage) se API não estiver disponível
- Mensagens de feedback amigáveis
- Acessibilidade completa (ARIA labels, focus management)

### Navegação

- **Home** (`/`) — Visão geral, drops e inscrição
- **Sobre** (`/marca`) — História, valores e processo
- **Links internos** — Navegação fluida entre seções

---

## Stack

- **HTML5** — Semântica, acessibilidade
- **CSS3** — Grid, Flexbox, animações suaves
- **JavaScript Vanilla** — Sem dependências externas
- **Fontes Google** — Carregamento otimizado

---

## Próximas Etapas

- [ ] Página de produtos com filtros
- [ ] Sistema de e-commerce
- [ ] Blog de processos criativos
- [ ] Integração com backend para salvar waitlist
- [ ] Dashboard administrativo
- [ ] Animações avançadas e micro-interações

---

## Contato & Redes

- **Email**: contacto@bucdesign.com
- **Localização**: Goiânia, Brasil
- **Website**: https://bucdesign.vercel.app

---

**" BUC" — Processos. Matéria. Intenções.**

*Cada detalhe importa. Cada peça conta uma história.*
