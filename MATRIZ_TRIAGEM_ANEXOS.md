# Matriz de triagem dos anexos enviados em 12/06/2026

**Pedido do autor:** "vai ter coisa que é o mesmo objeto, a diferença é a evolução do documento. organize isso também no GITHUB e exclua versões primárias, mantenha a última."

**Total recebido:** 72 arquivos em 5 lotes.

**Critério aplicado:**
- Versões evolutivas confirmadas por hash MD5 e metadados (data de modificação, contagem de palavras, autor).
- Quando há DOCX editável **e** PDF de apresentação da mesma versão final → manter ambos (DOCX para edição futura; PDF para citação/arquivo).
- Quando há PPTX e DOCX da mesma apresentação → manter ambos (PPTX para apresentar; DOCX como roteiro).
- Versões anteriores ao **projeto de qualificação v1** (já no repo) ficam em pasta `00_Projeto/historico/` (não são "versões evolutivas" do v1, mas predecessores históricos do projeto — valor de rastreabilidade).
- Duplicatas exatas (mesmo MD5) são descartadas sem perda.

---

## A. Linhagem CONTRAFAÇÃO HONDURAS — manter apenas as 2 versões finais

| # | Arquivo | Hash | Modificado | Palavras | Decisão |
|---|---------|------|------------|----------|---------|
| 1 | `Contrafacao-da-Autonomia-Politica-13.pdf` (pdf-lib, lote 2) | b18f36aa | 17/12/2025 | 675 | ❌ descartar (rascunho mínimo / extração ruim) |
| 2 | `CONTRAFACAO-DA-AUTONOMIA-POLITICA-15.docx` (lote 3) | f906b644 | 09/12/2025 | ~2200 | ❌ descartar (versão inicial) |
| 3 | `CONTRAFACAO-DA-AUTONOMIA-POLITICA-13.pdf` (lote 3) | c7ddfed9 | 11/12/2025 | ~2200 | ❌ descartar (PDF da v.15) |
| 4 | `Contrafacao-da-Autonomia-Politica.pptx` (lote 3, 19MB) | ace1ce47 | 13/12/2025 | — | ✅ **MANTER** (versão PPTX da apresentação acadêmica, 10 slides) |
| 5 | `CONTRAFACAO-6.pdf` (lote 2) | 2c737a35 | 05/01/2026 | 2882 | ❌ descartar |
| 6 | `CONTRAFACAO-7.docx` (lote 2) | 0d000d0a | 05/01/2026 | 2871 | ❌ descartar |
| 7 | `CONTRAFACAO-DA-AUTONOMIA-POLITICA-E-DERROTA-ELEITORAL-PROGRAMADA-3.docx` (lote 2) | 87964cca | 26/01/2026 | 3277 | ❌ descartar |
| 8 | `Contrafacao_Autonomia_Politica_Honduras_2025-2.docx` ≡ `-copia.docx` (lote 2) | 5effed9b | 02/02/2026 | 3539 | ❌ descartar (substituído pela final 7 dias depois) |
| 9 | `Contrafacao_Autonomia_Politica_Honduras_2025-1-16.docx` (lote 1) | 1f28d50c | 07/02/2026 | 3532 | ✅ **MANTER** (DOCX final editável) |
| 10 | `Contrafacao-Autonomia-Politica-Honduras-15.pdf` ≡ `-copia-11.pdf` (lote 1) | ba82642f | 09/02/2026 | 3548 | ✅ **MANTER** (PDF final para apresentação) |
| 11 | `Artigo-Rixi-Moncada-14.docx` (lote 3) | 748f149c | 10/12/2025 | 3233 | ⚠️ **MANTER em `historico/`** — texto-irmão do mesmo projeto, com foco em gênero/comunicação política (~80% sobreposição mas escopo metodológico distinto: framing analysis) |

### A.1 Linhagem Tegucigalpa/Autopsia (ensaios que precederam a Contrafação)
| # | Arquivo | Modificado | Palavras | Decisão |
|---|---------|------------|----------|---------|
| 1 | `A-Autopsia-de-um-Golpe-Eleitoral-e-a-Sombra-do-Narco-18.docx` | 02/12/2025 | 2151 | ⚠️ **MANTER em `historico/`** (ensaio inicial, base argumentativa) |
| 2 | `A-Batalha-por-Tegucigalpa-e-a-Sombra-da-Ingerencia-17.docx` | 02/12/2025 | 1568 | ❌ descartar (recorte do anterior) |

