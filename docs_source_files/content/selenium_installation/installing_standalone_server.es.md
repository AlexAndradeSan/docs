---
title: "Instalación del servidor independiente (_standalone_)"
weight: 3
---

 
Si planea usar [Grid]({{< ref "/grid/_index.md">}}) entonces debe descargar el archivo JAR [selenium-server-standalone](//www.seleniumhq.org/download/). El jar _selenium-server-standalone_ nunca se carga al proyecto, pero todos los componentes están disponibles a través de [selenium-server](//repo1.maven.org/maven2/org/seleniumhq/selenium/selenium-server/). El JAR independiente contiene todo, incluido el servidor remoto de Selenium y las librerías del lado del cliente. Esto significa que si utiliza el jar de selenium-server-standalone en su proyecto, entonces no tiene que agregar selenium-java o un jar específico del navegador.

 ```xml
<dependency>
  <groupId>org.seleniumhq.selenium</groupId>
  <artifactId>selenium-server</artifactId>
  <version>3.X</version>
</dependency>
```

