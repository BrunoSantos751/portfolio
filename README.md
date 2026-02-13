# Portfolio - Bruno Santos

Um portfolio pessoal moderno e responsivo, construído com HTML, CSS e JavaScript vanilla.

## 📋 Descrição

Este é um site de portfolio minimalista que apresenta uma estudante de Ciência da Computação, seus projetos e habilidades técnicas. O design moderno inclui tema claro/escuro e animações suaves ao fazer scroll.

## 🎨 Características

- **Tema Claro/Escuro** - Toggle entre temas com persistência visual
- **Design Responsivo** - Funciona perfeitamente em dispositivos móveis e desktop
- **Animações Suaves** - Elementos aparecem com animações ao fazer scroll
- **Navbar Fixa** - Navegação flutuante para fácil acesso às seções
- **Seções Bem Organizadas:**
  - Hero section com apresentação pessoal
  - Sobre mim com skills técnicas
  - Galeria de projetos
  - Contato

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (com animações e gradientes)
- JavaScript Vanilla
- Font Awesome (ícones)

## 📦 Estrutura do Projeto

```
portfolio/
├── index.html      # Estrutura HTML do site
├── style.css       # Estilos e layout
├── script.js       # Funcionalidades JavaScript
└── README.md       # Este arquivo
```

## 🚀 Como Usar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/BrunoSantos751/portfolio.git
   cd portfolio
   ```

2. **Abra no navegador:**
   - Abra o arquivo `index.html` diretamente no seu navegador
   - Ou use um servidor local (Ex: Live Server no VS Code)

3. **Personalize o conteúdo:**
   - Edite `index.html` com suas informações pessoais
   - Customize cores e estilos em `style.css`
   - Adicione novas funcionalidades em `script.js`

## ⚙️ Como Funciona

### Dark Mode
O JavaScript detecta cliques no botão de tema e alterna a classe `light` no body, aplicando o tema claro ou escuro conforme necessário.

### Animações ao Scroll
Usa a API `IntersectionObserver` para detectar quando elementos entram na viewport e anima sua aparição com a classe `show`.

## 🎯 Seções do Site

- **Hero** - Apresentação inicial com chamada para ação
- **Sobre** - Descrição pessoal e stack tecnológico
- **Projetos** - Galeria de projetos com descrições
- **Contato** - Links para redes sociais e formas de contato

## 📱 Responsividade

O site é totalmente responsivo com pontos de quebra (breakpoints) para:
- Mobile (até 768px)
- Tablet (768px a 1024px)
- Desktop (acima de 1024px)

## 🔗 Links Úteis

- Font Awesome: https://fontawesome.com/

## 📝 Licença

Este projeto é de código aberto e pode ser utilizado livremente como base para seu próprio portfolio.

---

**Desenvolvido com ❤️ por Bruno Santos**
