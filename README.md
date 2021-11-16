## Making a CI pipeline using GitHub Actions

# Install Git

$ sudo apt update

$ sudo apt install git

$ git --version

# Install Apache Maven

$ sudo apt install default-jdk

$ sudo apt install maven

# Create a Maven project

$ mvn archetype:generate -DgroupId=ie.cohogain.Tutorial -DartifactId=HelloWorld -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

# Update pom file


# Initiate Git repository

$ git config --global user.email "you@example.com"

$ git config --global user.name "Your Name"

$ git init

$ git status

$ git add .

$ git commit -m "First commit"

$ git remote add origin https://github.com/cohogainLYIT/CI_tutorial.git

$ git push -u origin master

