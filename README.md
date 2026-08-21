# Studio Pitaya — Projetos

Repositório central de dados e mídias dos projetos do Studio Pitaya. Cada pasta em
`projects/` contém um `project.json` (dados do projeto) e os assets de apresentação
(mockups, embalagens, vídeos) que alimentam o site do estúdio — cards, detalhes e
galeria de mockups.

![status](https://img.shields.io/badge/status-ativo-brightgreen)
![formato](https://img.shields.io/badge/assets-webp%20%2B%20mp4-blue)
![licenca](https://img.shields.io/badge/uso-restrito-red)

## Demonstração

O conteúdo deste repositório é consumido pelo site do Studio Pitaya via API própria,
com cache no navegador. Os arquivos também podem ser acessados diretamente por aqui,
organizados por projeto.

## Estrutura

```
projects.json                  índice dos projetos publicados
projects/<slug>/project.json   dados do projeto (template abaixo)
projects/<slug>/mockups/       mockups de site, produto e embalagem (webp)
projects/<slug>/images/        fotos e arte final (webp)
projects/<slug>/video/         vídeos de demonstração (mp4 720p)
```

### Template de project.json

```json
{
  "slug": "nome-do-projeto",
  "name": "NOME",
  "category": "branding | web | cardapio | marketing",
  "shortDescription": "Frase de uma linha para o card.",
  "description": "Descrição longa para a tela de detalhes.",
  "thumbnail": "mockups/arquivo.webp",
  "video": null,
  "gallery": ["caminhos relativos"],
  "mockups": ["caminhos relativos"],
  "year": 2026,
  "tags": [],
  "stack": [],
  "deliverables": [],
  "liveUrl": ""
}
```

Regras de mídia: imagens em webp com largura máxima de 1000px; vídeos em mp4 720p,
sem áudio quando demo de interface, com `+faststart`.

## Funcionalidades

- Fonte única de verdade para cards, detalhes e galeria de mockups do site.
- Publicação de projeto novo = criar pasta + commit.
- Remoção da vitrine sem deletar histórico: tirar o slug do índice.

## Tecnologias

Markdown, JSON e convenção de pastas. Nenhuma dependência.

## Como contribuir

Fluxo do estúdio: gerar/atualizar mídias na pasta do projeto, ajustar o
project.json se necessário e commitar na branch main. O site reflete na próxima
revalidação.

## Licença e autor

Conteúdo proprietário do Studio Pitaya — uso restrito. Autor: Lucas (Studio Pitaya).
