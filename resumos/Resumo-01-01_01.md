# Estudo dirigido

> Material referente aos slides 1.0 e 1.1 <br/>
> Feito por **Hugo Sobral de Lima Salomão**

---

## O que é a engenharia de requisitos?

Surgida em **1993** a engenharia de requisitos pode ser definida como um conjunto de atividades para identificar e comunicar as finalidades de um produto de software **(EASTERBOOK, 2004)**.

Não obstante, a engenharia de requisitos não se restringiu àpenas uma definição formal. Uma gama de materiais e conteúdos deposita informações acerca da definição da engenharia de requisitos.

> _"Um conjunto de atividades utilizadas para identificar e comunicar a finalidade de um sistema de software, e o contexto no qual será usado. Assim, a engenharia de requisitos atua como ponte entre as necessidades reais dos usuários, clientes, e outros grupos afetados por um sistema de software, e as potencialidades e oportunidades oferecidas pela tecnologia"_ <br/>**(EASTERBOOK, 2004)**
>
> ---
>
> _"Uma **área multidisciplinar, centrada no ser humano e em seus problemas.** Deve, portanto, investigar como as pessoas **percebem** e **entendem** o mundo ao seu redor, como trabalho afeta suas ações. A engenharia de requisitos deve se utilizar, portanto, das ciências sociais e cognitivas, tais como a filosofia, a psicologia cognitiva, a sociologia e a linguística, dentre outras, para fornecer fundamentos teóricos e técnicas para elicitar e modelar requisitos."_ <br/>**(NUSEIBEH, 2000)**
>
> ---
>
> _"Um processo iterativo, incremental, cognitivo, social, comunicativo e criativo, cujos objetivos são conhecer, entender, estruturar, representar, comunicar e transcrever as informações relevantes de um sistema, extraídas a partir de diferentes segmentos de informação: ambiente da organização; a gerência; e o desenvolvimento."_ <br/>**(CARVALHO, 2003)**

---

## O que é um requisito em engenharia de requisitos?

Os requisitos surgem como descrição das necessidades, serviços, finalidades ou pilares de um sistema de software.

Suplementarmente à definição de engenharia de requisitos, a definição dos requisitos em si também não se restringem àpenas uma definição formal.

> _"Requisitos de um sistema são descrições dos serviços que devem ser fornecidos por esse sistema e as suas restrições operacionais."_ <br/>**(SOMMERVILLE, 2007)**
>
> ---
>
> _"Um requisito de um sistema é uma característica do sistema ou a descrição de algo que o sistema é capaz de realizar para atingir seus objetivos."_ <br/>**(PFLEEGER, 2004)**
>
> ---
>
> _"Um requisito é algo que o produto dem de fazer ou uma qualidade que este precisa apresentar"_ <br/>**(ROBERTSON, 2006)**

---

## Contextos da engenharia de requisitos

A engenharia de requisitos geralmente ocorre em contextos de sistemas de **atividade humana** em que os "donos do problema" são pessoas.

> _"A **obtenção incorreta dos requisitos levará a obtenção e disponibilização de sistemas inadequados** às organizações."_ </br>**(ROCHA, 2002)**

---

## Processos

Em Engenharia de Software e no Gerenciamento de Projetos, um processo é um conjunto estruturado de práticas que pode ser repetível durante o processo de produção de software.

Dentro deste contexto, os processos podem ser separados em dois grandes grupos: <br/>

- Processos **tradicionais**, com enfoque para o Processo Unificado
- Processos **Ágeis**, com enfoque para o Scrum

### Processo Unificado

O RUP (Rational Unified Process, em português, **Processo Unificado**) é um processo de desenvolvimento de software. Ele engloba as ações necessárias para transformar um conjunto de requisitos do cliente em um sistema de software combinando os ciclos de vida iterativo, incremental e verificando a qualidade do mesmo de forma que cada entrega do software em um ciclo agrega mais valor ao produto em relação ao ciclo anterior.

### Scrum

Segundo os criadores desse método, _Ken Schwaber_ e _Jeff Sutherland_, o Scrum **"é um framework para desenvolver e manter produtos complexos"**. O Scrum consiste em um método que trabalha com ciclos curtos de desenvolvimento. Deste modo, o feedback a respeito do resultado é obtido rapidamente, o que garante a qualidade do produto desenvolvido e a satisfação do cliente.

---

## Qualidade de requisitos

A qualidade dos requisitos é um fator fundamental para o sucesso do produto de software a ser construído.

Tanto processos tradicionais, quanto processos ágeis prezam pela qualidade dos requisitos

Contudo, o momento da verificação da qualidade dos requisitos pode variar a depender da metodologia que está em vigor para cada projeto.

Existem algumas diretivas que servem de métricas para a medição da qualidade dos requisitos, estas são:

- Ser verificável (testável)
- Ser rastreável
- Ser inteligível
  > As seguintes diretivas são determinadas pela _IEEE - Computer Society_
- Ser correto
- Ser completo
- Ser consistente
- Ser não-ambíguo

### Verificável

Um sistema é verificável se existir algum processo efetivo que demonstre que o software atende aos requisitos documentados.

### Rastreável

Um sistema é rastreável se permite que sua origem seja determinada.

