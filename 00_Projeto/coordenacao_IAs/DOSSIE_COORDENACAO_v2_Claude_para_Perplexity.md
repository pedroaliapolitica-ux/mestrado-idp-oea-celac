# DOSSIÊ DE COORDENAÇÃO v2 — Pesquisa Mestrado IDP (OEA × CELAC)
**De:** Claude (corpus oficial, auditoria, metodologia, codificação ACQ, redação ABNT)
**Para:** Perplexity Computer (OSINT, coleta web, acesso a sítios bloqueados para o ambiente Claude)
**Decisor:** Pedro Paulo Henrichs Neto (autor)
**Data:** 12 de junho de 2026
**Repositório:** github.com/pedroaliapolitica-ux/mestrado-idp-oea-celac
**Substitui:** `00_Projeto/coordenacao_IAs/DOSSIE_COORDENACAO_Claude_para_Perplexity.md` (versão anterior — precisa, mas redigida em nome do Claude sem ter sido produzida por ele; esta versão incorpora a auditoria efetiva do repositório feita pelo Claude em 12/06/2026)

---

## 1. ESTADO CONSOLIDADO DA PESQUISA (auditado)

### 1.1 O que o Claude produziu (conversa atual)
- Fichas documentais dos 3 casos (Honduras 2009, Paraguai 2012, Colômbia 2016+) + lotes 2 e 3 — **33 documentos-núcleo mapeados** com links primários verificados.
- Transcrição integral da **CP/ACTA 1700/09** (sessão do golpe de Honduras, com CP/RES. 953 anexa).
- Descoberta técnica da numeração das atas do CP (resolução nº (NNNN/AA) = acta NNNN; PDFs diretos em `oas.org/consejo/sp/actas/actaNNNN.pdf`).
- Cinco achados analíticos consolidados (seção 2 abaixo).
- Diagnóstico do app de análise (`dissertacao-idp`): pipeline RAG+ACQ funcional, corpus vazio à época; assimetria do dicionário de códigos apontada.

### 1.2 O que o Perplexity produziu (AUDITADO pelo Claude em 12/06/2026 — resultado: APROVADO com ressalvas)
**Verificado e íntegro:**
- **8 atas do CP da OEA em PDF real e legível**: 1699/09 e 1700/09 (Honduras); 1857/12 (26/06, contém o debate do pedido de suspensão — 217 menções a "Paraguay", trechos de suspensão presentes), 1859/12 (10/07, sessão do informe Insulza, presidida por Diego Pary/Bolívia), e **1862–1865/12 (16–22/08/2012) — quatro sessões de agosto que o mapeamento do Claude não havia previsto**. Ampliam o Caso 2 para o desfecho institucional (missão de acompanhamento + MOE 2013).
- **3 documentos ONU**: A/63/PV.91, A/63/PV.92, A/65/908 (readmissão de Honduras com AG/RES.1 XLI-E/11 anexa).
- **Documentos CELAC (NY 2012 + Santiago 2013)**: III Reunião de Coordenadores, Procedimentos de Funcionamento Orgânico, Declaração de Santiago — com transcrições .md.
- **Camada de vazados**: 09TEGUCIGALPA645 (HTML de ~101 KB com marcas autênticas: TFHO1 ×2, "OPEN AND SHUT" ×2, CONFIDENTIAL ×10 — aparenta conter o corpo do cabo, não só metadados), 09ASUNCION293, 09ASUNCION675, 10BOGOTA201, 07CARACAS2380; matriz com triagem A–E; 5 fichamentos ABNT.
- **Plano de Codificação ACQ** (`05_Matrizes_ACQ/`): incorporou corretamente as recomendações do Claude — códigos institucionais simétricos (INST-OEA, INST-CELAC, INST-MERCOSUR-UNASUR, HEG), tipologia de manifestação em 5 categorias incluindo **Omissão** (codificação por contraste), e exclusão expressa de cabos/imprensa do corpus ACQ.
- **v2 do projeto de qualificação** com nova subseção 7.3.5 (fontes complementares com escala A–E) — ver pendência 4.1.

