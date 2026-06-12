# Memorando Metodológico — Pesquisa OSINT em fontes vazadas

**Projeto:** *Entre hegemonia e autonomia: OEA e CELAC na disputa pela governança regional latino-americana.*
**Autor:** Pedro Paulo Henrichs Neto · Mestrado IDP, Brasília/DF.
**Data do levantamento:** 12 de junho de 2026.
**Modo metodológico:** Modo 5 do Agente Mestre — *OSINT de documentos públicos* (apoiado pelo Modo 3 — Triagem de Evidências).

---

## 1. Objetivo do levantamento

Identificar, classificar e arquivar documentos diplomáticos vazados publicamente acessíveis que tenham aderência probatória aos três estudos de caso da dissertação (Honduras 2009, Paraguai 2012, Colômbia 2016+) e à hipótese de coexistência OEA/CELAC sob constrangimento hegemônico.

Cabos vazados **não substituem** o corpus oficial (resoluções da OEA, declarações da CELAC, relatórios da CIDH e da MAPP) — funcionam como **camada de contraste**, reconstituindo percepção e ação do hegemon estadunidense em paralelo à ação institucional dos organismos regionais.

## 2. Fronteira ética e legal

A pesquisa observa estritamente o protocolo de OSINT do Agente Mestre. Trabalha-se apenas com material:

- publicamente acessível;
- legalmente obtível pelo pesquisador;
- já publicado por arquivo público, repositório de pesquisa, veículo de mídia reconhecido ou organização jornalística (Public Library of US Diplomacy/WikiLeaks; National Security Archive/GWU; The Intercept);
- relevante para investigação acadêmica de interesse público legítimo.

**Não foram empregados** — e não devem ser empregados em qualquer extensão da pesquisa — hacking, contorno de controles de acesso, redistribuição de *dumps* de vítimas de ransomware, coleta de dados privados ou exploração de credenciais.

## 3. Plataformas consultadas

| Plataforma | Cobertura | Aderência ao projeto |
|---|---|---|
| **WikiLeaks — Public Library of US Diplomacy (PlusD)** | 1973–fev/2010; cabos do Departamento de Estado dos EUA. Inclui o *Cablegate* (251.287 cabos vazados em 2010) e os *Kissinger Cables* (1.7M de memorandos desclassificados). | Alta para Honduras 2009 e Paraguai 2009 (precursores do impeachment de 2012). Limitada para Colômbia 2016+ (fora da janela temporal). Ausente para CELAC institucional (organização criada em dez/2011). |
| **National Security Archive (GWU) — Colombia Project** | Documentos desclassificados via FOIA. Inclui registros sobre processo de paz colombiano, escândalo Santrich, DAS e Naranjo. | Única fonte estruturada para Colômbia 2016+. |
| **The Intercept** | Reportagens com base em vazamentos pós-2013 (Snowden e correlatos). | Cobertura tangencial; útil para contexto da estratégia de contenção. |
| **Cubadebate, Venezuelanalysis, Jacobin, The Nation** | Veículos com curadoria de cabos relativos à América Latina. | Triangulação; não substituem a leitura direta dos cabos. |

## 4. Caminho de pesquisa executado (registro de procedência)

### 4.1 Identificação da plataforma-âncora

