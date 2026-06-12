# DOSSIÊ DE COORDENAÇÃO — Pesquisa Mestrado IDP (OEA × CELAC)
**De:** Claude (assistente de pesquisa — corpus oficial, análise metodológica, redação)
**Para:** Perplexity Computer (assistente de pesquisa — OSINT, fontes de acesso restrito, coleta web)
**Intermediário/decisor:** Pedro Paulo Henrichs Neto (autor)
**Data:** 12 de junho de 2026
**Repositório de referência:** github.com/pedroaliapolitica-ux/mestrado-idp-oea-celac

---

## 1. PROPÓSITO DESTE DOCUMENTO

Registrar o que já foi produzido, sinalizar o que foi auditado e verificado, e dirigir ao Perplexity uma lista de tarefas de coleta que aproveitam suas capacidades de acesso (sítios atrás de barreira anti-bot, plataformas de vazamento, arquivos que o ambiente do Claude não alcança). O objetivo final é fechar a Fase II (Pesquisa Documental) para iniciar a Fase III (Codificação ACQ) e a redação da dissertação.

---

## 2. O QUE JÁ FOI FEITO (estado verificado em 12/06/2026)

### 2.1 Corpus oficial — mapeado e parcialmente baixado
- **33 documentos-núcleo** mapeados em fichas por caso (Honduras 2009, Paraguai 2012, Colômbia 2016+), com links primários oficiais verificados.
- **8 atas do Conselho Permanente da OEA** baixadas em PDF íntegro e auditadas pelo Claude (legíveis, texto extraível):
  - CP/ACTA 1699/09 (26/06/2009, pré-golpe Honduras, 29 pp.)
  - CP/ACTA 1700/09 (28/06/2009, golpe Honduras, 35 pp. + CP/RES. 953 anexa) — **documento-âncora, transcrito integralmente em .md**
  - CP/ACTA 1857/12 (26/06/2012, Paraguai, 61 pp.)
  - CP/ACTA 1859/12 (10/07/2012, informe Insulza, 38 pp.)
  - CP/ACTA 1862–1865/12 (16–22/08/2012, quatro sessões, 27+36+16+63 pp.)
- **3 atas literais da ONU**: A/63/PV.91, A/63/PV.92 (debate Honduras na AG) e A/65/908 (readmissão de Honduras, anexa AG/RES.1 XLI-E/11).
- **Documentos da CELAC (NY, 2012)**: III Reunião de Coordenadores Nacionais, Procedimentos de Funcionamento Orgânico, Declaração de Santiago 2013.

### 2.2 Achados analíticos consolidados (válidos, independem de fonte vazada)
1. **A não-intervenção não é monopólio da CELAC.** O preâmbulo das resoluções da OEA sobre Honduras invoca "el principio de la no intervención". → A codificação ACQ deve ser por CONTEXTO DE USO, não por frequência. (Já refletido no plano de codificação.)
2. **A prova da seletividade está nas atas, não nas resoluções** (no Paraguai não houve resolução). As atas 1857 e 1859/12 contêm as posições por delegação e o pedido de suspensão derrotado (Nicarágua/Venezuela/Bolívia/Equador) — núcleo empírico.
3. **Quito 2016 refina (não confirma) a hipótese central:** a CELAC forneceu observadores à missão da ONU na Colômbia — eficácia operacional, não só simbólica.
4. **Correção factual estabelecida:** a CELAC NUNCA suspendeu formalmente o Paraguai (exclusão de fato por não-convite à Cúpula de Santiago 2013, não sanção de direito). Materializa a variável "ausência institucional como recurso político".
5. **Contraste lexical EUA × América Latina mensurável dentro da CP/ACTA 1700/09:** declarações de Obama/Clinton ("concern", "worrisome", "dialogue free from outside interference") vs. falas latino-americanas ("condena", "repudio", "exigir", "ultimátum", "golpistas"). O par de falas do Paraguai (2009 ativa / 2012 alvo) é um micro-experimento natural.

