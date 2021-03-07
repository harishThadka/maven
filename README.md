# maven
About maven

### What is maven?
Maven is Project Management tool
Used for build management and dependencies
### why maven?
#### Problem:
When building your Java Project, you may need additional JAR files e.g. Spring, Hibernate, Commons Logging, JSON etc
One approach is to download JAR files from each project web site
Manually add the JAR files to your build path/classpath
This is cumbersome manual approach to download JAR from each project site and then copy
#### Solution:
Tell Maven the dependencies (the projects you are working with) e.g. Spring, Hibernate
Maven will go out and download the JAR files for those projects for you 
Maven will make those JAR files available during compile/run time
Maven is like a helping friend
Project Config file (list of dependencies i.e. shopping list :))
