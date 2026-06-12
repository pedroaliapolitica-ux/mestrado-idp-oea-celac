# Transcrição: ChatGPT_e_outras_IAs

**Origem:** `09_Textos_Autorais/ensaios_diversos/ChatGPT_e_outras_IAs.pdf`
**Extração:** pdftotext -layout (auto)

---
                                                                                               Artigo Original


ChatGPT e outras IAs transformarão a
pesquisa científica: reflexões sobre seus usos

                                                                                               DOI 10.1590/1678-98732432e008
                                     I
Rafael Cardoso Sampaio       ✉,
Maria Alejandra NicolásII ✉,
Tainá Aguiar JunquilhoIII ✉,
Luiz Rogério Lopes SilvaIV ✉,
Christiana Soares de FreitasV ✉, Márcio TellesVI ✉,
João Senna TeixeiraVII ✉, Fernanda da EscóssiaVIII ✉,
Luiza Carolina dos SantosIX ✉
I
 Programa de Pós-Graduação em Ciência Política, Universidade Federal do Paraná, Curitiba, PR, Brasil.
II
  Mestrado em Políticas Públicas e Desenvolvimento, Universidade Federal da Integração Latino-Americana, Foz do Iguaçu,
        PR, Brasil.
III
    Programa de Direito, Instituto de Direito Brasileiro de Ensino Pesquisa e Desenvolvimento, Brasília, DF, Brasil.
IV
    Programa de Pós-graduação em Gestão da Informação, Universidade Federal do Paraná, Curitiba, PR, Brasil.
V
  Programa de Pós-Graduação em Comunicação, Universidade de Brasília, Brasília, DF, Brasil.
VI
    Programa de Pós-Graduação em Comunicação e Linguagens, Universidade Tuiuti do Paraná, Curitiba, PR, Brasil.
VII
     Instituto Nacional de Ciência e Tecnologia em Democracia Digital, Universidade Federal da Bahia, Salvador, BA, Brasil.
VIII
      Faculdade de Comunicação Social, Universidade do Estado do Rio de Janeiro, Rio de Janeiro, RJ, Brasil.
IX
    Departamento de Jornalismo, Universidade de Ponta Grossa, Ponta Grossa, PR, Brasil.

Palavras-chave: ChatGPT, inteligência artificial generativa, aprendizado de máquina, pesquisa científica, revisão de literatura.

RESUMO Introdução: A chegada de grandes modelos de linguagem tem implicações profundas para diversas profissões da atuali-
dade e a atividade acadêmica não é exceção. O artigo aborda as transformações que o ChatGPT e outras inteligências artificiais (IAs)
podem causar na pesquisa acadêmica, no âmbito da busca, seleção e leitura de literatura, análise e apresentação de dados e escrita
e tradução de textos. Materiais e métodos: Foi feita uma revisão narrativa da literatura científica. A seguir, apresentamos e analisa-
mos algumas ferramentas de IA acadêmicas disponíveis em 2023. Resultados: Discutimos possíveis consequências, riscos e para-
doxos no uso de IAs para a pesquisa, tais como dilemas de autoria, deterioração da integridade da pesquisa, limitação das
abordagens metodológicas, modificações nas dinâmicas de produção de conhecimento. Discussão: Concluímos demandando por
um diálogo aprofundado sobre políticas públicas de regulação e criação de tecnologias adaptadas às necessidades das pesquisas do
Sul Global.

Recebido em 24 de Setembro de 2023. Aprovado em 16 de Janeiro de 2024. Aceito em 12 de Março de 2024.

                   1
I. Introdução
     1
       Agradecemos aos


                                         E
                                                  m novembro de 2022, a organização OpenAI lançou publicamente o
     pareceristas anônimos pelas
     sugestões e, especialmente, a
                                                  ChatGPT (Chat Generative Pre-Trained Transformer), chatbot cons-
     coordenação editorial da                     truído para estabelecer com os usuários interações em linguagem na-
     revista. Esta pesquisa contou       tural e formato de diálogo. Diferentemente de outras ferramentas anteriores,
     com apoio do CNPq (bolsa PQ         como chatbots repetitivos e assistentes pessoais automatizados e restritos
     311705/2023-5 edital 2023).
                                         (Santos, 2022), o ChatGPT demonstra capacidade de responder e criar diálo-
                                         gos similares aos de humanos, mantendo uma conversação longa. Além disso,
                                         este e outros modelos de inteligência artificial (IA) generativa permitem a
                                         automação de diversas tarefas, como escrever e-mails, preencher formulários,
                                         criar textos-padrão, traduzir, resumir, sintetizar, organizar e estruturar con-
                                         teúdos, realizar revisão sistemática de literatura, transcrever áudios, “criar” e
                                         corrigir scripts de programação - tudo através de comandos em linguagem na-
                                         tural, chamados de prompts (Alexopoulos et al., 2023; Ramos, 2023; Van Dis
                                         et al., 2023).


                                                                                                   Rev. Sociol. Polit., v. 32, e008, 2024
2/24                                                   Revista de Sociologia e Política v. 32


           As primeiras reações vieram de educadores, preocupados com a capaci-
       dade do ChatGPT de criar textos e responder de modo razoável a qualquer tipo
       de questão (Cotton et al., 2023) e com a possibilidade de ser usado para fazer
       testes, provas e exercícios em casa.
           As capacidades do ChatGPT e sua aplicabilidade em diferentes áreas do
       conhecimento, como marketing, direito, jornalismo, programação, ciência de
       dados e afins, impulsionaram um debate que vem sendo travado há alguns
       anos: a automação do trabalho e a substituição de profissionais humanos por
       tecnologias (Rodríguez et al., 2020). Os avanços que o ChatGPT representa
       tornaram essa realidade mais próxima; entretanto, o ChatGPT não é a única IA
       generativa nem o único modelo grande de linguagem (large language models,
       LLMs daqui em diante no artigo).

           Para compreender os LLMs, é necessário entender três conceitos: aprendi-
       zado de máquina, o método Transformers para processamento de texto e a
       importância dos dados massivos utilizados. Aprendizado de máquina é um
       campo da inteligência artificial que desenvolve algoritmos capazes de tomar
       decisões sem programação humana direta, aprendendo padrões e agindo de
       forma independente. Baseia-se em conjuntos de dados para treinar modelos
       que prevejam corretamente os estados desses dados, criando hipóteses com
       base em dados passados para fazer previsões futuras (Jung, 2022). Existem
       métodos de aprendizado de máquina com diferentes níveis de interferência
       humana, mas o objetivo é que o algoritmo aprenda a realizar a ação de forma
       autônoma, com revisão humana (isto é, human in the loop) ou ajustes no
       reforço positivo/negativo após análise dos resultados.

           Transformer é uma abordagem de análise textual fundamentada no concei-
       to de atenção, no qual cada elemento do texto é representado como um vetor
       em relação a todos os outros elementos do texto. A técnica de transformer
       permite que termos sejam relacionados entre si independentemente da sua dis-
       tância no texto e classifica os elementos em termos de importância, tudo isso
       com grande capacidade de paralelismo (Vaswani et al., 2017). Desta forma, o
       modelo é capaz de entender melhor o contexto do texto, pois, enquanto avalia
       o mais importante em termos de conteúdo, auxilia na construção do texto ao
       tentar prever a próxima palavra pela soma dos vetores da sentença e não só
       pela última palavra. Esse mesmo modelo de atenção é utilizado em IAs multi-
       modais, capazes de gerar imagens ou vídeos a partir de comandos de texto ou
       de sumarizar imagens ou vídeos em texto.

           O modelo Transformers permitiu a explosão do tamanho dos modelos de
       linguagem natural para se tornarem LLMs, pois fez com que eles se tornassem
       generalizáveis. Se antes, para ter um chatbot útil, era necessário treiná-lo com
       uma base de dados específica, agora é possível aumentar a base de dados ge-
       nérica e ter alguma garantia de que ela poderá ser utilizada para os mais diver-
       sos objetivos. É por causa dessa versatilidade, além da possibilidade de
       processamento em paralelo, que se chegou à criação de modelos cada vez
       maiores desde 2018, culminando no GPT-4 com mais de 1 trilhão de parâ-
       metros. No entanto, apesar dessa diferença de 100 vezes no número de parâ-
       metros em comparação ao GPT-3, não foi vista uma melhoria similar em
       performance, indicando que estamos em uma situação de diminuição dos ga-
       nhos com modelos maiores (Achiam et al., 2023).

           De acordo com Almeida et al. (2023), os sistemas usados para entender e
       interpretar a linguagem humana são conhecidos como modelos de linguagem e
       operam de maneira a prever palavras ou símbolos que podem vir a seguir em
       uma sentença. Para tornar essas previsões possíveis, os modelos são treinados
