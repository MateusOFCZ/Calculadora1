[![Github Actions Status for Vinicius-CS/Calculadora1](https://github.com/Vinicius-CS/Calculadora1/actions/workflows/maven.yml/badge.svg?branch=master)](https://github.com/Vinicius-CS/Calculadora1/actions/workflows/maven.yml) [![Quality Gate Status](sonarcloud.io/api/project_badges/measure?project=Vinicius-CS_Calculadora1&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=Vinicius-CS_Calculadora1) [![Coverage]([https://sonarcloud.io/api/project_badges/measure?project=calculadora&metric=coverage](https://sonarcloud.io/api/project_badges/measure?project=Vinicius-CS_Calculadora1&metric=coverage))](https://sonarcloud.io/component_measures?id=Vinicius-CS_Calculadora1&metric=coverage)

# Calculadora com CI.
Utiliza 3 ambientes:
- dev - Desenvolvimento
- hmg - Homologação
- prd - Produção

Pipeline
- dev - Compilação
- hmg - Compilação, Testes, Análise Código, Cobertura Código
- prd - Empacotamento
<br>
- Utiliza o Apache Maven para a automatização da construção.<br>
- A pasta test contêm os testes unitários do projeto utilizando JUnit 4.<br>
- A cobertura do código é realizada através do JaCoCo.<br>
