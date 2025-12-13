# Site para o projeto Gestão de Recessão de Hotel

Site feito com Docusaurus para o projeto de Universidade utilizando ferramenta Git.
Aplicação de gestão de recessão de hotel.

## Sobre o Site

Este site foi construído com recurso ao gerador de sites estáticos Docusaurus.

## Sobre o repositório

### Clonar repositório

Executar comando abaixo num diretório na máquina local, à sua escolha.
Só precisa de ser executado uma vez para criar uma cópia do repositório.

``` git
git clone https://github.com/martimteixeiraa89796/gestao-recessao-hotel.git
```

### Instalar dependências do Docusaurus

Executar comando abaixo no diretório do site.
Só precisa de ser executado uma vez para instalar o Docusaurus.

``` node
npm install
```

### Ramos Principais

- **main:** Ramo para o site final/estável.
- **dev:** Ramo geral para o site em desenvolviemnto.
- **src_static:** Ramo para páginas estáticas do site.
- **site_blog:** Ramo para o blog do site.
- **site_docs:** Ramo para tutoriais ou outra documentação do site.

> [!IMPORTANT]
> Não apagar ramos utilizados, eles vão ser usados para avaliação.

### Merging Ramos

Fazemos ***merges*** para atualizar um ramo com alterações de outros ramos.

Primeiro fazer ***checkout*** no ramo que queremos atualizar:

``` git
git checkout <inserir ramo aqui>
```

depois fazer o ***merge*** com o ramo que tem as alterações que queremos:

``` git
git merge <inserir ramo aqui>
```

> [!Note]
> Podem surgir conflitos. Para os resolver devemos ver qual das diferenças queremos que permaneçam no ***merge***.

---

## Contribuir para o repositório

### Fazer *Pull* do repositório (Atualizar/*Download*)

Primeiro fazer ***checkout*** no ramo que queremos:

``` git
git checkout <inserir ramo aqui>
```

Depois fazer ***pull*** do ramo:

``` git
git pull
```

> [!Note]
> Isto faz um ***merge*** automático do ***remote*** com o ***local***, por isso podem surgir casos de conflito que terão de ser resolvidos como nos ***merges*** normais.

### Fazer *Push* do repositório (*Upload*)

Primeiro fazer ***checkout*** no ramo que queremos:

``` git
git checkout <inserir ramo aqui>
```

Depois fazer ***push*** do ramo:

``` git
git push
```

> [!Note]
> Se o ***push*** não funcionar tenta fazer ***pull*** do repositório.