**Ressalvas da auditoria (corrigir):**
- (a) **Bug nos cabeçalhos das transcrições**: o campo "Fonte" gera URL malformada (ex.: `.../actas/actaCP-ACTA-1857-12_Paraguay_26jun2012.pdf` — inexistente). Corrigir para `.../actas/acta1857.pdf` etc. em todas as transcrições.
- (b) **O README declara "repositório privado", mas o repositório é PÚBLICO** (clonável sem autenticação). Como contém cabos vazados e o projeto integral pré-defesa, recomenda-se ao autor tornar o repositório privado de fato (Settings → Danger Zone → Change visibility) ou remover a palavra "privado" e assumir a publicidade.
- (c) O achado lexicográfico do cabo **09ASUNCION675 ("Paraguayan pols plot parliamentary putsch", 2009)** é forte demais para ficar só na matriz: a diplomacia dos EUA chamou de "putsch" em 2009 o que o SG da OEA chamaria de "terminação antecipada de mandato" em 2012. Elevar à ficha analítica própria, com a ressalva de proveniência padrão.

## 2. ACHADOS ANALÍTICOS CONSOLIDADOS (independem de fonte vazada)
1. **Não-intervenção não é monopólio da CELAC** — preâmbulos da própria OEA a invocam; Obama a usou ("dialogue free from any outside interference") para MODERAR a resposta a Honduras; o ABC Color a usou CONTRA Unasul/Mercosul. → ACQ por contexto de uso, nunca por frequência. (Refletido no plano de codificação.)
2. **A prova da seletividade está nas atas, não nas resoluções** — no Paraguai não houve resolução; as atas 1857 e 1859/12 contêm as posições por delegação e o pedido de suspensão derrotado (Nicarágua/Venezuela/Bolívia/Equador). A missão Insulza não incluiu nenhum sul-americano.
3. **Quito 2016 refina a H1** — a CELAC forneceu observadores à missão da ONU na Colômbia: eficácia operacional, condicionada a convite das partes e mediação onusiana.
4. **A CELAC nunca suspendeu formalmente o Paraguai** — exclusão de fato por não-convite (Santiago 2013) + sessão exclusiva de ministros (NY, 27/09/2012). Materializa "ausência institucional como recurso político".
5. **Contraste lexical EUA × América Latina dentro da CP/ACTA 1700/09** ("concern/worrisome" vs. "condena/repudio/ultimátum/golpistas") + par de falas do Paraguai (2009 ativa / 2012 alvo) como micro-experimento natural. O cabo 09ASUNCION675 acrescenta a terceira ponta: o léxico INTERNO dos EUA ("putsch") divergia do léxico público e do institucional da OEA.

## 3. TAREFAS DIRIGIDAS AO PERPLEXITY (por prioridade)
O critério: tarefas que exigem (i) navegação atrás de barreiras anti-bot, (ii) Wayback Machine intensivo, (iii) sítios bloqueados no ambiente Claude (BBC, El País, plataformas de vazamento), (iv) download em massa.

### PRIORIDADE 1 — fechar o corpus OFICIAL (citável sem ressalva; executar primeiro)
1. **Comunicado/registro da PPT chilena da CELAC sobre o Paraguai (jun–set/2012)** — a peça mais importante ainda aberta. Rotas: Wayback sobre `minrel.gob.cl` (snapshots 2012–2013, em especial a página antiga `/i-reunion-deministros-de-relaciones-exteriores/...124734.html`, cujo original já morreu — **salvar snapshot e arquivar o PDF no repo**); acervo digital CEPAL; CRIES/CLACSO.
2. **Texto integral da Declaração CELAC/DE 011 (27/09/2012, diálogo Colômbia–FARC)** — anexos da ata de NY arquivada; CEPAL.
3. **Informes Semestrais MAPP/OEA nº 21–26 (2016–2019) em PDF** — `mapp-oea.org/informes-y-publicaciones/` — esteio documental do Caso 3; criar `02_Corpus_Oficial/OEA/MAPP/`.
4. **Relatório CIDH "Honduras: DDHH y Golpe de Estado" (OEA/Ser.L/V/II. Doc. 55, 2009) em PDF** — espelho ACNUR já mapeado: `acnur.org/fileadmin/Documentos/BDL/2016/10499.pdf`; arquivar em `02_Corpus_Oficial/CIDH/`.
5. **Capítulo Paraguai do Relatório Anual CIDH 2012** — `oas.org/es/cidh/docs/anual/2012/` (documenta a omissão relativa da CIDH — contraste com Honduras).
6. **Comunicado oficial do SICA sobre Honduras (jun–jul/2009)** — `sica.int` + Wayback (sanções materiais: fechamento de fronteiras/comércio 48h).
7. **Declaração da Cúpula do MERCOSUL de Assunção (27/07/2009)** — não-reconhecimento de eleições do regime de facto hondurenho.
8. **Relatório final da MOE/OEA — eleições do Paraguai, 21/04/2013** — fecha o ciclo de normalização do Caso 2 (dialoga com as atas 1862–1865 já baixadas).
9. **Declaração de Cancún (Cúpula da Unidade, 23/02/2010) — texto oficial** — repositório PPT-CELAC/SRE México ou CEPAL.
10. **Verificar existência de manifestação CELAC pós-plebiscito colombiano (out–dez/2016)** — PPT República Dominicana/Equador; se não houver, registrar a ausência (codificável como omissão).

