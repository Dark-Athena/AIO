# AIO
AIO 是一个收集项目，它收集一些对于数据库来说，比较特殊的pl/sql功能   
all-in-oracle is a collection，that collecting special  utility packages of pl/sql  from 3rd party，to oracle database    

很多年前，我面临一个比较特殊的情况，部门收到了很多系统功能需求，但是缺少各种开发人员，
唯一比较充足的就是使用sql开发报表的人员和数据库运维人员，我就想着能不能用这些人最熟悉的方式，自己找一些或者做一些工具及组件，让这些人来使用，以满足快速开发的需求。  

而且，如果使用oracle的应用产品，有很多程序代码都是在数据库存储过程中的，如果需要对这些程序进行定制化修改，尤其是事务中的数据交互，必然也是使用plsql语言。  

但大多数orale的基础使用者，并不知道plsql作为一种开发语言，还能实现这么多其他语言比如python/c#/java才能实现的功能。  

一方面，ORACLE数据库会不断升级来支持新的功能，但另一方面，也有不少人在开发ORACLE的第三方组件或者功能。  

比如  
https://oracle-base.com/dba/scripts  
当然这里大部分都是DBA维护脚本，不过也有不少可以用于程序开发的功能

还有      
https://github.com/mortenbra/alexandria-plsql-utils   
alexandria-plsql-utils已经收集了很多很多plsql组件，为避免我更新不及时，对于这个库中已经存在的，我不会在我的github账号里上传，本项目只做索引     
  
我先把alexandria-plsql-utils的readme翻译成中文，方便国人阅读，该文档中，无链接的文件名，请移步至 https://github.com/mortenbra/alexandria-plsql-utils  进行下载

#  alexandria-plsql-utils
Oracle PL/SQL 实用程序库

