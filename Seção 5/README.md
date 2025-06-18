# 📒 Anotações – ISO/IEC 27001

Bem-vindo(a) às anotações da ``Seção 5`` do curso **EXIN ISO 27001: Fundamentos de Segurança da Informação**!

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

### Seção 5

- [Aula 07 - Definição de Informação](#aula-07---definição-de-informação)
- [Aula 08 - Dado e Informação](#aula-08--dado-e-informação)
- [Aula 09 - Como a Informação é Derivada](#aula-09--como-a-informação-é-derivada)
- [Aula 10 - Aplicando Contexto aos Dados](#aula-10--aplicando-contexto-aos-dados)
- [Aula 11 - Modelo DICS/DIKW](#aula-11--modelo-dics--dikw)
- [Aula 12 - Aplicação do Modelo DICS/DIKW](#aula-12--aplicação-do-modelo-dics--dikw)
- [Aula 13 - Formas de Informação](#aula-13--formas-de-informação)
- [Aula 14 – Sistema de Informação](#aula-14--sistema-de-informação)
- [Aula 15 – Tecnologia da Informação](#aula-15--tecnologia-da-informação)
- [Aula 16 – Diferença entre Sistema e Tecnologia da Informação](#aula-16--diferença-entre-sistema-e-tecnologia-da-informação)
- [Aula 17 – Valor da Informação](#aula-17--valor-da-informação)
- [Aula 18 – Quem determina o valor da informação](#aula-18--quem-determina-o-valor-da-informação)
- [Aula 19 – Informação como Ativo](#aula-19--informação-como-ativo)
- [Aula 20 – Tipos de Ativos](#aula-20--tipos-de-ativos)
- [Aula 21 – Ciclo de Vida das Informações](#aula-21--ciclo-de-vida-das-informações)
- [Aula 22 – Informação como Fator Estratégico](#aula-22--informação-como-fator-estratégico)
- [Aula 23 – Processo de Negócio](#aula-23--processo-de-negócio)
- [Aula 24 – Tipos de Processos de Negócios](#aula-24--tipos-de-processos-de-negócios)
- [Aula 25 – Valor da Informação para o Processo de Negócio de uma Organização](#aula-25--valor-da-informação-para-o-processo-de-negócio-de-uma-organização)
- [Aula 26 – Confiabilidade da Informação](#aula-26--confiabilidade-da-informação)
- [Aula 27 – O que é Segurança da Informação](#aula-27--o-que-é-segurança-da-informação)
- [Aula 28 – Em Breve](#aula-28--em-breve)

---

### Aula 07 – Definição de Informação

Nesta seção, o foco está nos seguintes tópicos:

- Informação e segurança (10% da prova)
- Conceito de informação
- Valor da informação
- Aspectos da confiabilidade

> Os demais 90% do conteúdo serão abordados em outras seções do curso.

---

#### Reflexão: O que entendemos por informação?

Antes de avançar, é importante refletir sobre o que realmente significa "informação". Mais adiante, veremos conceitos como DIKW (Dado, Informação, Conhecimento e Sabedoria).

**Minha resposta (Ivan):**

Para mim, informação é tudo. Hoje em dia, tudo pode ser considerado informação: desde uma embalagem de bala até um computador quântico. A informação está presente em todos os lugares – na sua mesa, no bolso, no carro, no avião, no transporte público. Até mesmo nossas informações pessoais estão disponíveis nas redes. Informação é tudo que podemos ler, ver, falar, sentir, etc.

Para algumas pessoas, informação significa apenas uma pequena quantidade isolada de dados.  
Para outras, é algo que possui significado.  
Para outros ainda, pode ser informações armazenadas em um computador ou banco de dados.

> No entanto, informação é tudo aquilo que tem significado, tudo que resulta da integração de dados e que permite a tomada de decisões ou ações.

**Exemplo prático:**  
Imagine pedir informações a um idoso na rua sobre onde fica um hospital. Ele responde: "Fica a quatro quadras daqui, na quarta quadra vire à direita e depois à esquerda, estará no número tal, na rua tal, em frente a um mercado, com a fachada azul e uma placa escrita Hospital X."  
Nesse exemplo, recebemos vários dados: nomes, números, endereços, características, etc.

---

**Definição segundo o livro base (Fundamentos da Segurança da Informação):**  
> “A informação é o dado ou conjunto de dados que tem significado em algum contexto para o receptor.”

Ou seja, informação pode ser falada, processada, armazenada – não importa o formato. Tudo aquilo que possui um contexto e significado é considerado informação.

---

### Aula 08 – Dado e Informação

Nesta aula, vamos correlacionar os conceitos de dado e informação.

O **dado** é tudo aquilo que, de forma isolada, não faz sentido ou não transmite significado completo. É um elemento bruto, sem contexto, que sozinho não permite tomar decisões.

**Exemplo prático:**  
Imagine que você para uma pessoa na rua e pergunta onde fica o hospital. Ela responde apenas: "Fica em frente a um mercado."  
Mas qual mercado? Essa resposta, por si só, é apenas um dado – está solta, sem contexto suficiente para ser útil.

Outro exemplo: você encontra uma sequência de números. Se essa sequência estiver sozinha, é apenas um dado. Agora, se ela estiver junto a uma carteira com cartões de crédito, você pode deduzir que se trata de uma senha.  
Nesse caso, o dado passa a fazer parte de uma informação quando está inserido em um contexto.

- **Dado:** Fato isolado, sem contexto. Não permite tomar decisões de forma segura.
- **Informação:** Conjunto de dados relacionados, com contexto. Permite tomar decisões ou fazer deduções.

---

De acordo com a ITIL,  
> Informação é a compreensão dos relacionamentos entre dados e responde a uma das quatro perguntas:

- Quem?
- O quê?
- Quando?
- Onde?

Ou seja, informação é aquilo que responde a pelo menos uma dessas perguntas, trazendo significado e utilidade aos dados.

---

### Aula 09 – Como a Informação é Derivada

De onde surge a informação?

A informação é derivada a partir de dados que, quando organizados e contextualizados, passam a ter significado e utilidade.

**Exemplo prático:**  
Imagine que seu gestor de TI pergunta quantos chamados foram abertos nesta semana. Para responder, você precisa buscar essa informação com base nos dados isolados que estão armazenados em algum sistema ou planilha.

Ao analisar esses dados, você pode informar ao gestor:  
"Com base nos números da última semana, foram abertos 30 chamados. Destes, o setor A, o setor B e o setor C estiveram envolvidos. Os chamados trataram de diferentes casos, como instalação de software não homologado, validação de uma extensão, entre outros."

Neste exemplo, a resposta fornecida ao gestor é uma **informação** construída a partir de diversos **dados** (quantidade, setores, tipos de chamados, etc.) que estavam armazenados. Se você tivesse apenas um código solto, sem data, nome ou descrição, isso seria apenas um dado isolado, sem contexto.

**Resumo:**  
Para obter uma informação, é necessário partir de dados brutos e ir agregando contexto e significado, até que esses dados, juntos, formem uma informação útil e compreensível.

---

### Aula 10 – Aplicando Contexto aos Dados

Atualmente, vivemos em um mundo digitalizado, onde quase tudo é processado na palma da mão: celulares, computadores, notebooks, tablets e até relógios inteligentes conectados aos nossos dispositivos. É comum pensarmos que o processamento de dados está restrito ao ambiente de TI, mas o conceito vai além.

Um exemplo fora do universo digital é uma delegacia no interior de uma cidade, onde todas as anotações ainda são feitas em papel. O tradicional livro de ocorrências contém tanto dados quanto informações.

**Exemplo prático:**  
- A **data** registrada em um boletim de ocorrência é um dado isolado.  
- Já a **descrição** do ocorrido, detalhando o que aconteceu, transforma esse dado em informação ao dar contexto:  
  "Na data X, ocorreu um assalto na rua Y, onde determinado pertence foi levado, totalizando um prejuízo de Z reais."

O mesmo raciocínio se aplica à área de TI. Imagine um banco de dados com datas de colaboradores. Se você gerar um relatório apenas com datas, elas não terão significado – serão apenas dados soltos. Agora, se essas datas estiverem associadas aos respectivos colaboradores e acompanhadas de uma descrição, como "Colaborador contratado em X" ou "Colaborador desligado em Y", aí sim temos uma informação, pois há contexto e significado.

**Resumo:**  
O contexto é fundamental para transformar dados em informação. Sem contexto, temos apenas fatos isolados; com contexto, os dados ganham significado e utilidade.

---

### Aula 11 – Modelo DICS / DIKW

O modelo DICS (ou DIKW, em inglês) representa as etapas de evolução da informação: **Dados, Informação, Conhecimento e Sabedoria**.

Até agora, abordamos apenas os conceitos de dados e informação. Agora, vamos analisar como esses elementos evoluem até se tornarem conhecimento e, por fim, sabedoria, seguindo as boas práticas do mercado.

**Como funciona o modelo DICS/DIKW:**

1. ``Dados:`` É o estado mais bruto, a base de todo o processo. Dados são fatos isolados, sem contexto ou significado.

2. ``Informação:`` Quando os dados são organizados e contextualizados, passam a responder perguntas como "quem?", "o quê?", "quando?" e "onde?". Assim, os dados ganham significado e se tornam informação.

3. ``Conhecimento:`` A partir da informação, surge o conhecimento, que responde à pergunta "como?". É o entendimento de como usar a informação para realizar tarefas ou tomar decisões.

4. ``Sabedoria:`` O estágio mais avançado, que responde à pergunta "por quê?". Sabedoria é a capacidade de aplicar o conhecimento de forma crítica, estratégica e ética, compreendendo as consequências e o propósito das ações.

**Resumo das etapas:**

- ``Etapa 1:`` Dados brutos  
- ``Etapa 2:`` Informação (quem, o quê, quando, onde)  
- ``Etapa 3:`` Conhecimento (como)  
- ``Etapa 4:`` Sabedoria (por quê)

Esse modelo ajuda a entender como evoluímos de simples dados até a tomada de decisões inteligentes e fundamentadas.

---

### Aula 12 – Aplicação do Modelo DICS / DIKW

Um conceito fundamental no processo de gestão do conhecimento é que só é possível alcançar o verdadeiro conhecimento após trabalhar os dados, inseri-los em uma plataforma ou sistema e transformá-los em informações. Informações são conjuntos de dados organizados que já permitem a tomada de decisões.

Vamos entender como percorrer o caminho dos dados até a sabedoria:

1. **Capturar todos os dados necessários:** Coletar dados relevantes para o contexto do negócio ou processo.

2. **Analisar, sintetizar e transformar em informação:** Organizar e contextualizar os dados, tornando-os úteis e compreensíveis.

3. **Identificar os dados relevantes:** Focar na coleta e análise dos dados que realmente agregam valor, otimizando recursos.

4. **Manter a integridade dos dados:** Garantir que os dados sejam precisos, completos e confiáveis durante todo o processo.

5. **Arquivar e eliminar dados desnecessários:** Gerenciar o ciclo de vida dos dados, equilibrando disponibilidade e uso eficiente dos recursos.

**Resumo do modelo:**

- ``D`` – Dados  
- ``I`` – Informação  
- ``C`` – Conhecimento  
- ``S`` – Sabedoria  

**Fluxo:**  
Dados → Informação → Conhecimento → Sabedoria

Esse processo garante que a organização evolua de simples coleta de dados até a tomada de decisões estratégicas e fundamentadas.

---

### Aula 13 – Formas de Informação

Nesta aula, vamos explorar as diferentes formas que a informação pode assumir e como ela pode ser transmitida, armazenada e protegida.

Como já vimos, a informação é o resultado da soma e organização dos dados. Ela pode ser transmitida e armazenada de diversas maneiras:

**Formas de transmissão:**
- **Meios físicos:** Envio de cartas pelos correios, documentos impressos, etc.
- **Meios eletrônicos:** E-mails, mensagens instantâneas, sistemas de informação, etc.
- **Forma verbal:** Comunicação oral, reuniões, telefonemas, etc.

**Formas de armazenamento eletrônico:**
- Discos ópticos (CD, DVD)
- Bancos de dados
- Planilhas eletrônicas
- Disquetes
- Pen drives
- Servidores e nuvens

**Informação em mídias visuais:**
- Filmes e fotos, como imagens captadas por câmeras de segurança.  
  Exemplo: Em um caso de assalto, as imagens gravadas podem ser usadas pela polícia para investigação, sendo uma informação armazenada e transmitida por meio eletrônico.

Cada tipo de informação exige medidas específicas de controle e proteção.

**Exemplo prático:**  
Ao enviar uma carta pelos correios, espera-se que ela não seja violada ou lida por pessoas não autorizadas. Para garantir a confidencialidade, podem ser adotadas medidas como criptografia (mesmo em comunicações físicas, como códigos ou linguagens secretas, por exemplo, o código Morse).

O objetivo é sempre manter as informações seguras e acessíveis apenas a pessoas autorizadas.  
Por exemplo, ao fornecer seu CPF em uma loja, espera-se que essa informação seja armazenada de forma sigilosa e não fique disponível ao público.

**Resumo:**  
A informação pode ser transmitida, armazenada e apresentada de várias formas, e cada uma delas requer cuidados específicos para garantir sua segurança, confidencialidade e integridade.

---

### Aula 14 – Sistema de Informação

O sistema de informação é formado pela junção de quatro componentes essenciais:

- ``Meios``
- ``Procedimentos``
- ``Regras``
- ``Pessoas``

Quando esses quatro elementos trabalham juntos, temos um verdadeiro sistema de informação.

Esses componentes garantem que as informações estejam disponíveis e acessíveis para os processos de negócio da organização, promovendo a integração e o suporte necessário para a tomada de decisões e o funcionamento eficiente da empresa.

---

### Aula 15 – Tecnologia da Informação

Em alguns casos, ainda encontramos sistemas de informação analógicos ou tradicionais, como o bom e velho papel e caneta. No entanto, atualmente, a tecnologia da informação (TI) predomina nas empresas, trazendo modernização e agilidade para os processos.

Hoje, é raro encontrar organizações que utilizam apenas métodos tradicionais. A TI está presente em praticamente todos os ambientes corporativos, sendo responsável por processar, armazenar e coletar dados de forma rápida e eficiente. Isso permite transformar dados em informação, gerar conhecimento e aplicar a sabedoria em poucos minutos ou até segundos.

**Exemplos de tecnologias da informação:**
- Celulares e smartphones
- Aplicativos e sites
- Computadores e notebooks
- Relógios inteligentes
- Softwares corporativos
- Servidores
- Inteligência Artificial (IA)

Essas tecnologias são utilizadas para coletar, armazenar e processar dados.

> Tudo que segue esses três passos – coletar, armazenar e processar dados – pode ser considerado tecnologia da informação.

**Meios de armazenamento de dados:**
- Pen drives
- Disquetes
- Fitas magnéticas (fitas cassete)
- Data centers
- Equipamentos próprios com HDs (celulares, computadores, notebooks)
- CDs e DVDs
- SSDs
- Storages corporativos
- Servidores

A tecnologia da informação é fundamental para garantir a eficiência, segurança e disponibilidade das informações nas organizações modernas.

---

### Aula 16 – Diferença entre Sistema e Tecnologia da Informação

O conceito é simples:

- ``Sistema de Informação:`` Tem como finalidade a transferência e o processamento de informações por meio de um conjunto de elementos integrados. Sempre que conseguimos transferir uma informação de um lado para o outro, já temos um sistema de informação.

  **Exemplos:**
  - Arquivos de armário (documentos físicos sendo organizados e acessados)
  - Telefone (uma ligação entre duas pessoas, transmitindo informações de um lado para o outro)
  - Impressora (ao enviar um documento para impressão, a informação é transmitida do computador para a impressora)

- ``Tecnologia da Informação:`` Refere-se às ferramentas, equipamentos e recursos tecnológicos utilizados para coletar, armazenar, processar e transmitir dados e informações (como computadores, softwares, servidores, redes, etc.).

**Resumo:** A tecnologia da informação fornece os meios e recursos tecnológicos, enquanto o sistema de informação é o conjunto de processos e elementos (tecnológicos ou não) que garantem a transferência, processamento e uso das informações.

---

### Aula 17 – Valor da Informação

A informação possui valor diferente para cada parte interessada, dependendo do contexto e do interesse de quem a recebe.

**Exemplo prático:** Se você fala sobre futebol para alguém que não gosta ou não acompanha o esporte, as informações transmitidas terão pouco ou nenhum valor para essa pessoa. Por outro lado, se você compartilha informações sobre futebol com alguém que é fã do esporte, essas informações passam a ter grande importância e valor.

**Valor da informação no contexto corporativo:** No ambiente empresarial, a informação é fundamental e pode ser considerada um ativo estratégico. Por exemplo, o registro de uma venda tem valor para a empresa, para o cliente e para o funcionário envolvido. Informações como para quem foi vendido, quando, preço, assinatura da nota fiscal, valor cobrado, data de vencimento, entre outros detalhes, são essenciais para o funcionamento e controle dos processos.

- ``Informação como ativo:`` Para a empresa, a informação armazenada é um ativo valioso, pois sustenta os processos operacionais, auxilia na tomada de decisões e pode representar vantagem competitiva.

- ``Informação como fator de produção:`` Assim como máquinas, pessoas e dinheiro, a informação é um recurso indispensável para a produção e operação das organizações.

**Resumo:** A informação ganha valor conforme sua utilidade, relevância e impacto para cada parte interessada. No contexto corporativo, ela é tratada como um ativo estratégico, essencial para o sucesso e a continuidade dos negócios.

---

### Aula 18 – Quem determina o valor da informação

É importante entender que quem determina o valor da informação é sempre o receptor final ou destinatário.

**Exemplo prático:** Você é um vendedor e insere a informação de uma venda no sistema. Essa informação será útil para o dono da loja, pois permitirá saber quanto foi vendido, quanto rendeu ou até mesmo identificar prejuízos. Ou seja, o valor da informação depende de quem a recebe e de como ela será utilizada.

Além disso, as informações precisam estar sempre contextualizadas em relação aos processos de negócio.  
Processos de negócio são as etapas e atividades que fazem a empresa funcionar e existir, sendo a razão de ser da organização.

**Resumo:** O valor da informação é definido pelo destinatário e pelo contexto em que ela é aplicada dentro dos processos de negócio.

---

### Aula 19 – Informação como Ativo

Com base na ISO 27002:2013, em um mundo interconectado, a informação e todos os processos relacionados, sistemas, redes e pessoas envolvidas em suas operações são considerados ativos importantes para a organização. Assim como outros ativos, a informação tem valor para o negócio e, por isso, requer proteção contra diversos riscos.

``O que é um ativo?`` Um ativo é qualquer coisa que pertence a um indivíduo ou organização e que possui valor. Pode ser algo utilizado para produzir bens ou serviços, ou ainda algo que pode ser vendido para gerar receita.

No contexto empresarial, por exemplo, uma pessoa que detém o conhecimento de um processo essencial dentro da empresa pode ser considerada um ativo, pois seu conhecimento é fundamental para o funcionamento do negócio. Da mesma forma, informações, procedimentos e instruções sobre como realizar determinado processo também são ativos, pois agregam valor à organização.

``Ativo que gera receita:`` Quando falamos em receita, estamos nos referindo ao dinheiro e aos lucros que a empresa pode obter a partir do uso, venda ou proteção adequada desses ativos.

**Resumo:** A informação é um ativo estratégico, pois pode gerar valor, receita e vantagem competitiva para a organização. Por isso, deve ser protegida com o mesmo cuidado dedicado a outros ativos importantes do negócio.

---

### Aula 20 – Tipos de Ativos

Existem dois tipos principais de ativos: ``ativos tangíveis`` e ``ativos intangíveis``.

#### Ativos Tangíveis

São aqueles que possuem um valor financeiro facilmente identificado e mensurável. Ou seja, é possível saber exatamente quanto foi pago ou investido naquele bem.

**Exemplos de ativos tangíveis:**
- Prédios
- Estoques
- Computadores
- Pessoas (força de trabalho)
- Casas
- Motos
- Carros

Esses ativos são chamados de tangíveis porque a empresa ou o indivíduo sabe o valor financeiro de cada um, pois foi pago ou investido diretamente.

#### Ativos Intangíveis

São aqueles cujo valor não pode ser mensurado de forma exata, sendo estimado de acordo com sua importância ou impacto para a organização.

**Exemplos de ativos intangíveis:**
- Informação
- Reputação
- Marca
- Conhecimento dos funcionários

Por exemplo, empresas como Amazon, Microsoft ou Google não valem bilhões ou trilhões de dólares apenas pelos seus computadores, escritórios ou pessoas, mas sim pelos seus ativos intangíveis, como reputação e imagem no mercado.

A informação é um ativo intangível, pois gera valor para a organização, mesmo que não seja possível calcular seu valor exato.

A empresa sabe o valor tangível que paga para um funcionário, mas não consegue mensurar o valor intangível do conhecimento que esse funcionário leva consigo. Por isso, o conhecimento dos colaboradores é um ativo estratégico: quando um funcionário encerra o expediente, a empresa espera que ele retorne, pois só ele detém o conhecimento necessário para fazer o negócio funcionar.

**Resumo:**  
- ``Ativos tangíveis:`` valor financeiro claro e mensurável.
- ``Ativos intangíveis:`` valor estimado, muitas vezes relacionado à informação, reputação e conhecimento, fundamentais para o sucesso e a continuidade da organização.

---

### Aula 21 – Ciclo de Vida das Informações

Na vida, tudo tem início, meio e fim: uma carreira, uma formação, a própria vida. Com as informações não é diferente – elas também possuem um ciclo de vida.

Segundo a norma ISO 27002, a informação tem um ciclo natural:  
**criação/origem → armazenamento → processamento/uso → transmissão/compartilhamento → arquivamento → destruição/obsolescência**

A própria norma reconhece que a informação pode se tornar obsoleta. Nesse caso, podemos armazená-la para consulta futura (histórico) ou simplesmente destruí-la.

#### Controles e Medidas

De acordo com a ISO 27002, a informação deve passar por etapas bem definidas:

1. **Criação:** Surgimento da informação, seja por meios analógicos ou digitais.
2. **Armazenamento:** Guardar a informação em meios físicos ou digitais (TI).
3. **Uso:** Utilização da informação como ativo intangível, gerando valor ou recursos.
4. **Compartilhamento:** A informação pode ser compartilhada, gerando conhecimento e sabedoria para outras pessoas ou para a organização (relacionando ao modelo DICS/DIKW).
5. **Arquivamento:** Após o uso, a informação pode ser arquivada para consultas futuras, mesmo que não seja mais tão útil.
6. **Destruição:** Quando a informação se torna totalmente obsoleta, pode ser destruída para evitar riscos desnecessários.

**Exemplo:**  
Você compra um livro para estudar para uma certificação. Se a certificação deixa de existir, o livro se torna obsoleto, mas pode ser guardado para consulta ou descartado.

Outro exemplo é a receita secreta da Coca-Cola. Em vez de patentear (o que limitaria a proteção a 10 anos), a empresa mantém a fórmula em segredo absoluto, prolongando o ciclo de vida da informação indefinidamente e evitando o compartilhamento.

Cada estágio do ciclo de vida da informação envolve riscos. Por isso, é fundamental aplicar controles e medidas de segurança para minimizar esses riscos e proteger a informação enquanto ela for um ativo valioso para a organização.

**Resumo do ciclo de vida da informação:**  
Criada → Armazenada → Usada → Compartilhada → Arquivada → Destruída

Cada etapa exige cuidados específicos para garantir a segurança, confidencialidade e integridade das informações.

---

### Aula 22 – Informação como Fator Estratégico

Toda empresa precisa de recursos, ativos e produtos para gerar bens ou serviços e entregá-los ao mercado.

Segundo o livro base:  
``Fator de produção`` é um recurso necessário para gerar produtos ou serviços.

Dentro desse conceito, temos:
- Capital
- Capital financeiro
- Capital intelectual
- Mão de obra
- Matéria-prima

Atualmente, vivemos na era digital, onde a produção e o uso de informações são essenciais. Todas as organizações dependem de informações para sobreviver e competir no mercado. Por isso, a informação passou a ser considerada um fator de produção fundamental.

Se a empresa não fizer uso adequado da informação, não conseguirá produzir bens ou recursos para oferecer ao mercado.

**Exemplo:**  
Uma empresa que deseja entrar no ramo de panelas precisa de informações como:
- Como fabricar uma panela
- Quem são os concorrentes
- Preços de venda praticados no mercado
- Despesas envolvidas
- Design inovador (para se diferenciar)
- Entre outros dados

A informação é essencial para a tomada de decisões estratégicas.

**Resumo:**  
O bem mais importante que uma empresa possui são suas informações. Elas são fundamentais para a sobrevivência, inovação e sucesso no mercado.

---

### Aula 23 – Processo de Negócio

No nosso dia a dia, estamos acostumados a resolver vários processos, muitos dos quais passam despercebidos. A informação faz parte de um processo de negócio, pois toda empresa possui uma sequência de atividades e saídas que resultam na produção de um bem ou serviço para o mercado.

**Exemplo: Fábrica de veículos**

- ``Entradas:``  
  - Pedido de compra do veículo
  - Solicitação de peças aos fornecedores (pneu, motor, vidro, etc.)

- ``Atividades:``  
  - Montagem do veículo, integração das peças e componentes

- ``Saída:``  
  - Veículo pronto para entrega ao cliente

A saída é a transformação das entradas, após a realização das atividades, em um bem final.

Toda organização precisa de processos de negócio, pois são eles que fazem a empresa operar e funcionar.

**Definição:** Processo de negócio é um processo estruturado que a empresa realiza para produzir algo ou entregar algum serviço

---

### Aula 24 – Tipos de Processos de Negócios

Em uma organização, existem diferentes níveis hierárquicos: diretoria/donos (nível estratégico), gerência/intermediários (nível de suporte), coordenação e, na base, o pessoal operacional.

O ciclo de um processo de negócio geralmente segue:  
``Entrada do processo → Atividade 1 → Atividade 2 → Atividade 3 → Saída do processo``

Os processos de negócio podem ser classificados em três tipos principais:

#### 1. Processos Primários (Operacionais)
São os processos que fazem parte da cadeia de valor e geram receita para a organização. Estão ligados diretamente à produção do produto final ou à entrega do serviço ao cliente.

- **Exemplo:** Produção de veículos em uma fábrica, atendimento ao cliente, vendas.

#### 2. Processos Estratégicos
Envolvem o nível mais alto da organização (diretoria), responsável por definir estratégias, automatizar processos, reduzir custos, aumentar a produção e expandir o alcance da empresa.

- **Exemplo:** Decidir como aumentar a produção de carros para atender uma região maior, definir novas metas de mercado.

#### 3. Processos de Suporte
São processos que dão suporte aos processos primários e estratégicos, geralmente realizados pela gerência e departamentos de apoio (RH, TI, financeiro, etc.).

- **Exemplo:** Gerência solicitando ao RH a contratação de novos funcionários para atender uma demanda da diretoria.

#### Pirâmide dos Processos de Negócio

1. ``Diretoria`` — Estratégico  
2. ``Gerência`` — Suporte  
3. ``Equipes Técnicas/Operacionais`` — Primário/Operacional

**Resumo:**  
- ``Primário:`` Produção do produto final, geração de receita (nível operacional)
- ``Estratégico:`` Definição de metas e estratégias (nível diretoria)
- ``Suporte:`` Apoio aos demais processos, garantindo que a organização alcance seus objetivos (nível

---

### Aula 25 – Valor da Informação para o Processo de Negócio de uma Organização

Nesta aula, vamos analisar o valor da informação considerando os três tipos de processos de negócios:

- ``Estratégico``
- ``Suporte``
- ``Primário``

Em cada um desses processos, a informação é produzida, passa por seu ciclo de vida e precisa de controles e medidas para garantir sua confiabilidade e segurança.

#### Determinando o valor da informação

Segundo o livro base, um dos métodos para determinar o valor da informação é analisar o papel que ela desempenha nos diferentes processos de negócio. É fundamental identificar se a informação está em um processo primário, de suporte ou estratégico, pois isso influencia diretamente nos controles de segurança que devem ser aplicados.

#### Exemplo prático: Montadora de carros

Se você trabalha na montagem de motores, a informação sobre o passo a passo do processo precisa ser ``confiável``. Isso garante que, ao seguir as instruções, o motor será montado corretamente, sem retrabalho, desperdício ou acidentes. Aqui, a informação deve ser:

- ``Disponível:`` Para que todos os funcionários possam acessar e executar as tarefas corretamente, inclusive novos colaboradores em treinamento.
- ``Íntegra:`` Para evitar alterações indevidas, como trocar o tipo de peça, o que pode causar falhas e prejuízos.
- ``Confidencial:`` Nem sempre é necessária nesse contexto, pois a informação precisa estar acessível aos operadores.

#### Exemplo prático: Estratégia empresarial

No nível estratégico, como um plano de expansão para novos produtos, a informação precisa ser ``confidencial``. O vazamento desse tipo de informação pode comprometer a competitividade da empresa. Portanto, o controle de acesso deve ser restrito à diretoria e pessoas envolvidas.

#### Princípios de Segurança da Informação

Os três pilares fundamentais são:

- ``Confidencialidade:`` Garantir que apenas pessoas autorizadas tenham acesso à informação.
- ``Integridade:`` Assegurar que a informação não seja alterada de forma indevida.
- ``Disponibilidade:`` Garantir que a informação esteja acessível quando necessário.

Cada processo exige controles específicos de acordo com o seu nível e importância para o negócio. Por exemplo:

- Informações de RH devem ser restritas ao setor responsável.
- Manuais de produtos devem ser íntegros e claros para o cliente.
- Planos estratégicos devem ser confidenciais.

**Resumo:**  
O valor da informação para o processo de negócio depende do contexto em que ela está inserida e dos controles de segurança aplicados. É fundamental garantir que cada informação tenha o nível adequado de confidencialidade, integridade e disponibilidade, conforme o tipo de processo e a necessidade

---

### Aula 26 – Confiabilidade da Informação

Quando falamos de confiabilidade, muitas pessoas pensam que é um pilar separado dentro dos princípios da Segurança da Informação (SI). Na verdade, confiabilidade está diretamente relacionada aos três pilares clássicos da SI, conhecidos como CID:

- ``C`` – Confidencialidade
- ``I`` – Integridade
- ``D`` – Disponibilidade

Para que uma informação seja considerada confiável, é necessário que esses três princípios sejam aplicados de forma adequada.

#### Exemplo prático: Hospital

Imagine que você é gerente de TI em um hospital, responsável pelo sistema que armazena informações dos pacientes, incluindo o controle de medicação. Se você não garante que apenas pessoas autorizadas (como enfermeiras específicas) tenham acesso a essas informações, está comprometendo a confidencialidade.

Se alguém não autorizado altera o medicamento de um paciente, a integridade da informação é quebrada, colocando o tratamento em risco.

No caso de pacientes importantes (presidente, celebridades, etc.), se a mídia tem acesso e divulga informações confidenciais sobre o tratamento, novamente a confidencialidade é violada.

#### Resumindo

Quando falamos de confiabilidade da informação, estamos falando da aplicação dos três pilares do CID. Segurança da informação é garantir a confiabilidade da informação, e isso só é possível por meio da confidencialidade, integridade e disponibilidade.

> **Observação:** Existem outros princípios além do CID, que serão abordados mais adiante no curso.

---

### Aula 27 – O que é Segurança da Informação

Nesta aula, vamos entender o que é segurança da informação, tanto pela visão das boas práticas do livro base quanto pela definição das normas ISO 27001/27002.

#### Definição segundo o livro base

Segurança da informação envolve a definição, implementação, manutenção e avaliação de um sistema coerente de medidas que garantam a ``disponibilidade``, ``integridade`` e ``confidencialidade`` das informações.

Ou seja, segurança da informação é garantir, por meio de controles, processos, regras e políticas, que a informação, durante todo o seu ciclo de vida, esteja protegida sob a tríade CID (Confidencialidade, Integridade e Disponibilidade).  
Isso vale tanto para informações em papel quanto digitais.

Essas medidas podem ser implementadas por meio de um SGSI (Sistema de Gestão de Segurança da Informação), que reúne todos os controles necessários para garantir a certificação da empresa e a melhoria contínua dos processos de segurança.

#### Definição segundo a ISO 27001/27002

De acordo com as normas, segurança da informação é:

> **Preservação da confidencialidade, integridade e disponibilidade da informação; além de outras propriedades que também podem estar envolvidas.**

Além da tríade CID, a norma inclui outros princípios importantes:

- ``Autenticidade``
- ``Responsabilidade``
- ``Não repúdio``

#### Exemplos práticos

Hoje, bancos exigem biometria (digital ou palma da mão) para autorizar transações.  
Ao usar a biometria para uma transferência bancária, você garante:

- ``Autenticidade:`` É realmente você realizando a operação.
- ``Responsabilidade:`` Você assume que está fazendo aquela transação.
- ``Não repúdio:`` Não é possível negar posteriormente que foi você quem realizou a operação, pois a biometria comprova a autoria.

> **Observação:**  
> Com o avanço dessas tecnologias, em casos de assalto ou sequestro, pode ser impossível recorrer ou pedir reembolso, pois a biometria prova que foi o titular da conta quem realizou a transação. Isso levanta discussões e críticas, mas é um ponto importante a ser considerado.

**Resumo:**  
Segurança da informação é garantir, por meio de controles e políticas, que a informação seja protegida em todos os seus aspectos, principalmente confidencialidade, integridade, disponibilidade, autenticidade, responsabilidade e não-repúdio.

---

### Aula 28 – Em Breve

---

## 💡 Considerações Finais

Essas anotações refletem o que considerei mais importante e interessante durante as aulas do curso.  
Organizei os principais conceitos e exemplos para facilitar a revisão e a fixação do conteúdo.

Vamos continuar estudando e evoluindo! 🚀

> _Última atualização: 18/06/25 por Ivan Rocha_