
# How to install a new jar

Example for handlebars.java library:

mvn install:install-file -DgroupId=com.github.jknack -DartifactId=handlebars -Dversion=4.1.0-SNAPSHOT -Dfile=/path/to/jar/handlebars-4.1.0-SNAPSHOT.jar -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=.  -DcreateChecksum=true

Add all the files generated to git. You may need to git add -f <your-jar>.jar
