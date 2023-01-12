## AEM Global Parent

Global parent for Maven artifact hierarchy for AEM projects. Defines AEM-specific plugins and general Maven settings.

[![Maven Central](https://img.shields.io/maven-central/v/io.wcm.maven/io.wcm.maven.aem-global-parent)](https://repo1.maven.org/maven2/io/wcm/maven/io.wcm.maven.aem-global-parent/)


### Overview

The settings in this AEM global parent POM cover:

* Dependencies for SCR and OSGi annotations
* Resource includes for src/main/webapp folder
* Default configurations for bundle projects using either maven-bundle-plugin or bnd-maven-plugin
* Default configurations for maven-sling-plugin, content-package-maven-plugin
* Include bnd Plugins for
  [Sling Models](https://sling.apache.org/documentation/bundles/models.html)
  and [Sling Context-Aware Configuration](https://sling.apache.org/documentation/bundles/context-aware-configuration/context-aware-configuration.html).
* Include wcm.io maven plugins [wcmio-content-package-maven-plugin](plugins/wcmio-content-package-maven-plugin/),
  [cq-maven-plugin](plugins/cq-maven-plugin/),
  [i18n-maven-plugin](plugins/i18n-maven-plugin/),
  [nodejs-maven-plugin](plugins/nodejs-maven-plugin/),
  [conga-maven-plugin](https://devops.wcm.io/conga/),
  [conga-aem-maven-plugin](https://devops.wcm.io/conga/plugins/aem/)
* Define default exclusions for m2e lifecycle

### Migration guides

* [Migrate from wcm.io Magen aem-global-parent 1.4.x to 1.5.x](https://wcm-io.atlassian.net/wiki/x/AoBihQ)
* [Migrate from wcm.io Maven aem-global-parent 1.1.x to 1.2.x](https://wcm-io.atlassian.net/wiki/x/7dELAw)
* [Migrate content package projects from wcmio-content-package-maven-plugin to Jackrabbit filevault-package-maven-plugin](https://wcm-io.atlassian.net/wiki/x/GYB1BQ)
* [How to switch from maven-bundle-plugin to bnd-maven-plugin](https://wcm-io.atlassian.net/wiki/x/BICFSw)


### GitHub Repository

Sources: https://github.com/wcm-io/io.wcm.maven.aem-global-parent
