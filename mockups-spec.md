---
versao: "1.0.0"
criado_em: "2026-08-26"
status: "planejado"
projeto: "Studio Pitaya"
objetivo: "17 mockups nível studio + vídeo LUMINA para portfólio V3 e novos cases"
gerador: "Higgsfield (Lucas) · Agente especifica, organiza e integra"
padrao_saida: "webp ≤ 1000px"
destino: "studio-pitaya-repo/projects/<slug>/mockups/ + commit + push + project.json mockups[]"
---

# Especificação de 17 Mockups + Vídeo LUMINA

> Organizado por **frente** (categoria de entrega). Cada item tem: slug do projeto, descritivo do mockup, referências visuais/estruturais, e uso no portfólio V3.

---

## 🌐 Frente 1 — Sites / Web (6 mockups)

Projetos de **landing pages e sites imersivos** para o portfólio V3 (máx 4–6 destaques na home).

| # | Slug Projeto | Mockup | Descritivo | Referências |
|---|--------------|--------|------------|-------------|
| 1 | `studio-pitaya-v3` | `hero-canvas-3d.webp` | Hero da V3: canvas WebGL 3D fullscreen (partículas morph + big typography Panchang) — estado inicial | PRD `site-studio-pitaya-v3.md` §1, §4 RF-01; spec-ia §7 cores/tokens; demo SmartDuke Prism/Zest |
| 2 | `studio-pitaya-v3` | `projetos-cards.webp` | Seção Projetos: 4–6 cards com thumb, hover tilt 3D, stack tags, link → case | PRD §4 RF-06; spec-ia §8 cards; `projects/*.json` existentes |
| 3 | `studio-pitaya-v3` | `servicos-marquee.webp` | Seção Serviços: marquee infinita "Branding · Web Design · Cardápios · Marketing Digital" + cards | PRD §4 RF-05; spec-ia §8 tags/badges |
| 4 | `novo-case-web` | `landing-hero.webp` | Landing page nova (cliente fictício/real): hero com scroll-scrub spritesheet/GSAP, CTA Pitaya Pink | `lumina-skin` (hero scroll-scrub); `mare` (hero 360vh vídeo); spec-ia §10 motion [A DEFINIR] |
| 5 | `novo-case-web` | `landing-section.webp` | Seção de conteúdo: ingredientes/benefícios com preview sticky, grid 12 col, respiro 96px | `lumina-skin` ingredients; `mare` ingredientes sticky; spec-ia §7 grid/spacing |
| 6 | `novo-case-web` | `landing-footer-cta.webp` | Footer/CTA final: WhatsApp + Instagram + email, contraste AA, alvo 44px | PRD §6 fluxo contato; spec-ia §9 a11y; `gooday` feed mockup |

---

## 🎨 Frente 2 — Branding / Identidade + Aplicações (5 mockups)

**Identidade visual completa** + aplicações digitais e físicas (estilo Quintal de Minas).

| # | Slug Projeto | Mockup | Descritivo | Referências |
|---|--------------|--------|------------|-------------|
| 7 | `novo-case-branding` | `identidade-sistema.webp` | Sistema de identidade: logo principal (Pitaya Pink), negativo (Warm White), 8 variações cromáticas, pattern | spec-ia §6 logo system; `branding/logo/variacoes/`; `quintal-de-minas` identidade-aplicada |
| 8 | `novo-case-branding` | `aplicacao-digital.webp` | Aplicações digitais: avatar social, cover LinkedIn/Insta, email signature, favicon set | spec-ia §12 logo social media; `gooday` splash-screen/feed; `branding/logo/variacoes/SOCIAL-MEDIA.af` |
| 9 | `novo-case-branding` | `aplicacao-papelaria.webp` | Papelaria: cartão de visita (frente/verso), carta timbrada, envelope, tag de produto | `quintal-de-minas` banner/embalagem; spec-ia §7 spacing/grid |
| 10 | `novo-case-branding` | `sinalizacao-externa.webp` | Sinalização: outdoor/billboard + mural/fachada — mockup em contexto urbano (rua, pôr do sol) | `quintal-de-minas` quintal-billboard.webp + quintal-murral.webp; spec-ia §7 cores |
| 11 | `novo-case-branding` | `brand-guidelines.webp` | Página de brand guidelines: paleta, tipografia Panchang (Display/Title/Subtitle/Body), iconografia outline | spec-ia §7–8 completo; `branding/referencias/Design System - Pitaya.pdf` |

---

## 📦 Frente 3 — Embalagens / Produto Físico (4 mockups)

**Packaging e produto** — nível studio, lifestyle + close-up com mãos/pessoa.

| # | Slug Projeto | Mockup | Descritivo | Referências |
|---|--------------|--------|------------|-------------|
| 12 | `novo-case-produto` | `embalagem-hero.webp` | Embalagem principal (caixa/frasco) hero: levitating/floating, iluminação studio, Pitaya Pink accent | `quintal-de-minas` quintal-embalagem.webp; Higgsfield mode `product_shot`/`conceptual_product` |
| 13 | `novo-case-produto` | `embalagem-closeup-maos.webp` | Close-up com mãos: pessoa segurando/abrindo, textura, detalhe do logo em variação cromática | Higgsfield mode `closeup_product_with_person`; spec-ia §6 logo variação p/ contraste |
| 14 | `novo-case-produto` | `embalagem-lifestyle.webp` | Lifestyle: produto em uso real (banheiro, cozinha, mesa) — luz natural, sensorial | Higgsfield mode `lifestyle_scene`/`moodboard_pin`; `quintal-de-minas` table-sunset |
| 15 | `novo-case-produto` | `kit-completo.webp` | Kit/unboxing: caixa + frasco + acessórios (pincel, espátula) — composição flat-lay premium | Higgsfield mode `social_carousel`/`ad_creative_pack`; `mare` dish-01/table-sunset |

