## JAVA连接数据库 ##
###sql server

	driver = "net.sourceforge.jtds.jdbc.Driver";
	url="jdbc:jtds:sqlserver://192.168.1.45:1433;DatabaseName=691Data";


###mysql

	driver = "com.mysql.jdbc.Driver";
	url = "jdbc:mysql://localhost:3306/691Data?useUnicode=true&characterEncoding=utf8";


###oracle

	driver = "oracle.jdbc.driver.OracleDriver";
	url="jdbc:oracle:thin:@192.168.2.66:1521:691Data"


###sqlite

	driver = "org.sqlite.JDBC"
	url="jdbc:sqlite:path(路径)/(数据库文件名).db"