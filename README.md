## Tratamento de Exceções em Java

1. Very bad solution
- Logica de validação no programa principal (Não delegada a reserva).

2. Bad solution
- Método retornando string
- A semântica da operação é prejudicada
- Nao há auxilio do compilador ( o programador deve verificar se houve erro)
- A lógica fica estruturada em condicionais aninhadas

3. Not so bad solution
- Tratamento de exceções em classe especial para isso
- tratamento nos construtores
- há auxilio do compilador

**Resumo**:
- Clausula throws: propaga a exceção ao invés de trata-la
- Clausula throw: lança exceção/ "corta" o método
- Exception: Compilador obriga a tratar ou propagar
- RuntimeException: compilador não obriga
- O tratamento de exceções permite que erros sejam tratados de forma consistente e flexível, usando boas práticas.

**Vantagens:**
- Lógica delegada
- Construtores podem ter tratamento de exceções
- Possibilidade de auxilio do compilador (Exception)
- Código mais simples
- É possível capturar inclusive outras exceções de sistema.

Sobre:
*Este projeto foi extraído da aula de tratamento de exceções,
do curso de Java do professor Nélio Alves.*
