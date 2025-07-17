# 📒 Anotações – ISO/IEC 27001

Bem-vindo(a) às anotações da ``Seção 7`` do curso **EXIN ISO 27001: Fundamentos de Segurança da Informação**!

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

### Seção 7

- [Aula 52 - Visão geral da seção](#aula-52---visão-geral-da-seção)
- [Aula 53 - O que é uma política de SI](#aula-53---o-que-é-uma-política-de-si)
- [Aula 54 - Tipos de políticas de SI](#aula-54---tipos-de-políticas-de-si)
- [Aula 55 - Criação de uma política de SI](#aula-55---criação-de-uma-política-de-si)
- [Aula 56 - Política de SI segundo a ISO/IEC 27002](#aula-56---política-de-si-segundo-a-isoiec-27002)
- [Aula 57 - Revisões das políticas de segurança da informação](#aula-57---revisões-das-políticas-de-segurança-da-informação)
- [Aula 58 - Código de conduta](#aula-58---código-de-conduta)
- [Aula 59 - Gerenciamento de ativos](#aula-59---gerenciamento-de-ativos)
- [Aula 60 - Papéis e responsabilidades](#aula-60---papéis-e-responsabilidades)
- [Aula 61 - em breve]()
- [Aula 62 - em breve]()
- [Aula 63 - em breve]()
- [Aula 64 - em breve]()
- [Aula 65 - em breve]()

---

### Aula 52 - Visão geral da seção

Nesta seção, vamos abordar a ``abordagem organizacional`` dentro do contexto da ISO/IEC 27001.

Aqui, trataremos dos outros 10% do exame, que correspondem a cerca de 4 questões na prova.

Os principais temas desta seção são:

- **Política de segurança e organização de segurança**
- **Componentes da organização de segurança**
- **Gerenciamento de incidentes**

Lembre-se: apesar de representar uma parte menor da prova, esses tópicos são fundamentais para entender como a segurança da informação é estruturada e mantida dentro de uma organização.

---

### Aula 53 - O que é uma política de SI

As políticas fazem parte da ``abordagem organizacional``. A empresa cria políticas para evitar, mitigar ou neutralizar riscos.

Para criar uma política, é necessário entender o risco, sua composição e decidir se ele deve ser evitado, neutralizado, transferido ou aceito. Em último caso, aceita-se o risco, mas normalmente busca-se neutralizá-lo antes.

``Política`` é um documento formal, que representa um compromisso entre colaboradores, liderança e diretoria para respeitar as regras estabelecidas.

#### Bases para criar uma política de SI:

- ``Regulamentos:`` Mais detalhados que as políticas e obrigatórios.  
  *Exemplo:* Regulamento interno de uso de recursos de TI.

- ``Procedimentos:`` Detalham as medidas específicas a serem tomadas.  
  *Exemplo:* Procedimento para solicitação de acesso a sistemas.

- ``Diretrizes:`` Servem como referência e consulta.  
  *Exemplo:* Diretriz para uso seguro de senhas.

Para criar políticas, há dois caminhos:

- Criar políticas sem um sistema de SI, apenas com base nas necessidades da empresa.
- Criar políticas como pré-requisito para a certificação ISO 27001 (neste caso, é obrigatório).

É importante consultar a ``ISO 27001`` para conhecer os pré-requisitos de certificação e a ``ISO 27002`` para orientações sobre como elaborar essas políticas.

---

### Aula 54 - Tipos de políticas de SI

Nesta aula, vamos detalhar os tipos de políticas de segurança da informação (SI).

Se cair uma questão sobre quem deve ter acesso às políticas de informação, a resposta é: ``todos``. A política precisa ser aplicada a todas as pessoas que trabalham com aquela informação, independentemente da área de atuação. A tríade ``CID`` (Confidencialidade, Integridade e Disponibilidade) deve ser garantida para toda informação.

**Segundo o livro base:**  
Política de SI é um documento que registra os princípios e diretrizes de segurança adotados pela organização, a serem observados por todos os integrantes e colaboradores, e aplicados a todos os sistemas de informação e processos corporativos.

Todos que acessam serviços, aplicações ou informações precisam conhecer a política.

#### Como a política de SI deve ser escrita:

- Deve ser um resumo de fatos-chave.
- Precisa ser específica para cada assunto (ex: política de acesso à internet, política de dados, política de cloud, etc).
- Para cada política, devem ser criadas diretrizes e padrões, deixando claros os limites, obrigações e deveres dos envolvidos.

A política **não deve ficar restrita à TI**. A ISO 27001 é aplicada a todas as áreas da empresa.

#### Estrutura de uma política de SI

- Definição de segurança da informação e sua importância
- Declaração do comprometimento da alta administração com a PSI
- Objetivos de segurança da organização
- Definição de responsabilidades gerais na gestão de SI
- Orientação sobre análise e gerenciamento de riscos
- Princípios de conformidade dos sistemas com a PSI
- Padrões mínimos de qualidade dos sistemas
- Princípios de supervisão constante das tentativas de violação
- Consequências de violação das normas estabelecidas
- Princípios de gestão da continuidade do negócio
- Plano de treinamento em segurança da informação

Ao criar uma política, é importante garantir que todos que precisam dela saibam de sua existência e tenham acesso ao documento.

**Resumo:** Política de SI é como uma lei interna da empresa. Deve ser clara, específica, acessível a todos e aplicada a qualquer pessoa que tenha contato com informações ou sistemas da organização.

---

### Aula 55 - Criação de uma política de SI

Como deve ser uma política de Segurança da Informação?

- ``Linguagem de negócio:``  
  A política deve ser redigida em linguagem clara, acessível e alinhada aos requisitos do negócio, evitando termos excessivamente técnicos.

- ``Alinhamento com legislações:``  
  Sempre que necessário, correlacione a política com leis ou normas externas relevantes (ex: LGPD, Marco Civil da Internet).

- ``Aprovação da alta direção:``  
  Após ser redigida, a política deve ser submetida à aprovação da diretoria ou conselho da empresa. É fundamental que a alta gestão esteja ciente e dê o aval para sua aplicação.

- ``Divulgação:``  
  A política deve ser publicada e comunicada a todos os funcionários e partes externas relevantes.  
  Exemplos de divulgação:
  - Folhetos entregues aos colaboradores
  - Publicação na intranet ou rede interna da empresa
  - Comunicados em murais ou áreas comuns
  - Treinamentos e reuniões de conscientização

- ``Treinamento:``  
  Todos que terão acesso à informação devem ser treinados sobre o conteúdo da política, entendendo claramente o que podem ou não fazer.

**Resumo:**  
A criação de uma política de SI envolve: 

- Redigir em linguagem de negócio
- Alinhar com legislações externas  
- Aprovação da alta direção  
- Divulgação ampla e acessível  
- Treinamento dos envolvidos

O importante é garantir que todos conheçam, entendam e sigam a política, utilizando os meios de comunicação mais adequados para o público-alvo.

---

### Aula 56 - Política de SI segundo a ISO/IEC 27002

Se você consultar a norma ``ISO/IEC 27001``, verá que o item 5 trata das políticas de segurança da informação, mais especificamente:

- **5.1 Orientação da direção para segurança da informação**
  - **5.1.1 Política para segurança da informação**
    - Diretrizes para implementação

A ideia é criar uma ``política superior`` (abrangente, geral sobre determinado assunto) e, a partir dela, desenvolver ``subpolíticas`` mais específicas e direcionadas. Funciona como um tópico central com subtemas, onde cada subpolítica trata de um aspecto mais focado.

**Exemplos de subpolíticas:**

- Controle de acesso
- Classificação e tratamento da informação
- Segurança física e do ambiente
- Backup
- Entre outras

A própria ISO/IEC 27001 traz exemplos de políticas que podem ser adotadas.

#### Como aplicar essas políticas segundo a norma

Para aplicar as políticas, você deve consultar a ``ISO/IEC 27002``, que faz a conexão com as políticas da 27001. Na 27002, você encontrará os controles, diretrizes e informações adicionais para implementação.

> **Importante:**  
> A norma traz recomendações e orientações, mas **não detalha linha por linha** como a política deve ser escrita. Ela indica o que deve ser feito, mas a elaboração detalhada fica a cargo da organização.

Se você busca um guia prático e detalhado, existe o livro [Políticas e Normas para a Segurança da Informação](https://www.amazon.com.br/Pol%C3%ADticas-Normas-Para-Seguran%C3%A7a-Informa%C3%A7%C3%A3o/dp/8574525154), que mostra passo a passo como criar uma política, detalhando o processo de elaboração.

---

### Aula 57 - Revisões das políticas de segurança da informação

Nada é estático, tudo precisa passar por revisões e atualizações. Assim como o curso e este repositório precisam ser atualizados, o mesmo vale para as políticas de segurança da informação.

Ao criar políticas com base em recomendações ou outras políticas, é possível que surjam novas necessidades ou pontos que não estavam contemplados inicialmente. Por isso, é fundamental realizar revisões periódicas, promovendo a ``melhoria contínua``.

#### Como a ISO/IEC 27001 trata esse quesito

Na norma, o item 5 aborda as políticas de segurança da informação:

- **5.1 Orientação da direção para segurança da informação**
- **5.1.2 Análise crítica das políticas para segurança da informação**
  - Informações adicionais

**Recomendação da norma:**  
Convém que as políticas para a segurança da informação sejam analisadas criticamente em intervalos planejados ou quando mudanças significativas ocorrerem, para garantir sua contínua pertinência, adequação e eficácia.

Além disso, cada política de segurança da informação deve ter um gestor responsável pelo desenvolvimento, análise crítica e avaliação dessas políticas.

---

**Resumo:**  
Revisar e atualizar as políticas de segurança da informação é essencial para garantir que estejam sempre alinhadas às necessidades da organização, às mudanças do ambiente e às melhores práticas do mercado.

---

### Aula 58 - Código de conduta

O que é um código de conduta?  
É um conjunto de recomendações, políticas, normas ou procedimentos que servem como referência para o comportamento do colaborador dentro da organização.

Resumindo, o código de conduta funciona como um guia de boas maneiras para que o colaborador conviva de forma adequada no ambiente corporativo.

**Segundo a norma ISO/IEC 27002:**

- **7. Segurança de recursos humanos**
  - **7.1 Antes da contratação**
  - **7.1.2 Termos e condições de contratação**
    - Informações adicionais

O código de conduta pode ser utilizado para estabelecer as responsabilidades de segurança da informação do funcionário ou parte externa, incluindo:

- Confidencialidade
- Proteção de dados
- Ética
- Uso apropriado dos equipamentos e recursos da organização
- Práticas respeitosas esperadas pela empresa

Partes externas, como fornecedores, também podem ser solicitadas a aderir ao código de conduta por meio de acordos contratuais.

``Sanções:`` O código de conduta pode prever medidas disciplinares caso seja violado.

**Exemplos de regras em um código de conduta:**

- E-mails pessoais não são permitidos
- Para uso de e-mail, o colaborador deve observar a legislação e aderir ao acordo de confidencialidade
- Campanhas de conscientização sobre ameaças como malware, phishing e spam
- É permitido usar telefone, e-mail e internet para fins pessoais, desde que não interfira no trabalho
- Sites de download e de conteúdo sexual são proibidos

Ao adotar o código de conduta, o colaborador já sabe, desde o início, o que pode ou não fazer na empresa.

**Diferença entre política e código de conduta:**

- ``Política:`` Documento formal, linguagem de negócio, define regras e diretrizes gerais da organização.
- ``Código de conduta:`` Focado no colaborador, orienta comportamentos e práticas diárias.

---

### Aula 59 - Gerenciamento de ativos

A norma ``ISO/IEC 27002`` orienta que devemos gerenciar os ativos de TI da organização.

**Segundo a norma:**

- Convém que regras para o uso aceitável das informações, dos ativos associados e dos recursos de processamento sejam identificadas, documentadas e implementadas.
- Convém que todos os funcionários e partes externas devolvam todos os ativos da organização que estejam em sua posse após o encerramento das atividades, contrato ou acordo.

**Segundo o livro base:**

Os ativos de negócio são essenciais para uma organização, pois custam dinheiro ou possuem valor estratégico. Exemplos de ativos:

- Informações
- Programas de computador
- Equipamentos
- Instalações
- Pessoas e seus conhecimentos
- Imagem e reputação

**Classificações de propriedade:**

- Ativos de negócio devem ser classificados para definir os níveis de segurança necessários.
- O proprietário é responsável pelo processo, subprocesso ou atividade de negócio, cuidando de todos os aspectos do ativo, incluindo segurança, gerenciamento, produção e desenvolvimento.

**Principais informações a serem registradas:**

- Tipos de ativos de negócio
- Proprietário
- Localização
- Formato
- Classificação
- Valor para o negócio

**Resumo:** Gerenciar os ativos de uma organização é fundamental, pois eles podem ser essenciais para o funcionamento ou crescimento da empresa. O controle adequado garante segurança, conformidade e proteção dos interesses do negócio.

---

### Aula 60 - Papéis e responsabilidades

É fundamental que cada colaborador siga seu papel e cumpra suas responsabilidades dentro da organização, pois isso contribui diretamente para a segurança da informação.

#### Matriz RACI de um processo qualquer

| Atividade      | Dono do processo | Analista 1 | Técnico | Analista de qualidade|
|----------------|------------------|------------|---------|----------------------|
| Atividade 1    | A/R              | C          | I       | C                    |
| Atividade 2    | A                | R          | I       | C                    |
| Atividade 3    | A                | R          | I       | I                    |
| Atividade 4    | A                | C          | I       | R                    |
| Atividade 5    | A                | R          | I       | I                    |

- ``A`` = Aprova
- ``R`` = Responsável
- ``C`` = Consulta
- ``I`` = Informa

Na matriz RACI, apenas uma pessoa pode ser proprietária de um serviço, processo ou atividade.

#### O que diz o livro base sobre papéis e responsabilidades

- É necessário ter um sistema documentado em que os ativos e processos de segurança da informação estejam identificados e descritos.
- Cada ativo ou processo de SI deve ser atribuído a um indivíduo competente para a função.
- A coordenação e supervisão dos aspectos de segurança no relacionamento com fornecedores devem ser identificadas e documentadas.
- É aconselhável integrar os papéis e responsabilidades de segurança na organização e nomear um proprietário para cada ativo, tornando-o responsável pela operação diária.

#### Papéis e responsabilidades segundo o livro base

- ``Chief Information Security Officer (CISO):``  
  Responsável pelo mais alto nível gerencial da segurança da informação, desenvolve a estratégia geral de SI para toda a empresa.

- ``Information Security Officer (ISO):``  
  Desenvolve a política de SI de uma unidade de negócio com base na política da empresa e garante sua aplicação.

- ``Information Security Manager (ISM):``  
  Desenvolve a política de SI dentro da área de TI e assegura que ela seja seguida.

Após o gerente, temos:

- Encarregado da política de SI
- Encarregado da proteção de dados

**Resumo:**  
Definir claramente os papéis e responsabilidades é essencial para garantir a segurança da informação, facilitar a gestão dos ativos e assegurar que todos saibam suas atribuições dentro da organização.

---

### Aula 61 - Gerenciando incidentes de segurança da informação

É recomendado que as empresas tenham um processo estruturado de gerenciamento de incidentes de segurança da informação.

**Exemplo:**  
Se um colaborador pede sua senha e usuário emprestado, caso aprovado, ele estará se passando por você dentro da organização, quebrando a confidencialidade.

**Segundo a norma ISO/IEC 27001:**  
Um incidente é caracterizado por um ou uma série de eventos de segurança da informação indesejados ou inesperados, que têm grande probabilidade de comprometer as operações do negócio e ameaçar a segurança da informação.

Incidentes podem impactar diretamente a integridade, confidencialidade e disponibilidade da informação (tríade CID).

#### Objetivo do processo de gerenciamento de incidentes

O processo deve permitir:

- Detectar
- Relatar
- Avaliar
- Responder
- Tratar
- Aprender

É fundamental que, mesmo colaboradores que não sejam da área de tecnologia, saibam identificar e relatar incidentes.

O processo precisa garantir que todos os eventos e fragilidades associados às informações sejam comunicados. Assim que um incidente é relatado, é essencial que alguém tome uma ação corretiva imediatamente.

**Resumo:**  
Gerenciar incidentes de segurança da informação é essencial para proteger os ativos da empresa, garantir a continuidade do negócio e promover a melhoria contínua dos processos de segurança.

---

### Aula 60 - Papéis e responsabilidades

---

### Aula 60 - Papéis e responsabilidades

---

### Aula 60 - Papéis e responsabilidades

---

### Aula 60 - Papéis e responsabilidades

---

## 💡 Considerações Finais

Essas anotações refletem o que considerei mais importante e interessante durante as aulas do curso.  
Organizei os principais conceitos e exemplos para facilitar a revisão e a fixação do conteúdo.

Vamos continuar estudando e evoluindo! 🚀

> _Última atualização: 17/07/25 por Ivan Rocha_