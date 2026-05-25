# Relatório de Atividades: Testes e manuteção de software - Emanoel R. Borges

Este documento contém as anotações e soluções para todas as atividades propostas na disciplina.

## 📊 Tabela de Relato e Acompanhamento

| Aula | Título da Aula | O que fez | Pendências | Impedimentos | O que fará na sequência? | Data/Hora | Descrição |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| [**1.1**](#aula-11-introdução-a-testes-e-manutenção-de-software) | Introdução a testes e manutenção de software | Resolvi as 5 questões da atividade: outros casos notáveis. | Nenhuma. | Nenhum. | Farei as outras atividades da aula 1.1. | 20/05/2026 - 15h | Nenhuma. |
| [**1.1**](#atividade-características-e-aspectos) | Introdução a testes e manutenção de software | Resolvi as 4 questões da atividade: Características e aspectos. | Nenhuma. | Nenhum. | Farei as outras atividades da aula 1.1. | 20/05/2026 - 15h30 | Nenhuma. |
| [**1.1**](#atividade-conceito-de-qualidade-de-software) | Introdução a testes e manutenção de software | Resolvi as 3 questões da atividade: Conceito de qualidade de software. | Nenhuma. | Nenhum. | Farei as outras atividades da aula 1.1. | 20/05/2026 - 16h | Nenhuma. |
| [**1.1**](#atividade-normas-de-qualidade) | Introdução a testes e manutenção de software | Resolvi as 4 questões da atividade: Normas de qualidade. | Nenhuma. | Nenhum. | Farei as outras atividades da aula 1.1. | 20/05/2026 - 16h30 | Nenhuma. |
| [**1.1**](#atividade-modelos-de-maturidade-de-processos) | Introdução a testes e manutenção de software | Resolvi as 4 questões da atividade: Modelos de maturidade de processos. | Nenhuma. | Nenhum. | Farei as outras atividades da aula 1.1. | 20/05/2026 - 17h | Nenhuma. |
| [**1.1**](#atividade-boas-práticas) | Introdução a testes e manutenção de software | Resolvi as 3 questões da atividade: Boas práticas. | Nenhuma. | Nenhum. | Farei as atividades da aula 2.1 | 20/05/2026 - 17h45 | Nenhuma. |

---

## Aula 1.1: Introdução a testes e manutenção de software

### Atividade: Outros casos notáveis...

**De acordo com os casos abaixo responda as questões**
* Bug do Milênio
* Queda do sistema de informática da British Airways
* Interrupção do Serviço AWS S3 da Amazon
* CrowdStrike e Microsoft: entenda a interrupção cibernética que deu 'tela azul' em vários países

1. Quais são os principais vilões nessas histórias?

    O verdadeiro vilão na maioria desses casos não é um hacker ou um software malicioso, mas sim falhas humanas, dívida técnica e processos inadequados.

2. O que poderia ser feito para evitar tais problemas?

    Ter cautela e rede de segurança. Isso significa liberar atualizações aos poucos (nunca para todos ao mesmo tempo), colocar "travas" no sistema para impedir que um simples erro de digitação apague tudo e testar o "Plano B" constantemente.

3. Como você avalia a qualidade desses softwares?

    Um software de verdade precisa saber falhar sem causar um desastre. O problema não estava nos sistemas em si, mas sim na falta de cuidado na hora de fazer a manutenção e mandar as atualizações para os clientes.

4. Qual é a relação entre os casos anteriores?

    É o efeito dominó. Quase todo o planeta usa os sistemas de pouquíssimas empresas gigantes. Por causa dessa dependência, um errinho em uma única ferramenta paralisa milhares de negócios no mundo todo de uma só vez.

5. Quais foram os impactos?

    O problema saiu da internet e gerou caos na vida real. Tivemos cirurgias adiadas, milhares de voos cancelados, bilhões de dólares jogados no lixo e um susto enorme que mostrou o quanto nossa sociedade é dependente da tecnologia.

---

### Atividade: Características e aspectos

Com base nos exemplos discutidos, pense sobre:

1. Quais são as características comuns a esses softwares?

    Tanto os bons quanto os ruins compartilham algumas características
    fundamentais, como:

    * Complexidade: Todos envolvem sistemas complexos, com grande responsabilidade funcional.
    * Interacão com usuários ou sistemas críticos: Muitos atuam em ambientes
    onde erros têm impacto direto na vida das pessoas ou em finanças.
    * Dependência de confiabilidade: A maioria precisa operar com alto grau de
    precisão e segurança.
    * Desenvolvimento sob pressão: Prazos, custo ou marketing influenciam
    decisões técnicas.

2. Quais aspectos definem as questões de qualidade?

    Com base nas normas ISO (9126, 25010) e na literatura (Pressman, Hirama),
    destacam-se os seguintes aspectos:

    * Funcionalidade: O sistema realiza corretamente as funções para as
    quais foi projetado?
    * Confiabilidade: Quao consistente e o software frente a diferentes
    condições de uso?
    * Usabilidade: É fácil de usar e entender?
    * Eficiência: Faz uso adequado dos recursos (tempo, memória)?
    * Manutenibilidade: É fácil corrigir, adaptar e evoluir?
    * Segurança: Protege contra falhas e acessos indevidos?
    * Portabilidade: Pode ser usado em diferentes plataformas?

    Além disso, expectativas dos stakeholders (usuários, desenvolvedores,
    gestores, clientes) influenciam a percepção de qualidade.

3. O que poderia ser feito para melhorar?

    Diversas melhorias podem ser aplicadas:

    * Testes mais abrangentes e em camadas (unitários, integração, sistema,
    aceitação).
    * Revisões independentes de código e projeto.
    Documentação clara e padronizada.
    * Validação e verificação rigorosas, inclusive com usuários finais.
    * Sistemas de redundância e failover, especialmente em sistemas críticos.
    * Interfaces mais intuitivas e com comunicação clara de erros.
    * Uso de padrões e frameworks reconhecidos (boas práticas da engenharia
    de software).

4. Onde os pontos falhos poderiam ser corrigidos?

    Os pontos falhos geralmente se concentram em:

    * Conversões e manipulações de dados sensíveis.
    * Interfaces de operação mal projetadas.
    * Ausência de testes em cenários críticos e raros.
    * Excesso de confiança no software e negligência na redundância de
    hardware.
    * Pressa na entrega sem garantir qualidade mínima.
    * Falta de cultura de qualidade no ciclo de vida do software (desde os
    requisitos até a manutenção).

---

### Atividade: Conceito de qualidade de software

Considerando as discussões e reflexões anteriores:

1. Compare as visões de Pressman e Hirama sobre Qualidade de Software. O que há de comum? O que há de diferente?

    Pontos em comum:

    Ambos associam a qualidade de software à satisfação de requisitos e
    expectativas. Consideram a qualidade como um resultado de um processo bem estruturado, que envolve práticas, padrões e gestão adequada. Ambos reconhecem que a qualidade deve ser avaliada a partir das necessidades dos envolvidos no processo de desenvolvimento (stakeholders).

    Diferenças:
    * Pressman foca na gestão de qualidade como meio para criar um produto útil,
    que agrega valor mensurável para quem o usa e quem o desenvolve. Sua
    visão é mais estruturada e orientada ao processo e resultado do produto.
    * Hirama enfatiza que a qualidade está nas expectativas dos stakeholders
    (desenvolvedores, gerentes, usuários, clientes etc.), ou seja, sua abordagem
    é mais centrada nas percepções e interesses das partes envolvidas no projeto.

2. Tente definir com suas palavras o conceito de Qualidade de
Software com base no que foi visto;

    Qualidade de Software é a capacidade de um sistema atender de forma eficaz e confiável às necessidades e expectativas dos seus usuários e demais envolvidos, garantindo desempenho, facilidade de uso, segurança e manutenção. Isso envolve tanto o produto quanto o processo de desenvolvimento, e deve gerar valor para todos os interessados, minimizando erros e aumentando a utilidade prática do software.

3. Na prática, como os aspectos vistos podem contribuir para:

    a) Avaliar a qualidade de um software existente?
    
    * Os aspectos e conceitos apresentados ajudam na avaliação de um software existente por meio de: 
        * Verificação de conformidade com requisitos funcionais e não funcionais;
        * Análise de atributos como: usabilidade, confiabilidade, eficiência, segurança e manutenibilidade, conforme normas como ISO/IEC 25010;
        * Identificação de erros recorrentes ou excesso de manutenção, o que indica baixa qualidade;
        * Avaliação do valor agregado ao usuário e à organização, como redução de custos, melhoria nos processos ou satisfação do cliente.

    b) Construir um novo software com qualidade?

    * Na construção de novo software, os aspectos abordados contribuem para:
        * Planejamento de um processo de desenvolvimento estruturado, com base em boas práticas de engenharia de software;
        * Definição clara dos requisitos e expectativas dos stakeholders, alinhando o desenvolvimento ao valor esperado;
        * Uso de modelos de qualidade e normas (como ISO/IEC 25010, SQuaRE,CMMI) como referência;
        * Inclusão de testes contínuos, revisões técnicas, gerenciamento de mudanças e monitoramento da evolução para evitar falhas graves;
        * Garantia de que o produto seja útil, confiável, fácil de usar e sustentável ao longo do tempo.

---

### Atividade: Normas de qualidade

Acesse as referências apresentadas, pesquise e descreva brevemente:

1. Como as normas definem os aspectos de qualidade enumerados anteriormente?

    As normas definem qualidade de software, a partir de características que permitem avaliar se o produto atende aos requisitos funcionais e não funcionais. As principais normas e suas definições:

    * ISO/IEC 9126 (1991):
        * Define 6 características principais:
            * Funcionalidade;
            * Confiabilidade;
            * Usabilidade;
            * Eficiência;
            * Manutenibilidade;
            * Portabilidade.

    * ISO/IEC 25010 (2011, atualizada em 2023):
        * Expande e atualiza os modelos anteriores:
            * Qualidade do Produto: Funcionalidade, Eficiência de desempenho, Compatibilidade, Usabilidade, Confiabilidade, Segurança, Manutenibilidade, Portabilidade.
            * Qualidade em uso: Eficácia, Eficiência, Satisfação, Liberdade de risco, Cobertura do contexto.

    * Família SQuaRE (ISO/IEC 25000):
        * Organização mais ampla da qualidade dividida em categorias:
            * Requisitos de Qualidade (2503n);
            * Modelos de Qualidade (2501n);
            * Medidas (2502n);
            * Avaliação (2504n);
            * Gerência de Qualidade (2500n);

2. Monte uma tabela com a correspondência entre os termos em português e inglês, com suas respectivas definições.

    | Português | Inglês | Definição |
    | :--- | :--- | :--- |
    | Funcionalidade | Functionality | Capacidade de fornecer funções que atendam às necessidades explícitas. |
    | Confiabilidade | Reliability | Capacidade de manter desempenho sob condições estabelecidas. |
    | Usabilidade | Usability | Facilidade com que o usuário pode utilizar o software. |
    | Eficiência | Efficiency | Relação entre desempenho e recursos utilizados. |
    | Manutenibilidade | Maintainability | Facilidade de modificação e atualização do software. |
    | Portabilidade | Portability | Capacidade de ser transferido para outro ambiente. |
    | Segurança | Security | Proteção contra acesso não autorizado e falhas. |
    | Compatibilidade | Compatibility | Capacidade de interagir com outros sistemas. |
    | Eficácia (uso) | Effectiveness (in use) | Precisão com que os usuários atingem objetivos com o sistema. |
    | Satisfação (uso) | Satisfaction (in use) | Grau de contentamento do usuário final com o produto. |
    | Cobertura de contexto | Context coverage | Adaptação a diferentes condições reais de uso. |

3. Considerando as diferentes versões de normas, houveram mudanças nessas definições? São significativas?

    Sim, houve evolução e refinamento das definições:

    * A ISO/IEC 9126 era mais restrita e centrada no produto em si.
    * AISO/IEC 25010 ampliou o modelo, separando qualidade do produto e em uso, além de introduzir novos atributos, como segurança, compatibilidade, eficiência de desempenho, entre outros.
    * A partir de 2023/2024, com a família SQuaRE, há uma visão mais sistêmica e modular da qualidade, com melhor detalhamento para diferentes contextos (produto, uso, processo, medição, avaliação).

    As mudanças foram significativas, pois:

    * Incorporaram questões modernas como segurança, interação, adaptabilidade e contexto de uso.
    * Adotaram uma estrutura modular, facilitando aplicação em diferentes cenários (ex: software embarcado, aplicativos móveis, sistemas web, entre outros).

4. Considerando as normas mais recentes, comente por que há diferentes categorias de normas dentro da Família SQuaRE.

    A família SQuaRE (ISO/IEC 25000) é dividida em categorias para tornar a avaliação e desenvolvimento da qualidade de software mais estruturada e completa. As diferentes categorias permitem:

    | Categoria | Objetivo |
    | :--- | :--- |
    | 2500n - Gerência | Definir princípios e vocabulários gerais de qualidade. |
    | 2501n - Modelos | Definir modelos de qualidade do produto e uso. |
    | 2502n - Medidas | Estabelecer métricas para avaliação quantitativa. |
    | 2503n - Requisitos | Identificar e definir requisitos de qualidade esperados. |
    | 2504n - Avaliação | Estabelecer métodos de avaliação com base nas métricas e modelos. |

    Essa organização facilita o uso modular e adaptado, às necessidades específicas de cada projeto ou organização, promovendo padronização e melhoria contínua.

---

### Atividade: Modelos de maturidade de processos
Pesquise sobre:
1. O que representam os níveis 1 ao 5 no CMMI? O que isso implica para as empresas?

    O modelo CMMI (Capability Maturity Model Integration) define cinco níveis de maturidade,
    que representam o grau de sofisticação e controle dos processos de desenvolvimento de software de uma organização:

    | Nível | Nome | Descrição |
    | :--- | :--- | :--- |
    | 1 | Inicial | Processos imprevisíveis, mal controlados e reativos. Resultados dependem de indivíduos. |
    | 2 | Gerenciado | Processos básicos de gerenciamento de projetos são estabelecidos. Controle limitado. |
    | 3 | Definido | Os processos são padronizados e documentados em toda a organização. |
    | 4 | Quantitativamente Gerenciado | Processos são medidos e controlados por métricas quantitativas. |
    | 5 | Otimização | Melhoria contínua com base em dados; foco em inovação e prevenção de defeitos. |

    Implicações para as empresas:
    * Empresas em níveis mais altos têm maior previsibilidade, produtividade e qualidade.
    * Conseguem reduzir riscos, custos com retrabalho e aumentar a confiança dos clientes.
    * Algumas licitaçoes (ex: contratos com o governo dos EUA) exigem que fornecedores estejam em nível 3 ou superior.

2. Responda a questão anterior, considerando o modelo MPS-BR.

    O MPS-BR (Melhoria de Processo do Software Brasileiro), desenvolvido pela SOFTEX, é inspirado no CMMI, mas adaptado à realidade brasileira, especialmente para pequenas e médias empresas. Ele possui 7 níveis, designados por letras:

    | Nível | Nome | Equivalente ao CMMI |
    | :--- | :--- | :--- |
    | G | Parcialmente Gerenciado | ~ CMMI Nível 2 |
    | F | Gerenciado | ~ CMMI Nível 2/3 |
    | E | Parcialmente Definido | ~ CMMI Nível 3 |
    | D | Largamente Definido | ~ CMMI Nível 3 |
    | C | Definido | ~ CMMI Nível 3 |
    | B | Gerenciado Quantitativamente | ~ CMMI Nível 4 |
    | A | Em Otimização | ~ CMMI Nível 5 |

    Implicações para as empresas:

    * Fornece um caminho gradual para melhoria dos processos.
    * Permite certificação incremental, com menor custo que o CMMI.
    * Incentiva a maturidade progressiva, com foco na realidade brasileira.

3. Como uma empresa pode se capacitar para usar um modelo de maturidade? Quais são os benefícios disso?

    Capacitação:

    1. Treinamento da equipe (consultores, gestores, engenheiros).
    2. Mapeamento dos processos atuais da organização.
    3. Adoção de boas práticas da engenharia de software (ex: requisitos, testes, revisões).
    4. Uso de ferramentas de apoio (ex .: rastreamento de requisitos, métricas).
    5. Engajamento da alta gestao e definição de metas de melhoria.
    6. Contratação de consultorias especializadas (para diagnóstico e auditoria).
    7. Avaliação formal (benchmark ou certificação).

    Benefícios:

    * Melhoria da qualidade do software.
    * Reducao de retrabalho e custos com erros.
    * Maior previsibilidade e controle de projetos.
    * Facilidade para conquistar novos clientes, especialmente empresas e governos que exigem certificações.
    * Valorização da empresa no mercado (inclusive para fusões e aquisições).

4. Pesquise por empresas que sejam certificadas em algum modelo de maturidade.

    Exemplos de empresas certificadas em CMMI:

    * TOTVS (Brasil) - CMMI nível 3.
    * Stefanini IT Solutions - CMMI nível 5.
    * Accenture-CMMI nível 5.
    * Tata Consultancy Services (TCS) - CMMI nivel 5.
    * Infosys (Índia)-CMMI nível 5.

    Empresas certificadas no MPS-BR:

    A lista oficial pode ser consultada no site da SOFTEX.
    Exemplos (retirados do site da SOFTEX):

    * G&P Projetos e Sistemas - MPS nível A.
    * Getrak - MPS nivel F.
    * CWI Software - MPS nivel C.
    * Stefanini (unidades no Brasil) - MPS em vários níveis (F, E, D ... ).

---

### Atividade: Boas práticas
Pesquise sobre:
1. Acesse a página de cada associação profissional indicada, observando os temas principais abordados em seus sites.

    * IEEE - Institute of Electrical and Electronics Engineers
        * Publicações científicas e técnicas (IEEE Xplore)
        * Desenvolvimento de padrões internacionais (ex. IEEE 829 - Teste de Software)
        * Conferências internacionais em engenharia elétrica, computação, IA, redes e sistemas embarcados
        * Educação continuada, workshops e certificações
        * Comunidade técnica global com foco em inovação tecnológica

    * ACM - Association for Computing Machinery
        * Biblioteca ACM Digital Library (pesquisa e acesso a periódicos e conferências)
        * Avanço da ciência e arte da computação
        * Especializações como software engineering, HCI, sistemas distribuídos
        * Eventos e prêmios como o Turing Award
        * Ações educacionais e éticas na computação

    * SBC - Sociedade Brasileira de Computação
        * Fomento à pesquisa em computação no Brasil
        * Organização de eventos como SBES, CBSOFT, CSBC
        * Publicação da SBC OpenLib (SOL) com artigos nacionais
        * Apoio à formação de profissionais por meio do POSCOMP
        * Discussões sobre políticas públicas e inclusão digital

2. Pesquise em suas bibliotecas digitais alguns artigos associados ao tema de qualidade de software. Tente baixar ao menos um de cada biblioteca que chame mais a sua atenção sobre o assunto.

    * IEEE Xplore Digital Library
        * Exemplo de artigo: "Software Quality Attributes and Metrics: A Comparative Study".
        
        Descreve diferentes atributos de qualidade (como confiabilidade, usabilidade, eficiência) com base em padrões ISO e modelos como o ISO/IEC 25010.

    * ACM Digital Library
        * Exemplo de artigo: "A Systematic Literature Review on Software Quality Models".
        
        Analisa e compara modelos clássicos como McCall, Boehm, Dromey e ISO/IEC.

    * SBC OpenLib (SOL)
        * Exemplo de artigo: "Uma Proposta de Extensão do Modelo ISO/IEC 25010 para Qualidade de Aplicativos Móveis".
        
        Discute como adaptar os critérios de qualidade para a realidade de dispositivos móveis.

3. Pesquisa sobre os autores indicados e aponte algumas de suas principais obras e contribuições para a área de Qualidade de Software.

* Barry Boehm
    * Obra principal: Software Engineering Economics (1981)
    * Contribuições:
        * Criador do modelo de ciclo de vida Spiral Model
        * Introduziu o conceito de Custo da Qualidade de Software
        * Fundador do modelo COCOMO (COnstructive COst Model)

* Watts Humphrey
    * Obra: Managing the Software Process
    * Contribuições:
        * Criador do PSP (Personal Software Process) e TSP (Team Software Process)
        * Atuou no SEI e contribuiu para o desenvolvimento do modelo CMM/CMMI

* David Parnas
    * Obra: On the Criteria to Be Used in Decomposing Systems into Modules (1972)
    * Contribuições:
        * Introduziu o conceito de ocultamento de informação (information hiding) na engenharia de software
        * Pioneiro em modularização e estruturação de software

* E. W. Dijkstra
    * Obra: A Discipline of Programming
    * Contribuições:
        * Fundador dos fundamentos teóricos da programação estruturada
        * Forte defensor da verificação formal de software

* C. A. R. Hoare
    * Obra: Communicating Sequential Processes
    * Contribuições:
        * Criador do algoritmo de ordenação QuickSort
        * Introduziu a lógica de Hoare para verificação formal de programas

* Michael Feathers
    * Obra: Working Effectively with Legacy Code
    * Contribuições:
        * Foco em refatoração e melhoria de código legado
        * Popularização de testes automatizados em sistemas antigos

* Martin Fowler
    * Obra: Refactoring, Patterns of Enterprise Application Architecture
    * Contribuições:
        * Criador de vários padrões de projeto aplicados à engenharia de software
        * Especialista em arquiteturas limpas e ágeis

* Robert C. Martin (Uncle Bob)
    * Obra: Clean Code, Clean Architecture
    * Contribuições:
        * Princípios SOLID
        * Advocacia de práticas ágeis e testes automáticos

* Kent Beck
    * Obra: Test-Driven Development: By Example
    * Contribuições:
        * Criador do Extreme Programming (XP)
        * Popularizador do TDD - Test Driven Development

---