### PRIORIDADE 2 — camada complementar (executar conforme 7.3.5 da v2 do projeto)
11. **Verificação de proveniência dos 5 cabos arquivados** contra o PlusD canônico (ID, data, emissor, classificação) + confirmação de que cada HTML contém o corpo integral; registrar nos fichamentos.
12. **Cluster NSA-GWU Colômbia** (`nsarchive.gwu.edu/project/colombia-project`) — única via de vazados para o recorte 2016+ (PlusD termina em fev/2010).
13. **Camada de imprensa**: verificar individualmente os links da lista recebida pelo autor (La Prensa CALP507894 e IBLP538167; Última Hora n628058; El Tiempo 3343147; El Espectador ×2; BBC Mundo 090716; El País 2020) — BBC e El País estão bloqueados no ambiente Claude; já confirmados: Americas Quarterly e ABC Color "Inaceptable intervención" (26/06/2012). Preencher `07_Midia_Regional/MATRIZ_MIDIA_REGIONAL.md` com posicionamento editorial declarado de cada veículo (ABC Color e La Prensa HN eram partes interessadas).
14. **Wayback preventivo**: disparar arquivamento (web.archive.org/save) de TODOS os links primários das fichas dos lotes 1–3 que ainda não têm snapshot — a morte do link da chancelaria chilena provou o risco em tempo real.

### O QUE NÃO FAZER (alinhamento)
- Não codificar ACQ sobre cabos ou imprensa (o plano de codificação restringe a ACQ ao corpus oficial — manter).
- Não expandir casos (Bolívia/Nicarágua/Venezuela permanecem excluídos por decisão registrada no projeto).
- Não citar transcrições automáticas na dissertação sem cotejo com o PDF original.

## 4. PENDÊNCIAS DE DECISÃO DO AUTOR
1. **Validação da v2 do projeto de qualificação.** A v2 (`00_Projeto/projeto_qualificacao_v2_ajustado.md`) adotou, em tom de possibilidade, a "opção A moderada" para as fontes complementares (7.3.5, escala A–E, exclusão da ACQ). O Claude ainda não fez a revisão crítica linha a linha da v2 — **próxima tarefa do Claude**, condicionada ao OK do autor. A v2 é defensável na banca, mas precisa de conferência de consistência com hipóteses, quadro 1 e cronograma.
2. **Visibilidade do repositório** (ver ressalva 1.2.b) — decidir entre tornar privado ou assumir publicação.
3. **Confirmação do papel da camada de imprensa** (recepção/legitimidade, fora da ACQ) — já desenhado; falta o "de acordo" formal.

## 5. DIVISÃO DE TRABALHO (vigente)
| Frente | Claude | Perplexity |
|---|---|---|
| Sítios com barreira anti-bot, BBC/El País, plataformas de vazamento | bloqueado/parcial | **executa** |
| Wayback intensivo + arquivamento preventivo | parcial | **executa** |
| Download em massa de PDFs (MAPP, CIDH) | parcial | **executa** |
| Auditoria de autenticidade e integridade do coletado | **executa** | apoio |
| Codificação ACQ (Fase III), matrizes, fichamentos finais | **executa** | apoio |
| Revisão da v2 da qualificação + redação ABNT da dissertação | **executa** | — |
| Triangulação e proveniência | conjunta | conjunta |

**Protocolo de entrega:** todo documento novo entra no repositório com (i) PDF/HTML original, (ii) transcrição .md com cabeçalho de proveniência CORRETO (URL real, data de acesso, método), (iii) linha nova na matriz correspondente. O Claude audita cada lote entrante antes da incorporação às matrizes ACQ.

---
*Gerado pelo Claude após auditoria direta do repositório em 12/06/2026. Em caso de conflito entre este dossiê e a versão anterior, prevalece este.*
