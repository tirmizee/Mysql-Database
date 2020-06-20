# Mysql-Document

### Check max_connections Value (ตรวจสอบค่า การเชื่อมต่อสูงสุด)

    SHOW VARIABLES LIKE "max_connections";
    
### Update max_connections Value 

    SET GLOBAL max_connections = 200;
    
### Setting this max_connections value permanently

/etc/mysql/my.cnf or /etc/my.cnf

    max_connections = 250
    
###  Check Index Information

    SHOW INDEX FROM schema_mysql.transaction;
