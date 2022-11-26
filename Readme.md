# first step to install sdk 

curl -s "https://get.sdkman.io" | bash

sdk install java 22.3.r19-grl


# maven install steps

export M2_HOME="/Users/hmadhukar/Documents/maven/apache-maven-3.8.6"
PATH="${M2_HOME}/bin:${PATH}"
export PATH

/Users/hmadhukar/Documents/maven/apache-maven-3.8.6

# run aot using maven
mvn -DskipTests -Pnative clean package 
