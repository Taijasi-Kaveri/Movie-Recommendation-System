# Movie-Recommendation-System
This is a project that demonstrates how to build a movie recommendation system using Apache Spark, Java, and SQL. The project uses the MovieLens dataset, which contains movie ratings provided by users. The goal of the project is to use Spark's collaborative filtering algorithm to generate movie recommendations for each user and perform additional analysis using SQL.

## Getting Started
To get started with the project, you will need to have Apache Spark, Java, and SQL installed on your machine. You will also need to download the MovieLens dataset and place it in a directory accessible to your Spark installation.

Follow the instructions in the README.md file to set up the project and run it on your machine.

## Project Structure
The project is structured as follows:

css
Copy code
├── data
│   └── ratings.csv
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── MovieRecommendation.java
│   │   │   ├── Rating.java
│   │   │   └── User.java
│   │   └── resources
│   │       └── application.properties
│   └── test
│       └── java
│           └── MovieRecommendationTest.java
├── pom.xml
└── README.md
1. data/ratings.csv - the MovieLens dataset file containing movie ratings provided by users.
2. src/main/java - the directory containing the Java source code for the project.
3. src/main/resources/application.properties - the configuration file for the project.
4. pom.xml - the Maven project configuration file.
5. README.md - the project documentation.

## License
This project is licensed under the MIT License.
