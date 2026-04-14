# 🛟 SyntaxWear - E-commerce de Tênis e Sneakers

Loja online moderna e responsiva especializada em **tênis e sneakers** de alta qualidade. Site desenvolvido com HTML, CSS puro e JavaScript vanilla, seguindo boas práticas de desenvolvimento frontend.

## 🎯 Características

- ✨ **Design moderno e responsivo**
- 📱 **Mobile-first approach**
- ♿ **Acessibilidade (ARIA labels)**
- 🎨 **Paleta de cores consistente**
- 🔄 **Navegação intuitiva**
- 📦 **Grid de produtos**
- 🏷️ **Categorias de produtos**
- 🔍 **Menu hamburger para mobile**

## 📂 Estrutura do Projeto

```
ecommerce-syntaxwear/
├── index.html              # Página principal
├── README.md              # Este arquivo
├── assets/                # Arquivos estáticos
│   ├── fonts/            # Fontes customizadas
│   └── images/
│       ├── banners/      # Imagens de banners (hero section)
│       ├── icons/        # Ícones SVG (logo, user, help, etc)
│       └── products/     # Imagens dos produtos
├── css/                   # Estilos CSS
│   ├── base/
│   │   ├── reset.css     # Reset CSS moderno (Andy Bell)
│   │   ├── variables.css # Variáveis CSS (fontes, cores, etc)
│   │   └── base.css      # Estilos base e componentes reutilizáveis
│   └── components/
│       ├── header.css    # Cabeçalho fixo com navegação
│       ├── hero.css      # Seção hero/banner
│       ├── product-category.css  # Seção de categorias
│       ├── product-grid.css      # Grid de produtos
│       └── footer.css    # Rodapé
└── pages/                # Páginas adicionais (em desenvolvimento)
```

## 🛠️ Tecnologias

- **HTML5** - Semântica e acessibilidade
- **CSS3** - Flexbox, Grid, Media Queries
- **JavaScript** - Menu mobile interativo
- **Google Fonts** - Tipografia (Ubuntu)

## 🎨 Design & Branding

### Paleta de Cores
- **Cor primária (Violeta):** `#7c3aed` - Usada em hovers e destaques
- **Cor secundária (Roxo escuro):** `#6329A2` - Texto em botões preenchidos
- **Cinza neutro:** `#333333` - Texto principal
- **Fundo:** `#f5f5f5` - Background claro
- **Branco:** `#ffffff` - Cards e componentes

### Tipografia
- **Fonte principal:** Ubuntu (300, 400, 500, 700)
- **Tamanho base de link/nav:** 1.25rem (20px)

## 📱 Responsividade

O site é responsivo com breakpoint principal em **1280px**:

```css
/* Tela grande (desktop) */
- Header com toda a navegação visível
- Menu completo expandido
- Grid de produtos otimizado

/* Tela pequena (tablet/mobile) */
@media (max-width: 1280px) {
- Menu hamburger ativo
- Navegação lateral (drawer)
- Layout adaptado para telas menores
```

## 🎯 Componentes Principais

### Header
- Logo com link para home
- Navegação central (Masculino, Feminino, Outlet)
- Menu direito (Nossas lojas, Sobre)
- Ícones de usuário e ajuda
- Menu mobile hamburger

### Hero Section
- Banner principal com imagem destaque
- Call-to-action com botões

### Product Category
- Seção de categorias de produtos
- Links para filtros

### Product Grid
- Exibição em grid responsivo
- Cards de produtos com imagem, nome, preço e botão de ação

### Footer
- Links e informações adicionais

## 🚀 Como Usar

1. **Clonar o repositório:**
   ```bash
   git clone <url-do-repositorio>
   cd ecommerce-syntaxwear
   ```

2. **Abrir o projeto:**
   - Abra o arquivo `index.html` em seu navegador
   - Ou use um servidor local (Live Server, Python, etc)

3. **Desenvolver:**
   - Edite os arquivos HTML, CSS e JS conforme necessário
   - Os estilos são modularizados por componentes para fácil manutenção

## 📐 Convenções de Código

### CSS
- Classes em **kebab-case** (ex: `.nav-center`, `.btn-filled`)
- Variáveis CSS em `variables.css`
- Um arquivo CSS por componente principal
- Mobile-first com media queries para desktop

### HTML
- Semântica HTML5 (`<header>`, `<nav>`, `<main>`, `<footer>`)
- ARIA labels para acessibilidade
- Alt text em todas as imagens

## 🔧 Customização

### Alterar cores
Edite `css/base/variables.css`:
```css
:root {
    --fonte-principal: 'Ubuntu', sans-serif;
    /* Adicione suas variáveis aqui */
}
```

### Alterar fontes
As fontes são importadas do Google Fonts em `variables.css`

### Adicionar novo componente
1. Crie um novo arquivo em `css/components/seu-componente.css`
2. Importe no `index.html`: `<link rel="stylesheet" href="css/components/seu-componente.css">`

## 📝 TODO

- [ ] Implementar páginas adicionais em `/pages`
- [ ] Adicionar funcionalidade de carrinho
- [ ] Sistema de filtros de produtos
- [ ] Página de detalhes do produto
- [ ] Sistema de autenticação
- [ ] Integração com API de produtos

## 👨‍💻 Desenvolvedor

**Carlos Lamego / DevQuest 2026** - Projeto Frontend

## 📄 Licença

Este projeto é parte do programa DevQuest 2026.

---

**Última atualização:** Abril de 2026