---

## B. Linhagem TRABALHO FINAL IDP (Filosofia Política)

| # | Arquivo | Modificado | Decisão |
|---|---------|------------|---------|
| 1 | `Trabalho_Final_IDP_Pedro_Henrichs-10.docx` | 17/12/2025 | ❌ descartar |
| 2 | `Trabalho-Final-IDP-9.docx` | 23/12/2025 | ✅ **MANTER (DOCX final)** |
| 3 | `Trabalho-Final-IDP-8.pdf` | 23/12/2025 | ✅ **MANTER (PDF da entrega)** |

---

## C. Linhagem PROJETO QUALIFICAÇÃO (predecessores ao v1)

| # | Arquivo | Modificado | Decisão |
|---|---------|------------|---------|
| 1 | `Pre-Projeto-com-ajustes-17.docx` | 17/10/2025 | ⚠️ `historico/` (pré-projeto) |
| 2 | `Projeto-avancado-13.docx` | 26/10/2025 | ⚠️ `historico/` (versão avançada) |
| 3 | `Projeto-14.pdf` | 26/10/2025 | ⚠️ `historico/` (PDF da versão avançada) |
| 4 | `Renato-14.docx` (lote 2) | 13/12/2025 | ⚠️ `historico/` — versão **conjunta com 4 colegas** (Méro, Romão, Santana, Bagre, Henrichs) – outubro/2025. **Importante:** ajuda a entender por que o projeto v1 (individual) começou em dezembro. |
| 5 | `00_Projeto/projeto_qualificacao_v1_original.docx` (já no repo) | — | ✅ mantido |
| 6 | `00_Projeto/projeto_qualificacao_v2_ajustado.md` (já no repo) | — | ✅ mantido |

---

## D. Linhagem PLANO ESTRATÉGICO MERCOSUL-UE

Esse objeto tem **três etapas** distintas: rascunho inicial → texto sem diagramação → apresentação final (PDF/PPTX). Manter todas as etapas pertinentes:

| # | Arquivo | Modificado | Palavras/Slides | Decisão |
|---|---------|------------|------|---------|
| 1 | `Plano-Estrategico-de-Influencia-16.docx` (lote 3) | 03/12/2025 | rascunho | ❌ descartar |
| 2 | `Plano-Estrategico-Basico-12.docx` (lote 3) | 12/12/2025 14:22 | versão básica | ❌ descartar |
| 3 | `PLANO-ESTRATEGICO-SEM-DIAGRAMACAO-10.docx` (lote 3) | 12/12/2025 18:30 | sem diagramação | ✅ **MANTER (DOCX texto-base final)** |
| 4 | `PLANO-ESTRATEGICO-SEM-DIAGRAMACAO-9.pdf` (lote 3) | 12/12/2025 19:11 | 17 pg | ✅ **MANTER (PDF texto-base)** |
| 5 | `apresen-11.docx` (lote 3) | 12/12/2025 14:55 | 733 palavras (roteiro) | ⚠️ **MANTER** (roteiro reestruturado por colega Iury Melo) |
| 6 | `Plano-Estrategico-de-Influencia-para-a-Ratificacao-do-Acordo-Mercosul-Uniao-Europeia-3.pptx` (lote 3, 19MB) | 12/12 21:50 | 12 slides | ❌ descartar (substituído pela versão 1-2) |
| 7 | `Plano-Estrategico-de-Influencia-para-a-Ratificacao-do-Acordo-Mercosul-Uniao-Europeia-1-2.pptx` (lote 3, 74MB) | 12/12 22:25 | 13 slides | ✅ **MANTER (PPTX final, 1 slide a mais)** |
| 8 | `Plano-Estrategico-de-Influencia-para-a-Ratificacao-do-Acordo-Mercosul-Uniao-Europeia-4.pdf` (lote 3) | 12/12 21:20 | 12 pg | ✅ **MANTER (PDF da apresentação)** |
| 9 | `Plano-Estrategico...-copia-12.pdf` (lote 2, idêntica a -4 em conteúdo) | 17/12/2025 | 10 pg / pdf-lib | ❌ descartar (compactado/recortado) |

