# Grails Plugin Trix Editor

## Installation

Add a dependency in your build.gradle

```
repositories {
    jcenter() 
}

dependencies {
    .
    ..
    ...
    compile 'org.grails.plugins:grails-trix-editor:1.3'
    ...
    ..
    .
}
```

## Usage

In your GSP files:

```
<!DOCTYPE html>
<html>
    <head>
    ..
    .
    .
        <asset:stylesheet src="trix/trix.css"/>
    </head>
    <body>

…
.
      <trix:editor name="about" value="${book?.about}"/>
.
..
        <asset:javascript src="trix/trix.js"/>
    </body>
</html>
```
