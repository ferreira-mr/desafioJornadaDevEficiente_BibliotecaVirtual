# Cadastro de um livro

## Necessidades
- Um livro precisa ser cadastrado com título, preço e respectivo ISBN.

## Restrições
- Título é obrigatório
- Preço é obrigatório
- ISBN é obrigatório
- ISBN não pode ser duplicado

## Resultado esperado
- Status 200 com o id do livro gerado retornado no corpo
- Status 400 caso tenha qualquer falha de validação com as falhas no corpo da resposta