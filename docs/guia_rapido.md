---
sidebar_position: 7
---

# Guia rápido da Aplicação

## Visualização de Dados

O opção **Visualizar Dados** permite que os funcionários do hotel **consultem informações existentes** na aplicação, como tipos de quarto, reservas, clientes ou horários.

### Como Visualizar Dados

1. **Escolher a Opção de Visualização**
   - A aplicação apresenta duas formas de visualização:
     1. **Ver Tabelas**: mostra todas as tabelas disponíveis, permitindo consultar todos os registos de cada tabela.
     2. **Dados Específicos**: permite consultar o tipo de cama, horários de chegada de clientes, clientes, entre outros.

2. **Ver Tabelas**
   - Ao selecionar esta opção, o funcionário pode escolher qualquer tabela do sistema, por exemplo:
     - Tipos de Cama
     - Tipos de Quarto
     - Tipos de Reserva
     - Clientes
     - Quartos
     - Funcionários
     - Horários
     - Hóspedes
   - A aplicação exibe todos os registos dessa tabela, permitindo consultar a informação

3. **Dados Específicos**
   - Esta opção mostra as consultas mais especificas, como:
     - Ver horários registados no sistema
     - Consultar quartos livres
     - Ver clientes alojados nos quartos
     - Acompanhar chegadas de clientes
     - Contar o número de camas disponíveis
     - Consultar a duração da estadia dos hóspedes
   - O funcionário escolhe a consulta desejada e o sistema retorna os dados correspondentes.

Exemplo de uma visualização da tabela de hospedes

![exemplo de visualização](/img/aplicacao/visualizacao/visualizacao.png)

## Atualização de Dados

A opção **Atualizar Dados** permite ao funcionario ou gerente alterar **alterar informações existentes** no sistema, como tipos de quarto, reservas, clientes e horários.

### Como Atualizar Dados

1. **Escolher a Tabela**
   - Esta aplicação vai mostra uma lista de tabelas disponíveis (ex: Tipos de Cama, Tipos de Quarto,  Clientes, Quartos, Reservas, Funcionários, Horários, Hóspedes)
   - O funcionário e o Gerente seleciona a tabela que quer atualizar.

2. **Escolher o Campo**
   - Depois de selecionar a tabela, aparecem os campos que podem ser alterados.
   - Por exemplo, na tabela **Tipos de Cama**, os campos disponíveis podem ser:
     - Número do Tipo de Cama
     - Nome do Tipo de Cama
   - O funcionário/Gerente escolhe qual campo deseja atualizar.

3. **Definir o Registo a Alterar**
   - A aplicação pede para indicar qual registo será alterado.
   - É feito escolhendo um  **Numero ou texto**.

4. **Selecionar o Tipo de Dado**
   - O sistema pede para escolher o tipo de dado do campo:
     - Número Inteiro (Int)
     - Número Decimal
     - Texto (String)
   - Isto garante que o sistema processe corretamente a alteração.

5. **Confirmar Alteração**
   - Após escolher tabela, campo, registo e tipo de dado, o sistema aplica a alteração feita pelo funcionario/gerente.
   - Uma mensagem de confirmação aparece, indicando que a atualização foi feita.

## Inserir Dados

A opção Inserir Dados permite aos funcionarios/gerente  do hotel adicionar novos registros á aplicação, com novos tipos de quarto, camas, reservas.

### Como Inserir Dados

1. **Escolher a Tabela**
   - Ao selecionar **Inserir Dados**, a aplicação apresenta uma lista com as tabelas disponíveis:
     - Tipos de Cama
     - Tipos de Quarto
     - Tipos de Reserva
     - Funções
     - Clientes
     - Quartos
     - Funcionários
     - Camas
     - Reservas
     - Horários
     - Hóspedes
   - O funcionário/gerente escolhe a tabela onde quer adicionar um registo.

2. **Preencher os Campos**
   - Depois de escolher a tabela, a aplicação solicita que sejam preenchidos os **dados necessários** para criar o novo registo.

3. **Confirmar Inserção**
   - Após o funcionario preencher os campos obrigatórios, a aplicação adiciona automaticamente o novo registo à tabela.
   - E vai aparecer uma mensagem de confirmação no ecrã, para indicar que o registro foi um sucesso.

## Apagar Dados

A opção **Apagar Dados** permite ao funcionario e o gerente do hotel remover as informacões da aplicação seja apagando regidtros de uma tabela ou apenas dados expecíficos.

### Como Apagar Dados

1. **Escolher opção**
    -Ao selecionar **Apagar Dados**, a aplicação apresenta duas opções:
    1. **Apagar Todos os Dados**: serve para remover todos os registos de uma tabela.
    2. **Apagar Dado Específico**: serve para remover apenas registos selecionados conforme critérios

2. **Apagar Todos os Dados**
   - O funcionário escolhe a tabela que vai limpar completamente (ex: Tipos de Reserva, Clientes, Quartos).
   - A aplicação apaga todos os registos da tabela escolhida pelo funcionário ou gerente.
   - Uma mensagem vai aparecer após a operação.

3. **Apagar Dado Específico**
   - O funcionário escolhe a tabela onde quer apagar um registo específico.
   - Depois, seleciona o campo que será usado como **condição** para localizar o registo.
   - Coloca o valor do registo que deseja apagar.
   - Escolhe o **tipo de dado** correspondente (Número Inteiro, Decimal ou Texto) para garantir que a aplicação faça corretamente.
   - A aplicação remove apenas o registo que corresponde à condição fornecida.
   - Uma mensagem de confirmação aparece após a operação esteja feita.
