# Lab 06: Introdução ao SQL
## Descrição:
- Exercícios básicos de SQL utilizando SQLite no R/Quarto.
- Comandos: SELECT, JOIN, COUNT, GROUP BY, etc.

## Estrutura de Arquivos
LAB06/
- README.md (Documentação do laboratório)
- Lab06.qmd (Código fonte completo - Quarto)
- Resultados.html (Relatório em HTML)
- Resultados.pdf (Relatório em PDF)
- disco.db (Banco de dados SQLite)

## Banco de Dados:
- **disco.db**: Banco de Dados de uma loja de músicas
- Tabelas: albums, artists, customers, employees, genres, invoice_items, invoices, etc.

## Conteúdo:
- Conexão com banco de dados
- Consultas Básicas
- Agrupamentos
- Junções de tabelas
- Filtros e Ordenação

## Como Executar

### Pré-requisitos
- R e RStudio instalados
- Pacotes: `RSQLite`, `Quarto`

### Instruções
1. Clone este repositório
2. Abra o arquivo `Lab06.qmd` no RStudio
3. Certifique-se que o arquivo `disco.db` está no mesmo diretório
4. Execute os chunks de código individualmente ou clique em "Render" para compilar o documento completo
5. Para visualização rápida dos resultados, abra o arquivo `Resultados.html` em qualquer navegador web
