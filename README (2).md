# Dependency Injection in Spring Using Java-Based Configuration

## 🎯 Objective
Demonstrate how Spring performs Dependency Injection (DI) using Java-based configuration instead of XML.

## 📂 Project Structure
```
SpringDIJavaConfig/
├── src/com/example/springdi/
│   ├── Course.java
│   ├── Student.java
│   ├── AppConfig.java
│   └── MainApp.java
└── pom.xml
```

## ⚙️ How to Run
1. Open the project in Eclipse/IntelliJ or any IDE supporting Maven.
2. Run the following command in the terminal:
   ```
   mvn compile exec:java -Dexec.mainClass="com.example.springdi.MainApp"
   ```
3. Output:
   ```
   Student Name: John Doe
   Enrolled Course: Computer Science
   ```

## 🧠 Concepts Demonstrated
- Spring Dependency Injection (DI)
- `@Configuration` and `@Bean` annotations
- Java-based Spring configuration (no XML)
