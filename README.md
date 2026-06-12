# Mestrado IDP — OEA e CELAC na governança regional latino-americana

Repositório de pesquisa do mestrado de **Pedro Paulo Henrichs Neto** no programa de Ciência Política e Relações Internacionais do Instituto Brasileiro de Ensino, Desenvolvimento e Pesquisa (IDP), Brasília/DF.

> **Política de visibilidade.** O repositório opera como **privado por padrão** e é tornado **público apenas em janelas de trabalho conjunto com assistentes de IA externos** (Claude, GPT, Perplexity) que precisam ler arquivos diretamente do GitHub. Encerrada a janela, retorna ao estado privado. Trabalho acadêmico em curso — não distribuir, não citar.

**Título da dissertação:** *Entre hegemonia e autonomia: OEA e CELAC na disputa pela governança regional latino-americana.*

**Pergunta de pesquisa:** Em que medida a dualidade entre a Institucionalidade da OEA e a Narrativa Política da CELAC se manifesta na eficácia e seletividade da governança regional latino-americana em crises de ruptura democrática?

**Estudos de caso:** Honduras (2009) · Paraguai (2012) · Colômbia (2016+).

---

## Estrutura do repositório

```
mestrado-idp-oea-celac/
├── 00_Projeto/                      Projeto de qualificação, cronograma, hipóteses
├── 01_Metodologia_OSINT/            Caminho de pesquisa em fontes vazadas/abertas
├── 02_Corpus_Oficial/               Documentos oficiais (OEA, CELAC, CIDH, ONU, MERCOSUL/UNASUL)
│   ├── OEA/                         Resoluções CP, AG, informes MAPP, atas
│   ├── CELAC/                       Declarações de cúpula, comunicados PPT
│   ├── CIDH/                        Relatórios de país e anuais
│   ├── ONU/                         Resoluções AG e CSNU correlatas
│   └── MERCOSUL_UNASUL/             Declarações de Mendoza, Decisão 26/2012
├── 03_Fontes_Vazadas/               Cabos diplomáticos vazados (WikiLeaks PlusD, NSA)
│   ├── Honduras_2009/
│   ├── Paraguai_2012/
│   ├── Colombia_2016/               (cobertura indireta — pré-2010)
│   └── CELAC_Bolivarianismo/        Contenção dos EUA ao processo bolivariano
├── 04_Fichamentos_ABNT/             Fichas individuais por documento (padrão ABNT)
│   └── literatura_celac/            5 artigos terceiros sobre CELAC/integração regional
├── 05_Matrizes_ACQ/                 Análise de Conteúdo Qualitativa (NV-NI, NV-SOB, NV-AUT)
├── 06_Bibliografia/                 Referencial teórico e leituras de apoio
│   ├── datasets_publish_or_perish/  Exports Google Scholar (PoP) para Cap. 2
│   └── referencias_complementares/  Artigos de apoio cruzado (fake news, NetLAB)
├── 07_Midia_Regional/               Matriz de mídia regional por país-caso
├── 08_Materiais_IDP/                Manuais do programa + planos de ensino das disciplinas cursadas
├── 09_Textos_Autorais/              Produção do mestrando ao longo do programa
│   ├── honduras_contrafacao/        Texto principal sobre Honduras 2025 (continuum 2009→2025)
│   ├── filosofia_politica/          Trabalho final disciplina Filosofia Política
│   ├── artigos_revista/             Artigos em preparação para revista (PT, Equador, Chile, Irã, Belém)
│   ├── ensaios_diversos/            Ensaios de outras disciplinas (Aras, Nicarágua, IAs)
│   └── apresentacoes/               PPTX da dissertação + apresentações principais
├── 10_Outras_Disciplinas/           Trabalhos de disciplinas cursadas (não diretamente correlatos à dissertação)
│   ├── comercio_internacional_OMC/  Disciplina IDP Comércio Digital 2025.1
│   ├── mercosul_ue_acordo/          Plano estratégico ratificação acordo Mercosul-UE
│   ├── smart_cities_maricá/         Trabalho Smart Cities + Mumbuca + Maricá (IPEA)
│   ├── governanca_climatica/        Amazônia urbana + apresentação Liderança Setor Público
│   ├── representacao_feminina/      Apresentações Mulheres Parlamentares (Prof. Pablo)
│   └── outros/                      Pé de Meia, IOF, coalizões, resenhas avulsas
├── 11_Instrumentos_Pesquisa/        Roteiro entrevistas, TCLE, TCLI, Quadro Z, Custos
└── 12_Entrevistas_Anotacoes/        Entrevista Pablo Vilas + anotações trabalho contextuais
    └── equador_2025_contexto/       Decreto Noboa, lawfare, análises de trabalho (caso fora do recorte)
```

