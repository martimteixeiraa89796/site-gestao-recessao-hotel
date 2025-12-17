---
sidebar_position: 2
---

# Iniciar base de dados

## Diagrama da base de dados

Mesmo tendo a aplicação pronta a ser utilizada, a base de dados da mesma vem vazia por padrão.
A base de dados está organizada tal como a figura a abaixo demonstra:

![Diagrama base de dados](/img/basedados/diagrama_bd.png)

## Ordem de inicialização

Para iniciar a base de dados pela primeira vez, é necessário populá-la de forma a evitar o risco de depenências em chaves que
ainda não existam. No fim da sua inicialização, sempre que for preciso adicionar dados à base de dados, dependendo do tipo a ser inserido, será necessário consultar a ordem de introdução de dados.

O utilizador deverá, pela ordem apresentada, proceder a:

1. Popular hotel
   - Inserir tipos de objetos (Classificações de camas, quartos e reservas);
   - Inserir os quartos disponíveis no hotel;
   - Colocar camas nos quartos do hotel;
2. Popular funcionários
   - Inserir as funções disponíveis no hotel que funcionários podem ocupar;
   - Inserir os funcionários do hotel;
   - Criar horários de trabalho para os funcionários;
3. Popular receção
   - Inserir clientes interessados no hotel;
   - Iniciar o processo de reserva;
   - Inserir a reserva e os clientes na tabela de hospedes;

O utilizador deverá verificar quais dos passos principais mais se enquadra no que pretende fazer e,
seguir os passos segundo a ordem de execução.

Cada um dos passos mencionados acima serão explicados mais a fundo nas páginas seguintes.