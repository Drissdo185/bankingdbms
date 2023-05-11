# bankingdbms
Small project build banking management system in DBMS class
String userdb = "sa";
    String passdb = "123";
    String url = "jdbc:sqlserver://localhost:1433;databaseName=bankingpdm;encrypt=true;trustServerCertificate=true";
    Connection con = DriverManager.getConnection(url, userdb, passdb);