![](https://github.com/mortenbra/alexandria-plsql-utils/blob/master/alexandria-logo.jpg)

该库是 PL/SQL 的各种实用程序包的集合，以及指向其他地方托管和维护的有用库的链接。


## 使用PL/SQL生成PDF文件


  * https://technology.amis.nl/2012/04/11/generating-a-pdf-document-with-some-plsql-as_pdf_mini-as_pdf3/
  * https://technology.amis.nl/2010/10/20/as_pdf-generating-a-pdf-document-with-some-plsql/
  * http://www.erasme.org/PL-FPDF,1337?lang=en
  * http://ora-00001.blogspot.com/2009/10/free-pdf-package-for-plsql.html
  * http://sourceforge.net/projects/pljrxml2pdf/
  * http://www.plpdf.com/
  * PDF_BUILDER_PKG
  * PDFGEN_PKG


## 使用PL/SQL生成Excel文件

  * https://technology.amis.nl/2011/02/19/create-an-excel-file-with-plsql/
  * http://www.jasonsdevelopercorner.com/?page_id=8
  * https://xml-spreadsheet.samplecode.oracle.com/
  * http://sanjeev-oracle-world.blogspot.com/2007/06/create-excel-workbook-by-plsql-code.html
  * http://matzberger.de/oracle/spreadsheet-en.html
  * http://www.protalk.in/oracle/plsql-tips-package-for-exporting-data-to-excel/
  * XLSX_BUILDER_PKG
  * SYLK_UTIL_PKG

## 使用PL/SQL生成RTF文件

  * http://monkeyonoracle.blogspot.com/2009/07/dynamic-rtf-documents-revisited.html

## 使用 PL/SQL 处理 Office 2007 (OOXML) 文件

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/1/1b/X-office-document.svg/48px-X-office-document.svg.png" align="right" />
<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/0/07/X-office-presentation.svg/48px-X-office-presentation.svg.png" align="right" />
<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/X-office-spreadsheet.svg/48px-X-office-spreadsheet.svg.png" align="right" />
<br>

  * http://ora-00001.blogspot.com/2011/02/working-with-office-2007-ooxml-files.html
  * https://technology.amis.nl/2010/06/09/parsing-a-microsoft-word-docx-and-unzip-zipfiles-with-plsql/
  * http://www.docufy.be/
  * OOXML_UTIL_PKG

## 使用 PL/SQL 压缩和解压缩文件

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/The_Unarchiver_zip.png/64px-The_Unarchiver_zip.png" align="right" /><br>

  * https://technology.amis.nl/2010/03/13/utl_compress-gzip-and-zlib/
  * ZIP_UTIL_PKG

## 使用PL/SQL生成和解析CSV文件

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/3/38/CsvDelimited001.svg/113px-CsvDelimited001.svg.png" align="right" /><br>

  * http://ora-00001.blogspot.com/2010/04/select-from-spreadsheet-or-how-to-parse.html
  * CSV_UTIL_PKG


## 使用 PL/SQL 生成和解析 RSS 提要

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/4/43/Feed-icon.svg/75px-Feed-icon.svg.png" align="right" /><br >

  * http://ora-00001.blogspot.com/2011/02/fun-with-rss-and-plsql-part-one.html
  * http://ora-00001.blogspot.com/2011/02/fun-with-rss-and-plsql-part-two.html
  * RSS_UTIL_PKG


## 使用 PL/SQL 生成 JSON

  * http://ora-00001.blogspot.com/2010/02/ref-cursor-to-json.html
  * JSON_UTIL_PKG


## 使用 PL/SQL 解析 JSON

  * https://github.com/pljson/pljson
  * http://reseau.erasme.org/pl-sql-library-for-JSON?lang=en


## 使用 PL/SQL 传输文件 (FTP)

  * http://www.oracle-base.com/articles/misc/FTPFromPLSQL.php
  * FTP_UTIL_PKG


## 使用 PL/SQL 发送电子邮件 (SMTP)

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/b/b1/Arobaze.svg/75px-Arobaze.svg.png" align="right" /><br>

  * https://oracle-base.com/articles/misc/email-from-oracle-plsql
  * https://docs.oracle.com/en/database/oracle/application-express/19.1/aeapi/APEX_MAIL.html


## 使用 PL/SQL 接收电子邮件 (POP3)

  * POP3_UTIL_PKG


## 使用 PL/SQL（和 Java）接收电子邮件（POP3 和 IMAP）

  * http://plsqlmailclient.sourceforge.net/

##使用 PL/SQL 使用 MS Exchange

  * http://ora-00001.blogspot.com/2012/05/ms-exchange-api-for-plsql.html
  * MS_EWS_UTIL_PKG


## 使用 PL/SQL 与谷歌服务（谷歌地图、谷歌日历、谷歌翻译）集成

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/3/30/Googlelogo.png/200px-Googlelogo.png" align="right" /><br>

  * http://ora-00001.blogspot.com/2009/12/using-google-translate-from-plsql.html
  * GOOGLE_AUTH_PKG
  * GOOGLE_CALENDAR_PKG
  * GOOGLE_MAPS_PKG
  * GOOGLE_TRANSLATE_PKG

## 使用 PL/SQL 与 Amazon Web 服务（简单存储服务 S3）集成

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1d/AmazonWebservices_Logo.svg/200px-AmazonWebservices_Logo.svg.png" align="right" /><br>

  * http://ora-00001.blogspot.com/2011/03/amazon-s3-api-for-plsql.html
  * http://jastraub.blogspot.com/2011/01/building-amazon-s3-client-with.html
  * AMAZON_AWS_AUTH_PKG
  * AMAZON_AWS_S3_PKG

## 与 PayPal 网络服务集成

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/3/39/PayPal_logo.svg/200px-PayPal_logo.svg.png" align="right" /><br>

  * PAYPAL_UTIL_PKG

## 使用 PL/SQL 与 Twitter 集成

<img src="http://upload.wikimedia.org/wikipedia/en/9/9f/Twitter_bird_logo_2012.svg" width="100" align="right" /><br>

  * http://oratweet.com/

## 使用 PL/SQL 调用 SOAP 和 REST Web 服务

  * http://jastraub.blogspot.com/2008/06/flexible-web-service-api.html
  * https://flex-ws-api.samplecode.oracle.com/
  * http://download.oracle.com/docs/cd/E17556_01/doc/apirefs.40/e15519/apex_web_service.htm#BABFFDEH
  * http://ora-00001.blogspot.com/2009/07/calling-soap-web-service-from-plsql-by.html
  * FLEX_WS_API
  * SOAP_CLIENT_UTIL_PKG
  * T_SOAP_ENVELOPE


## 使用 PL/SQL 发布 SOAP Web 服务

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/5/59/SOAP.svg/182px-SOAP.svg.png" align="right" /><br>

  * http://ora-00001.blogspot.com/2011/01/soap-server-in-plsql.html
  * SOAP_SERVER_PKG

## 使用 PL/SQL 发布 REST Web 服务

  * http://ora-00001.blogspot.com/2009/07/creating-rest-web-service-with-plsql.html
  * http://www.oracle-base.com/articles/misc/XMLOverHTTP.php

## 使用 PL/SQL 的正则表达式

<img src="http://upload.wikimedia.org/math/2/a/8/2a8ea57cab60c6ac9279fbf68e37ba0d.png" align="right" /><br>

  * REGEXP_UTIL_PKG


## 字符串、日期和数学实用程序

  * DATE_UTIL_PKG
  * MATH_UTIL_PKG
  * STRING_UTIL_PKG

## 编码和数据类型实用程序

  * ENCODE_UTIL_PKG
  * RAW_UTIL_PKG

##  SQL 实用程序

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/a/aa/SQL_ANATOMY_wiki.svg/275px-SQL_ANATOMY_wiki.svg.png" align="right" /><br>

  * SQL_BUILDER_PKG
  * SQL_UTIL_PKG

##  XML 实用程序

<img src="http://upload.wikimedia.org/wikipedia/commons/thumb/6/68/XML.svg/125px-XML.svg.png" align="right" /><br>

  * http://ora-00001.blogspot.com/2011/02/display-any-xml-as-clickable-tree-using.html
  * XML_BUILDER_PKG
  * XML_DATASET_PKG
  * XML_STYLESHEET_PKG
  * XML_UTIL_PKG

## 文件实用程序

  * FILE_UTIL_PKG

##  HTTP 实用程序

  * HTTP_UTIL_PKG

## 加密和安全实用程序和协议

  * http://ora-00001.blogspot.com/2011/08/ntlm-for-plsql.html
  * CRYPTO_UTIL_PKG
  * NTLM_UTIL_PKG
  * NTLM_HTTP_PKG

## 日志记录和调试实用程序

  * https://github.com/tmuth/Logger---A-PL-SQL-Logging-Utility
  * http://sourceforge.net/projects/log4plsql/
  * http://sourceforge.net/projects/ilo/
  * DEBUG_PKG

## 使用PL/SQL生成测试数据和随机位

  * http://ora-00001.blogspot.com/2011/02/generating-test-data-using-plsql.html
  * RANDOM_UTIL_PKG

##  PL/SQL Web 工具包 (OWA) 实用程序

  * OWA_UTIL_PKG

##  PL/SQL 的 Web 网关

  * http://download.oracle.com/docs/cd/B19306_01/appdev.102/b14258/d_epg.htm
  * http://download.oracle.com/docs/cd/B14099_19/web.1012/b14010/toc.htm
  * http://www.oracle.com/technetwork/developer-tools/apex-listener/overview/index.html
  * http://code.google.com/p/thoth-gateway/
  * http://sourceforge.net/projects/dbprism/
  * http://oss.oracle.com/projects/mod_owa/dist/documentation/modowa.htm

##  PL/SQL 和 Apex 的 jQGrid 集成工具包

  * http://ora-00001.blogspot.com/2010/03/jqgrid-integration-kit-for-plsql-and.html
  * http://code.google.com/p/jqgrid-for-plsql/

##  Application Express API

  * http://download.oracle.com/docs/cd/E17556_01/doc/apirefs.40/e15519/toc.htm
  * APEX_UTIL_PKG

## 其他实用程序和演示

  * http://www.oracle.com/webfolder/technetwork/tutorials/plsql/sfdemo.zip
  * http://www.toadworld.com/platforms/oracle/w/wiki/8243.plsql-obsession

##  PL/SQL 框架

  * http://sourceforge.net/projects/plsqlframestart/
  * http://www.toadworld.com/Freeware/PLVisionFreeware/tabid/687/Default.aspx

## 适用于 Java 的 PL/SQL 包装器

  * http://sourceforge.net/projects/oracle-jutils/

##  PL/SQL 的单元测试框架

  * https://utplsql.github.io/
  * http://code.google.com/p/pluto-test-framework/

## 文档生成器（JavaDoc 风格）

  * http://sourceforge.net/projects/plsqlutils/
  * http://www.thatjeffsmith.com/archive/2012/03/javadoc-for-the-database-a-la-dbdoc-via-sql-developer/

## 脚本、部署和安装实用程序

  * http://code.google.com/p/oracle-ddl2svn/

# 然后，我补充的
- 1.pl4py  在plsql中使用python函数   
https://github.com/Dark-Athena/pl4py   
  
- 2.email(ssl)  在plsql中发送ssl加密邮件   
https://github.com/Dark-Athena/PROCSENDEMAIL_SSL-oracle   

- 3.xlsx  在plsql中生成excel（xlsx文件）
  
- 4.workweixinrobot  在plsql中调用企业微信群机器人api发送消息   
https://github.com/Dark-Athena/workweixinrobot-oracle  
  
- 5.sql_to_dblink  在plsql中对查询sql的字符串，转换成带指定dblink的字符串   
https://github.com/Dark-Athena/sql_to_dblink-oracle  
  
