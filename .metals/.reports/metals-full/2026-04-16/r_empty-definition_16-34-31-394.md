error id: file:///C:/Users/maloc/Desktop/DevOpsTP2/tp-devops-correction-docker/simple-api/src/main/java/fr/takima/training/simpleapi/SimpleApiApplication.java:java/lang/String#
file:///C:/Users/maloc/Desktop/DevOpsTP2/tp-devops-correction-docker/simple-api/src/main/java/fr/takima/training/simpleapi/SimpleApiApplication.java
empty definition using pc, found symbol in pc: java/lang/String#
empty definition using semanticdb
empty definition using fallback
non-local guesses:

offset: 259
uri: file:///C:/Users/maloc/Desktop/DevOpsTP2/tp-devops-correction-docker/simple-api/src/main/java/fr/takima/training/simpleapi/SimpleApiApplication.java
text:
```scala
package fr.takima.training.simpleapi;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;

@SpringBootApplication
public class SimpleApiApplication {

	public static void main(String@@[] args) {
		Ceci est un bug volontaire pour le rollback;
		SpringApplication.run(SimpleApiApplication.class, args);
	}

}

```


#### Short summary: 

empty definition using pc, found symbol in pc: java/lang/String#