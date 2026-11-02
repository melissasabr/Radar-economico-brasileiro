# 🇧🇷 Radar Econômico Brasileiro

**Uma plataforma de automação e análise de indicadores econômicos que transforma dados públicos em informações acessíveis por meio de dashboards e inteligência artificial generativa.**

> **Status:** Em desenvolvimento — fase inicial de planejamento e arquitetura.

## 🎯 Problema e proposta de solução

Acompanhar indicadores como juros, inflação e câmbio exige consultar diferentes fontes e interpretar informações que nem sempre são apresentadas de forma acessível.

O Radar Econômico Brasileiro propõe automatizar a coleta, organização e análise desses indicadores, reunindo os dados em um ambiente centralizado e utilizando IA generativa para produzir resumos em linguagem simples.

O objetivo é transformar dados econômicos em informações mais fáceis de compreender e acompanhar.

## 📊 Indicadores econômicos

| Indicador | Fonte planejada |
|---|---|
| Taxa Selic      | Banco Central — API SGS |
| IPCA (inflação) | Banco Central — API SGS |
| Dólar comercial | Banco Central — API PTAX |

Outros indicadores poderão ser incorporados conforme a evolução do projeto.

## ⚙️ Arquitetura da solução

O projeto será desenvolvido em etapas:

1. **Coleta de dados:** utilização do n8n para consultar as APIs públicas do Banco Central em intervalos programados.
2. **Tratamento e validação:** organização dos dados, verificação de valores e padronização das informações.
3. **Armazenamento:** utilização do PostgreSQL para persistência dos indicadores, com controle de duplicidade dos registros.
4. **Visualização:** desenvolvimento de dashboards no Power BI para acompanhar a evolução dos indicadores.
5. **Inteligência artificial generativa:** integração de um modelo de linguagem (LLM) via API para gerar resumos em português simples, fundamentados exclusivamente nos dados recuperados.

## 🛠️ Tecnologias

| Tecnologia | Aplicação no projeto |
|---|---|
| n8n | Automação e orquestração de fluxos |
| APIs do Banco Central | Coleta de dados econômicos |
| PostgreSQL | Armazenamento dos dados |
| SQL | Consultas e manipulação de dados |
| Power BI | Dashboards e visualização |
| LLM via API | Geração de resumos com IA generativa |
| Python | Possível apoio ao processamento de dados |
| Git e GitHub | Versionamento e documentação |

## 🗺️ Roadmap

- [x] Estruturar o projeto e documentar a arquitetura.
- [ ] Integrar as APIs públicas do Banco Central.
- [ ] Desenvolver a coleta automatizada com n8n.
- [ ] Implementar tratamento e validação dos dados.
- [ ] Criar o banco de dados PostgreSQL.
- [ ] Implementar controle de duplicidade dos registros.
- [ ] Integrar um LLM via API para geração de resumos.
- [ ] Desenvolver dashboard no Power BI.
- [ ] Explorar consultas em linguagem natural sobre os indicadores.

## 🔐 Dados e privacidade

O projeto utilizará exclusivamente dados econômicos públicos disponibilizados pelo Banco Central do Brasil.

Não serão utilizados dados pessoais ou informações confidenciais de clientes. Credenciais e chaves de API, quando necessárias, serão mantidas fora do controle de versão.

## ▶️ Como executar

As instruções de instalação, configuração e execução serão documentadas conforme as funcionalidades forem implementadas.

## 📈 Resultados e demonstrações

Serão adicionados registros visuais e demonstrações das etapas concluídas, incluindo:

- Fluxos de automação no n8n.
- Estrutura e consultas do banco PostgreSQL.
- Dashboards desenvolvidos no Power BI.
- Exemplos de resumos produzidos pela IA generativa.

## 👩‍💻 Autora

**Melissandra Sá**

Estudante de Engenharia de Software, com foco em automação de processos, inteligência artificial aplicada a negócios, desenvolvimento de software e análise de dados.

[LinkedIn](https://www.linkedin.com/in/melissandra-s%C3%A1-a32983406) · [GitHub](https://github.com/melissasabr)
