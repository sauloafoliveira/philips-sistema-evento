# Calendário de entregas

- ``30/01`` Kick-off projeto final;
  - Criar um repositório **público** da equipe;
  - Adicionar a mim como membro do projeto;
  - Criação das classes/pacotes das entidades do projeto.
- ``14/02`` Definições da camada de Modelos;
  - Diagrama de Classes;
  - Diagrama de Entidade-Relacional;
  - Script SQL de criação do banco de dados do projeto.
- ``27/02`` Definições da camada de Visão;
  - Protótipo de telas com base nos requisitos;
  - Definição da identidade visual.
- ``14/03`` Definições da camada de Controle - *parte 01*;
  - Integração com Banco de dados (CRUD básico das entidades);
  - Implementação de Autenticação no sistema;
  - Início da implementação dos demais requisitos;
- ``29/03`` Definições da camada de Controle - *parte 02*;
  - Continuação da implementação dos demais requisitos.
- ``29-30/03`` e ``03-04/04`` Acompanhamento de projeto final;
- ``05/04`` Apresentação dos projetos.

## Requisitos gerais de TODOS os projetos 

- Precisa ter uma página inicial institucional estática, a página inicial;
- Demais páginas precisam ser dinâmicas e abordar os casos de uso;
- Ser responsivo, ter pontos de quebra para celular e Desktop; 
- Identidade visual com palheta de cores (até 05) e fontes;
- Possuir controle de acesso de usuários;
- Ter entre 05 e 10 componentes distintos do [Bootstrap](http://www.getbootstrap.com/). Entende-se como componentes tudo da seção Components;
- Diagrama Entidade-Relacionamento do banco de dados;
- O sistema precisa ter autenticação de usuários.

# Sistema de eventos

Tamanho de Equipe: **3** (+1)

## Descrição narrativa

O sistema de eventos tem como objetivo ajudar a instituições de ensino superior a fazer a gerência completa de um evento acadêmico (palestras, workshops, atividades de extensão, mostras e afins) em forma de divulgação. Cada evento possui informações, tais como nome, data de início e fim, local, organizadores, detalhes do evento e folder. O proponente do evento informa os dados supracitados para cadastrar o evento no sistema. 

Para a comunidade acadêmica inserir-se em um evento na condição de participante, é necessário ativar um cadastro com a matrícula e senha. Ao acessar a página inicial, é mostrado o calendário mensal e os eventos próximos de acontecer com algumas informações resumidas. É possível também buscar eventos.

Ao entrar no sistema, os participantes podem confirmar participação nos eventos. Em uma área específica, é possível acessar todo o histórico de participação, bem como fazer o download de certificados de participação.

Após a realização de um evento, a comunidade pode avaliar a organização do evento, emitindo opniões em forma de comentários e avaliação de estrelas.

Em outra área do sistema, é possível visualizar eventos passados e organizá-los por filtros que ranqueiam os eventos com base no número de avaliações, comentários, com maior ou menor participação, dentre outros.

## Requisitos específicos resumidos

- Fazer cadastro de evento;
- Fazer inscrição em evento;
- Vincular evento ao campi;
- Gerar certificado de participação;
- Evento precisa indicar nome, data de início e fim, local, organizadores, detalhes do evento, folder do evento;
- Visualizar agenda de eventos (mini-calendário);
- Avaliar o evento com estrelas e comentários;
- Pro organizador, mostrar um dashboard de engajamento dos eventos, mostrar participantes;
- Fazer busca por eventos com filtros variados.