---

## 📱 Frente 4 — Social / Marketing / Vídeo (2 mockups + 1 vídeo)

**Criativos para redes sociais, ads e o vídeo LUMINA.**

| # | Slug Projeto | Mockup | Descritivo | Referências |
|---|--------------|--------|------------|-------------|
| 16 | `lumina-skin` | `social-carousel-01.webp` | Carrossel Instagram (slide 1/3): capa com hero LUMINA + tagline "Ciência + Sensorialidade" | `lumina-skin` mockups existentes; spec-ia §5 voz/tom; Higgsfield mode `social_carousel` |
| 17 | `lumina-skin` | `social-carousel-02.webp` | Carrossel Instagram (slide 2/3): ingredientes ativos + benefícios, layout editorial Panchang | `lumina-skin` ingredients.webp; spec-ia §7 tipografia; Higgsfield mode `moodboard_pin` |
| 18 | `lumina-skin` | `video-lumina.mp4` | **Vídeo LUMINA** (15–30s): hero scroll-scrub spritesheet → ingredientes → texture → CTA WhatsApp — narrado/legendas, seedance 2.0, aspecto 9:16 (Reels/Shorts) + 16:9 (YouTube) | `lumina-skin` project.json deliverables: "scroll-scrub spritesheet"; `mare` mockup-desktop-video.mp4; Higgsfield `generate video` + `seed_audio` narração |

---

## 📁 Estrutura de Destino por Projeto

```
studio-pitaya-repo/projects/
├── studio-pitaya-v3/
│   ├── project.json
│   └── mockups/
│       ├── hero-canvas-3d.webp
│       ├── projetos-cards.webp
│       └── servicos-marquee.webp
├── novo-case-web/
│   ├── project.json
│   └── mockups/
│       ├── landing-hero.webp
│       ├── landing-section.webp
│       └── landing-footer-cta.webp
├── novo-case-branding/
│   ├── project.json
│   └── mockups/
│       ├── identidade-sistema.webp
│       ├── aplicacao-digital.webp
│       ├── aplicacao-papelaria.webp
│       ├── sinalizacao-externa.webp
│       └── brand-guidelines.webp
├── novo-case-produto/
│   ├── project.json
│   └── mockups/
│       ├── embalagem-hero.webp
│       ├── embalagem-closeup-maos.webp
│       ├── embalagem-lifestyle.webp
│       └── kit-completo.webp
└── lumina-skin/ (já existe)
    ├── project.json (atualizar mockups[] + video)
    └── mockups/
        ├── social-carousel-01.webp
        ├── social-carousel-02.webp
        └── video-lumina.mp4
```

---

## ✅ Checklist de Entrega (por mockup)

- [ ] Gerado no Higgsfield (modo correspondente na tabela)
- [ ] Exportado **webp ≤ 1000px** (lado maior)
- [ ] Salvo em `studio-pitaya-repo/projects/<slug>/mockups/`
- [ ] `project.json` atualizado: `mockups[]` (e `video` se aplicável)
- [ ] Commit + push para GitHub (`studio-pitaya-repo`)
- [ ] (Opcional) Copiar para `website/public/img/projects/<slug>/mockups/` para deploy

---

## 🔗 Referências Centrais (sempre consultar)

| Arquivo | Caminho | Uso |
|---------|---------|-----|
| Design System (tokens, componentes, a11y) | `studio-pitaya/spec-ia.md` §7–11 | Cores, tipografia Panchang, spacing 8px, grid, componentes, contraste |
| Logo System (variações, negativo, pattern) | `studio-pitaya/branding/logo/` + `logo-system.md` | Logo correto p/ cada fundo, variações cromáticas, área de proteção |
| PRD Site V3 (estrutura, hero 3D, seções) | `studio-pitaya/prds/site-studio-pitaya-v3.md` | Hero canvas, projetos cards, serviços marquee, CTA WhatsApp |
| Cases Existentes (mockups de referência) | `studio-pitaya-repo/projects/*/mockups/` | Estilo, enquadramento, iluminação, consistência visual |
| Higgsfield Modes | — | `product_shot`, `lifestyle_scene`, `closeup_product_with_person`, `moodboard_pin`, `hero_banner`, `social_carousel`, `ad_creative_pack`, `conceptual_product`, `generate video` |

---

## ⚠️ Regras de Ouro (não negociáveis)

1. **Logo é SEMPRE input do usuário** — nunca gerado por IA (spec-ia §6, decisão 2026-08-01)
2. **Pitaya Pink (#FF007F) ≈ 3.8:1** — só em títulos/destaques/CTAs grandes; texto corrido = Black Ink (spec-ia §9)
3. **Panchang** — fonte única; pesos: Display Bold 56px, Title Medium 32px, Subtitle Regular 20px, Body Light 16px (spec-ia §7)
4. **WebP ≤ 1000px** — padrão de saída para todos os mockups
5. **Vídeo LUMINA** — 2 aspectos (9:16 + 16:9), narração Seed Audio 1.0, estilo Seedance 2.0
6. **Naming**: `<slug>-<descritivo>.webp` (ex: `landing-hero.webp`, `embalagem-closeup-maos.webp`)