Sampaio et al.                                                                                                  3/24

    2                                                                                         2
      O GPT-3 foi treinado com       através do uso de grandes quantidades de textos escritos . Tais sistemas apli-
    175 bilhões de parâmetros,
                                     cam os chamados modelos generativos, conjuntos de regras e instruções que
    majoritariamente de páginas
    da internet (60%), textos        aprendem como as palavras são normalmente usadas juntas. Essas regras são
    online (22%), livros (16%) e     usadas para prever como novos textos podem ser formados, tentando imitar o
    Wikipédia (3%). O GPT-4,         mais fielmente possível o modo como as palavras são usadas por humanos.
    mais avançado, foi treinado
    com mais de um trilhão de            O ChatGPT e outros LLMS não são muito diferentes de um papagaio que
    parâmetros (Brown et al.,
    2020).                           tenta repetir o que aprendeu após doses massivas de treinamento. O modelo
                                     elabora palavra por palavra, baseado na probabilidade de um humano ter utili-
                                     zado aquela sequência de palavras. Exatamente por isso, tais modelos nunca
                                     repetem exatamente as respostas e, com alguma frequência, erram ao respon-
    3                                                                                      3
       Prompts, parâmetros do        der, causando o que tem sido chamado de alucinações (Hacker et al., 2023).
    modelo ou instruções
                                     Elas acontecem quando a máquina escolhe uma probabilidade que é sintatica-
    armazenadas no perfil do
    usuário podem diminuir as        mente possível, mas falsa em termos de fatos e dados (Alkaisse & Mcfarlane,
                                           4
    chances de alucinação.           2023) .
    4
       Os hiperparâmetros são
    essenciais para o desempenho         A rápida adoção do ChatGPT e de modelos generativos de imagens, como
    dos modelos, ajustando a         Midjourney e Stable Diffusion, afetou não apenas as buscas online, mas uma
    aleatoriedade das previsões
    (temperatura), a diversidade
                                     série de outros setores, incluindo plataformas digitais e diversos setores da
    do texto (penalidade de          economia, do sistema financeiro à saúde, passando por educação e entreteni-
    repetição), a quantidade de      mento. Temos até o momento ao menos quatro modelos comerciais bastante
                                                                               5                  6
    informação processada            difundidos, o ChatGPT, Claude, Copilot , Gemini e Llama . Alguns desses
    (tamanho dos tokens) e a
    seleção de palavras (função de   modelos, incluindo o GPT, disponibilizam APIs (Interface de programação de
    massa de probabilidade).         aplicações) que permitem a integração com diferentes ferramentas e a criação
    Ajustados, podem diminuir as     de instrumentos em cima da base do modelo.
    alucinações.
    5
       No momento, o Copilot             Em decorrência do seu modo de funcionamento, os tipos de IA difundidos
    apenas usa o modelo do
                                     atualmente, que se baseiam em redes neurais e aprendizado de máquina, apre-
    ChatGPT em ferramentas da
    Microsoft.                       sentam vieses. Nesse sentido, tendem a reproduzir premissas e escolhas reali-
    6
       Llama foi um modelo           zadas durante seus processos de criação e desenvolvimento, incorporando as
    liberado pela Meta em formato    visões de seus desenvolvedores, dos trabalhadores que realizam o treinamento,
    open source para seus
                                     bem como a rotulação dos dados e dos próprios bancos de dados escolhidos
    usuários.
                                     para treinamento. Para não explicar as decisões dos modelos de IA, as empre-
                                     sas geralmente se apoiam no argumento da proteção do segredo comercial,
                                     alegando que não podem tornar tais modelos transparentes pela competição no
                                     mercado; na prática, há muitos pontos obscuros e questionáveis, desde deci-
                                     sões e algoritmos envolvidos, passando pelos conjuntos de dados utilizados no
                                     treinamento (Dwivedi et al., 2023; Hacker et al., 2023).
                                         A UNESCO vem liderando uma discussão relevante sobre IA e educação.
                                     Dentre as ações, destaca-se o documento final da Conferência Internacional
                                     sobre Inteligência Artificial e Educação em Beijing (UNESCO, 2019), que
                                     apontou a importância de promover a colaboração internacional para desen-
                                     volver e implementar soluções de IA para a educação, garantir que a IA seja
                                     usada de forma ética e acessível a todos. O relatório do “International Forum
                                     on AI and the Futures of Education Developing Competencies for the AI Era”
                                     (Miao & Holmes, 2020) aponta benefícios e riscos da IA na educação, enfati-
                                     zando a necessidade de cautela na sua implementação para evitar disparidades
                                     de desempenho e promover um quadro abrangente para lidar com privacidade
                                     e segurança de dados. O documento recomenda a revisão curricular de todos
                                     os níveis de ensino, oferecendo educação sobre IA a todos os cidadãos e
                                     desenvolvendo diretrizes éticas para seu uso (O'Neil, 2021).

                                        Reconhecendo as discussões e limitações atuais do desenvolvimento das
                                     IAs generativas, o objetivo deste ensaio é refletir sobre seus impactos na pes-
                                     quisa acadêmica, com atenção especial para as ciências humanas e sociais.
                                     Para isso, iremos focar nos usos possíveis e desafios colocados a partir do
4/24                                                                             Revista de Sociologia e Política v. 32


                                 desenvolvimento de tais tecnologias, aproximando-as de aplicações práticas
                                 que temos experimentado em primeira mão ou a partir de relatos de colegas.
                                 Em nossa visão, o ChatGPT, LLMs e outros aplicativos baseados em IA têm
                                 potencial de modificar significativamente a forma de estudar e pesquisar. Esta-
                                 mos diante de uma quebra de paradigma e de práticas similares à passagem da
                                 máquina de datilografar aos computadores, à introdução da pesquisa online
                                 pelo Google e ao surgimento de enciclopédias colaborativas, como a Wikipe-
                                 dia.

                                     Este ensaio está dividido em três seções principais para além desta intro-
                                 dução. A primeira apresenta usos de sistemas de inteligência artificial para ta-
                                 refas rotineiras da pesquisa acadêmica de forma mais prática e aplicada, tendo
                                 em vista as ferramentas já disponíveis no momento e seu possível desenvolvi-
                                 mento no futuro próximo. Analisamos a utilização de ferramentas auto-
                                 matizadas para busca e seleção de literatura acadêmica, leitura de material,
                                 análise de dados e programação, escrita, tradução, apresentação dos dados. A
                                 segunda seção reflete sobre possíveis consequências, riscos e paradoxos no uso
                                 de IAs para a pesquisa científica. Discutimos questões de autoria e plágio,
                                 diminuição da integridade do fazer científico, restrição do leque de possibili-
                                 dades para a pesquisa, paradoxo da produção de conhecimentos. A conclusão
                                 discute a necessidade e formas possíveis de regulação governamental de tais
                                 tecnologias e do desenvolvimento de ferramentas mais adaptadas para nosso
                                 contexto de Sul Global.



II. Uso das IAs generativas: mudanças no fazer científico

                                     Esta seção apresenta plataformas, ferramentas, aplicativos, modelos e sis-
                                 temas baseados em inteligência artificial que podem ser utilizados em diferen-
                                 tes etapas da pesquisa acadêmica. O objetivo é compreender como funcionam
                                 esses sistemas, bem como as possibilidades de uso na produção do conheci-
                                 mento científico.



II.1. Busca e seleção de literatura acadêmica

                                    Enquanto o ChatGPT e outros LLMs podem trazer mudanças para-
                                 digmáticas para a escrita acadêmica, outros aspectos do fazer científico ainda
                                 não foram suficientemente valorizados no debate. Como Copilot, Germini e
                                 Perplexity evidenciam, teremos provavelmente diferenças notáveis na forma
                                 como procuramos e selecionamos a literatura acadêmica. Diferentemente da
                                 busca tradicional em bases indexadoras, como SciELO, Scopus e Web of Sci-
                                 ence (WoS), por palavras-chaves ou expressões que esperamos encontrar nos
                                 metadados do tópico do artigo (título, resumo, palavras-chave), e que jogamos
                                 com busca booleana (AND, OR, NOT), acreditamos que tais sistemas de IA
                                 vão nos levar para um caminho de busca semântica e, possivelmente, interação
                                 com os dados.

                                    Em outras palavras, a exemplo do ChatGPT e afins, provavelmente pes-
                                 quisaremos fazendo perguntas. Por exemplo, em vez de pesquisarmos pelos
                                 termos “fake news” AND “eleições” AND “efeitos”, perguntaremos objetiva-
                                 mente a tais sistemas, “quais são os efeitos de fake news em eleições?”. As
                                 respostas virão em trechos de artigos e outros materiais acadêmicos que bus-
                                 cam responder diretamente a nossos questionamentos. No exemplo abaixo,
Sampaio et al.                                                                                                    5/24


                                      SciSpace e Perplexity imediatamente apresentam questões follow-up, ou seja,
                                      que podem continuar o debate sobre o tema dado.

                                          Conforme a Figura 1, a principal diferença é que tais sistemas de busca
                                      acadêmica baseados em IA não apenas dão uma lista de referências, mas tam-
                                      bém apresentam trechos dos artigos relacionados à pesquisa e insights sobre
                                      estes, permitindo manter o diálogo em torno da questão original. No momento
                                      de escrita deste ensaio, algumas plataformas permitem “salvar” o histórico de
                                      diálogo e enviar, o que pode ser interessante em termos de replicabilidade e
                                      transparência de pesquisa.

                                          Várias ferramentas já estão fazendo isso, além do SciSpace e Perplexity.
                                      As mais avançadas no momento parecem ser o Elicit e o Consensus (Figura 2)
                                      - e esta faz algo importante para a decisão de leitura ou não do texto: mostra o
                                      estado de consenso de uma questão, desde que você faça uma pergunta que
                                      permita uma resposta no modelo “sim” ou “não”.
                                          Tais possibilidades complementam e aprofundam a experiência de busca
                                      de artigos. Entretanto, não diferem de modo significativo das experiências com
                                      as quais estávamos habituados em plataformas como Google Scholar, Seman-
                                      tic Scholar, Scinapse, dentre outras. Ainda na seara das buscas, há outras
                                      mudanças importantes. Agora, não mais fazendo uso de palavras-chaves ou
                                      questões, mas sim provendo referências acadêmicas ao sistema.



Figura 1 - Exemplo de questões follow-up no Perplexity




Fonte: captura de tela realizada pelos autores. Acesso em: 17 de set. 2023.
6/24                                                                                 Revista de Sociologia e Política v. 32


Figura 2 - Exemplo de resposta e cálculo do “consenso” pela plataforma Consensus




Fonte: captura de tela realizada pelos autores. Acesso em: 15 de set. 2023.



                                          Por exemplo, quando fornecemos ao Inciteful referências em formatos de
                                      gerenciadores de citação (como .bib ou .ris), ele nos retorna, conforme seus
                                      parâmetros, “textos similares”, os artigos considerados “mais importantes”,
                                      revisões recentes de “autores de destaque” e os textos recentes “mais rele-
                                      vantes” no tema pesquisado. Na mesma linha, existe um conjunto de plata-
                                      formas que, alimentadas com PDFs ou BIBs, fazem uso de técnicas de IA para
                                      gerar mapas de referência, mostrando conexões e redes de citações de materi-
                                      ais acadêmicos, como o próprio Inciteful, Connected Papers, Litmaps e
                                      Research Rabbit (Figuras 3 e 4). Em praticamente todas é possível criar uma
                                      biblioteca pessoal dentro do aplicativo e alimentar a inteligência artificial,
                                      aprimorando buscas e sugestões.

                                          À medida que o campo de pesquisa continua a crescer e se expandir, a ta-
                                      refa de realizar uma revisão da literatura torna-se cada vez mais desafiadora
                                      para os pesquisadores. Como apresentam respostas, dão listas de artigos mais
                                      “importantes” ou de trabalhos posteriores (isto é, later work), além de exi-
                                      birem grafos com as citações, esses aplicativos de IA podem acelerar as revi-
                                      sões de literatura, facilitando tanto a compreensão de lacunas na literatura
                                      quanto de temáticas e resultados consolidados, indicando de maneira rápida os
                                      artigos mais promissores a serem lidos.
Sampaio et al.                                                                                                     7/24


Figura 3 - Exemplo de mapa de citações do Litmaps




Fonte: captura de tela realizada pelos autores. Acesso em: 17 de set. 2023.

Figura 4 - Exemplo de redes de citação formadas pelo Research Rabbit




Fonte: captura de tela realizada pelos autores. Acesso em: 17 de set. 2023.

II.2. Leitura do material acadêmico

                                          A leitura de material acadêmico passará por mudanças significativas com a
                                      chegada dessas novas ferramentas. Por meio da IA generativa, será possível
                                      terceirizar para a IA a “leitura” desses materiais a partir do upload de arquivos,
                                      como PDFs e DOCX. Assim como acontece com o ChatGPT e ferramentas
                                      similares, tornou-se possível “conversar” com os arquivos. O ChatGPT
8/24                                                                                Revista de Sociologia e Política v. 32


                                      permite isso com ajuda de plugins ou na versão GPT4 com advanced data
                                      analysis, enquanto outros, como Claude e Perplexity, tornaram tal opção
                                      nativa, o que indica que isso deverá ser o modus operandi daqui em diante.

                                          Atualmente, várias plataformas se baseiam no modelo do GPT e/ou em
                                      outros LLMs, como o Elicit e o Scispace, já mencionados. Plataformas inde-
                                      pendentes ganharam destaque, como ChatPDF, Humata e My Reader. Ou
                                      seja, o usuário pode perguntar o que quiser para a AI sobre aquele upload e,
                                      com isso, interrogar o documento, questionando a quantidade de casos anali-
                                      sados, a metodologia, a conclusão ou os principais conceitos abordados. Ou
                                      simplesmente pedir que explique ou resuma um trecho ou conceito complexo e
                                      indique literatura correlata.

                                          Diferentemente de nossa leitura humana em gerenciadores de referência ou
                                      leitores de PDF, essas plataformas permitem analisar vários artigos simulta-
                                      neamente, conforme o exemplo do My Reader, na Figura 5, e do Claude, que
                                      permite o upload de cinco arquivos simultaneamente. Todas as questões acima
                                      poderão ser feitas diretamente a diferentes arquivos, pedindo indicações de
                                      pontos em comum e divergências entre os textos. Tais interações, que ficarão
                                      salvas, em breve alimentarão as IAs, que, conhecendo nossas preferências,
                                      poderão achar trechos e ideias similares nos documentos. Tais IAs tendem a
                                      substituir os gerenciadores padrões de referência (que, por sua vez, devem
                                      tentar sobreviver também lançando ou incorporando IAs).

                                         Várias ferramentas baseadas em IA vão facilitar de modo significativo o
                                      resumo dos materiais acadêmicos. Ao exemplo de ChatGPT, Claude e afins,
                                      vários aplicativos e plataformas conseguem resumir todo tipo de texto, como é
                                      o caso do aplicativo não acadêmico Resoomer. Neste momento, a plataforma
                                      dedicada a fazer resumos acadêmicos mais consolidada é a Scholarcy, com as
                                      características que provavelmente veremos com mais frequência no futuro
                                      próximo.

                                         Baseada em IA, Scholarcy é uma plataforma focada exclusivamente no
                                      resumo de material acadêmico. Ao fazer o upload de algum arquivo PDF, a

Figura 5 - Exemplo de interação com diferentes arquivos no MyReader




Fonte: captura de tela realizada pelos autores. Acesso em: 15 de set. 2023.
Sampaio et al.                                                                                                     9/24


                                     máquina “lê” todas as seções do texto, de modo similar ao feito por gerencia-
                                     dores de literatura. Além de coletar título, autores, ano de publicação, nome do
                                     periódico, resumo, palavras-chave e as referências finais, a plataforma usa IA
                                     para destacar e resumir trechos graças a ferramentas como Synopsis (uma
                                     espécie de resumo alternativo), Scholarcy highlights (trechos que a máquina
                                     considerou importantes, como se fossem grifos), Summary (o resumo do texto
                                     feito pela IA), comparative analysis (destaca trechos do artigo e sua compara-
                                     ção com outros artigos, incluindo o link dos mesmos para o Google Scholar),
                                     study subjects and analysis (em caso de estudos com pessoas, destaca o trecho
                                     que menciona a questão e ressalta a forma de análise buscando identificar a
                                     técnica de pesquisa). O sistema tenta retirar todas as tabelas e figuras do texto e
                                     apresenta automaticamente as referências finais que extraiu, tentando incluir
    7                                                                              7
      Trata-se de uma plataforma     links para o arXiV, Google Scholar e Scite . Várias dessas opções podem ser
    acadêmica dedicada a verificar
                                     exportadas pelo sistema.
    se determinado texto tem
    muito suporte ou se é
    fortemente rebatido.
                                         Também já percebemos um movimento de extensões de copiloto anexas
                                     aos navegadores. Para além do Copilot, várias extensões que fazem uso da API
                                     do ChatGPT ou outros modelos de LLMs permitem resumir uma página web
                                     ou um artigo acadêmico em formato aberto. Neste momento, o copiloto acadê-
                                     mico mais difundido parece ser o da SciSpace, que não só resume, mas explica
                                     trechos e busca textos acadêmicos similares. Tais ferramentas tendem a faci-
                                     litar de maneira substantiva a leitura de artigos.

                                         Um possível desenvolvimento positivo é a quebra de barreiras linguísticas,
                                     já que tais modelos grandes de linguagem foram, no geral, treinados em dife-
                                     rentes idiomas e as IAs apresentadas anteriormente podem gerar resultados
                                     (sumários, resumos e grafos) em uma língua diferente daquela em que o artigo
                                     foi escrito. Isso amplia o leque de idiomas disponíveis para o pesquisador,
                                     abrindo portas de bibliografias até então fechadas pela distância linguística, o
                                     que colabora para democratizar o conhecimento científico (Steigerwald et al.,
                                     2022). Para mais ferramentas de leitura, ver o anexo.



II.3. Análise de dados (e programação!)

                                         A onipresença de celulares e acesso a plataformas de redes sociais digitais
                                     tem gerado uma quantidade quase imensurável de todos os tipos de dados
                                     sobre indivíduos, governos, instituições, políticas públicas, empresas, associa-
                                     ções da sociedade civil, pesquisas acadêmicas etc. Especialmente na última
                                     década, presenciamos a emergência e a consolidação de práticas de raspagem e
                                     mineração de dados, analisados por cientistas de todas as áreas (Dalbello,
                                     2011; Poole, 2017). Nas áreas de sociologia e humanidades digitais temos
                                     vívidas discussões tanto teóricas, sobre essas novas formas de abordar e anali-
                                     sar os objetos, assim como sobre avanços constantes nas técnicas e ferra-
                                     mentas de pesquisa (Nascimento, 2020; Witte, 2012). Isso popularizou o uso
                                     de linguagens de programação, a exemplo de Python e R, habilidades cada vez
                                     mais desejáveis e valorizadas na academia, notadamente com a popularização
                                     da profissão de “cientista de dados”. Entretanto, tal cenário parece ter sido
                                     abalado pela emergência dos LLMs.

                                         Desde seu lançamento, o ChatGPT provou-se um grande auxiliar na elabo-
                                     ração e correção de códigos de programação de todas as naturezas. Hoje, exis-
                                     tem outras iniciativas, como o Github Copilot, que desde seu lançamento
                                     protagoniza histórias sobre perdas de postos de trabalho no setor. Mesmo que
                                     as IAs não sejam ainda tão eficientes para desenvolver sozinhas os códigos,
                                     aceleram consideravelmente o processo de correção. Parece-nos que o mesmo
10/24                                                                                Revista de Sociologia e Política v. 32


                                      ocorrerá na academia. De repente, a exigência de programação competente
                                      deve diminuir consideravelmente, e é provável que vejamos mais pesquisa-
                                      dores com alguma noção de programação usando IAs para redigir e revisar
                                      parte de seus códigos. Isso pode resultar em um efeito positivo, permitindo que
                                      maior número de pesquisadores acesse as possibilidades oferecidas por essas
                                      linguagens.

                                          As IAs já se mostram úteis também para a análise de dados. No
                                      ChatGPT-4, a ferramenta advanced data analysis (lançado como code inter-
                                      preter) acessa um servidor próprio baseado em Python e que permite auto-
                                      maticamente fazer diversos tipos de análise. A título de exemplo, um
                                      pesquisador pode fazer o upload de um banco de dados csv, e o ChatGPT
                                      irá concluir possíveis cruzamentos. No exemplo abaixo, baixamos a planilha
                                      de gastos dos deputados federais do portal de dados abertos da Câmara dos
                                      Deputados e subimos no advanced data analysis. Pedimos que fizesse uma
                                      somatória dos dados e respondesse quais os partidos com maior gasto no
                                      ano. Em seguida, pedimos que a ferramenta ponderasse isso pelo número de
                                      deputados, conforme o exemplo na Figura 6. O ChatGPT analisou os dados
                                      sozinho.

                                         Outros aplicativos de bastante repercussão foram o Rows, lançado no
                                      mercado como um Excel baseado em IA, e o Wolfram, especializado em
                                      operações matemáticas e estatísticas, capaz de gerar gráficos e outras repre-
                                      sentações visuais. Softwares acadêmicos para análises de dados em pesquisa

Figura 6 - Exemplo de uso do code interpreter do ChatGPT




Fonte: captura de tela realizada pelos autores. Acesso em: 17 de set. 2023.
Sampaio et al.                                                                                                 11/24

                                              8
    8
      Ver a pesquisa de Rottava &   qualitativa (por exemplo, Atlas.ti) e quantitativa (por exemplo, Tableau) já
    Da Silva (2023) que analisam    começam a incorporar IAs para auxiliar pesquisadores. Logo as IAs permi-
    as escolhas linguísticas na
    reescrita de textos por
                                    tirão “interagir” com esses dados, fornecendo dicas, vislumbres e caminhos
    aprendizes novatos em           para a análise, incluindo cruzamentos e testes estatísticos.
    contexto acadêmico e pela
    ferramenta ChatGPT.                 A ressalva aqui é, novamente, sobre o que parece ser uma perda qualitativa
                                    da pesquisa. O acaso e o oportuno, elementos comuns a empreitadas inte-
                                    lectuais, parecem ficar de lado quando terceirizamos as “análises” à máquina.
                                    Seria possível indagarmos: trata-se de “análise” ou apenas da correlação de
                                    dados em um padrão identificável pela máquina? A resposta a esta questão
                                    revela alguns limites do uso científico das IAs: elas são incapazes de reconhe-
                                    cer o que está fora do pensamento computacional (o que equivale a dizer que
                                    elas só são capazes de conhecer o que pode ser reduzido ao computacional) e,
                                    mais ainda, revelam como as habilidades analíticas humanas têm sido relega-
                                    das à mera instrumentalidade, facilmente substituída pelas máquinas. Para
                                    mais ferramentas de análise e de ajuda para programação, ver anexo.


II.4. Escrita acadêmica

                                        A capacidade de LLMs para escrever textos parecidos com humanos foi a
                                    questão mais abordada desde o lançamento do ChatGPT, motivando debates
                                    sobre autoria, plágio e limites éticos. Mas, para além da criação de textos, usos
                                    mais simples e com menos implicações éticas têm sido mencionados. Todos os
                                    modelos já citados fazem correções gramaticais, ortográficas e estruturais,
                                    além de avaliar e modificar o tom e a estrutura do texto, usando expressões da
                                    respectiva área acadêmica ou sugerindo melhorias em termos de coesão e
                                    coerência. Para elementos mais “simples” e estruturados de um texto, como
                                    título e resumo, parece-nos que a tendência de uso de tais ferramentas se tor-
                                    nará em pouco tempo a norma.
                                        Autores como Hartwell & Aull (2022) e Su et al. (2023) defendem o
                                    potencial de ferramentas de IA para auxiliar alunos e pesquisadores no enfren-
                                    tamento dos desafios dialógicos, estruturais e linguísticos da escrita argu-
                                    mentativa. Para os autores, as ferramentas de IA podem servir como um
                                    avaliador de redação que fornece feedback em relação a aspectos estruturais e
                                    linguísticos de ensaios argumentativos ou como um colega virtual que se
                                    envolve em conversas sobre o tópico de redação, soluciona problemas no pro-
                                    cesso de escrita e oferece dicas para fortalecer o aspecto dialógico da argu-
                                    mentação.
                                       Há quem aconselhe o uso das IAs para descrições detalhadas das seções de
                                    “procedimentos metodológicos” e “descrição dos resultados” de trabalhos
    9                                                                                               9
      O slogan da plataforma        científicos (Korinek, 2023). A plataforma Intellectus Statistics , por exemplo,
    inclusive é “estatística para
                                    roda os testes estatísticos de seu conjunto de dados e gera o texto descritivo
    não estatísticos”.
                                    dos resultados.

                                        Por meio de comandos específicos, é possível enriquecer o texto no que diz
                                    respeito a procedimentos experimentais, critérios de seleção de dados e razões
                                    para escolhas de abordagens. É provável que a IA forneça detalhes que permi-
                                    tam a outros pesquisadores compreender os passos seguidos e replicar os
                                    experimentos, bem como indicar aprimoramentos que não estejam evidentes
                                    no texto.

                                       Outra possibilidade é usar as IAs como ferramentas de teste de ideias.
                                    Além da possibilidade de naturalmente testar nos modelos conversacionais de
                                    LLMs, temos exemplos como do Research Kick, que permite fazer um
12/24                                                                                Revista de Sociologia e Política v. 32


                                      brainstorm de perguntas de pesquisa, e o Rytr, que apresenta a possibilidade
                                      de gerar diferentes palavras-chave para um artigo (acadêmico ou não).

                                          Não menos importante é o conceito de “copiloto”, que já abordamos acima
                                      e parece estar no cerne de todo o hype das plataformas e ferramentas de IA.
                                      Pela lógica da coprodução, as tecnologias de IA não iriam substituir os seres
                                      humanos, mas sim serem espécies de assistentes na pesquisa, especialmente na
                                      escrita acadêmica. Elas leriam o texto à medida que o autor escreve, fazendo
                                      sugestões ao vivo. E não apenas em um sentido similar ao já realizado por cor-
                                      retores, como o Grammarly, mas sim efetivamente reescrevendo, parafra-
                                      seando e até expandindo o texto. Vide o exemplo do SciSpace (Figura 7), que
                                      permite a criação de texto por IA em qualquer trecho do documento.

                                          Algumas IAs prometem copiar o estilo de escrita do autor, se devidamente
                                      alimentadas por material escrito anteriormente. Neste momento, tais copilotos
                                      já estão presentes no pacote Office, o que provavelmente naturalizará este uso
                                      na escrita acadêmica. Acreditamos que, assim como o corretor de celular teve
                                      impacto direto na forma como escrevemos e digitamos, tais ferramentas
                                      devem afetar significativamente o nosso modo de escrever - afinal, “nossa fer-
                                      ramenta de escrita trabalha juntamente com nosso pensamento” (Kittler, 2019,
                                      p. 278 - tradução nossa). Para mais ferramentas de escrita, ver Anexo.




II.5. Tradução

                                         Desde seu lançamento, algo que impressionou no ChatGPT foi a capaci-
                                      dade de interagir em muitos idiomas. Apesar de ser superior no inglês, essa e
                                      outras LLMs foram treinadas em bancos multilíngues, sendo capazes de ter
                                      boa performance nas línguas mais faladas do mundo. Seu treinamento mais
                                      amplo na língua inglesa tem chamado a atenção de pesquisadores ao redor do
                                      mundo interessados em traduzir seus idiomas nativos para o inglês ou corrigir
                                      escritos nesse idioma.

Figura 7 - Copiloto de escrita do SciSpace




Fonte: captura de tela realizada pelos autores. Acesso em 17 de set. 2023.
Sampaio et al.                                                                                           13/24


                                   Diferentemente do Google Tradutor e similares, as LLMs parecem ser
                               capazes de entregar expressões mais fidedignas, mais similares às nativas e
                               especialmente mais próximas do tom e estrutura de materiais acadêmicos.
                               Algo que certamente também foi facilitado pelo treinamento de tais modelos,
                               incluindo livros e artigos acadêmicos. Elas parecem ser mais capazes de captar
                               as nuances da língua e se aproximarem mais de uma frase que poderia ter sido
                               elaborada por um humano nativo da língua (Lyu et al., 2023).
                                   Para além disso, a tradução, como originalmente desenvolvida, realiza uma
                               cópia fidedigna do texto original em outra língua. Já as traduções feitas pelo
                               ChatGPT e outros recursos de IA não apenas reproduzem o conteúdo literal
                               contido no original, mas conseguem aprimorá-lo até o limite da solicitação do
                               usuário. Ou seja, podemos pedir a tradução de uma frase para determinada lín-
                               gua e, ao receber do artefato a tradução, solicitar que a tradução seja aprimo-
                               rada quantas vezes quisermos. Nesse sentido, tende-se a ter um texto mais bem
                               elaborado do que o conteúdo original traduzido literalmente; por outro lado,
                               um prompt mal elaborado também tende a gerar resultados inferiores (Lu
                               et al., 2023).

                                   Embora boa parte dos testes indique que não podemos simplesmente subs-
                               tituir tradutores tradicionais e mesmo humanos na tradução, já há indicativos
                               de que os LLMs serão cada vez mais usados nesta tarefa. Podemos, no limite,
                               pensar numa ciência multilíngue, já que diversas ferramentas fazem traduções
                               instantâneas e não haveria necessidade da publicação exclusivamente no
                               inglês nos periódicos de impacto. A tradução pode servir como solução de
                               curto e longo prazo para tornar a ciência mais resiliente, acessível, global-
                               mente representativa e com impacto para além da academia.



II.6. Apresentação dos dados

                                   Outra área que ganhou destaque nos últimos anos é a de visualização e
                               apresentação de dados. Com a proliferação de pacotes para Python e R para
                               incrementar a apresentação de resultados científicos e o uso de programas
                               como o Gephi e VOSViwer para apresentação de todos os tipos de redes (den-
                               tre tantas outras opções), houve avanço notável na visualização de informa-
                               ções, algo também incorporado ao jornalismo, notadamente aquele focado nos
                               dados, tendo o Nexo Jornal como exemplo no Brasil. Gráficos, tabelas e aná-
                               lises visuais “tradicionais” de programas acadêmicos tradicionais, como SPSS,
                               NVivo e Excel, têm sido substituídos por formas mais sofisticadas de visuali-
                               zação (Dalbello, 2011; Poole, 2017).

                                  Diante da demanda crescente, diversos plugins do ChatGPT e o próprio
                               code interpreter, além do supracitado Wolfram e outros, geram visualizações
                               automáticas dos dados, que podem ser ajustadas com poucos comandos no
                               formato ao qual estamos acostumados. Paralelamente, a pandemia de Covid-
                               19 acelerou drasticamente a necessidade de maior divulgação científica dos
                               resultados pelas universidades, incluindo uma melhor tradução de tais avanços
                               para as pessoas fora da área. Seja na apresentação dos dados, seja na criação de
                               apresentações acadêmicas para congressos ou divulgação científica, vivemos
                               um momento no qual o “publish or perish” vem sendo substituído por “com-
                               municate or perish”.

                                  Para além de facilitar a criação de figuras e representações gráficas para
                               materiais acadêmicos e possíveis apresentações, as IAs oferecem opções para
                               montar apresentações. A partir de um prompt simples com expressões ou
14/24                                                                                Revista de Sociologia e Política v. 32


                                      palavras-chave e algumas demandas, sites como Tome e Gamma criam uma
                                      apresentação do zero a partir do ChatGPT e de IAs generativas de imagens,
                                      como Midjourney e Stable Diffusion. E fazem tudo isso em questão de segun-
                                      dos (conforme Figura 8).

                                          A quebra de paradigma do próprio modo de ler, resumir e elaborar pesqui-
                                      sas está a nosso alcance. Em outras palavras, estamos falando de IAs selecio-
                                      nando, resumindo, apontando pontos principais, fazendo conexões com a
                                      literatura e respondendo perguntas dos pesquisadores, isso tudo como parte
                                      regular do processo da pesquisa acadêmica para os próximos anos. Essas fer-
                                      ramentas são lançadas com enorme frequência e tendem a ser naturalmente
                                      incorporadas no cotidiano acadêmico (para mais ferramentas de apresentação
                                      de dados, ver o Anexo). A seguir, questões que podem surgir de tais usos e
                                      naturalizações.




III. Consequências, riscos e paradoxos no uso de IAs para a pesquisa científica

                                          Embora sejam variados os usos das IAs generativas, elas podem trazer efe-
                                      tivos impactos sobre a educação e, como vamos discutir, a pesquisa acadê-
                                      mica. Vieses dos desenvolvedores e das bases de treinamentos, possibilidades
                                      de alucinação, falta de transparência de algoritmos, impossibilidade de repli-
                                      cação de certas respostas e outros critérios envolvidos em tais tecnologias são
                                      alguns dos problemas e riscos que precisam estar no radar. Apresentamos a
                                      seguir alguns desses riscos, que surgem em especial na utilização da IA gen-
                                      erativa no campo científico e no fazer acadêmico.




Figura 8 - Exemplo de apresentação sobre IA criada automaticamente no Gamma




Fonte: captura de tela realizada pelos autores. Acesso em 18 de set. 2023.
Sampaio et al.                                                                                      15/24


III.1. Autoria e plágio

                              A tendência é que as IAs façam parte da elaboração dos textos acadêmicos.
                          Será gradativamente mais difícil separar textos produzidos por humanos dos
                          elaborados por máquinas. Aqui se acumulam questões não resolvidas: um
                          texto escrito por um humano e revisado pela inteligência artificial deixa de ser
                          humano? Em outra possibilidade, se um humano cria boa parte de um texto,
                          entretanto pede à IA para complementar, infringe algum limite ético? Se pe-
                          dirmos que a IA leia um texto de nossa autoria e elabore o resumo ou o título,
                          ele será um texto da máquina, mesmo tendo em vista que o humano revisou
                          tudo e assinou como autor?

                              Diversas associações e editoras acadêmicas (por exemplo, Springer-Natu-
                          re, Elsevier e Taylor & Francis) postulam que o emprego dessas tecnologias
                          deve ser estritamente limitado ao aprimoramento textual e ao incremento da
                          legibilidade dos documentos, sob a condição de que haja supervisão, revisão e
                          edição por parte de seres humanos e deve-se mencioná-la em seção apropriada
                          do artigo (Rahman et al., 2023; Thorp, 2023). Portanto, argumenta-se que a
                          utilização de IA deve ser circunscrita a melhorar o conteúdo original, sem a
                          geração de novas ideias ou conceitos. Tais visões enfatizam que a IA não deve,
                          sob quaisquer circunstâncias, substituir funções essenciais da autoria,
                          incluindo a produção intelectual própria e a condução de pesquisas (Elsevier,
                          2023b).

                              Já outros autores (por exemplo, Boyd-Graber et al., 2023) consideram
                          aceitável o emprego de modelos generativos de IA para tarefas como agregar,
                          resumir, expandir e parafrasear textos, além de tratar questões mais ele-
                          mentares relacionadas ao conteúdo. Existem recomendações para o uso dessas
                          ferramentas em contextos mais controlados e estruturados, como na elabora-
                          ção de métodos e na descrição objetiva de resultados (Korinek, 2023), assim
                          como na geração ou aprimoramento de títulos, resumos e palavras-chave.
                          Contudo, essa aplicação ainda não é consensual. De qualquer forma, não é
                          recomendável o uso direto das saídas geradas pelas ferramentas de IA sem
                          revisão subsequente. (isto é, “copiar e colar”). Jarrah et al. (2023) afirmam
                          que, ao citar e atribuir a contribuição do ChatGPT no trabalho, prevenindo
                          plágio e mantendo os princípios de escrita acadêmica, os autores podem maxi-
                          mizar os benefícios da ferramenta, enquanto mantêm um uso responsável dela.
                          Todavia, até o momento, um dos poucos consensos é o de que modelos de IA
                          não estão em posição de ser considerados autores, pois não podem ser respon-
                          sabilizados pelo conteúdo produzido.

                              A irrupção da IA abala o cerne da produção intelectual, trazendo indaga-
                          ções a respeito de conceitos como autoria, colaboração e edição. Tal abalo
                          decorre do fato de as ferramentas executarem tarefas que vão além do limite
                          das consideradas “tarefas braçais”. Será a IA, afinal, a morte do autor? E, por
                          consequência, do editor? Tentamos neste ensaio refletir sobre isso. Mais que
                          falar de plágio ou “cola”, parece-nos que a discussão mais profícua será aquela
                          relacionada a autoria, direitos autorais, fontes e o limite da cooperação
                          humano-máquina (Møhl, 2020).

                              Destaca-se ainda que, no momento de conclusão deste ensaio, havia dúzias
                          de ferramentas de detecção de uso de IA em texto, porém nenhuma foi ava-
                          liada como efetiva (Sadasivan et al., 2023).
16/24                                                                             Revista de Sociologia e Política v. 32


III.2. Diminuição da integridade do fazer científico

                                      A falta de transparência sobre critérios e algoritmos usados pelas IAs pode
                                  levar a uma falta de compreensão sobre como as decisões são tomadas (Nat-
                                  ure, 2023). Por que a máquina recomendou a leitura de determinado texto em
                                  detrimento de outro? Por que recomendou um teste estatístico ou uma repre-
                                  sentação visual específica? ChatGPT e semelhantes podem ocasionalmente
                                  produzir respostas que, plausíveis à primeira vista, ao exame mais atento reve-
                                  lam-se descontextualizadas, factualmente incorretas ou consideravelmente
                                  distorcidas pelas inclinações do modelo (Susarla et al., 2023).

                                      A principal preocupação reside na atenção às possíveis distorções intro-
                                  duzidas pelo modelo e na verificação de erros ou imprecisões no conteúdo
                                  resultante. Isso significa que, mesmo em tarefas aparentemente simples como
                                  a revisão de um texto, o modelo pode adicionar informações novas ou omitir
                                  detalhes existentes. Como pouco ou nada sabemos sobre treinamentos das IAs,
                                  possíveis vieses não tratados e similares, o risco de inconsistência ou impreci-
                                  são, requerem uma abordagem crítica ao avaliar e utilizar as saídas desses
                                  modelos. Sublinhamos, assim, a importância da supervisão humana (humans
                                  in the loop/ humanos no ciclo) rigorosa e da revisão meticulosa para assegurar
                                  a qualidade e confiabilidade da escrita científica e a conscientização dos auto-
                                  res sobre a responsabilidade integral pelo conteúdo final (Sok & Heng, 2023).

                                      Reconhecemos que todas as tecnologias necessariamente apresentam
                                  vieses, escolhas, perspectivas e afins enquanto artefatos socioculturais huma-
                                  nos, nascendo inclusive de conflitos e resistências (Bijker & Law, 1992),
                                  entretanto nos parece que as IAs generativas apresentam particularidades
                                  importantes. Estamos falando de possíveis vieses em muitos pontos do pro-
                                  cesso. As empresas responsáveis por tais modelos argumentam que não podem
                                  tornar seus modelos transparentes pela competição no mercado, mas na prática
                                  há muitos elementos obscuros e questionáveis partindo desde os algoritmos e
                                  decisões ali envolvidas e passando especialmente pelos conjuntos de dados
                                  utilizados para o seu treinamento; logo, LLMs muitas vezes perpetuam vieses
                                  e estereótipos já existentes no material de treinamento.

                                      Em contraste com softwares acadêmicos, os quais frequentemente dis-
                                  ponibilizam versões estáveis e rastreáveis que são fundamentais para a pes-
                                  quisa científica, os modelos grandes de linguagem apresentam uma dinâmica
                                  distinta. Os LLMs são periodicamente atualizados, sem necessariamente pre-
                                  servar o acesso às suas versões anteriores. Tal prática impede a replicabilidade
                                  de estudos anteriormente realizados com versões obsoletas.

                                      Um exemplo ilustrativo dessa situação é a evolução do GPT-4, cuja meto-
                                  dologia de interpretação de código para leitura de arquivos, como PDFs sofreu
                                  alterações desde sua versão original. Neste início, era necessário fazer prompts
                                  mais precisos solicitando uma leitura geral do arquivo e os resultados eram
                                  melhores se acompanhados por pedidos do uso de bibliotecas do Python. Na
                                  atual versão, o GPT-4 já analisa o arquivo como um todo e responde melhor a
                                  linguagem natural sem a necessidade de indicar bibliotecas do Python.

                                      Essas modificações, embora observáveis em termos de resultados práticos,
                                  não são documentadas de maneira detalhada, limitando o entendimento pre-
                                  ciso de suas implicações. Por sua vez, softwares acadêmicos geralmente per-
                                  mitem o uso de diversas versões, inclusive as não mais atuais, facilitando a
                                  compreensão das mudanças implementadas e a replicação de pesquisas com
                                  parâmetros consistentes.
Sampaio et al.                                                                                              17/24


                                      São muitos pontos que estão fora do controle do pesquisador e que tornam
                                  tais tecnologias mais desafiadoras no uso científico. Isso dificulta a confiança
                                  nos resultados gerados pelas IAs e limita a capacidade do pesquisador de men-
                                  surar validade e confiabilidade desses resultados, tornando certos aspectos da
                                  pesquisa completamente não replicáveis.

                                      No momento, as principais recomendações são de explicitar o uso de tais
                                  instrumentos e as razões para utilizá-los, o que significa incluir o máximo de
                                  especificações sobre o nome e versão da ferramenta de IA (que em certos
                                  casos, como do ChatGPT, inclui a data da versão do modelo), data e horário da
                                  consulta. Idealmente, os autores devem incluir os prompts usados na interação,
                                  como anexos ao trabalho e os links do log (a conversa completa no chat) da
                                  interação com a IA.



III.3. Restrição do leque de possibilidades para a pesquisa

                                      A indicação de material de leitura numa pesquisa acadêmica vai mudar
                                  significativamente. No padrão estabelecido pelo Google, uma pesquisa resul-
                                  tava numa série de links para páginas; havia diversos critérios e problemas
                                  neste modelo, especialmente no ordenamento das primeiras páginas, mas era o
                                  paradigma. Indexadores acadêmicos funcionavam numa lógica similar, ten-
                                  dendo a priorizar resultados “mais relevantes” com base em questões como
                                  número e força das citações e impacto dos periódicos. Os dois paradigmas es-
                                  tão em plena mudança.

                                      Para além de prover links em uma busca usual e referências em uma busca
                                  acadêmica, os chatbots providenciam respostas ao questionamento original.
                                  Em vez de seguirmos os resultados de links da página principal, iremos nos
                                  aprofundar no tópico conversando com a IA. Isso provavelmente nos dará
                                  respostas mais rápidas e ágeis para perguntas específicas, porém diminuirá
                                  sensivelmente os debates em torno da questão pesquisada. A tendência é que a
                                  primeira resposta da máquina seja vista como a “verdade”, sem demonstrar os
                                  dissensos e debates envolvidos na questão.

                                      Da mesma forma, tendo em vista casos já relatados de reprodução, pelas
                                  IAs, das desigualdades existentes na formulação de políticas públicas datifica-
                                  das (O'Neil, 2021; Criado, 2021), pode-se considerar o risco de que os artefa-
                                  tos repliquem desigualdades no campo da produção de conhecimento
                                  científico. Tal situação tende a se agravar pelo fato de as IAs citadas neste
                                  texto se basearem especialmente em indexadores que priorizam a produção
                                  norte-americana, anglo-saxã e europeia. Isso pode reforçar visões específicas
                                  de ciência, determinados tipos de métodos e formas de análise, acentuando
                                  padrões já estabelecidos da pesquisa científica, com risco de impactar espe-
                                  cialmente as pesquisas das humanidades e a pesquisa qualitativa de maneira
                                  geral. Isso poderia resultar em mais citações para autores reconhecidos e
                                  menor inserção de novos pesquisadores, ou menor incidência de pesquisas
                                  inovadoras e emergentes (Susarla et al., 2023).
                                     A dependência excessiva das IAs para leitura, análise e redação de traba-
                                  lhos acadêmicos também traz o risco de prejudicar o desenvolvimento de
                                  habilidades críticas e criativas dos pesquisadores, especialmente estudantes
                                  universitários ou cientistas em início de carreira. Habib et al. (2024) analisam
                                  como o uso do ChatGPT-3.5 afetou a criatividade e originalidade de estu-
                                  dantes universitários para uma determinada tarefa. Por outro lado, a IA
                                  ampliou o escopo das ideias dos estudantes, oferecendo diferentes perspectivas
18/24                                                                         Revista de Sociologia e Política v. 32


                               e aumentando a diversidade de ideias. Também forneceu respostas mais deta-
                               lhadas e informativas. Contudo, essa vantagem deve ser considerada com cau-
                               tela devido ao potencial de gerar respostas “genéricas” ou “seguras”, com
                               preocupações de que a dependência excessiva na IA possa limitar, em vez de
                               expandir, o pensamento.

                                   Cabe ressaltar, todavia, que qualquer pesquisa passa pela aquisição e pelo
                               aprimoramento das habilidades de leitura, e textos “difíceis” fazem parte desse
                               processo. O processo de construção e desenvolvimento da maturidade intelec-
                               tual inclui a capacidade de elencar e concatenar ideias para a construção de
                               trabalhos acadêmicos.

                                   Nesse sentido, não é sem receio o temor de que estejamos entrando em
                               uma espécie de cultura de consumo “fast food” de textos científicos, com a lei-
                               tura terceirizada pela máquina de textos jamais lidos pelo pesquisador. A pri-
                               mazia dos dados, dos modelos e das formas automatizadas de “ler” pode levar
                               ao futuro desejado por Anderson (2008), no qual é delegada aos computadores
                               a capacidade de estabelecer relações sobre o mundo, sem a necessidade de
                               quadros de interpretação teórica (e, em última instância, sem a necessidade de
                               pensamento, apenas de computação). A esse contexto, Fazi (2020) chama de
                               (suposto) fim da teoria, resultado de uma hipervalorização dos dados e de uma
                               desvalorização do pensamento crítico e interpretativo proposto pelas ciências
                               humanas e sociais.



III.4. Paradoxo da produção de conhecimentos

                                   Ao longo dos séculos, diversas tecnologias geraram impactos de diferentes
                               naturezas no fazer científico. Em um exemplo simplório, a calculadora cientí-
                               fica, o computador pessoal, a world wide web, o Google, a Wikipedia, soft-
                               wares acadêmicos e tantos outros tiveram efeitos similares às IAs nas diversas
                               tarefas acadêmicas (vide a elaboração teórica de Kittler, 2019).

                                  Boa parte do que as IAs fazem é facilitar e acelerar tarefas, inclusive as
                               acadêmicas. Se havia forte tendência acadêmica de aumentar o aprendizado
                               em linguagens de programação, como R e Python, esse movimento tende a di-
                               minuir, já que o ChatGPT e outros artefatos podem gerar ou corrigir os códi-
                               gos de maneira mais fácil e rápida. Dominar os prompts de pesquisa das IAs
                               poderá ser mais importante que aprender a programação em si. O mesmo vale
                               para outras técnicas e softwares de pesquisa, além de teorias acadêmicas.

                                   Ainda assim, podemos facilmente imaginar futuros pesquisadores que vão
                               “ler” dezenas de artigos simultaneamente; elaborar “revisões de literatura”
                               automatizadas e substantivas; raspar, limpar e analisar quantidades massivas
                               de dados; usar tais modelos e tecnologias para testar os limites do conheci-
                               mento humano e, quem sabe, até alcançar resultados mais substantivos e
                               mesmo inovadores, ou seja, nos termos de Ito (2016), teremos cada vez mais
                               uma “inteligência estendida”, que não está nos indivíduos ou nas máquinas,
                               mas distribuída entre eles. Para o autor, não faz sentido a afirmação de que as
                               IAs irão tomar os lugares dos humanos, sendo mais provável que esta tecnolo-
                               gia (assim como outras que a antecederam) amplie a capacidade humana de
                               realizar tarefas complexas. O paradoxo que a tecnologia apresenta para a pes-
                               quisa acadêmica e que a inteligência artificial tende a aumentar de forma sig-
                               nificativa é que a ampliação da capacidade cognitiva por essas ferramentas
                               (McLuhan, 2001) possivelmente será capaz de gerar resultados mais substan-
                               tivos para a ciência.
Sampaio et al.                                                                                         19/24


                               Paradoxalmente, passaremos a ter estudantes e pesquisadores com menos
                           domínio de questões que julgamos, até hoje, importantes, como compreensão
                           aprofundada da literatura acadêmica, incluindo teorias, conceitos e discussões,
                           assim como menor conhecimento detalhado das técnicas de pesquisa. Em
                           suma, teremos pesquisadores “menos treinados”, “menos habilitados”, e que
                           ainda assim poderão realizar tarefas mais rápidas e significativas.

                               Outro paradoxo é o fato de os modelos de IA só reproduzirem conheci-
                           mentos já disponíveis. Logo, não é que o ChatGPT gere scripts de códigos, ele
                           na verdade foi treinado pelos scripts já gerados pelo mundo. Ele não cria textos
                           originais; apenas analisa tudo que já foi produzido pela humanidade e o rear-
                           ranja numa ordem que faça sentido em lógica exclusivamente estatística. Entra
                           em questão o próprio conceito de criatividade, essencial para o desenvolvi-
                           mento científico. Se, de uma ponta, as IAs tornam mais acessíveis ferramentas
                           e opções para quem que não domina linguagens de programação, de outra,
                           concentram ainda mais o poder de decisão entre empresas e indivíduos que
                           realmente controlam essa nova forma de produzir conhecimento.

                               Finalmente, as facilidades trazidas pelas IAs generativas podem facilmente
                           ser transformadas em uma gigantesca quantidade de lixo acadêmico. Estamos
                           sujeitos a presenciar, nos próximos anos, uma maré ainda superior de textos
                           científicos mal escritos, sem novidades, critérios nem rigor, buscando ali-
                           mentar apenas revistas predatórias e currículos de estudantes e professores em
                           busca de bolsas e financiamento (Kendall & Silva, 2023).



IV. Considerações finais

                               Na primeira seção deste artigo, nos empenhamos em descrever as possibi-
                           lidades de utilização de IA em diferentes etapas da pesquisa científica, sendo
                           estes: a) na busca e seleção de literatura acadêmica; b) na leitura de artigos; c)
                           na análise de dados e na programação; d) na escrita acadêmica; e) na tradução
                           e f) na visualização dos dados. Na segunda seção do artigo, sistematizamos e
                           discutimos algumas consequências possíveis da adoção de ferramentas base-
                           adas em IA na pesquisa acadêmica, partindo de fenômenos já mapeados no
                           contexto da utilização de IA em outros setores, ou de questões pré-existentes
                           no contexto acadêmico, que podem vir a ser exacerbadas. O objetivo do artigo
                           é, nesse sentido, contribuir para o debate e o pensamento reflexivo em torno do
                           tema, de forma individual e coletiva.

                               Devido a sua natureza ensaística, tendo como base a apresentação e análise
                           de ferramentas de IA para uso acadêmico e uma revisão narrativa da literatura,
                           este artigo apresenta limitações. Ainda que possa indicar possíveis questões e
                           efeitos da adoção destes sistemas, não é possível verificar, nesse momento,
                           como efetivamente será a sua adoção no campo científico. Pesquisas futuras
                           que visem contribuir com a temática podem focar na forma como a IA está
                           sendo integrada às práticas acadêmicas, em diferentes áreas do conhecimento,
                           e na percepção dos cientistas e das instituições sobre estes usos.
                               O debate informado em torno do tema se faz necessário do ponto de vista
                           coletivo. Apenas negar ou proibir ferramentas de IA não colocará o Brasil em
                           posição de liderança quanto à nova tecnologia nem nos permitirá um debate
                           sério sobre regulação de inteligência artificial, algoritmos e plataformas digi-
                           tais no futuro próximo. Em 2023, já temos um modelo grande de linguagem
                           (LLM) brasileiro, baseado no Llama e ajustado para o português, para casos e
                           especificidades do país. Portanto, é plenamente possível imaginarmos a
