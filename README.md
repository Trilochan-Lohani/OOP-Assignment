
Download MySql
1. Go to mysql.com
2. Go to Download tab
3. Download MYSQL Community(GPL) downloads.
4. Click MySQL installer for windows.

Install MySQL
1. Click on installetion file
2. Choose Set Up type Custom.
3. Extend MySQL Servers.
	-MySQL Server
		-MySQL Server 8.0
			-MySQL Server 8.0.26- x64
				Drag to Product to be instelled list.
4. Expand Applications
	-MySQL WorkBench
		-MySQL WorkBench 8.0
			-ADD Latest version.(8.0.34)
	-Select MySQL Shell
		-Select MySQL_Shell(8.0.35 x64)
5. On Account roles and details;
	User : root
	Password : 12345

Configuring MySQL In project.
Now in pycharm project,
-Go to terminal
	-type pipinsatll pymysql
Now go to Register page and import it in the top.


Now go to MySql Command Line Client
	type : show databases; //Shows databases in server.
		use databasename;
		show tables; //shows table list in databases.
		desc tablename; //describe the table columa/show table column.
		select *  from tablename; //shows data in the table.
		Drop Databasename //to drop(delete) database.
	
