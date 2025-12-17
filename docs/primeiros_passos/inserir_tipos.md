---
sidebar_position: 3
---

# Inserir tipos de objetos

Para começar a popular a base de dados, começamos pelos itens que apresentam menos dependências, ou seja, começamos por inserir listas dos tipos de objetos que o hotel possui.

## Tipos de objetos

Existem 3 tipos de objetos que o hotel pode classificar:

| Tipo    | Função                                                                                             |
|---------|----------------------------------------------------------------------------------------------------|
| Cama    | Quartos podem ter mais do que um tipo de cama, podendo variar em qualidade ou assistência especial |
| Quarto  | O hotel pode especificar a qualidade ou certas diferenças entre vários quartos                     |
| Reserva | Pode ser feita a distinção entre reservas com detalhes como VIP ou outros                          |

Estes objetos são dependências de várias outra tabelas, por esta razão, é importante que antes se inserir qualquer dado,
os mesmos tenham de já estar defenidos. Caso haja posteriormente a necessidade de se adicionar novos tipos de objetos, o mesmo pode ser feito.

## Adicionar à base de dados

Adicionar estes tipos de objetos é muito fácil. Basta abrir o menu inicial da aplicação e escolher a opção 3,
que corresponde à inserção de dados.

![Menu inicial da aplicação](/img/aplicacao/menu_inicial.png)

Após a escolha, será apresentado uma lista com as tabelas. Deverá escolher as tabelas referentes aos tipos mencionados anteriormente.

1. Tb_Tipo_Cama
2. Tb_Tipo_Quarto
3. Tb_Tipo_Reserva

![Lista de tabelas](/img/aplicacao/inserir_dados.png)

Após ser feita a escolha do tipo a inserir, vai-lhe ser perguntado o nome que quer dar ao tipo. Esta ação é semelhante para os 3 tipos mencionados anteriormente.

![Processo de inserção de tipos](/img/aplicacao/insercao_dados/tipos.png)