1. Localizou-se o PlusD como repositório único que reúne `Cablegate` + `Kissinger Cables` ([Phys.org, 08/04/2013](https://phys.org/news/2013-04-wikileaks-searchable-historical-archive.html); [Verso Books — Indexing the Empire](https://www.versobooks.com/blogs/news/2867-indexing-the-empire-how-to-use-wikileaks-public-library-of-us-diplomacy)).
2. Confirmou-se a janela temporal — 1973 a fev/2010 — e o volume — 251.287 cabos no Cablegate, dos quais ~30.386 referentes à América Latina ([The Nation, 29/06/2015](https://www.thenation.com/article/archive/wikileaks-latin-america-files/)).

### 4.2 Queries estruturadas executadas

#### Honduras 2009

```
WikiLeaks Honduras 2009 coup Zelaya OAS cables Tegucigalpa Llorens
WikiLeaks cables Honduras 2009 OEA Insulza Carta Democrática
Public Library US Diplomacy PlusD Honduras June 2009 Zelaya
site:wikileaks.org plusd cables Honduras Zelaya 2009 OAS
```

#### Paraguai 2012 (e precursores de 2009)

```
WikiLeaks cables Paraguay Lugo impeachment 2012 OAS UNASUR
WikiLeaks Asunción cable Paraguay Lugo Franco
Public Library US Diplomacy Paraguay Lugo cables
WikiLeaks cable Paraguayan pols plot parliamentary putsch
WikiLeaks cable Lugo impeachment rumors 2009 Asuncion
```

#### Colômbia (Uribe/Santos pré-2010 e processo de paz pós-2012)

```
WikiLeaks cables Colombia FARC peace process MAPP OAS Bogotá
WikiLeaks Colombia Santos Uribe cables peace negotiations
National Security Archive Colombia peace process FARC declassified documents
National Security Archive Colombia Santos Havana negotiations FOIA
Intercept Colombia FARC peace 2016 leaked documents
```

#### CELAC e regionalismo pós-hegemônico

```
WikiLeaks cables CELAC creation 2010 Caracas Chavez Calderon
WikiLeaks Rio Group cables Latin America OAS alternative
Public Library US Diplomacy CELAC post-hegemonic regionalism
```

### 4.3 Critérios de retenção

Um documento foi retido para o dossiê se atendesse a **todos** os seguintes critérios:

1. Origem confirmada em embaixada ou Departamento de Estado dos EUA.
2. Data verificável e disponível em pelo menos duas fontes (PlusD + cobertura jornalística).
3. Conteúdo com aderência direta a uma das três dimensões analíticas do projeto (Institucionalidade, Narrativa Política, Resultados Práticos) ou ao operador teórico da hegemonia.
4. Inexistência de redação substancial que comprometesse a leitura analítica.

### 4.4 Lacunas estruturais identificadas

- **Colômbia 2016+**: o processo formal de paz (Mesa de Havana, Acordo Final, plebiscito, implementação) está fora da janela do PlusD. A solução adotada foi recorrer ao [Colombia Project do National Security Archive](https://nsarchive.gwu.edu/project/colombia-project), que cobre o caso Santrich e a interferência da DEA pós-2016 ([NSA, OCR do relatório da Comissão da Verdade, 2022](https://nsarchive.gwu.edu/media/29482/ocr)).
- **CELAC institucional**: nenhum cabo do PlusD trata diretamente da CELAC enquanto organização (criada em dez/2011). O material existente cobre a estratégia estadunidense de contenção a Chávez, considerada estruturalmente conexa ao surgimento do regionalismo pós-hegemônico que cristaliza a CELAC ([Cambridge Core — Containing Hugo Chávez](https://www.cambridge.org/core/books/abs/official-record/containing-hugo-chavez-insights-from-the-wikileaks-cables/1CEE2835836CAE5295CD2628E62A0B1F)).
- **Atas do Conselho Permanente da OEA**: não vazadas; permanecem documentos oficiais. Download manual em oas.org (bloqueio anti-bot).

## 5. Triagem A-E aplicada (Modo 3 — Triagem de Evidências)

A escala segue o protocolo do Agente Mestre. Cada cabo do dossiê foi classificado individualmente em `03_Fontes_Vazadas/MATRIZ_FONTES_VAZADAS.md`.

| Classe | Definição | Exemplo no dossiê |
|---|---|---|
| **A** | Fonte primária oficial, autenticada, com cadeia de custódia rastreável. | Resoluções da OEA, declarações da CELAC. |
| **B** | Fonte primária problemática — vazamento publicado, cuja autenticidade foi reconhecida ou nunca contestada, com cadeia de custódia parcialmente rastreável. | Cabo 09TEGUCIGALPA645 (Llorens, 23/07/2009). |
| **C** | Fonte secundária reputada com acesso ao material primário. | National Security Archive; cobertura McClatchy/Knight Center. |
| **D** | Cobertura jornalística baseada em B ou C. | The Nation, Jacobin, The Conversation. |
| **E** | Material com proveniência incerta ou advocacy puro. | Excluído do corpus. |

## 6. Regra fixa de citação no texto da dissertação

Toda citação de cabo vazado deve obedecer ao formato:

> O cabo X (Embaixada Y, data Z, classificação W), publicado pela WikiLeaks no contexto do *Cablegate*, afirma que [...]. Analiticamente, isso sugere [...], sob a ressalva de que cabos refletem percepção da diplomacia estadunidense, não posição consolidada do Departamento de Estado nem ação institucional verificada da OEA.

A separação **"o cabo diz X → analiticamente, sugere Y"** é exigência inegociável da disciplina metodológica do projeto.

## 7. Próximos passos

1. Recuperar via [Wayback Machine](https://web.archive.org/) o texto integral do cabo 09TEGUCIGALPA645 (atualmente a página do PlusD exibe apenas metadados após mudança de layout).
2. Cruzar inventário do PlusD com os Electronic Briefing Books do National Security Archive sobre Colômbia para mapear cobertura pós-2016.
3. Aplicar a codificação ACQ (`NV-NI`, `NV-SOB`, `NV-AUT`) sobre os textos integrais — não sobre os fichamentos — quando do início da Fase III.
4. Registrar no fichamento de cada cabo a ressalva metodológica padrão (item 6).

---

**Aviso final.** Um documento vazado não é automaticamente evidência mais forte que um documento oficial. Trate material vazado como primário-mas-problemático: útil **apenas** quando proveniência, contexto e corroboração são tratados explicitamente.
