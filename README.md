# mvn-commands

A little list about some Maven commands:

## deploy

    $ mvn clean source:jar javadoc:jar deploy
    
## release

    $ mvn release:prepare release:perform

## build eclipse project

    $ mvn eclipse:eclipse
    
## build eclipse workspace

    $ mvn eclipse:configure-workspace
