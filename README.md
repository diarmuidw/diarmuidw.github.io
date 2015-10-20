# diarmuidw.github.io
My Github pages site
MYSQL
scp -P 3532 incoming100.sql rapidadmin@192.168.100.200:/tmp

“mysqldump -p – –user=username dbname tableName > tableName.sql”
mysql -u username -p -D dbname < tableName.sql

SELECT table_name, SUM(TABLE_ROWS)       FROM INFORMATION_SCHEMA.TABLES       WHERE TABLE_SCHEMA = 'asterisk' group by table_name;


history | grep scp

Asterisk

/usr/sbin/asterisk -rvvvgc

show master status;

slave stop;
change master ..
slave start;

show slave status;