20/24                                                                                   Revista de Sociologia e Política v. 32


                                    elaboração de modelos, chatbots, aplicativos e outras IAs pensadas para as
                                    necessidades acadêmicas e que tenham nossas especificidades em vista.

                                        Diante desse quadro, é fundamental que governos e instituições acadêmi-
                                    cas estabeleçam políticas e diretrizes claras para o uso de IAs com o intuito de
                                    garantir qualidade na pesquisa acadêmica. Isso inclui a definição de padrões
                                    éticos e responsáveis, a exigência de transparência nas decisões tomadas pelas
                                    IAs e a promoção de colaboração internacional para desenvolver soluções
                                    mais inclusivas e adaptáveis às diversas realidades acadêmicas, notadamente
                                    do Sul Global. Conforme Filgueiras & Junquilho (2023), o Brasil hoje vive
                                    praticamente um vácuo de regulação, uma vez que a Estratégia Brasileira de
                                    Inteligência Artificial falha em estabelecer definições e principalmente fun-
                                    ções importantes aos órgãos públicos brasileiros e envolver efetivamente os
                                    outros atores interessados na questão. O que não significa que o país, por seu
                                    tamanho, recursos e relevância geopolítica, não possa ser protagonista tanto na
                                    questão da regulação quanto no desenvolvimento de tais tecnologias.

                                        A exemplo do ChatGPT e outros chatbots, a saída é aprofundar o debate.
                                    Periódicos de alto impacto, como Nature (Nature, 2023; Van Dis et al., 2023),
                                    Science (Thorp 2023) e The Lancet (The Lancet Digital Health, 2023), já ini-
                                    ciaram a discussão. Devemos fazer o mesmo, mas mirando nossas especifici-
                                    dades e necessidades. Pesquisadores de AI da América Latina levantaram
                                    pontos iniciais interessantes para o nosso contexto, apesar das dificuldades de
                                    regulação apresentadas por Filgueiras (2023) e algumas reflexões oferecidas
                                    pelo professor Lemos (2023).
                                       Durante a escrita deste texto, o Brasil discutia regulação sobre as plata-
                                    formas digitais e sobre fake news. Parece-nos uma oportunidade para incluir
                                    no mesmo bojo a regulação de IAs. Inclusive porque ela já aconteceu de forma
                                    equivocada (Filgueiras & Junquilho, 2023). Dezoito meses depois do lança-
                                    mento do ChatGPT, procuramos, para finalizar este texto, referências de boas
                                    práticas pelos principais órgãos que regulam e fomentam a pesquisa no Brasil,
                                    nomeadamente Capes, MEC e CNPq. Em vão. Ainda não há diretrizes sobre
                                    como usar (ou não) ChatGPT e outros artefatos de inteligência artificial na
                                    pesquisa acadêmica.




