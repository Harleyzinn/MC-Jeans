# MC Jeans Industrial - Landing Page Institucional B2B

> **Portal Corporativo** | Parceiro Estratégico Exclusivo Sawary Jeans

![Project Status](https://img.shields.io/badge/status-production_ready-success)
![Version](https://img.shields.io/badge/version-2.1.0-blue)
![Compliance](https://img.shields.io/badge/LGPD-Compliant-brightgreen)
![SEO](https://img.shields.io/badge/SEO-Optimized-orange)

## 📌 Sobre o Projeto

Plataforma institucional de alta performance desenvolvida para a **MC Jeans (Maria do Carmo)**, indústria têxtil focada em manufatura de larga escala e precisão. 

O projeto foi projetado com uma estética **"Dark Industrial"**, transmitindo solidez, tecnologia e autoridade B2B. O site apresenta a capacidade produtiva da empresa, infraestrutura tecnológica (Corte a Laser, CNC, Audaces) e fornece pontos de contato direto com a diretoria.

### 🎯 Principais Funcionalidades

- **Arquitetura Híbrida:** Fluxo principal em *Single-Page Application* (SPA) para conversão rápida, com páginas secundárias dedicadas (Política de Privacidade).
- **Adequação LGPD:** - Modal de consentimento de Cookies com armazenamento local (`localStorage`).
  - Página dedicada de Política de Privacidade.
- **Integração Logística (Google Maps):** Mapas interativos estilizados via CSS (Dark Mode Invert) apontando para a Matriz Fabril e o Showroom de Varejo em Taguaí - SP.
- **Acessibilidade e Usabilidade:** - Botão *Back to Top* condicional ao scroll.
  - Navbar fluida com efeito de *Glassmorphism* dinâmico.
  - Rodapé com script de atualização automática de ano.
- **Contato Dinâmico B2B:** Call-to-Action (CTA) otimizado e botão flutuante persistente integrados à API do WhatsApp.
- **Otimização SEO Avançada:** - Meta tags Open Graph (`og:`) configuradas para gerar rich-cards no WhatsApp/LinkedIn.
  - `robots.txt` para indexação direta pelos motores de busca.
  - `sitemap.xml` hierárquico mapeando as rotas da aplicação.

## 🚀 Tecnologias Utilizadas

Projeto construído de forma nativa e enxuta (Vanilla), garantindo tempo de carregamento instantâneo e pontuação máxima de SEO.

- **HTML5 & XML:** Estruturação semântica multi-páginas e mapeamento de busca.
- **CSS3:** - CSS Grid & Flexbox para layout responsivo.
  - Variáveis de Escopo (`:root`) para padronização da paleta.
  - Filtros CSS avançados para customização de iframes (Mapas).
- **JavaScript (Vanilla):** - APIs nativas de observação de tela (Intersection animado `reveal`).
  - Manipulação de `localStorage` para a política de cookies.

## 📄 Estrutura de Arquivos

```text
mc-jeans-landing/
│
├── index.html                  # Landing Page Principal (Hero, Infraestrutura, Mapa)
├── politica-privacidade.html   # Documentação de Compliance LGPD
├── robots.txt                  # Permissões de rastreamento para Googlebot
├── sitemap.xml                 # Mapeamento de hierarquia para indexação
└── README.md                   # Documentação do Repositório
