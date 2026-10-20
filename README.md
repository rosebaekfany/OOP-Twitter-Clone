# Twitter Clone — Object-Oriented Programming Project

A Twitter-style social network desktop app built in **Java** with **JavaFX** and **MySQL**, developed for the Object-Oriented Programming course with Yekta Esmaeil Kashi.

## Features

- Sign up, log in and password recovery
- **Personal** and **business** accounts, with regular and business posts
- Comments and reactions (like, heart, laugh, cry)
- Following, user search, a personal page and follow recommendations (friends of friends)
- One-to-one chats and group chats
- Settings page
- Data stored in a MySQL database

## Project structure

```
src/main/java/com/yrtwitter/project_phase2/
├── Main.java          # entry point
├── media/             # model: users, posts, comments, chats, groups
├── controller/        # database access, editing, messaging, recommendations
├── view/              # console input/output
├── gui/               # JavaFX screens (login, sign-up, home, chat, search, settings…)
└── temporary/         # reactions and media types
src/main/resources/    # FXML layouts
```

## Running

Requirements: JDK 18+, Maven (or the included wrapper) and a local MySQL server with a `myTwitter` database.

```bash
./mvnw clean javafx:run
```

Update the database user and password in `controller/DatabaseUpdate.java` to match your local MySQL setup.

## Tools

Java · JavaFX 18 · Maven · MySQL
