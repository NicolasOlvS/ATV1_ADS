1 - A principal desvantagem é que o código se torna difícil de ler, manter e escalar. 
Com todas as responsabilidades juntas, fica mais complicado localizar problemas, 
aplicar mudanças e reutilizar partes do código, além de aumentar o risco de erros.

2 - A separação em camadas organiza a aplicação em módulos (apresentação, lógica de negócios, persistência), 
tornando-a mais fácil de manter e modificar. Cada camada tem uma responsabilidade específica, o que facilita a escalabilidade, 
já que as mudanças podem ser feitas em uma camada sem afetar as demais.

3 - Ela permite maior flexibilidade, pois cada transformação (filtro) é independente e pode ser alterada ou reorganizada sem impacto nos outros filtros. 
Além disso, facilita a reutilização e a modificação das transformações, adaptando-se melhor a novas demandas.