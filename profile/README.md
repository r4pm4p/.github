
#### **Introdução**

O projeto Rapmap visa a criação de um sistema web que seja o responsável por integrar pessoas interessadas em batalhas de rap que acontecem no Brasil, sendo o principal foco de nosso projeto, trazer a tona as diversas batalhas que acontecem nas regiões não metropolitanas do país e que com esse distanciamento dos grandes centros levam essas batalhas e eventos para o esquecimento.

#### **Responsáveis**

- **Diluan Lima de Matos**
- **Lucas Gabriel**
- **Luiz Henrique Gomes**

#### **Linguagem Ubíqua**

- **Administrador** -> Se refere aos usuários que gerem todo o sistema, sendo o nível mais alto dentro do sistema.
- **Batalhas** -> Se refere as batalhas de rap.
- **Eventos** -> Se refere aos eventos de batalhas de rap que podem acontecer em datas e locais.
- **Mc's** -> Se refere a usuários que também possuem um perfil de mc.
- **Owner** -> Se refere aos gerenciadores de batalhas e eventos.
- **Pódio** -> Se refere a colocação final que pode ser adicionada a cada evento.
- **Sistema** -> Se refere a parte tecnológica do Rapmap.
- **Usuário** -> Se refere a pessoas que possuem um cadastro simples no sistema.



#### **Visão geral de funcionalidades**

As propostas que o sistema têm, se definem a usuários acessarem uma página web e a partir dela visualizarem todas as batalhas de rap em andamento ou foram marcadas para datas específicas. Usuários comuns podem visualizar essas batalhas e esses eventos, podendo a partir dessa visualização confirmar a presença para assistir esses eventos.

Outra parte fundamental do sistema são os Mc's, que vão criar seu perfil no sistema e terão a possibilidade de solicitar a participação em batalhas de rap, essas solicitações que devem ser confirmadas pelo representante da batalha. Mc's também possuem a chance de publicar suas redes sociais, canais de YouTube e mesmo uma descrição de si para que outros usuários possam ver esse perfil.

Representantes de batalhas são os responsáveis por gerir uma arena, que nada mais é que um local onde acontecem batalhas, e gerir eventos q podem ser feitos nessas batalhas, aceitar ou recusar Mc's que decidam batalhar, adicionar um perfil da batalha e ao fim de cada evento adicionar o pódio.

#### **Funcionalidades**

- **Cadastro de Administradores**
- **Cadastro de Batalhas**
- **Cadastro de Mc's**
- **Cadastro de Usuários**
- **Buscar todos os Mc's** 
- **Buscar todas as Batalhas**
- **Buscar todos os Eventos**
- **Adicionar pódio em Evento finalizado**
- **Adicionar informações de perfil de Mc's**
- **Adicionar informações de perfil de Batalhas**
- **Solicitar participação em Evento**
- **Confirmar solicitação de participação em Evento**
- **Recusar solicitação de participação em Evento**
- **Ver perfil de Batalha**
- **Ver perfil de Evento**
- **Ver perfil de Mc's**


#### **Tecnologias**

Para que sejam desenvolvidas todas as funcionalidades propostas, a escolha de tecnologias resilientes e que permitam qualidade tanto no produto final, quanto aos desenvolvedores. Assim a escolhas temos: 

###### **1.JavaScript**

É a linguagem de programação que será utilizada, tanto no backend, quanto no frontend do Rapmap, sendo esta tecnologia escolhida devido a sua forte presença no mercado, resiliência, facilidade de encontrar plugins e bibliotecas que podem auxiliar no desenvolvimento e principalmente por versatilidade para ser utilizada em projetos das mais diversas finalidades.
Para saber mais, acesse: https://developer.mozilla.org/pt-BR/docs/Web/JavaScript

###### **2.Vue.js**

Vue.js é uma framework de desenvolvimento frontend utilizada para criação da parte visual de sistemas robustos presentes no mercado. Sua principal força é a facilidade de aprendizado, e sua progressividade na utilização  e implementação, já que se adapta facilmente a projeto novos e também projetos que já estão em produção.
Para saber mais, acesse: https://vuejs.org/

###### **3.Node.js**

Node.js é a tecnologia escolhida para desenvolver o backend do sistema, já que atualmente está entre as 3 tecnologias mais utilizadas em desenvolvimento backend.
Node.js é uma máquina de execução feita para rodar códigos em JavaScript. Assim permitindo que JavaScript seja a linguagem de programação que atua nas duas pontas do projeto.
Para saber mais, acesse: https://nodejs.org/en

###### **4.PostgreSQL**

PostgreSQL é a proposta de banco de dados do sistema, sendo um banco de dados relacional, que suporta acessos concorrentes, assim dando mais desempenho as aplicações que o utilizam.
Para saber mais, acesse: https://www.postgresql.org/

###### **5.Redis**

Redis é a tecnologia escolhida para ser o sistema de cache, o que aumenta a desempenho do sistema, já que requisições que não tem tanta criticidade, podem ser salvas em um cache para serem respondidas mais rapidamente.
Para saber mais, acesse: https://redis.io/

###### **6.Docker**

O Docker é um software de código aberto usado para implantar aplicativos dentro de contêineres virtuais. A conteinerização permite que vários aplicativos funcionem em diferentes ambientes complexos.
Para saber mais, acesse https://www.docker.com/

###### **7.Fastify**

Para criação de um servidor HTTP que seja funcional, rápido e simples de escalar, utilizaremos a Fastify que quando se trata de framework para Node.js é a mais performática que podemos encontrar no mercado.
Para saber mais, acesse https://fastify.dev/
