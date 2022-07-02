# Debug-error
Validação de erros por tipo
- Função: recebe um array e um número
Validações:
Se os parâmetros não forem enviados, erro do tipo ReferenceError;
Array não for do tipo 'object',  um erro do tipo TypeError;
Número não for do tipo 'number', um erro do tipo TypeError;
Tamanho do array for diferente do número enviado como parâmetro,  um erro do tipo RangeError;
Declaração try...catch;
Filtro nas chamadas de catch por cada tipo de erro utilizando o operador instanceof
