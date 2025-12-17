---
sidebar_position: 3
---

# Registar Hóspedes

Nesta secção do tutorial é explicado como funciona a opção Registar Hóspedes da aplicação, utilizada no momento de iniciar o atendimento na receção do hotel.

Esta funcionalidade permite associar um cliente a uma reserva e a um quarto, registando oficialmente a sua estadia no sistema.

## Acesso à funcionalidade

No menu principal da aplicação, o utilizador deve selecionar a opção Inserir dados.  
De seguida, é apresentada uma lista com as tabelas disponíveis na base de dados.

![Menu apagar dados](/img/aplicacao/inserir_dados2.png)

Ao escolher a tabela Hospede, a aplicação inicia o processo de registo de um novo hóspede.

## Introdução do número da reserva

O primeiro passo é inserir o número da reserva associada ao hóspede.  
Este número identifica a reserva previamente criada no sistema e permite ligar o hóspede ao período de estadia correto.

![Menu apagar dados](/img/aplicacao/inserir_dados2_numReserva.png)

## Identificação do cliente

De seguida, o utilizador deve inserir o NIF do cliente.  
Este dado permite identificar quem é o cliente responsável pela reserva e associá-lo corretamente ao hóspede que será registado.

![Menu apagar dados](/img/aplicacao/inserir_dados2_numReserva_nifCliente.png)

## Reserva em nome do cliente

A aplicação pergunta se a reserva foi feita em nome deste cliente.
O utilizador deve escolher entre as opções disponíveis (verdadeiro ou falso), indicando se o hóspede é o titular da reserva ou apenas um acompanhante.

![Menu apagar dados](/img/aplicacao/inserir_dados2_numReserva_nifCliente_confirmar.png)

## Escolha do quarto

Após isso, o utilizador deve inserir o número do quarto onde o hóspede ficará alojado.  
Este passo é importante para garantir que o sistema sabe exatamente em que quarto o hóspede está hospedado.

![Menu apagar dados](/img/aplicacao/inserir_dados2_numReserva_nifCliente_confirmar_numQuarto.png)

## Registo do hóspede

Depois de todos os dados serem introduzidos, a aplicação executa a operação de inserção e regista o hóspede na base de dados.  
A partir desse momento, o hóspede passa a fazer parte do sistema e a sua estadia fica corretamente associada à reserva e ao quarto.

