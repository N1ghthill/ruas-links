# ruas-links

Página estilo Linktree para centralizar os canais profissionais da Ruas.dev.

## Estrutura

```text
ruas-links/
├── index.html
├── assets/
│   ├── css/style.css
│   ├── js/main.js
│   └── img/
│       ├── brand/
│       └── projects/
└── README.md
```

## Rodar localmente

```bash
cd /home/irving/ruas/repos/ruas-links
python3 -m http.server 8080
```

Abra `http://localhost:8080`.

## Atualizações rápidas

- Texto principal: `index.html`
- Lista de links: `index.html` (bloco `.link-stack`)
- Cores/tipografia/efeitos: `assets/css/style.css`
- Microinterações: `assets/js/main.js`

## Fontes de conteúdo

A página foi montada com base em:
- Site profissional: `https://ruas.dev.br`
- Repositórios e canais oficiais: `N1ghthill/botassist-whatsapp` e perfil `N1ghthill`