---

## E. Linhagem PROPAGANDA NEGATIVA (mesmo objeto, duplicata exata)

| # | Arquivo | Hash | Decisão |
|---|---------|------|---------|
| 1 | `Propaganda-negativa-7.pdf` | 9b8000017 | ❌ descartar (duplicata) |
| 2 | `Propaganda-Negativa-11.pdf` | 9b8000017 | ✅ **MANTER** (artigo único) |

## F. Linhagem GPT/IA (mesmo objeto, duplicata exata)

| # | Arquivo | Hash | Decisão |
|---|---------|------|---------|
| 1 | `GPT-e-as-Ias-6.pdf` | 2e05c61a | ❌ descartar (duplicata) |
| 2 | `CHATGPT-e-Outras-Ias-10.pdf` | 2e05c61a | ✅ **MANTER** |

## G. Plano de ensino IDP (duplicata exata em 3 lotes)

| # | Arquivo | Hash | Decisão |
|---|---------|------|---------|
| 1 | `Plano-de-ensino-Comunicacao-Esfera-Publica-...-7.pdf` (lote 3) | 5af2792f | ❌ descartar |
| 2 | `Plano-de-ensino-Comunicacao-Esfera-Publica-...-8.pdf` (lote 3) | 5af2792f | ❌ descartar |
| 3 | `Plano-de-ensino-Comunicacao-Esfera-Publica-...-12.pdf` (lote 4) | 5af2792f | ✅ **MANTER** (1 cópia em manuais IDP) |

## H. Linhagem IRÃ

| # | Arquivo | Modificado | Decisão |
|---|---------|------------|---------|
| 1 | `Como-o-Ira-chegou-ate-aqui-14.docx` | 04/03/2026 | ❌ descartar (versão inicial) |
| 2 | `Das-Raizes-do-Nacionalismo-ao-Enfrentamento-Global-no-Seculo-XXI-13.docx` | 05/03/2026 | ✅ **MANTER** (versão assinada/ampliada com Economia de Resistência) |

## I. Datasets CELAC (mesmo conteúdo em formatos diferentes)

| # | Arquivo | Decisão |
|---|---------|---------|
| `CELAC-geral-Publish-18.xlsx` | ✅ **MANTER (XLSX nativo)** |
| `CELAC-geral-Publish-21.csv` | ⚠️ **MANTER (CSV para análise programática)** |
| `856-CELAC-19.xlsx` | ✅ **MANTER (XLSX nativo)** |
| `856-CELAC-20.csv` | ⚠️ **MANTER (CSV)** |

---

## J. Arquivos únicos (sem versões duplicadas) — TODOS MANTIDOS

### Manuais e materiais do programa IDP

- `MANUAL-DE-ESTRUTURA-E-FORMATACAO-DOS-TRABALHOS-DE-QUALIFICACAO-E-DISSERTACAO_LAYOUTADO-5.pdf`
- `MANUAL-QUALIFIQUEI-E-AGORA-_-2.pdf` (51 MB — manual pós-qualificação)
- `Calendario-2026_CPRI-3.pdf`
- `CPRI_Seminario-Orientacao-a-Pesquisa_28.03-4.pdf`
- `Professores-Permanentes_CPRI-6.pdf`
- `Como-acessar-o-portal-da-CAPES-7.pdf`
- `Manual-da-biblioteca-8.pdf`
- `Novo-tutorial-das-plataformas-digitais-2026-2-9.pdf`
- `IDP-Modelo-e-orientacoes-para-trabalho-final-11.docx` (modelo para Filosofia Política)
- `Plano-de-ensino-Comunicacao-Esfera-Publica-Democracia-...` (disciplina cursada)

### Textos autorais (Pedro)

