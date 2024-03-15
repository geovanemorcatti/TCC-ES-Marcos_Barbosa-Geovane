# Analyzing the State of Static Analysis: A Large-Scale Evaluation in Open Source Software

Abstract—Automatic Static Analysis Tools (ASATs) have been a staple in software engineering practices for decades, yet their real-world usage remains somewhat elusive. This paper presents two studies conducted on nine different ASATs across Java, JavaScript, Ruby, and Python projects, encompassing a population of 122 and 168,214 open-source software (OSS) projects. The studies aim to understand the prevalence of ASATs, their configurations, and how these configurations evolve over time. A General Defect Classification (GDC) is introduced to standardize the comparison of warnings across ASATs. The findings indicate that while ASAT usage is widespread in OSS projects, it's not universal, and projects often deviate slightly from default configurations, though rarely introducing custom analyses. Additionally, once ASAT configurations are set, they tend to remain unchanged, with any modifications typically occurring shortly after the configuration's initial introduction.

## 1. Fichamento de Conteúdo

O artigo apresenta dois estudos realizados em uma ampla variedade de projetos de código aberto, com o objetivo de entender a prevalência, configurações e evolução do uso de Ferramentas de Análise Estática Automatizada (ASATs). Os estudos revelam que embora o uso de ASATs seja difundido em projetos de código aberto, muitos projetos não seguem uma política estrita de uso dessas ferramentas. As configurações das ASATs tendem a se desviar ligeiramente da configuração padrão, mas raramente introduzem análises personalizadas. Além disso, uma vez estabelecidas, as configurações das ASATs geralmente permanecem inalteradas, com modificações ocorrendo principalmente logo após a introdução inicial da configuração.

## 2. Fichamento Bibliográfico 

* _Automatic Static Analysis Tools (ASATs):_ Ferramentas de Análise Estática Automatizada, utilizadas para identificar problemas no código-fonte ou binário de um sistema de software.
* _Open Source Software (OSS):_ Software de código aberto, cujo código-fonte é disponibilizado publicamente e pode ser modificado e distribuído livremente.
* _General Defect Classification (GDC):_ Classificação Geral de Defeitos, introduzida para padronizar a comparação de alertas entre diferentes ASATs.
* _Configuration Evolution:_ A evolução das configurações das ASATs ao longo do tempo, mostrando que, uma vez estabelecidas, tendem a permanecer estáveis.

## 3. Fichamento de Citações 

* _"Automated Static Analysis Tools (ASATs) scan the source or binary code of a software system for a set of pre-defined problems."_
* _"Next to testing and manual code review, ASATs have become an important pillar of modern Software Quality Assurance approaches."_
* _"Most ASAT configurations, once committed, never change. The ASAT configurations that do change are typically only very slightly modified within the first week of their appearance in the studied repositories."_
* _"Our findings show that, 60% of the most popular and (therefore arguably) most advanced projects make use of ASATs."_
* _"Developers might be skeptical of the practical usefulness of ASATs due to a possible overload with irrelevant warnings."_
* _"Possible benefiters are: Researchers, Practitioners, Tool Creators, and Dashboard Creators of tools."_

