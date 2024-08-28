| **Categoria**               | **Função**                                           | **Descrição**                                                                 |
|-----------------------------|-----------------------------------------------------|-------------------------------------------------------------------------------|
| **Funções de Aritmética**   | `ABS(x)`                                            | Retorna o valor absoluto de x.                                                |
|                             | `CEIL(x)` ou `CEILING(x)`                           | Retorna o menor inteiro maior ou igual a x.                                   |
|                             | `FLOOR(x)`                                          | Retorna o maior inteiro menor ou igual a x.                                   |
|                             | `ROUND(x, d)`                                       | Arredonda x para d casas decimais.                                            |
|                             | `SQRT(x)`                                           | Retorna a raiz quadrada de x.                                                 |
|                             | `POWER(x, y)` ou `POW(x, y)`                        | Retorna x elevado à potência y.                                               |
|                             | `MOD(x, y)`                                         | Retorna o resto da divisão de x por y.                                        |
| **Funções de Cadeia de Caracteres** | `CONCAT(str1, str2, ...)`                          | Concatena duas ou mais strings.                                               |
|                             | `LENGTH(str)`                                       | Retorna o comprimento da string em bytes.                                     |
|                             | `SUBSTRING(str, pos, len)`                          | Retorna uma substring começando na posição `pos` e com `len` caracteres.      |
|                             | `UPPER(str)` ou `UCASE(str)`                        | Converte todos os caracteres da string para maiúsculas.                       |
|                             | `LOWER(str)` ou `LCASE(str)`                        | Converte todos os caracteres da string para minúsculas.                       |
|                             | `TRIM(str)`                                         | Remove espaços em branco no início e no fim da string.                        |
|                             | `REPLACE(str, from_str, to_str)`                    | Substitui todas as ocorrências de `from_str` por `to_str` em `str`.           |
| **Funções de Data e Hora**  | `NOW()`                                             | Retorna a data e hora atuais.                                                 |
|                             | `CURDATE()`                                         | Retorna a data atual.                                                         |
|                             | `CURTIME()`                                         | Retorna a hora atual.                                                         |
|                             | `DATE_ADD(date, INTERVAL expr unit)`                | Adiciona um intervalo de tempo à data.                                        |
|                             | `DATE_SUB(date, INTERVAL expr unit)`                | Subtrai um intervalo de tempo da data.                                        |
|                             | `DATEDIFF(date1, date2)`                            | Retorna a diferença em dias entre duas datas.                                 |
|                             | `YEAR(date)`                                        | Retorna o ano da data.                                                        |
|                             | `MONTH(date)`                                       | Retorna o mês da data.                                                        |
|                             | `DAY(date)`                                         | Retorna o dia do mês da data.                                                 |
|                             | `HOUR(time)`                                        | Retorna a hora do tempo.                                                      |
|                             | `MINUTE(time)`                                      | Retorna os minutos do tempo.                                                  |
|                             | `SECOND(time)`                                      | Retorna os segundos do tempo.                                                 |
|                             | `DATE_FORMAT(date, format)`                         | Formata a data de acordo com o formato especificado.                          |
| **Funções de Agregação**    | `COUNT(expr)`                                       | Retorna o número de linhas que correspondem ao critério.                      |
|                             | `SUM(expr)`                                         | Retorna a soma de todos os valores de uma coluna.                             |
|                             | `AVG(expr)`                                         | Retorna a média dos valores de uma coluna.                                    |
|                             | `MIN(expr)`                                         | Retorna o menor valor de uma coluna.                                          |
|                             | `MAX(expr)`                                         | Retorna o maior valor de uma coluna.                                          |
| **Funções de Controle de Fluxo** | `IF(expr1, expr2, expr3)`                             | Retorna `expr2` se `expr1` for verdadeiro, caso contrário retorna `expr3`.     |
|                             | `CASE ... WHEN ... THEN ... ELSE ... END`           | Executa instruções condicionais.                                              |
| **Funções de Informações**  | `DATABASE()`                                        | Retorna o nome do banco de dados atual.                                       |
|                             | `USER()`                                            | Retorna o nome do usuário MySQL atual.                                        |
|                             | `VERSION()`                                         | Retorna a versão do servidor MySQL.                                           |
| **Funções de Conversão**    | `CAST(expr AS type)`                                | Converte uma expressão em outro tipo de dados.                                |
|                             | `CONVERT(expr, type)`                               | Converte uma expressão em outro tipo de dados.                                |
|                             | `BINARY(expr)`                                      | Converte uma string para uma string binária.                                  |
|                             | `CONVERT_TZ(datetime, from_tz, to_tz)`              | Converte um valor datetime de um fuso horário para outro.                     |
| **Funções de Criptografia** | `MD5(str)`                                          | Calcula o hash MD5 de uma string.                                             |
|                             | `SHA1(str)`                                         | Calcula o hash SHA-1 de uma string.                                           |
|                             | `PASSWORD(str)`                                     | Calcula uma senha criptografada com base em uma string.                       |
| **Funções Matemáticas**     | `EXP(x)`                                            | Retorna `e` elevado à potência de x.                                          |
|                             | `LOG(x)`                                            | Retorna o logaritmo natural de x.                                             |
|                             | `LOG10(x)`                                          | Retorna o logaritmo de base 10 de x.                                          |
|                             | `PI()`                                              | Retorna o valor de π (pi).                                                    |
|                             | `RAND()`                                           | Retorna um número aleatório entre 0 e 1.                                      |
| **Funções de Bitwise**      | `BIT_COUNT(x)`                                      | Retorna o número de bits ativos (1) em x.                                     |
|                             | `BIT_AND(expr)`                                     | Realiza uma operação bitwise AND entre todos os bits em expr.                 |
|                             | `BIT_OR(expr)`                                      | Realiza uma operação bitwise OR entre todos os bits em expr.                  |
|                             | `BIT_XOR(expr)`                                     | Realiza uma operação bitwise XOR entre todos os bits em expr.                 |