# Aula 07 - Atividade Pratica: Frameworks CSS

## Atividade Realizada

Estudo pratico e comparacao de frameworks CSS modernos atraves de exemplos de codigo.

## O que foi feito

- Criacao de exemplos com **Tailwind CSS** (classes utilitarias)
- Criacao de exemplos com **Bootstrap 5** (componentes prontos)
- Criacao de exemplos com **Bulma** (framework flexbox)
- Demonstrativo de **CSS Modules** (escopo local)
- Demonstrativo de **Styled Components** (CSS-in-JS)
- Aplicacao de metodologia **BEM** na nomenclatura
- Estrutura de arquivos organizada por componente

## Tecnologias Testadas

| Framework | Tipo | Status |
|-----------|------|--------|
| Tailwind CSS | Utilitario | Testado |
| Bootstrap 5 | Componentes | Testado |
| Bulma | Componentes | Testado |
| CSS Modules | Escopo local | Testado |
| Styled Components | CSS-in-JS | Testado |

## Estrutura de Exemplo Criada

```
src/
├── styles/
│   ├── variables.css      # Custom properties (design tokens)
│   ├── reset.css          # Normalize/reset
│   └── globals.css        # Estilos globais
├── components/
│   ├── Button/
│   │   ├── Button.jsx
│   │   ├── Button.module.css    # CSS Modules
│   │   └── Button.styled.js     # Styled Components
│   ├── Card/
│   │   ├── Card.jsx
│   │   └── Card.module.css
│   └── Navbar/
│       ├── Navbar.jsx
│       └── Navbar.module.css
└── tailwind-examples/
    ├── buttons.html
    ├── cards.html
    └── grid.html
```

## Conceitos Aplicados

- Mobile-first responsivo
- Design tokens com variaveis CSS
- Nomenclatura BEM consistente
- Escopo local com CSS Modules
- Componentes estilizados com Styled Components
- Classes utilitarias Tailwind
- Componentes Bootstrap/Bulma

## Referencias

- Tailwind: https://tailwindcss.com/docs
- Bootstrap: https://getbootstrap.com/docs
- Bulma: https://bulma.io/documentation
- BEM: https://getbem.com
- CSS Modules: https://github.com/css-modules/css-modules