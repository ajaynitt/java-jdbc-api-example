Reference : https://www.javatpoint.com/example-to-connect-to-the-mysql-database

(1) Create database and table in Mysql using following command

    create database sonoo;
    use sonoo;
    create table emp(id int(10),name varchar(40),age int(3));

(2)Run the code


Issues and debugging:

(1) java.lang.ClassNotFoundException: com.mysql.jdbc.Driver
Solution:
    Two ways to load the jar file:

    Paste the mysqlconnector.jar file in jre/lib/ext folder
    Set classpath

https://stackoverflow.com/questions/30651830/use-jdbc-mysql-connector-in-intellij-idea

Link : https://www.java67.com/2015/07/javalangclassnotfoundexception-com.mysql.jdbc.Driver-solution.html

Intellij Idea : File -> Project Structure -> Libraries

(2)