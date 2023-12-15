# 20232BSET03P2
Inteli - Engenharia de Software | Avaliação 2023-2B P2

Para previnir SQL injection, eu utilizei queries como parâmetros, invés de colocar os inputs diretamente dentro da notação SQL. Além disso, os inputs em string passam por uma remoção de (") e (') para garantir.

A logica de votação foi mudada para tentar validar se aquele registro existe antes de atualiza-lo e retorna erro caso não aconteça
