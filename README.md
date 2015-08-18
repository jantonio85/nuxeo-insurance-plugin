# nuxeo-insurance-plugin
Nuxeo Plugin about Car Insurance

## Motivation

There are a lot of common validations across any web application that could be centralized in one plugin to contribute to Nuxeo platform.

## Installation

You just have to compile the pom.xml using Maven and deploy the plugin in 
```{r, engine='bash', count_lines}
cd nuxeo-field-validator-plugin
mvn clean install
cp target/fieldValidator-*.jar $NUXEO_HOME/nxserver/plugins
```
And then, restart your nuxeo server and enjoy.


