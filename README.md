# NSYSU CDPA dorm-net repair system


Using python3, flask, and sqlalchemy


## Update Log:

Feb. 13rd, 2019, 13:36
```
	1. 前端登入頁面 帳號格式限定修復
	2. 後端admin介面 管理員修復日期的顯示問題修復
	3. 後端admin database page, 取消創建功能，僅能使用一般user介面新增資料
```


Feb. 13rd, 2019, 13:47
```
	1. 將登入失敗後的頁面之 redirect 從 login.html 改成 index.html 
	2. "登入失敗後，按註冊沒反應" 因前項的更改，已無此問題
```


Feb. 13rd, 2019, 19:10
```
	1. 更新IP conflict page image and add English version
```


Feb. 14th, 2019, 14:02
```
	1. trouble_shooting 的前往報修 連結修復
	2. add unauthorized handler
``` 


Feb. 15th, 2019, 14:08
```
	1. 更新en_trouble_shooting 連結
	2. 手機版文字會被切掉問題修復
```



Feb. 16th, 2019, 00:26
```
	1. 修復 duplicate repair form 判定問題
```

## Requirement:



	mysql

	python3

	python3-pakages:

		1. flask

		2. flask-login
	
		3. flask-admin
	
		4. flask-wtf
		
		5. flask-sqlalchemy

		6. pymysql

		7. sqlalchemy

	



## Usage:


First, install mysql, python3 and the above python3 packages.





Second, run the install.sh script, it will need your mysql root privilege.


	$ cd CDPA_Repair_System
	$ ./install.sh




Third, system start. You can sepcify your desire port, otherwise, the program runs on port 80

	
	$ cd app/
	$ python3 main.py --port=YOUR_PORT



