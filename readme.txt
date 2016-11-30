1] run the program from command line: mvn exec:java
2] uses logback.xml to get custom formatted logging
13:47.38.528 logging[com.subra.App.main()] INFO  c.s.App - Infolevel Hello World!
13:47.38.530 logging[com.subra.App.main()] DEBUG c.s.App - Debuglevel Hello World!
3] no need logback.xml. The default provided has all of the above logging elements. Needed maven dependency
of logback-classic with slf4j-api.
4] springboot project spring-boot-starter-data-jpa dependency brings springboot-starter-logging. And this brings slf4j-api and logback-classic dependency.
5] git command line: https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/