### Correto

Um sistema é correto se os requisitos contém toda a informação necessária, de acordo com as necessidades de cada contexto.

### Completo

Um sistema é completo se a especificação contem todos os requisitos significativos e necessários, tais como:

- funcionalidades
- performance
- restrições
- projetos
- interfaces externas

### Não-ambíguo

Um sistema é não-ambíguo se este possuir uma única interpretação. Esta interpretação deve ser universal e constante entre todos os _stakeholders_ envolvidos diretamente com o projeto.

### Consistente

Um sistema é consistente caso sua especificação (casos de uso, histórias de usuário e especificações suplementares\_ estejam coerentes com as especificações de mais alto nível).

Supletivamente, os requisitos devem apresentar consistência entre si, e em um mesmo nível hierárquico de requisitos, sem que haja conflitos internos.

---

## Atividades

### Elicitação de requisitos

> _A elicitação de requisitos pode ser considerada a atividade mais importante do processo de Engenharia de Requisitos._ <br/> **> (GOGUEN, 1994)**
>
> ---
>
> _Processo cuidadoso de análise da organização, do domínio da aplicação e do processo de negócio, no qual o sistema será utilizado.> _ <br/> **(PRESSMAN, 2002)**
>
> ---
>
> _É um processo de **transferência de conhecimento** do stakeholder para o engenheiro de requisitos._ <br/> **(KOTONYA, 1998)**

O processo de elicitação de requisitos requer uma **forte comunicação** entre analistas e stakeholders.

#### Técnicas

- Estudo de documentação
- Análise de contexto
- Observação
- Análise social
- Estudo etnográfico
- Entrevista
- Reunião JAD (Joint Application Development)
- Brainstorming
- Workshop
- Grupo focal
- Questionário
- ...

### Análise e Negociação

Nem tudo aquilo que se quer fazer em termos de software pode ser feito. O analista deve expor os motivos que possam limitar os requisitos e negociá-los msotrando os riscos envolvidos.

> _Refinar os requisitos e assegurar-se de que todas as partes interessadas compreendam e estejam atentos para erros e outras deficiências._ <br/> **(WIEGERS, 2003)**

### Documentação

> _Os requisitos aprovados na atividade de análise e negociação devem ser registrados._ <br/> **(KOTONYA, 1998)**
>
> ---
>
> _A especificação do sistema é o produto de trabalho final desenvolvido pelo engenheiro de requisitos._ <br/> **(PRESSMAN, 2002)**
>
> ---
>
> _Os modelos gráficos, auxiliam os engenheiros de softwarea entenderem a estrutura do projeto._ <br/> **(PRESSMAN, 2002)**

### Verificação e Validação

Esse processo visa antecipar problemas antes que eles passem para as fases seguintes.

> _"A validação de requisitos examina a especificação para garantir que todos os requisitos tenham sido declarados de modo não ambíguo, que as inconsistências, omissões e erros tenham sido detectados e corrigidos e que os produtos de trabalho estejam de acordo com as normas estabelecidas para o processo, projeto e produto."_ <br/> **(PRESSMAN, 2002)**

Esta atividade verifica se:

- Os requisitos estão claramente estabelecidos
- Os requisitos podem ser mal interpretados
- A fonte dos requisitos está identificada
- O requisito está limitado em termos quantitativos
- Pode-se rastrear os requisitos em qualquer modelo criado do sistema
- O requisito viola alguma restrição de domínio
- Outros requisitos se relacionam com esse requisito

#### Verificação

A verificação é o processo que confirma se o produto está sendo construindo de **maneira correta**.

#### Validação

A validação é o processo que confirma se o time está construindo o **projeto certo**.
software

### Gerência de requisitos

> _"Essa atividade possui como objetivo administrar os requisitos ao longo do projeto de software."_ <br/> **(PRESSMAN, 2002)**

Mantém a sincronia entre os requisitos e as demais atividades do processo de desenvolvimento.

Avalia os impactos e riscos envolvidos nas mudanças

#### Princípios

- Gerenciar as mudanças, para o aceite dos requisitos
- Gerenciar o relacionamento entre os requisitos
- Gerenciar as dependências entre o documento de requisitos e outros documentos produzidos durante o proceso de Engenharia de Software.

---

## Papéis

Os **stakeholders** são TODAS as pessoas envolvidas ou afetadas, direta ou indiretamento pelo software em desenvolvimento, entre elas:

- **Expert de domínio**: Profundo conhecedor de assuntos relativos ao sistema. Pode ser uma consultoria externa.
- **Usuário final**: Pessoa que irá operar o sistema após sua conclusão. Esta é fundamental para o sucesso do projeto.
- **Engenheiro de software**: Profissional de TI expert em linguagem de programação, redes, segurança, banco de dados e outros.
- **Engenheiro de requisitos**: Analista de sistema responsável por levantar os requisitos, documentá-los e gerenciá-los.
- **Gerente de projeto**: Líder responsável por planejar e estimar as atividades do projeto. Este irá, após a fase de engenharia de requisitos, comandar o projeto.
- **Sponsor**: É aquele responsável pelo financiamento do projeto. Cabe ao sponsor tomar as decisões estratégicas.
