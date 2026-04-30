### 🌐 Gerador de Dados Falsos (ISP Edition) 🚀

Este repositório contém um script Python desenvolvido para a geração de dados fictícios contextualizados de acordo com minha realidade profissional atual. Neste código será gerado duas massas de dados de teste(Tabela de Clientes e Tabela de Instalações) com objetivo de inicializar um dataset para estudos de visualização de dados e eventualmente programação.

Neste link é possível visualizar um resumo do algoritmo na plataforma Notion [![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/Projeto-de-Dados-I-299dcbd225b28041863ff72789d3d34d?source=copy_link)

### 📡 Contexto do Projeto

O foco principal deste gerador é o setor de Provedores de Internet (ISP). O script foi desenhado para simular uma base de dados operacional simples, permitindo que desenvolvedores e analistas trabalhem com estruturas de dados comuns nesse mercado sem lidar com informações sensíveis de clientes reais.

### 📋 A Tabela de Clientes

A principal funcionalidade é a criação de uma Tabela de Clientes simples, que inclui campos como:

>👤 Dados Pessoais: ID,Nome, idade, cargo profissional,telefone.

>💻 Serviços: Plano contratado (ex:Plano Básico - 500 Mega, Plano Pro - 750 Mega e Plano Full - 1Giga), data de Assinatura/Instalação.

>💰 Financeiro: Valor da fatura mensal(Plano Básico - R$99,90, Plano Pro - R$124,90, Plano Full - R$159,90).

E uma Tabela de Instalações, que inclui campos como:

>🛠️ Dados de Instalação: ID(id do cliente parsed),nome do técnico responsável, data da instalação.

>📋 Parâmetros técnico:sinal_dbm, status_sinal, nº de reclamações nos últimos 90 dias. 


### 🛠️ Tecnologias e Ferramentas

> Python 3.x 🐍: Linguagem base para a lógica de geração.

> Biblioteca Faker 🎭: Utilizada para gerar nomes e documentos brasileiros válidos.

> Pandas 🐼: Para organização dos dados em tabelas e exportação para formatos como .csv ou .sql.

### 💡 Por que usar este repositório?

> Segurança (LGPD): Teste suas aplicações sem utilizar dados reais de usuários.

> Escalabilidade: Gere de 10 a 1 milhão de linhas em poucos segundos. ⚡

> Treinamento: Perfeito para quem está aprendendo SQL ou Python para análise de dados.

### Aviso: Todos os dados gerados são aleatórios e possuem finalidade exclusiva de teste e aprendizado.