- `Mapeamento_Fontes_Dissertacao_CELAC_OEA.docx` — **documento-chave**: catálogo de fontes da dissertação por método de acesso
- `ENSAIO-copia-10.pdf` — ensaio sociologia/criminologia do crime (Prof. Wladimir Aras)
- `Pragmatismo-de-Hegemonia-copia-2-12.docx` — artigo sobre PT/hegemonia
- `Das-Raizes-do-Nacionalismo-...-13.docx` — artigo Irã
- `Chile-2025-15.docx` — artigo Chile 2025 (Kast)
- `Resenha_Regionalismo_Pos_Hegemonico_Pia_Tussie-2.docx` — **resenha do Riggirozzi & Tussie (2012)**, referencial central H1
- `Entre-hegemonia-e-autonomia_CELAC-OEA-...-Latino-Americana.pptx` — **apresentação principal da dissertação (14 slides, modificado 11/10/2025)**

### Instrumentos de pesquisa (lote 4)

- `Roteiro-de-Entrevistas-Semiestruturadas.docx`
- `TERMO-DE-CONSENTIMENTO-LIVRE-E-ESCLARECIDO-16.docx` (TCLE português)
- `TERMINO-DE-CONSENTIMIENTO-LIBRE-E-INRMADO-TCLI-2.docx` (TCLI espanhol)
- `Quadro_Z_Entrevistados-15.docx` — quadro de possíveis entrevistados por caso

### Textos auxiliares de pesquisa

- `Relatorio-Nicaragua-5.docx` — relato de campo (entrevistas não realizadas em Manágua, 26-27/10)
- `Relacao-Nica-USA-8.pdf` — texto sobre relação Nicaragua-EUA
- `CHATGPT-e-Outras-Ias-10.pdf` — texto sobre IAs (provavelmente de outra disciplina)
- `Propaganda-Negativa-11.pdf` — texto sobre propaganda negativa
- `Livro-contruindo-os-conceitos-9.docx` — livro/apostila Relações Institucionais e Governamentais (RIG)
- `administrador-04.artigo-3-final-4.pdf` — artigo Gomes & Dourado, "Fake news, comunicação política" (referência usada)
- `NetLAB.Compos-5.pdf` — artigo Compós 2024 sobre negacionismo climático no YouTube (referência usada)

### Fontes primárias / evidência empírica

- `DECLARACION-IDEA-HONDURAS-2025-4.pdf` — declaração Grupo IDEA sobre eleições Honduras 26/11/2025
- `Declaracao-de-Trump-3.jpg` — captura de declaração de Trump (provável evidência empírica para Contrafação)
- `WhatsApp-Image-2025-12-12-at-18.18.20-5.jpg` (1600×893)
- `WhatsApp-Image-2025-12-12-at-18.01.49-6.jpg` (1376×768)
  *(WhatsApp Images: provavelmente material de campo ou registro contextual)*

---

## Resumo numérico

- Total recebido: **72 arquivos**
- Descartados (duplicatas exatas ou versões anteriores substituídas): **22 arquivos**
- Mantidos no repositório: **50 arquivos** (entre ativos e histórico)
- Reaproveitados em fichas/citações: a definir caso a caso

---

# Adendo — Lotes 6 a 11 (12/06/2026, sessão autônoma)

**Total recebido (todos os lotes):** 179 arquivos em 11 lotes (16 + 15 + 18 + 21 + 2 + 11 + 19 + 3 + 26 + 25 + 16 + 23 já no repo de turnos anteriores).

**Recebidos nos lotes 6-11:** 107 arquivos adicionais.

## K. Lotes 6-7 — Pragmatismo, Smart Cities, Mumbuca, Maricá, Belém, Mercosul-UE

### K.1 Pragmatismo de Hegemonia (texto autoral, PT)
| Arquivo | Modificado | Decisão |
|---------|-----------|---------|
| `Pragmatismo-de-Hegemonia-8.docx` (lote 6) | dez/2025 | ❌ descartar (versão antiga) |
| `PRAGMATISMO-DE-HEGEMONIA-copia-5.docx` (lote 6) | dez/2025 | ❌ descartar |
| `Pragmatismo-de-Hegemonia-copia-2-12.docx` (lote 4) | 10/03/2026 | ✅ **MANTER** → `09_Textos_Autorais/artigos_revista/Pragmatismo_de_Hegemonia_PT.docx` |

