# 📒 Anotações – ISO/IEC 27001

Bem-vindo(a) às anotações da ``Seção 6`` do curso **EXIN ISO 27001: Fundamentos de Segurança da Informação**!

Aqui você encontrará um resumo da principal aula desta seção, com explicações e exemplos práticos sobre a norma **ISO/IEC 27001**.

---

## 📝 Resumo Geral

Este README contém minhas anotações pessoais sobre a norma **ISO/IEC 27001**, voltadas para estudo e aplicação prática no ambiente de segurança da informação.  
Organizei o conteúdo de forma objetiva, destacando os conceitos mais relevantes para revisão e fixação.

---

> **Atenção:** O link da aula não direciona para o vídeo, pois o conteúdo é pago.  
> Curso original: [EXIN ISO 27001: Fundamentos de segurança da informação](https://www.udemy.com/course/exin-iso-27001-information-security-foundation/)

---

## 📚 Conteúdo da Aula

### Seção 6

- [Aula 35 - Visão Geral da Seção 2](#aula-35--visão-geral-da-seção-2)
- [Aula 36 - O que é uma ameaça](#aula-36--o-que-é-uma-ameaça)
- [Aula 37 - O que é um risco](#aula-37--o-que-é-um-risco)
- [Aula 38 - O que é vulnerabilidade](#aula-38--o-que-é-vulnerabilidade)
- [Aula 39 - Diferença entre Acidente, Incidente e Desastre](#aula-39--diferença-entre-acidente-incidente-e-desastre)
- [Aula 40 - Incidente e Desastre em Segurança da Informação](#aula-40--incidente-e-desastre-em-segurança-da-informação)
- [Aula 41 - Tipos de Ameaças de Segurança](#aula-41--tipos-de-ameaças-de-segurança)
- [Aula 42 - Tipos de Danos](#aula-42--tipos-de-danos)
- [Aula 43 - Requisitos de SI (Segurança da Informação)](#aula-43--requisitos-de-si-segurança-da-informação)
- [Aula 44 - Gerenciamento de Risco de SI](#aula-44--gerenciamento-de-risco-de-si)
- [Aula 45 - Avaliação dos Riscos de SI](#aula-45--avaliação-dos-riscos-de-si)
- [Aula 46 - Análise de Riscos de SI](#aula-46--análise-de-riscos-de-si)
- [Aula 47 - Tratamento dos Riscos de SI](#aula-47--tratamento-dos-riscos-de-si)

---

### Aula 35 – Visão Geral da Seção 2

Nesta aula, foi apresentada uma visão geral da **Seção 2** do curso, destacando a importância dos temas abordados para a certificação ISO 27001.

O conteúdo desta seção é considerado um dos mais relevantes para a prova, pois trata de conceitos fundamentais como ``ameaças`` e ``riscos``, que juntos representam cerca de **30% do peso total do exame**.

#### Pontos principais:

- ``Ameaças:`` São eventos ou ações que podem comprometer a segurança da informação, afetando a confidencialidade, integridade ou disponibilidade dos dados.

- ``Riscos:`` Referem-se à probabilidade de uma ameaça explorar uma vulnerabilidade e causar impacto negativo à organização.

Durante a seção, foram explicados exemplos práticos, classificações e formas de identificar e tratar ameaças e riscos no contexto da segurança da informação.

**Resumo:** A compreensão profunda desses conceitos é essencial para quem busca a certificação ISO 27001, pois são temas recorrentes e de grande peso na avaliação.

---

### Aula 36 – O que é uma ameaça

Vamos entender o conceito de ameaça com exemplos do dia a dia:

Quando éramos pequenos, era comum ouvir frases como:

- "Se você não fizer o dever de casa, vai ficar sem celular/TV."
- "Se não comer a comida, vai ficar sem sobremesa."
- "Se não arrumar a cama, vai ficar sem brincar."

Essas situações são exemplos de ameaças: alguém (no caso, nossos responsáveis) nos alertava sobre uma possível consequência negativa caso não cumpríssemos uma tarefa. Algumas dessas ameaças se concretizavam, outras não passavam de avisos.

#### Conceito segundo a ISO 27001

- ``Ameaça:`` Potencial de causar um incidente indesejado que pode resultar em dano a um sistema ou organização.
- ``Agente de ameaça:`` Entidade (pessoa, evento, etc.) que explora uma vulnerabilidade.

No exemplo acima, a mãe seria o agente de ameaça, tentando causar um dano ao nosso lazer (tirar o celular, TV, etc.), sabendo que tínhamos a vulnerabilidade de não cumprir as tarefas.

#### No contexto de TI

A ameaça é a possibilidade de algo ruim acontecer. Por exemplo:

- **Servidor com disco rígido:** Todo disco sofre desgaste natural. O tempo é o agente de ameaça, pois com o passar dos anos, o disco pode falhar (vulnerabilidade: desgaste do disco).

#### Exemplos práticos

- **Funcionário mal-intencionado:** Pode tentar vazar informações estratégicas ou deletar dados importantes. Aqui, o funcionário é o agente de ameaça, e a vulnerabilidade pode ser o acesso que ele tem aos sistemas.

- **Erro acidental:** Um funcionário, ao limpar o data center, desliga acidentalmente o servidor. Ele não teve intenção, mas ainda assim foi o agente de ameaça, explorando a vulnerabilidade do acesso físico ao equipamento.

- **Ameaças naturais:** Furacões, enchentes, incêndios, etc., também são agentes de ameaça que podem explorar vulnerabilidades na infraestrutura.

#### Resumindo

- ``Vulnerabilidade:`` Fraqueza ou brecha que pode ser explorada.
- ``Ameaça:`` Algo que pode explorar essa fraqueza e causar um incidente.
- ``Agente de ameaça:`` Quem ou o que explora a vulnerabilidade.

Entender esses conceitos é fundamental para identificar riscos e proteger os ativos de informação da organização.

---

### Aula 37 – O que é um risco

Vamos entender o conceito de risco, trazendo exemplos do dia a dia e do ambiente de gerenciamento de projetos.

Quando falamos de riscos, temos duas possibilidades:

- ``Risco negativo:`` Sempre traz um impacto negativo.
- ``Risco positivo:`` É uma situação em que, ao tomar uma decisão, você pode tanto perder quanto ganhar. Se der certo, você obtém um benefício inesperado.

#### Exemplo prático

Imagine que você vai investir mil reais na bolsa de valores. Ao dormir, você corre o risco de acordar com 10 mil reais (risco positivo) ou com apenas 1 centavo (risco negativo).  
Aqui, você aceitou correr o risco, e o resultado pode ser bom ou ruim, dependendo do que acontecer no mercado.

No mundo dos investimentos, ouvimos muito que risco pode ser positivo ou negativo. Investidores correm o risco das ações subirem (ganho) ou caírem (perda).

#### Avaliando um risco

Para avaliar um risco, precisamos considerar:

> **Risco = ameaça + vulnerabilidade + probabilidade + potencial de impacto**

- ``Vulnerabilidade:`` No exemplo do investimento, é a possibilidade de ganhar ou perder dinheiro.
- ``Ameaça:`` É o evento que pode explorar essa vulnerabilidade, como a variação do mercado.
- ``Probabilidade:`` A chance de o evento acontecer.
- ``Potencial de impacto:`` O quanto você pode ganhar ou perder. Se você investe todo o seu dinheiro e perde, o impacto é alto.

Assim, é importante avaliar se você tem estrutura para assumir o risco.

#### Definição de risco (livro base)

> Risco é a probabilidade de um agente de ameaça tirar proveito de uma vulnerabilidade e do impacto correspondente no negócio.

Ou seja, risco é a composição de vulnerabilidade, ameaça e impacto.

---

**Resumo:** Risco pode ser positivo ou negativo, dependendo do resultado. Avaliar riscos envolve entender as ameaças, vulnerabilidades, a probabilidade de ocorrência e o impacto potencial para o negócio ou para você.

---

### Aula 38 – O que é vulnerabilidade

Todos possuem algum tipo de fraqueza, seja um animal selvagem, uma rede de computadores, um bebê ou um adulto. Essas fraquezas podem ser doenças, vícios ou comportamentos compulsivos. Cada pessoa ou sistema pode ter uma vulnerabilidade que pode ser explorada por uma ameaça.

No contexto de serviços de TI, para que um serviço gere valor ao cliente, ele precisa de processos de garantia bem definidos:

- ``Capacidade``
- ``Disponibilidade``
- ``Continuidade``
- ``Segurança``

Quando esses quatro processos estão bem arquitetados, dizemos que o serviço possui garantia.

#### Definição segundo a ISO 27001

> Vulnerabilidade é a fraqueza de um ativo ou controle que pode ser explorada por uma ou mais ameaças.  
> A vulnerabilidade caracteriza a ausência ou fraqueza de uma garantia que pode ser explorada.

**Exemplo:** Se um serviço de TI não possui um sistema de segurança, já existe uma vulnerabilidade: a falta de segurança.  
Se o serviço tem alta segurança, mas não possui controle de capacidade, pode ficar indisponível a qualquer momento — aqui, a garantia do serviço está comprometida.

A vulnerabilidade sempre estará ligada à ausência ou fraqueza de um desses componentes da garantia.

#### Relação com Segurança da Informação

Quando falamos de segurança da informação (integridade, disponibilidade, confidencialidade), estamos tratando do processo de segurança e também do processo de disponibilidade do serviço.

#### Para memorizar

Qualquer serviço que tenha ausência ou fraqueza em um dos quatro princípios da garantia (disponibilidade, capacidade, continuidade e segurança) já está sujeito a sofrer uma ameaça. Ou seja, já possui uma vulnerabilidade pronta para ser explorada.

Sempre que pensar em vulnerabilidade, pergunte-se:

- A disponibilidade está comprometida?
- A continuidade está comprometida?
- A capacidade está comprometida?
- A segurança está comprometida?

Se a resposta for sim para qualquer um desses pontos, o serviço tem uma vulnerabilidade — uma fraqueza que pode ser explorada por uma ameaça.

---

### Aula 39 – Diferença entre Acidente, Incidente e Desastre

No contexto da segurança da informação e tecnologia, é fundamental entender a diferença entre acidente, incidente e desastre, pois cada um exige respostas e preparações diferentes.

#### Acidente

- **Definição:** Acontecimento casual, inesperado, uma ocorrência que pode envolver dano, perda, sofrimento ou até morte.
- **Exemplo:** Acidente de carro.
- **No contexto de TI:** Pode ser uma falha inesperada, como um cabo rompido acidentalmente.

#### Incidente

- **Definição:** Algo que incide, ocorre de forma acessória ou secundária, geralmente de menor impacto e que não altera significativamente o andamento das operações.
- **Exemplo:** Dificuldade passageira que não modifica o desenrolar de uma operação.
- **No contexto de TI:** Uma queda momentânea de um serviço, um erro temporário que logo é resolvido.

#### Desastre

- **Definição:** Evento que causa sofrimento e grande prejuízo (físico, moral, material, emocional). É o pior cenário possível, uma verdadeira catástrofe.
- **Exemplo:** Situação catastrófica, como um incêndio que destrói todo o data center.
- **No contexto de TI:** Perda total de dados, falha completa de infraestrutura, situações em que o impacto é tão grande que compromete a continuidade do negócio.

> **Resumo prático:**  
> - ``Acidente:`` Algo inesperado, pode causar dano, mas nem sempre é grave.
> - ``Incidente:`` Algo secundário, geralmente de menor impacto e recuperável.
> - ``Desastre:`` O pior cenário possível, catástrofe total, exige plano de continuidade.

#### Preparação para Desastres

Na segurança da informação, precisamos estar preparados para desastres. Isso é feito por meio de ``planos de continuidade`` e processos específicos para enfrentar esses momentos críticos.

Como prever o que pode acontecer?  
A partir da análise de vulnerabilidades, ameaças, probabilidade e impacto — ou seja, avaliando os riscos.

---

**Resumo:**  

- ``Acidente``: evento inesperado, pode causar dano.
- ``Incidente``: evento secundário, geralmente de menor impacto.
- ``Desastre``: pior cenário possível, catástrofe total.
- Esteja sempre preparado com planos de continuidade para enfrentar ``desastres`` na área de TI e segurança da informação.

---

### Aula 40 – Incidente e Desastre em Segurança da Informação

Segundo a norma ISO 27001:

#### Incidente

Um ``incidente`` é indicado por um simples evento ou por uma série de eventos de segurança da informação indesejados ou inesperados, que tenham grande probabilidade de comprometer as operações do negócio e ameaçar a segurança da informação.

- **Exemplo:** Um ataque de ransomware, acesso não autorizado, vazamento de dados, ou qualquer situação que coloque em risco a confidencialidade, integridade ou disponibilidade das informações.

#### Desastre

Um ``desastre`` é um grande incidente que ameaça a continuidade do negócio, se manifestado.

- **Exemplo:** Incêndio em data center, enchente que destrói servidores, falha total de infraestrutura, ou qualquer evento de grande escala que pode paralisar as operações da organização.

---

**Resumo:**  

- ``Incidente:`` Evento (ou série de eventos) que compromete a segurança da informação e pode afetar as operações do negócio.
- ``Desastre:`` Incidente de grande proporção, capaz de ameaçar a continuidade do negócio, exigindo planos de recuperação e contingência.

A preparação para incidentes e desastres é fundamental para garantir a resiliência e a continuidade das operações em segurança da informação.

---

### Aula 41 – Tipos de Ameaças de Segurança

Quando falamos em ameaças à segurança da informação, podemos classificá-las em dois grandes grupos: ``humanas`` e ``não humanas``. Além disso, as ameaças humanas podem ser ``intencionais`` ou ``não intencionais``.

#### Tipos de ameaças

- ``Humanas``
  - **Intencionais:** São aquelas em que a pessoa tem a intenção de causar dano.  
    - *Exemplo:* Um colaborador apaga propositalmente arquivos importantes da empresa, sabendo que isso pode gerar prejuízo.
    - *Engenharia social:* Quando alguém tenta manipular outra pessoa, usando a famosa "lábia", para induzi-la a tomar uma ação desejada pelo atacante.
  - **Não intencionais:** Ocorrem sem a intenção de causar dano.  
    - *Exemplo:* Uma pessoa da limpeza esbarra e desliga acidentalmente o cabo de energia do data center. Não foi proposital, mas ainda assim representa uma ameaça.

- ``Não humanas``
  - São ameaças originadas por eventos naturais ou fatores externos.
    - *Exemplo:* Rompimento de uma barragem, enchentes, incêndios, terremotos, entre outros.

---

**Importante:**  
Independentemente do tipo de ameaça (humana, não humana, intencional ou não intencional), é fundamental aplicar medidas de segurança para assegurar a confiabilidade da informação.

Compreender os diferentes níveis e tipos de ameaças é essencial para definir as melhores estratégias de proteção e resposta, garantindo a segurança dos ativos

---

### Aula 42 – Tipos de Danos

Quando falamos em danos no contexto da segurança da informação, eles podem ser classificados em dois tipos principais: ``danos diretos`` e ``danos indiretos``.

#### Danos Diretos

- **Definição:** São aqueles que têm consequência imediata e direta sobre o negócio quando uma ameaça se concretiza.
- **Exemplo:** Perda financeira imediata devido a um ataque hacker, paralisação de sistemas essenciais, perda de dados críticos.

#### Danos Indiretos

- **Definição:** São consequências que surgem após o evento principal, muitas vezes como efeito colateral do dano direto.
- **Exemplo:** Prejuízo à imagem da empresa, perda de confiança dos clientes, processos judiciais, multas, queda no valor das ações.

Às vezes, um dano direto pode desencadear um dano indireto. Por exemplo, se uma empresa sofre um vazamento de dados (dano direto), pode ter sua reputação abalada e perder clientes (dano indireto).

Danos indiretos são comuns em situações que envolvem a imagem corporativa. Por exemplo, se a empresa X tem 100 milhões de logins vazados, além do impacto técnico e financeiro, há um grande prejuízo para a reputação e confiança na organização.

---

**Resumo:**  

- **Dano direto:** Impacto imediato e mensurável.
- **Dano indireto:** Consequências secundárias, geralmente relacionadas à imagem, confiança e continuidade do negócio.

---

### Aula 43 – Requisitos de SI (Segurança da Informação)

Algumas empresas não têm a opção de abrir mão da Segurança da Informação (SI).  
Muitas vezes, o segmento de mercado em que atuam exige a implementação de um Sistema de Gestão de Segurança da Informação (SGSI) e controles específicos.

Quando falamos de requisitos de SI, temos três pilares principais:

1. ``Avaliação dos riscos para a organização``
   - Identificar, analisar e tratar os riscos que podem afetar os ativos de informação.

2. ``Conjunto de princípios, objetivos e requisitos de negócios``
   - Alinhar a segurança da informação com as metas e necessidades estratégicas da empresa.

3. ``Questões legais, estatutárias, regulatórias e contratuais``
   - Atender às exigências de leis, normas, regulamentos e contratos aplicáveis ao negócio.

Independente do pilar, a empresa precisa possuir controles e medidas de proteção adequados.  
Essas medidas devem preparar a organização para lidar com perdas, ameaças e desastres.

> **Importante:**  
> As medidas de segurança a serem aplicadas dependem do cenário de cada empresa, serviço ou perfil de risco.  
> É fundamental entender o contexto para definir os controles e proteções mais adequados.

---

### Aula 44 – Gerenciamento de Risco de SI

Gerenciar significa "acompanhar".  
A função de um gerente é dar direcionamento para que a equipe conduza o trabalho da melhor forma possível.

Quando falamos de ``gerenciamento de risco``, estamos tratando de um processo, que é composto por ``entradas``, ``atividades`` e ``saídas``:

- **Entradas:** Análises, identificação, cruzamento de informações e avaliação do impacto que uma vulnerabilidade pode trazer.
- **Atividades:** Monitorar, mitigar, reduzir o impacto, aplicar contramedidas.
- **Saída:** Manter os riscos sob controle.

Dentro desse processo, existem duas vertentes principais:

- ``Análise de risco``
- ``Gerenciamento de risco``

O gerenciamento só acontece após a análise do risco.  
É como se "risco" fosse um grande grupo, e dentro dele tivéssemos essas duas áreas.

#### Definições

- **ISO 27001:**  
  > Atividades coordenadas para dirigir e controlar uma organização em relação aos riscos.

- **Livro base:**  
  > Processo de planejar, organizar, liderar e controlar as atividades de uma organização a fim de minimizar os efeitos dos riscos sobre o lucro e o capital.

O gerenciamento de riscos é uma ``atividade cíclica``, nunca acaba. Sempre que houver riscos, será necessário gerenciá-los.  
Não podemos ignorar um risco: é preciso identificar, mapear, analisar probabilidades e impactos, e acompanhar as medidas de evolução. O risco pode desaparecer, aumentar ou exigir novas contramedidas. Por isso, é fundamental reavaliar periodicamente.

**Independente do cenário ou nível, é necessário:**

- Tratar o risco
- Identificar, analisar, liderar e controlar as atividades
- Garantir que tudo esteja sob controle

O objetivo é ``mitigar os riscos``, diminuindo a possibilidade de ocorrência e, caso ocorram, que tragam o menor impacto possível para a organização.

**Resumindo, o gerenciamento de risco envolve:**

- Planejar
- Organizar
- Liderar
- Controlar

#### ISO 27005

A norma ``ISO 27005`` fornece orientações para o gerenciamento de risco em SI, incluindo:

- Identificação
- Análise
- Avaliação
- Tratamento
- Aceitação
- Comunicação
- Monitoramento e revisão de riscos

Para a certificação ``ISO 27001``, é necessário analisar os pré-requisitos de gerenciamento de riscos, baseando-se na ``ISO 27005``, que serve como referência para a implementação desses controles.

---

### Aula 45 – Avaliação dos Riscos de SI

A primeira fase do gerenciamento de risco é a ``avaliação``, ou seja, identificar e analisar os riscos.  
Somente após essa etapa é que partimos para o gerenciamento propriamente dito, tratando e monitorando os riscos identificados.

#### Definições

**Segundo a norma ISO 27001:**

> Avaliação de risco é o processo de identificação, análise e avaliação de riscos.  
> O objetivo é esclarecer quais ameaças são relevantes para os processos operacionais e identificar os riscos associados.

A norma orienta que devemos olhar para o ambiente de TI, analisar os serviços entregues ao negócio, entender os processos primários, de suporte e estratégicos.  
É preciso avaliar todos os processos, ambientes e níveis para garantir que a organização possa seguir adiante com segurança e lucratividade.

A preocupação principal da avaliação de risco é **identificar o máximo possível de ameaças e vulnerabilidades** presentes no ambiente.

A avaliação de risco serve para garantir que as medidas de segurança sejam implementadas de forma ``rentável e oportuna``, fornecendo uma resposta eficaz às ameaças.

**Segundo o livro base:**

- Identificar ativos de informação e seu valor
- Determinar ameaças e vulnerabilidades
- Determinar o risco de que as ameaças se tornem realidade e interrompam o processo operacional
- Determinar o equilíbrio entre os custos de um incidente e os custos de uma medida de segurança

Ou seja, a avaliação de risco consiste em ``identificar, analisar e avaliar os riscos`` relacionados aos ativos da organização.

---

**Resumo:** A avaliação de riscos é fundamental para mapear ameaças e vulnerabilidades, permitindo que a empresa implemente controles de segurança de forma eficiente e alinhada ao seu contexto operacional.

---

### Aula 46 – Análise de Riscos de SI

Para realizar uma análise de riscos, o primeiro passo é ``identificar o risco``.

Durante a análise, é fundamental compreender a natureza do risco e determinar o seu nível. Para isso, podem ser aplicadas duas metodologias principais:

#### Classificações de Análise de Risco

- ``Qualitativa:`` Trabalha com a **probabilidade** de algo ocorrer e o impacto associado, geralmente utilizando escalas subjetivas (baixo, médio, alto). É útil quando não há dados numéricos precisos, baseando-se em percepções, experiências e julgamentos.

- ``Quantitativa:`` Baseia-se em **números e dados concretos** para calcular o risco. Utiliza métricas financeiras, estatísticas e valores mensuráveis para chegar a um fator determinante do risco.

---

**Resumo:**  

- **Análise qualitativa:** Probabilidade e impacto subjetivos.
- **Análise quantitativa:** Cálculos e dados objetivos.

A escolha entre análise qualitativa ou quantitativa depende do contexto, dos dados disponíveis e dos objetivos da organização ao avaliar os riscos de segurança da informação.

---

### Aula 47 – Tratamento dos Riscos de SI

Independente da análise utilizada (qualitativa ou quantitativa), ao final teremos uma lista de riscos identificados. O mais importante é aplicar o **tratamento adequado para cada tipo de risco**.

Após a análise, começamos a identificar, de cima para baixo, aqueles riscos que são mais críticos e graves. A partir desse ponto, o foco é trabalhar para resolver ou mitigar esses riscos prioritários.

Quando falamos de ``tratamento de riscos``, estamos falando de **aplicar medidas**: medidas para reduzir, minimizar ou até eliminar a ocorrência dos riscos.

A fase de tratamento só ocorre depois que você já passou pela análise, avaliou as consequências e categorizou os riscos (quantitativos e qualitativos), priorizando o que é mais crítico. A partir daí, são definidas e implementadas as medidas necessárias para garantir o menor impacto possível, caso o risco venha a se concretizar.

---

**Resumo:** O tratamento de riscos consiste em priorizar os riscos mais críticos e aplicar medidas para reduzir a probabilidade de ocorrência ou minimizar o impacto, protegendo a organização de possíveis prejuízos.

---

### Aula 48 – Medidas de SI

Medidas de segurança são os ``controles`` aplicados para garantir que um risco não seja explorado.

**Exemplo prático:**  
Na nossa residência, dormimos com portas e janelas fechadas, usamos chaves e cadeados. Essas são medidas de segurança, pois sabemos que existe a vulnerabilidade de alguém entrar na casa.

A medida de segurança sempre faz parte do **gerenciamento de risco**.  
Lembrando: primeiro fazemos a análise, depois o gerenciamento.

O tipo de medida depende do cenário.  
Por exemplo, se você mora no 50º andar de um prédio, não faz sentido se preocupar em dormir com a janela aberta. As medidas variam conforme o contexto.

As ``contramedidas`` podem ser:

- Baseadas em códigos (software)
- Configurações de hardware (cabos, dispositivos)
- Procedimentos administrativos (políticas, treinamentos)

O objetivo é ``eliminar a vulnerabilidade`` ou ``reduzir a probabilidade`` de que um agente de ameaça explore essa vulnerabilidade.

Após aplicar as medidas, o risco pode ter sua probabilidade **aumentada ou diminuída**, dependendo da eficácia das ações tomadas.

---

**Resumo:**  

Medidas de segurança são controles implementados para proteger ativos, reduzir vulnerabilidades e minimizar a probabilidade de ocorrência de riscos, sempre adaptadas ao cenári``

---

### Aula 49 – ISO/IEC 27002 como referência para tratamento de ameaças e riscos

A norma ``ISO/IEC 27002`` é utilizada como referência para definir os objetivos e controles de segurança da informação.  
Esses objetivos e controles são as ``medidas`` que devemos implementar para o tratamento dos riscos identificados.

#### Estrutura da ISO/IEC 27002

- **Objetivo de controle:** O que se espera alcançar.
- **Controle:** O que deve ser feito para atingir o objetivo.
- **Diretrizes para implementação:** Como implementar o controle.
- **Informações adicionais:** Apoio extra para a implementação do controle.

#### Exemplo – Controle de Acesso

- **Objetivo de controle:** Limitar o acesso à informação e aos recursos de processamento.
- **Controle:** Estabelecer políticas de controle de acesso, documentadas e analisadas criticamente, baseadas nos requisitos de segurança da informação e do negócio.
- **Diretriz para implementação:** Os proprietários dos ativos devem definir regras apropriadas de controle de acesso, direitos e restrições para papéis específicos, com o nível de detalhe e rigor dos controles refletindo os riscos associados.
- **Informações adicionais:** Recomenda-se que as regras sejam baseadas na premissa de que tudo é proibido, a menos que expressamente permitido, ao invés de tudo ser permitido, a menos que proibido.

A ISO/IEC 27002 apresenta ``o que implementar`` e ``onde ter cuidado``, mas não detalha ``como implementar`` cada controle.  
Para saber como aplicar na prática, é necessário buscar literaturas externas, guias técnicos ou frameworks complementares.

---

**Resumo:**  

A ISO/IEC 27002 serve como guia para definir objetivos e controles de segurança, mas a implementação prática depende de outras referências e adaptações ao contexto da organização

---

### Aula 50 – Tipos de Estratégias para Lidar com Riscos

Já vimos que o risco é composto por ameaça, vulnerabilidade, probabilidade e potencial de dano. Agora, precisamos entender **como lidar com esses riscos**. Existem quatro principais estratégias:

#### 1. Evitar

- ``Evitar`` (prevenir ou eliminar riscos):  
  Consiste em não assumir o risco ou eliminá-lo completamente do ambiente.  
  Exemplo: Deixar de realizar uma atividade que apresenta alto risco.  
  Nem sempre é possível eliminar todos os riscos, então muitas vezes só conseguimos prevenir e nos preparar para agir caso a ameaça se concretize.

#### 2. Neutralizar

- ``Neutralizar`` (reduzir ou mitigar riscos):  
  Busca diminuir o impacto ou a probabilidade do risco.  
  Para isso, aplicamos ações:
  - ``Preventivas:`` Atuam antes do risco se manifestar.  
    *Exemplo:* Instalar antivírus para evitar infecção.
  - ``Detectivas:`` Identificam o risco quando ele ocorre.  
    *Exemplo:* Monitoramento de logs para detectar invasões.
  - ``Repressivas:`` Atuam após o risco se manifestar.  
    *Exemplo:* Bloquear usuário após tentativa de acesso indevido.

#### 3. Transferir

- ``Transferir`` (terceirizar ou compartilhar o risco):  
  Consiste em passar o risco para outra parte.  
  Exemplo: Contratar um seguro para o carro. Se ocorrer um acidente, o prejuízo é coberto pela seguradora.

#### 4. Aceitar

- ``Aceitar`` (suportar ou reter o risco):  
  Significa assumir o risco, sabendo que pode ocorrer um problema e, se acontecer, a organização irá lidar com as consequências.  
  Exemplo: Decidir não investir em controles adicionais para um risco considerado baixo.

---

**Resumo das estratégias:**

- Evitar
- Neutralizar
- Transferir
- Aceitar

Cada estratégia deve ser escolhida conforme o contexto e a análise dos riscos da organização.

---

### Aula 51 – ISO/IEC 27005 como referência estratégica para lidar com ameaças e riscos

A norma **ISO/IEC 27005** é dedicada ao gerenciamento de riscos em segurança da informação, abordando controles e medidas para lidar com riscos.

#### Abordagens segundo a ISO/IEC 27005:

- **Evitar:** Decisão de não se envolver ou agir para se retirar de uma situação de risco.
- **Modificação:** Ações para reduzir a probabilidade, as consequências negativas, ou ambas, associadas ao risco.
- **Compartilhamento:** Divisão do ônus da perda ou do benefício do ganho com outra entidade.
- **Retenção:** Aceitação do ônus da perda ou do benefício do ganho associado ao risco.

Segundo a norma e o livro base, as estratégias são as mesmas, mudando apenas a nomenclatura:

- **Evitar** (evitar o risco)
- **Modificação/Neutralizar** (reduzir ou mitigar o risco)
- **Compartilhamento/Transferir** (passar o risco para outro)
- **Retenção/Aceitar** (assumir a responsabilidade pelo risco)

Essas estratégias podem ser aplicadas tanto para riscos negativos quanto positivos.

---

**Resumo:**  
A ISO/IEC 27005 orienta sobre as principais estratégias para lidar com riscos: evitar, neutralizar, transferir e aceitar, sendo possível aplicar essas abordagens conforme o contexto e o tipo de risco identificado.

---

## 💡 Considerações Finais

Essas anotações refletem o que considerei mais importante e interessante durante as aulas do curso.  
Organizei os principais conceitos e exemplos para facilitar a revisão e a fixação do conteúdo.

Vamos continuar estudando e evoluindo! 🚀

> _Última atualização: 10/07/25 por Ivan Rocha_