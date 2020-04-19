# into-the-hive-ship
A simple tabletop game, thought up during the COVID-19 confinement period, created to entertain younger players and offer a toolbox so that players can create their own levels.

The rules can be downloaded [here](https://into-the-hive-ship.github.io/).

## Project tools
* AsciiDoctor : Used to write the rules. "adoc" files can be edited with any text editor. Formatting follows [these rules](https://asciidoctor.org/docs/asciidoc-syntax-quick-reference/);
* Maven : Used to generate the PDF rule files;
* [Inkscape](https://inkscape.org/) : Used to design tile grids.

## Generate the rules

``mvnw clean install org.asciidoctor:asciidoctor-maven-plugin:process-asciidoc``

Once generated, the rules can be found here :

``./target/generated-docs``