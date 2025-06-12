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

### a 

---
## 💡 Considerações Finais

Essas anotações refletem o que considerei mais importante e interessante durante as aulas do curso.  
Organizei os principais conceitos e exemplos para facilitar a revisão e a fixação do conteúdo.

Vamos continuar estudando e evoluindo! 🚀

> _Última atualização: 12/06/25 por Ivan Rocha_