# into-the-hive-ship
A simple tabletop game, thought up during the COVID-19 confinement period, created to entertain younger players and offer a toolbox so that players can create their own levels.

The rules can be downloaded [here](https://into-the-hive-ship.github.io/).

## Project tools
AsciiDoctor : Used to write the rules;
Maven : Used to generate the PDF rule files.

## Generate the rules

``mvnw clean install org.asciidoctor:asciidoctor-maven-plugin:process-asciidoc``

Once generated, the rules can be found here :

``./target/generated-docs``