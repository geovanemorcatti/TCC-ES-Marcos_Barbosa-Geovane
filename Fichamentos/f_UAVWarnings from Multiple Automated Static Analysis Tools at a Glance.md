# UAV: Warnings from Multiple Automated Static Analysis Tools at a Glance

Abstract—Automated Static Analysis Tools (ASATs) are an integral part of today’s software quality assurance practices. At present, a plethora of ASATs exist, each with different strengths. However, there is little guidance for developers on which of these ASATs to choose and combine for a project. As a result, many projects still only employ one ASAT with practically no customization. With UAV, the Unified ASAT Visualizer, we created an intuitive visualization that enables developers, researchers, and tool creators to compare the complementary strengths and overlaps of different Java ASATs. UAV’s enriched treemap and source code views provide its users with a seamless exploration of the warning distribution from a high-level overview down to the source code. We have evaluated our UAV prototype in a user study with ten second-year Computer Science (CS) students, a visualization expert and tested it on large Java repositories with several thousands of PMD, FindBugs, and Checkstyle warnings. Project Website: https://clintoncao.github.io/uav/

## 1. Fichamento de Conteúdo

O artigo apresenta UAV, o Visualizador Unificado de ASAT, uma ferramenta que permite aos desenvolvedores comparar visualmente as saídas de diferentes Ferramentas de Análise Estática Automatizada (ASATs) em projetos Java. Diante da falta de orientação para os desenvolvedores sobre quais ASATs escolher e combinar, o UAV oferece uma maneira intuitiva de entender as forças complementares e sobreposições dessas ferramentas. Ele unifica as diferentes tipologias de alertas gerados pelas ASATs em uma visualização interativa em treemap, permitindo uma exploração fluida da distribuição de alertas desde uma visão geral até o código-fonte. A avaliação do protótipo do UAV foi realizada em um estudo com dez estudantes de segundo ano de Ciência da Computação, um especialista em visualização e testes em grandes repositórios Java, demonstrando sua eficácia na análise de alertas.

## 2. Fichamento Bibliográfico 

* _Automated Static Analysis Tools (ASATs):_ Ferramentas que analisam o código-fonte ou binário sem observar seu comportamento em tempo de execução.
* _UAV (Unified ASAT Visualizer):_ Visualizador Unificado de ASAT, uma ferramenta que permite a comparação visual das saídas de diferentes ASATs em projetos Java.
* _Visualization Expert:_ Especialista em visualização, participante da avaliação do protótipo UAV.
* _Java repositories:_ Repositórios Java onde o UAV foi testado, contendo milhares de alertas de PMD, FindBugs e Checkstyle.

## 3. Fichamento de Citações 

* _"ASATs have become an integral part of today’s software quality assurance practices."_
* _"At present, a plethora of ASATs exist, each with different strengths and many different warning typologies."_
* _"Developers lack a tool that allows them to explore which warnings a certain ASAT emits where in the project, and whether there are overlaps with existing ASATs."_
* _"To address this issue, we have created UAV, the Unified ASAT visualizer."_
* _"UAV’s enriched treemap and source code views provide its users with a seamless exploration of the warning distribution from a high-level overview down to the source code."_
* _"Our vision is that one day, anyone who uses code analysis can input their preferences, and UAV will combine different ASATs to output a result that best suits their needs."_

