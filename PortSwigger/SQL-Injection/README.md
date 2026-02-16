## 🛡️ PortSwigger Academy: SQL Injection (SQLi)
### 📖 Introducción
La Inyección SQL (SQLi) es una vulnerabilidad web que permite a un atacante interferir en las consultas que una aplicación realiza a su base de datos. Ocurre cuando se insertan datos de 
usuario no filtrados directamente en una consulta, permitiendo ver datos privados, modificar registros o incluso obtener control total del servidor.

### Laboratorios
 
 Lab | Writeup | Dificultad |
|-----|---------|------------|
| SQLI vulnerability in WHERE clause allowing retrieval of hidden data | [Ver writeup](PortSwigger/SQL-Injection/01.SQL-injection-vulnerability-in-WHERE-clause-allowing-retrieval-of-hidden-data.md) | 🟢 Easy 
| SQLI vulnerability allowing login bypass | [Ver writeup](PortSwigger/SQL-Injection/02.SQL-injection-vulnerability-allowing-login-bypass.md) | 🟢 Easy | 🌐 Web |
| SQLI UNION attack, determining the number of columns returned by the query | [Ver writeup](PortSwigger/SQL-Injection/03.SQLI-UNION-attack-determining-the-number-of-columns-returned-by-the-query.md) | 🟢 Easy
| SQLI UNION attack finding a column containing text| [Ver writeup](PortSwigger/SQL-Injection/04.SQLI-UNION-attack-finding-a-column-containing-text.md) | 🟢 Easy
| SQLI UNION attack retrieving data from other tables| [Ver writeup](PortSwigger/SQL-Injection/05.SQLI-UNION-attack-retrieving-data-from-other-tables.md) | 🟡 Medium
| SQLI UNION attack, retrieving multiple values in a single column| [Ver writeup](PortSwigger/SQL-Injection/06.SQLI-UNION-attack-retrieving-multiple-values-in-a-single-column.md) | 🟡 Medium 
| SQLI attack, querying the database type and version on Oracle| [Ver writeup](PortSwigger/SQL-Injection/07.SQLI-attack-querying-the-database-type-and-version-on-Oracle.md) | 🟡 Medium 
| SQLi attack, querying the database type and version on MySQL and Microsoft| [Ver writeup](PortSwigger/SQL-Injection/08.SQLI-attack-querying-the-database-type-and-version-on-MySQL-and-Microsoft.md) | 🟡 Medium 
| SQL injection attack, listing the database contents on non-Oracle databases| [Ver writeup](PortSwigger/SQL-Injection/09.SQLI-attack-listing-the-database-contents-on-non-Oracle-databases.md) | 🟡 Medium 
| SQL injection attack, listing the database contents on Oracle| [Ver writeup](PortSwigger/SQL-Injection/10.SQLI-attack-listing-the-database-contents-on-Oracle.md) | 🟡 Medium 
| Blind SQL injection with conditional responses| [Ver writeup](PortSwigger/SQL-Injection/11.Blind-SQL-injection-with-conditional-responses.md) | 🔴 Hard 

### Prevención

Para mitigar estas vulnerabilidades, se recomienda:

- Sentencias Preparadas (Prepared Statements): Utilizar consultas parametrizadas.

- Validación de Entradas: Implementar "allow-lists" para los datos del usuario.

- Principio de Menor Privilegio: Limitar los permisos del usuario de la base de datos que conecta con la aplicación.
