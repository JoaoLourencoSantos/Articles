# Accept or Not? An Empirical Study on Analyzing the Factors that Affect the Outcomes of Modern Code Review?

D. Wang, Q. Wang, J. Wang and L. Shi, "Accept or Not? An Empirical Study on Analyzing the Factors that Affect the Outcomes of Modern Code Review?," 2021 IEEE 21st International Conference on Software Quality, Reliability and Security (QRS), 2021, pp. 946-955, doi: 10.1109/QRS54544.2021.00104. (https://ieeexplore.ieee.org/abstract/document/9724868)

## 1. Fichamento de Conteúdo

O artigo se trata de uma análise quantitativa que busca maneiras de melhorar a eficácia e a eficiência do MCR (do inglês Modern Code Review). Sendo assim, sua pesquisa visou identificar os fatores que impactam na aceitação das modificações e na quantidade de rodadas necessárias para uma revisão. Para a seleção de fatores, analisaram vários artigos que categorizam aspectos do _code review_. Após isto, selecionaram aspectos ainda não analisados pela literatura, obtendo uma lista final de 29 categorias de aspectos, os quais se dividem em quatro categorias: autor, modificação, qualidade do código e revisão. A partir disso, coletaram dados de 16.950 _patches_ de 18 projetos de código aberto dos sistemas Android e Eclipse, os quais se baseiam na linguagem Java e utilizavam a plataforma Gerrit para revisão de código. Assim, realizaram uma análise estatística dos dados obtidos. Como resultados, identificaram que: em relação ao autor do _patch_, aspectos como a quantidade de reviews aceitos e a quantidade de revisões realizadas, impactam de forma positiva na facilidade com que o review será aceito. Além disso, o tipo de projeto, a quantidade de linguagens diferentes contidas no _patch_, acompanhadas pela quantidade de revisores podem impactar diretamente na quantidade de rodadas de revisão. Além das constatações obtidas, evidenciaram também possíveis atuações para tornar o processo mais eficaz, tais como: incentivar a participação dos desenvolvedores na revisão, avaliar com maiores critérios _paths_ com multilinguagens de programação, alertou também sobre a quantidade de linhas de um _patch_, bem como os revisores, visando ser mais assertivo durante a escolha de revisores se atentando à experiência dos mesmos. Por fim, para trabalhos futuros, visam prosseguir a pesquisa com foco em várias linguagens além do Java, a fim de evidenciar como esses fatores podem impactar estes projetos.
## 2. Fichamento Bibliográfico  

* _MCR_ (Modern Code Review) segundo o autor, uma das práticas importantes de garantia de qualidade de software. Além disto, é um processo de revisão de código baseado em ferramentas, que pode integrar com o processo de desenvolvimento de software. (página 1)
* _Patch acceptance_ (Aceitação de alterações) conjunto de alterações consideradas aceitáveis seguindo padrões de qualidade, e sendo aprovada durante a revisão de código. (página 1)
* _OpenAFS_ (OpenAFS) é uma implementação de código aberto do sistema de arquivos distribuído Andrew, a qual foi utilizada para mineração de dados sobre a revisão de código. (página 2)
* _Gerrit_ (Gerrit) é uma ferramenta de revisão de código para projetos baseados no controle de versionamento _Git_, onde é possível avaliar as modificações de código de um determinado projeto, aprovando e reprovando-as. Este é amplamente utilizado por organizações de software de código aberto, como o Android e Eclipse. (página 3)
## 3. Fichamento de Citações 

* _"However, in practice, not all submitted patches can be accepted and integrated into the codebase the first time, since their quality is unsatisfactory or even poor, which might not pass patch review or need multiple revisions."_ 
* _"Software code review is one of the important practices of software quality assurance"_ 
* _"Modern code review is now widely utilized in some organizations, especially open source software organizations"_
* _" A patch is said to be abandoned if its code review fails, and it may occur when the patch does not implement a relevant, working feature or bug fix, or when the project’s development guidelines are not followed "_ 
* _"The more the max linesInserted an author submitted, the lower patch acceptance the author will have"_
* _" 75 percent of defects found during the review mainly focus on improving software evolvability by making it easier to understand and modify, rather than the visible functionality."_


