# BinSide: Static Analysis Framework for Defects Detection in Binary Code

Abstract—Software developers make mistakes that can lead to failures of a software product. One approach to detect defects is static analysis: examining code without execution. Currently, various source code static analysis tools are widely used to detect defects. However, source code analysis is not enough. This paper introduces BinSide: a binary static analysis framework for defects detection. It does interprocedural, context-sensitive, and flow-sensitive analysis. The framework uses platform-independent intermediate representation and provides an opportunity to analyze various architectures' binaries. The framework includes value analysis, reaching definition, taint analysis, freed memory analysis, constant folding, and constant propagation engines. It provides an API (application programming interface) and can be used to develop new analyzers. Additionally, we used the API to develop checkers for classic buffer overflow, format string, command injection, double free, and use after free defects detection.
Keywords—Binary static analysis, defects detection, value analysis

## 1. Fichamento de Conteúdo

O artigo apresenta o BinSide, um framework de análise estática de código binário para detecção de defeitos. Em contraste com as ferramentas de análise estática de código-fonte, o BinSide permite a detecção de defeitos em bibliotecas binárias de terceiros e otimizações do compilador que não são provavelmente corretas. O framework realiza análises interprocedurais, sensíveis ao contexto e sensíveis ao fluxo, utilizando uma representação intermediária independente da plataforma. Ele inclui uma variedade de mecanismos de análise, como análise de valor, análise de mancha, análise de memória liberada, dobra e propagação de constantes. Além disso, o BinSide oferece uma API para o desenvolvimento de novos analisadores e checkers para defeitos comuns, como estouro de buffer e injeção de comandos.

## 2. Fichamento Bibliográfico 

* _Static code analysis:_ Exame do código sem execução do programa, usado para encontrar bugs difíceis de detectar durante os testes.
* _Binary static analysis:_ Análise estática de código binário, menos investigada em comparação com a análise de código-fonte, mas útil quando o código-fonte não está disponível ou otimizações do compilador podem introduzir erros.
* _Interprocedural analysis:_ Análise que leva em conta o fluxo de controle e dados entre procedimentos.
* _Context-sensitive analysis:_ Análise que considera o contexto de execução de uma instrução.
* _Flow-sensitive analysis:_ Análise que considera o fluxo de controle do programa.
* _API (Application Programming Interface):_ Interface que permite aos usuários estender a funcionalidade do framework e desenvolver novos analisadores.
  
## 3. Fichamento de Citações 

* _"Static code analysis examines code without executing the program. Through a complete analysis of the semantics, control and data flow, static code analysis can find bugs that are difficult or even impossible to find in the stage of software testing."_
* _"Static analyzers scan all execution paths and analyze them regardless of the probability of their execution. Thus, static analyzers find errors on rarely executable paths that often go unnoticed during testing."_
* _"The main advantage of our framework is the rich set of analyses available to the user through API."_
* _"All these analyses are interprocedural, context-sensitive, flow-sensitive and take into account registers, memory in stack, heap and static region."_
* _"The API can be used to extend framework functionality ։ users can easily write their own analysis or defect detectors."_
* _"We used it to find classic buffer overflow, format string, command injection, use after free and double free defects."_

