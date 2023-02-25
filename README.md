From the top-level directory of your project, execute:

`mvn -P all clean install`

The switch -P all is used here in order to build with all extensions available, with paths and settings configured for the embedded mode.

When building for production, instead, it is recommended to check the Customization chapter of the Apache Syncope Reference Guide.

then, from the enduser subdirectory, execute:

`mvn -P embedded,all`