### K.2 Smart Cities / Mumbuca / Maricá (Trabalho disciplina)
| Arquivo | Decisão |
|---------|---------|
| `Smart-Cities-Trabalho-final-10.docx` + `-9.pdf` (lote 6) | ✅ **MANTER** (versão final, 13/09, 5521 palavras) |
| `Mumbuca-Cidade-Inteligente-13.docx` (lote 7) | ⚠️ manter (versão antecedente — núcleo Mumbuca isolado) |
| `A-Moeda-Social-Mumbuca-e-a-Construcao-de-uma-Cidade-Inteligente-14.docx` (lote 7) | ⚠️ manter (etapa intermediária) |
| `Start-Cities-trabalho-atualizado-ate-11-de-agosto-de-2025-11.docx` (lote 7) | ⚠️ manter (snapshot ago/2025) |
| `Apresentacao-Smart-Cities-1-7.pptx` (lote 7, 16MB) | ✅ MANTER apresentação |
| `MOEDA-SOCIAL-E-RENDA-9.pdf` | ✅ MANTER (lit/anexo) |
| `artigomumbuca_deniseneumannVF-8.pdf` | ✅ MANTER (referência terceira) |
| `bmt_70_politicas_publicas_marica-IPEA-15.pdf` | ✅ MANTER (referência IPEA) |
| `EFEITOS-NO-BEM-ESTAR-DE-UM-PROGRAMA-PERMANENTE-DE-TRANSFERENCIA-2-16.pdf` | ✅ MANTER (referência) |

### K.3 Governança Climática (apresentação Liderança Setor Público)
| Arquivo | Decisão |
|---------|---------|
| `1-Governanca-climatica-na-Amazonia-urbana-4.pdf` (lote 7) | ✅ MANTER |
| `Artigo-Governanca-climatica-na-Amazonia-urbana.pdf` (lote 7) | ✅ MANTER |
| `APRES-Lideranca-e-Transformacoes-no-Setor-Publico_FULL-12.pdf` (lote 7) | ✅ MANTER (versão completa) |
| `APRES-Lideranca-e-Transformacoes-no-Setor-Publico.pdf-6.pdf` (lote 7, 7,9MB) | ⚠️ manter (versão resumida) |
| `APRES-Lideranca-e-Transformacoes-no-Setor-Publico_FULL-copia-10.pdf` (lote 7) | ❌ descartar (duplicata FULL) |
| `Governanca-BelemCOP30-2.docx` (lote 8) | ✅ MANTER (texto autoral) → `09_Textos_Autorais/artigos_revista/` |

### K.4 NÃO ENTRAM no repo da dissertação — Henrichs Consultoria (skill separada)
| Arquivo | Razão |
|---------|-------|
| `Relatorio-Execucao-Comunicacao-1-18.pptx` (lote 7, 195MB) | Relatório operacional da Henrichs Consultoria — pertence ao skill `henrichs-consultoria` |
| `Relatorio-SISTEMA-DE-GESTAO-Material-esportivo-19.docx` (lote 7) | Sistema de gestão de material esportivo (IDECACE) — skill Henrichs |
| `PESQUISA-CIENTIFICA-FATURAMENTO-Relatorio-17.docx` (lote 7, 537KB) | Relatório operacional (cumpre função jurídica/contábil) — skill Henrichs |

## L. Lote 8 — apenas 3 arquivos
- `Texto-apresentacao.docx` → `09_Textos_Autorais/artigos_revista/`
- `Governanca-BelemCOP30-2.docx` → idem (já listado)
- `professores-3.pdf` → `08_Materiais_IDP/manuais/professores_permanentes_CPRI.pdf` (verificar duplicidade com `Professores-Permanentes_CPRI-6.pdf` do lote 1 — provavelmente o mesmo)

## M. Lote 9 — Comércio Internacional / OMC (26 arquivos)
Disciplina cursada (1.º sem 2025): IDP, Comércio Digital. Material organizado em **`10_Outras_Disciplinas/comercio_internacional_OMC/`**. Trabalhos pareados DOCX+PDF (manter ambos formatos), modelos auxiliares e bulletin do programa The Academy.

