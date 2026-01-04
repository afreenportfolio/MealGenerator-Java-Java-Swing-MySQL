# MealGenerator Java Application

![Type](https://img.shields.io/badge/Type-Personal_Project-blue) 
![Status](https://img.shields.io/badge/Status-Archived-grey)

> **Warning**: **This project is currently non-runnable due to known bugs in database connectivity and GUI logic.**  
> **This repository serves as a documentation showcase** of system design, MySQL integration, and Java Swing UI planning.

MealGenerator is a Java-based tool that suggests meals tailored to dietary needs, calories, regions, and ingredients. It integrates a MySQL database to retrieve and filter meal data dynamically, making it ideal for health-conscious users or meal planning.

## Features
1. Dynamic meal suggestions based on user inputs like calories, nutrition, and diet.
2. Normalized database schemas for efficient data management.
3. Unit tests and input validation for reliability.
4. Graphical user interface for easy interaction.

## Technologies Used
1. Language: Java
2. Database: MySQL
3. Tools: VS Code, Java Swing for GUI

## Installation
- Clone the repository: `git clone https://github.com/afreenportfolio/meal-generator.git`
- Set up MySQL: Create database and import schema/tables (e.g., Meals, Ingredients).
- Add MySQL Connector/J JAR to your classpath.
- Compile: `javac MealGenerator.java`
- Run: `java MealGenerator`

## Usage
- Run the application: `java Main`
- Input preferences via the GUI.
- View generated meal lists with details.

## License
- MIT License
