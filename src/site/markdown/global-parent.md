## Global Parent

Global parent for Maven artifact hierarchy. Defines fixed versions of Maven plugins to be used and certain general Maven settings.

[![Maven Central](https://img.shields.io/maven-central/v/io.wcm.maven/io.wcm.maven.global-parent)](https://repo1.maven.org/maven2/io/wcm/maven/io.wcm.maven.global-parent/)


### Overview

The settings in this global parent POM cover:

* Set output encoding to UTF-8
* Set default compiler settings
* Include [Global Build Tools](global-build-tools.html) with configurations for static code analysis
* Configure maven plugins for Checkstyle, Spotbugs, PMD and JaCoCo for static code analysis
* Configure maven-eclipse plugin with standard Eclipse project settings (usable in classic Eclipse and m2e Eclipse projects)
* Set build timestamps
* Define default versions of common used maven plugins
* Define default exclusions for m2e lifecycle


### GitHub Repository

Sources: https://github.com/wcm-io/io.wcm.maven.global-parent
