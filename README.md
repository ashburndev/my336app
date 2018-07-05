# my336app
a new grails 3.3.6 web application

Today (July 5, 2018) I downloaded grails-3.3.6.zip ... and unzipped it and put the bin directory in my path, and created a new Grails application using the command

grails create-app my336app

	ashburndave@dphnuc4:~/g2projects/my336app$ tree
	.
	├── build
	│   ├── classes
	│   │   └── main
	│   │       ├── META-INF
	│   │       └── my336app
	│   │           ├── Application.class
	│   │           ├── ApplicationLoader.class
	│   │           ├── BootStrap.class
	│   │           ├── BootStrap$_closure1.class
	│   │           ├── BootStrap$_closure2.class
	│   │           ├── UrlMappings.class
	│   │           ├── UrlMappings$__clinit__closure1.class
	│   │           ├── UrlMappings$__clinit__closure1$_closure2.class
	│   │           └── UrlMappings$__clinit__closure1$_closure2$_closure3.class
	│   ├── resources
	│   │   └── main
	│   │       ├── layouts
	│   │       ├── META-INF
	│   │       │   └── grails.build.info
	│   │       └── spring
	│   ├── springloaded
	│   ├── stacktrace.log
	│   └── tmp
	│       └── compileGroovy
	│           └── groovy-java-stubs
	├── build.gradle
	├── gradle
	│   └── wrapper
	│       ├── gradle-wrapper.jar
	│       └── gradle-wrapper.properties
	├── gradle.properties
	├── gradlew
	├── gradlew.bat
	├── grails-app
	│   ├── assets
	│   │   ├── images
	│   │   │   ├── apple-touch-icon.png
	│   │   │   ├── apple-touch-icon-retina.png
	│   │   │   ├── favicon.ico
	│   │   │   ├── grails-cupsonly-logo-white.svg
	│   │   │   ├── grails.svg
	│   │   │   ├── skin
	│   │   │   │   ├── database_add.png
	│   │   │   │   ├── database_delete.png
	│   │   │   │   ├── database_edit.png
	│   │   │   │   ├── database_save.png
	│   │   │   │   ├── database_table.png
	│   │   │   │   ├── exclamation.png
	│   │   │   │   ├── house.png
	│   │   │   │   ├── information.png
	│   │   │   │   ├── shadow.jpg
	│   │   │   │   ├── sorted_asc.gif
	│   │   │   │   └── sorted_desc.gif
	│   │   │   └── spinner.gif
	│   │   ├── javascripts
	│   │   │   ├── application.js
	│   │   │   ├── bootstrap.js
	│   │   │   └── jquery-2.2.0.min.js
	│   │   └── stylesheets
	│   │       ├── application.css
	│   │       ├── bootstrap.css
	│   │       ├── errors.css
	│   │       ├── grails.css
	│   │       ├── main.css
	│   │       └── mobile.css
	│   ├── conf
	│   │   ├── application.yml
	│   │   ├── logback.groovy
	│   │   └── spring
	│   │       └── resources.groovy
	│   ├── controllers
	│   │   └── my336app
	│   │       └── UrlMappings.groovy
	│   ├── domain
	│   ├── i18n
	│   │   ├── messages_cs.properties
	│   │   ├── messages_da.properties
	│   │   ├── messages_de.properties
	│   │   ├── messages_es.properties
	│   │   ├── messages_fr.properties
	│   │   ├── messages_it.properties
	│   │   ├── messages_ja.properties
	│   │   ├── messages_nb.properties
	│   │   ├── messages_nl.properties
	│   │   ├── messages_pl.properties
	│   │   ├── messages.properties
	│   │   ├── messages_pt_BR.properties
	│   │   ├── messages_pt_PT.properties
	│   │   ├── messages_ru.properties
	│   │   ├── messages_sk.properties
	│   │   ├── messages_sv.properties
	│   │   ├── messages_th.properties
	│   │   └── messages_zh_CN.properties
	│   ├── init
	│   │   └── my336app
	│   │       ├── Application.groovy
	│   │       └── BootStrap.groovy
	│   ├── services
	│   ├── taglib
	│   ├── utils
	│   └── views
	│       ├── error.gsp
	│       ├── index.gsp
	│       ├── layouts
	│       │   └── main.gsp
	│       └── notFound.gsp
	├── grailsw
	├── grailsw.bat
	├── grails-wrapper.jar
	└── src
	    ├── integration-test
	    │   ├── groovy
	    │   └── resources
	    │       └── GebConfig.groovy
	    ├── main
	    │   ├── groovy
	    │   └── webapp
	    └── test
	        └── groovy

	44 directories, 75 files
	ashburndave@dphnuc4:~/g2projects/my336app$ 

