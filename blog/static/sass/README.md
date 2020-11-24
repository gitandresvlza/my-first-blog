# SASS Sources

The files in `src` are compiled to `/web/css/compiled` as defined in `/pom.xml`.

If you're using IntelliJ/Webstorm or another major IDE with Tomcat support, read the `Important`-Part in the main readme regarding IntelliJ/Webstorm to integrate the compilation in the IDEs build process.

You can also run `mvn sass:compile` or `mvn sass:watch` manually instead. Normal maven commands (such as `mvn package`) will run just fine and compile automatically.