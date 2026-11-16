# 🏎️ Desafio Pit Wall

Interface web temática inspirada no universo da Fórmula 1, desenvolvida para exibição de informações de pista, cards de pilotos, formulários de cadastro/edição e tabelas de dados com filtros.

## 📋 Sobre o Projeto

O **Desafio Pit Wall** é uma aplicação front-end focada em estética automobilística, utilizando uma paleta de cores escura (*dark mode*) combinada com o vermelho característico das pistas e tipografia esportiva (`Titillium Web`). 

O layout conta com seções bem definidas que simulam um painel de telemetria e gestão de equipe/campeonato, incluindo detalhes visuais como a zebra da pista (*kerb*) e identificadores de cores por piloto.

## ✨ Funcionalidades e Componentes Visuais

- **Barra de Navegação (`Topbar`):** Cabeçalho fixo com logotipo estilizado e links de navegação.
- **Seção Principal (`Hero`):** Banner com recorte diagonal em gradiente, imagem de fundo focalizada, chamada principal e indicadores numéricos da pista (`Track Info`).
- **Zebra de Pista (`Kerb`):** Divisor visual criado puramente com CSS (`repeating-linear-gradient`).
- **Grid de Pilotos:** Cards responsivos em CSS Grid com numeração em marca d'água e bordas superiores personalizadas por equipe/piloto:
  - Leclerc (Vermelho Ferrari)
  - Piastri (Laranja McLaren)
  - Russell (Ciano Mercedes)
  - Bortoleto (Verde Sauber)
- **Formulários Estilizados:** Campos de texto, seleção e botões com estados de foco e hover personalizados.
- **Filtros e Tabelas:** Área de busca/filtragem e tabela responsiva com botões de ação para gerenciamento de registros.
- **Design Responsivo:** Adaptação completa para dispositivos móveis (`@media (max-width: 768px)`), reorganizando grids, menus e tabelas com rolagem horizontal.

## 🛠️ Tecnologias Utilizadas

- **HTML5** (`index.html`)
- **CSS3** (`styles.css`) — Variáveis CSS (`:root`), Flexbox, CSS Grid, Gradientes e Media Queries.
- **Google Fonts** — Fonte *Titillium Web*.

## 📁 Estrutura de Arquivos

```text
desafio-pit-wall/
├── img/
│   └── piloto.jpg      # Imagem de destaque da seção Hero
├── index.html          # Estrutura principal da página
├── styles.css          # Folha de estilos completa
└── README.md           # Documentação do projeto