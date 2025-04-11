## 🏁 Sobre o repositório `corrida_inscritos`

Este repositório reúne notebooks utilizados como apoio na organização e automação das corridas transmitidas no meu canal do YouTube, com foco em jogos da franquia Fórmula 1.

### 🏎️ Destaque: `Corrida dos Inscritos.ipynb`

Este notebook é responsável por processar um arquivo Excel de entrada, onde cada linha representa a posição final dos 10 primeiros colocados em cada etapa da competição, e as colunas representam as diferentes etapas.

Com base nesses dados, o notebook realiza as seguintes tarefas:

- Geração de um `DataFrame` com a pontuação atualizada dos pilotos, separando **Corrida dos Inscritos** e **Corrida dos Membros**;
- Criação de páginas HTML com os resultados, utilizadas para upload no site oficial (atualmente fora do ar);
- Cálculo da pontuação mensal dos **membros apoiadores** do canal, que concorrem a uma premiação exclusiva mensal.

### 💳 Destaque: `Credito Membros.ipynb`

Este notebook recebe dois arquivos `.csv` extraídos diretamente do YouTube, contendo a listagem de membros apoiadores em duas datas distintas. A partir desses dados, ele:

- Identifica **novos apoiadores** e **quem deixou de apoiar** o canal no período analisado;
- Gera um relatório `.txt` com os membros ativos, organizados por categoria de apoio:
  - Membros Premium
  - Membros Normais
  - Membros Lite+
  - Membros Lite
- Utiliza bibliotecas como **Pandas** para tratamento dos dados e geração dos relatórios.

---

### 🎯 Tecnologias e habilidades demonstradas

- Manipulação avançada de dados com **Pandas** e **DataFrames**  
- Geração de conteúdo automatizado em **HTML** e **TXT**  
- Processamento de arquivos `.xlsx` e `.csv`  
- Automação de tarefas repetitivas para gestão de comunidade  
- Organização de lógica para rankings e pontuação com base em regras definidas

---

Este projeto alia programação com a organização de eventos online em jogos de Fórmula 1, demonstrando versatilidade no uso de Python para soluções criativas e funcionais.
