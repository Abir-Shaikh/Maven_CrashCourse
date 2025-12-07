A quick crash-course project to understand Maven basics, including project structure, dependencies, plugins, and build lifecycle.

🚀 What You Learn

What Maven is and why it’s used

Standard Maven project structure

How to add dependencies in pom.xml

Running the Maven build lifecycle (clean, compile, package)

Creating and running a simple Java application with Maven


📁 Project Structure
myapp/
 └── src/
     ├── main/java
     └── test/java
 └── pom.xml


📦 Running the Project

Make sure Maven is installed. Then run:

mvn clean install


Run the app:

mvn exec:java


(Only if exec-maven-plugin is configured.)

🧩 Adding Dependencies

Add dependencies inside your pom.xml:

<dependencies>
    <dependency>
        <groupId>org.example</groupId>
        <artifactId>my-library</artifactId>
        <version>1.0</version>
    </dependency>
</dependencies>

📚 Topics Covered

What is Maven?

pom.xml basics

Maven lifecycle phases

Repositories

Dependency management

Using plugins

👍 Conclusion

This project gives you a simple and fast introduction to Maven so you can use it confidently in real-world Java projects.
