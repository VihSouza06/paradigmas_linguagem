**Aluna:** Vitória Souza Santos **RA:** 24229424-2



**1. A genealogia das linguagens não é uma escada de progresso. Explique essa afirmação e apresente dois fatores históricos que fazem uma linguagem influenciar outra sem necessariamente substituí-la.**

&#x20; A genealogia das linguagens de programação representa uma árvore, na qual diferentes linguagens surgem influenciadas por ideias anteriores, mas as antigas continuam existindo porque atendem a necessidades diferentes.

&#x20; Alguns fatores históricos fazem uma linguagem influenciar outra sem necessariamente substituí-la, sendo, as necessidades e domínios diferentes, uma linguagem pode ser criada para resolver problemas específicos. E também a evolução de conceitos, uma linguagem pode introduzir uma característica que posteriormente aparece em outras linguagens, mesmo que a linguagem original continue sendo utilizada.



**2. Plankalkül não foi implementada em sua época. Ainda assim, por que ela é relevante para a história das linguagens? Cite três recursos antecipados por seu projeto e explique o valor de um deles.**

&#x20; O Plankalkül, projetado por Konrad Zuse durante a década de 1940, é importante porque foi uma das primeiras propostas de uma linguagem de programação de alto nível, mesmo não tendo sido implementada de forma prática naquela época.

Seu projeto antecipou diversos recursos que posteriormente se tornaram comuns nas linguagens de programação. Entre eles podemos citar, tipos de dados e estruturas de dados, variáveis e atribuição de valores e estruturas de controle e operações condicionais.



**3. Compare Short Code, Speedcoding e os sistemas A-0/A-1/A-2 quanto ao problema enfrentado e à estratégia adotada. Por que chamá-los simplesmente de compiladores modernos seria impreciso?**

&#x20; As três iniciativas buscavam diminuir a dificuldade de programação em computadores que, originalmente, exigiam instruções muito próximas do código de máquina. Entretanto, elas adotavam estratégias diferentes.

&#x20; Chamá-los simplesmente de compiladores modernos seria impreciso porque eles não possuíam todas as características dos compiladores atuais. Alguns eram interpretadores ou sistemas de tradução bastante específicos, e os primeiros sistemas de compilação ainda estavam em uma fase experimental.



**4. Explique por que o projeto Fortran precisou convencer programadores de que código traduzido podia competir com código de máquina escrito à mão. Relacione desempenho, custo de programação e adoção.**

&#x20; Quando a Fortran foi desenvolvida pela IBM, um dos principais desafios do projeto Fortran foi desenvolver um compilador capaz de produzir código eficiente, suficientemente próximo do desempenho obtido por programadores experientes.

&#x20; Isso estava diretamente relacionado a três fatores, desempenho, pois os programas precisavam executar rapidamente, especialmente em aplicações científicas e numéricas. Custo de programação, escrever diretamente em código de máquina ou assembly exigia muito tempo e conhecimento especializado. Adoção, se Fortran produzisse programas significativamente mais lentos, os programadores poderiam não ter motivos para abandonar a programação de baixo nível.



**5. Lisp surgiu em um contexto diferente de Fortran. Compare os domínios, a representação de dados e o estilo de computação favorecido pelas duas linguagens.**

&#x20; A Fortran foi projetada pensando principalmente em problemas matemáticos e científicos. Por isso, números, operações aritméticas e arrays tiveram papel fundamental em sua concepção.

&#x20; Já a Lisp foi criada para trabalhar com processamento simbólico. Sua estrutura de listas tornou possível representar tanto dados quanto partes de programas de maneira bastante flexível. Isso favoreceu técnicas como recursão, manipulação de listas e funções, características importantes em pesquisas de inteligência artificial.





**11. Construa uma cadeia de influência que passe por ALGOL, Pascal e C. Depois contraste essa linhagem imperativa com a proposta declarativa de Prolog.**

&#x20; A cadeia de influência pode ser representada por: ALGOL → Pascal → C. ALGOL influenciou Pascal, principalmente nas estruturas de programação estruturada. Pascal influenciou outras linguagens e C pertence à mesma evolução das linguagens imperativas, embora tenha recebido influência direta de BCPL e B.



**12. Modele em linguagem natural uma pequena base Prolog com dois fatos, uma regra e uma consulta. Explique por que isso representa programação lógica, não apenas armazenamento de dados.**

&#x20; Isso é programação lógica porque, além de armazenar fatos, existem regras que permitem ao sistema deduzir novas informações.



*estudante(joao).*

*estuda(joao, computacao).*



*universitario(X) :-*

&#x20;   *estudante(X),*

&#x20;   *estuda(X, computacao).*



*universitario(joao).*



**13. Ada resultou de requisitos e projeto em grande escala. Analise como confiabilidade, tipos, pacotes e concorrência se relacionam ao domínio de sistemas críticos.**

&#x20; Ada foi projetada para sistemas grandes e críticos, nos quais confiabilidade é essencial. Tipos ajudam a detectar erros. Pacotes que organizam e modularizam o programa. Concorrência que permite controlar tarefas executadas simultaneamente. E Confiabilidade que reduz a possibilidade de erros. Por isso, Ada é adequada para sistemas em que falhas podem causar consequências graves.



**14. Compare o papel dos objetos em Smalltalk, C++ e Java. Inclua na resposta o compromisso de C++ com C e a estratégia de portabilidade de Java.**

&#x20; Smalltalk possui forte orientação a objetos; praticamente tudo é tratado como objeto.

C++: adicionou orientação a objetos ao C, mantendo grande compatibilidade com ele.

&#x20; Java foi projetada com orientação a objetos e priorizou a portabilidade, utilizando bytecode e JVM.

&#x20; Assim, C++ buscou manter a relação com C, enquanto Java buscou facilitar a execução em diferentes plataformas.



**15. A primeira aplicação de Java não foi a Web, mas a Web impulsionou sua adoção. Explique como mudanças de contexto podem reposicionar uma linguagem.**

&#x20; Java não foi criada originalmente para a Web, mas para dispositivos e sistemas embarcados. Com o crescimento da Web, suas características de portabilidade, segurança e execução por máquina virtual tornaram-se muito úteis. Isso mostra que uma linguagem pode ganhar importância quando surge um novo contexto tecnológico que valoriza suas características.

