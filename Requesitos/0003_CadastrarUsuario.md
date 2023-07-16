# Cadastro de um usuário

## Necessidades
- Os usuários(as) são as pessoas que podem solicitar o empréstimo do exemplar de um livro. A única característica necessária para este usuário é saber se ele do tipo Padrão ou Pesquisador.

## Restrições
- O tipo é obrigatório

## Resultado esperado
- Status 200 com o id do usuário gerado retornado no corpo
- Status 400 caso tenha qualquer falha de validação com as falhas no corpo da resposta