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
- [Aula 11 - Em Breve]()

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

### Aula 11 - Em Breve

---

## 💡 Considerações Finais

Essas anotações refletem o que considerei mais importante e interessante durante as aulas do curso.  
Organizei os principais conceitos e exemplos para facilitar a revisão e a fixação do conteúdo.

Vamos continuar estudando e evoluindo! 🚀

> _Última atualização: 09/06/25 por Ivan Rocha_