Declaração

                                        Nenhuma outra passagem deste artigo foi escrita com auxílio do ChatGPT
                                    ou de outras ferramentas de IA. Alguns trechos foram refinados por IA, a
                                    exemplo do resumo e do abstract, com uso de Claude 3, Deepl, Quillbot e
                                    ChatGPT 4. Após o uso destas ferramentas, os autores revisaram e editaram o
                                    conteúdo em conformidade com o método científico e assumem total respons-
                                    abilidade pelo conteúdo da publicação.

Rafael Cardoso Sampaio (cardososampaio@gmail.com) é professor do Departamento de Ciência Política e do Programa de
Pós-Graduação em Ciência Política da Universidade Federal do Paraná.

Maria Alejandra Nicolás (alejandranicolas@gmail.com) é professora da área de Administração Pública e Políticas Públicas e
do Mestrado em Políticas Públicas e Desenvolvimento da UNILA.

Tainá Aguiar Junquilho (taina.junquilho@idp.edu.br) é professora no programa de Direito do Instituto de Direito Brasileiro
de Ensino Pesquisa e Desenvolvimento (IDP).
Sampaio et al.                                                                                                             21/24


Luiz Lopes (luizlopescomunicacao@gmail.com) é professor do Programa de Pós-graduação em Gestão da Informação da
Universidade Federal do Paraná.

