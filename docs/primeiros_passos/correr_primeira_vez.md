---
sidebar_position: 1
---

# Correr a aplicação pela primeira vez

## Iniciar a aplicação

Começar a utilizar a aplicação é muito fácil. Basta abrir uma linha de comandos no diretório da aplicação e correr o seguinte comando:

``` python
python.exe .\main.py
```

Isto vai inicializar a aplicação todas as suas componentes. Pronta a usar quando aparecer o menu inicial.

![Menu inicial da aplicação](/img/aplicacao/menu_inicial.png)

A partir deste momento, a aplicação está pronta para ser usada e, devido à sua natureza portátil,
o utilizador por lever o diretório da aplicação para qualquer outra máquina que tenham as dependências necessárias.

## Verificação de Tabelas

A nossa aplicação é o quanto possível inteligente, no que diz respeito às tabelas da base de dados.
Uma vez que estas são o núcleo da aplicação, é necessário verificar se as mesmas existem antes de se utilizar a aplicação.

A boa notícia é que a nossa aplicação faz essa mesma verificação, automáticamente na sua inicialização.

![Verificação de tableas no inicio da aplicação](/img/aplicacao/verifi_tabelas.png)