### 2.3 Camada OSINT (produzida pelo Perplexity, auditada pelo Claude)
- 5 cabos PlusD/WikiLeaks reais e verificados (09TEGUCIGALPA645 contém marcas autênticas: TFHO1, "OPEN AND SHUT", Llorens, CONFIDENTIAL).
- Matriz de fontes vazadas com triagem A–E e 5 fichamentos ABNT.
- ⚠ **Ver seção 5 — pendência de decisão metodológica sobre esta camada.**

---

## 3. DIVISÃO DE TRABALHO SUGERIDA (quem faz o quê melhor)

| Capacidade | Claude | Perplexity |
|---|---|---|
| Acesso a sítios atrás de barreira anti-bot / login leve | limitado | **forte** |
| Plataformas de vazamento (PlusD, NSA, Intercept) | bloqueado no ambiente | **forte** |
| Wayback Machine / recuperação de links mortos | parcial | **forte** |
| Extração e leitura de PDFs longos já baixados | **forte** | variável |
| Análise metodológica, codificação ACQ, redação ABNT | **forte** | apoio |
| Triangulação e verificação cruzada de proveniência | **forte** (conjunta) | **forte** (conjunta) |

**Princípio de coordenação:** Perplexity coleta o que está atrás de barreiras; Claude processa, codifica e redige; ambos verificam proveniência cruzada. Nenhuma inferência central deve depender de fonte única (regra do próprio projeto).

---

## 4. TAREFAS DIRIGIDAS AO PERPLEXITY (ordem de prioridade)

### PRIORIDADE 1 — fechar lacunas do corpus OFICIAL (alto valor, baixa controvérsia)
Estas peças são oficiais e citáveis sem qualquer ressalva metodológica. Devem vir primeiro.

1. **Comunicado/ata da PPT chilena da CELAC sobre o Paraguai (jun–set/2012).** A ata da I Reunião de Ministros (NY, 27/09/2012) registra "Diálogo sobre Paraguay" em sessão exclusiva, mas o conteúdo não é público. Buscar: Wayback Machine sobre minrel.gob.cl (snapshots 2012–2013); acervo CEPAL; compilações CRIES/CLACSO. *Peça mais importante ainda em aberto no quadro comparativo.*
2. **Texto integral da Declaração CELAC/DE 011 (27/09/2012)** sobre o diálogo Governo da Colômbia–FARC — buscar nos anexos da ata arquivada e no acervo CEPAL.
3. **Informes Semestrais MAPP/OEA nº 21 a 26 (2016–2019)** em PDF — mapp-oea.org/informes-y-publicaciones/ (download direto). É o esteio documental do Caso 3.
4. **Comunicado oficial do SICA sobre Honduras (jun–jul/2009)** — sica.int, para elevar a evidência de força probatória secundária para primária.
5. **Declaração da Cúpula do MERCOSUL de Assunção (27/07/2009)** sobre não-reconhecimento de eleições convocadas pelo regime de facto — completa o paralelo MERCOSUL nos dois casos de ruptura.
6. **Capítulo Paraguai do Relatório Anual da CIDH 2012** — oas.org/es/cidh/docs/anual/2012/ (documenta a relativa omissão da CIDH no caso, contraste com Honduras).
7. **Relatório da MOE/OEA das eleições do Paraguai de abril/2013** — fecha o ciclo do Caso 2 (normalização).

### PRIORIDADE 2 — completar a camada OSINT (CONDICIONADA à decisão da seção 5)
*Executar apenas se o autor confirmar que a camada de cabos integra o desenho da dissertação.*

8. **Texto integral do cabo 09TEGUCIGALPA645 (Llorens, "OPEN AND SHUT")** — o PlusD por vezes exibe só metadados; confirmar se o HTML salvo contém o corpo do cabo ou apenas o cabeçalho. Se só metadados, reconstituir via CCR, McClatchy, Americas Quarterly.
9. **Cabos da NSA/GWU sobre Colômbia 2016+ (cluster Santrich/DEA, Comissão da Verdade)** — nsarchive.gwu.edu/project/colombia-project. É a única via para cobertura de vazamentos no recorte colombiano (PlusD termina em fev/2010).
10. **Verificação de proveniência** de cada cabo já arquivado: confirmar ID, data, classificação original e emissor contra o PlusD canônico; registrar no fichamento.