Christiana Soares de Freitas (freitas.christiana@gmail.com) é professora do Departamento de Políticas Públicas e do Pro-
grama de Pós-Graduação em Comunicação da Universidade de Brasília.

Marcio Telles (marcio.telles@utp.br) é professor permanente do Programa de Pós-Graduação em Comunicação e Linguagens
e do bacharelado em Jornalismo da Universidade Tuiuti do Paraná.

João Senna Teixeira (sennateixeira@gmail.com) é pesquisador pós-doc no Instituto Nacional de Ciência e Tecnologia em
Democracia Digital (INCT.DD) na Universidade Federal da Bahia.

Fernanda da Escóssia (fernandadaescossia@gmail.com) é jornalista, professora da UERJ e autora de “Invisíveis: uma etno-
grafia sobre brasileiros sem documento”.

Luiza Carolina dos Santos (luizacdsantos@gmail.com) é pós-doutoranda no Programa de Pós-Graduação em Comunicação e
Linguagens da Universidade Tuiuti do Paraná.



Referências
Achiam, J., Adler, S., Agarwal, S., Ahmad, L., Akkaya, I., et al. (2023) Gpt-4 technical report. arXiv preprint
      arXiv:2303.08774.
Alexopoulos, C., Saxena, S., Loukis, E.N., Rizun, N., Ioanna Maratsi, M., et al. (2023) ChatGPT application vis-a-vis open
      government data (OGD): a research agenda. SSRN Electronic Journal. DOI
