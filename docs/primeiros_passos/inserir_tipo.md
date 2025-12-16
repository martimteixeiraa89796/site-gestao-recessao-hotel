# Inserir dados

## Tipos de objetos

Existem 3 tipos de objetos na base de dados:

| Tipo      |Função                                                                                   |
|-----------|------------------------------------------------------------------------------------------|
| Funções   | Identifica os cargos dos funcionários, definindo permissões e responsabilidades dentro do hotel |
| Clientes  | Representa os hóspedes do hotel, permitindo controlar reservas, estadias e informações pessoais |
| Quartos   | Representa os espaços físicos do hotel, permitindo associar cada quarto a um tipo específico, controlar o preço, verificar ocupação e gerir reservas. |

Estes objetos são dependências de várias outra tabelas, por esta razão, é importante que antes se inserir qualquer dado, os mesmos tenham de já estar defenidos. Caso haja posteriormente a necessidade de se adicionar novos tipos de objetos, o mesmo pode ser feito.

### Adicionar à base de dados

Adicionar estes tipos de objetos é muito fácil. Basta abrir o menu inicial da aplicação e escolher a opção 3,que corresponde à inserção de dados.

![Menu inicial da aplicação](/img/aplicacao/menu_inicial.png)

Após a escolha, será apresentado uma lista com as tabelas. Deverá escolher as tabelas referente aos tipos mencionados anteriormente.

4. Tb_Funcões
5. Tb_Cliente
6. Tb_Quato

![Lista de tabelas](/img/aplicacao/inserir_dados.png)

Após ser feita a escolha do tipo a inserir, vai-lhe ser perguntado o nome que quer dar ao tipo. Esta ação é semelhante para os 3 tipos mencionados anteriormente.

![Lista de tabelas](/img/aplicacao/inserir_Quartos.png)