# SWAGGER DOCUMENTATION GENERATOR

## Prerequisites

1. Java JDK 1.8 or later.
2. Apache Maven 3.0.5 or later.

## How to install

Clone this repo using "git clone https://github.com/JKAUSHALYA/swaggerdocumentgenerator.git"

## How to run the tool

1. If there are any custom templates to be used, add them to the templates folder.
2. Copy the swagger yaml file into the swagger-yaml folder.
3. Open the pom file using a text editor and update the property <swagger.yaml.file.name></swagger.yaml.file.name> with
 correct swagger file name.
4. Open a terminal and run "mvn clean install post-site" command.
5. If all success, there will be a message displaying "BUILD SUCCESS".
6. Generated documentation site will be available as "doc.zip" inside doc folder.