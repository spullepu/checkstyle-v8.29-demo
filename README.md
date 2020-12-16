1. "mvn install" from root folder builds and compiled fine 

2. mvn checkstyle:checkstyle from CreateYourOwnCheckStyleCheck\TestProject> fails with an error shown below. 

```
[INFO] ------------------------------------------------------------------------
[ERROR] Failed to execute goal org.apache.maven.plugins:maven-checkstyle-plugin:3.1.1:checkstyle (default-cli) on project TestProject: An error has occurred in Checkstyle report generation.: Failed during c
heckstyle configuration: cannot initialize module TreeWalker - cannot initialize module com.blundell.checks.AntiHungarian - Unable to instantiate 'com.blundell.checks.AntiHungarian' class, it is also not po
ssible to instantiate it as null. Please recheck that class name is specified as canonical name or read how to configure short name usage https://checkstyle.org/config.html#Packages. Please also recheck tha
t provided ClassLoader to Checker is configured correctly. -> [Help 1]
```

