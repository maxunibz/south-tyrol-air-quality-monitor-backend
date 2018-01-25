# South Tyrol Air Quality Monitor Backend - Documentation

The South Tyrol Air Quality Monitor is a graphical HTML/JS frontend which displays air quality data provided by the province of South Tyrol through a [pulic web service](http://daten.buergernetz.bz.it/it/dataset/situazione-dell-aria).

## <a name="1"></a> Dependencies

+ [Spark](http://sparkjava.com/) - A micro framework for creating web applications with REST capability
+ [Quartz](http://www.quartz-scheduler.org/) - An open source job scheduling library
+ [MySQL](https://www.mysql.com/) - One of the world's most popular open source database
+ [Tomcat](http://tomcat.apache.org/) - An open source implementation of the Java Servlet, JavaServer Pages, Java Expression Language and Java WebSocket technologies


## <a name="2"></a> Structure of the Backend Server Environment

+ `/ims.unibz.cron` - contains the scheduler classes for the automatic update of the database
+ `/ims.unibz.db` - contains the database classes (CRUD) and the the two main objects of the project (Stations and Substance)
+ `/ims.unibz.ini` - contains all the external configuraton files of the project
+ `/ims.unibz.json` - contains the JSON classes for the JSON management of data exchange
+ `/ims.unibz.rest` - contains the classes for the REST server part
+ `/web` - contains the source code of the admin page application


