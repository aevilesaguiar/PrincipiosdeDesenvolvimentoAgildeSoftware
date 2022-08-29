# Princípios de Desenvolvimento Ágil de Software

- Manifesto Agil:
Mesmo havendo valor nos itens á direita , valorizamos mais os itens a esquerda.

## Indivíduos e interações mais que processos e ferramentas;

        - Alguns processos são difícies de serem seguidas sem ferramentas(e usar essas ferramentas é difícil e também rouba o foco principal no produto;
        - O foco não precisa ser processos o foco são as pessoas e como elas interagem.
        - Deve-se aproveitas ao máximo o potencial das pessoas(aproveitar o colaborador no melhor que ele pode oferecer);
        - é muito mais efetiva a comunicação faca a face.
        -  A prática mostra que ferrramentas sofisticadas não são importantes assim...Ou seja um quadro com postit, pode facilitar mais
       

## Software em funcionamento mais que documentação abrangente
            - Software RUP (Rational Unified Process- Processo Unificado da Rational),é um processo de engenharia de software criado para apoiar o desenvolvimento                  orientado a objetos, fornecendo uma forma sistemática para se obter vantagens no uso da UML. Foi criado pela Rational Software Corporation e                        adquirido em  fevereiro de 2003 pela IBM.    
               O principal objetivo do RUP é atender as necessidades dos usuários garantindo uma produção de software de alta qualidade que cumpra um cronograma e                  um orçamento previsíveis. Assim, o RUP mostra como o sistema será construído na fase de implementação, gerando o modelo do projeto e, opcionalmente,                o modelo de análise que é utilizado para garantir a robustez. O RUP define perfeitamente quem é responsável pelo que, como as coisas deverão ser                    feitas e quando devem ser realizadas, descrevendo todas as metas de desenvolvimento especificamente para que sejam alcançadas.

               O RUP organiza o desenvolvimento de software em quatro fases, onde são tratadas questões sobre planejamento, levantamento de requisitos, análise,                    implementação, teste e implantação do software.  Cada fase tem um papel fundamental para que o objetivo seja cumprido, distribuídos entre vários                    profissionais como o Analista de sistema, Projetista, Projetista de testes, entre outros. 
               
![image](https://user-images.githubusercontent.com/52088444/185456727-fe22b0f2-f2c7-4d0e-ad86-4e774eca6058.png)
![image](https://user-images.githubusercontent.com/52088444/185456903-a5825907-d41a-4dac-9a55-2d1c10b95d03.png)

![image](https://user-images.githubusercontent.com/52088444/185457359-29241480-c60f-4302-a97a-d9576938744d.png)
Isso é papel , não gera software, não tem entregável.

E se eu trocar o esforço de documentação pela criação do software. Eu escrevo os requisitos do cliente, e vou evoluindo o software em pequenas interações

TDD(focando na simplicidade)  e refatoração(código limpo) deixam o código mais fácil de ser modificado.

Não é que nenhuma documentação será gerada durante o projeto, mas ela só será utilizada quando agregar valor.



## Colaboração com o cliente mais que negociação de contratos

- Dar mais enfase na colaboração com o cliente mais que negociação de contratos;
- Você não pode escolher  que você deve ser o maior interessado no sucesso do projeto, Muitas vezes o cliente não tem maturidade de definir tudo no início do
 projeto. O ideal é trabalhar junto com o cliente ao invés de disputar, no contrato deve  ter mecanismos para facilitar para colaborar com o cliente, mudança
 no início do projeto é positivo, menos perdas, ou seja vamos ouvir o cliente refinando o projeto. Ágil é reagir as mudanças com agilidade. O contrato não deve ser um escudo.


## Responder a mudanças mais que seguir um plano

No tradicional qualquer mudança que atrapalha o planejamento é vista como uma coisa ruim. O feedback do  cliente geralmente irá resultar em mudanças para o projeto, e consequentemente para o planejamento. Muitas vezes seguir o plano virá o foco do projeto e não a entrega.

No desenvolvimento se, se utiliza várias práticas para tornar rápida a resposta a mudanças. O detalhamento do planejamento é feito de forma a poder ser alterado mais facilmente , um exemplo é o Kanban que facilmente pode ser alterado, mas sem nível de detalhamento.

TDD e refatoração são técnicas para deixar o código mais fácil de ser alterado.


Agil é diferente de Rápido.


## Scrum&XP: A Forma Como Fazemos Software

- Modelagem Tradicional
Evita mudanças em requisitos
Análise antes da implementação
Entrega software apenas no final

- Modelagem Ágil
Aceita mudança em requisitos
Usa feedvack e colaboração do cliente e também do time de desenvolvedores
Entrega software frequentemente de partes do softeware
![image](https://user-images.githubusercontent.com/52088444/185462891-eb22cfd0-c809-4262-817d-30f8860d14c2.png)

A parte gerencial do scrum está por fora , um exemplo no scrum nos temos o sprint corresponde as interações do XP. E no XP nós temos o TDD.

As empresas escolhem as melhores práticas para se usar.
![image](https://user-images.githubusercontent.com/52088444/185463079-d6644548-32ec-4790-997c-f920aa10fe27.png)

![image](https://user-images.githubusercontent.com/52088444/185463419-9ff3a034-4d22-45b3-bca5-180552b5b601.png)

## User Story: O que é?

Scrum-> PO:Product Owner Dono do produto
XP-> Cliente -Customer

Ele acompanha a equipe de desenvolvimento, do inicio ao fim, ele esclarece o que precisa ser feito no software, ele define a cara do software.

Quais são os requisitos?
Podemos usar funcionalidades, casos de uso ou user stories. 


O que é uma User Story?
Descreve uma funcionalidade que o PO gostaria de ver em seu produto.
A perspectiva é do PO(Dono do produto), ele descreve as users stories na linguagem do cliente, seria importante se ele escrevesse as U.S.

Podemos eestruturar a User story através das seguintes perguntas

Who?(determinar os papeis dos usuarios desse software) What?(mostra o objetivo)         why?(por que precisa ver isso)
quem?                                                  o que?                              Por quê?


Para identificar o tipo d usuário você fará:

![image](https://user-images.githubusercontent.com/52088444/185468241-e0e4cb1d-0834-4505-acd0-6c91ff8040cd.png)

quem-o quê- por quê
who-> As a-> como um usuario
what-> I want/I need/I can<objetivo> 
why-> So that<beneficio/razao>- o contexto , ele é opcional, você não deve ficar parado se em um determinado você não souber o motivo.
        
 ![image](https://user-images.githubusercontent.com/52088444/185469954-c46bfcdd-dc6e-4681-9717-d5598102827a.png)

![image](https://user-images.githubusercontent.com/52088444/185470153-1de72ea9-894a-44ec-971d-d39eca92fefb.png)
        
![image](https://user-images.githubusercontent.com/52088444/185470211-c9b15b26-ef80-4c92-9920-2390972ee505.png)
  
      
User Store é uma promessa de conversação , de dialogo entre o time de desenvolvimento e o PO.
O PO está perto do pessoal de desenvolvimento para poder tirar duvidas.
        
## User Story: Cartão, Conversação e Confirmação
        
![image](https://user-images.githubusercontent.com/52088444/185470710-915ab45c-91d4-4fc0-9918-526db52334e6.png)
   Essa tecnica 3C ajuda a entender a estrutura de user store
        User store é escrita na frente do cartão e a confirmação é feita atrás. Teste de aceitação não faz sentido sem uma User store.
        
## Entendendo o cartão
        
        - O cartão representa uma user Story
        - Uma user Story representa um requisito, ou seja um cartão é um requisito
        - Pode-se usar um cartão índice ou um Post-it ou ferramenta digital(software aplicativos, trelo, kanban);
        - A user story não precisa ser muito detalhada, deve ter texto suficiente para identificar o requisito;
        
## entendendo a conversação
        - Ela começa antes das users storyes estarem definidas normalmente elas ocorrem no sprint 0, ela antecede o desenvolvimento, corresponde a fase de 
        EDUF-Enough Design Up-Front (Define User Sories no Sprint Zero) . No Sprint Zero o PO e o time de desenvolvimento vai fazer entrevista, vão representar
        essas funcionalidades que se deseja se por nesse software na forma de User Stores.
        
        Para cada User Store o PO ele quer garantir que o que ele deseja seja feito naquela característica que está sendo representada pesa User Store.
        O PO cria um conjunto de testes de aceitação e associa isso a cada user stores.
        
![image](https://user-images.githubusercontent.com/52088444/185475662-e9ea0c8a-3577-4256-a587-5c38beb7bba2.png)
        
        PO define ATS no  Sprint Zero.
        *ATS=Acceptance Tests
        
        O teste de aceittação vai dar uma garantia ao time desenvolvedor que estão fazendo o caminho certo ao desenvolver aquela user Store. Depois 
        o O vai  validar se o que eles fizeram está de acordo com esses testes de aceitação.
        
![image](https://user-images.githubusercontent.com/52088444/185476129-fa3bba97-16d6-45f6-afe5-34ebd1ed9bc2.png)
        Se estima quantos dias iremos desenvolver essa User Store. Geralmente essa definição é feita usando uma reunião chamada de Planning Poker ou
        Scrum Poker, ou Planning Gamer em que o time de desenvolvimento na presença do PO vão atribuir a cada US o tamanho do esforço para se codificar.
        O PO no Sprint '0' vai definir uma estimativa de valor de negócio que pode variar com o tempo, o necessário é priorizar. 
        Valor de Negócio =Bussiness Value(BV). 
        
![image](https://user-images.githubusercontent.com/52088444/185476975-ce823fec-e985-482e-be02-38f0f4367d10.png)
        
        O teste de aceitação(roteiro) é o que mostra se estão no caminho certo.
        
        No sprint Review ou Demo, O PO confirma isso> a palavra final é dele, o mesmo pode rejeitar, ele pode rejeitar parcialmente. não se perde o trabalho e se cria uma nova user store
        
![image](https://user-images.githubusercontent.com/52088444/185477248-75ec266f-a6b0-464a-aa7c-bbaf697df612.png)

        Tamanho da user store(se é dificil ou não) BV (VALOR DE NEGÓCIO) e o teste de aceitação
 
       
## User Story: Testes de Aceitação
        
        Os ATs são escritos na na linguagem de dominio do negócio.
        
        Testes de aceitação são fruto da conversação entre PO e time de desenvolvedores. De fato os testes de aceitação são testes funcionais, testes de caixa preta, eles vão olhar se o software cumpre o requisito, aqui olhamos o resultado. A user store atingiu o resultado.
        Os testes de aceitação são implementados durante a Sprint(que é a interação no desenvolvimento de software), nesse sprint antes de começar a codificação
        eu devo ter os testes de aceitação, mas no Sprint 0 , fica dificil definir bons testes de aceitação, mas no decorrer será feito novos testes pois terão mais informações.
![image](https://user-images.githubusercontent.com/52088444/185479783-26b851a1-0930-4e76-a312-ca775c879f59.png)

        ATS ajudam o PO e o time de desenvolvimento a confirmar que a User Story foi codificada corretamente. Os testes de aceitação são informais. 
        
![image](https://user-images.githubusercontent.com/52088444/185479689-18f5e576-4c6e-4179-8026-3f62d440e401.png)

        Cerimonia onde vou apresentar/demonstração do código ou implmentação. Quando o time de desenvolvimento chega nesse ponto do demo , quer dizer que eles estão satisfeitos com os testes de aceitação. é feito uma demonstração publica, e o PO sabe o que está acontecendo.
        O PO pode não aceitar parciamente, ou total. Ou pode aceitar 100% . 
        Caso não tenha sido aceita , a User Story passa para o próximo Sprint para ser refeita , o código pode ser refeito, ou seja um recomeço. 
        
![image](https://user-images.githubusercontent.com/52088444/185480545-62820774-bc55-421d-b811-f41e0fd7b48d.png)
        
      Exemplo de Uma User Story:
![image](https://user-images.githubusercontent.com/52088444/185480999-81c6ddd5-e1de-465f-8793-28b84c193e45.png)

![image](https://user-images.githubusercontent.com/52088444/185481135-6aacd652-0cf3-4c2a-9dbd-dca6d289a1e7.png)


   ## User Story: Caracterização de Papéis de Usuário( User roles)
        
        a User Story tem pelo o menos 3 elementos.
        
![image](https://user-images.githubusercontent.com/52088444/185481521-45c4349d-c488-4409-b87a-15369d059b37.png)

        
![image](https://user-images.githubusercontent.com/52088444/185481610-4825214c-3e95-4d08-a98a-a256c236a059.png)

User Role(tipo de usuario)
        
![image](https://user-images.githubusercontent.com/52088444/185481860-f25c5ece-9814-4b41-9898-641478d39799.png)
![image](https://user-images.githubusercontent.com/52088444/185482102-a7a24740-db48-45ad-abee-8275523da9f0.png)

        o USER Role nem sempre é representado por pessoas, pode ser hardware, sistema
        
     Para começar o desenvolvimento de uma aplicação temos que desenvolver a visão da Aplicação e no nosso caso é um documento de requisitos que descreve o que o sistema vai fazer , e vai guiar todos os envolvidos, PO , dev, pessoas e=interessadas no que se deve fazer no desenvolvimento.
        
        Coloca-se requisitos funcionais não funcionais , tipos de usuario. E apartir disso o PO desenvolve as Users Storys.
        
        Ex:
        
![image](https://user-images.githubusercontent.com/52088444/185482739-25a6f066-0667-48e4-b918-363113678c5a.png)

        Papeis de Usuarios(User Roles)
        
        Os papeis de Usuarios no caso desse sistema: 
        Essa visão está definição esta sendo extraida da visão do usuario , e tem a ver com o Valor do negócio e fica com o Product Owner.
![image](https://user-images.githubusercontent.com/52088444/185483609-c870a6d2-b3a8-43d4-ae7a-84f4e9547e19.png)

        Podemos ter vários tipos de clientes
        Padrão e premium eu crio sub papeis
        
![image](https://user-images.githubusercontent.com/52088444/185483776-86e7408e-9c20-49f8-b9a8-c7a28211b03d.png)
  
## Fluxograma
![image](https://user-images.githubusercontent.com/52088444/185483851-c3209360-ece9-40b7-bffa-da33abf2134a.png)

## Visão da Aplicação no modelo Ágil (Scrum x XP)

No inicio do Scrum eu defino um Sprint Zero , eu antecipo o que eu quero fazer. Ele possui duração de duas semanas. E eu tenho duas coisas essenciasis que
tenho que definir a "Visão da Aplicação"(diz qual a direção vou tomar) e o segundo item é o Backlog do produto( conjunto de User Storys que vão representar de maneira formal os requisitos do ususario que estão expressos na visão da aplicação)



![image](https://user-images.githubusercontent.com/52088444/185606273-df090b95-07bc-485b-b135-6c1b6a9daca5.png)

Eduf :Projeto Suficiente antecipadamente.

O resultado final do Sprint zero é ter informações que der condição para iniciar, ou  seja terá mais segurança.

A visão da aplicação serve para direcionar a equipe de desenvolvimento. Pois ela descreve o porque o produto está sendo realizado. Descreve qual o estado final desejado.
Vamos envolver o time de desenvolvedor, marketing, designer de produto, designer de interface e partes interessadas.


## Visão da Aplicação: O Que É?

Existem dois lados para a visão da aplicação que é  Visão ou valor de Negócios e Necessidades dos clientes ou dos User Roles.

Identificamos os papeis, as necessidades e através das necessidades vamos desenvovler os requisitos.

Na segunda parte identificamos os atributos do produto.
 - Requisitos funcionais:(O software foi feito para atendeer essas necessidades que são especificas para o tipo de usuario)
 Fazer uma chamada telefonica
 Enviar um email

- Requisitos não funcionais(olha tudo de maneira global, e são influenciados pela visão de negócio)
Performance(Desempenho do software)
Robustez( que se algo parar , tudo não pode parara)
Usabilidade


Os cuidados que temos que tomar no desenvolvimento da visão da aplicação:
-subestificação( especificar rapidamente com poucos elementos, não consegue ver o suficiente para desenvolver o software)
-Superespecificação( não perder muito tempo fazendo uma documentação detalhada)
- EDUF- Especificação suficiente( dar segurança com as informações para a equipe0


## Criar informalmente Users Stories

User Stories: norteiam todo o desenvolvimento de software, ela srá o guia para que a equipe de desenvolvimento irá fazer, por isso da importancia do User Stories.
As melhores US são obtidas através do PO e da equipe, o PO é muito importante nessa hora, As Users Stories são definidas em cima da Visão da aplicação.
- Dicas para criar as Users Stories

 Foco "no que fazer"( não em como fazer, pois o PO geralmente não tem muito conhecimento em desenvolvimento , por isso da importancia da participação do time de desenvolvimento.
Envolva o PO na escrita das User Stories. Ele é fundamental , é crítico, pois ele conhece o valor do negócio, conhece a linguagem do usuario, na linguagem do domínio do negócio, pois ele discute com usuarios, clientes.
 Manter as User Stories Curtas( devem ser curtas por que são um lembrete para conversação)
 Crie User Stories com base em : who(quem vai interagir com o sistema) , what(qual o objetivo do tipo de usuario com a interação com o sistema) , why (qual o motivo de star fazendo isso) isso ajuda o time de desenvolvimento, principalmente na hora de desenvolver os testes de aceitação, lembrando que why é opcional.
 Tendo why ajuda a criar os testes de aceitação, tendo who e what dá para levantar o tempo de desenvolvimento.
 
 ## Receita para criar User Stories
    
Essa receita ocorre na reunião onde vai definir as User Stories, essa reunião é feita comandada pelo o PO junto com a equipe. 

![image](https://user-images.githubusercontent.com/52088444/186547119-edece9f5-cbe8-4b85-8b6b-545e96dfead6.png)
Sempre vai existir um tipo de usuario, mas pode existir k tipos de usuarios. Ler a visão e ir obtendo os tipos de usuario.
Ex tipos de Usuarios:
![image](https://user-images.githubusercontent.com/52088444/186547242-da8fdf34-0a5d-417d-9875-3d352b843f36.png)
Objetivos do Usuario Admin
![image](https://user-images.githubusercontent.com/52088444/186547279-85fc14fb-9217-45ea-abb4-b5138fef9f74.png)
![image](https://user-images.githubusercontent.com/52088444/186547353-f40e3a6e-62d8-47e3-908f-58614a3dcac2.png)
No nosso exemplo o k é igual a 5
![image](https://user-images.githubusercontent.com/52088444/186547491-bbb46d2b-c5c5-45bf-a541-56c31bbd8dbf.png)
Estrutura:
![image](https://user-images.githubusercontent.com/52088444/186547507-cb3e0072-7483-4da7-a4db-666929cc5bf4.png)
ou fazer em uma linha
![image](https://user-images.githubusercontent.com/52088444/186547580-6e039d11-1e3d-4151-97ed-6fbf7cebca00.png)

## exemplo de como criar a receita do Exemplo Livros a jato

APLICAÇÃO: LIVROS A JATO
GRUPO: PO E GRUPO DE DESENVOLVIMENTO
PASSO 1: IDENTIFICAMOS OS USER ROLES
![image](https://user-images.githubusercontent.com/52088444/186547821-47cb8967-e707-466d-84d9-3921f766d42d.png)
![image](https://user-images.githubusercontent.com/52088444/186547841-dce2b979-1c0d-44d2-9862-eea6ed21e34b.png)
Todos os objetivos do visitante o cliente também possui como procurar ebook, listas ebooks, registra-se no site, e quando eu falo de cliente eu falo de cliente padrão e Premium mas as suas outras funções

User stories
![image](https://user-images.githubusercontent.com/52088444/186548026-336ff8e0-4022-474b-b79b-4287c43d0b13.png)

User Stories descritos acima são chamados de EPIC(EPICOS) pois são muito grandes, e são quebradas como mostra-se abaixo:
![image](https://user-images.githubusercontent.com/52088444/186548148-ca31765c-43ae-4954-afff-9f665a456583.png)
![image](https://user-images.githubusercontent.com/52088444/186548259-4d55d74c-793b-4b1b-a6a7-6adf86e441ad.png)

![image](https://user-images.githubusercontent.com/52088444/186548325-dc479ef9-1d70-4511-a017-f8a9a9d996f5.png)
        
![image](https://user-images.githubusercontent.com/52088444/186548350-a9513047-8762-4376-8941-8c3e9cdb2db8.png)
![image](https://user-images.githubusercontent.com/52088444/186548386-aa62393a-d284-4811-b2a6-a841df30b163.png)


## Análise Ágil: BDUF vs EDUF


 «Enough Design Upfront» (EDUF)  antes  do «Big Design Upfront» (BDUF) . Existe também o  «No Design Upfront» (NDUF) .
 
 ##  BDUF 
 
 Big Design Up Front é uma abordagem de desenvolvimento de software na qual o design do programa deve ser concluído e aperfeiçoado antes que a implementação do programa seja iniciada. É frequentemente associado ao modelo em cascata de desenvolvimento de software.
 
 A abordagem BDUF baseia-se na suposição de que todas as necessidades podem ser descritas com precisão desde o início. Em um processo complexo, descreve-se o que o resultado deve ser capaz de fazer, onde estão os possíveis problemas, etc. A implementação só começa quando tudo foi descrito detalhadamente.
 
Esta abordagem remonta ao tempo em que os problemas "simples" ou "complicados" (ver  Cynefin Blog ) dominavam e precisavam ser desenvolvidos. No entanto, os problemas a serem resolvidos hoje tornaram-se muito mais "complicados" ou mesmo "complexos".

A abordagem BDUF é difícil de lidar, porque as mudanças que ocorrem durante a implementação estão associadas a altos custos. Como resultado, muitas coisas sem importância ou necessidades insignificantes são incluídas para não sofrer custos adicionais posteriormente. Em última análise, isso leva a descrições ainda mais extensas e processos mais complexos.

Mas quais são as vantagens do BDUF ?

- Desde que esteja muito claro quais são minhas necessidades e como quero que meu resultado seja, essa é uma abordagem muito eficiente.
- Como tudo é conhecido, você pode obter uma boa visão geral de tudo desde o início e possíveis conflitos podem ser eliminados antecipadamente.
- Os custos podem ser calculados e conhecidos - isso dá segurança ao planejamento.

Quais são as desvantagens do BDUF ?

- Desalinhamento do projetado com o executado
- Surgimento de bugs
- Documentação desatualizada
- Desperdício de tempo (pois é detalhado o backlog do qual boa parte é descartada)
- Custo de mudança(É muito mais barato realizar mudanças enquanto os itens de trabalho são somente ideias ou hipóteses.)
- Estimativas falhas

O “BIG”, do Big Design Up Front, se refere a grandes lotes de trabalho que, em qualquer etapa de um projeto, tendem sempre a gerar desperdício.

Portanto, o BDUF não costuma apresentar nenhum tipo de benefício e não pode ser confundido com a falta de uma visão mais ampla dos objetivos do projeto, o que é extremamente valioso.

## NDUF(Nenhum projeto adiantado)

O completo oposto do BDUF é o NDUF e, portanto, a forma mais pronunciada da abordagem mais ágil. Você pode iniciar o desenvolvimento quase imediatamente sem ter que investir tempo em um projeto de antemão. Uma visão do produto e um backlog aproximado do produto geralmente servem como ponto de partida, que é criado em uma chamada "iteração zero" ou «Sprint Zero» na primeira iteração produtiva resp. O «Sprint 1» está sendo preparado.

Durante o desenvolvimento, novas entradas e ideias são constantemente adotadas e implementadas. Uma abordagem tão livre requer muita experiência. A maioria corre o risco de desenvolver arquiteturas instáveis ​​e investir recursos em desenvolvimentos que depois se tornam redundantes ou inutilizáveis.

Uma citação apropriada de Dave Thomas, um dos autores do «Manifesto Ágil»: 

"Um grande design na frente é estúpido, mas não fazer nenhum design na frente é ainda mais estúpido." (BDUF é burro, mas NDUF é ainda mais burro.)


## EDUF 

A abordagem EDUF diz duas coisas: por um lado, tanto quanto necessário - apenas as necessidades mais importantes (MVP "Minimum Valuable Product") - devem ser definidas antecipadamente e, por outro lado, especifica as necessidades em que ponto no tempo e em que grau de detalhe (cf.  Vision2Code, agilist ) deve estar disponível. É importante nomear essas necessidades, pois elas servem de orientação para o processo de desenvolvimento. No entanto, ainda há espaço para ajustes e adições em andamento.

Por que EDUF?

Combina aspectos de BDUF e NDUF
Através da determinação grosseira das necessidades, o escopo do projeto pode ser grosseiramente determinado e extrapolado das necessidades mais importantes para as demais necessidades (cf. estimativa relativa,  agilist ,  edorex ). Assim, é possível regular contratualmente o âmbito dos serviços, prazos de entrega e custos.
Ajustes e novas ideias podem ser levados em consideração continuamente.
Ambos os parceiros contratuais se beneficiam do que é aprendido durante o processo, já que o desenvolvimento é um projeto conjunto.

Com o BDUF, descrevemos todas as características do veículo como em um catálogo e rapidamente reduzimos que será um carro. Com a abordagem EDUF, fica claro que deve haver um veículo que cubra as necessidades mais importantes. Como eles são explicitamente satisfeitos só se tornará aparente durante o desenvolvimento, porque há mais de uma solução e pode não ser um carro.

O agile.agreement combina as vantagens dos dois extremos BDUF e NDUF usando o Enough Design Upfront. Isso torna possível realizar um  projeto ágil a um preço fixo ou Para obter um teto de custo e  ao mesmo tempo garantir que as  metas  (escopo aberto, tempo fixo e orçamento)  sejam cumpridas  .

![image](https://user-images.githubusercontent.com/52088444/187073608-704371b0-5564-404e-a1a3-31c7512f5f23.png)


BDUF(Abordagem Tradicional) 
Analise Inicial-> Requisitos
Antecipar todas as informações , e geralmente essa forma de desenvolver é muito rigida, e normalmente o software que você desenvolveu não é o que o cliente pediu.

EDUF(Abordagem ágil, projeto antecipado suficiente)
Não especificamos a mais, nem a menos, temos uma análise ágil. Só levantamos os requisitos que sejam suficientes para desenvolver o software. Ou seja essa análise Agil compõe o documento chamado visão da aplicação, e ao longo do tempo podemos mudar os requisitos, incluir novos requisitos, e isso é responsabilidade do product Owner.

- Coletar dados usando a visão EDUF( levantamento apenas do necessário)
Para obter a visão da aplicação é realizado:
Entrevistas, questionários, observação direta.

- Para refinar user stories criadas informalmente:
Posso criar workshops( oficinas com PO, Usuarios, clientes stakeholders, entender melhor, a conversação é onde refinamos)

- Entrevistas

Serão utilizadas na maioria de desenvolvimentos ágeis. 
Serão realizados entrevistas individuais ou em pequenos grupos. Lembrando que é importante usar o viés de Users Stories.
O nosso interesse é Identificar tipos de usuarios e suas necessidades e quais seus objetivos com o sistema.
Com essas entrevistas a nossa intenção é extrair problemas, soluções e restrições do ponto de vista do usuário.

O importante nesse tipo de entrevistas , nas coletas dos requisitos é usar o viés USSS:
PARTES who, what e why.

Muitas vezes precisaremos de questionários, devido o numero muito grande de usuarios, para poder atingir clientes, usuarios e stakeholders, lembrando que questionários não podem ser utilizados como única ferramenta, e sim como completo. Os mesmos devem ser bem escritos, identificar tendencias entre os usuarios.
Os formulários devem ser complementos de entrevistas, pois é necessários ouvir os usuários em seus locais, para ver quais ferramnetas ele está usando, quais dificuldades com a tecnologia, pode ser interface com o usuário, tipo o equipamento ambiente.

Ao final das coletas teremos uma grande quantidade de informação , e aprtir disso analisar e gerar a visão da da aplicação.
Ou seja os pilares que ajudam a  gerar a visão da aplicação são as: entrevistas, observação direta e questionários.

## Como utilizar o Wokshop para refinar as US que foram derivadas da visão da aplicação.

![image](https://user-images.githubusercontent.com/52088444/187074530-d34c7ad0-e60e-4bd6-a9e2-aace868dbc30.png)

Nessa parte nós queremos o suficiente(EDUF).

Os workshops são usadas para exainar e refinar user stories já criadas.

O que fazemos nos Workshops?

Como podemos melhorar a busca de livros?
Que informações adicionais o usuário poderia precisar?
Por que o cliente Premium tem que pagar apenas pelo o paypal?

Examinar e quebrar user stories do tipo epic.
Definir os Whys e ATs (teste de Aceitação)
Mapear USsa a fluxos de Usuários.


## Mapeamento de US nos fluxos de Usuarios;

Fluxos de Usuarios(são todos os tipos de interações que o usuario pode ter com a aplicação);
O fluxo começa desde quando ele faz  login no website, procura o livro, e ler o ebook.

![image](https://user-images.githubusercontent.com/52088444/187074837-2bd08b79-0091-49e7-a61e-911bb046af7e.png)
*Varios tipos de fluxo que o cliente pode ter 

Vamos analizar o fluxo Acessar livros pagos;

![image](https://user-images.githubusercontent.com/52088444/187074895-5f5ed2c3-c23e-42f5-94ab-e0e6aa75c8a6.png)
*eu posso acrescentar novas Us ao fluxo.

Ex: 

![image](https://user-images.githubusercontent.com/52088444/187074946-c66efcec-3434-4107-8779-89793676bff2.png)

Backlog de produto é uma lista de User Stories em que você vai definindo a prioridade através do BV;

Bussiness ValuE dar a prioridade(BV);


## Programação em Pares(Pair Programmer)
        
![image](https://user-images.githubusercontent.com/52088444/187075799-7884de99-2b8a-4c15-8894-8adf4a19cc8c.png)
Duas pessoas trabalhando na mesma tarefa. 
        
O piloto é o programador , ele foca na linha de software que está escrevendo, sintaxe da linguagem e etc, e também temos o co-piloto possui uma visão mais ampla do contexto, classe, software, próximos passos e etc, ele tem visão global do software ele ajuda o piloto quando ele precisar.
O que ganho utilizando programação em pares?
O desenvolvimento ágil possui diversas técnicas que exigem disciplina como criação de testes automatizados e refatoração.
        
Essa técnica evita que desenvolvedores percam o foco e se distraiams com outras coisas.
        
Existe transferencia de conhecimento técnico e do negócio entre pessoas da equipe.Existe uma melhora significativa na qualidade do código , visto que a revisão de código aconteça de forma simutânea a sua criação.
        
## Pareamento com qualidade
O co-piloto não deve se colocar como passivo e ficar só observando o que o outro está fazendo. O piloto também não deve sair programando sem dar oportunidade do outro participar.

O primeiro passo quando uma dupla vai trabalhar é discutir como a funcionalidade deve ser implementada. Muitas vezes, só explicando sua ideia para a outra pessoa, ela já amadurece.

O piloto deve procurar explicar o código que está criando para poder receber feedback. Os desenvolvedores podem e devem trocar de posição quandoa acharem mais produtivos.
 
 ## Questões sobre programação em pares
 - Não perder a privacidade
 - não perder o foco
 - prover um ambiente individual e mais pessoal longe do local em que se desenvolve em pares;
 - tenha consideração por seu par;
 - o ideal é que seja rotação entre os pares. Pode trocar a cada dia;
 - Evitar ilhas de conhecimento,  ou seja deve ser feito rotação para desenvolver.
 - é um mito achar que programação em pares se perde produtividade, se ganha muito na redução de bugs  e a produtividade a longo prazo é pouco afetada;

 ## Como introduzir pair programmer
 Se houver resistencia, proponha um projeto pequeno para utilizar como piloto e proponha medidas para avaliar os resultados. Ajude os mais tímidos, fazendo os mais experientes quebrarem o gelo e estimular a interação.
        
 
 ## Variações em programmer Pair
Pair Development-> 2 pessoas e uma tarefa(task)
Eles decidem em fazer tarefas com Pair Programing , ou individualmente em paralelo. A ieia do Pair development é dar responsabilidade compartilhada. No caso de tarefas individuais , um pode testar o código feito pelo o outro.
        
Não é necessário parear o tempo todos para se obter vantagens técnicas. A autonomia é do desenvovledor. 
        
Mob Programmimg
É uma técnica em que mais de tres pessoas podem trabalhar no programa.
Ou seja todo o time senta em frente a uma máquina e um projetor e trabalha em cima do mesmo problema. A ideia é que todos participem .
é uma forma excelente de disseminar um conhecimento importante para toda equipe.
é uma forma de superar desafios muito dificies ou tomar decisões muito importantes.
        
## Escrevendo users stories mais efetivas

Escrevendo User Stories Mais Efetivas
Nós mostramos como definir, de forma informal, user stories nas seguintes
videoaulas: Dicas para Criar Informalmente User Stories, Receita para Criar
Informalmente User Stories, Exemplo de Criação Informal de User Stories: Parte 1 e
Exemplo de Criação Informal de User Stories: Parte 1. O papel dos 3 Cs, em especial
da Conversação, é essencial para se produzir código de qualidade a partir das user
stories desenvolvidas informalmente. Mas nem sempre isso acontece de forma fácil.
Muitas vezes as user stories não são muito boas e tornam o trabalho do time de
desenvolvimento mais difícil e menos produtivo.
Bill Wake, com objetivo de tornar o processo de definição mais formal e tentar
garantir user stories mais efetivas, que facilitem o trabalho posterior de
implementação, propôs o INVEST, um conjunto de diretrizes mais formais para
definição de user stories.
Definição
INVEST é um acrônimo que ajuda a lembrar 6 critérios ou diretrizes amplamente
aceitos. Forma, de fato, uma lista de verificação para avaliar a qualidade de uma
história de usuário. Se a história não atender a um desses critérios, a equipe pode
querer reformulá-la, ou mesmo considerar uma reescrita da história, que muitas vezes
se traduz em rasgar fisicamente o velho cartão de história e escrever um novo.
Assim, uma boa história de usuário deve seguir as seguintes diretrizes:
“I” – Independente de todas as outras user stories quanto ao valor de negócio (BV
ou Business Value)
“N” – Negociável: não é um contrato definitivo para o requisito; de fato, é apenas
o ponto inicial!
“V” – Valiosa para o cliente, PO ou stakeholder: O BV é dado pelo PO, em nome
de clientes e stakeholders
“E” – Estimável, com uma boa aproximação;
“S” – (Small) Pequena, de modo a caber dentro de uma iteração
"T" – Testável: em princípio, mesmo se ainda não houver um teste especificado
para ela
Explanação e Exemplos

## Time Scrum

Geralmente nós temos 3 tipos de pessoas
- Scrum Master(SM) - Ele está aqui para conduzir o processo do scrum e XP, ele é que vai garantir que todos os valores e pilares sejam seguidos, pelo o PO , time , stakeholders e clientes.
- Product Owner(PO) -Ele está interessado  no que fazer (what?)
- Time de Desenvolvimento- está preocupado em como fazer (HOW)

## Características dos times scrums
- Time auto-organizavel (escolhe a melhor forma para completar o trabalho);
- Time multifuncional(competencias necessárias para completar o trabalho, a equipe deve ter diferentes competências)
- A Equipe não pode ter menos que 3 ou mais que nova
- entregas iterativas e incrementais, maximizando as oportunidades de feedback, ou seja se os testes de os testes de aceitação que eles tinham previstos foram bem realizados e que aquele resultado realmente ficou de acordo com o que eles esperavam, okay. Mas e se não ficar? Se não ficar, você tem o feedback, e isso vai ser útil pra você tomar novas decisões. E dentro dos pilares do scrum e XP que você tem essa questão da inspeção e da adaptação, você verifica e vê que a coisa não deu certo e adapta. Mas você não fica fazendo isso de qualquer jeito. 
- Versão parcial potencialmente funcional do produto a cada sprint





## Papel do PO
O PO serve como ponte entre usuario/stakeholder e time de desenvolvimento. PO responsável pela Visão da aplicação. As Users Stories pode ser escrita pelo o PO, mas pode ser sugerida por todos da equipe, e aprtir dai eles vão para o backlog, ele prioriza o backlog e quais as US serão desenvolvidas primeiro. 
        
![image](https://user-images.githubusercontent.com/52088444/187194857-5afc42a0-11bc-4304-b14c-fdd9730adf86.png)

O PO pode ou não aceitar a implementação da Users Stories. Na hora da reunião de sprint Review/demo ELE PODE ACEITAR OU REJEITAR, OU ACEITAR PARCIALMENTE CADA INCREMENTO DE PRODUTO;
        
## Time de desenvolvedores 
As principais características do time de desenvolvimento é que ele possua 7+-2 ou seja 3 grupos de dois. Quanto mais gente maior interação e maior a complexidade. O time deve ficar localizado em uma sala , apenas. O PO fica na sala do lado do time. O time Scrum é multifuncional, várias tecnologias /competencias. Auto organizado, auto-gerenciado, pode alterar o tipo de metodologia, o PO e Scrum Master não mandam no time. Se negocia os compromissos com o PO. o TIME DE DESENVOLVIMENTO É QUEM DECIDE.
![image](https://user-images.githubusercontent.com/52088444/187195997-e00d337f-40cc-482e-8f60-f4d18caa0d04.png)

Tem autonomia para atender aos compromissos assumidos, desde que eles cumppram o compromisso e passem pelos os testes de aceitação.
Responsabilidade do time como um todo;
        
## Scrum Master
O papel do Scrum Master e suas características. Ele se preocupa com o processo do scrum/xp e como o processo está sendo desenvoldido se todos compreenderam , ele treina o PO e o time sobre as boas práticas do scrum e xp, treina usuarios, clientes, stakeholders. O papel dele é remover qualquer coisa que possa impedir o desenvolvimento. Exemplo de empedndimentos, inserir um novo software, relacionamento entre pessoas, inserir um novo hardware. Todos relatam pra ele, ou ele percebe pela observação e pelo feedback que ele tem, ele vai então tentar remover esses impedimentos. Outra coisa: todas as reuniões, praticamente, do Scrum, ele que vai ser o facilitador. Veja, ele não é o que manda, não; ele facilita. Geralmente é o SM que conduz a reunião. Ele quem zela pelas as práticas do scrum e XP. 
Ele tem o papel de proteger o time de interferencia externa, não pode conversar com a equipe , se for aspecto tecnico é com o PO, se for aspectos de bem estar é com o Scrum Master, geralmente nas reuniões. O scrum master não é chefe, todos tem o mesmo nível, o SM ele facilita, ele não é o gerente. O SM conduz a melhoria continua, atravéz da observação, backlog, ele verifica se a velocidade do processo através dos stories, reuniões formais do scrum/xp. Melhoria do software significa: melhoria de qualidade e melhoria no tempo. 

## Implementando uma User Story
        
O que significa implementar uma User Story? User story é composto por what, who e why. What corresponde ao requisito que queremos implementar.

![image](https://user-images.githubusercontent.com/52088444/187198188-a68da35c-157f-447e-9434-6aaf88f7c0be.png)
![image](https://user-images.githubusercontent.com/52088444/187198302-27f1d16b-692d-42ce-8ede-2466d0e2862e.png)
![image](https://user-images.githubusercontent.com/52088444/187198413-84f7f554-41f6-41a0-b6da-737433520ac6.png)
*Aplicar Testes de Aceitação(AT's') Para implementar uma users story nós temos que quebrar em tarefas       
        
## O que é task (no contexto de XP e Scrum?
        
Usr Story: descreve uma funcionalidade que o PO gostaria de ver em seu produto.  Normalmente, isso tem valor que a gente chama de valor de negócio. E além disso, a User Story está na linguagem do cliente, do Stakeholder, do Product owner. O que ela específica, o que deve ser feito. Já uma tarefa vai especificar como é que eu vou implementar essa user story. Ou seja, ela vai especificar como é que nós vamos alcançar com que o sistema faça, aquilo que o usuário determinou através do What, dentro lá da User Story. 
![image](https://user-images.githubusercontent.com/52088444/187199192-2d3bca3d-82ab-4b22-be47-801825b15f5d.png)

Enquanto a US é definida pelo o PO. As terefas são desenvolvidas pelo o time de desenvolvimento e geralente eles não entendem a linguagem do time.    
        
## Característica de uma Task?
        
Uma tarefa não deve levar mais tempo que um dia. A tarefa será estimada em horas. Crie tarefas de tamanho apropriado, quebre-as em tamanhos menores. e que a ideia seja que a tarefa não seja menor que uma hora. Não defina tarefa para teste de Unidade, você já usa TDD, o TDD já consiste ter ciclo que implica fazer testes de unidade. Inicialmente o teste falha, depois o teste funciona e depois a gente faz refatoração. Então teste de unidade codificação, refatoração, isso não fica como uma atividade à parte. Ela fica dentro de uma tarefa que é escrever o código, de acordo com o TDD.    
        
## Diferenciar User Story de Task        
Por exemplo a user story está, ela é o requisito. Então ela caracteriza o que deve ser feito pelo sistema. Já a task, ela é como isso vai ser feito.
        
Nós vamos ter essa oposição: a user story com o what, o que, e a tarefa com o how, o como. Outra característica é que a user story ela contém muitos tipos de trabalho que devem ser executados. Então por exemplo uma user story para ela existir, vai ter que ter todo trabalho de programação, de testes, projeto de banco dedados, projeto de interface com o usuário, análise e etc. Ou seja, você vai ter que fazer muita coisa, no final você vai ter que fazer bastante coisa, enquanto que a task, ela contém apenas tipo de trabalho, ou seja, enquanto na user story a gente colocou que todos os itens eram "e" lógico do Java, aqui nos estamos pondo "ou" lógico do Java. 
Então vai caracterizar que a tarefa, ela vai ser só alguma coisa sobre pouco de programação, pouco de teste ou vai ser pouco de testes ou vai ser, é "ou" exclusivo na verdade, porque ela vai conter apenas tipo de trabalho uma tarefa. Outra coisa que caracteriza a user story, como ela escrita na linguagem do domínio da aplicação. 
Ela é escrita na linguagem que o que o usuário, cliente, qualquer stakeholder entende. Então como ela escrita nessa linguagem que todos, daquele domínio da aplicação, todos entendem, você pode ter feedback deles, do que você está pretendendo fazer. Já a tarefa ela é parte da user story, mas ela é definida na linguagem do time de desenvolvimento, uma linguagem técnica. Então ela não vai permitir feedback do PO ou do cliente ou do usuário ou dos stakeholders, ou seja, ela está escrita numa linguagem técnica. Então não vai existir feedback, nesse sentido, de outras pessoas externas. Como nós havíamos dito, uma user story ela divide-se num conjunto de tarefas. 
        
        
 ![image](https://user-images.githubusercontent.com/52088444/187200621-9eee40ff-8f73-4b7e-99a6-c3765f40812b.png)
       
 ![image](https://user-images.githubusercontent.com/52088444/187200656-a8b13f84-f926-4cba-9dff-ff6f4ae0cb2b.png)
       
## Tipos de Tasks
Maneira de facilitar quebrar as Users Storys em tasks.
        
- Tipos de tasks:
Codifique isso
Projete aquilo
Crie dados de teste para isso e aquilo        
Automatize aquilo outro        
etc...       
        
- Arquitetura em camadas( Se o software tiver essa arquitetura)
APRESENTAÇÃO(IU)
REGRAS DE NEGÓCIO
INFRA & PERSISTENCIA(BD)        
        
        
![image](https://user-images.githubusercontent.com/52088444/187215023-75bb2d3c-7502-49aa-b429-6c2678ceeca8.png)   
![image](https://user-images.githubusercontent.com/52088444/187215199-410e9e7f-76b9-422f-95e2-816ec37854ca.png)
Já pela regra de negócios:
![image](https://user-images.githubusercontent.com/52088444/187215326-2b999a44-994c-4a5f-919c-e542e6b3d7ed.png)
![image](https://user-images.githubusercontent.com/52088444/187215484-4172d725-a08f-40fa-b085-0481fa059133.png)
Usando a arquitetura camadas isso facilita muito eu criar tipos de tarefas os mais apropriados para cada user story que eu precisar implementar.   
        
## Benefícios em Quebrar User Stories em Tasks
Não é obrigatório quebrar as US em tASKS. Mas é fortemente indicado que se quebre. Principalmente quando você esta em um time que não está costumado, é super indicado quebrar sistematicamente as US em Tasks , ela ajuda a aperfeiçoar as estimativas em horas dessas tarefas e aí você pode analisar se as tarefas foram feitas em mais ou menos tempo. Promove maior colaboração do time.Dividindo em tarefas ajuda a treinar jovens desenvolvedores. E o mais importante as tasks ajudam a medir o progresso.
        
## Erros em Planejamento de Software
        
Usando TDD a refatoração, o software se torna mais flexível e aceita mudanças mais fácil.        
Tentar enxergar além do que você consegue. Não é possivel planejar a longo prazo e sim a curto prazo, 
        
![image](https://user-images.githubusercontent.com/52088444/187218132-04880b87-36bb-449f-aa42-38ffb41ca77c.png)
Impor deadline, (tipo essa tarefa deve ser feita em 1 hora). Quem faz a estimativa não é quem faz o software, quem sabe o tempo é que faz o software.
Fazer um planejamento que ninguém vai alterar, ou seja tem que fazer um planejamento sabendo que vai mudar.O planejamento é como um guia, uma referencia e não como algo estático.
        
## Priorizando User Stories        

Técnicas:
        
Planning Game: o objetivo é entregar software que agrega mais valor e o mais rápido possivel. Ou seja de todas as US quais são as mais importantes de serem incluídas com maior priorização.         
        
![image](https://user-images.githubusercontent.com/52088444/187219859-eb317d1b-b9ec-4d73-9524-169c62ad16e0.png)
![image](https://user-images.githubusercontent.com/52088444/187219917-17dfce39-3eaa-418d-a397-6d04e6c2e987.png)
![image](https://user-images.githubusercontent.com/52088444/187220201-3a6f1a97-fd42-4aa4-a313-2ca169a73da0.png)
Para melhor visualização é usado a tabela baseada em Fibonnaci
![image](https://user-images.githubusercontent.com/52088444/187220381-fabcec35-d4a2-4af4-8635-4c5856f77c63.png)
        
![image](https://user-images.githubusercontent.com/52088444/187220496-d3fca01f-00dc-4617-a248-f7addb06feee.png)
       
 Mas esses valores, eles te dão uma referência para você saber o quê que seria mais prioridade, de você estar incluindo aí numa iteração. Então, depois que essas user stories são ordenadas, elas formam backlog do produto, que as que estiverem na frente vão fazer o backlog da sua iteração, para serem executadas na sua iteração.        
        
## Estimando User Stories e Tarefas

A estimativa de User Stories é  muito importante para termos ideia de quais US de maior prioridade cabem dentro de uma iteraçao.        
A primeira coisa a ser feita é uma estimativa relativa entre as US.        
        
Se uma US for muito Grande, quebre em menores para poder estimar melhor.        
Pegue as US de maior prioridade que cabem em uma itteraão, e divida elas em tarefas.
Faça agora a estimativa de cada uma das tarefas em horas ideiais(sem interrupções).        
Quando começamos a implementar o ágil é normal erras nas primeiras iterações, mas com o passar do tempo as suas estimativas ficam mais precisas;        
        
        
- Planning Poker: pode ajudar bastante a fazer a estimativa e para fazer avaliação de risco.        
        
Quanto tempo vc estima para essa User Story?        
        
![image](https://user-images.githubusercontent.com/52088444/187224066-010ecd37-863d-4808-90fb-3fb6abd4fd61.png)

Ou seja cada um escolhe e  mostra a carta com a sua opinião. Se as difernças são grandes aparentemente não houve entendimento da US, ou seja a equipe não está alinhada, ele vão jogando até chegar num consenso. Se alguém não consorda tem que mostrar os motivos e joga-se novamente as cartas até chegar a um consendo. 
        
![image](https://user-images.githubusercontent.com/52088444/187224614-6635c0e9-ca05-4ee4-9139-f790dcba7844.png)
Números altos indicam qua US precissa ser quebrada. Ou seja é necessário quebrar ela em tarefa . Se der 0 quer dizer que a US pode ser feita em minutos. Caso mostre ? muitas vezes a US não foi bem compreendida.        
        
Quanto maior a dificuldade para estimar , maior o risco da US. Quanto mais fácil chegar no consendo quer dizer que a equipe entendeu.        
## Dinâmica de uma Iteração                
O planejamento é executado em iterações curtas em intervalor de tempo(time box) bem definidos. O scrum chama essa iteração de Sprint.  A iteração não tem essa de esticar o intervalo é curto. Para ser uma Sprint de Scrum : Precisa ser curta(1 semana, 15 dias ou 1 mês). Precisa Entregar valor, ou seja o cliente precisa ver, aprovar , dar  feedback. Precisa conter um ciclo de desenvolvimento completo.       
A  de User Stories vai de acordo com a velocidade do time.         
 a execução das tarefas, elas tem que ser acompanhadas durante a interação. Uma forma de você fazer isso, por exemplo, você tem ali a User Story, você tem as tarefas dela, você tem as horas ideais que elas foram estimadas, quantas horas foram efetivamente trabalhadas e a restante. Repara que o primeiro ali, ele cumpriu o que estimou, ele estimou dez e conseguiu fazer ali o dez. O banco de dados, note que ele estimou oito e trabalhou 12 e conseguiu terminar. No controller aconteceu uma coisa diferente, ele estimou 12 mas seis ele conseguiu terminar. Olha o caso do último ali, por exemplo, ele estimou sete, ele trabalhou cinco só que ele estima que para terminar aquela tarefa ainda faltam cinco. Então, a gente sempre trabalha com o quanto que está faltando. Então, lembra que eu falei daquela questão lá das porcentagens e tudo mais? Então, essa é uma forma melhor de fazer, ao invés de falar quantos porcento você já fez. Você pergunta quantas horas ainda faltam para terminar. Pode ser que você tenha estimado cinco e agora faltem dez. Você começou a trabalhar e viu que o problema era bem maior. Não tem problema. O importante é a equipe estar ciente disso e ter tempo suficiente para agir cima desse imprevisto que aconteceu.
        
![image](https://user-images.githubusercontent.com/52088444/187227381-16f498cd-1eab-4ec8-aeed-1945b4c0ec4e.png)

Então, todo o controle ele acontece cima do quanto já foi trabalhado e o quanto que ainda falta.
        
![image](https://user-images.githubusercontent.com/52088444/187227860-2de426e7-f7bf-4392-af72-a19e3086f7d2.png)
Outro tipo de quadro Kanban, eu posso incluir novas colunas        
![image](https://user-images.githubusercontent.com/52088444/187227985-e21c37f9-822a-4a4a-bb77-d0d4f5612dbf.png)

![image](https://user-images.githubusercontent.com/52088444/187228131-7a37388b-85eb-453c-bee4-f5faef492534.png)
No mínimo uma vez por dia atualizamos os dados. Se percebermos que o Burndown Chart está saindo do controle é necessário replanejar as informações e começar novamente.         
![image](https://user-images.githubusercontent.com/52088444/187228792-ae59e9f6-8d84-468c-a0a4-1c9496bce41a.png)

## Como não fazer Diagramas
        
 - os diagramas podem ser muito úteis, só que as formas que eles são utilizados, às vezes, não são adequadas.
 - Criar diagramas só por que o processo diz que precisa criar não é adequado, pois é necessário saber o objetivo daquele diagrama       
 - Não saber as necessidades de quem vai utilizar o diagrama, muitas pessoas precisam de algo simples e o restante será disperdício.       
 - Não saber o perirdo em que aquele diagrama precisa existir e a frequencia que precisa ser atualizado.       
 - Adicionar detalhes demais, tira o foco do que realmente precisa, esse excesso de detalhes dificulta o entendimento.       
 - Utilizar ferramentas complicadas demais , enquanto algo simples teria resolvido.       
Os diagramas são importantes mais que precisam ser utilizados de forma inteligente e alinhados com a necessidade do projeto.        
        
## Como utilizar diagrama dentro do contexto ágil
        
O diagrama não vem do processo como existe no diagrama tradicional, o diagrama tem que surgir da necessidade da equipe, um exemplo não consegui entender as relações do BD. 
        
- Qual o objetivo do Diagrama?     
 Pensar sobre o problema. Comunicar com a equipe( como por exemplo como será o BD, qual a abordagem do BD, como será a arquitetura?), Criar documentação de software.       
- Quem é o publico?
Você mesmo , sua equipe, outra equipe, requisito do cliente.        

- Como e onde fazer?        
No quadro branco, em ferramentas sofisticadas, em ferramentas simples...        
ex: Icon finder, LucidChart        
        
- Qual o ciclo de vida do diagrama?      
fazer e jogar fora( apenas para informar a equipe, não precisa necessariamente virar uma documentação)        
será guardado da forma que foi feito, contanto que a equipe seja comunicada, e que as atualizações não interferam nas informaçoes principais.         
Será atualizado com frequencia(as vezes o cliente/equipe necessita que o diagrma seja contatemente atualizado);       
- Existem outras decisões:        
Quais diagramas utilizar? qual o nível de detalhe? qual será o escopo?        
Lembrando que investir tempo e recursos em umm diagrama é uma decisão da equipe. Argumente com a equipe pois as vezes não vale a pena fazer um diagrama tão elaborado.        
        
- Se documentar o software com diagramas for um requisito do cliente, trate isso como uma funcionalidade do software. Da mesma forma que você vai planejar as entregas do seu software, você também vai planejar as entregas dos seu diagramas.        
        
## Onde Entram TDD e Refatoração?        
        
Diagramas trabalham na organização geral das classes e o TDD no design interno e da API da classe        
        
O diagrama pode ser utilizado como uma forma de explorar o problema.        
        
Com o diagrama se pensa em uma visão mais global da solução. O TDD e a refatoração fazem a modelagem mais detalhada.  
com o TDD e a refatoração você vai fazer aquele design mais detalhado, por exemplo, quais os métodos que a classe precisa ter, como que vai ser a construção dessa classe, tudo isso daí pode ser definido no TDD e no diagrama você procura ter aquela visão do todo, como que as classes se conectam e etc, até mesmo pra você poder saber quais mocks você vai precisar criar nas suas classes. E aí, é, baseado no diagrama, você pode, por exemplo, começar refatorando o código existente. Muitas vezes a gente precisa refatorar pra abrir espaço pra nova funcionalidade que a gente precisa.        
        
##   Princípios da Modelagem Ágil      
        
O 1° principio é criar software funcionando.
O objetivo secundário é tornar essa entrega de software sustentável.        
Se um diagrama ajuda na comunicação/consulta vale a pena o investimento.        
Crie seus diagramas focados no seu trabalho de agora, e vá incrementando quando necessário.        
Foque no agora, não perca tempo tentando prever requisitos futuros, que ainda podem mudar.      
  
## Scrum&XP: Processo Adotado
        
- O Processo Proposto        
        
Sprint zero(planejamento ágil do projeto- usando eduf) -> Sprint Cycle (Desenvolvimento Agil do produto - posso ter de 1 a um numero indeterminado de sprints) - Produto entregue(Sprint final)        
![image](https://user-images.githubusercontent.com/52088444/187252741-a1e6b01c-e20c-4be4-b23b-74e455d4cb88.png)
Então, cada sprint vai ter esse conjunto e a gente chama isso então de desenvolvimento Ágil de produto, porque nós estamos usando o framework do Scrum e desenvolvendo usando o XP. Basicamente, o TDD.
        
O processo macro do nosso Scrum&XP é composto apenas de duas partes. Sprint zero que eu faço planejamento Ágil e depois conjunto de sprints que vão implementar aquilo que tinha sido inicialmente definido no Sprint Zero. E, basicamente, seria a visão da aplicação e o backlog do produto. E a cada sprint, nós iremos colocar novas user stories nesse backlog, e iremos construindo funcionalidades ao final. E eu tenho o produto entregue.    
   
        
## Planejamento Inicial: Sprint Zero        
        
![image](https://user-images.githubusercontent.com/52088444/187253627-19b80071-49b3-40df-a974-7c81fd959fda.png)

        
![image](https://user-images.githubusercontent.com/52088444/187253786-1b172701-b8d4-45e4-be22-43b946d0a20d.png)
![image](https://user-images.githubusercontent.com/52088444/187253867-2dcaf0e1-c320-4101-ab9c-62deeff8b52a.png)
- SERIA INTERESSANTE ANTES DE COMEÇAR A sPRINT 1         
![image](https://user-images.githubusercontent.com/52088444/187254151-6bbe306b-92ce-408a-afec-e89c4b5f4813.png)
        
        
## Estrutura de Eventos de um Sprint
        
 eventos que podem ocorrer Sprint e essa estrutura de eventos. cADA sPRINT PODE TER DE 1 A 4 SEMANAS, Usualmente 2 semanas 8 horas por dia, 5 dias por semana.        Sprint planing. Basicamente para o sprint planning que é o planejamento que você vai fazer para aquele sprint. O planejamento significa você escolher as user stories que você vai desenvolver, se comprometer que vai desenvolver esse conjunto de user stories quebrar essas user stories tarefas e o grupo escolher as primeiras tarefas, as de maior prioridade para serem desenvolvidas. Normalmente a regra é que sejam duas horas para cada semana. O sprint é de duas semanas, então o sprint planning vai ter quatro horas, se fosse de mês seria dia inteiro.
 ![image](https://user-images.githubusercontent.com/52088444/187254456-a52f35e7-d9d7-4907-852f-11796f65bf72.png)
       
Outro tipo de reunião que existe é a DS-> Daily Scrum.  ou reunião diária do Scrum. Ela é uma reunião bem pequena e rápida, ela é de 15 minutos. E é sempre de 15 minutos.Nela se discute o que cada elemento do grupo vai falar sobre o que tem feito, o que vai fazer, seus problemas e impedimentos que estão ocorrendo. Ela geral, todas essas reuniões são gerenciadas pelo Scrum Master. é para ser discutido rapidamente, mas é uma oportunidade muito boa de se levantar problemas. Se tem algum problema que não dá para resolver alí, aí é outra questão, mas ela só dura 15 minutos. 
![image](https://user-images.githubusercontent.com/52088444/187254793-f3b2394e-5f8b-43ff-8893-6b489f931210.png)
 
![image](https://user-images.githubusercontent.com/52088444/187255143-895461a9-bd4c-4b53-b413-36c499772627.png)
a sprint review, a revisão do sprint. É onde o projeto que foi codificado desde do primeiro dia do sprint até o último dia, é onde o time vai apresentar o que desenvolveu, fez os testes de aceitação, está confiante de que o produto está de acordo com o tinha sido definido pelo PO lá nas user stories e vai apresentar. É uma reunião que é aberta para o PO, que vai gerenciar, ela é aberta para o PO e stakeholders interessados no assunto, diversos são convidados e o PO é que vai validar, confirmar. É nesse momento que ele vai confirmar se as user stories foram implementadas de acordo. com o que ele tinha definido. Ou então pode ser que não aceite, ou o teste de aceitação não foi adequado, ou se esperava uma coisa e era outra.
        
![image](https://user-images.githubusercontent.com/52088444/187255879-583d7b04-3059-4794-861c-a0538ba19fbc.png)
Todas as reuniões que falamos estavam basicamente envolvendo o processo de desenvolvimento, como   a sprint Planner que planeja o que você vai fazer no planejamento,  a Daily Scrum que verifica o que está aconecendo no desenvolviemento, o Demo/sprint review vou mostrar se alcançou ou deixou de alcançar.      
E a retrospectiva tem a ver com o processo de Scrum e XP é nessa hora que nós vamos analisar se nós estamos seguindo direito todo esse processo que nós estamos mostrando. Então normalmente o demo leva duas horas para ser feito e a retrospectiva de duas semanas leva menos de duas horas. O demo normalmente corresponde a uma hora por semana, o sprint é de duas semanas então nós vamos ter duas horas. O sprint é de quatro semanas, então nós vamos ter quatro horas para o demo. A retrospectiva é sempre pouco menos,  por exemplo aqui e geralmente se coloca uma hora e 45 minutos no dobro seria o seu dobro de tempo correspondente. Seria três horas e meia,
Vamos relembrar aqui então agora essa questão da reunião do daily scrum, o scrum diário. Sobra-se muito pouco tempo aqui né para ser feito alguma coisa por causa dessa reunião então muitas vezes essa reunião pode não existir. Ou então ela vai existir para se tratar basicamente do que vai-se fazer para a apresentação e a retrospectiva.     
![image](https://user-images.githubusercontent.com/52088444/187258598-fab173d9-b5bc-4787-9cc0-ad6fde4ad701.png)    

Usando o XP se quiser usar o Pear Program eu vou usar o desenvolvimento contínuo, integração contínua, eu vou usar o TDD nesse desenvolvimento daquilo que foi planejado. Eu vou trabalhando em cima do que? Das tarefas. As tarefas que eu quebrei as user stories tarefas é o que eu estarei usando, então esse vai ser o meu desenvolvimento que no final eu vou ter uma funcionalidade entregue, vou ter incremento que vai ser as funcionalidades definidas pelas minhas user stories, que eu acabei de implementar testar, fazer os testes de aceitação e demonstrar para o PO e stakeholders. 
        
        
## Fase 1 do Sprint Planning – Parte 1        
        
No sprint planning apenas o PO, o product owner, o scrum master, e o time de desenvolvimento é que fazem parte. O scrum master tem papel essencial todos os tipos de reuniões, ou cerimonias, ou eventos como o sprint planning. É ele que vai comandar, ver a aderência dos membros que estão participando da reunião relação ao Scrum e XP, toda essa, os rituais, os eventos todos, se estamos cumprindo corretamente.
No nosso caso do sprint planning de duas semanas ela vai ter uma duração de quatro horas. Normalmente são duas horas por semana do sprint. Então se o sprint tem uma semana o sprint planning, o planejamento, vai ser de duas horas, se tem três semanas vai ser de seis, se tem quatro semanas vão ser oito horas        
        
O product backlog, também chamado de PBL, quem é dono dele?  É o PO, o product owner, é o responsável pelo product backlog. Que nada mais consiste do que ter todas as user stories que foram definidas lá no sprint zero, e depois, ao longo dos sprints, todas as user stories que ainda não foram implementadas. É papel muito importante de gerenciar isso. O product backlog é muito dinâmico, vão entrando e saindo estórias. Algumas estórias saem porque vão ser desenvolvidas, implementadas, outras estórias saem porque o product owner diz que não faz sentido mais ter aquele tipo de user story, e novas estórias vão entrando, novas estórias vão entrando   ![image](https://user-images.githubusercontent.com/52088444/187260999-29926a2a-b4fc-4fa5-b0d6-c5e47cfa04b0.png)
![image](https://user-images.githubusercontent.com/52088444/187261519-498019a9-f435-4f9a-a364-4a93416c1e27.png)
     
O PO adiciona novas User Stories,        
As US novas são colocadas no topo  na pilha de US que tem o BV      
![image](https://user-images.githubusercontent.com/52088444/187261946-e899bbc0-87dc-40ca-bafb-30235e8bdecc.png)
Procedimento como fazer para introduzir novas US        
![image](https://user-images.githubusercontent.com/52088444/187262017-98422d7f-6fc7-4625-9609-0b9347ff6fd9.png)
 
![image](https://user-images.githubusercontent.com/52088444/187262314-0244e95c-c84d-4983-b292-2952ee0f8093.png)
        
## Fase 2 do Sprint Planning
Na fase 1 fizemos uma avaliação do Product Backlog, com todas as Novas Users Stories, as mesmas estão no topo       
![image](https://user-images.githubusercontent.com/52088444/187262732-bc1c508d-32de-466c-ad26-e1918f11cf73.png)
![image](https://user-images.githubusercontent.com/52088444/187262864-370246aa-d8c3-4e0f-b5a8-853c79c75c8a.png)
Com essas novas inclusões é necessário         
Então nesse momento isso ajuda a mais uma conversa, uma conversação, entre o PO e o time, para esclarecer as user stories de tal forma que seja possível definir essa parte Why. Outra coisa que também é fruto dessa conversação, e que também não era obrigatório definir anteriormente, eram os testes de aceitação, eu estou chamando de Acceptation Tests, ou ATs. Mas os testes de aceitação, lá no sprint 0, não era obrigatório fazer pra todas as user stories, por questões de tempo, ou porque estava difícil de definir. Mas agora é a hora. Agora é a hora de definir e complementar os testes de aceitação. É muito importante que os testes de aceitação sejam definidos porque eles é que vão guiar se eu completei a user story de acordo com o que o PO estava querendo, ou não, está certo? Então nessa hora você complementa colocando user stories, testes de aceitação user stories que não tinham nenhum teste de aceitação, ou pondo novos testes de aceitação user stories que já tinham testes de aceitação, ou trocando alguns testes anteriores por outros novos. É isso que a gente faz. Ao fazer isso se ganha conhecimento muito grande sobre as user stories, sobre os seus contextos e o que deve ser feito e o que vai ser cobrado, está certo? E isso vai facilitar a vida na hora do time desenvolver as user stories que eles escolheram, está certo?        
       
![image](https://user-images.githubusercontent.com/52088444/187263445-3da97a10-e22d-456a-b481-3b508ac8dee1.png)
PBL atualizado, com os BVS/tamanho e testes de aceitação.     
![image](https://user-images.githubusercontent.com/52088444/187263758-9cb86085-aea5-4024-9520-742a5aa99a04.png)
        
Agora temos 2 Backlogs. Que é durante o projeto inteiro, que é o Product Backlog, o PBL, está certo, e o que é válido apenas para o sprint, que é o sprint backlog, o backlog do sprint, ou seja, é o conjunto de user stories e respectivas tarefas que devem ser desenvolvidas naquele sprint. E obviamente essas user stories saem do PBL, está certo, ou seja, no nosso PBL momento, no topo está a user story 2.3. Com isso a gente conseguiu então produzir conjunto de user stories, que estamos chamando de sprint backlog, que vai nortear todo o desenvolvimento daquela equipe, e isso, ao longo do sprint.     
        
        
        
        
        
## Referencias

- https://agilemanifesto.org/iso/ptbr/manifesto.html
-https://www.agileagreement.com/2020/07/21/enough-design-upfront-vor-big-design-upfront/

