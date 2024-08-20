
# Web Banking App

**Description:** Develop a console application that allows users to manage a collection of songs, albums and artists. 
The application includes classes for representing songs, albums, artists and genres, and interfaces for playing and managing the collection. A user can add, delete, and play songs, as well as view information about songs, albums, and artists.

## Functionality
The project includes abilities such as:

- User Creation
- View user by id
- View all users
- Account opening
- Account deletion
- Account crediting
- Account debit
- Transferring money between accounts

## Rules of Use

- The user must have a unique login
- You cannot open an account for a non-existing user
- You cannot debit more money from the account than there is in the account
- If a user has one account, you cannot close it

## Technologies

The project utilizes the following technologies and tools:

- **Java**.
- **Spring Framework**:
  - Spring Boot
  - Spring Data JPA
  - Spring Web
- **Docker** - application containerization.
- **PostgreSQL** - relational database.
- **Maven** - dependency management and project assembly.
- **Design Patterns** - using design patterns to improve architecture.
- **S.O.L.I.D.** - applying SOLID principles to create flexible and extensible code.

### Installation and Startup

- Installed Docker.
- Installed JDK (Java Development Kit).
- Installed Maven.

#### Installation Steps

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/banking-app.git
   cd banking-app
2. Build and run the project using Maven:
   ```bash
   mvn clean install
   mvn spring-boot:run
3. Run docker-compose.yml:
   ```bash
   docker-compose up -d
