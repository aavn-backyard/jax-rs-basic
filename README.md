# jax-rs-basic

A Maven archetype to create a basic JAX-RS application on Wildfly 10.

# Usage

If this archetype is not installed on your Maven repository, please check it out then run:

```
mvn install
mvn archetype:crawl # force Maven to update local archetypeCatalog
```


After that, simply generate using Maven interactive mode:

```bash
mvn archetype:generate -Dfilter=com.axonivy:jax-rs-basic
```
