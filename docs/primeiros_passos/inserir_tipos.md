---
sidebar_position: 2
---

# Iniciar base de dados

## Diagrama da base de dados

Mesmo tendo a aplicação pronta a ser utilizada, a base de dados da mesma vem vazia por padrão.
A base de dados está organizada tal como a figura a abaixo demonstra:

![Diagrama base de dados](/img/placeholder.png) colocar imagem do diagrama aqui

## Inserir tipos de objetos

Para começar a popular a base de dados, começamos pelos itens que apresentam menos dependências, ou seja, começamos por inserir listas dos tipos de objetos que o hotel possui.

### Tipos de objetos

Existem 3 tipos de objetos na base de dados:

| Tipo    | Função                                                                                             |
|---------|----------------------------------------------------------------------------------------------------|
| Cama    | Quartos podem ter mais do que um tipo de cama, podendo variar em qualidade ou assistência especial |
| Quarto  | O hotel pode especificar a qualidade ou certas diferenças entre vários quartos                     |
| Reserva | Pode ser feita a distinção entre reservas com detalhes como VIP ou outros                          |