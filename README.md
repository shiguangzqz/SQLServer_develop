# SQLServer_develop
一个安装SQL Server和用c#进行开发的教程
## 开发前的准备工作
* [下载和安装](https://www.microsoft.com/en-us/sql-server/developer-get-started/csharp/win/)   
这里的对SQL Server的开发用到的是SQL Server 2017 Developer版本(默认是安装了visual studio 2017)    
建议下载安装介质，防止第一次安装中出现各种问题
* 安装SQL Server Management Studio (SSMS)
[安装链接](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)
* 安装完成之后需要先启动SQL Server服务，可以在服务中查看是否有运行（因为我为了节约资源，所有的服务都选了手动启动），如若没有运行可以在以下目录找到sqlser程序，并运行   
路径：C:\Program Files\Microsoft SQL Server\MSSQL14.MSSQLSERVER\MSSQL\Binn   
* 关于防火墙的设置
[如遇到防火墙阻挡，见链接](https://docs.microsoft.com/zh-cn/sql/sql-server/install/configure-the-windows-firewall-to-allow-sql-server-access)
* 开始开发
[开发示例](https://www.microsoft.com/en-us/sql-server/developer-get-started/csharp/win/step/2.html)