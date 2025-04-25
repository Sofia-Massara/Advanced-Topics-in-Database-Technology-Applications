TEAM :
ΚΩΝΣΤΑΝΤΙΝΟΣ ΚΑΡΓΑΣ, 4381
ΣΟΦΙΑ ΜΑΣΣΑΡΑ, 4729
ΟΚΤΑΙ ΜΠΟΖ, 4437

Developed a full-stack application that integrates and visualizes climate and demographic data from multiple sources (Kaggle, IMF) into a unified MySQL database using custom ETL workflows. The system features structured SQL querying, automated data transformation scripts, and an interactive front-end that allows users to select countries, indicators, and time ranges, delivering insights through bar, line, and scatter visualizations.

Design Tools: Java 17, Maven Spring boot 2.6.4, Thymeleaf 3.1.0, eclipse, mySQLWorkbench 8.0CE
Installation: File->Import->Existing Maven Projects
Usage: In cs.uoi.gr.mye030.project.etl -> Run TableInitializationExecutor.java (username password database name and file path may differ) -> And then Run CsvToDBImporter.java

Starting by creating a Maven Spring boot project, the application runs from ProjectApplication.java class and homepage gets loaden from WebMvcConfig.java. 
Data transforming is handled by the classes in the package cs.uoi.gr.mye030.project.etl  and data manipulation by the classes in the packages 
cs.uoi.gr.mye030.project.model , cs.uoi.gr.mye030.project.dao , cs.uoi.gr.mye030.project.service and cs.uoi.gr.mye030.project.serviceImpl .
User Interface is created and handled in src/main/resources/templates , src/main/resources/static and in the package cs.uoi.gr.mye030.project.controller



























