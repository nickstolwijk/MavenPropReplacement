# MavenPropReplacement

Execute `mvn org.codehaus.mojo:build-helper-maven-plugin:regex-property@parseVersion -X`

Output:
```
[DEBUG] Configuring mojo 'org.codehaus.mojo:build-helper-maven-plugin:3.0.0:regex-property' with basic configurator -->
[DEBUG]   (f) failIfNoMatch = true
[DEBUG]   (f) name = parsedVersion
[DEBUG]   (f) project = MavenProject: org.example:PropReplacement:1.0-SNAPSHOT @ C:\work\PropReplacement\pom.xml
[DEBUG]   (f) regex = ^(?<regexVersion2>.*?)(-)(?<regexGroupId>.*?)$
[DEBUG]   (f) replacement = ${regexVersion2}null
[DEBUG]   (f) toLowerCase = false
[DEBUG]   (f) toUpperCase = false
[DEBUG]   (f) value = 1.0-SNAPSHOT-org.example
```
