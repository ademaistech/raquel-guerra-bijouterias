# Raquel Guerra Bijouterias — Landing Page

Landing page de alta conversão para a **Raquel Guerra Bijouterias**, ateliê e loja de
bijuterias autorais (vidro fundido, latão e couro) em Belo Horizonte - MG.

Site estático em **HTML/CSS/JS puro**, sem dependências de build — responsivo,
acessível e otimizado para SEO.

## Estrutura

```
site/
├── index.html        # Página (HTML semântico, Open Graph, JSON-LD LocalBusiness)
├── css/styles.css    # Sistema de design, layout e animações
├── js/main.js        # Menu mobile, scroll-reveal, WhatsApp flutuante
└── img/              # Fotos das peças e do ateliê

landing-page-para-loja-de-bijuterias/
└── ...               # Bundle de design original (Claude Design)
```

## Rodar localmente

Basta servir a pasta `site/` com qualquer servidor estático, por exemplo:

```bash
npx http-server site -p 4321
```

E abrir http://localhost:4321.

## Destaques

- **Design editorial** — Playfair Display / DM Sans / Space Grotesk, paleta areia/marrom/cobre
- **Responsivo** — layout fluido (`clamp()`), menu hambúrguer no mobile
- **Movimento** — hero com zoom, scroll-reveal, botão flutuante de WhatsApp
- **Acessibilidade** — skip-link, ARIA, `prefers-reduced-motion`
- **SEO** — meta tags Open Graph e dados estruturados `JewelryStore`

## Contato

- WhatsApp: [+55 31 99812-1202](https://wa.me/5531998121202)
- Endereço: R. Itaguaí, 441 - Alto Caiçaras, Belo Horizonte - MG, 30775-110
- Horário: Ter a Sáb · 09h às 17h