Destaques:
- `IDP-Mai2025.-Comercio-digital-22.pdf` → plano de ensino da disciplina
- `MODULO-3-CLASSIFICACAO-DE-COMERCIO-ELETRONICO` → módulo aula
- Vários exercícios e resenhas autorais (Tratamento Nacional, Margens de Preferência, Acordo Contratações Públicas, Teoria da Corrupção, Regulação de Investimentos)
- `Captura-de-Tela-2025-06-04` → contexto/anexo trabalho

**Aproveitamento na dissertação:** baixo (tema não diretamente correlato), mas mantido como portfólio acadêmico.

## N. Lote 10 — Mix variado + REVISÃO INTEGRATIVA (CRÍTICO)

### N.1 ✅ DOCUMENTO CRÍTICO: Revisão Integrativa PRISMA
| Arquivo | Avaliação |
|---------|-----------|
| `Revisao-Integrativa-A-CELAC-frente-a-OEA-14.docx` (lote 10, 115KB, 4722 palavras, maio/2025) | ✅ **CRÍTICO** — revisão PRISMA com 9 artigos. **Peça fundamental para Capítulo 2 da dissertação.** → `04_Fichamentos_ABNT/Revisao_Integrativa_CELAC_OEA_PRISMA.docx` |
| `Revisao-A-CELAC-frente-a-OEA-13.pdf` (lote 10, 351KB) | ✅ MANTER PDF correspondente |

### N.2 Outros (Política/Direito/Saúde — outras disciplinas)
Apresentação Mulheres Parlamentares (Prof. Pablo), Pé de Meia, Coalizão União-PP, IOF/Justiça Fiscal, Participação Social Mercosul, Pepe Mujica, Análise Regulatória Saúde, UE-Mercosul, Métodos Lista Positiva/Negativa, etc. — **TODOS** para `10_Outras_Disciplinas/outros/` ou pastas temáticas correspondentes.

## O. Lote 11 (este turno) — Equador 2025 + Artigos CELAC + Entrevista Pablo Vilas

### O.1 ✅ ENTREVISTA Pablo Vilas (CRÍTICO p/ H1)
| Arquivo | Avaliação |
|---------|-----------|
| `Entrevista-CELAC-Pablo-Vilas-11.docx` (1498 palavras, bilíngue ES/PT) | ✅ **CRÍTICO** — entrevista com ex-coordenador da CELAC. **Atenção:** Pablo Vilas é **argentino**, e o projeto de qualificação **restringe entrevistas a atores brasileiros**. Material pode ser usado como **base contextual** para roteiro e análise interpretativa, mas **não pode entrar como entrevista oficial codificada na ACQ** sem ajuste no projeto. → `12_Entrevistas_Anotacoes/` |
| `Perguntas-CELAC-13.docx` | ✅ Anotações da reunião com Luísa (caso Equador lawfare) + sugestões de perguntas CELAC. → `12_Entrevistas_Anotacoes/` |
| `Tarefa-1-Pablo.pptx` | ✅ Apresentação 1,9MB associada ao Pablo. → `12_Entrevistas_Anotacoes/` |

### O.2 ⚠️ Caso Equador 2025 (Noboa) — FORA DO RECORTE
**Atenção metodológica:** O caso Equador 2025 (governo Noboa, lawfare, estado de exceção) **NÃO** está nos 3 casos do projeto (Honduras 2009, Paraguai 2012, Colômbia 2016+). Textos do Pedro sobre o tema têm valor jornalístico/de opinião e podem virar artigos para revista, mas **não devem ser incorporados como caso da dissertação** sem revisão do recorte.

Arquivos:
- `Noboa-o-Justo-12.docx` → `09_Textos_Autorais/artigos_revista/`
- `O-Aparelhamento-Politico-e-o-Uso-de-Lawfare-nas-Eleicoes-do-Equador-9.pdf` + `-10.docx` → `09_Textos_Autorais/artigos_revista/`
- `Resumen-Decreto-14.docx` + `Drecreto-Equador-15.pdf` → `12_Entrevistas_Anotacoes/equador_2025_contexto/` (anotações trabalho)
- `Analise-Academica-do-Artigo-2.docx` (Mulheres Parlamentares) → `12_Entrevistas_Anotacoes/equador_2025_contexto/` (texto trabalho para a disciplina)
- `Analise-dos-textos-3.docx` → idem

