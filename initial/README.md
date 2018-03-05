
#Install dependencies

# SDKMAN http://sdkman.io/
curl -s "https://get.sdkman.io" | bash
source $HOME/.bashrc
sdk install springboot 2.0.0.RELEASE

#Run
spring run app.groovy