## Marco metodológico

- **Desenho:** Comparação Focada e Estruturada (Gerring; George & Bennett; Yin).
- **Técnica analítica:** Análise de Conteúdo Qualitativa (ACQ) — Bardin, com codificação por temas: `NV-NI` (Não-Intervenção), `NV-SOB` (Soberania), `NV-AUT` (Autodeterminação).
- **Dimensões analíticas:** Institucionalidade · Narrativa Política · Resultados Práticos.
- **Triangulação obrigatória:** Nenhuma inferência central pode depender de fonte única.

## Hipóteses

- **H1 (central):** A CELAC opera como fórum político de governança pós-hegemônica, usando flexibilidade institucional e coerência discursiva como fontes de legitimidade, em contraste com a OEA, que representa a institucionalização histórica da hegemonia estadunidense.
- **H2 (secundária):** A coexistência OEA/CELAC expressa dualidade funcional não excludente — OEA como arena normativo-jurídica; CELAC como fórum político-dialógico.

## Princípios de uso das fontes vazadas

O diretório `03_Fontes_Vazadas/` segue a regra fixa do projeto: cabos diplomáticos vazados são tratados como **fonte primária-mas-problemática**. Cada fichamento explicita proveniência, cadeia de custódia (WikiLeaks/Cablegate 2010; PlusD 2013) e ressalva de que cabos refletem **percepção da diplomacia estadunidense**, não posição consolidada do Departamento de Estado nem ação institucional verificada da OEA ou da CELAC.

A metodologia completa — fronteira ética, queries empregadas e racional de seleção — está em [`01_Metodologia_OSINT/MEMORANDO_OSINT.md`](01_Metodologia_OSINT/MEMORANDO_OSINT.md).

## Casos deliberadamente excluídos

Venezuela, Nicarágua (2018), Bolívia (2019), Cuba (1962–2014), Haiti (2010), UNASUL (2008) e Malvinas (1982). Justificativa metodológica registrada no projeto de qualificação (item 5).

## Estado da pesquisa

- Fase I — Projeto e referencial teórico: ✅ concluída.
- Fase II — Pesquisa documental: 🟢 substancialmente adiantada (33 documentos-núcleo mapeados; ~85% com link primário oficial verificado; 1.º documento integral incorporado: **CP/ACTA 1700/09**). Lacunas restantes são de download manual, não de localização.
- Fase III — Codificação ACQ: ⏳ a iniciar (codebook `NV-NI/NV-SOB/NV-AUT` já definido em `05_Matrizes_ACQ/`).
- Fase IV — Redação dos capítulos: ⏳ a iniciar.
- Qualificação prevista: 7º–8º mês do programa.

## Lotes documentais incorporados

| Lote | Data | Descrição | Localização |
|---|---|---|---|
| 1 | jun/2026 | Corpus oficial mapeado por caso (Honduras, Paraguai, Colômbia) | `02_Corpus_Oficial/caso{1,2,3}_*.md` |
| 2 | jun/2026 | Complemento CELAC + correção factual (CELAC não suspendeu Paraguai) + Ata I Reunião de Ministros CELAC (NY, 27/09/2012) | `02_Corpus_Oficial/lote2_complemento.md`, `02_Corpus_Oficial/CELAC/` |
| 3 ★ | 12/06/2026 | **Chave técnica para atas do CP/OEA** + 1.º documento integral incorporado (CP/ACTA 1700/09, 32 p.) + 8 atas oficiais OEA + 3 atas literais ONU | `02_Corpus_Oficial/lote3_complemento.md`, `02_Corpus_Oficial/OEA/`, `02_Corpus_Oficial/ONU/` |
| 4 ★ | 12/06/2026 | **Acervo autoral consolidado:** 179 anexos triados em 11 lotes → ~141 mantidos. Inclui Contrafação Honduras 2025 (final), Revisão Integrativa PRISMA (Cap. 2), Entrevista Pablo Vilas (ex-CELAC), 5 artigos terceiros para fichamento, datasets Publish-or-Perish, projeto qualificação (9 versões históricas) | Ver [MATRIZ_TRIAGEM_ANEXOS.md](MATRIZ_TRIAGEM_ANEXOS.md) — todas as pastas `08_` a `12_` |

