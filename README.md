Quarkus showcase archetype
====
This project contains an archetype for quarkus showcases.

Create a new service
----
```shell
mvn archetype:generate                            \
-DarchetypeGroupId=dev.unexist.showcase           \
-DarchetypeArtifactId=quarkus-showcase-archetype  \
-DarchetypeVersion=0.1                            \ <1>
-DgroupId=<my-groupId>                            \ <2>
-DartifactId=<my-artifactId>                      \ <3>
-Dname=<my-name> # <4>
```

<1> This is the version of the archetype, normally 0.1 should be fine for a starter. \
<2> The groupId sets the groupId of the new service and normally should be *dev.unexist.showcase*. \
<3> And this is the artifactId of the new service.  \
<4> Lastly, this is the name of the new service.