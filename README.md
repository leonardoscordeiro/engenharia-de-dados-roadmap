# Engenharia de Dados — Roadmap Python

Repositório de estudos de Engenharia de Dados com foco em Python. Organizado em módulos progressivos, cada fase constrói sobre a anterior.

---

## Roadmap

### Fase 1 — Fundamentos Python `[100%]`
- Funções, loops (`for`, `while`), condicionais
- Listas, dicionários, tuplas e estruturas aninhadas
- Padrões de acumulação, filtragem e agrupamento
- Tratamento de erros (`try/except`)
- List/dict comprehensions
- Fatiamento de strings e métodos úteis

### Fase 2 — Manipulação de Dados
- Ler e escrever arquivos (CSV, JSON, TXT)
- Trabalhar com datas (`datetime`)
- Expressões regulares (regex)
- Funções avançadas: `*args`, `**kwargs`, `lambda`
- Módulos e imports

### Fase 3 — Bibliotecas Essenciais
- **Pandas** — DataFrames e manipulação de tabelas
- **SQL** — SELECT, JOIN, GROUP BY
- **SQLAlchemy** — conexão Python + banco de dados
- **Requests** — consumir APIs REST
- **JSON** — parsear e construir payloads

### Fase 4 — Ferramentas de Pipeline
- **Airflow / Prefect** — orquestração
- **PySpark** — processamento em escala
- **Docker** — containerização
- **Git** — versionamento
- **Cloud** — AWS (S3, Glue, Redshift) ou GCP (BigQuery, Dataflow)

### Fase 5 — Projeto Real (ETL completo)
1. **Extract** — extrair dados de API ou banco
2. **Transform** — limpar e transformar com Pandas
3. **Load** — carregar num data warehouse

---

## Estrutura do Repositório

```
aulas/
├── modulo I/
│   ├── aula1.ipynb                    # Variáveis, Input/Output, Operações Básicas
│   ├── aula2.ipynb                    # TypeError, Type Check, Tratamento de Erros
│   ├── aula3.ipynb                    # Condicionais, FOR, WHILE, Estruturas de Dados
│   ├── aula4.ipynb                    # Type Hint, Listas, Dicionários, Funções
│   ├── aula5.ipynb                    # Projeto: 1 Bilhão de Linhas
│   ├── funcoes_metodos_python_1.ipynb # Material de Apoio — Iniciante
│   ├── funcoes_metodos_python_2.ipynb # Material de Apoio — Intermediário
│   ├── funcoes_metodos_python_3.ipynb # Material de Apoio — Avançado
│   └── funcoes_metodos_python_4.ipynb # Material de Apoio — Especialista
│
└── modulo II/
    ├── aula6.ipynb                    # Funções e Estrutura de Dados
    ├── aula7.ipynb                    # Funções e Estrutura de Dados
    ├── exercio_funcoes.ipynb          # Exercícios Práticos de Funções
    ├── revisoes.ipynb                 # Revisão — Relatório de Transações Bancárias
    └── vendas.csv                     # Dataset para exercícios
```

---

## Sistema de Revisão Espaçada

### Como funciona

Cada sessão (~1h) tem duas partes:
- **Aquecimento (10 min)** — 1 exercício de revisão, conceito já visto mas cenário novo voltado pra DE
- **Avanço (50 min)** — conteúdo novo da fase atual

A revisão segue intervalos espaçados: **Dia 1 → Dia 3 → Dia 7 → Dia 14 → Fixado**.
Conceitos de prioridade alta aparecem com mais frequência.

### Prioridade dos Conceitos (foco em Engenharia de Dados)

| Prioridade | Conceito | Motivo (uso em DE) |
|------------|----------|-------------------|
| :red_circle: ALTA | Agrupar/contar em dicionários | GROUP BY em todo pipeline |
| :red_circle: ALTA | Limpar dados (None, validação) | Qualidade de dados é tudo |
| :red_circle: ALTA | Cruzar dados (JOIN) | Merge entre tabelas/fontes |
| :red_circle: ALTA | Pipeline ETL (extrair → transformar → carregar) | Core da profissão |
| :red_circle: ALTA | Acumular e agregar valores | SUM, AVG, COUNT em tudo |
| :yellow_circle: MÉDIA | List/dict comprehension | Transformações rápidas |
| :yellow_circle: MÉDIA | Filtrar listas por condição | WHERE em queries |
| :yellow_circle: MÉDIA | try/except | Pipelines robustos |
| :yellow_circle: MÉDIA | Funções chamando funções | Modularização de pipelines |
| :green_circle: BAIXA | if/else, for, while, return | Já internalizado |
| :green_circle: BAIXA | Fatiamento, string methods | Já internalizado |

---

## Como usar

1. Clone o repositório
2. Abra os notebooks no VS Code ou Jupyter
3. Siga a ordem: Módulo I (aulas 1-5) → Módulo II
4. Use os materiais de apoio como referência rápida

---

## Tecnologias

- Python 3.12+
- Jupyter Notebooks
