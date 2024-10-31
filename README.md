# Teste para Programador PHP Júnior

## Regras
  - Pode consultar o site php.net;
  - Não pode perguntar para a IA.

## Objetivo

Desenvolver um script PHP que:

1. Leia um arquivo de texto 'palavras.txt' que contém palavras separadas por vírgulas.
2. Converta a primeira letra de cada parala para maiusculo, inclusive para palavras compostas separadas por underscore.
3. Conte a ocorrência de cada palavra e exiba os resultados em uma tabela.

> **Observação:** Utilize Bootstrap para estilizar a tabela, se preferir.

## Especificação do Projeto

1. **Leitura do arquivo**: Leia o conteúdo de um arquivo `palavras.txt`, que contém palavras separadas por vírgulas.
2. **Tratamento das palavras**:
   - Armazene as palavras em um array.
   - Para cada palavra, deixe a primeira letra de cada parte em maiúsculo. 
   - Exemplo:
     - `teste_padrao` deve se transformar em `Teste Padrão`.
3. **Contagem de ocorrências**: Conte quantas vezes cada palavra aparece no texto.
4. **Exibição**: Exiba o resultado em uma tabela com duas colunas: "Palavra" e "Quantidade".


### Exemplo de Lista de Palavras


| Palavra         | Quantidade |
|-----------------|------------|
| Teste           | 3          |
| Exemplo         | 3          |
| Teste Padrão    | 2          |
| Tarefa Única    | 1          |