### PRIORIDADE 3 — camada de imprensa (verificação de links)
O autor recebeu uma lista de links de noticiário (origem: outra IA). Antes de qualquer uso:
11. **Verificar individualmente** cada URL da lista (La Prensa, ABC Color, Última Hora, El Tiempo, El Espectador, BBC Mundo, El País) — listas geradas por IA têm taxa relevante de URLs inventadas. Confirmados: Americas Quarterly e ABC Color "Inaceptable intervención..." (26/06/2012). Bloqueados no ambiente Claude: BBC Mundo, El País (testar do lado Perplexity).
12. A imprensa NÃO entra na codificação ACQ (que é sobre documentos oficiais). Lugar correto: camada de RECEPÇÃO/percepção de legitimidade, com posicionamento editorial de cada veículo declarado (ABC Color e La Prensa HN eram partes interessadas nas respectivas crises).

---

## 5. ⚠ PENDÊNCIA DE DECISÃO METODOLÓGICA (requer resposta do autor antes da Prioridade 2)

**O problema:** O projeto de qualificação afirma que a pesquisa é "integralmente viável com base na análise documental pública [oficial]". A camada de cabos vazados (`03_Fontes_Vazadas/`) e a lente do "constrangimento hegemônico" apoiada neles não constam do documento aprovado e ampliam a base de evidências.

**As duas opções (decisão do autor):**
- **(A) Incorporar formalmente:** os cabos entram no desenho como "camada de contraste — fonte primária-mas-problemática". Exige (i) parágrafo novo na subseção 7.3 do projeto declarando a fonte; (ii) tratamento explícito de proveniência e dos limites (o cabo registra PERCEPÇÃO da diplomacia dos EUA, não ação institucional); (iii) defesa antecipada na banca. Vantagem: é a ideia mais original do trabalho; pode elevar a dissertação de descritiva a explicativa. Risco: amplia o flanco de questionamento na qualificação.
- **(B) Manter como exploratório:** os cabos ficam fora da dissertação, como material de contexto não citado. Vantagem: preserva exatamente o desenho aprovado, menor risco na banca. Custo: descarta o diferencial analítico.

**Recomendação do Claude:** decidir ANTES de investir mais coleta OSINT (Prioridade 2). Se (A), o Claude redige o tratamento metodológico que blinda a escolha na qualificação. Se (B), a Prioridade 2 não se executa e o esforço concentra-se na Prioridade 1.

---

## 6. PRÓXIMOS PASSOS DO LADO DO CLAUDE (independentes das tarefas acima)

1. Aguardar decisão da seção 5.
2. Revisar o documento de qualificação incorporando os 6 ajustes já identificados: (i) correção CELAC/Paraguai; (ii) refinamento da H1 via Quito 2016; (iii) simetria do dicionário de códigos (3 códigos CELAC × 1 OEA → equilibrar); (iv) operacionalização da "eficácia simbólica"; (v) decisão 3 vs. 5 casos no repositório; (vi) [se opção A] tratamento das fontes vazadas.
3. Iniciar a codificação ACQ piloto sobre a CP/ACTA 1700/09 (já integral), como teste do codebook antes de aplicá-lo às 7 atas restantes.
4. Estruturar os capítulos empíricos (um por caso) a partir do corpus consolidado.

---

## 7. NOTA DE INTEGRIDADE

Este dossiê e todo o material produzido destinam-se a ORGANIZAR E LOCALIZAR fontes legítimas e a estruturar análise própria do autor. Não substituem a leitura crítica, a codificação e a redação, que são trabalho intelectual do pesquisador. As fichas e transcrições são instrumentos de rastreabilidade; toda citação na dissertação deve ser conferida contra o documento original. A camada de fontes vazadas, se usada, exige o tratamento de proveniência descrito na seção 5.
