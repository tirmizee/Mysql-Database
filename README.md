# Mysql-Document

### Check max_connections Value (ตรวจสอบค่า การเชื่อมต่อสูงสุด)

    SHOW VARIABLES LIKE "max_connections";
    
### Update max_connections Value (แก้ไข "max_connections" ซึ่งค่าจะถูก Reset ใหม่ตอน Restart Service) 

    SET GLOBAL max_connections = 200;
    
### Setting this max_connections value permanently (แก้ไข "max_connections" อย่างถาวร) 

"/etc/mysql/my.cnf" or "/etc/my.cnf"

    max_connections = 250
    
###  Check Index Information (ตรวจสอบ Index ของ Table)

    SHOW INDEX FROM schema_mysql.transaction;
