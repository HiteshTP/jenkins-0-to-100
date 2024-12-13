# jenkins-0-to-100


**For creaditional binding**
go to the manage jenkins
go to credentials in that select the global > click Add Credentials >
inside the Add Credential > select kind as username with password > in username give the docker username > in password give the docker password or give the token (for this go to the docker > account settings > personal access token > click generate token > give the name in access token description and give the access permission (R,W,D)) > click generate > copy the token > go to the jenkins in the password session past the token > give the id (docker) > give the description > click create


**NOTE Importent**
Using Maven for Other Languages or Projects:

While Maven is designed for Java, you can adapt it for other languages, but this requires creating a valid pom.xml that aligns with the build and test requirements of the non-Java project.
However, most non-Java projects (e.g., Python, JavaScript, Go) have their own ecosystem-specific build tools:
Python: pytest, tox, setuptools
JavaScript: npm, yarn, webpack
Go: go build, go test
If a Project Lacks pom.xml:

Without a pom.xml, Maven commands like mvn compile or mvn test cannot be executed, as Maven needs the file to understand the project's dependencies and configuration.
