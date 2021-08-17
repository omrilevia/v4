---
date: '2'
title: 'UML Parser'
cover: './test5.png'
github: 'https://github.com/bchiang7/spotify-profile'
external: 'https://spotify-profile.herokuapp.com/'
tech:
  - Java
  - Javaparser
  - yUML API

showInProjects: true
---

UMLparser reads Java code and transforms it into a UML diagram. It uses a library called Javaparser to extract compilation units and traverse the abstract syntax trees of the Java source using visitor patterns. Metadata of the Java code is stored in JSON objects, and from the metadata a yUML string is generated. The string is sent to yUML via their API and an image is generated.
