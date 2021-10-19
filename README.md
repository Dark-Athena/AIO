# AIO
AIO 是一个收集项目，它收集一些对于数据库来说，比较特殊的pl/sql功能   
all-in-oracle is a collection，that collecting special pl/sql function from 3rd party，to oracle database    

很多年前，我面临一个比较特殊的情况，部门收到了很多系统功能需求，但是缺少各种开发人员，
唯一比较充足的就是使用sql开发报表的人员和数据库运维人员，我就想着能不能用这些人最熟悉的方式，自己找一些或者做一些工具及组件，让这些人来使用，以满足快速开发的需求。  

而且，如果使用oracle的应用产品，有很多程序代码都是在数据库存储过程中的，如果需要对这些程序进行定制化修改，尤其是事务中的数据交互，必然也是使用plsql语言。  

但大多数orale的基础使用者，并不知道plsql作为一种开发语言，还能实现这么多其他语言比如python/c#/java才能实现的功能。  

一方面，ORACLE数据库会不断升级来支持新的功能，但另一方面，也有不少人在开发ORACLE的第三方组件  

首先，看这里   
https://github.com/mortenbra/alexandria-plsql-utils


- 1.pljson
https://github.com/pljson/pljson

- 2.pl4py
https://github.com/Dark-Athena/pl4py

- 3.as_zip
https://technology.amis.nl/it/parsing-a-microsoft-word-docx-and-unzip-zipfiles-with-plsql/

- 4.ftp

- 5.email(ssl)

- 6.xlsx

- 7.workweixinrobot
https://github.com/Dark-Athena/workweixinrobot-oracle

- 8.sql_to_dblink
https://github.com/Dark-Athena/sql_to_dblink-oracle

- 9.gzip and zlib
https://technology.amis.nl/it/utl_compress-gzip-and-zlib/
