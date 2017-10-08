# 8R-Basic-Archetype

## What is it?

An basic Maven Archetype for standalone application or libraries.

## Using Basic Archetype

## Use example:

```
cd /path/to/your/workspace

mvn archetype:generate \
-DgroupId=com.example \
-DartifactId=my-artifact \
-Dversion=0.0.1-SNAPSHOT \
-DarchetypeGroupId=com.infinityrefactoring \
-DarchetypeArtifactId=8R-basic-archetype \
-DarchetypeVersion=1.0 \
-DinteractiveMode=false
```
*Note*:

* Replace `com.example` and `my-artifact` by something more appropriate for your project. The value of the attribute `-Dversion` is the version of your project.
* You too can use it directly in the Eclipse IDE. Create a new maven project and select the archetype: 8R-basic-archetype

## Licensing

**8R-Basic-Archetype** is provided and distributed under the [Apache Software License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

Refer to *LICENSE* for more information.
