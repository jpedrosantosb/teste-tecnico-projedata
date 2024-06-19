# TESTE PRÁTICO PROGRAMAÇÃO - PROJEDATA

## Descrição
Este projeto é uma aplicação Java (versão 17) que atende aos requisitos abaixo:

1. Classe `Pessoa` com os atributos:
   - `nome` (String)
   - `dataNascimento` (LocalDate)

2. Classe `Funcionario` que estende a classe `Pessoa`, com os atributos:
   - `salario` (BigDecimal)
   - `funcao` (String)

3. Classe `Principal` para executar as seguintes ações:
   3.1. Inserir todos os funcionários, na mesma ordem e informações da tabela acima.
   3.2. Remover o funcionário “João” da lista.
   3.3. Imprimir todos os funcionários com todas suas informações, com os seguintes formatos:
       - Data: dd/MM/yyyy
       - Valor numérico: separador de milhar como ponto e decimal como vírgula.
   3.4. Atualizar a lista de funcionários com um aumento de 10% no salário.
   3.5. Agrupar os funcionários por função em um `Map`, sendo a chave a “função” e o valor a “lista de funcionários”.
   3.6. Imprimir os funcionários agrupados por função.
   3.7. (O item 3.7 não foi especificado)
   3.8. Imprimir os funcionários que fazem aniversário nos meses 10 e 12.
   3.9. Imprimir o funcionário com a maior idade, exibindo os atributos: nome e idade.
   3.10. Imprimir a lista de funcionários por ordem alfabética.
   3.11. Imprimir o total dos salários dos funcionários.
   3.12. Imprimir quantos salários mínimos ganha cada funcionário, considerando que o salário mínimo é R$ 1212,00.

## Tecnologias Utilizadas
- Java 17
- Biblioteca para manipulação de datas: `java.time.LocalDate`
- Biblioteca para manipulação de valores monetários: `java.math.BigDecimal`

## Estrutura do Projeto
- `src/main/java`
  - `com.projedata`
    - `Pessoa.java`
    - `Funcionario.java`
    - `Principal.java`

## Como Executar o Projeto
1. Certifique-se de ter o Java 17 instalado.
2. Clone este repositório:
   ```bash
   git clone https://github.com/jpedrosantosb/teste-tecnico-projedata.git


