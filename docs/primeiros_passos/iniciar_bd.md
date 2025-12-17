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

## Inserir tipos de objetos

Para começar a popular a base de dados, começamos pelos itens que apresentam menos dependências, ou seja, começamos por inserir listas dos tipos de objetos que o hotel possui.

### Tipos de objetos

Existem 3 tipos de objetos na base de dados:

| Tipo    | Função                                                                                             |
|---------|----------------------------------------------------------------------------------------------------|
| Cama    | Quartos podem ter mais do que um tipo de cama, podendo variar em qualidade ou assistência especial |
| Quarto  | O hotel pode especificar a qualidade ou certas diferenças entre vários quartos                     |
| Reserva | Pode ser feita a distinção entre reservas com detalhes como VIP ou outros                          |

Estes objetos são dependências de várias outra tabelas, por esta razão, é importante que antes se inserir qualquer dado,
os mesmos tenham de já estar defenidos. Caso haja posteriormente a necessidade de se adicionar novos tipos de objetos, o mesmo pode ser feito.

### Adicionar à base de dados

Adicionar estes tipos de objetos é muito fácil. Basta abrir o menu inicial da aplicação e escolher a opção 3,
que corresponde à inserção de dados.

![Menu inicial da aplicação](/img/aplicacao/menu_inicial.png)

Após a escolha, será apresentado uma lista com as tabelas. Deverá escolher as tabelas referente aos tipos mencionados anteriormente.

1. Tb_Tipo_Cama
2. Tb_Tipo_Quarto
3. Tb_Tipo_Reserva

![Lista de tabelas](/img/aplicacao/inserir_dados.png)

Após ser feita a escolha do tipo a inserir, vai-lhe ser perguntado o nome que quer dar ao tipo. Esta ação é semelhante para os 3 tipos mencionados anteriormente.

![Processo de inserção de tipos](/img/aplicacao/insercao_dados/tipos.png)