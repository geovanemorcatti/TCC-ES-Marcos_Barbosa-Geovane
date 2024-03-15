### Referência completa do artigo:
"Automatic Detection of Performance Bugs in Database Systems using Equivalent Queries"  
Xinyu Liu, Qi Zhou, Joy Arulraj, Alessandro Orso  
Georgia Institute of Technology, Atlanta, GA, USA; liuxy@gatech.edu, arulraj@gatech.edu, orso@cc.gatech.edu  
Meta, Seattle, WA, USA; zhouqi@fb.com  

1. **Fichamento de Conteúdo:**

O artigo aborda a detecção automática de bugs de desempenho em sistemas de gerenciamento de banco de dados (DBMSs) por meio de consultas equivalentes. Ele destaca a importância do desempenho dos DBMSs em aplicativos de dados modernos e como os bugs de desempenho podem afetar negativamente a experiência do usuário. A técnica apresentada, chamada AMOEBA, propõe a comparação dos tempos de resposta de pares de consultas semanticamente equivalentes para identificar possíveis bugs de desempenho. Os resultados mostram que o AMOEBA descobriu 39 bugs potenciais em DBMSs populares, com 6 bugs confirmados e 5 corrigidos pelos desenvolvedores. Isso demonstra a eficácia da abordagem na melhoria da qualidade e do desempenho dos sistemas de banco de dados.

2. **Fichamento Bibliográfico:**

- Detecção automática de bugs de desempenho em DBMSs usando consultas equivalentes.
- Apresentação do AMOEBA como uma técnica para essa detecção.
- Avaliação do AMOEBA em DBMSs como PostgreSQL e CockroachDB.
- Uso de pares de consultas equivalentes para comparação de tempos de resposta.
- Descoberta de 39 bugs potenciais, com 6 confirmados e 5 corrigidos pelos desenvolvedores.

3. **Fichamento de Citações:**

- *"Because modern data-intensive applications rely heavily on database systems (DBMSs), developers extensively test these systems to eliminate bugs that negatively affect functionality."*
- *"To fill this gap, we present AMOEBA, a technique and tool for automatically detecting performance bugs in DBMSs."*
- *"The core idea behind AMOEBA is to construct semantically equivalent query pairs, run both queries on the DBMS under test, and compare their response time."*
- *"AMOEBA has so far discovered 39 potential performance bugs, among which developers have already confirmed 6 bugs and fixed 5 bugs."*
