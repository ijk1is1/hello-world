myeclipse
	导入 exam
数据库文件 
	exam.sql

common下  DBUtilHelper.java 文件
	修改 数据库的 账户和密码。


conn = DriverManager.getConnection(
					"jdbc:mysql://localhost:3306/exam", "root", "");