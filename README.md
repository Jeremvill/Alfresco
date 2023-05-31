# Alfresco
Alfresco_project
Alfresco project with documentation by Jerem

## Docs 

### Download
- First download Alfresco community edition : https://www.alfresco.com/fr/thank-you/thank-you-downloading-alfresco-community-edition
- Second download Apache Tomacat server (https://tomcat.apache.org/ , Get a stable version) and Mysql (https://www.mysql.com/en/downloads/ , get stable version)  or Postgresql (https://www.postgresql.org/download/) or Mariadb (https://mariadb.com/en/downloads/) 
- And download OpenJDK 17 or more, I recommend JDK 19 (https://openjdk.org/)  and ActiveMQ , an extension of apache  (https://activemq.apache.org/components/classic/download/)
- And LibreOffice (https://fr.libreoffice.org/download/telecharger-libreoffice/) and ImageMagick (https://imagemagick.org/script/download.php)

### Start / run 
- Folow this instructions : 
1.Download the distribution zip file by accessing the Alfresco Community Edition download page.
2.Generate certificates for mutual TLS.
3.Download Tomcat and review the installation steps required.
4.Set up Tomcat.
5.Install and configure Community Edition.
6.Install any Alfresco Module Packages (AMPs) such as Alfresco Share, Google Docs Integration, and Alfresco Office Services.
7.Set up ActiveMQ.
8.Install third-party software used by Community Edition. This includes LibreOffice, ImageMagick, and Alfresco PDF Renderer.

### Restart for init 
- Review and test your setup to check that all the installation steps are complete:
1.Start and configure your database.
2.Start and configure ActiveMQ.
3.Start the repository.

### Prepare Db
- Create a folder in local and create a database 
- If you use postgre do this command : 
'''
create database alfresco encoding 'utf8';
create role alfresco LOGIN password 'alfresco';
grant all on database alfresco to alfresco;
'''

And you have download alfresco
