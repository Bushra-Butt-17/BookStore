

---

# 📚 Bookstore Spring Boot Application

This is a simple **Bookstore** web application built using **Spring Boot**. It allows users to **view**, **add**, **update**, and **delete** books in an online store.

## 🗂️ Project Structure

The directory structure of this project is as follows:

```
- .idea/                # IDE specific files
- .mvn/                 # Maven wrapper files
- src/                  # Source code files
    - main/
        - java/          # Java source files
        - resources/     # Resources (application.properties, static files, etc.)
    - test/              # Test source files
- target/               # Compiled bytecode and JAR file
- .gitignore            # Git ignore file
- mvnw                  # Maven wrapper for Linux/Unix systems
- mvnw.cmd              # Maven wrapper for Windows systems
- pom.xml               # Maven project configuration file
```

## 📝 Requirements

- **Java 11 or later** ☕
- **Maven 3.6.3 or later** ⚙️
- **Spring Boot 2.x or later** 🚀

## 🔧 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Bushra-Butt-17/bookstore-spring-boot.git
   cd bookstore-spring-boot
   ```

2. **Build the project**:
   Using **Maven Wrapper** (recommended):
   ```bash
   ./mvnw clean install   # For Linux/Unix
   mvnw.cmd clean install  # For Windows
   ```

   Alternatively, you can use **Maven** directly if it’s installed:
   ```bash
   mvn clean install
   ```

3. **Run the application**:
   Once the build is successful, you can run the application with:
   ```bash
   ./mvnw spring-boot:run   # For Linux/Unix
   mvnw.cmd spring-boot:run  # For Windows
   ```

   The application will start on `http://localhost:8080` 🌐.

## 🔑 Endpoints

- `GET /books` 📚: Get the list of all books
- `POST /books` ➕: Add a new book
- `PUT /books/{id}` ✏️: Update a book's details
- `DELETE /books/{id}` ❌: Delete a book from the store

## ⚙️ Configuration

The project uses **default Spring Boot properties**. You can customize the configuration by editing the `src/main/resources/application.properties` file.

## 🧪 Testing

You can write **unit** and **integration tests** under the `src/test/java` directory. 

To run the tests, use the following command:

```bash
./mvnw test   # For Linux/Unix
mvnw.cmd test  # For Windows
```

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---
