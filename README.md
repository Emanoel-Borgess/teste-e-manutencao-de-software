# Relatório de Atividades: Testes e manuteção de software - Emanoel R. Borges

Este documento contém as anotações e soluções para todas as atividades propostas na disciplina.

## 📊 Tabela de Relato e Acompanhamento

| Aula | Título da Aula | O que fez | Pendências | Impedimentos | O que fará na sequência? | Data/Hora | Descrição |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| [**1.1**](#aula-11-introdução-a-testes-e-manutenção-de-software) | Introdução a testes e manutenção de software | Resolvi as 5 questões da atividade: outros casos notáveis. | Nenhuma. | Nenhum. | Farei as outras atividades da aula 1.1. | 20/05/2026 - 15h | Nenhuma. |
| [**1.1**](#atividade-características-e-aspectos) | Introdução a testes e manutenção de software | Resolvi as 4 questões da atividade: Características e aspectos. | Nenhuma. | Nenhum. | Farei as outras atividades da aula 1.1. | 20/05/2026 - 15h30 | Nenhuma. |

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
