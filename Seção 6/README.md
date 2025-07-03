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

## 💡 Considerações Finais

Essas anotações refletem o que considerei mais importante e interessante durante as aulas do curso.  
Organizei os principais conceitos e exemplos para facilitar a revisão e a fixação do conteúdo.

Vamos continuar estudando e evoluindo! 🚀

> _Última atualização: 03/07/25 por Ivan Rocha_