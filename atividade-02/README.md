# Atividade 02 - Tailwind CSS

Demonstracao pratica do uso de classes utilitarias do Tailwind CSS com mais de 30 classes diferentes.

## Objetivo

Criar um projeto utilizando o Tailwind CSS aplicando classes para cores, tipografia, espacamentos, dimensoes, bordas, posicionamento, flexbox, grid e responsividade.

## Projeto

O projeto consiste em uma pagina completa com header, cards, features, formulario, tabela e alertas, todos estilizados com classes Tailwind.

## Classes Utilizadas (30+)

### Cores e Background
| Classe | Funcao |
|--------|--------|
| `bg-gray-50` | Cor de fundo cinza claro |
| `bg-white` | Cor de fundo branca |
| `bg-blue-50` | Fundo azul claro (alertas) |
| `bg-blue-100` | Fundo azul medio (badges) |
| `bg-blue-600` | Fundo azul principal |
| `bg-blue-700` | Fundo azul escuro (hover) |
| `bg-gradient-to-r` | Gradiente horizontal |
| `from-blue-600` | Cor inicial do gradiente |
| `to-purple-600` | Cor final do gradiente |
| `text-white` | Cor do texto branca |
| `text-gray-800` | Texto cinza escuro |
| `text-gray-600` | Texto cinza medio |
| `text-blue-600` | Texto azul |
| `text-green-600` | Texto verde |
| `text-purple-600` | Texto roxo |
| `text-yellow-600` | Texto amarelo |
| `text-red-600` | Texto vermelho |
| `text-blue-300` | Texto azul claro |
| `text-gray-400` | Texto cinza claro |
| `text-gray-900` | Texto preto |

### Tipografia
| Classe | Funcao |
|--------|--------|
| `text-4xl` | Tamanho de fonte extra grande |
| `text-5xl` | Tamanho de fonte gigante |
| `text-2xl` | Tamanho de fonte grande |
| `text-xl` | Tamanho de fonte medio-grande |
| `text-lg` | Tamanho de fonte medio |
| `text-base` | Tamanho de fonte base |
| `text-sm` | Tamanho de fonte pequena |
| `font-bold` | Peso da fonte negrito |
| `font-semibold` | Peso da fonte semi-negrito |
| `font-medium` | Peso da fonte medio |

### Espacamento (Padding e Margin)
| Classe | Funcao |
|--------|--------|
| `py-16` | Padding vertical 4rem |
| `px-4` | Padding horizontal 1rem |
| `py-8` | Padding vertical 2rem |
| `py-4` | Padding vertical 1rem |
| `p-6` | Padding 1.5rem |
| `p-8` | Padding 2rem |
| `mb-4` | Margin bottom 1rem |
| `mb-8` | Margin bottom 2rem |
| `mt-4` | Margin top 1rem |
| `mt-16` | Margin top 4rem |
| `mx-auto` | Margin horizontal automatico |

### Dimensoes
| Classe | Funcao |
|--------|--------|
| `w-full` | Largura 100% |
| `h-48` | Altura 12rem |
| `min-h-screen` | Altura minima da tela |
| `max-w-6xl` | Largura maxima 72rem |
| `max-w-2xl` | Largura maxima 42rem |

### Bordas
| Classe | Funcao |
|--------|--------|
| `rounded-lg` | Borda arredondada 0.5rem |
| `rounded-xl` | Borda arredondada 0.75rem |
| `rounded-full` | Borda completamente arredondada |
| `border-2` | Borda de 2px |
| `border-gray-300` | Cor da borda cinza |
| `border-blue-200` | Cor da borda azul claro |

### Flexbox
| Classe | Funcao |
|--------|--------|
| `flex` | Display flex |
| `flex-col` | Direcao coluna |
| `items-center` | Alinhamento vertical centro |
| `justify-center` | Alinhamento horizontal centro |
| `justify-between` | Espacamento entre elementos |
| `gap-2` | Espacamento entre itens 0.5rem |
| `gap-4` | Espacamento entre itens 1rem |
| `gap-6` | Espacamento entre itens 1.5rem |
| `flex-1` | Flex grow 1 |
| `flex-wrap` | Quebra de linha flex |

### Grid
| Classe | Funcao |
|--------|--------|
| `grid` | Display grid |
| `grid-cols-1` | 1 coluna |
| `grid-cols-2` | 2 colunas |
| `grid-cols-3` | 3 colunas |
| `grid-cols-4` | 4 colunas |
| `gap-6` | Espacamento entre colunas 1.5rem |

### Responsividade
| Classe | Funcao |
|--------|--------|
| `md:grid-cols-2` | 2 colunas em tablet |
| `lg:grid-cols-3` | 3 colunas em desktop |
| `md:flex-row` | Flex row em tablet |
| `md:text-left` | Texto alinhado a esquerda em tablet |
| `lg:text-5xl` | Fonte maior em desktop |

### Outras Propriedades
| Classe | Funcao |
|--------|--------|
| `shadow-lg` | Sombra grande |
| `shadow-md` | Sombra media |
| `shadow-2xl` | Sombra extra grande |
| `hover:shadow-2xl` | Sombra no hover |
| `transform` | Transformacao CSS |
| `hover:-translate-y-2` | Movimento para cima no hover |
| `transition-all` | Transicao suave |
| `transition-colors` | Transicao de cores |
| `duration-300` | Duracao da transicao 300ms |
| `overflow-x-auto` | Scroll horizontal automatico |
| `rounded-lg` | Borda arredondada |

## Estrutura do Projeto

```
atividade-02/
├── index.html
└── README.md
```

## Como Executar

1. Abra o arquivo `index.html` em um navegador
2. Ou use uma extensao como "Live Server" no VS Code

## Screenshots

### Codigo
![Codigo](./screenshots/codigo.png)

### Aplicacao em Funcionamento
![Aplicacao](./screenshots/app.png)

## Link do Projeto

Repositorio: https://github.com/Gusleme/frameworks_css

## Conceitos Aplicados

- Classes utilitarias para cores e backgrounds
- Sistema de tipografia responsivo
- Espacamento com padding e margin
- Flexbox para layout de componentes
- Grid para layouts complexos
- Responsividade com breakpoints
- Estados hover e transicoes
- Sombras e bordas
- Formularios estilizados
- Tabelas responsivas