Alkaissi, H. & McFarlane, S. (2023) Artificial hallucinations in ChatGPT: implications in scientific writing. Cureus, 15(2),
      e35179. DOI
Almeida, V., Mendonça, R. & Filgueiras, F. (2023) ChatGPT: tecnologia, limitações e impactos. [online] Ciência Hoje
      (CH396). Disponível em: https://cienciahoje.org.br/artigo/chatgpt-tecnologia-limitacoes-e-impactos/. Acesso em: 26 de
      abr. 2024.
Anderson, C. (2008) The end of theory: the data deluge makes the scientific method obsolete. Wired Magazine, 23 de junho
      de 2008. Disponível em: https://www.wired.com/2008/06/pb-theory/. Acesso em: 27 de abr. de 2024.
Bernard, E. (2023) What are large language models? The AIedge Newsletter, 5 de jun. Disponível em: https://newsletter.
      theaiedge.io/p/what-are-large-language-models. Acesso em: 24 de fev. 2024.
Bijker, W. & Law, J. (1992) Shaping technology/building society. Cambridge: MIT Press.
Boyd-Graber, J., Okazaki, N. & Rogers, A. (2023) ACL 2023 policy on AI writing assistance, 2023. In: Association for
      Computational Linguistics - ACL 2023 Program Chairs. Toronto. Disponível em: https://2023.aclweb.org/blog/ACL-
      2023-policy. Acesso em: 2 de dez. 2023.
