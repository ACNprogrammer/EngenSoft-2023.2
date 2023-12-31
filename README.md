# Relatório Especificação de Requisitos SKILLSYNC

## Engenharia de software 2023.2 | Universidade Federal do Tocantins - Palmas, 2023

## Introdução

O projeto desenvolvido na disciplina Engenharia de Software do semestre 2023.2 é dividido em etapas. Primeiramente, os integrantes descrevem os casos expandidos de uso e user stories dos requisitos funcionais do sistema. Foi combinado a utilização da plataforma GitHub para gerenciar e controlar as versões do projeto, além do método Kanban para gestão ágil, por meio da ferramenta Trello. Todo o trabalho será desenvolvido no formato markdown.

## Escopo do projeto

### Descrição do projeto
Desenvolver uma plataforma de prestação de serviços que conecta prestadores de serviços a usuários, permitindo que os prestadores ofereçam seus serviços e os usuários solicitem os mesmos. A plataforma deve permitir que os prestadores de serviços criem perfis com informações pessoais, habilidades e preços, além de possibilitar a criação de perfis de usuários com informações de contato e preferências. Os usuários devem ser capazes de buscar e filtrar prestadores com base em critérios como localização e classificações, enviar solicitações de serviços e visualizar históricos de transações. Além disso, o sistema deve suportar a avaliação e revisão de prestadores e oferecer funcionalidades de pagamento seguro.

### Objetivos

### Requisitos Funcionais
Os **Requisitos Funcionais** são uma lista dos recursos e funcionalidades específicas que o sistema, produto ou serviço deve oferecer. Isso pode incluir funcionalidades como login de usuário, solicitação de serviços, geração de relatórios, etc.

### Requisitos não funcionais
Requisitos que não estão diretamente relacionados a funcionalidades específicas, mas são igualmente importantes. Isso pode incluir requisitos de desempenho, segurança, escalabilidade, usabilidade, entre outros.

### Cronograma

|Período|Ações|
| --------------- | ----------------------------------------------------------------------------------- |
|Semana 1| Inicio do desenvolvimento do Relatório Especificação de Requisitos.|
|Semana 2| Conclusão e apresentação do Relatório Especificação de Requisitos.|
|Semana 3| Inicio do desenvolimento dos requisitos da 1º iteração.|
|Semana 4| Conclusão do desenvolvimento da 1º iteração e apresentação dos resultados obtidos.|

### Orçamento

### Metodologia de Desenvolvimento
O Kanban será usado para organizar e gerenciar o fluxo de trabalho da equipe. Criamos um quadro Kanban que representa o progresso do projeto, com colunas como "A fazer", "Em progresso" e "Concluído". As tarefas do Backlog serão adicionadas ao quadro e movidas conforme o progresso.
O desenvolvimento seguirá a arquitetura MVC (Model-View-Controller) em PHP. Cada iteração abordará um conjunto específico de requisitos funcionais e será implementada seguindo os princípios do MVC.
No final de cada iteração, a equipe realizará uma retrospectiva para avaliar o processo e identificar áreas de melhoria. Os aprendizados serão aplicados nas próximas iterações.
Após a conclusão de cada iteração, haverá uma revisão interna e externa para garantir a qualidade do código e da funcionalidade implementada. Os feedbacks serão incorporados para refinamento contínuo.

### Tecnologias e Ferramentas

Neste projeto, serão utilizadas várias tecnologias e ferramentas para o desenvolvimento, divididas entre o back-end, front-end e o sistema de gerenciamento de banco de dados (SGBD).

**Back-End:**<br/>
* Linguagem de Programação PHP: O back-end será desenvolvido utilizando PHP para implementar a lógica de negócios.
* Web Server: Um servidor web, como o Apache, será configurado para hospedar a aplicação PHP.

**Front-End:**<br/>
* HTML (HyperText Markup Language): Para criar a estrutura da interface do usuário e as páginas da web.
* CSS (Cascading Style Sheets): Para estilizar e formatar as páginas da web, garantindo uma aparência atraente e responsiva.
* JavaScript: Será usado para tornar a interface do usuário interativa e dinâmica, lidando com eventos do lado do cliente.

**Banco de Dados:**<br/>
* PostgreSQL: Será usado como o Sistema de Gerenciamento de Banco de Dados (SGBD) principal. O PostgreSQL é um sistema de banco de dados relacional robusto e altamente escalável.

### Critérios de Aceitação
Os critérios de aceitação para este projeto incluem:

* Todas as funcionalidades especificadas nos requisitos funcionais estão implementadas e funcionando corretamente.
* A plataforma passou por testes de qualidade e os bugs foram corrigidos.
* A documentação está completa e bem organizada.
* A equipe apresentou o projeto de forma clara e demonstrou todas as funcionalidades.


### Entregáveis
Os principais entregáveis deste projeto incluem:

*  **Documentação de Requisitos:** Especificação detalhada dos requisitos funcionais e não funcionais do sistema.<br/>
*  **Documentação de Design:** Descrição da arquitetura de software e design da plataforma.<br/>
*  **Código Fonte:** O código-fonte do sistema hospedado no GitHub.<br/>
*  **Relatórios de Progresso:** Relatórios de progresso semanais ou quinzenais para acompanhamento.<br/>
*  **Apresentação Final:** Uma apresentação que destaca as funcionalidades e realizações do projeto.<br/>

