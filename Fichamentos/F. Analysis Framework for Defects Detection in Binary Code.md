# Static Analysis Framework for Defects Detection in Binary Code

Abstract—Automatic Static Analysis Tools (ASATs) detect coding rule violations, including mistakes and bad practices that frequently occur during programming. While ASATs are widely used in both OSS and industry, the developers do not resolve more than 80% of the detected violations. As one of the reasons, most ASATs users do not customize their ASATs to their projects after installation; the ASATs with the default configuration report many rule violations that confuse developers. To reduce the ratio of such uninteresting warning messages, we propose a method to customize ASATs according to the product source code automatically. Our fundamental hypothesis is: A software project has interesting ASAT rules that are consistent over time. Our method takes source code as input and generates an ASAT configuration. In particular, the method enables optional (i.e., disabled by default) rules that detected no violations on the version because developers are likely to follow the rules in future development. Our method also disables violated rules because developers were unlikely to follow them. To evaluate the method, we applied our method to 643 versions of four JavaScript projects. The generated configurations for all four projects increased the ASAT precision. They also increased recall for two projects. The result shows that our method helps developers to focus on their attractive rule violations. Our implementation of the proposed method is available at https://github.com/devreplay/linter-maintainer.

Index Terms—Static Analysis Tools, Coding Rule, Coding Convention, Empirical Study

## 1. Fichamento de Conteúdo

O artigo propõe um método para personalizar automaticamente as regras de codificação de ASATs de acordo com o código-fonte do projeto de software. O método visa reduzir o número de mensagens de alerta não interessantes, que são comuns quando os ASATs são configurados com as configurações padrão. Ele parte da hipótese fundamental de que um projeto de software tem regras de ASAT interessantes e consistentes ao longo do tempo. O método analisa o código-fonte e gera uma configuração de ASAT, habilitando regras opcionais que não detectaram violações na versão atual e desabilitando regras violadas. A avaliação do método em 643 versões de quatro projetos JavaScript mostrou um aumento na precisão e, em dois projetos, um aumento na capacidade de lembrança dos ASATs. Isso demonstra que o método ajuda os desenvolvedores a se concentrarem nas violações de regras relevantes.

## 2. Fichamento Bibliográfico 

* _Automatic Static Analysis Tools (ASATs):_ Ferramentas que detectam violações de regras de codificação automaticamente, comumente usadas tanto em código aberto quanto na indústria.
* _ASAT customization:_ Personalização das regras de ASAT de acordo com o código-fonte do projeto para reduzir o número de alertas não interessantes.
* _Source code analysis:_ Análise do código-fonte para gerar configurações de ASAT que habilitam regras relevantes e desabilitam regras não seguidas.
* _Empirical study:_ Estudo que avalia a eficácia do método proposto em 643 versões de quatro projetos JavaScript.

## 3. Fichamento de Citações 

* _"Our method takes source code as input and generates an ASAT configuration."_
* _"The method enables optional rules that detected no violations on the version because developers are likely to follow the rules in future development."_
* _"Our method helps developers to focus on their attractive rule violations."_
* _"The result shows that our method selected necessary and sufficient rules for the projects."_
* _"Our method is promising to help developers automatically configure their ASATs."_
* _"In future work, we will extend the evaluation to other ASATs for different programming languages."_ 