### O.3 ✅ Artigos CELAC para revisão de literatura (5 PDFs terceiros)
| Arquivo | Autor / fonte | Avaliação |
|---------|--------------|-----------|
| `Artigo-Celac-7.pdf` | **Pereira (2016)**, Cadernos Prolam/USP | ✅ **ALTAMENTE RELEVANTE** — CELAC e relações Sul-Sul; usar em Cap. 2 |
| `artigo-celac-2-6.pdf` | de Deus (2017), Revista Extensión +E | ⚠️ relevância média — universidades brasileiras/integração |
| `artigo-celac-3-5.pdf` | **Lessa & Tavolaro**, Latino-americanismos | ✅ **RELEVANTE** — campo de produção sobre AL |
| `artigo-celac-4-4.pdf` | **Cacciamali, Gremaud & Barros (2014)**, Tempo do Mundo (IPEA) | ✅ **ALTAMENTE RELEVANTE** — Brasil e integração latino-americana |
| `A_estrutura_institucional_dos_principais-8.pdf` | **Hamerski (UFRGS)** | ✅ **RELEVANTE** — comparação institucional MERCOSUL/UNASUL/ALBA/CELAC |
| `Artigo-MExico-16.pdf` (10,8MB) | (verificar) | ⚠️ a fichar |

**Destino:** `04_Fichamentos_ABNT/literatura_celac/` (já organizados, aguardam fichamento ABNT).

### O.4 ✅ Datasets Publish or Perish (Google Scholar)
Pedro entregou Excel/CSV com export do Google Scholar via Publish or Perish:
- `CELAC-geral-Publish-18.xlsx` + `-21.csv` — 200 artigos (busca geral CELAC)
- `856-CELAC-19.xlsx` + `-20.csv` — 856 artigos (busca ampla "intitle:celac")

**Aproveitamento:** ✅ **SIM, diretamente útil para o Capítulo 2 (Revisão de Literatura)** — base de dados para PRISMA, análise bibliométrica e identificação de literatura cinza (citation, PDF only).

→ `06_Bibliografia/datasets_publish_or_perish/`

---

## Resumo numérico FINAL

- Total recebido nos 11 lotes: **179 arquivos**
- Duplicatas exatas / versões substituídas: **~35 arquivos descartados**
- Henrichs Consultoria (fora deste skill): **3 arquivos excluídos**
- Mantidos no repositório: **~141 arquivos**, organizados em 13 pastas temáticas
- Transcrições MD geradas (regra Pedro): **32 transcrições** de PDFs autorais e de literatura crítica

## Estrutura final do repositório

```
00_Projeto/            ← Projeto v1 + v2 + 9 documentos do histórico
01_Metodologia_OSINT/  ← Catálogo de fontes + nota metodológica
02_Corpus_Oficial/     ← CIDH, OEA, CELAC, MAPP (Honduras, Paraguai, Colômbia)
03_Fontes_Vazadas/     ← WikiLeaks + imagens-evidência
04_Fichamentos_ABNT/   ← Fichas autorais + literatura_celac/ (5 artigos)
05_Matrizes_ACQ/       ← Códigos NV-NI, NV-SOB, NV-AUT (a expandir)
06_Bibliografia/       ← Datasets PoP + referências complementares
07_Midia_Regional/     ← Matriz de mídia (jornais por país)
08_Materiais_IDP/      ← Manuais + planos de ensino das disciplinas cursadas
09_Textos_Autorais/    ← Honduras_contrafacao + Filosofia + Artigos_revista + Ensaios + Apresentações
10_Outras_Disciplinas/ ← Comércio OMC, Mercosul-UE, Smart Cities, Governança Climática, Representação Feminina, outros
11_Instrumentos_Pesquisa/ ← Roteiro, TCLE, TCLI, Quadro Z, Custos
12_Entrevistas_Anotacoes/ ← Entrevista Pablo Vilas + anotações trabalho Equador 2025
```