### Chave técnica para atas do Conselho Permanente da OEA (lote 3)

As páginas `.asp` do sítio oas.org operam atrás de barreira Cloudflare que bloqueia acesso automatizado. Porém:

1. Os PDFs das atas são servidos em URL previsível:
   ```
   https://www.oas.org/consejo/sp/actas/acta{NNNN}.pdf
   ```
   onde `NNNN` é o número entre parênteses na referência oficial de cada resolução (ex.: CP/RES. 953 (1700/09) → `acta1700.pdf`).
2. A Wayback Machine contém snapshots completos a partir de 2020. Para baixar:
   ```bash
   curl -sL -A "Mozilla/5.0" -o acta1700.pdf \
     "https://web.archive.org/web/2020id_/http://www.oas.org/consejo/sp/actas/acta1700.pdf"
   ```

Isso destrava a fonte mais valiosa do corpus: as falas por delegação, permitindo ACQ no nível do ator (não só do organismo).

## Regra de transcrição (todo PDF → cópia em MD)

Todo documento PDF incorporado ao corpus oficial deve ter uma cópia em Markdown ao lado, com o sufixo `_transcricao.md`. A transcrição automatíca é gerada por `pdftotext -layout` e serve apenas para leitura por assistentes de IA (Claude, Perplexity, GPT) — economia substancial de tokens quando o documento precisa ser consultado.

**Padrão:**
- `arquivo.pdf` → documento oficial para citação (sempre conferir contra ele).
- `arquivo_transcricao.md` → texto plano para IAs ou busca de termos. **Nunca citar a transcrição na dissertação** — a transcrição automatica pode conter erros de OCR/extração.
- `arquivo.md` (sem sufixo) → quando existir, é a transcrição **anotada** à mão com sumarização e marcações analíticas (caso da CP/ACTA 1700/09).

**Comando padrão** para gerar transcrição de novo PDF incorporado ao corpus:

```bash
pdftotext -layout arquivo.pdf - > arquivo_transcricao.md
# (acrescentar manualmente o cabeçalho de proveniência com fonte e data de extração)
```

## Fichamentos já redigidos (padrão ABNT)

| Ficha | Documento | Tipo |
|---|---|---|
| FICHA_H1 | Cabo 09TEGUCIGALPA645 (Llorens, Honduras) | Fonte vazada (B) |
| **FICHA_H2** ★ | CP/ACTA 1700/09 (Honduras, 28/06/2009) | **Fonte primária oficial (A) — integral** |
| FICHA_P1 | Cabo 09ASUNCION293 (SUBJECT real: *Circling sharks in landlocked Paraguay*) | Fonte vazada (B) |
| FICHA_P2 | Cabo 09ASUNCION675 (SUBJECT real: *Scenesetter for A/S Valenzuela's visit to Paraguay*) | Fonte vazada (B) |
| FICHA_C3 | NSA Colombia Project (Santrich/DEA) | FOIA (B) |
| FICHA_CL1 | Cabo Brownfield/USAID-OTI | Fonte vazada (B) |
| FICHA_RIPRISMA | Revisão Integrativa CELAC/OEA (Henrichs, mai/2025) | Texto autoral / PRISMA |
| FICHA_Contra2025 | Contrafação da Autonomia Política — Honduras 2025 (Henrichs, fev/2026) | Texto autoral |
| FICHA_PVilas | Entrevista Pablo Vilas (ex-coordenação CELAC) | Entrevista (status preparatório) |

---

**Confidencialidade.** Repositório privado por padrão (ver política de visibilidade no topo). Não distribuir sem autorização do autor.
