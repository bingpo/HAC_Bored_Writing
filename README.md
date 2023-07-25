# HAC_Bored_Writing

各种未授权、RCE、文件上传、sql注入、信息泄露漏洞批量扫描poc、exp


## 文件读取

任意文件读取，可读取服务器文件内容

### 漏洞列表

#### 会捷通云视讯

- [会捷通云视讯 /fileDownload文件读取](./FileRead/会捷通云视讯任意文件读取)

#### FLIR-AX8

- [FLIR-AX8 /download.php文件读取](./FileRead/FLIR-AX8_fileread)

#### Jellyfin

- [Jellyfin /Audio/1/hls/文件读取](./FileRead/CVE-2021-21402Jellyfin任意文件读)

#### ShopXO

- [ShopXO CNVD-2021-15822文件读取](./FileRead/CNVD-2021-15822)

#### Grafana

- [Grafana CVE-2021-43798文件读取](./FileRead/Grafana_fileread)

#### 金山v8

- [金山 V8 终端安全系统文件下载](./FileRead/jinshanv8_fileread)

## 文件上传

可上传webshell，获取服务器权限

### 漏洞列表

#### 致远oa

- [seeyon /autoinstall.do.css/..;/ajax.do文件上传](./Fileupload/seeyon-oa-exp)

#### 用友时空KSOA

- [用友时空KSOA /com.sksoft.bill.ImageUpload文件上传](./Fileupload/KSOA_upload)

#### 泛微

- [泛微E-Office CNVD-2021-49104文件上传](./Fileupload/CNVD-2021-49104)

## sql注入

### 漏洞列表

#### CmsEasy

- [CmsEasy sql注入](./Sqlinject/CmsEasy_sql)

#### Jeecg-Boot

- [jmreport/qurestSql sql注入](./Sqlinject/CVE-2023-1454)

#### Doccms

- [Doccms keyword sql注入](./Sqlinject/Doccms-sql-injection)

#### 红帆OA

- [红帆OA iOffice.net udfmr.asmx sql注入](./Sqlinject/iOffice_sqlscan)

#### 泛微

- [泛微e-cology QVD-2023-5012 sql注入](./Sqlinject/QVD-2023-5012)

#### 源天OA

- [源天OA GetDataAction sql注入](./Sqlinject/yuantian_sql)

## RCE命令执行

### 漏洞列表

#### 学习管理系统Chamilo

- [Chamilo_CVE-2023-34960_RCE](./RCE/Chamilo__CVE-2023-34960_RCE)

#### 蓝海卓越计费管理系统

- [蓝海卓越计费管理系统 RCE](./RCE/lanhai_rce)


## 未授权访问

### 漏洞列表

#### H5S CONSOLE

- [零视技术(上海)有限公司H5S CONSOLE CNVD-2020-67113未授权访问](./unauthorized/CNVD-2020-67113)

#### druid

- [druid CVE-2021-34045未授权](./unauthorized/CVE-2021-34045)

## 免责声明

由于传播、利用此文所提供的信息而造成的任何直接或者间接的后果及损失，均由使用者本人负责，作者不为此承担任何责任。



