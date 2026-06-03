## 🛡️ PortSwigger Academy: SQL Injection (SQLi)
### 📖 Introducción
La Inyección SQL (SQLi) es una vulnerabilidad web que permite a un atacante interferir en las consultas que una aplicación realiza a su base de datos. Ocurre cuando se insertan datos de 
usuario no filtrados directamente en una consulta, permitiendo ver datos privados, modificar registros o incluso obtener control total del servidor.

### Laboratorios
 
 Lab | Writeup | 
|-----|---------|
| SQLI vulnerability in WHERE clause allowing retrieval of hidden data | [Ver writeup](01.SQL-injection-vulnerability-in-WHERE-clause-allowing-retrieval-of-hidden-data.md)
| SQLI vulnerability allowing login bypass | [Ver writeup](02.SQL-injection-vulnerability-allowing-login-bypass.md)
| SQLI UNION attack, determining the number of columns returned by the query | [Ver writeup](03.SQLI-UNION-attack-determining-the-number-of-columns-returned-by-the-query.md)
| SQLI UNION attack finding a column containing text| [Ver writeup](04.SQLI-UNION-attack-finding-a-column-containing-text.md)
| SQLI UNION attack retrieving data from other tables| [Ver writeup](05.SQLI-UNION-attack-retrieving-data-from-other-tables.md)
| SQLI UNION attack, retrieving multiple values in a single column| [Ver writeup](06.SQLI-UNION-attack-retrieving-multiple-values-in-a-single-column.md)
| SQLI attack, querying the database type and version on Oracle| [Ver writeup](07.SQLI-attack-querying-the-database-type-and-version-on-Oracle.md)
| SQLi attack, querying the database type and version on MySQL and Microsoft| [Ver writeup](08.SQLI-attack-querying-the-database-type-and-version-on-MySQL-and-Microsoft.md)
| SQL injection attack, listing the database contents on non-Oracle databases| [Ver writeup](09.SQLI-attack-listing-the-database-contents-on-non-Oracle-databases.md)
| SQL injection attack, listing the database contents on Oracle| [Ver writeup](10.SQLI-attack-listing-the-database-contents-on-Oracle.md)
| Blind SQL injection with conditional responses| [Ver writeup](11.Blind-SQL-injection-with-conditional-responses.md)
| Blind SQL injection with conditional errors | [Ver Writeup](12.Blind-SQL-injection-with-conditional-errors.md)
| Blind SQL injection with time delays | [Ver Writeup](13.Blind-SQL-Injection-with-time-delays.md)
| Blind SQL injection with time delays and information retrieval | [Ver Writeup](14.Blind-SQL-injection-with-time-delays-and-information-retrieval.md)

### Prevención

Para mitigar estas vulnerabilidades, se recomienda:

- Sentencias Preparadas (Prepared Statements): Utilizar consultas parametrizadas.

- Validación de Entradas: Implementar "allow-lists" para los datos del usuario.

- Principio de Menor Privilegio: Limitar los permisos del usuario de la base de datos que conecta con la aplicación.
