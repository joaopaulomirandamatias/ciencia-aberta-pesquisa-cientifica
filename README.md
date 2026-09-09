# Pré-registro e ciência aberta com OSF e Zenodo: passo a passo (MirandasTech)

Manual em formato de slides (48) para registrar o plano antes de coletar e abrir a pesquisa com responsabilidade: o que é ciência aberta (UNESCO) e por que pré-registrar (COS, Registered Reports, TOP Guidelines); pré-registro na prática com `preregistro.py` (modelos AsPredicted, OSF, revisão sistemática), OSF passo a passo (projeto, registro, embargo, DOI imutável), AsPredicted, PROSPERO e ReBEC; plano de gestão de dados (`plano_gestao_dados.py`, DMPTool), LGPD/TCLE, princípios FAIR, re3data e licenças Creative Commons; depósito no Zenodo (políticas, upload, versões, DOI de conceito × versão, sandbox, comunidades) com `deposito_zenodo.py` que bloqueia dado pessoal e gera o `.zenodo.json`; preprints (SciELO Preprints, arXiv, OSF Preprints, Figshare), política dos periódicos (Open policy finder) e ORCID; erros comuns, checklist, glossário com popovers e referências. Capturas reais e datadas (09/09/2026) sem login; nenhum registro, depósito ou preprint foi criado.

**Manual on-line:** https://cienciaaberta.mirandastech.com.br/ · **PDF:** https://cienciaaberta.mirandastech.com.br/manual.pdf

Manuais irmãos: **Bibliometria** — https://bibliometria.mirandastech.com.br/ · **Análise de dados** — https://dados.mirandastech.com.br/ · **Git e GitHub** — https://git.mirandastech.com.br/ · **LaTeX** — https://latex.mirandastech.com.br/ · **Busca em bases** — https://busca.mirandastech.com.br/ · **Revisão sistemática com PRISMA 2020** — https://prisma.mirandastech.com.br/ · **Zotero** — https://zotero.mirandastech.com.br/ · **Metodologia** — https://metodologia.mirandastech.com.br/ · **Gemini Notebook** — https://notebook.mirandastech.com.br/ · **Uso de IA na pesquisa** — https://manual.mirandastech.com.br/ · **Plugin Pesquisa** — https://plugin.mirandastech.com.br/ · Hub: https://www.mirandastech.com.br/pesquisa

| Pasta | O que há |
|---|---|
| `manual/` | deck HTML autônomo, PDF, fonte do artefato e `fatos_verificados.md` (fontes e execuções conferidas em 09/09/2026) |
| `site/` | o que o servidor serve (`index.html`, `manual.pdf`) |
| `capturas/` | 34 capturas reais, 09/09/2026 (páginas públicas; 3 figuras de terminal com saídas reais) |
| `scripts/preregistro.py` | rascunho do pré-registro com as perguntas do modelo (AsPredicted, OSF ou revisão sistemática) |
| `scripts/deposito_zenodo.py` | confere a pasta (tamanho, README, segredos, CPF, formatos), grava `.zenodo.json`, imprime o checklist FAIR; não envia nada |
| `scripts/plano_gestao_dados.py` | plano de gestão de dados em 7 seções |
| `scripts/gerar_deck.py` | regenera HTML e PDF a partir do fonte |
| `skills/ciencia-aberta-preregistro/` | skill do agente (cópia sincronizada do plugin Pesquisa MirandasTech) |
| `Dockerfile` · `Caddyfile` · `railway.json` | deploy estático (Caddy) |
| `.github/workflows/verificar.yml` | CI: integridade do deck e capturas referenciadas |

## Os manuais juntos
Este manual cobre o **registro e a abertura**: o plano registrado antes da coleta (manual de Metodologia), os dados e o código depositados com DOI (manuais de Git e de Análise de dados), o preprint ligado ao artigo. No plugin **Pesquisa MirandasTech**, a skill `ciencia-aberta-preregistro` prepara rascunhos e confere pastas; o aluno registra, faz o upload e publica.

## Como citar
MATIAS, J. P. M. *Pré-registro e ciência aberta com OSF e Zenodo: passo a passo.* MirandasTech, v1.0, set. 2026. CC BY 4.0.

## Declaração de uso de IA
Escrito com assistência de IA (Claude, Anthropic) na estruturação, redação, automação das capturas e execução dos scripts. Fatos conferidos nas fontes oficiais em 09/09/2026 (lista em `manual/fatos_verificados.md`); nenhuma captura com login; nenhum registro, depósito ou preprint foi criado. O autor responde integralmente pelo conteúdo. OSF/COS, Zenodo/CERN/OpenAIRE, PROSPERO/CRD, AsPredicted, ReBEC/Fiocruz, SciELO, arXiv, Creative Commons, GO FAIR, DMPTool, UNESCO, re3data, ORCID, Jisc e os demais serviços citados são marcas e projetos de terceiros; este manual não tem vínculo com eles.