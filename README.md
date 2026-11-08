# 7DaysOfCode

Repositório para o desafio **7 Days of Code** da Alura.

> :construction: Projeto em construção :construction:

O resultado do desafio é a página **"Como eu aprendo"** ([index.html](index.html)): um guia para os professores do Murilo, preparado pelos pais dele. Ele reúne dicas práticas para apoiar o aprendizado em cada momento do dia na escola.

📄 Documento de referência: [Google Docs][googleDocsLink]

## Índice

- [Sobre a página](#sobre-a-página)
- [Como visualizar](#como-visualizar)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Diário do desafio](#diário-do-desafio)

## Sobre a página

O guia está dividido por ambiente da escola:

| Seção | Âncora |
| --- | --- |
| Na sala de aula | `#sala` |
| No refeitório | `#refeitorio` |
| Na educação física | `#educacao-fisica` |
| Na biblioteca | `#biblioteca` |
| Na aula de música | `#musica` |
| Na aula de artes | `#artes` |
| Outras coisas sobre mim | `#sobre` |

Funcionalidades:

- **Navegação fixa** no topo, com atalhos para cada seção e botão "voltar ao topo".
- **Grupos recolhíveis** (ex.: "Quando eu chego na sala") para facilitar a leitura.
- **Checklist interativo**: cada dica pode ser marcada, e as marcações ficam salvas no navegador (`localStorage`).
- **Tema claro e escuro**, que acompanha a preferência do sistema.
- **Layout responsivo**, pensado para leitura no celular.
- **Arquivo único**: HTML, CSS, JavaScript e a foto (em base64) ficam todos no `index.html`. Só as fontes vêm do Google Fonts.
- A página tem `noindex, nofollow`, então não aparece em buscadores.

## Como visualizar

Não precisa instalar nada nem fazer build. Basta abrir o arquivo no navegador:

```bash
git clone https://github.com/alvaro-rosa/7DaysOfCode.git
cd 7DaysOfCode
open index.html        # macOS  (Linux: xdg-open index.html)
```

Também é possível publicar a página com o **GitHub Pages** (Settings → Pages → branch `main`, pasta raiz).

## Estrutura do repositório

```
7DaysOfCode/
├── index.html      # Página "Como eu aprendo" (autocontida)
├── murilo.jpg      # Foto usada na capa
├── Images/
│   └── murilo.jpg  # Cópia da foto
└── README.md
```

## Diário do desafio

### Dia 1
Criar um repositório do zero a partir da própria página do GitHub.

### Dia 2
_A preencher._

### Dia 3
_A preencher._

### Dia 4
_A preencher._

### Dia 5
_A preencher._

### Dia 6
_A preencher._

### Dia 7
_A preencher._

[googleDocsLink]: https://docs.google.com/document/d/1L6sAc7w-RJjWMXYXahhXV0td4FzdTSnMmP5epf-uj0s/edit?tab=t.0
