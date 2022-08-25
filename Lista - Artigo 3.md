# Anti-patterns in Modern Code Review: Symptoms and Prevalence

M. Chouchen et al., "Anti-patterns in Modern Code Review: Symptoms and Prevalence," 2021 IEEE International Conference on Software Analysis, Evolution and Reengineering (SANER), 2021, pp. 531-535, doi: 10.1109/SANER50967.2021.00060.(https://ieeexplore.ieee.org/abstract/document/9425884)

## 1. Fichamento de Conteúdo

O artigo se trata de um estudo preliminar que visa investigar o fenômeno de anti padrões no processo de Code Review Moderno, o qual se trata de uma ferramenta fundamental e amplamente adotada tanto em âmbito comercial quanto em softwares de código aberto (OSS - Open Source Softwares). Este se inicia retratando o desafio de se obter um bom review, visto que é uma tarefa humana que envolve aspectos técnicos, sociais e pessoais, os quais muitas vezes resultam em práticas ruins, e que com determinada frequência podem se tornar padrões, que impactam no software de forma negativa, prejudicando a qualidade, manutenibilidade e sustentabilidade do software. Sendo assim, foram definidos cinco antipadrões:  revisores confusos (Confused reviewers), revisores divergentes (Divergent reviewers), baixa participação na revisão (Low review participation), revisão superficial (Shallow review), revisão tóxica (Toxic review). A partir disto, utilizaram a plataforma _Opendev_ (https://opendev.org/), onde coletaram dados de 100 code review para serem utilizados em uma avaliação manual pelos integrantes, os quais buscavam analisar a frequência de antipadrões durante à prática de revisão, bem como a prevalência de anti padrões sobre esses dados. Por fim, obtiveram como resultados que, 67% revisões estudadas têm ao menos um antipadrão contido no corpo da revisão, além de constatarem que dos antipadrões elencados, a baixa participação no review (Low Review Participation), é o mais frequente dentro do _dataset_ analisado. Para trabalhos futuros pretendem se aprofundar na análise, buscando uma massa maior de dados, além de visar a criação de uma ferramenta que consiga analisar de forma mais objetiva se há ou não anti padrões, visto que neste o fizeram de forma manual.

 
## 2. Fichamento Bibliográfico 

* _Code Review_ (Revisão de Código) é definido pelo autor como o processo de revisar o código de outros desenvolvedores para garantir a qualidade do software e encontrar possíveis problemas no conteúdo modificado, antes destas alterações serem incluídas na base de código. (página 1)
* _Modern Code Review_ (Code Review Moderno) técnica que visa garantir a qualidade do software e a satisfação do cliente através da identificação de defeitos, melhoria do código e aceleração do processo de desenvolvimento, este é baseado no code review tradicional, o qual tende a ser mais formal, sendo o MCR um modelo muito utilizado em projetos de código aberto. (página 1)
* _Modern Code Review Anti-patterns_ (Anti-padrões em Code Review Modernos) são práticas ruins durante a revisão de código, as quais podem ser comuns, mas que devem ser evitadas pois podem prejudicar a qualidade, manutenibilidade e sustentabilidade do software. (página 1)
* _Patches_ (Conjunto de alterações) são os conjuntos de alterações avaliados durante o processo de Code Review. (página 1)
* _Opendev_ (Opendev - Ferramenta) é um ecossistema de código aberto em escala, com foco está na revisão de código, integração contínua e hospedagem de projetos fornecida exclusivamente por meio de soluções de código aberto como Git, Gerrit, Zuul e Gitea. (página 2)

## 3. Fichamento de Citações 

* _"Modern code review (MCR) is now broadly adopted as an established and effective software quality assurance practice, with an increasing number of open-source as well as commercial software projects identifying code review as a crucial practice"_ 
* _"Nevertheless, code review is basically a human task that involves technical, personal and social aspects."_ 
* _"It is often challenging to follow these standards due to the nature of code review being basically a human task involving technical, personal and social aspects."_ 
* _"The MCR process is most effective when developers follow best practices, such as efficient, collaborative and timely review discussions and code updates to improve the code quality, enhance knowledge transfer, increase team awareness and share code ownership"_
* _"The low review participation (LRP) anti-pattern is the most frequent affecting 32% of analyzed code reviews."_
* _"Code review is defined as the process of reviewing other developers code to ensure software quality, and find potential problems in their code changes before they are merged with the codebase."_