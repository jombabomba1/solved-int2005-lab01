Download Link: https://assignmentchef.com/product/solved-int2005-lab01
<br>
<strong> MySQL Server and MySQL Workbench  Installation and Configuration </strong>

<h1>DB Architecture</h1>

<table width="642">

 <tbody>

  <tr>

   <td width="321"><strong>  Client  Side</strong></td>

   <td width="321"><strong>Server Side</strong></td>

  </tr>

  <tr>

   <td width="321"> </td>

   <td width="321"><strong>Localhost: 127.0.0.1</strong></td>

  </tr>

  <tr>

   <td width="321"><strong>  MySQL Workbench   </strong></td>

   <td width="321"><strong>MySQL Server 8.0.12</strong></td>

  </tr>

 </tbody>

</table>







<h1>Task 1: MySQL Community Server Installation and Configuration</h1>

Download: <a href="https://dev.mysql.com/downloads/mysql/">https://dev.mysql.com/downloads/mysql/</a>

Documentation: <a href="https://dev.mysql.com/doc/refman/8.0/en/">https://dev.mysql.com/doc/refman/8.0/en/</a>




<table width="460">

 <tbody>

  <tr>

   <td width="460"></td>

  </tr>

  <tr>

   <td width="460"><strong>– Use Legacy Password Encryption</strong></td>

  </tr>

  <tr>

   <td width="460"></td>

  </tr>

  <tr>

   <td width="460"><strong>– You can create your own password of the Root user and please REMEMBER your password.</strong></td>

  </tr>

 </tbody>

</table>

<h1>Basic MySQL Command Summary</h1>

– Open the Terminal/Command Prompt and run the following commands:

<ul>

 <li>mysql -u root -p – h localhost</li>

 <li>show databases ;</li>

 <li>use [database_name] ;</li>

 <li>show tables ;</li>

 <li>describe [table_name] ;</li>

 <li>select * from mysql.user G</li>

 <li>show grants for ‘root’@’localhost’ ;</li>

 <li>exit</li>

</ul>




<h1>Task 2: MySQL Workbench Installation and Configuration</h1>

<u>Task 2.1</u>: Installing

<ul>

 <li>Download: <a href="https://dev.mysql.com/downloads/workbench/">https://dev.mysql.com/downloads/workbench/</a></li>

 <li>Source: <a href="https://dev.mysql.com/doc/workbench/en/wb-installing.html">https://dev.mysql.com/doc/workbench/en/wb-installing.html</a></li>

</ul>

<table width="456">

 <tbody>

  <tr>

   <td width="456"></td>

  </tr>

  <tr>

   <td width="456"><strong>– Three Modules</strong></td>

  </tr>

  <tr>

   <td width="456"><strong>SQL Development</strong><strong>Data Modelling</strong><strong>Migration Wizard</strong></td>

  </tr>

 </tbody>

</table>

<u>Task 2.2</u>: Creating A New MySQL Connection

Tutorial: <a href="https://dev.mysql.com/doc/workbench/en/wb-getting-started-tutorial-create-connection.html">https://dev.mysql.com/doc/workbench/en/wb-getting-started-tutorial-create</a><a href="https://dev.mysql.com/doc/workbench/en/wb-getting-started-tutorial-create-connection.html">connection.html</a>

<h1>Task 3: Creating a new database named “classicmodels”</h1>

Source: <a href="https://www.mysqltutorial.org/mysql-sample-database.aspx">https://www.mysqltutorial.org/mysql-sample-database.aspx</a>

The classicmodels database is a retailer of scale models of classic cars database. It contains typical business data such as customers, products, sales orders, sales order line items, etc.

<ul>

 <li>Download and run a script named “mysqlsampledatabase.sql” from MS teams/LEB2</li>

 <li>Try to type SQL statement to retrieve data from the Classicmodels database.</li>

</ul>