Brown, T., Mann, B., Ryder, N., Subbiah, M., Kaplan, J., et al. (2020) Language models are few-shot learners. In: 34th Con-
      ference on Neural Information Processing Systems. Vancouver. Disponível em: https://proceedings.neurips.cc/paper_
      files/paper/2020/file/1457c0d6bfcb4967418bfb8ac142f64a-Paper.pdf. Acesso em: 26 de abr. 2024.
Cotton, D.R.E., Cotton, P.A. & Shipway, J.R. (2023) Chatting and cheating: ensuring academic integrity in the era of
      ChatGPT. Innovations in Education and Teaching International, 61(2), pp. 228-239. DOI
Criado, J.I. (2021) Inteligencia artificial: madurez tecnológica, adopción e innovaciones en la gestión pública. In: Inteligencia
      artificial y ética en la gestión pública. Caracas, Centro Latinoamericano de Administración para el Desarrollo.
Dalbello, M. (2011). A genealogy of digital humanities. Journal of Documentation, 67(3), pp. 480-506. DOI
Dwivedi, Y.K., Kshetri, N., Hughes, L., Slade, E.L., Jeyaraj, A., et al. (2023) ‘So what if ChatGPT wrote it?' Multi-
      disciplinary perspectives on opportunities, challenges and implications of generative conversational AI for research,
      practice and policy. International Journal of Information Management, 71(0268-4012), p. 102642. Disponível em:
      https://www.sciencedirect.com/science/article/pii/S0268401223000233#bib211. Acesso em: 26 de abr. 2024.
Elsevier. (2023) The use of generative AI and AI-assisted technologies in writing for Elsevier. Disponível em: https://www.
      elsevier.com/about/policies-and-standards/the-use-of-generative-ai-and-ai-assisted-technologies-in-writing-for-else
      vier. Acesso em: 12 de abr. 2024.
Fazi, M. (2020) O fim da teoria da mídia. Intexto, 49, pp. 305-18. DOI
Filgueiras, F. (2023) Designing artificial intelligence policy: comparing design spaces in Latin America. Latin American
      Policy, 14(1), pp. 5-21. DOI
Filgueiras, F. & Junquilho, T. (2023) The Brazilian (non)perspective on national strategy for artificial intelligence. Discover
      Artificial Intelligence, 3, 7. DOI
Habib, S., Voguel, T., Xiao, A., X. & Thorne, E. (2024) How does generative artificial intelligence impact student creativity?
      Journal of Creativity, 34(1), p. 100072. DOI
22/24                                                                                        Revista de Sociologia e Política v. 32


Hacker, P., Engel, A. & Mauer, M. (2023) Regulating ChatGPT and other large generative AI models. arXiv:2302.02337
       [cs]. Disponível em: https://arxiv.org/abs/2302.02337. Acesso em: 26 de abr. 2024.
Hartwell, K. & Aull, L. (2022) Constructs of argumentative writing in assessment tools. Assessing Writin, 54, pp. 1-3. DOI
Ito, J. (2016) Extended intelligence, 11 de fev. Joi Ito's PubPub. Disponível em: https://pubpub.ito.com/pub/extended-intelli
       gence/release/1. Acesso em: 27 de abr. 2024. DOI
Jarrah, A.M., Wardat, Y. & Fidalgo, P. (2023) Using ChatGPT in academic writing is (not) a form of plagiarism: what does
       the literature say? Online Journal of Communication and Media Technologies, 13(4), p. e202346-e202346. DOI
Jung, A. (2022) Machine learning: the basics. Singapore: Springer.
Kendall, G. & Silva, J. (2023) Risks of abuse of large language models, like ChatGPT, in scientific publishing: Authorship,
       predatory publishing, and paper mills. Learned Publishing, 37(1), pp. 55-62. DOI
Kittler, F. (2019) Gramofone, filme, typewriter. Belo Horizonte: Editora UFMG; Rio de Janeiro: Ed. UERJ.
Korinek, A. (2023) Language models and cognitive automation for economic research. National Bureau of Economic
       Research, 61(4), pp. 1281-1317. DOI
Lu, Q., Qiu, B., Ding, L., Xie, L. & Tao, D. (2023) Error analysis prompting enables human-like translation evaluation in
       large language models: A case study on ChatGPT. arXiv:2303.13809 [cs.CL]. DOI
Lyu, C., Xu, J. & Wang, L. (2023) New Trends in machine translation using large language models: caseeexamples with
       ChatGPT. arXiv:2305.01181 [cs.CL]. DOI
Mcluhan, M. (2001) Understanding media. Oxon: Routledge.
Miao, F. & Holmes, W. (2020) International Forum on AI and the futures of education, developing competencies for the AI
       Era: synthesis report. In: International Forum on AI and the Futures of Education - Unesco. Beijing. Disponível em:
       https://unesdoc.unesco.org/ark:/48223/pf0000377251. Acesso em: 30 de abr. 2024.
Møhl, P. (2020) Seeing threats, sensing flesh: human-machine ensembles at work. AI & SOCIETY, 36, pp.1243-1252. DOI
Nascimento, L. (2020) Sociologia digital. Salvador: EDUFBA.
Nature (2023) Tools such as ChatGPT threaten transparent science; here are our ground rules for their use. Nature, 613
       (7945), pp. 612-612. DOI
O'Neil, C. (2021) Algoritmos de destruição em massa. Cotia: Editora Rua do Sabão.
Orduña-Malea, E. & Cabezas-Clavijo, Á. (2023) ChatGPT and the potential growing of ghost bibliographic references. Sci-
       entometrics, 128(9), pp. 5351-5355. DOI
Poole, A.H. (2017) The conceptual ecology of digital humanities. Journal of Documentation, 73(1), pp. 91-122. DOI
Rahman, M., Terano, H.J.R., Rahman, N., Salamzadeh, A. & Rahaman, S. (2023) ChatGPT and academic research: a review
       and recommendations based on practical examples. Journal of Education, Management and Development Studies, 3(1),
       pp. 1-12. DOI
Ramos, A.S.M. (2023) Generative artificial intelligence based on large language models - tools for use in academic research.
       SciELO Preprints [Preprint]. DOI
Rodríguez, E.I., Zaballos, A.G., Gabarró, P.P. & Benzaqué, I. (2020) Inteligencia artificial: la gran oportunidad del siglo
       XXI: documento de reflexión y propuesta de actuación. Monografia do Banco Interamericano de Desarrollo, 904. DOI
       Disponível em: https://unesdoc.unesco.org/ark:/48223/pf0000377251.
Rottava, L. & Silva, M.A. (2023) Sistema lógico-semântico de expansão na reescrita de textos acadêmicos: escolhas linguís-
       ticas de uma estudante versus as escolhas do ChatGPT. Diálogo das Letras, (12), pp. e02307-e02307. DOI
Sadasivan, V.S., Kumar, A., Balasubramanian, S., Wang, W. & Feizi, S. (2023) Can AI-generated text be reliably detected?
       arXiv:2303.11156v3 [cs.CL]. DOI
