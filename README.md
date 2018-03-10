# Brasil Open
Projeto que visa reunir e padronizar repositórios de dados abertos do Brasil.

## O projeto

### Problema

Muitos não sabem, mas o Brasil é hoje o 8° país com maior transparência de dados públicos no mundo. Mas apesar desta transparência, os dados públicos ainda não são bem utilizados por um problema de má organização.

### Proposta

O projeto tem o intuito de centralizar os dados públicos em um único lugar, padronizando o acesso para futuros projetos que venham a utilizá-los. Facilitando iniciativas que possam vir a fazer uso desses dados.

### Arquitetura Proposta

O projeto como um todo pode ser dividido em 4 componentes:
- Crawlers: aplicações que consomem os repositórios de dados oficiais fornecidos pelo [
Portal Brasileiro de Dados Abertos
](http://dados.gov.br/) de forma agendada ou reativa

## Crawlers

Parte onde será necessário o maior esforço do projeto. Aplicações que executarão consultas periodicamente dos dados gorvernamentais. Como esses dados hoje estão desorganizados, será necessário a criação de diversos crawlers, um para cada instituição.

## Armazenamento de dados

O projeto trabalha em cima de um domínio obscuro. Não é possível determinar quando as instituições mudarão a forma como distribuirão os dados. Por esse motivo e por estar-se trabalhando com uma grande quantidade de dados, serão utilizadas formas de armazenamento NoSQL.

## API

Como principal objetivo do projeto, a API será a interface de comunicação com os dados armazenados. Esta disponibilizará os dados em forma de JSON.

## Interface de visualização

Assim como desenvolvedores podem vir a usar a API para construir aplicações, outros usuários podem vir a utilizá-la com o intuito de pesquisa. Para estes, é ideal uma interface de exibição dos dados.

## Documentação

Para que o projeto faça sentido, outras pessoas devem conseguir entendê-lo e utilizá-lo. Por isso, junto com o projeto, será construída uma documentação explicando sua estrutura e como consultar cada tipo de dado.

## Acessos

A API, as páginas de exibição e a documentação serão de livre acesso. O banco, por questões de segurança, terá uma quantidade de pessoas restrita que poderão acessá-lo. O código dos crawlers estará sempre disponível no Git e qualquer um é bem-vindo a contribuir com o projeto.

## Contribuindo
[Acesse aqui](https://github.com/brasilapi/brapi/blob/master/CONTRIBUTING.md) o arquivo de contribuição do projeto.

## Comunidade

Foi criado um [grupo no Telegram](https://t.me/joinchat/CnB8oELd_FLZM_KELhnHwg) com o intuito de discutir o projeto.
