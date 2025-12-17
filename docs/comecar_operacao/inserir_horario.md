---
sidebar_position: 3
---

# Inserir horário

Com os funcionários e as suas funções definidas, é preciso estabeler os horários de trabalhos para cada indivíduo. Para tal, vamos usar a tabela de horários.

## Sobre a tabela

Caso queira saber os campos que a tabela possui, refira-se ao [**diagrama**](/docs/primeiros_passos/iniciar_bd.md#diagrama-da-base-de-dados) da base de dados.

| Tabela     | Função                                                                              |
|------------|-------------------------------------------------------------------------------------|
| Tb_Horario | Guarda dados como o começo e fim de trabalho, respetivo funcionário e dias de folga |

Esta tabela é muita maleável, pelo que pode conter várias entradas para um funcionário.

## Adicionar à base de dados

Para selecionar uma tabela para inserir dados, é preciso escolher a opção 3, que corresponde à inserção de dados, do menu principal.

![Menu principal da aplicação](/img/aplicacao/menu_inicial.png)

Após a escolha, será apresentado uma lista com as tabelas disponíveis para escolha. Deverá escolher a tabela referente aos horários do funcionário.

10. Tb_Horario

![d](/img/aplicacao/inserir_dados.png)

## Processo de inserção

O processo de inserção de dados é muito fácil. A imagem a baixo demonstra o mesmo.

![Inserir horario](/img/aplicacao/insercao_dados/horario.png)

### Explicação

Tendo em conta a natureza maleável da tabela, a mesma pode apresentar uma quantidade abismal de dados, pelo que é preciso
ter noção do que se está a colocar nesta tabela.

1. Primeiro é preciso inserir o número do funcionário, para isso é preciso que o respetivo funcionário exista;
2. Introduzir o dia da semana onde necessita de informação;
3. Por fim basta inserir uma nota do torno de trabalho ou, caso pertinente, algo como folga ou incapacidade.