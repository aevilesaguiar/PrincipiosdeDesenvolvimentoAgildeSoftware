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

## Referencias

- https://agilemanifesto.org/iso/ptbr/manifesto.html

