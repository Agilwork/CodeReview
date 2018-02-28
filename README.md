# Code Review Checklist

## Geral

1 - O código funciona? ele desempenha o papel esperado, a lógica está correta, etc?<br />
2 - O código é facilmente entendido?<br />
3 - O código respeita as convençes de codificação definidas para o projeto?<br />
4 - Existe algum código redundante ou duplicado?<br />
5 - O código é o mais modular possivel?<br />
6 - Algum código de log ou debug pode ser removido<br />
7 - O código comentado foi removido?<br />

## Segurança
1 - Todos os inputs foram validados (tipo correto, tamanho, formato, valores válidos)<br />
2 - Os valores inválidos foram tratados?<br />

## Performance
1 - Informações que podem ser armazenada em cache estão sendo cacheadas?<br />
2 - Processamento redundantes ou lentos foram otimizados?<br />
3 - Foi evitado o uso de construções com IF/ELSE para diminuir a complexidade da execução?<br />

## Testes
1 - Se a tarefa envolver apensa um módulo,<br /> 
2 - Executar os testes daquele módulo, se envolver mais de uma, rodar todos os testes do sistema.<br />
3 - Os testes unitários deve rodar com todos os erros do php habilitado<br />
4 - Os testes devem cobrir tanto os testes de sucesso com os de erro<br />