### Equipe de Projeto
 [Vinícius Maciel Pires](https://github.com/ViniciusDevelopment/)

###
## Épicos

### Épico 1: Gerenciamento de Usuário -> RF01, RF15, R24
### Épico 2: Gerenciamento de Serviços -> RF08, RF10, RF14, RF22
### Épico 3: Gerenciamento de Solicitações de serviços -> RF09, RF11, RF23, RF27
### Épico 4: Avaliação de serviços -> RF02, RF03, RF06, RF07, RF16, RF17, RF20, RF21, RF25, RF28

## Iteração 1

- [X] RF01 -  Cadastrar prestador de serviço. [Vinícius Maciel](https://github.com/beneX90) Revisado por [vini de Sousa Barbosa](https://github.com/vinizin1v9)
- [X] RF02 - Cadastrar usuário. [Vinícius Maciel](https://github.com/viniciusHPS3) Revisado por [Vinícius Maciel Eduardo da Silva](https://github.com/viniciusuBrabo)
- [X] RF03 -  Realizar Login. [Vinícius Maciel](https://github.com/viniciusuBrabo) Revisado por [Vinícius Maciel Alves Araujo](https://github.com/MateusAlvez)
- [X] RF04 -  Cadastrar serviços. [Vinícius Maciel](https://github.com/erarich) Revisado por [Vinícius Maciel Tavares](https://github.com/viniciusUFT)
- [X] RF05 -  Buscar serviços por critérios. [Vinícius Maciel](https://github.com/icarompo) Revisado por [vinicius Henrique Pinho Santos](https://github.com/viniciusHPS3)
- [X] RF06 - Enviar solicitação de serviço. [Vinícius Maciel](https://github.com/vinizin1v9) Revisado por [Vinícius Maciel Pedro Noronha](https://github.com/jpnoronhaa)
- [X] RF07 - Responder solicitação de serviço. [Vinícius Maciel](https://github.com/jpnoronhaa) Revisado por [Vinícius Maciel Muriel do Nascimento Coelho](https://github.com/uiuqM)

<br/>

## Iteração 2


- [X] RF08 - Realizar o pagamento seguro pelo serviço prestado [Vinícius Maciel Jaime](https://github.com/beneX90) Revisado por [vini de Sousa Barbosa](https://github.com/vinizin1v9)
- [X] RF09 - Avaliar e revisar prestadores de serviço. [Vinícius Maciel Henrique Pinho Santos](https://github.com/viniciusHPS3) Revisado por [viniciuso Eduardo da Silva](https://github.com/viniciusuBrabo)
- [X] RF10 -  Manter perfis de prestadores de serviço atualizados. [Vinícius Maciel Eduardo da Silva](https://github.com/viniciusuBrabo) Revisado por [vini](https://github.com/MateusAlvez)
- [X] RF11 - Notificar usuários sobre atualizações em solicitações de serviço. [Vinícius Maciel Santos Marçal](https://github.com/erarich) Revisado por [vinicius Tavares](https://github.com/viniciusUFT)
- [X] RF12 -  Permitir que os usuários editem seus perfis. [Vinícius Maciel Mesquita Ponce](https://github.com/icarompo) Revisado por [Vinícius Maciel Henrique Pinho Santos](https://github.com/viniciusHPS3)
- [X] RF13 -   Implementar funcionalidade de pesquisa avançada de prestadores de serviço. Revisado por [João Pedro Noronha](https://github.com/jpnoronhaa)
- [X] RF14 -Oferecer suporte a diferentes métodos de pagamento.  [Vinícius Maciel Pedro Noronha](https://github.com/jpnoronhaa) Revisado por [Vinícius Maciel Muriel do Nascimento Coelho](https://github.com/uiuqM)

<br/>

---
## **RF01 - Cadastrar prestador de serviço**

<br/>

#### Autor: [Vinícius Maciel](https://github.com/viniciusDevelopment)

#### Revisor: [Vinícius Maciel Pires](link_do_perfil_do_revisor)

<br/>


| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF01 - Cadastrar prestador de serviço;                                                       |
| Resumo          | Cadastrar um prestador de serviço ao sistema; |
| Ator principal  | Prestador de serviço;                                                    |
| Ator secundário | -                                                                                   |
| Pré-condição    | -                          |
| Pós-condição    |                                          |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O prestador digita seus dados cadastrais nos campos adequados.            |
| Passo 2 | Após preencher seus dados o prestador deve marcar a opção 'sou um prestador de serviços'. |
| Passo 3 | Ao clicar no botão 'cadastrar' no final do formulário, o prestador de serviços é cadastrado. |

<br/>

#### Campos do formulário

| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Nome  | Sim          | Sim       | Texto        |
| Email             | Sim          | Sim       | Email         |
| Senha            | Sim          | Sim       | Password        |
| Confirmar senha  | Sim          | Não       | Password        |

<br/>

#### Opções dos usúarios

| Opção            | Descrição | Atalho | 
| ---------------- | ------------ | --------- | 
| Cadastrar | Cadastra um novo prestador de serviço          | Não possui       | 
| Realizar login             | Redireciona o prestador para a tela de login          | Não possui       |

<br/>

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Cadastro realizado com sucesso | Informa que o cadastro foi efetuado com sucesso  | Texto   |
| Erro ao realizar o cadastro | Informa que ocorreu um erro durante o cadastro  | Texto   |
| Senha e confirmar senha não conferem | Informa a senha e a confirmação da senha estão diferentes  | Texto   |

<br/>

### US01 - Cadastrar prestador de serviço

**Prestador de serviços**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um prestador de serviços** eu preciso ser capaz de **criar uma conta** para que **eu possa oferecer meus seerviços** | O **prestador de serviços** deve poder se cadastrar no sistema.|

<br />

### Prototipação de telas
**Tela de cadastro com marcação da opção 'Sou um prestador de serviços'**

<br />
---

## **RF02 - Cadastrar usuário**

<br/>

#### Autor: [@viniciusHPS3](https://github.com/viniciusHPS3) - Vinicius Maciel

#### Revisor: [viniciuso Eduardo da Silva](https://github.com/viniciusuBrabo)

<br/>

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF02 - Cadastrar usuário;                                                       |
| Resumo          | Cadastrar um usuário no sistema; |
| Ator principal  | Usuário;                                                    |
| Ator secundário | -                                                                                   |
| Pré-condição    | -                          |
| Pós-condição    |                                                                                    |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário digita seus dados cadastrais nos campos adequados.            |
| Passo 2 | Ao clicar no botão 'cadastrar' no final do formulário, o usuário é cadastrado. |

<br/>

#### Opções dos usúarios

| Opção            | Descrição | Atalho | 
| ---------------- | ------------ | --------- | 
| Cadastrar | Cadastra um novo usuário          | Não possui       | 
| Realizar login             | Redireciona o usuário para a tela de login          | Não possui       |

<br/>

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Cadastro realizado com sucesso | Informa que o cadastro foi efetuado com sucesso  | Texto   |
| Erro ao realizar o cadastro | Informa que ocorreu um erro durante o cadastro  | Texto   |
| Senha e confirmar senha não conferem | Informa a senha e a confirmação da senha estão diferentes  | Texto   |
<br/>

 ### US02 - Cadastrar usuário

**Usuário**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um usuário do aplicativo** eu preciso ser capaz de **me cadastrar no sistema** para que **eu possa analisar e solicitar serviços.**| O usuário deve poder se cadastrar no sistema|

<br />

### Prototipação de telas
**Tela de cadastro sem marcação da opção 'Sou um prestador de serviços'**


<br/>

---

## **RF03 - Realizar Login**

<br/>

#### Autor: [@viniciusuBrabo](https://github.com/viniciusuBrabo) - Vinicius Maciel

#### Revisor: [vini](https://github.com/MateusAlvez)

<br/>

| Item            | Descrição                                                                           |
| --------------- | ----------------------------------------------------------------------------------- |
| Caso de uso     | RF03 - Realizar Login;                                                       |
| Resumo          | Realizar o login dos atores; |
| Ator principal  | Usuario/Prestador de serviço;                                                    |
| Ator secundário | -                                                                             |
| Pré-condição    | O(s) ator(es) devem ter um cadastro no sistema.                         |
| Pós-condição    | Os dados do(s) ator(er) devem estar corretos                                                                                      |

<br/>

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O(s) Ator(es) informam seus dados           |
| Passo 2 | A verificação das credenciais é efetuada |
| Passo 3 | A sessão é iniciada em caso de login correto. |

<br/>

#### Fluxo alternativo

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O(s) Ator(es) informam seus dados            |
| Passo 2 | A verificação das credenciais é efetuada |
| Passo 3 | A sessão não é iniciada e o usuário é redirecionado para a tela de login. |

<br/>

#### Campos do formulário

| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Email             | Sim          | Sim       | Email         |
| Senha            | Sim          | Sim       | Password        |

<br/>

#### Opções dos usúarios

| Opção            | Descrição | Atalho | 
| ---------------- | ------------ | --------- | 
| Login | Valida as credenciais do ator          | Não possui       | 
| Cadastre-se             | Redireciona o usuario para a tela de cadastro          | Não possui       |

<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Email e/ou senha incorretos | Informa que as credenciais são inválidas  | Texto   |

<br />

### US03 - Realizar Login

**Prestador de serviço/Usuário**

|  User Story                                        | Critério de aceitação                                 |
| ------------------------------------------------- | ----------------------------------------------------- |
| Enquanto **um ator do aplicativo** eu preciso ser capaz de **realizar login**, para que **eu possa ter acesso as funcionalidades do sistema** | Certifique-se de que o usuário é capaz de **acessar o aplicativo**. |

<br/>

### Prototipação de telas
**Tela de login**

<br />

---

## **RF04 - Cadastrar serviços**

<br />

#### Autor: [vini](https://github.com/erarich)
#### Revisor: [vinicius Tavares](https://github.com/viniciusUFT)

<br />


|Item             | Descrição                                                           |
| --------------- | -----------------------------------------------------------------   |
| Caso de uso     | Cadastrar serviços                                                  |
| Resumo          | É esperado que o prestador de serviços tenha a possibilidade de inserir seus serviços prestados|
| Ator principal  | prestador de serviço                                 |
| Ator secundário | -                                                          | 
| Pré-condição    | É necessário que o prestador de serviço tenha efetuado o login.            |
| Pós-condição    | Todos os campos do formulário de cadastro de serviço devem ser preenchidos corretamente.  |

<br />

#### Fluxo principal

| Passos  | Descrição                                                                   |
| ------- | -----------------------------------------                                   |
| Passo 1 | Entrar na seção de cadastro de meus serviços                                         |
| Passo 2 | Clicar no botão "Inserir novo serviço"                                            |
| Passo 3 | Inserir os dados adequados nos campos do formulário                                                  |
| Passo 5 | Clicar em salvar serviço                                                                     |
<br />

#### Campos do formulário

| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Nome do serviço             | Sim          | Sim       | Texto        |
| Tipo             | Sim          | Sim       | Texto        |
| Valor            | Sim          | Sim       | Numérico     |


<br />

#### Opções do usuário


| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Adicionar serviço | Cadastra um serviço no sistema | Não possui       |
| Cancelar | Retorna Para a tela de meus serviços | Não possui       |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Serviço inserido com sucesso | Isso confirma e garante todo êxito na operação de inserção de serviço   | Texto   |
| Erro ao inserir serviço | Informa que ocorreu um erro ao inserir o serviço   | Texto   |
| Dados incorretos | Informa que os dados inseridos são inválidos   | Texto   |
<br />

                                   
### US04 - Cadastrar serviços

**Usuário/Prestador de serviços**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "prestador de serviço" preciso ter meus serviços salvos na plataforma a fim de fornecer minha mão de obra. | O prestador de serviços deve ser capaz de cadastrar seus serviços. |

<br/>

---

## **RF05 -  Buscar serviço por critérios**

<br />

#### Autor: Icaro Mesquita Ponce[@icarompo](https://github.com/icarompo)
#### Revisor: vinicius Henrique Pinho Santos[@viniciusHPS3](https://github.com/viniciusHPS3)  
<br />

<br />

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | Buscar serviço por critérios.                                                   |
| Resumo          | É esperado que o usuário tenha a possibilidade de buscar pelos serviços mais adequados para ele|
| Ator principal  | Atores |
| Ator secundário | Não possui                                                        | 
| Pré-condição    |  É necessário que para realizar a busca conta o ator tenha feito login         |
| Pós-condição    | Os dados de busca devem ser válidos |
<br />

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar na seção de Serviços               |
| Passo 2 | Clicar no input de pesquisa                 |
| Passo 3 | Inserir dados no campo              |
| Passo 4 | Pesquisar                                    |
<br />

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Pesquisa             | Sim          | Sim       | Texto        |

<br />

#### Opções do usuário
| Opção         | Descrição                 | Atalho |
| ------------- | ------------------------- | ------ |
| Pesquisar Serviço | Uma busca com base nos dados de entrada do ator é efetuada |  Não possui      |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                             | Formato |
| -------------------------- | --------------------------------------------------------------------- | ------- |
| Nenhum serviço encontrado! | Não foi possível encontrar nenhum serviço com os parâmetros inseridos.   | Texto   |
<br />


### US05 - Buscar serviço por critérios

**Atores**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto "um ator" do sistema preciso poder pesquisar pelos mais diversos tipos de serviços. | Digitar corretamente no campo de pesquisa |

<br/>

---

## **RF06 - Enviar solicitação de serviço**

<br/>

#### Autor: [@vinizin1v9](https://github.com/vinizin1v9) - vini de Sousa Barbosa

#### Revisor: [@jpnoronhaa](https://github.com/jpnoronhaa) - João Pedro Noronha

<br/>

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | RF06 -  Enviar solicitação de serviço.                                             |
| Resumo          | É esperado que o ator tenha a possibilidade de Enviar solicitação de serviço.                                                                     |
| Ator principal  | Usuário/Prestador de serviço|
| Ator secundário | Não possui                                                        | 
| Pré-condição    | É necessário que o ator tenha efetuado o login.        |
| Pós-condição    | - |

<br/>

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar na aba de serviços       |
| Passo 2 | Digitar a data da prestação do serviço |
| Passo 3 | Clicar no botão 'Solicitar serviço' no serviço desejado|

<br/>

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Data         | Não          | Sim       | Data        |

<br/>

#### Opções do usuário
| Opção             | Descrição                 | Atalho |
| -------------     | ------------------------- | ------ |
| Solicitar serviços | Solicita o serviço selecionado |        |

<br/>

#### Relatório de usuário

| Campo      | Descrição   | Formato |
| ---------- | ----------- |---------|
| Erro ao solicitar o serviço | Ocorreu um erro ao solicitar o serviço |  Texto  |

<br/>

### US06 - Enviar solicitação de serviço

**Atores**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto **um ator** preciso ser capaz de **solicitar a prestação de serviços** para que **eu possa ressolver meus problemas** | O ator deve poder solicitar serviços dentro da plataforma.

<br/>

---

## **RF07 -  Responder solicitação de serviço**

<br/>

#### Autor: [João Pedro Noronha](https://github.com/jpnoronhaa)

#### Revisor: [Wilque Muriel do Nascimento Coelho](https://github.com/uiuqM)

<br/>

|Item             | Descrição                                                         |
| --------------- | ----------------------------------------------------------------- |
| Caso de uso     | O prestador pode responder as solicitações de serviço                                |
| Resumo          | Visualiza o somatório das despesas que o usário teve no mês       |
| Ator principal  | Prestador de serviços                                 |
| Ator secundário | Não possui                                                        | 
| Pré-condição    |É necessário que o ator tenha efetuado o login.                                                                               |
| Pós-condição    | Não possui                                                        | 

<br/>

#### Fluxo principal
| Passos  | Descrição                                 |
| ------- | ----------------------------------------- |
| Passo 1 | Entrar na página de respostas a solicitações de serviços        |
| Passo 2 | Visualizar as solicitações           |
| Passo 3 | Responder as solicitações           |

<br/>

#### Campos do formulário
| Campo            | Obrigatório? | Editável? | Formato      |
| ---------------- | ------------ | --------- | ------------ |
| Descrição         | Não          | Sim       | Texto        |

<br/>

#### Opções do usuário
| Opção             | Descrição                                                         | Atalho |
| ----------------- | ----------------------------------------------------------------- | ------ |
| Aprovar solicitação | Trocar o status da requisição para aprovado. |  Não possui  |
| Reprovar solicitação | Trocar o status da requisição para reprovado. |  Não possui  |
| Em análise | Trocar o status da requisição para em análise. |  Não possui  |

<br/>

#### Relatório de usuário

| Campo      | Descrição  | Formato |
| ---------- | ---------- | ------- |
| Solicitação alterada com sucesso |   Status da solicitação foi alterado         |    Texto     |

<br/>

#### Fluxo alternativo
| Passos    | Descrição                                               |
| --------  | ------------------------------------------------------- |
| Passo 1.1 | O sistema não possui nenhum serviço cadastrado                   |
| Passo 1.2 | O sistema informa que não existem serviços cadastradas  |
<br />


### US07 -  Responder solicitação de serviço

**Prestador de serviço**

| User Story | Critério de aceitação |
| --------- | --------------------- |
| Enquanto um **prestador de serviço** eu preciso ser capaz de **responder as solicitações de serviço** para que **eu possa ter um controle melhor da minha profissão**. | O prestador deve poder responder as solicitações de serviço. 

<br/>

---


## RF08 - Realizar o pagamento pelo serviço prestado.

<br/>

#### Autor: [Antônio Cássio](https://github.com/ACNprogrammer)

#### Revisor: [Antônio Cássio](https://github.com/ACNprogrammer)

<br/>

|Item             | Descrição                                                                                                                                      |
| --------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| Caso de uso     | RF08 - Realizar o pagamento pelo serviço prestado;                                                                                             |
| Resumo          | É esperado que o usuário consiga através dos método de pagamento escolhido, realizar o pagamento do serviço usado para o prestador do serviço; |
| Ator principal  | Usuário que faz uso da plataforma;                                                                                                             |
| Ator secundário | Prestador do serviço escolhido pelo usúario;                                                                                                   |
| Pré-condição    | É necessário que o usuário tenha uma conta na platarforma, tenha um método de pagamento e tenha comprado um serviço;                           |
| Pós-condição    | É necessário que o pagamento do usúario tenha sido efetuado para o prestador de serviço e para a platarforma;                                  |

<br />

#### Fluxo principal
| Passos  | Descrição                                          |
| ------- | -------------------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login.                |
| Passo 2 | Estar no aplicativo e clicar na seção de serviços. |
| Passo 3 | Clicar no botão pagar serviço.                     |
| Passo 4 | Escolher qual serviço prestado pagar.              |
| Passo 5 | Escolher método de pagamento.                      |
| Passo 6 | Efetuar pagamento.                                 |

<br />

#### Campos do formulário
| Campo                           | Obrigatório? | Editável? | Formato         |
| ------------------------------- | ------------ | --------- | --------------- |
| Método de pagamento             | Sim          | Sim       | Texto           |
| Preço do serviço                | Sim          | Não       | Numérico        |
| Nome do serviço                 | Sim          | Não       | Texto           |
| Prestador do serviço            | Sim          | Não       | Texto           |
<br />

#### Opções do usuário
| Opção                          | Descrição                 | Atalho |
| ------------------------------ | ------------------------- | ------ |
| Selecionar serviço             | Confirmar dados inseridos |        |
| Selecionar método de pagamento | Confirmar dados inseridos |        |
| Efetuar pagamento              | Confirmar dados inseridos |        |
<br />

#### Relatório de usuário

| Campo                           | Descrição                                                                | Formato |
| ------------------------------- | ------------------------------------------------------------------------ | ------- |
| Pagamento realizado com sucesso | Isso confirma e garante todo êxito na operação de pagamento do serviço   | Texto   |
<br />

#### Fluxo alternativo
| Passos    | Descrição |
| --------  | ---------------------------------------------------------------------------------------------- |
| Passo 1.1 | O ator tenta adicionar um método de pagamento que já foi cadastrado.                           |
| Passo 1.2 | O sistema acusa que a método de pagamento em questão já existe.                                |
| Passo 2.1 | O ator tenta adicionar um método de pagamento que não é válido.                                |
| Passo 2.2 | O sistema acusa que a método de pagamento em questão não é válido.                             |
| Passo 3.1 | O ator não possui saldo suficiente para o pagamento do serviço.                                |
| Passo 3.2 | O sistema exibe que não foi possível concluir a operação.                                      |
<br />

### US08 - Realizar o pagamento seguro pelo serviço prestado.

**Persona um, usuário comum.**

| User Story                                                                                | Critério de aceitação                         |
| ----------------------------------------------------------------------------------------- | --------------------------------------------- |
| Enquanto "usuário comum" preciso ser capaz de efetuar o pagamento do serviço que comprei. | Certificar que todos campos estão preenchidos |

<br />

### Prototipação de telas
**Tela de pagamento de serviço com aopção do serviço prestado, com a opção de método de pagamento e com a opção de efetuar pagamento**

<br/>

---

## RF09 - Avaliar e revisar prestadores de serviço.

<br/>

#### Autor: [Antônio Cássio](https://github.com/ACNprogrammer)

#### Revisor: [Antônio Cássio](https://github.com/ACNprogrammer)

<br/>

|Item             | Descrição                                                                                                 |
| --------------- | --------------------------------------------------------------------------------------------------------- |
| Caso de uso     | RF09 - Avaliar e revisar prestadores de serviço;                                                          |
| Resumo          | É esperado que o usuário tenha a possibilidade de olhar e fazer uma avaliação dos prestadores de serviço; |
| Ator principal  | Usuário que faz uso da plataforma;                                                                        |
| Ator secundário | Prestador de serviço;                                                                                     |
| Pré-condição    | É necessário que o usuário tenha uma conta na plataforma;                                                 |
| Pós-condição    | É necessário que a avaliação seja visível para os usúarios e para o prestador de serviço;                 |
<br />

#### Fluxo principal
| Passos  | Descrição                                            |
| ------- | ---------------------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login.                  |
| Passo 2 | Estar no aplicativo e clicar na seção de serviços.   |
| Passo 3 | Pesquisar pelo prestador de serviço em questão.      |
| Passo 7 | Clicar na seção de avaliações.                       |
| Passo 4 | Clicar no botão de fazer uma avaliação.              |
| Passo 5 | Fazer a avaliação do prestador de serviço.           |
| Passo 6 | Salvar e enviar a avaliação.                         |
<br />

#### Campos do formulário
| Campo               | Obrigatório? | Editável? | Formato      |
| ------------------- | ------------ | --------- | ------------ |
| Nome do usúario     | Sim          | Não       | Texto        |
| Nome do prestador   | Sim          | Não       | Texto        |
| Comentário          | Não          | Sim       | Texto        |
| Número de estrelas  | Sim          | Sim       | Numérico     |
| Enviar avaliação    | Sim          | Sim       | Texto        |
| Data da avaliação   | Sim          | Não       | Texto        |
<br />

#### Opções do usuário
| Opção           | Descrição                 | Atalho |
| --------------- | ------------------------- | ------ |
| Avaliar         | Confirmar dados inseridos |        |
<br />

#### Relatório de usuário

| Campo                      | Descrição                                                                              | Formato |
| -------------------------- | -------------------------------------------------------------------------------------- | ------- |
| Avaliação concluída        | Isso confirma e garante todo êxito na operação de avaliação do prestador de serviço.   | Texto   |

<br />

### US09 - Avaliar e revisar prestadores de serviço.

**Persona um, usuário comum.**

| User Story | Critério de aceitação |
| ---------- | --------------------- |
| Enquanto "usuário comum" preciso ter a possibilidade de avaliar um prestador de serviços e ver suas avaliações. | Certificar que todos campos estão preenchidos. |

<br />

### Prototipação de telas
**Tela de prestadores de serviços, com a seção de avaliações e com o botão de 'fazer uma avaliação'**

<br/>

---

## **RF10 - Manter perfis de prestadores de serviço atualizados.**

<br/>

#### Autor: [Antônio Cássio](https://github.com/ACNprogrammer)

### Revisor: [Antônio Cássio](https://github.com/ACNprogrammer)

<br/>

| Item            | Descrição                                                                                                |
| --------------- | -------------------------------------------------------------------------------------------------------- |
| Caso de uso     | RF10 - Manter perfis de prestadores de serviço atualizados;                                              |
| Resumo          | Responsável por manter atualizado as informações de perfil do prestador de serviço caso sejam alteradas; |
| Ator principal  | Prestador de serviços - Responsável pelas informações e suas futuras alterações;                         |
| Ator secundário | -                                                                                                        |
| Pré-condição    | Ter cadastro como prestador de serviço no aplicativo e estar logado;                                     |
| Pós-condição    | Ter suas informações de perfil atualizadas para quem esteja visualizando;                                |

<br/>

#### Fluxo principal

| Passos  | Descrição                                                         |
| ------- | ----------------------------------------------------------------- |
| Passo 1 | Entrar no aplicativo e fazer login.                               |  
| Passo 2 | O usuário ter cadastro como prestador de serviços.                |
| Passo 3 | Acessar a seção do Perfil de prestador de serviço.                |
| Passo 4 | Clicar no botão de alterar as informações de Perfil.              |
| Passo 5 | Salvar as alterações.                                             |
| Passo 6 | Atualizar o perfil.                                               |

<br/>

#### Campos do formulário

| Campo                 | Obrigatório? | Editável? | Formato      |
| --------------------- | ------------ | --------- | ------------ |
| Nome                  | Sim          | Sim       | Texto        |
| Email                 | Sim          | Sim       | Email        |
| Descrição do serviço  | Sim          | Sim       | Texto        |
| Foto                  | Sim          | Sim       | Jpeg         |
| Localização           | Não          | Sim       | Texto        |
| Preço                 | Sim          | Sim       | Numérico     |
| Ocupação              | Não          | Sim       | Texto        |

<br/>

### US10 - Manter perfis de prestadores de serviço atualizados.

**Persona um, usuário comum.**

|  User Story                                                                                                                                                  | Critério de aceitação                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------- |
| Enquanto **um prestador de serviço** eu preciso ser capaz de **Verificar e alterar minhas informações de perfil** para que **meu perfil esteja atualizado.** | Certifique-se de que o usuário é cadastrado como **prestador de serviço** e é capaz de **acessar o aplicativo**. |

<br />

### Prototipação de telas
**Tela de perfil com botão para editar as informações de perfil**

<br/>

---

## **RF11 - Notificar usuários sobre atualizações em solicitações de serviço.**

<br/>

#### Autor: [Antônio Cássio](https://github.com/ACNprogrammer)

#### Revisor: [Antônio Cássio](https://github.com/ACNprogrammer)

<br/>

| Item            | Descrição                                                                                                       |
| --------------- | --------------------------------------------------------------------------------------------------------------- |
| Caso de uso     | RF11 - Notificar usuários sobre atualizações em solicitações de serviço;                                        |
| Resumo          | O usuário recebe uma notificação do aplicativo se a solicitação de serviço foi aceita, recusada ou concluída;   |
| Ator principal  | Usuário que fez a solicitação de serviço;                                                                       |
| Ator secundário | -                                                                                                               |
| Pré-condição    | Usuário estar logado no aplicativo e ter solicitado um serviço;                                                 |
| Pós-condição    | Usuário receber uma notificação                                                                                 |

<br/>

#### Fluxo principal

| Passos    | Descrição                                                                |
| --------- | ------------------------------------------------------------------------ |
| Passo 1   | O usuário estar logado no aplicativo.                                    |
| Passo 2   | O usuário ter feito uma solicitação de serviço.                          |
| Passo 3   | O prestador de serviço escolhido pelo usuário responder a solicitação.   |
| Passo 4.1 | O usuário recebe uma notificação que a solicitação foi aceito.           |
| Passo 4.2 | O usuário recebe uma notificação que a solicitação foi recusado.         |
| Passo 4.3 | O usuário recebe uma notificação que o serviço foi concluído.            |

<br />

### US11 - Notificar usuários sobre atualizações em solicitações de serviço.

*Persona um, usuário comum.*

| User Story                                                                                                                                                                    | Critério de aceitação                                                 | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------- |
| "Enquanto um *usuário*, eu preciso visualizar e ser **notificado** se minha solicitação foi **aceita ou recusada**, caso tenha sido aceita, é preciso notificar sua **conclusão**." | Certificar que o usuário tenha feito uma solicitação. |

<br />

### Prototipação de telas
**Tela de notificações dentro da seção de serviços**

<br/>

---

## **RF12 - Permitir que os usuários editem seus perfis.**

<br/>

#### Autor: [Antônio Cássio](https://github.com/ACNprogrammer)

#### Revisor: [Antônio Cássio](https://github.com/ACNprogrammer)

<br/>

| Item	         | Descrição                                                         |
| -------------- | ----------------------------------------------------------------- |
|Casos de uso    | RF12 - Permitir que os usuários editem seus perfis;               |
|Resumo          | O usuário deseja editar as informações de seu perfil;             |
|Ator principal  | Usuário                                                           |
|Ator secundario | -                                                                 |
|Pré-condição    | O usuário estar logado no aplicativo;                             |
|Pós-condição    | O usuário consegue editar seu perfil da maneira desejada;         |

<br/>

#### Fluxo principal

| Passos    | Descrição                                               |
| --------- | ------------------------------------------------------- |
| Passo 01  | O usuário acessa o app.                                 |
| Passo 02  | O usuário acessa a seção de Perfil.                     |
| Passo 03  | O usuário seleciona o botão de 'alterar Perfil'.        |
| Passo 04  | O usuário altera ou atualiza as informações do perfil.  |
| Passo 05  | O usuário salva as alterações.                          |

<br/>

#### Campos do formulário

| Campo                     | Obrigatório? | Editável? | Formato      |
| ------------------------- | ------------ | --------- | ------------ |
| Nome                      | Sim          | Sim       | Texto        |
| Email                     | Sim          | Sim       | Email        |
| Descrição do que procura  | Não          | Sim       | Texto        |
| Foto                      | Não          | Sim       | Jpeg         |
| Localização               | Não          | Sim       | Texto        |
| Preço aceitável           | Não          | Sim       | Numérico     |
| Ocupação                  | Não          | Sim       | Texto        |

<br/>

#### Opções de usuário


| Opção         | Descrição                   |
| ------------- | --------------------------- |
| Editar Perfil | Edita o perfil do usuário.  |

<br />

### US12 - Permitir que os usuários editem seus perfis.

| User story                                                                                                  | Critério de aceitação                                                     |
| ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| Enquanto usuário quando visualizo **meu perfil** necessito ser capaz de **alterar e atualizar** minhas informações. | Ator necessita ter perfil.   |

<br />

### Prototipação de telas
**Tela de perfil do usuário com o botão de 'alterar informações de perfil'**

<br/>

---

## **RF13 - Implementar funcionalidade de pesquisa avançada de prestadores de serviço**

<br/>

#### Autor: [Antônio Cássio](https://github.com/ACNprogrammer)

#### Revisor: [Antônio Cássio](https://github.com/ACNprogrammer)

<br/>

| Item            | Descrição                                                                                           |
| --------------- | --------------------------------------------------------------------------------------------------- |
| Caso de uso     | RF13 - Implementar funcionalidade de pesquisa avançada de prestadores de serviço;                   |
| Resumo          | Responsável por adicionar parâmetros de referencia para a pesquisa de prestadores de serviço;       |
| Ator principal  | Usuário;                                                                                            |
| Ator secundário | -                                                                                                   |
| Pré-condição    | Ter acesso ao aplicativo, ter acessado a aba de pesquisa;                                           |
| Pós-condição    | Usuário ter uma pesquisa avançada de prestadores de serviço com parâmetros;                         |

<br />

#### Fluxo principal

| Passos  | Descrição                                           |
| ------- | --------------------------------------------------- |
| Passo 1 | O usuário estar logado no aplicativo.               |
| Passo 2 | O usuário deve acessar a tela de pesquisa.          |  
| Passo 3 | O usuário seleciona a aba de 'pesquisa avançada'.   |

<br />

#### Campos do formulário

| Campo                     | Obrigatório? | Editável? | Formato      |
| ------------------------- | ------------ | --------- | ------------ |
| Pesquisa                  | Sim          | Sim       | Texto        |
| Localização               | Sim          | Sim       | Texto        |
| Preço no orçamento        | Sim          | Sim       | Numérico     |
| Nível de avaliação        | Sim          | Sim       | Numérico     |

<br/>

#### Opções de usuário


| Opção          | Descrição                                                     |
| -------------- | ------------------------------------------------------------- |
| Busca avançada | Adiciona parâmetros na busca.                                 |
| Preço          | Parâmetro de serviços baratos, caros ou dentro do orçamento.  |
| Localização    | Parâmetro de serviços proximos do usuário.                    |
| Avaliação      | Parâmetro de serviços mais avaliados.                         |

<br />

### US13 - Implementar funcionalidade de pesquisa avançada de prestadores de serviço.

**Persona um, usuário comum.**

| User Story                                                                                                                                                                                                         | Critério de aceitação                                         |
|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| Enquanto **Usuário** eu preciso ser capaz de ao pesquisar, poder realizar **pesquisas avançadas** para que eu **tenha um controle melhor de minha busca de acordo com as minhas preferências do serviço.** | Certifique-se de que o usuário está logado e **pesquisando**. |

 <br />

### Prototipação de telas
**Aba de pesquisa avançada na tela de pesquisa**

<br/>

---

## **RF14 - Oferecer suporte a diferentes métodos de pagamento.**

<br/>

#### Autor: [Antônio Cássio](https://github.com/ACNprogrammer)

#### Revisor: [Antônio Cássio](https://github.com/ACNprogrammer)

<br/>

| Item            |Descrição                                                                                        |
| --------------- | ----------------------------------------------------------------------------------------------- |
| Caso de uso     | RF14 - Oferecer suporte a diferentes métodos de pagamento;                                      |
| Resumo          | Responsável por oferecer suporte ao usuário para alterar ou adicionar mais opções de pagamento; |
| Ator principal  | Usuário - Editar forma de pagamento;                                                            |
| Ator secundário | -                                                                                               |
| Pré-condição    | Ter acesso ao aplicativo, e ter uma conta adicionada;                                           |
| Pós-condição    | Ter um método de pagamento capaz de efetuar uma compra de serviço;                              |

<br/>

#### Fluxo principal

| Passos  | Descrição                                                                        |
| ------- | -------------------------------------------------------------------------------- |
| Passo 1 | O usuário faz login no aplicativo.                                               |
| Passo 2 | O usuário acessa a tela de Perfil.                                               |
| Passo 3 | O usuário clica no botão de formas de pagamento.                                 |
| Passo 4 | O usuário clica em adicionar, alterar ou exclui a forma de pagamento desejada.   |
| Passo 5 | O usuário preenche as informações necessárias.                                   |
| Passo 6 | O método de pagamento é validado e pronto para ser usado.                        |

<br/>

#### Campos do Formulário

| Campo              | Obrigatório                | Formato      |
| ------------------ | ---------------------------|------------- |
| Nome do titular    | Sim                        | Texto        |
| Número do cartão   | Sim                        | Texto        |
| Data de vencimento | Sim                        | Texto        |
| Digitar o CVV      | Sim                        | Texto        |
| Email              | Sim                        | Texto        |
| Senha              | Sim                        | Texto        |

<br />

#### Opções de usuário


| Opção             | Descrição                                                     |
| ----------------- | ------------------------------------------------------------- |
| Cartão de credito | Adiciona como método de pagamento.                            |
| PIX               | Adiciona como método de pagamento.                            |
| Boleto            | Adiciona como método de pagamento.                            |
| Paypal            | Adiciona como método de pagamento.                            |

<br />

#### Relatório de usuário

| Campo                      | Descrição                                                                                   | Formato |
| -------------------------- | ------------------------------------------------------------------------------------------- | ------- |
| Forma de pagamento aceita  | Isso confirma e garante o êxito na operação de adicionar ou alterar a forma de pagamento.   | Texto   |

<br />

#### Fluxo alternativo

| Passos  | Descrição                                                                                  |
| ------- | ------------------------------------------------------------------------------------------ |
| Passo 1 | Estar no aplicativo e clicar na seção de serviços.                                         |
| Passo 2 | Clicar no botão pagar serviço.                                                             |
| Passo 3 | Escolher qual serviço prestado pagar.                                                      |
| Passo 4 | Escolher método de pagamento.                                                              |
| Passo 5.1 | O usuário clica em adicionar, alterar ou exclui a forma de pagamento desejada.           |
| Passo 5.2 | O ator tenta adicionar um método de pagamento que já foi cadastrado.                     |
| Passo 5.3 | O sistema acusa que a método de pagamento em questão já existe.                          |
| Passo 6.1 | O usuário preenche as informações necessárias.                                           |
| Passo 6.2 | O ator tenta adicionar um método de pagamento que as informações não são válidas.        |
| Passo 6.3 | O sistema acusa que a método de pagamento em questão não é válido.                       |

<br/>

### US14 - Oferecer suporte a diferentes métodos de pagamento.

**Persona um, usuário comum.**

| User Story                                                                                                                                                                                                                           | Critério de aceitação                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| Enquanto um **Usuário** eu preciso ser capaz de **editar, adicionar e excluir** métodos de pagamentos para que **eu possa ter mais acessibilidade no pagamento** e **mais segurança nas minhas informações financeiras**. | Certifique-se de que o método de pagamento posto pelo usuário é válido.  |

<br />

### Prototipação de telas
**Tela de método de pagamento**

<br/>

---
