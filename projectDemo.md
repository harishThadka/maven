# Create a New Maven Project in Eclipse

1. Open your eclipse and Go to File > New > Others.
![image](./images/img1.PNG)
2. Select Maven > Maven Project and click on Next.
![image](./images/img2.PNG)
3. Choose your workspace where you would like to set up your Maven project and click on Next.
![image](./images/img3.PNG)
4. Search the archetype in filter, for now just select the 'maven-archetype-quickstart' and click on Next.(Make sure you should have internet connection as it is going to retrieve maven projects)
![image](./images/img4.PNG)
5. Specify the Group Id & Artifact Id and click on Finish.
    - GroupId- a package of a new project.
    - ArtifactId- a name of your project.
    - Version- a version of a new project. By default, this field is specified automatically.
![image](./images/img5.PNG)
6.  Go to the project location to see the newly created maven project with below following directory structure
![image](./images/img6.PNG)
7. Now open the pom.xml file, which resides in the project folder. By default the POM is generated like this:
![image](./images/img7.PNG)
8. Succesfully created a demo maven project