Santos, L. (2022) Inteligência artificial conversacional e o paradigma simulativo: pistas antropomórficas nas assistentes digi-
       tais. In: 31o Encontro Anual da Compós. Imperatriz.
Sok, S. & Heng, K. (2023) ChatGPT for education and research: a review of benefits and risks. SSRN Electronic Journal.
       DOI
Steigerwald, E., Ramírez-Castañeda, V., Brandt, D.Y.C., Báldi, A., Shapiro, J.T., et al. (2022) Overcoming language barriers
       in academia: machine translation tools and a vision for a multilingual future. BioScience, 72(10), pp. 988-998. DOI
Su, Y., Lin, Y. & Lai, C. (2023) Collaborating with ChatGPT in argumentative writing classrooms. Assessing Writing, 57, pp.
       100752-100752. DOI
Susarla, A., Gopal, R., Thatcher, J.B. & Sarker, S. (2023) The janus effect of generative AI: charting the path for responsible
       conduct of scholarly activities in information systems. Information Systems Research, 34(2), pp. 399-408. DOI
The Lancet Digital Health (2023) ChatGPT: friend or foe? The Lancet Digital Health, 5(3), p. e102. DOI
Thorp, H.H. (2023) ChatGPT is fun, but not an author. Science, 379(6630), pp. 313-313. DOI
UNESCO (2019) Beijing consensus on artificial intelligence and education. In: International Conference on Artificial Intelli-
       gence and Education, Planning Education in the AI Era: Lead the Leap. Beijing. Disponível em: https://unesdoc.
       unesco.org/ark:/48223/pf0000368303. Acesso em: 30 de abr. 2024.
Van Dis, E.A.M., Bollen, J., Zuidema, W., van Rooij, R. & Bockting, C.L. (2023) ChatGPT: five priorities for research. Nat-
       ure, 614(7947), pp. 224-226. DOI
Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., , et al. (2017) Attention is all you need. In: 31st Conference on
       Neural Information Processing Systems. Long Beach.
Witte, J. (2012) A Ciência Social digitalizada: avanços, oportunidades e desafios. Sociologias, 14(31), pp. 52-92. DOI
Sampaio et al.                                                                                                          23/24


Outras fontes
ChatGPT. Modelo grande de linguagem. Disponível em: https://chat.openai.com/. Acesso em: 19 de jan. 2024.
ChatGPT Advanced data analysis: explained. EnterpriseDNA. Disponível em: https://blog.enterprisedna.co/chatgpt-
      advanced-data-analysis-explained/. Acesso em: 7 de mar. 2024.
ChatPDF. Leitor de PDF com auxílio de inteligência artificial. Disponível em: https://www.chatpdf.com Acesso em: 19 de
      ago. 2023.
Claude. Modelo grande de linguagem. Disponível em: https://claude.ai/. Acesso em: 19 de jan. 2024.
Code Interpreter, novo recurso do ChatGPT, é um cientista de dados eficaz, afirma professor da Wharton School. Época
      Negócios. 10 de jul. 2023. Disponível em: https://epocanegocios.globo.com/tecnologia/noticia/2023/07/code-inter
      preter-novo-recurso-do-chatgpt-e-um-cientista-de-dados-eficaz-afirma-professor-da-wharton-school.ghtml. Acesso em:
      19 de ago. 2023.
Connected Papers. Buscador acadêmico. Disponível em: https://www.connectedpapers.com. Acesso em: 19 de ago. 2023.
Consensus. Buscador acadêmico. Disponível em: https://www.consensus.app/. Acesso em: 19 de ago. 2023.
Declaración de Montevideo sobre Inteligencia Artificial y su impacto en América Latina. Fundación Sadosky. 10 de mar. de
      2023. Disponível em: https://fundacionsadosky.org.ar/declaracion-de-montevideo-fun/. Acesso em: 19 de ago. 2023.
Elicit. Plataforma acadêmica digital. Disponível em: https://elicit.org/. Acesso em: 19 de ago. 2023.
Gamma. Plataforma para criação de apresentações. Disponível em: https://gamma.app. Acesso em: 20 de ago. 2023.
Gemini. Modelo grande de linguagem. Disponível em: https://gemini.google.com/. Acesso em: 19 de jan. 2024.
Gephi. Software para análise de redes. Disponível em: https://gephi.org/. Acesso em: 20 de ago. 2023.
Github Copilot. Ajudante de inteligência artificial para programação. Disponível em: https://github.com/features/copilot.
      Acesso em: 19 de ago. 2023.
Grammarly. Plataforma para revisão da língua inglesa. Disponível em: https://www.grammarly.com/. Acesso em: 20 de ago.
      2023.
Humata. Leitor de PDF com auxílio de inteligência artificial. Disponível em: https://app.humata.ai/. Acesso em: 19 de ago.
      2023.
Inciteful. Buscador acadêmico. Disponível em: https://inciteful.xyz/. Acesso em 19 de ago. 2023.
Intellectus Statistics. Plataforma para análise de dados. Disponível em: https://www.intellectusstatistics.com/. Acesso em: 20
      ago. 2023.
Introducing: AI Coding Beta powered by OpenAI. Atlasti. Disponível em: https://atlasti.com/ai-coding-powered-by-openai.
      Acesso em: 20 de ago. 2023.
Lemos, A. (2023) Sugestões sobre a IA na AL. André's Newsletter, 21 de mar. Disponível em: https://andrelemos.substack.
      com/p/sugestoes-sobre-a-ia-na-al. Acesso em 19 ago. 2023.
Litmaps. Buscador acadêmico. Disponível em: https://app.litmaps.com/seed. Acesso em: 19 de ago. 2023.
Llama. Modelo grande de linguagem. Disponível em: https://ai.meta.com/llama/. Acesso em: 19 de jan. 2024.
Maritaca. Modelo grande de linguagem. Disponível em: https://www.maritaca.ai/. Acesso em: 19 de jan. 2024.
Midjourney. Modelo de inteligência artificial para geração de imagens. Disponível em: https://www.midjourney.com/.
      Acesso em: 19 de jan. 2024.
My Reader. Leitor de PDF com auxílio de inteligência artificial. Disponível em: https://www.myreader.ai/. Acesso em: 19 de
      ago. 2023.
OpenAI's CEO says the age of giant AI models is already over (2023) Wired, 17 de abr. Disponível em: https://www.wired.
      com/story/openai-ceo-sam-altman-the-age-of-giant-ai-models-is-already-over/. Acesso em: 24 de fev. 2024.
O que norteia as propostas de regular a inteligência artificial. Nexo, 18 de jun. 2023. Disponível em: https://www.nexojornal.
      com.br/expresso/2023/06/18/O-que-norteia-as-propostas-de-regular-a-intelig%C3%AAncia-artificial. Acesso em: 19
      de ago. 2023.
Perplexity. Buscador online. Disponível em: https://www.perplexity.ai/. Acesso em: 26 de jan. 2024.
Quillbot. Plataforma de escrita acadêmica. Disponível em: https://quillbot.com/. Acesso em: 20 de ago. 2023.
Research Kick. Disponível em: https://www.researchkick.com/ Acesso em: 7 de mar. 2024.
Research Rabbit. Buscador acadêmico. Disponível em: https://www.researchrabbit.ai. Acesso em: 19 de ago. 2023.
Resoomer. Leitor de PDF com auxílio de inteligência artificial. Disponível em: https://resoomer.com/pt/. Acesso em: 20 de
      fev. 2024.
Rows. Plataforma para análise de dados. Disponível em: https://rows.com/. Acesso em: 20 de ago. 2023.
Rytr. Plataforma de escrita acadêmica. Disponível em: https://app.rytr.me/create. Acesso em: 20 de ago. 2023.
Salesforce Introduces the next generation of Tableau, bringing generative AI for data and analytics to everyone. Salesforce, 9
      de mai. de 2023. Disponível em: https://www.salesforce.com/news/stories/tableau-einstein-gpt-user-insights/. Acesso
      em: 20 de ago. 2023.
Scholarcy. Plataforma acadêmica digital. Disponível em: https://www.scholarcy.com/. Acesso em: 20 de fev. 2024.
SciSpace. Extensão para Chrome. Disponível em: https://chrome.google.com/webstore/detail/scispace-copilot/cipccbpjpemc
      nijhjcdjmkjhmhniiick. Acesso em: 19 de ago. 2023.
SciSpace. Plataforma acadêmica digital. Disponível em: https://typeset.io/. Acesso em: 26 de jan. 2024.
Scite. Plataforma acadêmica digital. Disponível em: https://scite.ai/. Acesso em: 20 de fev. 2024.
24/24                                                                                             Revista de Sociologia e Política v. 32


Stable Diffusion. Modelo de inteligência artificial para geração de imagens. Disponível em: https://stability.ai. Acesso em: 19
     de jan. 2024.
Tome. Plataforma para criação de apresentações. Disponível em: https://tome.app/. Acesso em: 20 de ago. 2023.
VOSViewer. Software para análise de redes acadêmica. Disponível em: https://www.vosviewer.com/. Acesso em: 20 de ago.
     2023.
Wolfram Alpha. Plataforma para análise de dados. Disponível em: https://www.wolframalpha.com/. Acesso em: 20 de ago.
     2023.



ChatGPT and other artificial intelligences will transform scientific research: reflections on their uses

Keywords: ChatGPT, generative artificial intelligence, machine learning, scientific research, literature review.

ABSTRACT Introduction: The emergence of sophisticated language models such as ChatGPT has far-reaching implications across
numerous fields, including academia. This article explores the potential impact of ChatGPT and other artificial intelligences (AIs) on
academic research, particularly in tasks such as literature review, data analysis and presentation, and text composition and transla-
tion. Materials and methods: We conducted an extensive narrative review of the scientific literature, followed by an evaluation of
various academic AI tools available as of 2023. Results: We discuss the potential consequences, risks, and paradoxes associated
with integrating AIs into research practices, such as dilemmas concerning authorship, research integrity, methodological limitations,
and shifts in the dynamics of knowledge production. Discussion: We conclude by calling for an in-depth debate on public policies
focused on regulating and developing technologies adapted to the distinct research needs in the Global South.




This is an Open Access article distributed under the terms of the Creative Commons Attribution License, which permits unrestricted use,
distribution, and reproduction in any medium, provided the original work is properly cited.


Anexo

Dado o cenário tecnológico atual, muitas empresas estão surgindo ou mesmo deixando de existir em um curto espaço de
     tempo. Provavelmente, em alguns anos, várias ferramentas citadas no artigo não estarão mais presentes. Com isso em
     vista, optamos por fazer um anexo online na plataforma Open Science Network, que poderá então ser atualizado com
     maior frequência e refletir melhor o cenário de tais tecnologias ao longo do tempo.
Os anexos digitais estão disponíveis em: https://osf.io/6dpfn/. Acesso em: 28 de abr. de 2024.
