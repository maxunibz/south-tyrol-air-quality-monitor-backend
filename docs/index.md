# South Tyrol Air Quality Monitor Backend - Documentation

The South Tyrol Air Quality Monitor is a graphical HTML/JS frontend which displays air quality data provided by the province of South Tyrol through a [pulic web service](http://daten.buergernetz.bz.it/it/dataset/situazione-dell-aria).

## <a name="1"></a> Dependencies

+ [Spark](http://sparkjava.com/) - A micro framework for creating web applications with REST capability
+ [Quartz](http://www.quartz-scheduler.org/) - An open source job scheduling library
+ [MySQL](https://www.mysql.com/) - One of the world's most popular open source database
+ [Tomcat](http://tomcat.apache.org/) - An open source implementation of the Java Servlet, JavaServer Pages, Java Expression Language and Java WebSocket technologies


## <a name="2"></a> Structure of the Development Environment

+ `/builds` - contains the development and production builds of the application
+ `/docs` - contains the documentation
+ `/node_modules` - contains all the dependencies of the project and the build tool
+ `/src` - contains the source code of the application
+ .gitignore - contains all files which should be ignored by the version management system
+ gulpfile.js - contains all build steps
+ package.json - contains the definition of this project with descriptive metadata as well as a list of all it's dependencies

## <a name="3"></a> The Source Code Folder

The source code folder is structured as follows:

+ `/img` - contains image assets
+ `/js` - contains all JS assets
+ `/less` - contains all Less stylesheets (Bootstrap-based and custom ones)
+ `index.html` - The "one page" of our one page appli
