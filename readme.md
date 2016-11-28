**Run**

java -Dfile.encoding=UTF-8 -cp lib/Ab.jar Main bot=test action=chat trace=false

**Program arguments**

bot=test action=chat trace=false

**manual add lib**

mvn install:install-file -Dfile=lib/sanmoku-0.0.5.jar -DgroupId=net.reduls.sanmoku -DartifactId=sanmoku -Dversion=0.0.5 -Dpackaging=jar

mvn install:install-file -Dfile=lib/sanmoku-feature-ex-0.0.1.jar -DgroupId=net.reduls.sanmoku -DartifactId=sanmoku-feature-ex -Dversion=0.0.1 -Dpackaging=jar
