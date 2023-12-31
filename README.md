<!-- ---
layout: home
author_profile: true
title: Exemplo de Documento de Requisitos de Software
permalink: /lessons/softeng/requirements/req/sample/
sidebar:
  nav: "softeng-requirements"
--- -->

# Capa

---

<h1>Requisitos de Software</h1>

<h2>Sistema de Varejo (SDV)</h2>

<small>Versão 1.0</small>

---

## Histórico de revisões

|    Data    | Versão |          Descrição          |              Autor                |
| :--------: | :----: | :-------------------------: | :-------------------------------: |
| 01/04/2023 |  1.0   |    Criação do documento     | Marcos AND Lima / Vamberto Junior |


---

## Sumário

- [Capa](#capa)
  - [Histórico de revisões](#histórico-de-revisões)
  - [Sumário](#sumário)
- [Introdução](#introdução)
  - [Definições, Acrônimos e Abreviações](#definições-acrônimos-e-abreviações)
- [Usuários identificados](#usuários-identificados)
- [Requisitos funcionais](#requisitos-funcionais)
- [Requisitos não-funcionais](#requisitos-não-funcionais)
  - [Disponibilidade](#disponibilidade)
  - [Privacidade e segurança](#privacidade-e-segurança)
  - [Usabilidade](#usabilidade)
  - [Suportabilidade](#suportabilidade)
  - [Interoperabilidade](#interoperabilidade)
  - [Manutenibilidade](#manutenibilidade)
  - [Desempenho](#desempenho)
  - [Implementação](#implementação)
  - [Implantação](#implantação)
- [Matriz de rastreabilidade](#matriz-de-rastreabilidade)
  - [Rastreabilidade entre NFs e RNFs](#rastreabilidade-entre-nfs-e-rnfs)

---

# Introdução

O objetivo deste documento é apresentar os requisitos de software do produto **Sistema de Varejo (SDV)**

## Definições, Acrônimos e Abreviações

Esta subseção fornece as definições de todos os termos, acrônimos e abreviações necessárias à adequada interpretação do Documento de Requisitos.

- Identificação dos requisitos: por convenção, a referência a requisitos é feita através do identificador de requisitos, de acordo como descrito abaixo:

  `[IDENTIFICADOR DO TIPO DE REQUISITOSidentificador do requisito]`

  O identificador do tipo de requisitos é conforme abaixo:

  - RF – Requisito Funcional
  - RNF – Requisito Não-Funcional
  - NR – Não-Requisito

  O identificador do requisito será uma sequência numérica. Esse número sequencial será único para todo o conjunto de tipos de requisitos.

  **Exemplo**: RF0001, RF1234, RNF1234, NR1212

- Atributos dos Requisitos: os atributos de requisitos estabelecidos são:
  - **Requisitos vinculados**: fornece uma lista dos requisitos que mantém rastreabilidade.
  - **Prioridade**: Essencial, Importante, Desejável
  - **Complexidade**: Complexa, Alta, Média ou Baixa.
  - **Risco**: Alto, Médio, Baixo

# Usuários identificados

Os seguintes usuários foram identificados para o sistema:

- Clientes: vão usar o software para gerenciar garantias de produtos.
- Funcionários: vão usar o software para fornecer suporte aos clientes.

# Requisitos funcionais

Os requisitos funcionais são descritos a seguir.

- **[RF001]** - O sistema deve permitir que os clientes visualizem o catálogo de produtos e seus preços.
- **[RF002]** - O sistema deve permitir que os clientes façam pedidos de produtos.
- **[RF003]** - O sistema deve permitir que os clientes rastreiem o status de seus pedidos.
- **[RF004]** - O sistema deve permitir que os clientes solicitem suporte.
- **[RF005]** - O sistema deve permitir que os funcionários visualizem o estoque de produtos.
- **[RF006]** - O sistema deve permitir que os funcionários processem pedidos de produtos.
- **[RF007]** - O sistema deve permitir que os funcionários atendam clientes.
- **[RF008]** - O sistema deve permitir que os funcionários forneçam suporte.

# Requisitos não-funcionais

Os requisitos não-funcionais são descritos a seguir.

## Disponibilidade

- **[RNF001]** - O sistema deve ser desenvolvido de forma que possa ser implantado em qualquer plataforma.
- **[RNF011]** - O sistema deve ser acessível a partir de qualquer dispositivo com conexão à internet.
- **[RNF012]** - O sistema deve estar disponível 24 horas por dia, 7 dias por semana, 365 dias por ano.
- **[RNF013]** - O sistema deve ser escalável para suportar um grande número de clientes.
- **[RNF014]** - O sistema deve ser seguro e proteger as informações dos clientes.
- **[RNF015]** - O sistema deve ser fácil de usar.

## Privacidade e segurança

- **[RNF002]** - O sistema deve ser desenvolvido de forma que os dados dos clientes sejam protegidos e não sejam acessíveis por terceiros.
- **[RNF003]** - O sistema deve atender aos requisitos de privacidade da LGPD (Lei Geral de Proteção de Dados).
- **[RNF016]** - O sistema deve ser desenvolvido de forma que os dados pessoais dos clientes sejam criptografados, como endereço de e-mail, senha, nome completo, cidade e estado. A criptografia deverá ser realizada com o algoritmo SHA-512, e deve impossibilitar a recuperação dos dados originais.

## Usabilidade

- **[RNF004]** - O sistema deve ser desenvolvido de forma que seja fácil de usar e de fácil aprendizado, de forma que os usuários não precisem de treinamento para utilizá-lo.
- **[RNF019]** - O sistema deve ser desenvolvido de forma que possa ser acessado por pessoas com deficiência visual, auditiva e física.

## Suportabilidade

- **[RNF005]** - O sistema deve ser desenvolvido de forma que possa ser executado nos três principais navegadores da web: Google Chrome, Mozilla Firefox e Microsoft Edge através de um computador com sistema operacional Windows, Linux ou Mac OS, bem como tablets e smartphones com sistema operacional Android ou iOS.
- **[RNF006]** - O sistema deve ser desenvolvido de forma que possa ser executado em aplicativos nativos para Android e iOS.

## Interoperabilidade

- **[RNF007]** - O sistema deve ser desenvolvido de forma que possa ser integrado com a API do Google para autenticação de usuários.

## Manutenibilidade

- **[RNF008]** - O sistema deve ser desenvolvido de forma que possa ser facilmente atualizado e mantido, preferencialmente, de maneira automatizada.
- **[RNF009]** - O sistema deve ser desenvolvido de forma que possa ser facilmente testado e validado, de forma manual e automatizada.
- **[RNF017]** - O sistema deve ser documentado de forma que possa ser facilmente compreendido por terceiros e para facilitar a manutenção do sistema.

## Desempenho

- **[RNF010]** - O sistema deve ser desenvolvido de forma que possa ser executado em qualquer dispositivo com conexão à internet, com velocidade de conexão de no mínimo 1 Mbps com tempo de resposta de no máximo 5 segundos.

## Implementação

- **[RNF015]** - O sistema deve ser desenvolvido com APIs de acesso aos dados, para que possa ser integrado com outros sistemas.

## Implantação

- **[RNF018]** - O sistema deve ser desenvolvido de forma que possa ser implantado em qualquer plataforma de software atualizada.
- **[RNF020]** - O sistema deve ser desenvolvido de forma que possa ser implantado em plataformas de hardware x64 e ARM64, com arquitetura mínima de 64 bits.
- **[RNF021]** - O sistema deve ser verificado quanto ao desempenho mínimo tolerado dos lados servidor e clientes. As especificações sobre pré-requisitos de hardware e software para a execução do sistema devem ser apresentadas em uma página de pré-requisitos, que deve ser acessível a partir do rodapé do site.

# Matriz de rastreabilidade

A matriz de rastreabilidade é apresentada a seguir.

## Rastreabilidade entre NFs e RNFs

| RF / RNF | RF001 | RF002 | RF003 | RF004 | RF005 | RF006 | RF007 | RF008 | 
| :------: | :---: | :---: | :---: | :---: | :---: | ----- | ----- | ----- | 
|  RNF001  |       |       |       |       |       |       |       |       | 
|  RNF002  |       |       |   X   |   X   |   X   |       |       |       | 
|  RNF003  |       |       |   X   |   X   |   X   |       |       |       |
|  RNF004  |       |       |       |       |       |       |       |       | 
|  RNF005  |       |       |       |       |       |       |       |       | 
|  RNF006  |       |       |       |       |       |       |       |       |
|  RNF007  |       |       |       |       |       |       |       |       |
|  RNF008  |       |       |       |       |       |       |       |       |
|  RNF009  |       |       |       |       |       |       |       |       |
|  RNF010  |       |       |       |       |       |       |       |       | 
|  RNF011  |       |       |       |       |       |       |       |       |
|  RNF012  |       |       |       |       |       |       |       |       | 
|  RNF013  |       |       |       |       |       |       |       |       | 
|  RNF014  |       |       |       |       |       |       |       |       | 
|  RNF015  |       |       |       |       |       |       |       |       | 
|  RNF016  |       |       |       |       |       |       |       |       | 
|  RNF017  |       |       |       |       |       |       |       |       | 
|  RNF018  |       |       |       |       |       |       |       |       | 
|  RNF019  |       |       |       |       |       |       |       |       | 
|  RNF020  |       |       |       |       |       |       |       |       | 
|  RNF021  |       |       |       |       |       |       |       |       | 


Criado em Outubro de 2023 por _Marcos AND Lima // Vamberto Jr_
