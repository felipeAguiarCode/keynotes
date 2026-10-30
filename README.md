# Keynotes

Apresentações interativas em HTML, cada uma em um único arquivo, prontas para abrir no navegador.

**Página publicada:** https://felipeaguiarcode.github.io/keynotes/

## Índice por tema

### Engenharia com IA

| Keynote | Descrição | Slides | Links |
| --- | --- | --- | --- |
| **Vibe Coding sem Doom Loop** | Origem do vibe coding, doom loop, planejamento, spec-driven development, revisão e depuração. Cockpit 3D, morph entre objetos, camada de jogo e notas do apresentador. | 56 slides, 7 capítulos | [Abrir online](https://felipeaguiarcode.github.io/keynotes/engenharia-com-ia/vibe-coding-sem-doom-loop.html) · [Arquivo](engenharia-com-ia/vibe-coding-sem-doom-loop.html) |

### Dados

| Keynote | Descrição | Slides | Links |
| --- | --- | --- | --- |
| **Dados com Claude Code e Python** | Apresentação interativa da mentoria de análise de dados com Claude Code e Python. Interface tática em coral, preto e branco. | 40 slides | [Abrir online](https://felipeaguiarcode.github.io/keynotes/dados/dados-com-claude-code-e-python.html) · [Arquivo](dados/dados-com-claude-code-e-python.html) |

## Estrutura

```
keynotes/
├─ index.html            página raiz do GitHub Pages
├─ README.md             este índice
├─ engenharia-com-ia/    keynotes do tema Engenharia com IA
├─ dados/                keynotes do tema Dados
└─ .templates/           templates locais (fora do git)
```

## Como adicionar um keynote

1. Crie o keynote a partir de um template em `.templates/` (a pasta fica só na máquina local, está no `.gitignore`).
2. Salve o arquivo final em `<tema>/<slug>.html`, por exemplo `dados/pandas-na-pratica.html`. Para um tema novo, crie uma pasta nova.
3. Adicione uma linha na tabela do tema neste README.
4. Adicione um card no `index.html`, dentro da seção do tema.
5. Faça commit e push na `main`: o GitHub Pages publica sozinho em alguns minutos.
