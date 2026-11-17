# NCroch's — Portfólio Digital

> Site institucional e vitrine digital para uma marca de peças artesanais em crochê, com identidade visual própria e experiência responsiva.

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-orange)](#status)
[![Categoria](https://img.shields.io/badge/projeto-site%20institucional-blue)](#objetivo)
[![Stack](https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20JavaScript-yellow)](#tecnologias)

---

## Objetivo

A **NCroch's** é uma marca de peças artesanais em crochê. O projeto cria uma presença digital para apresentar a identidade da marca, valorizar o trabalho manual e facilitar o contato de pessoas interessadas em encomendas.

A interface segue uma direção visual editorial, leve e acolhedora. O foco é apresentar a marca e suas criações sem transformar o site em um catálogo genérico.

## Experiência implementada

- Página inicial com apresentação da marca e chamada para conhecer as criações.
- Navegação por âncoras para portfólio, história, processo e encomendas.
- Seções de apresentação institucional e manifesto da marca.
- Categorias demonstrativas para organizar futuras fotografias das peças.
- Explicação do fluxo de encomenda em etapas.
- Chamada para contato e acesso ao Instagram.
- Menu adaptado para dispositivos móveis.
- Assistente visual de encomendas com painel de conversa.
- Layout responsivo e animações sutis de entrada.
- Metadados básicos, ícone e identidade visual com a marca.

**Atenção ao estado do catálogo:** os blocos de categorias ainda utilizam áreas demonstrativas. Eles não representam um catálogo completo nem devem ser interpretados como fotografias reais de produtos.

## Tecnologias

- **HTML5:** estrutura semântica e conteúdo.
- **CSS3:** identidade visual, responsividade e animações.
- **JavaScript:** navegação mobile, interações e assistente de encomendas.
- **Google Fonts:** tipografia DM Sans e Playfair Display.

A versão atual é uma aplicação estática, sem backend, banco de dados ou processamento de pedidos.

## Arquitetura atual

```text
site_ncrochs/
├── index.html       # Estrutura da página e componentes da interface
├── image.png        # Identidade visual / logo
├── css/
│   └── style.css    # Estilos e comportamento responsivo
├── js/
│   └── main.js      # Interações da página e assistente
└── README.md
```

## Fluxo de navegação

```text
Visitante
   │
   ▼
Página inicial
   ├── Conhecer as criações
   ├── Conhecer a marca
   ├── Entender o processo artesanal
   └── Iniciar contato / encomenda
             │
             ▼
      Atendimento externo
      (a integração de envio ainda depende de configuração)
```

## Executar localmente

1. Clone o repositório.
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` em um navegador moderno.

Não é necessário instalar dependências ou iniciar um servidor para visualizar a página estática.

## Estado atual e limitações

**Versão atual: V1 — estrutura institucional em desenvolvimento.**

| Área | Situação |
|---|---|
| Identidade visual e estrutura da Home | Implementadas |
| Navegação responsiva | Implementada |
| Seções institucionais | Implementadas |
| Categorias do portfólio | Estrutura demonstrativa |
| Fotografias reais das peças | Pendente |
| Catálogo com detalhes de produtos | Planejado |
| Envio de encomenda por WhatsApp | Pendente de integração |
| Gestão de conteúdo / painel administrativo | Não implementado |
| Backend e banco de dados | Não implementados |

O assistente atual é uma interface de interação no front-end. Não representa atendimento automatizado conectado a um serviço de IA nem registra encomendas em um servidor.

## Roadmap

### V1 — Presença digital
- [x] Estrutura institucional da página
- [x] Identidade visual inicial
- [x] Layout responsivo
- [x] Navegação mobile
- [x] Seções de marca, portfólio e processo
- [x] Interface inicial do assistente

### V1.1 — Conteúdo real
- [ ] Inserir fotografias autorizadas das peças
- [ ] Substituir áreas demonstrativas por imagens do portfólio
- [ ] Revisar textos, categorias e informações de encomenda
- [ ] Validar a experiência em dispositivos reais

### V2 — Encomendas
- [ ] Integrar chamada de encomenda ao WhatsApp oficial da marca
- [ ] Definir perguntas e dados necessários para orçamento
- [ ] Exibir orientações sobre prazo, disponibilidade e personalização
- [ ] Melhorar acessibilidade e metadados para compartilhamento

### V3 — Catálogo
- [ ] Galeria por categoria
- [ ] Página ou modal de detalhes de cada peça
- [ ] Filtros e navegação pelo catálogo
- [ ] Processo simples de atualização de conteúdo

## Privacidade e conteúdo

O site não possui cadastro, autenticação ou armazenamento remoto de encomendas nesta versão. Fotografias, textos e dados de contato devem ser publicados somente com autorização da responsável pela marca.

## Status

**Em desenvolvimento.** A base institucional está montada; as próximas entregas dependem principalmente da inclusão de conteúdo real e da definição do fluxo de encomendas.

## Autoria

Desenvolvimento por **Bruno Silva**, em colaboração com a responsável pela marca NCroch's.

Instagram: [@ncrochs](https://www.instagram.com/ncrochs/)

---

**Projeto:** NCroch's — Portfólio Digital  
**Categoria:** Desenvolvimento Web / Site Institucional  
**Stack:** HTML, CSS e JavaScript  
**Status:** V1 em desenvolvimento
