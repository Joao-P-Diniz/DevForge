# DevForge

Landing page institucional para a DevForge, empresa de desenvolvimento web profissional.

## Funcionalidades

- **Header fixo** com menu hamburger para mobile, backdrop blur e sombra ao rolar
- **Hero** com animações de entrada, shapes abstratas animadas e botões com efeito glow
- **Serviços** com 3 cards em grid responsivo, ícones estilizados e efeito de borda gradiente
- **Sobre** layout duas colunas com estatísticas e placeholder decorativo
- **Depoimentos** 3 cards com texto, avatar e cargo
- **Contato** formulário com validação e estilização nos inputs
- **Footer** com logo, links rápidos, redes sociais (SVG) e copyright

## Tecnologias Utilizadas

- HTML5
- CSS3 (variáveis, flexbox, grid, animações, backdrop-filter)
- Google Fonts (Inter)
- JavaScript vanilla (menu hamburger, scroll shadow)

## Como Executar

1. Clone o repositório
   ```bash
   git clone https://github.com/Joao-P-Diniz/DevForge.git
   ```
2. Abra o arquivo `index.html` no navegador

## Estrutura do Projeto

```
devforge/
├── assets/
│   ├── DF.png
│   ├── DevForge.png
│   └── DevForgeOriginal.png
├── css/
│   └── style.css
├── index.html
└── README.md
```

## Requisitos Técnicos Atendidos

| Requisito | Implementação |
|-----------|---------------|
| `:root` com variáveis | Paleta de cores e escala de espaçamento |
| `box-sizing: border-box` | Reset global |
| `position: fixed` | Header/navbar |
| `display: flex` | Header, hero, sobre, footer |
| `flex-wrap: wrap` | Cards de serviços |
| `gap:` | Grids e cards |
| `transition:` | Hovers em botões, cards e links |
| `::before` / `::after` | Borda gradiente nos cards, underline nos links, shapes do hero |
| Paleta de cores | 3 cores principais (roxo, preto, branco) |
| Espaçamento consistente | 8px, 16px, 24px, 32px, 48px, 64px |
| Google Fonts | Inter |
| IDs para âncoras | hero, servicos, sobre, depoimentos, contato |
| Sem `<br>` | ✅ |

## Responsividade

| Breakpoint | Comportamento |
|------------|---------------|
| > 992px | Layout completo |
| 768–992px | Hero e shapes menores |
| < 768px | Menu hamburger, coluna única |
| < 480px | Shapes ainda menores, stats empilhadas |

## Autor

João Pedro Diniz - [GitHub](https://github.com/Joao-P-Diniz)
