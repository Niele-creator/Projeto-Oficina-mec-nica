# Projeto-Oficina-mecânica 
Oficina Mecânica - Banco de Dados

Descrição do Projeto

Este projeto consiste na modelagem e implementação de um banco de dados relacional para gerenciar uma oficina mecânica. O sistema foi projetado para registrar informações de clientes, veículos, equipes de mecânicos, ordens de serviço e controle de serviços e peças utilizadas em cada atendimento.

Objetivo

O objetivo principal deste banco de dados é garantir um gerenciamento eficiente e organizado dos processos da oficina, permitindo:

Cadastro de clientes e seus respectivos veículos;

Registro de mecânicos e suas especialidades;

Atribuição de equipes para ordens de serviço;

Controle detalhado dos serviços prestados e peças utilizadas;

Atualização do status das ordens de serviço.


Estrutura do Banco de Dados

Principais Tabelas

1. Cliente: Contém informações pessoais e de contato dos clientes.


2. Veiculo: Armazena informações sobre os veículos dos clientes.


3. Equipe: Define as equipes de mecânicos da oficina.


4. Mecanico: Registra os mecânicos e suas respectivas equipes.


5. OrdemServico: Contém as ordens de serviço, incluindo status e valores.


6. Servico: Lista os serviços prestados e seus respectivos custos.


7. Peca: Armazena as peças disponíveis para reparos.


8. ServicoExecutado: Relaciona os serviços realizados a cada ordem de serviço.


9. PecaUtilizada: Relaciona as peças utilizadas a cada ordem de serviço.



Regras de Negócio

Um cliente pode possuir vários veículos.

Cada ordem de serviço está associada a um cliente e a um veículo.

Equipes de mecânicos são atribuídas para executar ordens de serviço.

Uma ordem de serviço pode conter múltiplos serviços e peças utilizadas.

O status da ordem de serviço pode ser 'Aberta', 'Em andamento', 'Concluída' ou 'Cancelada'.


Tecnologias Utilizadas

Banco de Dados: MySQL

Linguagem SQL: Para criação e manipulação de tabelas

Ferramentas de Modelagem: Diagramas relacionais para estruturação do banco de dados

