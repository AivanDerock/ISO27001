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
- [Aula 80 - Em Breve]()
- [Aula 81 - Em Breve]()
- [Aula 82 - Em Breve]()
- [Aula 83 - Em Breve]()
- [Aula 84 - Em Breve]()
- [Aula 85 - Em Breve]()
- [Aula 86 - Em Breve]()
- [Aula 87 - Em Breve]()
- [Aula 88 - Em Breve]()
- [Aula 89 - Em Breve]()
- [Aula 90 - Em Breve]()

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

### Aula 80 - Em Breve

---

### Aula 81 - Em Breve

---

### Aula 82 - Em Breve

---

### Aula 83 - Em Breve

---

### Aula 84 - Em Breve

---

### Aula 85 - Em Breve

---

### Aula 86 - Em Breve

---

### Aula 87 - Em Breve

---

### Aula 88 - Em Breve

---

### Aula 89 - Em Breve

---

### Aula 90 - Em Breve

---

## 💡 Considerações Finais

Essas anotações refletem o que considerei mais importante e interessante durante as aulas do curso.  
Organizei os principais conceitos e exemplos para facilitar a revisão e a fixação do conteúdo.

Vamos continuar estudando e evoluindo! 🚀

> _Última atualização: 22/07/25 por Ivan Rocha_