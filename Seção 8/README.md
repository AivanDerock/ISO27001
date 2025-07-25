# 📒 Anotações – ISO/IEC 27001

Bem-vindo(a) às anotações da ``Seção 8`` do curso **EXIN ISO 27001: Fundamentos de Segurança da Informação**!

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

### Seção 8

- [Aula 70 - Visão geral da seção](#aula-70---visão-geral-da-seção)
- [Aula 71 - Importância das medidas de segurança](#aula-71---importância-das-medidas-de-segurança)
- [Aula 72 - Seleção de medidas de segurança](#aula-72---seleção-de-medidas-de-segurança)
- [Aula 73 - Categorias de medidas de segurança](#aula-73---categorias-de-medidas-de-segurança)
- [Aula 74 - Tipos de medidas de segurança](#aula-74---tipos-de-medidas-de-segurança)
- [Aula 75 - Classificação das informações](#aula-75---classificação-das-informações)
- [Aula 76 - Medidas físicas para manter áreas seguras](#aula-76---medidas-físicas-para-manter-áreas-seguras)
- [Aula 77 - Medidas físicas para equipamentos](#aula-77---medidas-físicas-para-equipamentos)
- [Aula 78 - Medidas técnicas](#aula-78---medidas-técnicas)
- [Aula 79 - Conceitos de criptografia](#aula-79---conceitos-de-criptografia)
- [Aula 80 - Conceitos de Assinatura Digital](#aula-80---conceitos-de-assinatura-digital)
- [Aula 81 - Conceitos de criptografia HASH](#aula-81---conceitos-de-criptografia-hash)
- [Aula 82 - Tipos de softwares maliciosos e medidas de proteção](#aula-82---tipos-de-softwares-maliciosos-e-medidas-de-proteção)
- [Aula 83 - Medidas organizacionais](#aula-83---medidas-organizacionais)
- [Aula 84 - Medidas organizacionais: exemplos](#aula-84---medidas-organizacionais-exemplos)
- [Aula 85 - Sistema de Gestão de Segurança da Informação (SGSI)](#aula-85---sistema-de-gestão-de-segurança-da-informação-sgsi)
- [Aula 86 - Segurança de recursos humanos](#aula-86---segurança-de-recursos-humanos)
- [Aula 87 - Gestão de acesso](#aula-87---gestão-de-acesso)
- [Aula 88 - Conceitos de gestão de acesso](#aula-88---conceitos-de-gestão-de-acesso)
- [Aula 89 - Responsabilidades do usuário](#aula-89---responsabilidades-do-usuário)
- [Aula 90 - Em Breve]()
- [Aula 91 - Em Breve]()
- [Aula 92 - Em Breve]()
- [Aula 93 - Em Breve]()

---

### Aula 70 - Visão geral da seção

Nesta seção, vamos abordar as ``medidas de segurança``, tema que representa cerca de 10% da prova de certificação.

Serão apresentadas as principais práticas, controles e recomendações para proteger as informações e os ativos da organização, conforme orientações da norma ISO/IEC 27001.

Prepare-se para entender como as medidas de segurança são aplicadas no contexto do SGSI e como elas impactam a proteção dos dados e processos da empresa.

---

### Aula 71 - Importância das medidas de segurança

As medidas de segurança podem ser restritivas ou mais simples, mas todas têm o objetivo de:

- Evitar incidentes
- Combater ameaças
- Minimizar perdas

Essas medidas estão diretamente relacionadas à existência de vulnerabilidades e ameaças. Por exemplo:  
Você possui um ativo (como um sistema), a vulnerabilidade pode ser um software desatualizado e a ameaça pode ser um ataque hacker. Nesse cenário, aplicam-se medidas de segurança para evitar, combater ou minimizar possíveis perdas.

**Importante:**  
As medidas de segurança são sempre implementadas após uma análise de risco. O processo de risco envolve duas etapas principais: ``análise`` e ``gerenciamento``.

A norma **ISO/IEC 27002** apresenta diversas medidas de segurança e deve ser consultada como referência para a implementação dos controles exigidos pela **ISO/IEC 27001**.

**Exemplo prático:**  
Imagine que você vai comprar uma casa em um bairro desconhecido. Antes de se mudar, faz uma ``análise`` para se proteger de possíveis ``ameaças``, como furtos ou assaltos. Se descobre que o bairro tem alto índice de criminalidade, você identifica a ``vulnerabilidade`` (casa sem trancas, janelas sem grades, muro baixo) e a ``ameaça`` (criminalidade).  
A partir disso, começa a implementar ``medidas de segurança``: instalar grades, aumentar o muro, colocar câmeras, reforçar portas, etc. Mesmo assim, nunca estará 100% seguro, por isso é fundamental ``analisar riscos``, ``identificar ameaças`` e ``vulnerabilidades`` e, então, aplicar as ``medidas de segurança`` adequadas.

**Resumo:**  
Medidas de segurança são essenciais para proteger ativos, reduzir riscos e garantir a continuidade do negócio, sempre baseadas em uma análise criteriosa das ameaças e vulnerabilidades.

---

### Aula 72 - Seleção de medidas de segurança

Existem vários tipos de vulnerabilidades e, para cada uma delas, é possível encontrar possíveis soluções na **ISO/IEC 27002**, que traz controles e recomendações para diferentes cenários.

Por exemplo, ao identificar uma vulnerabilidade, você pode consultar a ISO/IEC 27002 e buscar, pela categoria ou pelo tipo de vulnerabilidade, uma medida de segurança adequada para aplicar na sua organização.

Essas medidas devem ser selecionadas de acordo com os requisitos e as necessidades do negócio. O objetivo da seleção de medidas é garantir que os riscos estejam sempre dentro de um nível aceitável para a organização.

**Exemplo prático:**  
Se você compra uma casa sem porta, de acordo com sua necessidade, pode optar por instalar uma porta simples de madeira. Em outros casos, pode ser necessário instalar uma porta de metal blindada. A escolha depende do risco e da necessidade de proteção.

Além disso, a seleção de medidas de segurança também visa garantir que a empresa esteja em conformidade com legislações e regulamentos, como a **LGPD** (Lei Geral de Proteção de Dados Pessoais). Muitas empresas precisaram se adaptar para atender a essa nova lei.

**Importante:**  
Mesmo que a empresa não busque a certificação ISO/IEC 27001, é possível utilizar a ISO/IEC 27002 como referência para selecionar e implementar medidas de segurança adequadas para cada vulnerabilidade identificada.

---

### Aula 73 - Categorias de medidas de segurança

As medidas de segurança podem ser classificadas em diferentes categorias, cada uma com um objetivo específico dentro da gestão de riscos. Veja as principais:

#### **Preventivas**

- **Objetivo:** Prevenir incidentes de segurança antes que aconteçam.
- **Exemplo:** Uso de firewall, políticas de senha forte, treinamento de usuários.

#### **Redutivas**

- **Objetivo:** Reduzir a probabilidade de uma ameaça ocorrer.
- **Exemplo:** Atualização de sistemas, segmentação de rede, controle de acesso.

#### **Detectivas**

- **Objetivo:** Detectar incidentes de segurança rapidamente.
- **Exemplo:** Sistemas de monitoramento, logs de auditoria, alarmes.

#### **Repressivas**

- **Objetivo:** Limitar ou conter um incidente em andamento.
- **Exemplo:** Bloqueio automático de contas suspeitas, isolamento de máquinas infectadas.

#### **Corretivas**

- **Objetivo:** Recuperar-se do prejuízo causado pelo incidente.
- **Exemplo:** Planos de recuperação de desastres, restauração de backups.

#### **Contratar seguro**

- **Objetivo:** Minimizar os impactos financeiros que envolvam perdas de ativos.
- **Exemplo:** Seguro contra roubo de dados, seguro cibernético.

#### **Aceitação**

- **Objetivo:** Aceitar o risco quando não há razão ou motivo para investir em medidas adicionais.
- **Exemplo:** Decidir não investir em proteção extra para um ativo de baixo valor.

---

#### Estratégias de risco relacionadas:

- **Evitar** → Preventivas
- **Neutralizar** → Redutivas
- **Transferir** → Contratar seguro
- **Aceitar** → Aceitação

Cada categoria deve ser escolhida de acordo com o contexto, o risco e a necessidade da organização.

---

### Aula 74 - Tipos de medidas de segurança

É importante entender que existem **três tipos principais de medidas de segurança**:

- **Físicas**
- **Técnicas**
- **Organizacionais/Burocráticas**

Na norma **ISO/IEC 27002**, encontramos diversas estratégias para lidar com riscos, e essas medidas estão basicamente separadas nessas categorias:

#### **Medidas físicas**

Focam na proteção física de um ativo de informação.

- **Exemplo:** Controle de acesso por crachá, câmeras de segurança, portas blindadas, alarmes, barreiras físicas.

#### **Medidas técnicas**

São estruturas implementadas no ambiente de TI e seus respectivos sistemas.

- **Exemplo:** Firewalls, antivírus, criptografia, autenticação multifator, sistemas de detecção de intrusão.

#### **Medidas organizacionais**

Relacionadas a políticas, processos, pessoas e parceiros.

- **Exemplo:** Políticas de segurança da informação, treinamentos de conscientização, contratos de confidencialidade, procedimentos internos.

Cada tipo de medida deve ser escolhido conforme a necessidade e o contexto da organização, garantindo uma abordagem completa e eficaz para a proteção dos ativos.

---

### Aula 75 - Classificação das informações

Não adianta criar barreiras e proteções para todas as informações da mesma forma. Algumas informações são de domínio público e, por isso, precisam de uma classificação adequada.

#### **Classificação Pública**

Por exemplo, existe uma lei de transparência que obriga a divulgação do salário de agentes públicos. Mesmo sendo uma informação pública, ela ainda deve ser tratada com certo rigor, pois pode ser considerada sensível em alguns contextos.

Toda informação deve ter um tipo de classificação para garantir um nível adequado de proteção, de acordo com sua importância para a organização.

Um exemplo clássico de classificação aparece em filmes policiais, onde vemos pastas com etiquetas como "secreto", "ultra secreto" ou "estritamente secreto".

#### **Como criar uma classificação de informação?**

Devemos considerar:

- A sensibilidade da informação
- O valor que ela tem para a organização
- Os requisitos legais aplicáveis (em caso de vazamento)
- A importância estratégica para o negócio

Essas quatro características ajudam a definir a classificação da informação e os níveis de sensibilidade.

- **Classificar** é atribuir um nível de sensibilidade apropriado a uma informação.
- **Designação** é uma forma especial de categorização da informação.

Ao classificar uma informação, também é necessário definir quem é o proprietário dessa informação, ou seja, quem será responsável por sua proteção e uso adequado.

---

### Aula 76 - Medidas físicas para manter áreas seguras

De acordo com o livro base:

- A segurança física faz parte da segurança da informação.
- As medidas devem ser criadas conforme a necessidade do negócio.
- Não se deve exagerar nas medidas físicas de segurança.

**Exemplos de medidas físicas:**

- Sensores
- Câmeras de segurança
- Sensores infravermelhos
- Detectores de vibração
- Sensores de quebra de vidro
- Contatos magnéticos
- Segurança humana (vigilantes)
- Detectores de metais

Um exemplo prático é um banco, que utiliza diversas câmeras, detectores de metais e seguranças para proteger suas áreas.

#### Anéis de proteção

A área que tentamos proteger é chamada de ``anel de proteção``, que pode ser composta por várias camadas:

- **Cerca:** Anel externo
- **Prédio:** Área da instalação da organização
- **Ambiente de trabalho:** Mais um anel de proteção (salas, escritórios)
- **Objeto:** O alvo final, onde a informação está armazenada (ex: cofre, servidor)

Cada camada exige controles físicos específicos, aumentando a dificuldade de acesso conforme se aproxima do objeto protegido.

> A norma ISO/IEC 27002 traz recomendações sobre esses anéis de proteção e como implementá-los de forma adequada.

**Resumo:**  
A segurança física deve ser planejada em camadas, protegendo desde o perímetro externo até o objeto de maior valor, sempre considerando o contexto e a real necessidade da organização.

---

### Aula 77 - Medidas físicas para equipamentos

Hoje em dia, existem armários resistentes ao fogo e armários de segurança para proteger equipamentos e mídias importantes.

Se você faz backup das suas informações (especialmente em empresas), é recomendado armazenar as cópias em um armário cofre, onde apenas pessoas autorizadas (com senha ou chave) possam acessar.

Muitas empresas armazenam backups no próprio data center, mas esse local pode ser considerado hostil para esse tipo de armazenamento. Por isso, algumas medidas físicas podem ser adotadas para aumentar a segurança:

- Leitores de biometria nas portas
- Acesso restrito por cartão magnético cadastrado
- Evitar paredes de gesso em ambientes sensíveis (ex: data center, cofres)
- Controle de umidade
- Proteção contra incêndios
- Boa sinalização
- Equipamentos de energia de emergência
- Refrigeração adequada
- Segurança do cabeamento de rede e elétrico
- Manutenção regular dos equipamentos

Além disso, é fundamental planejar:

- Remoção segura de ativos
- Segurança física dos ativos
- Eliminação segura dos ativos
- Reutilização de equipamentos
- Controle de equipamentos desacompanhados

Essas medidas devem ser aplicadas conforme a criticidade, valor e sensibilidade dos ativos, sempre alinhadas à necessidade do negócio e à legislação vigente.

> Para mais detalhes e recomendações sobre essas medidas, consulte a norma ISO/IEC 27002.

---

### Aula 78 - Medidas técnicas

Existem três tipos principais de medidas de segurança: ``físicas``, ``técnicas`` e ``organizacionais``.  
Nesta aula, o foco é nas **medidas técnicas**.

As medidas técnicas são implementadas diretamente no ambiente tecnológico, visando proteger sistemas, redes e informações. Entre as principais, destacam-se o **controle de acesso** e a **criptografia de dados**.

Segundo a norma ISO/IEC 27002:

#### 9. Controle de acesso

- **9.1 Requisitos comerciais do controle de acesso**  
  *Objetivo:* Limitar o acesso a informações e recursos de processamento de informações.

- **9.2 Gerenciamento de acesso do usuário**  
  *Objetivo:* Garantir o acesso de usuários autorizados e impedir o acesso não autorizado a sistemas e serviços.

- **9.3 Responsabilidades do usuário**  
  *Objetivo:* Tornar os usuários responsáveis pela proteção de suas informações de autenticação.

- **9.4 Controle de acesso ao sistema e aplicativos**  
  *Objetivo:* Impedir o acesso não autorizado a sistemas e aplicativos.

#### 10. Criptografia

- **10.1 Controles criptográficos**  
  *Objetivo:* Assegurar o uso adequado e efetivo da criptografia para proteger a confidencialidade, autenticidade e integridade das informações.

---

**Resumo:**  
Medidas técnicas são essenciais para proteger o ambiente tecnológico da organização. Os principais exemplos são o controle de acesso (quem pode acessar o quê) e a criptografia (proteger dados em trânsito e em repouso).  
A ISO/IEC 27002 detalha boas práticas e controles para garantir a segurança das informações por meio dessas medidas.

---

### Aula 79 - Conceitos de criptografia

Atualmente, existem basicamente dois tipos de criptografia:

- **Criptografia simétrica**
- **Criptografia assimétrica**

#### **Criptografia simétrica**

- Utiliza um único algoritmo e uma **chave secreta** compartilhada entre remetente e destinatário.
- Ambos usam a mesma chave para criptografar e descriptografar a mensagem.
- **Problema:** Se alguém obtiver acesso à chave, poderá ler todas as mensagens.

#### **Criptografia assimétrica**

- Utiliza **duas chaves diferentes**: uma chave pública e uma chave privada.
- A chave pública geralmente é usada para criptografar, e a chave privada para descriptografar.
- Também pode ser usada para assinatura digital: o remetente assina com a chave privada e o destinatário verifica com a chave pública.
- **Vantagem:** Se uma chave for comprometida, é possível gerar um novo par de chaves.

**Resumo:**  
A criptografia simétrica é mais simples e rápida, mas depende do segredo da chave compartilhada. Já a criptografia assimétrica é mais segura para troca de informações, pois utiliza pares de chaves diferentes para criptografia e autenticação.

---

### Aula 80 - Conceitos de Assinatura Digital

A assinatura digital é um procedimento que utiliza a criptografia, especificamente a **criptografia assimétrica** (com chave pública e chave privada).

Quando o remetente assina digitalmente uma mensagem, ele garante:

- **Autenticidade:** Confirma que a mensagem foi realmente enviada por quem assinou.
- **Integridade:** Garante que o conteúdo não foi alterado após a assinatura.
- **Não repúdio:** O remetente não pode negar que enviou a mensagem.

Se a mensagem for alterada ou enviada por engano, as chaves do remetente e do destinatário não irão se "encaixar", indicando que houve violação ou erro.

Atualmente, assinaturas digitais são válidas tanto para pessoas físicas quanto jurídicas. Muitas empresas utilizam assinaturas digitais para validar documentos eletrônicos.

**Importante:**  
A assinatura digital possui valor jurídico, sendo reconhecida legalmente em diversos processos e contratos.

---

### Aula 81 - Conceitos de criptografia HASH

Quando falamos de ``HASH``, estamos nos referindo a um identificador único que cada arquivo ou mensagem possui. Esse identificador é gerado por meio de uma função hash e, em condições normais, não se altera com o tempo.

O hash garante que o arquivo **não foi alterado** desde a última vez que foi gerado.  
Ou seja, uma vez que um arquivo ou mídia é criado, ele recebe um hash único. Ao ser compartilhado, o destinatário pode calcular o hash novamente para verificar se o arquivo foi modificado.

Se o arquivo for alterado (por exemplo, por um vírus), o hash muda, indicando que a ``integridade`` foi comprometida. Isso afeta diretamente os princípios de ``CID`` (Confidencialidade, Integridade e Disponibilidade), pois o arquivo deixa de ser íntegro.

**Exemplo prático:**  

- Um vírus pode modificar um arquivo e alterar seu hash, fazendo com que ele pareça um arquivo comum.  
- Ferramentas de verificação de integridade comparam o hash atual com o hash original para identificar alterações.

**Resumo:**  
O hash é fundamental para garantir a integridade das informações, permitindo identificar rapidamente se um arquivo ou mensagem foi alterado de forma não autorizada.

---

### Aula 82 - Tipos de softwares maliciosos e medidas de proteção

Todo software malicioso deve ser considerado um ``malware``. Antigamente, era comum chamar tudo de vírus, mas hoje o termo correto é **malware**.

**Malware** (do inglês "malicious software") é um código, programa ou software criado para infiltrar-se em sistemas de forma ilícita, com o objetivo de causar danos, alterações ou roubo de informações.

#### Exemplos de malware e ameaças associadas:

- **Phishing:** Tentativa de enganar o usuário para obter credenciais ou informações sensíveis, geralmente por e-mail falso.
- **Spam:** Envio e recebimento de mensagens indesejadas, normalmente em massa.
- **Hoax:** Boatos, fofocas ou fake news, geralmente para enganar ou alarmar usuários.
- **Vírus:** Se espalha pelo sistema e por máquinas, como um vírus biológico.
- **Worm:** "Larva" digital que se propaga sozinha, consumindo recursos e danificando sistemas.
- **Trojan (Cavalo de Troia):** Programa disfarçado de legítimo, mas que executa ações maliciosas. Pode trazer bombas-relógio.
- **Bomba-relógio:** Software que permanece inativo até ser ativado em determinado momento, causando danos.
- **Botnet:** Rede de máquinas "zumbis" controladas remotamente para executar ataques coordenados.
- **Rootkit:** Ferramenta que explora vulnerabilidades para obter acesso privilegiado e ocultar atividades maliciosas.
- **Spyware:** Programa espião que monitora e registra as atividades do usuário, como teclas digitadas e sites acessados.

**Resumo:**  
Todos esses exemplos são tipos de malware, cada um com uma função específica, mas todos são softwares mal-intencionados.

#### Medidas de proteção recomendadas:

- Utilizar antivírus e mantê-lo sempre atualizado.
- Manter o sistema operacional e aplicativos atualizados.
- Não clicar em links ou anexos suspeitos.
- Desconfiar de e-mails e mensagens de remetentes desconhecidos.
- Utilizar firewalls e filtros de conteúdo.
- Realizar backups regulares das informações.
- Treinar usuários para reconhecer ameaças e golpes.

A prevenção e a conscientização são as melhores formas de proteção contra malwares.

---

### Aula 83 - Medidas organizacionais

Quando falamos de segurança de operações, estamos nos referindo a práticas e controles que garantem que tudo que está em operação (computadores, servidores, notebooks, etc.) esteja seguro e funcionando corretamente.

Segundo a norma ISO/IEC 27002, destacam-se os seguintes controles:

#### 12. Segurança de operações

- **12.1 Procedimentos e responsabilidades operacionais**  
  *Objetivo:* Garantir operações corretas e seguras das instalações de processamento de informações.

- **12.2 Proteção contra malware**  
  *Objetivo:* Garantir que as instalações e informações estejam protegidas contra softwares maliciosos.

- **12.3 Backup**  
  *Objetivo:* Proteger contra a perda de dados.

- **12.4 Logging e monitoramento**  
  *Objetivo:* Registrar eventos e gerar evidências para auditoria e análise.

- **12.5 Controle do software operacional**  
  *Objetivo:* Garantir a integridade dos sistemas operacionais.

- **12.6 Gestão de vulnerabilidades técnicas**  
  *Objetivo:* Prevenir a exploração de vulnerabilidades técnicas.

- **12.7 Considerações sobre auditoria de sistemas de informação**  
  *Objetivo:* Minimizar o impacto das atividades de auditoria nos sistemas operacionais.

---

Essas medidas organizacionais são fundamentais para manter a segurança das operações e garantir a continuidade dos serviços, protegendo os ativos de informação da organização.

---

### Aula 84 - Medidas organizacionais: exemplos

As **medidas organizacionais** representam o lado burocrático da segurança da informação. Elas são definidas de cima para baixo, ou seja, partem da alta direção e precisam do comprometimento dos líderes para que a ISO 27001 seja efetivamente implementada na organização.

Na prática, tudo que for criado em termos de políticas, normas, procedimentos e regras — e que deve ser seguido por usuários, colaboradores e clientes — está sob o guarda-chuva das medidas organizacionais. É fundamental que a alta direção aprove, apoie e esteja ciente dessas medidas.

**Exemplos de medidas organizacionais:**

- Políticas de segurança da informação aprovadas pela diretoria
- Procedimentos internos documentados e divulgados
- Termos de responsabilidade e confidencialidade assinados por colaboradores
- Treinamentos de conscientização em segurança da informação
- Processos de gestão de riscos formalizados
- Auditorias internas e revisões periódicas das políticas
- Definição clara de papéis e responsabilidades
- Planos de resposta a incidentes e continuidade de negócios

Todos os processos operacionais e técnicos precisam estar alinhados e subordinados a essas medidas organizacionais, garantindo que a segurança da informação seja uma responsabilidade de toda a organização, com apoio e liderança da alta direção.

---

### Aula 85 - Sistema de Gestão de Segurança da Informação (SGSI)

Para estabelecer um ``SGSI`` (Sistema de Gestão de Segurança da Informação), é necessário seguir um ciclo contínuo de melhoria, garantindo que a segurança da informação seja:

- Estabelecida
- Implementada
- Operada
- Monitorada
- Revisada
- Mantida
- Melhorada

O SGSI utiliza como base o ciclo ``PDCA``:

- ``P`` (Plan / Planejar): Planejar as ações, começando pela análise e gestão de riscos. Identificar pontos de falha e definir as medidas necessárias (físicas, técnicas e organizacionais).
- ``D`` (Do / Executar): Implementar as ações planejadas, colocando em prática as medidas de segurança.
- ``C`` (Check / Verificar): Monitorar e verificar se as ações implementadas estão funcionando conforme o esperado, por meio de auditorias e revisões.
- ``A`` (Act / Agir): Caso algo não esteja funcionando, agir para corrigir e melhorar continuamente o sistema.

O ciclo PDCA é uma lógica de gestão que garante a melhoria contínua do SGSI.  
Independentemente do ponto de partida, sempre se inicia com a ``análise de risco``, que direciona todas as ações seguintes.

**Resumo:**  
O SGSI é implementado e mantido com base no ciclo PDCA, começando pela análise de riscos e utilizando medidas físicas, técnicas e organizacionais para proteger a informação. O processo é contínuo, sempre buscando aprimorar a segurança da organização.

---

### Aula 86 - Segurança de recursos humanos

Qualquer pessoa que usa, manipula ou armazena dados é responsável, direta ou indiretamente, pela segurança dessas informações. Não é possível transferir totalmente a responsabilidade de uma informação para outra pessoa ou setor.

Por exemplo, se uma informação pertence ao setor de RH, o departamento de TI também é responsável por garantir sua proteção. Se você cria uma informação, seu colega que tem acesso também compartilha essa responsabilidade.

Até mesmo uma simples conversa de elevador sobre assuntos internos pode se tornar uma falha de segurança da informação.

Segundo o livro base, ``todos os funcionários são responsáveis pela segurança da informação``.

A empresa deve ter processos rigorosos de contratação e desligamento de colaboradores, pois não basta apenas o RH desligar o funcionário e a TI desativar o acesso dias depois. Ambos os setores precisam atuar juntos para evitar riscos, como ações mal-intencionadas de ex-colaboradores.

É fundamental que a empresa tenha processos definidos para:

- Antes da contratação
- Durante o vínculo empregatício
- Após o encerramento do contrato

Outro ponto importante é o controle de acesso dos colaboradores: saber o que está sendo acessado, como os recursos estão sendo utilizados e monitorar possíveis comportamentos suspeitos.

**Resumo:**  
A segurança de recursos humanos envolve todos os colaboradores e exige processos claros e integrados entre os setores, desde a contratação até o desligamento, além de monitoramento contínuo dos acessos e atividades.

---

### Aula 87 - Gestão de acesso

A ``gestão de acesso`` tem como objetivo impedir ou autorizar o acesso de pessoas a sistemas, informações e recursos da organização. É fundamental que o sistema esteja preparado para monitorar as atividades dos usuários, identificando tentativas de invasão, cópia de arquivos ou outras ações suspeitas.

O gerenciamento de acesso envolve:

- **Registro e cancelamento de usuários:** Controle de criação, alteração e exclusão de contas em serviços ou aplicações.
- **Provisionamento de acesso:** Definir quais permissões cada usuário deve ter, de acordo com sua função.
- **Revisão periódica de acessos:** Verificar regularmente quem tem acesso às aplicações, identificando colaboradores desligados ou mudanças de função.
- **Gestão da informação de autenticação secreta:** Gerenciar senhas, tokens e outros métodos de autenticação para garantir que apenas pessoas autorizadas acessem os recursos.

Esses procedimentos garantem que apenas pessoas autorizadas tenham acesso às informações e recursos necessários, reduzindo riscos e fortalecendo a segurança da organizaçã``

---

### Aula 88 - Conceitos de gestão de acesso

Dar acesso a uma pessoa a determinada informação envolve três etapas principais:

1. ``Identificação:`` O usuário informa quem é (por exemplo, login, número de matrícula, cartão).
2. ``Autenticação:`` O usuário comprova sua identidade (senha, biometria, token, etc.).
3. ``Autorização:`` O sistema verifica se o usuário tem permissão para acessar a informação ou recurso solicitado.

Um bom exemplo é o funcionamento de um caixa eletrônico:  
Primeiro, você se identifica inserindo o cartão; depois, autentica sua identidade com a senha ou biometria; por fim, o sistema autoriza (ou não) o acesso às funções bancárias.

Em muitas empresas, as informações ainda estão facilmente acessíveis, sem um processo claro de autorização e verificação. Isso representa um risco, pois o acesso deve sempre passar por essas três etapas para garantir a segurança das informações.

**Resumo:**  
A gestão de acesso eficiente depende da correta aplicação dos processos de identificação, autenticação e autorização, garantindo que apenas pessoas autorizadas possam acessar informações sensíveis.

---

### Aula 89 - Responsabilidades do usuário

Na ISO/IEC 27002, existem recomendações importantes sobre a criação e o gerenciamento de senhas, especialmente no controle:

#### 9. Controle de acesso

##### 9.4 Controle de acesso ao sistema e à aplicação

##### 9.4.3 Sistema de gerenciamento de senha

**Controle:**  
Convém que sistemas para gerenciamento de senhas sejam interativos e assegurem senhas de qualidade.

Ou seja, o sistema deve orientar o usuário durante a criação da senha, indicando se ela está fraca ou forte, e exigir padrões mínimos de segurança.

**Diretrizes para criação de senhas seguras:**

- Utilizar senhas com comprimento mínimo (ex: 8 caracteres ou mais)
- Misturar letras maiúsculas, minúsculas, números e caracteres especiais
- Evitar senhas óbvias, como datas de nascimento, nomes ou sequências simples
- Não reutilizar senhas em diferentes sistemas
- Alterar senhas periodicamente, conforme política da organização
- Não compartilhar senhas com outras pessoas
- Utilizar, sempre que possível, autenticação multifator (MFA)

**Resumo:**  
O usuário é responsável por criar e manter senhas seguras, seguindo as orientações do sistema e as políticas da organização. Sistemas de gerenciamento de senha devem ser interativos, ajudando o usuário a escolher senhas fortes e protegendo o acesso às informações.

---

### Aula 90 - Formas de controle de acesso lógico

O ``acesso lógico`` é aquele realizado por meio de sistemas, aplicações, desktops ou notebooks, ou seja, qualquer acesso digital a recursos de informação.

Existem quatro principais formas de controle de acesso lógico:

1. ``Controle de acesso discricionário (DAC)``  
   O proprietário do recurso define quem pode acessar e quais permissões cada usuário terá. É o modelo mais flexível, mas também o mais suscetível a erros humanos.

2. ``Controle de acesso mandatório (MAC)``  
   As permissões são definidas por políticas centralizadas da organização, e não podem ser alteradas pelo usuário. Muito utilizado em ambientes de alta segurança, como órgãos governamentais.

3. ``Controle de acesso baseado em papéis (RBAC)``  
   O acesso é concedido de acordo com o papel ou função do usuário na organização. Exemplo: um gerente tem acesso a determinados recursos que um analista não possui.

4. ``Controle de acesso baseado em requisitos (ou atributos) (ABAC)``  
   O acesso é concedido com base em requisitos específicos, como horário, localização, tipo de dispositivo, entre outros atributos. Permite regras mais dinâmicas e contextuais.

**Resumo:**  
Cada forma de controle de acesso lógico atende a necessidades diferentes de segurança e flexibilidade, sendo importante escolher o modelo mais adequado ao contexto da organização.

---

### Aula 91 - Segregação de tarefas

A palavra ``segregação`` significa dividir ou separar funções e responsabilidades dentro de uma organização.

Segundo o livro base:

Convém que tarefas e responsabilidades sejam separadas para evitar o uso indevido, alterações não autorizadas ou não intencionais de ativos.

Na prática, a segregação de tarefas envolve analisar se uma pessoa acumula funções de decisão, execução ou controle. Se uma mesma pessoa tem acesso desnecessário ou exerce múltiplos papéis críticos, o risco de uso indevido, alteração ou destruição de informações aumenta — seja de forma intencional ou acidental.

**Resumo:**  
Dividir as tarefas entre diferentes pessoas reduz os riscos para a organização, garantindo maior segurança e integridade das informações e processos.

---

### Aula 92 - Em Breve

---

### Aula 93 - Em Breve

---

## 💡 Considerações Finais

Essas anotações refletem o que considerei mais importante e interessante durante as aulas do curso.  
Organizei os principais conceitos e exemplos para facilitar a revisão e a fixação do conteúdo.

Vamos continuar estudando e evoluindo! 🚀

> _Última atualização: 24/07/25 por Ivan Rocha_