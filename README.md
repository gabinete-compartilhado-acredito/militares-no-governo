# Militares no governo

Nesta análise, buscamos levantar a fração de cargos/funções comissionados (i.e. de livre escolha dos governantes)
de níveis altos ocupados por militares, mês a mês, de janeiro de 2013 a dezembro de 2021.

## 1. Resultados

O resultado dessa análise (com dados até a metade de 2020) foi publicado no [Antagonista](https://www.oantagonista.com/brasil/a-militarizacao-do-executivo-e-real-e-sem-precedentes/) e
no [Congresso em foco](https://congressoemfoco.uol.com.br/governo/militares-governo-tabata-alessandro/). Uma descrição detalhada do projeto e o gráfico
final podem ser encontrados [aqui](http://xavier.turmadafisica.net/militares_governo.html). A tabela com os número finais está disponível
[aqui](https://docs.google.com/spreadsheets/d/1e7qfBBNXN3FA7LFq08ymaocMeeakYcSrdD62OTfhVIE).

## 2. Estrutura do projeto

    .
    ├── LICENSE                                   <- Licença de uso, cópia e modificações
    ├── README.md                                 <- Este documento
    ├── militares_com_cargos_comissionados.ipynb  <- Jupyter notebook com a análise realizada
    ├── dados                                     <- Diretório onde colocar os dados (baixar dos links abaixo)
    └── resultados                                <- Diretório com os arquivos CSV produzidos pela análise ou para a visualização

## 3. Fonte de dados

Os dados brutos foram obtidos do [Portal da Transparência](http://www.portaltransparencia.gov.br/download-de-dados/servidores)
e da resposta ao Requerimento de Informação [RIC 791/2020](https://www.camara.leg.br/proposicoesWeb/fichadetramitacao?idProposicao=2257469).
Os dados selecionados e preparados por nós foram disponibilizados no Google Storage:

* [Cadastro de servidores civis com cargos/funções comissionadas](https://storage.googleapis.com/gab-compartilhado-publico/militares-no-governo/servidores_de_confianca_civis_ateh_2021-01.csv) (até 01/2021)
* [Cadastro de servidores civis com cargos/funções comissionadas](https://storage.googleapis.com/gab-compartilhado-publico/militares-no-governo/servidores_de_confianca_civis_2021-02_2021-12.csv) (de 02/2021 em diante)

* [Cadastro de servidores militares da ativa com cargos/funções comissionadas](https://storage.googleapis.com/gab-compartilhado-publico/militares-no-governo/servidores_de_confianca_militares_ateh_2021-01.csv)
* [Lista de militares inativos](https://storage.googleapis.com/gab-compartilhado-publico/militares-no-governo/militares_inativos_2019-01_2021-11.csv)

### Autoria

Esse projeto é uma realização do senador Alessandro Vieira (PSDB/SE) e da deputada Tabata Amaral (PSB/SP).
A análise e visualização foi feita por Henrique Xavier - [@hsxavier](https://github.com/hsxavier).

### Licença

Este projeto é distribuído sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
