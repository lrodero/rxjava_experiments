Experiments with [RxJava (2.0) library](https://github.com/ReactiveX/RxJava)

This project is set using maven. Basic configuration is defined at `root/pom.xml` (it is advised not to change that file), which includes dependencies to `Junit` and `log4j2`. The configuration for the later is `src/main/resources/log4j2.xml`. All configuration specific for this project is set at `pom.xmlp`, _e.g._ the dependency to RxJava2 is set there.

To execute main class (example):
```bash
$ mvn exec:java -Dexec.mainClass="org.lrodero.Experiment"
```

To run code style checker (results are in `target/site/checkstyle.html`):
```bash
$ mvn checkstyle:checkstyle
```

